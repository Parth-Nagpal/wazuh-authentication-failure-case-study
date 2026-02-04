# Wazuh SIEM – SSH Authentication Failure Case Study

## Overview
This project documents a hands-on SIEM case study using Wazuh to detect and analyze SSH authentication failures in an all-in-one lab environment.

## Objectives
- Understand host-based log ingestion in a SIEM
- Analyze SSH authentication failure behavior
- Correlate alerts with MITRE ATT&CK techniques
- Practice SOC-style alert analysis and documentation

## Lab Environment
- OS: Ubuntu (Wazuh all-in-one deployment)
- Components: Wazuh Manager, Indexer, Dashboard
- Log Source: /var/log/auth.log
- Access Method: SSH

## Attack Simulation
Repeated failed SSH login attempts were generated using a non-existent user to simulate password guessing behavior.

## Key Findings
- Wazuh successfully detected SSH authentication failures
- Alerts were time-correlated and classified correctly
- Events mapped to MITRE ATT&CK techniques T1110 and T1110.001
- Alerts were appropriately classified as medium severity

## Documentation
📄 Full case study available here:
- `Wazuh_SIEM_SSH_Authentication_Failure_Case_Study.pdf`

## Disclaimer
This project was conducted in an isolated lab environment for educational purposes only.

