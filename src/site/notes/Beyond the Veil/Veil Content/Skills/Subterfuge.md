---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/skills/subterfuge/","dg-note-properties":{"base":"[[Skills.base]]","Description":"Hiding Yourself, Hiding Objects, Hiding in Cover, Silent Movement, Darkness Training, Remove Evidence, Hide your Tracks, Sleight of Hand. You operate where eyes don’t. Vanish into shadows, trail or shake a tail, lift or plant small objects unseen, and infiltrate guarded spaces."}}
---


```base
filters:
  and:
    - base == link("Passives Database.base")
    - MasterySkills.contains(link("Subterfuge"))
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
