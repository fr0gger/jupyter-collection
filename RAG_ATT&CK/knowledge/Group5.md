# Group5 - G0043

**Created**: 2017-05-31T21:32:08.304Z

**Modified**: 2020-03-30T19:07:39.812Z

**Contributors**: 

## Aliases

Group5

## Description

[Group5](https://attack.mitre.org/groups/G0043) is a threat group with a suspected Iranian nexus, though this attribution is not definite. The group has targeted individuals connected to the Syrian opposition via spearphishing and watering holes, normally using Syrian and Iranian themes. [Group5](https://attack.mitre.org/groups/G0043) has used two commonly available remote access tools (RATs), [njRAT](https://attack.mitre.org/software/S0385) and [NanoCore](https://attack.mitre.org/software/S0336), as well as an Android RAT, DroidJack. (Citation: Citizen Lab Group5)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Group5](https://attack.mitre.org/groups/G0043) disguised its malicious binaries with several layers of obfuscation, including encrypting the files.(Citation: Citizen Lab Group5)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1113|Screen Capture|Malware used by [Group5](https://attack.mitre.org/groups/G0043) is capable of watching the victim's screen.(Citation: Citizen Lab Group5)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Network|T1056.001|Keylogging|Malware used by [Group5](https://attack.mitre.org/groups/G0043) is capable of capturing keystrokes.(Citation: Citizen Lab Group5)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|Malware used by [Group5](https://attack.mitre.org/groups/G0043) is capable of remotely deleting files from victims.(Citation: Citizen Lab Group5)|
