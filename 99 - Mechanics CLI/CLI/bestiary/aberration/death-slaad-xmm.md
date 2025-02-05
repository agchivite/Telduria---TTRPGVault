---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/shapechanger
statblock: inline
aliases: ["Death Slaad"]
---
# [Death Slaad](3-Mechanics\CLI\bestiary\aberration/death-slaad-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Death Slaad (XMM)"
"size": "Medium"
"type": "aberration"
"subtype": "shapechanger"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "170"
"hit_dice": "20d8 + 80"
"stats":
- !!int "20"
- !!int "15"
- !!int "19"
- !!int "15"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "8"
  "Arcana": !!int "6"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 18"
"languages": "Slaad, telepathy 60 ft."
"cr": "10"
"traits":
- "desc": "The slaad's innate spellcasting ability is Charisma (spell save DC 15,\
    \ +7 to hit with spell attacks). The slaad can innately cast the following spells,\
    \ requiring no material components:\n\nAt will: detect magic, detect thoughts,\
    \ invisibility (self only), mage hand, major image\n\n1/day each: cloudkill,\
    \ plane shift\n\n2/day each: fear, fireball, fly, tongues"
  "name": "Innate Spellcasting"
- "desc": "The slaad can use its action to polymorph into a Small or Medium humanoid,\
    \ or back into its true form. Its statistics, other than its size, are the same\
    \ in each form. Any equipment it is wearing or carrying isn't transformed. It\
    \ reverts to its true form if it dies."
  "name": "Shapechanger"
- "desc": "The slaad has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The slaad's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "The slaad regains 10 hit points at the start of its turn if it has at least\
    \ 1 hit point."
  "name": "Regeneration"
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "The slaad makes three attacks: one with its bite and two with its claws\
    \ or greatsword."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 5) piercing damage plus 7 (2d6) necrotic damage."
  "name": "Bite (Slaad Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 10\
    \ (1d10 + 5) slashing damage plus 7 (2d6) necrotic damage."
  "name": "Claws (Slaad Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage plus 7 (2d6) necrotic damage."
  "name": "Greatsword"
"source":
- "XMM"
```
^statblock