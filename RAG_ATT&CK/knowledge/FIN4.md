# FIN4 - G0085

**Created**: 2019-01-31T02:01:45.129Z

**Modified**: 2023-02-01T21:27:44.778Z

**Contributors**: 

## Aliases

FIN4

## Description

[FIN4](https://attack.mitre.org/groups/G0085) is a financially-motivated threat group that has targeted confidential information related to the public financial market, particularly regarding healthcare and pharmaceutical companies, since at least 2013.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye FIN4 Stealing Insider NOV 2014) [FIN4](https://attack.mitre.org/groups/G0085) is unique in that they do not infect victims with typical persistent malware, but rather they focus on capturing credentials authorized to access email and other non-public correspondence.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[FIN4](https://attack.mitre.org/groups/G0085) has lured victims to click malicious links delivered via spearphishing emails (often sent from compromised accounts).(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
|mitre-attack|enterprise-attack|Windows,Office 365,Linux,macOS,Google Workspace|T1564.008|Email Hiding Rules|[FIN4](https://attack.mitre.org/groups/G0085) has created rules in victims' Microsoft Outlook accounts to automatically delete emails containing words such as “hacked," "phish," and “malware" in a likely attempt to prevent organizations from communicating about their activities.(Citation: FireEye Hacking FIN4 Dec 2014)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[FIN4](https://attack.mitre.org/groups/G0085) has used spearphishing emails containing attachments (which are often stolen, legitimate documents sent from compromised accounts) with embedded malicious macros.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[FIN4](https://attack.mitre.org/groups/G0085) has lured victims to launch malicious attachments delivered via spearphishing emails (often sent from compromised accounts).(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[FIN4](https://attack.mitre.org/groups/G0085) has used VBA macros to display a dialog box and collect victim credentials.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Network|T1056.001|Keylogging|[FIN4](https://attack.mitre.org/groups/G0085) has captured credentials via fake Outlook Web App (OWA) login pages and has also used a .NET based keylogger.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1056.002|GUI Input Capture|[FIN4](https://attack.mitre.org/groups/G0085) has presented victims with spoofed Windows Authentication prompts to collect their credentials.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[FIN4](https://attack.mitre.org/groups/G0085) has used spearphishing emails (often sent from compromised accounts) containing malicious links.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
|mitre-attack|enterprise-attack|Office 365,Windows,Google Workspace|T1114.002|Remote Email Collection|[FIN4](https://attack.mitre.org/groups/G0085) has accessed and hijacked online email communications using stolen credentials.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1090.003|Multi-hop Proxy|[FIN4](https://attack.mitre.org/groups/G0085) has used Tor to log in to victims' email accounts.(Citation: FireEye Hacking FIN4 Dec 2014)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[FIN4](https://attack.mitre.org/groups/G0085) has used legitimate credentials to hijack email communications.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[FIN4](https://attack.mitre.org/groups/G0085) has used HTTP POST requests to transmit data.(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)|
