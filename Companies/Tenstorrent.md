---
type: company
sector: "AI Compute / Semiconductors"
sub_sector: "AI accelerators"
stage: "Series D"
status: "sourcing"
owner:
founded: 2016
hq: "Toronto, Ontario, Canada"
website: "https://tenstorrent.com"
linkedin: "https://linkedin.com/company/tenstorrent-inc."
crunchbase: "https://www.crunchbase.com/organization/tenstorrent"
pitchbook: "https://pitchbook.com/profiles/company/171627-13"
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-05-13
created: 2026-05-13
tags:
  - company
---

# Tenstorrent

> [!summary] One-Liner
> AI compute company building general-purpose AI architecture (RISC-V CPU + custom AI accelerators) with TT-Forge open-source compiler running 92% of public Hugging Face models. Selling hardware and IP into hyperscalers, financial-services HFT firms, and OEMs (Hyundai, LG, Bosch, SanDisk).

---

## Thesis Fit

**Why we like it:**
- General-purpose AI architecture vs. competitors' LLM-only focus
- World-record performance: 350 tokens/sec at scale (vs 144 market standard), 2.4 sec video generation (vs 20+ sec)
- Significant traction in regulated financial services (Virtue Financial, Morgan Stanley POC, XTX Markets)
- Repeat senior team (Jim Keller — ex-AMD, Apple, Tesla, Intel chief architect)

**Relevant thesis:** [[]]

**Fin sub-sector:** AI Compute / Semiconductors

---

## Team

| Role | Person | Background |
|------|--------|------------|
| Tenstorrent (Capital Markets / IR) | [[Walker Stamps]] | Tenstorrent — primary external attendee on 2026-05-13 Fin update call |
| CEO | Jim Keller | CEO Tenstorrent (2023–present); prior CTO & President Tenstorrent; SVP Silicon Engineering Intel; VP Autopilot HW Tesla; Corporate VP & Chief Architect AMD; VP Engineering Apple |
| Co-Founder | Ivan Hamer | Co-Founder Tenstorrent (2016); prior AMD, Altera |
| Co-Founder | Milos Trajkovic | Co-Founder & Sr Fellow, Systems Engineering & Software (2016–present) |
| VP RISC-V Cores | Divyang Agrawal | ex-Director Silicon Design AMD; MBA UC Berkeley Haas |
| VP Robotics & Automotive | Thaddeus Fortenberry | ex-Apple SPG; ex-Tesla Autopilot Infra Architect; ex-AMD Cloud Server Director |
| CMO | Christine Blizzard | ex-Google Senior Creative Producer |
| VP Legal Strategy | Alicia Shah | ex-Intel Director & Group Counsel |

---

## Business Description

- **Problem:** AI compute is dominated by NVIDIA; alternatives are LLM-only or lack a mature software stack. Customers (hyperscalers, financial services, OEMs) want a credible second source with open software.
- **Product:** General-purpose AI architecture combining RISC-V CPU with custom AI accelerators. 36-server clusters operate as a single computer (56× 800Gb networking ports per server). TT-Forge open-source compiler runs 92% of all public Hugging Face models (2.5M models). Hardware manufactured at TSMC 6nm; next-gen planned Samsung 4nm (potential TSMC switch).
- **Wedge / entry point:** Sell to performance-sensitive customers (HFT, hyperscalers, OEM IP) where general-purpose architecture and open software win against NVIDIA.

---

## Market & Competition

- **Market size:** AI accelerator market; targeting hyperscalers, financial services (100+ institutions, 10-30 servers minimum each), OEMs
- **Key competitors:** Primarily NVIDIA in most bids; rarely see Cerebras, AMD, Groq
- **Differentiation:**
  - General-purpose architecture vs. LLM-only focus
  - Open software stack (TT-Forge runs 92% of HF models)
  - World-record performance (350 tok/s @ scale; 2.4s video gen)
  - Data placement and flow architecture built from scratch

---

## GTM & Business Model

- **Buyer persona:** Hyperscalers, frontier labs (OpenAI, xAI, Anthropic dialogue early), top banks/HFT firms (Virtue Financial, Morgan Stanley, XTX, Citadel/Jane Street target), Tier-1 OEMs (Hyundai, LG, Bosch, SanDisk)
- **Pricing model:** Hardware list-price sales; IP licensing for OEMs
- **ACV:** $30–40M typical hardware deal; $50M IP revenue locked (Honda, SanDisk, LG, Bosch)
- **Contract structure:** Hardware deployments + multi-year IP licenses

**Distribution strategy:**
- Top-down enterprise sales; major launch event w/ 5 customers on stage (Virtue Financial, Equinix, Seroscale, Neo Cloud, AIN Japan)
- Government/sovereign deals (Qatar $300M order on hold due to Middle East tensions)

---

## Traction

- Shipping $10M/week in product at list price (manufacturing issues resolved) (as of 2026-05-13)
- Hardware revenue target: $200M this year; $48M in orders received since April (as of 2026-05-13)
- IP business: $50M revenue locked with Honda, SanDisk, LG Electronics, Bosch Automotive (as of 2026-05-13)
- Pipeline: 3-4 deals worth $30-40M each — 2 expected to close by end June, all 4 by end July (as of 2026-05-13)
- $6M overnight order from Singapore company (as of 2026-05-13)
- Virtue Financial: scaled POC → production finance AI workloads (as of 2026-05-13)
- Morgan Stanley: POC in progress (as of 2026-05-13)
- XTX Markets ($200M investor): active commercial dialogue (as of 2026-05-13)
- Miami-based HFT firm: interested in low-latency, open software (as of 2026-05-13)
- Headcount: 1,125 (563 engineering, 19 sales, 88 operations) per Harmonic (as of 2026-05-13)

---

## Financing

| Date | Round | Amount | Investors |
|------|-------|--------|-----------|
| (multiple, 2024 prior) | Through Series D | ~$1.03B total | Fidelity, Maverick Capital, Baillie Gifford, Hyundai, LG Electronics, XTX Markets, Samsung Catalyst, Bezos Expeditions, Eclipse, HOOPP, K2 Global, etc. |
| 2026 (in progress) | Convertible Note | $300M (target close June 2024 per founder framing) | Fidelity ($102M+), Maverick Capital, ARK Invest |

**Current round:**
- $300M convertible note at $3.2B valuation cap; 15% discount, 10% PIK interest, 1.4x liquidation preference (as of 2026-05-13)
- $200M additional funding needed to fully close
- Plan: Series F at $6B+ valuation in Q1 2025 if revenue targets hit; potential $10B+ if major hyperscaler customer signed

---

## Deal Team Notes

- 2026-05-13: Update call between Fin Capital (Derek Wu, Logan Allin, Matthew Mann, Matthew Cueto) and Tenstorrent (Walker Stamps, Bob Grim, Isaac Salameh)
- Top 5 bank requesting board seat for major hardware deployment consideration
- Qatar deal on hold ($300M) due to Middle East tensions

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

- [ ] Internal Fin review of $300M convertible note terms
- [ ] Confirm participation in current round or Series F timing
- [ ] Track Q1 2025 Series F trigger (revenue targets)
