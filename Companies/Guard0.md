---
type: company
sector: "cybersecurity"
sub_sector: "AI agent security / AI-SPM"
stage: "Pre-seed/Seed"
status: "sourcing"
owner:
founded: 2025
hq: "San Francisco, California"
website: "https://guard0.ai"
linkedin: "https://linkedin.com/company/guard0"
crunchbase:
pitchbook: "https://pitchbook.com/profiles/company/1372745-35"
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-05-11
created: 2026-05-11
tags:
  - company
---

> [!info] One-Liner
> Guard0 is an AI Security Posture Management (AI-SPM) platform for AI agents and agentic workflows — discovering every AI agent across code, cloud, and agent platforms, mapping blast radius, and monitoring runtime behavior to enforce policy and stop rogue activity in real time.

## Thesis Fit

- Aligns with Fin's AI-security thesis — specifically the AI agent governance pillar (overlaps with [[Witness AI]], Noma space, and adjacent to [[Pluto Security]])
- Founder is a repeat security operator with strong API/observability background (Traceable acquired by Harness for ~$1B)
- Enterprise traction in financial services (JPMC, Charles Schwab, National Bank of Dubai) is directly Fin-aligned
- Profitable at the end of Q2 2026 — capital-efficient profile rare in this category

## Team

| Role | Person | Background |
|---|---|---|
| Founder & CEO | [[Jayesh Ahire]] | ex-Traceable (6 yrs) — built/ran open-source observability platform Hyper; ran EMEA + APAC sales, closed $2.5M; Stanford masters; worked with AI lab |

## Business Description

- **Problem:** Rapid proliferation of AI agents (vendor-deployed, internally-built, and service-provider-sold) creates an inventory, governance, and runtime risk problem that existing security stacks don't cover.
- **Product:** AI-SPM platform that uses access to cloud and code platforms to discover every AI service / agent, maps blast radius and what each agent can access, then monitors runtime behavior. Identifies deviation in behavior vs. intent and deviation from governance policies. Built-in catalog of AI agents plus customer-built agents on top of Guard0 data.
- **Wedge:** Agentless discovery via cloud/code platform access (filed IP on the methodology); 95% inventory accuracy with business context mapping; on-prem / air-gapped deployment option.

## Market & Competition

- AI agent security is an emerging category — three types of agents Guard0 covers:
  1. Databricks and Snowflake agents (research/business specific)
  2. Agents built on customers' own internal agent-building platforms
  3. Agents sold by service providers (ServiceNow, Notion, etc.)
- Differentiation:
  - Agent-building-platform agnostic
  - Completely agentless — no proxy, no eBPF, self-service
  - On-prem / air-gapped deployment supported; most SLMs run locally
  - Open data — customers can build custom workflows/reporting on Guard0's data without using Guard0 dashboards
- Adjacent / overlapping: [[Witness AI]] (network-level agent compliance), [[Pluto Security]] (AI endpoint security)

## GTM & Business Model

- Enterprise sales (not PLG)
- Sales motion started January 2026
  - 18 long-term POVs deployed
  - Conversion push starting April 2026
- Customers:
  - National Bank of Dubai (deployed)
  - JPMC (deployed)
  - Charles Schwab (deployed; conversion target Q3)
  - AMEX (next quarter)
  - Eli Lilly engaged to build their internal-agent-platform governance layer
- Enterprise customers can build custom workflows and reporting agents on top of Guard0's data

## Traction

- Closing at $750K ARR this quarter (as of 2026-05-11)
- Near-final OEM deal with $3.5M TCV (Indian company, APAC market)
- Year-end target: $1.5M ARR
- Pipeline: $9.5M
- Profitable at end of current quarter (~$250K above spend)

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| 2025-11 | Pre-seed (SAFE) | $1.5M | Angels, some system integrators, some strategics |
| 2026 (in progress) | SAFE | Targeting $6-8M | $3.5M already committed from previous round; ~$4.5M remaining over next 2 weeks |

- Cap: $35M pre-money on current SAFE
- Founder strategy: SAFEs now, larger priced round at end of year with more traction
- Founded January 2023 per Harmonic; product launched ~6 months before this meeting per founder

## Deal Team Notes

- 2026-05-11: Intro / diligence call with Jayesh Ahire (Founder/CEO); Derek Wu on Fin side
- Founder phone: 650-509-8537
- Current SAFE is filling fast — $4.5M remaining over ~2 weeks at $35M cap; decision window short
- Worth assessing overlap/conflict with [[Witness AI]] and [[Pluto Security]] before deepening
- Harmonic record shows 0 headcount and no funding recorded (likely undercount for stealth)

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Internal: assess overlap with [[Witness AI]] and [[Pluto Security]] (AI security pillar conflicts)
- [ ] Validate JPMC / Charles Schwab / National Bank of Dubai deployments via Fin's bank LP network
- [ ] Confirm OEM deal economics and APAC partner identity
- [ ] Decide on participation in current $4.5M SAFE remaining
- [ ] Track end-of-year priced round
