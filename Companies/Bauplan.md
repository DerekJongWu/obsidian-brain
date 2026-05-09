---
type: company
sector: data infrastructure
sub_sector: agentic data platform / data pipelines
stage: Series A
status: sourcing
owner: Daria Davydenko
founded: 2022
hq: San Francisco, CA
website: http://bauplanlabs.com
linkedin: https://linkedin.com/company/bauplanlabs
crunchbase: https://www.crunchbase.com/organization/bauplan-a2fa
pitchbook: https://pitchbook.com/profiles/company/521629-48
deck_link: 
data_room: 
lighthouse_link: 
last_touch: 2026-05-08
created: 2026-05-08
tags:
  - company
---

> [!info] One-Liner
> Code-first data platform purpose-built for autonomous AI agents — typed APIs, zero-copy data branching ("git for everything including data"), and a custom runtime delivering order-of-magnitude cost efficiency at agent scale.

## Thesis Fit

Data infrastructure for the AI/agent era. Existing data warehouses (Databricks, Snowflake) are human-centric and break down on agent-driven workloads (10x compute, conflicting writes, no code-first interface). Repeat founder team with prior exit (Tooso → Coveo).

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Ciro Greco]] | Co-Founder & CEO of Tooso (acquired by Coveo); former VP of AI at Coveo; PhD cognitive neuroscience |
| Co-Founder | Jacopo Tagliabue | Founder of Tooso (acquired by Coveo); Director of AI at Coveo; Adjunct Professor NYU Tandon; PhD |
| Co-Founder | Mattia Pavoni | Co-founder of Tooso (acquired by Coveo); Director of Value Realization at Coveo |

## Business Description

- **Problem:** Current data infrastructure (Databricks, Snowflake) is built for humans, not agents. Agents run 10x more compute than humans, hit cost-structure walls, lack transactional isolation, and lack code-first interfaces. Example customer: 60,000 operations/week vs typical human usage.
- **Product:** Data platform for autonomous AI agents — entire platform expressed as code with typed APIs; documentation fits in LLM context window; built on "git for everything including data."
- **Solution approach:**
  1. Zero-copy data branching for safe agent experimentation
  2. Custom runtime for order-of-magnitude cost efficiency
  3. Transactional isolation preventing agent conflicts
- Built on Apache Iceberg storage; SQL + Python with version control.

## Market & Competition

- Direct competitors: Databricks, Snowflake — but those are human-first.
- Differentiation: code-first / typed APIs; LLM-friendly docs; agent-scale economics.

## GTM & Business Model

- Pricing tiers: Free → $700/month → up to $10K/month
- Target ACV: $100K (already achieved with one customer)
- Currently inbound-only; controlled rollout
- Enterprise gates: RBAC system (currently basic) and formal SLAs (currently Slack-based support) needed before broad enterprise push

## Traction

- ARR: ~$300K (as of 2026-05-08), projecting $560K by September 2026
- 6 customers in controlled rollout, all inbound (as of 2026-05-08)
- Headcount: 10 (4 engineering, 1 sales, 4 operations)
- Notable customers / pipeline:
  - Media for Europe ($5B broadcaster) — customer
  - Real Page (US real estate SaaS) — customer
  - N26 — pipeline
  - Nexi (European payment processor) — pipeline
  - MOB (South American credit/background checks) — customer
- Strong financial services pipeline pending product maturity

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| Through 2025-04 | Seed (3 rounds total) | $11.6M | South Park Commons, Recursion Venture Capital, Innovation Endeavors, FirsthandVC, Materialized View Capital, Ben Lorica, Wes McKinney, Aditya Agarwal, Chris Re, Spencer Kimball, Ihab Ilyas, Jeffrey Rothschild |
| 2026 (planned) | Series A | $15M (~10% dilution) | TBD — opening end of May |

- Previous round at $34M post (per founder).
- Series A starts end of month; ~2 weeks to "open formula."
- Goal: GA by EOY 2026, then Series B at $5M ARR.
- Investment deck requires voiceover presentation; webinar videos and technical papers available.

## Deal Team Notes

- Met 2026-05-08 with Daria Davydenko (Fin) and Ciro Greco (Bauplan, CEO). See [[Bauplan - 2026-05-08 Summary]].
- Repeat founder (Tooso → Coveo exit). Strong angel/SPC backing including Wes McKinney, Aditya Agarwal, Spencer Kimball.
- Ciro available week of May 19 for in-person SF or NYC follow-up.

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Schedule in-person follow-up week of May 19 (SF or NYC)
- [ ] Request investment deck with voiceover + technical papers
- [ ] Diligence on agent-workload customer use cases (Media for Europe, Real Page)
- [ ] Reference check with South Park Commons and Innovation Endeavors
