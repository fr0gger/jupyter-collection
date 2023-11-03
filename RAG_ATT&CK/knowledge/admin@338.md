# admin@338 - G0018

**Created**: 2017-05-31T21:31:53.579Z

**Modified**: 2020-03-18T19:54:59.120Z

**Contributors**: Tatsuya Daitoku, Cyber Defense Institute, Inc.

## Aliases

admin@338

## Description

[admin@338](https://attack.mitre.org/groups/G0018) is a China-based cyber threat group. It has previously used newsworthy events as lures to deliver malware and has primarily targeted organizations involved in financial, economic, and trade policy, typically using publicly available RATs such as [PoisonIvy](https://attack.mitre.org/software/S0012), as well as some non-public backdoors. (Citation: FireEye admin@338)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[admin@338](https://attack.mitre.org/groups/G0018) has sent emails with malicious Microsoft Office documents attached.(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[admin@338](https://attack.mitre.org/groups/G0018) has attempted to get victims to launch malicious Microsoft Word attachments delivered via spearphishing emails.(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[admin@338](https://attack.mitre.org/groups/G0018) has exploited client software vulnerabilities for execution, such as Microsoft Word CVE-2012-0158.(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1087.001|Local Account|[admin@338](https://attack.mitre.org/groups/G0018) actors used the following commands following exploitation of a machine with [LOWBALL](https://attack.mitre.org/software/S0042) malware to enumerate user accounts: <code>net user >> %temp%\download</code> <code>net user /domain >> %temp%\download</code>(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[admin@338](https://attack.mitre.org/groups/G0018) actors used the following command to rename one of their tools to a benign file name: <code>ren "%temp%\upload" audiodg.exe</code>(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1069.001|Local Groups|[admin@338](https://attack.mitre.org/groups/G0018) actors used the following command following exploitation of a machine with [LOWBALL](https://attack.mitre.org/software/S0042) malware to list local groups: <code>net localgroup administrator >> %temp%\download</code>(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[admin@338](https://attack.mitre.org/groups/G0018) actors used the following commands after exploiting a machine with [LOWBALL](https://attack.mitre.org/software/S0042) malware to obtain information about the OS: <code>ver >> %temp%\download</code> <code>systeminfo >> %temp%\download</code>(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[admin@338](https://attack.mitre.org/groups/G0018) actors used the following command after exploiting a machine with [LOWBALL](https://attack.mitre.org/software/S0042) malware to acquire information about local networks: <code>ipconfig /all >> %temp%\download</code>(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1007|System Service Discovery|[admin@338](https://attack.mitre.org/groups/G0018) actors used the following command following exploitation of a machine with [LOWBALL](https://attack.mitre.org/software/S0042) malware to obtain information about services: <code>net start >> %temp%\download</code>(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1049|System Network Connections Discovery|[admin@338](https://attack.mitre.org/groups/G0018) actors used the following command following exploitation of a machine with [LOWBALL](https://attack.mitre.org/software/S0042) malware to display network connections: <code>netstat -ano >> %temp%\download</code>(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[admin@338](https://attack.mitre.org/groups/G0018) actors used the following commands after exploiting a machine with [LOWBALL](https://attack.mitre.org/software/S0042) malware to obtain information about files and directories: <code>dir c:\ >> %temp%\download</code> <code>dir "c:\Documents and Settings" >> %temp%\download</code> <code>dir "c:\Program Files\" >> %temp%\download</code> <code>dir d:\ >> %temp%\download</code>(Citation: FireEye admin@338)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|Following exploitation with [LOWBALL](https://attack.mitre.org/software/S0042) malware, [admin@338](https://attack.mitre.org/groups/G0018) actors created a file containing a list of commands to be executed on the compromised computer.(Citation: FireEye admin@338)|
