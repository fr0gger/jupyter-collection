# Mofang - G0103

**Created**: 2020-05-12T21:23:59.021Z

**Modified**: 2020-05-29T03:30:39.739Z

**Contributors**: 

## Aliases

Mofang

## Description

[Mofang](https://attack.mitre.org/groups/G0103) is a likely China-based cyber espionage group, named for its frequent practice of imitating a victim's infrastructure. This adversary has been observed since at least May 2012 conducting focused attacks against government and critical infrastructure in Myanmar, as well as several other countries and sectors including military, automobile, and weapons industries.(Citation: FOX-IT May 2016 Mofang)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Office 365,SaaS,Google Workspace|T1566.002|Spearphishing Link|[Mofang](https://attack.mitre.org/groups/G0103) delivered spearphishing emails with malicious links included.(Citation: FOX-IT May 2016 Mofang)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.001|Malicious Link|[Mofang](https://attack.mitre.org/groups/G0103)'s spearphishing emails required a user to click the link to connect to a compromised website.(Citation: FOX-IT May 2016 Mofang)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Mofang](https://attack.mitre.org/groups/G0103) delivered spearphishing emails with malicious documents, PDFs, or Excel files attached.(Citation: FOX-IT May 2016 Mofang)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Mofang](https://attack.mitre.org/groups/G0103)'s malicious spearphishing attachments required a user to open the file after receiving.(Citation: FOX-IT May 2016 Mofang)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Mofang](https://attack.mitre.org/groups/G0103) has compressed the [ShimRat](https://attack.mitre.org/software/S0444) executable within malicious email attachments. [Mofang](https://attack.mitre.org/groups/G0103) has also encrypted payloads before they are downloaded to victims.(Citation: FOX-IT May 2016 Mofang)|
