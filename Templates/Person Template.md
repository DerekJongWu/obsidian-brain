---
type: person
role: 
company: 
linkedin: 
email: 
location: 
relationship: 
last_contact: 
created: <% tp.date.now("YYYY-MM-DD") %>
tags:
  - person
---

# <% tp.file.title %>

> **Role:** | **Company:** [[]] | **Location:**

---

## Background

- 

---

## Relationship Notes

- **How we know them:**
- **Warm paths:**
- **Last interaction:**

---

## Mentions Across Vault

```dataview
LIST
FROM [[]]
WHERE file.name != this.file.name
SORT file.mtime DESC
```
