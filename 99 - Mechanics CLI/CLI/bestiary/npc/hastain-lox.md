---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lox
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
aliases: ["Hastain"]
---
# [Hastain](3-Mechanics\CLI\bestiary\npc/hastain-lox.md)
*Source: Light of Xaryxis p. 25*  

```statblock
"name": "Hastain (LoX)"
"size": "Medium"
"type": "celestial"
"alignment": "typically  Chaotic Evil"
"ac": !!int "19"
"ac_class": "glory"
"hp": !!int "82"
"hit_dice": "15d8 + 15"
"stats":
- !!int "18"
- !!int "15"
- !!int "12"
- !!int "19"
- !!int "16"
- !!int "24"
"speed": "30 ft., swim 30 ft."
"saves":
  "Charisma": !!int "10"
  "Dexterity": !!int "5"
  "Wisdom": !!int "6"
  "Constitution": !!int "4"
"skillsaves":
  "History": !!int "7"
  "Performance": !!int "10"
  "Arcana": !!int "7"
  "Persuasion": !!int "10"
"senses": "passive Perception 13"
"languages": "Celestial, Common, Deep Speech, Draconic"
"cr": "8"
"traits":
- "desc": "Hastain casts one of the following spells, requiring no spell components\
    \ and using Charisma as the spellcasting ability (spell save DC 18):\n\nAt will:\
    \ light, mage hand, prestidigitation\n\n1/day each: mass suggestion, sending\n\
    \n2/day each: dimension door, phantasmal force"
  "name": "Spellcasting (Psionics)"
- "desc": "Hastain's Armor Class includes its Charisma modifier."
  "name": "Glory"
- "desc": "Hastain can hold its breath for 1 hour."
  "name": "Hold Breath"
- "desc": "Hastain wears a talarith."
  "name": "Special Equipment"
"actions":
- "desc": "Hastain makes two Trident attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing\
    \ damage if used with two hands to make a melee attack, plus 3 (1d6) force damage\
    \ if Hastain is wearing its talarith."
  "name": "Trident"
- "desc": "Ranged Spell Attack: +10 to hit, range 90 ft., one target. Hit: 22\
    \ (5d8) damage of a type chosen by Hastain from the following list: cold, fire,\
    \ lightning, or radiant."
  "name": "Chromatic Bolt"
- "desc": "Using its talarith, Hastain summons a duplicate of itself. The duplicate\
    \ obeys Hastain's commands and uses Hastain's statistics, except it is an unaligned\
    \ Construct that doesn't have a talarith of its own. The duplicate takes its turn\
    \ immediately after Hastain. It vanishes after 1 hour or when it is reduced to\
    \ 0 hit points."
  "name": "Summon Duplicate (Recharges after a Short or Long Rest)"
"source":
- "LoX"
"image": "3-Mechanics/CLI/bestiary/npc/token/hastain-lox.webp"
```
^statblock