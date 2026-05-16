# Contributing to RGDS

This repository documents an independent research framework, not a software product. Contributions are welcome in the forms described below.

---

## What This Project Accepts

**Evidence corrections and source additions.** If a cited claim is incorrect, a source is inaccessible, or a stronger source exists, open an issue with the citation number, the current claim, and the proposed correction with a verifiable link. High-risk evidentiary claims (financial projections, FDA deficiency rates, clinical hold statistics) receive particular scrutiny and benefit from stronger sourcing.

**Regulatory updates.** FDA guidance, ICH harmonization, and EMA policy evolve. If a Q9 or Q10 finding is superseded by new agency action, open an issue with the agency document title, publication date, and the specific finding it affects.

**Implementation experience.** If you have deployed a decision governance framework in an IND program and the implementation findings diverge materially from Q8 projections (cycle times, adoption rates, overhead estimates), a documented case note is valuable. Anonymized organizational data is acceptable.

**Framework extensions.** RGDS as described covers phase-gated drug development. If you are adapting the decision log schema or governance covenant for device submissions (SaMD), combination products, or biologics with distinct regulatory pathways, an issue describing the adaptation is a useful contribution to the record.

---

## What This Project Does Not Accept

- Changes that weaken or remove existing citations without stronger replacements
- Additions that are not traceable to verifiable primary or authoritative secondary sources
- Promotional content, vendor references, or product recommendations
- Changes to the framework's core non-agentic AI governance principle without substantial regulatory precedent

---

## How to Contribute

1. Open an issue before submitting a pull request. Describe the problem, the proposed change, and the source that supports it.
2. For documentation edits, target the relevant Markdown file in `docs/`. Follow the existing heading structure and citation format (`[[N]](../../references/bibliography/#citeN)`).
3. For bibliography additions, add the entry to `docs/references/bibliography.md` with an `<a id="citeNN"></a>` anchor, following the existing Tier 1 / Tier 2 structure.
4. Pull requests that change evidentiary claims require a direct link to the source in the PR description.

---

## Citation Format

Inline citations use:

```markdown
[[N]](../../references/bibliography/#citeN)
```

where `N` is the bibliography entry number. New additions take the next available number and must include an interpretive note in `appendix-a.md` following the existing format.

---

## Code of Conduct

This is a research repository. Engagement should be factual, traceable, and professional. Disputes about evidence are resolved by reference to primary sources, not assertion.

---

## Contact

For questions about the framework, collaboration proposals, or implementation partnerships, contact Mark Julius Banasihan at [markjuliusbanasihan@gmail.com](mailto:markjuliusbanasihan@gmail.com).
