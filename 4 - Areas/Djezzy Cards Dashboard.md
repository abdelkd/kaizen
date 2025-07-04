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
| Wednesday | 07:47 AM | 25            | 0799905057   |
| Sunday    | 07:49 PM | 41            | 0799922427   |
| Wednesday | 09:25 AM | 12            | 0772737646   |
| Thursday  | 09:33 AM | 07            | 0781321859   |
| Friday    | 09:52 AM | 80            | 0775596228   |
| Saturday  | 07:14 AM | 66            | 0781401357   |
| Sunday    | 07:09 AM | 60            | 0775246770   |
| Friday    | 09:26 PM | 09            | 0775418744   |
| Thursday  | 09:36 PM | 71            | 0773485175   |
| Tuesday   | 08:04 AM | 59            | 0781056088   |
| Monday    | 08:03 AM | 86            | 0776602021   |


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
