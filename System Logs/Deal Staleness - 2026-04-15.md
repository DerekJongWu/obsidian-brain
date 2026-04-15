---
type: sync-log
date: 2026-04-15
deals_scanned: 23
deals_with_outlook_signal: 23
todos_extracted: 6
---

# Deal Staleness Report — 2026-04-15

## Needs Attention

Four deals in **Initial Meetings** (7-day cadence) have exceeded the staleness threshold using the best of manifest `last_touch_at` and the new Outlook signal:

- [[Zenyard AI]] — Initial Meetings — **28 days** since last touch (source: email, 2026-03-18) — _next steps: none recorded_
- [[Tonic Security]] — Initial Meetings — **15 days** since last touch (source: email, 2026-03-31) — _next steps: Discuss with the team; follow up for lead convos_
- [[Discern Security]] — Initial Meetings — **14 days** since last touch (source: email, 2026-04-01) — _next steps: Currently raising a Series A_
- [[Backline AI]] — Initial Meetings — **13 days** since last touch (source: email, 2026-04-02) — _next steps: Meeting scheduled for two weeks (Apr 20 on calendar)_

## Recently Touched

All other 19 deals have been touched within the last 7 days:

- [[Orchid]] — 2026-04-15 — email (Roy sent inline diligence answers today)
- [[DBGorilla]] — 2026-04-15 — attio (Outlook email 2026-04-10; intro call Apr 16)
- [[Freeflow]] — 2026-04-15 — attio (Outlook signal stale from Dec 2025)
- [[Opti]] — 2026-04-15 — attio (Outlook email 2026-04-10)
- [[Arcade]] — 2026-04-14 — email (Alex sent confirmatory answers)
- [[Echelon AI]] — 2026-04-14 — email (Fan made US Bank intro)
- [[Engramme]] — 2026-04-14 — email (Fan follow-up on round)
- [[LotLine]] — 2026-04-14 — calendar (Teams meeting took place yesterday)
- [[Overwatch]] — 2026-04-14 — manual (Outlook email 2026-04-02)
- [[Aembit]] — 2026-04-13 — email (Fan follow-up on strategic round)
- [[Axia Security]] — 2026-04-13 — email (Asaf post-meeting follow-up)
- [[Embed Security]] — 2026-04-13 — attio (Outlook email 2026-04-07)
- [[Entro Security]] — 2026-04-13 — email (Fan asked for data room)
- [[IndyKite]] — 2026-04-13 — attio (Outlook calendar 2026-04-09 with Lasse)
- [[Nametag]] — 2026-04-13 — attio (Outlook calendar stale from Feb)
- [[Relvino]] — 2026-04-13 — attio (Outlook calendar 2026-04-07)
- [[Unstructured]] — 2026-04-13 — attio (Outlook email 2026-03-19)
- [[VanishID]] — 2026-04-13 — email (Matt sent updated slides; update for Logan expected this week)
- [[vCluster]] — 2026-04-13 — attio (Outlook email 2026-04-06 Fan follow-up)

## No Outlook Signal

_All 23 active deals returned at least one Outlook email or calendar signal — no domains appear broken._

## Sync Summary

- Deals in manifest: 23
- Outlook signals found: 23 (email: 20 had email_touch_at, calendar: 20 had calendar_touch_at)
  - `outlook_touch_source` = email: 19 deals
  - `outlook_touch_source` = calendar: 4 deals (IndyKite, LotLine, Nametag, Relvino)
- No Outlook signal: 0
- To-do items extracted: 6 (4 deal-linked + 2 non-deal LP items)
- Errors: 0

## To-Do Highlights

Extracted action items written to `Automations/outlook-todos.json` (for the deal flow app inbox):

- **Arcade** — Circle back to Alex with partner-review thoughts on confirmatory answers (Daria committed end of week)
- **DBGorilla** — Prep for intro call Apr 16 (warm intro from Staircase Ventures, Series A)
- **LotLine** — Send post-meeting follow-up notes to Sean after Apr 14 Teams call
- **Orchid** — Complete follow-up diligence on Roy's ARR miss / RTX reconciliation / concentration / GSI answers
- **Non-deal** — Review Met.IO 2026 Requirements before MetLife call today (4pm ET)
- **Non-deal** — Prep for Fubon LP in-person meeting Apr 20 at NYC office

Items already tracked in `active_todos` or `next_steps` (e.g., Axia follow-up, VanishID data room review, Engramme round tracking, Echelon Logan trial) were suppressed to avoid duplication.
