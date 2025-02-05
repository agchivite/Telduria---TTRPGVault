---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Shadow"]
---
# [Shadow](3-Mechanics\CLI\bestiary\undead/shadow-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Shadow (XMM)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "6"
- !!int "14"
- !!int "13"
- !!int "6"
- !!int "10"
- !!int "8"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "4"
"damage_vulnerabilities": "radiant"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "exhaustion, frightened, grappled, paralyzed, petrified, poisoned,\
  \ prone, restrained"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The shadow can move through a space as narrow as 1 inch wide without squeezing."
  "name": "Amorphous"
- "desc": "While in dim light or darkness, the shadow can take the Hide action as\
    \ a bonus action. Its stealth bonus is also improved to +6."
  "name": "Shadow Stealth"
- "desc": "While in sunlight, the shadow has disadvantage on attack rolls, ability\
    \ checks, and saving throws."
  "name": "Sunlight Weakness"
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 9\
    \ (2d6 + 2) necrotic damage, and the target's Strength score is reduced by 1d4.\
    \ The target dies if this reduces its Strength to 0. Otherwise, the reduction\
    \ lasts until the target finishes a short or long rest.\n\nIf a non-evil humanoid\
    \ dies from this attack, a new shadow rises from the corpse 1d4 hours later."
  "name": "Strength Drain"
"source":
- "XMM"
```
^statblock