# DarkHydrus - G0079

**Created**: 2018-10-17T00:14:20.652Z

**Modified**: 2021-10-12T19:52:22.454Z

**Contributors**: Oleg Skulkin, Group-IB

## Aliases

DarkHydrus

## Description

[DarkHydrus](https://attack.mitre.org/groups/G0079) is a threat group that has targeted government agencies and educational institutions in the Middle East since at least 2016. The group heavily leverages open-source tools and custom payloads for carrying out attacks. (Citation: Unit 42 DarkHydrus July 2018) (Citation: Unit 42 Playbook Dec 2017)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[DarkHydrus](https://attack.mitre.org/groups/G0079) has obtained and used tools such as [Mimikatz](https://attack.mitre.org/software/S0002), [Empire](https://attack.mitre.org/software/S0363), and [Cobalt Strike](https://attack.mitre.org/software/S0154).(Citation: Unit 42 DarkHydrus July 2018)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1564.003|Hidden Window|[DarkHydrus](https://attack.mitre.org/groups/G0079) has used <code>-WindowStyle Hidden</code> to conceal [PowerShell](https://attack.mitre.org/techniques/T1059/001) windows. (Citation: Unit 42 DarkHydrus July 2018)|
|mitre-attack|enterprise-attack|Windows|T1187|Forced Authentication|[DarkHydrus](https://attack.mitre.org/groups/G0079) used [Template Injection](https://attack.mitre.org/techniques/T1221) to launch an authentication window for users to enter their credentials.(Citation: Unit 42 Phishery Aug 2018)|
|mitre-attack|enterprise-attack|Windows|T1221|Template Injection|[DarkHydrus](https://attack.mitre.org/groups/G0079) used an open-source tool, Phishery, to inject malicious remote template URLs into Microsoft Word documents and then sent them to victims to enable [Forced Authentication](https://attack.mitre.org/techniques/T1187).(Citation: Unit 42 Phishery Aug 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[DarkHydrus](https://attack.mitre.org/groups/G0079) has sent malware that required users to hit the enable button in Microsoft Excel to allow an .iqy file to be downloaded.(Citation: Unit 42 DarkHydrus July 2018)(Citation: Unit 42 Playbook Dec 2017)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[DarkHydrus](https://attack.mitre.org/groups/G0079) leveraged PowerShell to download and execute additional scripts for execution.(Citation: Unit 42 DarkHydrus July 2018)(Citation: Unit 42 Playbook Dec 2017)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[DarkHydrus](https://attack.mitre.org/groups/G0079) has sent spearphishing emails with password-protected RAR archives containing malicious Excel Web Query files (.iqy). The group has also sent spearphishing emails that contained malicious Microsoft Office documents that use the “attachedTemplate” technique to load a template from a remote server.(Citation: Unit 42 DarkHydrus July 2018)(Citation: Unit 42 Phishery Aug 2018)(Citation: Unit 42 Playbook Dec 2017)|
