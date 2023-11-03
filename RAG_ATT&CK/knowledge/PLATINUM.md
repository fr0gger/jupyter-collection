# PLATINUM - G0068

**Created**: 2018-04-18T17:59:24.739Z

**Modified**: 2021-04-22T00:39:49.529Z

**Contributors**: Ryan Becwar

## Aliases

PLATINUM

## Description

[PLATINUM](https://attack.mitre.org/groups/G0068) is an activity group that has targeted victims since at least 2009. The group has focused on targets associated with governments and related organizations in South and Southeast Asia. (Citation: Microsoft PLATINUM April 2016)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036|Masquerading|[PLATINUM](https://attack.mitre.org/groups/G0068) has renamed rar.exe to avoid detection.(Citation: Twitter ItsReallyNick Platinum Masquerade)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[PLATINUM](https://attack.mitre.org/groups/G0068) has used keyloggers that are also capable of dumping credentials.(Citation: Microsoft PLATINUM April 2016)|
|mitre-attack|enterprise-attack|Windows|T1056.004|Credential API Hooking|[PLATINUM](https://attack.mitre.org/groups/G0068) is capable of using Windows hook interfaces for information gathering such as credential access.(Citation: Microsoft PLATINUM April 2016)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Network|T1056.001|Keylogging|[PLATINUM](https://attack.mitre.org/groups/G0068) has used several different keyloggers.(Citation: Microsoft PLATINUM April 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[PLATINUM](https://attack.mitre.org/groups/G0068) has attempted to get users to open malicious files by sending spearphishing emails with attachments to victims.(Citation: Microsoft PLATINUM April 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[PLATINUM](https://attack.mitre.org/groups/G0068) has transferred files using the Intel® Active Management Technology (AMT) Serial-over-LAN (SOL) channel.(Citation: Microsoft PLATINUM June 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1068|Exploitation for Privilege Escalation|[PLATINUM](https://attack.mitre.org/groups/G0068) has leveraged a zero-day vulnerability to escalate privileges.(Citation: Microsoft PLATINUM April 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,Network|T1095|Non-Application Layer Protocol|[PLATINUM](https://attack.mitre.org/groups/G0068) has used the Intel® Active Management Technology (AMT) Serial-over-LAN (SOL) channel for command and control.(Citation: Microsoft PLATINUM June 2017)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[PLATINUM](https://attack.mitre.org/groups/G0068) has sent spearphishing emails with attachments to victims as its primary initial access vector.(Citation: Microsoft PLATINUM April 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1055|Process Injection|[PLATINUM](https://attack.mitre.org/groups/G0068) has used various methods of process injection including hot patching.(Citation: Microsoft PLATINUM April 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[PLATINUM](https://attack.mitre.org/groups/G0068) has sometimes used drive-by attacks against vulnerable browser plugins.(Citation: Microsoft PLATINUM April 2016)|
