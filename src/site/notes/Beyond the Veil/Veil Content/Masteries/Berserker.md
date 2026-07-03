---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/berserker/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"","Status":"Mostly Done","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Unorthodox Fighting Knowledge]]"]}}
---


| Mastery Level | Effect                                                                                                    |
| ------------- | --------------------------------------------------------------------------------------------------------- |
| Adept         | You gain the [[Beyond the Veil/Veil Content/Abilities/Berserker Stance\|Berserker Stance]] ability.                                                                |
| Veteran       | While in [[Beyond the Veil/Veil Content/Abilities/Berserker Stance\|Berserker Stance]] you are immune to the [[Beyond the Veil/Veil Content/Conditions/Slowed\|Slowed]], [[Beyond the Veil/Veil Content/Conditions/Terror\|Terror]], and [[Beyond the Veil/Veil Content/Conditions/Lethargic\|Lethargic]] conditions. |
| Master        | While in [[Beyond the Veil/Veil Content/Abilities/Berserker Stance\|Berserker Stance]] you no longer have a [[Beyond the Veil/Veil Glossary/Bane\|Bane]] to your [[Beyond the Veil/Veil Glossary/Defense\|Defense]] and you gain 2 [[Beyond the Veil/Veil Glossary/Speed\|Speed]]. |

```base
filters:
  and:
    - MasterySkills.contains(link("Berserker"))
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



## TODO Abilities 

- [[Beyond the Veil/Veil Content/Abilities/Leaping Crash\|Leaping Crash]] Master Edition.
