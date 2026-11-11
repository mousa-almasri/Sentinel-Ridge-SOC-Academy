# Incident Response Playbooks

This directory contains practical Security Operations Center (SOC) incident response playbooks developed as part of the Sentinel Ridge SOC Academy.

## Purpose

These playbooks provide structured procedures for investigating security alerts, assessing potential threats, preserving evidence, escalating incidents, and recommending appropriate response actions.

The goal is to develop repeatable investigative workflows that can be applied across different SIEM, EDR, and security monitoring platforms.

## SOC Analyst Responsibilities

### Tier 1 — Initial Triage

- Review incoming security alerts and identify affected systems.
- Validate alert details against available log evidence.
- Determine whether activity appears suspicious, benign, or inconclusive.
- Correlate related events and establish an initial timeline.
- Assess alert priority and potential business impact.
- Document findings and escalate incidents when appropriate.

### Tier 2 — Advanced Investigation

- Conduct deeper endpoint, network, and identity investigations.
- Correlate evidence from multiple security data sources.
- Investigate potential persistence, lateral movement, and privilege escalation.
- Develop and test investigative hypotheses.
- Identify detection gaps and recommend improvements.
- Coordinate containment and remediation through authorized incident response procedures.

## Standard Incident Response Workflow

1. **Detection:** Identify and review the security alert.
2. **Validation:** Determine whether the alert represents suspicious activity.
3. **Triage:** Identify affected assets, accounts, and potential impact.
4. **Investigation:** Correlate logs, endpoint telemetry, and network evidence.
5. **Evidence preservation:** Record relevant artifacts, timestamps, and collection methods.
6. **Classification:** Assess confidence, severity, and incident status.
7. **Escalation:** Notify the appropriate response team when escalation criteria are met.
8. **Containment and remediation:** Recommend or perform only explicitly authorized actions.
9. **Recovery and monitoring:** Verify recovery and monitor for recurring suspicious activity.
10. **Documentation:** Record findings, decisions, and lessons learned.

## Planned Playbooks

### IR-001 — Suspicious SSH Authentication Activity

Investigate repeated failed SSH authentication attempts, identify affected accounts and source systems, and determine whether escalation is necessary.

### IR-002 — Suspicious Privileged Account Activity

Investigate unexpected sudo usage, privileged authentication events, and possible unauthorized administrative access.

### IR-003 — Potential Endpoint Compromise

Investigate suspicious processes, network connections, file modifications, and related endpoint alerts.

### IR-004 — Phishing Email Investigation

Review suspicious email indicators, authentication results, URLs, domains, and supporting threat intelligence.

### IR-005 — Identity Security Incident

Investigate suspicious Windows Active Directory or Microsoft Entra ID authentication activity, including failed logins, account lockouts, and unusual privilege changes.

## Playbook Documentation Standards

Each completed playbook should include:

- Playbook identifier and title
- Security scenario and detection triggers
- Required tools and log sources
- Initial triage questions
- Investigation steps and commands
- Evidence collection procedures
- MITRE ATT&CK mapping, where applicable
- Severity and escalation criteria
- Authorized response recommendations
- Reporting requirements
- Validation steps and limitations

## AI-Assisted SOC Investigations

AI tools may support log summarization, hypothesis generation, evidence correlation, and incident report drafting.

AI-generated findings must be independently verified against original security evidence.

Sensitive credentials, confidential information, and private investigation data must not be submitted to unapproved AI services.

AI tools must not independently authorize containment or remediation actions.

## Safety and Authorization

All exercises are performed within an authorized training environment.

Playbooks are educational examples and must be adapted to organizational policies, incident response procedures, and approval requirements before use in production environments.

## Project Status

Active — Incident response playbooks will be developed, tested, and refined through hands-on SOC Tier 1 and Tier 2 investigations.
