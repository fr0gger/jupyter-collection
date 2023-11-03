# Silence - G0091

**Created**: 2019-05-24T17:57:36.491Z

**Modified**: 2023-03-22T05:34:46.346Z

**Contributors**: Oleg Skulkin, Group-IB

## Aliases

Silence,Whisper Spider

## Description

[Silence](https://attack.mitre.org/groups/G0091) is a financially motivated threat actor targeting financial institutions in different countries. The group was first seen in June 2016. Their main targets reside in Russia, Ukraine, Belarus, Azerbaijan, Poland and Kazakhstan. They compromised various banking systems, including the Russian Central Bank's Automated Workstation Client, ATMs, and card processing.(Citation: Cyber Forensicator Silence Jan 2019)(Citation: SecureList Silence Nov 2017) 

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Silence](https://attack.mitre.org/groups/G0091) has obtained and modified versions of publicly-available tools like [Empire](https://attack.mitre.org/software/S0363) and [PsExec](https://attack.mitre.org/software/S0029).(Citation: Group IB Silence Aug 2019) (Citation: SecureList Silence Nov 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1571|Non-Standard Port|[Silence](https://attack.mitre.org/groups/G0091) has used port 444 when sending data about the system from the client to the server.(Citation: Group IB Silence Sept 2018)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1090.002|External Proxy|[Silence](https://attack.mitre.org/groups/G0091) has used ProxyBot, which allows the attacker to redirect traffic from the current node to the backconnect server via Sock4\Socks5.(Citation: Group IB Silence Sept 2018)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1072|Software Deployment Tools|[Silence](https://attack.mitre.org/groups/G0091) has used RAdmin, a remote software tool used to remotely control workstations and ATMs.(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1055|Process Injection|[Silence](https://attack.mitre.org/groups/G0091) has injected a DLL library containing a Trojan into the fwmain32.exe process.(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Silence](https://attack.mitre.org/groups/G0091) has used <code>HKCU\Software\Microsoft\Windows\CurrentVersion\Run</code>, <code>HKLM\Software\Microsoft\Windows\CurrentVersion\Run</code>, and the Startup folder to establish persistence.(Citation: Group IB Silence Sept 2018)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Silence](https://attack.mitre.org/groups/G0091) has downloaded additional modules and malware to victim’s machines.(Citation: Group IB Silence Sept 2018)	|
|mitre-attack|enterprise-attack|Windows|T1021.001|Remote Desktop Protocol|[Silence](https://attack.mitre.org/groups/G0091) has used RDP for lateral movement.(Citation: Group IB Silence Sept 2018)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[Silence](https://attack.mitre.org/groups/G0091) has used Nmap to scan the corporate network, build a network topology, and identify vulnerable hosts.(Citation: Group IB Silence Sept 2018)	|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[Silence](https://attack.mitre.org/groups/G0091) has used the Farse6.1 utility (based on [Mimikatz](https://attack.mitre.org/software/S0002)) to extract credentials from lsass.exe.(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Windows|T1112|Modify Registry|[Silence](https://attack.mitre.org/groups/G0091) can create, delete, or modify a specified Registry key or value.(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Silence](https://attack.mitre.org/groups/G0091) has named its backdoor "WINWORD.exe".(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[Silence](https://attack.mitre.org/groups/G0091) has used compromised credentials to log on to other systems and escalate privileges.(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|macOS,Windows|T1553.002|Code Signing|[Silence](https://attack.mitre.org/groups/G0091) has used a valid certificate to sign their primary loader Silence.Downloader (aka TrueBot).(Citation: Group IB Silence Aug 2019)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Silence](https://attack.mitre.org/groups/G0091) has used PowerShell to download and execute payloads.(Citation: Cyber Forensicator Silence Jan 2019)(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.007|JavaScript|[Silence](https://attack.mitre.org/groups/G0091) has used JS scripts.(Citation: Cyber Forensicator Silence Jan 2019)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Silence](https://attack.mitre.org/groups/G0091) has sent emails with malicious DOCX, CHM, LNK and ZIP attachments. (Citation: Cyber Forensicator Silence Jan 2019)(Citation: SecureList Silence Nov 2017)(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[Silence](https://attack.mitre.org/groups/G0091) has used scheduled tasks to stage its operation.(Citation: Cyber Forensicator Silence Jan 2019)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[Silence](https://attack.mitre.org/groups/G0091) has used VBS scripts.(Citation: Cyber Forensicator Silence Jan 2019)|
|mitre-attack|enterprise-attack|Windows|T1569.002|Service Execution|[Silence](https://attack.mitre.org/groups/G0091) has used [Winexe](https://attack.mitre.org/software/S0191) to install a service on the remote system.(Citation: SecureList Silence Nov 2017)(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Silence](https://attack.mitre.org/groups/G0091) has used Windows command-line to run commands.(Citation: Cyber Forensicator Silence Jan 2019)(Citation: SecureList Silence Nov 2017)(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Silence](https://attack.mitre.org/groups/G0091) attempts to get users to launch malicious attachments delivered via spearphishing emails.(Citation: Cyber Forensicator Silence Jan 2019)(Citation: SecureList Silence Nov 2017)(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Windows|T1218.001|Compiled HTML File|[Silence](https://attack.mitre.org/groups/G0091) has weaponized CHM files in their phishing campaigns.(Citation: Cyber Forensicator Silence Jan 2019)(Citation: SecureList Silence Nov 2017)(Citation: Group IB Silence Aug 2019)(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1106|Native API|[Silence](https://attack.mitre.org/groups/G0091) has leveraged the Windows API, including using CreateProcess() or ShellExecute(), to perform a variety of tasks.(Citation: SecureList Silence Nov 2017)(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[Silence](https://attack.mitre.org/groups/G0091) has used environment variable string substitution for obfuscation.(Citation: Cyber Forensicator Silence Jan 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[Silence](https://attack.mitre.org/groups/G0091) has deleted artifacts, including scheduled tasks, communicates files from the C2 and other logs.(Citation: Cyber Forensicator Silence Jan 2019)(Citation: Group IB Silence Sept 2018)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1113|Screen Capture|[Silence](https://attack.mitre.org/groups/G0091) can capture victim screen activity.(Citation: SecureList Silence Nov 2017)(Citation: Group IB Silence Sept 2018)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1125|Video Capture|[Silence](https://attack.mitre.org/groups/G0091) has been observed making videos of victims to observe bank employees day to day activities.(Citation: SecureList Silence Nov 2017)(Citation: Group IB Silence Sept 2018)|
