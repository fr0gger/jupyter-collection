# APT1 - G0006

**Created**: 2017-05-31T21:31:47.955Z

**Modified**: 2021-05-26T12:23:48.842Z

**Contributors**: 

## Aliases

APT1,Comment Crew,Comment Group,Comment Panda

## Description

[APT1](https://attack.mitre.org/groups/G0006) is a Chinese threat group that has been attributed to the 2nd Bureau of the People’s Liberation Army (PLA) General Staff Department’s (GSD) 3rd Department, commonly known by its Military Unit Cover Designator (MUCD) as Unit 61398. (Citation: Mandiant APT1)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[APT1](https://attack.mitre.org/groups/G0006) has used various open-source tools for privilege escalation purposes.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|PRE|T1588.001|Malware|[APT1](https://attack.mitre.org/groups/G0006) used publicly available malware for privilege escalation.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|PRE|T1585.002|Email Accounts|[APT1](https://attack.mitre.org/groups/G0006) has created email accounts for later use in social engineering, phishing, and when registering domains.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[APT1](https://attack.mitre.org/groups/G0006) has sent spearphishing emails containing malicious attachments.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[APT1](https://attack.mitre.org/groups/G0006) has sent spearphishing emails containing hyperlinks to malicious files.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|PRE|T1584.001|Domains|[APT1](https://attack.mitre.org/groups/G0006) hijacked FQDNs associated with legitimate websites hosted by hop points.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|PRE|T1583.001|Domains|[APT1](https://attack.mitre.org/groups/G0006) has registered hundreds of domains for use in operations.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Office 365,Windows,Google Workspace|T1114.002|Remote Email Collection|[APT1](https://attack.mitre.org/groups/G0006) uses two utilities, GETMAIL and MAPIGET, to steal email. MAPIGET steals email still on Exchange servers that has not yet been archived.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[APT1](https://attack.mitre.org/groups/G0006) gathered a list of running processes on the system using <code>tasklist /v</code>.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1135|Network Share Discovery|[APT1](https://attack.mitre.org/groups/G0006) listed connected network shares.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[APT1](https://attack.mitre.org/groups/G0006) used the <code>ipconfig /all</code> command to gather network configuration information.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,IaaS,SaaS|T1119|Automated Collection|[APT1](https://attack.mitre.org/groups/G0006) used a batch script to perform a series of discovery techniques and saves it to a text file.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1087.001|Local Account|[APT1](https://attack.mitre.org/groups/G0006) used the commands <code>net localgroup</code>,<code>net user</code>, and <code>net group</code> to find accounts on the system.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1049|System Network Connections Discovery|[APT1](https://attack.mitre.org/groups/G0006) used the <code>net use</code> command to get a listing on network connections.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1007|System Service Discovery|[APT1](https://attack.mitre.org/groups/G0006) used the commands <code>net start</code> and <code>tasklist</code> to get a listing of the services on the system.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[APT1](https://attack.mitre.org/groups/G0006) has collected files from a local victim.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560.001|Archive via Utility|[APT1](https://attack.mitre.org/groups/G0006) has used RAR to compress files before moving them outside of the victim network.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Windows|T1021.001|Remote Desktop Protocol|The [APT1](https://attack.mitre.org/groups/G0006) group is known to have used RDP during operations.(Citation: FireEye PLA)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[APT1](https://attack.mitre.org/groups/G0006) has been known to use credential dumping using [Mimikatz](https://attack.mitre.org/software/S0002).(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[APT1](https://attack.mitre.org/groups/G0006) has used the Windows command shell to execute commands, and batch scripting to automate execution.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Windows|T1550.002|Pass the Hash|The [APT1](https://attack.mitre.org/groups/G0006) group is known to have used pass the hash.(Citation: Mandiant APT1)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|The file name AcroRD32.exe, a legitimate process name for Adobe's Acrobat Reader, was used by [APT1](https://attack.mitre.org/groups/G0006) as a name for malware.(Citation: Mandiant APT1)(Citation: Mandiant APT1 Appendix)|
|mitre-attack|enterprise-attack|Windows|T1114.001|Local Email Collection|[APT1](https://attack.mitre.org/groups/G0006) uses two utilities, GETMAIL and MAPIGET, to steal email. GETMAIL extracts emails from archived Outlook .pst files.(Citation: Mandiant APT1)|
