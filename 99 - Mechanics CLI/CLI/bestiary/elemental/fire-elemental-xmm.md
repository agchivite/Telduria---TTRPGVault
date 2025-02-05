---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
aliases: ["Fire Elemental"]
---
# [Fire Elemental](3-Mechanics\CLI\bestiary\elemental/fire-elemental-xmm.md)
*Source: Monster Manual (2024) p. 118*  

```statblock
"name": "Fire Elemental (XMM)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"stats":
- !!int "10"
- !!int "17"
- !!int "16"
- !!int "6"
- !!int "10"
- !!int "7"
"speed": "50 ft."
"damage_vulnerabilities": "cold"
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "fire, poison"
"condition_immunities": "exhaustion, grappled, paralyzed, petrified, poisoned, prone,\
  \ restrained, unconscious"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Primordial (Ignan)"
"cr": "5"
"traits":
- "desc": "At the end of each of the elemental's turns, each creature in a 10-foot\
    \ Emanation originating from the elemental takes 5 (1d10) Fire damage. Creatures\
    \ and flammable objects in the Emanation start burning."
  "name": "Fiery Aura"
- "desc": "The elemental can move through a space as narrow as 1 inch wide without\
    \ expending extra movement to do so, and it can enter a creature's space and stop\
    \ there. The first time it enters a creature's space on a turn, that creature\
    \ takes 5 (1d10) Fire damage."
  "name": "Fire Form"
- "desc": "The elemental sheds Bright Light in a 30-foot radius and Dim Light for\
    \ an additional 30 feet."
  "name": "Illumination"
- "desc": "The elemental takes 3 (1d6) Cold damage for every 5 feet the elemental\
    \ moves in water or for every gallon of water splashed on it."
  "name": "Water Susceptibility"
"actions":
- "desc": "The elemental makes two Burn attacks."
  "name": "Multiattack"
- "desc": "Melee Attack: +6, reach 5 ft. Hit: 10 (2d6 + 3) Fire damage. If\
    \ the target is a creature or a flammable object, it starts burning."
  "name": "Burn"
"source":
- "XMM"
```
^statblock