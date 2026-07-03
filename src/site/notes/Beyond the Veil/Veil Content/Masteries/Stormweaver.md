---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/stormweaver/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"As a Stormweaver you channel lightning and electricity to deliver destruction upon your foes, as you channel more electricity your body builds Overcharge, you can then overcharge any attack or ability you do with your stormweaver powers to deal even more destruction.","Status":"Done","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Weather Knowledge]]"]}}
---

# [[Beyond the Veil/Veil Content/Masteries/Stormweaver\|Stormweaver]] Discipline Mastery

| Mastery Level | Effect                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain the [[Beyond the Veil/Veil Content/Features and Passives/Overcharge\|Overcharge]] feature. Every time you deal damage with the [[Beyond the Veil/Veil Glossary/Air\|Air]] Trait or use an ability with said trait, you gain a stack of [[Beyond the Veil/Veil Content/Features and Passives/Overcharge\|Overcharge]].<br><br>When dealing any damage you can spend an additional action to unleash [[Beyond the Veil/Veil Content/Features and Passives/Overcharge\|Overcharge]] dealing an additional 2 [[Beyond the Veil/Veil Glossary/Air Damage\|Air Damage]] per charge used. [[Beyond the Veil/Veil Content/Features and Passives/Overcharge\|Overcharge]] expires at the [[Beyond the Veil/Veil Glossary/End of Encounter\|End of Encounter]].<br><br>You can have a maximum of 2 stack of [[Beyond the Veil/Veil Content/Features and Passives/Overcharge\|Overcharge]]. |
| Veteran       | [[Beyond the Veil/Veil Content/Features and Passives/Overcharge\|Overcharge]] stack limit increases to 4.<br><br>You gain [[Beyond the Veil/Veil Glossary/Boon\|Boon]] against [[Beyond the Veil/Veil Glossary/Air Damage\|Air Damage]].                                                                                                                                                                                                                                                                                                                                       |
| Master        | [[Beyond the Veil/Veil Content/Features and Passives/Overcharge\|Overcharge]] stack limit increases to 6.<br><br>You gain [[Beyond the Veil/Veil Glossary/Major Boon\|Major Boon]] against [[Beyond the Veil/Veil Glossary/Air Damage\|Air Damage]].                                                                                                                                                                                                                                                                                                                                 |
{ #8caad2}



```base
filters:
  and:
    - MasterySkills.contains(link("Stormweaver"))
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


