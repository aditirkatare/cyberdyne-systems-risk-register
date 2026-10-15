# Cyberdyne Systems | Risk Register & Treatment Plan

**Project #2 · GRC portfolio simulation · October 2026**  
**Prepared by:** Aditi Rajendra Katare

> Independent fictional GRC portfolio exercise. Cyberdyne Systems is a fictional 50-employee SaaS company. No real organization, system, control implementation, audit, or certification is represented.

## Purpose
Identify and prioritize cybersecurity and business risks, define treatment actions and accountable owners, and provide traceable high-level mappings to NIST Cybersecurity Framework (CSF) 2.0, CIS Critical Security Controls v8.1, and selected SOC 2 Trust Services Criteria.

## Repository contents
- `deliverables/cyberdyne_risk_register.xlsx` — risk register, scoring method, treatment plan, framework mapping.
- `deliverables/cyberdyne_risk_register.csv` — portable CSV export.
- `docs/risk_methodology.md` — scoring, assumptions, thresholds, review process.
- `docs/risk_register_summary.md` — concise review table.
- `docs/framework_mapping.md` — high-level mapping notes and scope cautions.
- `docs/risk_treatment_plan.md` — prioritized action plan.
- `docs/assumptions_and_limitations.md` — explicit assumptions and limitations.
- `templates/risk_review_minutes.md` — quarterly review template.
- `templates/risk_acceptance_record.md` — risk acceptance template.

## Executive summary
The register contains **24 illustrative risks** across customer data, AWS, identity, endpoints, collaboration tools, software delivery, resilience, vendors, privacy, incident response, and governance. Inherent risk is scored as likelihood × impact on a 1–5 scale. The workbook includes proposed control actions and **target residual scores** for planning. Target residual risk is not evidence of a real reduction.

### Important interpretation
- All proposed controls are marked **Proposed** unless a control is explicitly evidenced and tested. This simulation does not verify live controls.
- Project #1 policies establish intended requirements; they do not prove implementation or operating effectiveness.
- Backup and recovery coverage, immutability, and restore testing remain an explicitly unverified gap until evidence is collected.
- Framework mappings are indicative cross-references, not a formal compliance determination or an assertion of SOC 2 readiness.
- SOC 2 references are high-level examples. Confirm applicability and exact criteria against current AICPA materials and the organization's defined scope.

## Scoring
| Score | Rating | Suggested response |
|---:|---|---|
| 1–4 | Low | Routine controls and review |
| 5–9 | Medium | Assign owner and track treatment |
| 10–16 | High | Prioritize treatment; review monthly |
| 17–25 | Critical | Escalate promptly; document interim safeguards and decision |

A risk rating is a prioritization aid, not a precise prediction of loss.

## How to use
1. Read `docs/risk_methodology.md`.
2. Validate scenarios, likelihood, impact, owners, and dates.
3. Confirm whether any controls are truly implemented.
4. Gather evidence, test control operation, and then re-score residual risk.
5. Record acceptance decisions using the template.
6. Review High and Critical risks monthly and the full register at least quarterly.

## Resume-ready description
**Cyberdyne Systems GRC Risk Register (Independent Portfolio Project)** — Developed a 24-risk register for a fictional SaaS company using a 5×5 likelihood-impact model; documented inherent and target residual risk, treatment actions, accountable owners, and indicative NIST CSF 2.0, CIS Controls v8.1, and SOC 2 mappings. Separated proposed controls from verified evidence and documented assumptions, acceptance workflow, and backup/recovery validation gaps.

## Disclaimer
Educational portfolio work only. Not legal advice, an audit opinion, a penetration test, a certification, or a claim that any control is implemented.
