# Sujal Chetan Parmar — SOC Analyst Portfolio

B.Tech Computer Science (Cyber Security, IoT and Blockchain Technology) | REVA University, Bengaluru

## About

SOC-focused security professional with hands-on experience in SIEM monitoring, log analysis, threat detection, and incident response. This repository documents practical work across Active Directory security monitoring, EDR/SOAR automation, and network traffic analysis — the core toolset of a SOC L1 analyst — alongside a completed cyber security internship.

## Experience

**Cyber Security Intern | Codec Technologies Pvt. Ltd.**
Completed an AICTE-recognized internship covering the defensive security lifecycle — SIEM, endpoint security, vulnerability assessment, and incident response. Delivered an Active Directory SOC lab as the capstone project, applying detection and investigation skills to a simulated domain environment.

## Projects

**Active Directory SOC Environment with Splunk**
Deployed a multi-VM Active Directory lab (Windows Server, Windows 10, Kali) with Sysmon and Splunk Universal Forwarder shipping endpoint telemetry into a centralised index. Detected and investigated an RDP brute-force attack by correlating Event IDs 4624/4625 in Splunk, and validated detection coverage against MITRE ATT&CK techniques (T1136.001, T1059.001) using Atomic Red Team.
[Repo link]

**SOC Automation with LimaCharlie EDR and Tines SOAR**
Built a custom LimaCharlie detection rule for credential recovery tool activity on a Windows endpoint. Integrated the detection into a Tines SOAR playbook that alerts the analyst via Slack and email, and executes host isolation only on human approval — mirroring real-world SOC escalation practice.
[Repo link]

**Network Traffic Analysis Tool (Python, Scapy)**
Built a packet capture analysis tool to support network-based threat detection: port scanning, C2 beaconing, and DNS tunneling. Validated detection logic against real-world malware traffic captures to confirm accuracy.
[Repo link]

## Skills & Tools

**SIEM & Log Analysis:** Splunk, Windows Event Logs, syslog, log correlation and analysis
**Detection & Incident Response:** MITRE ATT&CK, incident investigation, IOC extraction and enrichment, EDR/SOAR (LimaCharlie, Tines)
**Network Security:** Wireshark, tcpdump, Nmap, TCP/IP, DNS, HTTP/S, firewalls, IDS/IPS
**Systems & Identity:** Active Directory, Windows, Linux, VMware
**Application Security:** Burp Suite, OWASP Top 10, vulnerability assessment
**Programming & Scripting:** Python, PowerShell, Bash, SQL

## Certifications

- Cisco Security Operations — Cisco Networking Academy
- SOC Level 1 Learning Path — TryHackMe
- Fortinet NSE 1 — Cybersecurity and Cloud
- Pre Security Learning Path — TryHackMe

## Profiles

- TryHackMe: tryhackme.com/p/sujalparmar2004
- LinkedIn: linkedin.com/in/sujalparmar
