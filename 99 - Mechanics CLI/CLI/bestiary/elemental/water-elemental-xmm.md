---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
aliases: ["Water Elemental"]
---
# [Water Elemental](3-Mechanics\CLI\bestiary\elemental/water-elemental-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Water Elemental (XMM)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"stats":
- !!int "18"
- !!int "14"
- !!int "18"
- !!int "5"
- !!int "10"
- !!int "8"
"speed": "30 ft., swim 90 ft."
"damage_resistances": "acid; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, grappled, paralyzed, petrified, poisoned, prone,\
  \ restrained, unconscious"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Aquan"
"cr": "5"
"traits":
- "desc": "The elemental can enter a hostile creature's space and stop there. It can\
    \ move through a space as narrow as 1 inch wide without squeezing."
  "name": "Water Form"
- "desc": "If the elemental takes cold damage, it partially freezes; its speed is\
    \ reduced by 20 feet until the end of its next turn."
  "name": "Freeze"
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "The elemental makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage."
  "name": "Slam"
- "desc": "Each creature in the elemental's space must make a DC 15 Strength saving\
    \ throw. On a failure, a target takes 13 (2d8 + 4) bludgeoning damage. If it\
    \ is Large or smaller, it is also grappled (escape DC 14). Until this grapple\
    \ ends, the target is restrained and unable to breathe unless it can breathe water.\
    \ If the saving throw is successful, the target is pushed out of the elemental's\
    \ space.\n\nThe elemental can grapple one Large creature or up to two Medium or\
    \ smaller creatures at one time. At the start of each of the elemental's turns,\
    \ each target grappled by it takes 13 (2d8 + 4) bludgeoning damage. A creature\
    \ within 5 feet of the elemental can pull a creature or object out of it by taking\
    \ an action to make a DC 14 Strength check and succeeding."
  "name": "Whelm (Recharge 4-6)"
"source":
- "XMM"
```
^statblock