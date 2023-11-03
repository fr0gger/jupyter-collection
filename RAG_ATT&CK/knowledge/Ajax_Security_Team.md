# Ajax Security Team - G0130

**Created**: 2021-04-14T13:17:43.941Z

**Modified**: 2021-12-17T19:27:27.246Z

**Contributors**: 

## Aliases

Ajax Security Team,Operation Woolen-Goldfish,AjaxTM,Rocket Kitten,Flying Kitten,Operation Saffron Rose

## Description

[Ajax Security Team](https://attack.mitre.org/groups/G0130) is a group that has been active since at least 2010 and believed to be operating out of Iran. By 2014 [Ajax Security Team](https://attack.mitre.org/groups/G0130) transitioned from website defacement operations to malware-based cyber espionage campaigns targeting the US defense industrial base and Iranian users of anti-censorship technologies.(Citation: FireEye Operation Saffron Rose 2013)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[Ajax Security Team](https://attack.mitre.org/groups/G0130) has used FireMalv custom-developed malware, which collected passwords from the Firefox browser storage.(Citation: Check Point Rocket Kitten)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Network|T1056.001|Keylogging|[Ajax Security Team](https://attack.mitre.org/groups/G0130) has used CWoolger and MPK, custom-developed malware, which recorded all keystrokes on an infected system.(Citation: Check Point Rocket Kitten)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1566.003|Spearphishing via Service|[Ajax Security Team](https://attack.mitre.org/groups/G0130) has used various social media channels to spearphish victims.(Citation: FireEye Operation Saffron Rose 2013)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Ajax Security Team](https://attack.mitre.org/groups/G0130) has used personalized spearphishing attachments.(Citation: Check Point Rocket Kitten)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[Ajax Security Team](https://attack.mitre.org/groups/G0130) has used Wrapper/Gholee, custom-developed malware, which downloaded additional malware to the infected system.(Citation: Check Point Rocket Kitten)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Ajax Security Team](https://attack.mitre.org/groups/G0130) has lured victims into executing malicious files.(Citation: FireEye Operation Saffron Rose 2013)|
