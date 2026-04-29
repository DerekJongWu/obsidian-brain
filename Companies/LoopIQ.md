---
type: company
sector: "developer tools"
sub_sector: "AI-native SDLC / compliance"
stage: "Pre-seed"
status: "passed"
owner:
founded: 2025
hq: "Jersey"
website: "https://loopiq.com"
linkedin: "https://linkedin.com/company/loopiq-corp"
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-04-28
created: 2026-04-28
tags:
  - company
---

> [!info] One-Liner
> LoopIQ is a compliance-first, AI-native SDLC workspace that unifies idea management, planning, testing, DevOps, and compliance — using AI micro-agents to automate repetitive work, predict delivery risks, and certify releases with real metrics.

## Thesis Fit

- AI-native SDLC tooling adjacent to Fin's enterprise AI thesis
- Compliance-first wedge (release certification, evidence collection) is interesting, but design partners are not in financial services today
- **Pass for now**: Fin requires at least one financial services design partnership before engaging on a seed round
- Re-engage once Ashwin secures a bank/asset manager design partner

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CTO | [[Ashwin Kondapalli]] | LoopIQ Founder (Dec 2025–present); ex-Equifax (QE Manager, QE Architect, QA Automation), ex-Mastercard (SDET contractor), ex-DHI Group (Senior QA Automation), B.E. Visvesvaraya Technological University |
| Co-Founder | Divya Lokala | ex-United Health, ex-Citi |
| Co-Founder | Abhishek | ex-Amazon, ex-Goldman Sachs |

## Business Description

- **Problem:** SDLC tooling fragmentation across Jira, ServiceNow, test management, etc.; manual, error-prone audit/compliance evidence collection at release time
- **Product:** Unified data model spanning idea management, project management, test management, compliance, and knowledge management
- **Wedge:** Automated release certification with continuous compliance tracking — collects evidence from security/code-scanning tools (SonarQube, Checkmarx, Datadog, GitHub Security); flags policy violations at release time; tracks exceptions, deviations, and accepted risks in a release dossier
- **Technical approach:** Integrates with Google Cloud Zero Trust agent identity framework; 76 AI micro-agents in production across SDLC regions; OpenAI Codex and GitHub Copilot integrations in progress

## Market & Competition

- ICP validated at Google Cloud Next: healthcare, fintech, and insurance
- ~5 employees on Harmonic (as of 2026-04-28); LinkedIn followers 452 (+5.7% MoM, +144% over 180 days)
- Competing against fragmented incumbent stack (Jira, ServiceNow, separate test management, separate compliance tooling)

## GTM & Business Model

- Three product variants:
  1. **SaaS** — $10–$30 / user / month, targeting startups to mid-market
  2. **Enterprise** — air-gapped / private cloud deployment, minimum $50K / year ACV
  3. **LoopIQ Analytics** — predictive analytics layer, crossover between SaaS and Enterprise
- Pricing user- and feature-based; Enterprise tokens not charged separately (customers tie to their own Vertex AI environment)
- GTM motion: target CTOs / CIOs; key pain point is manual, error-prone audit / compliance evidence collection at release time
- Team composition: 3 co-founders + 4 offshore developers + 2 onshore sales/marketing

## Traction

- 2 design partners (both India-based) — ~96 users total
  - Consulting firm: ~50 users
  - ZX AI (test automation company): ~46 users
- 130 leads from Google Cloud Next sponsorship; majority hot (15–20 min demo engagement)

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| — | Pre-seed (target) | $5M | TBD |

- Bootstrapped to date; raising $5M seed round (proceeds: product team scaling, sales/marketing)
- Valuation/dilution not yet determined — Ashwin to follow up
- No funding rounds recorded (Harmonic, as of 2026-04-28)

## Deal Team Notes

- 2026-04-28: Discovery call with Ashwin Kondapalli (CTO); Derek Wu solo on Fin side
- **Pass for now**: no financial services design partners yet — prerequisite for Fin's thesis
- One FS logo tends to unlock others; Fin wants to see at least one bank/asset manager design partnership before engaging
- Ashwin plans to convert hot fintech leads from Google Cloud Next into design partners before re-engaging

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Ashwin to follow up with hot fintech/FS leads from Google Cloud Next to secure a design partner
- [ ] Ashwin to circle back to Derek once a financial services design partnership is in place
- [ ] Ashwin to send target valuation / dilution figures for the seed round
- [ ] Derek remains available for ad-hoc fundraising / VC strategy questions
