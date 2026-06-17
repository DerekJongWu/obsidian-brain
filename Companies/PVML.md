---
type: company
sector: data infrastructure
sub_sector: Data security / virtual database for AI access
stage: Series A
status: sourcing
owner:
founded: 2020
hq: Tel Aviv-Yafo, Israel
website: https://pvml.com
linkedin: https://linkedin.com/company/pvml
crunchbase: https://www.crunchbase.com/organization/pvml
pitchbook: https://pitchbook.com/profiles/company/510632-11
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-06-16
created: 2026-06-16
tags:
  - company
---

> [!info] One-Liner
> PVML is a "virtual database" layer that sits between live production databases and AI/BI/API consumers — intercepting queries, applying deterministic security guardrails, rewriting and returning sanitized results, with no data movement and sub-3ms added latency.

## Thesis Fit

- Enterprise AI deployment unlock — most orgs ran 2025 POCs without data security and now need guardrails to ship to production in 2026.
- Wedge: connect sensitive production data to AI agents/apps without duplication, encryption-of-copies, or LLM-in-the-loop access control.
- Founder PhD-in-data-protection + ex-Microsoft co-founder + 18-person team in Tel Aviv with $1.9M ARR fits Fin's pattern of Israeli infra companies hitting commercial inflection.

**Relevant thesis:** [[]]

## Team

| Role | Person | Background |
|---|---|---|
| CEO & Co-Founder | [[Shachar Schnapp]] | PhD in Computer Science (data protection), Ben-Gurion University; ex-General Motors (Computer Vision/Deep Learning, Autonomous Vehicles, 2018–2020); ex-Infinidat (C++ engineer); Israeli Air Force software developer |
| CTO & Co-Founder | Rina Galperin | Ex-Microsoft (5 yrs, Software Engineer Data & Applied Science, Herzliya R&D); M.S. CS, Ben-Gurion; Israeli Navy military photographer |
| VP R&D | Bar Haim | Ex-JFrog (R&D Team Lead, ~5 yrs Sunnyvale + Israel); joined PVML March 2023; promoted to VP R&D April 2024 |
| VP Revenue & GTM | Natalie Lubelchick | Founder/CEO Aware (2021–2024); Z Fellows; PhD candidate Physics, Tel Aviv University; IAF simulator instructor |

## Business Description

- **Problem:** Enterprises cannot connect sensitive production data to AI/BI/API consumers without violating data-protection requirements. Today's workarounds — encrypt a duplicate of the data and re-point clients at it — are slow, impractical at scale, and break the production source of truth. Some teams skip security entirely and risk corrupting databases (NACS example cited).
- **Product:** A "virtual database" that intercepts queries between consumers and the underlying database. Applies dynamic, user-level permissions and proprietary mathematical guardrails; rewrites queries and returns sanitized results. **No data movement or duplication. Transparent to existing code (swap the connection string).** Deterministic security — no LLM in the access-control path. Sub-3ms added latency. Supports 9 database types, unifies security policy across all of them. Integrates with existing IAM. Supports MCP, ODBC, JDBC, agent-to-agent protocols.
- **Wedge:** Enterprises that ran AI POCs in 2025 and now need to ship to production with deterministic data-security guardrails.

## Market & Competition

- **Market timing:** 2025 was POC year (no security); 2026 is production year (guardrails required). PVML positioned as the missing piece between live production data and AI consumers.
- **Differentiation:** Deterministic (mathematical) guardrails — no LLM in the access path. No data movement (vs. encrypt-and-duplicate workarounds). Single policy plane across 9 DB types.
- **Adjacents / alternatives:** in-house encrypt-and-duplicate workarounds; manual access policies in BI tools; LLM-based access control (which PVML positions as non-deterministic).

## GTM & Business Model

- **Buyer persona:** Enterprise data/security/AI leaders shipping AI into production over sensitive production data — financial services and government early.
- **Pricing model:** **Flat infrastructure fee + usage-based overage ("PVML units")**. Existing customers already exceeding their packages — strong NRR expected.
- **ACV:** average ~$250–270K. Top customer (VisionWave) $600K.
- **Channel:** Accenture program — 10 banks competed to work with PVML; most companies get 2–4.
- **Integrations:** MCP, ODBC, JDBC, agent-to-agent protocols; existing IAM systems.

## Traction

- **ARR (2026-06-16):** $1.9M, targeting **$10.6M ARR by end of Q2 2027**
- **Customers:** 6 paying customers; top (VisionWave) $600K; avg deal size $250–270K
- **Selling for 10 months** (since ~Aug 2025)
- **Active pipeline:** Wells Fargo, JPM, AQR (POC complete → commercial/legal), IDF (in POC)
- **NRR signal:** existing customers already exceeding their packages

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| 2023-12 | Seed | $7M (NFX led) | NFX, FJ Labs, Gefen Capital, Erez Yarkoni, Ran Nahmias, Jonathan Lebowitsch, Amit On |
| TBD | SAFE | $2M | Papaya Global founder ($180M cap, 50% discount) |

**Total raised to date:** ~$9M (Harmonic shows $8M; founder cited ~$9M including Papaya Global founder SAFE)

**Current round (2026-06-16):**
- Raising **$30–40M Series A**
- **Focused on finding a lead first** — strong follower interest but limited room
- Founder's explicit ask: indicate quickly whether Fin can lead, or stand down so Shachar can prioritize other conversations
- If Fin can't lead: Shachar will circle back once lead is set, if room remains
- Harmonic valuation $40M (estimated from 2023 $8M seed @ ~20% dilution) is stale — pre-Papaya SAFE, pre-current Series A

## Deal Team Notes

- 2026-06-16 — Teams intro pitch with Jake Fuchs + Derek Wu. Shachar walked through product, traction ($1.9M ARR, 6 customers, $250K avg), Accenture program, and current $30–40M raise.
- Co-founder Rina Galperin (ex-Microsoft, 5 yrs) hit the data-protection-meets-AI problem firsthand alongside Shachar; both have direct domain experience.
- Papaya Global founder's SAFE is a notable inbound signal — came in after trying to buy the product (told as a founder anecdote).
- Founder is explicit about lead-or-stand-down — has not yet picked a lead but expects to soon. Time-sensitive decision for Fin.

## Meetings & References

```dataview
TABLE date, type, meeting_type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Indicate quickly whether Fin can seriously consider leading (Shachar's ask) — Derek + Jake to discuss internally and revert
- [ ] Review deck once Shachar sends it
- [ ] Diligence Accenture program economics (10-bank bake-off; PVML selected)
- [ ] Diligence NRR / package-overage dynamic with VisionWave + 5 other paying customers
- [ ] Validate Wells Fargo / JPM / AQR / IDF pipeline timing
- [ ] Reference Rina Galperin's Microsoft tenure (Data & Applied Science, Herzliya) and Shachar's General Motors AV research
- [ ] Compare deterministic-guardrail positioning vs. emerging LLM-based access-control vendors
