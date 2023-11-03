# Molerats - G0021

**Created**: 2017-05-31T21:31:55.093Z

**Modified**: 2021-04-27T20:16:16.057Z

**Contributors**: 

## Aliases

Molerats,Operation Molerats,Gaza Cybergang

## Description

[Molerats](https://attack.mitre.org/groups/G0021) is an Arabic-speaking, politically-motivated threat group that has been operating since 2012. The group's victims have primarily been in the Middle East, Europe, and the United States.(Citation: DustySky)(Citation: DustySky2)(Citation: Kaspersky MoleRATs April 2019)(Citation: Cybereason Molerats Dec 2020)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows|T1218.007|Msiexec|[Molerats](https://attack.mitre.org/groups/G0021) has used msiexec.exe to execute an MSI payload.(Citation: Unit42 Molerat Mar 2020) |
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[Molerats](https://attack.mitre.org/groups/G0021) has created scheduled tasks to persistently run VBScripts.(Citation: Unit42 Molerat Mar 2020)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1140|Deobfuscate/Decode Files or Information|[Molerats](https://attack.mitre.org/groups/G0021) decompresses ZIP files once on the victim machine.(Citation: Kaspersky MoleRATs April 2019)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Molerats](https://attack.mitre.org/groups/G0021) used PowerShell implants on target machines.(Citation: Kaspersky MoleRATs April 2019)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.007|JavaScript|[Molerats](https://attack.mitre.org/groups/G0021) used various implants, including those built with JS, on target machines.(Citation: Kaspersky MoleRATs April 2019)	|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[Molerats](https://attack.mitre.org/groups/G0021) used various implants, including those built with VBScript, on target machines.(Citation: Kaspersky MoleRATs April 2019)(Citation: Unit42 Molerat Mar 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[Molerats](https://attack.mitre.org/groups/G0021) has sent phishing emails with malicious links included.(Citation: Kaspersky MoleRATs April 2019)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Molerats](https://attack.mitre.org/groups/G0021) has sent phishing emails with malicious Microsoft Word and PDF attachments.(Citation: Kaspersky MoleRATs April 2019)(Citation: Unit42 Molerat Mar 2020)(Citation: Cybereason Molerats Dec 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Molerats](https://attack.mitre.org/groups/G0021) has sent malicious files via email that tricked users into clicking Enable Content to run an embedded macro and to download malicious archives.(Citation: Kaspersky MoleRATs April 2019)(Citation: Unit42 Molerat Mar 2020)(Citation: Cybereason Molerats Dec 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[Molerats](https://attack.mitre.org/groups/G0021) has sent malicious links via email trick users into opening a RAR archive and running an executable.(Citation: Kaspersky MoleRATs April 2019)(Citation: Unit42 Molerat Mar 2020) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Molerats](https://attack.mitre.org/groups/G0021) has delivered compressed executables within ZIP files to victims.(Citation: Kaspersky MoleRATs April 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Molerats](https://attack.mitre.org/groups/G0021) used executables to download malicious files from different sources.(Citation: Kaspersky MoleRATs April 2019)(Citation: Unit42 Molerat Mar 2020) |
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Molerats](https://attack.mitre.org/groups/G0021) saved malicious files within the AppData and Startup folders to maintain persistence.(Citation: Kaspersky MoleRATs April 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[Molerats](https://attack.mitre.org/groups/G0021) used the public tool BrowserPasswordDump10 to dump passwords saved in browsers on victims.(Citation: DustySky)|
|mitre-attack|enterprise-attack|macOS,Windows|T1553.002|Code Signing|[Molerats](https://attack.mitre.org/groups/G0021) has used forged Microsoft code-signing certificates on malware.(Citation: FireEye Operation Molerats)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Molerats](https://attack.mitre.org/groups/G0021) actors obtained a list of active processes on the victim and sent them to C2 servers.(Citation: DustySky)|
