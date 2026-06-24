---
type: company
sector: AI infrastructure
sub_sector: task-specific enterprise SLMs / agentic workflows for finance and audit
stage: Seed
status: sourcing
owner: 
founded: 2023
hq: Palo Alto, California
website: https://nace.ai
linkedin: https://linkedin.com/company/nace-ai
crunchbase: https://www.crunchbase.com/organization/nace-ai
pitchbook: https://pitchbook.com/profiles/company/718478-92
deck_link: 
data_room: 
lighthouse_link: 
last_touch: 2026-06-23
created: 2026-06-23
tags:
  - company
---

> [!info] One-Liner
> Nace AI develops AI agents that automate financial processes — particularly accounting and auditing — by leveraging customized task-specific language models. Built on a proprietary hypernetwork (metamodel) that generates SLM weights on the fly, deployed on an in-house H100 inference platform.

## Thesis Fit

Task-specific small language models with own inference stack, targeting privacy-sensitive enterprise verticals (Big Four audit, healthcare billing). Avoids LoRA's per-model overhead and removes the need for ML engineers per deployment.

## Team

| Role | Person | Background |
|---|---|---|
| CEO & Co-Founder | [[Dos Bahá]] | ex-GOAT.AI (CEO/co-founder), Sprint Squads, Otbasy.com, HSBC; KBTU (Kazakh-British Technical University) |
| COO & Co-Founder | Sudha Valluru | ex-Apple Camera (Center Stage, Cinematic Video), Google (Dir. Eng. YouTube/Video Search), Akruta (CEO), Baarzo (CEO, acq. Google), ViVu (CEO, acq. Polycom), IMG Academy VP Eng., Cisco; Drexel University |
| CTO & Co-Founder | Zhanibek Datbayev | ex-Celonis (Staff SWE), Facebook (Staff SWE), IPSY (Founding Engineer); Purdue MS |
| Co-Founder | Gareth Woolley | ex-Northeastern Institute for Experiential AI, WooliesX (Data Scientist), Pepper Money |
| Co-Founder | Satya Tummalapenta | ex-Nouveau Labs (Founder/CEO), ShoreTel (Head India Eng), Motorola Mobility |

## Business Description

- **Problem:** General-purpose LLMs underperform on enterprise workflows that require task specificity, privacy, and evidence trails. Per-model fine-tuning (LoRA) requires ML engineers per deployment.
- **Product:** Hypernetwork metamodel generates weights on the fly for target open-source SLMs. Self-perpetual feedback loop adjusts weights from task results. Own inference platform (H100s) built in-house — existing providers (Fireworks, Deep Infra) couldn't keep pace with new model releases. Enables full VPC deployments for fintech, insurance, healthcare.
- **Wedge:** NAVI for Financial Audit — planning, substantive testing, evidence generation.

### Product suite

- **NAVI for Financial Audit** (flagship): planning, substantive testing, evidence generation
  - Multi-year contract with a Big Four firm (unnamed; displacing OpenAI/$100M deal)
  - Continuous audit use case gaining traction (Tesla internal audit mentioned)
  - Anti-compete clause blocks selling to other Big Four firms
- **NAVI for Billing**: automated invoice generation with explainability
  - Detected several million dollars in revenue leakage for a healthcare staffing marketplace
  - Integrates with Salesforce, NetSuite, internal SQL databases
- **Next Context** (enterprise memory + reasoning): structured enterprise knowledge with evidence trails
  - Answers complex queries across Slack, GitHub, Linear, Cursor logs in 15-20 seconds
  - Differentiated from search tools (e.g., Glean) by reasoning and evidence layers
- Common platform across all three: document intelligence, model inference, agentic execution

## Market & Competition

- General LLM providers (OpenAI) bid for the same Big Four audit work — Nace displaced a $100M OpenAI deal.
- Adjacent tools: Glean (enterprise search) — Nace differentiates with reasoning and evidence layers.
- Specialization play vs. horizontal frontier-model providers.

## GTM & Business Model

- Target verticals: financial audit (Big Four), billing leakage, supply chain, healthcare billing.
- Privacy-sensitive industries favor VPC deployment with own inference stack.
- Sales motion: multi-year enterprise contracts (Big Four audit firm signed; Tesla in pilot).

## Traction

- Multi-year contract with unnamed Big Four firm (displaced OpenAI/$100M deal); anti-compete clause blocks other Big Four sales
- Tesla internal audit mentioned for continuous audit use case
- Healthcare staffing marketplace: detected several million in revenue leakage via NAVI for Billing
- ~30 people total (10-12 Palo Alto, rest in Astana, Kazakhstan)

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| 2026-05-05 | Seed | $26.5M total raised across 2 rounds | MVP Ventures, Coalition Operators, .406 Ventures, General Catalyst, Walden Catalyst Ventures, MA7 Ventures |

- Estimated valuation $108M (from $21.5M Seed round, ~20% dilution per Harmonic)
- Not actively raising; expect to re-enter market in ~1 quarter (Q3 2026)
- Revenues coming in; preference for controlled growth over aggressive raise
- Fin's check size ($250K-$20M) fits well; target ~$5-10M
- Preferred path: Fin provides customer introductions first as validation, then investment

## Deal Team Notes

- Founder credibility: Sudha (COO) is a multi-time founder w/ two acquisitions (Baarzo→Google, ViVu→Polycom); Zhanibek (CTO) ex-Celonis/Facebook Staff SWE
- Architecture moat: hypernetworks + own H100 inference stack — high technical bar
- Customer concentration risk: heavy reliance on single Big Four contract; anti-compete locks out further Big Four expansion

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Daria to identify LP / portfolio intros for Nace AI pilots (audit, billing leakage, supply chain, healthcare billing)
- [ ] Re-engage Nace AI on fundraising in ~1 quarter (Q3 2026)
