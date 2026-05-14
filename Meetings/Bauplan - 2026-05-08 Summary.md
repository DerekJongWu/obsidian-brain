---
type: meeting
date: 2026-05-08
company: Bauplan
attendees: Derek Wu, Daria Davydenko, Ciro Greco
meeting_type: intro
transcript: "[[Bauplan - 2026-05-08 Transcript]]"
created: 2026-05-08
tags:
  - meeting
---

[[Bauplan]] | 2026-05-08 | Intro

## Attendees

- [[Daria Davydenko]] (Fin Capital)
- Derek Wu (Fin Capital)
- [[Ciro Greco]] (Co-Founder & CEO, [[Bauplan]])

## Transcript

[[Bauplan - 2026-05-08 Transcript]]

## Company Overview & Product

- Bauplan: Data platform for autonomous AI agents
  - Entire platform expressed as code with typed APIs
  - Documentation fits in LLM context window
  - Built on "git for everything including data" concept
- Core problem: Current data infrastructure (Databricks, Snowflake) not built for agents
  - No code-first interfaces, too human-centric
  - Agents run 10x more compute than humans
  - Cost structure unsustainable at agent scale
  - Example: Customer runs 60,000 operations/week vs typical human usage
- Solution approach:
  1. Zero-copy data branching for safe agent experimentation
  2. Custom runtime for order-of-magnitude cost efficiency
  3. Transactional isolation preventing agent conflicts

## Traction

- 6 customers in controlled rollout, all inbound
- Revenue: ~$300K ARR, projecting $560K by September
- Customer progression: Free tier → $700/month → up to $10K/month
- Notable customers:
  - Media for Europe ($5B broadcaster)
  - Real Page (US real estate SaaS)
  - N26 (in pipeline)
  - Nexi (European payment processor, in pipeline)
  - MOB (South American credit/background checks)
- Target ACV: $100K (already achieved with one customer)

## Financing & Growth

- Raising $15M Series A — probably giving up ~10%
- Previous round: $34M valuation
- Timeline: Starting process end of month, ~2 weeks to open formula
- Goal: Reach general availability by end of year, then Series B at $5M ARR
- Key requirements for enterprise customers:
  - RBAC system (currently basic)
  - Formal SLAs (currently Slack-based support)
- Strong financial services pipeline but need product maturity first

## Next Steps

- Follow up for in-person meeting in San Francisco or New York
  - Ciro available week of May 19
  - Investment deck requires voiceover presentation
- Materials available: webinar videos, technical papers
