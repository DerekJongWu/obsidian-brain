---
type: meeting
date: 2026-06-17
company: Forestrat
attendees: Derek Wu, Logan Allin, Matthew Mann, Jake Fuchs, Jacquelyn Arnold, Anand Chavan, Jacob Kaippallimalil
meeting_type: in-person
transcript: "[[Forestrat - 2026-06-17 Transcript]]"
created: 2026-06-17
tags:
  - meeting
---

[[Forestrat]] | 2026-06-17 | In-Person (Fin NYC)

## Attendees

- [[Anand Chavan]] — Co-Founder, Forestrat
- [[Jacob Kaippallimalil]] — Co-Founder, Forestrat (AI / unstructured data)
- Derek Wu — Fin Capital
- Logan Allin — Fin Capital
- Matthew Mann — Fin Capital
- Jake Fuchs — Fin Capital
- Jacquelyn Arnold — Fin Capital

## Transcript

[[Forestrat - 2026-06-17 Transcript]]

## Product & Technical Approach

- Core platform: data strategy layer ingesting structured + unstructured data via shared pipelines (web scraping, PDFs, FTP, email attachments).
  - Ontologies defined per vendor, auto-generated via agents where missing.
  - Extraction uses historical similarity, agentic approaches, and ELM (ensemble LLM scoring).
  - Output verified by agentic actor/checker models; human monitor for urgent cases (e.g. trade ideas).
  - Unstructured piece feeds into the data strategy platform as a standalone vendor layer.
- Vision: "hedge fund in a box" covering the full stack — data, research insights, custom unstructured datasets, signal generation, execution (direct, broker, or via partners like TestX), and post-trade TCA.
  - Apple ecosystem analogy: single point of contact, everything modular.
  - Agentic overlay planned once unstructured piece ships; on-prem hosting supported for privacy/compliance.
  - Code-generation model: LLM generates Python against ontology schema rather than querying raw data directly, keeping external model use safe.

## Positioning (Logan's framing)

- Position explicitly as "agentic AI-first" company, not just a data platform.
- Current story doesn't land that way yet; marketing and positioning need to catch up to the vision.
- Hedge funds and agency desks are thinly staffed and legally blocked from using tools like Claude; on-prem agentic tooling is the unlock.

## GTM & Business Model

- Business model evolving toward **cost-plus with points on AUM** for smaller funds.
  - Avoids predatory optics by capping or gating the revenue share initially.
  - Gross margin on software component plus a share of the expanding pie.

## Traction & Pipeline

- **Anchor client:** Capilas (climate-focused capital allocator); one individual PM also onboarded.
- **Unexpected strong pull from mid-sized investment banks on agency trading desks**:
  - Want analytics and TCA to compete with larger players (UBS etc.) without the full build.
  - Two active conversations; no closed deal yet.
- **Exchanges:** conversation with NYSE head of market structure next Thursday.
  - Angle: research environment where clients can trial and consume exchange data, competing with Bloomberg on flexibility.
  - CBOE relationship also in play.
- **Data vendors:** FactSet reached out when Jacob left; non-compete expires June, conversations resuming July.
  - FactSet has a legacy unstructured data platform they've been trying to replace for years; open to collaboration.
  - Forestrat's pitch: bring the product, let FactSet leverage it for the build.
- **S&P CDO keen; compliance sign-off pending.**
  - S&P CEO of Market Intelligence recently departed; replacement is technology-centric, creating opening.
- **TestX** (7-8 years, 30-40 clients, execution-only): exploring a combined offering; TestX wants to stay in execution, not expand into data.
- **Trade ideas product:** aggregate semi-structured bank trade ideas into a private dataset per fund, score them.
  - Replaces the role of a vendor like "Ten" (banks now prefer sending data directly to hedge funds).
  - Estimated potential: tens of millions of dollars in that product alone.
- **Jefferies:** Jeff Johnson is an angel investor in Forestrat; sending buy-side contacts their way.
  - Met with Jeff's boss's boss today; relationship described as strong.
  - SMBC is Jeff's largest investor and one of Fin's largest LPs, useful connective tissue.
- **Prediction markets:** early-stage exploration.
  - Collecting data from Polymarket, Kalshi, and a few others.
  - Interest in correlating prediction market data with macro signals (e.g. CPI futures).
  - Fin portfolio company [[Mojo]]: best pricing and risk models in sports betting, current CEO from prop desk at Goldman; sports-only focus but potential data synergy.

## Next Steps

- Connect Forestrat to Brian (co-founder and CTO of Era) for potential research data synergy — Matthew on Era's board (Logan / Matthew).
- Explore Jefferies intro for agency trading desk conversations; Jeff Johnson willing to serve as reference (Forestrat to confirm).
- Connect Forestrat into SMBC and CIB relationships at Fin (Logan).
- Follow-up email from Forestrat to Fin after today's meeting (Anand / Jacob).
