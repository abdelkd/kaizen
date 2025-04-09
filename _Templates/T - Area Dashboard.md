---
Area: <% tp.file.title %>
Tags: area-dashboard
Created: <% tp.date.now() %>
---

# Area: <% tp.file.title %>

---

## 🎯 Long-Term Goals / Vision

*   Goal 1: Describe a long-term objective for this area.
*   Goal 2: Another ongoing aim or standard to maintain.
*   ...

---

## ✅ Routine Tasks & Checklists

*   [ ] Task/Checklist Item (e.g., Weekly framework review) #Task #{{title}} 🔁 every week [[<% tp.file.title %> Dashboard]]
*   [ ] Another routine task #Task #<% tp.file.title %> 🔁 every month on the 1st [[<% tp.file.title %> Dashboard]]
*   ...

*(Note: Added [[{{title}} Dashboard]] link to tasks for easier Dataview finding in the query below)*

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