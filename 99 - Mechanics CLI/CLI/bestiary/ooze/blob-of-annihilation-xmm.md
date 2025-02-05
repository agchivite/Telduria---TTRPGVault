---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/ooze
statblock: inline
aliases: ["Blob of Annihilation"]
---
# [Blob of Annihilation](3-Mechanics\CLI\bestiary\ooze/blob-of-annihilation-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Blob of Annihilation (XMM)"
"size": "Huge"
"type": "ooze"
"alignment": "Typically  Lawful Evil"
"ac": !!int "16"
"hp": !!int "115"
"hit_dice": "10d12 + 50"
"stats":
- !!int "15"
- !!int "16"
- !!int "21"
- !!int "22"
- !!int "13"
- !!int "18"
"speed": "20 ft."
"saves":
  "Charisma": !!int "8"
  "Intelligence": !!int "10"
"skillsaves":
  "Nature": !!int "10"
  "Deception": !!int "8"
  "Religion": !!int "10"
  "Perception": !!int "5"
  "History": !!int "10"
  "Arcana": !!int "10"
"condition_immunities": "blinded, charmed, deafened, exhaustion, prone"
"senses": "blindsight 60 ft. (blind beyond this distance), passive Perception 15"
"languages": "Common plus six more languages"
"cr": "10"
"traits":
- "desc": "The oblex casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 18):\n\nAt\
    \ will: charm person (as 5th-level spell), detect thoughts\n\n3/day each:\
    \ dimension door, dominate person, hypnotic pattern, telekinesis"
  "name": "Spellcasting (Psionics)"
- "desc": "The oblex can move through a space as narrow as 1 inch wide without squeezing."
  "name": "Amorphous"
- "desc": "If the oblex takes fire damage, it has disadvantage on attack rolls and\
    \ ability checks until the end of its next turn."
  "name": "Aversion to Fire"
- "desc": "The oblex doesn't require sleep."
  "name": "Unusual Nature"
- "desc": "\n> [!note]\n> This statblock is a placeholder. A Blob of Annihilation\
    \ is a CR 23 Ooze."
  "name": "Temporary Statblock"
"actions":
- "desc": "The elder oblex makes two Pseudopod attacks, and it uses Eat Memories."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 17\
    \ (4d6 + 3) bludgeoning damage plus 14 (4d6) psychic damage."
  "name": "Pseudopod"
- "desc": "The oblex targets one creature it can see within 5 feet of it. The target\
    \ must succeed on a DC 18 Wisdom saving throw or take 44 (8d10) psychic damage\
    \ and become memory drained until it finishes a short or long rest or until it\
    \ benefits from the greater restoration or heal spell. Constructs, Oozes, Plants,\
    \ and Undead succeed on the save automatically.\n\nWhile memory drained, the target\
    \ must roll a d4 and subtract the number rolled from any ability check or attack\
    \ roll it makes. Each time the target is memory drained beyond the first, the\
    \ die size increases by one: the d4 becomes a d6, the d6 becomes a d8,\
    \ and so on until the die becomes a d20, at which point the target becomes unconscious\
    \ for 1 hour. The effect then ends.\n\nThe oblex learns all the languages a memory-drained\
    \ target knows and gains all its skill proficiencies."
  "name": "Eat Memories"
"bonus_actions":
- "desc": "The oblex extrudes a piece of itself that assumes the appearance of one\
    \ Medium or smaller creature whose memories it has stolen. This simulacrum appears,\
    \ feels, and sounds exactly like the creature it impersonates, though it smells\
    \ faintly of sulfur. The oblex can impersonate 2d6 + 1 different creatures,\
    \ each one tethered to its body by a strand of slime that can extend up to 120\
    \ feet away. The simulacrum is an extension of the oblex, meaning that the oblex\
    \ occupies its space and the simulacrum's space simultaneously. The tether is\
    \ immune to damage, but it is severed if there is no opening at least 1 inch wide\
    \ between the oblex and the simulacrum. The simulacrum disappears if the tether\
    \ is severed."
  "name": "Sulfurous Impersonation"
"source":
- "XMM"
```
^statblock