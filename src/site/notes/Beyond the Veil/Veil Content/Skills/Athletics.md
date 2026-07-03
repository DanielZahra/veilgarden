---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/skills/athletics/","dg-note-properties":{"base":"[[Skills.base]]","Description":"You turn muscle and grit into motion. Force open paths, climb and leap across obstacles, shove and wrestle foes, and keep going under sustained strain. Athletics governs, Stamina, Strength and Endurance."}}
---


```base
filters:
  and:
    - base == link("Passives Database.base")
    - MasterySkills.contains(link("Athletics"))
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
