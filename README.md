# Compliance Gap Assessment Tool

## Dual-Framework Gap Assessment for Small and Midsize Organizations

**Frameworks:** NIST Cybersecurity Framework (CSF) 2.0 + CIS Controls v8 (Implementation Group 1)  
**Context:** MedCaribe Health Group, 55-person private healthcare provider, Trinidad and Tobago  
**Author:** Jelani D. Maitland  
**Date:** April 2026  
**Related Projects:**  
- [Project 1: MedCaribe Security Program](https://github.com/jelanidm/medcaribe-security-program)  
- [Project 2: CIS Controls v8 IG1 to M365 Mapping](https://github.com/jelanidm/m365-cis-controls-mapping)  
- [Project 3: Tabletop Exercise Kit](https://github.com/jelanidm/tabletop-exercise-kit)  
- [Project 4: Vendor Risk Assessment Framework](https://github.com/jelanidm/vendor-risk-assessment-framework)

---

## Overview

This repository provides a complete compliance gap assessment tool that evaluates an organization's security posture against two frameworks simultaneously: NIST CSF 2.0 and CIS Controls v8 IG1. It includes assessment templates, a scoring methodology, a cross-framework comparison view, and a sample completed gap report for MedCaribe Health Group.

This is the capstone project of a five-project GRC portfolio. It brings together the governance program (Project 1), technical controls mapping (Project 2), exercise testing (Project 3), and vendor risk assessment (Project 4) into a single assessment that measures where the organization stands after all that work.

---

## Why a Dual-Framework Assessment?

Most gap assessments are built against a single framework. That works, but it misses something important: different frameworks serve different audiences and purposes.

**NIST CSF 2.0** provides the strategic view. It organizes security into six functions (Govern, Identify, Protect, Detect, Respond, Recover) that executives and board members understand. It answers: "Are we thinking about all the right areas?"

**CIS Controls v8 IG1** provides the tactical view. It lists 56 specific safeguards that IT teams can implement. It answers: "Are we actually doing the essential things?"

Assessing against both frameworks, and showing how they align, demonstrates that governance and implementation are not the same thing, but they must work together.

---

## What This Tool Includes

**Assessment Methodology** - How to conduct the assessment, the scoring scale, and how to interpret results.

**NIST CSF 2.0 Assessment Template** - All 22 categories across 6 functions, scored on a 1-5 maturity scale with findings and recommendations.

**CIS Controls v8 IG1 Assessment Template** - All 56 safeguards assessed as Implemented, Partial, Not Implemented, or N/A with evidence and gap fields.

**Cross-Framework Comparison** - A mapping showing how NIST CSF categories align to CIS Controls safeguards, with a unified gap view.

**Sample Completed Gap Report** - MedCaribe assessed against both frameworks with current scores, gaps, and prioritized recommendations.

---

## Repository Structure

```
compliance-gap-assessment-tool/
├── README.md
├── 01-assessment-guide/
│   └── assessment-methodology.md
├── 02-assessment-templates/
│   ├── nist-csf-assessment.md
│   ├── cis-controls-assessment.md
│   └── cross-framework-comparison.md
├── 03-sample-report/
│   └── medcaribe-gap-report.md
└── pdf-versions/
```

---

## How the Portfolio Connects

| Project | What It Built | How It Feeds Project 5 |
|---------|--------------|----------------------|
| Project 1 | Governance program | Assessed for policy maturity, IR readiness, risk management |
| Project 2 | CIS to M365 mapping | Implementation status used as CIS assessment input |
| Project 3 | Tabletop exercises | IR exercise completion credited toward Respond maturity |
| Project 4 | Vendor risk framework | Vendor assessment credited toward Supply Chain maturity |

---

## About the Author

Jelani D. Maitland is a cybersecurity professional based in Trinidad and Tobago, holding CySA+, Security+, SC-200, and Fortinet FCA certifications. He specializes in security operations, governance, and risk management for small and midsize organizations in the Caribbean.

- [LinkedIn](https://linkedin.com/in/jelanidm)
- [GitHub](https://github.com/jelanidm)

---

## License

This project is shared under the [MIT License](LICENSE).
