---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/throwing/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"","Status":"Mostly Done","Mastery Type":["[[Equipment Mastery]]"],"Knowledge Gained":"Range Weapon Knowledge or Weapon Family Knowledge (Throwing)"}}
---

# [[Beyond the Veil/Veil Content/Masteries/Throwing\|Throwing]] Equipment Mastery

| Mastery Level | Effect                                                                                                                                           |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Adept         | You can choose 1 trait for this weapon family. Up to [[Beyond the Veil/Veil Glossary/Adept\|Adept]].                                                                                  |
| Veteran       | You can choose 2 traits for this weapon family. Up to [[Beyond the Veil/Veil Glossary/Veteran\|Veteran]].<br><br>You can choose a single [[Modification\|Modification]] trait for this weapon family. |
| Master        | You can choose 3 traits for this weapon family. Up to [[Beyond the Veil/Veil Glossary/Master\|Master]].                                                                                |

```base
filters:
  and:
    - MasterySkills.contains(link("Throwing"))
    - base == link("Abilities.base")
formulas:
  Untitled: ""
properties:
  formula.Untitled:
    displayName: sortOrderRank
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
      note.MasterySkills: 232
      note.Traits: 120
    rowHeight: medium

```



```base
filters:
  and:
    - file.hasLink("Bases/Weapon Families.base")
    - and:
        - Families.contains(link("Throwing"))
properties:
  file.name:
    displayName: Name
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


## TODO Abilities 

- Adept
    - pinning throw, a creature next to a surface can be held to that surface Fort DC
- Veteran
    - [[Beyond the Veil/Veil Glossary/Combo\|Combo]] Abilities
        - Incorporated Throw: When an ally uses a ranged attack, you can use this paired action to throw your weapon as part of their attack, this attack is made with advantage.
    - Block Projecttile (Reaction)
        - You can throw your weapon as a reaction against a **ranged** attack in your reach, if your roll is higher, you [[Beyond the Veil/Veil Glossary/Interrupt\|Interrupt]] the attack.
    - Repeating throw (veteran) (Agile)
        - 2 or 3 actions, you make 2 or 3 [[Beyond the Veil/Veil Glossary/Power Strike\|Power Strike]]s 
        - You strike multiple times, each successful strike gives the traget a single bane to your weapon’s damage type, until the end of your turn.
    - Binding Chains: you generate a chains of dense mana to your thrown weapon, if you hit an enemy with this attack, you can ‘pull them towards you’ Fort DC
- Master
    - Heart Piercer (master)
        - Strike with [[Beyond the Veil/Veil Glossary/Advantage\|Advantage]] and this attack can crit on 8 rather than 10.
    - Unload Arsenal, large aoe damage + Held as the weapins pin creatures to the ground.