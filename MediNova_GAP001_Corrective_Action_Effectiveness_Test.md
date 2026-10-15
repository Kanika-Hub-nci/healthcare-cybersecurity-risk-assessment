# MediNova — Corrective Action Effectiveness Testing Report

**Report Reference:** TEST-001  
**Related Finding:** GAP-001  
**Related Incident:** INC-001  
**Control Area:** Employee Offboarding and Access Revocation  
**Framework:** ISO/IEC 27001:2022 — A.5.16 Identity Management and A.5.18 Access Rights  
**Assessment Status:** Simulated Testing Completed  
**Finding Status:** Open — Further Remediation Required

## 1. Executive Summary

This report presents a simulated effectiveness test of MediNova's employee offboarding access removal process.

Five fictional employee departure records were reviewed against an illustrative internal requirement to disable user accounts within 24 hours of departure.

Four records met the requirement, while one exceeded the permitted timeframe.

**Sample Compliance Rate: 80%**

The results indicate a control exception requiring investigation. The available sample does not provide sufficient assurance to recommend closure of GAP-001.

## 2. Testing Objective

To determine whether the employee offboarding control consistently removes user access within the organisation's defined timeframe.

The test evaluates whether the control is operating as intended, rather than merely whether an offboarding procedure has been documented.

## 3. Scope and Methodology

**Population:** Fictional employee departures; complete population size not provided.

**Sample Size:** Five employee records.

**Sample Selection:** Illustrative sample; representativeness cannot be established.

**Testing Criterion:** Account disabled within 24 hours of departure.

**Testing Procedure:**

1. Identify employee departure records.
2. Compare departure timestamps with account disablement timestamps.
3. Calculate the elapsed time.
4. Compare results against the 24-hour requirement.
5. Document exceptions.
6. Assess whether additional investigation and retesting are required.

The 24-hour timeframe is an assumed MediNova policy requirement for this exercise, not a universal ISO 27001 deadline.

## 4. Testing Results

| Employee ID | Disablement Time | Required Time | Result |
|---|---|---|---|
| EMP-001 | 3 hours | Within 24 hours | Pass |
| EMP-002 | 6 hours | Within 24 hours | Pass |
| EMP-003 | 31 hours | Within 24 hours | Fail |
| EMP-004 | 2 hours | Within 24 hours | Pass |
| EMP-005 | 10 hours | Within 24 hours | Pass |

**Total Samples:** 5  
**Passed:** 4  
**Failed:** 1  
**Sample Compliance:** 80%  
**Sample Exception Rate:** 20%

## 5. Exception Details

**Exception Reference:** EXC-TEST-001

**Affected Record:** EMP-003

**Expected Outcome:** Account disabled within 24 hours.

**Observed Outcome:** Account disabled after 31 hours.

**Deviation:** 7 hours beyond the requirement.

**Potential Risk:** Continued account availability after employment termination may increase the opportunity for unauthorised access.

**Root Cause:** Not yet determined.

**Exception Status:** Open — Investigation Required.

## 6. Recommended Corrective Actions

| Recommended Action | Proposed Owner | Status |
|---|---|---|
| Investigate the EMP-003 delay | IT Operations | Pending |
| Review HR departure notification timing | HR and IT Operations | Pending |
| Check account disablement workflow | IAM Team | Pending |
| Correct identified process weaknesses | Process Owner | Pending |
| Perform follow-up effectiveness testing | GRC / Control Assurance | Pending |

Owners and statuses are proposed for the simulation, not confirmed operational assignments.

## 7. Additional Evidence Required

- Approved offboarding procedure and access removal timeframe.
- HR departure records with timestamps.
- Identity provider account disablement logs.
- Service desk offboarding tickets.
- Evidence of corrective action implementation.
- Follow-up test samples covering the relevant systems and time period.

## 8. Assessment Conclusion

The simulated test identified one exception among five sampled employee departures.

Although four samples met the stated requirement, the failed sample indicates that the control did not operate consistently across the tested records.

The small, illustrative sample does not support a conclusion about organisation-wide control effectiveness.

**Recommended GAP-001 Status: Remain Open.**

Further investigation, corrective action and proportionate retesting are required before recommending closure.

## 9. Management Reporting

**Key Finding:** One late account deactivation identified.

**Potential Business Impact:** Increased risk of unauthorised access following employee departure.

**Recommended Decision:** Continue remediation and request evidence of control effectiveness.

**Closure Approval:** Not requested.

## 10. Educational Disclaimer

MediNova is a fictional healthcare organisation.

All employee identifiers, timestamps, test results and recommendations in this document are simulated. No real employee data, audit testing or management approval is represented.
