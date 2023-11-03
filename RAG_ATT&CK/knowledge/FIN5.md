# FIN5 - G0053

**Created**: 2018-01-16T16:13:52.465Z

**Modified**: 2021-10-16T19:48:37.809Z

**Contributors**: Walker Johnson

## Aliases

FIN5

## Description

[FIN5](https://attack.mitre.org/groups/G0053) is a financially motivated threat group that has targeted personally identifiable information and payment card information. The group has been active since at least 2008 and has targeted the restaurant, gaming, and hotel industries. The group is made up of actors who likely speak Russian. (Citation: FireEye Respond Webinar July 2017) (Citation: Mandiant FIN5 GrrCON Oct 2016) (Citation: DarkReading FireEye FIN5 Oct 2015)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[FIN5](https://attack.mitre.org/groups/G0053) has obtained and used a customized version of [PsExec](https://attack.mitre.org/software/S0029), as well as use other tools such as [pwdump](https://attack.mitre.org/software/S0006), [SDelete](https://attack.mitre.org/software/S0195), and [Windows Credential Editor](https://attack.mitre.org/software/S0005).(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[FIN5](https://attack.mitre.org/groups/G0053) has used the open source tool Essential NetTools to map the network and build a list of targets.(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,Containers,macOS|T1133|External Remote Services|[FIN5](https://attack.mitre.org/groups/G0053) has used legitimate VPN, Citrix, or VNC credentials to maintain access to a victim environment.(Citation: FireEye Respond Webinar July 2017)(Citation: DarkReading FireEye FIN5 Oct 2015)(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Windows|T1070.001|Clear Windows Event Logs|[FIN5](https://attack.mitre.org/groups/G0053) has cleared event logs from victims.(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1090.002|External Proxy|[FIN5](https://attack.mitre.org/groups/G0053) maintains access to victim environments by using [FLIPSIDE](https://attack.mitre.org/software/S0173) to create a proxy for a backup RDP tunnel.(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[FIN5](https://attack.mitre.org/groups/G0053) uses [SDelete](https://attack.mitre.org/software/S0195) to clean up the environment and attempt to prevent detection.(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[FIN5](https://attack.mitre.org/groups/G0053) has used legitimate VPN, RDP, Citrix, or VNC credentials to maintain access to a victim environment.(Citation: FireEye Respond Webinar July 2017)(Citation: DarkReading FireEye FIN5 Oct 2015)(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1074.001|Local Data Staging|[FIN5](https://attack.mitre.org/groups/G0053) scripts save memory dump data into a specific directory on hosts in the victim environment.(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1110|Brute Force|[FIN5](https://attack.mitre.org/groups/G0053) has has used the tool GET2 Penetrator to look for remote login and hard-coded credentials.(Citation: DarkReading FireEye FIN5 Oct 2015)(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,IaaS,SaaS|T1119|Automated Collection|[FIN5](https://attack.mitre.org/groups/G0053) scans processes on all victim systems in the environment and uses automated scripts to pull back the results.(Citation: Mandiant FIN5 GrrCON Oct 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network,Office 365,Azure AD,IaaS,Google Workspace|T1059|Command and Scripting Interpreter|[FIN5](https://attack.mitre.org/groups/G0053) scans processes on all victim systems in the environment and uses automated scripts to pull back the results.(Citation: Mandiant FIN5 GrrCON Oct 2016)|
