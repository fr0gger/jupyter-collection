# Whitefly - G0107

**Created**: 2020-05-26T16:55:09.674Z

**Modified**: 2021-10-12T21:43:24.133Z

**Contributors**: 

## Aliases

Whitefly

## Description

[Whitefly](https://attack.mitre.org/groups/G0107) is a cyber espionage group that has been operating since at least 2017. The group has targeted organizations based mostly in Singapore across a wide variety of sectors, and is primarily interested in stealing large amounts of sensitive information. The group has been linked to an attack against Singapore’s largest public health organization, SingHealth.(Citation: Symantec Whitefly March 2019)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Whitefly](https://attack.mitre.org/groups/G0107) has obtained and used tools such as [Mimikatz](https://attack.mitre.org/software/S0002).(Citation: Symantec Whitefly March 2019)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[Whitefly](https://attack.mitre.org/groups/G0107) has used [Mimikatz](https://attack.mitre.org/software/S0002) to obtain credentials.(Citation: Symantec Whitefly March 2019)|
|mitre-attack|enterprise-attack|Windows|T1574.001|DLL Search Order Hijacking|[Whitefly](https://attack.mitre.org/groups/G0107) has used search order hijacking to run the loader Vcrodat.(Citation: Symantec Whitefly March 2019)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Whitefly](https://attack.mitre.org/groups/G0107) has named the malicious DLL the same name as DLLs belonging to legitimate software from various security vendors.(Citation: Symantec Whitefly March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Whitefly](https://attack.mitre.org/groups/G0107) has encrypted the payload used for C2.(Citation: Symantec Whitefly March 2019)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Whitefly](https://attack.mitre.org/groups/G0107) has the ability to download additional tools from the C2.(Citation: Symantec Whitefly March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Whitefly](https://attack.mitre.org/groups/G0107) has used malicious .exe or .dll files disguised as documents or images.(Citation: Symantec Whitefly March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1068|Exploitation for Privilege Escalation|[Whitefly](https://attack.mitre.org/groups/G0107) has used an open-source tool to exploit a known Windows privilege escalation vulnerability (CVE-2016-0051) on unpatched computers.(Citation: Symantec Whitefly March 2019)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network,Office 365,Azure AD,IaaS,Google Workspace|T1059|Command and Scripting Interpreter|[Whitefly](https://attack.mitre.org/groups/G0107) has used a simple remote shell tool that will call back to the C2 server and wait for commands.(Citation: Symantec Whitefly March 2019)|
