# Deep Panda - G0009

**Created**: 2017-05-31T21:31:49.412Z

**Modified**: 2022-07-20T20:10:29.593Z

**Contributors**: Andrew Smith, @jakx_

## Aliases

Deep Panda,Shell Crew,WebMasters,KungFu Kittens,PinkPanther,Black Vine

## Description

[Deep Panda](https://attack.mitre.org/groups/G0009) is a suspected Chinese threat group known to target many industries, including government, defense, financial, and telecommunications. (Citation: Alperovitch 2014) The intrusion into healthcare company Anthem has been attributed to [Deep Panda](https://attack.mitre.org/groups/G0009). (Citation: ThreatConnect Anthem) This group is also known as Shell Crew, WebMasters, KungFu Kittens, and PinkPanther. (Citation: RSA Shell Crew) [Deep Panda](https://attack.mitre.org/groups/G0009) also appears to be known as Black Vine based on the attribution of both group names to the Anthem intrusion. (Citation: Symantec Black Vine) Some analysts track [Deep Panda](https://attack.mitre.org/groups/G0009) and [APT19](https://attack.mitre.org/groups/G0073) as the same group, but it is unclear from open source information if the groups are the same. (Citation: ICIT China's Espionage Jul 2016)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1564.003|Hidden Window|[Deep Panda](https://attack.mitre.org/groups/G0009) has used <code>-w hidden</code> to conceal [PowerShell](https://attack.mitre.org/techniques/T1059/001) windows by setting the WindowStyle parameter to hidden. (Citation: Alperovitch 2014)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1018|Remote System Discovery|[Deep Panda](https://attack.mitre.org/groups/G0009) has used ping to identify other machines of interest.(Citation: Alperovitch 2014)|
|mitre-attack|enterprise-attack|Windows|T1546.008|Accessibility Features|[Deep Panda](https://attack.mitre.org/groups/G0009) has used the sticky-keys technique to bypass the RDP login screen on remote systems during intrusions.(Citation: RSA Shell Crew)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[Deep Panda](https://attack.mitre.org/groups/G0009) has used PowerShell scripts to download and execute programs in memory, without writing to disk.(Citation: Alperovitch 2014)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS,Network|T1505.003|Web Shell|[Deep Panda](https://attack.mitre.org/groups/G0009) uses Web shells on publicly accessible Web servers to access victim networks.(Citation: CrowdStrike Deep Panda Web Shells)|
|mitre-attack|enterprise-attack|Windows|T1021.002|SMB/Windows Admin Shares|[Deep Panda](https://attack.mitre.org/groups/G0009) uses net.exe to connect to network shares using <code>net use</code> commands with compromised credentials.(Citation: Alperovitch 2014)|
|mitre-attack|enterprise-attack|Windows|T1218.010|Regsvr32|[Deep Panda](https://attack.mitre.org/groups/G0009) has used regsvr32.exe to execute a server variant of [Derusbi](https://attack.mitre.org/software/S0021) in victim networks.(Citation: RSA Shell Crew)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.005|Indicator Removal from Tools|[Deep Panda](https://attack.mitre.org/groups/G0009) has updated and modified its malware, resulting in different hash values that evade detection.(Citation: Symantec Black Vine)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Deep Panda](https://attack.mitre.org/groups/G0009) uses the Microsoft [Tasklist](https://attack.mitre.org/software/S0057) utility to list processes running on systems.(Citation: Alperovitch 2014)|
|mitre-attack|enterprise-attack|Windows|T1047|Windows Management Instrumentation|The [Deep Panda](https://attack.mitre.org/groups/G0009) group is known to utilize WMI for lateral movement.(Citation: Alperovitch 2014)|
