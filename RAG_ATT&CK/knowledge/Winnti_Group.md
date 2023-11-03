# Winnti Group - G0044

**Created**: 2017-05-31T21:32:08.682Z

**Modified**: 2023-03-20T22:02:53.982Z

**Contributors**: Edward Millington

## Aliases

Winnti Group,Blackfly

## Description

[Winnti Group](https://attack.mitre.org/groups/G0044) is a threat group with Chinese origins that has been active since at least 2010. The group has heavily targeted the gaming industry, but it has also expanded the scope of its targeting.(Citation: Kaspersky Winnti April 2013)(Citation: Kaspersky Winnti June 2015)(Citation: Novetta Winnti April 2015) Some reporting suggests a number of other groups, including [Axiom](https://attack.mitre.org/groups/G0001), [APT17](https://attack.mitre.org/groups/G0025), and [Ke3chang](https://attack.mitre.org/groups/G0004), are closely linked to [Winnti Group](https://attack.mitre.org/groups/G0044).(Citation: 401 TRG Winnti Umbrella May 2018)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Winnti Group](https://attack.mitre.org/groups/G0044) has downloaded an auxiliary program named ff.exe to infected machines.(Citation: Kaspersky Winnti April 2013)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[Winnti Group](https://attack.mitre.org/groups/G0044) has used a program named ff.exe to search for specific documents on compromised hosts.(Citation: Kaspersky Winnti April 2013)|
|mitre-attack|enterprise-attack|PRE|T1583.001|Domains|[Winnti Group](https://attack.mitre.org/groups/G0044) has registered domains for C2 that mimicked sites of their intended targets.(Citation: Kaspersky Winnti April 2013)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1014|Rootkit|[Winnti Group](https://attack.mitre.org/groups/G0044) used a rootkit to modify typical server functionality.(Citation: Kaspersky Winnti April 2013)|
|mitre-attack|enterprise-attack|macOS,Windows|T1553.002|Code Signing|[Winnti Group](https://attack.mitre.org/groups/G0044) used stolen certificates to sign its malware.(Citation: Kaspersky Winnti April 2013)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Winnti Group](https://attack.mitre.org/groups/G0044) looked for a specific process running on infected servers.(Citation: Kaspersky Winnti April 2013)|
