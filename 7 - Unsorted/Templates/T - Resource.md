---
tags: type/source, .
author: [Author Name]
link: [URL if applicable]
created: <% tp.file.creation_date("YYYY-MM-DD") %>
status: reading # or to-read, finished
rating: 
---
# Source: <% tp.file.title.split(' - ')[2] %>

## Summary / Key Takeaways



## Notes & Highlights

*   

## References

*   MOC Software Design Principles

## Generated Zettel

```dataview
LIST FROM "40_ZETTELKASTEN"
WHERE contains(Context/Source, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name ASC