# HAFNIUM - G0125

**Created**: 2021-03-03T19:40:47.280Z

**Modified**: 2023-04-10T21:54:46.756Z

**Contributors**: Daniyal Naeem, BT Security,Matt Brenton, Zurich Insurance Group,Mayuresh Dani, Qualys,Harshal Tupsamudre, Qualys,Vinayak Wadhwa, SAFE Security

## Aliases

HAFNIUM,Operation Exchange Marauder

## Description

[HAFNIUM](https://attack.mitre.org/groups/G0125) is a likely state-sponsored cyber espionage group operating out of China that has been active since at least January 2021. [HAFNIUM](https://attack.mitre.org/groups/G0125) primarily targets entities in the US across a number of industry sectors, including infectious disease researchers, law firms, higher education institutions, defense contractors, policy think tanks, and NGOs.(Citation: Microsoft HAFNIUM March 2020)(Citation: Volexity Exchange Marauder March 2021)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[HAFNIUM](https://attack.mitre.org/groups/G0125) has collected data and files from a compromised machine.(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1564.001|Hidden Files and Directories|[HAFNIUM](https://attack.mitre.org/groups/G0125) has hidden files on a compromised host.(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[HAFNIUM](https://attack.mitre.org/groups/G0125) has searched file contents on a compromised host.(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[HAFNIUM](https://attack.mitre.org/groups/G0125) has collected IP information via IPInfo.(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1016.001|Internet Connection Discovery|[HAFNIUM](https://attack.mitre.org/groups/G0125) has checked for network connectivity from a compromised host using `ping`, including attempts to contact `google[.]com`.(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used `tasklist` to enumerate processes.(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used `whoami` to gather user information.(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[HAFNIUM](https://attack.mitre.org/groups/G0125) has enumerated domain controllers using `net group "Domain computers"` and `nltest /dclist`.(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,IaaS,Linux,macOS,Google Workspace,SaaS,Network|T1098|Account Manipulation|[HAFNIUM](https://attack.mitre.org/groups/G0125) has granted privileges to domain accounts.(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used `cmd.exe` to execute commands on the victim's machine.(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Windows|T1218.011|Rundll32|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used <code>rundll32</code> to load malicious DLLs.(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[HAFNIUM](https://attack.mitre.org/groups/G0125) has downloaded malware and tools--including Nishang and PowerCat--onto a compromised host.(Citation: Microsoft HAFNIUM March 2020)(Citation: Rapid7 HAFNIUM Mar 2021) |
|mitre-attack|enterprise-attack|Windows,Linux,macOS,Network|T1095|Non-Application Layer Protocol|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used TCP for C2.(Citation: Microsoft HAFNIUM March 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1132.001|Standard Encoding|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used ASCII encoding for C2 traffic.(Citation: Microsoft HAFNIUM March 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1078.003|Local Accounts|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used the NT AUTHORITY\SYSTEM account to create files on Exchange servers.(Citation: FireEye Exchange Zero Days March 2021)|
|mitre-attack|enterprise-attack|PRE|T1590.005|IP Addresses|[HAFNIUM](https://attack.mitre.org/groups/G0125) has obtained IP addresses for publicly-accessible Exchange servers.(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1136.002|Domain Account|[HAFNIUM](https://attack.mitre.org/groups/G0125) has created domain accounts.(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|PRE|T1590|Gather Victim Network Information|[HAFNIUM](https://attack.mitre.org/groups/G0125) gathered the fully qualified domain names (FQDNs) for targeted Exchange servers in the victim's environment.(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|Windows|T1003.003|NTDS|[HAFNIUM](https://attack.mitre.org/groups/G0125) has stolen copies of the Active Directory database (NTDS.DIT).(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|PRE|T1589.002|Email Addresses|[HAFNIUM](https://attack.mitre.org/groups/G0125) has collected e-mail addresses for users they intended to target.(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560.001|Archive via Utility|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used 7-Zip and WinRAR to compress stolen files for exfiltration.(Citation: Microsoft HAFNIUM March 2020)(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used the Exchange Power Shell module <code>Set-OabVirtualDirectoryPowerShell</code> to export mailbox data.(Citation: Microsoft HAFNIUM March 2020)(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|Office 365,Windows,Google Workspace|T1114.002|Remote Email Collection|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used web shells to export mailbox data.(Citation: Microsoft HAFNIUM March 2020)(Citation: Volexity Exchange Marauder March 2021)|
|mitre-attack|enterprise-attack|Windows|T1003.001|LSASS Memory|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used <code>procdump</code> to dump the LSASS process memory.(Citation: Microsoft HAFNIUM March 2020)(Citation: Volexity Exchange Marauder March 2021)(Citation: Rapid7 HAFNIUM Mar 2021)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS,Network|T1505.003|Web Shell|[HAFNIUM](https://attack.mitre.org/groups/G0125) has deployed multiple web shells on compromised servers including SIMPLESEESHARP, SPORTSBALL, [China Chopper](https://attack.mitre.org/software/S0020), and [ASPXSpy](https://attack.mitre.org/software/S0073).(Citation: Microsoft HAFNIUM March 2020)(Citation: Volexity Exchange Marauder March 2021)(Citation: FireEye Exchange Zero Days March 2021)(Citation: Tarrask scheduled task)(Citation: Rapid7 HAFNIUM Mar 2021)   |
|mitre-attack|enterprise-attack|PRE|T1583.003|Virtual Private Server|[HAFNIUM](https://attack.mitre.org/groups/G0125) has operated from leased virtual private servers (VPS) in the United States.(Citation: Microsoft HAFNIUM March 2020)|
|mitre-attack|enterprise-attack|PRE|T1592.004|Client Configurations|[HAFNIUM](https://attack.mitre.org/groups/G0125) has interacted with Office 365 tenants to gather details regarding target's environments.(Citation: Microsoft HAFNIUM March 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1567.002|Exfiltration to Cloud Storage|[HAFNIUM](https://attack.mitre.org/groups/G0125) has exfiltrated data to file sharing sites, including MEGA.(Citation: Microsoft HAFNIUM March 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[HAFNIUM](https://attack.mitre.org/groups/G0125) has used open-source C2 frameworks, including Covenant.(Citation: Microsoft HAFNIUM March 2020)|
|mitre-attack|enterprise-attack|PRE|T1583.006|Web Services|[HAFNIUM](https://attack.mitre.org/groups/G0125) has acquired web services for use in C2 and exfiltration.(Citation: Microsoft HAFNIUM March 2020)|
|mitre-attack|enterprise-attack|Windows,IaaS,Network,Linux,macOS,Containers|T1190|Exploit Public-Facing Application|[HAFNIUM](https://attack.mitre.org/groups/G0125) has exploited CVE-2021-26855, CVE-2021-26857, CVE-2021-26858, and CVE-2021-27065  to compromise on-premises versions of Microsoft Exchange Server, enabling access to email accounts and installation of additional malware.(Citation: Microsoft HAFNIUM March 2020)(Citation: Volexity Exchange Marauder March 2021)(Citation: FireEye Exchange Zero Days March 2021)(Citation: Tarrask scheduled task)   |
