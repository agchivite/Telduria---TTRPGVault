---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Dire Wolf"]
---
# [Dire Wolf](3-Mechanics\CLI\bestiary\beast/dire-wolf-xphb.md)
*Source: Player's Handbook (2024) p. 348, Monster Manual (2024) p. 352*  

```statblock
"name": "Dire Wolf (XPHB)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "22"
"hit_dice": "3d10 + 6"
"stats":
- !!int "17"
- !!int "15"
- !!int "15"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "50 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "1"
"traits":
- "desc": "The wolf has Advantage on an attack roll against a creature if at least\
    \ one of the wolf's allies is within 5 feet of the creature and the ally doesn't\
    \ have the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 8 (1d10 + 3) Piercing damage,\
    \ and the target has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone) condition\
    \ if it is Huge or smaller."
  "name": "Bite"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/beast/token/dire-wolf-xphb.webp"
```
^statblock