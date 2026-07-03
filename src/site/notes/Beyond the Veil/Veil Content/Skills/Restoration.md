---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/skills/restoration/","dg-note-properties":{"base":"[[Skills.base]]","Description":"Treat Wounds, Treat Curses, Treat Afflictions, Autopsy, First Aid, Prevention Medicine, Making Medicine or Potions. You keep people standing. Stabilize the fallen, treat wounds and afflictions, counter toxins and maladies, and prepare field remedies that stave off worse harm."}}
---


```base
filters:
  and:
    - base == link("Passives Database.base")
    - MasterySkills.contains(link("Restoration"))
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
