---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Sprite"]
---
# [Sprite](3-Mechanics\CLI\bestiary\fey/sprite-xphb.md)
*Source: Player's Handbook (2024) p. 358, Monster Manual (2024) p. 298*  

```statblock
"name": "Sprite (XPHB)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "15"
"hp": !!int "10"
"hit_dice": "4d4"
"stats":
- !!int "3"
- !!int "18"
- !!int "10"
- !!int "14"
- !!int "13"
- !!int "11"
"speed": "10 ft., fly 40 ft."
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": "Common, Elvish, Sylvan"
"cr": "1/4"
"traits":
- "desc": "The sprite casts [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)\
    \ on itself, requiring no spell components and using Charisma as the spellcasting\
    \ ability.\n\nAt will: [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)"
  "name": "Invisibility"
"actions":
- "desc": "Melee Attack: +6, reach 5 ft. Hit: 6 (1d4 + 4) Piercing damage."
  "name": "Needle Sword"
- "desc": "Ranged Attack: +6, range 40/160 ft. Hit: 1 Piercing damage, and the\
    \ target has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) condition\
    \ until the start of the sprite's next turn."
  "name": "Enchanting Bow"
- "desc": "Charisma Saving Throw: DC 10, one creature within 5 feet the sprite can\
    \ see. Celestials, Fiends, and Undead automatically fail the save. Failure:\
    \ The sprite knows the target's emotions and alignment."
  "name": "Heart Sight"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/fey/token/sprite-xphb.webp"
```
^statblock