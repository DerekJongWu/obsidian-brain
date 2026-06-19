---
type: meeting
date: 2026-06-18
company: Qeso
attendees: Derek Wu, Jake Fuchs, Eddy Bobritsky, Eyal Gurevich, Dani Kamanovsky
meeting_type: follow-up
transcript: "[[Qeso - 2026-06-18 Transcript]]"
created: 2026-06-18
tags:
  - meeting
---

# Qeso - 2026-06-18 Summary

[[Qeso]] | 2026-06-18 | Follow-up

## Attendees

- [[Eddy Bobritsky]] (CEO & Co-Founder, Qeso)
- Eyal Gurevich (COO & Co-Founder, Qeso)
- Dani Kamanovsky (Co-Founder, Qeso)
- Derek Wu (Fin)
- Jake Fuchs (Fin)

## Transcript

[[Qeso - 2026-06-18 Transcript]]

## Platform Overview

- Core function: maps all security exclusions and exceptions across an org's stack, correlates them, and surfaces compound risk
  - Connects to CrowdStrike, Microsoft, and ~50+ other platforms via API
  - Calculates "choke points": the top 3-5 combined blind spots most likely to enable a breach
  - Also models attack paths from the outside in, narrating exactly how an attacker would move
- Compensating controls: when an exclusion can't be removed, Qeso recommends mitigations
  - Examples: Microsoft ASR rules, AppLocker, scoped audit policies
  - Steps are ranked by ease of deployment; all shown are free and low-risk
  - Simulation mode shows blast radius before any change is applied
- Retroactive mapping for new customers
  - Pulls existing exclusions from connected platforms (e.g. CrowdStrike API has a clean list)
  - For systems without records (CI/CD, supply chain, internal tools), Qeso reconstructs context from experience
  - Day-one POC value is high: finds orphaned exclusions (deleted users, retired software, 15-year-old AD exceptions)
- Roadmap highlights
  - Automated cleanup of unused exclusions (no business need = auto-remove)
  - Agentic workflow: developer requests access, security agent evaluates compound risk, grants and auto-revokes
  - Crowdsourced threat intel + vendor feeds to benchmark exclusion hygiene by industry
  - Custom connector builder so customers can onboard internal platforms without waiting for native support

## Fundraise Status

- Raising $10M seed; target: 24-month runway, $2M ARR, broad product buildout
- Committed so far: Silver Standard + one other VC at ~$1M each (soft-circled, not the lead)
- Two Israeli VCs in advanced conversations, either could lead the full round
- Eyal relocating to US post-raise to build US presence (currently heavy Israel/light US split)

## Next Steps

- Share lead VC names with Derek under NDA once confirmed with the team (Eyal)
- Derek to discuss with Fin partnership before any commitment; interest confirmed, no authority to commit unilaterally (Derek)
