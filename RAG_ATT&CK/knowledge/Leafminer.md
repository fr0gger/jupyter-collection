# Leafminer - G0077

**Created**: 2018-10-17T00:14:20.652Z

**Modified**: 2023-03-22T04:50:51.782Z

**Contributors**: 

## Aliases

Leafminer,Raspite

## Description

[Leafminer](https://attack.mitre.org/groups/G0077) is an Iranian threat group that has targeted government organizations and business entities in the Middle East since at least early 2017. (Citation: Symantec Leafminer July 2018)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Leafminer](https://attack.mitre.org/groups/G0077) has obtained and used tools such as [LaZagne](https://attack.mitre.org/software/S0349), [Mimikatz](https://attack.mitre.org/software/S0002), [PsExec](https://attack.mitre.org/software/S0029), and [MailSniper](https://attack.mitre.org/software/S0413).(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[Leafminer](https://attack.mitre.org/groups/G0077) used several tools for retrieving login and password information, including LaZagne.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555|Credentials from Password Stores|[Leafminer](https://attack.mitre.org/groups/G0077) used several tools for retrieving login and password information, including LaZagne.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Windows|T1003.005|Cached Domain Credentials|[Leafminer](https://attack.mitre.org/groups/G0077) used several tools for retrieving login and password information, including LaZagne.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Windows|T1003.004|LSA Secrets|[Leafminer](https://attack.mitre.org/groups/G0077) used several tools for retrieving login and password information, including LaZagne.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers|T1552.001|Credentials In Files|[Leafminer](https://attack.mitre.org/groups/G0077) used several tools for retrieving login and password information, including LaZagne.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Windows|T1055.013|Process Doppelgänging|[Leafminer](https://attack.mitre.org/groups/G0077) has used [Process Doppelgänging](https://attack.mitre.org/techniques/T1055/013) to evade security software while deploying tools on compromised systems.(Citation: Symantec Leafminer July 2018)	|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[Leafminer](https://attack.mitre.org/groups/G0077) has infected victims using watering holes.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[Leafminer](https://attack.mitre.org/groups/G0077) used Microsoft’s Sysinternals tools to gather detailed information about remote systems.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.010|Command Obfuscation|[Leafminer](https://attack.mitre.org/groups/G0077) obfuscated scripts that were used on victim machines.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.007|JavaScript|[Leafminer](https://attack.mitre.org/groups/G0077) infected victims using JavaScript code.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[Leafminer](https://attack.mitre.org/groups/G0077) used a tool called MailSniper to search for files on the desktop and another utility called Sobolsoft to extract attachments from EML files.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers|T1110.003|Password Spraying|[Leafminer](https://attack.mitre.org/groups/G0077) used a tool called Total SMB BruteForcer to perform internal password spraying.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Office 365,Windows,Google Workspace|T1114.002|Remote Email Collection|[Leafminer](https://attack.mitre.org/groups/G0077) used a tool called MailSniper to search through the Exchange server mailboxes for keywords.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[Leafminer](https://attack.mitre.org/groups/G0077) used several tools for retrieving login and password information, including LaZagne and Mimikatz.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1136.001|Local Account|[Leafminer](https://attack.mitre.org/groups/G0077) used a tool called Imecab to set up a persistent remote access account on the victim machine.(Citation: Symantec Leafminer July 2018)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers,Network|T1046|Network Service Discovery|[Leafminer](https://attack.mitre.org/groups/G0077) scanned network services to search for vulnerabilities in the victim system.(Citation: Symantec Leafminer July 2018)|
