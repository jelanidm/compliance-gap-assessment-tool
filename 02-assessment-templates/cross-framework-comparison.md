# Cross-Framework Comparison: NIST CSF 2.0 to CIS Controls v8 IG1

**Purpose:** Unified view showing where NIST CSF maturity and CIS Controls implementation align or diverge.

---

## How to Use This Document

Fill in the NIST CSF score (1-5) and CIS Controls implementation percentage after completing both individual assessments. The "Alignment" column identifies whether the strategic maturity (NIST) matches the tactical implementation (CIS). Misalignment in either direction reveals important findings.

---

## Comparison Matrix

| NIST CSF Function / Category | NIST Score (1-5) | Corresponding CIS Controls | CIS % Implemented | Alignment | Priority Gap? |
|------------------------------|-----------------|---------------------------|-------------------|-----------|--------------|
| **GOVERN** | | | | | |
| GV.OC - Organizational Context | /5 | 15.1 (Service provider inventory) | % | Aligned / Misaligned | Y / N |
| GV.RM - Risk Management Strategy | /5 | No direct CIS mapping | N/A | N/A | Y / N |
| GV.RR - Roles and Responsibilities | /5 | 17.1 (IR personnel) | % | | Y / N |
| GV.PO - Policy | /5 | 3.1 (Data management process) | % | | Y / N |
| GV.SC - Supply Chain Risk Mgmt | /5 | 15.1, 15.4 (Vendor management) | % | | Y / N |
| **IDENTIFY** | | | | | |
| ID.AM - Asset Management | /5 | 1.1, 1.2, 2.1, 2.2, 2.3 (Asset/software inventory) | % | | Y / N |
| ID.RA - Risk Assessment | /5 | 3.7 (Data classification) | % | | Y / N |
| ID.IM - Improvement | /5 | No direct CIS mapping | N/A | N/A | Y / N |
| **PROTECT** | | | | | |
| PR.AA - Identity and Access | /5 | 5.1-5.4, 6.1-6.5 (Account and access mgmt) | % | | Y / N |
| PR.AT - Awareness and Training | /5 | 14.1-14.5, 14.8 (Security training) | % | | Y / N |
| PR.DS - Data Security | /5 | 3.1-3.12 (Data protection) | % | | Y / N |
| PR.PS - Platform Security | /5 | 4.1, 4.3, 4.7, 7.1-7.4 (Config and patching) | % | | Y / N |
| PR.IR - Infrastructure Resilience | /5 | 12.1, 12.6 (Network infrastructure) | % | | Y / N |
| **DETECT** | | | | | |
| DE.CM - Continuous Monitoring | /5 | 8.1-8.3, 8.5 (Audit logs) | % | | Y / N |
| DE.AE - Adverse Event Analysis | /5 | 8.2, 13.1 (Log collection, alerting) | % | | Y / N |
| **RESPOND** | | | | | |
| RS.MA - Incident Management | /5 | 17.1, 17.4 (IR process) | % | | Y / N |
| RS.RP - Response Planning | /5 | 17.4, 17.7 (IR process, exercises) | % | | Y / N |
| RS.CO - Incident Communication | /5 | 17.2, 17.6 (Contacts, communication) | % | | Y / N |
| RS.AN - Incident Analysis | /5 | 17.4 (IR process) | % | | Y / N |
| RS.MI - Incident Mitigation | /5 | 17.4 (IR process) | % | | Y / N |
| **RECOVER** | | | | | |
| RC.RP - Recovery Planning | /5 | 11.1-11.4 (Data recovery) | % | | Y / N |
| RC.CO - Recovery Communication | /5 | No direct CIS mapping | N/A | N/A | Y / N |

---

## Alignment Interpretation Guide

| NIST Score | CIS Implementation | Interpretation | Action |
|-----------|-------------------|----------------|--------|
| High (3+) | High (70%+) | Aligned. Both governance and implementation are strong. | Maintain. Monitor for drift. |
| High (3+) | Low (<50%) | Governance exists but is not technically enforced. Policies without controls. | Prioritize technical implementation. |
| Low (<3) | High (70%+) | Technical controls exist but lack governance structure. Ad hoc, person-dependent. | Formalize governance around existing controls. |
| Low (<3) | Low (<50%) | Neither governance nor implementation. Critical gap. | Highest priority. Start with governance, follow with implementation. |

---

## Summary Scorecard

| Metric | NIST CSF 2.0 | CIS Controls v8 IG1 |
|--------|-------------|---------------------|
| Overall Score | /5 average | % implemented |
| Strongest Area | | |
| Weakest Area | | |
| Number of Priority Gaps | | |
| Alignment Status | Mostly aligned / Partially aligned / Misaligned |
