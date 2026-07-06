---
Parent: Work
Project: Reference
---
```base
properties:
  file.ctime:
    displayName: Date Created
  note.Address:
    displayName: Notes
views:
  - type: cards
    name: Table
    filters:
      and:
        - file.inFolder("Platforms")
    order:
      - file.name
    sort:
      - property: Status
        direction: ASC
    cardSize: 240
  - type: table
    name: View
    filters:
      and:
        - file.folder == "Waddle"
    order:
      - Project
      - Status
      - file.name
      - Due Date
      - Address
    sort:
      - property: Address
        direction: ASC
      - property: Project
        direction: ASC
      - property: file.name
        direction: ASC
    columnSize:
      note.Project: 126
      note.Status: 96
      file.name: 434

```
