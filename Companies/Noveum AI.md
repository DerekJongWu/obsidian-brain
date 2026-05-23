---
type: company
sector: "AI infrastructure"
sub_sector: "AI agent observability & reliability"
stage: "Pre-seed"
status: "sourcing"
owner:
founded: 2023
hq: "San Francisco, California"
website: "https://noveum.ai"
linkedin: "https://linkedin.com/company/noveum-ai"
crunchbase: "https://www.crunchbase.com/organization/magicapi"
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-05-22
created: 2026-05-22
tags:
  - company
---

> [!info] One-Liner
> Noveum AI is an AI agent monitoring and reliability platform — integrates at the application layer to track every LLM/RAG/tool call across an agent trajectory, scoring hallucinations, policy adherence, and conversation flow so enterprises (banks, telecom) can scale agent deployments with visibility into failures.

## Thesis Fit

- AI infrastructure / agent observability — adjacent to AI agent governance (overlaps with [[Witness AI]], [[Guard0]] runtime layer) but focused on reliability/performance vs. security/governance
- BFSI traction (Vanguard POC, Deloitte $8K POC with $100K+ ACV potential) lines up with Fin's FinServ enterprise relationships
- Founder is a deeply technical repeat operator (AWS SageMaker, Amazon ML platform, Activeloop CTO) — exactly the profile for an infrastructure category

## Team

| Role | Person | Background |
|---|---|---|
| Founder & CEO | [[Shashank Agarwal]] | Founder/CEO since June 2025; ex-Amazon (Senior SWE, Nov 2022–Jun 2024, London); ex-AWS SageMaker (built initial version); ex-Activeloop (CTO, Mar–Jun 2021); ex-PipFeed (Founder); MS Computer Science, The Ohio State University; ~12 years AI experience |
| Co-Founder & Chief Growth Officer | Additi Upadhyay | Co-Founder & CGO since Dec 2024; ex-SambaNova (Product & Growth, 2024–2025); ex-Spenmo (Founding Member, Product & Growth, 2019–2024); IIM Lucknow (Data Driven PM) |

## Business Description

- **Problem:** Banks and large enterprises deploy AI agents handling 100K+ daily conversations with zero visibility into errors — hallucinations, wrong policies, and compliance issues go undetected. Problems are only discovered when customers screenshot and complain (~2-week fix cycle), which prevents scaling agent deployments.
- **Product:** Integrates at the application layer inside agent code and monitors the complete agent trajectory — every LLM call, RAG call, tool call, system-prompt adherence, parameter correctness, tool relevancy, and task-progression efficiency. A scoring system evaluates content safety, hallucination, conversation flow, toxicity, uncertainty, and goal achievement, with priority levels (high/medium/low) computed from impact + frequency. Tracks/stores call history and can record call audio.
- **Wedge:** Application-layer placement (not network/eBPF) means deep semantic visibility into agent behavior beyond what infra-level observability can see. Roadmap includes automated code fixes via GitHub PRs with backtesting.

## Market & Competition

- AI agent observability / reliability — fast-emerging category alongside LLM-evals
- Competitors named on call:
  - **Langfuse** — beaten at Deloitte
  - **Secura** — beaten at Exotel
- Adjacent: agent-security players ([[Guard0]], [[Witness AI]]) — Noveum positioned for reliability/performance vs. security/governance
- Differentiation: full trajectory monitoring (LLM + RAG + tool call) with priority-weighted scoring, planned auto-remediation via PRs

## GTM & Business Model

- Target buyer: agent builders (Deloitte, KPMG) and direct enterprise — primary verticals BFSI (immediate ROI) and retail/ecommerce
- Pricing model: per agent + volume (conversations/invocations) + evaluation count
- Active POCs:
  - **Deloitte** — $8K / 30-day POC, $100K+ ACV potential
  - **Vanguard** — internal chatbot reliability (met at Dubai conference)
  - **Siemens** — pipeline
  - **Five9** — pipeline

## Traction

- 8–9 months building platform; 2 months onboarding customers (as of 2026-05-22)
- Current paying customers (as of 2026-05-22):
  - **Alpha Vantage** (YC company, stock API)
  - **Exotel** (30% of India telephony, fixing Uber agents)
  - **Reliance Jio** (India's largest telecom)
- Pipeline ARR: ~$983K from existing customers / ~$1M ARR (as of 2026-05-22)
- Won competitive evaluations against Langfuse (Deloitte) and Secura (Exotel)

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| Pre-2026 | Angel | $150K | (angels, names not disclosed) |
| 2026 (in progress) | Pre-seed | Targeting $2.5–3M | Rolling basis starting "Tuesday" with angels, then VCs |

- Current raise: $2.5–3M pre-seed, open to Fin leading the round (as of 2026-05-22)
- Not optimizing for valuation; seeking strategic partners
- Harmonic shows VENTURE_UNKNOWN stage / $0 funding recorded (likely undercount given $150K angel) — confirm cap/structure in next touch

## Deal Team Notes

- 2026-05-22: Intro call with Shashank Agarwal (Founder/CEO); Derek Wu on Fin side
- Founder cited Logan as natural next step for a partner call
- Round is rolling — angels onboarding starting "Tuesday" — short decision window if Fin wants to lead
- Strong AI/infra resume (AWS SageMaker, Amazon ML platform, Activeloop CTO) but limited track record from prior founder attempts (Hopdata, PipFeed, API.Market — all still listed as current per Harmonic) — diligence resource focus/cap-table cleanliness
- BFSI + retail/ecom focus aligns with Fin LP base (US Bank, Vanguard prospect) — potential intro leverage

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Derek to sync at Wednesday Fin pipeline meeting
- [ ] Schedule partner call with Logan (managing partner)
- [ ] Shashank to send sales deck and demo materials
- [ ] Follow-up timing: late next week or early week after (post-holiday)
- [ ] Diligence: confirm round cap/structure, Shashank's commitment to Noveum vs. parallel ventures (API.Market still listed as current), reference Vanguard / Deloitte POCs
