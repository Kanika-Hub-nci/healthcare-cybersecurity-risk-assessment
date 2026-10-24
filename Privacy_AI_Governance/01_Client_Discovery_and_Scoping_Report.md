# MediNova Healthcare — Client Discovery & Scoping Report
## AI-Powered Patient Triage Assistant

**Document ID:** PRIV-AI-002  
**Version:** 1.0  
**Date:** 24 October 2026  
**Status:** Draft for simulated client discussion  
**Prepared by:** Junior Privacy & AI Governance Consultant (simulation)

> **Simulation notice:** MediNova is fictional. This report is a portfolio exercise based on assumptions, not a record of an actual client meeting. Items marked “to confirm” are open discovery questions and must not be treated as established facts.

## 1. Purpose of this report

This report defines the proposed advisory engagement, records the initial scenario, identifies information required from the organisation, and recommends the next steps for assessing privacy and AI governance risks before any launch decision.

## 2. Proposed use case

MediNova is exploring an AI-powered assistant that would review information submitted by patients, categorise requests and suggest a priority for clinical review.

The system could affect how quickly a patient receives attention. For that reason, the assessment must consider not only confidentiality and security, but also the potential effect of inaccurate, biased, misleading or poorly supervised recommendations on patients.

**Preliminary recommendation:** Treat the proposal as potentially high impact until the intended purpose, actual system behaviour, and clinical workflow are understood. This is a cautious scoping position, not a formal legal classification.

## 3. Objectives and decisions needed

The engagement should enable MediNova to:
- Describe the purpose and boundaries of the AI system.
- Confirm which data is collected, generated, shared, retained and deleted.
- Establish who determines the purposes and means of processing and the roles of technology suppliers.
- Assess necessity, proportionality and less intrusive alternatives.
- Determine and document whether a DPIA is required; if required, complete it before processing begins.
- Identify a defensible Article 6 lawful basis and an applicable Article 9 condition for health data, with legal/DPO input as needed.
- Define privacy, security, clinical oversight and AI governance controls.
- Decide what must be resolved before testing or deployment.

## 4. Preliminary scope and boundaries

**Included:** discovery, data mapping, privacy risk identification, DPIA screening, DPIA preparation, lawful-basis questions, vendor due diligence, transparency, retention, security safeguards, human oversight, governance actions and executive reporting.

**Excluded:** clinical efficacy testing, medical-device regulatory advice, penetration testing, definitive legal opinions, and approval to launch. These may require separate qualified specialists.

## 5. Discovery questions for the client

### A. Purpose and workflow
1. What specific problem is the assistant intended to solve?
2. Who will use it: patients, reception staff, nurses, doctors, or another group?
3. What exactly will the AI output: a category, urgency score, suggested response, or clinical recommendation?
4. Can the output change a patient's place in a queue or access to care?
5. What happens if a patient reports emergency symptoms or the AI cannot interpret the submission?
6. Who makes the final decision, and can that person override the output?

### B. Personal data and data flow
7. What data fields will patients submit, and which fields are mandatory?
8. Will the system process names, contact details, symptoms, medical history, images, audio, or other identifiers?
9. Will it infer or generate health-related information about a patient?
10. Where will data be collected, processed, stored, backed up and deleted?
11. Who can access raw submissions, AI outputs and logs?
12. How long will each data type be retained, and what triggers deletion?

### C. Lawful basis, transparency and individual rights
13. What Article 6 lawful basis is proposed, and who approved the reasoning?
14. What Article 9 condition is proposed for processing health data?
15. What privacy information will patients receive, and at what point?
16. How can a patient ask questions, exercise applicable data protection rights, or challenge an incorrect record or prioritisation?
17. Is any decision solely automated and producing legal or similarly significant effects? If so, what specialist review is planned under GDPR Article 22 and related requirements?

### D. Supplier and technology
18. Who supplies and operates the AI model and hosting service?
19. Will the supplier act as a processor, an independent controller, or in another role for any processing activity?
20. Will prompts, patient submissions or outputs be retained or used to train or improve a model?
21. Which subprocessors are involved, and where are they located?
22. What contractual terms cover instructions, confidentiality, security, deletion, audits, incident notification and international transfers?
23. What testing evidence exists for accuracy, bias, robustness and performance across relevant patient groups?

### E. Security and operational governance
24. What access controls, authentication, encryption, logging and monitoring are planned?
25. How will staff be trained to understand limitations and avoid over-reliance on AI outputs?
26. Who monitors errors, complaints, incidents, drift and unexpected outcomes?
27. What is the process for suspending the system if a serious risk or failure is identified?
28. Who approves launch, accepts residual risks, and authorises material changes?

## 6. Initial information request

Request the following documents or evidence before finalising the assessment:

| Requested item | Why it is needed |
|---|---|
| Product description and intended-purpose statement | Establish what the system is designed to do |
| Current and proposed process map | Understand where AI enters the patient workflow |
| Data inventory and sample data fields (synthetic only) | Identify personal and health data and assess minimisation |
| System architecture and data-flow diagram | Identify systems, storage locations, interfaces and transfers |
| Vendor privacy notice, DPA and relevant contract schedules | Review roles, instructions, subprocessors and commitments |
| Retention and deletion schedule | Test whether retention is justified and operationally achievable |
| Draft patient privacy notice | Review transparency and communication |
| Security design and access model | Review proposed technical and organisational safeguards |
| Model testing, validation and known limitations | Understand performance, bias and failure modes |
| Clinical escalation and human-review procedure | Understand how unsafe or uncertain outputs are handled |
| Incident response and complaints process | Confirm escalation and response arrangements |
| Existing risk assessments and relevant policies | Avoid duplication and identify gaps |

Evidence should be requested through an approved secure channel. Real patient data is not required for this portfolio exercise.

## 7. Preliminary privacy and governance considerations

| Topic | Initial concern | Evidence or decision required |
|---|---|---|
| Purpose limitation | The system may be used beyond its original intended purpose | Approved intended-purpose statement and change-control process |
| Data minimisation | Free-text submissions may contain unnecessary details | Field inventory, necessity rationale and minimisation design |
| Lawful processing | Health data requires both an Article 6 basis and an applicable Article 9 condition | Documented analysis reviewed by the appropriate accountable parties |
| Transparency | Patients may not understand the role of AI | Draft privacy notice and patient-facing explanation |
| Accuracy and fairness | Errors or bias could affect priority for care | Validation evidence, subgroup testing and monitoring plan |
| Human oversight | Staff may over-rely on automated suggestions | Documented review, override, escalation and training process |
| Supplier governance | Patient data may be retained or reused by a vendor | Contract review, data-use restrictions and subprocessor information |
| Security and retention | Sensitive data may be exposed or kept too long | Access design, logs, incident process and retention/deletion rules |
| Accountability | Ownership of launch and residual risks may be unclear | Named decision owners, action tracker and approval record |

## 8. DPIA screening — preliminary position

A DPIA is required under GDPR Article 35 where a type of processing is likely to result in a high risk to individuals' rights and freedoms, taking account of the nature, scope, context and purposes of the processing. The precise conclusion depends on the facts.

This scenario involves proposed processing of health data and AI-assisted prioritisation that could influence access to clinical review. These features warrant a careful DPIA screening and strong consideration of a full DPIA before processing begins. The final decision should be documented after discovery and checked against current DPC/EDPB guidance and the actual system design.

If a DPIA identifies a high residual risk that cannot be sufficiently mitigated, the controller should assess whether prior consultation with the supervisory authority is required under Article 36 before proceeding.

## 9. Initial engagement risks and dependencies

- **Incomplete system facts:** the model, workflow or data flows may change. Mitigation: validate assumptions with product, IT, clinical and vendor stakeholders.
- **Unclear decision ownership:** privacy and clinical risks may not have accountable owners. Mitigation: agree named owners and an escalation route.
- **Vendor opacity:** insufficient information about training, retention or subprocessors may prevent a reliable assessment. Mitigation: make vendor evidence a project dependency.
- **Clinical safety concerns:** AI errors may affect patients. Mitigation: involve qualified clinical leadership; do not treat a privacy review as clinical validation.
- **Legal uncertainty:** lawful basis, Article 9 condition, Article 22 and AI Act applicability depend on facts. Mitigation: document the analysis and obtain DPO/legal/specialist review where appropriate.

## 10. Recommended next steps

| Priority | Action | Suggested owner | Evidence of completion |
|---|---|---|---|
| 1 | Confirm intended purpose, users and clinical workflow | Product owner + clinical lead | Approved use-case statement and process map |
| 2 | Complete data inventory and data-flow mapping | Product owner + IT | Data inventory and diagram |
| 3 | Obtain vendor documentation and contract terms | Procurement + legal | Vendor evidence pack |
| 4 | Confirm controller/processor roles and proposed data uses | Privacy lead / DPO + legal | Documented role analysis |
| 5 | Complete DPIA screening and record rationale | Controller with DPO advice, where applicable | Signed-off screening record |
| 6 | Analyse Article 6 basis and Article 9 condition | Privacy lead / DPO + legal | Documented lawful-basis assessment |
| 7 | Assess AI governance and applicable regulatory requirements | AI owner + legal/specialist adviser | Applicability assessment and action log |
| 8 | Develop detailed risk register and safeguards | Project team | Risk register with owners and residual risk |
| 9 | Review unresolved high risks before any launch decision | Accountable management + clinical lead | Recorded decision and conditions |

Target dates should be agreed with the fictional client during planning; none are invented in this draft.

## 11. Provisional conclusion

The proposal should not move directly to deployment on the basis of the current limited information. The immediate priority is to confirm the intended purpose, patient workflow, data flows, vendor arrangements, lawful processing rationale and human clinical oversight.

A DPIA screening should be documented promptly, with a full DPIA developed before processing begins if required. Any unresolved high risks, clinical safety concerns or legal uncertainties should be escalated to the appropriate accountable decision-makers. Privacy safeguards alone cannot establish that the system is clinically safe or legally ready for launch.

## 12. Reference points

- GDPR text, including Articles 5, 6, 9, 13–14, 22, 25, 32, 35 and 36: https://eur-lex.europa.eu/eli/reg/2016/679/oj
- Irish Data Protection Commission DPIA guidance: https://www.dataprotection.ie/en/organisations/know-your-obligations/data-protection-impact-assessments
- European Data Protection Board: https://www.edpb.europa.eu/
- EU AI Act official text and implementation information: https://eur-lex.europa.eu/ and https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai

**Document status:** Draft scoping deliverable for a fictional portfolio exercise. Update it as assumptions are validated; do not present it as a completed legal assessment.
