# Silent Librarian - G0122

**Created**: 2021-02-03T16:36:38.145Z

**Modified**: 2021-04-21T12:02:00.278Z

**Contributors**: 

## Aliases

Silent Librarian,TA407,COBALT DICKENS

## Description

[Silent Librarian](https://attack.mitre.org/groups/G0122) is a group that has targeted research and proprietary data at universities, government agencies, and private sector companies worldwide since at least 2013. Members of  [Silent Librarian](https://attack.mitre.org/groups/G0122) are known to have been affiliated with the Iran-based Mabna Institute which has conducted cyber intrusions at the behest of the government of Iran, specifically the Islamic Revolutionary Guard Corps (IRGC).(Citation: DOJ Iran Indictments March 2018)(Citation: Phish Labs Silent Librarian)(Citation: Malwarebytes Silent Librarian October 2020)

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
|mitre-attack|enterprise-attack|PRE|T1608.005|Link Target|[Silent Librarian](https://attack.mitre.org/groups/G0122) has cloned victim organization login pages and staged them for later use in credential harvesting campaigns. [Silent Librarian](https://attack.mitre.org/groups/G0122) has also made use of a variety of URL shorteners for these staged websites.(Citation: Secureworks COBALT DICKENS September 2019)(Citation: Malwarebytes Silent Librarian October 2020)(Citation: Proofpoint TA407 September 2019)|
|mitre-attack|enterprise-attack|PRE|T1588.002|Tool|[Silent Librarian](https://attack.mitre.org/groups/G0122) has obtained free and publicly available tools including SingleFile and HTTrack to copy login pages of targeted organizations.(Citation: Proofpoint TA407 September 2019)(Citation: Secureworks COBALT DICKENS September 2019)|
|mitre-attack|enterprise-attack|PRE|T1588.004|Digital Certificates|[Silent Librarian](https://attack.mitre.org/groups/G0122) has obtained free Let's Encrypt SSL certificates for use on their phishing pages.(Citation: Phish Labs Silent Librarian)(Citation: Secureworks COBALT DICKENS September 2019)|
|mitre-attack|enterprise-attack|PRE|T1585.002|Email Accounts|[Silent Librarian](https://attack.mitre.org/groups/G0122) has established e-mail accounts to receive e-mails forwarded from compromised accounts.(Citation: DOJ Iran Indictments March 2018)|
|mitre-attack|enterprise-attack|Windows,Office 365,Google Workspace,macOS,Linux|T1114|Email Collection|[Silent Librarian](https://attack.mitre.org/groups/G0122) has exfiltrated entire mailboxes from compromised accounts.(Citation: DOJ Iran Indictments March 2018)|
|mitre-attack|enterprise-attack|Office 365,Windows,Google Workspace,macOS,Linux|T1114.003|Email Forwarding Rule|[Silent Librarian](https://attack.mitre.org/groups/G0122) has set up auto forwarding rules on compromised e-mail accounts.(Citation: DOJ Iran Indictments March 2018)|
|mitre-attack|enterprise-attack|PRE|T1589.002|Email Addresses|[Silent Librarian](https://attack.mitre.org/groups/G0122) has collected e-mail addresses from targeted organizations from open Internet searches.(Citation: DOJ Iran Indictments March 2018)|
|mitre-attack|enterprise-attack|PRE|T1589.003|Employee Names|[Silent Librarian](https://attack.mitre.org/groups/G0122) has collected lists of names for individuals from targeted organizations.(Citation: DOJ Iran Indictments March 2018)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers|T1110.003|Password Spraying|[Silent Librarian](https://attack.mitre.org/groups/G0122) has used collected lists of names and e-mail accounts to use in password spraying attacks against private sector targets.(Citation: DOJ Iran Indictments March 2018)|
|mitre-attack|enterprise-attack|Windows,Azure AD,Office 365,SaaS,IaaS,Linux,macOS,Google Workspace,Containers,Network|T1078|Valid Accounts|[Silent Librarian](https://attack.mitre.org/groups/G0122) has used compromised credentials to obtain unauthorized access to online accounts.(Citation: DOJ Iran Indictments March 2018)|
|mitre-attack|enterprise-attack|PRE|T1583.001|Domains|[Silent Librarian](https://attack.mitre.org/groups/G0122) has acquired domains to establish credential harvesting pages, often spoofing the target organization and using free top level domains .TK, .ML, .GA, .CF, and .GQ.(Citation: DOJ Iran Indictments March 2018)(Citation: Phish Labs Silent Librarian)(Citation: Secureworks COBALT DICKENS August 2018)(Citation: Proofpoint TA407 September 2019)(Citation: Secureworks COBALT DICKENS September 2019)(Citation: Malwarebytes Silent Librarian October 2020)|
|mitre-attack|enterprise-attack|PRE|T1594|Search Victim-Owned Websites|[Silent Librarian](https://attack.mitre.org/groups/G0122) has searched victim's websites to identify the interests and academic areas of targeted individuals and to scrape source code, branding, and organizational contact information for phishing pages.(Citation: DOJ Iran Indictments March 2018)(Citation: Phish Labs Silent Librarian)(Citation: Proofpoint TA407 September 2019)|
|mitre-attack|enterprise-attack|PRE|T1598.003|Spearphishing Link|[Silent Librarian](https://attack.mitre.org/groups/G0122) has used links in e-mails to direct victims to credential harvesting websites designed to appear like the targeted organization's login page.(Citation: DOJ Iran Indictments March 2018)(Citation: Phish Labs Silent Librarian)(Citation: Secureworks COBALT DICKENS August 2018)(Citation: Proofpoint TA407 September 2019)(Citation: Secureworks COBALT DICKENS September 2019)(Citation: Malwarebytes Silent Librarian October 2020)|
