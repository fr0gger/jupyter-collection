# Windshift - G0112

**Created**: 2020-06-25T17:16:39.168Z

**Modified**: 2021-04-26T14:37:33.234Z

**Contributors**: 

## Aliases

Windshift,Bahamut

## Description

[Windshift](https://attack.mitre.org/groups/G0112) is a threat group that has been active since at least 2017, targeting specific individuals for surveillance in government departments and critical infrastructure across the Middle East.(Citation: SANS Windshift August 2018)(Citation: objective-see windtail1 dec 2018)(Citation: objective-see windtail2 jan 2019)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack,mobile-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Windshift](https://attack.mitre.org/groups/G0112) has created LNK files in the Startup folder to establish persistence.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Windows|T1047|Windows Management Instrumentation|[Windshift](https://attack.mitre.org/groups/G0112) has used WMI to collect information about target machines.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Windshift](https://attack.mitre.org/groups/G0112) has used malware to identify the computer name of a compromised host.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[Windshift](https://attack.mitre.org/groups/G0112) has used malware to identify the username on a compromised host.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Windshift](https://attack.mitre.org/groups/G0112) has used malware to enumerate active processes.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518|Software Discovery|[Windshift](https://attack.mitre.org/groups/G0112) has used malware to identify installed software.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Windshift](https://attack.mitre.org/groups/G0112) has used tools to deploy additional payloads to compromised hosts.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518.001|Security Software Discovery|[Windshift](https://attack.mitre.org/groups/G0112) has used malware to identify installed AV and commonly used forensic and malware analysis tools.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[Windshift](https://attack.mitre.org/groups/G0112) has used Visual Basic 6 (VB6) payloads.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[Windshift](https://attack.mitre.org/groups/G0112) has used tools that communicate with C2 over HTTP.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Windshift](https://attack.mitre.org/groups/G0112) has used string encoding with floating point calculations.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1566.003|Spearphishing via Service|[Windshift](https://attack.mitre.org/groups/G0112) has used fake personas on social media to engage and target victims.(Citation: SANS Windshift August 2018)	|
|mitre-attack|enterprise-attack,mobile-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[Windshift](https://attack.mitre.org/groups/G0112) has used compromised websites to register custom URL schemes on a remote system.(Citation: objective-see windtail1 dec 2018)|
|mitre-attack|enterprise-attack,mobile-attack|macOS,Windows|T1036.001|Invalid Code Signature|[Windshift](https://attack.mitre.org/groups/G0112) has used revoked certificates to sign malware.(Citation: objective-see windtail1 dec 2018)(Citation: SANS Windshift August 2018)|
|mitre-attack|enterprise-attack,mobile-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Windshift](https://attack.mitre.org/groups/G0112) has sent spearphishing emails with attachment to harvest credentials and deliver malware.(Citation: SANS Windshift August 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[Windshift](https://attack.mitre.org/groups/G0112) has sent spearphishing emails with links to harvest credentials and deliver malware.(Citation: SANS Windshift August 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows,Containers|T1036|Masquerading|[Windshift](https://attack.mitre.org/groups/G0112) has used icons mimicking MS Office files to mask malicious executables.(Citation: objective-see windtail1 dec 2018) [Windshift](https://attack.mitre.org/groups/G0112) has also attempted to hide executables by changing the file extension to ".scr" to mimic Windows screensavers.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[Windshift](https://attack.mitre.org/groups/G0112) has used links embedded in e-mails to lure victims into executing malicious code.(Citation: SANS Windshift August 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Windshift](https://attack.mitre.org/groups/G0112) has used e-mail attachments to lure victims into executing malicious code.(Citation: SANS Windshift August 2018)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1533|Data from Local System|[Windshift](https://attack.mitre.org/groups/G0112) has exfiltrated local account data and calendar information as part of Operation ROCK.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1512|Video Capture|[Windshift](https://attack.mitre.org/groups/G0112) has included video recording in the malicious apps deployed as part of Operation BULL.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1407|Download New Code at Runtime|[Windshift](https://attack.mitre.org/groups/G0112) has included malware functionality capable of downloading new DEX files at runtime during Operation BULL.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1417.001|Keylogging|[Windshift](https://attack.mitre.org/groups/G0112) has included keylogging capabilities as part of Operation ROCK.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|iOS,Android|T1636.003|Contact List|[Windshift](https://attack.mitre.org/groups/G0112) has included contact list exfiltration in the malicious apps deployed as part of Operation BULL.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1406|Obfuscated Files or Information|[Windshift](https://attack.mitre.org/groups/G0112) has encrypted application strings using AES in ECB mode and Blowfish, and stored strings encoded in hex during Operation BULL. Further, in Operation BULL, encryption keys were stored within the application’s launcher icon file.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1636.004|SMS Messages|[Windshift](https://attack.mitre.org/groups/G0112) has included SMS message exfiltration in the malicious apps deployed as part of Operation BULL and Operation ROCK.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1521.001|Symmetric Cryptography|[Windshift](https://attack.mitre.org/groups/G0112) has encrypted C2 communications using AES in CBC mode during Operation BULL and Operation ROCK.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1632.001|Code Signing Policy Modification|[Windshift](https://attack.mitre.org/groups/G0112) has installed malicious MDM profiles on iOS devices as part of Operation ROCK.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1420|File and Directory Discovery|[Windshift](https://attack.mitre.org/groups/G0112) has included file enumeration in the malicious apps deployed as part of Operation BULL and Operation ROCK.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1430|Location Tracking|[Windshift](https://attack.mitre.org/groups/G0112) has included location tracking capabilities in the malicious apps deployed as part of Operation BULL and Operation ROCK.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1426|System Information Discovery|[Windshift](https://attack.mitre.org/groups/G0112) has included system information enumeration in the malicious apps deployed as part of Operation BULL and Operation ROCK.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1429|Audio Capture|[Windshift](https://attack.mitre.org/groups/G0112) has included phone call and audio recording capabilities in the malicious apps deployed as part of Operation BULL and Operation ROCK.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1627.001|Geofencing|[Windshift](https://attack.mitre.org/groups/G0112) has region-locked their malicious applications during their Operation BULL campaign.(Citation: BlackBerry Bahamut)|
|mitre-attack|enterprise-attack,mobile-attack|Android,iOS|T1633.001|System Checks|[Windshift](https://attack.mitre.org/groups/G0112) has deployed anti-analysis capabilities during their Operation BULL campaign.(Citation: BlackBerry Bahamut)|
