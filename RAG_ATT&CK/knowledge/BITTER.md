# BITTER - G1002

**Created**: 2022-06-01T20:26:53.880Z

**Modified**: 2022-06-01T21:20:18.113Z

**Contributors**: 

## Aliases

BITTER,T-APT-17

## Description

[BITTER](https://attack.mitre.org/groups/G1002) is a suspected South Asian cyber espionage threat group that has been active since at least 2013. [BITTER](https://attack.mitre.org/groups/G1002) has primarily targeted government, energy, and engineering organizations in Pakistan, China, Bangladesh, and Saudi Arabia.(Citation: Cisco Talos Bitter Bangladesh May 2022)(Citation: Forcepoint BITTER Pakistan Oct 2016)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1608.001|Upload Malware|[BITTER](https://attack.mitre.org/groups/G1002) has registered domains to stage payloads.(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|PRE|T1583.001|Domains|[BITTER](https://attack.mitre.org/groups/G1002) has registered a variety of domains to host malicious payloads and for C2.(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1068|Exploitation for Privilege Escalation|[BITTER](https://attack.mitre.org/groups/G1002) has exploited CVE-2021-1732 for privilege escalation.(Citation: DBAPPSecurity BITTER zero-day Feb 2021)(Citation: Microsoft CVE-2021-1732 Feb 2021)|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[BITTER](https://attack.mitre.org/groups/G1002) has obtained tools such as PuTTY for use in their operations.(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1568|Dynamic Resolution|[BITTER](https://attack.mitre.org/groups/G1002) has used DDNS for C2 communications.(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1573|Encrypted Channel|[BITTER](https://attack.mitre.org/groups/G1002) has encrypted their C2 communications.(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,Network|T1095|Non-Application Layer Protocol|[BITTER](https://attack.mitre.org/groups/G1002) has used TCP for C2 communications.(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[BITTER](https://attack.mitre.org/groups/G1002) has used HTTP POST requests for C2.(Citation: Cisco Talos Bitter Bangladesh May 2022)(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[BITTER](https://attack.mitre.org/groups/G1002) has used a RAR SFX dropper to deliver malware.(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[BITTER](https://attack.mitre.org/groups/G1002) has used scheduled tasks for persistence and execution.(Citation: Cisco Talos Bitter Bangladesh May 2022)|
|mitre-attack|enterprise-attack|Windows|T1559.002|Dynamic Data Exchange|[BITTER](https://attack.mitre.org/groups/G1002) has executed OLE objects using Microsoft Equation Editor to download and run malicious payloads.(Citation: Cisco Talos Bitter Bangladesh May 2022) |
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1036.004|Masquerade Task or Service|[BITTER](https://attack.mitre.org/groups/G1002) has disguised malware as a Windows Security update service.(Citation: Cisco Talos Bitter Bangladesh May 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[BITTER](https://attack.mitre.org/groups/G1002) has downloaded additional malware and tools onto a compromised host.(Citation: Cisco Talos Bitter Bangladesh May 2022)(Citation: Forcepoint BITTER Pakistan Oct 2016) |
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[BITTER](https://attack.mitre.org/groups/G1002) has exploited Microsoft Office vulnerabilities CVE-2012-0158, CVE-2017-11882, CVE-2018-0798, and CVE-2018-0802.(Citation: Cisco Talos Bitter Bangladesh May 2022)(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[BITTER](https://attack.mitre.org/groups/G1002) has attempted to lure victims into opening malicious attachments delivered via spearphishing.(Citation: Cisco Talos Bitter Bangladesh May 2022)(Citation: Forcepoint BITTER Pakistan Oct 2016)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[BITTER](https://attack.mitre.org/groups/G1002) has sent spearphishing emails with a malicious RTF document or Excel spreadsheet.(Citation: Cisco Talos Bitter Bangladesh May 2022)(Citation: Forcepoint BITTER Pakistan Oct 2016)|
