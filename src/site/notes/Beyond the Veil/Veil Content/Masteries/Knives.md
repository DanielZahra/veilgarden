---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/knives/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"","Status":"Mostly Done","Mastery Type":["[[Equipment Mastery]]"],"Knowledge Gained":"Melee Weapon Knowledge or Weapon Family Knowledge (Knives)"}}
---


# [[Beyond the Veil/Veil Content/Masteries/Knives\|Knives]] Equipment Mastery
| Mastery Level | Effect                                                                                                                                       |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain the  [[Beyond the Veil/Veil Content/Abilities/Reactive Strike\|Reactive Strike]] Ability.  <br>  <br>You can choose 1 trait for this weapon family. Up to Adept.                            |
| Veteran       | You can choose 2 traits for this weapon family. Up to Veteran.  <br>  <br>You can choose a single Modification trait for this weapon family. |
| Master        | You can choose 3 traits for this weapon family. Up to Master.                                                                                |


```base
filters:
  and:
    - MasterySkills.contains(link("Knives"))
    - base == link("Abilities.base")
formulas:
  Untitled: ""
properties:
  formula.Untitled:
    displayName: sortOrderRank
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
      note.MasterySkills: 232
    rowHeight: medium

```



```base
filters:
  and:
    - file.hasLink("Bases/Weapon Families.base")
    - and:
        - Families.contains(link("Knives"))
views:
  - type: table
    name: Table
    order:
      - file.name
      - Families
      - Damage
      - Basic Traits
      - Adept Traits
      - Veteran Traits
      - Modification Trait
      - Master Traits
    columnSize:
      file.name: 122
      note.Families: 122
      note.Damage: 100
      note.Basic Traits: 225
      note.Adept Traits: 134
      note.Veteran Traits: 178
      note.Modification Trait: 236
      note.Master Traits: 168
    rowHeight: tall

```
