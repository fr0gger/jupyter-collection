# LuminousMoth - G1014

**Created**: 2023-02-23T15:31:38.829Z

**Modified**: 2023-04-17T21:49:16.371Z

**Contributors**: Kyaw Pyiyt Htet, @KyawPyiytHtet,Zaw Min Htun, @Z3TAE

## Aliases

LuminousMoth

## Description

[LuminousMoth](https://attack.mitre.org/groups/G1014) is a Chinese-speaking cyber espionage group that has been active since at least October 2020. [LuminousMoth](https://attack.mitre.org/groups/G1014) has targeted high-profile organizations, including government entities, in Myanmar, the Philippines, Thailand, and other parts of Southeast Asia. Some security researchers have concluded there is a connection between [LuminousMoth](https://attack.mitre.org/groups/G1014) and [Mustang Panda](https://attack.mitre.org/groups/G0129) based on similar targeting and TTPs, as well as network infrastructure overlaps.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|macOS,Windows|T1553.002|Code Signing|[LuminousMoth](https://attack.mitre.org/groups/G1014) has signed their malware with a valid digital signature.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|PRE|T1608.001|Upload Malware|[LuminousMoth](https://attack.mitre.org/groups/G1014) has hosted malicious payloads on Dropbox.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|PRE|T1608.005|Link Target|[LuminousMoth](https://attack.mitre.org/groups/G1014) has created a link to a Dropbox file that has been used in their spear-phishing operations.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|PRE|T1587.001|Malware|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used unique malware for information theft and exfiltration.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Windows|T1112|Modify Registry|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used malware that adds Registry keys for persistence.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1041|Exfiltration Over C2 Channel|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used malware that exfiltrates stolen data to its C2 server.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[LuminousMoth](https://attack.mitre.org/groups/G1014) has created scheduled tasks to establish persistence for their tools.(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1030|Data Transfer Size Limits|[LuminousMoth](https://attack.mitre.org/groups/G1014) has split archived files into multiple parts to bypass a 5MB limit.(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used a malicious DLL to collect the username from compromised hosts.(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[LuminousMoth](https://attack.mitre.org/groups/G1014) has collected files and data from compromised machines.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used malware that scans for files in the Documents, Desktop, and Download folders and in other drives.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[LuminousMoth](https://attack.mitre.org/groups/G1014) has obtained an ARP spoofing tool from GitHub.(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560|Archive Collected Data|[LuminousMoth](https://attack.mitre.org/groups/G1014) has manually archived stolen files from victim machines before exfiltration.(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|PRE|T1608.004|Drive-by Target|[LuminousMoth](https://attack.mitre.org/groups/G1014) has redirected compromised machines to an actor-controlled webpage through HTML injection.(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1557.002|ARP Cache Poisoning|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used ARP spoofing to redirect a compromised machine to an actor-controlled website.(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1567.002|Exfiltration to Cloud Storage|[LuminousMoth](https://attack.mitre.org/groups/G1014) has exfiltrated data to Google Drive.(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[LuminousMoth](https://attack.mitre.org/groups/G1014) has downloaded additional malware and tools onto a compromised host.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used HTTP for C2.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1564.001|Hidden Files and Directories|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used malware to store malicious binaries in hidden directories on victim's USB drives.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Windows|T1091|Replication Through Removable Media|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used malicious DLLs to spread malware to connected removable USB drives on infected machines.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1539|Steal Web Session Cookie|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used an unnamed post-exploitation tool to steal cookies from the Chrome browser.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[LuminousMoth](https://attack.mitre.org/groups/G1014) has disguised their exfiltration malware as `ZoomVideoApp.exe`.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used malicious DLLs that setup persistence in the Registry Key `HKCU\Software\Microsoft\Windows\Current Version\Run`.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Windows|T1574.002|DLL Side-Loading|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used legitimate executables such as `winword.exe` and `igfxem.exe` to side-load their malware.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[LuminousMoth](https://attack.mitre.org/groups/G1014) has lured victims into clicking malicious Dropbox download links delivered through spearphishing.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[LuminousMoth](https://attack.mitre.org/groups/G1014) has sent spearphishing emails containing a malicious Dropbox download link.(Citation: Kaspersky LuminousMoth July 2021)|
|mitre-attack|enterprise-attack|PRE|T1588.004|Digital Certificates|[LuminousMoth](https://attack.mitre.org/groups/G1014) has used a valid digital certificate for some of their malware.(Citation: Kaspersky LuminousMoth July 2021) |
|mitre-attack|enterprise-attack|PRE|T1588.001|Malware|[LuminousMoth](https://attack.mitre.org/groups/G1014) has obtained and used malware such as [Cobalt Strike](https://attack.mitre.org/software/S0154).(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)|
