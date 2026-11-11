# Linux and Windows Forensics

This directory documents hands-on Linux and Windows forensic investigation exercises conducted as part of the Sentinel Ridge SOC Academy.

## Purpose

The goal is to develop practical forensic triage and evidence analysis skills that support Security Operations Center (SOC) investigations and provide a foundation for Digital Forensics and Incident Response (DFIR).

Exercises focus on identifying suspicious activity, reconstructing event timelines, preserving evidence, and documenting defensible findings.

## Learning Objectives

- Investigate Linux and Windows security events.
- Analyze authentication activity and suspicious login attempts.
- Examine running processes, services, and network connections.
- Identify suspicious file modifications and persistence mechanisms.
- Correlate endpoint evidence with Wazuh SIEM alerts.
- Collect and preserve forensic evidence.
- Generate SHA-256 hashes to verify file integrity.
- Reconstruct incident timelines using multiple log sources.
- Distinguish confirmed evidence from investigative hypotheses.
- Produce clear forensic investigation reports.

## Linux Forensic Investigations

Planned exercises include:

### LF-001 — SSH Authentication Forensics

Investigate failed and successful SSH authentication events using Linux system logs, journalctl, and Wazuh alerts.

### LF-002 — Suspicious Process Investigation

Examine process information, parent-child relationships, running services, and suspicious command execution.

### LF-003 — Network Connection Investigation

Analyze active network connections, listening ports, and processes associated with network activity.

### LF-004 — File Integrity and Timeline Analysis

Investigate file modifications, timestamps, and file integrity monitoring events.

### LF-005 — Linux Persistence Investigation

Examine scheduled tasks, systemd services, and other potential persistence mechanisms.

## Windows Forensic Investigations

The following exercises are planned for future training:

### WF-001 — Windows Authentication Investigation

Analyze Windows Security Event Logs, including successful and failed logins.

### WF-002 — Suspicious Process Execution

Investigate process creation events, command-line activity, and related endpoint telemetry.

### WF-003 — Windows Persistence Investigation

Examine scheduled tasks, services, and startup-related artifacts.

### WF-004 — PowerShell Activity Investigation

Review PowerShell logging and suspicious command execution.

### WF-005 — Windows Account and Privilege Changes

Investigate account creation, group membership changes, and privileged activity.

## Forensic Evidence Collection

Evidence documentation should include:

1. Investigation and evidence identifiers
2. Source system and artifact location
3. Collection date, time, and time zone
4. Collection command or tool
5. Original evidence filename and SHA-256 hash, where applicable
6. Evidence handling and analysis procedures
7. Observed findings and limitations
8. Sanitization performed before publication

## Investigation Tools

- Wazuh SIEM
- Linux journalctl and system logs
- Linux process and network inspection utilities
- SHA-256 hashing tools
- Windows Event Viewer (planned)
- Windows Sysmon (planned)
- PowerShell investigation tools (planned)
- MITRE ATT&CK framework
- AI-assisted analysis with independent evidence verification

## Forensic Investigation Workflow

1. Identify the alert or suspicious activity.
2. Determine the affected system and relevant time window.
3. Preserve available evidence before making unnecessary changes.
4. Collect relevant logs and endpoint artifacts.
5. Record evidence sources, timestamps, and hashes.
6. Correlate events to reconstruct a timeline.
7. Evaluate competing explanations and investigative limitations.
8. Document findings, confidence levels, and recommended next steps.

## Evidence Integrity and Safety

All exercises are performed in an authorized training environment.

Original evidence should be preserved separately from working copies. Hashes help detect changes to collected files but do not independently establish the authenticity of their contents.

Only synthetic or appropriately sanitized evidence will be published. Credentials, private keys, sensitive personal information, and confidential employer data must never be uploaded.

## Project Status

Active — Linux forensic triage is being integrated into Wazuh SOC investigations. Windows forensic exercises are
