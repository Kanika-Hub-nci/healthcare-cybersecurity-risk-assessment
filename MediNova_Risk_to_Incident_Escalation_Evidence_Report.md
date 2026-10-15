# MediNova — Risk-to-Incident Escalation and Evidence Handling Report

**Report Reference:** RIE-001  
**Related Risk:** RISK-IAM-001  
**Related Finding:** GAP-001  
**Related Reassessment:** RRM-001  
**Scenario Event Reference:** EVT-002  
**Control Area:** Identity and Access Management / Security Monitoring  
**Framework:** ISO/IEC 27001:2022  
**Assessment Type:** Suspected Security Incident Escalation  
**Report Status:** Escalation Recommended — Investigation Pending  
**Document Classification:** Educational Simulation

---

## 1. Executive Summary

This report documents a fictional security event involving database access from a former employee's administrator account at MediNova.

The event was identified during follow-up activities associated with an existing employee offboarding risk and a material change in account privileges.

A screenshot indicating successful database access was made available to the GRC Analyst.

However, the original logs have not yet been preserved, and the available information does not establish whether the activity was authorised or whether patient information was compromised.

The event therefore requires prompt escalation to the Security Incident Response Team for investigation and evidence preservation.

**Current Classification:** Suspicious Security Event — Incident Determination Pending.

**Recommended Action:** Escalate, preserve evidence and investigate.

No confirmed unauthorised access or personal data breach is asserted.

## 2. Background

**Existing Risk:** Delayed deactivation of an employee account following departure.

**Related Finding:** GAP-001 — Employee Offboarding Control Weakness.

**Material Change:** Expanded administrator privileges and access to a sensitive patient database.

**Observed Event:** Successful database connection associated with the former employee's administrator account.

**Evidence Available:** Screenshot of a log entry.

**Evidence Limitation:** Original log records have not yet been secured or independently validated.

The event may indicate increased security exposure and requires further investigation.

## 3. Event Description

| Field | Simulated Detail |
|---|---|
| Event Reference | EVT-002 |
| Account | admin_user_017 |
| Event Time | 12 October 2026, 14:32:10 UTC |
| Resource | Patient_Records_DB |
| Event Type | Database Connection |
| Result | Successful |
| Source IP | 10.0.2.15 |
| Evidence | Screenshot of access log |
| Authorisation | Not established |
| Data Accessed | Not established |
| Incident Status | Under assessment |

All identifiers and event details are fictional.

A successful connection does not establish that the named former employee personally initiated the activity or that patient records were viewed or extracted.

## 4. Risk-to-Incident Escalation Assessment

### 4.1 Existing Risk

The previously identified risk concerns failure to remove access promptly after an employee's departure.

### 4.2 Security Event

A successful database connection associated with the account has been observed.

### 4.3 Potential Incident

The event requires investigation because the account is associated with a former employee and has privileged access to a sensitive resource.

### 4.4 Confirmed Incident

A confirmed security incident classification requires evaluation against the organisation's incident criteria and supporting evidence.

### 4.5 Personal Data Breach

A personal data breach determination requires evidence and assessment of whether a breach of security resulted in accidental or unlawful destruction, loss, alteration, unauthorised disclosure of, or access to personal data.

**Current Determination:** Not established.

## 5. Relevant ISO/IEC 27001:2022 Controls

- A.5.16 — Identity Management.
- A.5.18 — Access Rights.
- A.5.24 — Information Security Incident Management Planning and Preparation.
- A.5.25 — Assessment and Decision on Information Security Events.
- A.5.26 — Response to Information Security Incidents.
- A.5.28 — Collection of Evidence.
- A.8.15 — Logging.
- A.8.16 — Monitoring Activities.

These controls are relevant to the scenario. This report does not verify their implementation or effectiveness.

## 6. Immediate Escalation Requirements

The GRC Analyst should:

1. Record the observed event and its source.
2. Notify the Security Incident Response Team promptly.
3. Provide the event reference, account identifier, timestamp and affected resource.
4. Identify the existing risk and control finding associated with the event.
5. Request preservation of original logs through authorised personnel.
6. Document known facts separately from assumptions.
7. Support risk assessment updates as the investigation progresses.

Where there is a credible ongoing exposure, authorised responders should evaluate immediate containment measures.

The GRC Analyst should not independently alter production systems or collect evidence outside their authorised role.

## 7. Evidence Inventory

| Evidence ID | Evidence Description | Status | Purpose |
|---|---|---|---|
| EVD-001 | Screenshot of database access log | Reported Available | Initial event identification |
| EVD-002 | Original database connection logs | Preservation Pending | Validate the observed connection |
| EVD-003 | Identity provider authentication logs | Pending | Examine account authentication |
| EVD-004 | Privileged access records | Pending | Confirm permissions |
| EVD-005 | Employee departure record | Pending | Validate offboarding timeline |
| EVD-006 | Account disablement records | Pending | Establish account lifecycle |
| EVD-007 | Database audit logs | Pending | Determine actions performed |
| EVD-008 | Monitoring configuration and test evidence | Pending | Assess detection controls |

No original log or supporting evidence is represented as collected or verified.

## 8. Evidence Preservation and Integrity

Evidence handling should follow the organisation's approved incident response and forensic procedures.

Recommended requirements include:

- Preserve relevant original logs and associated metadata.
- Record the evidence source and collection method.
- Record collection timestamps and time zones.
- Identify the authorised collector.
- Restrict access to authorised personnel.
- Use appropriate integrity verification where applicable.
- Maintain an auditable record of evidence transfers.
- Store evidence in an approved location.
- Retain evidence according to applicable policies and legal requirements.

Evidence preservation should be coordinated with authorised Security Operations and forensic personnel.

## 9. Evidence Chain-of-Custody Record

| Field | Required Information |
|---|---|
| Evidence Reference | Unique evidence identifier |
| Description | Evidence type and contents |
| Original Source | System or person providing evidence |
| Collection Date and Time | Timestamp and time zone |
| Collected By | Authorised individual |
| Collection Method | Approved method used |
| Integrity Verification | Hash or other suitable method, where applicable |
| Storage Location | Approved restricted repository |
| Access or Transfer History | Individuals, timestamps and purposes |
| Retention Requirements | Applicable policy or legal requirements |

**Current Chain-of-Custody Status:** Not established.

The screenshot alone does not provide a complete evidentiary history.

## 10. Investigation Questions

The Security Incident Response Team should determine:

1. Was the database connection genuinely associated with the account?
2. Was the account active after the employee's departure?
3. Who or what initiated the connection?
4. Was the connection authorised?
5. Were patient records queried, viewed, modified or exported?
6. Were other systems accessed?
7. Was any suspicious administrative activity recorded?
8. Were monitoring and access controls functioning as intended?
9. Is the activity part of a wider security incident?
10. Are containment, recovery or notification actions required?

## 11. GRC Responsibilities

The GRC Analyst supports the incident response process by:

- Maintaining links to relevant risks and control findings.
- Documenting escalation and accountability.
- Tracking corrective actions.
- Monitoring control weaknesses identified during investigation.
- Supporting evidence requests and audit readiness.
- Reporting risk changes to appropriate stakeholders.
- Ensuring management decisions are recorded.

The GRC Analyst should not replace the technical incident investigation or make unsupported forensic conclusions.

## 12. GDPR and Regulatory Considerations

If the investigation identifies a personal data breach, MediNova's appropriate privacy and legal personnel should assess notification requirements under the GDPR.

Where Article 33 applies, notification to the competent supervisory authority is generally required without undue delay and, where feasible, within 72 hours after becoming aware of a personal data breach, unless the breach is unlikely to result in a risk to individuals' rights and freedoms.

The organisation should also assess whether communication to affected individuals is required under Article 34.

A suspicious log entry alone does not automatically establish that a reportable personal data breach has occurred.

No regulatory notification determination has been made in this scenario.

## 13. Escalation and Decision Register

| Field | Simulated Status |
|---|---|
| Event Reference | EVT-002 |
| Escalation Reference | ESC-004 |
| Incident Response Team Notification | Recommended — Not Confirmed |
| Evidence Preservation | Pending |
| Incident Classification | Pending |
| Personal Data Breach Determination | Pending |
| Risk Reassessment | Required |
| Management Notification | Pending |
| Corrective Actions | To Be Determined |
| Final Closure | Not Authorised |

## 14. Relationship to Existing MediNova Records

The event should be cross-referenced with:

- GAP-001 — Employee Offboarding Control Weakness.
- RISK-IAM-001 — Delayed Privileged Account Deactivation.
- EXC-002 — Temporary Risk Acceptance.
- RRM-001 — Risk Reassessment After Material Change.
- KRI-001 — Key Risk Indicator Monitoring.
- RAE-001 — Risk Appetite Breach Escalation.

The new event should be tracked separately from any earlier fictional incident exercise, including INC-001, unless an authorised investigation establishes a relationship.

## 15. Recommended Follow-Up Actions

| Action | Proposed Owner | Status |
|---|---|---|
| Escalate the suspicious event | GRC / Security Operations | Recommended |
| Preserve original database logs | Security Operations | Pending |
| Review account authentication | Incident Response Team | Pending |
| Determine activity authorisation | Incident Response Team | Pending |
| Assess possible patient data impact | Incident Response / Privacy Team | Pending |
| Review control effectiveness | IAM / Security Operations | Pending |
| Update risk and finding records | GRC | Pending |
| Determine corrective actions | Relevant Control Owners | Pending |
| Record final incident decision | Authorised Incident Manager | Pending |

All responsibilities and statuses are illustrative.

## 16. Final GRC Recommendation

Based on the simulated event, the GRC Analyst should recommend:

1. Prompt escalation to authorised incident responders.
2. Preservation of original logs and relevant supporting evidence.
3. Documentation of evidence provenance and handling.
4. Investigation of account activity and potential patient data exposure.
5. Reassessment of the associated cybersecurity risk.
6. Tracking of any identified control failures and corrective actions.
7. Recording of the authorised incident classification and management decisions.

**Final Status: SUSPICIOUS SECURITY EVENT — INVESTIGATION REQUIRED.**

No confirmed security incident or personal data breach conclusion is made.

## 17. Educational Disclaimer

MediNova is a fictional healthcare organisation used for cybersecurity GRC training.

All event details, accounts, timestamps, evidence records, risk assessments, findings and recommendations are simulated.

This report does not represent an actual security investigation, confirmed data breach, regulatory notification or ISO 27001 certification.
