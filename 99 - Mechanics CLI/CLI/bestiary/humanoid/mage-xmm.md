---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Mage"]
---
# [Mage](3-Mechanics\CLI\bestiary\humanoid/mage-xmm.md)
*Source: Monster Manual (2024) p. 199*  

```statblock
"name": "Mage (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "15"
"hp": !!int "81"
"hit_dice": "18d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "History": !!int "6"
  "Arcana": !!int "6"
"senses": "passive Perception 11"
"languages": "Common and any three languages"
"cr": "6"
"traits":
- "desc": "The mage casts one of the following spells using Intelligence as the spellcasting\
    \ ability (spell save DC 14):\n\nAt will: [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
    \ [Light](3-Mechanics/CLI/spells/light-xphb.md), [Mage Armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)\
    \ (included above), [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [Prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\
    \n1/day: [Cone of Cold](3-Mechanics/CLI/spells/cone-of-cold-xphb.md)\n\n2/day\
    \ each: [Fireball](3-Mechanics/CLI/spells/fireball-xphb.md), [Fly](3-Mechanics/CLI/spells/fly-xphb.md),\
    \ [Suggestion](3-Mechanics/CLI/spells/suggestion-xphb.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The mage makes three Arcane Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack: +6, reach 5 ft. or range 120 ft. Hit: 16\
    \ (3d10) Force damage."
  "name": "Arcane Burst"
"reactions":
- "desc": "The mage casts [Counterspell](3-Mechanics/CLI/spells/counterspell-xphb.md)\
    \ in response to that spell's trigger, using the same spellcasting ability in\
    \ Spellcasting."
  "name": "Counterspell (1/Day)"
- "desc": "The mage casts [Shield](3-Mechanics/CLI/spells/shield-xphb.md) in response\
    \ to that spell's trigger, using the same spellcasting ability in Spellcasting."
  "name": "Shield (2/Day)"
"source":
- "XMM"
```
^statblock