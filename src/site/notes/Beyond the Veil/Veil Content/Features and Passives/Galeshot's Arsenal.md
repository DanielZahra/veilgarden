---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/features-and-passives/galeshot-s-arsenal/","dg-note-properties":{"base":"[[Passives Database.base]]","rank":"[[Adept]]","MasterySkills":["[[Beyond the Veil/Veil Content/Masteries/Galeshot\|Galeshot]]"],"sortOrderByRank":1}}
---


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/beyond-the-veil/veil-content/masteries/galeshot/#bb23db" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# [[Beyond the Veil/Veil Content/Masteries/Galeshot\|Galeshot]] Equipment Mastery

| Mastery Level | Effect                                                                                                                                                                                                                                                          |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain [[Beyond the Veil/Veil Content/Features and Passives/Galeshot's Arsenal\|Galeshot's Arsenal]]<br><br>Your held weapons that have the [[Beyond the Veil/Veil Glossary/Range/Range\|Range]] or [[Beyond the Veil/Veil Glossary/Thrown/Thrown\|Thrown]] trait gain the [[Beyond the Veil/Veil Glossary/Graze\|Graze]] trait.<br><br>Your [[Beyond the Veil/Veil Glossary/Range/Range\|Range]] or [[Beyond the Veil/Veil Glossary/Thrown/Thrown\|Thrown]] gains [[Beyond the Veil/Veil Glossary/Extended Range/Extended Range 3\|Extended Range 3]], if you already have this trait, it increased by an additional 3. |
| Veteran       |                                                                                                                                                                                                                                                                 |
| Master        |                                                                                                                                                                                                                                                                 |


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


</div></div>
