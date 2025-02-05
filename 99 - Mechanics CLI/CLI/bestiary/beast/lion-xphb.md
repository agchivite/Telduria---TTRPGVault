---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Lion"]
---
# [Lion](3-Mechanics\CLI\bestiary\beast/lion-xphb.md)
*Source: Player's Handbook (2024) p. 352, Monster Manual (2024) p. 364*  

```statblock
"name": "Lion (XPHB)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "4d10"
"stats":
- !!int "17"
- !!int "15"
- !!int "11"
- !!int "3"
- !!int "12"
- !!int "8"
"speed": "50 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "1"
"traits":
- "desc": "The lion has Advantage on an attack roll against a creature if at least\
    \ one of the lion's allies is within 5 feet of the creature and the ally doesn't\
    \ have the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition."
  "name": "Pack Tactics"
- "desc": "With a 10-foot running start, the lion can Long Jump up to 25 feet."
  "name": "Running Leap"
"actions":
- "desc": "The lion makes two Rend attacks. It can replace one of these attacks with\
    \ a use of Roar."
  "name": "Multiattack"
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 7 (1d8 + 3) Slashing damage."
  "name": "Rend"
- "desc": "Wisdom Saving Throw: DC 11, one creature within 15 feet. Failure: The\
    \ target has the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
    \ condition until the start of the lion's next turn."
  "name": "Roar"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/beast/token/lion-xphb.webp"
```
^statblock