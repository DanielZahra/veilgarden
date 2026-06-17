---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/weapons/weapons/","dg-note-properties":{}}
---

# Weapon Traits

Weapon Properties are unlocked or gained by investing in gear mastery, properties alter a base weapons.  **You can only have one weapon trait chosen at each tier unless a feature specifies that you can have multiple.**

Weapons have different trait categories:

- Damage: Their Default Damage 
- Basic Traits: The basic elements of the weapon, main damage, hands needed, range and other traits that are available to everyone without mastery.
- Mastery Traits
    - Adept Traits: Traits you can use when you reach Adept mastery in these weapons
    - Veteran Traits: Traits you can use when you reach veteran mastery in these weapons
    - At veteran you can also gain a modification trait, where you can modify your weapons to to apply special effects or to perform in a different way.
    - Master Traits: Traits you can use when you reach Master mastery in these weapons


```base
filters:
  and:
    - note["base"] == link("Weapon Families.base")
properties:
  file.name:
    displayName: Type
  Master Traits:
    displayName: Master Traits
  Veteran Traits:
    displayName: Veteran Traits
  Modification Trait:
    displayName: Modification Trait
  Damage:
    displayName: Damage
  Families:
    displayName: Families
  Adept Traits:
    displayName: Adept Traits
  Comment:
    displayName: Comment
  Basic Traits:
    displayName: Basic Traits
  note.Families:
    displayName: Families
views:
  - type: table
    name: Weapons Families All
    order:
      - file.name
      - Families
      - Damage
      - Basic Traits
      - Adept Traits
      - Veteran Traits
      - Modification Trait
      - Master Traits
      - Comment
    sort:
      - property: Families
        direction: ASC
    columnSize:
      note.Families: 191
      note.Basic Traits: 620
      note.Modification Trait: 292
      note.Master Traits: 255
  - type: cards
    name: Cards View
    order:
      - file.name
      - Families
      - Damage
      - Basic Traits
      - Adept Traits
      - Veteran Traits
      - Modification Trait
      - Master Traits
      - Comment
    sort:
      - property: Families
        direction: ASC
    columnSize:
      note.Families: 265
      note.Basic Traits: 507
    imageFit: contain
    imageAspectRatio: 1.15
    cardSize: 390

```


