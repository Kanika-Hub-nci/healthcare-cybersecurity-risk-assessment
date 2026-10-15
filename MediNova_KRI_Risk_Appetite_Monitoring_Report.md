# MediNova — Key Risk Indicator and Risk Appetite Monitoring Report

**Report Reference:** KRI-001  
**Related Finding:** GAP-001  
**Control Area:** Employee Offboarding and Access Revocation  
**Framework:** ISO/IEC 27001:2022  
**Reporting Period:** October 2026 — Simulated  
**Report Status:** Red KRI Threshold Breach  
**Prepared By:** Cybersecurity GRC Analyst — Educational Simulation

---

## 1. Executive Summary

This report presents a simulated assessment of MediNova's cybersecurity Key Risk Indicators (KRIs) relating to employee offboarding and access revocation.

The fictional organisation achieved an overall offboarding compliance rate of 99%, exceeding its illustrative management target of 95%.

However, one former employee's privileged administrator account remained active beyond the permitted timeframe.

Under the scenario's assumed monitoring rules, any overdue privileged account deactivation triggers a Red KRI status.

**Overall Risk Monitoring Status: RED**

The result requires investigation, risk assessment and escalation in accordance with the organisation's approved procedures.

The 99% compliance result does not eliminate the potential risk associated with the privileged account exception.

## 2. Risk Appetite Statement

MediNova's illustrative risk appetite for unauthorised access to sensitive patient information is very low.

The organisation aims to minimise unnecessary access privileges, ensure timely removal of access following employment termination and promptly investigate exceptions involving privileged accounts.

This statement is proposed for training purposes. It is not an approved organisational risk appetite statement.

## 3. Risk Tolerance and Monitoring Thresholds

The following thresholds are illustrative and require formal organisational approval before operational use.

| Key Risk Indicator | Green | Amber | Red |
|---|---|---|---|
| Overdue standard account deactivations per month | 0 | 1–2 | 3 or more |
| Overdue privileged account deactivations | 0 | Not applicable | 1 or more |
| Overall offboarding compliance | 95% or above | 90% to below 95% | Below 90% |

The most severe applicable threshold determines the overall monitoring status for this scenario.

## 4. Current Monitoring Results

| Indicator | Simulated Result | Status |
|---|---|---|
| Overall offboarding compliance | 99% | Green |
| Privileged accounts overdue | 1 | Red |
| Standard accounts overdue | Not provided | Not assessed |
| Overall monitoring status | Critical threshold breached | Red |

The number of standard account exceptions and the underlying account population were not supplied and cannot be inferred from the 99% compliance figure.

## 5. KRI Breach Description

**Exception Reference:** KRI-EXC-001

**Issue:** Former employee's privileged administrator account remained active beyond the permitted offboarding timeframe.

**Threshold:** Zero overdue privileged account deactivations.

**Observed Result:** One overdue privileged account.

**KRI Status:** Red.

**Potential Impact:**

- Unauthorised access to sensitive systems.
- Misuse of administrative privileges.
- Exposure of confidential organisational or patient information.
- Increased potential for security incidents.

The available scenario does not establish that the account was used maliciously or that a data breach occurred.

## 6. Risk Assessment Considerations

The GRC Analyst should assess:

1. The administrator account's actual permissions.
2. The systems and information accessible through the account.
3. How long the account remained active after departure.
4. Whether authentication or activity logs show post-departure access.
5. Existing safeguards, including MFA and privileged access monitoring.
6. Whether the account has now been disabled.
7. Whether the issue is isolated or part of a recurring control weakness.

A final likelihood, impact and residual risk rating cannot be assigned without supporting evidence.

## 7. Recommended Escalation Actions

| Action | Proposed Responsible Team | Priority |
|---|---|---|
| Validate the privileged account exception | IAM / IT Operations | Immediate |
| Assess account activity and potential exposure | Security Operations | High |
| Determine whether incident response is required | Security Incident Response Team | High |
| Notify the responsible control and risk owners | GRC | High |
| Investigate the offboarding failure | HR / IT Operations | High |
| Track corrective action and retesting | GRC / Control Assurance | High |

These responsibilities and priorities are proposed for the fictional scenario.

## 8. Evidence Required

- Employee departure record.
- Account status and disablement timestamps.
- Privileged access assignment records.
- Authentication and activity logs.
- Offboarding tickets.
- Approved access removal procedure.
- Corrective action records.
- Follow-up control effectiveness testing.

## 9. Management Reporting

**Overall KPI Performance:** 99% — Target Met.

**Privileged Account KRI:** Red — Threshold Breached.

**Management Attention Required:** Yes.

**Recommended Decision:** Investigate and address the privileged account exception, assess its risk and determine whether additional escalation or remediation is necessary.

**Management Approval:** Not obtained.

## 10. Relationship to GAP-001

The KRI breach is relevant to the underlying employee offboarding weakness documented in GAP-001.

The GRC Analyst should determine whether the new exception indicates that corrective actions were ineffective or that the finding's closure assessment requires reconsideration.

If GAP-001 remains pending approval, the new evidence should be included in the closure review.

If GAP-001 has already been formally closed, the organisation should assess whether to reopen the finding or record a new finding under its approved procedures.

No actual reopening or closure decision is represented in this exercise.

## 11. Recommended Monitoring Improvements

- Monitor privileged account deactivations separately from standard accounts.
- Introduce alerts for overdue privileged access removal.
- Review HR–IT notification and identity lifecycle workflows.
- Report repeated exceptions to management.
- Periodically validate monitoring data quality.
- Reassess KRI thresholds as the organisation's risk profile changes, subject to authorised approval.

## 12. Conclusion

MediNova's simulated offboarding performance demonstrates that a positive overall compliance rate can coexist with a significant security control exception.

Although the organisation achieved 99% overall compliance, one overdue privileged administrator account breached the illustrative Red KRI threshold.

The GRC Analyst should therefore recommend investigation, appropriate escalation and corrective action monitoring.

**Final Monitoring Status: RED — Further Investigation Required.**

## 13. Educational Disclaimer

MediNova is a fictional healthcare organisation used for cybersecurity GRC training.

All monitoring results, risk appetite statements, thresholds, account details and recommendations are simulated.

This report does not represent an actual security assessment, confirmed data breach, approved risk appetite statement or ISO 27001 certification.
