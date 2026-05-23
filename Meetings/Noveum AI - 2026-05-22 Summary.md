---
type: meeting
date: 2026-05-22
company: "Noveum AI"
attendees: "Derek Wu, Shashank Agarwal"
meeting_type: "intro"
transcript: "[[Noveum AI - 2026-05-22 Transcript]]"
created: 2026-05-22
tags:
  - meeting
---

**[[Noveum AI]]** | 2026-05-22 | Intro / pitch call

## Attendees

**Fin Capital:**
- [[Derek Wu]]

**Noveum AI:**
- [[Shashank Agarwal]] (Founder & CEO)

## Transcript

[[Noveum AI - 2026-05-22 Transcript]]

## Company Overview

- Noveum AI: AI agent monitoring and reliability platform
- [[Shashank Agarwal]], founder, ~12 years AI experience
  - Former AWS SageMaker team (built initial version)
  - Amazon ML platform (India) and Prime Video AI (built $32M revenue model)
- Problem: banks deploy AI agents handling 100K+ daily conversations with zero visibility into errors
  - Hallucinations, wrong policies, compliance issues go undetected
  - Discovery only via customer screenshots / complaints — ~2-week fix cycle
  - Prevents scaling agent deployments

## Product & Technical Approach

- Integrates at the application layer in agent code
- Monitors complete agent trajectory:
  - Every LLM call, RAG call, tool call
  - System-prompt adherence analysis
  - Parameter correctness and tool relevancy
  - Task progression efficiency
- Scoring system evaluates:
  - Content safety, hallucination, conversation flow
  - Toxicity, uncertainty, goal achievement
  - Priority levels (high/medium/low) computed from impact + frequency
- Future roadmap: automated code fixes via GitHub PRs with backtesting
- Tracks/stores call history; can also record call audio

## Traction & Customers

- 8–9 months building platform, 2 months onboarding customers
- Current paying customers:
  - **Alpha Vantage** (YC company, stock API)
  - **Exotel** (30% of India telephony, fixing Uber agents)
  - **Reliance Jio** (India's largest telecom)
- Active POCs:
  - **Deloitte**: $8K / 30-day POC, $100K+ ACV potential
  - **Vanguard**: internal chatbot reliability (met at Dubai conference)
  - **Siemens**, **Five9** in pipeline
- Pipeline: ~$983K ARR from existing customers
- Beat competitors **Langfuse** (Deloitte) and **Secura** (Exotel)

## Go-to-Market

- Targeting agent builders (Deloitte, KPMG) and direct enterprise
- Primary verticals: BFSI (immediate ROI) and retail/ecommerce
- Pricing model: per agent + volume (conversations/invocations) + evaluation count

## Financing & Growth

- Raised: $150K angel funding (pre-seed)
- Current round: $2.5–3M pre-seed
  - Needs capital to scale for incoming enterprise customers
  - Not optimizing for valuation, seeking strategic partners
  - Rolling basis starting Tuesday with angels, then VCs
  - Open to Fin leading the round

## Next Steps

- Derek to sync with Fin team at Wednesday pipeline meeting
- Partner call with Logan (managing partner) likely next step
- Shashank to send sales deck and demo materials
- Follow-up timing: late next week or early week after (post-holiday)
