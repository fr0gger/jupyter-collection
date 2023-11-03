# ALLANITE - G1000

**Created**: 2017-05-31T21:31:57.307Z

**Modified**: 2022-05-24T19:26:10.721Z

**Contributors**: Dragos Threat Intelligence

## Aliases

ALLANITE,Palmetto Fusion

## Description

[ALLANITE](https://attack.mitre.org/groups/G1000) is a suspected Russian cyber espionage group, that has primarily targeted the electric utility sector within the United States and United Kingdom. The group's tactics and techniques are reportedly similar to [Dragonfly](https://attack.mitre.org/groups/G0035), although [ALLANITE](https://attack.mitre.org/groups/G1000)s technical capabilities have not exhibited disruptive or destructive abilities. It has been suggested that the group maintains a presence in ICS for the purpose of gaining understanding of processes and to maintain persistence. (Citation: Dragos)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|ics-attack|Human-Machine Interface|T0852|Screen Capture|[ALLANITE](https://attack.mitre.org/groups/G1000) has been identified to collect and distribute screenshots of ICS systems such as HMIs. (Citation: Dragos) (Citation: ICS-CERT October 2017)|
|mitre-attack|ics-attack|None|T0817|Drive-by Compromise|[ALLANITE](https://attack.mitre.org/groups/G1000) leverages watering hole attacks to gain access into electric utilities. (Citation: Eduard Kovacs May 2018)|
|mitre-attack|ics-attack|Engineering Workstation,Human-Machine Interface,Control Server,Data Historian|T0865|Spearphishing Attachment|[ALLANITE](https://attack.mitre.org/groups/G1000) utilized spear phishing to gain access into energy sector environments. (Citation: Jeff Jones May 2018)|
|mitre-attack|ics-attack|Control Server,Data Historian,Engineering Workstation,Field Controller/RTU/PLC/IED,Human-Machine Interface,Input/Output Server,Safety Instrumented System/Protection Relay|T0859|Valid Accounts|[ALLANITE](https://attack.mitre.org/groups/G1000) utilized credentials collected through phishing and watering hole attacks. (Citation: Dragos)|
