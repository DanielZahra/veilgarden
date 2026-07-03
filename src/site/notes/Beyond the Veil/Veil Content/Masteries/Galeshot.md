---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/galeshot/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"","Status":"Work in Progress","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Air Element Knowledge]]"]}}
---

# [[Beyond the Veil/Veil Content/Masteries/Galeshot\|Galeshot]] Equipment Mastery

| Mastery Level | Effect                                                                                                                                                                                                                                                          |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain [[Beyond the Veil/Veil Content/Features and Passives/Galeshot's Arsenal\|Galeshot's Arsenal]]<br><br>Your held weapons that have the [[Beyond the Veil/Veil Glossary/Range/Range\|Range]] or [[Beyond the Veil/Veil Glossary/Thrown/Thrown\|Thrown]] trait gain the [[Beyond the Veil/Veil Glossary/Graze\|Graze]] trait.<br><br>Your [[Beyond the Veil/Veil Glossary/Range/Range\|Range]] or [[Beyond the Veil/Veil Glossary/Thrown/Thrown\|Thrown]] gains [[Beyond the Veil/Veil Glossary/Extended Range/Extended Range 3\|Extended Range 3]], if you already have this trait, it increased by an additional 3. |
| Veteran       |                                                                                                                                                                                                                                                                 |
| Master        |                                                                                                                                                                                                                                                                 |
{ #bb23db}


```base
filters:
  and:
    - MasterySkills.contains(link("Galeshot"))
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
      file.name: 196
      note.MasterySkills: 367

```


## TODO

- Abilities
    - Adept
        - [[Beyond the Veil/Veil Content/Abilities/Static Armaments\|Static Armaments]] imbe
    - Veteran
        - 
    - Master
