---
type: meeting
date: 2026-06-16
company: Brava Security
attendees: Idan Basre, Richie Chaikof, Derek Wu
meeting_type: intro
transcript: "[[Brava Security - 2026-06-16 Transcript]]"
created: 2026-06-16
tags:
  - meeting
---

[[Brava Security]] | 2026-06-16 | Intro

## Attendees

- [[Idan Basre]] — Co-Founder & CEO, Brava Security
- [[Richie Chaikof]] — Fin Capital
- [[Derek Wu]] — Fin Capital

## Transcript

[[Brava Security - 2026-06-16 Transcript]]

## Company Overview

- [[Brava Security]] is building an **interpretation layer** between raw security telemetry and downstream tools (SIEM, detection, compliance). Founder framing: "Telemetry is to security what electricity was to the light bulb" — massively underutilized because teams can't access, parse, or act on it.
- **Founders:** Idan Basre (CEO) — 10 years as a vulnerability researcher, Commander of Unit 8200's **ARAM course** (specialized vuln research track), then technical leadership at Microsoft; moved from Israel to NYC ~5 months ago. Itai Gabai (CTO) — former collaborator at Intelligence Force; built an anomaly-detection project with US **DARPA**; built a pre-SageMaker ML platform on top of Reddit, presented at KubeCon in IDF uniform.
- **Org:** Delaware-incorporated; R&D in Israel; commercializing in the US. **Team of 15** — all R&D plus one video, one ops, and Idan.

## Product & Technical Approach

- **Interpretation layer:** sits between raw telemetry sources and downstream tools (SIEM, detection, compliance).
- **CTF-trained agents:** agents learn the mapping between every attacker behavior and its telemetry footprint by training on capture-the-flag exercises.
- **Outputs:** coverage gaps, detectability gaps, improved detections, and log-cost reduction.
- **Differentiation vs. [[Cribl]]:** Cribl moves data blindly (cost optimization without security context); Brava adds a "brain" that ties cost decisions to detection coverage.
- **Long-term vision:** horizontal telemetry platform spanning security, identity, vuln management, GRC — but explicitly focused on the **AIC (AI-driven SOC) buyer persona for the next 24 months**.

## Market & Competition

- **vs. Cribl:** Cushman Wakefield benchmark — **93% log-cost reduction with Brava vs. 27% with Cribl alone**. Brava competes alongside or replaces Cribl in deployments.
- **vs. Databricks / Exabeam:** founder positions them as cost-focused, not security-focused.
- **Vertical spread:** retail, healthcare, finance (Toronto/Montreal stock exchanges + Form 3 in pipeline).

## Go-to-Market

- **Buyer persona (next 24 months):** AI-driven SOC (AIC).
- **Sales motion:** AI-driven outbound agents for ICP research and warm LinkedIn intros, supported by two outsourced sales reps.
- **Annual contracts:** ACVs range from $75K (Well Health) to $405K (Cushman Wakefield).

## Pricing & Competition

- **Annual subscription** — representative ACVs:
  - McDonald's — $250K/yr
  - Cushman Wakefield — $405K/yr (just closed)
  - Well Health (Canadian healthcare, ~5K employees) — $75K/yr (expansion potential)
  - Fortune 500 in pipeline — $270K
- **Competitive frame:** alongside or replacing Cribl in detection-cost optimization; Databricks/Exabeam viewed as not security-native.

## Financing & Growth

- **Current ARR:** ~$400K; **target $1.2M by year-end 2026**.
- **Seed:** $8M in Summer 2024 from **Pitango** and **F2**. Raise delayed ~6 months by Oct 7. Pitango + F2 hold **~36% combined**.
- **Series A:** raising **$15M** — launched ~1 week prior to the meeting.
- **Lead preference:** **US-based lead**, not solely Israeli VCs. Founder ask: strategic counsel and smart board members (Pitango/F2 cited as models), not just commercial intros.
- **Referral context:** introduced via **Barak (IGA)** — Richie and Derek are in advanced discussions with Barak.
- **Reference offer:** Shai (Unit 8200 alum, Fin portfolio) flagged as a potential reference; Richie offered to broker the intro.

## Next Steps

- Send calendar invite for in-person meeting in **Soho, Monday or Tuesday** (action: Richie/Derek)
- Idan to share **deep-dive materials in person** rather than ahead of the meeting (action: Idan)
