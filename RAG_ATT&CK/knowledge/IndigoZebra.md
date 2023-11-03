# IndigoZebra - G0136

**Created**: 2021-09-24T21:41:34.797Z

**Modified**: 2021-10-16T02:06:06.404Z

**Contributors**: Pooja Natarajan, NEC Corporation India,Yoshihiro Kori, NEC Corporation,Manikantan Srinivasan, NEC Corporation India

## Aliases

IndigoZebra

## Description

[IndigoZebra](https://attack.mitre.org/groups/G0136) is a suspected Chinese cyber espionage group that has been targeting Central Asian governments since at least 2014.(Citation: HackerNews IndigoZebra July 2021)(Citation: Checkpoint IndigoZebra July 2021)(Citation: Securelist APT Trends Q2 2017)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1586.002|Email Accounts|[IndigoZebra](https://attack.mitre.org/groups/G0136) has compromised legitimate email accounts to use in their spearphishing operations.(Citation: Checkpoint IndigoZebra July 2021)|
|mitre-attack|enterprise-attack|PRE|T1583.001|Domains|[IndigoZebra](https://attack.mitre.org/groups/G0136) has established domains, some of which were designed to look like official government domains, for their operations.(Citation: Checkpoint IndigoZebra July 2021)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[IndigoZebra](https://attack.mitre.org/groups/G0136) has downloaded additional files and tools from its C2 server.(Citation: Checkpoint IndigoZebra July 2021)|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[IndigoZebra](https://attack.mitre.org/groups/G0136) has acquired open source tools such as [NBTscan](https://attack.mitre.org/software/S0590) and Meterpreter for their operations.(Citation: Checkpoint IndigoZebra July 2021)(Citation: Securelist APT Trends Q2 2017) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[IndigoZebra](https://attack.mitre.org/groups/G0136) sent spearphishing emails containing malicious attachments that urged recipients to review modifications in the file which would trigger the attack.(Citation: HackerNews IndigoZebra July 2021)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[IndigoZebra](https://attack.mitre.org/groups/G0136) sent spearphishing emails containing malicious password-protected RAR attachments.(Citation: HackerNews IndigoZebra July 2021)(Citation: Checkpoint IndigoZebra July 2021)|
|mitre-attack|enterprise-attack|PRE|T1583.006|Web Services|[IndigoZebra](https://attack.mitre.org/groups/G0136) created Dropbox accounts for their operations.(Citation: HackerNews IndigoZebra July 2021)(Citation: Checkpoint IndigoZebra July 2021)|
