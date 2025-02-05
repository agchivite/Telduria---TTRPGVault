---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Tiger"]
---
# [Tiger](3-Mechanics\CLI\bestiary\beast/tiger-xphb.md)
*Source: Player's Handbook (2024) p. 358, Monster Manual (2024) p. 371*  

```statblock
"name": "Tiger (XPHB)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "3d10 + 6"
"stats":
- !!int "17"
- !!int "16"
- !!int "14"
- !!int "3"
- !!int "12"
- !!int "8"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "1"
"actions":
- "desc": "The tiger makes one Pounce attack and uses Prowl."
  "name": "Multiattack"
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 6 (1d6 + 3) Slashing damage.\
    \ If the tiger had Advantage on the attack roll, the target takes an extra 3 (1d6)\
    \ Slashing damage and, if it is Huge or smaller, has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
    \ condition."
  "name": "Pounce"
- "desc": "The tiger moves up to half its Speed without provoking Opportunity Attacks.\
    \ At the end of this movement, the tiger can take the Hide action."
  "name": "Prowl"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/beast/token/tiger-xphb.webp"
```
^statblock