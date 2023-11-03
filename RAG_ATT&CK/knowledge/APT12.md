# APT12 - G0005

**Created**: 2017-05-31T21:31:47.537Z

**Modified**: 2020-03-30T18:44:59.268Z

**Contributors**: 

## Aliases

APT12,IXESHE,DynCalc,Numbered Panda,DNSCALC

## Description

[APT12](https://attack.mitre.org/groups/G0005) is a threat group that has been attributed to China. The group has targeted a variety of victims including but not limited to media outlets, high-tech companies, and multiple governments.(Citation: Meyers Numbered Panda)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1568.003|DNS Calculation|[APT12](https://attack.mitre.org/groups/G0005) has used multiple variants of [DNS Calculation](https://attack.mitre.org/techniques/T1568/003) including multiplying the first two octets of an IP address and adding the third octet to that value in order to get a resulting command and control port.(Citation: Meyers Numbered Panda)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102.002|Bidirectional Communication|[APT12](https://attack.mitre.org/groups/G0005) has used blogs and WordPress for C2 infrastructure.(Citation: Meyers Numbered Panda)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[APT12](https://attack.mitre.org/groups/G0005) has sent emails with malicious Microsoft Office documents and PDFs attached.(Citation: Moran 2014)(Citation: Trend Micro IXESHE 2012)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[APT12](https://attack.mitre.org/groups/G0005) has exploited multiple vulnerabilities for execution, including Microsoft Office vulnerabilities (CVE-2009-3129, CVE-2012-0158) and vulnerabilities in Adobe Reader and Flash (CVE-2009-4324, CVE-2009-0927, CVE-2011-0609, CVE-2011-0611).(Citation: Moran 2014)(Citation: Trend Micro IXESHE 2012)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[APT12](https://attack.mitre.org/groups/G0005) has attempted to get victims to open malicious Microsoft Word and PDF attachment sent via spearphishing.(Citation: Moran 2014)(Citation: Trend Micro IXESHE 2012)|
