# Carbanak - G0008

**Created**: 2017-05-31T21:31:49.021Z

**Modified**: 2021-10-18T21:02:30.899Z

**Contributors**: Anastasios Pingios

## Aliases

Carbanak,Anunak

## Description

[Carbanak](https://attack.mitre.org/groups/G0008) is a cybercriminal group that has used [Carbanak](https://attack.mitre.org/software/S0030) malware to target financial institutions since at least 2013. [Carbanak](https://attack.mitre.org/groups/G0008) may be linked to groups tracked separately as [Cobalt Group](https://attack.mitre.org/groups/G0080) and [FIN7](https://attack.mitre.org/groups/G0046) that have also used [Carbanak](https://attack.mitre.org/software/S0030) malware.(Citation: Kaspersky Carbanak)(Citation: FireEye FIN7 April 2017)(Citation: Europol Cobalt Mar 2018)(Citation: Secureworks GOLD NIAGARA Threat Profile)(Citation: Secureworks GOLD KINGSWOOD Threat Profile)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Carbanak](https://attack.mitre.org/groups/G0008) has obtained and used open-source tools such as [PsExec](https://attack.mitre.org/software/S0029) and [Mimikatz](https://attack.mitre.org/software/S0002).(Citation: Kaspersky Carbanak)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1036.004|Masquerade Task or Service|[Carbanak](https://attack.mitre.org/groups/G0008) has copied legitimate service names to use for malicious services.(Citation: Kaspersky Carbanak)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1219|Remote Access Software|[Carbanak](https://attack.mitre.org/groups/G0008) used legitimate programs such as AmmyyAdmin and Team Viewer for remote interactive C2 to target systems.(Citation: Group-IB Anunak)|
|mitre-attack|enterprise-attack|Windows|T1218.011|Rundll32|[Carbanak](https://attack.mitre.org/groups/G0008) installs VNC server software that executes through rundll32.(Citation: Kaspersky Carbanak)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1562.004|Disable or Modify System Firewall|[Carbanak](https://attack.mitre.org/groups/G0008) may use [netsh](https://attack.mitre.org/software/S0108) to add local firewall rule exceptions.(Citation: Group-IB Anunak)|
|mitre-attack|enterprise-attack|Windows|T1543.003|Windows Service|[Carbanak](https://attack.mitre.org/groups/G0008) malware installs itself as a service to provide persistence and SYSTEM privileges.(Citation: Kaspersky Carbanak)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102.002|Bidirectional Communication|[Carbanak](https://attack.mitre.org/groups/G0008) has used a VBScript named "ggldr" that uses Google Apps Script, Sheets, and Forms services for C2.(Citation: Forcepoint Carbanak Google C2)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Carbanak](https://attack.mitre.org/groups/G0008) has named malware "svchost.exe," which is the name of the Windows shared service host program.(Citation: Kaspersky Carbanak)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[Carbanak](https://attack.mitre.org/groups/G0008) actors used legitimate credentials of banking employees to perform operations that sent them millions of dollars.(Citation: Kaspersky Carbanak)|
