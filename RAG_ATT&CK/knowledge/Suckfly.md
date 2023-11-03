# Suckfly - G0039

**Created**: 2017-05-31T21:32:06.777Z

**Modified**: 2022-04-15T16:27:38.682Z

**Contributors**: 

## Aliases

Suckfly

## Description

[Suckfly](https://attack.mitre.org/groups/G0039) is a China-based threat group that has been active since at least 2014. (Citation: Symantec Suckfly March 2016)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|Several tools used by [Suckfly](https://attack.mitre.org/groups/G0039) have been command-line driven.(Citation: Symantec Suckfly May 2016)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers,Network|T1046|Network Service Discovery|[Suckfly](https://attack.mitre.org/groups/G0039) the victim's internal network for hosts with ports 8080, 5900, and 40 open.(Citation: Symantec Suckfly May 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1003|OS Credential Dumping|[Suckfly](https://attack.mitre.org/groups/G0039) used a signed credential-dumping tool to obtain victim account credentials.(Citation: Symantec Suckfly May 2016)|
|mitre-attack|enterprise-attack|macOS,Windows|T1553.002|Code Signing|[Suckfly](https://attack.mitre.org/groups/G0039) has used stolen certificates to sign its malware.(Citation: Symantec Suckfly March 2016)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[Suckfly](https://attack.mitre.org/groups/G0039) used legitimate account credentials that they dumped to navigate the internal victim network as though they were the legitimate account owner.(Citation: Symantec Suckfly May 2016)|
