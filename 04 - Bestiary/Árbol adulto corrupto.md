---
tags:
  - FAUNA
obsidianUIMode: preview
cssclasses:
  - json5e-monster
statblock: inline
aliases:
  - Árbol adulto corrupto
---
  
  ```statblock
  
"name": "Árbol adulto corrupto"
"size": "Large"
"type": "plant"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "126"  
"hit_dice": "12d10 + 60"
"stats":
- !!int "20"
- !!int "8"
- !!int "20"
- !!int "10"
- !!int "14"
- !!int "16"
"speed": "20 ft."
"saves":
  "Constitution": !!int "8"
  "Wisdom": !!int "5"
"skillsaves":
  "Perception": !!int "5"
"damage_immunities": "poison"
"damage_resistances": "bludgeoning, piercing"
"damage_vulnerabilities": "fire"
"condition_immunities": "blinded, deafened"
"senses": "blindsight 60 ft., passive Perception 15"
"languages": "Common, Druidic, Sylvan"
"cr": "8"

"traits":
- "name": "Aura de Corrupción Menor"
  "desc": "Al inicio de cada turno del Árbol Adulto Corrupto, cada criatura a 20 pies de él debe superar una tirada de salvación de Constitución CD 15 o sufrir 5 (1d10) de daño necrótico."

- "name": "Raíces Firmes"
  "desc": "El Árbol Adulto Corrupto tiene ventaja en las tiradas de salvación contra efectos que lo empujarían o lo derribarían."

"actions":
- "name": "Ataque Múltiple"
  "desc": "El Árbol Adulto Corrupto realiza dos ataques de Golpe de Rama."

- "name": "Golpe de Rama"
  "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 14 (2d8 + 5) bludgeoning damage plus 5 (1d10) necrotic damage."

- "name": "Esporas Nocivas (Recarga 5-6)"
  "desc": "El Árbol Adulto Corrupto libera una nube de esporas en un radio de 20 pies. Cada criatura en el área debe realizar una tirada de salvación de Constitución CD 16. En caso de fallo, la criatura sufre 22 (5d8) de daño por veneno y queda envenenada durante 1 minuto. En caso de éxito, sufre la mitad del daño y no queda envenenada. Una criatura envenenada puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto sobre sí misma en caso de éxito."

- "name": "Enredaderas Corruptas (Recarga 4-6)"
  "desc": "El Árbol Adulto Corrupto anima mágicamente las enredaderas en un radio de 30 pies. El área se convierte en terreno difícil durante 1 minuto. Además, hasta tres criaturas de elección del árbol en el área deben superar una tirada de salvación de Fuerza CD 15 o quedar restringidas. Una criatura restringida puede usar su acción para hacer una prueba de Fuerza CD 15, liberándose en caso de éxito."

"reactions":
- "name": "Contraataque de Ramas"
  "desc": "Cuando el Árbol Adulto Corrupto es golpeado por un ataque cuerpo a cuerpo, puede usar su reacción para hacer un ataque de Golpe de Rama contra el atacante."

"source":
- "Telduria"

 ```
 ^statblock