---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/assassination/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"","Status":"Work in Progress","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Murder and Assassination Knowledge]]"]}}
---

# [[Beyond the Veil/Veil Content/Masteries/Assassination\|Assassination]] Discipline Mastery

| Mastery Level | Effect                                                                                                                                                                                                                                 |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | When you take a turn in a round, all creatures that have not taken a their turn yet in the same round, are [[Beyond the Veil/Veil Content/Conditions/Exposed\|Exposed]] to you.<br><br>Once per round, when you bring a creature to 0 [[Beyond the Veil/Veil Glossary/Vitality\|Vitality]] or kill a target you gain [[Beyond the Veil/Veil Content/Conditions/Haste\|Haste]]. |
| Veteran       |                                                                                                                                                                                                                                        |
| Master        |                                                                                                                                                                                                                                        |


```base
filters:
  and:
    - MasterySkills.contains(link("Assassination"))
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

```
