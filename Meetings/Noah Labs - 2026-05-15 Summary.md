---
type: meeting
date: 2026-05-15
company: Noah Labs
attendees: Derek Wu, Daria Davydenko, Murat Isik
meeting_type: intro
transcript: "[[Noah Labs - 2026-05-15 Transcript]]"
created: 2026-05-15
tags:
  - meeting
---

# Noah Labs Call Summary

> **Company:** [[Noah Labs]] | **Date:** 2026-05-15 | **Type:** Intro

**Attendees:** [[Derek Wu]], [[Daria Davydenko]], [[Murat Isik]] (Founder, [[Noah Labs]])

**Transcript:** [[Noah Labs - 2026-05-15 Transcript]]

---

### Company Overview

- [[Noah Labs]] — AI-native IDE for government and regulated industries
- Founded by [[Murat Isik]] (PhD Electrical Engineering, Stanford per Granola; Harmonic shows Drexel PhD + Stanford Research Scholar — to be reconciled)
- Originally from Istanbul, Turkey
- Part of StartX Stanford accelerator program

### Product & Technology

- AI-native IDE for regulated industries (air-gapped environments)
- 15 features shaped by customer feedback
  - Formal verification
  - Quality analysis
  - No MCP integration (by customer request)
- Code translation engine integrated
  - Specializes in Rust conversions
  - Supports COBOL → Java, Kotlin → Rust
- Backend powered by open source models
  - Gemma 31B for general use
  - Granite 8B for COBOL → Java (IBM-trained)
  - Planning dual LLM architecture (Mistral + Gemma) for ASO
- 91% accuracy on SWE-bench under air-gapped conditions
- Platform requirements: 500GB (vs competitors' 1–10GB)
  - Needs H100/H200 GPUs
  - Heavy LLM + multi-agent framework

### Customer Traction & Use Cases

- **Completed projects:**
  - F-16 conversion: 3 weeks, $50K (vs competitor's 13 months, $150K)
  - Stanford Federal Credit Union: 500K lines COBOL → Java
  - Netherlands enterprise (IOMET): Kotlin → Rust
- **Current customers:**
  - Lockheed Martin: 2 pilot deployments (Denver, Sunnyvale)
  - Airlines company: legacy flight simulator / controller code
- **Compliance:** IL5+, NIST, CMC 2.0 cybersecurity (not FedRAMP — on-premise only)

### Business Model & Pricing

- Lockheed Martin contract structure:
  - $10K installation fee
  - Per-user pricing for 20 users across 2 divisions
  - First contract: $50K (June 2026 target)
  - Plans to expand to Denver, Florida, New Jersey offices
- Higher pricing planned for direct buyers (BAE, Boeing)
- Alternative: private compute via Lambda Labs (US data residency)

### Fundraising & Next Steps

- Raising $2M SAFE
- $500K committed + $50K angel (PhD advisor) at $10M valuation cap
- Active conversations:
  - HSBC CVC (invest-then-customer model)
  - Quota Capital, Exceptional VC, Hustle Fund
  - Lockheed Martin venture arm (slow timeline)
- SBIR grants: targeting $250K Phase 1 with Lockheed partnership
- Materials to send: deck + one-pagers used for Lockheed/HSBC

### Next Steps

- [[Murat Isik]] to send deck + Lockheed/HSBC one-pagers to [[Derek Wu]] and [[Daria Davydenko]]
- Fin to diligence Lockheed pilot ramp and June $50K contract close
- Reconcile education detail (Stanford PhD vs Drexel PhD + Stanford Research Scholar)
