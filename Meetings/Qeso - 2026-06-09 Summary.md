---
type: meeting
date: 2026-06-09
company: Qeso
attendees: Derek Wu, Jake Fuchs, Eddy Bobritsky, Eyal Gurevich, Dani Kamanovsky
meeting_type: intro
transcript: "[[Qeso - 2026-06-09 Transcript]]"
created: 2026-06-09
tags:
  - meeting
---

[[Qeso]] | 2026-06-09 | Intro

## Attendees

- [[Eddy Bobritsky]] — CEO & Co-Founder, [[Qeso]]
- Eyal Gurevich — COO & Co-Founder, [[Qeso]] (no person note yet)
- Dani Kamanovsky — Co-Founder, [[Qeso]] (no person note yet; first Minerva employee, led endpoint security at Rapid7)
- Derek Wu (Fin Capital)
- Jake Fuchs (Fin Capital)

## Transcript

[[Qeso - 2026-06-09 Transcript]]

## Team & Background

- **Eddy Bobritsky, CEO** — 7 years IDF cyber officer; founded Minerva Labs in 2014 (raised $7.5M); sold to Rapid7 in 2023 for $40M + $5M retention (~$4M ARR at exit, on track for $6M).
- **Eyal Gurevich, COO** — 9 years IDF cyber elite unit; 6 years at CyberArk; joined Minerva through to the Rapid7 exit.
- **Dani Kamanovsky** — first Minerva employee; led endpoint security group at Rapid7 across 5 teams and 4 continents.

## Product: Security Exclusion & Exception Management

- **Core insight:** Every enterprise accumulates thousands of security control exclusions (EDR, cloud, network, etc.) that are never cleaned up or centrally tracked.
  - Average enterprise runs ~80 security controls; exclusions can number in the hundreds to tens of thousands per tool.
  - Math: 20 controls × 100 exclusions × 2,000 assets ≈ 4M blind spots.
  - CISOs surveyed couldn't estimate their total exclusion count, let alone which are still needed.
- **Why exclusions are structurally dangerous:**
  - Disabling a security capability removes vendor liability entirely (per EULA).
  - Vendors have no incentive to add expiry dates: more exclusions = less liability for them.
  - Siloed ownership: EDR exclusions owned by security, cloud by DevOps, network by IT; no cross-visibility.
  - Currently managed via spreadsheets, Jira, or SharePoint at best.
  - 82% of attacks exploit non-malware blind spots (CrowdStrike); 30% of successful ransomware attacks leveraged EDR exclusions (Microsoft, Oct 2025).
- **AI / vibe coding accelerant:** Employees and agents are generating exclusion requests at exponential rates.
- **Platform vision — control plane and system of record for all accepted risk across the org:**
  - Connects to security controls, business tools (Slack, Jira, ServiceNow), threat intel, and software vendors.
  - Cross-correlates exclusions to map compound attack vectors, not just catalog them.
  - Use cases: GRC audit / proof of review, M&A due diligence, pen testing (white-box), cyber insurance, CISO policy enforcement.
  - Longer-term: agentic infrastructure layer where AI agents request and receive scoped exclusion approvals automatically.
- **SIEM blind spot:** CrowdStrike stops forwarding logs for excluded assets, so the SOC can't see them either.

## Fundraise & Traction

- Raising **$10M seed**; US-incorporated entity.
- One design partner active (CISO at CBC-level firm) — discussing ~$200K ARR.
- Second design partner meeting next week — Henry at **Barrel Fans** (known from Minerva days).
- **Charlie Silverstein committed.** Actively seeking lead investor; prefer smart money with financial services connections; a few weeks into lead conversations.
- **Team location:** Eyal already in NJ; Eddy and Dani in Israel, plan to relocate post-raise. Development team to be distributed (Israel, Europe, US). *Fin SBIC vehicle has US headcount/operations requirements — worth monitoring.*

## Next Steps

- Qeso to send deck.
- Derek and Jake to confirm product demo for next week by end of week.
- Warm intros to potential co-investors if Fin moves forward (Derek/Jake).
