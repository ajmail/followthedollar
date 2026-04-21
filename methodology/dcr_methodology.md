# Direct Capital Ratio — Methodology

**Follow The Dollar | followthedollar.org**
**Version 1.0 | April 2026**

---

## Overview

The Direct Capital Ratio (DCR) is a metric that measures the share of public appropriations that reaches intended recipients as direct capital. It was developed through forensic analysis of Pennsylvania's state innovation funding ecosystem and is designed to be applied universally across any nonprofit intermediary that receives and deploys public funds.

---

## Formula

```
DCR = Direct Disbursements to Recipients
      ─────────────────────────────────────
      Total State Appropriations Received
```

The result expresses how many cents of every appropriated public dollar reached the intended recipient directly.

---

## Data Sources

All figures used in the Follow The Dollar index are drawn exclusively from primary audited sources. No estimates, projections, or secondary aggregators are used.

### 1. IRS Form 990 Schedule I
**What it shows:** Grants and other assistance to domestic organizations and domestic governments; direct grants to individuals.
**Where to access:** ProPublica Nonprofit Explorer (projects.propublica.org/nonprofits)
**What we extract:** Total direct disbursements to recipient founders, individuals, or organizations — the numerator of the DCR.

### 2. IRS Form 990 Schedule J
**What it shows:** Compensation information for certain officers, directors, trustees, key employees, and highest compensated employees.
**Where to access:** ProPublica Nonprofit Explorer
**What we extract:** Base compensation, bonus and incentive compensation, other reportable compensation, retirement and deferred compensation, nontaxable benefits — total compensation per named individual.

### 3. Federal Audit Clearinghouse — Single Audits
**What it shows:** Single audits for organizations that expend $750,000 or more in federal awards in a fiscal year. Includes Schedule of Expenditures of Federal Awards (SEFA).
**Where to access:** facweb.census.gov
**What we extract:** Total federal and state awards received, cross-referenced against program-specific expenditure schedules.

### 4. State Budget Appropriations Documents
**What it shows:** Legislative appropriations by program and recipient organization.
**Where to access:** State budget office websites; Pennsylvania Office of the Budget (budget.pa.gov)
**What we extract:** Total state appropriations directed to each intermediary organization by fiscal year.

### 5. SAM.gov
**What it shows:** Federal award data including grants, contracts, and cooperative agreements.
**Where to access:** sam.gov/reports
**What we extract:** Federal awards to intermediary organizations, used to cross-reference Schedule I disbursements.

---

## Calculation Steps

### Step 1: Identify the organization's total public appropriations
Pull the organization's state budget appropriations for the target fiscal year. Cross-reference with Federal Audit Clearinghouse single audit SEFA schedules to confirm total public funds received.

### Step 2: Identify direct disbursements to recipients
From IRS Form 990 Schedule I, identify grants and direct assistance flowing to intended recipients — founders, individuals, or downstream organizations that are the stated beneficiaries of the program.

**Important distinction:** Only disbursements that flow directly to the intended recipient population are counted in the numerator. Grants to related organizations, subcontractors, or pass-through administrative entities are excluded unless they demonstrably reach the intended recipient.

### Step 3: Calculate the ratio
```
DCR = Step 2 total / Step 1 total
```

Express as cents per dollar (e.g., 0.25 = 25 cents on the dollar).

### Step 4: Layer in executive compensation
From IRS Form 990 Schedule J, record total compensation for all disclosed individuals. This is reported alongside the DCR for context — not incorporated into the ratio itself — but provides critical interpretive context for overhead absorption.

---

## Comparability Standards

For cross-organizational comparisons to be valid, organizations must meet the following criteria:

- Comparable primary mission (e.g., innovation funding intermediaries compared to other innovation funding intermediaries)
- Comparable funding structure (primarily state-appropriated funds, not primarily donor-funded)
- Same fiscal year or adjacent fiscal years with noted adjustment
- Sufficient Schedule I data to calculate a meaningful numerator

---

## Known Limitations

**Technical assistance value:** Some intermediaries provide non-capital services (mentorship, due diligence support, technical assistance) that have real value but do not appear as direct disbursements in Schedule I. The DCR does not capture this value. However: organizations with high technical assistance delivery should still be able to demonstrate high direct capital ratios. Indiana's Elevate Ventures (54¢ DCR) demonstrates this is achievable.

**Fiscal year alignment:** State appropriations and Schedule I disbursements may not perfectly align within a single fiscal year due to multi-year grants or delayed disbursement cycles. Where misalignment exists, it is noted in the source documentation.

**Related organization grants:** Some intermediaries disburse funds to related LLCs or subsidiaries before reaching founders. Where this is identified, it is flagged in the source documentation.

---

## Benchmark Reference

| Organization | State | Sector | DCR | Source Year |
|---|---|---|---|---|
| Elevate Ventures | IN | Innovation | 54¢ | FY2023 |
| Innovation Works | PA | Innovation | 25¢ | FY2023 |
| JumpStart | OH | Innovation | 21¢ | FY2023 |
| Feeding America | National | Food Security | 38¢ | FY2023 |
| Natl Alliance to End Homelessness | DC | Homelessness | 29¢ | FY2022 |

---

## Peer Review & Publication

The underlying empirical research comparing Pennsylvania, Ohio, and Indiana innovation intermediaries across FY2019–2024 is being prepared for SSRN publication. The paper applies regression analysis with board composition and interlock variables as additional explanatory factors.

Upon publication, the SSRN link will be added here.

---

## Version History

| Version | Date | Notes |
|---|---|---|
| 1.0 | April 2026 | Initial public release. Pennsylvania innovation funding anchor dataset. |

---

*Follow The Dollar is a Pittsburgh Compact initiative. Methodology questions: followthedollar.org*
