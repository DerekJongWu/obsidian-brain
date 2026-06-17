---
type: meeting
date: 2026-06-16
company: PVML
attendees: Shachar Schnapp, Jake Fuchs, Derek Wu
meeting_type: intro
transcript: "[[PVML - 2026-06-16 Transcript]]"
created: 2026-06-16
tags:
  - meeting
---

[[PVML]] | 2026-06-16 | Intro

## Attendees

- [[Shachar Schnapp]] — CEO & Co-Founder, PVML
- [[Jake Fuchs]] — Fin Capital
- [[Derek Wu]] — Fin Capital

## Transcript

[[PVML - 2026-06-16 Transcript]]

## Company Overview

- [[PVML]] is an infrastructure play — a **"virtual database" layer** that sits between live production databases and AI/BI/API consumers. Intercepts queries, applies security guardrails, rewrites the query, and returns a sanitized result.
- **No data movement or duplication.** Transparent to existing code — swap the connection string.
- **Deterministic security** — no LLM in the access-control path. Sub-3ms added latency.
- Supports **9 database types**, unifies security policy across all of them. Integrates with existing IAM. Supports MCP, ODBC, JDBC, and agent-to-agent protocols.
- **Founders:** Shachar Schnapp (CEO) — PhD in data protection (Ben-Gurion), ex-General Motors autonomous-vehicle research, ex-Infinidat. Rina Galperin (CTO Co-Founder) — ex-Microsoft 5 yrs (Data & Applied Science, Herzliya). Both hit the data-protection-meets-AI problem firsthand.

## Product & Technical Approach

- **Core wedge:** enterprises can't connect sensitive data to AI in production without a security layer.
- **2025 vs. 2026:** most orgs ran POCs in 2025 without security; now they need guardrails to ship to prod in 2026.
- **Today's workaround:** encrypt a duplicate of the data, change client connection strings — very slow and impractical. Some orgs skip security entirely and risk corrupting the database; founder cited **NACS** as an example.
- **PVML architecture:**
  - Sits in the query path
  - Dynamic user-level permissions
  - Proprietary mathematical guardrails (deterministic, no LLM)
  - Query rewriting + sanitized response
  - Sub-3ms latency
  - 9 DB types unified under one policy plane
  - IAM integration; MCP/ODBC/JDBC/agent-to-agent protocol support

## Market & Competition

- **Timing thesis:** 2025 was POC year (no security required); 2026 is production year (guardrails required).
- **Differentiation:** deterministic mathematical guardrails (no LLM in access path) and no data movement. Competing alternatives are encrypt-and-duplicate workarounds or LLM-based access control.
- **Channel:** Accenture program — **10 banks competed to work with PVML**; most companies get 2–4.

## Go-to-Market

- **Buyer persona:** Enterprise data/security/AI leaders shipping AI into production over sensitive data (financial services and government early).
- **Pipeline:** Wells Fargo, JPM, AQR (POC complete → moving to commercial/legal), IDF (in POC).
- **Channel motion:** Accenture bake-off won; expect downstream bank deployments.

## Pricing & Competition

- **Model:** flat infrastructure fee + usage-based overage ("PVML units").
- **ACVs:** average $250–270K. Top customer **VisionWave** at $600K.
- **NRR signal:** existing customers already exceeding their packages — strong NRR expected.
- **Competitive frame:** LLM-based access control (non-deterministic, slower); manual encrypt-and-duplicate workarounds.

## Financing & Growth

- **ARR (2026-06-16):** **$1.9M** today, targeting **$10.6M ARR by end of Q2 2027**.
- **Customers:** 6 paying. Top — VisionWave ($600K). Selling for **10 months**.
- **Raised to date:** ~$9M. **NFX led seed at $7M** (Dec 2023). **Papaya Global founder** put in a SAFE — **$180M cap, 50% discount** — after trying to buy the product.
- **Other seed investors:** FJ Labs, Gefen Capital, Erez Yarkoni, Ran Nahmias, Jonathan Lebowitsch, Amit On.
- **Current round:** raising **$30–40M Series A**. Focused on finding a **lead first**. Strong follower interest but limited room. Founder ask: indicate quickly whether Fin can lead, or stand down so he can prioritize other conversations.

## Next Steps

- Indicate quickly whether Fin can seriously consider leading, or should stand down and wait (Shachar's ask)
- Review deck once Shachar shares it (Shachar to send)
- Discuss internally and revert with lead/follow indication (action: Derek + Jake)
