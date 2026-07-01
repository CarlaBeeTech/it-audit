# IT Audit — SOC 2 ITGC Readiness Assessment

A demonstration IT General Controls (ITGC) audit, built to show working knowledge of the SOC 2 audit lifecycle: scoping, control testing, findings/risk rating, and reporting.

**Mock engagement:** SOC 2 Type II readiness audit of a fictitious healthcare-tech company ("Meridian Health Partners"), covering the Security (Common Criteria), Availability, and Confidentiality Trust Services Criteria, cross-mapped to NIST SP 800-53 Rev. 5.

> This is a portfolio/demonstration project. Meridian Health Partners is a fictitious entity; all data, findings, and evidence references are illustrative.

## What's in this repo

| File | Description |
|---|---|
| `SOC2_ITGC_Audit_Report.docx` | Formal audit report — executive summary, scope, methodology, system description, results by TSC category, 5 detailed findings with risk ratings, and overall opinion. |
| `SOC2_ITGC_Controls_Testing_Workbook.xlsx` | Working papers — 22 tested controls (CC1–CC9, A1, C1), a risk & findings log, and a live summary dashboard (pass rate, findings by risk/status). |

## Approach

- **Framework:** AICPA Trust Services Criteria (2017, with 2022 revisions), cross-referenced to NIST SP 800-53 Rev. 5 control families.
- **Testing method:** risk-based sampling — full population for low-volume controls (e.g., annual DR test), judgmental/statistical sampling for transaction-level controls (access provisioning, change tickets, vulnerability remediation).
- **Rating scale:** Pass / Pass with Exception / Fail, consistent with SOC 2 service auditor conventions.
- **Results:** 22 controls tested — 17 passed cleanly, 5 passed with a noted exception, 0 failures. One High-risk finding (critical vulnerability remediation exceeding SLA with no documented risk acceptance); four Medium-risk findings (termination-access timeliness, risk register documentation, vendor attestation tracking, DR runbook automation).

## Skills demonstrated

- ITGC control design & operating-effectiveness testing
- Risk rating and findings documentation (likelihood/impact)
- Audit report writing for an executive/compliance-committee audience
- Controls-testing workpaper structure (Excel, with conditional formatting and live summary formulas)
- Mapping between SOC 2 TSC and NIST 800-53

## Methodology note

This deliverable was built with AI-assisted drafting (report structure, control language, and workbook formulas), then reviewed and customized by Carla Bee. It's intended to demonstrate applied understanding of SOC 2 ITGC audit methodology, not to represent a real client engagement or an independent auditor's attestation.

## About

Built by Carla Bee, CMB Enterprise Group LLC, as part of a GRC/IT Audit portfolio while completing the Per Scholas Cybersecurity with AI Tools program.
