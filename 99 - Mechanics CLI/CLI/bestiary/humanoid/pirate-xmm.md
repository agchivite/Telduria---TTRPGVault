---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Pirate"]
---
# [Pirate](3-Mechanics\CLI\bestiary\humanoid/pirate-xmm.md)
*Source: Monster Manual (2024) p. 241*  

```statblock
"name": "Pirate (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "14"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "10"
- !!int "16"
- !!int "12"
- !!int "8"
- !!int "12"
- !!int "14"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Dexterity": !!int "5"
"senses": "passive Perception 11"
"languages": "Common plus one other language"
"cr": "1"
"actions":
- "desc": "The pirate makes two Dagger attacks. It can replace one of these attacks\
    \ with a use of Enthralling Panache."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack: +5, reach 5 ft. or range 20/60 ft. Hit: 5\
    \ (1d4 + 3) Piercing damage."
  "name": "Dagger"
- "desc": "Wisdom Saving Throw: DC 12, one creature the pirate can see within 30\
    \ feet. Failure: The target has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
    \ condition until the start of the pirate's next turn."
  "name": "Enthralling Panache"
"source":
- "XMM"
```
^statblock