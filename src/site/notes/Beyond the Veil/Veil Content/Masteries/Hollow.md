---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/hollow/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"You are as acoltye of the void, you have learnt to tap into the void and use its power for yourself. As you cause the void to devour your foes, your own vitality also suffers the consequences.","Status":"Mostly Done","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Void Element Knowledge]]"]}}
---

# [[Beyond the Veil/Veil Content/Masteries/Hollow\|Hollow]] Discipline Mastery

| Mastery Level | Effect                                                                                                                                                                                                                                                                                                                                                                                        |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain the [[Beyond the Veil/Veil Content/Features and Passives/Hollowification\|Hollowification]] Feature.  <br>  <br>When you deal [[Beyond the Veil/Veil Glossary/Direct Damage\|Direct Damage]] with the [[Beyond the Veil/Veil Glossary/Void\|Void]] Trait or use an ability with said trait, you can trigger [[Beyond the Veil/Veil Content/Features and Passives/Hollowification\|Hollowification]] and deal an additional 2 [[Beyond the Veil/Veil Glossary/Void Damage\|Void Damage]].<br>  <br>Every time you trigger [[Beyond the Veil/Veil Content/Features and Passives/Hollowification\|Hollowification]] your total [[Beyond the Veil/Veil Glossary/Vitality\|Vitality]]  is reduced by 1. The [[Beyond the Veil/Veil Content/Features and Passives/Hollowification\|Hollowification]] effect is removed during [[Beyond the Veil/Veil Content/Exploration Activities/Take a Break\|Take a Break]] |
| Veteran       | Once per Encounter when you deal [[Beyond the Veil/Veil Glossary/Void Damage\|Void Damage]] to a creature through [[Beyond the Veil/Veil Content/Features and Passives/Hollowification\|Hollowification]], you also give them a [[Beyond the Veil/Veil Glossary/Bane\|Bane]] to [[Beyond the Veil/Veil Glossary/Void Damage\|Void Damage]] until [[Beyond the Veil/Veil Glossary/End of this turn\|End of this turn]].                                                                                                                                                                                                                      |
| Master        | You gain 2 maximum [[Beyond the Veil/Veil Glossary/Vitality\|Vitality]].                                                                                                                                                                                                                                                                                                                                                              |
{ #911dbe}



```base
filters:
  and:
    - MasterySkills.contains(link("Hollow"))
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


## TODO

- Abilities
    - Adept
        - 
    - Veteran
        - Large cone that ‘sucks’ in Foes
        - Void Swap
    - Master
        - Sword of darkness, line aoe, conditon applies
- Passives