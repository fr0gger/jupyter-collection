# HEXANE - G1001

**Created**: 2018-10-17T00:14:20.652Z

**Modified**: 2023-03-22T04:43:59.082Z

**Contributors**: Dragos Threat Intelligence,Mindaugas Gudzis, BT Security

## Aliases

HEXANE,Lyceum,Siamesekitten,Spirlin

## Description

[HEXANE](https://attack.mitre.org/groups/G1001) is a cyber espionage threat group that has targeted oil & gas, telecommunications, aviation, and internet service provider organizations since at least 2017. Targeted companies have been located in the Middle East and Africa, including Israel, Saudi Arabia, Kuwait, Morocco, and Tunisia. [HEXANE](https://attack.mitre.org/groups/G1001)'s TTPs appear similar to [APT33](https://attack.mitre.org/groups/G0064) and [OilRig](https://attack.mitre.org/groups/G0049) but due to differences in victims and tools it is tracked as a separate entity.(Citation: Dragos Hexane)(Citation: Kaspersky Lyceum October 2021)(Citation: ClearSky Siamesekitten August 2021)(Citation: Accenture Lyceum Targets November 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1588.002|Tool|[HEXANE](https://attack.mitre.org/groups/G1001) has acquired, and sometimes customized, open source tools such as [Mimikatz](https://attack.mitre.org/software/S0002), [Empire](https://attack.mitre.org/software/S0363), VNC remote access software, and DIG.net.(Citation: Kaspersky Lyceum October 2021)(Citation: SecureWorks August 2019)(Citation: Zscaler Lyceum DnsSystem June 2022)|
|mitre-attack|enterprise-attack,ics-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518|Software Discovery|[HEXANE](https://attack.mitre.org/groups/G1001) has enumerated programs installed on an infected machine.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[HEXANE](https://attack.mitre.org/groups/G1001) has collected the hostname of a compromised machine.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[HEXANE](https://attack.mitre.org/groups/G1001) has downloaded additional payloads and malicious scripts onto a compromised host.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1102.002|Bidirectional Communication|[HEXANE](https://attack.mitre.org/groups/G1001) has used cloud services, including OneDrive, for C2.(Citation: Microsoft POLONIUM June 2022)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1567.002|Exfiltration to Cloud Storage|[HEXANE](https://attack.mitre.org/groups/G1001) has used cloud services, including OneDrive, for data exfiltration.(Citation: Microsoft POLONIUM June 2022)|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1583.002|DNS Server|[HEXANE](https://attack.mitre.org/groups/G1001) has set up custom DNS servers to send commands to compromised hosts via TXT records.(Citation: Zscaler Lyceum DnsSystem June 2022)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[HEXANE](https://attack.mitre.org/groups/G1001) has used `net view` to enumerate domain machines.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[HEXANE](https://attack.mitre.org/groups/G1001) has used [Ping](https://attack.mitre.org/software/S0097) and `tracert` for network discovery.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Windows,IaaS,Linux,macOS,Network|T1049|System Network Connections Discovery|[HEXANE](https://attack.mitre.org/groups/G1001) has used [netstat](https://attack.mitre.org/software/S0104) to monitor connections to specific ports.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Windows,Linux,macOS|T1016.001|Internet Connection Discovery|[HEXANE](https://attack.mitre.org/groups/G1001) has used tools including [BITSAdmin](https://attack.mitre.org/software/S0190) to test internet connectivity from compromised hosts.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1053.005|Scheduled Task|[HEXANE](https://attack.mitre.org/groups/G1001) has used a scheduled task to establish persistence for a keylogger.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[HEXANE](https://attack.mitre.org/groups/G1001) has used a VisualBasic script named `MicrosoftUpdator.vbs` for execution of a PowerShell keylogger.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[HEXANE](https://attack.mitre.org/groups/G1001) has used a [Mimikatz](https://attack.mitre.org/software/S0002)-based tool and a PowerShell script to steal passwords from Google Chrome.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[HEXANE](https://attack.mitre.org/groups/G1001) has enumerated processes on targeted systems.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1069.001|Local Groups|[HEXANE](https://attack.mitre.org/groups/G1001) has run `net localgroup` to enumerate local groups.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1555|Credentials from Password Stores|[HEXANE](https://attack.mitre.org/groups/G1001) has run `cmdkey` on victim machines to identify stored credentials.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[HEXANE](https://attack.mitre.org/groups/G1001) has run `whoami` on compromised machines to identify the current user.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1585.002|Email Accounts|[HEXANE](https://attack.mitre.org/groups/G1001) has established email accounts for use in domain registration including for ProtonMail addresses.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[HEXANE](https://attack.mitre.org/groups/G1001) has used Base64-encoded scripts.(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1608.001|Upload Malware|[HEXANE](https://attack.mitre.org/groups/G1001) has staged malware on fraudulent websites set up to impersonate targeted organizations.(Citation: ClearSky Siamesekitten August 2021)|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1585.001|Social Media Accounts|[HEXANE](https://attack.mitre.org/groups/G1001) has established fraudulent LinkedIn accounts impersonating HR department employees to target potential victims with fake job offers.(Citation: ClearSky Siamesekitten August 2021)|
|mitre-attack|enterprise-attack,ics-attack|Windows,macOS,Linux,Office 365,SaaS,Google Workspace|T1534|Internal Spearphishing|[HEXANE](https://attack.mitre.org/groups/G1001) has conducted internal spearphishing attacks against executives, HR, and IT personnel to gain information and access.(Citation: SecureWorks August 2019)|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1589|Gather Victim Identity Information|[HEXANE](https://attack.mitre.org/groups/G1001) has identified specific potential victims at targeted organizations.(Citation: ClearSky Siamesekitten August 2021)|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1591.004|Identify Roles|[HEXANE](https://attack.mitre.org/groups/G1001) has identified executives, HR, and IT staff at victim organizations for further targeting.(Citation: SecureWorks August 2019)(Citation: ClearSky Siamesekitten August 2021)|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1583.001|Domains|[HEXANE](https://attack.mitre.org/groups/G1001) has registered and operated domains for campaigns, often using a security or web technology theme or impersonating the targeted organization.(Citation: SecureWorks August 2019)(Citation: Dragos Hexane)(Citation: ClearSky Siamesekitten August 2021)|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1589.002|Email Addresses|[HEXANE](https://attack.mitre.org/groups/G1001) has targeted executives, human resources staff, and IT personnel for spearphishing.(Citation: SecureWorks August 2019)(Citation: ClearSky Siamesekitten August 2021)
|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1021.001|Remote Desktop Protocol|[HEXANE](https://attack.mitre.org/groups/G1001) has used remote desktop sessions for lateral movement.(Citation: SecureWorks August 2019)|
|mitre-attack|enterprise-attack,ics-attack|macOS,Windows,Linux|T1010|Application Window Discovery|[HEXANE](https://attack.mitre.org/groups/G1001) has used a PowerShell-based keylogging tool to capture the window title.(Citation: SecureWorks August 2019)|
|mitre-attack|enterprise-attack,ics-attack|Windows,macOS,Linux,Network|T1056.001|Keylogging|[HEXANE](https://attack.mitre.org/groups/G1001) has used a PowerShell-based keylogger named `kl.ps1`.(Citation: SecureWorks August 2019)(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Windows|T1059.001|PowerShell|[HEXANE](https://attack.mitre.org/groups/G1001) has used PowerShell-based tools and scripts for discovery and collection on compromised hosts.(Citation: SecureWorks August 2019)(Citation: Kaspersky APT Trends Q1 April 2021)(Citation: Kaspersky Lyceum October 2021)|
|mitre-attack|enterprise-attack,ics-attack|Linux,macOS,Windows|T1204.002|Malicious File|[HEXANE](https://attack.mitre.org/groups/G1001) has relied on victim's executing malicious file attachments delivered via email or embedded within actor-controlled websites to deliver malware.(Citation: SecureWorks August 2019)(Citation: Dragos Hexane)(Citation: ClearSky Siamesekitten August 2021)(Citation: Zscaler Lyceum DnsSystem June 2022)|
|mitre-attack|enterprise-attack,ics-attack|PRE|T1586.002|Email Accounts|[HEXANE](https://attack.mitre.org/groups/G1001) has used compromised accounts to send spearphishing emails.(Citation: SecureWorks August 2019)|
|mitre-attack|enterprise-attack,ics-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1110|Brute Force|[HEXANE](https://attack.mitre.org/groups/G1001) has used brute force attacks to compromise valid credentials.(Citation: SecureWorks August 2019)|
|mitre-attack|enterprise-attack,ics-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers|T1110.003|Password Spraying|[HEXANE](https://attack.mitre.org/groups/G1001) has used password spraying attacks to obtain valid credentials.(Citation: SecureWorks August 2019)|
