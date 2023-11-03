# APT33 - G0064

**Created**: 2018-04-18T17:59:24.739Z

**Modified**: 2023-03-08T22:07:25.123Z

**Contributors**: Dragos  Threat  Intelligence

## Aliases

APT33,HOLMIUM,Elfin

## Description

[APT33](https://attack.mitre.org/groups/G0064) is a suspected Iranian threat group that has carried out operations since at least 2013. The group has targeted organizations across multiple industries in the United States, Saudi Arabia, and South Korea, with a particular interest in the aviation and energy sectors. (Citation: FireEye APT33 Sept 2017) (Citation: FireEye APT33 Webinar Sept 2017)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1588.002|Tool|[APT33](https://attack.mitre.org/groups/G0064) has obtained and leveraged publicly-available tools for early intrusion activities.(Citation: FireEye APT33 Guardrail)(Citation: Symantec Elfin Mar 2019)|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1546.003|Windows Management Instrumentation Event Subscription|[APT33](https://attack.mitre.org/groups/G0064) has attempted to use WMI event subscriptions to establish persistence on compromised hosts.(Citation: Microsoft Holmium June 2020)|
|mitre-attack|enterprise-attack,ics-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[APT33](https://attack.mitre.org/groups/G0064) has sent spearphishing e-mails with archive attachments.(Citation: Microsoft Holmium June 2020)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1204.002|Malicious File|[APT33](https://attack.mitre.org/groups/G0064) has used malicious e-mail attachments to lure victims into executing malware.(Citation: Microsoft Holmium June 2020)|
|mitre-attack|enterprise-attack,ics-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[APT33](https://attack.mitre.org/groups/G0064) has used VBScript to initiate the delivery of payloads.(Citation: Microsoft Holmium June 2020)|
|mitre-attack|enterprise-attack,ics-attack|Azure AD,Office 365,SaaS,IaaS,Google Workspace|T1078.004|Cloud Accounts|[APT33](https://attack.mitre.org/groups/G0064) has used compromised Office 365 accounts in tandem with [Ruler](https://attack.mitre.org/software/S0358) in an attempt to gain control of endpoints.(Citation: Microsoft Holmium June 2020)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1571|Non-Standard Port|[APT33](https://attack.mitre.org/groups/G0064) has used HTTP over TCP ports 808 and 880 for command and control.(Citation: Symantec Elfin Mar 2019)|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1552.006|Group Policy Preferences|[APT33](https://attack.mitre.org/groups/G0064) has used a variety of publicly available tools like Gpppassword to gather credentials.(Citation: Symantec Elfin Mar 2019)(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1555|Credentials from Password Stores|[APT33](https://attack.mitre.org/groups/G0064) has used a variety of publicly available tools like [LaZagne](https://attack.mitre.org/software/S0349) to gather credentials.(Citation: Symantec Elfin Mar 2019)(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[APT33](https://attack.mitre.org/groups/G0064) has used a variety of publicly available tools like [LaZagne](https://attack.mitre.org/software/S0349) to gather credentials.(Citation: Symantec Elfin Mar 2019)(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1003.005|Cached Domain Credentials|[APT33](https://attack.mitre.org/groups/G0064) has used a variety of publicly available tools like [LaZagne](https://attack.mitre.org/software/S0349) to gather credentials.(Citation: Symantec Elfin Mar 2019)(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1003.004|LSA Secrets|[APT33](https://attack.mitre.org/groups/G0064) has used a variety of publicly available tools like [LaZagne](https://attack.mitre.org/software/S0349) to gather credentials.(Citation: Symantec Elfin Mar 2019)(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Windows,IaaS,Linux,macOS,Containers|T1552.001|Credentials In Files|[APT33](https://attack.mitre.org/groups/G0064) has used a variety of publicly available tools like [LaZagne](https://attack.mitre.org/software/S0349) to gather credentials.(Citation: Symantec Elfin Mar 2019)(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers|T1110.003|Password Spraying|[APT33](https://attack.mitre.org/groups/G0064) has used password spraying to gain access to target systems.(Citation: FireEye APT33 Guardrail)(Citation: Microsoft Holmium June 2020)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows,Containers|T1068|Exploitation for Privilege Escalation|[APT33](https://attack.mitre.org/groups/G0064) has used a publicly available exploit for CVE-2017-0213 to escalate privileges on a local system.(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Linux,Windows,macOS|T1573.001|Symmetric Cryptography|[APT33](https://attack.mitre.org/groups/G0064) has used AES for encryption of command and control traffic.(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[APT33](https://attack.mitre.org/groups/G0064) has used base64 to encode payloads.(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1132.001|Standard Encoding|[APT33](https://attack.mitre.org/groups/G0064) has used base64 to encode command and control traffic.(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1053.005|Scheduled Task|[APT33](https://attack.mitre.org/groups/G0064) has created a scheduled task to execute a .vbe file multiple times a day.(Citation: Symantec Elfin Mar 2019)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows,Network|T1048.003|Exfiltration Over Unencrypted Non-C2 Protocol|[APT33](https://attack.mitre.org/groups/G0064) has used FTP to exfiltrate files (separately from the C2 channel).(Citation: Symantec Elfin Mar 2019)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[APT33](https://attack.mitre.org/groups/G0064) has used HTTP for command and control.(Citation: Symantec Elfin Mar 2019)|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[APT33](https://attack.mitre.org/groups/G0064) has deployed a tool known as [DarkComet](https://attack.mitre.org/software/S0334) to the Startup folder of a victim, and used Registry run keys to gain persistence.(Citation: Symantec Elfin Mar 2019)(Citation: Microsoft Holmium June 2020)|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1059.001|PowerShell|[APT33](https://attack.mitre.org/groups/G0064) has utilized PowerShell to download files from the C2 server and run various scripts. (Citation: Symantec Elfin Mar 2019)(Citation: Microsoft Holmium June 2020)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[APT33](https://attack.mitre.org/groups/G0064) has downloaded additional files and programs from its C2 server.(Citation: Symantec Elfin Mar 2019)(Citation: Microsoft Holmium June 2020)	
|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1560.001|Archive via Utility|[APT33](https://attack.mitre.org/groups/G0064) has used WinRAR to compress data prior to exfil.(Citation: Symantec Elfin Mar 2019)	
|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1003.001|LSASS Memory|[APT33](https://attack.mitre.org/groups/G0064) has used a variety of publicly available tools like [LaZagne](https://attack.mitre.org/software/S0349), [Mimikatz](https://attack.mitre.org/software/S0002), and ProcDump to dump credentials.(Citation: Symantec Elfin Mar 2019)(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows,Network,IaaS|T1040|Network Sniffing|[APT33](https://attack.mitre.org/groups/G0064) has used SniffPass to collect credentials by sniffing network traffic.(Citation: Symantec Elfin Mar 2019)|
|mitre-attack|enterprise-attack,ics-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[APT33](https://attack.mitre.org/groups/G0064) has attempted to exploit a known vulnerability in WinRAR (CVE-2018-20250), and attempted to gain remote code execution via a security bypass vulnerability (CVE-2017-11774).(Citation: Symantec Elfin Mar 2019)(Citation: Microsoft Holmium June 2020)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[APT33](https://attack.mitre.org/groups/G0064) has lured users to click links to malicious HTML applications delivered via spearphishing emails.(Citation: FireEye APT33 Sept 2017)(Citation: Symantec Elfin Mar 2019)|
|mitre-attack|enterprise-attack,ics-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[APT33](https://attack.mitre.org/groups/G0064) has used valid accounts for initial access and privilege escalation.(Citation: FireEye APT33 Webinar Sept 2017)(Citation: FireEye APT33 Guardrail)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[APT33](https://attack.mitre.org/groups/G0064) has sent spearphishing emails containing links to .hta files.(Citation: FireEye APT33 Sept 2017)(Citation: Symantec Elfin Mar 2019)|
|mitre-attack|enterprise-attack,ics-attack|Human-Machine Interface|T0852|Screen Capture|[APT33](https://attack.mitre.org/groups/G0064) utilize backdoors capable of capturing screenshots once installed on a system. (Citation: Jacqueline O'Leary et al. September 2017)(Citation: Junnosuke Yagi March 2017)|
|mitre-attack|enterprise-attack,ics-attack|Engineering Workstation|T0853|Scripting|[APT33](https://attack.mitre.org/groups/G0064) utilized PowerShell scripts to establish command and control and install files for execution. (Citation: Symantec March 2019) (Citation: Dragos)|
|mitre-attack|enterprise-attack,ics-attack|Engineering Workstation,Human-Machine Interface,Control Server,Data Historian|T0865|Spearphishing Attachment|[APT33](https://attack.mitre.org/groups/G0064) sent spear phishing emails containing links to HTML application files, which were embedded with malicious code. (Citation: Jacqueline O'Leary et al. September 2017) [APT33](https://attack.mitre.org/groups/G0064) has conducted targeted spear phishing campaigns against U.S. government agencies and private sector companies. (Citation: Andy Greenburg June 2019)|
