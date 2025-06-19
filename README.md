# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard Labs continues to observe ongoing attack attempts targeting SimpleHelp, a Remote Monitoring and Management (RMM) software, due to a critical unauthenticated path traversal vulnerability (CVE-2024-57727) affecting versions 5.5.7 and earlier.  

 The **Outbreak Response - SimpleHelp Support Software Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.1.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/simplehelp-ransomware-attack) contains information about the outbreak alert **Outbreak Response - SimpleHelp Support Software Attack**. 

## Background: 

This flaw allows remote attackers to access and download arbitrary files from the server without authentication, simply by sending specially crafted HTTP requests. The exposed files may contain highly sensitive information, including server configuration data, hashed administrator passwords, API keys, and other credentials. These exploits impact SimpleHelp v5.5.7 and all earlier releases and The root cause is improper input validation, which lets attackers manipulate file paths to reach files outside the intended directories. 

According to Cybersecurity Advisory published by the Cybersecurity and Infrastructure Security Agency (CISA), multiple ransomware groups, including initial access brokers with ties to Play ransomware operators, exploited the vulnerabilities in remote monitoring and management (RMM) tool SimpleHelp to conduct remote code execution. 

## Announced: 

FortiGuard Labs urges all users of SimpleHelp to upgrade to the latest available version as soon as possible, if not done already. 

## Latest Developments: 

June 12, 2025: CISA Released an advisory: Ransomware Actors Exploit Unpatched SimpleHelp Remote Monitoring and Management to Compromise Utility Billing Software Provider
https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-163a

June 4, 2025: Play Ransomware was observed exploiting CVE-2024-57727 for initial access.
https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-352a

May 29, 2025: FortiGuard Labs released a Threat Signal Report on SimpleHelp Path Traversal Vulnerability
https://www.fortiguard.com/threat-signal-report/6107/simplehelp-path-traversal-vulnerability

February 13, 2025: This vulnerability was added to CISA's Known Exploited Vulnerabilities catalog

January 22, 2025: Arctic Wolf began observing a campaign involving unauthorised access to devices running SimpleHelp RMM software as an initial access vector
https://arcticwolf.com/resources/blog-uk/arctic-wolf-observes-campaign-exploiting-simplehelp-rmm-software-initial-access/ 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
