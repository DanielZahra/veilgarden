---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/trickster/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"Nobody said you need to fight fair. The trickstar is a master of fighting while tricking their opponents and making sure they hide, fake getting hit and move around the battlefield with deftness. They are skilled at creating illusions and avoiding attacks.","Status":"Mostly Done","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Illusion Knowledge]]"]}}
---

# [[Beyond the Veil/Veil Content/Masteries/Trickster\|Trickster]] Discipline Mastery

| Mastery Level | Effect                                                                                                                                                                                                                                                                                                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain the [[Beyond the Veil/Veil Content/Features and Passives/Trickster's Evasion\|Trickster's Evasion]] feature.<br><br>When you take the [[Beyond the Veil/Veil Content/Actions/Dodge\|Dodge]] action you create an illusory double that warps your image.  If you suffer a successful [[Beyond the Veil/Veil Glossary/Attack\|Attack]], you can turn it into a failure.<br><br>[[Beyond the Veil/Veil Content/Features and Passives/Trickster's Evasion\|Trickster's Evasion]] resets at the start of your turn.<br><br>[[Beyond the Veil/Veil Content/Features and Passives/Trickster's Evasion\|Trickster's Evasion]] has no effect on critical attacks against you. |
| Veteran       | When using [[Beyond the Veil/Veil Content/Features and Passives/Trickster's Evasion\|Trickster's Evasion]], your [[Beyond the Veil/Veil Content/Actions/Dodge\|Dodge]] sets your [[Beyond the Veil/Veil Glossary/Defense\|Defense]] to 15 rather than 14.                                                                                                                                                                                                                                                                      |
| Master        | TBD                                                                                                                                                                                                                                                                                                                                                                 |
{ #d037df}



```base
filters:
  and:
    - MasterySkills.contains(link("Trickster"))
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
      file.name: 233

```


## TODO

- Abilities
    - Adept
        - 
    - Veteran
        - Swap positions with an enemy or ally
        - AOE Illusion attack Veteran
    - Master