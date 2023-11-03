# Poseidon Group - G0033

**Created**: 2017-05-31T21:32:04.179Z

**Modified**: 2020-03-18T20:25:54.945Z

**Contributors**: 

## Aliases

Poseidon Group

## Description

[Poseidon Group](https://attack.mitre.org/groups/G0033) is a Portuguese-speaking threat group that has been active since at least 2005. The group has a history of using information exfiltrated from victims to blackmail victim companies into contracting the [Poseidon Group](https://attack.mitre.org/groups/G0033) as a security firm. (Citation: Kaspersky Poseidon Group)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1087.001|Local Account|[Poseidon Group](https://attack.mitre.org/groups/G0033) searches for administrator accounts on both the local victim machine and the network.(Citation: Kaspersky Poseidon Group)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Poseidon Group](https://attack.mitre.org/groups/G0033) tools attempt to spoof anti-virus processes as a means of self-defense.(Citation: Kaspersky Poseidon Group)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1087.002|Domain Account|[Poseidon Group](https://attack.mitre.org/groups/G0033) searches for administrator accounts on both the local victim machine and the network.(Citation: Kaspersky Poseidon Group)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|The [Poseidon Group](https://attack.mitre.org/groups/G0033)'s Information Gathering Tool (IGT) includes PowerShell components.(Citation: Kaspersky Poseidon Group)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1007|System Service Discovery|After compromising a victim, [Poseidon Group](https://attack.mitre.org/groups/G0033) discovers all running services.(Citation: Kaspersky Poseidon Group)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1049|System Network Connections Discovery|[Poseidon Group](https://attack.mitre.org/groups/G0033) obtains and saves information about victim network interfaces and addresses.(Citation: Kaspersky Poseidon Group)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1003|OS Credential Dumping|[Poseidon Group](https://attack.mitre.org/groups/G0033) conducts credential dumping on victims, with a focus on obtaining credentials belonging to domain and database servers.(Citation: Kaspersky Poseidon Group)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|After compromising a victim, [Poseidon Group](https://attack.mitre.org/groups/G0033) lists all running processes.(Citation: Kaspersky Poseidon Group)|
