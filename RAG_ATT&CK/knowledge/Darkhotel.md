# Darkhotel - G0012

**Created**: 2017-05-31T21:31:50.624Z

**Modified**: 2022-10-19T22:07:30.243Z

**Contributors**: Harry, CODEMIZE

## Aliases

Darkhotel,DUBNIUM

## Description

[Darkhotel](https://attack.mitre.org/groups/G0012) is a suspected South Korean threat group that has targeted victims primarily in East Asia since at least 2004. The group's name is based on cyber espionage operations conducted via hotel Internet networks against traveling executives and other select guests. [Darkhotel](https://attack.mitre.org/groups/G0012) has also conducted spearphishing campaigns and infected victims through peer-to-peer and file sharing networks.(Citation: Kaspersky Darkhotel)(Citation: Securelist Darkhotel Aug 2015)(Citation: Microsoft Digital Defense FY20 Sept 2020)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1497.002|User Activity Based Checks|[Darkhotel](https://attack.mitre.org/groups/G0012) has used malware that repeatedly checks the mouse cursor position to determine if a real user is on the system.(Citation: Lastline DarkHotel Just In Time Decryption Nov 2015)|
|mitre-attack|enterprise-attack|Windows,Network|T1124|System Time Discovery|[Darkhotel](https://attack.mitre.org/groups/G0012) malware can obtain system time from a compromised host.(Citation: Lastline DarkHotel Just In Time Decryption Nov 2015)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1497|Virtualization/Sandbox Evasion|[Darkhotel](https://attack.mitre.org/groups/G0012) malware has employed just-in-time decryption of strings to evade sandbox detection.(Citation: Lastline DarkHotel Just In Time Decryption Nov 2015)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Darkhotel](https://attack.mitre.org/groups/G0012) has used malware that is disguised as a Secure Shell (SSH) tool.(Citation: Microsoft DUBNIUM June 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1497.001|System Checks|[Darkhotel](https://attack.mitre.org/groups/G0012) malware has used a series of checks to determine if it's being analyzed; checks include the length of executable names, if a filename ends with <code>.Md5.exe</code>, and if the program is executed from the root of the C:\ drive, as well as checks for sandbox-related libraries.(Citation: Lastline DarkHotel Just In Time Decryption Nov 2015)(Citation: Microsoft DUBNIUM June 2016)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Darkhotel](https://attack.mitre.org/groups/G0012) has exploited Adobe Flash vulnerability CVE-2015-8651 for execution.(Citation: Microsoft DUBNIUM June 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Darkhotel](https://attack.mitre.org/groups/G0012) has used first-stage payloads that download additional malware from C2 servers.(Citation: Microsoft DUBNIUM June 2016)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1573.001|Symmetric Cryptography|[Darkhotel](https://attack.mitre.org/groups/G0012) has used AES-256 and 3DES for C2 communications.(Citation: Microsoft DUBNIUM July 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[Darkhotel](https://attack.mitre.org/groups/G0012) has used malware that searched for files with specific patterns.(Citation: Microsoft DUBNIUM July 2016)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Darkhotel](https://attack.mitre.org/groups/G0012) has sent spearphishing emails with malicious RAR and .LNK attachments.(Citation: Securelist Darkhotel Aug 2015)(Citation: Microsoft DUBNIUM July 2016)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Darkhotel](https://attack.mitre.org/groups/G0012) has collected the hostname, OS version, service pack version, and the processor architecture from the victim’s machine.(Citation: Securelist Darkhotel Aug 2015)(Citation: Microsoft DUBNIUM July 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Darkhotel](https://attack.mitre.org/groups/G0012) has sent spearphishing emails in an attempt to lure users into clicking on a malicious attachments.(Citation: Securelist Darkhotel Aug 2015)(Citation: Microsoft DUBNIUM July 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1140|Deobfuscate/Decode Files or Information|[Darkhotel](https://attack.mitre.org/groups/G0012) has decrypted strings and imports using RC4 during execution.(Citation: Securelist Darkhotel Aug 2015)(Citation: Microsoft DUBNIUM July 2016)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[Darkhotel](https://attack.mitre.org/groups/G0012) used embedded iframes on hotel login portals to redirect selected victims to download malware.(Citation: Kaspersky Darkhotel)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[Darkhotel](https://attack.mitre.org/groups/G0012) has collected the IP address and network adapter information from the victim’s machine.(Citation: Securelist Darkhotel Aug 2015)(Citation: Microsoft DUBNIUM July 2016)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Darkhotel](https://attack.mitre.org/groups/G0012) has obfuscated code using RC4, XOR, and RSA.(Citation: Securelist Darkhotel Aug 2015)(Citation: Microsoft DUBNIUM July 2016)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518.001|Security Software Discovery|[Darkhotel](https://attack.mitre.org/groups/G0012) has searched for anti-malware strings and anti-virus processes running on the system.(Citation: Securelist Darkhotel Aug 2015)(Citation: Microsoft DUBNIUM June 2016) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Darkhotel](https://attack.mitre.org/groups/G0012) malware can collect a list of running processes on a system.(Citation: Securelist Darkhotel Aug 2015)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Darkhotel](https://attack.mitre.org/groups/G0012) has dropped an mspaint.lnk shortcut to disk which launches a shell script that downloads and executes a file.(Citation: Securelist Darkhotel Aug 2015)|
|mitre-attack|enterprise-attack|Windows,Office 365,SaaS,Linux,macOS|T1080|Taint Shared Content|[Darkhotel](https://attack.mitre.org/groups/G0012) used a virus that propagates by infecting executables stored on shared drives.(Citation: Kaspersky Darkhotel)|
|mitre-attack|enterprise-attack|macOS,Windows|T1553.002|Code Signing|[Darkhotel](https://attack.mitre.org/groups/G0012) has used code-signing certificates on its malware that are either forged due to weak keys or stolen. [Darkhotel](https://attack.mitre.org/groups/G0012) has also stolen certificates and signed backdoors and downloaders with them.(Citation: Kaspersky Darkhotel)(Citation: Securelist Darkhotel Aug 2015)|
|mitre-attack|enterprise-attack|Windows|T1091|Replication Through Removable Media|[Darkhotel](https://attack.mitre.org/groups/G0012)'s selective infector modifies executables stored on removable media as a method of spreading across computers.(Citation: Kaspersky Darkhotel)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Network|T1056.001|Keylogging|[Darkhotel](https://attack.mitre.org/groups/G0012) has used a keylogger.(Citation: Kaspersky Darkhotel)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Darkhotel](https://attack.mitre.org/groups/G0012) has been known to establish persistence by adding programs to the Run Registry key.(Citation: Kaspersky Darkhotel)|
