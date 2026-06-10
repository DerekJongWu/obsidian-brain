---
type: company
sector: cybersecurity
sub_sector: agentic AI security / reverse-proxy CASB
stage: Seed
status: sourcing
owner:
founded: 2025
hq: Tel Aviv, Israel
website: http://valorsecurity.ai
linkedin:
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-06-09
created: 2026-06-09
tags:
  - company
---

# Valor Security

> [!summary] One-Liner
> Two-sided reverse-proxy security layer for externally-facing agentic AI applications — modern CASB for the post-Sierra / Vesta era where vertical SaaS AI apps are publicly exposed to the internet AND have deep semantic access to enterprise data. Founded by the Axis Security GTM/product team (acquired by HPE for ~$500M). $8M of $10M seed closed (NFX-led, oversubscribed).

---

## Thesis Fit

**Why we like it:**
- Repeat-founder team out of **Axis Security** (acquired by HPE Enterprise for ~$500M at ~$15M ARR after 4.5 years) — credible GTM and product execution at SASE scale
- Distinct positioning vs. internal-facing AI security (Witness AI, Jordi, Onyx) — Valor protects the BUSINESS PROCESS itself, not the employee identity or internal user
- Vertical SaaS AI apps (Sierra, Vesta, Dekagon, Wonderful) are growing exponentially and are publicly exposed + have semantic access to enterprise data — clear infrastructure gap
- Strong technical bench from Unit 8200 (CTO Shaka Dek — designed scale infrastructure in army, founded Axonius, VP Product at Axis Security; VP R&D Omer — 7yr Israeli secret service, then Forter fraud detection)
- Active design partners across Adidas, Hub International, Otis, PennyMac, large Israeli healthcare provider; United Health Group (Fortune 8) in pursuit
- Seed oversubscribed; entertaining SAFE for pre-A; valuation $35M cap

**Relevant thesis:** [[]]

**Fin sub-sector:** Cybersecurity / Agentic AI Security

---

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Michael Magen]] | Ex-COO **Axis Security** (Mar 2023 – Nov 2025, through HPE acquisition); ex-VP Business & Operations + Director of Operations & Strategy, Axis Security (Feb 2019 – Mar 2023); ex-M&A Manager, **IBI Investment House** (Jul 2017 – Jan 2019); combat soldier in IDF special unit; ex-professional swimmer, **Israeli national champion and record holder, 1500 breaststroke**; 33 years old; based Tel Aviv, considering NYC relocation |
| Co-Founder & CTO | Shaka Dek (Granola rendering — full name not yet captured) | Ex-VP Product at **Axis Security** (early employee → engineer → leader → VP Product, ~3.5 years through HPE acquisition); ex-CTO at an ad-tech company likened to "Cambridge Analytica for Israeli elections"; founded a company called **Axonius** earlier (per Granola — full name and Harmonic confirmation pending); designed tech infrastructure at scale in army (**Unit 8200**, SaaS vulnerabilities specialization); ex-governmental offensive agency ("manager of this operation called free shoe" per Granola); Bachelor's in Computer Science (finished high school in 10th grade) |
| Co-Founder & VP R&D | Omer (last name not captured) | Served in IDF Unit 8200 alongside Shaka; 7 years at **Israeli secret service** (governmental agency); ex-**Forter** (fraud detection, sells to retailers like Nike); ex-Head of Infrastructure at a gaming startup (Set, raised money from Bessemer); based Israel |

> Per Harmonic, Valor Security's company record is sparse (urn:harmonic:company:75165674; only the website domain valorsecurity.ai is captured — no name, description, headcount, location, funding, or employees). Founder identified as **Michael Magen** (id 53663430) via entity_lookup match on "Michael COO Axis Security acquired by HPE swimmer Israeli national champion." Co-founders' full names (Shaka Dek, Omer) not yet resolved — flag for diligence.

---

## Business Description

- **Problem:** The new class of vertical SaaS AI apps (Sierra, Vesta, Dekagon, Wonderful) is publicly exposed to the internet AND has semantic access to enterprise data ("crown jewels"). Existing tools (Zscaler, Netskope, Witness AI) protect inside-out traffic; nobody protects outside-in.
- **Product:** Two-sided reverse-proxy that sits as an inline access broker for the enterprise.
  - **Input control:** authenticate request, validate credentials
  - **Prompt inspection:** detect malicious prompts
  - **File scanning:** scan uploads
  - **Context isolation engine:** "limit the context that it gets" — ensures the right caller gets only the right slice of data
- **Modern CASB framing:** When Salesforce launched (~2008/9), orgs uploaded customer data into a 3rd-party SaaS on implied trust; the CASB category emerged after Salesforce breaches. Valor is positioning as the same evolution for vertical AI apps — the security broker between the public internet and the enterprise data inside agentic services.
- **Example use cases (as of 2026-06-09):**
  - **Otis Elevator** — fully agentic customer service via Google Studio, publicly facing, needs a security broker
  - **PennyMac** — agentic mortgage / lending workflow (via Vesta)
  - Demonstrated ability to **probe publicly available agentic services to extract emails and send on a user's behalf** — the exact risk vector
- **Wedge / entry point:** Vertical AI applications that are exposed to consumers and gain access to enterprise systems — Valor sells WITH the vertical-AI app vendor into the enterprise, not waiting for the enterprise CISO to start a project.

---

## Market & Competition

- **Market:** Outside-in security for agentic AI applications — a new wedge category between WAF (Imperva) and external-facing CASB.
- **Key differentiator vs. Witness AI (per founder, 2026-06-09):**
  - Witness monitors **employee use of AI tools inside the org** (identity-aware, inside-out)
  - Valor secures the **business process itself**, not the identity or internal user (outside-in)
  - The founder's framing: "Who is the user? Is it an employee, or is it a consumer?" Witness assumes employee; Valor assumes consumer / outside actor.
- **Other adjacent / "not the same" companies named:** Witness AI, Jordi, Onyx (per founder — internal/identity-focused, not in Valor's scope); Reco AI (DLP inside org); Imperva WAF (closer in spirit but not agentic).
- **Independent validation:** Folks at **Dell Capital** (active investors in Zscaler) and **Zscaler itself** are aware of this blind spot and looking at the category (per founder, 2026-06-09).

## GTM & Business Model

- **Stage:** Pre-product; design partner phase (as of 2026-06-09)
- **Design partners (as of 2026-06-09):**
  - Adidas
  - Hub International
  - Otis (elevator)
  - PennyMac
  - Large Israeli healthcare provider (second largest in country — automated customer success via Wonderful)
  - DHL in pipeline
- **Pursuing:** United Health Group (Fortune 8) — meeting CEO in London next month at Amit Kif / Inside Ignite event
- **Buyer persona:** Vertical-AI vendors (Sierra, Vesta, Wonderful) co-selling into enterprises; enterprise security leaders responsible for outside-in agentic risk

## Traction

- **Product:** Not built yet (as of 2026-06-09)
- **Design partners:** Adidas, Hub International, Otis, PennyMac, large Israeli healthcare provider; DHL in pipeline
- Demonstrated ability to probe public agentic services to extract emails and send on user's behalf — research-led validation

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| In progress (June 2026) | Seed | **$8M closed of $10M total**; remaining $2M filling with angels | Lead: **Gigi Levy-Weiss (NFX)**; also AV from **Entrée Capital**, **Doron from Cyberstarts**, **Gila Zerant** |
| Optional / future | Pre-A (SAFE) | Entertaining offer | TBD |

- **Stage:** Seed (closing)
- **Valuation:** **$35M cap** (typical seed)
- **Status:** Oversubscribed; entertaining a SAFE offer for the pre-A
- **Note:** Harmonic has no funding record on Valor Security — captured from Granola summary + transcript only.

## Deal Team Notes

- 2026-06-09 — First Granola-captured intro call. Derek Wu and Fan Wen on Fin side; Michael Magen (CEO) on Valor side. Granola id `d3181228-cfbf-4976-be13-c3ed26339b26`. See [[Valor Security - 2026-06-09 Summary]].
- Axis Security HPE-acquisition team is a strong signal — Michael (COO) + Shaka (VP Product) ran the playbook through a $500M exit; they understand enterprise security GTM.
- "Outside-in for agentic AI" framing is structurally distinct from the Witness AI / Reco AI internal-monitoring category — worth validating with a vertical-AI customer (e.g., PennyMac's CISO) to confirm the gap is real.
- Granola rendered investors: "tamsev zarola" → likely "Gila Zerant" (per founder); "giggling vice" → likely Gigi Levy-Weiss; "av from entry" → AV from Entrée Capital; "door from cyber starts" → Doron from Cyberstarts. All confirmed in cleaner pass through transcript.
- **Fin angle:** International fund could write a $1M check given Valor's Israel base — Fan exploring this with the team. Connection to AmEx (Lauren) and Capital One LP contacts available when Michael ready for POC conversations.
- Valor Security not yet enriched in Harmonic (sparse record). Co-founders Shaka Dek and Omer last names not captured by Granola — flagged in Next Steps.

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Receive deck and any product materials from Michael
- [ ] Fan + Derek to bring to Fin IC; explore $1M check from international fund
- [ ] Fan to connect Michael with AmEx (Lauren) and Capital One LP contacts when ready for POC conversations
- [ ] Resolve co-founder full names: "Shaka Dek" (likely a Granola phonetic mishearing — founder said he had founded Axonius previously, which would mean either Avidor Bartov / Dean Sysman / Ofri Shur — but none match phonetically; recheck transcript and confirm with Michael) and "Omer" (VP R&D, ex-secret service + Forter)
- [ ] Submit Harmonic data report to enrich Valor Security company record
- [ ] Validate $8M seed closed / NFX lead / $35M cap with Michael in writing
- [ ] Reference one named design partner (PennyMac CISO is well aware of Witness; would be ideal validator) on the outside-in security gap
- [ ] Confirm United Health Group CEO meeting in London (Amit Kif / Inside Ignite event)
