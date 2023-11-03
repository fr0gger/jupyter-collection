# APT-C-36 - G0099

**Created**: 2020-05-05T18:53:08.166Z

**Modified**: 2021-05-26T20:17:53.085Z

**Contributors**: Jose Luis Sánchez Martinez

## Aliases

APT-C-36,Blind Eagle

## Description

[APT-C-36](https://attack.mitre.org/groups/G0099) is a suspected South America espionage group that has been active since at least 2018. The group mainly targets Colombian government institutions as well as important corporations in the financial sector, petroleum industry, and professional manufacturing.(Citation: QiAnXin APT-C-36 Feb2019)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[APT-C-36](https://attack.mitre.org/groups/G0099) obtained and used a modified variant of [Imminent Monitor](https://attack.mitre.org/software/S0434).(Citation: QiAnXin APT-C-36 Feb2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[APT-C-36](https://attack.mitre.org/groups/G0099) has downloaded binary data from a specified domain after the malicious document is opened.(Citation: QiAnXin APT-C-36 Feb2019)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[APT-C-36](https://attack.mitre.org/groups/G0099) has embedded a VBScript within a malicious Word document which is executed upon the document opening.(Citation: QiAnXin APT-C-36 Feb2019)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1036.004|Masquerade Task or Service|[APT-C-36](https://attack.mitre.org/groups/G0099) has disguised its scheduled tasks as those used by Google.(Citation: QiAnXin APT-C-36 Feb2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1571|Non-Standard Port|[APT-C-36](https://attack.mitre.org/groups/G0099) has used port 4050 for C2 communications.(Citation: QiAnXin APT-C-36 Feb2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[APT-C-36](https://attack.mitre.org/groups/G0099) has prompted victims to accept macros in order to execute the subsequent payload.(Citation: QiAnXin APT-C-36 Feb2019)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[APT-C-36](https://attack.mitre.org/groups/G0099) has used a macro function to set scheduled tasks, disguised as those used by Google.(Citation: QiAnXin APT-C-36 Feb2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[APT-C-36](https://attack.mitre.org/groups/G0099) has used ConfuserEx to obfuscate its variant of [Imminent Monitor](https://attack.mitre.org/software/S0434), compressed payload and RAT packages, and password protected encrypted email attachments to avoid detection.(Citation: QiAnXin APT-C-36 Feb2019)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[APT-C-36](https://attack.mitre.org/groups/G0099) has used spearphishing emails with password protected RAR attachment to avoid being detected by the email gateway.(Citation: QiAnXin APT-C-36 Feb2019) |
