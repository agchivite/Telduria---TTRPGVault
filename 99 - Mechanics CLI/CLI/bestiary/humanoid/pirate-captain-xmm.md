---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Pirate Captain"]
---
# [Pirate Captain](3-Mechanics\CLI\bestiary\humanoid/pirate-captain-xmm.md)
*Source: Monster Manual (2024) p. 242*  

```statblock
"name": "Pirate Captain (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "17"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "10"
- !!int "18"
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
  "Dexterity": !!int "7"
  "Wisdom": !!int "5"
  "Strength": !!int "3"
"skillsaves":
  "Perception": !!int "5"
  "Acrobatics": !!int "7"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "6"
"actions":
- "desc": "The pirate makes three attacks, using Rapier or Pistol in any combination."
  "name": "Multiattack"
- "desc": "Melee Attack: +7, reach 5 ft. Hit: 13 (2d8 + 4) Piercing damage,\
    \ and the pirate has Advantage on the next attack roll it makes before the end\
    \ of this turn."
  "name": "Rapier"
- "desc": "Ranged Attack: +7, range 30/90 ft. Hit: 15 (2d10 + 4) Piercing\
    \ damage."
  "name": "Pistol"
"bonus_actions":
- "desc": "Wisdom Saving Throw: DC 14, one creature the pirate can see within 30\
    \ feet. Failure: The target has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
    \ condition until the start of the pirate's next turn."
  "name": "Captain's Charm"
"reactions":
- "desc": "Trigger: The pirate is hit by a melee attack roll while holding a weapon.\
    \ Response: The pirate adds 3 to its AC against that attack, possibly causing\
    \ the attack to miss. On a miss, the pirate makes one Rapier attack against the\
    \ triggering creature."
  "name": "Riposte"
"source":
- "XMM"
```
^statblock