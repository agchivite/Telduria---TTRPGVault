---
tags:
  - FAUNA
obsidianUIMode: preview
cssclasses:
  - json5e-monster
statblock: inline
aliases:
  - Falso Corazón de Sylvanos Corrupto
---
  
  ```statblock
  
"name": "Falso Corazón de Sylvanos Corrupto"
"size": "Large"
"type": "construct"
"alignment": "neutral evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "114"  
"hit_dice": "12d10 + 48"
"stats":
- !!int "10"
- !!int "8"
- !!int "18"
- !!int "10"
- !!int "14"
- !!int "16"
"speed": "0 ft., hover 20 ft."
"saves":
  "Constitution": !!int "7"
  "Wisdom": !!int "5"
"damage_immunities": "poison"
"damage_resistances": "necrotic, bludgeoning, piercing, and slashing from nonmagical attacks"
"condition_immunities": "charmed, exhaustion, frightened, poisoned"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "entiende Común y Silvano pero no puede hablar"
"cr": "7"

"traits":
- "name": "Aura de Corrupción"
  "desc": "Al inicio del turno de cualquier criatura que esté a 15 pies del corazón, debe realizar una tirada de salvación de Constitución CD 14. En caso de fallo, sufre 5 (1d10) de daño de caos."

"actions":
- "name": "Pulso de Caos"
  "desc": "El corazón emite un pulso de energía oscura. Cada criatura en un radio de 20 pies debe realizar una tirada de salvación de Constitución CD 14. En caso de fallo, sufre 17 (5d6) de daño caótico. En caso de éxito, sufre la mitad del daño."

- "name": "Slime de Caos (Recarga 5-6)"
  "desc": "El corazón escupe energía oscura hacia dos objetivos diferentes dentro de 30 pies. Cada objetivo debe realizar una tirada de salvación de Destreza CD 14. En caso de fallo, sufre 13 (3d6 + 3) de daño de caos y queda apresado (CD 14 para escapar). En caso de éxito, sufre la mitad del daño y no queda apresado."

- "name": "Absorción Vital"
  "desc": "El corazón elige una criatura apresada por sus tentáculos. El objetivo debe realizar una tirada de salvación de Constitución CD 14. En caso de fallo, sufre 10 (3d6) de daño de caos y el corazón recupera puntos de golpe igual a la mitad del daño causado."

"reactions":
- "name": "Pulso Defensivo"
  "desc": "Cuando el corazón recibe daño de un ataque, puede usar su reacción para forzar a todas las criaturas en un radio de 10 pies a realizar una tirada de salvación de Constitución CD 14. En caso de fallo, son empujadas 15 pies hacia atrás."

"source":
- "Telduria"

```
^statblock
