---
type: meeting
date: 2026-05-01
company: Rein
attendees: Derek Wu, Matan Bar-Efrat, Jake Fuchs
meeting_type: intro
transcript: "[[Rein - 2026-05-01 Transcript]]"
created: 2026-05-01
tags:
  - meeting
---

[[Rein]] | 2026-05-01 | Intro

## Attendees

- Derek Wu (Fin Capital)
- [[Matan Bar-Efrat]] (Rein, Co-Founder & CEO)
- Jake Fuchs (Fin Capital)

## Transcript

[[Rein - 2026-05-01 Transcript]]

## Company Overview

- [[Rein]] builds an application sidecar for agentic AI security.
- Deploys directly into the pod where the agent runs via an environment variable.
- Performance: <0.5ms latency, 20MB memory, <1% CPU impact.
- Monitors agent behavior at the application layer vs. traditional prompt filtering or syscall monitoring.
- Core thesis: creating deterministic actions for non-deterministic workflows.
  - Profiles resource consumption and execution context.
  - Baselines each code execution and associates it to API calls, libraries, and functions.
  - Returns "permission denied" when an agent attempts unauthorized actions.

## Team

- Founded by Unit 8200 veterans: [[Matan Bar-Efrat]] and his co-founder.
- Matan previously managed the European region at Cyberbit.
- Co-founder was a vulnerability researcher at Check Point; sold a company to Elbit.

## Product & Technical Approach

- Application-layer behavioral monitoring rather than configuration or identity-only access.
- Captures JWT / authorization data for governance.
- Distinguishes admin API config access (normal) from other API config access (problematic).

## Go-to-Market

- **Land:** Agentic security positioning — board-level priority, faster sales cycles.
- **Expand:** Replace traditional stack (Snyk, API security tools).
  - H&R Block: removing 3 tools for Rein on a $300K contract.
- Dual value prop serves security and observability:
  - Lemonade uses Rein as an observability tool alongside DataDog.
  - Developers log in daily to understand API/agent behavior.
  - New developer onboarding runs through the Rein platform.
- Key prospects:
  - **Salesforce:** Tender process vs. Upwind scheduled May 15, ~$300K target.
  - **ServiceNow:** Product deployed on their agents, conducting pentests; venture arm likely investing.

## Pricing & Competition

- **Token Security:** identity governance only — cannot prevent actions in real time, only provides forensic analysis. Cannot prevent agent data exfiltration from databases.
- Rein's edge: only solution monitoring actual execution vs. configuration access.
- Could expand into identity space but strategically focused on behavior monitoring; considering integrations with identity providers for data sharing.

## Financing & Growth

- Current ARR: $700K.
- Signed term sheet with Glilot.
- Targeting $5M from followers within 2.5–3 weeks; split between strategic and venture investors.
- US relocation post-raise confirmed (visa processes filed, relocation agency selected).

## Next Steps

- Fin considering a quick follow-on investment.
- Potential partner meeting if needed.
- Monday team meeting to discuss internally.
