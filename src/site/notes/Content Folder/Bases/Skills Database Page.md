---
{"dg-publish":true,"permalink":"/content-folder/bases/skills-database-page/","dg-note-properties":{}}
---


```base
filters:
  and:
    - note["base"] == link("Skills.base")
properties:
  file.name:
    displayName: Categories
  Category:
    displayName: Category
  Actions/Usage/Benefits:
    displayName: Actions/Usage/Benefits
  note.Actions/Usage/Benefits:
    displayName: Description
views:
  - type: table
    name: Table View
    order:
      - file.name
      - Description
    sort:
      - property: Category
        direction: ASC
    cardSize: 800

```
