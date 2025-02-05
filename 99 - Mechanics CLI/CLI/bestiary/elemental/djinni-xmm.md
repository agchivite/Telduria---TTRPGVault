---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
aliases: ["Djinni"]
---
# [Djinni](3-Mechanics\CLI\bestiary\elemental/djinni-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Djinni (XMM)"
"size": "Large"
"type": "elemental"
"alignment": "Chaotic Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "161"
"hit_dice": "14d10 + 84"
"stats":
- !!int "21"
- !!int "15"
- !!int "22"
- !!int "15"
- !!int "16"
- !!int "20"
"speed": "30 ft., fly 90 ft."
"saves":
  "Charisma": !!int "9"
  "Dexterity": !!int "6"
  "Wisdom": !!int "7"
"damage_immunities": "lightning, thunder"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Auran"
"cr": "11"
"traits":
- "desc": "The djinni's innate spellcasting ability is Charisma (spell save DC 17,\
    \ +9 to hit with spell attacks). It can innately cast the following spells,\
    \ requiring no material components:\n\nAt will: detect evil and good, detect\
    \ magic, thunderwave\n\n1/day each: conjure elemental (air elemental only),\
    \ creation, gaseous form, invisibility, major image, plane shift\n\n3/day each:\
    \ create food and water (can create wine instead of water), tongues, wind walk"
  "name": "Innate Spellcasting"
- "desc": "If the djinni dies, its body disintegrates into a warm breeze, leaving\
    \ behind only equipment the djinni was wearing or carrying."
  "name": "Elemental Demise"
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "The djinni makes three scimitar attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage plus 3 (1d6) lightning or thunder damage (djinni's\
    \ choice)."
  "name": "Scimitar"
- "desc": "A 5-foot-radius, 30-foot-tall cylinder of swirling air magically forms\
    \ on a point the djinni can see within 120 feet of it. The whirlwind lasts as\
    \ long as the djinni maintains concentration (as if concentrating on a spell).\
    \ Any creature but the djinni that enters the whirlwind must succeed on a DC 18\
    \ Strength saving throw or be restrained by it. The djinni can move the whirlwind\
    \ up to 60 feet as an action, and creatures restrained by the whirlwind move with\
    \ it. The whirlwind ends if the djinni loses sight of it.\n\nA creature can use\
    \ its action to free a creature restrained by the whirlwind, including itself,\
    \ by succeeding on a DC 18 Strength check. If the check succeeds, the creature\
    \ is no longer restrained and moves to the nearest space outside the whirlwind."
  "name": "Create Whirlwind"
"source":
- "XMM"
```
^statblock