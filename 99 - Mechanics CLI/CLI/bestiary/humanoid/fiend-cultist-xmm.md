---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
aliases: ["Fiend Cultist"]
---
# [Fiend Cultist](3-Mechanics\CLI\bestiary\humanoid/fiend-cultist-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Fiend Cultist (XMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "scale mail"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "13"
- !!int "17"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "6"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "5"
  "Religion": !!int "4"
  "Insight": !!int "6"
  "Perception": !!int "6"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Elvish, Undercommon"
"cr": "8"
"traits":
- "desc": "The drow's spellcasting ability is Charisma (spell save DC 15). She can\
    \ innately cast the following spells, requiring no material components:\n\nAt\
    \ will: dancing lights\n\n1/day each: darkness, faerie fire, levitate (self\
    \ only)"
  "name": "Innate Spellcasting"
- "desc": "The drow is a 10th-level spellcaster. Her spellcasting ability is Wisdom\
    \ (save DC 14, +6 to hit with spell attacks). The drow has the following cleric\
    \ spells prepared:\n\nCantrips (at will): guidance, poison spray, resistance,\
    \ spare the dying, thaumaturgy\n\n1st level (4 slots): animal friendship,\
    \ cure wounds, detect poison and disease, ray of sickness\n\n2nd level (3 slots):\
    \ lesser restoration, protection from poison, web\n\n3rd level (3 slots):\
    \ conjure animals (2 [giant spiders](3-Mechanics/CLI/bestiary/beast/giant-spider-xphb.md)),\
    \ dispel magic\n\n4th level (3 slots): divination, freedom of movement\n\n\
    5th level (2 slots): insect plague, mass cure wounds"
  "name": "Spellcasting"
- "desc": "The drow has advantage on saving throws against being charmed, and magic\
    \ can't put the drow to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, the drow has disadvantage on attack rolls, as well as\
    \ on Wisdom (Perception) checks that rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "The drow makes two scourge attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 17 (5d6) poison damage."
  "name": "Scourge"
- "desc": "The drow attempts to magically summon a yochlol with a 30 percent chance\
    \ of success. If the attempt fails, the drow takes 5 (1d10) psychic damage.\
    \ Otherwise, the summoned demon appears in an unoccupied space within 60 feet\
    \ of its summoner, acts as an ally of its summoner, and can't summon other demons.\
    \ It remains for 10 minutes, until it or its summoner dies, or until its summoner\
    \ dismisses it as an action."
  "name": "Summon Demon (1/Day)"
"source":
- "XMM"
```
^statblock