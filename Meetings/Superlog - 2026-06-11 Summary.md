---
type: meeting
date: 2026-06-11
company: Superlog
attendees: Derek Wu, Jake Fuchs, Nicolò Magnante
meeting_type: intro
transcript: "[[Superlog - 2026-06-11 Transcript]]"
created: 2026-06-11
tags:
  - meeting
---

[[Superlog]] | 2026-06-11 | Intro

## Attendees

- [[Nicolò Magnante]] — Co-Founder & CEO, [[Superlog]]
- Derek Wu (Fin Capital)
- Jake Fuchs (Fin Capital)

## Transcript

[[Superlog - 2026-06-11 Transcript]]

## Team and Company Background

- Nicolò and Arseniy: best friends from Paris, co-founded together.
- **Arseniy:** Russian-born, started coding at 12, national coding olympiad winner, attended **42 Paris** (elite French coding school), then spent **3–4 years at Datadog** building core architecture.
- **Nicolò:** studied in the US (Michigan), attended **HEC Paris** (top European business school), **BCG** background, launched a startup as EIR and scaled to $1M ARR in year one.
- **Previous company (Bluco** — Granola summary says "Bluecol"; Harmonic spelling is Bluco): bootstrapped HR/blue-collar staffing platform.
  - Clients included **McDonald's, Burger King, Volkswagen**.
  - Shut down after a third co-founder's family (Mexican investors) sued them post-rejection of a buyout offer.
  - Arseniy's visa was at risk, forcing a clean exit.
- Relocated to SF December 2025 / January 2026, selected by YC (P26), Demo Day next Tuesday (week of 2026-06-15).

## Product: Superlog

- **Core thesis:** observability tooling was built for human engineers reading dashboards; today agents write and review code, so the data format, storage, and consumption model needs to be rebuilt from scratch.
- **One-prompt install:** paste a prompt into Claude Code, Cursor, or Codex; the agent auto-instruments traces, logs, and metrics for all future features.
  - No integration with Datadog or any existing vendor; redirects existing telemetry to Superlog on install.
  - Arseniy's prior Datadog architecture knowledge enables migration in ~20 minutes vs. months.
- **Telemetry storage:** ClickHouse (cheaper than Datadog); accessible via platform or Slack shortcuts.
- **Output is a PR, not an alert:** Superlog identifies the one meaningful alert out of many and auto-generates a fix.
  - **80%+ of PRs merged as-is**; remainder tweaked via Greptile, Copilot, etc., then pushed.
  - **North star:** fully self-healing product (Superlog chooses what to merge autonomously).
- **Traction:** 350+ organizations onboarded in the last month; ~20 PRs auto-generated per org per week.
- **GTM strategy:** win startups first (fastest AI adopters, Datadog no longer keeping up), grow with them into mid-market, then upsell enterprise.
  - Datadog is a known LP-adjacent vendor for Fin's LPs; Nicolò framed this as a complement initially, full rip-and-replace over time.

## Raise and Next Steps

- Raising **$2M cash** on top of **$2M in OpenAI tokens** and **~$4–4.5M YC money**.
- Round moving fast: started Monday 2026-06-08, already largely committed.
  - Key angels include **ex-Datadog executives** and SF-based operators.
  - Two additional fund conversations ongoing, potentially at a higher total raise.
- Use of funds: hire two world-class engineers (one infra, one ML, both known personally).
- **Hard deadline:** round may close before next Wednesday/Thursday (week of 2026-06-15).

## Next Steps

- Share deck with Fin team (Nicolò).
- Fin team to sync internally Wednesday 2026-06-17 and respond with feedback by Wed/Thu 2026-06-17/18 (Derek, Jake).
