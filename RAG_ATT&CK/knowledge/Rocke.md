# Rocke - G0106

**Created**: 2020-05-26T14:20:20.623Z

**Modified**: 2020-06-19T20:41:21.215Z

**Contributors**: 

## Aliases

Rocke

## Description

[Rocke](https://attack.mitre.org/groups/G0106) is an alleged Chinese-speaking adversary whose primary objective appeared to be cryptojacking, or stealing victim system resources for the purposes of mining cryptocurrency. The name [Rocke](https://attack.mitre.org/groups/G0106) comes from the email address "rocke@live.cn" used to create the wallet which held collected cryptocurrency. Researchers have detected overlaps between [Rocke](https://attack.mitre.org/groups/G0106) and the Iron Cybercrime Group, though this attribution has not been confirmed.(Citation: Talos Rocke August 2018)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1014|Rootkit|[Rocke](https://attack.mitre.org/groups/G0106) has modified /etc/ld.so.preload to hook libc functions in order to hide the installed dropper and mining software in process lists.(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071|Application Layer Protocol|[Rocke](https://attack.mitre.org/groups/G0106) issued wget requests from infected systems to the C2.(Citation: Talos Rocke August 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102|Web Service|[Rocke](https://attack.mitre.org/groups/G0106) has used Pastebin, Gitee, and GitLab for Command and Control.(Citation: Anomali Rocke March 2019)(Citation: Talos Rocke August 2018)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1140|Deobfuscate/Decode Files or Information|[Rocke](https://attack.mitre.org/groups/G0106) has extracted tar.gz files after downloading them from a C2 server.(Citation: Talos Rocke August 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Rocke](https://attack.mitre.org/groups/G0106) has used shell scripts which download mining executables and saves them with the filename "java".(Citation: Talos Rocke August 2018)|
|mitre-attack|enterprise-attack|Linux,macOS|T1574.006|Dynamic Linker Hijacking|[Rocke](https://attack.mitre.org/groups/G0106) has modified /etc/ld.so.preload to hook libc functions in order to hide the installed dropper and mining software in process lists.(Citation: Anomali Rocke March 2019)	|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1059.006|Python|[Rocke](https://attack.mitre.org/groups/G0106) has used Python-based malware to install and spread their coinminer.(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Rocke](https://attack.mitre.org/groups/G0106) has modified UPX headers after packing files to break unpackers.(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.004|Compile After Delivery|[Rocke](https://attack.mitre.org/groups/G0106) has compiled malware, delivered to victims as .c files, with the GNU Compiler Collection (GCC).(Citation: Anomali Rocke March 2019)	|
|mitre-attack|enterprise-attack|Linux,macOS|T1021.004|SSH|[Rocke](https://attack.mitre.org/groups/G0106) has spread its coinminer via SSH.(Citation: Anomali Rocke March 2019)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1552.004|Private Keys|[Rocke](https://attack.mitre.org/groups/G0106) has used SSH private keys on the infected machine to spread its coinminer throughout a network.(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Rocke](https://attack.mitre.org/groups/G0106) has used uname -m to collect the name and information about the infected system's kernel.(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS|T1070.002|Clear Linux or Mac System Logs|[Rocke](https://attack.mitre.org/groups/G0106) has cleared log files within the /var/log/ folder.(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers|T1496|Resource Hijacking|[Rocke](https://attack.mitre.org/groups/G0106) has distributed cryptomining malware.(Citation: Talos Rocke August 2018)(Citation: Unit 42 Rocke January 2019)|
|mitre-attack|enterprise-attack|Windows,IaaS,Network,Linux,macOS,Containers|T1190|Exploit Public-Facing Application|[Rocke](https://attack.mitre.org/groups/G0106) exploited Apache Struts, Oracle WebLogic (CVE-2017-10271), and Adobe ColdFusion (CVE-2017-3066) vulnerabilities to deliver malware.(Citation: Talos Rocke August 2018)(Citation: Unit 42 Rocke January 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Rocke](https://attack.mitre.org/groups/G0106) used malware to download additional malicious files to the target system.(Citation: Talos Rocke August 2018)	|
|mitre-attack|enterprise-attack|macOS,Linux|T1059.004|Unix Shell|[Rocke](https://attack.mitre.org/groups/G0106) used shell scripts to run commands which would obtain persistence and execute the cryptocurrency mining malware.(Citation: Talos Rocke August 2018)	|
|mitre-attack|enterprise-attack|Linux,macOS|T1053.003|Cron|[Rocke](https://attack.mitre.org/groups/G0106) installed a cron job that downloaded and executed files from the C2.(Citation: Talos Rocke August 2018)(Citation: Unit 42 Rocke January 2019)(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[Rocke](https://attack.mitre.org/groups/G0106) has executed wget and curl commands to Pastebin over the HTTPS protocol.(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Containers,Network|T1046|Network Service Discovery|[Rocke](https://attack.mitre.org/groups/G0106) conducted scanning for exposed TCP port 7001 as well as SSH and Redis servers.(Citation: Talos Rocke August 2018)(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1562.004|Disable or Modify System Firewall|[Rocke](https://attack.mitre.org/groups/G0106) used scripts which killed processes and added firewall rules to block traffic related to other cryptominers.(Citation: Talos Rocke August 2018)	|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace|T1518.001|Security Software Discovery|[Rocke](https://attack.mitre.org/groups/G0106) used scripts which detected and uninstalled antivirus software.(Citation: Talos Rocke August 2018)(Citation: Unit 42 Rocke January 2019)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Containers,IaaS|T1562.001|Disable or Modify Tools|[Rocke](https://attack.mitre.org/groups/G0106) used scripts which detected and uninstalled antivirus software.(Citation: Talos Rocke August 2018)(Citation: Unit 42 Rocke January 2019)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1564.001|Hidden Files and Directories|[Rocke](https://attack.mitre.org/groups/G0106) downloaded a file "libprocesshider", which could hide files on the target system.(Citation: Talos Rocke August 2018)(Citation: Unit 42 Rocke January 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[Rocke](https://attack.mitre.org/groups/G0106) has looked for IP addresses in the known_hosts file on the infected system and attempted to SSH into them.(Citation: Talos Rocke August 2018)	|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Rocke](https://attack.mitre.org/groups/G0106)'s miner has created UPX-packed files in the Windows Start Menu Folder.(Citation: Talos Rocke August 2018)	|
|mitre-attack|enterprise-attack|Windows|T1055.002|Portable Executable Injection|[Rocke](https://attack.mitre.org/groups/G0106)'s miner, "TermsHost.exe", evaded defenses by injecting itself into Windows processes, including Notepad.exe.(Citation: Talos Rocke August 2018)	|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1027.002|Software Packing|[Rocke](https://attack.mitre.org/groups/G0106)'s miner has created UPX-packed files in the Windows Start Menu Folder.(Citation: Talos Rocke August 2018)(Citation: Unit 42 Rocke January 2019)(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102.001|Dead Drop Resolver|[Rocke](https://attack.mitre.org/groups/G0106) has used Pastebin to check the version of beaconing malware and redirect to another Pastebin hosting updated malware.(Citation: Anomali Rocke March 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.004|File Deletion|[Rocke](https://attack.mitre.org/groups/G0106) has deleted files on infected machines.(Citation: Anomali Rocke March 2019)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Rocke](https://attack.mitre.org/groups/G0106) can detect a running process's PID on the infected machine.(Citation: Anomali Rocke March 2019)	|
|mitre-attack|enterprise-attack|macOS,Linux|T1222.002|Linux and Mac File and Directory Permissions Modification|[Rocke](https://attack.mitre.org/groups/G0106) has changed file permissions of files so they could not be modified.(Citation: Anomali Rocke March 2019)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1070.006|Timestomp|[Rocke](https://attack.mitre.org/groups/G0106) has changed the time stamp of certain files.(Citation: Anomali Rocke March 2019)	|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1037|Boot or Logon Initialization Scripts|[Rocke](https://attack.mitre.org/groups/G0106) has installed an "init.d" startup script to maintain persistence.(Citation: Anomali Rocke March 2019)	|
|mitre-attack|enterprise-attack|Linux|T1543.002|Systemd Service|[Rocke](https://attack.mitre.org/groups/G0106) has installed a systemd service script to maintain persistence.(Citation: Anomali Rocke March 2019)	|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1571|Non-Standard Port|[Rocke](https://attack.mitre.org/groups/G0106)'s miner connects to a C2 server using port 51640.(Citation: Anomali Rocke March 2019)	|
