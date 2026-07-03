---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/skills/agility/","dg-note-properties":{"base":"[[Skills.base]]","Description":"Breaking a Fall, Tumbling, Squeezing, Catch a Ledge, Cover Utilization and benefits, Walking on difficult ground, dancing, flexibility. You move with control and snap decisions. Keep balance, tumble through danger, slip tight spaces, recover from falls, and reposition under fire."}}
---


```base
filters:
  and:
    - base == link("Passives Database.base")
    - MasterySkills.contains(link("Agility"))
properties:
  file.name:
    displayName: Name
views:
  - type: table
    name: Table
    order:
      - file.name
      - MasterySkills
      - rank
      - Requirement
    sort:
      - property: sortOrderByRank
        direction: ASC
    columnSize:
      note.MasterySkills: 576

```
