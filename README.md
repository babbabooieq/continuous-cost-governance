# Continuous Cost Governance (CCG)

### Extending FinOps from Cost Optimization to Financial Accountability

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23555398.svg)](https://doi.org/10.5281/zenodo.23555398)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0004--0144--1497-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0004-0144-1497)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Version](https://img.shields.io/badge/Version-1.5.6-1B2A41.svg)](v1.5.6/Continuous%20Cost%20Governance%20Paper%20V1.5.6.pdf)

**Author:** Andy Surujnarine ([ORCID: 0009-0004-0144-1497](https://orcid.org/0009-0004-0144-1497))  
**Affiliation:** Founder, Compute LLC; Cloud Operations & Security Practitioner  
**Correspondence:** [https://surujnarine.net](https://surujnarine.net)  
**DOI:** [10.5281/zenodo.23555398](https://doi.org/10.5281/zenodo.23555398)  
**Status:** Working Paper for Industry Review (Version 1.5.6, September 2026)

---

> ### Continuous Cost Governance in One Sentence
> **FinOps determines what should be done with technology spend. Continuous Cost Governance establishes what was actually done, on whose authority, and what it verifiably delivered.**

---

## Download the Working Paper (Version 1.5.6)

- **[Download PDF (`Continuous Cost Governance Paper V1.5.6.pdf`)](v1.5.6/Continuous%20Cost%20Governance%20Paper%20V1.5.6.pdf)**
- **[Read Full Markdown (`Continuous Cost Governance Paper V1.5.6.md`)](v1.5.6/Continuous%20Cost%20Governance%20Paper%20V1.5.6.md)**
- **[Download Word Document (`Continuous Cost Governance Paper V1.5.6.docx`)](v1.5.6/Continuous%20Cost%20Governance%20Paper%20V1.5.6.docx)**

The DOI resolves to the permanent Zenodo record of Version 1.5.6.

## Versions

Both versions remain available in this repository.

| Version | Files | Git tag |
|---|---|---|
| **1.5.6** (current) | [PDF](v1.5.6/Continuous%20Cost%20Governance%20Paper%20V1.5.6.pdf) · [Markdown](v1.5.6/Continuous%20Cost%20Governance%20Paper%20V1.5.6.md) · [Word](v1.5.6/Continuous%20Cost%20Governance%20Paper%20V1.5.6.docx) (folder [`v1.5.6/`](v1.5.6)) | [`v1.5.6`](https://github.com/babbabooieq/continuous-cost-governance/tree/v1.5.6) |
| 1.4 | [PDF](Continuous%20Cost%20Governance%20Paper%20V1.4.pdf) · [Markdown](Continuous%20Cost%20Governance%20Paper%20V1.4.md) · [Word](Continuous%20Cost%20Governance%20Paper%20V1.4.docx) (repository root) | [`v1.4.0`](https://github.com/babbabooieq/continuous-cost-governance/tree/v1.4.0) |

The Version 1.4 files at the repository root are the October 22, 2026 repository copy.

---

## Abstract

Between 2019 and 2026, cloud financial management matured into a recognized discipline, yet 78% of FinOps practices now sit within the CTO or CIO organization while only 8% report to the CFO (State of FinOps 2026). While FinOps has shifted up into technology strategy and left into engineering workflow, it has not shifted across into the finance control environment. Consequently, the industry's headline metric, "potential savings," measures unverified hypotheses rather than financial outcomes.

This working paper proposes Continuous Cost Governance (CCG): a vendor-neutral control specification that treats each material cost decision as a governed transaction carrying decision-grade evidence, a named accountable owner, risk-proportionate authorization, and an independently verified outcome against an adjusted baseline. Grounded in the FinOps Framework, FOCUS 1.3, COSO, and IPMVP and ASHRAE Guideline 14 measurement and verification protocols, the paper contributes: (1) a decision-centric governance model; (2) a reportability standard separating operational tracking from financial reporting; and (3) a proposed Measurement and Verification (M&V) protocol for consumption-based cloud and AI expenditure (Appendix A).

### Key Contributions

1. **A decision-centric governance model.** It proposes the individual cost decision (not the period, the resource, or the service) as the unit of governance, with a defined lifecycle and a retained evidentiary record.
2. **A reportability standard for realized savings.** It proposes a rule separating what may be tracked operationally from what may be reported as a financial result, grounded in established measurement and verification practice.
3. **A control specification that extends rather than competes with FinOps.** It locates that specification inside the FinOps Framework's Policy & Governance capability, and names the organizational seam between engineering-owned telemetry and finance-owned control that current practice leaves unattended.

---

## Core Architecture

### Figure 1: The Continuous Governance Loop
![Figure 1: The Continuous Governance Loop](v1.5.6/D1%20Continuous%20Governance%20Loop%20v1.4.png)

### Figure 2: The Governance Pyramid
![Figure 2: The Governance Pyramid](v1.5.6/D2%20Governance%20Pyramid.png)

### Figure 3: The estimate-to-verified-outcome funnel (schematic; not to scale)
![Figure 3: The estimate-to-verified-outcome funnel](v1.5.6/D3%20Estimate%20to%20Verified%20Outcome%20Funnel.png)

### Figure 4: TBM, FinOps and CCG: a division of labor
![Figure 4: TBM, FinOps and CCG: a division of labor](v1.5.6/D4%20TBM%20FinOps%20CCG%20Division%20of%20Labour.png)

### Figure 5: The Governed Transaction Record
![Figure 5: The Governed Transaction Record](v1.5.6/D5%20Governed%20Transaction%20Record%20Schema.png)

---

## Feedback & Industry Review

This working paper is published openly for critique and empirical testing across FinOps, Finance/FP&A, Engineering, and Internal Audit communities. Feedback, critiques of the Appendix A M&V protocol, and empirical replication inquiries are welcome via GitHub Issues or at [surujnarine.net](https://surujnarine.net).

---

## How to Cite

**APA:**
> Surujnarine, A. (2026). *Introducing Continuous Cost Governance: Extending FinOps from Cost Optimization to Financial Accountability* (Working Paper Version 1.5.6). Compute LLC. https://doi.org/10.5281/zenodo.23555398

**BibTeX:**
```bibtex
@techreport{surujnarine2026ccg,
  author      = {Surujnarine, Andy},
  title       = {Introducing Continuous Cost Governance: Extending FinOps from Cost Optimization to Financial Accountability},
  institution = {Compute LLC},
  year        = {2026},
  month       = sep,
  type        = {Working Paper},
  number      = {Version 1.5.6},
  doi         = {10.5281/zenodo.23555398},
  url         = {https://doi.org/10.5281/zenodo.23555398}
}
```

---

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](LICENSE).
