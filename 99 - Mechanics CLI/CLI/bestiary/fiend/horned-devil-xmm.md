---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
aliases: ["Horned Devil"]
---
# [Horned Devil](3-Mechanics\CLI\bestiary\fiend/horned-devil-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Horned Devil (XMM)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"stats":
- !!int "22"
- !!int "17"
- !!int "21"
- !!int "12"
- !!int "16"
- !!int "17"
"speed": "20 ft., fly 60 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "7"
  "Wisdom": !!int "7"
  "Strength": !!int "10"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Infernal, telepathy 120 ft."
"cr": "11"
"traits":
- "desc": "Magical darkness doesn't impede the devil's darkvision."
  "name": "Devil's Sight"
- "desc": "The devil has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "The devil makes three melee attacks: two with its fork and one with its\
    \ tail. It can use Hurl Flame in place of any melee attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 15\
    \ (2d8 + 6) piercing damage."
  "name": "Fork"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 10\
    \ (1d8 + 6) piercing damage. If the target is a creature other than an undead\
    \ or a construct, it must succeed on a DC 17 Constitution saving throw or lose\
    \ 10 (3d6) hit points at the start of each of its turns due to an infernal wound.\
    \ Each time the devil hits the wounded target with this attack, the damage dealt\
    \ by the wound increases by 10 (3d6). Any creature can take an action to stanch\
    \ the wound with a successful DC 12 Wisdom (Medicine) check. The wound also closes\
    \ if the target receives magical healing."
  "name": "Tail"
- "desc": "Ranged Spell Attack: +7 to hit, range 150 ft., one target. Hit: 14\
    \ (4d6) fire damage. If the target is a flammable object that isn't being worn\
    \ or carried, it also catches fire."
  "name": "Hurl Flame"
"source":
- "XMM"
```
^statblock