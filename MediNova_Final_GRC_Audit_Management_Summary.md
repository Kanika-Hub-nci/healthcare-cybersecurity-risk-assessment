# MediNova — Cybersecurity GRC Final Audit and Management Summary

**Report Reference:** MED-GRC-FINAL-001  
**Organisation:** MediNova Healthcare (Fictional)  
**Frameworks:** ISO/IEC 27001:2022, ISO 27005, EU GDPR  
**Assessment Type:** Integrated GRC Portfolio and Management Summary  
**Document Status:** Final Educational Portfolio Summary  
**Classification:** Educational Simulation

---

## 1. Executive Summary

This report consolidates the fictional cybersecurity governance, risk management, compliance and assurance work developed for MediNova Healthcare.

The project demonstrates how a GRC function can identify information security weaknesses, document risks, recommend treatment actions, assess audit evidence, investigate security events, support privacy compliance and report unresolved exposures to management.

The original ISO 27001 gap assessment identified three principal areas requiring attention:

- **GAP-001:** A former employee account remained active after employment ended.
- **GAP-002:** Three of twenty administrator accounts were excluded from MFA enforcement.
- **GAP-003:** Backup restoration testing had not been performed.

Subsequent exercises examined risk treatment, management escalation, IAM operating effectiveness, incident response, GDPR breach communication and risk acceptance governance.

The most extensively developed scenario concerns GAP-001 and RISK-IAM-001.

Corrective action retesting produced an illustrative result of 11 passing samples out of 12, with one account disabled beyond the internal deadline.

A later simulated risk committee decision conditionally accepted the defined residual IAM risk for 30 days, subject to monitoring and escalation conditions.

**Overall Management Conclusion:** MediNova has developed a structured governance and assurance approach in the simulation, but material control weaknesses and evidence gaps remain. Conditional risk acceptance does not establish successful remediation or justify automatic audit finding closure.

## 2. Assessment Objectives

The project was designed to demonstrate the following GRC capabilities:

1. Information security gap assessment.
2. Cybersecurity risk identification and documentation.
3. ISO 27001 Annex A control mapping.
4. Risk treatment planning.
5. Audit evidence assessment.
6. Corrective action and exception tracking.
7. Control operating effectiveness testing.
8. Incident and breach governance.
9. GDPR notification and communication assessment.
10. Residual risk reassessment.
11. Risk acceptance governance.
12. Management reporting and escalation.

## 3. Assessment Scope and Limitations

The project covers selected aspects of identity and access management, privileged access, multifactor authentication, backup assurance, incident response, personal data breach governance and risk oversight.

It does not represent a comprehensive audit of all ISO 27001 requirements or controls.

All organisational information, findings, test populations, security events and management decisions are fictional.

No production systems were accessed, no real patient information was processed and no independent audit opinion is expressed.

## 4. Initial ISO 27001 Gap Assessment

| Finding | Identified Weakness | Principal Risk | Portfolio Status |
|---|---|---|---|
| GAP-001 | Former employee account remained active | Unauthorised access after departure | Open |
| GAP-002 | Three of twenty administrator accounts excluded from MFA | Increased exposure to credential-based attacks | Open in original assessment; no verified closure |
| GAP-003 | Backup restoration testing not performed | Inability to recover information after disruption | Open in original assessment; no verified closure |

### Relevant ISO 27001:2022 Controls

- A.5.16 — Identity Management.
- A.5.18 — Access Rights.
- A.8.2 — Privileged Access Rights.
- A.8.5 — Secure Authentication.
- A.8.13 — Information Backup.

These are relevant control references, not evidence of ISO 27001 certification.

## 5. Risk Management Approach

The MediNova portfolio includes risk registers, treatment planning, exception monitoring, risk escalation and management dashboard exercises.

The governance approach follows a risk lifecycle:

**Identify → Assess → Treat → Monitor → Reassess → Escalate → Obtain Authorised Decisions**

The project distinguishes between inherent risk, residual risk, treatment actions, acceptance requests and formally approved risk acceptance.

An important governance principle is that management awareness does not constitute risk acceptance.

Similarly, a risk acceptance request is not equivalent to an authorised approval.

## 6. IAM Control Assurance — GAP-001

### Initial Testing

The fictional employee offboarding control required account deactivation within 24 hours of the approved termination effective time.

The initial operating effectiveness test produced:

| Measure | Initial Test |
|---|---:|
| Samples tested | 10 |
| Passed | 8 |
| Failed | 2 |
| Sample pass rate | 80% |

Two accounts were disabled after 36 and 48 hours.

The control did not meet the stated requirement in all tested cases.

### Root Cause Assessment

The IAM manager suggested that workload caused the delays.

The GRC analysis correctly distinguished this explanation from a verified root cause.

Supporting evidence such as HR notifications, ticket histories and IAM logs would be required before determining the underlying cause.

### Corrective Action Retesting

A subsequent fictional retest produced:

| Measure | Retest |
|---|---:|
| Samples tested | 12 |
| Passed | 11 |
| Failed | 1 |
| Sample pass rate | 91.7% |

One account was disabled after 30 hours, exceeding the internal requirement by six hours.

The improved sample result does not establish organisation-wide control effectiveness.

### Management Assessment

The remaining exception requires investigation and appropriate assurance.

**GAP-001 Status: Open.**

## 7. Security Incident and GDPR Governance

The portfolio also contains a fictional security event, EVT-002, involving unauthorised access to patient records through an account associated with a former employee.

The scenario progressed through investigation, personal data breach assessment, phased notification, communication to affected individuals and post-incident governance.

### Breach Scenario Summary

| Item | Fictional Scenario Outcome |
|---|---|
| Security event | EVT-002 |
| Breach register | GDPR-BR-001 |
| Affected individuals | Approximately 180 |
| GDPR Article 33 | Notification and supplementary update addressed in scenario |
| GDPR Article 34 | Individual communication required under scenario assumptions |
| Initial notifications delivered | 165 |
| Initial delivery failures | 15 |
| Alternative contact completed | 10 |
| Remaining cases | 5 subject to documented privacy assessment |
| Communication workstream | Closure approved in scenario |
| Underlying IAM risk | Open |

The simulated closure decision concerned the Article 34 communication workstream.

It did not establish that every individual received or read the notification, that the underlying incident was fully closed or that the IAM control weakness was remediated.

### Governance Learning

Incident response, regulatory notification, communication workstream closure, corrective action closure and risk acceptance are distinct processes.

Each requires appropriate evidence and authorisation.

## 8. Residual Risk and Conditional Acceptance

The portfolio subsequently examined the remaining IAM risk.

The fictional risk committee conditionally approved temporary acceptance of RISK-IAM-001 for 30 days.

The approval included conditions requiring:

- Daily review of overdue deactivations.
- Weekly reporting of unresolved exceptions.
- Immediate escalation of privileged-account delays.
- Weekly corrective action progress tracking.
- Reassessment when material changes occur.
- Review before acceptance expiry.

The actual approval and expiry dates were not specified in the exercise.

The acceptance is therefore presented as a fictional governance scenario, not a real approval record.

### Key Governance Distinction

**Risk acceptance does not equal audit finding closure.**

The risk may be temporarily retained within an authorised scope while GAP-001 remains open and corrective action work continues.

## 9. Consolidated Management Dashboard

| Management Area | Current Portfolio Position | Required Attention |
|---|---|---|
| IAM offboarding | Retest exception remains | Investigate and validate remediation |
| Privileged-account MFA | Original GAP-002 unresolved | Verify enforcement and exceptions |
| Backup recoverability | Original GAP-003 unresolved | Perform documented restoration testing |
| GDPR communication | Simulated workstream closure approved | Preserve records and continuing obligations |
| IAM residual risk | Conditional acceptance in Lesson 46 scenario | Monitor conditions and review before expiry |
| Audit finding closure | GAP-001 remains open | Obtain sufficient assurance and authorised decision |
| Management reporting | Registers and dashboard exercises developed | Maintain evidence-based reporting |

This dashboard summarises the portfolio's fictional governance position; it is not a live organisational dashboard.

## 10. Priority Recommendations

### Priority 1 — IAM Offboarding Assurance

Investigate the remaining retest exception, verify the causes of delayed account deactivation and perform appropriate further assurance.

### Priority 2 — Privileged Access Security

Review MFA exclusions and validate whether privileged-account authentication requirements are operating effectively.

### Priority 3 — Backup Recovery Testing

Perform documented restoration tests and assess whether critical information can be recovered within the organisation's approved recovery requirements.

### Priority 4 — Risk Acceptance Monitoring

Ensure conditional approval requirements are tracked, breaches are escalated and acceptance is reviewed before expiry.

### Priority 5 — Evidence and Audit Governance

Maintain traceable links between risks, findings, control tests, exceptions, corrective actions, approvals and closure decisions.

## 11. Proposed Management Action Tracker

| Action | Proposed Owner | Status |
|---|---|---|
| Investigate remaining IAM retest failure | IAM Operations | Open |
| Verify GAP-001 corrective action effectiveness | Control Assurance | Pending |
| Review GAP-002 MFA exceptions | IAM / Security | Pending |
| Complete GAP-003 restoration testing | IT Operations | Pending |
| Monitor conditional IAM risk acceptance | Risk Owner | Required |
| Review acceptance before expiry | Risk Committee / Risk Owner | Required |
| Reassess finding closure readiness | GRC / Audit | Pending |

All owners and statuses are illustrative.

## 12. GRC Skills Demonstrated

The MediNova project demonstrates practical familiarity with:

**Governance**
- Security control ownership.
- Management reporting.
- Escalation and approval processes.
- Risk acceptance conditions.

**Risk Management**
- Risk identification and assessment.
- Treatment planning.
- Residual risk reassessment.
- Risk registers and monitoring.

**Compliance and Assurance**
- ISO 27001 control mapping.
- Audit gap assessment.
- Evidence requirements.
- Control testing and retesting.
- Exception and corrective action tracking.
- GDPR breach governance.

**Professional Documentation**
- Structured reports.
- Risk and action registers.
- Management dashboards.
- Audit finding closure assessments.
- Evidence-based recommendations.

These are demonstrated through simulated portfolio work rather than professional audit engagement experience.

## 13. Final Management Conclusion

The MediNova project illustrates an integrated cybersecurity GRC workflow, beginning with control gap identification and progressing through risk assessment, remediation, operating effectiveness testing, incident governance and management oversight.

The central lesson is that security governance depends on evidence and accountable decisions.

A policy does not prove implementation.

Implementation does not prove operating effectiveness.

Improved testing results do not automatically justify closure.

A risk acceptance request does not constitute approval.

An approved risk acceptance does not eliminate the need for monitoring or automatically resolve an audit finding.

**Final Management Position:** Continue remediation and assurance for unresolved findings, maintain oversight of the conditional IAM risk acceptance and ensure future closure decisions are supported by reliable evidence and appropriate authority.

## 14. Portfolio Conclusion

This educational project provides a structured example of how a cybersecurity GRC Analyst may support an organisation's information security management and assurance activities.

It brings together risk management, ISO 27001 controls, IAM, audit findings, GDPR breach governance and executive reporting within one fictional healthcare scenario.

The project is suitable for demonstrating foundational GRC analysis and documentation skills during cybersecurity graduate, junior GRC, IT risk and compliance interviews.

## 15. References

- ISO/IEC 27001:2022 — Information security management systems — Requirements.
- ISO/IEC 27002:2022 — Information security controls.
- ISO/IEC 27005:2022 — Information security risk management.
- ISO 31000:2018 — Risk management — Guidelines.
- Regulation (EU) 2016/679 — General Data Protection Regulation.

## 16. Educational Disclaimer

MediNova is a fictional healthcare organisation.

All scenarios, control testing results, risks, security incidents, GDPR communications, management decisions and approvals are simulated.

The portfolio does not represent a real audit engagement, production security assessment, ISO 27001 certification or verified GDPR compliance.
