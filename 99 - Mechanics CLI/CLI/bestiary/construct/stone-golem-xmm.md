---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
aliases: ["Stone Golem"]
---
# [Stone Golem](3-Mechanics\CLI\bestiary\construct/stone-golem-xmm.md)
*Source: Monster Manual (2024) p. 301*  

```statblock
"name": "Stone Golem (XMM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"hp": !!int "252"
"hit_dice": "24d10 + 120"
"stats":
- !!int "22"
- !!int "9"
- !!int "20"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, petrified, poisoned"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands Common plus two other languages but can't speak"
"cr": "10"
"traits":
- "desc": "The golem can't shape-shift."
  "name": "Immutable Form"
- "desc": "The golem has Advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The golem makes two attacks, using Slam or Force Bolt in any combination."
  "name": "Multiattack"
- "desc": "Melee Attack: +10, reach 5 ft. Hit: 15 (2d8 + 6) Bludgeoning damage\
    \ plus 9 (2d8) Force damage."
  "name": "Slam"
- "desc": "Ranged Attack: +9, range 90 ft. Hit: 26 (4d12) Force damage."
  "name": "Force Bolt"
- "desc": "The golem casts [Slow](3-Mechanics/CLI/spells/slow-xphb.md) (spell save\
    \ DC 17), requiring no spell components and using Constitution as the spellcasting\
    \ ability."
  "name": "Slow (Recharge 5-6)"
"source":
- "XMM"
```
^statblock