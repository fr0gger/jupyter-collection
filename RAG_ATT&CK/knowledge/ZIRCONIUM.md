# ZIRCONIUM - G0128

**Created**: 2021-03-24T15:48:17.731Z

**Modified**: 2023-03-22T22:10:43.732Z

**Contributors**: 

## Aliases

ZIRCONIUM,APT31

## Description

[ZIRCONIUM](https://attack.mitre.org/groups/G0128) is a threat group operating out of China, active since at least 2017, that has targeted individuals associated with the 2020 US presidential election and prominent leaders in the international affairs community.(Citation: Microsoft Targeting Elections September 2020)(Citation: Check Point APT31 February 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1598.003|Spearphishing Link|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used web beacons in e-mails to track hits to attacker-controlled URL's.(Citation: Microsoft Targeting Elections September 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used a tool to enumerate proxy settings in the target environment.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1567.002|Exfiltration to Cloud Storage|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has exfiltrated stolen data to Dropbox.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1036.004|Masquerade Task or Service|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has created a run key named <code>Dropbox Update Setup</code> to mask a persistence mechanism for a malicious binary.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1140|Deobfuscate/Decode Files or Information|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used the AES256 algorithm with a SHA1 derived key to decrypt exploit code.(Citation: Check Point APT31 February 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1068|Exploitation for Privilege Escalation|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has exploited CVE-2017-0005 for local privilege escalation.(Citation: Check Point APT31 February 2021)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1027.002|Software Packing|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used multi-stage packers for exploit code.(Citation: Check Point APT31 February 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used tools to download malicious files to compromised hosts.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1041|Exfiltration Over C2 Channel|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has exfiltrated files via the Dropbox API C2.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used a tool to open a Windows Command Shell on a remote host.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used a tool to capture the username on a compromised host in order to register it with C2.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1573.001|Symmetric Cryptography|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used AES encrypted communications in C2.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used a tool to capture the processor architecture of a compromised host in order to register it with C2.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Windows,Network|T1124|System Time Discovery|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used a tool to capture the time on a compromised host in order to register it with C2.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Windows|T1012|Query Registry|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used a tool to query the Registry for proxy settings.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used a tool to steal credentials from installed web browsers including Microsoft Internet Explorer and Google Chrome.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has created a Registry Run key named <code>Dropbox Update Setup</code> to establish persistence for a malicious Python binary.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Windows|T1218.007|Msiexec|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used the msiexec.exe command-line utility to download and execute malicious MSI files.(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used malicious links in e-mails to lure victims into downloading malware.(Citation: Google Election Threats October 2020)(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036|Masquerading|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has spoofed legitimate applications in phishing lures and changed file extensions to conceal  installation of malware.(Citation: Google Election Threats October 2020)(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102.002|Bidirectional Communication|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used Dropbox for C2 allowing upload and download of files as well as execution of arbitrary commands.(Citation: Google Election Threats October 2020)(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|PRE|T1598|Phishing for Information|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) targeted presidential campaign staffers with credential phishing e-mails.(Citation: Google Election Threats October 2020)|
|mitre-attack|enterprise-attack|PRE|T1583.006|Web Services|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used GitHub to host malware linked in spearphishing e-mails.(Citation: Google Election Threats October 2020)(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1059.006|Python|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used Python-based implants to interact with compromised hosts.(Citation: Google Election Threats October 2020)(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used malicious links in e-mails to deliver malware.(Citation: Microsoft Targeting Elections September 2020)(Citation: Google Election Threats October 2020)(Citation: Zscaler APT31 Covid-19 October 2020)|
|mitre-attack|enterprise-attack|PRE|T1583.001|Domains|[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has purchased domains for use in targeted campaigns.(Citation: Microsoft Targeting Elections September 2020)|
