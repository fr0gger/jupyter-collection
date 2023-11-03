# APT37 - G0067

**Created**: 2018-04-18T17:59:24.739Z

**Modified**: 2021-10-15T16:54:01.193Z

**Contributors**: Valerii Marchuk, Cybersecurity Help s.r.o.

## Aliases

APT37,Richochet Chollima,InkySquid,ScarCruft,Reaper,Group123,TEMP.Reaper

## Description

[APT37](https://attack.mitre.org/groups/G0067) is a North Korean state-sponsored cyber espionage group that has been active since at least 2012. The group has targeted victims primarily in South Korea, but also in Japan, Vietnam, Russia, Nepal, China, India, Romania, Kuwait, and other parts of the Middle East. [APT37](https://attack.mitre.org/groups/G0067) has also been linked to the following campaigns between 2016-2018: Operation Daybreak, Operation Erebus, Golden Time, Evil New Year, Are you Happy?, FreeMilk, North Korean Human Rights, and Evil New Year 2018.(Citation: FireEye APT37 Feb 2018)(Citation: Securelist ScarCruft Jun 2016)(Citation: Talos Group123)

North Korean group definitions are known to have significant overlap, and some security researchers report all North Korean state-sponsored cyber activity under the name [Lazarus Group](https://attack.mitre.org/groups/G0032) instead of tracking clusters or subgroups.

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network,Office 365,Azure AD,IaaS,Google Workspace|T1059|Command and Scripting Interpreter|[APT37](https://attack.mitre.org/groups/G0067) has used Ruby scripts to execute payloads.(Citation: Volexity InkySquid RokRAT August 2021)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1059.006|Python|[APT37](https://attack.mitre.org/groups/G0067) has used Python scripts to execute payloads.(Citation: Volexity InkySquid RokRAT August 2021)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[APT37](https://attack.mitre.org/groups/G0067) has created scheduled tasks to run malicious scripts on a compromised host.(Citation: Volexity InkySquid RokRAT August 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[APT37](https://attack.mitre.org/groups/G0067) executes shellcode and a VBA script to decode Base64 strings.(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.003|Steganography|[APT37](https://attack.mitre.org/groups/G0067) uses steganography to send images to users that are embedded with shellcode.(Citation: Talos Group123)(Citation: Securelist ScarCruft May 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1529|System Shutdown/Reboot|[APT37](https://attack.mitre.org/groups/G0067) has used malware that will issue the command <code>shutdown /r /t 1</code> to reboot a system after wiping its MBR.(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Windows|T1548.002|Bypass User Account Control|[APT37](https://attack.mitre.org/groups/G0067) has a function in the initial dropper to bypass Windows UAC in order to execute the next payload with higher privileges.(Citation: Securelist ScarCruft May 2019)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1120|Peripheral Device Discovery|[APT37](https://attack.mitre.org/groups/G0067) has a Bluetooth device harvester, which uses Windows Bluetooth APIs to find information on connected Bluetooth devices. (Citation: Securelist ScarCruft May 2019)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[APT37](https://attack.mitre.org/groups/G0067) collects the computer name, the BIOS model, and execution path.(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1033|System Owner/User Discovery|[APT37](https://attack.mitre.org/groups/G0067) identifies the victim username.(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[APT37](https://attack.mitre.org/groups/G0067) obfuscates strings and payloads.(Citation: Talos Group123)(Citation: Securelist ScarCruft May 2019)(Citation: Volexity InkySquid RokRAT August 2021)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1106|Native API|[APT37](https://attack.mitre.org/groups/G0067) leverages the Windows API calls: VirtualAlloc(), WriteProcessMemory(), and CreateRemoteThread() for process injection.(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[APT37](https://attack.mitre.org/groups/G0067)'s Freenki malware lists running processes using the Microsoft Windows API.(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1055|Process Injection|[APT37](https://attack.mitre.org/groups/G0067) injects its malware variant, [ROKRAT](https://attack.mitre.org/software/S0240), into the cmd.exe process.(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[APT37](https://attack.mitre.org/groups/G0067) uses HTTPS to conceal C2 communications.(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[APT37](https://attack.mitre.org/groups/G0067) has used the command-line interface.(Citation: FireEye APT37 Feb 2018)(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS,SaaS|T1189|Drive-by Compromise|[APT37](https://attack.mitre.org/groups/G0067) has used strategic web compromises, particularly of South Korean websites, to distribute malware. The group has also used torrent file-sharing sites to more indiscriminately disseminate malware to victims. As part of their compromises, the group has used a Javascript based profiler called RICECURRY to profile a victim's web browser and deliver malicious code accordingly.(Citation: Securelist ScarCruft Jun 2016)(Citation: FireEye APT37 Feb 2018)(Citation: Volexity InkySquid BLUELIGHT August 2021)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[APT37](https://attack.mitre.org/groups/G0067) has used exploits for Flash Player (CVE-2016-4117, CVE-2018-4878), Word (CVE-2017-0199), Internet Explorer (CVE-2020-1380 and CVE-2020-26411), and Microsoft Edge (CVE-2021-26411) for execution.(Citation: Securelist ScarCruft Jun 2016)(Citation: FireEye APT37 Feb 2018)(Citation: Talos Group123)(Citation: Volexity InkySquid BLUELIGHT August 2021)|
|mitre-attack|enterprise-attack|Windows|T1559.002|Dynamic Data Exchange|[APT37](https://attack.mitre.org/groups/G0067) has used Windows DDE for execution of commands and a malicious VBS.(Citation: Securelist ScarCruft Jun 2016)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[APT37](https://attack.mitre.org/groups/G0067) delivers malware using spearphishing emails with malicious HWP attachments.(Citation: FireEye APT37 Feb 2018)(Citation: Talos Group123)(Citation: Securelist ScarCruft May 2019)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1123|Audio Capture|[APT37](https://attack.mitre.org/groups/G0067) has used an audio capturing utility known as SOUNDWAVE that captures microphone input.(Citation: FireEye APT37 Feb 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1555.003|Credentials from Web Browsers|[APT37](https://attack.mitre.org/groups/G0067) has used a credential stealer known as ZUMKONG that can harvest usernames and passwords stored in browsers.(Citation: FireEye APT37 Feb 2018)|
|mitre-attack|enterprise-attack|macOS,Windows|T1036.001|Invalid Code Signature|[APT37](https://attack.mitre.org/groups/G0067) has signed its malware with an invalid digital certificates listed as “Tencent Technology (Shenzhen) Company Limited.”(Citation: Securelist ScarCruft Jun 2016)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[APT37](https://attack.mitre.org/groups/G0067)'s has added persistence via the Registry key <code>HKCU\Software\Microsoft\CurrentVersion\Run\</code>.(Citation: FireEye APT37 Feb 2018)(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1102.002|Bidirectional Communication|[APT37](https://attack.mitre.org/groups/G0067) leverages social networking sites and cloud platforms (AOL, Twitter, Yandex, Mediafire, pCloud, Dropbox, and Box) for C2.(Citation: FireEye APT37 Feb 2018)(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1005|Data from Local System|[APT37](https://attack.mitre.org/groups/G0067) has collected data from victims' local systems.(Citation: FireEye APT37 Feb 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[APT37](https://attack.mitre.org/groups/G0067) has sent spearphishing attachments attempting to get a user to open them.(Citation: FireEye APT37 Feb 2018)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1561.002|Disk Structure Wipe|[APT37](https://attack.mitre.org/groups/G0067) has access to destructive malware that is capable of overwriting a machine's Master Boot Record (MBR).(Citation: FireEye APT37 Feb 2018)(Citation: Talos Group123)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1105|Ingress Tool Transfer|[APT37](https://attack.mitre.org/groups/G0067) has downloaded second stage malware from compromised websites.(Citation: FireEye APT37 Feb 2018)(Citation: Securelist ScarCruft May 2019)(Citation: Volexity InkySquid BLUELIGHT August 2021)(Citation: Volexity InkySquid RokRAT August 2021)|
