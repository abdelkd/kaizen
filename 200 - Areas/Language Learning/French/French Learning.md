---
Area: French Learning
Tags: area-dashboard
Created: 2025-04-09
---

# Area: French Learning

---

## 🎯 Long-Term Goals / Vision

*   Goal 1: Achieve B2 level in french
*   Goal 2: Become able to watch and read french content

---

## ✅ Routine Tasks & Checklists

*   [ ] Task/Checklist Item (e.g., Weekly framework review) #Task 🔁 every week [[French Learning Dashboard]]
*   [ ] Another routine task #Task #French Learning 🔁 every month on the 1st [[French Learning Dashboard]]

---

## 🔗 Key Links

*   **Core Resources:**
    *   [[Link to a foundational concept in 30 - Resources]]
    *   [[Link to another key resource note]]
*   **Related Projects:**
    *   [[Link to an active project in 10 - Projects related to this area]]
    *   [[Link to a completed project in 40 - Archives]]
*   **Sub-Areas (if any):**
    *   [[Link to a sub-area dashboard, e.g., 20 - Areas/Web Development/Frontend/Frontend Dashboard.md]]

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