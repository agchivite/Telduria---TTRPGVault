---
tags:
  - FAUNA
obsidianUIMode: preview
cssclasses:
  - json5e-monster
statblock: inline
aliases:
  - Falso Golem de Sylvanos
---

  ```statblock
  
"name": "Falso Golem de Sylvanos"
"size": "Huge"
"type": "construct"
"alignment": "unaligned"
"ac": !!int "23"
"ac_class": "natural armor"
"hp": !!int "350"  
"stats":
- !!int "26"
- !!int "8"
- !!int "30"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "35 ft."
"saves":
  "Constitution": !!int "15"
  "Wisdom": !!int "5"
"damage_immunities": "poison, psychic; bludgeoning, piercing, and slashing from nonmagical attacks not made with adamantine weapons"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, petrified, poisoned"
"senses": "darkvision 120 ft., tremorsense 60 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "16"

"traits":
- "name": "Absorber ácido"
  "desc": "Cuando el golem es sometido a daño por ácido, en lugar de recibir daño recupera una cantidad de puntos de golpe igual al daño por ácido infligido."

- "name": "Forma inmutable"
  "desc": "El golem es inmune a cualquier hechizo o efecto que altere su forma."

- "name": "Resistencia mágica"
  "desc": "El golem tiene ventaja en las tiradas de salvación contra hechizos y otros efectos mágicos."

- "name": "Armas mágicas"
  "desc": "Los ataques de arma del golem son mágicos."

"actions":
- "name": "Golpe cercano mortal"
  "desc": "Insta muerte a criaturas con 100 puntos de vida o menos, a menos que tenga alguna habilidad que lo proteja"

- "name": "Multiataque"
  "desc": "El golem realiza tres ataques de Golpe Sísmico."

- "name": "Golpe Sísmico"
  "desc": "Ataque de arma cuerpo a cuerpo: +13 al ataque, alcance 90 pies, un objetivo. Impacto: 24 (3d10 + 8) de daño contundente. Si el objetivo es una criatura, debe superar una tirada de salvación de Constitución CD 18 o caer derribado."

- "name": "Terremoto (Recarga 5-6)"
  "desc": "El golem golpea el suelo, creando un terremoto en un radio de 60 pies. Cada criatura en el suelo en esa área debe hacer una tirada de salvación de Destreza CD 18. En caso de fallo, la criatura sufre 45 (10d8) de daño contundente y cae derribada. En caso de éxito, sufre la mitad del daño y no cae derribada. El terreno en esa área se convierte en terreno difícil hasta que sea despejado."

"legendary_actions":
- "name": "Ataque"
  "desc": "El golem realiza un ataque de Golpe Sísmico."

- "name": "Muro de Tierra (Cuesta 2 Acciones)"
  "desc": "El golem crea un muro de tierra sólida en un punto que pueda ver dentro de 120 pies. El muro tiene 30 pies de largo, 10 pies de alto y 5 pies de grosor. Dura hasta el siguiente turno del golem a menos que sea destruido antes."

- "name": "Regeneración de Tierra (Cuesta 3 Acciones)"
  "desc": "El golem recupera 40 puntos de golpe."

"source":
- "Telduria"

```
^statblock