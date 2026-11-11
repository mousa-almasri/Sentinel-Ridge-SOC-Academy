# Wazuh Detection Rules

This directory documents custom Wazuh detection rules, testing procedures, alert validation, and detection tuning exercises developed during the Sentinel Ridge SOC Academy.

## Purpose

The goal of this directory is to demonstrate practical security detection engineering skills through controlled, hands-on laboratory exercises.

Detection engineering involves identifying suspicious behavior, developing rules to detect that behavior, validating alerts, and improving detection accuracy.

## Learning Objectives

- Understand how Wazuh processes security events and generates alerts.
- Examine built-in Wazuh rules and rule identifiers.
- Develop and test custom detection rules.
- Identify false positives and false negatives.
- Correlate authentication, endpoint, and network events.
- Map detections to relevant MITRE ATT&CK techniques.
- Evaluate alert severity and investigation priority.
- Document detection logic, testing results, and limitations.

## Detection Rule Development Workflow

1. Identify the suspicious behavior or security activity to detect.
2. Collect representative log samples from the authorized lab environment.
3. Examine relevant Wazuh decoders and existing detection rules.
4. Develop or modify detection logic.
5. Test the rule using appropriate Wazuh testing tools.
6. Generate controlled events to validate alert behavior.
7. Review false positives, false negatives, and detection limitations.
8. Document the results and publish validated rules.

## Tools and Technologies

- Wazuh SIEM and detection engine
- Wazuh XML rule configuration
- Wazuh log testing utilities
- Linux authentication and system logs
- Windows Event Logs (planned)
- MITRE ATT&CK framework
- Endpoint and network telemetry

## Planned Detection Exercises

### DET-001 — SSH Authentication Failure Detection

Investigate Wazuh's built-in SSH authentication rules and develop a controlled detection exercise involving repeated failed login attempts.

### DET-002 — Suspicious Privilege Escalation

Examine Linux sudo and privilege-related events to identify potentially suspicious administrative activity.

### DET-003 — File Integrity Monitoring

Generate controlled file modifications and investigate Wazuh file integrity monitoring alerts.

Additional exercises will be introduced as training progresses.

## Rule Documentation Standards

Each completed detection exercise should include:

- Detection ID and title
- Security objective and threat scenario
- Required log sources
- Wazuh rule ID and detection logic
- Relevant MITRE ATT&CK techniques
- Testing commands and procedures
- Expected and observed results
- False-positive considerations
- Detection limitations
- Tuning recommendations

## Safety and Publication Guidelines

All testing will occur in an authorized, isolated training environment.

Only validated detection rules and appropriately sanitized supporting evidence will be published.

Sensitive credentials, confidential employer data, private keys, and production security configurations will not be included.

## Project Status

Active — Detection engineering exercises are planned and will be documented as hands-on training progresses.
