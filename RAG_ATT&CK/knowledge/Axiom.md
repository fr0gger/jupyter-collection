# Axiom - G0001

**Created**: 2017-05-31T21:31:45.629Z

**Modified**: 2023-03-20T22:03:44.661Z

**Contributors**: 

## Aliases

Axiom,Group 72

## Description

[Axiom](https://attack.mitre.org/groups/G0001) is a suspected Chinese cyber espionage group that has targeted the aerospace, defense, government, manufacturing, and media sectors since at least 2008. Some reporting suggests a degree of overlap between [Axiom](https://attack.mitre.org/groups/G0001) and [Winnti Group](https://attack.mitre.org/groups/G0044) but the two groups appear to be distinct based on differences in reporting on TTPs and targeting.(Citation: Kaspersky Winnti April 2013)(Citation: Kaspersky Winnti June 2015)(Citation: Novetta Winnti April 2015)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[Axiom](https://attack.mitre.org/groups/G0001) has collected data from a compromised network.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|PRE|T1583.002|DNS Server|[Axiom](https://attack.mitre.org/groups/G0001) has acquired dynamic DNS services for use in the targeting of intended victims.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|PRE|T1583.003|Virtual Private Server|[Axiom](https://attack.mitre.org/groups/G0001) has used VPS hosting providers in targeting of intended victims.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560|Archive Collected Data|[Axiom](https://attack.mitre.org/groups/G0001) has compressed and encrypted data prior to exfiltration.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|Windows|T1563.002|RDP Hijacking|[Axiom](https://attack.mitre.org/groups/G0001) has targeted victims with remote administration tools including RDP.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[Axiom](https://attack.mitre.org/groups/G0001) has used previously compromised administrative accounts to escalate privileges.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|PRE|T1584.005|Botnet|[Axiom](https://attack.mitre.org/groups/G0001) has used large groups of compromised machines for use as proxy nodes.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1553|Subvert Trust Controls|[Axiom](https://attack.mitre.org/groups/G0001) has used digital certificates to deliver malware.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[Axiom](https://attack.mitre.org/groups/G0001) has used watering hole attacks to gain access.(Citation: Cisco Group 72)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,SaaS,Office 365,Google Workspace|T1566|Phishing|[Axiom](https://attack.mitre.org/groups/G0001) has used spear phishing to initially compromise victims.(Citation: Cisco Group 72)(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Axiom](https://attack.mitre.org/groups/G0001) has used exploits for multiple vulnerabilities including CVE-2014-0322, CVE-2012-4792, CVE-2012-1889, and CVE-2013-3893.(Citation: Cisco Group 72)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1001.002|Steganography|[Axiom](https://attack.mitre.org/groups/G0001) has used steganography to hide its C2 communications.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|Windows,IaaS,Network,Linux,macOS,Containers|T1190|Exploit Public-Facing Application|[Axiom](https://attack.mitre.org/groups/G0001) has been observed using SQL injection to gain access to systems.(Citation: Novetta-Axiom)(Citation: Cisco Group 72)|
|mitre-attack|enterprise-attack|Windows|T1546.008|Accessibility Features|[Axiom](https://attack.mitre.org/groups/G0001) actors have been known to use the Sticky Keys replacement within RDP sessions to obtain persistence.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|Windows|T1021.001|Remote Desktop Protocol|[Axiom](https://attack.mitre.org/groups/G0001) has used RDP during operations.(Citation: Novetta-Axiom)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1003|OS Credential Dumping|[Axiom](https://attack.mitre.org/groups/G0001) has been known to dump credentials.(Citation: Novetta-Axiom)|
