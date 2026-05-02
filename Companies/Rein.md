---
type: company
sector: cybersecurity
sub_sector: agentic AI / application security
stage: Seed
status: sourcing
owner:
founded: 2024
hq: New York, NY
website: https://reinsec.io
linkedin: https://linkedin.com/company/rein-security
crunchbase:
pitchbook: https://pitchbook.com/profiles/company/1014284-71
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-05-01
created: 2026-05-01
tags:
  - company
---

> [!info] One-Liner
> Rein builds an application sidecar for agentic AI security — deploying directly into the pod where an agent runs to monitor behavior at the application layer with sub-millisecond latency, creating deterministic actions for non-deterministic workflows.

## Thesis Fit

Application-layer runtime security for AI agents. Rein addresses a structural gap: identity and prompt-filtering tools cannot prevent unauthorized agent actions in real time. Sits at the intersection of agentic AI infrastructure and application security.

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Matan Bar-Efrat]] | Unit 8200 alum; former Director of Sales & BD Europe at Cyberbit and Elbit Systems |
| Co-Founder & CTO | Netanel Rubin | Unit 8200 security researcher; Senior Vulnerability Researcher at Check Point; CTO at Lab42 |
| VP R&D | Roy Cagan | Unit 8200 Head of Cyber Operations & R&D Division; former CTO at Jeeng (acquired by OpenWeb) |
| VP Ops | Liat Morad | IDF C4I leadership; Director of Cyber Operations at Lab42 |
| VP People | Hadar Bar-Kat | Former Chief People Officer at Jeeng |

## Business Description

- **Problem:** Agentic AI workflows are non-deterministic and existing security tools (identity governance, prompt filtering, syscall monitors) cannot prevent unauthorized agent actions in real time.
- **Product:** Application sidecar deployed into the pod where an agent runs (via env var). Profiles resource consumption and execution context, baselines code execution paths, and ties them to API calls, libraries, and functions. Returns "permission denied" when an agent attempts unauthorized actions.
- **Wedge:** Agentic security positioning — board-level priority that drives faster sales cycles. Expansion replaces traditional stack (e.g., Snyk, API security tools).

## Market & Competition

- **Differentiation:** Only solution monitoring actual execution vs. configuration access. Distinguishes admin API config access (normal) from other API config access (problematic).
- **Competitors / adjacent:** Token Security (identity governance only — cannot prevent actions in real time, only forensic), Upwind (Salesforce tender competitor), Snyk and traditional API security tools (displaced on expansion).
- **Performance envelope:** <0.5ms latency, 20MB memory, <1% CPU.

## GTM & Business Model

- **Land:** Agentic security positioning — fast board-level approval.
- **Expand:** Replace traditional stack (Snyk, API security). H&R Block removing 3 tools for Rein on a $300K contract.
- **Dual value prop:** Security + observability. Lemonade uses Rein as observability tool alongside DataDog; developers log in daily to understand API/agent behavior; new developer onboarding runs through the Rein platform.

## Traction

- ARR: $700K (as of 2026-05-01)
- Headcount: 25 (7 engineering, 7 operations, 3 sales, 1 marketing, 1 design, 1 people, 1 data)
- Key prospects:
  - Salesforce — tender vs. Upwind scheduled May 15, ~$300K target
  - ServiceNow — product deployed on agents conducting pentests; venture arm likely investing
  - H&R Block — $300K contract, displacing 3 incumbent tools
  - Lemonade — observability use case alongside DataDog

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| 2026-01-28 | Seed | $8M | Glilot Capital Partners; Amir Jerbi; Ofer Ben-Noon |

**Current round (as of 2026-05-01):** Term sheet signed with Glilot. Targeting $5M from followers within 2.5–3 weeks; split between strategic and venture investors. US relocation post-raise confirmed (visa filed, relocation agency selected).

## Deal Team Notes

- Fin considering quick follow-on investment.
- Potential partner meeting if needed; Monday team meeting to discuss internally.
- Strategic angle: could expand into identity space (already captures JWT/authorization data) but currently focused on behavior monitoring.

## Meetings & References

```dataview
TABLE date, meeting_type
FROM "Meetings"
WHERE company = "Rein"
SORT date DESC
```

## Next Steps

- [ ] Internal Monday team meeting on potential follow-on
- [ ] Decision on partner meeting
- [ ] Track Salesforce tender outcome (May 15)
