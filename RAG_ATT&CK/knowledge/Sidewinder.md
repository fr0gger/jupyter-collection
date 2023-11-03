# Sidewinder - G0121

**Created**: 2021-01-27T15:57:11.183Z

**Modified**: 2023-03-22T05:31:54.382Z

**Contributors**: Lacework Labs,Daniyal Naeem, BT Security

## Aliases

Sidewinder,T-APT-04,Rattlesnake

## Description

[Sidewinder](https://attack.mitre.org/groups/G0121) is a suspected Indian threat actor group that has been active since at least 2012. They have been observed targeting government, military, and business entities throughout Asia, primarily focusing on Pakistan, China, Nepal, and Afghanistan.(Citation: ATT Sidewinder January 2021)(Citation: Securelist APT Trends April 2018)(Citation: Cyble Sidewinder September 2020)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[Sidewinder](https://attack.mitre.org/groups/G0121) has used base64 encoding for scripts.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder APT April 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Sidewinder](https://attack.mitre.org/groups/G0121) has named malicious files <code>rekeywiz.exe</code> to match the name of a legitimate Windows executable.(Citation: Rewterz Sidewinder COVID-19 June 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[Sidewinder](https://attack.mitre.org/groups/G0121) has lured targets to click on malicious links to gain execution in the target environment.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder APT April 2020)(Citation: Rewterz Sidewinder COVID-19 June 2020)(Citation: Cyble Sidewinder September 2020)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518.001|Security Software Discovery|[Sidewinder](https://attack.mitre.org/groups/G0121) has used the Windows service <code>winmgmts:\\.\root\SecurityCenter2</code> to check installed antivirus products.(Citation: Rewterz Sidewinder APT April 2020)|
|mitre-attack|enterprise-attack|Windows|T1559.002|Dynamic Data Exchange|[Sidewinder](https://attack.mitre.org/groups/G0121) has used the ActiveXObject utility to create OLE objects to obtain execution through Internet Explorer.(Citation: Rewterz Sidewinder APT April 2020)(Citation: Rewterz Sidewinder COVID-19 June 2020)|
|mitre-attack|enterprise-attack|Windows|T1218.005|Mshta|[Sidewinder](https://attack.mitre.org/groups/G0121) has used <code>mshta.exe</code> to execute malicious payloads.(Citation: Rewterz Sidewinder APT April 2020)(Citation: Rewterz Sidewinder COVID-19 June 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Sidewinder](https://attack.mitre.org/groups/G0121) has lured targets to click on malicious files to gain execution in the target environment.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder APT April 2020)(Citation: Rewterz Sidewinder COVID-19 June 2020)(Citation: Cyble Sidewinder September 2020)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Sidewinder](https://attack.mitre.org/groups/G0121) has added paths to executables in the Registry to establish persistence.(Citation: Rewterz Sidewinder APT April 2020)(Citation: Rewterz Sidewinder COVID-19 June 2020)(Citation: Cyble Sidewinder September 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,IaaS,SaaS|T1119|Automated Collection|[Sidewinder](https://attack.mitre.org/groups/G0121) has used tools to automatically collect system and network configuration information.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1020|Automated Exfiltration|[Sidewinder](https://attack.mitre.org/groups/G0121) has configured tools to automatically send collected files to attacker controlled servers.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[Sidewinder](https://attack.mitre.org/groups/G0121) has used HTTP in C2 communications.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder APT April 2020)(Citation: Rewterz Sidewinder COVID-19 June 2020)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518|Software Discovery|[Sidewinder](https://attack.mitre.org/groups/G0121) has used tools to enumerate software installed on an infected host.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder APT April 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[Sidewinder](https://attack.mitre.org/groups/G0121) has used malware to collect information on files and directories.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1074.001|Local Data Staging|[Sidewinder](https://attack.mitre.org/groups/G0121) has collected stolen files in a temporary folder in preparation for exfiltration.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[Sidewinder](https://attack.mitre.org/groups/G0121) has used malware to collect information on network interfaces, including the MAC address.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Windows,Network|T1124|System Time Discovery|[Sidewinder](https://attack.mitre.org/groups/G0121) has used tools to obtain the current system time.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Sidewinder](https://attack.mitre.org/groups/G0121) has used tools to identify running processes on the victim's machine.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Sidewinder](https://attack.mitre.org/groups/G0121) has used tools to collect the computer name, OS version, installed hotfixes, as well as information regarding the memory and processor on a compromised host.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder COVID-19 June 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[Sidewinder](https://attack.mitre.org/groups/G0121) has used tools to identify the user of a compromised host.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Sidewinder](https://attack.mitre.org/groups/G0121) has used base64 encoding and ECDH-P256 encryption for payloads.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder APT April 2020)(Citation: Cyble Sidewinder September 2020)|
|mitre-attack|enterprise-attack|Windows|T1574.002|DLL Side-Loading|[Sidewinder](https://attack.mitre.org/groups/G0121) has used DLL side-loading to drop and execute malicious payloads including the hijacking of the legitimate Windows application file rekeywiz.exe.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.007|JavaScript|[Sidewinder](https://attack.mitre.org/groups/G0121) has used JavaScript to drop and execute malware loaders.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder COVID-19 June 2020)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Sidewinder](https://attack.mitre.org/groups/G0121) has used PowerShell to drop and execute malware loaders.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[Sidewinder](https://attack.mitre.org/groups/G0121) has used VBScript to drop and execute malware loaders.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Sidewinder](https://attack.mitre.org/groups/G0121) has exploited vulnerabilities to gain execution including CVE-2017-11882 and CVE-2020-0674.(Citation: ATT Sidewinder January 2021)(Citation: Cyble Sidewinder September 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Sidewinder](https://attack.mitre.org/groups/G0121) has used LNK files to download remote files to the victim's network.(Citation: ATT Sidewinder January 2021)(Citation: Cyble Sidewinder September 2020)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Sidewinder](https://attack.mitre.org/groups/G0121) has sent e-mails with malicious attachments often crafted for specific targets.(Citation: ATT Sidewinder January 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[Sidewinder](https://attack.mitre.org/groups/G0121) has sent e-mails with malicious links often crafted for specific targets.(Citation: ATT Sidewinder January 2021)(Citation: Cyble Sidewinder September 2020)|
|mitre-attack|enterprise-attack|PRE|T1598.002|Spearphishing Attachment|[Sidewinder](https://attack.mitre.org/groups/G0121) has sent e-mails with malicious attachments that lead victims to credential harvesting websites.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder APT April 2020)(Citation: Cyble Sidewinder September 2020)|
|mitre-attack|enterprise-attack|PRE|T1598.003|Spearphishing Link|[Sidewinder](https://attack.mitre.org/groups/G0121) has sent e-mails with malicious links to credential harvesting websites.(Citation: ATT Sidewinder January 2021)|
