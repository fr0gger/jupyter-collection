# WIRTE - G0090

**Created**: 2019-05-24T17:02:44.226Z

**Modified**: 2022-04-15T19:50:19.478Z

**Contributors**: Lab52 by S2 Grupo

## Aliases

WIRTE

## Description

[WIRTE](https://attack.mitre.org/groups/G0090) is a threat group that has been active since at least August 2018. [WIRTE](https://attack.mitre.org/groups/G0090) has targeted government, diplomatic, financial, military, legal, and technology organizations in the Middle East and Europe.(Citation: Lab52 WIRTE Apr 2019)(Citation: Kaspersky WIRTE November 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1571|Non-Standard Port|[WIRTE](https://attack.mitre.org/groups/G0090) has used HTTPS over ports 2083 and 2087 for C2.(Citation: Kaspersky WIRTE November 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[WIRTE](https://attack.mitre.org/groups/G0090) has named a first stage dropper `Kaspersky Update Agent` in order to appear legitimate.(Citation: Kaspersky WIRTE November 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[WIRTE](https://attack.mitre.org/groups/G0090) has attempted to lure users into opening malicious MS Word and Excel files to execute malicious payloads.(Citation: Kaspersky WIRTE November 2021)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[WIRTE](https://attack.mitre.org/groups/G0090) has sent emails to intended victims with malicious MS Word and Excel attachments.(Citation: Kaspersky WIRTE November 2021)|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[WIRTE](https://attack.mitre.org/groups/G0090) has obtained and used [Empire](https://attack.mitre.org/software/S0363) for post-exploitation activities.(Citation: Lab52 WIRTE Apr 2019)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1140|Deobfuscate/Decode Files or Information|[WIRTE](https://attack.mitre.org/groups/G0090) has used Base64 to decode malicious VBS script.(Citation: Lab52 WIRTE Apr 2019)|
|mitre-attack|enterprise-attack|Windows|T1218.010|Regsvr32|[WIRTE](https://attack.mitre.org/groups/G0090) has used `regsvr32.exe` to trigger the execution of a malicious script.(Citation: Lab52 WIRTE Apr 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[WIRTE](https://attack.mitre.org/groups/G0090) has downloaded PowerShell code from the C2 server to be executed.(Citation: Lab52 WIRTE Apr 2019)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[WIRTE](https://attack.mitre.org/groups/G0090) has used PowerShell for script execution.(Citation: Lab52 WIRTE Apr 2019)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[WIRTE](https://attack.mitre.org/groups/G0090) has used VBScript  in its operations.(Citation: Lab52 WIRTE Apr 2019)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[WIRTE](https://attack.mitre.org/groups/G0090) has used HTTP for network communication.(Citation: Lab52 WIRTE Apr 2019)	|
