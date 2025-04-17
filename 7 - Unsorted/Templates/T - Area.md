---
tags: type/area
aliases: [Abbreviation or related term]
created: <% tp.file.creation_date("YYYY-MM-DD") %>
---
# Area: <% tp.file.title.split(' - ')[1] %>

## Purpose / Focus



## Key Resources / MOCs (Maps of Content)



## Active Projects in this Area

```dataview
LIST FROM "10_PROJECTS"
WHERE contains(Area, this.file.link) AND contains(tags, "status/active")
SORT file.name ASC