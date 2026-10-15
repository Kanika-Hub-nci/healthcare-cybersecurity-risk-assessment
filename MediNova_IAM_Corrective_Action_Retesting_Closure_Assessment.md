# MediNova — Corrective Action Retesting and Audit Finding Closure Assessment

**Report Reference:** IAM-RET-001  
**Related Audit Finding:** GAP-001  
**Related Risk:** RISK-IAM-001  
**Related Root Cause Assessment:** IAM-RCA-002  
**Framework:** ISO/IEC 27001:2022  
**Report Status:** Retesting Exception Identified — Closure Not Recommended  
**Classification:** Educational Simulation

---

## 1. Executive Summary

This report evaluates the effectiveness of corrective actions introduced to address MediNova's employee offboarding control weakness.

An earlier operating effectiveness assessment identified two failures among ten sampled employee departures.

Following reported corrective action implementation, MediNova conducted a fictional follow-up test involving twelve employee departures.

**Retesting results:**

- 12 employee departures tested.
- 11 accounts disabled within the required timeframe.
- 1 account disabled after the required timeframe.
- Sample pass rate: 91.7%.
- Sample exception rate: 8.3%.

Although the sample pass rate improved from the earlier 80%, one control failure remains.

**GRC Recommendation:** Keep GAP-001 open pending investigation of the remaining exception, appropriate corrective action and further assurance.

## 2. Background

MediNova's employee offboarding control requires applicable employee accounts to be disabled within 24 hours of the approved termination effective time.

The control is intended to reduce the risk of former employees retaining access to organisational systems.

The original assessment identified two delayed account deactivations.

Following that assessment, MediNova reported implementing improvements to its offboarding process.

These improvements require validation to determine whether they are effective.

## 3. Assessment Objectives

The objectives of the retesting exercise are to:

1. Determine whether corrective actions have improved control operation.
2. Verify account deactivation against the 24-hour requirement.
3. Identify recurring or new exceptions.
4. Assess whether further remediation is required.
5. Evaluate GAP-001 closure readiness.

## 4. Relevant Security Controls

**ISO/IEC 27001:2022 Annex A.5.16 — Identity Management**

Supports appropriate management of identities throughout their lifecycle.

**ISO/IEC 27001:2022 Annex A.5.18 — Access Rights**

Addresses provisioning, reviewing, modifying and removing access rights.

**ISO/IEC 27001:2022 Annex A.8.2 — Privileged Access Rights**

Addresses restriction and management of privileged access.

The 24-hour timeframe is a fictional MediNova internal requirement, not a universal ISO 27001 or GDPR deadline.

## 5. Previous Testing Results

| Metric | Original Test |
|---|---:|
| Sample size | 10 |
| Passed | 8 |
| Failed | 2 |
| Sample pass rate | 80% |
| Sample exception rate | 20% |

The two failures involved accounts disabled after 36 hours and 48 hours.

The original exceptions were retained for investigation and corrective action tracking.

## 6. Corrective Action Background

For this simulation, MediNova is assumed to have introduced improvements such as:

- Updated HR-to-IAM notification procedures.
- Improved service desk ticket assignment.
- Overdue deactivation alerts.
- Additional staff guidance.
- Enhanced monitoring of offboarding activities.

The exact implementation evidence has not been independently reviewed.

These measures should therefore be treated as reported improvements rather than independently validated controls.

## 7. Retesting Scope

| Item | Details |
|---|---|
| Control | Employee account deactivation |
| Related finding | GAP-001 |
| Related risk | RISK-IAM-001 |
| Testing approach | Operating effectiveness retesting |
| Sample size | 12 |
| Control requirement | Within 24 hours |
| Testing period | Fictional post-remediation period |
| Population completeness | Not independently verified |

The test results are illustrative and cannot be generalised to all employee departures.

## 8. Testing Methodology

For each selected employee departure, the GRC Analyst should:

1. Obtain the approved termination effective time from HR.
2. Identify relevant employee accounts.
3. Obtain IAM deactivation timestamps.
4. Calculate elapsed time between termination and deactivation.
5. Compare results against the 24-hour requirement.
6. Review relevant offboarding tickets.
7. Record each sample as Pass, Fail or Unable to Determine.
8. Investigate exceptions and retain supporting evidence.

The tester should also verify time-zone consistency and evidence reliability.

## 9. Retesting Results

| Sample ID | Deactivation Time | Requirement | Result |
|---|---:|---|---|
| RET-001 | 1 hour | Within 24 hours | Pass |
| RET-002 | 3 hours | Within 24 hours | Pass |
| RET-003 | 5 hours | Within 24 hours | Pass |
| RET-004 | 7 hours | Within 24 hours | Pass |
| RET-005 | 9 hours | Within 24 hours | Pass |
| RET-006 | 11 hours | Within 24 hours | Pass |
| RET-007 | 13 hours | Within 24 hours | Pass |
| RET-008 | 15 hours | Within 24 hours | Pass |
| RET-009 | 18 hours | Within 24 hours | Pass |
| RET-010 | 20 hours | Within 24 hours | Pass |
| RET-011 | 23 hours | Within 24 hours | Pass |
| RET-012 | 30 hours | Within 24 hours | Fail |

All employee identifiers and results are fictional.

## 10. Retesting Summary

| Metric | Result |
|---|---:|
| Samples tested | 12 |
| Passed | 11 |
| Failed | 1 |
| Sample pass rate | 91.7% |
| Sample exception rate | 8.3% |

**Pass Rate Calculation**

(11 ÷ 12) × 100 = 91.7%

**Exception Rate Calculation**

(1 ÷ 12) × 100 = 8.3%

## 11. Comparison of Previous and Current Results

| Measurement | Previous Test | Retest |
|---|---:|---:|
| Samples | 10 | 12 |
| Passed | 8 | 11 |
| Failed | 2 | 1 |
| Pass rate | 80% | 91.7% |
| Exception rate | 20% | 8.3% |

The sample pass rate increased by approximately 11.7 percentage points.

However, the tests used different fictional samples. This comparison does not establish statistically significant improvement or organisation-wide control effectiveness.

## 12. Remaining Control Exception

**Exception ID:** RET-EXC-001

**Employee Sample:** RET-012

**Required Deactivation:** Within 24 hours.

**Actual Deactivation:** After 30 hours.

**Delay Beyond Requirement:** 6 hours.

**Result:** Fail.

### Risk Implications

The delayed deactivation may have allowed the account to remain available beyond the approved deadline.

Potential consequences include unauthorised access, misuse of permissions or exposure of sensitive information.

The late deactivation alone does not establish that unauthorised access occurred.

### Investigation Requirements

The IAM team should investigate:

- When HR issued the termination notification.
- When the offboarding ticket was created.
- When the ticket was assigned.
- Whether escalation alerts were generated.
- Whether the account held privileged permissions.
- Whether account activity occurred during the delay.
- Whether the failure relates to an earlier root cause.

**Root Cause Status:** Not established.

## 13. Corrective Action Validation

| Validation Requirement | Status |
|---|---|
| Corrective actions reported implemented | Yes, in scenario |
| Implementation evidence verified | Not independently verified |
| Retesting completed | Illustrative test completed |
| All tested samples passed | No |
| Remaining exception investigated | Pending |
| Control effectiveness established | Not fully demonstrated |
| Finding closure criteria satisfied | No |

**Validation Conclusion:** Additional assurance is required.

## 14. Corrective Action Follow-Up Plan

| Action ID | Recommended Action | Proposed Owner | Status |
|---|---|---|---|
| ACT-RET-001 | Investigate remaining exception | IAM Operations | Open |
| ACT-RET-002 | Identify verified root cause | IAM / GRC | Pending |
| ACT-RET-003 | Review effectiveness of implemented changes | Control Owner | Pending |
| ACT-RET-004 | Implement additional corrective actions if required | IAM Engineering | Pending |
| ACT-RET-005 | Review overdue-ticket monitoring | Security Operations | Pending |
| ACT-RET-006 | Conduct additional operating effectiveness testing | Control Assurance | Pending |
| ACT-RET-007 | Reassess residual risk | Risk Owner / GRC | Pending |
| ACT-RET-008 | Reassess audit finding closure | GRC / Audit | Pending |

## 15. Evidence Requirements

| Evidence ID | Evidence Description | Status |
|---|---|---|
| RET-EVD-001 | Approved corrective action plan | Not provided |
| RET-EVD-002 | Corrective action implementation records | Not provided |
| RET-EVD-003 | Complete HR departure population | Not provided |
| RET-EVD-004 | IAM account deactivation records | Illustrative results only |
| RET-EVD-005 | Offboarding ticket history | Not provided |
| RET-EVD-006 | Exception investigation findings | Pending |
| RET-EVD-007 | Additional remediation evidence | Pending |
| RET-EVD-008 | Follow-up testing workpapers | Pending |
| RET-EVD-009 | Authorised closure approval | Not recorded |

## 16. Residual Risk Assessment

**Related Risk:** RISK-IAM-001.

The remaining failure indicates that delayed account deactivation remains possible within the tested process.

Potential risk areas include:

- Continued access after employment termination.
- Unauthorised access to organisational systems.
- Privileged account misuse.
- Exposure of confidential information.
- Inadequate monitoring of offboarding exceptions.

The residual risk rating should be reassessed using MediNova's approved risk methodology.

No revised risk rating is assigned without supporting evidence.

## 17. GAP-001 Audit Finding Closure Assessment

| Closure Criterion | Status |
|---|---|
| Original control weakness documented | Completed |
| Corrective action plan established | Reported |
| Implementation evidence validated | Pending |
| Retesting performed | Yes, illustrative |
| All samples passed | No |
| Remaining exception investigated | No |
| Additional remediation assessed | Pending |
| Residual risk reassessed | Pending |
| Authorised closure decision | Not recorded |

**Closure Recommendation:** Do not close GAP-001.

An improved sample pass rate is not sufficient by itself to demonstrate that the underlying weakness has been resolved.

## 18. Management Reporting Statement

"The corrective action retesting exercise identified eleven passing samples and one failed sample. Although the sample pass rate increased compared with the earlier test, one employee account was disabled six hours beyond the approved deadline. The exception requires investigation, and the effectiveness of the corrective actions has not been fully demonstrated. Closure of GAP-001 is therefore not recommended at this stage."

## 19. GRC Analyst Responsibilities

The GRC Analyst should:

1. Preserve the original and retesting results.
2. Maintain the exception register.
3. Review the reliability of supporting evidence.
4. Investigate unresolved control failures with the relevant owners.
5. Track corrective action progress.
6. Coordinate appropriate follow-up testing.
7. Support residual risk reassessment.
8. Document management decisions.
9. Maintain GAP-001 as open until closure criteria are met.
10. Seek authorised approval before updating the finding status.

## 20. Final Recommendations

MediNova should:

1. Investigate the remaining failed sample.
2. Determine whether the weakness is recurring or new.
3. Review implementation evidence.
4. Implement additional remediation where appropriate.
5. Perform further risk-based operating effectiveness testing.
6. Reassess RISK-IAM-001.
7. Retain relevant audit evidence.
8. Reconsider GAP-001 closure only after sufficient assurance has been obtained.

**Final Recommendation: GAP-001 REMAINS OPEN — RETEST EXCEPTION REQUIRES INVESTIGATION AND FURTHER ASSURANCE.**

## 21. Conclusion

This fictional assessment demonstrates that an increase in control compliance does not automatically justify closing an audit finding.

MediNova's illustrative sample pass rate improved from 80% to approximately 91.7%, but one employee account was still disabled after the approved deadline.

The remaining exception requires investigation and appropriate follow-up.

**Final Status: CORRECTIVE ACTION IMPROVEMENT OBSERVED — AUDIT FINDING CLOSURE NOT RECOMMENDED.**

## 22. References

- ISO/IEC 27001:2022 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements.
- ISO/IEC 27002:2022 — Information security, cybersecurity and privacy protection — Information security controls.
- European Union. Regulation (EU) 2016/679, General Data Protection Regulation. https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng

## 23. Educational Disclaimer

MediNova is a fictional healthcare organisation used for cybersecurity GRC training.

All employee records, control tests, corrective actions, findings and management decisions are simulated.

No actual production IAM evidence or independent assurance testing was performed.

This document does not establish ISO 27001 certification or GDPR compliance.
