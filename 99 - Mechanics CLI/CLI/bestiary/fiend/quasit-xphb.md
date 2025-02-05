---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
aliases: ["Quasit"]
---
# [Quasit](3-Mechanics\CLI\bestiary\fiend/quasit-xphb.md)
*Source: Player's Handbook (2024) p. 355, Monster Manual (2024) p. 252*  

```statblock
"name": "Quasit (XPHB)"
"size": "Tiny"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "25"
"hit_dice": "10d4"
"stats":
- !!int "5"
- !!int "17"
- !!int "10"
- !!int "7"
- !!int "10"
- !!int "10"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "5"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Abyssal, Common"
"cr": "1"
"traits":
- "desc": "The quasit casts [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)\
    \ on itself, requiring no spell components and using Charisma as the spellcasting\
    \ ability.\n\nAt will: [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)"
  "name": "Invisibility"
- "desc": "The quasit has Advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Attack: +5, reach 5 ft. Hit: 5 (1d4 + 3) Slashing damage,\
    \ and the target has the [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
    \ condition until the start of the quasit's next turn."
  "name": "Rend"
- "desc": "The quasit changes into a form that resembles a bat (Speed 10 ft., Fly\
    \ 40 ft.), a centipede (40 ft., Climb 40 ft.), or a toad (40 ft., Swim 40 ft.),\
    \ or it returns to its true form. Its statistics are the same in each form, except\
    \ for its Speed. Any equipment it's wearing or carrying isn't transformed. The\
    \ quasit reverts to its true form if it dies."
  "name": "Change Shape"
- "desc": "Wisdom Saving Throw: DC 10, one creature within 20 feet. Failure: The\
    \ target has the [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
    \ condition. At the end of each of its turns, the target repeats the save, ending\
    \ the effect on itself on a success. After 1 minute, it succeeds automatically"
  "name": "Scare (1/Day)"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/fiend/token/quasit-xphb.webp"
```
^statblock