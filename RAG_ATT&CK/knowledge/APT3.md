# APT3 - G0022

**Created**: 2017-05-31T21:31:55.853Z

**Modified**: 2021-10-01T19:09:20.817Z

**Contributors**: Patrick Sungbahadoor

## Aliases

APT3,Gothic Panda,Pirpi,UPS Team,Buckeye,Threat Group-0110,TG-0110

## Description

[APT3](https://attack.mitre.org/groups/G0022) is a China-based threat group that researchers have attributed to China's Ministry of State Security.(Citation: FireEye Clandestine Wolf)(Citation: Recorded Future APT3 May 2017) This group is responsible for the campaigns known as Operation Clandestine Fox, Operation Clandestine Wolf, and Operation Double Tap.(Citation: FireEye Clandestine Wolf)(Citation: FireEye Operation Double Tap) As of June 2015, the group appears to have shifted from targeting primarily US victims to primarily political organizations in Hong Kong.(Citation: Symantec Buckeye)

In 2017, MITRE developed an APT3 Adversary Emulation Plan.(Citation: APT3 Adversary Emulation Plan)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[APT3](https://attack.mitre.org/groups/G0022) has sent spearphishing emails containing malicious links.(Citation: FireEye Clandestine Wolf)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[APT3](https://attack.mitre.org/groups/G0022) has lured victims into clicking malicious links delivered through spearphishing.(Citation: FireEye Clandestine Wolf)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[APT3](https://attack.mitre.org/groups/G0022) has exploited the Adobe Flash Player vulnerability CVE-2015-3113 and Internet Explorer vulnerability CVE-2014-1776.(Citation: FireEye Clandestine Wolf)(Citation: FireEye Clandestine Fox)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[APT3](https://attack.mitre.org/groups/G0022) has used tools to dump passwords from browsers.(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1564.003|Hidden Window|[APT3](https://attack.mitre.org/groups/G0022) has been known to use <code>-WindowStyle Hidden</code> to conceal [PowerShell](https://attack.mitre.org/techniques/T1059/001) windows.(Citation: FireEye Operation Double Tap)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1090.002|External Proxy|An [APT3](https://attack.mitre.org/groups/G0022) downloader establishes SOCKS5 connections for its initial C2.(Citation: FireEye Operation Double Tap)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,IaaS,Linux,macOS,Google Workspace,SaaS,Network|T1098|Account Manipulation|[APT3](https://attack.mitre.org/groups/G0022) has been known to add created accounts to local admin groups to maintain elevated access.(Citation: aptsim)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,Azure AD,Network|T1110.002|Password Cracking|[APT3](https://attack.mitre.org/groups/G0022) has been known to brute force password hashes to be able to leverage plain text credentials.(Citation: APT3 Adversary Emulation Plan)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1027.002|Software Packing|[APT3](https://attack.mitre.org/groups/G0022) has been known to pack their tools.(Citation: APT3 Adversary Emulation Plan)(Citation: FireEye Clandestine Wolf) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.005|Indicator Removal from Tools|[APT3](https://attack.mitre.org/groups/G0022) has been known to remove indicators of compromise from tools.(Citation: APT3 Adversary Emulation Plan)|
|mitre-attack|enterprise-attack|Windows|T1218.011|Rundll32|[APT3](https://attack.mitre.org/groups/G0022) has a tool that can run DLLs.(Citation: FireEye Clandestine Fox)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[APT3](https://attack.mitre.org/groups/G0022) has a tool that looks for files and directories on the local file system.(Citation: FireEye Clandestine Fox)(Citation: evolution of pirpi)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[APT3](https://attack.mitre.org/groups/G0022) has a tool that can copy files to remote machines.(Citation: FireEye Clandestine Fox)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1041|Exfiltration Over C2 Channel|[APT3](https://attack.mitre.org/groups/G0022) has a tool that exfiltrates data over the C2 channel.(Citation: FireEye Clandestine Fox)|
|mitre-attack|enterprise-attack|Windows|T1546.008|Accessibility Features|[APT3](https://attack.mitre.org/groups/G0022) replaces the Sticky Keys binary <code>C:\Windows\System32\sethc.exe</code> for persistence.(Citation: aptsim)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[APT3](https://attack.mitre.org/groups/G0022) has a tool that can list out currently running processes.(Citation: FireEye Clandestine Fox)(Citation: evolution of pirpi)|
|mitre-attack|enterprise-attack|Windows|T1543.003|Windows Service|[APT3](https://attack.mitre.org/groups/G0022) has a tool that creates a new service for persistence.(Citation: FireEye Operation Double Tap)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[APT3](https://attack.mitre.org/groups/G0022) has a tool that can delete files.(Citation: FireEye Clandestine Fox)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1049|System Network Connections Discovery|[APT3](https://attack.mitre.org/groups/G0022) has a tool that can enumerate current network connections.(Citation: Symantec Buckeye)(Citation: FireEye Clandestine Fox)(Citation: evolution of pirpi)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560.001|Archive via Utility|[APT3](https://attack.mitre.org/groups/G0022) has used tools to compress data before exfilling it.(Citation: aptsim)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1136.001|Local Account|[APT3](https://attack.mitre.org/groups/G0022) has been known to create or enable accounts, such as <code>support_388945a0</code>.(Citation: aptsim)|
|mitre-attack|enterprise-attack|Windows|T1021.002|SMB/Windows Admin Shares|[APT3](https://attack.mitre.org/groups/G0022) will copy files over to Windows Admin Shares (like ADMIN$) as part of lateral movement.(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|Windows|T1021.001|Remote Desktop Protocol|[APT3](https://attack.mitre.org/groups/G0022) enables the Remote Desktop Protocol for persistence.(Citation: aptsim) [APT3](https://attack.mitre.org/groups/G0022) has also interacted with compromised systems to browse and copy files through RDP sessions.(Citation: Twitter Cglyer Status Update APT3 eml)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1078.002|Domain Accounts|[APT3](https://attack.mitre.org/groups/G0022) leverages valid accounts after gaining credentials for use within the victim domain.(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1074.001|Local Data Staging|[APT3](https://attack.mitre.org/groups/G0022) has been known to stage files for exfiltration in a single location.(Citation: aptsim)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[APT3](https://attack.mitre.org/groups/G0022) will identify Microsoft Office documents on the victim's computer.(Citation: aptsim)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[APT3](https://attack.mitre.org/groups/G0022) has a tool that can obtain information about the local system.(Citation: Symantec Buckeye)(Citation: evolution of pirpi)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers|T1552.001|Credentials In Files|[APT3](https://attack.mitre.org/groups/G0022) has a tool that can locate credentials in files on the file system such as those from Firefox or Chrome.(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|Windows|T1574.002|DLL Side-Loading|[APT3](https://attack.mitre.org/groups/G0022) has been known to side load DLLs with a valid version of Chrome with one of their tools.(Citation: FireEye Clandestine Fox)(Citation: FireEye Clandestine Fox Part 2)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[APT3](https://attack.mitre.org/groups/G0022) has a tool that can detect the existence of remote systems.(Citation: Symantec Buckeye)(Citation: FireEye Clandestine Fox)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers|T1069|Permission Groups Discovery|[APT3](https://attack.mitre.org/groups/G0022) has a tool that can enumerate the permissions associated with Windows groups.(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[APT3](https://attack.mitre.org/groups/G0022) obfuscates files or information to help evade defensive measures.(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[APT3](https://attack.mitre.org/groups/G0022) places scripts in the startup folder for persistence.(Citation: FireEye Operation Double Tap)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1087.001|Local Account|[APT3](https://attack.mitre.org/groups/G0022) has used a tool that can obtain info about local and global group users, power users, and administrators.(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[APT3](https://attack.mitre.org/groups/G0022) has used a tool to dump credentials by injecting itself into lsass.exe and triggering with the argument "dig."(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Network|T1056.001|Keylogging|[APT3](https://attack.mitre.org/groups/G0022) has used a keylogging tool that records keystrokes in encrypted files.(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|A keylogging tool used by [APT3](https://attack.mitre.org/groups/G0022) gathers network information from the victim, including the MAC address, IP address, WINS, DHCP server, and gateway.(Citation: Symantec Buckeye)(Citation: evolution of pirpi)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|An [APT3](https://attack.mitre.org/groups/G0022) downloader uses the Windows command <code>"cmd.exe" /C whoami</code> to verify that it is running with the elevated privileges of “System.”(Citation: FireEye Operation Double Tap)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|An [APT3](https://attack.mitre.org/groups/G0022) downloader creates persistence by creating the following scheduled task: <code>schtasks /create /tn "mysc" /tr C:\Users\Public\test.exe /sc ONLOGON /ru "System"</code>.(Citation: FireEye Operation Double Tap)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[APT3](https://attack.mitre.org/groups/G0022) has used PowerShell on victim systems to download and run payloads after exploitation.(Citation: FireEye Operation Double Tap)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|An [APT3](https://attack.mitre.org/groups/G0022) downloader uses the Windows command <code>"cmd.exe" /C whoami</code>. The group also uses a tool to execute commands on remote computers.(Citation: FireEye Operation Double Tap)(Citation: Symantec Buckeye)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1104|Multi-Stage Channels|An [APT3](https://attack.mitre.org/groups/G0022) downloader first establishes a SOCKS5 connection to 192.157.198[.]103 using TCP port 1913; once the server response is verified, it then requests a connection to 192.184.60[.]229 on TCP port 81.(Citation: FireEye Operation Double Tap)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,Network|T1095|Non-Application Layer Protocol|An [APT3](https://attack.mitre.org/groups/G0022) downloader establishes SOCKS5 connections for its initial C2.(Citation: FireEye Operation Double Tap)|
