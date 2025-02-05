---
tags:
  - FAUNA
obsidianUIMode: preview
cssclasses:
  - json5e-monster
statblock: inline
aliases:
  - Enjambre de Retoños Corrompidos
---
  
  ```statblock

"name": "Enjambre de Retoños Corrompidos"
"size": "Large"
"type": "swarm of Medium plants"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "97"  
"hit_dice": "13d10 + 26"
"stats":
- !!int "14"
- !!int "14"
- !!int "14"
- !!int "3"
- !!int "10"
- !!int "6"
"speed": "30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_vulnerabilities": "fire"
"condition_immunities": "charmed, frightened, grappled, paralyzed, petrified, prone, restrained, stunned"
"senses": "blindsight 10 ft., passive Perception 10"
"languages": "understands Druid but can't speak"
"cr": "5"

"traits":
- "name": "Enjambre"
  "desc": "El enjambre puede ocupar el espacio de otra criatura y viceversa, y el enjambre puede moverse a través de cualquier apertura lo suficientemente grande para un retoño Mediano. El enjambre no puede recuperar puntos de golpe ni ganar puntos de golpe temporales."

- "name": "Aura de Corrupción"
  "desc": "Al inicio del turno del enjambre, cada criatura en un radio de 10 pies debe superar una tirada de salvación de Constitución CD 13 o sufrir 3 (1d6) de daño de caos."

"actions":
- "name": "Zarcillos"
  "desc": "Melee Weapon Attack: +5 to hit, reach 0 ft., one creature in the swarm's space. Hit: 14 (4d6) piercing damage, or 7 (2d6) piercing damage if el enjambre tiene la mitad de sus puntos de golpe o menos. El objetivo debe superar una tirada de salvación de Constitución CD 13 o quedar corrupto hasta el final de su próximo turno."

- "name": "Esporas Corruptas (Recarga 5-6)"
  "desc": "El enjambre libera una nube de esporas en un radio de 15 pies. Cada criatura en el área debe realizar una tirada de salvación de Constitución CD 13. En caso de fallo, la criatura sufre 10 (3d6) de daño por caos y queda cegada durante 1 minuto. En caso de éxito, sufre la mitad del daño y no queda cegada. Una criatura cegada puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto sobre sí misma en caso de éxito."

"reactions":
- "name": "Dispersión Rápida"
  "desc": "Cuando el enjambre recibe daño de un ataque de área, puede usar su reacción para moverse hasta la mitad de su velocidad sin provocar ataques de oportunidad."

"source":
- "Telduria"


```
^statblock
