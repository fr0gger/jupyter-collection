# Ember Bear - G1003

**Created**: 2022-06-09T14:49:57.704Z

**Modified**: 2023-03-22T03:40:53.311Z

**Contributors**: Hannah Simes, BT Security

## Aliases

Ember Bear,Saint Bear,UNC2589,UAC-0056,Lorec53,Lorec Bear,Bleeding Bear

## Description

[Ember Bear](https://attack.mitre.org/groups/G1003) is a suspected Russian state-sponsored cyber espionage group that has been active since at least March 2021. [Ember Bear](https://attack.mitre.org/groups/G1003) has primarily focused their operations against Ukraine and Georgia, but has also targeted Western European and North American foreign ministries, pharmaceutical companies, and financial sector organizations. Security researchers assess [Ember Bear](https://attack.mitre.org/groups/G1003) likely conducted the [WhisperGate](https://attack.mitre.org/software/S0689) destructive wiper attacks against Ukraine in early 2022.(Citation: CrowdStrike Ember Bear Profile March 2022)(Citation: Mandiant UNC2589 March 2022)(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 ) 

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[Ember Bear](https://attack.mitre.org/groups/G1003) has obfuscated malicious scripts to help avoid detection.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|PRE|T1588.003|Code Signing Certificates|[Ember Bear](https://attack.mitre.org/groups/G1003) has stolen legitimate certificates to sign malicious payloads.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Windows|T1218.002|Control Panel|[Ember Bear](https://attack.mitre.org/groups/G1003) has used control panel files (CPL), delivered via e-mail, for execution.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Ember Bear](https://attack.mitre.org/groups/G1003) has used tools to download malicious code.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|macOS,Windows|T1553.002|Code Signing|[Ember Bear](https://attack.mitre.org/groups/G1003) has used stolen certificates from Electrum Technologies GmbH to sign payloads.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Windows|T1112|Modify Registry|[Ember Bear](https://attack.mitre.org/groups/G1003) has used an open source batch script to modify Windows Defender registry keys.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.001|Binary Padding|[Ember Bear](https://attack.mitre.org/groups/G1003) has added extra spaces between JavaScript code characters to increase the overall file size.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Ember Bear](https://attack.mitre.org/groups/G1003) has obtained and used open source scripts from GitHub.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 ) |
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Containers,IaaS|T1562.001|Disable or Modify Tools|[Ember Bear](https://attack.mitre.org/groups/G1003) has executed a batch script designed to disable Windows Defender on a compromised host.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Ember Bear](https://attack.mitre.org/groups/G1003) has obfuscated malware to help avoid detection.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1027.002|Software Packing|[Ember Bear](https://attack.mitre.org/groups/G1003) has packed malware to help avoid detection.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102|Web Service|[Ember Bear](https://attack.mitre.org/groups/G1003) has used Discord's content delivery network (CDN) to deliver malware and malicious scripts to a compromised host.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Ember Bear](https://attack.mitre.org/groups/G1003) had used `cmd.exe` and Windows Script Host (wscript) to execute malicious code.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Ember Bear](https://attack.mitre.org/groups/G1003) has used PowerShell to download and execute malicious code.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Ember Bear](https://attack.mitre.org/groups/G1003) has exploited Microsoft Office vulnerability CVE-2017-11882.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.007|JavaScript|[Ember Bear](https://attack.mitre.org/groups/G1003) has used JavaScript to execute malicious code on a victim's machine.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[Ember Bear](https://attack.mitre.org/groups/G1003) has sent spearphishing emails containing malicious links.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[Ember Bear](https://attack.mitre.org/groups/G1003) has attempted to lure users to click on a malicious link within a spearphishing email.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Ember Bear](https://attack.mitre.org/groups/G1003) has attempted to lure victims into executing malicious files.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Ember Bear](https://attack.mitre.org/groups/G1003) has sent spearphishing emails containing malicious attachments in the form of PDFs, Word documents, JavaScript files, and Control Panel File (CPL) executables.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 ) |
