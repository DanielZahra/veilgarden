---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/lifespinner/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"You manipulate the forces of life between creatures to energy allies or destroy your foes. You spin your mana as if it were a needle between life and death.\n\n“The world is a tapestry of veins. I simply choose where to pull the thread.“","Status":"Work in Progress","Mastery Type":["[[Discipline Mastery]]"],"Knowledge Gained":["[[Blood Element Knowledge]]"]}}
---

# [[Beyond the Veil/Veil Content/Masteries/Lifespinner\|Lifespinner]] Discipline Mastery

| Mastery Level | Effect                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain the [[Beyond the Veil/Veil Content/Features and Passives/Crimson Embroidery\|Crimson Embroidery]] feature.<br><br>Your [[Beyond the Veil/Veil Glossary/Healing\|Healing]] trait abilities can be used for both harming foes or healing your allies. When using abilities to harm foes, they lose the [[Beyond the Veil/Veil Glossary/Healing\|Healing]] trait . You use the abilities' attack or offensive portions. If it does not have an offensive roll you simply make a [[Prowess roll vs Basic Will\|Prowess roll vs Basic Will]] and this turns [[Beyond the Veil/Veil Glossary/Healing\|Healing]] into [[Beyond the Veil/Veil Glossary/Anima Damage\|Anima Damage]]. |
| Veteran       |                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Master        |                                                                                                                                                                                                                                                                                                                                                                                                                   |
{ #9ebd4a}



```base
filters:
  and:
    - MasterySkills.contains(link("Lifespinner"))
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

- 
- Abilities
    - Adept
        - 
        - 
        - 
    - Veteran
        - Corpse Teleportation  + Splash Heal/dmg
        - Paired, blood damage and healing ability
            - Blood Attack?
        - Blood Well (dmg/healing)
            - Area of healing, ground (only allies heal)
        - Blood Link
            - Similar to see but the healing half of the damage and range is bigger, but it’s 1 to 1 creature.
    - Master
        - [[Beyond the Veil/Veil Content/Abilities/Vampiric Symbiote\|Vampiric Symbiote]] but AOE
