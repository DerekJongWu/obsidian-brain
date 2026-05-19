---
type: company
sector: cybersecurity
sub_sector: identity security / ITDR / NHI
stage: Seed
status: sourcing
owner:
founded: 2024
hq: Tel Aviv, Israel
website: https://rig.security
linkedin: https://linkedin.com/company/rig-security
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-05-18
created: 2026-05-18
tags:
  - company
---

# Rig Security

> [!summary] One-Liner
> Identity protection platform combining risk management and threat detection across human and AI/non-human identities. Built the Rig Identity Correlation Engine (RICE) with Harvard ML specialists for 95%+ confidence in cross-system identity correlation, plus open AI-powered risk scoring and ITDR with automated remediation.

---

## Thesis Fit

**Why we like it:**
- Squarely on Fin's broader identity thesis (NHI, ITDR, AI agent identity) — natural extension of the Symphony investment
- ITDR market validation: Rig's investor (rendered "Corrugated"/"Quasterk" in Granola — likely Cyberstarts / Cresta / similar) has 50+ portfolio customers paying $2M+/yr for ITDR alone (as of 2026-05-18)
- Real customer pull across Insurance, Healthcare, Financial Services — just started pilot with the largest NYC-based private equity firm after multiple calls (as of 2026-05-18)
- Founder pedigree: Guy Kozliner (ex-Wiz CTO Team, prior CU founder/acquired) + Nissim Bitan (ex-Rookout, Firefly founding engineer, Aqua Security, IDF Cyber Defense)
- Differentiated wedge: combines human + non-human identity in one platform, not a point ITDR solution

**Relevant thesis:** [[]] (NHI / Identity)

**Fin sub-sector:** Cybersecurity / Identity Security / NHI & ITDR

---

## Team

| Role | Person | Background |
|------|--------|------------|
| Co-Founder & CEO | [[Guy Kozliner]] | CTO Team at Wiz (2022–2024); Co-Founder & CEO of CU (acquired 2023, expanded to 17 EMEA countries); COO at FrontLife; SWE & DevOps at Cybereason; B.Sc. The Academic College of Tel-Aviv, Yaffo + cybersecurity program at Technion |
| Co-Founder & CTO | Nissim Bitan | Tech Lead & Senior SWE at Rookout (2023–2024); Principal SWE / Founding Engineer at Firefly; Senior DevOps SWE at Aqua Security; DevOps SWE at Taboola; Cloud Architect at IDF J6 & Cyber Defense Directorate; CS at The College of Management Academic Studies |

---

## Business Description

- **Problem:** Existing IGA/IAM/PAM solutions manage identity lifecycle but don't continuously assess identity risk or detect identity-driven threats — especially the explosion of non-human / AI agent identities accessing production systems where traditional network-edge controls don't reach.
- **Product:** Identity protection platform with three core capabilities:
  1. **Posture management** with AI-powered continuous risk scoring (Open Risk Evaluation Scoring)
  2. **NHI inventory** — API keys, tokens, agents accessing production
  3. **Identity Threat Detection & Response (ITDR)** with automated/semi-automated remediation via the Rig AI agent
- **Core innovation:** Rig Identity Correlation Engine (RICE) — ML models developed with Harvard specialists, 95%+ confidence correlating identities across company systems and tracking threat movement between identities where the network edge stops.
- **Deployment options:**
  1. Agentless API ingest (cloud + on-prem)
  2. On-prem connectors (egress only)
  3. Bifrost endpoint sensor for local sessions, agents, and fingerprints

---

## Market & Competition

- **Market size:** ITDR alone is a multi-billion category — investor Q has 50+ portfolio customers paying $2M+/yr for ITDR (as of 2026-05-18). NHI/identity-graph adjacencies expand it materially.
- **Not replacing:** SailPoint, Okta, CyberArk, BeyondTrust — Rig is complementary to existing IGA/IAM/PAM stacks.
- **Threats caught that other solutions miss:** AI agents accessing production systems, cross-system lateral movement, privilege escalation.
- **Potential overlap with [[Symphony]] (Fin portfolio, stealth):**
  - Symphony: identity access graph focused on human employees, real-time anomalous behavior, insider risk
  - Rig: NHI + endpoint approach, infrastructure-centric
  - Per Guy: no competitive overlap encountered in market; Symphony reads as "human-focused / phishing / awareness / mixed positioning" vs Rig's NHI + ITDR infrastructure positioning
  - Fin conflict check ongoing — message to Symphony team this week, response expected by end of week

---

## GTM & Business Model

- **Buyer persona:** Security architecture and identity teams at regulated enterprises — Insurance, Healthcare, Financial Services, Private Equity (as of 2026-05-18)
- **Pilot pipeline (as of 2026-05-18):** Just started a pilot with the largest NYC-based PE firm after multiple calls
- **Pricing:** Not disclosed in this call

---

## Traction

- **Customer base (as of 2026-05-18):** Active across Insurance, Healthcare, Financial Services; pilot with largest NYC-based PE firm
- **Team growth (as of 2026-05-18):** Headcount expanding — Harmonic shows 3 today, clearly stale
- **Receiving inbound fundraising inquiries; decided to proceed with raise**

---

## Financing

| Date | Round | Amount | Investors |
|------|-------|--------|-----------|
| To date (per Harmonic) | Pre-seed / undisclosed | — | Cyberstarts (likely) and other identity-focused funds — investor name rendered "Corrugated" / "Quasterk" in Granola, awaiting confirmation |

**Current round (as of 2026-05-18):**
- Active raise — Guy managing multiple processes with time sensitivity
- Fin investment posture if no Symphony conflict:
  - Participatory check, $2–12M range, flexible sizing
  - Co-lead possible, not standalone lead
  - Process can move fast if Fin is following the existing round
- Quasterk / Corrugated investor (Granola renderings) was cited as the validation point for the ITDR market — 50+ customers paying $2M+/yr each

---

## Deal Team Notes

- 2026-05-18: Granola-captured call. Two simultaneous Granola recordings (Derek's + Jake's) of the same physical meeting; this note synthesizes both. Derek Wu + Jake Fuchs on Fin side; Guy Kozliner (CEO) on Rig side. See [[Rig Security - 2026-05-18 Summary]].
- **Symphony conflict-check is the gating item** — Fin to message Symphony team today/tomorrow, response expected by end of week. Guy's read is that Symphony is human-/awareness-focused and Rig is NHI/infrastructure-focused, but Fin must confirm.
- Investor name "Corrugated" (Derek's recording) / "Quasterk" (Jake's recording) is almost certainly a Granola misrendering — likely Cyberstarts given the Israeli + identity + ITDR pattern. Flagged for confirmation.
- Guy was on the CTO Team at Wiz from 2022–2024 — strong cloud-security operator network; also founded and exited CU (community-management platform, acquired 2023). The "Stealth Company (Guy Kozliner)" Harmonic profile is almost certainly Rig Security pre-naming — start date 2024-10 lines up with Rig's founding-date timeline.
- Harvard ML collaboration on RICE is a notable academic anchor; worth diligencing whether the Harvard relationship is a published-research partnership or contract work.

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

- [ ] Run Symphony conflict check this week and resolve by end of week
- [ ] Confirm true investor name (likely Cyberstarts or similar — "Corrugated"/"Quasterk" appears to be Granola misrendering)
- [ ] Diligence the RICE model — Harvard ML collaboration, 95%+ correlation confidence, methodology
- [ ] Diligence the NYC PE pilot — stage, scope, expected conversion timing
- [ ] Diligence Bifrost endpoint sensor — coverage and competitive vs CrowdStrike/Sentinel-style endpoint agents
- [ ] Customer references in Insurance, Healthcare, FS verticals
- [ ] Term sheet and round structure clarification — co-lead vs participation
