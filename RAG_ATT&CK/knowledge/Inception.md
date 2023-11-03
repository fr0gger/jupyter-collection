# Inception - G0100

**Created**: 2020-05-08T17:01:04.058Z

**Modified**: 2021-10-12T23:21:06.480Z

**Contributors**: Oleg Skulkin, Group-IB

## Aliases

Inception,Inception Framework,Cloud Atlas

## Description

[Inception](https://attack.mitre.org/groups/G0100) is a cyber espionage group active since at least 2014. The group has targeted multiple industries and governmental entities primarily in Russia, but has also been active in the United States and throughout Europe, Asia, Africa, and the Middle East.(Citation: Unit 42 Inception November 2018)(Citation: Symantec Inception Framework March 2018)(Citation: Kaspersky Cloud Atlas December 2014)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Inception](https://attack.mitre.org/groups/G0100) has obtained and used open-source tools such as [LaZagne](https://attack.mitre.org/software/S0349).(Citation: Kaspersky Cloud Atlas August 2019)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518|Software Discovery|[Inception](https://attack.mitre.org/groups/G0100) has enumerated installed software on compromised systems.(Citation: Symantec Inception Framework March 2018)|
|mitre-attack|enterprise-attack|Windows|T1218.005|Mshta|[Inception](https://attack.mitre.org/groups/G0100) has used malicious HTA files to drop and execute malware.(Citation: Kaspersky Cloud Atlas August 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[Inception](https://attack.mitre.org/groups/G0100) used a file hunting plugin to collect .txt, .pdf, .xls or .doc files from the infected host.(Citation: Kaspersky Cloud Atlas August 2019)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Inception](https://attack.mitre.org/groups/G0100) has used PowerShell to execute malicious commands and payloads.(Citation: Unit 42 Inception November 2018)(Citation: Kaspersky Cloud Atlas December 2014)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[Inception](https://attack.mitre.org/groups/G0100) has used VBScript to execute malicious commands and payloads.(Citation: Unit 42 Inception November 2018)(Citation: Kaspersky Cloud Atlas December 2014)|
|mitre-attack|enterprise-attack|Windows|T1221|Template Injection|[Inception](https://attack.mitre.org/groups/G0100) has used decoy documents to load malicious remote payloads via HTTP.(Citation: Unit 42 Inception November 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Inception](https://attack.mitre.org/groups/G0100) has encrypted malware payloads dropped on victim machines with AES and RC4 encryption.(Citation: Kaspersky Cloud Atlas December 2014)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[Inception](https://attack.mitre.org/groups/G0100) used a file listing plugin to collect information about file and directories both on local and remote drives.(Citation: Symantec Inception Framework March 2018)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Inception](https://attack.mitre.org/groups/G0100) has exploited CVE-2012-0158, CVE-2014-1761, CVE-2017-11882 and CVE-2018-0802 for execution.(Citation: Kaspersky Cloud Atlas August 2019)(Citation: Kaspersky Cloud Atlas December 2014)(Citation: Symantec Inception Framework March 2018)(Citation: Unit 42 Inception November 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[Inception](https://attack.mitre.org/groups/G0100) has used HTTP, HTTPS, and WebDav in network communications.(Citation: Kaspersky Cloud Atlas December 2014)(Citation: Unit 42 Inception November 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[Inception](https://attack.mitre.org/groups/G0100) used a browser plugin to steal passwords and sessions from Internet Explorer, Chrome, Opera, Firefox, Torch, and Yandex.(Citation: Symantec Inception Framework March 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Inception](https://attack.mitre.org/groups/G0100) lured victims into clicking malicious files for machine reconnaissance and to execute malware.(Citation: Kaspersky Cloud Atlas December 2014)(Citation: Kaspersky Cloud Atlas August 2019)(Citation: Symantec Inception Framework March 2018)(Citation: Unit 42 Inception November 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1090.003|Multi-hop Proxy|[Inception](https://attack.mitre.org/groups/G0100) used chains of compromised routers to proxy C2 communications between them and cloud service providers.(Citation: Symantec Inception Framework March 2018)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Inception](https://attack.mitre.org/groups/G0100) has maintained persistence by modifying Registry run key value 
 <code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run\</code>.(Citation: Kaspersky Cloud Atlas December 2014)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1573.001|Symmetric Cryptography|[Inception](https://attack.mitre.org/groups/G0100) has encrypted network communications with AES.(Citation: Kaspersky Cloud Atlas December 2014)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1069.002|Domain Groups|[Inception](https://attack.mitre.org/groups/G0100) has used specific malware modules to gather domain membership.(Citation: Symantec Inception Framework March 2018)|
|mitre-attack|enterprise-attack|Windows|T1218.010|Regsvr32|[Inception](https://attack.mitre.org/groups/G0100) has ensured persistence at system boot by setting the value <code>regsvr32 %path%\ctfmonrn.dll /s</code>.(Citation: Kaspersky Cloud Atlas December 2014)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102|Web Service|[Inception](https://attack.mitre.org/groups/G0100) has incorporated at least five different cloud service providers into their C2 infrastructure including CloudMe.(Citation: Kaspersky Cloud Atlas December 2014)(Citation: Symantec Inception Framework March 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Inception](https://attack.mitre.org/groups/G0100) has used a reconnaissance module to identify active processes and other associated loaded modules.(Citation: Symantec Inception Framework March 2018)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Inception](https://attack.mitre.org/groups/G0100) has used a reconnaissance module to gather information about the operating system and hardware on the infected host.(Citation: Symantec Inception Framework March 2018)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Inception](https://attack.mitre.org/groups/G0100) has used weaponized documents attached to spearphishing emails for reconnaissance and initial compromise.(Citation: Kaspersky Cloud Atlas December 2014)(Citation: Symantec Inception Framework March 2018)(Citation: Unit 42 Inception November 2018)(Citation: Kaspersky Cloud Atlas August 2019)|
