---
type: company
sector: AI infrastructure
sub_sector: AI-native IDE / regulated industries
stage: Pre-Seed
status: sourcing
owner:
founded: 2026
hq: Palo Alto, CA
website: https://noahlabs.ai
linkedin: https://linkedin.com/company/noah-labs-ai
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-05-15
created: 2026-05-15
tags:
  - company
---

# Noah Labs

> [!summary] One-Liner
> AI-native IDE for government and regulated industries — operates entirely in local, air-gapped environments to manage large legacy codebases under strict compliance regimes (IL5+, NIST, CMC 2.0).

---

## Thesis Fit

**Why we like it:**
- Defense/regulated-industries wedge with concrete pilots already running (Lockheed Martin × 2 sites; Stanford Federal Credit Union COBOL migration)
- On-prem / air-gapped architecture defensibly differentiated from cloud coding agents — solves a real compliance constraint no incumbent IDE addresses
- Quantified performance edge: 91% SWE-bench accuracy under air-gapped conditions; F-16 codebase conversion delivered in 3 weeks vs competitor's 13 months

**Relevant thesis:** [[]]

**Fin sub-sector:** AI Infrastructure / Defense & Regulated Industries Developer Tools

---

## Team

| Role | Person | Background |
|------|--------|------------|
| Founder | [[Murat Isik]] | PhD candidate Drexel University (MS 2023, PhD path); Research Scholar Stanford University (2023–2026); Intel Labs Research Member (2023–2025); FPGA roles at Lattice Semiconductor and Mindway; Baykar Technologies intern; from Istanbul, Turkey; currently in StartX Stanford accelerator |

---

## Business Description

- **Problem:** Government and regulated industries (defense, financial services, airlines) run massive legacy codebases (COBOL, Kotlin, etc.) that cannot use cloud-based coding agents due to compliance constraints. Existing AI coding tools require cloud connectivity and are non-starters in air-gapped environments.
- **Product:** AI-native IDE operating fully on-prem / air-gapped with:
  - Static + runtime analysis, formal proof verification, multi-step planning
  - Code translation engine specialized in Rust conversions (also COBOL→Java, Kotlin→Rust)
  - 15 features shaped by customer feedback — formal verification, quality analysis; intentionally **no MCP integration** at customer request
- **Wedge / entry point:** Legacy code migration for defense primes (Lockheed Martin) and regulated FS (Stanford FCU). Land via high-value migration project, expand to general IDE usage per-user across divisions.

---

## Market & Competition

- **Market size:**
- **Key competitors:** Cloud-based coding agents (Cursor, GitHub Copilot, Devin) — structurally cannot serve air-gapped customers
- **Differentiation:**
  - Fully air-gapped / on-prem operation (vs cloud-only incumbents)
  - 91% SWE-bench accuracy under air-gapped conditions (as of 2026-05-15)
  - Compliance posture: IL5+, NIST, CMC 2.0 (not FedRAMP — on-prem only by design)
  - Heavy platform footprint (500GB, H100/H200 GPUs) is a moat, not a liability, for target buyers who can provision it

---

## GTM & Business Model

- **Buyer persona:** Defense primes (Lockheed Martin, BAE, Boeing), regulated FS (credit unions, banks), airlines with legacy flight simulator/controller code
- **Pricing model:** Installation fee + per-user pricing
  - Lockheed contract structure: $10K installation fee + per-user pricing for 20 users across 2 divisions (as of 2026-05-15)
- **ACV:** First Lockheed contract targeted at $50K (June 2026); planned expansion to Denver, Florida, New Jersey offices
- **Contract structure:** Higher pricing planned for direct buyers (BAE, Boeing) vs initial Lockheed pilot
- **Alternative compute:** Private compute via Lambda Labs with US data residency for customers who cannot stand up own H100/H200 fleet

---

## Traction

- **Active customers (as of 2026-05-15):**
  - Lockheed Martin — 2 pilot deployments (Denver, Sunnyvale)
  - Airlines company — legacy flight simulator / controller code (unnamed)
- **Completed projects (as of 2026-05-15):**
  - F-16 codebase conversion — 3 weeks, $50K (vs competitor's 13 months, $150K)
  - Stanford Federal Credit Union — 500K lines COBOL → Java
  - IOMET (Netherlands enterprise) — Kotlin → Rust
- **Compliance achieved (as of 2026-05-15):** IL5+, NIST, CMC 2.0
- **Headcount:** 11 (per Harmonic, as of 2026-05-15)
- **Accelerator:** StartX (Stanford)

---

## Financing

| Date | Round | Amount | Investors |
|------|-------|--------|-----------|
| In progress (2026) | Pre-Seed SAFE | $2M target — $500K committed + $50K angel | PhD advisor angel ($10M valuation cap) |

**Current round (as of 2026-05-15):**
- Raising $2M SAFE
- $500K committed + $50K angel from PhD advisor at $10M valuation
- Active conversations: HSBC CVC (invest-then-customer model), Quota Capital, Exceptional VC, Hustle Fund, Lockheed Martin venture arm (slow timeline)
- Targeting SBIR Phase 1 grant ($250K) in partnership with Lockheed Martin

---

## Backend / Model Stack (technical reference, 2026-05-15)

- Gemma 31B for general use
- Granite 8B (IBM-trained) for COBOL → Java
- Planning dual LLM architecture (Mistral + Gemma) for ASO
- Heavy LLM + multi-agent framework — 500GB platform footprint, requires H100/H200 GPUs

---

## Deal Team Notes

- 2026-05-15: Intro call with [[Murat Isik]] (Founder); [[Derek Wu]] and [[Daria Davydenko]] on Fin side. See [[Noah Labs - 2026-05-15 Summary]].
- Murat in StartX (Stanford) — found via accelerator network; previous Stanford Research Scholar role and Intel Labs background.
- Materials to request: deck + one-pagers used for Lockheed/HSBC conversations.
- HSBC CVC pursuing "invest-then-customer" pattern — worth tracking as a potential FS LP-adjacent customer signal.

---

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

---

## Next Steps

- [ ] Receive deck + Lockheed/HSBC one-pagers from Murat
- [ ] Diligence Lockheed pilot ARR ramp and June $50K contract close
- [ ] Reconcile education detail — Granola summary says "PhD Electrical Engineering, Stanford"; Harmonic shows Drexel PhD + Stanford Research Scholar (2023–2026). Confirm with founder.
- [ ] Evaluate fit vs Fin defense / regulated-industries thesis
- [ ] Reference-check via StartX network on commercial traction and Lockheed relationship depth
