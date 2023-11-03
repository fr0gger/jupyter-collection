# Nomadic Octopus - G0133

**Created**: 2021-08-24T17:04:27.002Z

**Modified**: 2022-09-02T18:03:55.294Z

**Contributors**: 

## Aliases

Nomadic Octopus,DustSquad

## Description


[Nomadic Octopus](https://attack.mitre.org/groups/G0133) is a Russian-speaking cyber espionage threat group that has primarily targeted Central Asia, including local governments, diplomatic missions, and individuals, since at least 2014. [Nomadic Octopus](https://attack.mitre.org/groups/G0133) has been observed conducting campaigns involving Android and Windows malware, mainly using the Delphi programming language, and building custom variants.(Citation: Security Affairs DustSquad Oct 2018)(Citation: Securelist Octopus Oct 2018)(Citation: ESET Nomadic Octopus 2018)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Nomadic Octopus](https://attack.mitre.org/groups/G0133) as attempted to lure victims into clicking on malicious attachments within spearphishing emails.(Citation: Securelist Octopus Oct 2018)(Citation: ESET Nomadic Octopus 2018)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1564.003|Hidden Window|[Nomadic Octopus](https://attack.mitre.org/groups/G0133) executed PowerShell in a hidden window.(Citation: ESET Nomadic Octopus 2018) |
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Nomadic Octopus](https://attack.mitre.org/groups/G0133) has used PowerShell for execution.(Citation: ESET Nomadic Octopus 2018) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Nomadic Octopus](https://attack.mitre.org/groups/G0133) has used malicious macros to download additional files to the victim's machine.(Citation: ESET Nomadic Octopus 2018) |
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Nomadic Octopus](https://attack.mitre.org/groups/G0133) used <code>cmd.exe /c</code> within a malicious macro.(Citation: ESET Nomadic Octopus 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036|Masquerading|[Nomadic Octopus](https://attack.mitre.org/groups/G0133) attempted to make [Octopus](https://attack.mitre.org/software/S0340) appear as a  Telegram Messenger with a Russian interface.(Citation: Securelist Octopus Oct 2018)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Nomadic Octopus](https://attack.mitre.org/groups/G0133) has targeted victims with spearphishing emails containing malicious attachments.(Citation: Security Affairs DustSquad Oct 2018)(Citation: ESET Nomadic Octopus 2018)|
