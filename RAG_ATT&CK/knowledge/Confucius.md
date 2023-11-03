# Confucius - G0142

**Created**: 2021-12-26T23:11:39.442Z

**Modified**: 2022-06-30T20:15:32.697Z

**Contributors**: 

## Aliases

Confucius,Confucius APT

## Description

[Confucius](https://attack.mitre.org/groups/G0142) is a cyber espionage group that has primarily targeted military personnel, high-profile personalities, business persons, and government organizations in South Asia since at least 2013. Security researchers have noted similarities between [Confucius](https://attack.mitre.org/groups/G0142) and [Patchwork](https://attack.mitre.org/groups/G0040), particularly in their respective custom malware code and targets.(Citation: TrendMicro Confucius APT Feb 2018)(Citation: TrendMicro Confucius APT Aug 2021)(Citation: Uptycs Confucius APT Jan 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows|T1218.005|Mshta|[Confucius](https://attack.mitre.org/groups/G0142) has used mshta.exe to execute malicious VBScript.(Citation: TrendMicro Confucius APT Feb 2018) |
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[Confucius](https://attack.mitre.org/groups/G0142) has used VBScript to execute malicious code.(Citation: TrendMicro Confucius APT Feb 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1567.002|Exfiltration to Cloud Storage|[Confucius](https://attack.mitre.org/groups/G0142) has exfiltrated victim data to cloud storage service accounts.(Citation: TrendMicro Confucius APT Feb 2018)|
|mitre-attack|enterprise-attack|PRE|T1583.006|Web Services|[Confucius](https://attack.mitre.org/groups/G0142) has obtained cloud storage service accounts to host stolen data.(Citation: TrendMicro Confucius APT Feb 2018)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Confucius](https://attack.mitre.org/groups/G0142) has crafted and sent victims malicious attachments to gain initial access.(Citation: Uptycs Confucius APT Jan 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[Confucius](https://attack.mitre.org/groups/G0142) has sent malicious links to victims through email campaigns.(Citation: TrendMicro Confucius APT Aug 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[Confucius](https://attack.mitre.org/groups/G0142) has lured victims into clicking on a malicious link sent through spearphishing.(Citation: TrendMicro Confucius APT Aug 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Confucius](https://attack.mitre.org/groups/G0142) has lured victims to execute malicious attachments included in crafted spearphishing emails related to current topics.(Citation: Uptycs Confucius APT Jan 2021)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Confucius](https://attack.mitre.org/groups/G0142) has used PowerShell to execute malicious files and payloads.(Citation: TrendMicro Confucius APT Aug 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[Confucius](https://attack.mitre.org/groups/G0142) has used HTTP for C2 communications.(Citation: Uptycs Confucius APT Jan 2021)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Confucius](https://attack.mitre.org/groups/G0142) has exploited Microsoft Office vulnerabilities, including CVE-2015-1641, CVE-2017-11882, and CVE-2018-0802.(Citation: Uptycs Confucius APT Jan 2021)(Citation: TrendMicro Confucius APT Feb 2018)|
|mitre-attack|enterprise-attack|Windows|T1221|Template Injection|[Confucius](https://attack.mitre.org/groups/G0142) has used a weaponized Microsoft Word document with an embedded RTF exploit.(Citation: Uptycs Confucius APT Jan 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Confucius](https://attack.mitre.org/groups/G0142) has downloaded additional files and payloads onto a compromised host following initial access.(Citation: Uptycs Confucius APT Jan 2021)(Citation: TrendMicro Confucius APT Aug 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,IaaS,SaaS|T1119|Automated Collection|[Confucius](https://attack.mitre.org/groups/G0142) has used a file stealer to steal documents and images with the following extensions: txt, pdf, png, jpg, doc, xls, xlm, odp, ods, odt, rtf, ppt, xlsx, xlsm, docx, pptx, and jpeg.(Citation: TrendMicro Confucius APT Aug 2021)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[Confucius](https://attack.mitre.org/groups/G0142) has created scheduled tasks to maintain persistence on a compromised host.(Citation: TrendMicro Confucius APT Aug 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1041|Exfiltration Over C2 Channel|[Confucius](https://attack.mitre.org/groups/G0142) has exfiltrated stolen files to its C2 server.(Citation: TrendMicro Confucius APT Aug 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[Confucius](https://attack.mitre.org/groups/G0142) has used a file stealer that checks the Document, Downloads, Desktop, and Picture folders for documents and images with specific extensions.(Citation: TrendMicro Confucius APT Aug 2021)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Confucius](https://attack.mitre.org/groups/G0142) has dropped malicious files into the startup folder `%AppData%\Microsoft\Windows\Start Menu\Programs\Startup` on a compromised host in order to maintain persistence.(Citation: Uptycs Confucius APT Jan 2021)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Confucius](https://attack.mitre.org/groups/G0142) has used a file stealer that can examine system drives, including those other than the C drive.(Citation: TrendMicro Confucius APT Aug 2021)|
