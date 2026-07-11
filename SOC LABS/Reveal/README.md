# Reveal – Memory Forensics Investigation

## Overview

This investigation analyzes a Windows memory dump acquired from a compromised system to identify evidence of malicious activity. The analysis focuses on process execution, command-line artifacts, network connections, and in-memory evidence using Volatility 3.

The investigation revealed a hidden PowerShell process that executed built-in Windows utilities (LOLBins) to establish a remote WebDAV connection and attempt the execution of a DLL hosted on a remote server.

## Objectives

* Identify the malicious process chain.
* Analyze suspicious command-line activity.
* Correlate process execution with active network connections.
* Collect Indicators of Compromise (IOCs).
* Map the observed attacker behavior to the MITRE ATT&CK framework.

## Tools Used

* Volatility 3
* Windows Memory Dump
* Command Prompt
* MITRE ATT&CK Framework

## Repository Structure

* Findings
* Timeline
* IOCs
* Memory Analysis
* Network Analysis
* MITRE Mapping
