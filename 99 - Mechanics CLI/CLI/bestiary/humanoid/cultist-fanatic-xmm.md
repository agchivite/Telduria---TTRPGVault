---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
aliases: ["Cultist Fanatic"]
---
# [Cultist Fanatic](3-Mechanics\CLI\bestiary\humanoid/cultist-fanatic-xmm.md)
*Source: Monster Manual (2024) p. 85*  

```statblock
"name": "Cultist Fanatic (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
"skillsaves":
  "Deception": !!int "3"
  "Persuasion": !!int "3"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "The fanatic casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 12):\n\nAt will: [Light](3-Mechanics/CLI/spells/light-xphb.md),\
    \ [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\n1/day: [Hold\
    \ Person](3-Mechanics/CLI/spells/hold-person-xphb.md)\n\n2/day: [Command](3-Mechanics/CLI/spells/command-xphb.md)"
  "name": "Spellcasting (Cleric)"
"actions":
- "desc": "Melee Attack: +4, reach 5 ft. Hit: 6 (1d8 + 2) Slashing damage\
    \ plus 3 (1d6) Necrotic damage."
  "name": "Pact Blade"
"bonus_actions":
- "desc": "The fanatic casts the [Spiritual Weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)\
    \ spell: +4, reach 5 feet of the spectral weapon. Hit: 6 (1d8 + 2) Force damage."
  "name": "Spiritual Weapon (2/Day)"
"source":
- "XMM"
```
^statblock