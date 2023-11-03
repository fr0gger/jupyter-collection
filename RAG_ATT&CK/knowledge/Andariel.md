# Andariel - G0138

**Created**: 2021-09-29T15:10:19.236Z

**Modified**: 2022-11-30T22:51:40.270Z

**Contributors**: Kyoung-ju Kwak (S2W)

## Aliases

Andariel,Silent Chollima

## Description

[Andariel](https://attack.mitre.org/groups/G0138) is a North Korean state-sponsored threat group that has been active since at least 2009. [Andariel](https://attack.mitre.org/groups/G0138) has primarily focused its operations--which have included destructive attacks--against South Korean government agencies, military organizations, and a variety of domestic companies; they have also conducted cyber financial operations against ATMs, banks, and cryptocurrency exchanges. [Andariel](https://attack.mitre.org/groups/G0138)'s notable activity includes Operation Black Mine, Operation GoldenAxe, and Campaign Rifle.(Citation: FSI Andariel Campaign Rifle July 2017)(Citation: IssueMakersLab Andariel GoldenAxe May 2017)(Citation: AhnLab Andariel Subgroup of Lazarus June 2018)(Citation: TrendMicro New Andariel Tactics July 2018)(Citation: CrowdStrike Silent Chollima Adversary September 2021)

[Andariel](https://attack.mitre.org/groups/G0138) is considered a sub-set of [Lazarus Group](https://attack.mitre.org/groups/G0032), and has been attributed to North Korea's Reconnaissance General Bureau.(Citation: Treasury North Korean Cyber Groups September 2019)

North Korean group definitions are known to have significant overlap, and some security researchers report all North Korean state-sponsored cyber activity under the name [Lazarus Group](https://attack.mitre.org/groups/G0032) instead of tracking clusters or subgroups.

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1590.005|IP Addresses|[Andariel](https://attack.mitre.org/groups/G0138) has limited its watering hole attacks to specific IP address ranges.(Citation: AhnLab Andariel Subgroup of Lazarus June 2018)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[Andariel](https://attack.mitre.org/groups/G0138) has used watering hole attacks, often with zero-day exploits, to gain initial access to victims within a specific IP range.(Citation: AhnLab Andariel Subgroup of Lazarus June 2018)(Citation: TrendMicro New Andariel Tactics July 2018)|
|mitre-attack|enterprise-attack|PRE|T1592.002|Software|[Andariel](https://attack.mitre.org/groups/G0138) has inserted a malicious script within compromised websites to collect potential victim information such as browser type, system language, Flash Player version, and other data.(Citation: TrendMicro New Andariel Tactics July 2018)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1049|System Network Connections Discovery|[Andariel](https://attack.mitre.org/groups/G0138) has used the <code>netstat -naop tcp</code> command to display TCP connections on a victim's machine.(Citation: Kaspersky Andariel Ransomware June 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Andariel](https://attack.mitre.org/groups/G0138) has attempted to lure victims into enabling malicious macros within email attachments.(Citation: AhnLab Andariel Subgroup of Lazarus June 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Andariel](https://attack.mitre.org/groups/G0138) has used <code>tasklist</code> to enumerate processes and find a specific string.(Citation: Kaspersky Andariel Ransomware June 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Andariel](https://attack.mitre.org/groups/G0138) has downloaded additional tools and malware onto compromised hosts.(Citation: AhnLab Andariel Subgroup of Lazarus June 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.003|Steganography|[Andariel](https://attack.mitre.org/groups/G0138) has hidden malicious executables within PNG files.(Citation: MalwareBytes Lazarus-Andariel Conceals Code April 2021)(Citation: Kaspersky Andariel Ransomware June 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[Andariel](https://attack.mitre.org/groups/G0138) has collected large numbers of files from compromised network systems for later extraction.(Citation: FSI Andariel Campaign Rifle July 2017)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Andariel](https://attack.mitre.org/groups/G0138) has conducted spearphishing campaigns that included malicious Word or Excel attachments.(Citation: AhnLab Andariel Subgroup of Lazarus June 2018)(Citation: MalwareBytes Lazarus-Andariel Conceals Code April 2021)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Andariel](https://attack.mitre.org/groups/G0138) has exploited numerous ActiveX vulnerabilities, including zero-days.(Citation: FSI Andariel Campaign Rifle July 2017)(Citation: IssueMakersLab Andariel GoldenAxe May 2017)(Citation: TrendMicro New Andariel Tactics July 2018)|
|mitre-attack|enterprise-attack|PRE|T1588.001|Malware|[Andariel](https://attack.mitre.org/groups/G0138) has used a variety of publicly-available remote access Trojans (RATs) for its operations.(Citation: FSI Andariel Campaign Rifle July 2017)|
