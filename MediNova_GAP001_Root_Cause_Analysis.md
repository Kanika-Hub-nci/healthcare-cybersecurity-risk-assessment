# MediNova — Root Cause Analysis Report

**Finding ID:** GAP-001  
**Finding Title:** Former Employee Account Remains Active  
**Risk Severity:** High (illustrative)  
**ISO/IEC 27001:2022 Control References:** A.5.16 — Identity Management; A.5.18 — Access Rights  
**Status:** Open — Investigation and Remediation Pending

## 1. Purpose

This report documents a simulated root cause analysis for an identity and access management weakness identified in the fictional MediNova healthcare environment.

**Disclaimer:** This is an educational GRC portfolio exercise. No real employee accounts, organisational records or security configurations were examined.

## 2. Problem Description

An account belonging to a former employee remains active after their employment has ended.

This creates a potential risk of unauthorised access to organisational systems and sensitive patient information.

## 3. Root Cause Analysis — 5 Whys

| Question | Illustrative explanation |
|---|---|
| Why 1: Why is the former employee's account active? | IT did not disable the account. |
| Why 2: Why was the account not disabled? | IT may not have received the employee's departure notification. |
| Why 3: Why might the notification have been missed? | HR may not have submitted an offboarding request. |
| Why 4: Why might the request have been missed? | The process may rely on manual email communication. |
| Why 5: Why might the process rely on manual communication? | A formal HR–IT offboarding workflow may not exist or may be ineffective. |

**Suspected Root Cause:** An inadequate or inconsistently implemented employee offboarding process.

This is a hypothesis requiring investigation, not a confirmed root cause.

## 4. Immediate Correction

**Proposed actions:**
- Investigate the account and disable it where appropriate.
- Review authentication logs for unusual activity.
- Check whether other former employees retain active accounts.

**Implementation Status:** Not verified.

## 5. Corrective and Preventive Actions

1. Establish a documented employee offboarding procedure.
2. Assign clear responsibilities to HR and IT.
3. Introduce a formal departure notification and account deactivation workflow.
4. Define and monitor account deactivation deadlines.
5. Conduct periodic reviews of departed employees' access rights.

**Proposed Action Owner:** IT Operations Manager, in coordination with HR.

**Illustrative Target Date:** 6 November 2026.

## 6. Evidence Required

- Employee departure records.
- HR offboarding notifications and tickets.
- Identity management account status reports.
- Account deactivation timestamps.
- Approved offboarding procedure.
- Samples of completed offboarding cases.

No actual evidence has been collected or assessed for this simulation.

## 7. Verification and Effectiveness Review

Before recommending closure, the GRC Analyst should:

1. Confirm that the affected account has been appropriately disabled.
2. Review whether other departed employees retain unnecessary access.
3. Verify that the new offboarding procedure is implemented.
4. Examine a sample of completed offboarding cases.
5. Confirm that account deactivation meets organisational requirements.
6. Record verification results and obtain authorised closure approval.

## 8. Conclusion

The simulated GAP-001 finding demonstrates the importance of identifying underlying process weaknesses rather than addressing only the immediate access issue.

The finding should remain open until the agreed corrective actions have been implemented, their effectiveness has been verified and closure has been approved.

**Final Status:** Open — Remediation and verification pending.
