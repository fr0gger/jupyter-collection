# Naikon - G0019

**Created**: 2017-05-31T21:31:54.232Z

**Modified**: 2021-08-19T18:23:23.507Z

**Contributors**: Kyaw Pyiyt Htet, @KyawPyiytHtet

## Aliases

Naikon

## Description

[Naikon](https://attack.mitre.org/groups/G0019) is assessed to be a state-sponsored cyber espionage group attributed to the Chinese People’s Liberation Army’s (PLA) Chengdu Military Region Second Technical Reconnaissance Bureau (Military Unit Cover Designator 78020).(Citation: CameraShy) Active since at least 2010, [Naikon](https://attack.mitre.org/groups/G0019) has primarily conducted operations against government, military, and civil organizations in Southeast Asia, as well as against international bodies such as the United Nations Development Programme (UNDP) and the Association of Southeast Asian Nations (ASEAN).(Citation: CameraShy)(Citation: Baumgartner Naikon 2015) 

While [Naikon](https://attack.mitre.org/groups/G0019) shares some characteristics with [APT30](https://attack.mitre.org/groups/G0013), the two groups do not appear to be exact matches.(Citation: Baumgartner Golovkin Naikon 2015)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1036.004|Masquerade Task or Service|[Naikon](https://attack.mitre.org/groups/G0019) renamed a malicious service <code>taskmgr</code> to appear to be a legitimate version of Task Manager.(Citation: Bitdefender Naikon April 2021)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Naikon](https://attack.mitre.org/groups/G0019) has modified a victim's Windows Run registry to establish persistence.(Citation: Bitdefender Naikon April 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Naikon](https://attack.mitre.org/groups/G0019) has disguised malicious programs as Google Chrome, Adobe, and VMware executables.(Citation: Bitdefender Naikon April 2021)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers,Network|T1046|Network Service Discovery|[Naikon](https://attack.mitre.org/groups/G0019) has used the LadonGo scanner to scan target networks.(Citation: Bitdefender Naikon April 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[Naikon](https://attack.mitre.org/groups/G0019) has used a netbios scanner for remote machine identification.(Citation: Bitdefender Naikon April 2021)|
|mitre-attack|enterprise-attack|Windows|T1047|Windows Management Instrumentation|[Naikon](https://attack.mitre.org/groups/G0019) has used WMIC.exe for lateral movement.(Citation: Bitdefender Naikon April 2021)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[Naikon](https://attack.mitre.org/groups/G0019) has used schtasks.exe for lateral movement in compromised networks.(Citation: Bitdefender Naikon April 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1078.002|Domain Accounts|[Naikon](https://attack.mitre.org/groups/G0019) has used administrator credentials for lateral movement in compromised networks.(Citation: Bitdefender Naikon April 2021)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Naikon](https://attack.mitre.org/groups/G0019) has used malicious e-mail attachments to deliver malware.(Citation: CheckPoint Naikon May 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Naikon](https://attack.mitre.org/groups/G0019) has convinced victims to open malicious attachments to execute malware.(Citation: CheckPoint Naikon May 2020)|
|mitre-attack|enterprise-attack|Windows,Office 365|T1137.006|Add-ins|[Naikon](https://attack.mitre.org/groups/G0019) has used the RoyalRoad exploit builder to drop a second stage loader, intel.wll, into the Word Startup folder on the compromised host.(Citation: CheckPoint Naikon May 2020)|
|mitre-attack|enterprise-attack|Windows|T1574.002|DLL Side-Loading|[Naikon](https://attack.mitre.org/groups/G0019) has used DLL side-loading to load malicious DLL's into legitimate executables.(Citation: CheckPoint Naikon May 2020)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518.001|Security Software Discovery|[Naikon](https://attack.mitre.org/groups/G0019) uses commands such as <code>netsh advfirewall firewall</code> to discover local firewall settings.(Citation: Baumgartner Naikon 2015)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[Naikon](https://attack.mitre.org/groups/G0019) uses commands such as <code>netsh interface show</code> to discover network interface settings.(Citation: Baumgartner Naikon 2015)|
