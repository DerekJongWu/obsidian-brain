---
type: sync-log
date: 2026-04-15
deals_scanned: 0
deals_with_outlook_signal: 0
todos_extracted: 0
---

# Deal Staleness Report — 2026-04-15

> [!ERROR] Sync aborted: deal manifest missing
> `Automations/deal-manifest.json` was not found in the repository. This file is expected to be exported daily by the local deal flow app and contains the list of active deals to scan. Without it, no Outlook queries could be issued and no staleness analysis could be performed.
>
> **To resolve:** run the local deal flow app's manifest export, confirm `Automations/deal-manifest.json` lands in this repo, and re-run the sync (or wait for tomorrow's 7:15 AM EDT scheduled run).

## Needs Attention

_No deals scanned — manifest missing._

## Recently Touched

_No deals scanned — manifest missing._

## No Outlook Signal

_No deals scanned — manifest missing._

## Sync Summary

- Deals in manifest: 0 (manifest file not present)
- Outlook signals found: 0 (email: 0, calendar: 0)
- No Outlook signal: 0
- To-do items extracted: 0
- Errors: 1
  - `Automations/deal-manifest.json` not found. Cannot query Outlook signals or extract to-dos without a deal list.
