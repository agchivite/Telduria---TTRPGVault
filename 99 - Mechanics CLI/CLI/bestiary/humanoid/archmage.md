---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Archmage"]
---
# [Archmage](3-Mechanics\CLI\bestiary\humanoid/archmage.md)
*Source: Monster Manual p. 342, Light of Xaryxis. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Archmages are powerful (and usually quite old) spellcasters dedicated to the study of the arcane arts. Benevolent ones counsel kings and queens, while evil ones rule as tyrants and pursue lichdom. Those who are neither good nor evil sequester themselves in remote towers to practice their magic without interruption.

An archmage typically has one or more apprentice mages, and an archmage's abode has numerous magical wards and guardians to discourage interlopers.

```statblock
"name": "Archmage"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "99"
"hit_dice": "18d8 + 18"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "20"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "9"
"skillsaves":
  "History": !!int "13"
  "Arcana": !!int "13"
"damage_resistances": "damage from spells; nonmagical bludgeoning, piercing, slashing\
  \ (from stoneskin)"
"senses": "passive Perception 12"
"languages": "any six languages"
"cr": "12"
"traits":
- "desc": "The archmage is an 18th-level spellcaster. Its spellcasting ability is\
    \ Intelligence (spell save DC 17, +9 to hit with spell attacks). The archmage\
    \ can cast disguise self and invisibility at will and has the following wizard\
    \ spells prepared:\n\nAt will: disguise self, invisibility\n\nCantrips (at\
    \ will): fire bolt, light, mage hand, prestidigitation, shocking grasp\n\n1st\
    \ level (4 slots): detect magic, identify, mage armor, magic missile\n\n2nd\
    \ level (3 slots): detect thoughts, mirror image, misty step\n\n3rd level\
    \ (3 slots): counterspell, fly, lightning bolt\n\n4th level (3 slots): banishment,\
    \ fire shield, stoneskin\n\n5th level (3 slots): cone of cold, scrying, wall\
    \ of force\n\n6th level (1 slots): globe of invulnerability\n\n7th level\
    \ (1 slots): teleport\n\n8th level (1 slots): mind blank\n\n9th level\
    \ (1 slots): time stop\n\nThe archmage casts these spells on itself before\
    \ combat."
  "name": "Spellcasting"
- "desc": "The archmage has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "MM"
- "LoX"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/archmage.webp"
```
^statblock

## Environment

urban