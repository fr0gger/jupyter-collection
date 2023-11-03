# GOLD SOUTHFIELD - G0115

**Created**: 2020-09-22T19:41:27.845Z

**Modified**: 2023-03-28T20:49:53.223Z

**Contributors**: Thijn Bukkems, Amazon

## Aliases

GOLD SOUTHFIELD,Pinchy Spider

## Description

[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) is a financially motivated threat group active since at least 2018 that operates the [REvil](https://attack.mitre.org/software/S0496) Ransomware-as-a Service (RaaS). [GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) provides backend infrastructure for affiliates recruited on underground forums to perpetrate high value deployments. By early 2020, [GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) started capitalizing on the new trend of stealing data and further extorting the victim to pay for their data to not get publicly leaked.(Citation: Secureworks REvil September 2019)(Citation: Secureworks GandCrab and REvil September 2019)(Citation: Secureworks GOLD SOUTHFIELD)(Citation: CrowdStrike Evolution of Pinchy Spider July 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1059.001|PowerShell|[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has staged and executed PowerShell scripts on compromised hosts.(Citation: Tetra Defense Sodinokibi March 2020)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has executed base64 encoded PowerShell scripts on compromised hosts.(Citation: Tetra Defense Sodinokibi March 2020)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1113|Screen Capture|[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has used the remote monitoring and management tool ConnectWise to obtain screen captures from victim's machines.(Citation: Tetra Defense Sodinokibi March 2020)|
|mitre-attack|enterprise-attack,ics-attack|Linux,Windows,macOS|T1219|Remote Access Software|[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has used the cloud-based remote management and monitoring tool "ConnectWise Control" to deploy [REvil](https://attack.mitre.org/software/S0496).(Citation: Tetra Defense Sodinokibi March 2020)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1195.002|Compromise Software Supply Chain|[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has distributed ransomware by backdooring software installers via a strategic web compromise of the site hosting Italian WinRAR.(Citation: Secureworks REvil September 2019)(Citation: Secureworks GandCrab and REvil September 2019)(Citation: Secureworks GOLD SOUTHFIELD)|
|mitre-attack|enterprise-attack,ics-attack|Windows,IaaS,Network,Linux,macOS,Containers|T1190|Exploit Public-Facing Application|[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has exploited Oracle WebLogic vulnerabilities for initial compromise.(Citation: Secureworks REvil September 2019)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows,SaaS,Office 365,Google Workspace|T1566|Phishing|[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has conducted malicious spam (malspam) campaigns to gain access to victim's machines.(Citation: Secureworks REvil September 2019)|
|mitre-attack|enterprise-attack,ics-attack|Windows,SaaS,IaaS,Linux,macOS,Office 365|T1199|Trusted Relationship|[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has breached Managed Service Providers (MSP's) to deliver malware to MSP customers.(Citation: Secureworks REvil September 2019)|
|mitre-attack|enterprise-attack,ics-attack|Windows,Linux,Containers,macOS|T1133|External Remote Services|[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has used publicly-accessible RDP and remote management and monitoring (RMM) servers to gain access to victim machines.(Citation: Secureworks REvil September 2019)	|
