# Threat Group-1314 - G0028

**Created**: 2017-05-31T21:31:59.120Z

**Modified**: 2020-03-19T21:58:20.831Z

**Contributors**: 

## Aliases

Threat Group-1314,TG-1314

## Description

[Threat Group-1314](https://attack.mitre.org/groups/G0028) is an unattributed threat group that has used compromised credentials to log into a victim's remote access infrastructure. (Citation: Dell TG-1314)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Threat Group-1314](https://attack.mitre.org/groups/G0028) actors spawned shells on remote systems on a victim network to execute commands.(Citation: Dell TG-1314)|
|mitre-attack|enterprise-attack|Windows|T1021.002|SMB/Windows Admin Shares|[Threat Group-1314](https://attack.mitre.org/groups/G0028) actors mapped network drives using <code>net use</code>.(Citation: Dell TG-1314)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1078.002|Domain Accounts|[Threat Group-1314](https://attack.mitre.org/groups/G0028) actors used compromised domain credentials for the victim's endpoint management platform, Altiris, to move laterally.(Citation: Dell TG-1314)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1072|Software Deployment Tools|[Threat Group-1314](https://attack.mitre.org/groups/G0028) actors used a victim's endpoint management platform, Altiris, for lateral movement.(Citation: Dell TG-1314)|
