---
tags:
  - FAUNA
obsidianUIMode: preview
cssclasses:
  - json5e-monster
statblock: inline
aliases:
  - Serpiente Esmeralda Alfa
---
  
  ```statblock

"name": "Serpiente Esmeralda Alfa"
"size": "Huge"
"type": "beast"
"alignment": "unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "162"  
"hit_dice": "13d12 + 78"
"stats":
- !!int "19"
- !!int "17"
- !!int "19"
- !!int "4"
- !!int "14"
- !!int "12"
"speed": "50 ft., climb 50 ft., swim 50 ft."
"saves":
  "Dexterity": !!int "8"
  "Constitution": !!int "10"
"skills":
  "Perception": !!int "6"
  "Stealth": !!int "8"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "blindsight 30 ft., darkvision 60 ft., passive Perception 16"
"languages": "--"
"cr": "11"

"traits":
- "name": "Camuflaje Esmeralda"
  "desc": "La Serpiente Esmeralda tiene ventaja en las pruebas de Destreza (Sigilo) para esconderse en entornos con vegetación."

- "name": "Cuerpo Flexible"
  "desc": "La Serpiente Esmeralda puede moverse a través de un espacio tan estrecho como 5 pies de ancho sin apretujarse."

- "name": "Reflejos Sobrenaturales"
  "desc": "La Serpiente Esmeralda puede realizar una acción adicional en cada uno de sus turnos."

"actions":
- "name": "Ataque Múltiple"
  "desc": "La Serpiente Esmeralda realiza tres ataques: uno con su Mordisco, uno con su Cola y uno con sus manos"

- "name": "Mordisco"
  "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 17 (2d10 + 6) piercing damage plus 24 (7d6) poison damage. El objetivo debe realizar una tirada de salvación de Constitución CD 16. En caso de fallo, el objetivo queda envenenado durante 1 minuto. Mientras está envenenado de esta manera, el objetivo está paralizado. El objetivo puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto sobre sí mismo en caso de éxito."

- "name": "Cola/Arañazo"
  "desc": "Melee Weapon Attack: +10 to hit, reach 15 ft., one target. Hit: 15 (2d8 + 6) bludgeoning damage. Si el objetivo es una criatura, debe superar una tirada de salvación de Fuerza CD 18 o quedar derribado."

- "name": "Arañazo"
  "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 15 (2d4 + 6) piercing damage."

- "name": "Espiral Constrictora (Recarga 5-6)"
  "desc": "La Serpiente Esmeralda se enrolla rápidamente alrededor de hasta tres criaturas Grandes o más pequeñas que estén a 15 pies o menos de ella. Cada objetivo debe hacer una tirada de salvación de Destreza CD 18. En caso de fallo, una criatura sufre 21 (3d10 + 5) de daño contundente y queda apresada (escape CD 18). Hasta que este agarre termine, la criatura está restringida. La serpiente puede constricir a un máximo de tres criaturas a la vez."

- "name": "Aliento Venenoso (Recarga 5-6)"
  "desc": "La Serpiente Esmeralda exhala gas venenoso en un cono de 30 pies. Cada criatura en esa área debe hacer una tirada de salvación de Constitución CD 16, sufriendo 42 (12d6) de daño por veneno en una salvación fallida, o la mitad de daño en una exitosa."

"reactions":
- "name": "Ataque de Oportunidad Mejorado"
  "desc": "La Serpiente Esmeralda puede realizar un ataque de oportunidad cuando una criatura entra en su alcance, no solo cuando sale de él."

- "name": "Escamas Deflectoras"
  "desc": "Cuando la Serpiente Esmeralda es golpeada por un ataque, puede usar su reacción para aumentar su AC en 3 contra ese ataque. Si el ataque falla debido a este aumento, la serpiente puede hacer un ataque de mordisco contra el atacante si está dentro del alcance."

"source":
- "Telduria"

```
^statblock