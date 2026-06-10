---
type: meeting
date: 2026-06-09
company: Mars Security
attendees: Derek Wu, Jake Fuchs, Shahaf Galili
meeting_type: intro
transcript: "[[Mars Security - 2026-06-09 Transcript]]"
created: 2026-06-09
tags:
  - meeting
---

[[Mars Security]] | 2026-06-09 | Intro

## Attendees

- [[Shahaf Galili]] — Co-Founder & CEO, [[Mars Security]]
- Derek Wu (Fin Capital)
- Jake Fuchs (Fin Capital)

## Transcript

[[Mars Security - 2026-06-09 Transcript]]

## Company & Product

- 8 months old, ~6 months of active building; 15 people in Tel Aviv (Harmonic: 17).
- Raised **$9M** (TLV Partners, Jibe Ventures + angels); introduced via **Opio** (seed lead).
- **Threat hunting and detection engineering platform:**
  - Ingests security telemetry across tools (SIEM, EDR, data lakes) via API
  - **Federated search engine** maps data sources automatically, queries all with one interface
  - **Harvests threat intelligence from ~200 open-web sources**, auto-deploys detections against live threat campaigns and actors
  - **50+ integrations supported today, adding 5–10/week**
- **Not a SIEM replacement** — explicitly positioned as a smart layer on top of existing stack
  - Competitors (Artemis, Vega) play the "same but not a SIEM" game; Mars is not going there
  - **No plans to host customer data; financially unreasonable at scale**
- **No SOAR/containment yet:** alerts feed into existing SIEM or SOAR; containment and access revocation on roadmap but not current
- **Two paying customers** (small deals) + design partners; core functionality in production

## Go-to-Market & Banks

- Hiring first AE in the US now; also building out BDR function
- **Banks** acknowledged as attractive but difficult
  - Strong fit on paper (dedicated threat-intel, detection-engineering, and threat-hunting teams)
  - Blocker: reluctance to connect a SaaS platform to so many data sources with cloud-side computation
  - **Vega** (Gil Berstler's company) aggressively targeting banks with a similar solution
  - Current focus is elsewhere given the friction; banks are not the primary near-term target
- **Budget question:** not replacing a line item, **adding one**
  - Shahaf's framing: organizations choose between **headcount OR a product** to mature detection capability; Mars is the product path
  - AI-driven fear cycle is creating urgency and opening budgets right now

## Fundraise & Next Steps

- Actively debating next raise: **$3–5M SAFE or ~$10M Series A**
- Timing is now; no formal process started yet, VCs not yet looped in
- Deck inbound from Shahaf; Jake and Derek to sync by end of week or early next week on potential next steps

## Next Steps

- Receive deck from Shahaf
- Jake and Derek to sync end of week / early next week on whether to engage in the SAFE or wait for the Series A
- Validate Harmonic funding undercount (Harmonic: $0 / 0 rounds vs founder $9M from TLV/Jibe + angels)
