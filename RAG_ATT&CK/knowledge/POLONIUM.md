# POLONIUM - G1005

**Created**: 2022-07-01T19:07:04.253Z

**Modified**: 2022-08-10T12:31:10.192Z

**Contributors**: 

## Aliases

POLONIUM

## Description

[POLONIUM](https://attack.mitre.org/groups/G1005) is a Lebanon-based group that has primarily targeted Israeli organizations, including critical manufacturing, information technology, and defense industry companies, since at least February 2022. Security researchers assess [POLONIUM](https://attack.mitre.org/groups/G1005) has coordinated their operations with multiple actors affiliated with Iran’s Ministry of Intelligence and Security (MOIS), based on victim overlap as well as common techniques and tooling.(Citation: Microsoft POLONIUM June 2022)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1567.002|Exfiltration to Cloud Storage|[POLONIUM](https://attack.mitre.org/groups/G1005) has exfiltrated stolen data to [POLONIUM](https://attack.mitre.org/groups/G1005)-owned OneDrive and Dropbox accounts.(Citation: Microsoft POLONIUM June 2022) |
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[POLONIUM](https://attack.mitre.org/groups/G1005) has obtained and used tools such as AirVPN and plink in their operations.(Citation: Microsoft POLONIUM June 2022) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102.002|Bidirectional Communication|[POLONIUM](https://attack.mitre.org/groups/G1005) has used OneDrive and DropBox for C2.(Citation: Microsoft POLONIUM June 2022)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1090|Proxy|[POLONIUM](https://attack.mitre.org/groups/G1005) has used the AirVPN service for operational activity.(Citation: Microsoft POLONIUM June 2022)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[POLONIUM](https://attack.mitre.org/groups/G1005) has used valid compromised credentials to gain access to victim environments.(Citation: Microsoft POLONIUM June 2022)|
|mitre-attack|enterprise-attack|Windows,SaaS,IaaS,Linux,macOS,Office 365|T1199|Trusted Relationship|[POLONIUM](https://attack.mitre.org/groups/G1005) has used compromised credentials from an IT company to target downstream customers including a law firm and aviation company.(Citation: Microsoft POLONIUM June 2022)|
|mitre-attack|enterprise-attack|PRE|T1583.006|Web Services|[POLONIUM](https://attack.mitre.org/groups/G1005) has created and used legitimate Microsoft OneDrive accounts for their operations.(Citation: Microsoft POLONIUM June 2022)|
