---
{"dg-publish":true,"permalink":"/beyond-the-veil/beyond-the-veil-director-s-desk/","dg-note-properties":{}}
---


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
      - Grade
      - Actions
      - Activation
      - image
    columnSize:
      note.Actions: 152
    cardSize: 240
  - type: cards
    name: Gallery
    order:
      - file.name
      - Traits
      - Rarity
      - Grade
      - Activation
    cardSize: 280
    image: note.image
    imageAspectRatio: 1

```
