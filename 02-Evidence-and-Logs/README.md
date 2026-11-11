# Evidence and Logs

This directory contains sanitized security logs, alert records, screenshots, and supporting evidence collected during hands-on investigations in the Sentinel Ridge SOC Academy.

## Purpose

The purpose of this directory is to demonstrate how SOC analysts collect, analyze, correlate, and document security evidence while maintaining evidence integrity and protecting sensitive information.

## Types of Evidence

- Wazuh SIEM alerts and event records
- Linux authentication and system logs
- Windows Security Event Logs (planned)
- Network connection and traffic analysis
- Process and endpoint activity
- File integrity monitoring events
- Investigation timelines
- Sanitized screenshots and log excerpts

## Evidence Collection and Documentation

For each investigation, evidence documentation should include:

1. Investigation or case ID
2. Evidence identifier
3. Source system and log location
4. Collection date and time, including time zone
5. Collection method or command
6. Original filename and SHA-256 hash, where applicable
7. Evidence description and relevance to the investigation
8. Sanitization performed before publication

## Evidence Handling Guidelines

- Preserve original evidence separately in protected local storage.
- Work from copies when analyzing or preparing evidence for publication.
- Record timestamps and time zones accurately.
- Use SHA-256 hashes to help verify file integrity.
- Maintain a record of evidence collection and handling.
- Clearly distinguish observed facts from analyst interpretations.
- Never modify original evidence to make an investigation appear more suspicious.

## Privacy and Security

Only synthetic or appropriately sanitized training evidence will be published.

Do not upload passwords, authentication tokens, private keys, recovery codes, personal information, confidential employer records, or other sensitive material.

## Planned Evidence

**SOC-LAB-001 — SSH Authentication Investigation**

Evidence will be added after the investigation is completed, reviewed, and sanitized.

## Project Status

Active — Evidence collection and forensic documentation procedures are being developed through hands-on SOC training.
