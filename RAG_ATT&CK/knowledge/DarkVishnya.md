# DarkVishnya - G0105

**Created**: 2020-05-15T13:07:26.651Z

**Modified**: 2021-10-12T22:10:04.107Z

**Contributors**: 

## Aliases

DarkVishnya

## Description

[DarkVishnya](https://attack.mitre.org/groups/G0105) is a financially motivated threat actor targeting financial institutions in Eastern Europe. In 2017-2018 the group attacked at least 8 banks in this region.(Citation: Securelist DarkVishnya Dec 2018)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[DarkVishnya](https://attack.mitre.org/groups/G0105) has obtained and used tools such as [Impacket](https://attack.mitre.org/software/S0357), [Winexe](https://attack.mitre.org/software/S0191), and [PsExec](https://attack.mitre.org/software/S0029).(Citation: Securelist DarkVishnya Dec 2018)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers,Network|T1046|Network Service Discovery|[DarkVishnya](https://attack.mitre.org/groups/G0105) performed port scanning to obtain the list of active services.(Citation: Securelist DarkVishnya Dec 2018)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1110|Brute Force|[DarkVishnya](https://attack.mitre.org/groups/G0105) used brute-force attack to obtain login data.(Citation: Securelist DarkVishnya Dec 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network,IaaS|T1040|Network Sniffing|[DarkVishnya](https://attack.mitre.org/groups/G0105) used network sniffing to obtain login data. (Citation: Securelist DarkVishnya Dec 2018)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1219|Remote Access Software|[DarkVishnya](https://attack.mitre.org/groups/G0105) used DameWare Mini Remote Control for lateral movement.(Citation: Securelist DarkVishnya Dec 2018)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[DarkVishnya](https://attack.mitre.org/groups/G0105) used PowerShell to create shellcode loaders.(Citation: Securelist DarkVishnya Dec 2018)|
|mitre-attack|enterprise-attack|Windows|T1543.003|Windows Service|[DarkVishnya](https://attack.mitre.org/groups/G0105) created new services for shellcode loaders distribution.(Citation: Securelist DarkVishnya Dec 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1571|Non-Standard Port|[DarkVishnya](https://attack.mitre.org/groups/G0105) used ports 5190 and 7900 for shellcode listeners, and 4444, 4445, 31337 for shellcode C2.(Citation: Securelist DarkVishnya Dec 2018)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1135|Network Share Discovery|[DarkVishnya](https://attack.mitre.org/groups/G0105) scanned the network for public shared folders.(Citation: Securelist DarkVishnya Dec 2018)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1200|Hardware Additions|[DarkVishnya](https://attack.mitre.org/groups/G0105) used Bash Bunny, Raspberry Pi, netbooks or inexpensive laptops to connect to the company’s local network.(Citation: Securelist DarkVishnya Dec 2018)|
