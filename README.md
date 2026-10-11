# Log Analysis Projects

**Target role:** SOC Analyst L1  
**Focus:** Event analysis • Authentication monitoring • Endpoint telemetry • SIEM fundamentals

A collection of log-analysis exercises covering web, Linux, Windows, and SIEM data sources.

## Project Index
1. [Apache Web Server Log Analysis](https://github.com/bala-soc/Log-Analysis-Projects/blob/main/1.%20Apache%20Web%20Server%20Log%20Analysis.md)
2. [Linux Syslog Analysis](https://github.com/bala-soc/Log-Analysis-Projects/blob/main/2.%20Syslog%20Analysis%20on%20Linux%20Systems.md)
3. [Windows Event Log Analysis](https://github.com/bala-soc/Log-Analysis-Projects/blob/main/3.%20Analyzing%20Windows%20Event%20Logs.md)
4. [Log Analysis with the ELK Stack](https://github.com/bala-soc/Log-Analysis-Projects/blob/main/4.%20Log%20Analysis%20with%20ELK%20Stack.md)
5. [Windows Sysmon Event Analysis](https://github.com/bala-soc/Log-Analysis-Projects/blob/main/5.%20Analyzing%20Windows%20Sysmon%20Events%20for%20Security%20Incidents.md)

## Investigation Workflow
- Identify the question, source, and relevant time range.
- Filter events and examine the fields available in the data.
- Correlate authentication, process, network, and web activity where relevant.
- Separate suspicious indicators from confirmed conclusions.
- Document evidence, false-positive considerations, limitations, and next steps.

## Tools
Windows Event Viewer, Sysmon, Linux syslog, Apache logs, Elasticsearch, Logstash, Kibana, and command-line utilities.

## Safe Practice
Use authorised systems and sample data. Redact usernames, hostnames, IP addresses, and other sensitive details before publishing log excerpts.