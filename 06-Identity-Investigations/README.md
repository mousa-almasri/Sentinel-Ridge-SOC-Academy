# Identity Investigations

This directory documents hands-on identity security investigations conducted as part of the Sentinel Ridge SOC Academy.

## Purpose

The goal is to develop practical SOC Tier 1 and Tier 2 skills for investigating suspicious authentication activity, compromised accounts, privilege changes, and identity-related security alerts.

Training will focus on analyzing identity security evidence rather than performing routine identity administration.

## Learning Objectives

- Investigate successful and failed authentication attempts.
- Identify suspicious account activity and possible credential attacks.
- Analyze account lockouts and repeated login failures.
- Investigate unexpected privilege and group membership changes.
- Correlate identity alerts with endpoint and network activity.
- Understand multifactor authentication (MFA) security events.
- Recognize potential account compromise and lateral movement.
- Map relevant activity to MITRE ATT&CK techniques.
- Document evidence, findings, confidence levels, and escalation recommendations.

## Identity Security Technologies

### Linux Identity and Authentication

- SSH authentication logs
- PAM authentication events
- sudo and privileged account activity
- Local user and group changes
- Wazuh authentication alerts

### Windows Active Directory (Planned)

- Domain authentication events
- Windows Security Event Logs
- Kerberos and NTLM authentication
- Account lockouts
- Privileged group membership changes
- Domain account creation and modification

### Microsoft Entra ID (Planned)

- Cloud identity sign-in logs
- Failed and suspicious sign-in attempts
- MFA authentication events
- Conditional Access results
- Privileged role assignments
- Identity-related security alerts

## Planned Investigation Exercises

### ID-001 — Linux SSH Authentication Investigation

Analyze failed and successful SSH authentication events and correlate relevant Wazuh alerts.

### ID-002 — Windows Account Lockout Investigation

Investigate repeated authentication failures and account lockout events using Windows Security logs.

### ID-003 — Suspicious Privileged Account Activity

Investigate unexpected sudo usage, privileged group changes, and potentially unauthorized administrative activity.

### ID-004 — Microsoft Entra ID Suspicious Sign-In

Analyze cloud identity sign-in activity, source information, authentication outcomes, and MFA-related events.

### ID-005 — Potential Account Compromise

Correlate authentication, endpoint, and network evidence to evaluate possible account compromise.

## Standard Identity Investigation Workflow

1. Identify the authentication alert or suspicious identity activity.
2. Determine the affected account, system, and relevant time window.
3. Review authentication results, timestamps, and source information.
4. Correlate related login attempts and account activity.
5. Examine relevant endpoint, network, and identity logs.
6. Identify indicators that support or contradict account compromise.
7. Assess severity, confidence, and potential impact.
8. Preserve relevant evidence and document the investigation timeline.
9. Escalate according to established incident response procedures.
10. Recommend appropriate response actions within authorized responsibilities.

## Evidence and Documentation

Completed investigations should include:

- Investigation ID and title
- Alert source and detection details
- Affected accounts and systems
- Relevant authentication and security logs
- Event timestamps and time zones
- Supporting and contradictory evidence
- MITRE ATT&CK mapping, where applicable
- Investigation findings and confidence level
- Escalation decisions and response recommendations
- Evidence handling and sanitization notes

## AI-Assisted Identity Investigations

AI tools may assist with summarizing authentication logs, identifying unusual patterns, generating investigative hypotheses, and drafting incident reports.

All AI-generated conclusions must be independently verified against original evidence.

Sensitive identity information, credentials, authentication tokens, and confidential logs must not be submitted to unapproved AI services.

## Security and Privacy

All exercises will be conducted in an authorized training environment using fictional accounts or appropriately sanitized data.

Passwords, authentication tokens, private keys, personal information, and confidential employer data will not be published.

## Project Status

Active — Linux authentication investigations are underway. Windows Active Directory and Microsoft Entra ID investigation exercises are planned for future training.
