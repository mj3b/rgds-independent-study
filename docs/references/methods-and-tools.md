# Supplementary Materials and Technical Notes

---

## Purpose

This page documents the research workflow, tooling, and validation practices underlying the RGDS framework. It is intended for readers who wish to audit the methods more closely, evaluate the robustness of the work beyond the main narrative, or understand how AI-assisted tools were used and governed throughout the project.

The main [Acknowledgements](acknowledgements.md/) page provides a summary of intellectual influences and a brief AI disclosure. This page provides the operational detail.

---

## Research Workflow

### Literature Search and Source Selection

The evidence base for this project was assembled through a structured, multi-pass research process conducted between November 2025 and January 2026:

1. **Regulatory primary sources.** FDA guidance documents, Federal Register notices, ICH guidelines, EMA and WHO publications, and PDUFA reauthorization materials were identified through direct agency searches and regulatory intelligence platforms.
2. **Academic and industry literature.** Published analyses from Tufts CSDD, Duke-Margolis, McKinsey, Deloitte, Lumanity, Analysis Group, and professional societies (RAPS, FDLI, ISPE) were located through web-based deep research, cross-referencing citation chains, and reviewing bibliographies of foundational sources.
3. **Domain-specific research.** Focused searches were conducted on AI in clinical trials, AI in software as a medical device (SaMD), AI readiness assessment frameworks, eCTD standards, and regulatory science policy trajectories.
4. **Source selection criteria.** Sources were included based on institutional authority, recency, direct relevance to decision governance or regulatory science, and verifiability. Blog posts, opinion pieces, and unverified industry commentary were excluded unless corroborated by primary sources.

The final bibliography comprises 96 entries, each confirmed for accuracy, accessibility, and direct source verification.

### Citation Management

All inline citations use the format `[\[N\]](bibliography.md#citeN)` and link directly to the [Bibliography](bibliography.md/) page. Citations were audited in multiple passes to ensure that high-risk claims (financial projections, regulatory statistics, FDA deficiency rates) were traceable to primary or authoritative secondary sources. Where the framework extends or reinterprets an existing model—for example, adapting FDA's seven-step credibility framework—the extension is noted and the original source is cited.

---

## AI-Assisted Research and Development Tools

This project used AI-enabled tools across four functional areas: literature discovery and synthesis, framework development, schema and code generation, and documentation. The tools, their roles, and the boundaries of their use are described below.

### Claude (Anthropic)

- **Role:** Primary tool for framework development, iterative refinement, documentation authoring, and technical architecture
- **Period:** November 2025 – January 2026
- **Scope of use:**
    - Evolved RGDS from v1.0 through v1.4, including articulation of the non-agentic AI governance principle
    - Drafted and iterated the `decision-log.schema.json` with semantic invariants; produced example decision logs (RGDS-DEC-0001 through RGDS-DEC-0006) aligned to the schema
    - Generated submission-style research write-ups; conducted multi-pass formatting normalization for MkDocs rendering
    - Implemented and validated clickable bracket citations; conducted citation audit passes for high-risk claims
    - Supported technical architecture diagrams and documentation of framework application in regulated biopharma contexts
    - Assisted with MkDocs and GitHub Pages configuration, repository packaging, and license notice preparation

### Perplexity AI (Deep Research Mode)

- **Role:** Comprehensive literature synthesis and regulatory intelligence
- **Period:** November 2025 – January 2026
- **Scope of use:**
    - Deep research on FDA guidance documents, international regulatory frameworks (WHO, EMA, ICH), and emerging policy trajectories
    - Synthesis of biopharmaceutical industry trends, portfolio management methodologies, and competitive positioning from consulting firms and academic institutions
    - Literature review of decision frameworks, AI governance standards, and change management research
    - Citation discovery and bibliography building: identified and verified authoritative sources across 96 entries
    - Research on MkDocs best practices, open-source licensing requirements (MIT, Apache 2.0, BSD-2-Clause), and documentation attribution standards
    - Domain-specific research on AI in clinical trials, SaMD governance, and AI readiness assessment frameworks

### ChatGPT (OpenAI)

- **Role:** Schema prototyping, code generation, documentation drafting, and conceptual brainstorming
- **Period:** December 2025 – January 2026
- **Scope of use:**
    - Initial JSON schema structures for decision logs and governance covenants, subsequently validated and refined against regulatory scenarios
    - Python implementation examples for RGDS framework usage and schema validation workflows
    - Documentation drafting and technical writing assistance
    - Brainstorming organizational structures for complex regulatory concepts; identifying edge cases and potential user confusion points
    - Grammar and terminology refinement for regulatory and governance content

---

## Human Oversight and Validation

All AI-generated output was treated as draft material subject to critical human review. The following validation procedures were applied throughout the project:

- **Regulatory citations** were verified against original FDA guidance documents, Federal Register entries, and agency source pages.
- **Industry analyses** were cross-checked with primary publications from consulting firms, academic institutions, and professional organizations.
- **Technical implementations** (JSON schemas, code examples, validation pipelines) were tested against real-world use cases and iterated based on results.
- **Financial calculations** in [Appendix A](appendix-a.md/) were verified using established portfolio NPV and probability-of-success methodologies.
- **All 96 bibliography entries** were confirmed for accuracy, accessibility, and direct source linkage.
- **Framework positioning** was validated against regulatory precedent, published industry standards, and inspection-readiness expectations.
- **Documentation structure and citation integrity** were audited across multiple passes for internal consistency.

AI tools were not listed as authors or co-authors. The author assumes sole responsibility for the selection, interpretation, integration, and accuracy of all content.

---

## Technical Artifacts

### Decision Log Schema

The RGDS decision log schema (`decision-log.schema.json`) enforces structured documentation of phase-gate decisions through required fields including decision question, options considered, evidence base with completeness classification, risk posture, residual risk and contingency, conditions, and approvers. Schema validation is enforced via CI/CD pipeline (GitHub Actions) before any decision log can be merged to the repository.

Example decision logs (RGDS-DEC-0001 through RGDS-DEC-0006) are provided as canonical references illustrating Data Readiness Gates, Risk Assessment decisions, Manufacturing Strategy decisions, and Study Go/No-Go decisions.

### Governance Covenant

The governance covenant template defines organizational commitments for RGDS adoption, including decision categories requiring logs, authoring workflows, approval chains, and schema compliance expectations.

### Repository Structure

- **[RGDS Core Framework](https://github.com/mj3b/rgds)** — Decision log schemas, governance covenants, canonical examples, and validation pipeline
- **[RGDS AI Governance](https://github.com/mj3b/rgds-ai-governance)** — Governance boundaries and non-agentic AI constraints for regulated decision support

Both repositories are licensed under the Apache License 2.0.

---

## Documentation Infrastructure

### Site Generation

This documentation site is built with the following open-source tools:

| Tool | License | Copyright | Purpose |
|------|---------|-----------|---------|
| [MkDocs](https://www.mkdocs.org/) | BSD-2-Clause | © 2014, Tom Christie | Static site generation |
| [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) | MIT | © 2016–2026, Martin Donath | Theme and navigation |

Complete license texts are available in the [THIRD_PARTY_LICENSES](https://github.com/mj3b/rgds-reference/blob/main/THIRD_PARTY_LICENSES) file.

### Version Control and CI/CD

Decision logs and documentation are managed in Git with version-controlled commits. GitHub Actions validates all decision logs against the JSON schema before merge, ensuring that required fields (decision question, options, evidence, risk posture, conditions, approvers) cannot be omitted.

---

## Reproducibility

Readers wishing to reproduce or extend this work can:

1. Clone the RGDS repositories and review the schema, example logs, and governance covenant templates.
2. Use the bibliography (entries 1–96) to trace every cited claim to its original source.
3. Review this page to understand how AI tools were used and how their outputs were validated.
4. Consult [Appendix A](appendix-a.md/) for financial analysis methodology and ROI modeling assumptions.

The goal is to make the project fully interrogable: any claim, design choice, or analytic conclusion should be traceable to its evidence, and any reader should be able to form an independent judgment about the strength of that evidence.
