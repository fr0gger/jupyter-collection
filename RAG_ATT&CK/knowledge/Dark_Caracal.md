# Dark Caracal - G0070

**Created**: 2018-10-17T00:14:20.652Z

**Modified**: 2021-10-11T19:08:18.503Z

**Contributors**: 

## Aliases

Dark Caracal

## Description

[Dark Caracal](https://attack.mitre.org/groups/G0070) is threat group that has been attributed to the Lebanese General Directorate of General Security (GDGS) and has operated since at least 2012. (Citation: Lookout Dark Caracal Jan 2018)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[Dark Caracal](https://attack.mitre.org/groups/G0070)'s version of [Bandook](https://attack.mitre.org/software/S0234) communicates with their server over a TCP port using HTTP payloads Base64 encoded and suffixed with the string “&&&”.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Dark Caracal](https://attack.mitre.org/groups/G0070) makes their malware look like Flash Player, Office, or PDF documents in order to entice a user to click on it.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Dark Caracal](https://attack.mitre.org/groups/G0070) has obfuscated strings in [Bandook](https://attack.mitre.org/software/S0234) by base64 encoding, and then encrypting them.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|macOS,Windows,Linux|T1027.002|Software Packing|[Dark Caracal](https://attack.mitre.org/groups/G0070) has used UPX to pack [Bandook](https://attack.mitre.org/software/S0234).(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[Dark Caracal](https://attack.mitre.org/groups/G0070) leveraged a watering hole to serve up malicious code.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1113|Screen Capture|[Dark Caracal](https://attack.mitre.org/groups/G0070) took screenshots using their Windows malware.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1566.003|Spearphishing via Service|[Dark Caracal](https://attack.mitre.org/groups/G0070) spearphished victims via Facebook and Whatsapp.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[Dark Caracal](https://attack.mitre.org/groups/G0070) collected file listings of all default Windows directories.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Dark Caracal](https://attack.mitre.org/groups/G0070)'s version of [Bandook](https://attack.mitre.org/software/S0234) adds a registry key to <code>HKEY_USERS\Software\Microsoft\Windows\CurrentVersion\Run</code> for persistence.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Windows|T1059.003|Windows Command Shell|[Dark Caracal](https://attack.mitre.org/groups/G0070) has used macros in Word documents that would download a second stage if executed.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[Dark Caracal](https://attack.mitre.org/groups/G0070) collected complete contents of the 'Pictures' folder from compromised Windows systems.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Windows|T1218.001|Compiled HTML File|[Dark Caracal](https://attack.mitre.org/groups/G0070) leveraged a compiled HTML file that contained a command to download and run an executable.(Citation: Lookout Dark Caracal Jan 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1437.001|Web Protocols|[Dark Caracal](https://attack.mitre.org/groups/G0070) controls implants using standard HTTP communication.(Citation: Lookout Dark Caracal Jan 2018) |
