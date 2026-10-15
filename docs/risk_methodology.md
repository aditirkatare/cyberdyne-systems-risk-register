# Risk Assessment Methodology

## Scope and horizon
This register covers illustrative cybersecurity and business risks for a fictional 50-employee SaaS provider using AWS, GitHub, Google Workspace, Slack, and employee laptops. The working assessment horizon is the next 12 months.

## Scoring
- **Likelihood (1–5):** 1 Rare, 2 Unlikely, 3 Possible, 4 Likely, 5 Almost Certain.
- **Impact (1–5):** 1 Insignificant, 2 Minor, 3 Moderate, 4 Major, 5 Severe.
- **Inherent risk:** Likelihood × Impact before proposed mitigation.
- **Target residual risk:** a planning estimate only, not a measured result.

| Score | Rating | Handling |
|---:|---|---|
| 1–4 | Low | Routine management and review |
| 5–9 | Medium | Assign owner and track treatment or rationale |
| 10–16 | High | Prioritize treatment; monthly review |
| 17–25 | Critical | Prompt leadership escalation and interim safeguards |

These are proposed internal thresholds, not thresholds mandated by NIST, CIS, or AICPA.

### Likelihood anchors
1 Rare: exceptional circumstances. 2 Unlikely: plausible but not expected. 3 Possible: credible scenario with meaningful exposure. 4 Likely: strong exposure or recurring opportunity. 5 Almost Certain: occurring or expected repeatedly / imminently.

### Impact anchors
1 Insignificant: limited, quickly recoverable internal disruption. 2 Minor: localized disruption or limited impact. 3 Moderate: material team/service impact. 4 Major: substantial outage, sensitive-data exposure, or significant contractual/financial consequences. 5 Severe: broad customer-data compromise, prolonged outage, or major legal/regulatory exposure.

## Residual scoring caveat
For this first draft, target residual likelihood and impact are each reduced by one level (minimum 1) as a consistent placeholder. This is mechanical and **must be replaced by a control-specific reassessment** after treatment. Some controls reduce likelihood, some impact, and some may not change the score.

Before re-scoring, record implementation date, evidence source and period, test performed, sample and result, exceptions, revised rationale, and owner approval.

## Control status
- **Proposed:** recommended but not verified as implemented.
- **Implemented, evidence pending:** only after owner confirms deployment.
- **Tested effective:** only after documented testing supports operation for a defined period.
- **Exception / not implemented:** record gap, interim safeguards, owner, due date, and approval.

Drafted policies do not prove implementation or operating effectiveness.

## Treatment and review
Treatment choices: mitigate, avoid, transfer/share, or accept. Acceptance must include rationale, interim safeguards, expiry/review date, and approval from an authorized risk owner. Suggested cadence: Critical weekly until stable, High monthly, Medium quarterly, and full-register review quarterly and after material changes.
