# Higaisa - G0126

**Created**: 2021-03-05T18:54:56.267Z

**Modified**: 2021-04-22T02:12:43.892Z

**Contributors**: Daniyal Naeem, BT Security

## Aliases

Higaisa

## Description

[Higaisa](https://attack.mitre.org/groups/G0126) is a threat group suspected to have South Korean origins. [Higaisa](https://attack.mitre.org/groups/G0126) has targeted government, public, and trade organizations in North Korea; however, they have also carried out attacks in China, Japan, Russia, Poland, and other nations. [Higaisa](https://attack.mitre.org/groups/G0126) was first disclosed in early 2019 but is assessed to have operated as early as 2009.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)(Citation: PTSecurity Higaisa 2020)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.005|Visual Basic|[Higaisa](https://attack.mitre.org/groups/G0126) has used VBScript code on the victim's machine.(Citation: PTSecurity Higaisa 2020)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1106|Native API|[Higaisa](https://attack.mitre.org/groups/G0126) has called various native OS APIs.(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Windows|T1574.002|DLL Side-Loading|[Higaisa](https://attack.mitre.org/groups/G0126)’s JavaScript file used a legitimate Microsoft Office 2007 package to side-load the <code>OINFO12.OCX</code> dynamic link library.(Citation: PTSecurity Higaisa 2020)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1564.003|Hidden Window|[Higaisa](https://attack.mitre.org/groups/G0126) used a payload that creates a hidden window.(Citation: PTSecurity Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1057|Process Discovery|[Higaisa](https://attack.mitre.org/groups/G0126)’s shellcode attempted to find the process ID of the current process.(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1029|Scheduled Transfer|[Higaisa](https://attack.mitre.org/groups/G0126) sent the victim computer identifier in a User-Agent string back to the C2 server every 10 minutes.(Citation: PTSecurity Higaisa 2020)|
|mitre-attack|enterprise-attack|Windows,IaaS,Linux,macOS,Network|T1082|System Information Discovery|[Higaisa](https://attack.mitre.org/groups/G0126) collected the system volume serial number, GUID, and computer name.(Citation: PTSecurity Higaisa 2020)(Citation: Malwarebytes Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1203|Exploitation for Client Execution|[Higaisa](https://attack.mitre.org/groups/G0126) has exploited CVE-2018-0798 for execution.(Citation: PTSecurity Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1204.002|Malicious File|[Higaisa](https://attack.mitre.org/groups/G0126) used malicious e-mail attachments to lure victims into executing LNK files.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Windows|T1053.005|Scheduled Task|[Higaisa](https://attack.mitre.org/groups/G0126) dropped and added <code>officeupdate.exe</code> to scheduled tasks.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|macOS,Windows,Linux|T1566.001|Spearphishing Attachment|[Higaisa](https://attack.mitre.org/groups/G0126) has sent spearphishing emails containing malicious attachments.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020) |
|mitre-attack|enterprise-attack|Windows,Network|T1124|System Time Discovery|[Higaisa](https://attack.mitre.org/groups/G0126) used a function to gather the current time.(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Windows|T1547.001|Registry Run Keys / Startup Folder|[Higaisa](https://attack.mitre.org/groups/G0126) added a spoofed binary to the start-up folder for persistence.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Windows|T1059.003|Windows Command Shell|[Higaisa](https://attack.mitre.org/groups/G0126) used <code>cmd.exe</code> for execution.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)(Citation: PTSecurity Higaisa 2020)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1059.007|JavaScript|[Higaisa](https://attack.mitre.org/groups/G0126) used JavaScript to execute additional files.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)(Citation: PTSecurity Higaisa 2020)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1036.004|Masquerade Task or Service|[Higaisa](https://attack.mitre.org/groups/G0126) named a shellcode loader binary <code>svchast.exe</code> to spoof the legitimate <code>svchost.exe</code>.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020) |
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1140|Deobfuscate/Decode Files or Information|[Higaisa](https://attack.mitre.org/groups/G0126) used certutil to decode Base64 binaries at runtime and a 16-byte XOR key to decrypt data.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Windows|T1220|XSL Script Processing|[Higaisa](https://attack.mitre.org/groups/G0126) used an XSL file to run VBScript code.(Citation: PTSecurity Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027|Obfuscated Files or Information|[Higaisa](https://attack.mitre.org/groups/G0126) used Base64 encoded compressed payloads.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1090.001|Internal Proxy|[Higaisa](https://attack.mitre.org/groups/G0126) discovered system proxy settings and used them if available.(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1071.001|Web Protocols|[Higaisa](https://attack.mitre.org/groups/G0126) used HTTP and HTTPS to send data back to its C2 server.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1001.003|Protocol Impersonation|[Higaisa](https://attack.mitre.org/groups/G0126) used a FakeTLS session for C2 communications.(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,Windows,macOS|T1573.001|Symmetric Cryptography|[Higaisa](https://attack.mitre.org/groups/G0126) used AES-128 to encrypt C2 traffic.(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows,Network|T1016|System Network Configuration Discovery|[Higaisa](https://attack.mitre.org/groups/G0126) used <code>ipconfig</code> to gather network configuration information.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1041|Exfiltration Over C2 Channel|[Higaisa](https://attack.mitre.org/groups/G0126) exfiltrated data over its C2 channel.(Citation: Zscaler Higaisa 2020)|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1027.001|Binary Padding|[Higaisa](https://attack.mitre.org/groups/G0126) performed padding with null bytes before calculating its hash.(Citation: Zscaler Higaisa 2020)|
