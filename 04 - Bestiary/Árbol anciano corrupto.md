---
tags:
  - FAUNA
obsidianUIMode: preview
cssclasses:
  - json5e-monster
statblock: inline
aliases:
  - Árbol anciano corrupto
---
  
  ```statblock
  
"name": "Árbol anciano corrupto"
"size": "Huge"
"type": "plant"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "184"  
"hit_dice": "16d12 + 80"
"stats":
- !!int "23"
- !!int "8"
- !!int "21"
- !!int "12"
- !!int "16"
- !!int "18"
"speed": "10 ft."
"saves":
  "Constitution": !!int "9"
  "Wisdom": !!int "7"
"skillsaves":
  "Perception": !!int "7"
"damage_immunities": "poison"
"damage_resistances": "bludgeoning, piercing"
"damage_vulnerabilities": "fire"
"condition_immunities": "blinded, deafened, exhaustion"
"senses": "blindsight 120 ft., passive Perception 17"
"languages": "Common, Druidic, Sylvan"
"cr": "12"

"traits":
- "name": "Aura de Corrupción"
  "desc": "Al inicio de cada turno del Árbol Anciano Corrupto, cada criatura a 30 pies de él debe superar una tirada de salvación de Constitución CD 16 o sufrir 7 (2d6) de daño necrótico y quedar envenenada hasta el final de su próximo turno."

- "name": "Raíces Profundas"
  "desc": "El Árbol Anciano Corrupto tiene ventaja en las tiradas de salvación contra efectos que lo empujarían, derribarían o lo moverían contra su voluntad."

"actions":
- "name": "Ataque Múltiple"
  "desc": "El Árbol Anciano Corrupto realiza tres ataques de Golpe de Rama."

- "name": "Golpe de Rama"
  "desc": "Melee Weapon Attack: +10 to hit, reach 15 ft., one target. Hit: 16 (3d6 + 6) bludgeoning damage plus 7 (2d6) necrotic damage."

- "name": "Esporas Venenosas (Recarga 5-6)"
  "desc": "El Árbol Anciano Corrupto libera una nube de esporas venenosas en un radio de 30 pies. Cada criatura en el área debe realizar una tirada de salvación de Constitución CD 17. En caso de fallo, la criatura sufre 31 (7d8) de daño por veneno y queda envenenada durante 1 minuto. En caso de éxito, sufre la mitad del daño y no queda envenenada. Una criatura envenenada puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto sobre sí misma en caso de éxito."

- "name": "Invocar Enredaderas (1/día)"
  "desc": "El Árbol Anciano Corrupto anima mágicamente las enredaderas y raíces en un radio de 60 pies. El área se convierte en terreno difícil durante 1 minuto. Además, cada criatura de elección del árbol en el área cuando las enredaderas aparecen debe superar una tirada de salvación de Fuerza CD 16 o quedar restringida. Una criatura puede usar su acción para hacer una prueba de Fuerza CD 16, liberándose a sí misma o a otra criatura a su alcance en caso de éxito."

"reactions":
- "name": "Contraataque de Ramas"
  "desc": "Cuando el Árbol Adulto Corrupto es golpeado por un ataque cuerpo a cuerpo, puede usar su reacción para hacer un ataque de Golpe de Rama contra el atacante."

"legendary_actions":
- "name": "Ataque de Rama"
  "desc": "El Árbol Anciano Corrupto realiza un ataque de Golpe de Rama."

- "name": "Regeneración Corrupta (Cuesta 2 Acciones)"
  "desc": "El Árbol Anciano Corrupto recupera 20 puntos de golpe."

- "name": "Onda de Corrupción (Cuesta 3 Acciones)"
  "desc": "El Árbol Anciano Corrupto libera una onda de energía corrupta. Cada criatura en un radio de 30 pies debe realizar una tirada de salvación de Sabiduría CD 16. En caso de fallo, la criatura sufre 18 (4d8) de daño psíquico y queda asustada durante 1 minuto. Una criatura asustada puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto sobre sí misma en caso de éxito."

"source":
- "Telduria"

```
^statblock
