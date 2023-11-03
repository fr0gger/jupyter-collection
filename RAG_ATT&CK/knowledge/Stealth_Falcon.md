# Stealth Falcon - G0038

**Created**: 2017-05-31T21:32:06.390Z

**Modified**: 2020-11-23T18:57:19.208Z

**Contributors**: 

## Aliases

Stealth Falcon

## Description

[Stealth Falcon](https://attack.mitre.org/groups/G0038) is a threat group that has conducted targeted spyware attacks against Emirati journalists, activists, and dissidents since at least 2012. Circumstantial evidence suggests there could be a link between this group and the United Arab Emirates (UAE) government, but that has not been confirmed. (Citation: Citizen Lab Stealth Falcon May 2016)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows|T1555.004|Windows Credential Manager|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers passwords from the Windows Credential Vault.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers passwords from multiple sources, including Internet Explorer, Firefox, and Chrome.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers a list of running processes.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers data from the local victim system.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network,Office 365,Azure AD,IaaS,Google Workspace|T1059|Command and Scripting Interpreter|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware uses WMI to script data collection and command execution on the victim.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555|Credentials from Password Stores|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers passwords from multiple sources, including Windows Credential Vault and Outlook.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1041|Exfiltration Over C2 Channel|After data is collected by [Stealth Falcon](https://attack.mitre.org/groups/G0038) malware, it is exfiltrated over the existing C2 channel.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware uses PowerShell commands to perform various functions, including gathering system information via WMI and executing commands from its C2 server.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1573.001|Symmetric Cryptography|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware encrypts C2 traffic using RC4 with a hard-coded key.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers the Address Resolution Protocol (ARP) table from the victim.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware communicates with its C2 server via HTTPS.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware creates a scheduled task entitled “IE Web Cache” to execute a malicious file hourly.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Windows|T1047|Windows Management Instrumentation|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers system information via Windows Management Instrumentation (WMI).(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers the registered user and primary owner name via WMI.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Windows|T1012|Query Registry|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware attempts to determine the installed version of .NET by querying the Registry.(Citation: Citizen Lab Stealth Falcon May 2016)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers system information via WMI, including the system directory, build number, serial number, version, manufacturer, model, and total physical memory.(Citation: Citizen Lab Stealth Falcon May 2016)|
