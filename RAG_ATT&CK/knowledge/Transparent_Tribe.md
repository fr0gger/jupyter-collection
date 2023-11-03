# Transparent Tribe - G0134

**Created**: 2021-09-02T15:14:33.738Z

**Modified**: 2022-09-22T20:27:21.053Z

**Contributors**: Manikantan Srinivasan, NEC Corporation India,Pooja Natarajan, NEC Corporation India,Hiroki Nagahama, NEC Corporation

## Aliases

Transparent Tribe,COPPER FIELDSTONE,APT36,Mythic Leopard,ProjectM

## Description

[Transparent Tribe](https://attack.mitre.org/groups/G0134) is a suspected Pakistan-based threat group that has been active since at least 2013, primarily targeting diplomatic, defense, and research organizations in India and Afghanistan.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Kaspersky Transparent Tribe August 2020)(Citation: Talos Transparent Tribe May 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has used websites with malicious hyperlinks and iframes to infect targeted victims with [Crimson](https://attack.mitre.org/software/S0115), [njRAT](https://attack.mitre.org/software/S0385), and other malicious tools.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Unit 42 ProjectM March 2016)(Citation: Talos Transparent Tribe May 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has embedded links to malicious downloads in e-mails.(Citation: Talos Oblique RAT March 2021)(Citation: Talos Transparent Tribe May 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has directed users to open URLs hosting malicious content.(Citation: Talos Oblique RAT March 2021)(Citation: Talos Transparent Tribe May 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1564.001|Hidden Files and Directories|[Transparent Tribe](https://attack.mitre.org/groups/G0134) can hide legitimate directories and replace them with malicious copies of the same name.(Citation: Kaspersky Transparent Tribe August 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Transparent Tribe](https://attack.mitre.org/groups/G0134) can mimic legitimate Windows directories by using the same icons and names.(Citation: Kaspersky Transparent Tribe August 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1568|Dynamic Resolution|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has used dynamic DNS services to set up C2.(Citation: Proofpoint Operation Transparent Tribe March 2016)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has crafted VBS-based malicious documents.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Kaspersky Transparent Tribe August 2020)	 |
|mitre-attack|enterprise-attack|PRE|T1583.001|Domains|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has registered domains to mimic file sharing, government, defense, and research websites for use in targeted campaigns.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Talos Transparent Tribe May 2021)|
|mitre-attack|enterprise-attack|PRE|T1584.001|Domains|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has compromised domains for use in targeted malicious campaigns.(Citation: Proofpoint Operation Transparent Tribe March 2016)|
|mitre-attack|enterprise-attack|PRE|T1608.004|Drive-by Target|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has set up websites with malicious hyperlinks and iframes to infect targeted victims with [Crimson](https://attack.mitre.org/software/S0115), [njRAT](https://attack.mitre.org/software/S0385), and other malicious tools.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Unit 42 ProjectM March 2016)(Citation: Talos Transparent Tribe May 2021)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has sent spearphishing e-mails with attachments to deliver malicious payloads.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Kaspersky Transparent Tribe August 2020)(Citation: Talos Oblique RAT March 2021)(Citation: Talos Transparent Tribe May 2021)(Citation: Unit 42 ProjectM March 2016)	 |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has used weaponized documents in e-mail to compromise targeted systems.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Kaspersky Transparent Tribe August 2020)(Citation: Talos Oblique RAT March 2021)(Citation: Talos Transparent Tribe May 2021)(Citation: Unit 42 ProjectM March 2016)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has crafted malicious files to exploit CVE-2012-0158 and CVE-2010-3333 for execution.(Citation: Proofpoint Operation Transparent Tribe March 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Transparent Tribe](https://attack.mitre.org/groups/G0134) has dropped encoded executables on compromised hosts.(Citation: Proofpoint Operation Transparent Tribe March 2016)|
