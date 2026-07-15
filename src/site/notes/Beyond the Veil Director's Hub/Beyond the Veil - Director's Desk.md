---
{"dg-publish":true,"permalink":"/beyond-the-veil-director-s-hub/beyond-the-veil-director-s-desk/","dg-note-properties":{}}
---


## Ability Design

When designing an ability, we start with calculating the damage, an ability can have a base damage or include a strike which are both counted as damage. All effects that apply to an ability are applied, and stack together. Example a ranged ability with range of 18 or more gains -2 damage since it has both range cumulatives.

Abilities can then modify the numbers or apply effects based on their mastery level.

### Mastery Abilities

In the table below, Adept typically has 1 Element, Veteran has 2 and Master has 3.

|Element|Desc|
|---|---|
|Conditions|Ability Applies a boon, bane, or condition|
|Additional Damage|Ability deals more damage then usual.  <br>  <br>Normal Abilities simply deal 1 more damage, or 2 if applied twice, 3 if applied 3 times.  <br>Strikes Deal 2 more damage|
|Action Economy|Ability Costs 1 less Action|
|Other Effects|This is very broad, tbd.|

| Design Step                 | Options                                 | Modifications                                                                                                     | Comments                                                                              |
| --------------------------- | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| Base Damage                 | Strike                                  | Weapon Based                                                                                                      | Abilities with Strike do not have the base damage modified.                           |
| 1 Action                    | 3                                       |                                                                                                                   |                                                                                       |
| 2 Actions                   | 6                                       |                                                                                                                   |                                                                                       |
| 3 Actions                   | 9                                       |                                                                                                                   |                                                                                       |
| Persistent Damage           | 2                                       | Persistent Damage is not modified.                                                                                |                                                                                       |
| Range and Area              | Melee/Adjacent/Self Only                | 1                                                                                                                 |                                                                                       |
| Ranged                      | 1-                                      | Abilities that originate from the actor, such as a Cone of Fire are not classified as ranged. (but they are area) |                                                                                       |
| Ranged Long                 | 1-                                      | 18 Range or over                                                                                                  |                                                                                       |
| Multitarget 3+              | 1-                                      |                                                                                                                   |                                                                                       |
| Area                        | 1-                                      | Area considers only Abilities that cover 3x3 or 9 Spaces total. Anything smaller doesn't get negative damage.     |                                                                                       |
| Area Large                  | 1-                                      | Large Area is 6x6 or 36 Spaces or larger.                                                                         |                                                                                       |
| Conditions, Boons and Banes | Major Boon or Bane and Major Conditions | 1-                                                                                                                | (Doesn't Overlap with Minor Conditions, or Boons and banes, biggest takes effect)     |
| Damage Boon or Bane         | 2                                       | Damage Resistaces and Weaknesses                                                                                  |                                                                                       |
| Major Damage Boon or Bane   | 4                                       | Damage Resistaces and Weaknesses                                                                                  |                                                                                       |
| Duration                    | Long Duration Damage                    | 1-                                                                                                                | This typically refeers to abilities that last till end of encouter, such as firewall. |
| Strike Damage Buff          | Long                                    | 1                                                                                                                 | Long Refers to Permanent or Encounter long buff                                       |
| Instant                     | 2                                       | Instant refers to damage buff to the current ability or strike                                                    |                                                                                       |
| Restriction                 | Small                                   | 1                                                                                                                 | Effect that add a single/minor restriction (Example Sneak attacking need Agile Trait) |
| Major                       | 2                                       | Effect that add multiple or major restrictions.(Example Target must be prone)                                     |                                                                                       |

## [[Beyond the Veil Director's Hub/Monster Building\|Monster Building]]


### Monster Types

| Type           | Effect                                                                                                         |
| -------------- | -------------------------------------------------------------------------------------------------------------- |
| [[Artillery\|Artillery]]  | Relies mainly on dealing damage from range.                                                                    |
| [[Brawler\|Brawler]]    | Skilled warriors that fight in closer range                                                                    |
| [[Controller\|Controller]] | Relies on debilitation and battlefield control                                                                 |
| [[Skirmisher\|Skirmisher]] | Relies on hit and run, varies between melee and range attacks                                                  |
| [[Stealthy\|Stealthy]]   | Ambushing and Stealth Tactics                                                                                  |
| [[Defender\|Defender]]   | High Defenses , defends allies                                                                                 |
| [[Support\|Support]]    | Support their allies with healing and buffs                                                                    |
| [[Pack\|Pack]]       | These monsters funciton well within a pack of their own kind, typically benefitting from pairing and flanking. |
| [[Beyond the Veil/Veil Glossary/Swarm\|Swarm]]      |                                                                                                                |

# Magic Items


```base
filters:
  and:
    - note["base"] == link("Magic Items.base")
properties:
  file.name:
    displayName: Name
  Activation:
    displayName: Activation
  Traits:
    displayName: Traits
  Cooldown:
    displayName: Cooldown
  Rarity:
    displayName: Rarity
  Grade:
    displayName: Grade
views:
  - type: table
    name: Table View
    order:
      - file.name
      - Traits
      - Cooldown
      - Rarity
      - Rank
      - Activation
      - image
    sort:
      - property: Cooldown
        direction: ASC
      - property: Grade
        direction: ASC
    columnSize:
      note.Rank: 277
      note.Actions: 152
    cardSize: 240
  - type: cards
    name: Gallery
    order:
      - file.name
      - Traits
      - Rarity
      - Activation
      - Rank
    cardSize: 280
    image: note.image
    imageAspectRatio: 1

```
