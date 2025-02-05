---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Octopus"]
---
# [Octopus](3-Mechanics\CLI\bestiary\beast/octopus-xphb.md)
*Source: Player's Handbook (2024) p. 353, Monster Manual (2024) p. 365*  

```statblock
"name": "Octopus (XPHB)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"stats":
- !!int "4"
- !!int "15"
- !!int "11"
- !!int "3"
- !!int "10"
- !!int "4"
"speed": "5 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "2"
"senses": "darkvision 30 ft., passive Perception 12"
"languages": ""
"cr": "0"
"traits":
- "desc": "The octopus can move through a space as narrow as 1 inch without spending\
    \ extra movement to do so."
  "name": "Compression"
- "desc": "The octopus can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Attack: +4, reach 5 ft. Hit: 1 Bludgeoning damage."
  "name": "Tentacles"
"reactions":
- "desc": "Trigger: A creature ends its turn within 5 feet of the octopus while underwater.\
    \ Response: The octopus releases ink that fills a 5-foot Cube centered on itself,\
    \ and the octopus moves up to its Swim Speed. The Cube is Heavily Obscured for\
    \ 1 minute or until a strong current or similar effect disperses the ink."
  "name": "Ink Cloud (1/Day)"
"source":
- "XPHB"
- "XMM"
"image": "3-Mechanics/CLI/bestiary/beast/token/octopus-xphb.webp"
```
^statblock