# Compliance Gap Assessment Methodology

**Document Classification:** Internal / Security Program  
**Version:** 1.0  
**Date:** April 2026  
**Author:** Jelani D. Maitland

---

## 1. Purpose

This document defines how to conduct a compliance gap assessment against NIST CSF 2.0 and CIS Controls v8 IG1, how to score findings, and how to produce a gap report with prioritized recommendations.

---

## 2. Assessment Approach

The assessment is conducted in four steps:

**Step 1: NIST CSF 2.0 Maturity Assessment.** Score each of the 22 NIST CSF categories across the 6 functions on a 1-5 maturity scale. This produces the strategic view of the organization's security posture.

**Step 2: CIS Controls v8 IG1 Implementation Assessment.** Evaluate each of the 56 IG1 safeguards as Implemented, Partial, Not Implemented, or N/A. This produces the tactical view showing which specific controls are in place.

**Step 3: Cross-Framework Comparison.** Map the NIST CSF results to the CIS Controls results to identify where strategic gaps and tactical gaps overlap. Areas that score low in both frameworks are the highest priority.

**Step 4: Gap Report.** Compile findings into a report with current state summary, identified gaps, root causes, and prioritized recommendations with estimated effort and cost.

---

## 3. NIST CSF 2.0 Scoring Scale

| Level | Rating | Definition |
|-------|--------|------------|
| 1 | Initial | No formal process. Ad hoc and reactive. Dependent on individual knowledge. |
| 2 | Developing | Some awareness. Informal processes in place but inconsistent. Not documented. |
| 3 | Defined | Documented policies and procedures. Roles assigned. Processes followed but not measured. |
| 4 | Managed | Processes measured and monitored. Metrics tracked. Regular review and improvement. |
| 5 | Optimized | Continuous improvement based on data. Proactive risk management. Integrated into operations. |

**How to score:** For each NIST CSF category, assess the organization's current capability using the definitions above. Provide evidence for the score and document any gaps between the current level and the target level.

---

## 4. CIS Controls v8 IG1 Scoring Scale

| Status | Definition |
|--------|------------|
| Implemented | Safeguard is fully configured, operational, and consistently followed |
| Partial | Safeguard exists but is incomplete, inconsistent, or has known gaps |
| Not Implemented | Safeguard does not exist or has not been configured |
| N/A | Safeguard does not apply to this organization's environment |

**How to score:** For each CIS IG1 safeguard, determine the current implementation status based on evidence (configuration screenshots, policy documents, log reviews, interviews). Document what evidence was reviewed and any gaps found.

---

## 5. Cross-Framework Alignment

The cross-framework comparison maps each NIST CSF function to the CIS Controls that support it:

| NIST CSF Function | Primary CIS Control Families |
|-------------------|------------------------------|
| Govern | 15 (Service Provider Mgmt), 17 (IR Management), plus governance docs |
| Identify | 1 (Asset Inventory), 2 (Software Inventory), 3 (Data Protection) |
| Protect | 3, 4 (Secure Config), 5 (Account Mgmt), 6 (Access Mgmt), 14 (Training) |
| Detect | 8 (Audit Logs), 13 (Network Monitoring) |
| Respond | 17 (Incident Response) |
| Recover | 11 (Data Recovery) |

When a NIST CSF function scores low AND the corresponding CIS Controls are not implemented, that is a confirmed gap requiring priority action. When scores disagree (high NIST maturity but low CIS implementation, or vice versa), investigate whether the organization has governance in place but lacks technical enforcement, or has technical controls but lacks the governance structure around them.

---

## 6. Gap Prioritization

Gaps are prioritized using three factors:

**Risk impact:** Does this gap correspond to a Critical or High risk in the risk register?

**Effort to close:** Can this gap be closed quickly (configuration change) or does it require significant investment (new tools, staff, budget)?

**Dependency:** Does closing this gap enable other improvements?

Priority levels:

| Priority | Criteria | Expected Timeline |
|----------|----------|------------------|
| P1 - Critical | Addresses top-5 risk, low effort, enables other improvements | Weeks 1-4 |
| P2 - High | Addresses significant risk, moderate effort | Months 2-3 |
| P3 - Medium | Improves posture, requires planning or budget | Months 4-6 |
| P4 - Low | Good practice, lower urgency | Months 7-12 |

---

## 7. Evidence Collection

For each assessment item, document:

- **What was reviewed:** Configuration settings, policy documents, interviews, log samples, vendor reports
- **Who provided the information:** IT admin, management, vendor documentation
- **Date of evidence:** When the evidence was collected
- **Finding:** What the evidence showed (supports the score given)

Evidence does not need to be formal for an IG1 assessment. Screenshots, policy document references, and interview notes are sufficient. The goal is to show the assessment is based on facts, not assumptions.

---

## 8. Reporting

The gap report should include:

1. **Executive summary:** Overall maturity score, number of gaps, top 3 priorities
2. **NIST CSF maturity summary:** Score per function with visual comparison to target
3. **CIS Controls implementation summary:** Percentage implemented, partial, and not implemented
4. **Cross-framework gap analysis:** Where both frameworks show weakness simultaneously
5. **Prioritized recommendations:** Specific actions, owners, timelines, and estimated costs
6. **Comparison to baseline:** If a previous assessment exists, show improvement

---

## 9. Document Control

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | April 2026 | J. Maitland | Initial methodology |
