# Follow The Dollar

**followthedollar.org**

A public accountability index measuring how much of every taxpayer dollar reaches the people it was appropriated to serve — across nonprofits, intermediaries, and public programs nationwide.

---

## The Problem

Billions of public dollars flow annually through nonprofit intermediaries — innovation funds, food banks, homeless services, workforce development programs, healthcare access initiatives. These organizations exist, on paper, to serve specific populations. But in almost every case, nobody is measuring how much actually gets through.

The Form 990 is public. The federal single audit is public. The state budget is public. The accountability gap is a framing problem, not a data problem.

Follow The Dollar closes that gap with a single metric.

---

## The Direct Capital Ratio (DCR)

```
DCR = Direct Disbursements to Recipients / Total Public Appropriations Received
```

The result: how many cents of every public dollar actually reached the intended recipient.

Every figure in this index traces to a primary audited source. No estimates. No projections.

**Primary sources used:**
- IRS Form 990 Schedule I (ProPublica Nonprofit Explorer)
- IRS Form 990 Schedule J (executive compensation)
- Federal Audit Clearinghouse single audits
- State budget appropriations documents
- SAM.gov

Full methodology: [`/methodology/dcr_methodology.md`](methodology/dcr_methodology.md)

---

## Current Dataset

| Organization | Location | Sector | DCR | CEO Comp | Source Year |
|---|---|---|---|---|---|
| Innovation Works | Pittsburgh, PA | Innovation Funding | 25¢ | $576,383 | FY2023 |
| JumpStart | Cleveland, OH | Innovation Funding | 21¢ | — | FY2023 |
| Elevate Ventures | Indianapolis, IN | Innovation Funding | 54¢ | — | FY2023 |
| Feeding America | Chicago, IL | Food Security | 38¢ | $1,113,502 | FY2023 |
| Natl Alliance to End Homelessness | Washington, DC | Homelessness | 29¢ | $313,000 | FY2022 |

Full dataset: [`/data/dcr_verified.csv`](data/dcr_verified.csv)

---

## Build Plan

**Phase 1 — Pennsylvania (Active)**
Manually verified DCR for all major PA innovation intermediaries. Innovation Works anchor data complete. BFTP regional centers in progress.

**Phase 2 — Multi-State Expansion (Building)**
Comparable innovation intermediaries in OH, IN, MI, NY, MA. National food security and homelessness organizations with audited figures.

**Phase 3 — Nomos Automation (Planned)**
IRS 990 XML pipeline + Federal Audit Clearinghouse API. Manual layer: state budget documents only. Full database goes live at followthedollar.org.

---

## Repository Structure

```
followthedollar/
├── index.html              # Public-facing landing page
├── data/
│   ├── dcr_verified.csv    # Verified DCR dataset (primary sources only)
│   └── sources.md          # Source documentation per organization
├── methodology/
│   └── dcr_methodology.md  # Full methodology documentation
└── README.md
```

---

## Origin

The Direct Capital Ratio was developed through forensic analysis of Pennsylvania's innovation funding ecosystem — comparing Innovation Works (PA), JumpStart (OH), and Elevate Ventures (IN) across FY2019–2024 using federal single audits and IRS Schedule I filings.

The underlying empirical research is being prepared for SSRN publication.

Follow The Dollar is a Pittsburgh Compact initiative. Non-commercial.
Commercial data API: **Nomos** — contact for access.

---

## Contact

**Ajmail Matin**
Founder, Pittsburgh Compact
followthedollar.org
pittsburghcompact.org
