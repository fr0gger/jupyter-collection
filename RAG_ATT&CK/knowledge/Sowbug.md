# Sowbug - G0054

**Created**: 2018-01-16T16:13:52.465Z

**Modified**: 2020-03-30T02:46:16.483Z

**Contributors**: Alan Neville, @abnev

## Aliases

Sowbug

## Description

[Sowbug](https://attack.mitre.org/groups/G0054) is a threat group that has conducted targeted attacks against organizations in South America and Southeast Asia, particularly government entities, since at least 2015. (Citation: Symantec Sowbug Nov 2017)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows,macOS,Linux,Network|T1056.001|Keylogging|[Sowbug](https://attack.mitre.org/groups/G0054) has used keylogging tools.(Citation: Symantec Sowbug Nov 2017)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Sowbug](https://attack.mitre.org/groups/G0054) has used command line during its intrusions.(Citation: Symantec Sowbug Nov 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1039|Data from Network Shared Drive|[Sowbug](https://attack.mitre.org/groups/G0054) extracted Word documents from a file server on a victim network.(Citation: Symantec Sowbug Nov 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560.001|Archive via Utility|[Sowbug](https://attack.mitre.org/groups/G0054) extracted documents and bundled them into a RAR archive.(Citation: Symantec Sowbug Nov 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Containers|T1036.005|Match Legitimate Name or Location|[Sowbug](https://attack.mitre.org/groups/G0054) named its tools to masquerade as Windows or Adobe Reader software, such as by using the file name adobecms.exe and the directory <code>CSIDL_APPDATA\microsoft\security</code>.(Citation: Symantec Sowbug Nov 2017)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Sowbug](https://attack.mitre.org/groups/G0054) obtained OS version and hardware configuration from a victim.(Citation: Symantec Sowbug Nov 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1083|File and Directory Discovery|[Sowbug](https://attack.mitre.org/groups/G0054) identified and extracted all Word documents on a server by using a command containing * .doc and *.docx. The actors also searched for documents based on a specific date range and attempted to identify all installed software on a victim.(Citation: Symantec Sowbug Nov 2017)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1135|Network Share Discovery|[Sowbug](https://attack.mitre.org/groups/G0054) listed remote shared drives that were accessible from a victim.(Citation: Symantec Sowbug Nov 2017)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1003|OS Credential Dumping|[Sowbug](https://attack.mitre.org/groups/G0054) has used credential dumping tools.(Citation: Symantec Sowbug Nov 2017)|
