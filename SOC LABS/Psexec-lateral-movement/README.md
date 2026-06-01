# PsExec - CyberDefenders

## Scenario

Investigation of network traffic associated with suspected lateral movement activity.

## Objective

Identify the source host, determine whether PsExec was used, and assess evidence of remote service execution.

## Evidence Sources

- Packet capture (.pcapng)
- SMB traffic
- DCERPC traffic
- Service Control Manager activity

## Key Findings

- SMB access to IPC$ and ADMIN$ shares observed.
- PSEXESVC.EXE deployment identified.
- Service creation requests detected through SVCCTL.
- Activity consistent with PsExec-based lateral movement.

## Severity

High

## MITRE ATT&CK

- T1021.002 - SMB/Windows Admin Shares
- T1569.002 - Service Execution
- T1570 - Lateral Tool Transfer

## Repository Contents

- findings.txt
- timeline.txt
- iocs.txt
- recommendations.txt
- notes/raw_analysis.txt

## Conclusion

Evidence strongly supports PsExec-mediated remote service deployment and lateral movement between hosts.