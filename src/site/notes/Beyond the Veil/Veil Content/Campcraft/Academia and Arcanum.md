---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/campcraft/academia-and-arcanum/","dg-note-properties":{}}
---


```base
filters:
  and:
    - base == link("Campcraft Passive Database.base")
    - Dossier.contains(link("Academia and Arcanum"))
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
    - Dossier.contains(link("Academia and Arcanum"))
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



```base
filters:
  and:
    - note["base"] == link("Rituals.base")
properties:
  file.name:
    displayName: Name
  Primary DC:
    displayName: Primary DC
  Traits:
    displayName: Traits
  Unlocked:
    displayName: Unlocked
  Wealth Cost:
    displayName: Wealth Cost
  Cast Time:
    displayName: Cast Time
  Primary Skill:
    displayName: Primary Skill
  Kits or Tools:
    displayName: Kits or Tools
  Tier:
    displayName: Tier
  Casting Cost:
    displayName: Casting Cost
  Secondary Skill/s:
    displayName: Secondary Skill/s
views:
  - type: table
    name: Table View
    order:
      - file.name
      - Primary DC
      - Traits
      - Unlocked
      - Wealth Cost
      - Cast Time
      - Primary Skill
      - Kits or Tools
      - Tier
      - Casting Cost
      - Secondary Skill/s

```
