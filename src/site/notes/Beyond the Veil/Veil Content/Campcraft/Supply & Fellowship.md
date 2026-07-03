---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/campcraft/supply-and-fellowship/","dg-note-properties":{}}
---


```base
filters:
  and:
    - base == link("Campcraft Passive Database.base")
    - Dossier.contains(link("Supply & Fellowship"))
properties:
  file.name:
    displayName: Name
views:
  - type: table
    name: Table
    order:
      - file.name
      - rank
      - Dossier
      - Wealth Cost
      - Requirements
      - Traits
      - Text
    sort:
      - property: sortOrderByRank
        direction: ASC
    columnSize:
      file.name: 260
      note.Requirements: 228
      note.Text: 859
    rowHeight: medium

```



```base
filters:
  and:
    - base == link("Gear.base")
    - Dossier.contains(link("Supply & Fellowship"))
properties:
  file.name:
    displayName: Name
views:
  - type: table
    name: Table
    order:
      - file.name
      - rank
      - Traits
      - Dossier
      - Multi-Purchase
      - Stack
      - Wealth Cost
      - Actions
    sort:
      - property: sortOrderByRank
        direction: ASC
    columnSize:
      note.Traits: 362
      note.Dossier: 238

```
