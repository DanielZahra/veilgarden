---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/skills/influence/","dg-note-properties":{"base":"[[Skills.base]]","Description":"Persuasion, diplomacy, debating, negotiation, coercing, deceit and bluffing. You’re good at influencing others, motive, persuasion or charm. Influence also gives you a semblance of leadership skills needed to tarry on in an adventure."}}
---


```base
filters:
  and:
    - base == link("Passives Database.base")
    - MasterySkills.contains(link("Influence"))
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
