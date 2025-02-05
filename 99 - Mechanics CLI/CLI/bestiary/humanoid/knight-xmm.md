---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Knight"]
---
# [Knight](3-Mechanics\CLI\bestiary\humanoid/knight-xmm.md)
*Source: Monster Manual (2024) p. 184*  

```statblock
"name": "Knight (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "11"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
"senses": "passive Perception 10"
"languages": "Common plus one other language"
"cr": "3"
"actions":
- "desc": "The knight makes two attacks, using Greatsword or Heavy Crossbow in any\
    \ combination."
  "name": "Multiattack"
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 10 (2d6 + 3) Slashing damage\
    \ plus 4 (1d8) Radiant damage."
  "name": "Greatsword"
- "desc": "Ranged Attack: +2, range 100/400 ft. Hit: 11 (2d10) Piercing damage\
    \ plus 4 (1d8) Radiant damage."
  "name": "Heavy Crossbow"
"reactions":
- "desc": "Trigger: The knight is hit by a melee attack roll while holding a weapon.\
    \ Response: The knight adds 2 to its AC against that attack, possibly causing\
    \ it to miss."
  "name": "Parry"
"source":
- "XMM"
```
^statblock