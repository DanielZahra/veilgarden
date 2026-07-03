---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/conduit/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"You channel electricity through your body as if you were lightning itself.","Status":"Mostly Done","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Weather Knowledge]]"]}}
---

# [[Beyond the Veil/Veil Content/Masteries/Conduit\|Conduit]] Discipline Mastery

| Mastery Level | Effect |
| --- | --- |
| Adept | You learn the [[Beyond the Veil/Veil Content/Abilities/AC-DC\|AC-DC]] Ability |
| Veteran | Once per turn, you can switch between [[Beyond the Veil/Veil Content/Abilities/AC-DC\|AC-DC]]’s effects as a free action |
| Master | Improve [[Beyond the Veil/Veil Content/Abilities/AC-DC\|AC-DC]] TBD |

```base
filters:
  and:
    - MasterySkills.contains(link("Conduit"))
    - base == link("Abilities.base")
properties:
  file.name:
    displayName: Name
views:
  - type: table
    name: Table
    order:
      - file.name
      - rank
      - MasterySkills
      - Actions
      - defenses
      - Traits
      - RangeArea
    sort:
      - property: sortOrderByRank
        direction: ASC
    columnSize:
      file.name: 196
      note.MasterySkills: 367

```


## TODO

- Ability
    - Atttack that causes persisent elec dmg
    - Discharge? nova?
    - Teleportation
    - Repelling force, aoe push emanation 
    - Control Electricity
    - Ignore Resistance free action?
