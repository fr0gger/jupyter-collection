# LazyScripter - G0140

**Created**: 2021-11-24T19:26:27.305Z

**Modified**: 2023-03-22T04:49:29.731Z

**Contributors**: Manikantan Srinivasan, NEC Corporation India,Pooja Natarajan, NEC Corporation India,Hiroki Nagahama, NEC Corporation

## Aliases

LazyScripter

## Description

[LazyScripter](https://attack.mitre.org/groups/G0140) is threat group that has mainly targeted the airlines industry since at least 2018, primarily using open-source toolsets.(Citation: MalwareBytes LazyScripter Feb 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1583.006|Web Services|[LazyScripter](https://attack.mitre.org/groups/G0140) has established GitHub accounts to host its toolsets.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|PRE|T1583.001|Domains|[LazyScripter](https://attack.mitre.org/groups/G0140) has used dynamic DNS providers to create legitimate-looking subdomains for C2.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|PRE|T1608.001|Upload Malware|[LazyScripter](https://attack.mitre.org/groups/G0140) has hosted open-source remote access Trojans used in its operations in GitHub.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|PRE|T1588.001|Malware|[LazyScripter](https://attack.mitre.org/groups/G0140) has used a variety of open-source remote access Trojans for its operations.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[LazyScripter](https://attack.mitre.org/groups/G0140) had downloaded additional tools to a compromised host.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[LazyScripter](https://attack.mitre.org/groups/G0140) has relied upon users clicking on links to malicious files.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[LazyScripter](https://attack.mitre.org/groups/G0140) has lured users to open malicious email attachments.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.007|JavaScript|[LazyScripter](https://attack.mitre.org/groups/G0140) has used JavaScript in its attacks.(Citation: MalwareBytes LazyScripter Feb 2021) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036|Masquerading|[LazyScripter](https://attack.mitre.org/groups/G0140) has used several different security software icons to disguise executables.(Citation: MalwareBytes LazyScripter Feb 2021) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.004|DNS|[LazyScripter](https://attack.mitre.org/groups/G0140) has leveraged dynamic DNS providers for C2 communications.(Citation: MalwareBytes LazyScripter Feb 2021) |
|mitre-attack|enterprise-attack|Windows|T1218.011|Rundll32|[LazyScripter](https://attack.mitre.org/groups/G0140) has used `rundll32.exe` to execute [Koadic](https://attack.mitre.org/software/S0250) stagers.(Citation: MalwareBytes LazyScripter Feb 2021) |
|mitre-attack|enterprise-attack|Windows|T1218.005|Mshta|[LazyScripter](https://attack.mitre.org/groups/G0140) has used `mshta.exe` to execute [Koadic](https://attack.mitre.org/software/S0250) stagers.(Citation: MalwareBytes LazyScripter Feb 2021) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102|Web Service|[LazyScripter](https://attack.mitre.org/groups/G0140) has used GitHub to host its payloads to operate spam campaigns.(Citation: MalwareBytes LazyScripter Feb 2021) |
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[LazyScripter](https://attack.mitre.org/groups/G0140) has used VBScript to execute malicious code.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[LazyScripter](https://attack.mitre.org/groups/G0140) has used PowerShell scripts to execute malicious code.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[LazyScripter](https://attack.mitre.org/groups/G0140) has achieved persistence via writing a PowerShell script to the autorun registry key.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[LazyScripter](https://attack.mitre.org/groups/G0140) has leveraged the BatchEncryption tool to perform advanced batch script obfuscation and encoding techniques.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[LazyScripter](https://attack.mitre.org/groups/G0140) has used batch files to deploy open-source and multi-stage RATs.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[LazyScripter](https://attack.mitre.org/groups/G0140) has used spam emails that contain a link that redirects the victim to download a malicious document.(Citation: MalwareBytes LazyScripter Feb 2021)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[LazyScripter](https://attack.mitre.org/groups/G0140) has used spam emails weaponized with archive or document files as its initial infection vector.(Citation: MalwareBytes LazyScripter Feb 2021)|
