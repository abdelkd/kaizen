---
Date: <% tp.date.now() %>
Tags: daily-note
---

# 📅 Daily Note - <% tp.date.now() %>

---

## ✨ Today's Focus / Top 3 Priorities

1.
2.
3.

---

## ✅ Tasks Due Today

```dataviewjs
dv.taskList(
  dv.pages("#Task")
  .where(p => p.file.tasks.length > 0)
  .flatMap(p => p.file.tasks)
  .where(t => !t.completed && t.due && t.due.ts === dv.date("{{date:YYYY-MM-DD}}").ts)
  .sort(t => t.priority === "high" ? 0 : (t.priority === "medium" ? 1 : (t.priority === "low" ? 2 : 3))), // Sort by priority
  false // Group by file path (optional, set true if preferred)
)