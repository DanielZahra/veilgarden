---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/skills/perception/","dg-note-properties":{"base":"[[Skills.base]]","Description":"Sight, Smell, Hearing, Search, Spotting Traps, Tracking Creatures. You notice what others miss. Spot ambushes and traps, sift scenes for clues, track fresh signs, and pick out fleeting tells in the chaos."}}
---


```base
filters:
  and:
    - base == link("Passives Database.base")
    - MasterySkills.contains(link("Perception"))
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
