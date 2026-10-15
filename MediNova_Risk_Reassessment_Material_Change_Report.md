# MediNova — Risk Reassessment After Material Change Report

**Report Reference:** RRM-001  
**Related Risk:** RISK-IAM-001  
**Related Finding:** GAP-001  
**Related Exception:** EXC-002  
**Control Area:** Identity and Access Management / Privileged Access  
**Framework:** ISO/IEC 27001:2022  
**Assessment Type:** Event-Driven Risk Reassessment  
**Report Status:** Reassessment Required — Management Decision Pending  
**Document Classification:** Educational Simulation

---

## 1. Executive Summary

This report documents a fictional event-driven cybersecurity risk reassessment for MediNova following a material change in an employee account's access privileges.

The original risk assessment concerned delayed deactivation of an employee account following departure.

During a subsequent review, the account was identified as having expanded administrative privileges and access to a sensitive patient database.

Additionally, the effectiveness of the required monitoring control could not be verified.

These changes may significantly increase the potential impact of unauthorised access and undermine assumptions supporting the earlier risk assessment and temporary risk acceptance.

**Assessment Outcome: MATERIAL CHANGE IDENTIFIED — FORMAL REASSESSMENT REQUIRED**

A revised risk rating and fresh authorised management decision are required after evidence has been collected and evaluated.

No actual security incident, data compromise or management approval is represented.

## 2. Background

**Risk Title:** Delayed Deactivation of Employee Account with Expanded Privileges

**Original Risk Event:** An employee account remains active beyond the permitted timeframe following departure.

**Material Change:** The account now has expanded administrative privileges and access to a sensitive patient database.

**Additional Concern:** The effectiveness of the required monitoring control has not been verified.

The previous assessment may no longer accurately represent the organisation's current risk exposure.

## 3. Material Change Identification

| Assessment Area | Original Assumption | Changed Circumstance | Risk Implication |
|---|---|---|---|
| Account privileges | Limited permissions | Expanded administrator privileges | Greater potential for privileged misuse |
| Data access | Sensitive patient data access not established | Patient database access identified | Increased confidentiality and regulatory exposure |
| Monitoring | Monitoring assumed operational | Effectiveness not verified | Reduced assurance about detection capability |
| Risk acceptance | Based on earlier circumstances | Material exposure change | Earlier approval may no longer be appropriate |
| Residual risk | Based on previous assessment | Requires reevaluation | Revised rating pending |

## 4. Relevant ISO/IEC 27001:2022 Controls

- A.5.16 — Identity Management.
- A.5.18 — Access Rights.
- A.8.2 — Privileged Access Rights.
- A.8.5 — Secure Authentication.
- A.8.15 — Logging.
- A.8.16 — Monitoring Activities.

These controls are relevant to the scenario. Their implementation or effectiveness has not been established by this report.

## 5. Risk Reassessment Objectives

The reassessment aims to:

1. Determine the scope of the expanded privileges.
2. Confirm the account's access to sensitive patient information.
3. Identify whether the account remains active.
4. Establish the duration of exposure.
5. Review relevant authentication and activity records.
6. Verify existing safeguards and their effectiveness.
7. Reassess likelihood and potential business impact.
8. Evaluate whether the revised risk is within approved appetite and tolerance limits.
9. Recommend appropriate risk treatment.
10. Obtain a fresh authorised management decision.

## 6. Evidence Requirements

| Evidence | Purpose | Status |
|---|---|---|
| Account permission history | Identify privilege changes | Pending |
| Role assignment records | Confirm administrative access | Pending |
| Database access permissions | Confirm sensitive data exposure | Pending |
| Authentication logs | Review account activity | Pending |
| Privileged activity logs | Assess administrative actions | Pending |
| Monitoring configuration | Understand intended safeguards | Pending |
| Monitoring test results | Verify control effectiveness | Not Available |
| Original risk assessment | Review earlier assumptions | Reference Required |
| Risk acceptance approval | Confirm scope and conditions | Reference Required |
| Employee departure record | Validate offboarding timeline | Pending |

No evidence is represented as reviewed or verified.

## 7. Risk Assessment

### 7.1 Potential Impact

The expanded permissions and patient database access could increase the potential consequences of unauthorised activity.

Possible impacts include:

- Exposure of confidential patient information.
- Unauthorised modification or deletion of records.
- Disruption of healthcare services.
- Regulatory or contractual consequences.
- Financial and reputational damage.

These are potential consequences, not confirmed outcomes.

### 7.2 Likelihood Assessment

Likelihood cannot be reliably determined without reviewing:

- Account status and access restrictions.
- Authentication and activity logs.
- Privileged access safeguards.
- Duration of exposure.
- Relevant threat information.
- Control effectiveness evidence.

**Likelihood Rating:** Pending.

### 7.3 Impact Assessment

The new database access indicates potentially greater impact than assumed in the original assessment.

**Impact Rating:** Pending formal evaluation using the organisation's approved methodology.

### 7.4 Residual Risk Assessment

**Residual Risk Rating:** Pending.

A numerical rating is not assigned without sufficient supporting evidence.

## 8. Risk Appetite and Acceptance Review

The original temporary acceptance was based on a defined scope and set of assumptions.

The expansion of privileges and uncertainty about monitoring effectiveness may invalidate those assumptions.

The GRC Analyst should determine:

- Whether the new exposure falls within the original acceptance scope.
- Whether the approved risk appetite and tolerance limits are exceeded.
- Whether required compensating controls are operating.
- Whether the acceptance conditions remain satisfied.
- Whether a new authorised decision is necessary.

**Previous Acceptance:** Not sufficient evidence of approval for the changed exposure.

**Fresh Management Decision:** Required.

The organisation should also assess whether immediate containment is necessary under its security procedures.

## 9. Recommended Risk Treatment

| Treatment | Recommended Consideration |
|---|---|
| Reduce | Remove unnecessary privileges, disable inappropriate access and improve offboarding controls |
| Avoid | Eliminate unnecessary access arrangements |
| Share / Transfer | Consider contractual or financial arrangements where applicable, without assuming the underlying exposure is eliminated |
| Accept | Consider only where permitted, justified, documented and authorised |

The preferred recommendation is to investigate and reduce unnecessary privileged access exposure.

Formal treatment selection remains subject to the accountable Risk Owner's decision.

## 10. Proposed Corrective Actions

| Action | Proposed Owner | Status |
|---|---|---|
| Validate account status and privileges | IAM Team | Pending |
| Review patient database permissions | Database Administration / IAM | Pending |
| Review authentication and activity logs | Security Operations | Pending |
| Verify monitoring controls | Security Operations | Pending |
| Reassess risk using approved methodology | GRC / Risk Owner | Pending |
| Determine need for incident escalation | Security Incident Response Team | Pending |
| Obtain new management decision | Risk Owner | Pending |
| Test corrective action effectiveness | Control Assurance | Not Started |

All owners and statuses are illustrative.

## 11. Management Escalation

**Escalation Reference:** ESC-003

**Reason for Escalation:** Material increase in privileged access exposure and unverified monitoring effectiveness.

**Escalation Recipient:** Accountable Risk Owner and relevant security management.

**Decision Requested:**

- Confirm the current risk exposure.
- Review the updated assessment.
- Approve an appropriate risk treatment.
- Determine required safeguards and deadlines.
- Confirm monitoring and review responsibilities.

**Decision Status:** Pending.

**Risk Acceptance Extension:** Not approved for the changed exposure.

## 12. Relationship to Existing GRC Records

This reassessment should be cross-referenced with:

- GAP-001 — Employee Offboarding Control Weakness.
- RISK-IAM-001 — Delayed Privileged Account Deactivation.
- EXC-002 — Temporary Risk Acceptance.
- KRI-001 — Key Risk Indicator Monitoring.
- RAE-001 — Risk Appetite Breach Escalation.
- RAR-001 — Risk Acceptance Expiry Review.

The relevant registers and reports should be updated consistently after new evidence and authorised decisions become available.

## 13. Follow-Up Monitoring

The GRC Analyst should monitor:

1. Completion of the technical investigation.
2. Confirmation of account deactivation or appropriate access restrictions.
3. Verification of monitoring controls.
4. Updated risk assessment results.
5. Risk Owner decisions.
6. Remediation deadlines.
7. Control effectiveness testing.
8. Evidence required for eventual closure.

The underlying risk should not be marked Closed merely because a reassessment has been performed.

## 14. GRC Recommendation

The material change requires a reassessment of the account's security exposure.

The GRC Analyst should recommend:

- Immediate validation of the account's permissions and status.
- Investigation of potential unauthorised access.
- Verification of monitoring safeguards.
- Reassessment using the approved risk methodology.
- Escalation of the changed risk exposure.
- A fresh authorised risk treatment decision.
- Continued tracking until appropriate resolution.

**Final Recommendation: REASSESS AND ESCALATE — MANAGEMENT DECISION REQUIRED.**

## 15. Educational Disclaimer

MediNova is a fictional healthcare organisation used for cybersecurity GRC training.

All account details, material changes, risk assessments, findings, exceptions, management decisions and proposed corrective actions are simulated.

This report does not represent a real security investigation, confirmed data breach, approved risk acceptance or ISO 27001 certification.
