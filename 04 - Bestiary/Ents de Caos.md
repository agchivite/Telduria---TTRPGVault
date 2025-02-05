---
tags:
  - FAUNA
obsidianUIMode: preview
cssclasses:
  - json5e-monster
statblock: inline
aliases:
  - Ent de Caos
---

```statblock
"name": "Ent de Caos"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor -> Chaos and Wood"
"hp": !!int "45"  
"hit_dice": "6d8 + 18"
"stats":
- !!int "16"
- !!int "12"
- !!int "16"
- !!int "10"
- !!int "10"
- !!int "16"
"speed": "0ft."
"saves":
  "Charisma": !!int "6"
  "Constitution": !!int "6"
"skillsaves":
  "Nature": !!int "8"
"damage_immunities": "chaos"
"damage_resistances": "bludgeoning, piercing, and slashing from nonmagical attacks"
"damage_vulnerabilities": "fire"
"senses": "blindsight 60 ft., darkvision 120 ft."
"languages": "Deep Speech"
"cr": "3"

"traits":
- "name": "Murmullos del Vacío"
  "desc": "Cualquier criatura hostil que comience su turno a 10 pies del Ent de Caos debe hacer una tirada de salvación de Sabiduría (DC 14). Si falla, sufrirá desventaja en su siguiente tirada de ataque y en cualquier prueba de habilidad hasta el final de su turno."

"actions":
- "name": "Burlas del Caos"
  "desc": "El Ent de Caos lanza una burla aterradora contra una criatura a 30 pies que pueda oírlo. El objetivo debe hacer una tirada de salvación de Sabiduría (DC 14). En una falla, sufre 9 (2d8) daño psíquico y tiene desventaja en sus tiradas de ataque hasta el final de su siguiente turno."

- "name": "Raíces Retorcidas (Recarga 5-6)"
  "desc": "El Ent de Caos extiende raíces anómalas en un radio de 15 pies. Cada criatura en la zona debe hacer una tirada de salvación de Destreza (DC 14) o queda **restringida** por las raíces hasta que use una acción para liberarse con una prueba de Fuerza (DC 14)."

- "name": "Golpe Caótico"
  "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13 (2d8 + 4) bludgeoning damage. Si el objetivo es una criatura, debe hacer una tirada de salvación de Sabiduría (DC 14). En una falla, entra en un estado de confusión leve y debe lanzar 1d4 en su próximo turno:\n 1-2: Actúa normalmente.\n 3: No puede moverse ni realizar acciones este turno.\n 4: Ataca a la criatura más cercana (incluyendo aliados)."

"source":
- "Telduria"
```
^statblock