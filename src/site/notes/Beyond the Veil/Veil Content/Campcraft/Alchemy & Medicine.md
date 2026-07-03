---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/campcraft/alchemy-and-medicine/","dg-note-properties":{}}
---

### [[Beyond the Veil/Veil Content/Campcraft/Alchemy & Medicine\|Alchemy & Medicine]] Campcraft Upgrades

```base
filters:
  and:
    - base == link("Campcraft Passive Database.base")
    - Dossier.contains(link("Alchemy & Medicine"))
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
    sort:
      - property: sortOrderByRank
        direction: ASC
    columnSize:
      file.name: 260
      note.Requirements: 150
      note.Text: 859
    rowHeight: medium

```


### [[Beyond the Veil/Veil Content/Campcraft/Alchemy & Medicine\|Alchemy & Medicine]] Gear


```base
filters:
  and:
    - base == link("Gear.base")
    - Dossier.contains(link("Alchemy & Medicine"))
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

```
