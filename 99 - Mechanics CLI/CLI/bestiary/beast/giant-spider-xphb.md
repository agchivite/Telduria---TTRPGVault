---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Giant Spider"]
---
# [Giant Spider](3-Mechanics\CLI\bestiary\beast/giant-spider-xphb.md)
*Source: Player's Handbook (2024) p. 351, Monster Manual (2024) p. 359*  

```statblock
"name": "Giant Spider (XPHB)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "26"
"hit_dice": "4d10 + 4"
"stats":
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "2"
- !!int "11"
- !!int "4"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "1"
"traits":
- "desc": "The spider can climb difficult surfaces, including along ceilings, without\
    \ needing to make an ability check."
  "name": "Spider Climb"
- "desc": "The spider ignores movement restrictions caused by webs, and it knows the\
    \ location of any other creature in contact with the same web."
  "name": "Web Walker"
"actions":
- "desc": "Melee Attack: +5 , reach 5 ft. Hit: 7 (1d8 + 3) Piercing damage plus\
    \ 7 (2d6) Poison damage."
  "name": "Bite"
- "desc": "Dexterity Saving Throw: DC 13, one creature the spider can see within\
    \ 60 feet. Failure: The target has the [Restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
    \ condition until the web is destroyed (AC 10; HP 5; Vulnerability to Fire damage;\
    \ Immunity to Poison and Psychic damage)."
  "name": "Web (Recharge 5-6)"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/beast/token/giant-spider-xphb.webp"
```
^statblock