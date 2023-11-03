# FIN10 - G0051

**Created**: 2017-12-14T16:46:06.044Z

**Modified**: 2021-05-26T12:35:39.400Z

**Contributors**: 

## Aliases

FIN10

## Description

[FIN10](https://attack.mitre.org/groups/G0051) is a financially motivated threat group that has targeted organizations in North America since at least 2013 through 2016. The group uses stolen data exfiltrated from victims to extort organizations. (Citation: FireEye FIN10 June 2017)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[FIN10](https://attack.mitre.org/groups/G0051) has relied on publicly-available software to gain footholds and establish persistence in victim environments.(Citation: FireEye FIN10 June 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1078.003|Local Accounts|[FIN10](https://attack.mitre.org/groups/G0051) has moved laterally using the Local Administrator account.(Citation: FireEye FIN10 June 2017)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[FIN10](https://attack.mitre.org/groups/G0051) has used stolen credentials to connect remotely to victim networks using VPNs protected with only a single factor.(Citation: FireEye FIN10 June 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[FIN10](https://attack.mitre.org/groups/G0051) has used batch scripts and scheduled tasks to delete critical system files.(Citation: FireEye FIN10 June 2017)|
|mitre-attack|enterprise-attack|Windows|T1021.001|Remote Desktop Protocol|[FIN10](https://attack.mitre.org/groups/G0051) has used RDP to move laterally to systems in the victim environment.(Citation: FireEye FIN10 June 2017)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[FIN10](https://attack.mitre.org/groups/G0051) uses PowerShell for execution as well as PowerShell Empire to establish persistence.(Citation: FireEye FIN10 June 2017)(Citation: Github PowerShell Empire)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1570|Lateral Tool Transfer|[FIN10](https://attack.mitre.org/groups/G0051) has deployed Meterpreter stagers and SplinterRAT instances in the victim network after moving laterally.(Citation: FireEye FIN10 June 2017)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[FIN10](https://attack.mitre.org/groups/G0051) has established persistence by using S4U tasks as well as the Scheduled Task option in PowerShell Empire.(Citation: FireEye FIN10 June 2017)(Citation: Github PowerShell Empire)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[FIN10](https://attack.mitre.org/groups/G0051) has used Meterpreter to enumerate users on remote systems.(Citation: FireEye FIN10 June 2017)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[FIN10](https://attack.mitre.org/groups/G0051) has established persistence by using the Registry option in PowerShell Empire to add a Run key.(Citation: FireEye FIN10 June 2017)(Citation: Github PowerShell Empire)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[FIN10](https://attack.mitre.org/groups/G0051) has executed malicious .bat files containing PowerShell commands.(Citation: FireEye FIN10 June 2017)|
