---
type: company
sector: developer tools
sub_sector: AI-native observability / agent-instrumented telemetry
stage: Pre-Seed
status: sourcing
owner:
founded: 2026
hq: San Francisco, CA
website: https://superlog.sh
linkedin: https://linkedin.com/company/superlogyc
crunchbase:
pitchbook:
deck_link:
data_room:
lighthouse_link:
last_touch: 2026-06-11
created: 2026-06-11
tags:
  - company
  - "#sourcing"
  - "#devtools"
  - "#observability"
---

# Superlog

> [!summary] One-Liner
> AI-native observability platform — rebuilds the data format, storage, and consumption model of telemetry for a world where AI agents (not humans) read dashboards. One-prompt install via Claude Code / Cursor / Codex auto-instruments traces, logs, and metrics; output is a merge-ready PR, not an alert. YC P26 company raising $2M cash on top of $2M OpenAI tokens + ~$4–4.5M YC capital; round started Monday and largely committed.

---

## Thesis Fit

**Why we like it:**
- Co-founder Arseni was core architecture at Datadog (3.5 yrs) — migration off Datadog onto Superlog takes ~20 min vs. months
- Output is a PR, not an alert — 80%+ of generated PRs merged as-is; trajectory to fully self-healing
- 350+ organizations onboarded in the last month (as of 2026-06-11); ~20 PRs auto-generated per org per week
- Datadog "no longer keeping up" with startup AI adopters → clear bottom-up wedge into mid-market and enterprise
- YC P26 Demo Day next Tuesday (week of 2026-06-15); round closing before Wed/Thu of following week

**Relevant thesis:** [[]]

**Fin sub-sector:** Developer Tools / AI-native Infrastructure

---

## Team

| Role | Person | Background |
|---|---|---|
| Co-Founder & CEO | [[Nicolò Magnante]] | HEC Paris (top European business school); BCG / Bain & Company (strategy consulting, Milan); CEO Right Hand at OVRSEA (Paris); Co-Founder & CEO of Bluco (HR/blue-collar staffing platform, McDonald's / Burger King / Volkswagen as clients); studied in Michigan; launched a startup as EIR and scaled to $1M ARR in year one |
| Co-Founder & CTO | Arseniy Shishaev | Russian-born; started coding at 12; national coding olympiad winner; 42 Paris (elite French coding school, 2019–2022); Lomonosov Moscow State University (Bachelor's with Honours); Software Engineer at **Datadog** (Paris → SF, Nov 2021 – Dec 2024, ~3.5 yrs, built core architecture); Co-Founder & CTO of Bluco; LinkedIn: https://linkedin.com/in/arseniy-shishaev |

> Per Harmonic: Superlog headcount 3, San Francisco, CA. Founders Nicolò Magnante (CEO) and Arseniy Shishaev (CTO) both listed. Plan: hire two world-class engineers (one infra, one ML — both known personally to the founders).

---

## Business Description

- **Problem:** Observability tooling was built for human engineers reading dashboards. Today AI agents write and review code, so the data format, storage, and consumption model of telemetry needs to be rebuilt from scratch for agents to consume.
- **Product:** AI-native observability platform.
  - **One-prompt install:** paste a prompt into Claude Code, Cursor, or Codex; the agent auto-instruments traces, logs, and metrics for all future features.
  - **No integration with Datadog or any existing vendor** — redirects existing telemetry to Superlog on install. Arseniy's prior Datadog architecture knowledge enables migration in ~20 minutes vs. months.
  - **Telemetry stored on ClickHouse** (cheaper than Datadog); accessible via platform or Slack shortcuts.
  - **Output is a PR, not an alert:** Superlog identifies the one meaningful alert out of many and auto-generates a fix. 80%+ of PRs merged as-is; remainder tweaked via Greptile, Copilot, etc., then pushed.
- **North Star:** fully self-healing product — Superlog chooses what to merge autonomously.
- **Wedge / entry point:** Startups (fastest AI adopters; Datadog no longer keeping up). Grow with them into mid-market, then upsell enterprise.

---

## Market & Competition

- **Primary competitor:** Datadog — Superlog's positioning is initially complementary (Datadog is a known LP-adjacent vendor for Fin's LPs, per Nicolò), but the long-term motion is full rip-and-replace.
- **Other observability incumbents:** New Relic, Splunk, Honeycomb (all built for human dashboard consumption).
- **Differentiation:** Data model designed for agent consumption, not human dashboards; output is merge-ready PRs vs. alerts; one-prompt install via existing coding agents.

---

## GTM & Business Model

- **Buyer persona:** Engineering leaders at AI-native startups (350+ orgs onboarded in last month as of 2026-06-11).
- **Install motion:** One-prompt install via Claude Code / Cursor / Codex. No vendor procurement cycle needed.
- **Pricing model:** ClickHouse-backed → cost structure materially below Datadog (specific pricing TBD).
- **Growth path:** Startups → grow-with → mid-market → enterprise upsell.

---

## Traction

- **350+ organizations onboarded in the last month** (as of 2026-06-11)
- **~20 PRs auto-generated per org per week** (as of 2026-06-11)
- **80%+ PR merge-as-is rate** (as of 2026-06-11); remainder tweaked via Greptile / Copilot then pushed
- **Headcount (per Harmonic, as of 2026-06-11):** 3 (founders + small team)

---

## Financing

| Date | Round | Amount | Investors |
|---|---|---|---|
| 2026-04-02 (per Harmonic) | Pre-Seed | $500K | Y Combinator |
| In progress (June 2026) | YC Demo Day | $2M cash + $2M OpenAI tokens + ~$4–4.5M YC money | Round started Monday 2026-06-08; largely committed; key angels = ex-Datadog executives and SF operators; 2 fund conversations potentially at a higher total raise |

- **Hard deadline:** round may close before Wed/Thu of week of 2026-06-15.
- **Use of funds:** hire two world-class engineers (one infra, one ML, both known personally to founders).
- **Valuation:** Harmonic estimate ~$2M post on prior $500K pre-seed (typical 25% dilution).

---

## Deal Team Notes

- 2026-06-11 — First Granola-captured intro call. Derek Wu and Jake Fuchs on Fin side; Nicolò Magnante (CEO) on Superlog side. Granola id `260c84a2-db8c-4025-a78d-ee94df249ce1`. See [[Superlog - 2026-06-11 Summary]].
- **Datadog/LP tension:** Datadog is a known LP-adjacent vendor for Fin's LPs. Nicolò framed Superlog as initial complement but full rip-and-replace over time — worth surfacing in IC.
- **Founder narrative gap:** Previous company "Bluecol" per Granola transcript; Harmonic confirms spelling "Bluco". Bluco shut down after a third co-founder's family (Mexican investors) sued post-rejection of buyout offer — Arseniy's visa was at risk, forcing clean exit. Worth diligencing.
- **Time-sensitive:** round may close before Wed/Thu of the following week; Fin team to sync internally Wednesday 2026-06-17 and respond with feedback by Wed/Thu (per call commitment).

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

- [ ] Receive deck from Nicolò
- [ ] Fin internal sync Wednesday 2026-06-17
- [ ] Respond with feedback by Wed/Thu 2026-06-17/18 (per commitment on call)
- [ ] Diligence Bluco shutdown circumstances (lawsuit from third co-founder's family)
- [ ] Confirm whether $2M cash round is fully soft-committed or still has allocation
- [ ] Reference the ex-Datadog executive angels
