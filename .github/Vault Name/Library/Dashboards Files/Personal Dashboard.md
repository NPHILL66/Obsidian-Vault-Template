---
tags:
  - Personal
Parent: Personal
Project: Dashboard
dashboard: "true"
cssclasses:
  - Personal
---

<div class="personal-banner"></div>



Use Meta Bind buttons to link to other dashboards, or quick reference for commonly used notes. 
`BUTTON[Purpose]`  `BUTTON[Scrap]`  `BUTTON[Work_Dashboard]` 


> [! ]
> # Current Tasks
> This view pulls in personal task from my tasks folder. Then filter to pull in daily, weekly, or monthly tasks.
> ![[Tasks - All Personal.base]]

---
Project tasks and project references are linked together by the same parent and project properties.
 > [! ]
> # Project Task Sub-Dashboards
> These are notes have embed bases of **TASKS** for each subject/note. The notes on the sub page bases populate in the Current Tasks view.
> ![[All Project Tasks.base]]

> [! ]
> # Project Reference Sub-Dashboards
> These are notes have embed bases of **REFERENCE NOTES** for each subject/note.
>  ![[All Projects.base]]

---

> [! ]
> # Platform Sub-Dashboards
> These are notes with embed bases of each platform I use in work and personally.
> ![[All Platforms.base]]


___

```meta-bind-button
style: primary
label: Scrap
icon: "document"
id: Scrap
hidden: true
actions:
- type: open
  link: Library/Templates/Scrap
  newTab: true
```

```meta-bind-button
style: primary
label: Personal Development
icon: "target"
id: Purpose
hidden: true
actions:
- type: open
  link: Project Reference/_Homepages/Personal Development
  newTab: true
```

```meta-bind-button
style: primary
label: Work Dashboard
icon: "briefcase"
id: Work_Dashboard
hidden: true
actions:
- type: open
  link: Library/Templates/Scrap
  newTab: true
```