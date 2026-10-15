# MediNova — Audit Evidence Review Checklist

**Finding ID:** GAP-002  
**Finding Title:** Incomplete MFA Enforcement for Privileged Accounts  
**ISO/IEC 27001:2022 Control:** A.8.5 — Secure Authentication  
**Risk Rating:** High (illustrative)  
**Review Status:** Failed Verification — Simulated Exercise  
**Finding Closure Status:** Open

## 1. Objective

To assess whether Multi-Factor Authentication (MFA) is appropriately enforced across MediNova's privileged administrator accounts and whether sufficient evidence exists to support remediation closure.

## 2. Scope

The assessment covers 20 fictional administrator accounts, including any emergency access accounts and documented exceptions.

## 3. Evidence Review Checklist

| ID | Evidence / Verification Requirement | Simulated Result | Assessment |
|---|---|---|---|
| EVD-001 | Current inventory of all 20 administrator accounts | Inventory lists 20 accounts | Satisfactory for population identification |
| EVD-002 | MFA configuration report for all privileged accounts | 19 of 20 accounts show MFA enabled | Failed |
| EVD-003 | Authentication logs or test evidence demonstrating MFA enforcement | Logs provided for only 10 accounts | Incomplete |
| EVD-004 | Documented and approved MFA exceptions | No approved exception record provided | Failed |
| EVD-005 | Evidence of compensating controls for emergency accounts | Not provided | Pending |
| EVD-006 | Evidence of monitoring and review of privileged access | Not provided | Pending |

## 4. Key Observations

- One administrator account does not have MFA enabled in the simulated configuration report.
- Authentication evidence covers only 10 of the 20 accounts.
- No documented approval has been provided for the account without MFA.
- Compensating control and monitoring evidence is unavailable.

## 5. Risk Assessment

An administrator account without adequate authentication safeguards may increase the likelihood of unauthorised privileged access, potentially affecting sensitive patient information and critical healthcare systems.

**Illustrative Risk Rating:** High.

## 6. Recommended Corrective Actions

1. Investigate the administrator account without MFA.
2. Confirm whether it is an approved emergency access account.
3. Review the risk assessment and documented exception approval.
4. Evaluate compensating controls and monitoring arrangements.
5. Obtain current authentication evidence covering the relevant account population.
6. Repeat verification after corrective actions are completed.

## 7. Evidence Verification Conclusion

**Verification Outcome:** Failed — simulated scenario.

The evidence provided does not sufficiently demonstrate that MFA is appropriately enforced or that exceptions are adequately managed across the complete administrator account population.

**Recommended Finding Status:** Open — further remediation and verification required.

**Closure Recommendation:** Do not close GAP-002 at this stage.

## 8. Educational Disclaimer

This document is part of a fictional cybersecurity GRC portfolio project. The evidence IDs, observations and results are simulated. No real security systems, administrator accounts, authentication logs or organisational records were examined.
