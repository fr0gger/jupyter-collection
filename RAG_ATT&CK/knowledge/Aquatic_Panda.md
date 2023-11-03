# Aquatic Panda - G0143

**Created**: 2022-01-18T14:49:29.505Z

**Modified**: 2023-03-21T21:16:34.243Z

**Contributors**: NST Assure Research Team, NetSentries Technologies,Pooja Natarajan, NEC Corporation India,Hiroki Nagahama, NEC Corporation,Manikantan Srinivasan, NEC Corporation India

## Aliases

Aquatic Panda

## Description

[Aquatic Panda](https://attack.mitre.org/groups/G0143) is a suspected China-based threat group with a dual mission of intelligence collection and industrial espionage. Active since at least May 2020, [Aquatic Panda](https://attack.mitre.org/groups/G0143) has primarily targeted entities in the telecommunications, technology, and government sectors.(Citation: CrowdStrike AQUATIC PANDA December 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has acquired and used [Cobalt Strike](https://attack.mitre.org/software/S0154) in its operations.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|PRE|T1588.001|Malware|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has acquired and used [njRAT](https://attack.mitre.org/software/S0385) in its operations.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Windows|T1574.001|DLL Search Order Hijacking|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has used DLL search-order hijacking to load `exe`, `dll`, and `dat` files into memory.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has encoded PowerShell commands in Base64.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has used native OS commands to understand privilege levels and system details.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1007|System Service Discovery|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has attempted to discover services for third party EDR products.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has attempted and failed to run Bash commands on a Windows host by passing them to <code>cmd /C</code>.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560.001|Archive via Utility|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has used WinRAR to compress memory dumps prior to exfiltration.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has deleted malicious executables from compromised machines.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has attempted to harvest credentials through LSASS memory dumping.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has downloaded additional malware onto compromised hosts.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has downloaded additional scripts and executed Base64 encoded commands in PowerShell.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Containers,IaaS|T1562.001|Disable or Modify Tools|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has attempted to stop endpoint detection and response (EDR) tools on compromised systems.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|PRE|T1595.002|Vulnerability Scanning|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has used publicly accessible DNS logging services to identify servers vulnerable to Log4j (CVE 2021-44228).(Citation: CrowdStrike AQUATIC PANDA December 2021)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518.001|Security Software Discovery|[Aquatic Panda](https://attack.mitre.org/groups/G0143) has attempted to discover third party endpoint detection and response (EDR) tools on compromised systems.(Citation: CrowdStrike AQUATIC PANDA December 2021)|
