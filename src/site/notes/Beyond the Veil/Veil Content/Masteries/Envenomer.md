---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/envenomer/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"If it’s poison you want, the Envenomer knows it.","Status":"Work in Progress","Knowledge Gained":"[[Poison, Venom and Toxin Knowledge]]","Mastery Type":["[[Equipment Mastery]]"]}}
---


| Mastery Level | Effect                                                                                                                                                                                                      |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | Once per turn you can use an [[Beyond the Veil/Veil Content/Actions/Interact\|Interact]] action on a [[Beyond the Veil/Veil Glossary/Venom\|Venom]] trait gear as a [[Beyond the Veil/Veil Glossary/Free Action\|Free Action]].<br>  <br>You gain [[Beyond the Veil/Veil Glossary/Major Boon\|Major Boon]] to [[Beyond the Veil/Veil Glossary/Earth Damage\|Earth Damage]].                                                      |
| Veteran       | When you apply a [[Beyond the Veil/Veil Glossary/Venom\|Venom]] to a creature, the creature also suffers 2 points of  [[Beyond the Veil/Veil Glossary/Persistent/Persistent\|Persistent]] [[Beyond the Veil/Veil Glossary/Earth Damage\|Earth Damage]] until [[Beyond the Veil/Veil Glossary/End of Encounter\|End of Encounter]]<br>  <br>[[Beyond the Veil/Veil Glossary/Persistent/Persistent\|Persistent]] [[Beyond the Veil/Veil Glossary/Earth Damage\|Earth Damage]] you apply stacks.      |
| Master        | When applying your [[Beyond the Veil/Veil Glossary/Venom\|Venom]] to [[Beyond the Veil/Veil Glossary/Overpower/Overpower\|Overpower]] a creature’s [[Beyond the Veil/Veil Glossary/Fortitude\|Fortitude]], [[Beyond the Veil/Veil Glossary/Reflex\|Reflex]] or [[Beyond the Veil/Veil Glossary/Will\|Will]] the creature is treated as if having a [[Beyond the Veil/Veil Glossary/Bane\|Bane]] against the [[Beyond the Veil/Veil Glossary/Overpower/Overpower\|Overpower]] effect concerning the [[Beyond the Veil/Veil Glossary/Venom\|Venom]]. |

```base
filters:
  and:
    - MasterySkills.contains(link("Envenomer"))
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
    - base == link("Gear.base")
    - Traits.contains(link("Venom"))
views:
  - type: table
    name: Table
    order:
      - file.name
      - Traits
      - Dossier
      - Multi-Purchase
      - rank
      - Stack
      - Wealth Cost
      - Actions
    sort:
      - property: sortOrderByRank
        direction: ASC
    columnSize:
      file.name: 182

```



## TODO

- Abilities
    - Veteran
        - Apply a venom to an ally’s attack (adjacent) as a free action, paired action
        - Toxic Dot Strike
        - Poweful toxin, ignore any earth boon/resistance for 1 ability
    - Master
        - Aoe earth dmg boon for allies