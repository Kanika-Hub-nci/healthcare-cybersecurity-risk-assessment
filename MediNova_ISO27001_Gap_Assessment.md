# MediNova Healthcare — ISO 27001 Gap Assessment

## 1. Project Overview

This project demonstrates a simulated ISO/IEC 27001:2022 gap assessment for MediNova, a fictional healthcare technology platform that processes sensitive patient information.

The purpose of this assessment is to identify potential information security control gaps, evaluate associated cybersecurity risks, and recommend appropriate corrective actions.

## 2. Assessment Objectives

- Identify weaknesses in selected information security controls.
- Evaluate potential risks to the confidentiality, integrity, and availability of patient information.
- Map identified gaps to relevant ISO/IEC 27001:2022 Annex A controls.
- Recommend corrective actions and identify supporting audit evidence.
- Demonstrate practical Governance, Risk and Compliance (GRC) assessment skills.

## 3. Assessment Scope

This educational assessment focuses on:

- User access management
- Employee offboarding
- Privileged account security
- Multi-factor authentication (MFA)
- Data backup and recovery

**Disclaimer:** All scenarios, organisations, findings, and evidence described in this report are fictional and intended for educational purposes. This is not a formal ISO 27001 audit or certification assessment.
## 4. Gap Assessment Findings

### GAP-001: Former Employee Account Remains Active

**ISO 27001 Controls:**
- A.5.16 — Identity Management
- A.5.18 — Access Rights

**Finding:** A former employee's user account remained active after their employment ended.

**Risk:** An active account belonging to a former employee could be misused to gain unauthorised access to sensitive patient information and company systems.

**Evidence Required:**
- HR employee exit records
- User account status reports
- Account deactivation logs
- Employee offboarding records

**Recommendation:** The IT team should investigate the account, revoke access where appropriate, review the employee offboarding process, and ensure user accounts are disabled within the organisation's required timeframe.

**Provisional Severity:** High (illustrative)

**Status:** Open — remediation pending

**Assessment Note:** This finding is based on a fictional scenario. No actual company systems or employee records were assessed.
### GAP-002: Incomplete MFA Enforcement for Privileged Accounts

**ISO 27001 Control:**
- A.8.5 — Secure Authentication

**Finding:** Three out of twenty administrator accounts are excluded from MFA enforcement.

**Risk:** Administrator accounts without MFA are more vulnerable to credential-based attacks. A compromised privileged account could allow unauthorised access to sensitive patient information and critical systems.

**Evidence Required:**
- Administrator account inventory
- MFA configuration reports
- Authentication and sign-in logs
- Approved MFA exception records

**Recommendation:** Enforce MFA for all applicable privileged accounts, investigate existing exclusions, and verify that authentication policies are functioning effectively. Any necessary exceptions should be formally approved and supported by appropriate compensating controls.

**Provisional Severity:** High (illustrative)

**Status:** Open — remediation pending

**Assessment Note:** This is a fictional finding created for educational purposes. No real administrator accounts were assessed.
### GAP-003: Backup Restoration Testing Not Performed

**ISO 27001 Control:**
- A.8.13 — Information Backup

**Finding:** MediNova performs daily backups of patient records; however, backup restoration testing has not been conducted to verify whether the information can be successfully recovered.

**Risk:** In the event of ransomware, accidental deletion, system failure, or data corruption, the organisation may be unable to restore critical patient information. This could result in operational disruption, data loss, and reduced availability of healthcare services.

**Evidence Required:**
- Backup policy and procedures
- Backup execution logs
- Backup restoration test reports
- Disaster recovery test records
- Backup failure and remediation records

**Recommendation:** Conduct periodic backup restoration tests to verify data recoverability. Document the test results, investigate any failures, and establish a formal schedule for future recovery testing.

**Provisional Severity:** High (illustrative)

**Status:** Open — remediation pending

**Assessment Note:** This finding is based on a fictional healthcare scenario. No actual backup systems or recovery processes were assessed.
