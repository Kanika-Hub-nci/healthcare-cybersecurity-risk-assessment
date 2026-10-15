# MediNova — Risk Appetite Breach Escalation and Management Decision Report

**Report Reference:** RAE-001  
**Related Finding:** GAP-001  
**Related KRI Report:** KRI-001  
**Related Monitoring Exception:** KRI-EXC-001  
**Control Area:** Employee Offboarding and Privileged Access Management  
**Framework:** ISO/IEC 27001:2022  
**Report Status:** Escalation Recommended — Management Decision Pending  
**Document Classification:** Educational Simulation

---

## 1. Executive Summary

This report documents a simulated escalation concerning a privileged administrator account that remained active after an employee's departure from MediNova.

The organisation's illustrative monitoring framework requires zero overdue privileged account deactivations.

One overdue privileged account has been identified, triggering a Red Key Risk Indicator (KRI).

Although overall employee offboarding compliance was reported as 99%, the privileged account exception requires separate investigation because of its potential security impact.

The issue requires formal risk assessment, escalation and an authorised management decision.

**Current Status:** Red KRI threshold breached; formal risk appetite determination and management decision pending.

No actual security incident, risk acceptance or management approval is represented.

## 2. Risk Description

**Risk ID:** RISK-IAM-001

**Risk Title:** Delayed Deactivation of Privileged Employee Account

**Risk Event:** A privileged administrator account remains enabled after the associated employee has departed.

**Potential Consequences:**

- Unauthorised administrative access.
- Exposure of sensitive systems and information.
- Modification or deletion of critical data.
- Disruption of healthcare operations.
- Potential regulatory, financial and reputational consequences.

The scenario does not establish that unauthorised access or data compromise occurred.

## 3. Relevant Security Controls

ISO/IEC 27001:2022 Annex A:

- A.5.16 — Identity Management.
- A.5.18 — Access Rights.
- A.8.2 — Privileged Access Rights.
- A.8.5 — Secure Authentication.

## 4. Risk Appetite and KRI Assessment

**Illustrative Risk Appetite:** Very low appetite for unauthorised access to sensitive healthcare information.

**KRI Threshold:** Zero overdue privileged account deactivations.

**Observed Result:** One overdue privileged account.

**KRI Status:** RED.

**Formal Risk Appetite Breach Status:** Pending assessment against approved organisational risk appetite criteria.

The KRI threshold and appetite statement are assumptions for this educational scenario. They are not evidence of actual management-approved policies.

## 5. Initial Risk Assessment

| Assessment Area | Current Position |
|---|---|
| Potential business impact | High, subject to validation |
| Likelihood | Not yet determined |
| Account privileges | Administrative access indicated; scope unverified |
| Duration of exposure | Not established |
| Post-departure account activity | Not established |
| Existing safeguards | Not yet verified |
| Inherent risk rating | Pending formal assessment |
| Residual risk rating | Pending formal assessment |

The available scenario does not support assigning a reliable numerical risk score.

## 6. Immediate Investigation and Escalation

Recommended actions:

1. Validate the employee's departure date and account status.
2. Determine the systems and permissions associated with the privileged account.
3. Confirm whether the account has been disabled.
4. Request relevant authentication and activity logs.
5. Assess whether post-departure activity occurred.
6. Refer suspected malicious or unauthorised activity to the Security Incident Response Team.
7. Notify the responsible control owner and risk owner.
8. Document findings, decisions and actions.

Where an active exposure is confirmed, authorised technical personnel should take appropriate containment action without waiting for a routine management meeting.

## 7. Risk Treatment Options

| Option | Possible Application | Considerations |
|---|---|---|
| Reduce | Disable unnecessary access and improve offboarding controls | Preferred approach for addressing the identified control weakness |
| Avoid | Eliminate unnecessary privileged access or retire the affected access arrangement | May not be practical for every business process |
| Share / Transfer | Use contractual or insurance arrangements for certain financial consequences | Does not eliminate the underlying access exposure or accountability |
| Accept | Formally retain a defined residual risk under an authorised process | Requires justification, approval and appropriate safeguards |

Risk acceptance must not be used to bypass mandatory legal, regulatory or organisational requirements.

## 8. Management Decision Required

The accountable risk owner should review:

- The validated risk assessment.
- The affected systems and privileges.
- Existing and proposed safeguards.
- The potential business consequences.
- Available treatment options.
- Proposed remediation deadlines.
- Any applicable legal or regulatory obligations.

**Requested Decision:** Approve an appropriate risk treatment plan or request further assessment.

**Management Decision Status:** Pending.

**Risk Acceptance Status:** Not Approved.

**Final Risk Owner:** To be confirmed.

## 9. Proposed Corrective Action Plan

| Corrective Action | Proposed Owner | Status |
|---|---|---|
| Validate and address the overdue privileged account | IAM / IT Operations | Proposed |
| Review privileged account activity | Security Operations | Proposed |
| Investigate HR–IT offboarding failure | HR and IT Operations | Proposed |
| Review privileged access removal controls | IAM Team | Proposed |
| Assess risk and required escalation | GRC / Risk Owner | Proposed |
| Perform follow-up effectiveness testing | GRC / Control Assurance | Proposed |

Owners and actions are illustrative. No implementation is claimed.

## 10. Interim Safeguards

Depending on the validated circumstances, appropriate interim safeguards may include:

- Prompt removal or suspension of unnecessary privileged access.
- Increased monitoring of relevant authentication and administrative activity.
- Review of other accounts associated with departed employees.
- Additional privileged access approval checks.
- More frequent reporting of unresolved exceptions.

The suitability and implementation of safeguards must be confirmed by authorised personnel.

## 11. Management Decision Register

| Field | Recorded Value |
|---|---|
| Decision reference | DEC-001 |
| Decision maker | Pending identification |
| Decision date | Not recorded |
| Risk treatment selected | Pending |
| Acceptance requested | Not formally submitted |
| Acceptance approved | No |
| Remediation deadline | To be agreed |
| Follow-up review | To be scheduled |
| Closure status | Open |

**Important:** Management awareness does not constitute formal risk acceptance.

## 12. Escalation and Monitoring Requirements

The GRC Analyst should:

1. Maintain the risk in the appropriate register.
2. Track the Red KRI exception.
3. Record the accountable risk owner.
4. Monitor investigation and corrective action progress.
5. Escalate missed deadlines or unresolved exposure.
6. Update management on the risk position.
7. Document the final authorised decision.
8. Request evidence before recommending closure.

## 13. Relationship to GAP-001

This exception relates to MediNova's employee offboarding control weakness.

If GAP-001 is awaiting closure approval, the new privileged account exception should be considered before a final decision.

If GAP-001 has already been formally closed, the organisation should assess whether to reopen it or record a new finding in accordance with its approved procedures.

The scenario does not establish that GAP-001 has been formally closed.

## 14. GRC Recommendation

Based on the simulated information, the recommended approach is to:

- Treat the Red KRI as requiring prompt investigation and escalation.
- Validate the account exposure and associated safeguards.
- Obtain a documented risk treatment decision from the authorised risk owner.
- Track corrective actions and verify their effectiveness.
- Maintain the finding and exception records until applicable closure criteria are satisfied.

**Final Recommendation:** Escalate for formal assessment and management decision.

**Current Status:** Open — Decision Pending.

## 15. Educational Disclaimer

MediNova is a fictional healthcare organisation used for cybersecurity GRC training.

All account information, risk thresholds, findings, proposed owners, decisions and recommendations are simulated.

This report does not represent an actual risk appetite breach determination, authorised risk acceptance, security investigation or ISO 27001 certification.
