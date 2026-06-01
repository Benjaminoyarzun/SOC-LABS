# SOC-Labs

Collection of security investigations performed through hands-on blue team labs focused on incident analysis, log review, phishing detection, and network traffic investigation.

---

## Overview

This repository contains documented security investigations completed as part of practical cybersecurity training using platforms such as CyberDefenders and Let'sDefend.

The objective of these investigations is to develop and demonstrate fundamental SOC (Security Operations Center) skills, including:

* Log Analysis
* Incident Triage
* Network Traffic Analysis
* Timeline Reconstruction
* IOC Identification
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

## Repository Structure

Each investigation contains:

* README.md
* Findings
* Timeline (when applicable)
* Indicators of Compromise (IOCs)
* Recommendations
* MITRE ATT&CK Mapping (when applicable)
* Investigation Notes / Raw Analysis

```text
SOC-Labs/
│
├── phishing-analysis/
├── hammered-log-analysis/
├── psexec-lateral-movement/
└── tools-and-notes/
```

---

## Tools Used

* Wireshark
* Kali Linux
* VSCode
* CyberDefenders
* Let'sDefend

---

## Current Focus

Currently developing practical SOC Analyst skills through:

* Incident Investigation
* Log Analysis
* Network Traffic Analysis
* Linux Administration Fundamentals
* Threat Detection Methodologies

---

## Disclaimer

This repository is intended for educational and portfolio purposes. All investigations were performed within controlled training environments and cybersecurity laboratory platforms.
