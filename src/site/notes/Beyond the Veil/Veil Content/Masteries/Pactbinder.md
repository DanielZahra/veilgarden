---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/pactbinder/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"The Pactbinder creates magical pacts with allies to strengthen them and forces pacts on enemies to hinder their efficacy.","Status":"Mostly Done","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Curses Knowledge]]"]}}
---

# [[Beyond the Veil/Veil Content/Masteries/Pactbinder\|Pactbinder]] Discipline Mastery

| Mastery Level | Effect                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain the [[Beyond the Veil/Veil Content/Features and Passives/Pact Edict\|Pact Edict]] Feature.<br><br>[[Beyond the Veil/Veil Content/Features and Passives/Pact Edict\|Pact Edict]] allows you to enforce Boons, Banes and Some conditions. By expending the edict’s power.<br><br>When you apply a [[Beyond the Veil/Veil Glossary/Boon\|Boon]] or [[Beyond the Veil/Veil Glossary/Bane\|Bane]] you can use a Free Action to spend your [[Beyond the Veil/Veil Content/Features and Passives/Pact Edict\|Pact Edict]] to increase to a [[Beyond the Veil/Veil Glossary/Major Boon\|Major Boon]] or [[Beyond the Veil/Veil Glossary/Major Bane\|Major Bane]] on a single creature.<br><br>If you apply a [[Beyond the Veil/Veil Glossary/Boon\|Boon]] or [[Beyond the Veil/Veil Glossary/Bane\|Bane]] to a group of creatures you choose which creature gets your [[Beyond the Veil/Veil Content/Features and Passives/Pact Edict\|Pact Edict]].<br><br>Some abilities may outline a different use for [[Beyond the Veil/Veil Content/Features and Passives/Pact Edict\|Pact Edict]].<br><br> This use is restored with a [[Beyond the Veil/Veil Content/Exploration Activities/Take a Break\|Take a Break]]. |
| Veteran       | You have 2 Pact Edicts.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Master        | You have 2 Pact Edicts.<br>You have 1 Major Pact Edict, which can be used on multiple creatures at the same time.                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
{ #e70fb2}



```base
filters:
  and:
    - MasterySkills.contains(link("Pactbinder"))
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

- Main Feature
    - 
- Abilities
    - Adept
        - Pact of Brittleness
            - Debuff Defense, roll vs will DC
            - Chose a single Damage type as a bane.
    - Veteran
    - Master
