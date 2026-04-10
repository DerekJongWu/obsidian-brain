---
type: dashboard
tags:
  - dashboard
---

# Pipeline Dashboard

## Active Diligence

```dataview
TABLE sector as "Sector", stage as "Stage", owner as "Owner", last_touch as "Last Touch"
FROM "Companies"
WHERE status = "active-diligence"
SORT last_touch DESC
```

## Sourcing

```dataview
TABLE sector as "Sector", stage as "Stage", owner as "Owner"
FROM "Companies"
WHERE status = "sourcing"
SORT created DESC
```

## Portfolio

```dataview
TABLE sector as "Sector", stage as "Stage"
FROM "Companies"
WHERE status = "portfolio"
SORT file.name ASC
```

## Passed

```dataview
TABLE sector as "Sector", stage as "Stage", owner as "Owner"
FROM "Companies"
WHERE status = "passed"
SORT last_touch DESC
LIMIT 20
```

## Recent Meetings

```dataview
TABLE company as "Company", meeting_type as "Type", date as "Date"
FROM "Meetings"
SORT date DESC
LIMIT 15
```

## Recent Reference Calls

```dataview
TABLE company as "Company", reference_contact as "Contact", sentiment as "Sentiment"
FROM "References"
SORT date DESC
LIMIT 10
```
