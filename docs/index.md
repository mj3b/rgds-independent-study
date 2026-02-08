# RGDS: Decision-Centric AI Governance in Biopharma/Biotech Development

## Research Challenges and Opportunities

### Regulatory Status (January 2026)

Note: Several tables are intentionally wide to preserve detail. On smaller screens, use horizontal scrolling to view all columns.

| Status | Detail |
|---|---|
| Required Now | FDA 2025 guidance requires AI credibility documentation for AI-assisted submissions |
| Current Baseline | Decision governance and decision documentation remain voluntary in most programs today |
| Predicted Trend | RGDS anticipates FDA may mandate decision documentation by 2027–2030 based on regulatory trajectory and international harmonization *(See Q10: Regulatory Evolution Framework)* |
| Early Adopter Advantage | Implementing RGDS now positions organizations ahead of potential future regulatory expectations and delivers operational benefits |

**PORTFOLIO RESEARCH PROJECT**

This documentation was created as an independent research initiative during my job search to demonstrate regulatory affairs and AI governance expertise. It represents independent work and is unaffiliated with any employer.

---

## Contents

- [Foreword by Mark Julius Banasihan](#foreword-by-mark-julius-banasihan)
- [Preface](#preface)
- [Introduction to RGDS](#introduction-to-rgds)
- [RGDS Research Questions](#rgds-research-questions)

- [1. How can biopharma/biotech organizations reconstruct decision logic when FDA requests justification months or years after decisions were made?](#1-how-can-biopharmabiotech-organizations-reconstruct-decision-logic-when-fda-requests-justification-months-or-years-after-decisions-were-made)
- [2. How can AI-assisted regulatory processes preserve human accountability while leveraging AI's efficiency gains?](#2-how-can-ai-assisted-regulatory-processes-preserve-human-accountability-while-leveraging-ais-efficiency-gains)
- [3. How can decision governance frameworks integrate with existing biopharma/biotech project management practices without adding bureaucratic overhead?](#3-how-can-decision-governance-frameworks-integrate-with-existing-biopharmabiotech-project-management-practices-without-adding-bureaucratic-overhead)
- [4. How can schema-validated decision logs reduce FDA deficiency rates and clinical hold risks?](#4-how-can-schema-validated-decision-logs-reduce-fda-deficiency-rates-and-clinical-hold-risks)
- [5. How can decision cycle time be compressed while maintaining decision quality and regulatory defensibility?](#5-how-can-decision-cycle-time-be-compressed-while-maintaining-decision-quality-and-regulatory-defensibility)
- [6. How will decision governance reshape regulatory interactions, investor due diligence, and board governance in biopharma/biotech development?](#6-how-will-decision-governance-reshape-regulatory-interactions-investor-due-diligence-and-board-governance-in-biopharmabiotech-development)
- [7. How can organizations measure the ROI of decision governance infrastructure across portfolio-level timelines and outcomes?](#7-how-can-organizations-measure-the-roi-of-decision-governance-infrastructure-across-portfolio-level-timelines-and-outcomes)
- [8. How should implementation roadmaps balance pilot validation, organizational integration, and thought leadership positioning?](#8-how-should-implementation-roadmaps-balance-pilot-validation-organizational-integration-and-thought-leadership-positioning)
- [9. How can AI governance disclosure frameworks satisfy evolving FDA expectations for transparency in algorithmic decision-making?](#9-how-can-ai-governance-disclosure-frameworks-satisfy-evolving-fda-expectations-for-transparency-in-algorithmic-decision-making)
- [10. How should regulatory frameworks evolve to mandate or incentivize decision documentation as standard practice in biopharma/biotech submissions?](#10-how-should-regulatory-frameworks-evolve-to-mandate-or-incentivize-decision-documentation-as-standard-practice-in-biopharmabiotech-submissions)

- [About the Author](references/about-the-author/)
- [Acknowledgements](references/acknowledgements/)
- [Appendix A](references/appendix-a/)
- [Bibliography](references/bibliography/)

---

## Foreword by Mark Julius Banasihan

This work examines a problem that recurs across regulated biopharma and biotechnology development, regardless of company size, therapeutic area, or operating model: **organizations struggle to reconstruct and defend critical decisions when regulators ask for justification months or years later**.

In my work observing and analyzing regulated development programs, I have repeatedly seen that regulatory setbacks often stem less from missing science than from missing decision logic. FDA questions frequently focus on *why* a sponsor proceeded with incomplete data, deferred specific studies, or accepted defined risks. The underlying evidence usually exists, yet the reasoning that connected evidence to action is fragmented across email threads, meeting notes, slide decks, and individual memory.

When those decisions must be reconstructed under regulatory pressure, organizations enter a costly forensic exercise. Teams spend weeks aligning on narratives that should have been captured at the moment the decision was made. The result is delay, inconsistency, and erosion of regulatory confidence.

At the same time, regulated development is undergoing a second structural shift: the rapid integration of **AI-assisted tools** into regulatory, clinical, and CMC workflows. Medical writing automation, regulatory intelligence platforms, and predictive analytics now compress timelines dramatically. These tools introduce efficiency gains that are both real and necessary. They also introduce a new governance challenge: **how to preserve clear human accountability when AI contributes to regulatory-relevant work**.

Regulatory guidance issued in 2025 makes explicit what was previously implicit: when AI assists regulatory processes, sponsors must be able to explain who reviewed the output, what was accepted or rejected, how confidence was assessed, and where human judgment was applied. Many organizations currently lack a systematic way to answer those questions.

This research proceeds from a simple but demanding premise:

**Decisions—rather than documents—are the primary artifacts that require governance in regulated systems.**

Regulated Gate Decision Support (RGDS) is presented here as an independent research case study exploring how structured, schema-validated decision logs can address both decision reconstructability failures and AI accountability gaps without introducing bureaucratic overhead. The work focuses on how decisions can be documented contemporaneously, linked to evidence, articulated in terms of risk posture, and preserved in a form that is auditable, explainable, and regulator-ready.

The ten research questions that structure this paper reflect recurring challenges observed across regulated development programs: reconstructability under inspection, AI disclosure, cross-functional alignment, decision cycle compression, ROI justification, and the likely evolution of regulatory expectations. The goal is to surface a governance pattern that can be scrutinized, tested, and adapted.

This paper is intended for readers who operate in environments where decisions carry regulatory consequence: regulatory affairs professionals, clinical and CMC leaders, medical writers, project managers, quality and governance specialists, and researchers examining decision-making in high-stakes systems.

This work is an **independent, non-commercial research case study and reference framework** with no sponsor, commission, or endorsement from any organization.

---

## Preface

The period from 2022 through 2025 marked a structural inflection point in regulated biopharma and biotechnology development. Advances in AI capability dramatically expanded what could be automated in regulatory, clinical, and manufacturing workflows. Tasks that once required months of coordinated human effort—drafting nonclinical summaries, scanning regulatory precedent, reconciling clinical datasets, predicting manufacturing outcomes—could now be completed in days or hours.

These gains exposed a latent weakness in existing governance practices. Traditional quality control and documentation models were designed for human-authored work products. They did not translate cleanly to AI-assisted outputs, nor did they provide a reliable way to document how human judgment was exercised when AI contributed to regulatory-relevant decisions.

At the same time, longstanding challenges in decision governance became more visible. Project management artifacts such as RACI matrices, critical path analyses, and status reporting proved effective at coordination, yet they failed to preserve the reasoning behind major phase-gate decisions. When regulators asked why a decision was made, organizations could produce evidence but struggled to produce decision rationale.

RGDS emerged from sustained analysis of these overlapping pressures. Rather than introducing another layer of process, the research asks whether a single, well-defined decision record—validated by schema, linked to evidence, and governed by named human accountability—can replace fragmented documentation practices and close reconstructability gaps.

This paper documents that inquiry. It synthesizes observed patterns, pilot-scale case studies, regulatory guidance, and interdisciplinary discussion into a set of research questions intended to advance understanding of decision governance in regulated systems.

The framing is deliberately conservative. Claims are bounded. Where evidence is strong, it is stated. Where uncertainty remains, it is acknowledged. Governance is treated as an enabler of defensibility and efficiency, rather than a substitute for scientific quality or sound regulatory strategy.

The work that follows is offered as a reference point for further examination, critique, and refinement.

---

## Introduction to RGDS

Our biopharma/biotech development landscape is undergoing a profound evolution driven by two converging forces:

**Force 1: FDA's Increasing Expectations for Decision Transparency**

FDA Complete Response Letters cite "insufficient information" in **50% of first-cycle submissions**—often because FDA reviewers cannot reconstruct the **decision logic** behind critical choices [1](references/bibliography/#cite1) [2](references/bibliography/#cite2) [3](references/bibliography/#cite3). When FDA asks "Why did you proceed with incomplete CMC data?", "How did you determine acceptable risk for a hepatotoxicity signal?", or "What evidence supported your dose selection?", organizations struggle to provide coherent answers. The evidence exists—GLP toxicology reports, stability protocols, manufacturing characterization data—but the decisions connecting that evidence to strategic choices exist only in fragmented emails, meeting notes, and individual memory.

This **decision reconstructability crisis** costs biopharma/biotech organizations an average of **2–4 weeks per FDA question** during deficiency letter response cycles, **$300K–$500K per clinical hold** (8.9% baseline IND hold rate), and **6–12 months timeline extensions** when holds require substantive remediation [2](references/bibliography/#cite2) [3](references/bibliography/#cite3) [26](references/bibliography/#cite26). More critically, weak reconstructability erodes FDA trust: reviewers perceive organizations with poor reconstructability as governance-immature, increasing scrutiny on subsequent submissions [3](references/bibliography/#cite3) [24](references/bibliography/#cite24) [25](references/bibliography/#cite25).

**Force 2: Rapid Integration of AI-Driven Tools Without Accountability Frameworks**

The 2025 biopharma/biotech landscape increasingly leverages AI for regulatory processes:

- **Medical writing automation** (CoAuthor, Yseop, Multiplier AI): Generate Module 2.6 nonclinical summaries with **35–40% timeline compression** (180 hours → 80 hours) [4](references/bibliography/#cite4) [5](references/bibliography/#cite5) [6](references/bibliography/#cite6)
- **Regulatory intelligence** (IQVIA, Clarivate, IONI): Scan **200+ IND submissions** to identify precedent for unplanned study requirements in hours versus weeks [7](references/bibliography/#cite7) [8](references/bibliography/#cite8)
- **Predictive analytics** (digital twin simulations): Predict manufacturing yield and impurity with **92% accuracy**, enabling proactive CMC risk mitigation [9](references/bibliography/#cite9)
- **Clinical data integration** (Medidata, Quanticate): Reconcile discrepancies across EDC systems, lab data, and patient-reported outcomes automatically [27](references/bibliography/#cite27) [28](references/bibliography/#cite28)

However, frameworks remain underdeveloped for documenting:

- Who reviewed AI-generated output?
- What sections were rejected and rewritten by human experts?
- Where did AI over-interpret clinical significance?
- How was AI confidence assessed?
- What was the final human approval process?

FDA's January 2025 guidance on algorithmic decision-making requires documented human oversight of AI-assisted regulatory processes [10](references/bibliography/#cite10). Organizations using AI tools without governance structures face regulatory risk: FDA may question validity during inspection, request re-analysis with documented human review, or issue deficiency letters citing inadequate quality control [10](references/bibliography/#cite10) [11](references/bibliography/#cite11).

### The RGDS Solution

**RGDS (Regulated Gate Decision Support)** addresses both challenges by proposing a single unifying principle:

**Treat decisions—rather than documents—as primary artifacts requiring governance, documentation, and audit trails.**

Rather than documenting what was decided after the fact, RGDS uses contemporaneous decision logs at major phase gates that capture:

1. **Decision question** (explicitly stated)
2. **Options considered** (including alternatives rejected)
3. **Evidence base** (linked to source documents with completeness classification)
4. **Risk posture** (risk-accepting, risk-minimizing, or risk-neutral)
5. **Decision outcome** (go, no-go, conditional-go, defer)
6. **Conditions** (for conditional-go: what must be satisfied, by whom, by when)
7. **Residual risk** (risks remaining after the decision)
8. **AI assistance** (tool, confidence, human review process)
9. **Decision owner and approvers** (named individuals with accountability)

Each decision log is:

- **Schema-validated** (enforcing completeness via JSON Schema)
- **Evidence-linked** (connecting to source data with traceability)
- **Risk-articulated** (explicitly documenting risk posture)
- **Human-governed** (AI assistance disclosed; human accountability preserved)
- **Audit-ready** (retrievable quickly with complete context)

### Core RGDS Principles

RGDS is built on five foundational principles that ensure decision governance enhances rather than burdens biopharma/biotech development:

**Principle 1: Human-Governed Decision-Making**

Decisions remain with named humans with expertise and accountability. AI tools assist by accelerating evidence gathering, flagging risks, drafting summaries, analyzing precedent, and generating predictions—while humans approve the final outcome. This preserves regulatory credibility while leveraging efficiency gains [4](references/bibliography/#cite4) [5](references/bibliography/#cite5) [6](references/bibliography/#cite6) [10](references/bibliography/#cite10).

**Principle 2: Evidence-Linked**

Every decision log references source evidence (GLP tox reports, FDA guidance, regulatory precedent, stability protocols, manufacturing characterization data, stakeholder input). Evidence is classified as:

- **Complete:** Final validated data available (e.g., final GLP toxicology report received, QC-confirmed)
- **Partial:** Preliminary data available; final data pending
- **Placeholder:** Data absent; estimated or assumed

This makes data gaps explicit and reduces silent assumptions that later trigger FDA questions [3](references/bibliography/#cite3) [13](references/bibliography/#cite13) [24](references/bibliography/#cite24).

**Principle 3: Schema-Validated**

Decision logs are structured as JSON or YAML validated against a JSON Schema. Required fields cannot be omitted. Invalid logs trigger CI/CD validation failures, preventing acceptance of incomplete decision records [15](references/bibliography/#cite15) [18](references/bibliography/#cite18).

**Principle 4: Non-Agentic AI**

AI operates as an assistive system, never as the accountable decision owner. AI-generated content (drafts, summaries, precedent analyses, predictions) receives review and approval from human experts. Decision logs include `aiassistance` objects documenting:

- **Tool used**
- **Confidence level**
- **Human review process**
- **Human override rationale**

This structure aligns with FDA’s 2025 transparency expectations while preserving efficiency gains [4](references/bibliography/#cite4) [10](references/bibliography/#cite10) [11](references/bibliography/#cite11).

**Principle 5: Audit-Ready**

Decision logs are version-controlled in Git repositories, providing immutable audit trails. A decision can be retrieved quickly with complete context:

- What was decided?
- By whom?
- Based on what evidence?
- What risks were accepted?
- What conditions must be satisfied?

This reconstructability supports inspection readiness, board governance, and investor due diligence [3](references/bibliography/#cite3) [15](references/bibliography/#cite15) [24](references/bibliography/#cite24) [25](references/bibliography/#cite25).

### The RGDS Mission: Integrated, Enabling, Durable

To integrate decision governance into biopharma/biotech development, RGDS emphasizes three outcomes:

**Integrated:** Decision governance coexists with established workflows without adding friction. RGDS integrates with practices such as RACI, critical path methods, target product profiles, and multi-tier QA rather than replacing them.

**Enabling:** Decision governance strengthens organizational capability—accelerating decision cycles, reducing rework, improving regulatory outcomes, and strengthening investor confidence.

**Durable:** As regulatory expectations and AI tooling evolve, RGDS infrastructure adapts without destabilizing historical records. Schema-validated logs accommodate new fields (e.g., AI disclosure requirements) while preserving earlier logs [15](references/bibliography/#cite15) [18](references/bibliography/#cite18) [10](references/bibliography/#cite10).

### RGDS as Governance Backbone

RGDS complements operational execution platforms and project management tooling by providing a governance backbone one layer above execution:

**Layer 3 (Top): Business Outcomes**
- FDA acceptance
- Audit confidence (rapid decision reconstructability)
- Investor trust (transparent decision rationale)

**Layer 2 (Middle): RGDS Decision Governance**
- Decision log (schema-validated)
- Evidence completeness classification
- Risk posture articulation
- Conditions and contingency
- AI disclosure (tool, confidence, review, override)

**Layer 1 (Bottom): Operational Execution**
- CMC development
- Medical writing
- Regulatory strategy
- Document automation
- Analytics

**Combined value**
- **Speed:** AI compresses timelines operationally [4](references/bibliography/#cite4) [5](references/bibliography/#cite5) [6](references/bibliography/#cite6)
- **Quality:** Reduced deficiency cycles and rework [3](references/bibliography/#cite3) [26](references/bibliography/#cite26)
- **Defensibility:** Decisions remain reconstructable and inspection-ready [3](references/bibliography/#cite3) [24](references/bibliography/#cite24) [25](references/bibliography/#cite25)

---

## RGDS Research Questions

The 10 research questions below reflect recurring governance challenges observed across regulated development programs and stakeholder roles. They are intended as a research agenda and practical framing for decision governance design, evaluation, and adoption.

### The 10 RGDS Research Questions

Below are the ten research questions that structure this white paper.

---

### 1. How can biopharma/biotech organizations reconstruct decision logic when FDA requests justification months or years after decisions were made?

Addresses: **Decision reconstructability** (50% of FDA Complete Response Letters cite "insufficient information") [1](references/bibliography/#cite1) [2](references/bibliography/#cite2) [3](references/bibliography/#cite3)

---

### 2. How can AI-assisted regulatory processes preserve human accountability while leveraging AI's efficiency gains?

Addresses: **AI accountability** (FDA 2025 guidance requires documented human oversight) [10](references/bibliography/#cite10) [11](references/bibliography/#cite11)

---

### 3. How can decision governance frameworks integrate with existing biopharma/biotech project management practices without adding bureaucratic overhead?

Addresses: **Adoption and integration** (decision logs perceived as overhead despite cycle time compression) [13](references/bibliography/#cite13) [15](references/bibliography/#cite15)

---

### 4. How can schema-validated decision logs reduce FDA deficiency rates and clinical hold risks?

Addresses: **Risk reduction** (IND hold rate; remediation costs) [2](references/bibliography/#cite2) [3](references/bibliography/#cite3) [26](references/bibliography/#cite26)

---

### 5. How can decision cycle time be compressed while maintaining decision quality and regulatory defensibility?

Addresses: **Decision velocity** (explicit risk posture reduces recurring debate cycles) [13](references/bibliography/#cite13)

---

### 6. How will decision governance reshape regulatory interactions, investor due diligence, and board governance in biopharma/biotech development?

Addresses: **Strategic governance** (inspection readiness, due diligence reconstructability, governance maturity) [3](references/bibliography/#cite3) [24](references/bibliography/#cite24) [25](references/bibliography/#cite25)

---

### 7. How can organizations measure the ROI of decision governance infrastructure across portfolio-level timelines and outcomes?

Addresses: **ROI measurement** (portfolio-level value creation framing) [2](references/bibliography/#cite2) [3](references/bibliography/#cite3) [26](references/bibliography/#cite26)

---

### 8. How should implementation roadmaps balance pilot validation, organizational integration, and thought leadership positioning?

Addresses: **Implementation sequencing** [13](references/bibliography/#cite13) [25](references/bibliography/#cite25)

---

### 9. How can AI governance disclosure frameworks satisfy evolving FDA expectations for transparency in algorithmic decision-making?

Addresses: **Disclosure** (`aiassistance` schema pattern aligned to AI transparency expectations) [10](references/bibliography/#cite10) [11](references/bibliography/#cite11)

---

### 10. How should regulatory frameworks evolve to mandate or incentivize decision documentation as standard practice in biopharma/biotech submissions?

Addresses: **Regulatory evolution** (trajectory toward stronger decision documentation expectations) [10](references/bibliography/#cite10)

---

These ten questions guide the structure of this white paper. Each subsequent section explores one question in depth and presents:

- **The Challenge:** evidence of the problem (FDA data, benchmarks, case studies)
- **The RGDS Solution:** operational framework (schema design, workflow integration, outcomes)
- **Research Highlights:** examples and case patterns
- **Open Research Questions:** future directions
