# APT18 - G0026

**Created**: 2017-05-31T21:31:57.733Z

**Modified**: 2020-03-30T18:46:16.853Z

**Contributors**: 

## Aliases

APT18,TG-0416,Dynamite Panda,Threat Group-0416

## Description

[APT18](https://attack.mitre.org/groups/G0026) is a threat group that has operated since at least 2009 and has targeted a range of industries, including technology, manufacturing, human rights groups, government, and medical. (Citation: Dell Lateral Movement)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.004|DNS|[APT18](https://attack.mitre.org/groups/G0026) uses DNS for C2 communications.(Citation: PaloAlto DNS Requests May 2016)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[APT18](https://attack.mitre.org/groups/G0026) establishes persistence via the <code>HKCU\Software\Microsoft\Windows\CurrentVersion\Run</code> key.(Citation: Anomali Evasive Maneuvers July 2015)(Citation: PaloAlto DNS Requests May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[APT18](https://attack.mitre.org/groups/G0026) obfuscates strings in the payload.(Citation: PaloAlto DNS Requests May 2016)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[APT18](https://attack.mitre.org/groups/G0026) uses cmd.exe to execute commands on the victim’s machine.(Citation: PaloAlto DNS Requests May 2016)(Citation: Anomali Evasive Maneuvers July 2015)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[APT18](https://attack.mitre.org/groups/G0026) can upload a file to the victim’s machine.(Citation: PaloAlto DNS Requests May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[APT18](https://attack.mitre.org/groups/G0026) can list files information for specific directories.(Citation: PaloAlto DNS Requests May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[APT18](https://attack.mitre.org/groups/G0026) uses HTTP for C2 communications.(Citation: PaloAlto DNS Requests May 2016)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[APT18](https://attack.mitre.org/groups/G0026) can collect system information from the victim’s machine.(Citation: PaloAlto DNS Requests May 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1053.002|At|[APT18](https://attack.mitre.org/groups/G0026) actors used the native [at](https://attack.mitre.org/software/S0110) Windows task scheduler tool to use scheduled tasks for execution on a victim network.(Citation: Dell Lateral Movement)|
|mitre-attack|enterprise-attack|Windows,Linux,Containers,macOS|T1133|External Remote Services|[APT18](https://attack.mitre.org/groups/G0026) actors leverage legitimate credentials to log into external remote services.(Citation: RSA2017 Detect and Respond Adair)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[APT18](https://attack.mitre.org/groups/G0026) actors leverage legitimate credentials to log into external remote services.(Citation: RSA2017 Detect and Respond Adair)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[APT18](https://attack.mitre.org/groups/G0026) actors deleted tools and batch files from victim systems.(Citation: Dell Lateral Movement)|
