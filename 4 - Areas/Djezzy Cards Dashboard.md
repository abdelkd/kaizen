---
Area: 
tags:
  - area-dashboard
Created: 2025-04-09
---

# Area: Djezzy Cards Dashboard

---

## 🎯 Long-Term Goals / Vision

EMPTY

---


---

## 🔗 Key Links

*   **Table:**

| Weekday   | Time     | Last 2 digits | Phone Number |
| --------- | -------- | ------------- | ------------ |
| Saturday  | 01:44 AM | 25            | 0799905057   |
| Sunday    | 07:42 AM | 41            | 0799922427   |
| Monday    | 05:30 AM | 12            | 0772737646   |
| Monday    | 11:18 AM | 07            | 0781321859   |
| Tuesday   | 10:00 PM | 80            | 0775596228   |
| Wednesday | 09:33 PM | 66            | 0781401357   |
| Thursday  | 09:30 PM | 60            | 0775246770   |
| Thursday  | 11:18 AM | 71            | 0773485175   |
| Friday    | 09:26 PM | 09            | 0775418744   |
| Saturday  | 02:02 PM | 59            | 0781056088   |
| Friday    | 01:05 AM | 86            | 0776602021   |


## 📝 Notes & Standards

*   Note summarizing current focus or standards for this area.

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