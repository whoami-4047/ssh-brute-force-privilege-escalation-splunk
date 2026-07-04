# SSH Brute Force Detection & Privilege Escalation Investigation using Splunk

## Overview

This project demonstrates a complete SOC investigation in a controlled lab environment. An SSH brute-force attack was simulated against a Linux server, followed by privilege escalation. Security events were collected, monitored, and investigated using Splunk SIEM.

---

## Objectives

- Detect SSH brute-force attempts
- Identify successful authentication
- Investigate privilege escalation
- Detect access to sensitive files
- Analyze Linux logs using Splunk
- Map attacker activity to MITRE ATT&CK

---

## Lab Environment

| Component | Technology |
|----------|------------|
| Attacker | Kali Linux |
| Target | Ubuntu Server |
| SIEM | Splunk Enterprise |
| Log Forwarder | Splunk Universal Forwarder |
| Logs | auth.log, audit.log |

---

## Tools Used

- Splunk Enterprise
- Kali Linux
- Ubuntu Server
- Splunk Universal Forwarder
- Linux Audit Logs

---

## Attack Workflow

1. SSH Brute Force Attack
2. Successful Authentication
3. Privilege Escalation
4. Root Command Execution
5. Access to /etc/shadow
6. Incident Investigation
7. MITRE ATT&CK Mapping
8. Remediation

---

## Skills Demonstrated

- SIEM Monitoring
- Log Analysis
- Threat Detection
- Incident Investigation
- Linux Security Monitoring
- MITRE ATT&CK
- Cyber Kill Chain
- Splunk SPL Queries

---

## Report

The complete incident report is available in the `report` folder.

---

## Screenshots

Project screenshots are available in the `screenshots` folder.

---

## Author

**Amir Mulla**

SOC Analyst | Cybersecurity Analyst
