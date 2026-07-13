---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-glossary/downtime-activity/","tags":["Terminology"],"dg-note-properties":{"base":"[[Veil Glossary.base]]","Type":null,"Description":null,"tags":["Terminology"]}}
---

These are the activities you take when you [[Beyond the Veil/Veil Glossary/Rest/Rest\|Rest]].


```base
filters:
  and:
    - note["base"] == link("Downtime Activities Database.base")
properties:
  file.name:
    displayName: Downtime Activity
  Effect:
    displayName: Effect
  Requirements:
    displayName: Requirements
  Related:
    displayName: Related
  Select:
    displayName: Select
  Related Skills:
    displayName: Related Skills
views:
  - type: table
    name: Table View
    order:
      - file.name
      - Effect
      - Requirements
    sort: []
    columnSize:
      note.Requirements: 347

```
