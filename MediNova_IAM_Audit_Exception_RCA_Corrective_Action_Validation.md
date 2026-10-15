# MediNova — Audit Exception Root Cause Analysis and Corrective Action Validation Report

**Report Reference:** IAM-RCA-002  
**Related Finding:** GAP-001  
**Related Operating Effectiveness Test:** IAM-OET-001  
**Related Risk:** RISK-IAM-001  
**Related Security Event:** EVT-002  
**Framework:** ISO/IEC 27001:2022  
**Assessment Status:** Root Cause Investigation and Corrective Action Validation Pending  
**Classification:** Educational Simulation

---

## 1. Executive Summary

This report examines two fictional employee offboarding control failures identified during MediNova's IAM operating effectiveness testing.

The control requires employee accounts to be disabled within 24 hours of the approved termination effective time.

Of ten illustrative departures tested, eight met the requirement and two failed.

The failed cases were:

- EMP-009: Account disabled after 36 hours.
- EMP-010: Account disabled after 48 hours.

The IAM manager attributed the delays to a busy workload.

However, no supporting evidence has yet established that workload was the root cause.

The GRC assessment therefore recommends a structured root cause investigation, evidence-based corrective action planning and follow-up validation.

**Overall Recommendation:** Keep GAP-001 open pending root cause verification, corrective action implementation and operating effectiveness retesting.

## 2. Assessment Objectives

The objectives are to:

1. Document the control failures accurately.
2. Identify and verify their root causes.
3. Distinguish symptoms from underlying process weaknesses.
4. Develop proportionate corrective actions.
5. Establish validation criteria.
6. Determine whether evidence supports closure of GAP-001.

## 3. Control Background

**Control Objective:** Ensure employee access is removed promptly following departure.

**Internal Requirement:** Accounts must be disabled within 24 hours of the approved termination effective time.

**Control Owner:** IAM / IT Operations.

**Related ISO/IEC 27001:2022 Controls:**

- A.5.16 — Identity Management.
- A.5.18 — Access Rights.
- A.8.2 — Privileged Access Rights.

The 24-hour requirement is a fictional MediNova policy requirement rather than a universal ISO 27001 or GDPR deadline.

## 4. Original Testing Results

| Metric | Fictional Result |
|---|---:|
| Departure population | 40 |
| Samples tested | 10 |
| Passing samples | 8 |
| Failed samples | 2 |
| Sample pass rate | 80% |
| Sample exception rate | 20% |

The sample results do not establish the failure rate across the entire population.

## 5. Exception Register

| Exception ID | Sample | Observed Time | Requirement | Outcome |
|---|---|---:|---:|---|
| IAM-EXC-001 | EMP-009 | 36 hours | 24 hours | Fail |
| IAM-EXC-002 | EMP-010 | 48 hours | 24 hours | Fail |

### Exception IAM-EXC-001

The account was disabled 12 hours after the internal deadline.

### Exception IAM-EXC-002

The account was disabled 24 hours after the internal deadline.

Both cases require investigation.

The delays alone do not establish that unauthorised access occurred.

## 6. Initial Management Explanation

The IAM manager stated that the team was experiencing a busy workload.

**Evidence Status:** Not independently substantiated.

**Assessment:** Possible contributing factor.

**Root Cause Status:** Not confirmed.

The explanation must not be used to reclassify the failed tests as passing.

## 7. Root Cause Investigation Plan

The investigation should examine:

| Investigation Area | Evidence Required | Purpose |
|---|---|---|
| HR notification | Departure notification records | Determine whether IT received timely notice |
| Ticket creation | Service management timestamps | Establish when work entered the queue |
| Work allocation | Assignment and queue records | Assess ownership and workload |
| IAM processing | Account status and action logs | Verify execution times |
| Escalation | Overdue ticket alerts | Assess detection of delays |
| Procedure | Approved offboarding documentation | Check clarity of responsibilities |
| Staffing | Relevant staffing and workload records | Assess the manager's explanation |
| Automation | Workflow configuration | Identify manual dependencies |

Evidence should be handled securely and access restricted to authorised reviewers.

## 8. Root Cause Analysis — Five Whys Framework

The Five Whys method may help structure the investigation, but each answer requires supporting evidence.

| Question | Current Assessment |
|---|---|
| Why was account deactivation late? | Processing exceeded the 24-hour requirement |
| Why did processing exceed the requirement? | Not yet established |
| Why was the delay not prevented? | Not yet established |
| Why was the issue not escalated sooner? | Not yet established |
| What underlying process weakness contributed? | Investigation pending |

**Important:** The analysis must not invent missing causes to complete the Five Whys.

## 9. Potential Root Cause Hypotheses

The following are investigation hypotheses, not confirmed findings:

- HR departure notifications were delayed.
- IAM tickets were not assigned promptly.
- Manual processing created a bottleneck.
- Staff workload exceeded available capacity.
- No effective overdue-ticket escalation existed.
- Responsibilities between HR and IT were unclear.
- The offboarding workflow lacked appropriate automation.

Each hypothesis should be tested against reliable evidence.

## 10. Root Cause Determination

**Current Root Cause:** Undetermined.

**Evidence Reviewed:** Fictional testing results and management explanation.

**Additional Evidence Needed:** Workflow timestamps, notifications, tickets, staffing records, IAM logs and escalation records.

**Decision:** Defer final root cause classification until evidence is available.

## 11. Corrective Action Planning

Corrective actions should be selected after the relevant causes have been verified.

| Action ID | Proposed Action | Condition | Owner | Status |
|---|---|---|---|---|
| RCA-ACT-001 | Review HR-to-IAM notification process | If notification delays are found | HR / IAM | Proposed |
| RCA-ACT-002 | Introduce or improve overdue-ticket alerts | If escalation gaps are found | IAM Operations | Proposed |
| RCA-ACT-003 | Review staffing and queue management | If workload contributes to failures | IAM Management | Proposed |
| RCA-ACT-004 | Assess automated account deactivation | If manual processing creates risk | IAM Engineering | Proposed |
| RCA-ACT-005 | Clarify ownership and handoffs | If responsibilities are unclear | HR / IT | Proposed |
| RCA-ACT-006 | Conduct follow-up control testing | After remediation | Control Assurance | Pending |

Proposed actions should not be represented as implemented.

## 12. Corrective Action Validation Criteria

A corrective action should be evaluated for both implementation and effectiveness.

### Implementation Validation

Confirm that:

1. The approved change was introduced.
2. Relevant personnel were informed.
3. Supporting procedures were updated.
4. Technical configurations were changed where applicable.
5. Evidence of implementation was retained.

### Operating Effectiveness Validation

Confirm that:

1. A suitable post-remediation testing period has elapsed.
2. The departure population is complete and accurate.
3. The sample selection is documented.
4. Account deactivation timestamps are reliable.
5. Results are compared against the approved requirement.
6. Exceptions are investigated.
7. The testing conclusion is supported by evidence.

A corrective action is not automatically effective because implementation was completed.

## 13. Follow-Up Testing Plan

**Testing Objective:** Determine whether the revised offboarding process operates consistently within the defined 24-hour requirement.

**Population:** Employee departures during the approved post-remediation testing period.

**Sample Size:** To be determined under MediNova's assurance methodology.

**Sampling Considerations:**

- Include relevant higher-risk or privileged accounts.
- Consider departures across different teams.
- Verify the completeness of the population.
- Document the sample selection method.

**Pass Criteria:** All selected records meet the applicable test criteria, subject to the organisation's approved assurance methodology and treatment of any exceptions.

**Retesting Status:** Not started.

## 14. Corrective Action Evidence Register

| Evidence ID | Description | Status |
|---|---|---|
| RCA-EVD-001 | Verified root cause analysis | Pending |
| RCA-EVD-002 | Approved corrective action plan | Pending |
| RCA-EVD-003 | Implementation evidence | Pending |
| RCA-EVD-004 | Updated procedure or configuration | Pending |
| RCA-EVD-005 | Post-remediation departure population | Pending |
| RCA-EVD-006 | Retesting workpapers | Pending |
| RCA-EVD-007 | Exception investigation records | Pending |
| RCA-EVD-008 | Control owner confirmation | Pending |
| RCA-EVD-009 | Authorised finding closure decision | Pending |

## 15. Risk Implications

Delayed account deactivation may expose the organisation to:

- Continued access by former employees.
- Unauthorised use of privileged permissions.
- Inappropriate access to sensitive information.
- Delayed identification of account misuse.
- Failure to meet internal access management requirements.

The actual level of risk depends on permissions, monitoring, account activity and compensating controls.

**Related Risk:** RISK-IAM-001.

**Risk Status:** Open.

No revised risk score is assigned without supporting assessment.

## 16. GAP-001 Closure Readiness

| Closure Criterion | Status |
|---|---|
| Control failure documented | Completed in scenario |
| Root cause verified | No |
| Corrective actions approved | Pending |
| Corrective actions implemented | Not established |
| Implementation evidence reviewed | No |
| Follow-up operating effectiveness test | Pending |
| Test exceptions resolved | Pending |
| Residual risk reassessed | Pending |
| Authorised closure decision | Not recorded |

**Closure Recommendation:** Not recommended.

## 17. Management Reporting

**Finding:** GAP-001

**Control:** Employee Account Deactivation

**Failed Samples:** 2 of 10

**Root Cause:** Not verified

**Management Explanation:** High workload

**Corrective Action Status:** Proposed / Pending

**Retesting:** Not started

**Risk Status:** Open

**Finding Closure:** Not recommended

Management should receive updates on the investigation, corrective action ownership, deadlines and retesting results.

## 18. Final GRC Recommendations

The GRC Analyst should:

1. Preserve the original testing results.
2. Record the management explanation separately from verified findings.
3. Obtain relevant workflow and IAM evidence.
4. Determine the root cause using documented analysis.
5. Develop corrective actions targeted at verified causes.
6. Confirm implementation through supporting evidence.
7. Perform appropriate operating effectiveness retesting.
8. Reassess the related IAM risk.
9. Maintain GAP-001 as open until closure criteria are satisfied.
10. Obtain authorised approval before recording closure.

**Final Recommendation: INVESTIGATE ROOT CAUSE, VALIDATE CORRECTIVE ACTIONS AND RETEST BEFORE CLOSING GAP-001.**

## 19. Conclusion

The fictional MediNova assessment demonstrates why an explanation for a control failure should not be confused with a verified root cause.

Two employee accounts were disabled after the defined 24-hour deadline.

Although workload was suggested as the reason, the evidence necessary to confirm that explanation has not been reviewed.

The GRC Analyst should therefore preserve the exceptions, investigate the underlying causes, track corrective actions and verify operating effectiveness before recommending closure.

**Final Status: ROOT CAUSE UNVERIFIED — GAP-001 REMAINS OPEN.**

## 20. References

- ISO/IEC 27001:2022 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements.
- ISO/IEC 27002:2022 — Information security, cybersecurity and privacy protection — Information security controls.
- European Union. Regulation (EU) 2016/679, General Data Protection Regulation. https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng

## 21. Educational Disclaimer

MediNova is a fictional healthcare organisation used for cybersecurity GRC training.

All employee records, sample results, root cause hypotheses, corrective actions and testing plans are simulated.

No actual IAM logs, production records or independent assurance evidence were reviewed.

This report does not constitute proof of GDPR compliance or ISO 27001 certification.
