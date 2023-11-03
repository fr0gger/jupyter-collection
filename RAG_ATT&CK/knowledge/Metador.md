# Metador - G1013

**Created**: 2023-01-25T23:57:51.818Z

**Modified**: 2023-04-14T12:25:35.434Z

**Contributors**: Massimiliano Romano, BT Security,Sittikorn Sangrattanapitak

## Aliases

Metador

## Description

[Metador](https://attack.mitre.org/groups/G1013) is a suspected cyber espionage group that was first reported in September 2022. [Metador](https://attack.mitre.org/groups/G1013) has targeted a limited number of telecommunication companies, internet service providers, and universities in the Middle East and Africa. Security researchers named the group [Metador](https://attack.mitre.org/groups/G1013) based on the "I am meta" string in one of the group's malware samples and the expectation of Spanish-language responses from C2 servers.(Citation: SentinelLabs Metador Sept 2022)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Metador](https://attack.mitre.org/groups/G1013) has encrypted their payloads.(Citation: SentinelLabs Metador Sept 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[Metador](https://attack.mitre.org/groups/G1013) has quickly deleted `cbd.exe` from a compromised host following the successful deployment of their malware.(Citation: SentinelLabs Metador Sept 2022) |
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Metador](https://attack.mitre.org/groups/G1013) has used Microsoft's Console Debugger in some of their operations.(Citation: SentinelLabs Metador Sept 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Metador](https://attack.mitre.org/groups/G1013) has downloaded tools and malware onto a compromised system.(Citation: SentinelLabs Metador Sept 2022)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Metador](https://attack.mitre.org/groups/G1013) has used the Windows command line to execute commands.(Citation: SentinelLabs Metador Sept 2022)|
|mitre-attack|enterprise-attack|Windows|T1546.003|Windows Management Instrumentation Event Subscription|[Metador](https://attack.mitre.org/groups/G1013) has established persistence through the use of a WMI event subscription combined with unusual living-off-the-land binaries such as `cdb.exe`.(Citation: SentinelLabs Metador Sept 2022)|
|mitre-attack|enterprise-attack|PRE|T1588.001|Malware|[Metador](https://attack.mitre.org/groups/G1013) has used unique malware in their operations, including [metaMain](https://attack.mitre.org/software/S1059) and [Mafalda](https://attack.mitre.org/software/S1060).(Citation: SentinelLabs Metador Sept 2022)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,Network|T1095|Non-Application Layer Protocol|[Metador](https://attack.mitre.org/groups/G1013) has used TCP for C2.(Citation: SentinelLabs Metador Sept 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[Metador](https://attack.mitre.org/groups/G1013) has used HTTP for C2.(Citation: SentinelLabs Metador Sept 2022)|
