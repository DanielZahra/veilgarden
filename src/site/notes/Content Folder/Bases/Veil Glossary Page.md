---
{"dg-publish":true,"permalink":"/content-folder/bases/veil-glossary-page/","dg-note-properties":{}}
---


```base
filters:
  and:
    - note["base"] == link("Veil Glossary.base")
properties:
  file.name:
    displayName: Name
  Type:
    displayName: Type
  Description:
    displayName: Description
views:
  - type: table
    name: Table View
    order:
      - file.name
      - tags
    sort:
      - property: Description
        direction: DESC
    columnSize:
      file.name: 492
      note.Description: 874
  - type: cards
    name: View
    image: note.tags

```
