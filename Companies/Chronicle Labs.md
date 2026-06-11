---
type: company
sector: enterprise AI
sub_sector: AI agent simulation / pre-production testing
stage: Seed
status: sourcing
owner:
founded:
hq:
website: https://chronicle-labs.com
linkedin:
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-06-10
created: 2026-06-10
tags:
  - company
---

# Chronicle Labs

> [!summary] One-Liner
> Simulation environment for enterprise AI agents — captures production events across enterprise systems and reconstructs them as replayable "traces" so agents can be stress-tested against full production scenarios before they touch customers, revenue, or compliance. Analogy: flight simulator / crash test facility for AI agents. Current YC batch. $45K MRR, growing from $5K at YC entry. Raising $4M on $40M cap ($1M closed).

---

## Thesis Fit

**Why we like it:**
- Co-founders bring rare autonomous-systems pedigree — Ayman (JPL/NASA, Mars rover landing, hundreds of thousands of pre-launch simulations) and Rawan (Boeing, led 737 Max fleet return-to-service, brokered Microsoft Flight Simulator pilot training integration). Domain-expert founders solving an enterprise AI-agent problem with mission-critical aerospace simulation playbook.
- Enterprises are stuck in slow phased rollouts (5% of users, months of iteration) because no proper validation layer exists for AI agents — Chronicle compresses the cycle via full production replay before launch.
- Inbound pipeline post-launch (3 weeks pre-meeting) is enterprise-grade: Verizon LOI (~1B calls/year, building agents fully in-house), Row Banking pilot, American Express, Adyen.
- Handshake AI approached with acquisition offer; declined — founder conviction signal.

**Relevant thesis:** [[]]

**Fin sub-sector:** Enterprise AI / AI Agent Infrastructure

---

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Ayman Saleh]] | Ex-JPL/NASA — worked on Mars rover landing (hundreds of thousands of simulations pre-launch); Deutsche Bank quant researcher background |
| Co-Founder | Rawan | Ex-Boeing — led 737 Max fleet return-to-service; brokered Microsoft Flight Simulator pilot training integration |

> Harmonic search_companies_natural_language timed out (two attempts, 5s backoff); entity_lookup on Chronicle Labs and Ayman Saleh confirmed both but did not return URNs for detailed enrichment. Co-founder Rawan's full last name not captured in Granola summary — flagged in Next Steps.

---

## Business Description

- **Problem:** Enterprises deploying AI agents have no proper validation layer. Default path is slow phased rollout (5% of users, months of iteration) because failures land on real customers, revenue, or compliance.
- **Product:** Simulation environments built from production logs. Captures events across enterprise systems, reconstructs them as replayable "traces," and places agents into simulations to surface failures before they touch customers.
- **Wedge / entry point:** Enterprises that are building their own agents in-house (~75% of Chronicle's use cases) — not just companies adopting Sierra / Giga style agent builders.
- **Analogy:** Flight simulator / crash-test facility for AI agents.

## Market & Competition

- **Direct competitors:** None building enterprise simulators for AI agents per founder.
- **Adjacent:** Observability tools (Braintrust, Raindrop) — Chronicle integrates with Braintrust rather than competing.
- **RL environments space:** Handshake AI (lab-aligned) approached with acquisition offer; declined.
- **Differentiation:** ~75% of customers are enterprises building their own agents in-house, where the pre-launch validation gap is widest. Direct production replay rather than synthetic eval sets.

## GTM & Business Model

- **Pricing (as of 2026-06-10):** Target ACV ~$100K; founder believes pricing is currently low and expects usage-based expansion as agent adoption grows.
- **Data access:**
  - One-click OAuth connectors for SaaS webhook events
  - Self-hosted deployments (cloud-formation template in customer's AWS); customer owns all data
  - SOC 2 Type 2 in progress; self-hosting has been sufficient for large enterprises and HIPAA customers
- **Entry persona:** VP of Customer Support (Kofi at Remedy Meds) — trickled down to engineering team.

## Traction

- **MRR (as of 2026-06-10):** $45K — up from $5K at YC entry (current batch).
- **Flagship case study — Remedy Meds** (large US telehealth co., ~30% of US telehealth market by volume): caught two critical agent failures pre-launch (retention offers sent to patients reporting side effects; structurally impossible discount offers). Fixed across all production scenarios and launched confidently within 48 hours.
- **Largest paying customer — Red Cat Holdings** (publicly traded): ~$200K ACV.
- **Pilot starting end of June 2026:** QC Healthcare (pediatric).
- **Inbound pipeline (post-launch ~3 weeks pre-meeting):**
  - **Verizon** — LOI signed, came inbound after product launch, ~1B calls/year, building agents fully in-house
  - **Row Banking** — pilot expected end of month
  - **American Express** and **Adyen** — in advanced conversations
- **Longer-term vision:** "agent factories" — a dashboard showing enterprises which agents are ready to spin up, back-tested against 180 days of production data via a continuous RL loop.

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| Current YC batch | YC participation | TBD | Y Combinator |
| In progress (June 2026) | Seed | $4M on $40M cap | $1M already closed; fundraise launched Monday 2026-06-08 |

- **Acquisition offer:** Handshake AI extended an acquisition offer — declined.
- **Investor profile sought:** Investors with enterprise and banking distribution; Ayman's Deutsche Bank background is the leverage point.

## Deal Team Notes

- 2026-06-10 — First Granola-captured intro call. Stephanie Perez (Fin) and Ayman Saleh (Chronicle, Founder/CEO). Derek Wu also on the call (note creator). Granola id `10fa8cc5-bab9-4bd0-a6f2-fb12a196e7a9`. See [[Chronicle Labs - 2026-06-10 Summary]].
- **Time-sensitive:** Fundraise launched Monday 2026-06-08; $1M of $4M already closed. Fin's stated process per Stephanie: portfolio conflict check → diligence → IC → partner presentation. Stephanie committed to feedback by 2026-06-11.
- Verizon LOI is the most attention-grabbing signal — large-enterprise inbound pull at YC batch stage is unusual; worth probing for substance (sales cycle stage, contract value).
- Founder pedigree (JPL Mars rover + Boeing 737 Max simulation) is differentiated and on-thesis with the company's actual product approach.

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Stephanie to share feedback and portfolio conflict-check outcome by 2026-06-11
- [ ] Ayman to send pitch deck to Derek and Stephanie
- [ ] Confirm co-founder Rawan's full last name and add to Harmonic
- [ ] Diligence Verizon LOI — sales cycle stage, contract value, in-house build vs. Chronicle scope
- [ ] Reference Kofi (VP Customer Support, Remedy Meds) — entry persona; how did the 48-hour fix actually play out
- [ ] Reference Red Cat Holdings ($200K ACV, largest paying customer)
- [ ] Validate "no direct competitors" claim against active RL-environments space (Handshake AI named)
- [ ] Confirm SOC 2 Type 2 timing and which enterprises have signed under self-hosted deployment to date
