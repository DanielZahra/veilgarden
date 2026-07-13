---
{"dg-publish":true,"permalink":"/beyond-the-veil/veil-content/campcraft/academia-and-arcanum/","dg-note-properties":{}}
---

#### [[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum\|Academia and Arcanum]] [[Beyond the Veil/Veil Glossary/Gear\|Gear]]
| Item Name                                                                 | Rank                                                  | Traits                                                                                             | Dossier                                                                                  | Actions           | Stack | Wealth Cost | Multi-Purchase |
| ------------------------------------------------------------------------- | ----------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ----------------- | ----- | ----------- | -------------- |
| [[Beyond the Veil/Veil Content/Gear/Language Manual\|Language Manual]] | [[Beyond the Veil/Veil Glossary/Adept\|Adept]]     | [[Beyond the Veil/Veil Glossary/Knowledge\|Knowledge]]                                          | [[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum\|Academia and Arcanum]] | Downtime Activity | \-    | Varies      | true           |
| [[Beyond the Veil/Veil Content/Gear/Scholar’s Set\|Scholar’s Set]]     | [[Beyond the Veil/Veil Glossary/Adept\|Adept]]     | [[Beyond the Veil/Veil Glossary/Kit\|Kit]]                                                      | [[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum\|Academia and Arcanum]] |                   | 1     | 1           | true           |
| [[Beyond the Veil/Veil Content/Gear/Study material\|Study material]]   | \-                                                    | [[Beyond the Veil/Veil Glossary/Knowledge\|Knowledge]]                                          | [[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum\|Academia and Arcanum]] | Downtime Activity | \-    | Varies      | false          |
| [[Beyond the Veil/Veil Content/Gear/Catalyst\|Catalyst]]               | [[Beyond the Veil/Veil Glossary/Veteran\|Veteran]] | [[Beyond the Veil/Veil Glossary/Gear\|Gear]]<br>[[Beyond the Veil/Veil Glossary/Worn\|Worn]] | [[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum\|Academia and Arcanum]] | Ability Based     | 1     | 1           | true           |

{ .block-language-dataview}

#### [[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum\|Academia and Arcanum]] [[Beyond the Veil/Veil Glossary/Campcraft\|Campcraft]] Upgrades
| Name                                                                                                | Rank                      | Dossier                                                                                                     | Requirements | Wealth Cost | Traits |
| --------------------------------------------------------------------------------------------------- | ------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------ | ----------- | ------ |
| [[Beyond the Veil/Veil Content/Campcraft Passive Database/Favored Ritual\|Favored Ritual]]       | <ul><li>Adept</li></ul>   | <ul><li>[[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum.md\\|Academia and Arcanum]]</li></ul> |              | 8           |        |
| [[Beyond the Veil/Veil Content/Campcraft Passive Database/Learning Candles\|Learning Candles]]   | <ul><li>Adept</li></ul>   | <ul><li>[[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum.md\\|Academia and Arcanum]]</li></ul> |              | 2           |        |
| [[Beyond the Veil/Veil Content/Campcraft Passive Database/Catalyst Creation\|Catalyst Creation]] | <ul><li>Veteran</li></ul> | <ul><li>[[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum.md\\|Academia and Arcanum]]</li></ul> |              | 6           |        |
| [[Beyond the Veil/Veil Content/Campcraft Passive Database/Thoughts of Mana\|Thoughts of Mana]]   | <ul><li>Veteran</li></ul> | <ul><li>[[Beyond the Veil/Veil Content/Campcraft/Academia and Arcanum.md\\|Academia and Arcanum]]</li></ul> |              | 4           |        |

{ .block-language-dataview}
#### [[Ritual Tome\|Ritual Tome]]


```base
filters:
  and:
    - note["base"] == link("Rituals.base")
properties:
  file.name:
    displayName: Name
  Primary DC:
    displayName: Primary DC
  Traits:
    displayName: Traits
  Unlocked:
    displayName: Unlocked
  Wealth Cost:
    displayName: Wealth Cost
  Cast Time:
    displayName: Cast Time
  Primary Skill:
    displayName: Primary Skill
  Kits or Tools:
    displayName: Kits or Tools
  Tier:
    displayName: Tier
  Casting Cost:
    displayName: Casting Cost
  Secondary Skill/s:
    displayName: Secondary Skill/s
views:
  - type: table
    name: Table View
    order:
      - file.name
      - Traits
      - Unlocked
      - Wealth Cost
      - Cast Time
      - Skills
      - Skill Check DC
      - Kits or Tools
      - Rank
      - sortOrderByRank
      - Requirement
    sort:
      - property: sortOrderByRank
        direction: ASC
    columnSize:
      file.name: 214
      note.Unlocked: 91
      note.Wealth Cost: 106
      note.Skills: 233
      note.Rank: 190
    rowHeight: medium

```
