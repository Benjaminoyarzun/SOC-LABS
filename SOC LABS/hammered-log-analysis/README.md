# Hammered - CyberDefenders

## Scenario

Investigation of a potentially compromised Linux host based on authentication and web server logs.

## Objective

Determine whether unauthorized access occurred, identify privilege escalation activity, and assess evidence of persistence.

## Evidence Sources

- auth.log
- user.log
- Apache access logs

## Key Findings

- Multiple successful SSH authentications following failed login attempts.
- Root password modification events observed.
- Privileged account creation (UID=0) detected.
- Service manipulation involving Apache identified.
- Evidence consistent with persistence establishment.

## Severity

High

## MITRE ATT&CK

- T1078 - Valid Accounts
- T1021.004 - SSH
- T1098 - Account Manipulation
- T1136 - Create Account

## Repository Contents

- findings.txt
- timeline.txt
- iocs.txt
- recommendations.txt
- notes/raw_analysis.txt

## Conclusion

Available evidence supports unauthorized privileged access and persistence establishment on the affected host.