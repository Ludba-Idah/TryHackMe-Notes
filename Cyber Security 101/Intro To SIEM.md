# Room: Introduction to SIEM

**Category:** Fundamentals

## Overview
This room covers the fundamentals of SIEM (Security Information and Event Management) and it also explains the importance of network logs.
## Key Takeaways

Log Sources and Categories
* **Log Sources ->** Any device that continuously generates a digital paper trail of its activities to assist in troubleshooting and threat detection.
* **Host-Centric Logs ->** Logs that capture internal events happening locally within a single device, such as a user accessing files, authenticating, running processes or executing PowerShell scripts.
* **Network-Centric Logs ->** Logs generated when hosts communicate with each other, capturing activities like SSH connections, FTP file transfers, web traffic, and VPN resource access.

Log Management Challenges
* **Numerous Log Sources ->** Networks contain many devices generating hundreds of events per second, making it tedious to examine logs on each device individually.
* **No Centralization ->** Because logs naturally reside locally on the machines that created them, analysts waste valuable time manually connecting to individual systems via SSH or RDP during investigations.
* **Limited Context ->** Individual logs often seem harmless on their own; without correlation across different devices, critical attack patterns remain hidden.
* **Limited Analysis ->** The massive volume of logs generated every second makes manual human review impossible, leading to missed alerts.
* **Format Issues ->** Different log sources generate data in widely varying formats, forcing analysts to memorize multiple syntax structures across various operating systems and appliances.

Core Features of SIEM
* **Centralized Log Collection ->** SIEM solutions automatically aggregate data from all network endpoints, firewalls, and servers into one repository using lightweight agents or APIs.
* **Normalization of Logs ->** The process where raw logs are parsed (broken down into distinct fields like user, IP, and action) and normalized into a single, uniform layout for easy querying.
* **Correlation of Logs ->** The system analyzes timelines and links seemingly isolated events across multiple devices to uncover broader malicious patterns, such as data exfiltration from compromised credentials.
* **Real-time Alerting ->** Built-in and custom detection rules evaluate log conditions instantly, automatically triggering notifications for security analysts when specific threat behaviors are matched.
* **Dashboards and Reporting ->** Visual command centers that synthesize normalized data into clear charts, graphs, and actionable metrics like failed login trends, alert highlights, and health notices.
