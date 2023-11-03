# Gallmaker - G0084

**Created**: 2019-01-30T14:26:42.897Z

**Modified**: 2020-03-30T19:04:47.798Z

**Contributors**: 

## Aliases

Gallmaker

## Description

[Gallmaker](https://attack.mitre.org/groups/G0084) is a cyberespionage group that has targeted victims in the Middle East and has been active since at least December 2017. The group has mainly targeted victims in the defense, military, and government sectors.(Citation: Symantec Gallmaker Oct 2018)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560.001|Archive via Utility|[Gallmaker](https://attack.mitre.org/groups/G0084) has used WinZip, likely to archive data prior to exfiltration.(Citation: Symantec Gallmaker Oct 2018)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Gallmaker](https://attack.mitre.org/groups/G0084) sent emails with malicious Microsoft Office documents attached.(Citation: Symantec Gallmaker Oct 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Gallmaker](https://attack.mitre.org/groups/G0084) sent victims a lure document with a warning that asked victims to “enable content” for execution.(Citation: Symantec Gallmaker Oct 2018)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Gallmaker](https://attack.mitre.org/groups/G0084) used PowerShell to download additional payloads and for execution.(Citation: Symantec Gallmaker Oct 2018)|
|mitre-attack|enterprise-attack|Windows|T1559.002|Dynamic Data Exchange|[Gallmaker](https://attack.mitre.org/groups/G0084) attempted to exploit Microsoft’s DDE protocol in order to gain access to victim machines and for execution.(Citation: Symantec Gallmaker Oct 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Gallmaker](https://attack.mitre.org/groups/G0084) obfuscated shellcode used during execution.(Citation: Symantec Gallmaker Oct 2018)|
