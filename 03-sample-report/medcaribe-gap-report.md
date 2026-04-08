# MedCaribe Health Group - Compliance Gap Assessment Report

**Document Classification:** Confidential / Executive Leadership  
**Assessment Date:** April 2026  
**Assessed By:** Jelani D. Maitland  
**Frameworks:** NIST CSF 2.0 + CIS Controls v8 IG1  
**Scope:** All MedCaribe systems, data, and processes across four clinic locations

---

## Executive Summary

This assessment evaluates MedCaribe Health Group's cybersecurity posture against two industry frameworks: NIST CSF 2.0 (strategic maturity) and CIS Controls v8 IG1 (tactical implementation).

The assessment captures the organization's status after implementing the security program from Project 1, the M365 controls from Project 2, conducting tabletop exercises from Project 3, and completing the first vendor assessment from Project 4.

| Metric | Baseline (March 2026) | Current (April 2026) | Change |
|--------|----------------------|---------------------|--------|
| NIST CSF Average Maturity | 1.2 / 5 | 2.4 / 5 | +1.2 |
| CIS IG1 Implemented | 0% | 39% (22 of 56) | +39% |
| CIS IG1 Partial | 0% | 25% (14 of 56) | +25% |
| Critical Risks (from Risk Register) | 8 | 4 | -4 |
| Policies in Place | 0 | 5 | +5 |
| Vendor Assessments Completed | 0 | 1 (CloudMed EHR) | +1 |

**Key finding:** The security program has moved MedCaribe from a completely undocumented, ad hoc security posture to a governed, partially implemented program in approximately 8 weeks. The governance layer (policies, IR plan, risk register) is the strongest area. Technical implementation (M365 controls, backup, network hardening) is progressing but not yet complete.

---

## NIST CSF 2.0 Maturity Assessment

| Function | Category | Baseline | Current | Target (12 mo) | Evidence |
|----------|----------|----------|---------|----------------|---------|
| **Govern** | GV.OC - Organizational Context | 1.0 | 3.0 | 3.0 | Company profile, regulatory context, and scope documented in Project 1 |
| | GV.RM - Risk Management Strategy | 1.0 | 3.0 | 3.0 | Risk register with scoring methodology, 20 risks identified and prioritized |
| | GV.RR - Roles and Responsibilities | 1.0 | 3.0 | 3.0 | IR team roles assigned, security program owner designated |
| | GV.PO - Policy | 1.0 | 3.0 | 3.0 | 5 policies created, distributed, staff acknowledgement in progress |
| | GV.SC - Supply Chain Risk Mgmt | 1.0 | 2.5 | 3.0 | Vendor Risk Policy (POL-005), tiering methodology, CloudMed assessed. Other vendors pending. |
| **Govern Average** | | **1.0** | **2.9** | **3.0** | |
| **Identify** | ID.AM - Asset Management | 1.5 | 2.5 | 3.0 | Asset inventory documented in Project 1. Intune enrollment in progress. |
| | ID.RA - Risk Assessment | 1.0 | 3.0 | 3.0 | Formal risk assessment completed with 20 scored risks |
| | ID.IM - Improvement | 1.0 | 2.0 | 3.0 | Remediation roadmap tracks improvements. After-action report process established. |
| **Identify Average** | | **1.2** | **2.5** | **3.0** | |
| **Protect** | PR.AA - Identity and Access | 1.5 | 2.5 | 3.0 | MFA enforced. Admin accounts separated. Offboarding checklist implemented. RBAC in progress. |
| | PR.AT - Awareness and Training | 1.0 | 1.5 | 3.0 | Training platform selected but first session not yet delivered |
| | PR.DS - Data Security | 1.0 | 2.5 | 3.0 | BitLocker enabled. Classification policy in place. Purview labels pending. |
| | PR.PS - Platform Security | 1.0 | 2.0 | 2.5 | Intune security baselines deployed. Printer defaults partially addressed. |
| | PR.IR - Infrastructure Resilience | 1.0 | 1.5 | 2.5 | Guest Wi-Fi separated at 2 locations. Firewall upgrade planned for Phase 4. |
| **Protect Average** | | **1.1** | **2.0** | **2.8** | |
| **Detect** | DE.CM - Continuous Monitoring | 1.0 | 2.5 | 3.0 | M365 unified audit log enabled. Basic alerts configured. Weekly review cadence started. |
| | DE.AE - Adverse Event Analysis | 1.0 | 2.0 | 2.5 | M365 Defender incident queue active. Log analysis capability developing. |
| **Detect Average** | | **1.0** | **2.3** | **2.8** | |
| **Respond** | RS.MA - Incident Management | 1.0 | 3.0 | 3.0 | Full IR plan with containment procedures for 5 incident types |
| | RS.RP - Response Planning | 1.0 | 3.0 | 3.0 | IR plan documented and reviewed |
| | RS.CO - Incident Communication | 1.0 | 3.0 | 3.0 | Communication templates, escalation decision tree |
| | RS.AN - Incident Analysis | 1.0 | 2.0 | 2.5 | Analysis capability limited to M365 tools; external IR support TBD |
| | RS.MI - Incident Mitigation | 1.0 | 2.5 | 3.0 | Pre-authorized containment actions defined and tested in tabletop |
| **Respond Average** | | **1.0** | **2.7** | **2.9** | |
| **Recover** | RC.RP - Recovery Planning | 1.0 | 2.0 | 2.5 | Third-party M365 backup implemented. EHR vendor backup verified. RTO/RPO defined. Full restore test pending. |
| | RC.CO - Recovery Communication | 1.0 | 2.5 | 3.0 | Recovery communication included in IR plan. Vendor breach templates added after Project 3. |
| **Recover Average** | | **1.0** | **2.3** | **2.8** | |

### NIST CSF Maturity Summary

| Function | Baseline | Current | Improvement |
|----------|----------|---------|-------------|
| Govern | 1.0 | 2.9 | +1.9 |
| Identify | 1.2 | 2.5 | +1.3 |
| Protect | 1.1 | 2.0 | +0.9 |
| Detect | 1.0 | 2.3 | +1.3 |
| Respond | 1.0 | 2.7 | +1.7 |
| Recover | 1.0 | 2.3 | +1.3 |
| **Overall** | **1.05** | **2.4** | **+1.35** |

---

## CIS Controls v8 IG1 Implementation Summary

| Status | Safeguards | Percentage |
|--------|-----------|------------|
| Implemented | 22 | 39% |
| Partial | 14 | 25% |
| Not Implemented | 16 | 29% |
| Not Applicable | 2 | 4% |
| **Total** | **56** | |

### Implementation by Control Family

| Control Family | Total | Implemented | Partial | Not Impl | N/A |
|---------------|-------|-------------|---------|----------|-----|
| 1. Asset Inventory | 2 | 0 | 2 | 0 | 0 |
| 2. Software Inventory | 3 | 1 | 1 | 0 | 1 |
| 3. Data Protection | 10 | 5 | 3 | 2 | 0 |
| 4. Secure Configuration | 3 | 2 | 1 | 0 | 0 |
| 5. Account Management | 4 | 3 | 1 | 0 | 0 |
| 6. Access Management | 5 | 4 | 1 | 0 | 0 |
| 7. Vulnerability Mgmt | 4 | 2 | 2 | 0 | 0 |
| 8. Audit Log Mgmt | 4 | 4 | 0 | 0 | 0 |
| 9. Email/Web | 4 | 2 | 1 | 1 | 0 |
| 10. Malware Defenses | 4 | 3 | 1 | 0 | 0 |
| 11. Data Recovery | 4 | 1 | 1 | 2 | 0 |
| 12. Network Infra | 2 | 0 | 1 | 1 | 0 |
| 13. Network Monitoring | 1 | 1 | 0 | 0 | 0 |
| 14. Security Awareness | 6 | 0 | 2 | 4 | 0 |
| 15. Service Provider | 2 | 0 | 2 | 0 | 0 |
| 16. Application Security | 2 | 0 | 0 | 0 | 2 |
| 17. Incident Response | 7 | 5 | 1 | 1 | 0 |

---

## Cross-Framework Alignment

| Area | NIST Score | CIS Status | Alignment | Notes |
|------|-----------|------------|-----------|-------|
| Governance and Policy | 2.9 | N/A (governance) | Strong | Governance is the strongest area. Policies in place, roles assigned, risk register active. |
| Identity and Access | 2.5 | 78% implemented | Aligned | MFA enforced, admin separation done, offboarding active. RBAC still in progress. |
| Data Protection | 2.5 | 55% implemented | Partially Aligned | BitLocker and transit encryption done. Classification labels and data segmentation pending. |
| Detection and Monitoring | 2.3 | 100% implemented | Aligned | Audit logging enabled and reviewed. Alerts configured. Strong for a small org. |
| Incident Response | 2.7 | 71% implemented | Aligned | Plan, team, severity thresholds, and exercises all in place. External IR support still TBD. |
| Recovery | 2.3 | 25% implemented | Misaligned | Governance is ahead of implementation. M365 backup done but EHR immutable backup and full restore testing still needed. |
| Network Infrastructure | 1.5 | 0% implemented | Aligned (both weak) | Largest remaining gap. Consumer routers, no VLANs, partial DNS filtering. Planned for Phase 4. |
| Security Awareness | 1.5 | 0% implemented | Aligned (both weak) | Training platform selected but no sessions delivered yet. Planned for Phase 3. |
| Vendor Management | 2.5 | 50% partial | Aligned | Framework built, CloudMed assessed. Remaining vendors on schedule for Q3. |

---

## Top 5 Remaining Gaps

| Priority | Gap | NIST Impact | CIS Impact | Recommended Action | Est. Cost |
|----------|-----|-------------|------------|-------------------|-----------|
| P1 | Security awareness training not yet delivered | PR.AT stuck at 1.5 | Control 14 at 0% implemented | Launch first training session and phishing simulation this month | TTD 0 (M365 built-in) |
| P2 | Network infrastructure not hardened | PR.IR stuck at 1.5 | Control 12 at 0% implemented | Deploy business-grade firewalls, VLAN segmentation | TTD 5,000-15,000 |
| P2 | EHR immutable backup not yet in place | RC.RP limited to 2.0 | Control 11.4 not implemented | Confirm immutable storage with backup provider | TTD 0 (config change) |
| P3 | Purview sensitivity labels not deployed | PR.DS limited to 2.5 | Control 3.7 partial | Configure and publish labels matching POL-004 tiers | TTD 0 (M365) |
| P3 | Remaining vendor assessments not started | GV.SC limited to 2.5 | Control 15 partial | Send Tier 2 questionnaires to Sagicor, Guardian, QuickBooks, labs | TTD 0 (process) |

---

## Conclusion

MedCaribe has moved from a maturity of 1.05 to 2.4 in approximately 8 weeks, a 129% improvement. The governance layer is nearly at target (2.9 vs. 3.0 target). Technical implementation is progressing but has further to go, particularly in network infrastructure, security awareness training, and data recovery.

The most significant remaining investment is network infrastructure (firewalls and VLANs). Everything else on the priority list can be completed at zero additional cost using existing M365 licensing and the frameworks already built.

At the current trajectory, MedCaribe is on track to reach the 12-month target maturity of 2.7 by the end of the remediation roadmap.

---

## Document Control

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | April 2026 | J. Maitland | Initial gap assessment post-implementation |

**Next Assessment:** October 2026 (6-month reassessment)
