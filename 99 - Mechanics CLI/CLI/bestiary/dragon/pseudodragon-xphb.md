---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/dragon
statblock: inline
aliases: ["Pseudodragon"]
---
# [Pseudodragon](3-Mechanics\CLI\bestiary\dragon/pseudodragon-xphb.md)
*Source: Player's Handbook (2024) p. 354, Monster Manual (2024) p. 249*  

```statblock
"name": "Pseudodragon (XPHB)"
"size": "Tiny"
"type": "dragon"
"alignment": "Neutral Good"
"ac": !!int "14"
"hp": !!int "10"
"hit_dice": "3d4 + 3"
"stats":
- !!int "6"
- !!int "15"
- !!int "13"
- !!int "10"
- !!int "12"
- !!int "10"
"speed": "15 ft., fly 60 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 15"
"languages": "understands Common and Draconic but can't speak"
"cr": "1/4"
"traits":
- "desc": "The pseudodragon has Advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The pseudodragon makes two Bite attacks."
  "name": "Multiattack"
- "desc": "Melee Attack: +4, reach 5 ft. Hit: 4 (1d4 + 2) Piercing damage."
  "name": "Bite"
- "desc": "Constitution Saving Throw: DC 12, one creature the pseudodragon can see\
    \ within 5 feet. Failure: 5 (2d4) Poison damage, and the target has the [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
    \ condition for 1 hour. Failure by 5 or More: The [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
    \ target also has the [Unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
    \ condition until it takes damage or another creature takes an action to shake\
    \ it awake."
  "name": "Sting"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/pseudodragon-xphb.webp"
```
^statblock