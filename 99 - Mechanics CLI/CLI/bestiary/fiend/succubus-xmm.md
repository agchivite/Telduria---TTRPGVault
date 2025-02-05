---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
aliases: ["Succubus"]
---
# [Succubus](3-Mechanics\CLI\bestiary\fiend/succubus-xmm.md)
*Source: Monster Manual (2024) p. 303*  

```statblock
"name": "Succubus (XMM)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "8"
- !!int "17"
- !!int "13"
- !!int "15"
- !!int "12"
- !!int "20"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  "Deception": !!int "9"
  "Stealth": !!int "7"
  "Perception": !!int "5"
"damage_resistances": "cold, fire, poison, psychic"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Abyssal, Common, Infernal, telepathy 60 ft."
"cr": "4"
"traits":
- "desc": "The succubus casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 15):\n\nAt will:\
    \ [Dominate Person](3-Mechanics/CLI/spells/dominate-person-xphb.md) (level 8 version)\n\
    \n1/day: [Hypnotic Pattern](3-Mechanics/CLI/spells/hypnotic-pattern-xphb.md)"
  "name": "Spellcasting"
- "desc": "When the succubus finishes a Long Rest, it can shape-shift into an [Incubus](3-Mechanics/CLI/bestiary/fiend/incubus-xmm.md),\
    \ using that stat block instead of this one."
  "name": "Incubus Form"
"actions":
- "desc": "The succubus makes two Fiendish Touch attacks and can use Spellcasting\
    \ to cast [Dominate Person](3-Mechanics/CLI/spells/dominate-person-xphb.md). It\
    \ can replace one attack with a use of Draining Kiss."
  "name": "Multiattack"
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 6 (1d6 + 3) Psychic damage."
  "name": "Fiendish Touch"
- "desc": "Constitution Saving Throw: DC 15, one creature [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
    \ by the succubus within 5 feet. Failure: 13 (3d8) Psychic damage. Success:\
    \ Half damage. Failure or Success: The target's Hit Point maximum is reduced\
    \ by an amount equal to the damage taken."
  "name": "Draining Kiss"
"bonus_actions":
- "desc": "The succubus shape-shifts to resemble a Medium or Small Humanoid or back\
    \ into its true form. Its game statistics are the same in each form, except its\
    \ Fly Speed is available only in its true form. Any equipment it's wearing or\
    \ carrying isn't transformed."
  "name": "Shape-Shift"
"source":
- "XMM"
```
^statblock