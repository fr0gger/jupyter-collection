# Tonto Team - G0131

**Created**: 2021-05-05T17:18:25.987Z

**Modified**: 2022-01-27T17:51:41.433Z

**Contributors**: 

## Aliases

Tonto Team,Earth Akhlut,BRONZE HUNTLEY,CactusPete,Karma Panda

## Description

[Tonto Team](https://attack.mitre.org/groups/G0131) is a suspected Chinese state-sponsored cyber espionage threat group that has primarily targeted South Korea, Japan, Taiwan, and the United States since at least 2009; by 2020 they expanded operations to include other Asian as well as Eastern European countries. [Tonto Team](https://attack.mitre.org/groups/G0131) has targeted government, military, energy, mining, financial, education, healthcare, and technology organizations, including through the Heartbeat Campaign (2009-2012) and Operation Bitter Biscuit (2017).(Citation: Kaspersky CactusPete Aug 2020)(Citation: ESET Exchange Mar 2021)(Citation: FireEye Chinese Espionage October 2019)(Citation: ARS Technica China Hack SK April 2017)(Citation: Trend Micro HeartBeat Campaign January 2013)(Citation: Talos Bisonal 10 Years March 2020)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1090.002|External Proxy|[Tonto Team](https://attack.mitre.org/groups/G0131) has routed their traffic through an external server in order to obfuscate their location.(Citation: TrendMicro Tonto Team October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1068|Exploitation for Privilege Escalation|[Tonto Team](https://attack.mitre.org/groups/G0131) has exploited CVE-2019-0803 and MS16-032 to escalate privileges.(Citation: TrendMicro Tonto Team October 2020)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1135|Network Share Discovery|[Tonto Team](https://attack.mitre.org/groups/G0131) has used tools such as [NBTscan](https://attack.mitre.org/software/S0590) to enumerate network shares.(Citation: TrendMicro Tonto Team October 2020)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1003|OS Credential Dumping|[Tonto Team](https://attack.mitre.org/groups/G0131) has used a variety of credential dumping tools.(Citation: TrendMicro Tonto Team October 2020) |
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1059.006|Python|[Tonto Team](https://attack.mitre.org/groups/G0131) has used Python-based tools for execution.(Citation: TrendMicro Tonto Team October 2020) |
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Network|T1056.001|Keylogging|[Tonto Team](https://attack.mitre.org/groups/G0131) has used keylogging tools in their operations.(Citation: TrendMicro Tonto Team October 2020)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1210|Exploitation of Remote Services|[Tonto Team](https://attack.mitre.org/groups/G0131) has used EternalBlue exploits for lateral movement.(Citation: TrendMicro Tonto Team October 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1069.001|Local Groups|[Tonto Team](https://attack.mitre.org/groups/G0131) has used the <code>ShowLocalGroupDetails</code> command to identify administrator, user, and guest accounts on a compromised host.(Citation: TrendMicro Tonto Team October 2020)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS,Network|T1505.003|Web Shell|[Tonto Team](https://attack.mitre.org/groups/G0131) has used a first stage web shell after compromising a vulnerable Exchange server.(Citation: ESET Exchange Mar 2021)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Tonto Team](https://attack.mitre.org/groups/G0131) has used PowerShell to download additional payloads.(Citation: ESET Exchange Mar 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Tonto Team](https://attack.mitre.org/groups/G0131) has downloaded malicious DLLs which served as a [ShadowPad](https://attack.mitre.org/software/S0596) loader.(Citation: ESET Exchange Mar 2021)|
|mitre-attack|enterprise-attack|Windows|T1574.001|DLL Search Order Hijacking|[Tonto Team](https://attack.mitre.org/groups/G0131) abuses a legitimate and signed Microsoft executable to launch a malicious DLL.(Citation: ESET Exchange Mar 2021)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Tonto Team](https://attack.mitre.org/groups/G0131) has delivered payloads via spearphishing attachments.(Citation: TrendMicro Tonto Team October 2020)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Tonto Team](https://attack.mitre.org/groups/G0131) has exploited Microsoft vulnerabilities, including CVE-2018-0798, CVE-2018-8174, CVE-2018-0802, CVE-2017-11882, CVE-2019-9489 CVE-2020-8468, and CVE-2018-0798 to enable execution of their delivered malicious payloads.(Citation: Kaspersky CactusPete Aug 2020)(Citation: TrendMicro Tonto Team October 2020)(Citation: Talos Bisonal Mar 2020)(Citation: Talos Bisonal 10 Years March 2020) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Tonto Team](https://attack.mitre.org/groups/G0131) has relied on user interaction to open their malicious RTF documents.(Citation: TrendMicro Tonto Team October 2020)(Citation: Talos Bisonal Mar 2020) |
