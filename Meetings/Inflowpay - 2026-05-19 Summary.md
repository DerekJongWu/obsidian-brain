---
type: meeting
date: 2026-05-19
company: Inflowpay
attendees: Derek Wu, Daria Davydenko, Jim Nguyen
meeting_type: intro
transcript: "[[Inflowpay - 2026-05-19 Transcript]]"
created: 2026-05-19
tags:
  - meeting
---

# Inflowpay Call Summary

> **Company:** [[Inflowpay]] | **Date:** 2026-05-19 | **Type:** Intro

**Attendees:** [[Derek Wu]], [[Daria Davydenko]], [[Jim Nguyen]] (Inflowpay, jim@inflowpay.ai)

**Transcript:** [[Inflowpay - 2026-05-19 Transcript]]

---

### Company Overview & Product Vision

- [[Inflowpay]]: "PayPal for OpenClaw" — agent-native payment system
- Launched June 2025, product shipped December 2025
- 10 customers integrating, transactions running through system
- Policy engine that no other payment wallet has today
  - Allows policies to be programmed for agents
  - Think of authorized-spender model
  - Agent operates under guardrails, reports back to human

### Technical Architecture & Demo

- Complete rebuild from scratch — not a 0.5 solution cobbled together
- Policy engine as system spine (MD file/context for ML models)
- MCP integration for Claude, Cursor, other AI platforms
- Demo: GPU provisioning through Pictor
  - Agent accesses wallet, finds GPU instances, gets pricing
  - Human approves via mobile 2FA
  - Never left Claude interface — headless commerce end-to-end
- Three API calls, one-hour integration for sellers

### Market Positioning & Competition

- Agent-native vs agent-assisted distinction
  - Agent-assisted: existing accounts, agent helps with tasks
  - Agent-native: agent registers, pays, purchases entire commerce flow
- Wedge: buying GPUs and other infrastructure for AI workloads
- Skyfire pivoted to KYC, focused on stable coins only
- Nakuta targeting consumer use cases (airlines, shopping)
- Stripe/PayPal serve human flows — different channel segmentation

### Business Model & Traction

- 3% fee on sell side (similar to PSP model)
- No revenue from buy-side wallet yet
- Largest customer: public company moving $2B/year in GPU/cloud services
- Neon (acquired by Databricks): 80% of databases provisioned by agents
- Visa partnership announced — "B2AI" commerce with new payment rails

### Fundraising Details

- Raising $15M seed round
- Previous: $1.5M pre-seed (September 2025)
- Round "spoken for" by existing investors/customers
- Seeking lead investor for diversification
- Target close: July 2026
- Focus: regulatory compliance (MTLs, VASP licenses)
- Lost one customer due to regulatory concerns
