# MediNova — IAM Offboarding Control Operating Effectiveness Testing Report

**Report Reference:** IAM-OET-001  
**Related Audit Finding:** GAP-001  
**Related Risk:** RISK-IAM-001  
**Related Security Event:** EVT-002  
**Related Control:** Employee Account Deactivation  
**Framework Reference:** ISO/IEC 27001:2022 — Annex A.5.16 and A.5.18  
**Assessment Type:** Operating Effectiveness Testing  
**Report Status:** Exceptions Identified — Further Remediation Required  
**Document Classification:** Educational Simulation

---

## 1. Executive Summary

This report presents a fictional operating effectiveness assessment of MediNova's employee offboarding access control.

Following an earlier security incident involving an account associated with a former employee, MediNova introduced an updated offboarding checklist and access deactivation procedure.

The control requires employee accounts to be disabled within 24 hours of the approved termination effective time.

The testing exercise uses a fictional population of 40 employee departures, from which 10 records were selected for review.

Of the 10 records tested:

- Eight met the defined deactivation requirement.
- Two did not meet the requirement.
- The observed sample compliance rate was 80%.

The two exceptions indicate that the control did not operate as required in all tested cases.

**Overall Assessment:** Operating effectiveness not demonstrated to the required standard.

**GRC Recommendation:** Keep GAP-001 open pending exception investigation, corrective action and appropriate retesting.

## 2. Assessment Objective

To determine whether MediNova's employee offboarding process consistently disables access within the organisation's defined 24-hour requirement.

The assessment also considers whether sufficient evidence exists to support closure of the related audit finding.

## 3. Scope

| Item | Assessment Scope |
|---|---|
| Process | Employee offboarding |
| Control | Account deactivation |
| Population | 40 fictional employee departures |
| Sample size | 10 |
| Testing period | Illustrative period; exact dates not specified |
| Primary evidence | HR termination records and IAM deactivation records |
| Related finding | GAP-001 |
| Related risk | RISK-IAM-001 |

Privileged accounts, third-party identities, application-specific access and emergency access may require additional testing depending on MediNova's approved control scope.

## 4. Control Description

### Control Objective

Prevent former employees from retaining unauthorised access to organisational systems after departure.

### Expected Control Operation

The HR department records the approved termination effective time.

The responsible IT or IAM team receives the departure information and disables the employee's applicable accounts within 24 hours.

The organisation retains appropriate evidence of the action.

### Control Frequency

Event-driven — whenever an employee leaves the organisation.

### Control Owner

IAM / IT Operations, supported by HR.

### Testing Criterion

Account deactivation must occur no later than 24 hours after the approved termination effective time.

This 24-hour requirement is a fictional internal MediNova standard, not a universal GDPR or ISO 27001 deadline.

## 5. Relevant Control Framework

### ISO/IEC 27001:2022 Annex A.5.16 — Identity Management

Supports the management of identities throughout their lifecycle.

### ISO/IEC 27001:2022 Annex A.5.18 — Access Rights

Addresses provisioning, reviewing, modifying and removing access rights in accordance with organisational access control requirements.

The existence of these control references does not establish implementation or certification.

## 6. Test Population and Sample Selection

The fictional HR departure population contains 40 records.

Ten records were selected for illustrative testing.

In a real assessment, the tester should:

1. Obtain the complete population from an authoritative source.
2. Verify population completeness and accuracy.
3. Define the review period.
4. Select a documented sample.
5. Consider higher-risk cases, including privileged users.
6. Record the selection method and rationale.

The sample in this exercise is illustrative. No actual random selection or independent population validation was performed.

## 7. Evidence Requirements

| Evidence ID | Evidence Description | Purpose |
|---|---|---|
| EVD-IAM-001 | HR departure population | Establish complete population |
| EVD-IAM-002 | Approved termination effective times | Determine deactivation deadlines |
| EVD-IAM-003 | IAM account status history | Verify actual deactivation |
| EVD-IAM-004 | Offboarding tickets | Confirm workflow execution |
| EVD-IAM-005 | Privileged access records | Identify elevated access |
| EVD-IAM-006 | Exception and escalation records | Assess failures |
| EVD-IAM-007 | Updated offboarding procedure | Confirm control design |
| EVD-IAM-008 | Corrective action evidence | Support remediation review |

Evidence should be securely retained and should not unnecessarily expose personal information.

## 8. Testing Methodology

For each selected departure:

1. Identify the approved termination effective time.
2. Identify the associated user account or accounts.
3. Obtain the actual deactivation timestamp.
4. Calculate the elapsed time between termination and deactivation.
5. Compare the result against the 24-hour requirement.
6. Review whether any relevant account remained active.
7. Record the result as Pass, Fail or Unable to Determine.
8. Investigate and document exceptions.

The tester should confirm that timestamps use a consistent time zone and that the approved termination effective time is authoritative.

Missing or unreliable evidence should not automatically be treated as a passing result.

## 9. Illustrative Sample Results

| Sample | Deactivation Time After Termination | Requirement | Result |
|---|---:|---|---|
| EMP-001 | 2 hours | Within 24 hours | Pass |
| EMP-002 | 5 hours | Within 24 hours | Pass |
| EMP-003 | 8 hours | Within 24 hours | Pass |
| EMP-004 | 12 hours | Within 24 hours | Pass |
| EMP-005 | 18 hours | Within 24 hours | Pass |
| EMP-006 | 20 hours | Within 24 hours | Pass |
| EMP-007 | 22 hours | Within 24 hours | Pass |
| EMP-008 | 24 hours | Within 24 hours | Pass |
| EMP-009 | 36 hours | Within 24 hours | Fail |
| EMP-010 | 48 hours | Within 24 hours | Fail |

All sample IDs and timestamps are fictional.

The exercise assumes that the underlying evidence is sufficient to calculate the stated intervals.

## 10. Test Result Summary

| Metric | Result |
|---|---:|
| Samples tested | 10 |
| Passed | 8 |
| Failed | 2 |
| Unable to determine | 0 |
| Sample pass rate | 80% |
| Sample exception rate | 20% |

### Calculation

Sample pass rate = (8 / 10) × 100 = 80%.

Sample exception rate = (2 / 10) × 100 = 20%.

These results describe only the illustrative tested sample and should not be presented as the verified failure rate across all 40 departures.

## 11. Exception Analysis

### Exception IAM-EXC-001

**Sample:** EMP-009  
**Required Deactivation:** Within 24 hours  
**Observed Deactivation:** 36 hours  
**Delay Beyond Requirement:** 12 hours  
**Result:** Fail

**Potential Exposure:** The account remained active beyond the approved deactivation deadline.

**Root Cause:** Not established.

**Required Action:** Investigate the workflow, identify the reason for delay and determine whether the account was used during the extended active period.

### Exception IAM-EXC-002

**Sample:** EMP-010  
**Required Deactivation:** Within 24 hours  
**Observed Deactivation:** 48 hours  
**Delay Beyond Requirement:** 24 hours  
**Result:** Fail

**Potential Exposure:** The account remained active beyond the approved deactivation deadline.

**Root Cause:** Not established.

**Required Action:** Investigate the cause of delay, confirm the account's permissions and assess whether additional security review is necessary.

Neither exception alone proves that unauthorised access occurred.

## 12. Control Effectiveness Assessment

### Design Effectiveness

The updated procedure defines a control objective, responsibility and deactivation timeframe.

A complete design effectiveness conclusion would require reviewing the actual approved procedure and supporting workflow.

**Design Status:** Appears appropriately directed in the scenario; independent validation not performed.

### Implementation

The scenario assumes that the updated checklist has been introduced.

**Implementation Status:** Reported as implemented; underlying implementation evidence not independently verified.

### Operating Effectiveness

Two of the ten fictional tested cases failed the defined requirement.

**Operating Effectiveness Status:** Exceptions identified; consistent operation not demonstrated.

## 13. Risk Assessment Implications

Delayed account deactivation may increase the risk of:

- Unauthorised access after employment ends.
- Misuse of privileged accounts.
- Access to confidential information.
- Delayed detection of inappropriate activity.
- Non-compliance with internal access management requirements.

The actual impact depends on account permissions, available resources, monitoring and whether any misuse occurred.

The test results support continued review of RISK-IAM-001.

A revised risk rating should be determined using MediNova's approved risk methodology.

## 14. Corrective Action Recommendations

| Action ID | Recommended Action | Proposed Owner | Status |
|---|---|---|---|
| ACT-IAM-001 | Investigate both late deactivations | IAM / IT Operations | Open |
| ACT-IAM-002 | Confirm completeness of HR-to-IAM notifications | HR / IAM | Open |
| ACT-IAM-003 | Review account permissions during the delay | Security Operations | Open |
| ACT-IAM-004 | Review automated deactivation opportunities | IAM Engineering | Proposed |
| ACT-IAM-005 | Implement exception escalation and monitoring | IAM / Security Operations | Proposed |
| ACT-IAM-006 | Reassess control design and implementation | Control Owner | Pending |
| ACT-IAM-007 | Perform follow-up operating effectiveness testing | Control Assurance | Pending |
| ACT-IAM-008 | Reassess GAP-001 closure readiness | GRC / Audit | Pending |

Owners and statuses are illustrative.

## 15. Retesting Strategy

Following remediation, MediNova should perform an appropriate follow-up test.

The retest should:

1. Cover a defined period after corrective actions were implemented.
2. Use a validated departure population.
3. Include relevant privileged and higher-risk accounts.
4. Apply documented sample selection criteria.
5. Verify deactivation timestamps.
6. Investigate missing or inconsistent records.
7. Evaluate whether exceptions recur.
8. Document the testing conclusion.

A retest should not automatically be declared successful simply because a new checklist has been issued.

The appropriate sample size and acceptance criteria should follow the organisation's approved assurance methodology.

## 16. GAP-001 Closure Assessment

| Closure Criterion | Status |
|---|---|
| Updated procedure introduced | Reported in scenario |
| Implementation evidence verified | Not independently verified |
| Operating effectiveness testing completed | Illustrative test completed |
| All tested cases met the requirement | No |
| Exceptions investigated | Pending |
| Corrective actions completed | Pending |
| Successful retesting | Pending |
| Authorised finding closure | Not approved |

**GAP-001 Closure Recommendation:** Do not close.

The finding should remain open until remediation and assurance evidence support an authorised closure decision.

## 17. Management Reporting Summary

**Finding:** GAP-001

**Control:** Employee Account Deactivation

**Population:** 40 fictional departures

**Samples Tested:** 10

**Passed:** 8

**Failed:** 2

**Sample Compliance Rate:** 80%

**Exception Status:** Investigation required

**Operating Effectiveness:** Not demonstrated to the defined requirement

**Residual Risk:** Open

**Finding Closure:** Not recommended

## 18. Final GRC Recommendations

The GRC Analyst should recommend:

1. Keeping GAP-001 open.
2. Investigating both deactivation failures.
3. Assessing the exposure associated with the delayed accounts.
4. Reviewing the reliability of the HR-to-IAM offboarding process.
5. Implementing appropriate corrective actions.
6. Conducting follow-up effectiveness testing.
7. Updating RISK-IAM-001 as necessary.
8. Retaining the supporting evidence and exception records.
9. Seeking authorised closure only when the required criteria have been satisfied.

**Final Recommendation: GAP-001 REMAINS OPEN — CONTROL EXCEPTIONS REQUIRE INVESTIGATION AND RETESTING.**

## 19. Conclusion

This fictional assessment demonstrates the difference between introducing a security procedure and verifying that it operates effectively.

Although MediNova has implemented an updated offboarding process, two of the ten illustrative tested departures failed the defined 24-hour deactivation requirement.

The observed exceptions require investigation and appropriate remediation.

The GRC Analyst should therefore maintain the audit finding as open and recommend further assurance before closure.

**Final Status: OPERATING EFFECTIVENESS EXCEPTIONS IDENTIFIED — GAP-001 OPEN.**

## 20. References

- ISO/IEC 27001:2022 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements.
- ISO/IEC 27002:2022 — Information security, cybersecurity and privacy protection — Information security controls.
- European Union. Regulation (EU) 2016/679, General Data Protection Regulation. https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng

## 21. Educational Disclaimer

MediNova is a fictional healthcare organisation used for cybersecurity GRC training.

All employee records, testing populations, timestamps, results, exceptions and corrective actions are simulated.

No real employee information, production IAM evidence or independent operating effectiveness testing is represented.

This document does not constitute proof of ISO 27001 certification or GDPR compliance.
