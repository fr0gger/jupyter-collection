# FIN8 - G0061

**Created**: 2018-04-18T17:59:24.739Z

**Modified**: 2023-03-22T03:52:13.089Z

**Contributors**: Daniyal Naeem, BT Security

## Aliases

FIN8

## Description

[FIN8](https://attack.mitre.org/groups/G0061) is a financially motivated threat group known to launch tailored spearphishing campaigns targeting the retail, restaurant, and hospitality industries. (Citation: FireEye Obfuscation June 2017) (Citation: FireEye Fin8 May 2016)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows|T1055.004|Asynchronous Procedure Call|[FIN8](https://attack.mitre.org/groups/G0061) has injected malicious code into a new svchost.exe process.(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[FIN8](https://attack.mitre.org/groups/G0061) has used HTTPS for command and control.(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Windows|T1546.003|Windows Management Instrumentation Event Subscription|[FIN8](https://attack.mitre.org/groups/G0061) has used WMI event subscriptions for persistence.(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Windows|T1134.001|Token Impersonation/Theft|[FIN8](https://attack.mitre.org/groups/G0061) has used a malicious framework designed to impersonate the lsass.exe/vmtoolsd.exe token.(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102|Web Service|[FIN8](https://attack.mitre.org/groups/G0061) has used <code>sslip.io</code>, a free IP to domain mapping service that also makes SSL certificate generation easier for traffic encryption, as part of their command and control.(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Windows|T1482|Domain Trust Discovery|[FIN8](https://attack.mitre.org/groups/G0061) has retrieved a list of trusted domains by using <code>[Nltest](https://attack.mitre.org/software/S0359).exe /domain_trusts</code>.(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[FIN8](https://attack.mitre.org/groups/G0061) has used emails with malicious links to lure victims into installing malware.(Citation: FireEye Obfuscation June 2017)(Citation: FireEye Fin8 May 2016)(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Windows|T1021.001|Remote Desktop Protocol|[FIN8](https://attack.mitre.org/groups/G0061) has used RDP for lateral movement.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Windows|T1021.002|SMB/Windows Admin Shares|[FIN8](https://attack.mitre.org/groups/G0061) has attempted to map to C$ on enumerated hosts to test the scope of their current credentials/context.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Windows|T1070.001|Clear Windows Event Logs|[FIN8](https://attack.mitre.org/groups/G0061) has cleared logs during post compromise cleanup activities.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Windows|T1112|Modify Registry|[FIN8](https://attack.mitre.org/groups/G0061) has deleted Registry keys during post compromise cleanup activities.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1573.002|Asymmetric Cryptography|[FIN8](https://attack.mitre.org/groups/G0061) has used the Plink utility to tunnel RDP back to C2 infrastructure.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1048.003|Exfiltration Over Unencrypted Non-C2 Protocol|[FIN8](https://attack.mitre.org/groups/G0061) has used FTP to exfiltrate collected data.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[FIN8](https://attack.mitre.org/groups/G0061) has used scheduled tasks to maintain RDP backdoors.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Windows|T1047|Windows Management Instrumentation|[FIN8](https://attack.mitre.org/groups/G0061)'s malicious spearphishing payloads use WMI to launch malware and spawn cmd.exe execution. [FIN8](https://attack.mitre.org/groups/G0061) has also used WMIC for lateral movement as well as during and post compromise cleanup activities.(Citation: FireEye Obfuscation June 2017)(Citation: Bitdefender FIN8 July 2021)(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[FIN8](https://attack.mitre.org/groups/G0061) has deleted tmp and prefetch files during post compromise cleanup activities.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[FIN8](https://attack.mitre.org/groups/G0061) has distributed targeted emails containing Word documents with embedded malicious macros.(Citation: FireEye Obfuscation June 2017)(Citation: FireEye Fin8 May 2016)(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560.001|Archive via Utility|[FIN8](https://attack.mitre.org/groups/G0061) has used RAR to compress collected data before exfiltration.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[FIN8](https://attack.mitre.org/groups/G0061) has used remote code execution to download subsequent payloads.(Citation: FireEye Fin8 May 2016)(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[FIN8](https://attack.mitre.org/groups/G0061) has used environment variables and standard input (stdin) to obfuscate command-line arguments. [FIN8](https://attack.mitre.org/groups/G0061) also obfuscates malicious macros delivered as payloads.(Citation: FireEye Obfuscation June 2017)(Citation: FireEye Know Your Enemy FIN8 Aug 2016)(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[FIN8](https://attack.mitre.org/groups/G0061)'s malicious spearphishing payloads are executed as [PowerShell](https://attack.mitre.org/techniques/T1059/001). [FIN8](https://attack.mitre.org/groups/G0061) has also used [PowerShell](https://attack.mitre.org/techniques/T1059/001) for lateral movement and credential access.(Citation: FireEye Obfuscation June 2017)(Citation: Bitdefender FIN8 July 2021)(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[FIN8](https://attack.mitre.org/groups/G0061) has distributed targeted emails containing links to malicious documents with embedded macros.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[FIN8](https://attack.mitre.org/groups/G0061) has used malicious e-mail attachments to lure victims into executing malware.(Citation: FireEye Obfuscation June 2017)(Citation: FireEye Fin8 May 2016)(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[FIN8](https://attack.mitre.org/groups/G0061) has used [dsquery](https://attack.mitre.org/software/S0105) and other Active Directory utilities to enumerate hosts; they have also used <code>nltest.exe /dclist</code> to retrieve a list of domain controllers.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS|T1074.002|Remote Data Staging|[FIN8](https://attack.mitre.org/groups/G0061) aggregates staged data from a network into a single location.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[FIN8](https://attack.mitre.org/groups/G0061) harvests credentials using Invoke-Mimikatz or Windows Credentials Editor (WCE).(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1068|Exploitation for Privilege Escalation|[FIN8](https://attack.mitre.org/groups/G0061) has exploited the CVE-2016-0167 local vulnerability.(Citation: FireEye Fin8 May 2016)(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[FIN8](https://attack.mitre.org/groups/G0061) has used a Batch file to automate frequently executed post compromise cleanup activities.(Citation: FireEye Know Your Enemy FIN8 Aug 2016) [FIN8](https://attack.mitre.org/groups/G0061) has also executed commands remotely via [cmd](https://attack.mitre.org/software/S0106).(Citation: FireEye Obfuscation June 2017)(Citation: Bitdefender FIN8 July 2021)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518.001|Security Software Discovery|[FIN8](https://attack.mitre.org/groups/G0061) has used Registry keys to detect and avoid executing in potential sandboxes.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[FIN8](https://attack.mitre.org/groups/G0061) has used valid accounts for persistence and lateral movement.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)|
