---
type: meeting
date: 2026-06-15
company: Humwork
attendees: Yash Goenka, Derek Wu, Allison Leake, Domenica Cevallos
meeting_type: intro
transcript: "[[Humwork - 2026-06-15 Transcript]]"
created: 2026-06-15
tags:
  - meeting
---

[[Humwork]] | 2026-06-15 | Intro

## Attendees

- [[Yash Goenka]] — Co-Founder & CEO, Humwork
- Derek Wu — Fin Capital
- Allison Leake — Fin Capital
- Domenica Cevallos — Fin Capital

## Transcript

[[Humwork - 2026-06-15 Transcript]]

## Company Overview

- [[Humwork]] is building the **human escalation layer for autonomous AI** — an MCP / plugin that lets any coding agent (Claude Code, Codex, Open Claude, etc.) call out to verified human domain experts in real time when stuck or in need of judgment, taste, or accountability.
- **Coding is the wedge.** Yash's "aha" came from a Zoom call with an Upwork freelancer who realized that most recent project requests were from non-technical builders using coding agents to get 80–90% of the way and then stalling. Watching live, Yash realized that 3 sentences typed directly into the agent's transcript would unblock the user.
- **Long-term vision:** as agents do more autonomous work, a small but persistent share of their decisions will require human expertise. Founder analogy: Waymo still has remote operators 15 years into self-driving.

## Product & Technical Approach

- **Two escalation modes:**
  - **Manual** — user instructs their agent to "ask a human expert"; agent fires an MCP call to Humwork.
  - **Autonomous** — Humwork's script monitors a rolling window of the agent's transcript and prompts the agent to escalate when it detects the agent is stuck. Yash called this "notoriously difficult to build because agents are really bad at realizing when they're wrong."
- **Expert vetting:** voice interviewer probes experience and skills, then runs a simulated "agent stuck" conversation and grades the candidate.
- **QA / safety:**
  - LLM reviews every expert response; manual review on top (still at tractable scale).
  - OpenAI's open-source PII redaction model strips user data before exposing to experts.
  - Prompt-injection checks on the expert side.
- Founder also flagged an early-signal experiment: scraped GitHub/Twitter for `@agentmail.to` addresses and ran outbound to autonomous agents — 8 Open-Claude / Hermes-class agents signed up and paid for Humwork on their own. Founder read: as agents are given purchasing power, "humans as a tool" is one of the services they'll buy.

## Market & Competition

- **Market sizing (founder framing):**
  - Today — 28M deployed agents (IDC), ~100 consequential decisions/day, 0.1% needing human help × $3 take rate per session ≈ **$3B/year**.
  - 2030 — 2.2B agents → **$240B/year**. Founder noted an upside where agents grow 3 orders of magnitude (offset by 2–3 orders of magnitude less escalation need), so $240B held up as a defensible midpoint.
- **Differentiation vs Mercor / Surge:** those are pre-emptive training-data annotation marketplaces; Humwork is runtime, post-deployment escalation for the long tail you can't preempt in training data. Founder bet is that the long-tail problem persists for a long time.
- **Marketplace cold-start:** supply side has been easy — job posts on Indeed, ZipRecruiter, LinkedIn pulled in candidates plus YC launch traffic. Same playbook the data-annotation marketplaces (Mercor, Surge) use.

## Go-to-Market

- **Today:** PLG / individual non-technical builders using coding agents.
- **Next — legal vertical:** Latham & Watkins in active conversation as a QA/reliability layer over Harvey. Today Latham uses ALSPs (alternative legal service providers) to QA Harvey-generated review tables and deposition summaries; Humwork would recruit a dedicated pool of legal experts to make this programmatic. Lawyers' own time is too expensive to allocate to QA, so the work gets outsourced — Humwork captures it.
- **Series A target:** 20–30 AI-native companies / enterprises embedded.

## Pricing & Competition

- **Subscription tiers:** $30 to $100/month → bucket of expert minutes.
- **Per session:** $10 per 10 minutes; **70% to expert, 30% take rate to Humwork**.
- **Tiered rates coming** — by domain (e.g., legal premium) and by skill (analogy: UberX vs Uber Black; agent picks the tier).
- Adjacents: [[Mercor]], Surge (training-data plays, not runtime escalation).

## Financing & Growth

- **Current round:** raising **$3M at a $30M post-money cap**; **~$740K raised so far** in the round. Named existing investors: **Pioneer Fund** and **Jake Heller** (founder, Casetext).
- **Traction:** **$71K ARR in 6 weeks**, 3,000 vetted experts onboarded.
- **YC P26 Demo Day:** 2026-06-16 (next day). Founder expects post-Demo-Day commitments to come in fast.
- **Team:** Yash Goenka (Co-Founder & CEO; Berkeley DS; ex-Instawrite, ex-Phonecall.bot) and Rohan (Co-Founder; Berkeley; Yash's college roommate and longtime friend; previously co-built Phonecall.bot with Yash).

## Next Steps

- Yash to send the deck (action: Yash)
- Fin to review at Wednesday (2026-06-17) pipeline call and respond with next steps (action: Derek / Allison)
- Track post-Demo-Day round momentum
