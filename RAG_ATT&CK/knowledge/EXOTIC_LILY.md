# EXOTIC LILY - G1011

**Created**: 2022-08-18T15:25:59.689Z

**Modified**: 2022-10-24T18:48:18.917Z

**Contributors**: Phill Taylor, BT Security

## Aliases

EXOTIC LILY

## Description

[EXOTIC LILY](https://attack.mitre.org/groups/G1011) is a financially motivated group that has been closely linked with [Wizard Spider](https://attack.mitre.org/groups/G0102) and the deployment of ransomware including [Conti](https://attack.mitre.org/software/S0575) and [Diavol](https://attack.mitre.org/software/S0659). [EXOTIC LILY](https://attack.mitre.org/groups/G1011) may be acting as an initial access broker for other malicious actors, and has targeted a wide range of industries including IT, cybersecurity, and healthcare since at least September 2021.(Citation: Google EXOTIC LILY March 2022)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) conducted an e-mail thread-hijacking campaign with malicious ISO attachments.(Citation: Google EXOTIC LILY March 2022)(Citation: Proofpoint Bumblebee April 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has used malicious links to lure users into executing malicious payloads.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1566.003|Spearphishing via Service|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has used the e-mail notification features of legitimate file sharing services for spearphishing.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|PRE|T1597|Search Closed Sources|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has searched for information on targeted individuals on business databases including RocketReach and CrunchBase.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|PRE|T1593.001|Social Media|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has copied data from social media sites to impersonate targeted individuals.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|PRE|T1585.001|Social Media Accounts|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has established social media profiles to mimic employees of targeted companies.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|PRE|T1608.001|Upload Malware|[EXOTIC LILY](https://attack.mitre.org/groups/G1011)  has uploaded malicious payloads to file-sharing services including TransferNow, TransferXL, WeTransfer, and OneDrive.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|PRE|T1594|Search Victim-Owned Websites|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has used contact forms on victim websites to generate phishing e-mails.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|PRE|T1589.002|Email Addresses|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has gathered targeted individuals' e-mail addresses through open source research and website contact forms.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|PRE|T1585.002|Email Accounts|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has created e-mail accounts to spoof targeted organizations.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|PRE|T1583.001|Domains|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has registered domains to spoof targeted organizations by changing the top-level domain (TLD) to “.us”, “.co” or “.biz”.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102|Web Service|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has used file-sharing services including WeTransfer, TransferNow, and OneDrive to deliver payloads.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has relied on victims to open malicious links in e-mails for execution.(Citation: Google EXOTIC LILY March 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has gained execution through victims clicking on malicious LNK files contained within ISO files, which can execute hidden DLLs within the ISO.(Citation: Google EXOTIC LILY March 2022)(Citation: Proofpoint Bumblebee April 2022)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has used malicious documents containing exploits for CVE-2021-40444 affecting Microsoft MSHTML.(Citation: Google EXOTIC LILY March 2022)|
