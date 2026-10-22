# Continuous Cost Governance (CCG)

### Extending FinOps from Cost Optimization to Financial Accountability

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23555398.svg)](https://doi.org/10.5281/zenodo.23555398)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0004--0144--1497-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0004-0144-1497)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Version](https://img.shields.io/badge/Version-1.4-1B2A41.svg)](Continuous%20Cost%20Governance%20Paper%20V1.4.pdf)

**Author:** Andy Surujnarine ([ORCID: 0009-0004-0144-1497](https://orcid.org/0009-0004-0144-1497))  
**Affiliation:** Founder, Compute LLC; Cloud Operations & Security Practitioner  
**Correspondence:** [https://surujnarine.net](https://surujnarine.net)  
**DOI:** [10.5281/zenodo.23555398](https://doi.org/10.5281/zenodo.23555398)  
**Status:** Working Paper for Industry Review (Version 1.4, October 2026)

---

> ### Continuous Cost Governance in One Sentence
> **FinOps determines what should be done with technology spend. Continuous Cost Governance establishes what was actually done, on whose authority, and what it verifiably delivered.**

---

## Download the Working Paper (Version 1.4)

- **[Download PDF (`Continuous Cost Governance Paper V1.4.pdf`)](Continuous%20Cost%20Governance%20Paper%20V1.4.pdf)**
- **[Read Full Markdown (`Continuous Cost Governance Paper V1.4.md`)](Continuous%20Cost%20Governance%20Paper%20V1.4.md)**
- **[Download Word Document (`Continuous Cost Governance Paper V1.4.docx`)](Continuous%20Cost%20Governance%20Paper%20V1.4.docx)**

---

## Abstract

Between 2019 and 2026, cloud financial management matured from an improvised practice into a recognised discipline. Yet the *State of FinOps 2026* survey of 1,192 practitioners managing more than \$83 billion in annual cloud spend reports that 78% of FinOps practices now sit within the CTO or CIO organisation, while the share reporting to the CFO has fallen to 8%. FinOps has shifted **up** into technology strategy and **left** into engineering workflow. It has not, on the evidence, shifted **across** into the finance control environment.

A technical recommendation becomes a financial result only when someone is accountable for it, someone authorises it, someone implements it, and someone independently measures what actually changed. In consumption-based technology spend those steps are not systematically performed, and the industry's headline metric, "potential savings," measures the absence of that discipline.

This working paper proposes **Continuous Cost Governance (CCG)**: a vendor-neutral control specification that treats each material cost decision as a governed transaction with an owner, an evidentiary record, a risk-proportionate authorisation, and an independently verified outcome against an adjusted baseline. It is offered as an extension to the FinOps Framework's *Policy & Governance* capability, not a replacement for it.

### Key Contributions

1. **A decision-centric governance model.** Proposes the individual cost decision, rather than the period, the resource, or the service, as the unit of governance, with a defined seven-stage lifecycle and a retained evidentiary record.
2. **A reportability standard for realised savings.** Establishes a rule separating what may be tracked operationally from what may be reported as a financial result, grounded in IPMVP and ASHRAE Guideline 14 measurement and verification (M&V) practice.
3. **An executable M&V protocol for consumption-based spend (Appendix A).** Transposes IPMVP Options A to D to FOCUS-normalised (`EffectiveCost`) cloud and AI expenditure, including an adjusted-baseline savings equation, pre-registered adjustment sets, elasticity estimation, overlapping-change attribution rules, and a two-sigma detectability test.

---

## Core Architecture

### 1. The Continuous Governance Loop
![Figure 1: The Continuous Governance Loop](D1%20Continuous%20Governance%20Loop.png)

### 2. The Governance Pyramid
![Figure 2: The Governance Pyramid](D2%20Governance%20Pyramid.png)

### 3. Division of Labour: TBM, FinOps, and CCG
![Figure 3: TBM, FinOps and CCG: a division of labour](D4%20TBM%20FinOps%20CCG%20Division%20of%20Labour.png)

---

## Feedback & Industry Review

This working paper is published openly for critique and empirical testing across FinOps, Finance/FP&A, Engineering, and Internal Audit communities. Feedback, critiques of the Appendix A M&V protocol, and empirical replication inquiries are welcome via GitHub Issues or at [surujnarine.net](https://surujnarine.net).

---

## How to Cite

**APA:**
> Surujnarine, A. (2026). *Introducing Continuous Cost Governance: Extending FinOps from Cost Optimization to Financial Accountability* (Working Paper Version 1.4). Compute LLC. https://doi.org/10.5281/zenodo.23555398

**BibTeX:**
```bibtex
@techreport{surujnarine2026ccg,
  author      = {Surujnarine, Andy},
  title       = {Introducing Continuous Cost Governance: Extending FinOps from Cost Optimization to Financial Accountability},
  institution = {Compute LLC},
  year        = {2026},
  month       = oct,
  type        = {Working Paper},
  number      = {Version 1.4},
  doi         = {10.5281/zenodo.23555398},
  url         = {https://doi.org/10.5281/zenodo.23555398}
}
```

---

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](LICENSE).
