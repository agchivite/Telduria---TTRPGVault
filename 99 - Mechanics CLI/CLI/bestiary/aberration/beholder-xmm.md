---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
aliases: ["Beholder"]
---
# [Beholder](3-Mechanics\CLI\bestiary\aberration/beholder-xmm.md)
*Source: Monster Manual (2024)*  

```statblock
"name": "Beholder (XMM)"
"size": "Large"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "180"
"hit_dice": "19d10 + 76"
"stats":
- !!int "10"
- !!int "14"
- !!int "18"
- !!int "17"
- !!int "15"
- !!int "17"
"speed": "0 ft., fly 20 ft. (hover)"
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "7"
  "Intelligence": !!int "8"
"skillsaves":
  "Perception": !!int "12"
"condition_immunities": "prone"
"senses": "darkvision 120 ft., passive Perception 22"
"languages": "Deep Speech, Undercommon"
"cr": "13"
"traits":
- "desc": "The beholder's central eye creates an area of antimagic, as in the antimagic\
    \ field spell, in a 150-foot cone. At the start of each of its turns, the beholder\
    \ decides which way the cone faces and whether the cone is active. The area works\
    \ against the beholder's own eye rays."
  "name": "Antimagic Cone"
- "desc": "\n> [!note]\n> This statblock is a placeholder."
  "name": "Temporary Statblock"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 14\
    \ (4d6) piercing damage."
  "name": "Bite"
- "desc": "The beholder shoots three of the following magical eye rays at random (reroll\
    \ duplicates), choosing one to three targets it can see within 120 feet of it:\n\
    \n- 1. Charm Ray. The targeted creature must succeed on a DC 16 Wisdom saving\
    \ throw or be charmed by the beholder for 1 hour, or until the beholder harms\
    \ the creature.  \n- 2. Paralyzing Ray. The targeted creature must succeed\
    \ on a DC 16 Constitution saving throw or be paralyzed for 1 minute. The target\
    \ can repeat the saving throw at the end of each of its turns, ending the effect\
    \ on itself on a success.  \n- 3. Fear Ray. The targeted creature must succeed\
    \ on a DC 16 Wisdom saving throw or be frightened for 1 minute. The target can\
    \ repeat the saving throw at the end of each of its turns, ending the effect on\
    \ itself on a success.  \n- 4. Slowing Ray. The targeted creature must succeed\
    \ on a DC 16 Dexterity saving throw. On a failed save, the target's speed is halved\
    \ for 1 minute. In addition, the creature can't take reactions, and it can take\
    \ either an action or a bonus action on its turn, not both. The creature can repeat\
    \ the saving throw at the end of each of its turns, ending the effect on itself\
    \ on a success.  \n- 5. Enervation Ray. The targeted creature must make a\
    \ DC 16 Constitution saving throw, taking 36 (8d8) necrotic damage on a failed\
    \ save, or half as much damage on a successful one.  \n- 6. Telekinetic Ray.\
    \ If the target is a creature, it must succeed on a DC 16 Strength saving throw\
    \ or the beholder moves it up to 30 feet in any direction. It is restrained by\
    \ the ray's telekinetic grip until the start of the beholder's next turn or until\
    \ the beholder is incapacitated.  \n\n    If the target is an object weighing\
    \ 300 pounds or less that isn't being worn or carried, it is moved up to 30 feet\
    \ in any direction. The beholder can also exert fine control on objects with this\
    \ ray, such as manipulating a simple tool or opening a door or a container.  \n\
    - 7. Sleep Ray. The targeted creature must succeed on a DC 16 Wisdom saving\
    \ throw or fall asleep and remain unconscious for 1 minute. The target awakens\
    \ if it takes damage or another creature takes an action to wake it. This ray\
    \ has no effect on constructs and undead.  \n- 8. Petrification Ray. The targeted\
    \ creature must make a DC 16 Dexterity saving throw. On a failed save, the creature\
    \ begins to turn to stone and is restrained. It must repeat the saving throw at\
    \ the end of its next turn. On a success, the effect ends. On a failure, the creature\
    \ is petrified until freed by the  greater restoration spell or other magic. \
    \ \n- 9. Disintegration Ray. If the target is a creature, it must succeed\
    \ on a DC 16 Dexterity saving throw or take 45 (10d8) force damage. If this\
    \ damage reduces the creature to 0 hit points, its body becomes a pile of fine\
    \ gray dust.  \n\n    If the target is a Large or smaller nonmagical object or\
    \ creation of magical force, it is disintegrated without a saving throw. If the\
    \ target is a Huge or larger object or creation of magical force, this ray disintegrates\
    \ a 10-foot cube of it.  \n- 10. Death Ray. The targeted creature must succeed\
    \ on a DC 16 Dexterity saving throw or take 55 (10d10) necrotic damage. The\
    \ target dies if the ray reduces it to 0 hit points.  "
  "name": "Eye Rays"
"legendary_actions":
- "desc": "The beholder can take 3 legendary actions, using the Eye Ray option below.\
    \ It can take only one legendary action at a time and only at the end of another\
    \ creature's turn. The beholder regains spent legendary actions at the start of\
    \ its turn."
  "name": ""
- "desc": "The beholder uses one random eye ray."
  "name": "Eye Ray"
"source":
- "XMM"
```
^statblock