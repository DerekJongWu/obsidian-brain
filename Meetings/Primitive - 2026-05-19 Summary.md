---
type: meeting
date: 2026-05-19
company: Primitive
attendees: Derek Wu, Stephanie Perez, Jake Fuchs, Matthew Cueto, Rina Okachi, Allison Leake, Richie Chaikof, Domenica Cevallos, Lauren Houpt, Daria Davydenko, Ian Ormerod
meeting_type: deep-dive
transcript: "[[Primitive - 2026-05-19 Transcript]]"
created: 2026-05-19
tags:
  - meeting
---

# Primitive Call Summary

> **Company:** [[Primitive]] | **Date:** 2026-05-19 | **Type:** Platform deep-dive (Microsoft Teams)

**Attendees:** [[Derek Wu]], [[Stephanie Perez]], [[Jake Fuchs]], [[Matthew Cueto]], [[Rina Okachi]], [[Allison Leake]], [[Richie Chaikof]], [[Domenica Cevallos]], [[Lauren Houpt]], [[Daria Davydenko]], [[Ian Ormerod]] (Head of Product and Execution, [[Primitive]])

**Transcript:** [[Primitive - 2026-05-19 Transcript]]

---

### Platform Overview & Positioning

- [[Primitive]] enables banks to manage "agent capital" at enterprise scale
  - Four core capabilities: create, orchestrate, govern, measure agents
  - Addresses systemic risk of uncontrolled intelligent agents across the organization
- Platform architecture spans three building blocks:
  1. **Engine Room** — governance, guardrails, gateway (the "three Gs")
  2. **Assembler** — build/integrate agents, orchestrate into workflows ("pods")
  3. **Control Tower** — 7-layer drill-down visibility from executive to session level
- Integration capabilities
  - Can govern non-Primitive agents via 808 protocols
  - Future roadmap includes build-framework integration (Copilot and other providers)
  - Maintains a vendor-agnostic approach across LLMs, agents, governance tools

### Technical Capabilities & Features

- LLM Gateway provides access to 19+ providers with live token-cost optimization
  - Intelligent routing minimizes spend by selecting optimal models per task
  - Custom SLM integration supported
  - Multi-model agent architecture (different models for reasoning, response, memory)
- Proprietary guardrails plus third-party integrations
  - Banking/finance-specific prompt injection protection
  - Parallel processing reduces latency vs sequential guardrail checking
  - PII/PCI redaction with custom regex rules at platform or agent level
  - Supports Leakera, Deep Level, Nemo adapters via API keys

### Pricing Structure & Commercial Model

- Three-stage engagement model:
  1. **Early Start Agreement** — $50K flat fee, no system/data access
  2. **Pilot Stage** — Master Service Agreement + SOW
  3. **Full Deployment** — License + development-team costs
- License pricing based on:
  - Number of pods (workflows/agents)
  - Transaction volumes and peak TPS requirements
  - Platform access fee
  - Overage fees beyond contracted volumes
- Current approach bundles all features vs modular pricing
  - Rationale: combined platform is more powerful than siloed components
  - Microservices architecture enables future unbundling if needed

### Next Steps

- Fin team to provide feedback on:
  - Pricing structure optimization
  - Commercialization strategy recommendations
  - Quick-win identification for faster market adoption
- Follow-up meeting to be scheduled for deeper discussion
- Fin to send structured feedback via email before next call
