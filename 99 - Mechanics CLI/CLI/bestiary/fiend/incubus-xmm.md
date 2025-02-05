---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
aliases: ["Incubus"]
---
# [Incubus](3-Mechanics\CLI\bestiary\fiend/incubus-xmm.md)
*Source: Monster Manual (2024) p. 178*  

```statblock
"name": "Incubus (XMM)"
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
- "desc": "The incubus casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 15):\n\nAt will:\
    \ [Charm Person](3-Mechanics/CLI/spells/charm-person-xphb.md), [Disguise Self](3-Mechanics/CLI/spells/disguise-self-xphb.md),\
    \ [Etherealness](3-Mechanics/CLI/spells/etherealness-xphb.md)\n\n1/day each:\
    \ [Dream](3-Mechanics/CLI/spells/dream-xphb.md), [Hypnotic Pattern](3-Mechanics/CLI/spells/hypnotic-pattern-xphb.md)"
  "name": "Spellcasting"
- "desc": "When the incubus finishes a Long Rest, it can shape-shift into a [Succubus](3-Mechanics/CLI/bestiary/fiend/succubus-xmm.md),\
    \ using that stat block instead of this one. Any equipment it's wearing or carrying\
    \ isn't transformed."
  "name": "Succubus Form"
"actions":
- "desc": "The incubus makes two Nightmare Touch attacks."
  "name": "Multiattack"
- "desc": "Melee Attack: +7, reach 5 ft. Hit: 15 (3d6 + 5) Psychic damage,\
    \ and the target is cursed for 24 hours or until the incubus dies. Until the curse\
    \ ends, the target gains no benefit from finishing Short Rests."
  "name": "Nightmare Touch"
"bonus_actions":
- "desc": "Wisdom Saving Throw: DC 15, one creature the incubus can see within 60\
    \ feet. Failure: If the target has 20 Hit Points or fewer, it has the [Unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
    \ condition for 1 hour, until it takes damage, or until a creature within 5 feet\
    \ of it takes an action to wake it. Otherwise, the target takes 18 (4d8) Psychic\
    \ damage."
  "name": "Nightmare (Recharge 6)"
"source":
- "XMM"
```
^statblock