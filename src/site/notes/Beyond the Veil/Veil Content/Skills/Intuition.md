---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/skills/intuition/","dg-note-properties":{"base":"[[Skills.base]]","Description":"Sensing emotions, insight or magic. You trust the read beneath the surface. Sense motives and patterns, follow hunches, commune with the world’s currents (mundane or mystical), and choose the right moment to act."}}
---


```base
filters:
  and:
    - base == link("Passives Database.base")
    - MasterySkills.contains(link("Intuition"))
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
      note.MasterySkills: 488

```
