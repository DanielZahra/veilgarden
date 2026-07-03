---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/outsider/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"Your have a deep seated power from the cosmos, a horror of the unknown, void powers that grandmothers scare their grandchildren with. You have learnt to control these powers and unleash the monster inside with a transformation. ","Status":"Mostly Done","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Aberrant Knowledge]]"]}}
---


| Mastery Level | Effect                                                                                                                                                                                  |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain the [[Beyond the Veil/Veil Content/Abilities/Outsider Shift\|Outsider Shift]] Ability  <br>  <br>During [[Beyond the Veil/Veil Glossary/Preparation\|Preparation]] you can choose your unlocked Outsider Traits.  <br>  <br>You can prepare two [[Beyond the Veil/Veil Glossary/Transformation\|Transformation]] Adept Traits. |
| Veteran       | You can prepare three [[Beyond the Veil/Veil Glossary/Transformation\|Transformation]] Adept Trait.  <br>You can prepare one [[Beyond the Veil/Veil Glossary/Transformation\|Transformation]] Veteran Trait.                                                                        |
| Master        | You can prepare three [[Beyond the Veil/Veil Glossary/Transformation\|Transformation]] Adept Trait.  <br>You can prepare two [[Beyond the Veil/Veil Glossary/Transformation\|Transformation]] Veteran Trait.  <br>You can prepare one [[Beyond the Veil/Veil Glossary/Transformation\|Transformation]] Master Trait.              |

```base
filters:
  and:
    - MasterySkills.contains(link("Outsider"))
    - base == link("Abilities.base")
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
      file.name: 204

```



```base
filters:
  and:
    - MasterySkills.contains(link("Outsider"))
    - base == link("Passives Database.base")
views:
  - type: table
    name: Table
    order:
      - file.name
      - rank
      - MasterySkills
      - Traits
      - Requirement
    sort:
      - property: sortOrderByRank
        direction: ASC
    columnSize:
      file.name: 204

```
