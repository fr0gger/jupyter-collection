# Gorgon Group - G0078

**Created**: 2018-10-17T00:14:20.652Z

**Modified**: 2021-10-12T21:57:25.847Z

**Contributors**: 

## Aliases

Gorgon Group

## Description

[Gorgon Group](https://attack.mitre.org/groups/G0078) is a threat group consisting of members who are suspected to be Pakistan-based or have other connections to Pakistan. The group has performed a mix of criminal and targeted attacks, including campaigns against government organizations in the United Kingdom, Spain, Russia, and the United States. (Citation: Unit 42 Gorgon Group Aug 2018)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Gorgon Group](https://attack.mitre.org/groups/G0078) has obtained and used tools such as [QuasarRAT](https://attack.mitre.org/software/S0262) and [Remcos](https://attack.mitre.org/software/S0332).(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1564.003|Hidden Window|[Gorgon Group](https://attack.mitre.org/groups/G0078) has used <code>-W Hidden</code> to conceal [PowerShell](https://attack.mitre.org/techniques/T1059/001) windows by setting the WindowStyle parameter to hidden. (Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can use cmd.exe to download and execute payloads and to execute commands on the system.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[Gorgon Group](https://attack.mitre.org/groups/G0078) has used macros in [Spearphishing Attachment](https://attack.mitre.org/techniques/T1566/001)s as well as executed VBScripts on victim machines.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can use PowerShell commands to download and execute a payload and open a decoy document on the victim’s machine.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Gorgon Group](https://attack.mitre.org/groups/G0078) sent emails to victims with malicious Microsoft Office documents attached.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Containers,IaaS|T1562.001|Disable or Modify Tools|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can attempt to disable security features in Microsoft Office and Windows Defender using the <code>taskkill</code> command.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows|T1055.012|Process Hollowing|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can use process hollowing to inject one of its trojans into another process.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can download additional files from C2 servers.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1140|Deobfuscate/Decode Files or Information|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can decode contents from a payload that was Base64 encoded and write the contents to a file.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows|T1112|Modify Registry|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can deactivate security mechanisms in Microsoft Office by editing several keys and values under <code>HKCU\Software\Microsoft\Office\</code>.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows|T1055.002|Portable Executable Injection|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can download a remote access tool, [ShiftyBug](https://attack.mitre.org/software/S0294), and inject into another process.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1106|Native API|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can leverage the Windows API call, CreateProcessA(), for execution.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can create a .lnk file and add a Registry Run key to establish persistence.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Gorgon Group](https://attack.mitre.org/groups/G0078) attempted to get users to launch malicious Microsoft Office attachments delivered via spearphishing emails.(Citation: Unit 42 Gorgon Group Aug 2018)|
|mitre-attack|enterprise-attack|Windows|T1547.009|Shortcut Modification|[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can create a .lnk file and add a Registry Run key to establish persistence.(Citation: Unit 42 Gorgon Group Aug 2018)|
