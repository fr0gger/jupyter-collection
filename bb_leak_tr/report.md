---
title: App
marimo-version: 0.11.7
width: medium
---

# BlackBasta Chat Logs Leak Analysis
#### Author: Thomas Roccia - @fr0gger_

## Introduction
In this notebook, we will break down the leaked chat logs from the Black Basta ransomware syndicate. The goal is to analyze the internal communications, identify key players, understand operational workflows, and extract valuable insight from the data.

We will start by exploring the dataset to get an overview of its structure—identifying users, message distribution, and general activity patterns. Then, we will use generative AI with a RAG model to interact dynamically with the data, to allow direct analysis of the logs, and retrieve discussions, tools, and tactics used by the group.

My goal is to show you how to analyze this kind of data with practical code that you can understand, adapt, and reapply. In this specific notebook, I didn’t use Jupyter; I used Marimo, and I recommend checking out the [Marimo documentation](https://marimo.io/docs](https://docs.marimo.io/) to understand how to run this notebook locally.




**Disclaimer: This notebook is my personal work to demonstrate how Python and GenAI can be used for analyzing chat logs. It is not affiliated with or supported by my employer.**

## Overview
In the fist part of this notebook, we will explore the dataset, analyze the structure of the leak, identify the number of users, message activity, and key trends.

In the second part, we will build a RAG system to interact dynamically with the data and extract meaningful insights. The RAG will be customizable, allowing you to adapt it to your own needs.

By the end of this notebook, you will have a solid workflow for analyzing this kind of data.

*`<shameless_plug>` If you want to take your skills even further, check out my [training on GenAI for Threat Intel](https://store.securitybreak.io/ctiai) `</shameless_plug>`*

Let's jump into the analysis 👇

## LICENCE

```python {.marimo}
import marimo as mo

# LICENCE
print(open("LICENSE.md").read())
```

## Part 1: Data Analysis
In this first part, we will analyze the structure of the file to understand its content and get an overview.

*Please note that the process of converting the file into a proper JSON format is not included in this notebook. During the conversion, I ignored errors, resulting in a minor data loss of 0.15% of the total dataset. You are free to use any dataset you want, but to run the code, the file must be in a valid JSON format.*

### File Overview

```python {.marimo}
# import lib
import pandas as pd
import numpy as np
from datetime import datetime
import json
import re
from collections import Counter
import altair as alt
```

```python {.marimo}
# File Content
#print("\n".join(open("output.json").readlines()[:50]))
```

```
[

  {

    "chat_id": "!VdvDXHFZwWDpIAtpCj:matrix.bestflowers247.online",

    "message": "BAZA",

    "sender_alias": "@usernamenn:matrix.bestflowers247.online",

    "timestamp": "2023-09-18 13:35:07"

  },

  {

    "chat_id": "!uJZKZVgGmmSiNvobZH:matrix.bestflowers247.online",

    "message": "!!!",

    "sender_alias": "@usernamess:matrix.bestflowers247.online",

    "timestamp": "2023-09-18 13:50:31"

  },

  {

    "chat_id": "!FtoGkSqUPiGjGNKkOl:matrix.bestflowers247.online",

    "message": "cpu 2core 2.4 ghz, 4 gb ram, 100 gb space x2",

    "sender_alias": "@usernameyy:matrix.bestflowers247.online",

    "timestamp": "2023-09-18 17:43:18"

  },

  {

    "chat_id": "!FtoGkSqUPiGjGNKkOl:matrix.bestflowers247.online",

    "message": "``` Login: usernameboy Password: wet4vEtZq!D2sCRFdV!TRXwq3Tx!XC2ZzScX4vZQ Login: username777 Password: FgTTe@fCSSC%qaFBTb43RXFVA1farXq!3Zc35wRT Login: usernamehunter Password: v1vAq24gV!45zB!xt!dxqAg4@ESaa!re4xDtr#v% ``` matrix.bestflowers247.online",

    "sender_alias": "@usernameyy:matrix.bestflowers247.online",

    "timestamp": "2023-09-18 17:44:42"

  },

  {

    "chat_id": "!kJVcUcyUsQhwBCuIPD:matrix.bestflowers247.online",

    "message": "1",

    "sender_alias": "@usernameyy:matrix.bestflowers247.online",

    "timestamp": "2023-09-18 17:47:48"

  },

  {

    "chat_id": "!kJVcUcyUsQhwBCuIPD:matrix.bestflowers247.online",

    "message": "``` Login: usernameboy Password: wet4vEtZq!D2sCRFdV!TRXwq3Tx!XC2ZzScX4vZQ Login: username777 Password: FgTTe@fCSSC%qaFBTb43RXFVA1farXq!3Zc35wRT Login: usernamehunter Password: v1vAq24gV!45zB!xt!dxqAg4@ESaa!re4xDtr#v%",

    "sender_alias": "@usernameyy:matrix.bestflowers247.online",

    "timestamp": "2023-09-18 17:47:56"

  },

  {

    "chat_id": "!kJVcUcyUsQhwBCuIPD:matrix.bestflowers247.online",

    "message": "matrix.bestflowers247.online",

    "sender_alias": "@usernameyy:matrix.bestflowers247.online",

    "timestamp": "2023-09-18 17:48:02"

  },

  {

    "chat_id": "!kJVcUcyUsQhwBCuIPD:matrix.bestflowers247.online",

    "message": "cpu 2core 2.4 ghz, 4 gb ram, 100 gb space x2",

    "sender_alias": "@usernameyy:matrix.bestflowers247.online",

    "timestamp": "2023-09-18 17:48:07"

  },
```

```python {.marimo}
with open('output.json', 'r') as f:
    data = json.load(f)

df = pd.DataFrame(data)
df['timestamp'] = pd.to_datetime(df['timestamp'])

stats = {
    "Total messages": len(df),
    "Unique senders": df['sender_alias'].nunique(),
    "Unique chat rooms": df['chat_id'].nunique(),
    "Date range": f"{df['timestamp'].min()} to {df['timestamp'].max()}"
}

mo.md(f"""
### Dataset Overview
- Total Messages: {stats['Total messages']}
- Unique Users: {stats['Unique senders']}
- Chat Rooms: {stats['Unique chat rooms']}
- Time Period: {stats['Date range']}
""")
```

### Temporal Analysis

In this section, we will analyze activity patterns to understand the operational timing of the Black Basta ransomware group. By examining timestamps in the chat logs, we can identify:

- Peak activity periods – When the group was most active.
- Daily and weekly trends – Whether operations followed a structured schedule.
- Time zones and coordination – Insights into the possible locations of key actors.
- Operational shifts – Changes in activity over time, indicating internal disruptions or strategic adjustments.

```python {.marimo}
def format_chart(chart):
    return chart.configure_axis(
        labelFontSize=14, titleFontSize=16, grid=True, gridColor="lightgray"
    ).configure_legend(
        labelFontSize=14, titleFontSize=16
    ).configure_title(
        fontSize=18, anchor='start'
    ).configure_view(
        strokeWidth=0
    )

hourly_chart = (
    alt.Chart(df)
    .mark_bar(opacity=0.8)
    .encode(
        x=alt.X(
            "hours(timestamp):O",
            title="Hour of Day",
            axis=alt.Axis(format='%H')
        ),
        y=alt.Y(
            "count():Q",
            title="Number of Messages"
        ),
        color=alt.Color(
            "weekday(timestamp):N",
            title="Day of Week",
            scale=alt.Scale(scheme='tableau10')
        ),
        tooltip=[
            alt.Tooltip("hours(timestamp):O", title="Hour"),
            alt.Tooltip("count():Q", title="Messages"),
            alt.Tooltip("weekday(timestamp):N", title="Day")
        ]
    )
    .properties(
        title="Message Activity by Hour",
        width=800,
        height=400
    )
)

chart1 = mo.ui.altair_chart(format_chart(hourly_chart))
chart1
```

```python {.marimo}
df["day"] = df["timestamp"].dt.day_name()
df["hour"] = df["timestamp"].dt.hour

heatmap_data = df.groupby(["day", "hour"]).size().reset_index(name="count")

day_order = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"]

# create the github style heatmap
heatmap = alt.Chart(heatmap_data).mark_rect().encode(
    x=alt.X("hour:O", title="Hour of Day"),
    y=alt.Y("day:N", title="Day of Week", sort=day_order),
    color=alt.Color("count:Q", title="Activity Level", scale=alt.Scale(scheme="greens")),
    tooltip=[
        alt.Tooltip("hour:O", title="Hour"),
        alt.Tooltip("day:N", title="Day"),
        alt.Tooltip("count:Q", title="Messages")
    ]
).properties(
    title="GitHub-Style Activity Heatmap",
    width=800,
    height=400
)

heatmap
```

```python {.marimo}
# monthly activity 
df['month'] = df['timestamp'].dt.to_period('M')

monthly_counts = df.groupby("month").size().reset_index(name="count")
chart = (
    alt.Chart(monthly_counts)
    .mark_bar(size=30)
    .encode(
        x=alt.X("month:T", title="Month", axis=alt.Axis(format="%b %Y", labelAngle=-45)),
        y=alt.Y("count:Q", title="Number of Discussions"),
        color=alt.Color("count:Q", scale=alt.Scale(scheme='blues')),
        tooltip=["month:T", "count:Q"],
    )
    .properties(title="Discussions Over Time", width=900, height=450)
)
mo.ui.altair_chart(chart)
```

```python {.marimo}
# Create User Message Distribution Chart
#user_chart = (
#    alt.Chart(df)
#    .mark_bar()
#    .encode(
#        x=alt.X("count():Q", title="Total Messages"),  # X Total messages
#        y=alt.Y("sender_alias:N", title="Users", sort="-x"),  # Y Users sorted by message count
#        color=alt.Color("sender_alias:N", legend=None, scale=alt.Scale(scheme="tableau10")), 
##        tooltip=[
#          alt.Tooltip("sender_alias:N", title="User"),
#            alt.Tooltip("count():Q", title="Messages"),
#        ],
#    )
#    .properties(
#        title="User Message Distribution",
#        width=800,
#        height=450,
#    )
#)

# chart
#chart2 = mo.ui.altair_chart(format_chart(user_chart))
#chart2
```

```python {.marimo}
# top 10 Users 
top_users = df["sender_alias"].value_counts().nlargest(10).reset_index()
top_users.columns = ["sender_alias", "message_count"]

top_users_chart = (
    alt.Chart(top_users)
    .mark_bar()
    .encode(
        x=alt.X("message_count:Q", title="Message Count"),
        y=alt.Y("sender_alias:N", title="Top 10 Users", sort="-x"),
        color=alt.Color("sender_alias:N", legend=None, scale=alt.Scale(scheme='tableau10')),
        tooltip=["sender_alias", "message_count"]
    )
    .properties(
        title="Top 10 Most Active Users",
        width=800,
        height=450
    )
)

chart3 = mo.ui.altair_chart(format_chart(top_users_chart))
chart3
```

### IOCs Extraction
Here, we are going to extract potential IOCs mentioned in the leak, such as IP addresses, wallet addresses, domain names, hashes...

```python {.marimo}
import ipaddress


def is_valid_ip(ip):
    try:
        ip_obj = ipaddress.ip_address(ip)
        # Filter out common false positives like version numbers
        if ip_obj.is_private or ip_obj.is_loopback or ip_obj.is_link_local:
            return False
        octets = ip.split('.')
        if octets[0] == '0' or all(o == '0' for o in octets):
            return False
        return True
    except ValueError:
        return False

def is_valid_domain(domain):
    # Common executables and dlls that might be mistaken for domains
    executable_patterns = [
        r'.*\.exe$',
        r'.*\.dll$',
        r'.*\.x64\.dll$',
        r'.*\.sys$',
        r'.*svc.*\.exe$'
    ]

    # Check if domain matches any executable pattern
    for pattern in executable_patterns:
        if re.match(pattern, domain.lower()):
            return False

    # Filter common false positives
    invalid_domains = {'com', 'net', 'org', 'gov', 'edu'}
    if domain.lower() in invalid_domains:
        return False
    if len(domain) > 253:  # Max domain length
        return False
    return True

ioc_patterns = {
    "ip": r'\b(?:[0-9]{1,3}\.){3}[0-9]{1,3}\b(?!\.\w)(?!\d+\s*[A-Za-z]+)',
    "domain": r'\b(?:(?![0-9]+\.[0-9]+\.[0-9]+\.[0-9]+)(?:[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])?\.)+(?!exe|dll|sys)(?:[a-zA-Z]{2,}|onion))\b',
    "hash": r'\b(?!0+[a-f0-9]*$)(?![f]{32}$)(?![0]{32}$)[a-fA-F0-9]{32,64}\b',
    "credentials": r'(?i)(?:username|user|login|password|pass)\s*[:=]\s*([^\s,]{8,64})',
    "wallet": r'\b(?:bc1|[13])[a-km-zA-HJ-NP-Z1-9]{25,34}\b',
    "filename": r'\b[a-zA-Z0-9](?:[a-zA-Z0-9._-]*[a-zA-Z0-9])?\.(?:exe|dll|bin|dat|sys|ovpn|zip|rar|tar|gz|7z)\b'
}

def extract_iocs(text):
    iocs = []
    for key, pattern in ioc_patterns.items():
        matches = re.findall(pattern, str(text))
        for match in matches:
            match = match.strip()
            if key == "ip" and not is_valid_ip(match):
                continue
            if key == "domain" and not is_valid_domain(match):
                continue
            if isinstance(match, tuple):
                match = match[0]
            iocs.append({"type": key, "value": match})
    return iocs

# Process DataFrame
ioc_records = df["message"].apply(extract_iocs)
ioc_flat_list = [item for sublist in ioc_records if sublist for item in sublist]
ioc_df = pd.DataFrame(ioc_flat_list)
ioc_df.to_csv("bb_iocs.csv", index=False)
```

### IOCs Browsing

In the below table you can browse the iocs, just click on + Add and select the transform you want to apply.

```python {.marimo}
ioc_csv = pd.read_csv("bb_iocs.csv")

mo.ui.dataframe(ioc_csv, page_size=50)
```

## Part 2: Using Generative AI to Analyze the Leak

The goal here is simple: take the leaked chat data, make it searchable, and use AI to analyze it efficiently. Instead of manually searching through thousands of messages.

To enforce the retrieval I created a RAG Hybrid Search which is an approach that combines Retrieval-Augmented Generation (RAG) with multiple search techniques to improve information retrieval. Instead of relying only on one retrieval method, hybrid search leverages different strategies to improve relevance, accuracy, and efficiency.

In that specific case, I used FAISS for semantic search and BM25 for keyword-based search, and I combine them with an EnsembleRetriever to ensure that retrieved chat logs are both contextually relevant and precise.

With these techniques, we get better information retrieval and more accurate results based on the request, while also reducing the risk of hallucination. Additionally, the retrieved documents are displayed to the user, so you can validate and verify the data yourself. That’s the beauty of having full control over your workflow. 😉

*Note: There are multiple ways to build a retrieval system, and depending on your use case, another method might be more efficient.*
<!---->
### Limitations
Before going further, you need to understand the limitations of this approach and how to mitigate them.

Hybrid search improves retrieval accuracy and reduces hallucination by grounding model responses in real data, but it’s not foolproof. If the retrieval system doesn’t index relevant chat logs properly (which is not the case here), the model might generate incomplete answers. This can also be influenced by the number of documents retrieved, as limiting retrieval too much may exclude critical context.

Additionally, even when provided with accurate data, the model can still misinterpret context or phrase responses incorrectly.

To mitigate these risks, you can apply confidence scoring to rank results based on reliability and ensure human oversight for critical queries. This is why it’s important to display the retrieved data to the user, to let you verify the model answer.

That being said the workflow here should be solid enough to let you conduct your analysis.
<!---->
### Loading the data

The first step her is to load the data, in that case I am using the JSONLoader from LangChain and I am also specifying the metadata which are important for the retrieval.

```python {.marimo}
from langchain_community.retrievers import BM25Retriever
from langchain_core.documents import Document
from langchain_community.document_loaders import JSONLoader
from pathlib import Path
from pprint import pprint

# Extracting the metadata 
def metadata_func(record: dict, metadata: dict) -> dict:
    metadata["chat_id"] = record.get("chat_id")
    metadata["sender_alias"] = record.get("sender_alias")
    metadata["timestamp"] = record.get("timestamp")
    return metadata

loader = JSONLoader(
    file_path="output.json",
    jq_schema=".[]",
    content_key="message",
    metadata_func=metadata_func
)

data2 = loader.load()

# BM25Retriever 
bm25_retriever = BM25Retriever.from_documents(data2)
bm25_retriever.k = 10  # number of  documents to retrieve
```

### Loading your OpenAI API Key

Before to continue and to let you run the rest of the code you need to enter your API key.

```python {.marimo}
# Add your openai key
api_key = mo.ui.text(
    kind="password",
    placeholder="Enter your API key",
    label="API Key",
    full_width=True
)

#api_key
```

```python {.marimo}
#import os
#os.environ["OPENAI_API_KEY"] = api_key.value
```

### Creating the embeddings

I have already created the embeddings and saved the index, so you do not need to redo the process, which can be quite long depending on your resources. The code for creating the embeddings is not available, but you have access to the code for loading the index and the index itself in the bb_index folder.

Note that I am using weights=[0.5, 0.5], meaning BM25 and FAISS have equal weight in the retrieval process. You can change this value to see how the answers differ.

```python {.marimo}
from langchain_community.vectorstores import FAISS
from langchain_openai import OpenAIEmbeddings
from langchain.retrievers.ensemble import EnsembleRetriever
from langchain.schema.runnable import Runnable

#  embeddings
embeddings = OpenAIEmbeddings(model="text-embedding-3-large", api_key=api_key.value)

# load FAISS index
faiss_store = FAISS.load_local(
    "bb_index", embeddings, allow_dangerous_deserialization=True
)

# get FAISS retriever
faiss_retriever = faiss_store.as_retriever(search_kwargs={"k": 10})

# Create ensemble retriever
hybrid_retriever = EnsembleRetriever(
    retrievers=[bm25_retriever, faiss_retriever],
    weights=[0.5, 0.5]
)
```

### Defining your Prompt and Loading the model
Here, we will define the prompt for our system. I am explicitly specifying that the system should focus on the ransomware gang ecosystems. Additionally, I am instructing the model to understand Russian slang since I did not translate the data beforehand—the model can handle it.

I am also specifying that the model should ground its responses only on our retrieval context. This is a basic hallucination mitigation technique, but it should be sufficient if the previous steps were done correctly.

```python {.marimo}
from langchain_core.prompts import ChatPromptTemplate
from langchain_openai import ChatOpenAI
from langchain_core.runnables import RunnablePassthrough
from langchain_core.output_parsers import StrOutputParser

# Define your prompt template
prompt = ChatPromptTemplate.from_template(
    """You are an expert system specializing in analyzing ransomware gang ecosystems. You are specialized in chat log analysis and understand Russian slang. Answer the question only in English and always justify your answer based only on the following context:
    {context}

    Question: {question}

Note: If the question does not require the context or is out of scope, answer without using the context.
    """
)

# Initialize the language model
llm = ChatOpenAI(
    model="gpt-4o-mini",
    max_tokens=None,
    timeout=None,
    max_retries=2,
    api_key=api_key.value
)
```

### Formating output and loading calling our RAG
Now, I just call our RAG and formatt the output to retrieve the data. Finally, I am using Marimo UI to create the chat interface (notice how simple it is for rapid prototyping).

```python {.marimo}
# format documents
def format_docs2(docs):
    return "\n\n".join(doc.page_content for doc in docs)

# chain retriever
def retrieve_and_format2(query):
    docs = hybrid_retriever.invoke(query)
    return {
        "formatted": format_docs2(docs),
        "raw_docs": docs
    }

# RAG chain with context preservation
rag_chain2 = (
    {
        "context": lambda x: retrieve_and_format2(x)["formatted"],
        "question": RunnablePassthrough(),
        "raw_docs": lambda x: retrieve_and_format2(x)["raw_docs"]
    }
    | prompt
    | llm
    | StrOutputParser()
)

def chat_with_documents2(query):
    context_docs = hybrid_retriever.invoke(query)
    response = rag_chain2.invoke(query)

    output = {
        "response": response,
        "retrieved_documents": [
            {
                "content": doc.page_content,
                "metadata": doc.metadata
            } for doc in context_docs
        ]
    }
    return output

def rag_chat_model2(messages, config):
    query = messages[-1].content
    result = chat_with_documents2(query)

    response_text = result["response"]
    context_text = "\n\nRetrieved Documents:\n"
    for i, doc in enumerate(result["retrieved_documents"], 1):
        context_text += f"\n--- Document {i} ---\n"
        context_text += f"Content: {doc['content']}\n"
        context_text += f"Metadata: {doc['metadata']}\n"

    return response_text + context_text
```

```python {.marimo}
# chat interface with context display
mo.ui.chat(
    rag_chat_model2,
    prompts=["What are the tactics techniques and procedures used?", "Give me details about ofensive tools mentionned"],
    show_configuration_controls=True
)
```

And boom we now have a fully customisable rag grounded for our specific data with the original data to verify.
<!---->
### Bonus: Context relevancy evaluation
I know some of you might still be skeptical about the usage of generative AI, and of course, these kinds of systems are not perfect. But I wanted to share some additional tips to help improve response accuracy.

I’m going to use the lib DeepEval to assess context relevancy—instead of just checking if the model is making things up, we will evaluate how well the retrieved data supports the response. The idea is simple:

- Retrieve relevant context before generating a response.
- Compare the model output against the retrieved documents.
- Measure contextual relevancy using DeepEval ContextualRelevancyMetric, which scores how well the model response aligns with the available data.

This will help us gauge if the model is actually using relevant information or just generating a loosely related answer. Instead of blindly trusting the response, we can check if it is based on strong supporting evidence from retrieved sources.

#### Limitations of Contextual Relevancy
- It does not check for factual correctness—if all retrieved documents contain false information, the model can still score high.
- If the AI rephrases the response too much, it might get penalized even when the meaning is correct.
- Chat logs, informal text, and language translation can lower the score, even if the response is well-structured and useful.
- Also, if the number of retrieved documents is too high, some will be irrelevant and lower the relevancy score.

So while contextual relevancy helps ensure the AI isn’t ignoring retrieved data, it does not guarantee that the information is objectively true. However this show one way to mitigate falsed information from your model.

```python {.marimo}
from deepeval import evaluate
from deepeval.metrics import ContextualRelevancyMetric
from deepeval.test_case import LLMTestCase

def chat_with_documents3(query):
    context_docs = hybrid_retriever.invoke(query)
    response = rag_chain2.invoke(query)

    retrieval_context = [doc.page_content for doc in context_docs]

    test_case = LLMTestCase(
        input=query,
        actual_output=response,
        retrieval_context=retrieval_context
    )
    metric = ContextualRelevancyMetric(threshold=0.5, model="gpt-4o-mini", include_reason=True)
    metric.measure(test_case)

    output = {
        "response": response,
        "retrieved_documents": [
            {
                "content": doc.page_content,
                "metadata": doc.metadata
            } for doc in context_docs
        ],
        "contextual_relevancy_score": metric.score,
        "contextual_relevancy_reason": metric.reason
    }
    return output

def rag_chat_model3(messages):
    query = messages[-1]["content"] 
    result = chat_with_documents3(query)

    response_text = result["response"]

    relevancy_info = {
        "score": result["contextual_relevancy_score"],
        "reason": result["contextual_relevancy_reason"]
    }

    retrieved_docs = []
    for i, doc in enumerate(result["retrieved_documents"], 1):
        retrieved_docs.append({
            "doc_number": i,
            "content": doc["content"],
            "metadata": doc["metadata"]
        })

    return response_text, relevancy_info, retrieved_docs

# example queries
#messages = [{"content": "What is the impact of Log4Shell on modern web applications?"}]
messages = [{"content": "Give me any mentions of offensive tools discussed"}] 

#response, relevancy, docs = rag_chat_model3(messages)

#print("Response:", response)
#print("\nContextual Relevancy Score:", relevancy["score"])
#print("Contextual Relevancy Reason:", relevancy["reason"])
#print("\nRetrieved Documents:")
#for doc in docs:
#    print(f"\nDocument {doc['doc_number']}:")
#    print(f"Content: {doc['content']}")
#    print(f"Metadata: {doc['metadata']}")
```

```python {.marimo}
#response
```

```python {.marimo}
#relevancy["score"]
```

```python {.marimo}
#relevancy["reason"]
```

## Conclusion

Thanks for reading until here. In this notebook, we explored how to use Python and GenAI to analyze a data leak practically. I first demonstrated how to parse the data and generate visuals for an overview of the analysis.

From understanding the structure of the file, the number of messages, users, and temporal investigation, it is clear that the user seems to work during normal business hours with downtime in August.

After getting an overview of the data, we loaded the logs into a hybrid RAG. First, I loaded the data while ensuring the metadata remained available. Then, I stored the data in a FAISS index for semantic search, used BM25 for keyword search, and combined everything into an ensemble retriever.

I also showed how to retrieve the original data so you can validate and verify the LLM’s answers with the raw information.

Finally, I discussed a way to ground the data by scoring retrieval relevancy instead of just hallucination. By using DeepEval’s Contextual Relevancy Metric, we measured how well the AI’s response aligns with the retrieved documents. This is an initial step, and there are multiple ways to improve retrieval quality and ensure your system stays relevant. I'll let you explore the DeepEval library on your own.

This was also my first time using Marimo as a replacement for Jupyter. I found it very intuitive and useful, and setting up the chat interface was super simple.

I hope you learned something along the way. I documented the process and code so you can reuse and adapt it.

If you liked my work, feel free to tag me on social networks and drop me a follow 👇
<!---->
# Follow me
<div style="display: flex; justify-content: center; gap: 15px; margin-top: 20px;">
    <a href="https://www.linkedin.com/in/thomas-roccia/" target="_blank">
        <button style="background-color: #0077b5; color: white; border: none; padding: 12px 18px; border-radius: 8px; font-size: 16px; cursor: pointer;">
            🔗 LinkedIn
        </button>
    </a>
    <a href="https://x.com/fr0gger_" target="_blank">
        <button style="background-color: #000000; color: white; border: none; padding: 12px 18px; border-radius: 8px; font-size: 16px; cursor: pointer;">
            🐦 Twitter
        </button>
    </a>
    <a href="https://store.securitybreak.io/theintelbrief" target="_blank">
        <button style="background-color: #ff4500; color: white; border: none; padding: 12px 18px; border-radius: 8px; font-size: 16px; cursor: pointer;">
            📰 Newsletter
        </button>
    </a>
</div>

```python {.marimo}

```
