# RTM - G0048

**Created**: 2017-05-31T21:32:10.206Z

**Modified**: 2020-05-12T22:16:44.650Z

**Contributors**: Oleg Skulkin, Group-IB

## Aliases

RTM

## Description

[RTM](https://attack.mitre.org/groups/G0048) is a cybercriminal group that has been active since at least 2015 and is primarily interested in users of remote banking systems in Russia and neighboring countries. The group uses a Trojan by the same name ([RTM](https://attack.mitre.org/software/S0148)). (Citation: ESET RTM Feb 2017)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[RTM](https://attack.mitre.org/groups/G0048) has attempted to lure victims into opening e-mail attachments to execute malicious code.(Citation: Group IB RTM August 2019)|
|mitre-attack|enterprise-attack|Windows|T1574.001|DLL Search Order Hijacking|[RTM](https://attack.mitre.org/groups/G0048) has used search order hijacking to force TeamViewer to load a malicious DLL.(Citation: Group IB RTM August 2019)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1219|Remote Access Software|[RTM](https://attack.mitre.org/groups/G0048) has used a modified version of TeamViewer and Remote Utilities for remote access.(Citation: Group IB RTM August 2019)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[RTM](https://attack.mitre.org/groups/G0048) has used Registry run keys to establish persistence for the [RTM](https://attack.mitre.org/software/S0148) Trojan and other tools, such as a modified version of TeamViewer remote desktop software.(Citation: ESET RTM Feb 2017)(Citation: Group IB RTM August 2019)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[RTM](https://attack.mitre.org/groups/G0048) has used spearphishing attachments to distribute its malware.(Citation: Group IB RTM August 2019)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[RTM](https://attack.mitre.org/groups/G0048) has distributed its malware via the RIG and SUNDOWN exploit kits, as well as online advertising network <code>Yandex.Direct</code>.(Citation: ESET RTM Feb 2017)(Citation: ESET Buhtrap and Buran April 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102.001|Dead Drop Resolver|[RTM](https://attack.mitre.org/groups/G0048) has used an RSS feed on Livejournal to update a list of encrypted C2 server names.(Citation: ESET RTM Feb 2017)|
