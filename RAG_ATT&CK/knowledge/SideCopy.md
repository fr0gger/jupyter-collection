# SideCopy - G1008

**Created**: 2022-08-07T13:52:07.791Z

**Modified**: 2022-10-24T18:51:09.213Z

**Contributors**: Pooja Natarajan, NEC Corporation India,Hiroki Nagahama, NEC Corporation,Manikantan Srinivasan, NEC Corporation India

## Aliases

SideCopy

## Description

[SideCopy](https://attack.mitre.org/groups/G1008) is a Pakistani threat group that has primarily targeted South Asian countries, including Indian and Afghani government personnel, since at least 2019. [SideCopy](https://attack.mitre.org/groups/G1008)'s name comes from its infection chain that tries to mimic that of [Sidewinder](https://attack.mitre.org/groups/G0121), a suspected Indian threat group.(Citation: MalwareBytes SideCopy Dec 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1608.001|Upload Malware|[SideCopy](https://attack.mitre.org/groups/G1008) has used compromised domains to host its malicious payloads.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518|Software Discovery|[SideCopy](https://attack.mitre.org/groups/G1008) has collected browser information from a compromised host.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|PRE|T1598.002|Spearphishing Attachment|[SideCopy](https://attack.mitre.org/groups/G1008) has crafted generic lures for spam campaigns to collect emails and credentials for targeting efforts.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|PRE|T1584.001|Domains|[SideCopy](https://attack.mitre.org/groups/G1008) has compromised domains for some of their infrastructure, including for C2 and staging malware.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[SideCopy](https://attack.mitre.org/groups/G1008) has identified the OS version of a compromised host.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,IaaS|T1614|System Location Discovery|[SideCopy](https://attack.mitre.org/groups/G1008) has identified the country location of a compromised host.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[SideCopy](https://attack.mitre.org/groups/G1008) has identified the IP address of a compromised host.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Windows|T1218.005|Mshta|[SideCopy](https://attack.mitre.org/groups/G1008) has utilized `mshta.exe` to execute a malicious hta file.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1106|Native API| [SideCopy](https://attack.mitre.org/groups/G1008) has executed malware by calling the API function `CreateProcessW`.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[SideCopy](https://attack.mitre.org/groups/G1008) has used a legitimate DLL file name, `Duser.dll` to disguise a malicious remote access tool.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Windows|T1574.002|DLL Side-Loading|[SideCopy](https://attack.mitre.org/groups/G1008) has used a malicious loader DLL file to execute the `credwiz.exe` process and side-load the malicious payload `Duser.dll`.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518.001|Security Software Discovery|[SideCopy](https://attack.mitre.org/groups/G1008) uses a loader DLL file to collect AV product names from an infected host.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[SideCopy](https://attack.mitre.org/groups/G1008) has sent Microsoft Office Publisher documents to victims that have embedded malicious macros that execute an hta file via calling `mshta.exe`.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[SideCopy](https://attack.mitre.org/groups/G1008) has delivered trojanized executables via spearphishing emails that contacts actor-controlled servers to download malicious payloads.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[SideCopy](https://attack.mitre.org/groups/G1008) has attempted to lure victims into clicking on malicious embedded archive files sent via spearphishing campaigns.(Citation: MalwareBytes SideCopy Dec 2021)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[SideCopy](https://attack.mitre.org/groups/G1008) has sent spearphishing emails with malicious hta file attachments.(Citation: MalwareBytes SideCopy Dec 2021)|
