# Equation - G0020

**Created**: 2017-05-31T21:31:54.697Z

**Modified**: 2020-06-29T01:39:22.044Z

**Contributors**: 

## Aliases

Equation

## Description

[Equation](https://attack.mitre.org/groups/G0020) is a sophisticated threat group that employs multiple remote access tools. The group is known to use zero-day exploits and has developed the capability to overwrite the firmware of hard disk drives. (Citation: Kaspersky Equation QA)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1564.005|Hidden File System|[Equation](https://attack.mitre.org/groups/G0020) has used an encrypted virtual file system stored in the Windows Registry.(Citation: Kaspersky Equation QA)|
|mitre-attack|enterprise-attack|Windows,Linux,macOS|T1542.002|Component Firmware|[Equation](https://attack.mitre.org/groups/G0020) is known to have the capability to overwrite the firmware on hard drives from some manufacturers.(Citation: Kaspersky Equation QA) |
|mitre-attack|enterprise-attack|Linux,macOS,Windows|T1480.001|Environmental Keying|[Equation](https://attack.mitre.org/groups/G0020) has been observed utilizing environmental keying in payload delivery.(Citation: Kaspersky Gauss Whitepaper)(Citation: Kaspersky Equation QA)|
|mitre-attack|enterprise-attack|Windows,macOS,Linux|T1120|Peripheral Device Discovery|[Equation](https://attack.mitre.org/groups/G0020) has used tools with the functionality to search for specific information about the attached hard drive that could be used to identify and overwrite the firmware.(Citation: Kaspersky Equation QA)|
