# Obsidian Vault Schema Reference

Use this document as context when prompting an AI to create, edit, or query notes in this vault. It describes every note type, its YAML frontmatter properties, body structure, linking conventions, and the folder it belongs in.

---

## Vault Overview

This is a venture capital deal-flow vault for **Fin Capital**. It tracks companies through the investment pipeline, the people associated with them, investment theses, meeting notes, transcripts, and reference calls. Everything is connected via `[[wikilinks]]` and queryable through Dataview.

**Plugins:** Dataview, Templater, Obsidian Git

---

## Folder Structure

| Folder | Contents |
|---|---|
| `Companies/` | One note per company — deal profile, diligence, status |
| `People/` | One note per person — founders, operators, LPs, references |
| `Theses/` | Investment theses, market maps, sector deep-dives |
| `Meetings/` | Meeting summaries with metadata, takeaways, and action items |
| `Transcripts/` | Raw meeting transcripts (linked from Meeting notes) |
| `References/` | Reference/diligence calls — linked to both company and person |
| `Dashboards/` | Dataview-powered views (Pipeline Dashboard, Thesis Overview) |
| `Templates/` | Templater templates for each note type |
| `Misc/` | Scratch notes, ideas, random capture |

---

## Naming Conventions

| Type | Pattern | Example |
|---|---|---|
| Company | `{Company Name}` | `OpenLayer` |
| Person | `{First Last}` | `Gabriel Bayomi` |
| Meeting | `{Company} - {YYYY-MM-DD} Summary` | `OpenLayer- 2026-04-10 Summary` |
| Transcript | `{Company} - {YYYY-MM-DD} Transcript` | `OpenLayer - 2026-04-10 Transcript` |
| Reference | `{Referee Org} - {Company} Reference Call` | `S&P Global - Nametag Reference Call` |
| Thesis | `{Thesis Name}` | `NHI Identity` |

---

## Note Types & Schemas

### 1. Company (`type: company`)

**Folder:** `Companies/`

**Frontmatter:**

```yaml
type: company
sector:             # e.g. "cybersecurity", "AI governance"
sub_sector:         # more specific category
stage:              # e.g. "Series A", "Series B", "Seed"
status:             # one of: "sourcing", "active-diligence", "portfolio", "passed", "monitoring"
owner:              # Fin team member responsible
founded:            # year
hq:                 # city/region
website:            # URL
linkedin:           # URL
crunchbase:         # URL
pitchbook:          # URL
deck_link:          # URL to pitch deck
data_room:          # URL to data room
lighthouse_link:    # URL to internal Lighthouse app
last_touch:         # YYYY-MM-DD — date of most recent interaction
created:            # YYYY-MM-DD
tags:
  - company
```

**Body sections (in order):**

1. **One-Liner** — callout block with brief company description
2. **Thesis Fit** — why we like it, link to relevant `[[Thesis]]`, Fin sub-sector
3. **Team** — table with Role / `[[Person]]` link / Background
4. **Business Description** — Problem, Product, Wedge/entry point
5. **Market & Competition** — Market size, key competitors (`[[wikilinks]]`), differentiation
6. **GTM & Business Model** — Buyer persona, pricing model, ACV, contract structure
7. **Traction** — ARR, growth, key customers (`[[wikilinks]]`), retention/NRR
8. **Financing** — table of rounds (Date/Round/Amount/Investors), current round details
9. **Deal Team Notes** — free-form bullets
10. **Meetings & References** — Dataview query pulling all backlinked meeting and reference notes
11. **Next Steps** — task checkboxes

---

### 2. Person (`type: person`)

**Folder:** `People/`

**Frontmatter:**

```yaml
type: person
role:               # e.g. "Founder & CEO", "VP Engineering"
company:            # company name (plain text, not a wikilink in frontmatter)
linkedin:           # URL
email:              # email address
location:           # city/region
relationship:       # e.g. "warm intro via X", "met at conference"
last_contact:       # YYYY-MM-DD
created:            # YYYY-MM-DD
tags:
  - person
```

**Body sections:**

1. **Header line** — Role | Company (`[[wikilink]]`) | Location
2. **Background** — bullets on professional history
3. **Relationship Notes** — how we know them, warm paths, last interaction
4. **Mentions Across Vault** — Dataview query showing all backlinks

---

### 3. Meeting (`type: meeting`)

**Folder:** `Meetings/`

**Frontmatter:**

```yaml
type: meeting
date:               # YYYY-MM-DD
company:            # company name (plain text in frontmatter)
attendees:          # comma-separated names (plain text in frontmatter)
meeting_type:       # e.g. "intro", "deep-dive", "follow-up", "demo"
transcript:         # wikilink string to transcript note, e.g. "[[Company - YYYY-MM-DD Transcript]]"
created:            # YYYY-MM-DD
tags:
  - meeting
```

**Body sections:**

1. **Header line** — Company (`[[wikilink]]`) | Date | Type
2. **Attendees** — `[[wikilinks]]` to person notes
3. **Transcript** — `[[wikilink]]` to transcript note
4. **Summary content** — structured under headings like Company Overview, Product & Technical Approach, Go-to-Market, Pricing & Competition, Financing & Growth, Next Steps

---

### 4. Transcript (`type: transcript`)

**Folder:** `Transcripts/`

**Frontmatter:**

```yaml
type: transcript
date:               # YYYY-MM-DD
company:            # company name (plain text)
summary_note:       # wikilink to the corresponding meeting summary
source:             # e.g. "Granola", "Zoom", "Manual"
created:            # YYYY-MM-DD
tags:
  - transcript
```

**Body sections:**

1. **Header line** — Summary (`[[wikilink]]`) | Source
2. **Transcript** — raw transcript text, may include `[[wikilinks]]` to people mentioned

---

### 5. Reference Call (`type: reference`)

**Folder:** `References/`

**Frontmatter:**

```yaml
type: reference
date:               # YYYY-MM-DD
company:            # company being referenced (plain text)
reference_contact:  # name of the reference (plain text)
contact_role:       # their role/title
introduced_by:      # who made the intro
sentiment:          # "Positive", "Mixed", or "Negative"
created:            # YYYY-MM-DD
tags:
  - reference
```

**Body sections:**

1. **Header line** — Company (`[[wikilink]]`) | Contact (`[[wikilink]]`) | Date
2. **Contact role / relationship to company**
3. **Sentiment** — Positive / Mixed / Negative
4. **Key Signals** — Product, Team, Support/service, Competitive alternatives (`[[wikilinks]]`)
5. **Verbatim Highlights** — direct quotes in blockquotes
6. **Takeaways for Diligence**

---

### 6. Thesis (`type: thesis`)

**Folder:** `Theses/`

**Frontmatter:**

```yaml
type: thesis
sector:             # sector this thesis covers
status:             # e.g. "active", "draft", "archived"
last_updated:       # YYYY-MM-DD
created:            # YYYY-MM-DD
tags:
  - thesis
```

**Body sections:**

1. **Core Conviction** — 2-3 sentence summary of the structural shift and opportunity
2. **Market Structure** — Buyer, Budget, Buying motion, Market size
3. **What Great Looks Like** — ideal company attributes (Product, Team, GTM, Traction benchmarks)
4. **Landscape** — Dataview query pulling companies whose `sector` matches this thesis
5. **Key Questions / Risks** — numbered list
6. **Related Theses** — `[[wikilinks]]`
7. **Reading & Sources**

---

### 7. Dashboard (`type: dashboard`)

**Folder:** `Dashboards/`

**Frontmatter:**

```yaml
type: dashboard
tags:
  - dashboard
```

Dashboards are pure Dataview query collections. Two exist:

- **Pipeline Dashboard** — tables for Active Diligence, Sourcing, Portfolio, Passed companies, Recent Meetings, Recent Reference Calls
- **Thesis Overview** — all theses, companies grouped by sector, untagged companies

---

## Status Tags & Values

The `status` field on Company notes drives the pipeline. Valid values:

| Status | Meaning |
|---|---|
| `sourcing` | Identified, not yet met or early conversations |
| `active-diligence` | In active evaluation |
| `portfolio` | Invested |
| `passed` | Decided not to invest |
| `monitoring` | Tracking but not actively pursuing |

Additional hashtags used in note bodies: `#active-diligence`, `#passed`, `#portfolio`, `#monitoring`, `#sourcing`

---

## Linking Conventions

- **Company ↔ Person:** Company team table links to `[[Person]]` notes; Person notes link back to `[[Company]]` in body and frontmatter.
- **Company ↔ Meeting:** Meeting frontmatter has `company` field; meeting body links to `[[Company]]`. Company note has a Dataview query pulling all backlinked meetings.
- **Meeting ↔ Transcript:** Meeting frontmatter `transcript` field contains a `[[wikilink]]`; Transcript frontmatter `summary_note` links back.
- **Company ↔ Reference:** Reference frontmatter has `company` field; body links to `[[Company]]`.
- **Company ↔ Thesis:** Company frontmatter `sector` is matched by Thesis Dataview queries; Company body links to relevant `[[Thesis]]` in the Thesis Fit section.
- **Person ↔ Meeting:** Meeting `attendees` field lists names; body uses `[[Person]]` wikilinks.

---

## Dataview Query Patterns

Common queries used in this vault:

```dataview
// Companies by status
TABLE sector, stage, owner, last_touch
FROM "Companies"
WHERE status = "active-diligence"
SORT last_touch DESC

// All backlinked notes for a company/person
TABLE date, type
FROM [[]]
WHERE type = "meeting" OR type = "reference"
SORT date DESC

// Companies grouped by sector
TABLE length(rows) as "Count", rows.file.link as "Companies"
FROM "Companies"
WHERE sector != null
GROUP BY sector

// Landscape query inside a Thesis note
TABLE stage, status, owner
FROM "Companies"
WHERE contains(sector, this.sector)
SORT status ASC
```

---

## Instructions for AI Agents

When creating or editing notes in this vault:

1. **Always include YAML frontmatter** with the correct `type` and all relevant fields. Use `YYYY-MM-DD` for dates.
2. **Use `[[wikilinks]]`** for all cross-references in the note body — companies, people, theses. Keep frontmatter values as plain text (not wikilinks) unless the template shows otherwise (e.g., `transcript` field uses a wikilink string).
3. **Follow the naming conventions** exactly — this is how links resolve.
4. **Place notes in the correct folder** based on their type.
5. **Populate the `status` field** on company notes with one of the five valid values.
6. **When creating meeting summaries**, structure content under clear headings and always link to the transcript and attendee person notes.
7. **When updating a company**, also update `last_touch` to today's date if there was a new interaction.
