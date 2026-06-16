---
type: company
sector: AI infrastructure
sub_sector: Human-in-the-loop / human escalation layer for AI agents
stage: Pre-Seed
status: sourcing
owner:
founded: 2025
hq: San Francisco, CA
website: https://humwork.ai
linkedin: https://linkedin.com/company/humwork
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-06-15
created: 2026-06-15
tags:
  - company
---

> [!info] One-Liner
> Humwork is building the human escalation layer for autonomous AI — an MCP / plugin that lets coding agents (Claude Code, Codex, Open Claude, etc.) call out to verified human domain experts in real time when they get stuck or need judgment, taste, or accountability.

## Thesis Fit

- Human-in-the-loop infrastructure for the agentic stack — picks coding as a wedge but expands into legal, medical, finance verticals
- Two-sided marketplace where supply (vetted experts) is straightforward to acquire via standard job-board recruiting (similar to Mercor / Surge), and demand pulls through MCP integration into existing coding-agent surfaces
- Autonomous-escalation product (script monitoring agent transcripts, triggering hand-offs) is the long-term bet — analogous to Waymo remote operators for self-driving
- YC P26 — Demo Day 2026-06-16 (day after meeting)

**Relevant thesis:** [[]]

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Yash Goenka]] | Berkeley data science; founded Instawrite (AI copywriter, 2021–2023) and Phonecall.bot (AI voice calling, ~$200K ARR); GPT-3 chatbot startup engineer; YC S25 + P26 |
| Co-Founder | Rohan (last name TBD) | Berkeley; college roommate and longtime friend of Yash; originally from Irvine, CA (family moved to India in middle school); previously built voice-calling platform with Yash |

## Business Description

- **Problem:** AI agents (especially coding agents used by non-technical builders) hit a long tail of problems where they get stuck, need domain expertise, judgment, taste, or accountability that no training data covers. Today users either abandon the project or fall back to Upwork/freelancer marketplaces, which are too slow and high-friction for in-loop assistance.
- **Product:** MCP / plugin that any coding agent can call. A verified human expert connects within seconds and chats with the agent in real time (typically 2–3 sentences to unblock). Two escalation modes: (1) manual — user tells the agent "ask a human expert"; (2) autonomous — Humwork script watches a rolling window of the agent's transcript and prompts the agent to escalate when it detects the agent is stuck.
- **Wedge:** Coding agents used by non-technical builders (lovable users, Claude Code users, etc.) who get 80–90% of the way and can't finish.

## Market & Competition

- **Market size (founder framing):** 28M agents deployed today (IDC), ~100 consequential decisions/day, 0.1% need human help × $3 take rate per session ≈ **$3B/year today**. By 2030, 2.2B agents → **$240B/year**. Founder notes upside scenario of 3 orders of magnitude more agents (offset by 2–3 orders of magnitude less escalation need) suggests $240B is defensible mid-case.
- **Key competitors / adjacents:** [[Mercor]], Surge — data-annotation / RLHF marketplaces. Humwork's positioning: those are pre-emptive training-data plays; Humwork is post-deployment, runtime escalation for the long tail you can't preempt.
- **Differentiation:** Real-time runtime escalation via MCP (not batch labeling); vetted experts via simulated-agent voice interview; autonomous-escalation script as core long-term moat.

## GTM & Business Model

- **Buyer persona:** Today — individual non-technical builders / prosumers using coding agents (PLG). Next — AI-native companies and enterprises embedding Humwork as a QA/reliability layer (legal vertical is the active enterprise wedge).
- **Pricing model:** Subscription ($30 to $100/month plans → bucket of expert minutes). Per-session rate $10 per 10 minutes; Humwork takes 30%, expert keeps 70%. Variable tiered rates (by domain and skill tier — analogy: UberX vs Uber Black) being introduced soon.
- **Expert supply:** 3,000 vetted experts onboarded; recruited via Indeed, ZipRecruiter, LinkedIn job posts + YC launch. Vetting flow: candidate completes voice interview that probes experience/skills and runs a simulated "agent stuck" conversation; Humwork grades performance. ~50% engineers, ~50% other domains (legal, marketing, design).
- **Enterprise wedge — legal:** In conversations with Latham & Watkins as a QA/reliability layer over Harvey (Latham today uses ALSPs — alternative legal service providers — to QA Harvey-generated review tables and deposition summaries; Humwork would recruit a dedicated pool of legal experts to make this programmatic). Series A target: 20–30 AI-native companies/enterprises embedded.
- **QA / safety:** LLM reviews every expert response + manual human review (still at the scale where this is tractable). OpenAI's open-source PII redaction model used to redact user data before exposing to experts. Prompt-injection checks on the expert side.

## Traction

- **ARR (2026-06-15):** $71K, in 6 weeks of operation
- **Vetted experts:** 3,000 onboarded
- **Early autonomous-agent demand signal:** Scraped GitHub and Twitter ~6 weeks ago for `@agentmail.to` email addresses and did outbound to autonomous agents; 8 Open-Claude / Hermes-class agents signed up and paid for Humwork on their own — taken as a signal that as agents get purchasing power, "humans as a tool" is one of the services they'll buy.
- **Enterprise pipeline:** Latham & Watkins (active conversation, legal QA over Harvey)

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| 2026-02-27 | Pre-Seed | $500K | Y Combinator |

**Current round (2026-06-15):**
- Raising **$3M at a $30M post-money cap**
- ~$740K raised so far in the current round (incremental on top of YC pre-seed)
- Named existing investors: **Pioneer Fund**, **Jake Heller** (founder, Casetext)
- YC P26 Demo Day is **2026-06-16** (next day) — expect a wave of commitments after demo day
- Harmonic estimated valuation $2M is stale (based on pre-current $500K pre-seed round)

## Deal Team Notes

- 2026-06-15 — Intro pitch (Yash Goenka → Derek Wu, Allison Leake, Domenica Cevallos)
- Action items called out live:
  - Yash to send deck to Fin
  - Fin to review at Wednesday (2026-06-17) pipeline call and respond with next steps
- Macro questions raised by Derek:
  - Marketplace cold-start — supply side surprisingly easy (standard job-board recruiting, mimicking Mercor/Surge playbook)
  - Mercor/Surge differentiation — Humwork is runtime escalation post-deployment, not pre-training data annotation; long-tail problems can't be preempted in training data
  - Moving up-market — legal is the explicit next vertical (lawyers' time is too expensive to use for AI QA → outsourced today via ALSPs → Humwork programmatic layer)

## Meetings & References

```dataview
TABLE date, type, meeting_type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Receive deck from Yash
- [ ] Discuss at Wednesday (2026-06-17) pipeline call
- [ ] Confirm Rohan's full name + role (Co-Founder; not in Harmonic record)
- [ ] Diligence the autonomous-escalation script (claimed moat — agents are "bad at realizing when they're wrong")
- [ ] Diligence legal vertical pipeline (Latham & Watkins / Harvey QA path)
- [ ] Track post-Demo-Day round momentum
- [ ] Validate market sizing assumptions (28M agents, 0.1% escalation rate, $3 take rate)
