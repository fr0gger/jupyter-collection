# Aoqin Dragon - G1007

**Created**: 2022-07-14T14:32:47.582Z

**Modified**: 2022-10-24T18:50:40.179Z

**Contributors**: Hiroki Nagahama, NEC Corporation,Pooja Natarajan, NEC Corporation India,Manikantan Srinivasan, NEC Corporation India

## Aliases

Aoqin Dragon

## Description

[Aoqin Dragon](https://attack.mitre.org/groups/G1007) is a suspected Chinese cyber espionage threat group that has been active since at least 2013. [Aoqin Dragon](https://attack.mitre.org/groups/G1007) has primarily targeted government, education, and telecommunication organizations in Australia, Cambodia, Hong Kong, Singapore, and Vietnam. Security researchers noted a potential association between [Aoqin Dragon](https://attack.mitre.org/groups/G1007) and UNC94, based on malware, infrastructure, and targets.(Citation: SentinelOne Aoqin Dragon June 2022)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows|T1091|Replication Through Removable Media|[Aoqin Dragon](https://attack.mitre.org/groups/G1007) has used a dropper that employs a worm infection strategy using a removable device to breach a secure network environment.(Citation: SentinelOne Aoqin Dragon June 2022)|
|mitre-attack|enterprise-attack|PRE|T1587.001|Malware|[Aoqin Dragon](https://attack.mitre.org/groups/G1007) has used custom malware, including [Mongall](https://attack.mitre.org/software/S1026) and [Heyoka Backdoor](https://attack.mitre.org/software/S1027), in their operations.(Citation: SentinelOne Aoqin Dragon June 2022)|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Aoqin Dragon](https://attack.mitre.org/groups/G1007) obtained the Heyoka open source exfiltration tool and subsequently modified it for their operations.(Citation: SentinelOne Aoqin Dragon June 2022)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1027.002|Software Packing|[Aoqin Dragon](https://attack.mitre.org/groups/G1007) has used the Themida packer to obfuscate malicious payloads.(Citation: SentinelOne Aoqin Dragon June 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1570|Lateral Tool Transfer|[Aoqin Dragon](https://attack.mitre.org/groups/G1007) has spread malware in target networks by copying modules to folders masquerading as removable devices.(Citation: SentinelOne Aoqin Dragon June 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[Aoqin Dragon](https://attack.mitre.org/groups/G1007) has run scripts to identify file formats including Microsoft Word.(Citation: SentinelOne Aoqin Dragon June 2022)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Aoqin Dragon](https://attack.mitre.org/groups/G1007) has exploited CVE-2012-0158 and CVE-2010-3333 for execution against targeted systems.(Citation: SentinelOne Aoqin Dragon June 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Aoqin Dragon](https://attack.mitre.org/groups/G1007) has used fake icons including antivirus and external drives to disguise malicious payloads.(Citation: SentinelOne Aoqin Dragon June 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Aoqin Dragon](https://attack.mitre.org/groups/G1007) has lured victims into opening weaponized documents, fake external drives, and fake antivirus to execute malicious payloads.(Citation: SentinelOne Aoqin Dragon June 2022)|
