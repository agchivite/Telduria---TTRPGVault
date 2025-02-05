---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
aliases: ["Storm Giant"]
---
# [Storm Giant](3-Mechanics\CLI\bestiary\giant/storm-giant-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Storm Giant (XMM)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Good"
"ac": !!int "16"
"ac_class": "scale mail"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"stats":
- !!int "29"
- !!int "14"
- !!int "20"
- !!int "16"
- !!int "18"
- !!int "18"
"speed": "50 ft., swim 50 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "9"
  "Strength": !!int "14"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "14"
  "Perception": !!int "9"
  "History": !!int "8"
  "Arcana": !!int "8"
"damage_resistances": "cold"
"damage_immunities": "lightning, thunder"
"senses": "passive Perception 19"
"languages": "Common, Giant"
"cr": "13"
"traits":
- "desc": "The giant's innate spellcasting ability is Charisma (spell save DC 17).\
    \ It can innately cast the following spells, requiring no material components:\n\
    \nAt will: detect magic, feather fall, levitate, light\n\n3/day each:\
    \ control weather, water breathing"
  "name": "Innate Spellcasting"
- "desc": "The giant can breathe air and water."
  "name": "Amphibious"
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "The giant makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 30\
    \ (6d6 + 9) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +14 to hit, range 60/240 ft., one target. Hit:\
    \ 35 (4d12 + 9) bludgeoning damage."
  "name": "Rock"
- "desc": "The giant hurls a magical lightning bolt at a point it can see within 500\
    \ feet of it. Each creature within 10 feet of that point must make a DC 17 Dexterity\
    \ saving throw, taking 54 (12d8) lightning damage on a failed save, or half\
    \ as much damage on a successful one."
  "name": "Lightning Strike (Recharge 5-6)"
"source":
- "XMM"
```
^statblock