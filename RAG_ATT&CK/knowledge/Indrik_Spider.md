# Indrik Spider - G0119

**Created**: 2021-01-06T17:46:35.134Z

**Modified**: 2022-09-15T19:49:18.799Z

**Contributors**: 

## Aliases

Indrik Spider,Evil Corp

## Description

[Indrik Spider](https://attack.mitre.org/groups/G0119) is a Russia-based cybercriminal group that has been active since at least 2014. [Indrik Spider](https://attack.mitre.org/groups/G0119) initially started with the [Dridex](https://attack.mitre.org/software/S0384) banking Trojan, and then by 2017 they began running ransomware operations using [BitPaymer](https://attack.mitre.org/software/S0570), [WastedLocker](https://attack.mitre.org/software/S0612), and Hades ransomware.(Citation: Crowdstrike Indrik November 2018)(Citation: Crowdstrike EvilCorp March 2021)(Citation: Treasury EvilCorp Dec 2019)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1074.001|Local Data Staging|[Indrik Spider](https://attack.mitre.org/groups/G0119) has stored collected date in a .tmp file.(Citation: Symantec WastedLocker June 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Indrik Spider](https://attack.mitre.org/groups/G0119) has attempted to get users to click on a malicious zipped file.(Citation: Symantec WastedLocker June 2020) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[Indrik Spider](https://attack.mitre.org/groups/G0119) has used PowerView to enumerate all Windows Server, Windows Server 2003, and Windows 7 instances in the Active Directory database.(Citation: Symantec WastedLocker June 2020)|
|mitre-attack|enterprise-attack|Windows|T1070.001|Clear Windows Event Logs|[Indrik Spider](https://attack.mitre.org/groups/G0119) has used [Cobalt Strike](https://attack.mitre.org/software/S0154) to empty log files.(Citation: Symantec WastedLocker June 2020)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1489|Service Stop|[Indrik Spider](https://attack.mitre.org/groups/G0119) has used [PsExec](https://attack.mitre.org/software/S0029) to stop services prior to the execution of ransomware.(Citation: Symantec WastedLocker June 2020)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.007|JavaScript|[Indrik Spider](https://attack.mitre.org/groups/G0119) has used malicious JavaScript files for several components of their attack.(Citation: Symantec WastedLocker June 2020)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[Indrik Spider](https://attack.mitre.org/groups/G0119) used [Cobalt Strike](https://attack.mitre.org/software/S0154) to carry out credential dumping using ProcDump.(Citation: Symantec WastedLocker June 2020)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,IaaS,Linux,macOS,Google Workspace,Network|T1136|Create Account|[Indrik Spider](https://attack.mitre.org/groups/G0119) used <code>wmic.exe</code> to add a new user to the system.(Citation: Symantec WastedLocker June 2020)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Containers,IaaS|T1562.001|Disable or Modify Tools|[Indrik Spider](https://attack.mitre.org/groups/G0119) used [PsExec](https://attack.mitre.org/software/S0029) to leverage Windows Defender to disable scanning of all downloaded files and to restrict real-time monitoring.(Citation: Symantec WastedLocker June 2020)|
|mitre-attack|enterprise-attack|Windows|T1047|Windows Management Instrumentation|[Indrik Spider](https://attack.mitre.org/groups/G0119) has used WMIC to execute commands on remote computers.(Citation: Symantec WastedLocker June 2020) |
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1007|System Service Discovery|[Indrik Spider](https://attack.mitre.org/groups/G0119) has used the win32_service WMI class to retrieve a list of services from the system.(Citation: Symantec WastedLocker June 2020) |
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Indrik Spider](https://attack.mitre.org/groups/G0119) has used batch scripts on victim's machines.(Citation: Crowdstrike Indrik November 2018) |
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Indrik Spider](https://attack.mitre.org/groups/G0119) has used PowerShell [Empire](https://attack.mitre.org/software/S0363) for execution of malware.(Citation: Crowdstrike Indrik November 2018)(Citation: Symantec WastedLocker June 2020) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1078.002|Domain Accounts|[Indrik Spider](https://attack.mitre.org/groups/G0119) has collected credentials from infected systems, including domain accounts.(Citation: Crowdstrike Indrik November 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Indrik Spider](https://attack.mitre.org/groups/G0119) has downloaded additional scripts, malware, and tools onto a compromised host.(Citation: Crowdstrike Indrik November 2018)(Citation: Symantec WastedLocker June 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Indrik Spider](https://attack.mitre.org/groups/G0119) used fake updates for FlashPlayer plugin and Google Chrome as initial infection vectors.(Citation: Crowdstrike Indrik November 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,IaaS|T1486|Data Encrypted for Impact|[Indrik Spider](https://attack.mitre.org/groups/G0119) has encrypted domain-controlled systems using [BitPaymer](https://attack.mitre.org/software/S0570).(Citation: Crowdstrike Indrik November 2018)|
|mitre-attack|enterprise-attack|Windows|T1484.001|Group Policy Modification|[Indrik Spider](https://attack.mitre.org/groups/G0119) has used Group Policy Objects to deploy batch scripts.(Citation: Crowdstrike Indrik November 2018)|
|mitre-attack|enterprise-attack|PRE|T1584.004|Server|[Indrik Spider](https://attack.mitre.org/groups/G0119) has served fake updates via legitimate websites that have been compromised.(Citation: Crowdstrike Indrik November 2018)	|
