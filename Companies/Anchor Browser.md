---
type: company
sector: cybersecurity
sub_sector: AI agent infrastructure / browser automation
stage: Seed
status: sourcing
owner:
founded: 2024
hq: Wilmington, DE
website: https://anchorbrowser.io
linkedin: https://linkedin.com/company/anchorbrowser
crunchbase:
pitchbook: https://pitchbook.com/profiles/company/753300-46
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-06-09
created: 2026-06-09
tags:
  - company
---

# Anchor Browser

> [!summary] One-Liner
> Infrastructure for enterprise-grade computer-using agents — a custom Chromium fork (10,000+ patches) plus an action-index built from hundreds of millions of learned browser interactions that lets AI agents authenticate, bypass MFA/SSO/CAPTCHAs, and operate web applications securely. Pitched as "Fireblocks for crypto, but for computer use." ~$1.5M ARR (May 2026), 60%+ QoQ growth.

---

## Thesis Fit

**Why we like it:**
- Horizontal infra layer with a vertically focused GTM (finance, healthcare, logistics, commerce) — finance is the largest vertical
- Customers are switching from API-based integrations to browser-based specifically for observability and human-in-the-loop control (as of 2026-06-09)
- Self-hosted deployment option (customer cloud) is margin-accretive and unlocks regulated buyers — large US banks in active conversations all want self-hosted (as of 2026-06-09)
- Repeat-founder team out of Noname Security + SentinelOne + Unit 8200
- Capital-efficient growth from $500K → $1.5M ARR in 5 months (as of 2026-06-09)

**Relevant thesis:** [[]]

**Fin sub-sector:** Cybersecurity / AI Agent Infrastructure

---

## Team

| Role | Person | Background |
|---|---|---|
| CEO & Co-Founder | [[Idan Raman]] | Ex-GTM Director (Sales Enablement, SE, Partnerships) at BlinkOps (Austin, 2023–2024); ex-R&D Team Lead at BlinkOps (2021–2023); ex-R&D Team Lead + Senior Software Engineer at Unit 8200; ex-Israeli Air Force Pilots Course + Project Manager |
| CTO & Co-Founder | Dor Dankner | Ex-Head of Research at Noname Security (San Jose, 2021–2023); ex-Research Team Lead + Security Researcher at SentinelOne (Tel Aviv, 2017–2020); ex-Unit 8200 Software R&D (2012–2017) |
| CPO & Co-Founder | Guy Ben Simhon | Ex-Innovation Team Lead at Noname Security (Tel Aviv, 2022–2024); ex-Security Researcher at Noname Security (2021–2022); ex-Unit 8200 Cyber Security Specialist (2017–2021); B.A. Tel Aviv University |
| Fractional CRO | Joshua Behar | Ex-CEO Ericom Security by Cradlepoint (2014–2018); ex-CEO Mobile2CRM (2019–2024); ex-VP Strategic Accounts & BD at Tymely (2024); ex-Amdocs COO/VP Operations (2004–2008); MBA Bar-Ilan, BA UCLA |

> Per Harmonic: company is named "Anchor Browser" (Wilmington, DE, founded 2024-10-01). Granola summary referenced founders "Dor and Guy previously at No Name Security and SentinelOne" — Harmonic confirms Dor Dankner held both Noname (2021–2023) and SentinelOne (2017–2020) roles; Guy Ben Simhon held Noname only (2021–2024).

---

## Business Description

- **Problem:** AI agents that drive browsers in production hit two structural blockers: (1) authentication / identity (MFA, SSO, Cloudflare CAPTCHAs all detect non-human browsers) and (2) brittle automation (full Playwright scripts break on UI changes; fully agentic loops are non-deterministic).
- **Product:** Cloud-based browser platform purpose-built for AI agents:
  - **Authentication & identity layer** — agents log in on behalf of humans, bypass MFA, SSO, Cloudflare CAPTCHAs via a custom Chromium fork with 10,000+ patches to appear human-like
  - **Action-taking layer** — proprietary "action index" built from hundreds of millions of learned browser interactions, lets agents be both dynamic and deterministic across the spectrum from Playwright scripts to fully agentic tasks
  - **Human-to-agent delegation** — agents learn from human browser demonstrations, then take over the workflow
  - **Managed Chromium instances**, secure proxy support, self-healing automation
- **Wedge / entry point:** Enterprises that were previously stuck integrating via APIs (back-office portals, insurance carrier portals, AP workflows) and now want browser-based agents for observability and human-in-the-loop control.

---

## Market & Competition

- **Market:** AI agent infrastructure — specifically the browser-runtime layer beneath vertical and horizontal agent products. Adjacent to Browserbase, Multi-on, Skyvern, and OpenAI's own browser-use stack, but positioned at the enterprise/regulated end with self-hosted and identity-layer differentiation.
- **Positioning vs. APIs:** Some customers are explicitly switching FROM API integrations TO browser-based specifically for observability and human-in-the-loop control (as of 2026-06-09).
- **Analogy used by founder:** "Fireblocks for crypto, but for computer use" — the secure, regulated infrastructure layer that lets agents touch production systems.

---

## GTM & Business Model

- **Pricing (as of 2026-06-09):** Usage-based per browser task
- **Deployment:** SaaS or customer-hosted on their own cloud — self-hosted is margin-accretive for Anchor and the preferred mode for large US banks in active conversations (as of 2026-06-09)
- **Vertical focus:** Finance (largest), healthcare, logistics, commerce
- **Buyer persona:** Vertical AI product teams (Pay Clearly, Applied Pay) building agent workflows; enterprise IT/security at regulated buyers (banks) for self-hosted deployments

---

## Traction

- **ARR (as of 2026-06-09):** ~$1.5M (5 months in from ~$500K at start of 2026 — ~3x growth)
- **Growth rate (as of 2026-06-09):** 60%+ quarter over quarter
- **2026 year-end target (as of 2026-06-09):** $3.5–4M
- **2027 target (as of 2026-06-09):** $15–18M
- **Customers (as of 2026-06-09):**
  - **Pay Clearly** — automated ~80% of accounts payable workflows for AT&T and similar enterprises, replacing offshore Philippines labor at ~20% of the cost
  - **Applied Pay** — connects to insurance carrier portals that were previously human-only, enabling data collection and process automation
  - **Stage** (fintech) — bank compliance automation
  - **Large US banks in active conversations** — all interested in self-hosted deployment
- **Headcount (per Harmonic, as of 2026-06-09):** 20 — Engineering 7, Product 2, Sales 2, Operations 4, Other 4

---

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| 2025-10-22 (per Harmonic) | Seed | $6M | Blumberg Capital, Maccabee Ventures, Gradient |
| In progress (May 2026, per founder) | Series A | $20M total target — **~$8M soft-circled**, ~$12M still open for lead or new investors | Seeking lead |

- **Stage:** Seed (closing Series A)
- **Valuation:** ~$30M post estimated by Harmonic on the prior seed (typical 20% dilution)
- **Note:** Granola summary attributed Seed lead to "Bloomberg Beta and Gradient Ventures." Harmonic shows **Blumberg Capital** (different firm — Blumberg ≠ Bloomberg Beta), Maccabee Ventures, and Gradient. Flagged for confirmation with Idan.

---

## Deal Team Notes

- 2026-06-09 — First Granola-captured intro call. Derek Wu and Jake Fuchs on Fin side; Idan Raman (CEO) on Anchor side. Granola id `aaaab72a-5a26-4487-af85-cae73f20fa79`. See [[Anchor Browser - 2026-06-09 Summary]].
- Horizontal infra + vertical GTM is the right pattern for an agent infra company today — Fin's financial-services LP base maps directly onto Anchor's primary vertical.
- API → browser migration framing is a strong narrative point — customers are actively de-prioritizing API integrations because they can't observe or control agent behavior on them.
- Self-hosted deployment for banks is a margin tailwind, not a margin drag — flagged as a positive datapoint for diligence economics.
- Granola → Harmonic investor discrepancy: "Bloomberg Beta" (Granola) vs. **Blumberg Capital** (Harmonic). Two distinct firms — confirm with Idan which seed investor is correct.

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

- [ ] Receive pitch deck from Idan (sent during call)
- [ ] Derek to try Anchor Browser product firsthand for YC scraping use case
- [ ] Flag Anchor at Wednesday team meeting; advance to product demo and partner intro if interest confirmed (Jake, Derek)
- [ ] Confirm seed investor identity — Blumberg Capital vs. Bloomberg Beta — with Idan
- [ ] Validate $1.5M ARR and 60%+ QoQ growth in diligence
- [ ] Diligence self-hosted deployment economics vs. SaaS gross margin
- [ ] Reference one of the named bank prospects on self-hosted ZTNA / deployment requirements
- [ ] Determine fit against Fin's broader agent-infrastructure / cybersecurity thesis
