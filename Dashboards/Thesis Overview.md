---
type: dashboard
tags:
  - dashboard
---

# Thesis Overview

## Active Theses

```dataview
TABLE sector as "Sector", status as "Status", last_updated as "Last Updated"
FROM "Theses"
SORT last_updated DESC
```

## Companies by Sector

```dataview
TABLE length(rows) as "Count", rows.file.link as "Companies"
FROM "Companies"
WHERE sector != null
GROUP BY sector
SORT length(rows) DESC
```

## Untagged Companies (needs sector)

```dataview
LIST
FROM "Companies"
WHERE sector = null OR sector = ""
```
