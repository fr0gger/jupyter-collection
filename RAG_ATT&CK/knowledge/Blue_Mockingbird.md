# Blue Mockingbird - G0108

**Created**: 2020-05-26T20:09:39.139Z

**Modified**: 2021-10-12T21:46:13.007Z

**Contributors**: Tony Lambert, Red Canary

## Aliases

Blue Mockingbird

## Description

[Blue Mockingbird](https://attack.mitre.org/groups/G0108) is a cluster of observed activity involving Monero cryptocurrency-mining payloads in dynamic-link library (DLL) form on Windows systems. The earliest observed Blue Mockingbird tools were created in December 2019.(Citation: RedCanary Mockingbird May 2020)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has obtained and used tools such as [Mimikatz](https://attack.mitre.org/software/S0002).(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1574.012|COR_PROFILER|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used wmic.exe and Windows Registry modifications to set the COR_PROFILER environment variable to execute a malicious DLL whenever a process loads the .NET CLR.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has obfuscated the wallet address in the payload binary.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1047|Windows Management Instrumentation|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used wmic.exe to set environment variables.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1112|Modify Registry|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used Windows Registry modifications to specify a DLL payload.(Citation: RedCanary Mockingbird May 2020)	|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has collected hardware details for the victim's system, including CPU and memory information.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1543.003|Windows Service|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has made their XMRIG payloads persistent as a Windows Service.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has masqueraded their XMRIG payload name by naming it wercplsupporte.dll after the legitimate wercplsupport.dll file.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1134|Access Token Manipulation|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used JuicyPotato to abuse the <code>SeImpersonate</code> token privilege to escalate from web application pool accounts to NT Authority\SYSTEM.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used Mimikatz to retrieve credentials from LSASS memory.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1021.001|Remote Desktop Protocol|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used Remote Desktop to log on to servers interactively and manually copy files to remote hosts.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1021.002|SMB/Windows Admin Shares|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used Windows Explorer to manually copy malicious files to remote hosts over SMB.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used PowerShell reverse TCP shells to issue interactive commands over a network connection.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1090|Proxy|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used frp, ssf, and Venom to establish SOCKS proxy connections.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers|T1496|Resource Hijacking|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used XMRIG to mine cryptocurrency on victim systems.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1546.003|Windows Management Instrumentation Event Subscription|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used mofcomp.exe to establish WMI Event Subscription persistence mechanisms configured from a *.mof file.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used batch script files to automate execution and deployment of payloads.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used Windows Scheduled Tasks to establish persistence on local and remote hosts.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows,IaaS,Network,Linux,macOS,Containers|T1190|Exploit Public-Facing Application|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has gained initial access by exploiting CVE-2019-18935, a vulnerability within Telerik UI for ASP.NET AJAX.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1218.011|Rundll32|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has executed custom-compiled XMRIG miner DLLs using rundll32.exe.(Citation: RedCanary Mockingbird May 2020)|
|mitre-attack|enterprise-attack|Windows|T1218.010|Regsvr32|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has executed custom-compiled XMRIG miner DLLs using regsvr32.exe.(Citation: RedCanary Mockingbird May 2020)	|
|mitre-attack|enterprise-attack|Windows|T1569.002|Service Execution|[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has executed custom-compiled XMRIG miner DLLs by configuring them to execute via the "wercplsupport" service.(Citation: RedCanary Mockingbird May 2020)	|
