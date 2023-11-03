# BlackTech - G0098

**Created**: 2020-05-05T18:36:45.970Z

**Modified**: 2022-04-06T13:14:27.477Z

**Contributors**: Tatsuya Daitoku, Cyber Defense Institute, Inc.,Hannah Simes, BT Security

## Aliases

BlackTech,Palmerworm

## Description

[BlackTech](https://attack.mitre.org/groups/G0098) is a suspected Chinese cyber espionage group that has primarily targeted organizations in East Asia--particularly Taiwan, Japan, and Hong Kong--and the US since at least 2013. [BlackTech](https://attack.mitre.org/groups/G0098) has used a combination of custom malware, dual-use tools, and living off the land tactics to compromise media, construction, engineering, electronics, and financial company networks.(Citation: TrendMicro BlackTech June 2017)(Citation: Symantec Palmerworm Sep 2020)(Citation: Reuters Taiwan BlackTech August 2020)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[BlackTech](https://attack.mitre.org/groups/G0098) has obtained and used tools such as Putty, SNScan, and [PsExec](https://attack.mitre.org/software/S0029) for its operations.(Citation: Symantec Palmerworm Sep 2020)|
|mitre-attack|enterprise-attack|PRE|T1588.004|Digital Certificates|[BlackTech](https://attack.mitre.org/groups/G0098) has used valid, stolen digital certificates for some of their malware and tools.(Citation: ESET PLEAD Malware July 2018)|
|mitre-attack|enterprise-attack|PRE|T1588.003|Code Signing Certificates|[BlackTech](https://attack.mitre.org/groups/G0098) has used stolen code-signing certificates for its malicious payloads.(Citation: Symantec Palmerworm Sep 2020)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers,Network|T1046|Network Service Discovery|[BlackTech](https://attack.mitre.org/groups/G0098) has used the SNScan tool to find other potential targets on victim networks.(Citation: Symantec Palmerworm Sep 2020)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1106|Native API|[BlackTech](https://attack.mitre.org/groups/G0098) has used built-in API functions.(Citation: IronNet BlackTech Oct 2021)|
|mitre-attack|enterprise-attack|Linux,macOS|T1021.004|SSH|[BlackTech](https://attack.mitre.org/groups/G0098) has used Putty for remote access.(Citation: Symantec Palmerworm Sep 2020)|
|mitre-attack|enterprise-attack|Windows|T1574.002|DLL Side-Loading|[BlackTech](https://attack.mitre.org/groups/G0098) has used DLL side loading by giving DLLs hardcoded names and placing them in searched directories.(Citation: Trend Micro Waterbear December 2019) |
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[BlackTech](https://attack.mitre.org/groups/G0098) has used spearphishing e-mails with malicious password-protected archived files (ZIP or RAR) to deliver malware.(Citation: TrendMicro BlackTech June 2017)(Citation: NTT Security Flagpro new December 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[BlackTech](https://attack.mitre.org/groups/G0098) has used e-mails with malicious documents to lure victims into installing malware.(Citation: TrendMicro BlackTech June 2017)(Citation: NTT Security Flagpro new December 2021)	 |
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[BlackTech](https://attack.mitre.org/groups/G0098) has used spearphishing e-mails with links to cloud services to deliver malware.(Citation: TrendMicro BlackTech June 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[BlackTech](https://attack.mitre.org/groups/G0098) has used e-mails with malicious links to lure victims into installing malware.(Citation: TrendMicro BlackTech June 2017)	 |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1036.002|Right-to-Left Override|[BlackTech](https://attack.mitre.org/groups/G0098) has used right-to-left-override to obfuscate the filenames of malicious e-mail attachments.(Citation: TrendMicro BlackTech June 2017)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[BlackTech](https://attack.mitre.org/groups/G0098) has exploited multiple vulnerabilities for execution, including Microsoft Office vulnerabilities CVE-2012-0158, CVE-2014-6352, CVE-2017-0199, and Adobe Flash CVE-2015-5119.(Citation: TrendMicro BlackTech June 2017)|
|mitre-attack|enterprise-attack|Windows,IaaS,Network,Linux,macOS,Containers|T1190|Exploit Public-Facing Application|[BlackTech](https://attack.mitre.org/groups/G0098) has exploited a buffer overflow vulnerability in Microsoft Internet Information Services (IIS) 6.0, CVE-2017-7269, in order to establish a new HTTP or command and control (C2) server.(Citation: TrendMicro BlackTech June 2017)|
