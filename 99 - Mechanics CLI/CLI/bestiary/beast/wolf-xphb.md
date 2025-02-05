---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Wolf"]
---
# [Wolf](3-Mechanics\CLI\bestiary\beast/wolf-xphb.md)
*Source: Player's Handbook (2024) p. 359, Monster Manual (2024) p. 373*  

```statblock
"name": "Wolf (XPHB)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "15"
- !!int "12"
- !!int "3"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The wolf has Advantage on attack rolls against a creature if at least one\
    \ of the wolf's allies is within 5 feet of the creature and the ally doesn't have\
    \ the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) condition."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Attack: +4, reach 5 ft. Hit: 5 (1d6 + 2) Piercing damage,\
    \ and the target has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone) condition\
    \ if it is Medium or smaller."
  "name": "Bite"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/beast/token/wolf-xphb.webp"
```
^statblock