# Fin Capital — Obsidian Vault

## Setup

1. Open this folder as a vault in Obsidian (`Open folder as vault`)
2. Install community plugins (Settings → Community Plugins → Turn off Restricted Mode):
   - **Dataview** — query your notes like a database
   - **Templater** — use the templates in `/Templates` when creating new notes
   - **Calendar** — daily notes integration (optional)
3. In Templater settings, set the template folder to `Templates`
4. Recommended: set Dataview to auto-refresh and enable inline queries

## Folder Structure

| Folder | What goes here |
|---|---|
| `Companies` | One note per company — deal profile, diligence, status |
| `People` | One note per person — founders, operators, LPs, references |
| `Theses` | Investment theses, market maps, sector deep-dives |
| `Meetings` | Meeting summaries with metadata, takeaways, and action items |
| `Transcripts` | Raw meeting transcripts (linked from Meeting notes) |
| `References` | Reference/diligence calls — linked to both company and person |
| `Dashboards` | Dataview-powered views across your vault |
| `Templates` | Note templates for each type |

## Conventions

- **Links over folders**: Use `[[Company Name]]` liberally. Don't stress about filing — links are how you navigate.
- **Tags for status**: `#active-diligence`, `#passed`, `#portfolio`, `#monitoring`, `#sourcing`
- **Properties (YAML frontmatter)**: Every note has structured metadata at the top for Dataview queries.
- **Daily notes** (optional): Use for quick capture, then refactor into proper notes.

## Naming Conventions

- Companies: `Nametag`
- People: `Aaron Painter`
- Meetings: `Nametag - 2026-04-10 Summary`
- Transcripts: `Nametag - 2026-04-10 Transcript`
- References: `S&P Global - Nametag Reference Call`
