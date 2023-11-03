# Putter Panda - G0024

**Created**: 2017-05-31T21:31:56.785Z

**Modified**: 2020-03-30T19:15:04.771Z

**Contributors**: 

## Aliases

Putter Panda,APT2,MSUpdater

## Description

[Putter Panda](https://attack.mitre.org/groups/G0024) is a Chinese threat group that has been attributed to Unit 61486 of the 12th Bureau of the PLA’s 3rd General Staff Department (GSD). (Citation: CrowdStrike Putter Panda)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Containers,IaaS|T1562.001|Disable or Modify Tools|Malware used by [Putter Panda](https://attack.mitre.org/groups/G0024) attempts to terminate processes corresponding to two components of Sophos Anti-Virus (SAVAdminService.exe and SavService.exe).(Citation: CrowdStrike Putter Panda)|
|mitre-attack|enterprise-attack|Windows|T1055.001|Dynamic-link Library Injection|An executable dropped onto victims by [Putter Panda](https://attack.mitre.org/groups/G0024) aims to inject the specified DLL into a process that would normally be accessing the network, including Outlook Express (msinm.exe), Outlook (outlook.exe), Internet Explorer (iexplore.exe), and Firefox (firefox.exe).(Citation: CrowdStrike Putter Panda)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|Droppers used by [Putter Panda](https://attack.mitre.org/groups/G0024) use RC4 or a 16-byte XOR key consisting of the bytes 0xA0 – 0xAF to obfuscate payloads.(Citation: CrowdStrike Putter Panda)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|A dropper used by [Putter Panda](https://attack.mitre.org/groups/G0024) installs itself into the ASEP Registry key <code>HKCU\Software\Microsoft\Windows\CurrentVersion\Run</code> with a value named McUpdate.(Citation: CrowdStrike Putter Panda)|
