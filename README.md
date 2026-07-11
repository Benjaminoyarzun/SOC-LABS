# SOC-Labs

Collection of security investigations performed through hands-on blue team labs focused on incident response, log analysis, memory forensics, phishing detection, and network traffic investigation.

---

## Overview

This repository contains documented security investigations completed as part of practical cybersecurity training using platforms such as CyberDefenders and Let'sDefend.

The objective of these investigations is to develop and demonstrate fundamental SOC (Security Operations Center) skills, including:

* Log Analysis
* Memory Forensics
* Windows Process Analysis
* Incident Triage
* Network Traffic Analysis
* Timeline Reconstruction
* IOC Identification
* Threat Hunting Fundamentals
* Severity Assessment
* Escalation Decision Making
* MITRE ATT&CK Mapping

---

## Investigations

### Phishing Analysis (Let'sDefend)

Investigation of a phishing email impersonating PayPal.

**Key activities:**

* Email triage
* Sender validation
* URL analysis
* IOC identification
* Incident classification

**Skills demonstrated:**

* Phishing Detection
* Email Analysis
* Security Triage

---

### Hammered (CyberDefenders)

Investigation of a compromised Linux host using authentication and web server logs.

**Key findings included:**

* Suspicious SSH authentications
* Privilege escalation activity
* Root account modifications
* Persistence establishment through privileged account creation

**Skills demonstrated:**

* Linux Log Analysis
* SSH Investigation
* Privilege Escalation Detection
* Timeline Reconstruction

---

### PsExec (CyberDefenders)

Investigation of a packet capture involving suspected lateral movement activity.

**Key findings included:**

* SMB administrative share access
* PsExec service deployment
* Remote service creation through SVCCTL
* Evidence consistent with lateral movement between hosts

**Skills demonstrated:**

* Wireshark Analysis
* SMB Investigation
* Network Traffic Analysis
* Lateral Movement Detection

---

### Reveal (CyberDefenders)

Memory forensics investigation of a compromised Windows system using Volatility 3.

**Key findings included:**

* Hidden PowerShell execution
* LOLBin abuse (PowerShell, net.exe, and rundll32)
* Remote WebDAV connection
* Active TCP communication with an external host
* Attempted DLL execution from a remote WebDAV share

**Skills demonstrated:**

* Memory Forensics
* Volatility 3
* Windows Process Analysis
* Process Tree Analysis
* Command-line Analysis
* Network Artifact Correlation
* IOC Identification
* MITRE ATT&CK Mapping

---

## Repository Structure

Each investigation contains:

* README.md
* Findings
* Timeline
* Indicators of Compromise (IOCs)
* Memory Analysis *(when applicable)*
* Network Analysis *(when applicable)*
* MITRE ATT&CK Mapping
* Recommendations
* Investigation Notes / Raw Analysis

```text
SOC-Labs/
│
├── phishing-analysis/
├── hammered-log-analysis/
├── psexec-lateral-movement/
├── reveal-memory-forensics/
└── tools-and-notes/
```

---

## Tools Used

* Volatility 3
* Wireshark
* Kali Linux
* VSCode
* CyberDefenders
* Let'sDefend

---

## Current Focus

Currently developing practical SOC Analyst skills through:

* Incident Investigation
* Memory Forensics
* Log Analysis
* Network Traffic Analysis
* Threat Detection & Hunting
* Windows & Linux Security Analysis

---

## Disclaimer

These investigations are performed in controlled laboratory environments for educational purposes only. The analyses, findings, and recommendations are intended to demonstrate SOC investigation methodology and technical documentation skills.


This repository is intended for educational and portfolio purposes. All investigations were performed within controlled training environments and cybersecurity laboratory platforms.
