# BackdoorDiplomacy - G0135

**Created**: 2021-09-21T14:52:49.596Z

**Modified**: 2021-10-18T19:47:11.389Z

**Contributors**: Zaw Min Htun, @Z3TAE

## Aliases

BackdoorDiplomacy

## Description

[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) is a cyber espionage threat group that has been active since at least 2017. [BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has targeted Ministries of Foreign Affairs and telecommunication companies in Africa, Europe, the Middle East, and Asia.(Citation: ESET BackdoorDiplomacy Jun 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1120|Peripheral Device Discovery|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has used an executable to detect removable media, such as USB flash drives.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1074.001|Local Data Staging|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has copied files of interest to the main drive's recycle bin.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS,Network|T1505.003|Web Shell|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has used web shells to establish an initial foothold and for lateral movement within a victim's system.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has obtained a variety of open-source reconnaissance and red team tools for discovery and lateral movement.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has obfuscated tools and malware it uses with VMProtect.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,Network|T1095|Non-Application Layer Protocol|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has used EarthWorm for network tunneling with a SOCKS5 server and port transfer functionalities.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1036.004|Masquerade Task or Service|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has disguised their backdoor droppers with naming conventions designed to blend into normal operations.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Windows,IaaS,Network,Linux,macOS,Containers|T1190|Exploit Public-Facing Application|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has exploited CVE-2020-5902, an F5 BIP-IP vulnerability, to drop a Linux backdoor. [BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has also exploited mis-configured Plesk servers.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1049|System Network Connections Discovery|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has used NetCat and PortQry  to enumerate network connections and display the status of related TCP and UDP ports.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has dropped implants in folders named for legitimate software.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers,Network|T1046|Network Service Discovery|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has used SMBTouch, a vulnerability scanner, to determine whether a target is vulnerable to EternalBlue malware.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Windows|T1574.001|DLL Search Order Hijacking|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has executed DLL search order hijacking.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has downloaded additional files and tools onto a compromised host.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|PRE|T1588.001|Malware|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has obtained and used leaked malware, including DoublePulsar, EternalBlue, EternalRocks, and EternalSynergy, in its operations.(Citation: ESET BackdoorDiplomacy Jun 2021)|
|mitre-attack|enterprise-attack|Windows|T1055.001|Dynamic-link Library Injection|[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has dropped legitimate software onto a compromised host and used it to execute malicious DLLs.(Citation: ESET BackdoorDiplomacy Jun 2021)|
