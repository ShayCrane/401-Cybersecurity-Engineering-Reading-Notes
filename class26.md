Reading Notes <br>
Class 26<br>
Re: Cyber Threat Analyst Role; Remote Code Execution<br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity topics.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>

## Cyber Threat Analyst: Key Job Skills and Expected Salary
***https://www.spiceworks.com/it-security/vulnerability-management/articles/cyber-threat-analyst-key-jobs-and-salary/***<br><br>

**Typical Duties**:
- monitor enterprise network for security breaches; investigate vilations
- install, use data encryption programs/firewalls 
- pen testing
- document breaches, damage caused by breaches; reports
- build/maintain security standards/best practices for a company
- keep up with security trends
- work with team to develop security policy; implement policy
- recommend security enhancements to senior management
- decision makers regarding best tools for various relevant security issues
- monitor, audit system/processes (ex.: access management)
- cybersecurity awareness training for other departments




<br><br>



## Tracking, Detecting, and Thwarting PowerShell-based Malware and Attacks
***https://www.trendmicro.com/vinfo/us/security/news/cybercrime-and-digital-threats/tracking-detecting-and-thwarting-powershell-based-malware-and-attacks***<br><br>


***PowerShell is an effective attack vector because***:
- is an ideal channel for delivering payload attacks
- has access to all parts of a host via .NET framework
- scripts are easy to develop
- is a trusted application, often allowed to execute with impunity

<br>

***Prominent attacks that use PowerShell***: 
- Pawn Storm: https://www.trendmicro.com/vinfo/us/security/news/cyber-attacks/espionage-cyber-propaganda-two-years-of-pawn-storm
- Equifax breach: https://www.trendmicro.com/vinfo/us/security/news/cyber-attacks/equifax-reveals-extent-of-2017-data-breach-number-of-stolen-records
- APT33: https://www.trendmicro.com/vinfo/ph/security/news/internet-of-things/drilling-deep-a-look-at-cyberattacks-on-the-oil-and-gas-industry 
<br><br>

***Mitigation and best practices***
- track PowerShell's activities with module logging
- script block logging
- transcription (records only input/output from powershell session)
- counter obfuscation
- behavior monitoring

