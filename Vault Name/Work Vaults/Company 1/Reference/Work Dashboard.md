---
Parent: Work
Company: Work
Project: Dashboard
tags:
  - Work
  - dashboard
cssclasses:
  - Work
---
<div class="work-banner"></div>

I like the idea of scrap notes to quickly write something down. I also like buttons to quickly link to common projects. 
`BUTTON[Scrap]` `BUTTON[Project_1]` 

> [! ] 
> # Projects 
> These are the titles of all active projects
![[All Work Projects.base]]

---
>[! ] 
># Reminders 
> These are reminders that aren't necessarily tied to a project
>  ![[All Work Reminders.base]]
 
---
> [! ]
> # General Knowledge
> Any general company knowledge
![[General Knowledge.base]]

---
# Systems Knowledge
> [! ] 
> ## System 1
> All general system knowledge broken down by each system
> ![[System 1.base]]

---
# Other Brands
 > [! ]
 > ## Brand 1
 > If a company has other brands
![[Brand 1.base]]




---

```meta-bind-button
style: primary
label: Scrap
icon: "document"
id: Scrap
hidden: true
actions:
- type: open
  link: Work Vaults/Company 1/Reference/Scrap
  newTab: true
```

```meta-bind-button
style: primary
label: Project 1
icon: "document"
id: Project_1
hidden: true
actions:
- type: open
  link: Work Vaults/Company 1/Department 1/Projects/Project 1
  newTab: true
```
