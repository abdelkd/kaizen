---
Area: Djezzy_Cards_Dashboard
Tags: area-dashboard
Created: 2025-04-09
---

# Area: Djezzy_Cards_Dashboard

---

## 🎯 Long-Term Goals / Vision

*   Goal 1: Describe a long-term objective for this area.
*   Goal 2: Another ongoing aim or standard to maintain.
*   ...

---

## ✅ Routine Tasks & Checklists

*   [ ] Activate SIM #Task #{{title}} 🔁 every day [[Djezzy_Cards_Dashboard Dashboard]]
*   [ ] Another routine task #Task #

---

## 🔗 Key Links

*   **Core Resources:**
    *   [[Link to a foundational concept in 30 - Resources]]

---

## 📝 Notes & Standards

*   Note summarizing current focus or standards for this area.
*   Link to specific notes about maintaining standards [[e.g., Frontend Standards.md]]

---

## 📊 Area Overview (Dataview Queries)

### Tasks for this Area

```dataviewjs
const currentFolder = dv.current().file.folder;
const currentFileLink = dv.current().file.link;

dv.taskList(
  dv.pages(`"${currentFolder}" OR outgoing(${currentFileLink})`)
  .where(p => p.file.tasks.length > 0)
  .flatMap(p => p.file.tasks)
  .where(t => !t.completed && (t.path.includes(currentFolder + "/") || t.outlinks?.some(link => link.path === currentFileLink.path)))
  .sort(t => t.due ? t.due.ts : Infinity) // Sort by due date, tasks without due date last
  .limit(25) // Optional limit
);