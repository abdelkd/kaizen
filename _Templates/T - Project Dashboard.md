---
Project: <% tp.file.title %>
Status: Active | Planning | On Hold | Completed | Archived
Deadline: <%* tR += tp.date.now("YYYY-MM-DD", "P3M") %>
Tags: project-dashboard
Created: <% tp.date.now() %>
---

# Project: <% tp.file.title %>

**Status:** <% tp.frontmatter.Status %>
**Deadline:** <% tp.frontmatter.Deadline %>

---

## 🎯 Goals

*   [ ] Goal 1: Define the primary objective here.
*   [ ] Goal 2: Add another key result or objective.
*   [ ] Goal 3: ...

---

## 🔗 Key Links & Resources

*   **Project Files:** [[<% tp.file.title %>/_Notes|Project Notes Folder]], [[<% tp.file.title %>/_Resources|Project Resources Folder]]
*   **Related Concepts:**
    *   [[Link to relevant concept in 30 - Resources]]
    *   [[Another relevant resource note]]
*   **External Links:**
    *   [Client Brief](URL)
    *   [Design Mockups](URL)

---

## 📝 Notes & Log

*   **<% tp.date.now() %>**: Initial project setup. Defined goals.
*   YYYY-MM-DD: Add updates, meeting notes, key decisions, or challenges here. Link to specific notes in `_Notes` if needed.

---

## ✅ Tasks

*   [ ] Task description ➕ {{date}} 📅 YYYY-MM-DD ⏫ High #Task [[<% tp.file.title %>]]
*   [ ] Another task for this project 📅 YYYY-MM-DD #Task [[<% tp.file.title %>]]
*   [ ] Research topic X 📅 YYYY-MM-DD 🔽 Low #Task [[<% tp.file.title %>]]

---

## 📊 Project Overview (Dataview Queries)

### Open Tasks for this Project

```dataviewjs
dv.taskList(dv.pages('#Task and [["' + dv.current().file.folder + '"]]')
    .where(t => !t.completed)
    .sort(t => t.due ? t.due.ts : 9999999999) // Sort by due date, tasks without due date last
    .map(t => {
        let taskText = t.text;
        // Attempt to add context like file link if not already present by default task rendering
        taskText += ` (from [[${t.file.name}]])`;
        return { ...t, text: taskText };
    })
    .values
)