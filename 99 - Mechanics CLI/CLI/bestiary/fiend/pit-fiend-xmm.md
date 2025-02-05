---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
aliases: ["Pit Fiend"]
---
# [Pit Fiend](3-Mechanics\CLI\bestiary\fiend/pit-fiend-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Pit Fiend (XMM)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "300"
"hit_dice": "24d10 + 168"
"stats":
- !!int "26"
- !!int "14"
- !!int "24"
- !!int "22"
- !!int "18"
- !!int "24"
"speed": "30 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "10"
  "Constitution": !!int "13"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"senses": "truesight 120 ft., passive Perception 14"
"languages": "Infernal, telepathy 120 ft."
"cr": "20"
"traits":
- "desc": "The pit fiend's spellcasting ability is Charisma (spell save DC 21). The\
    \ pit fiend can innately cast the following spells, requiring no material components:\n\
    \nAt will: detect magic, fireball\n\n3/day each: hold monster, wall of\
    \ fire"
  "name": "Innate Spellcasting"
- "desc": "Any creature hostile to the pit fiend that starts its turn within 20 feet\
    \ of the pit fiend must make a DC 21 Wisdom saving throw, unless the pit fiend\
    \ is incapacitated. On a failed save, the creature is frightened until the start\
    \ of its next turn. If a creature's saving throw is successful, the creature is\
    \ immune to the pit fiend's Fear Aura for the next 24 hours."
  "name": "Fear Aura"
- "desc": "The pit fiend has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The pit fiend's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "The pit fiend makes four attacks: one with its bite, one with its claw,\
    \ one with its mace, and one with its tail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 5 ft., one target. Hit: 22\
    \ (4d6 + 8) piercing damage. The target must succeed on a DC 21 Constitution\
    \ saving throw or become poisoned. While poisoned in this way, the target can't\
    \ regain hit points, and it takes 21 (6d6) poison damage at the start of each\
    \ of its turns. The poisoned target can repeat the saving throw at the end of\
    \ each of its turns, ending the effect on itself on a success."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d8 + 8) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 15\
    \ (2d6 + 8) bludgeoning damage plus 21 (6d6) fire damage."
  "name": "Mace"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 24\
    \ (3d10 + 8) bludgeoning damage."
  "name": "Tail"
"source":
- "XMM"
```
^statblock