---
type: company
sector: "developer tools"
sub_sector: "version control / source control for scale"
stage: "Seed"
status: "sourcing"
owner:
founded: 2022
hq: "San Francisco, California"
website: "https://diversion.dev"
linkedin: "https://linkedin.com/company/diversion-company-inc"
crunchbase: "https://www.crunchbase.com/organization/diversion-company"
pitchbook: "https://pitchbook.com/profiles/company/497765-71"
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-05-26
created: 2026-05-26
tags:
  - company
---

> [!info] One-Liner
> Diversion is a cloud-native version control system built for scale — a Git alternative for the AI era (and for large-file/monorepo workloads that Git can't handle), architected like Dropbox/Gmail for massive data, with a GitHub sync path for gradual migration. Early traction in game dev / creative industries, expanding to enterprises (finance, gaming, semiconductors).

## Thesis Fit

- Infrastructure bet on a post-Git source-control layer as AI agents explode code/data volume (each engineer running ~10 agents, ~20x faster)
- Cloud-native architecture solves the monorepo/large-file/scale problems Google and Facebook built proprietary systems for
- Repeat-founder team (Sasha Medvedovsky, 2 prior exits) with Dropbox alumni; YC-backed; real bottoms-up traction (40K developers, 1M+ commits)

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Sasha Medvedovsky]] | Co-Founder & CEO since 2021; CS master's + MBA (Tel Aviv University), YC; 2 prior exits — ex-Adience Co-Founder & CPO, ex-Leprechaun Systems VP R&D/Co-Founder; ex-IDF algorithms/lead SWE; ex-NICE |
| Co-Founder & CTO | Egal Lazarev | Co-Founder & CTO since 2021; YC; ex-Adience (lead SWE), ex-Voyantis/Assured Allies; co-founder from a prior startup with Sasha; IDF Intelligence cyber R&D team leader; BSc Tel Aviv University |
| Chief Strategy Officer | Meir Morgenstern | CSO since 2024 (advisor from 2021); ex-Dropbox Israel Site Lead; ex-CloudOn Co-Founder & VP Eng (acquired by Dropbox); ex-Pangea (co-founder/chairman, acquired by Clarivate); ex-Cisco; MBA Tel Aviv University |

## Business Description

- **Problem:** Git was built ~21 years ago and doesn't scale for the AI era — conservatively ~1000x more data creation is coming as each engineer runs ~10 agents at ~20x human speed. Git struggles with large files and monorepos (GitHub's CTO cited monorepos as the biggest unsolvable challenge); Google/Facebook built their own systems to cope.
- **Product:** Cloud-native version control vs. Git's local-machine constraints — built like Dropbox/Gmail for massive data management, with real-time sync, large-file management, web interface, IDE plugins, and an interactive CLI. A synchronization tool with GitHub (releasing in a few weeks) enables gradual migration.
- **Wedge:** Large enterprises that couldn't use Git — financial sector, gaming, semiconductors — and game development / virtual production (Unreal-powered, large binary assets) per Harmonic's profile.

## Market & Competition

- Replaces/augments Git/GitHub at scale; GitHub has ~180M users vs. ~30–40M actual developers worldwide
- Market opportunity amplified by GitHub reliability issues — founder cited uptime degrading "from 11 nines to zero nines," outages every other day, enterprises seeking alternatives
- Differentiation: cloud-native architecture, large-file/monorepo handling, gradual GitHub-sync migration

## GTM & Business Model

- Pricing: $25–50 per seat/month, plus usage-based for AI agents
- Migration strategy: GitHub synchronization tool enabling gradual transition (releasing in a few weeks)
- Enterprise pipeline (as of 2026-05-26):
  1. **Activision** — final contract stages, $50K for 50 users ($1K/seat/year); full-deployment potential 400 users ≈ $2.5M contract
  2. **Supercell** — active evaluation, biggest project imported
  3. **Japanese subsidiary** — already a paying customer
- Revenue target: $50M ARR from enterprise + self-service

## Traction

- 40K developers signed up; 30K projects; 1M+ commits in production (as of 2026-05-26)
- Launched January 2024; spent ~18 months hardening edge cases
- 500–600 weekly signups; active Discord community (~3K members)
- Headcount: 17 per Harmonic (as of 2026-05-26)

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| Through 2025-05 | Seed (3 rounds) | ~$12.4M total per Harmonic; founder cited ~$11.7M raised | New Era Capital Partners, Y Combinator, Konvoy, Secret Chord Ventures, Pioneer Fund, Evening Fund |
| 2026 (in progress) | (round) | Raising $15M | — |

- Financing history: $11.7M raised per founder private notes; Harmonic records ~$12.425M across 3 seed rounds (last May 2025)
- Currently raising $15M (as of 2026-05-26)

## Deal Team Notes

- 2026-05-26: Intro Teams call with Sasha Medvedovsky (Co-Founder & CEO); Derek Wu and Jake Fuchs on Fin side
- Founding-date note: founder stated "Founded August 2022"; Harmonic shows 2021 (founders' roles start Dec 2021) — used 2022 in frontmatter, minor discrepancy
- Positioning note: Harmonic profile emphasizes game dev / creative industries (Unreal, virtual production); founder framed it more broadly as a Git replacement for the AI era / enterprise scale — both captured
- Funding figures: founder ~$11.7M raised + raising $15M; Harmonic ~$12.4M across 3 rounds — reconcile
- Sasha to send deck to Jake and Derek; Fin to socialize internally and respond by end of week

## Meetings & References

```dataview
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC
```

## Next Steps

- [ ] Receive deck from Sasha; socialize internally and respond by end of week
- [ ] Reconcile funding ($11.7M vs ~$12.4M) and current $15M round terms
- [ ] Diligence enterprise pipeline (Activision contract, Supercell eval)
- [ ] Validate GitHub-reliability tailwind and migration-tool traction
