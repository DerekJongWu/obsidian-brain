---
type: company
sector: cybersecurity
sub_sector: Security telemetry / detection-engineering platform
stage: Series A
status: sourcing
owner:
founded: 2024
hq: New York, NY (R&D in Israel)
website: https://brava.security
linkedin: https://linkedin.com/company/bravasecurity
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-06-16
created: 2026-06-16
tags:
  - company
---

> [!info] One-Liner
> Brava Security is building an "interpretation layer" between raw security telemetry and downstream SIEM / detection / compliance tools — agents trained on CTFs map every attacker behavior to its telemetry pattern, surfacing coverage gaps, better detections, and dramatic log-cost reduction.

## Thesis Fit

- "Telemetry is to security what electricity was to the light bulb" — most teams can't access, parse, or act on their own telemetry. Brava adds a "brain" on top of pipelines (vs. Cribl, which moves data blindly).
- Near-term wedge: AIC (AI-driven SOC) buyer persona for the next 24 months.
- Long-term: horizontal telemetry platform across security, identity, vuln management, GRC.
- Founder/team pedigree (Unit 8200 ARAM commander, Microsoft, DARPA, Intelligence Force) aligns with Fin's bias toward Israeli cyber founders with deep technical roots.

**Relevant thesis:** [[]]

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Idan Basre]] | 10 yrs vulnerability researcher; Commander of Unit 8200's ARAM course (specialized vuln research track); ex-Senior Product Manager at Microsoft (SaaS Security Posture Mgmt, Defender); Hebrew University B.Sc Physics/Math (Talpiot Class XXXI); based NYC (moved ~5 months ago) |
| CTO | Itai Gabai | Former collaborator at Intelligence Force; built anomaly-detection project with US DARPA; built pre-SageMaker ML platform on top of Reddit; presented at KubeCon in IDF uniform |

## Business Description

- **Problem:** Security teams generate massive telemetry across endpoints, identity, cloud, and SaaS, but can't access it, parse it, or map it to attacker behaviors. The result: detection gaps, runaway SIEM/log costs, and reactive posture.
- **Product:** Interpretation layer that sits between raw telemetry sources and downstream tools (SIEM, detection, compliance). Agents trained on CTFs (capture-the-flag exercises) learn the mapping between every attacker behavior and its telemetry footprint. Outputs: coverage gaps, detectability gaps, improved detections, and log-cost reduction.
- **Wedge:** AI-driven SOC (AIC) buyer persona — security teams already adopting AI tooling and willing to pay for a brain layer that makes their telemetry actionable.

## Market & Competition

- **Differentiation vs. [[Cribl]]:** Cribl moves data blindly (cost-optimization pipeline); Brava adds a brain — CTF-trained agents map behavior → telemetry, so reduction is detection-aware, not blind volume cuts.
- **Cushman Wakefield benchmark:** 93% log-cost reduction with Brava vs. 27% with Cribl alone.
- **Adjacent:** Databricks, Exabeam — positioned as cost-focused, not security-focused (per founder framing).
- **Vertical spread (current/pipeline):** retail, healthcare, finance (Toronto/Montreal stock exchanges, Form 3 in pipeline).

## GTM & Business Model

- **Buyer persona:** AI-driven SOC teams at mid-market to F500 enterprises across retail, healthcare, finance.
- **Pricing / contracts:** annual subscription; representative ACVs — McDonald's $250K/yr, Cushman Wakefield $405K/yr (just closed), Well Health $75K/yr (Canadian healthcare, ~5K employees, expansion potential), Fortune 500 pipeline $270K.
- **Sales motion:** AI-driven outbound agents for ICP research and warm LinkedIn intros, supported by two outsourced sales reps.

## Traction

- **ARR (as of 2026-06-16):** ~$400K, targeting **$1.2M by year-end 2026**
- **Logos:** McDonald's ($250K/yr), Cushman Wakefield ($405K/yr — just closed), Well Health (Canada, $75K/yr)
- **Pipeline:** Fortune 500 ($270K), Toronto/Montreal stock exchanges, Form 3
- **Vertical spread:** retail, healthcare, finance

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| 2024 (Summer) | Seed | $8M | Pitango, F2 |

**Current round (2026-06-16):**
- Raising **$15M Series A** (launched ~1 week prior to meeting)
- Wants a **US-based lead** (not solely Israeli VCs)
- Cap table: Pitango + F2 hold ~36% combined
- Pre-existing investors (Pitango, F2) cited as models for the kind of strategic value-add Idan wants — board members with strategic counsel, not just commercial intros

**Corporate:**
- Delaware-incorporated; R&D in Israel, commercialization in the US
- Team size: 15 (all R&D + one video, one ops, plus Idan)

## Deal Team Notes

- 2026-06-16 — Teams intro call with Richie Chaikof + Derek Wu. Referred by Barak (IGA) — Richie/Derek are in advanced discussions with Barak.
- Idan's founder ask: **strategic counsel and smart board members**, not just commercial intros. Explicitly does not want a fully Israeli syndicate — needs a US-based lead.
- Shai (Unit 8200 alumnus, Fin portfolio) flagged as a potential reference; Richie offered to broker the intro.
- In-person follow-up scheduled for Mon/Tue (Soho); Idan to share deep-dive materials in person rather than pre-send.
- Harmonic record is sparse: company shows headcount 2, $0 funding, no founding date — Harmonic likely indexes the company under a stealth identifier (Idan's Harmonic profile still lists "Stealth Company (Idan Basre)" as current role). Data in this note sourced from founder narrative on 2026-06-16.

## Meetings & References

```dataview
TABLE date, type, meeting_type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] In-person deep-dive in Soho (Mon/Tue) — Richie/Derek to send invite
- [ ] Idan to share deep-dive materials in person
- [ ] Broker intro to Shai (Fin portfolio, Unit 8200 alum) as reference
- [ ] Diligence Cribl-vs-Brava log-cost benchmark (Cushman Wakefield 93% vs. 27%)
- [ ] Validate ARR ramp ($400K → $1.2M by year-end) against pipeline conversion
- [ ] Confirm CTO Itai Gabai full background + DARPA / KubeCon references
- [ ] Reconcile with Barak (IGA) referral context — coordinate diligence timelines
