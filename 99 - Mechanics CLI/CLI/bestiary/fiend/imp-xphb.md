---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
aliases: ["Imp"]
---
# [Imp](3-Mechanics\CLI\bestiary\fiend/imp-xphb.md)
*Source: Player's Handbook (2024) p. 352, Monster Manual (2024) p. 177*  

```statblock
"name": "Imp (XPHB)"
"size": "Tiny"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "21"
"hit_dice": "6d4 + 6"
"stats":
- !!int "6"
- !!int "17"
- !!int "13"
- !!int "11"
- !!int "12"
- !!int "14"
"speed": "20 ft., fly 40 ft."
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "5"
  "Insight": !!int "3"
"damage_resistances": "cold"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Common, Infernal"
"cr": "1"
"traits":
- "desc": "The imp casts [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)\
    \ on itself, requiring no spell components and using Charisma as the spellcasting\
    \ ability.\n\nAt will: [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)"
  "name": "Invisibility"
- "desc": "Magical Darkness doesn't impede the imp's Darkvision."
  "name": "Devil's Sight"
- "desc": "The imp has Advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 6 (1d6 + 3) Piercing damage\
    \ plus 7 (2d6) Poison damage."
  "name": "Sting"
- "desc": "The imp changes into a form that resembles a rat (Speed 20 ft.), a raven\
    \ (20 ft., Fly 60 ft.), or a spider (20 ft., Climb 20 ft.), or it returns to its\
    \ true form. Its statistics are the same in each form, except for its Speed. Any\
    \ equipment it's wearing or carrying isn't transformed. The imp reverts to its\
    \ true form if it dies."
  "name": "Change Shape"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/fiend/token/imp-xphb.webp"
```
^statblock