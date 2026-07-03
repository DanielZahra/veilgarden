---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/skills/tinkering/","dg-note-properties":{"base":"[[Skills.base]]","Description":"Open Physical Locks, Disable Physical Traps, Operate Machinery, Operate Vehicles, Operate Strange Devices, Forgery, Create Things, customize gear. You converse with mechanisms. Pick and bypass locks, disable or rig devices and traps, repair or modify gear, and coax balky vehicles or constructs into working."}}
---


```base
filters:
  and:
    - base == link("Passives Database.base")
    - MasterySkills.contains(link("Tinkering"))
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
