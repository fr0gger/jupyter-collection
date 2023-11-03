# Cleaver - G0003

**Created**: 2017-05-31T21:31:46.390Z

**Modified**: 2022-07-22T18:37:22.178Z

**Contributors**: 

## Aliases

Cleaver,Threat Group 2889,TG-2889

## Description

[Cleaver](https://attack.mitre.org/groups/G0003) is a threat group that has been attributed to Iranian actors and is responsible for activity tracked as Operation Cleaver. (Citation: Cylance Cleaver) Strong circumstantial evidence suggests Cleaver is linked to Threat Group 2889 (TG-2889). (Citation: Dell Threat Group 2889)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Cleaver](https://attack.mitre.org/groups/G0003) has obtained and used open-source tools such as [PsExec](https://attack.mitre.org/software/S0029), [Windows Credential Editor](https://attack.mitre.org/software/S0005), and [Mimikatz](https://attack.mitre.org/software/S0002).(Citation: Cylance Cleaver)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1557.002|ARP Cache Poisoning|[Cleaver](https://attack.mitre.org/groups/G0003) has used custom tools to facilitate ARP cache poisoning.(Citation: Cylance Cleaver)|
|mitre-attack|enterprise-attack|PRE|T1587.001|Malware|[Cleaver](https://attack.mitre.org/groups/G0003) has created customized tools and payloads for functions including ARP poisoning, encryption, credential dumping, ASP.NET shells, web backdoors, process enumeration, WMI querying, HTTP and SMB communications, network interface sniffing, and keystroke logging.(Citation: Cylance Cleaver)|
|mitre-attack|enterprise-attack|PRE|T1585.001|Social Media Accounts|[Cleaver](https://attack.mitre.org/groups/G0003) has created fake LinkedIn profiles that included profile photos, details, and connections.(Citation: Dell Threat Group 2889)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[Cleaver](https://attack.mitre.org/groups/G0003) has been known to dump credentials using Mimikatz and Windows Credential Editor.(Citation: Cylance Cleaver)|
