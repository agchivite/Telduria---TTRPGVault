---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lmop
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
aliases: ["Nezznar the Black Spider"]
---
# [Nezznar the Black Spider](3-Mechanics\CLI\bestiary\npc/nezznar-the-black-spider-lmop.md)
*Source: Lost Mine of Phandelver p. 59*  

Drow (dark elves) are a devious, scheming subterranean race that worships Lolth, the Demon Queen of Spiders.

Drow society is strictly matriarchal. Male drow are relegated to servitor roles, and while most train as warriors, a few, such as Nezznar, become skilled wizards.

```statblock
"name": "Nezznar the Black Spider (LMoP)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "11"
"ac_class": "14 with mage armor"
"hp": !!int "27"
"hit_dice": "6d8"
"stats":
- !!int "9"
- !!int "13"
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "5"
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "4"
  "Arcana": !!int "5"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Elvish, Undercommon"
"cr": "2"
"traits":
- "desc": "Nezznar can innately cast the following spells, requiring no material components:\n\
    \nAt will: dancing lights\n\n1/day each: darkness, faerie fire (save DC\
    \ 12)"
  "name": "Innate Spellcasting"
- "desc": "Nezznar is a 4th-level spellcaster that uses Intelligence as his spellcasting\
    \ ability (spell save DC 13; +5 to hit with spell attacks). Nezznar has the\
    \ following spells prepared from the wizard's spell list:\n\nCantrips (at will):\
    \ mage hand, ray of frost, shocking grasp\n\n1st level (4 slots): mage armor,\
    \ magic missile, shield\n\n2nd level (3 slots): invisibility, suggestion"
  "name": "Spellcasting"
- "desc": "Nezznar has a [spider staff](3-Mechanics/CLI/items/spider-staff-lmop.md)."
  "name": "Special Equipment"
- "desc": "Nezznar has advantage on saving throws against being charmed, and magic\
    \ can't put him to sleep."
  "name": "Fey Ancestry"
- "desc": "Nezznar has disadvantage on attack rolls when he or his target is in sunlight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) bludgeoning damage plus 3 (1d6) poison damage."
  "name": "Spider Staff"
"source":
- "LMoP"
"image": "3-Mechanics/CLI/bestiary/npc/token/nezznar-the-black-spider-lmop.webp"
```
^statblock