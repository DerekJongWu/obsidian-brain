---
type: company
sector: AI / Enterprise Software
sub_sector: Enterprise General Intelligence / Organizational Memory
stage: Seed
status: sourcing
owner:
founded: 2025
hq: San Francisco Bay Area (Canada entity per Harmonic)
website: https://sentra.app
linkedin: https://linkedin.com/company/sentra-app
crunchbase:
pitchbook: https://pitchbook.com/profiles/company/1130490-19
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-04-21
created: 2026-04-21
tags:
  - company
---

# Sentra

> [!summary] One-Liner
> Building "enterprise general intelligence" — an AI-driven organizational memory system that captures the interaction layer (meetings, messages, emails) across an enterprise to replace static systems of record like CRMs.

---

## Thesis Fit

**Why we like it:**
- Strong technical founder (ex-Caltech/MIT faculty, multiple bio company exits); early contributor to agentic-framework literature (reflection technique)
- Novel architecture claim: semantic memory file system (POSIX + knowledge graphs) vs. RAG/vector DBs; paper in peer review mathematically proving RAG failure modes at scale
- Traction with enterprise design partners (SoftBank Telecom, Warp, Runway, Lenscard India) and active NEA / Sequoia IC conversations

**Relevant thesis:** [[]]

**Fin sub-sector:** AI Infra / Enterprise Knowledge

---

## Team

| Role | Person | Background |
|------|--------|------------|
| Co-Founder | [[Ashwin Gopinath]] | Co-Founder, Sentra (2025-06 — present); former MIT Assistant Professor (2019–2025); Co-Founder & CTO, Palamedrix (acquired by Somalogic); Co-Founder, Biostate AI; Research Scientist, X The Moonshot Factory; Senior Research Scientist, Caltech; Ph.D. Boston University |
| Co-Founder & CRO | Al Rey | Prior CRO at Vidora, Quantive, and Leanplum (by CleverTap); Head of Enterprise Sales at Vapi; Director of Sales at Kontagent; MBA University of San Francisco; BA UC Santa Barbara |
| Co-Founder (Advisor) | Jae Gwan Park | Previously Co-Founder & CEO, Sentra (2025-03 — 2026-02); MIT researcher; Hummingbird Ventures Fellow; BASc University of Toronto |

---

## Business Description

- **Problem:** Systems of record (CRMs, wikis, ticketing) capture static artifacts, not the actual interaction layer where decisions and commitments live. Existing RAG/vector-DB approaches degrade at enterprise scale due to semantic interference, not raw data volume.
- **Product:** AI-driven organizational memory platform that ingests meetings, messages, and emails; automates meeting notes, follow-ups, reminders, and attribution. Core architecture: a **semantic memory file system** — POSIX-based, S3-compatible — combining file systems with knowledge graphs. Offers on-prem deployment for sensitive data.
- **Wedge / entry point:** Observability/status reporting for C-suite and Gong-replacement for sales teams. Vision: eliminate CRMs entirely (automatic meeting scheduling, updates, attribution, performance reviews based on actual business impact).

---

## Market & Competition

- **Market size:**
- **Key competitors:** [[Gong]] (sales interaction layer), classic CRMs, RAG-based enterprise search vendors
- **Differentiation:**
  - First to mathematically prove (paper in peer review) that RAG/vector DB approaches fail at scale due to semantic interference
  - DRM forgetting test: 58% error rate on RAG (comparable to human 55%) — semantically similar concepts create false memories
  - Semantic memory file system (POSIX + knowledge graphs) vs. embedding-index approaches

---

## GTM & Business Model

- **Buyer persona:** C-suite (largely lacks dedicated tooling vs. other business units); sales leadership as Gong displacement
- **Pricing model:**
  - Platform tier: per user, unlimited integrations, "Enterprise Search 2.0"
  - Intelligence tier: credit-based — 100 LLM tokens = 1 credit unit (~25% markup); bring-your-own-key option available
- **ACV:**
- **Contract structure:**

**Distribution strategy:**
- Direct C-suite sales + system integrator partnerships (CTC, NEC mentioned)
- Agentic sandboxing angle for large banks / insurance

---

## Traction

- **Design partners:** 11 design partnerships, several converted (as of 2026-04-21)
  - SoftBank Telecom, [[Campfire]], Warp, Runway
  - Lenscard India: 150 seats pilot → 1,500–2,000 seats (LOI signed)
- **ARR:**
- **Growth:** 15 employees (6 eng, 4 ops, 2 sales, 2 data)
- **Retention / NRR:**

---

## Financing

| Date | Round | Amount | Investors |
|------|-------|--------|-----------|
| 2026-01 | Seed | $5.5M total (2 rounds) | Inovia Capital, Precursor Ventures, Together, Backwards Capital, a16z speedrun, Antigravity, Parable; angels: Siqi Chen, Cailen D'Sa, Gokul Rajaram, Shaad Khan, Kaitlyn Knopp |

**Current round:**
- Active fundraising process (as of 2026-04-21)
  - NEA IC this week (close relationship)
  - Sequoia IC being scheduled
- Terms:
- Timeline:

---

## Deal Team Notes

- Founder claims early contributions to agentic-framework literature (reflection technique now industry standard)
- Technical thesis: RAG fails due to semantic interference, not volume — paper in peer review
- Vision to eliminate CRMs entirely — automatic meeting scheduling, updates, attribution, performance reviews based on actual business impact
- Partnership opportunities: agentic sandboxing for large banks/insurance; SI partnerships (CTC, NEC)

---

## Meetings & References

```dataview
TABLE date as "Date", type as "Type"
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

---

## Next Steps

- [ ] Fan to share introduction list for relevant connections (focus on innovative, early-stage friendly companies; direct C-suite access)
- [ ] Track outcome of NEA IC and Sequoia IC
- [ ] Evaluate partnership fit for agentic sandboxing in banking/insurance portfolio
