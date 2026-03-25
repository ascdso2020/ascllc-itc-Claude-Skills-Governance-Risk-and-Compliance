# ISO/IEC 42001:2023 — Annex A Controls (All 38)

ISO/IEC 42001:2023 Annex A contains **38 controls** organised across **9 control domains** (A.2–A.10). Annex B provides implementation guidance for each control.

> **How to use:** Controls are selected based on organisational role (provider, user, or both), AI system impact level, and risk assessment outcomes. Inapplicable controls must be justified in the Statement of Applicability (SoA).

---

## A.2 — Policies Related to AI (2 controls)

| Control ID | Control Name | Applies To | Description |
|-----------|-------------|-----------|-------------|
| A.2.1 | AI policy | Provider + User | A formal AI policy must be established, documented, and communicated. Must include: commitment to responsible AI, alignment with organisational values, compliance obligations, and objectives. Signed by top management. |
| A.2.2 | AI-specific controls in organisational policies | Provider + User | Existing organisational policies (HR, procurement, IT, data) must be reviewed and updated to include AI-specific requirements where relevant. |

**Common gaps:** AI policy exists but lacks specific responsible AI commitments; other policies not updated.

---

## A.3 — Internal Organisation (1 control)

| Control ID | Control Name | Applies To | Description |
|-----------|-------------|-----------|-------------|
| A.3.1 | Roles and responsibilities related to AI | Provider + User | Roles accountable for AI governance must be defined: AI owner, AI risk owner, data governance lead, AI ethics function (where applicable). RACI matrix or equivalent required. |

**Common gaps:** AI ownership informal or split across IT/data science without clear accountability.

---

## A.4 — Resources for AI Systems (4 controls)

| Control ID | Control Name | Applies To | Description |
|-----------|-------------|-----------|-------------|
| A.4.1 | Policies for AI system resources | Provider | Policies governing compute resources, infrastructure, and tooling used for AI development and deployment. Covers provisioning, access, and decommissioning. |
| A.4.2 | Human resource policies related to AI | Provider + User | AI-specific competency requirements documented; training programmes for AI developers, operators, and business users; awareness programme for all staff interacting with AI. |
| A.4.3 | Procurement policies for AI | Provider + User | Procurement process for AI tools, APIs, and services — includes vendor due diligence, contractual requirements, and AI-specific risk assessment for third-party AI. |
| A.4.4 | Third-party AI capabilities | User (primarily) | Governance of AI capabilities sourced from external providers — includes API risk, model provenance, SLA for AI outputs, data handling by provider, right to audit. |

**Common gaps:** No AI-specific procurement checklist; staff AI awareness training missing; third-party AI tools not inventoried.

---

## A.5 — AI System Lifecycle (8 controls)

| Control ID | Control Name | Applies To | Description |
|-----------|-------------|-----------|-------------|
| A.5.1 | AI system specifications | Provider | Documented specifications for each AI system: intended purpose, inputs/outputs, performance criteria, operating conditions, stakeholders. Baseline for impact and risk assessment. |
| A.5.2 | AI system design | Provider | Design process controls: fairness considerations in model architecture, documentation of design decisions, explainability requirements tied to impact level. |
| A.5.3 | Data management for AI systems | Provider | Controls across the full data lifecycle used in AI: acquisition, quality assessment, labelling, versioning, bias testing, retention, and deletion. |
| A.5.4 | AI system development | Provider | Secure development practices for AI: version control of models and training code, reproducibility, documentation of model versions and hyperparameters. |
| A.5.5 | AI system verification and validation | Provider | Testing protocols before deployment: performance benchmarks, fairness/bias testing across demographic groups, adversarial testing, edge case validation. |
| A.5.6 | AI system documentation | Provider + User | Comprehensive documentation per AI system: technical specifications, intended use, limitations, performance data, known failure modes. Supports transparency obligations. |
| A.5.7 | AI system deployment | Provider | Controlled deployment process: staged rollout, deployment authorisation, go/no-go criteria based on risk/impact assessment, rollback procedure. |
| A.5.8 | AI system operation and monitoring | Provider + User | Continuous monitoring of AI system in production: performance drift detection, output quality monitoring, bias monitoring, alert thresholds, remediation process. |

**Common gaps:** No model versioning; bias testing not documented; no production monitoring for drift.

---

## A.6 — AI System Impact Assessment (3 controls)

| Control ID | Control Name | Applies To | Description |
|-----------|-------------|-----------|-------------|
| A.6.1 | Processes for assessing impact of AI systems | Provider + User | Formal AISIA process documented and executed for each in-scope AI system. Must consider: affected individuals, societal impact, reversibility of harm, vulnerable populations. |
| A.6.2 | Assessing impacts on individuals | Provider + User | Assessment of how AI outputs may affect individual rights, wellbeing, and autonomy. Includes discrimination risk, profiling, automated decision-making without meaningful human review. |
| A.6.3 | Determining and assessing societal concerns | Provider + User | Broader societal impact: misinformation generation, labour displacement, environmental impact of AI compute, reinforcement of systemic bias at scale. |

**Common gaps:** AISIA done once at deployment but not repeated when AI system changes; societal dimension often skipped.

---

## A.7 — Data for AI Systems (4 controls)

| Control ID | Control Name | Applies To | Description |
|-----------|-------------|-----------|-------------|
| A.7.1 | Data management for AI | Provider | Governance framework for all data used in AI — covers data quality standards, data cataloguing, metadata management, and lineage tracking. |
| A.7.2 | Data acquisition for AI | Provider | Controls on how training and test data is sourced: legal basis for data use, consent where required, provenance documentation, prohibition on using unlawfully obtained data. |
| A.7.3 | Data quality for AI | Provider | Quality criteria defined for training, validation, and test data: completeness, accuracy, representativeness, recency. Testing against criteria before use. |
| A.7.4 | Data preparation for AI | Provider | Processes for data cleaning, transformation, labelling, and annotation: quality controls on annotation, human review of labelled data, bias identification in preparation steps. |

**Common gaps:** Training data sourcing undocumented; no data quality checks; labelling process not auditable.

---

## A.8 — Information for Interested Parties (3 controls)

| Control ID | Control Name | Applies To | Description |
|-----------|-------------|-----------|-------------|
| A.8.1 | Transparency of AI systems | Provider + User | Disclosures proportionate to AI impact level: inform affected individuals that AI is being used, what it does, and what rights they have. Higher-impact systems require more disclosure. |
| A.8.2 | Communication of responsibilities to stakeholders | Provider + User | Stakeholders (customers, employees, regulators, public) must understand their roles and what to expect from AI systems. Communication plan required. |
| A.8.3 | Reporting on AI incidents | Provider + User | AI-specific incident reporting: internal escalation, notification to affected individuals where required, regulatory reporting (e.g., EU AI Act notification obligations), post-incident review. |

**Common gaps:** No disclosure to users that AI is being used in decision-making; incident reporting not AI-specific.

---

## A.9 — Use of AI by Third Parties (7 controls)

| Control ID | Control Name | Applies To | Description |
|-----------|-------------|-----------|-------------|
| A.9.1 | Policy for use of AI by third parties | Provider + User | Overarching policy for engaging third parties that use or provide AI: due diligence requirements, minimum standards, prohibited uses by third parties. |
| A.9.2 | Supply chain relationships | Provider + User | AI supply chain risk management: tiering of AI suppliers by risk, assessment questionnaires, contractual AI-specific clauses, right to audit. |
| A.9.3 | Sharing of AI system data | Provider | Controls on sharing AI training data, model outputs, or model artefacts with third parties: data sharing agreements, anonymisation requirements, export controls. |
| A.9.4 | Interactions between AI systems | Provider | Governance of AI-to-AI interactions: multi-agent systems, AI pipeline dependencies, automated AI decisions feeding other AI systems — assess cascading risk. |
| A.9.5 | Use of AI system by external entities | Provider | Controls when external parties (customers, partners) interact with or use the organisation's AI systems: terms of use, prohibited use cases, monitoring of use patterns. |
| A.9.6 | Procurement of AI components | Provider | Procurement process specifically for AI model components, pre-trained models, datasets: provenance checks, licence review, model cards review. |
| A.9.7 | Use of publicly available AI systems | User | Governance of staff use of public AI tools (ChatGPT, Copilot, etc.): acceptable use policy, data classification rules (what can/cannot be entered), review cycle. |

**Common gaps:** No AI-specific supplier questionnaire; staff using public AI tools without policy; no contractual AI clauses with key AI vendors.

---

## A.10 — AI System Decommission (6 controls)

| Control ID | Control Name | Applies To | Description |
|-----------|-------------|-----------|-------------|
| A.10.1 | AI system decommissioning policy | Provider | Formal decommissioning process: trigger criteria, stakeholder notification, data deletion/archival, model retirement documentation. |
| A.10.2 | Retention and disposal of AI system data | Provider | Data retention schedule for AI: training data, model artefacts, logs, evaluation records. Secure disposal processes aligned to data protection requirements. |
| A.10.3 | Model deprecation | Provider | Process for retiring AI models: communication to AI users, migration path to successor model, documentation of deprecated model behaviour for audit trail. |
| A.10.4 | Reuse of data and models | Provider | Controls on reuse of training data or models across different AI systems or purposes: re-assessment of AISIA and data rights when purpose changes. |
| A.10.5 | Archiving of AI systems | Provider | Archival of AI system artefacts for audit and legal purposes: what to archive (model weights, training scripts, evaluation records), retention period, access controls. |
| A.10.6 | Responsible AI system disposal | Provider | Environmental and societal responsibility in disposal: energy-efficient decommission, consideration of societal impact of removing AI system (e.g., AI providing accessibility features). |

**Common gaps:** No decommission policy; training data not securely deleted when systems retired; model artefacts not archived.

---

## Summary: Controls by Organisational Role

| Domain | AI Provider | AI User |
|--------|------------|---------|
| A.2 Policies | Both | Both |
| A.3 Organisation | Both | Both |
| A.4 Resources | Primary | Partial (A.4.2, A.4.3, A.4.4) |
| A.5 Lifecycle | Primary | A.5.6, A.5.8 |
| A.6 Impact Assessment | Both | Both |
| A.7 Data | Primary | Limited |
| A.8 Transparency | Both | Both |
| A.9 Third Parties | Both | Both (especially A.9.2, A.9.7) |
| A.10 Decommission | Primary | Limited |

**Total: 38 controls** — organisations select applicable controls based on role and risk; exclusions must be documented in the SoA.
