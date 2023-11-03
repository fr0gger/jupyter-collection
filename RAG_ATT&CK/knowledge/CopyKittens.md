# CopyKittens - G0052

**Created**: 2018-01-16T16:13:52.465Z

**Modified**: 2022-08-08T21:29:36.462Z

**Contributors**: 

## Aliases

CopyKittens

## Description

[CopyKittens](https://attack.mitre.org/groups/G0052) is an Iranian cyber espionage group that has been operating since at least 2013. It has targeted countries including Israel, Saudi Arabia, Turkey, the U.S., Jordan, and Germany. The group is responsible for the campaign known as Operation Wilted Tulip.(Citation: ClearSky CopyKittens March 2017)(Citation: ClearSky Wilted Tulip July 2017)(Citation: CopyKittens Nov 2015)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1090|Proxy|[CopyKittens](https://attack.mitre.org/groups/G0052) has used the AirVPN service for operational activity.(Citation: Microsoft POLONIUM June 2022)|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[CopyKittens](https://attack.mitre.org/groups/G0052) has used Metasploit, [Empire](https://attack.mitre.org/software/S0363), and AirVPN for post-exploitation activities.(Citation: ClearSky and Trend Micro Operation Wilted Tulip July 2017)(Citation: Microsoft POLONIUM June 2022)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1564.003|Hidden Window|[CopyKittens](https://attack.mitre.org/groups/G0052) has used <code>-w hidden</code> and <code>-windowstyle hidden</code> to conceal [PowerShell](https://attack.mitre.org/techniques/T1059/001) windows. (Citation: ClearSky Wilted Tulip July 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560.003|Archive via Custom Method|[CopyKittens](https://attack.mitre.org/groups/G0052) encrypts data with a substitute cipher prior to exfiltration.(Citation: CopyKittens Nov 2015)|
|mitre-attack|enterprise-attack|Windows|T1218.011|Rundll32|[CopyKittens](https://attack.mitre.org/groups/G0052) uses rundll32 to load various tools on victims, including a lateral movement tool named Vminst, Cobalt Strike, and shellcode.(Citation: ClearSky Wilted Tulip July 2017)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1560.001|Archive via Utility|[CopyKittens](https://attack.mitre.org/groups/G0052) uses ZPP, a .NET console program, to compress files with ZIP.(Citation: ClearSky Wilted Tulip July 2017)|
|mitre-attack|enterprise-attack|Windows|T1059.001|PowerShell|[CopyKittens](https://attack.mitre.org/groups/G0052) has used PowerShell Empire.(Citation: ClearSky Wilted Tulip July 2017)|
|mitre-attack|enterprise-attack|macOS,Windows|T1553.002|Code Signing|[CopyKittens](https://attack.mitre.org/groups/G0052) digitally signed an executable with a stolen certificate from legitimate company AI Squared.(Citation: ClearSky Wilted Tulip July 2017)|
