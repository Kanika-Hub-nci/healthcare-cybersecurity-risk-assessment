# MediNova — Continuous Control Monitoring Report

**Report Reference:** CCM-001  
**Related Finding:** GAP-001  
**Control Area:** Employee Offboarding and Access Revocation  
**Framework:** ISO/IEC 27001:2022  
**Reporting Period:** July–September 2026 (Simulated)  
**Report Status:** Monitoring Exception Identified  
**Prepared By:** Cybersecurity GRC Analyst — Educational Simulation

---

## 1. Executive Summary

This report presents a simulated continuous control monitoring review of MediNova's employee offboarding and access revocation process.

The purpose of the review is to assess whether user accounts are consistently disabled within the organisation's assumed 24-hour offboarding requirement.

Monthly compliance decreased from 100% in July to 95% in August and 80% in September.

September's performance was 15 percentage points below the illustrative management target of 95%.

This declining trend indicates that the control requires further investigation and management attention.

No actual organisational monitoring or security assessment has been performed.

## 2. Control Overview

**Control Objective:** Ensure user access is removed promptly following employee departure.

**Relevant ISO/IEC 27001:2022 Controls:**

- A.5.16 — Identity Management
- A.5.18 — Access Rights
- A.8.5 — Secure Authentication

**Proposed Control Owner:** IT Operations Manager

**Supporting Function:** Human Resources

**Monitoring Function:** GRC / Control Assurance

**Monitoring Frequency:** Monthly

**Assumed Policy Requirement:** Disable employee accounts within 24 hours of departure.

The 24-hour timeframe is an illustrative internal requirement, not a universal ISO 27001 requirement.

## 3. Monitoring Metrics

### Key Performance Indicator (KPI)

Percentage of employee accounts disabled within the required timeframe.

**Formula:**

Compliance Rate (%) = (Number of compliant account deactivations / Total eligible account deactivations assessed) × 100

**Illustrative Target:** At least 95%.

### Key Risk Indicator (KRI)

Number or percentage of employee accounts remaining active beyond the permitted offboarding timeframe.

An increasing KRI may indicate greater exposure to unauthorised access.

### Key Control Indicator (KCI)

Percentage of employee departures supported by complete offboarding evidence, including HR notifications, service desk tickets and identity management records.

## 4. Monthly Monitoring Results

| Month | Compliance Rate | Target | Result |
|---|---|---|---|
| July 2026 | 100% | 95% | Target Met |
| August 2026 | 95% | 95% | Target Met |
| September 2026 | 80% | 95% | Below Target |

**Overall Trend:** Declining.

**July–September Change:** Decrease of 20 percentage points.

**September Target Shortfall:** 15 percentage points.

Monthly population sizes and underlying evidence have not been provided; therefore, these illustrative percentages cannot be independently verified.

## 5. Monitoring Exception

**Exception Reference:** CCM-EXC-001

**Control:** Employee offboarding and access revocation.

**Issue:** September compliance fell below the defined management target.

**Observed Compliance:** 80%.

**Required Target:** 95%.

**Exception Status:** Open — Investigation Required.

**Potential Risk:** Delayed access removal may increase the likelihood of unauthorised access to organisational systems or sensitive information.

**Root Cause:** Not yet established.

## 6. Potential Contributing Factors

The following are investigation hypotheses, not confirmed findings:

- Delays in HR departure notifications.
- Manual processing errors.
- Incomplete integration between HR and identity management systems.
- Lack of automated account disablement.
- Inadequate coverage of legacy applications.
- Insufficient monitoring of overdue access removal.

Evidence must be collected before assigning a root cause.

## 7. Recommended Investigation

1. Obtain the complete September employee departure population.
2. Identify accounts disabled after the required timeframe.
3. Compare HR departure timestamps with account disablement timestamps.
4. Review service desk tickets and identity provider logs.
5. Identify affected applications and privileged accounts.
6. Determine whether any overdue accounts were used after departure.
7. Investigate recurring causes of delay.
8. Assess whether the issue requires additional security incident escalation.

## 8. Recommended Corrective Actions

| Action | Proposed Owner | Priority | Status |
|---|---|---|---|
| Investigate September exceptions | IT Operations | High | Proposed |
| Review HR–IT notification workflow | HR and IT Operations | High | Proposed |
| Identify applications outside central IAM | IAM Team | High | Proposed |
| Assess automated deprovisioning | IAM Team | Medium | Proposed |
| Retest affected offboarding controls | GRC / Control Assurance | High | Proposed |
| Report monitoring trends to management | GRC Analyst | High | Proposed |

Priorities and owners are illustrative and subject to organisational approval.

## 9. Evidence Requirements

The following evidence should be requested:

- Approved employee offboarding policy.
- HR departure records.
- Identity management account status reports.
- Account disablement timestamps.
- Service desk offboarding tickets.
- Access review records.
- Previous monthly monitoring results.
- Corrective action implementation evidence.

Evidence should be reviewed for completeness, accuracy, relevance and timeliness.

## 10. Risk Assessment and Escalation

The decline in control performance may increase the risk associated with GAP-001.

The GRC Analyst should:

- Notify the responsible control owner.
- Assess the affected systems, account privileges and potential business impact.
- Determine whether additional remediation is necessary.
- Escalate significant or overdue control failures according to the organisation's risk management procedures.
- Update the relevant risk and remediation records.

No revised numerical risk score is assigned without sufficient supporting evidence.

## 11. Management Decisions Required

Management should consider:

1. Whether the current level of control performance is acceptable.
2. Whether additional resources are needed for remediation.
3. Whether further testing is required.
4. Whether monitoring frequency should be increased.
5. Whether GAP-001 closure should be deferred or a previously closed finding should be reassessed.

**Management Decision Status:** Pending — Simulated.

## 12. Monitoring Plan

**Frequency:** Monthly, subject to risk-based adjustment.

**Recommended Reporting:**

- Monthly compliance percentage.
- Number of overdue account deactivations.
- Number of privileged accounts affected.
- Number of unresolved exceptions.
- Progress of corrective actions.
- Evidence completeness.

**Suggested Escalation Trigger:** Compliance below the approved target or identification of a potentially serious access exposure.

## 13. Assessment Conclusion

The fictional monitoring results show a decline in employee offboarding compliance, with September performance falling below the illustrative management target.

The GRC Analyst should recommend further investigation, risk assessment and corrective action monitoring.

The available information does not establish the cause of the decline or prove that unauthorised access occurred.

**Overall Assessment:** Monitoring Exception Identified — Further Investigation Required.

## 14. Educational Disclaimer

MediNova is a fictional healthcare organisation created for cybersecurity GRC training.

All monitoring data, control owners, targets, exceptions and recommendations are simulated.

This document does not represent an actual audit, verified security control assessment or ISO 27001 certification.
