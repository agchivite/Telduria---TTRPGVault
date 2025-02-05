---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Elephant"]
---
# [Elephant](3-Mechanics\CLI\bestiary\beast/elephant-xphb.md)
*Source: Player's Handbook (2024) p. 349, Monster Manual (2024) p. 353*  

```statblock
"name": "Elephant (XPHB)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "76"
"hit_dice": "8d12 + 24"
"stats":
- !!int "22"
- !!int "9"
- !!int "17"
- !!int "3"
- !!int "11"
- !!int "6"
"speed": "40 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "4"
"actions":
- "desc": "The elephant makes two Gore attacks."
  "name": "Multiattack"
- "desc": "Melee Attack: +8, reach 5 ft. Hit: 15 (2d8 + 6) Piercing damage.\
    \ If the elephant moved at least 20 feet straight toward the target immediately\
    \ before the hit, the target also has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
    \ condition."
  "name": "Gore"
"bonus_actions":
- "desc": "Dexterity Saving Throw: DC 16, one creature within 5 feet that has the\
    \ [Prone](3-Mechanics/CLI/rules/conditions.md#Prone) condition. Failure: 17\
    \ (2d10 + 6) Bludgeoning damage. Success: Half damage."
  "name": "Trample"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/beast/token/elephant-xphb.webp"
```
^statblock