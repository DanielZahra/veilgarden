---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/skills/smarts/","dg-note-properties":{"base":"[[Skills.base]]","Description":"Deductive assessment, Logic and reasoning challenges, cryptography, mathematics, linguistics, strategy. You win with knowledge and synthesis. Recall lore across disciplines, crack codes and puzzles, test hypotheses, and turn information into plans that give your team the edge."}}
---


```base
filters:
  and:
    - base == link("Passives Database.base")
    - MasterySkills.contains(link("Smarts"))
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
