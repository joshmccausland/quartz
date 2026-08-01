---
obsidianUIMode: preview
---

# The Ephemero Age (E.A.)

```dataview
TABLE Date AS "Year", event-description AS "Summary"
FROM #timeline
WHERE age = "E.A."
SORT Date ASC
```


# The Sadhana Age (S.A.)

```dataview
TABLE Date AS "Year", event-description AS "The Chronicle"
FROM #timeline
WHERE age = "S.A."
SORT Date ASC
```