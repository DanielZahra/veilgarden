---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/masteries/ossifier/","dg-note-properties":{"base":"[[Masteries Base.base]]","Description":"You raise a skeletal creatures to do you bidding and massacre your foes.","Status":"Mostly Done","Mastery Type":["[[Companion Mastery]]"],"Knowledge Gained":["[[Necromancy Knowledge]]"]}}
---

# [[Beyond the Veil/Veil Content/Masteries/Ossifier\|Ossifier]] Companion Mastery

| Mastery Level | Effect                                                                                                                                                                     |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adept         | You gain the [[Beyond the Veil/Veil Content/Rituals/Bind Ossified Ally\|Bind Ossified Ally]] Ritual and [[Beyond the Veil/Veil Content/Abilities/Bone Pack\|Bone Pack]] Ability.<br><br>You can prepare 2 Adept Traits for your Bound Skeleton                                        |
| Veteran       | You can prepare 3 Adept Traits for your Bound Skeleton<br>You can prepare 1 Veteran Trait for your Bound Skeleton                                                          |
| Master        | You can prepare 3 Adept Trait for your Bound Skeleton<br>You can prepare 2 Veteran Traits for your Bound Skeleton<br>You can prepare 1 Master Trait for you Bound Skeleton |

```base
filters:
  and:
    - MasterySkills.contains(link("Ossifier"))
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



```base
filters:
  and:
    - MasterySkills.contains(link("Ossifier"))
    - base == link("Passives Database.base")
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
      - Traits
      - Requirement
    sort:
      - property: sortOrderByRank
        direction: ASC
    columnSize:
      file.name: 244
      note.rank: 146
      note.MasterySkills: 478

```


## TODO

- Review familiar abilities
- Abilities
    - 
        - Harded Bones
            - Companion gains boon to defense and fortitude
        - Harvest
            - If the companion is adjacent to a dead enemy, free action get gain a boon to all stats until end of this turn.
    - Veteran
        - Summon abilities
            - Skeletal swarm
                - Choice or archer, solider, mages
        - Bone nova
            - From companion
    - Master
- Passives