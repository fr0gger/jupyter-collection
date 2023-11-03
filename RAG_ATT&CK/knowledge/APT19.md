# APT19 - G0073

**Created**: 2018-10-17T00:14:20.652Z

**Modified**: 2023-03-21T20:44:02.443Z

**Contributors**: FS-ISAC,Darren Spruell

## Aliases

APT19,Codoso,C0d0so0,Codoso Team,Sunshop Group

## Description

[APT19](https://attack.mitre.org/groups/G0073) is a Chinese-based threat group that has targeted a variety of industries, including defense, finance, energy, pharmaceutical, telecommunications, high tech, education, manufacturing, and legal services. In 2017, a phishing campaign was used to target seven law and investment firms. (Citation: FireEye APT19) Some analysts track [APT19](https://attack.mitre.org/groups/G0073) and [Deep Panda](https://attack.mitre.org/groups/G0009) as the same group, but it is unclear from open source information if the groups are the same. (Citation: ICIT China's Espionage Jul 2016) (Citation: FireEye APT Groups) (Citation: Unit 42 C0d0so0 Jan 2016)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[APT19](https://attack.mitre.org/groups/G0073) used Base64 to obfuscate executed commands.(Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[APT19](https://attack.mitre.org/groups/G0073) has obtained and used publicly-available tools like [Empire](https://attack.mitre.org/software/S0363).(Citation: NCSC Joint Report Public Tools)(Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1564.003|Hidden Window|[APT19](https://attack.mitre.org/groups/G0073) used <code>-W Hidden</code> to conceal [PowerShell](https://attack.mitre.org/techniques/T1059/001) windows by setting the WindowStyle parameter to hidden. (Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|Windows|T1218.011|Rundll32|[APT19](https://attack.mitre.org/groups/G0073) configured its payload to inject into the rundll32.exe.(Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|Windows|T1543.003|Windows Service|An [APT19](https://attack.mitre.org/groups/G0073) Port 22 malware variant registers itself as a service.(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Windows|T1574.002|DLL Side-Loading|[APT19](https://attack.mitre.org/groups/G0073) launched an HTTP malware variant and a Port 22 malware variant using a legitimate executable that loaded the malicious DLL.(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[APT19](https://attack.mitre.org/groups/G0073) attempted to get users to launch malicious attachments delivered via spearphishing emails.(Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[APT19](https://attack.mitre.org/groups/G0073) used Base64 to obfuscate payloads.(Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[APT19](https://attack.mitre.org/groups/G0073) used an HTTP malware variant and a Port 22 malware variant to collect the victim’s username.(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[APT19](https://attack.mitre.org/groups/G0073) used PowerShell commands to execute payloads.(Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network,Office 365,Azure AD,IaaS,Google Workspace|T1059|Command and Scripting Interpreter|[APT19](https://attack.mitre.org/groups/G0073) downloaded and launched code within a SCT file.(Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[APT19](https://attack.mitre.org/groups/G0073) sent spearphishing emails with malicious attachments in RTF and XLSM formats to deliver initial exploits.(Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1132.001|Standard Encoding|An [APT19](https://attack.mitre.org/groups/G0073) HTTP malware variant used Base64 to encode communications to the C2 server.(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[APT19](https://attack.mitre.org/groups/G0073) used HTTP for C2 communications. [APT19](https://attack.mitre.org/groups/G0073) also used an HTTP malware variant to communicate over HTTP for C2.(Citation: FireEye APT19)(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1140|Deobfuscate/Decode Files or Information|An [APT19](https://attack.mitre.org/groups/G0073) HTTP malware variant decrypts strings using single-byte XOR keys.(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|An [APT19](https://attack.mitre.org/groups/G0073) HTTP malware variant establishes persistence by setting the Registry key <code>HKCU\Software\Microsoft\Windows\CurrentVersion\Run\Windows Debug Tools-%LOCALAPPDATA%\</code>.(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Windows|T1218.010|Regsvr32|[APT19](https://attack.mitre.org/groups/G0073) used Regsvr32 to bypass application control techniques.(Citation: FireEye APT19)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[APT19](https://attack.mitre.org/groups/G0073) used an HTTP malware variant and a Port 22 malware variant to collect the MAC address and IP address from the victim’s machine.(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Windows|T1112|Modify Registry|[APT19](https://attack.mitre.org/groups/G0073) uses a Port 22 malware variant to modify several Registry keys.(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[APT19](https://attack.mitre.org/groups/G0073) performed a watering hole attack on forbes.com in 2014 to compromise targets.(Citation: Unit 42 C0d0so0 Jan 2016)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[APT19](https://attack.mitre.org/groups/G0073) collected system architecture information. [APT19](https://attack.mitre.org/groups/G0073) used an HTTP malware variant and a Port 22 malware variant to gather the hostname and CPU information from the victim’s machine.(Citation: FireEye APT19)(Citation: Unit 42 C0d0so0 Jan 2016)|
