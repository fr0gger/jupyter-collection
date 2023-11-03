# TEMP.Veles - G0088

**Created**: 2019-04-16T15:14:38.533Z

**Modified**: 2022-11-30T22:46:40.135Z

**Contributors**: Dragos  Threat  Intelligence

## Aliases

TEMP.Veles,XENOTIME

## Description

[TEMP.Veles](https://attack.mitre.org/groups/G0088) is a Russia-based threat group that has targeted critical infrastructure. The group has been observed utilizing [TRITON](https://attack.mitre.org/software/S0609), a malware framework designed to manipulate industrial safety systems.(Citation: FireEye TRITON 2019)(Citation: FireEye TEMP.Veles 2018)(Citation: FireEye TEMP.Veles JSON April 2019)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|ics-attack,enterprise-attack|PRE|T1588.002|Tool|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has obtained and used tools such as [Mimikatz](https://attack.mitre.org/software/S0002) and [PsExec](https://attack.mitre.org/software/S0029).(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|PRE|T1583.003|Virtual Private Server|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has used Virtual Private Server (VPS) infrastructure.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Linux,macOS,Windows|T1571|Non-Standard Port|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has used port-protocol mismatches on ports such as 443, 4444, 8531, and 50501 during C2.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Linux,macOS,Windows|T1027.005|Indicator Removal from Tools|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has modified files based on the open-source project cryptcat in an apparent attempt to decrease AV detection rates.(Citation: FireEye TEMP.Veles 2018)|
|mitre-attack|ics-attack,enterprise-attack|Windows|T1059.001|PowerShell|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has used a publicly-available PowerShell-based tool, WMImplant.(Citation: FireEye TEMP.Veles 2018) The group has also used PowerShell to perform [Timestomp](https://attack.mitre.org/techniques/T1070/006)ing.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Linux,Windows,macOS,Network|T1505.003|Web Shell|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has planted Web shells on Outlook Exchange servers.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Windows,Linux,Containers,macOS|T1133|External Remote Services|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has used a VPN to persist in the victim environment.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Windows|T1021.001|Remote Desktop Protocol|[TEMP.Veles](https://attack.mitre.org/groups/G0088) utilized RDP throughout an operation.(Citation: FireEye TRITON 2019)	|
|mitre-attack|ics-attack,enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has used compromised VPN accounts.(Citation: FireEye TRITON 2019)	|
|mitre-attack|ics-attack,enterprise-attack|Linux,macOS|T1021.004|SSH|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has relied on encrypted SSH-based tunnels to transfer tools and for remote command/program execution.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Linux,macOS,Windows|T1074.001|Local Data Staging|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has created staging folders in directories that were infrequently used by legitimate users or processes.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[TEMP.Veles](https://attack.mitre.org/groups/G0088) routinely deleted tools, logs, and other files after they were finished with them.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Linux,macOS,Windows|T1070.006|Timestomp|[TEMP.Veles](https://attack.mitre.org/groups/G0088) used timestomping to modify the $STANDARD_INFORMATION attribute on tools.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Windows|T1053.005|Scheduled Task|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has used scheduled task XML triggers.(Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Windows|T1546.012|Image File Execution Options Injection|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has modified and added entries within <code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options</code> to maintain persistence.(Citation: FireEye TRITON 2019)	
|
|mitre-attack|ics-attack,enterprise-attack|Windows|T1003.001|LSASS Memory|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has used [Mimikatz](https://attack.mitre.org/software/S0002) and a custom tool, SecHack, to harvest credentials. (Citation: FireEye TRITON 2019)|
|mitre-attack|ics-attack,enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[TEMP.Veles](https://attack.mitre.org/groups/G0088) has renamed files to look like legitimate files, such as Windows update files or Schneider Electric application files.(Citation: FireEye TRITON 2019)
|
|mitre-attack|ics-attack,enterprise-attack|Engineering Workstation,Human-Machine Interface,Control Server|T0886|Remote Services|[TEMP.Veles](https://attack.mitre.org/groups/G0088) utilized remote desktop protocol (RDP) jump boxes to move into the ICS environment. (Citation: Dragos December 2017)|
|mitre-attack|ics-attack,enterprise-attack|Control Server,Data Historian,Engineering Workstation,Field Controller/RTU/PLC/IED,Human-Machine Interface,Input/Output Server,Safety Instrumented System/Protection Relay|T0859|Valid Accounts|[TEMP.Veles](https://attack.mitre.org/groups/G0088) used valid credentials when laterally moving through RDP jump boxes into the ICS environment. (Citation: Dragos December 2017)|
|mitre-attack|ics-attack,enterprise-attack|Control Server,Data Historian,Field Controller/RTU/PLC/IED,Human-Machine Interface,Input/Output Server,Safety Instrumented System/Protection Relay|T0862|Supply Chain Compromise|[TEMP.Veles](https://attack.mitre.org/groups/G0088) targeted several ICS vendors and manufacturers. (Citation: Dragos Threat Intelligence August 2019)|
|mitre-attack|ics-attack,enterprise-attack|None|T0817|Drive-by Compromise|[TEMP.Veles](https://attack.mitre.org/groups/G0088) utilizes watering hole websites to target industrial employees. (Citation: Chris Bing May 2018)|
