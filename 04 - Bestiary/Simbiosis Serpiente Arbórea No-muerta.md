---
tags:
  - FAUNA
obsidianUIMode: preview
cssclasses:
  - json5e-monster
statblock: inline
aliases:
  - Simbiosis Serpiente Arbórea No-muerta
---

```statblock

"name": "Simbiosis Serpiente Arbórea No-muerta"
"size": "Huge"
"type": "undead plant"
"alignment": "Neutral Evil"
"ac": !!int "16 con ESQUELETO 21"
"ac_class": "natural armor"
"hp": !!int "31 simbiosis + 145 esqueleto" 
"stats":
- !!int "22"
- !!int "14"
- !!int "20"
- !!int "10"
- !!int "16"
- !!int "18"
"speed": "40 ft., climb 40 ft."
"saves":
  "Constitution": !!int "10"
  "Wisdom": !!int "8"
  "Charisma": !!int "9"
"skills":
  "Perception": !!int "8"
  "Stealth": !!int "7"
"damage_immunities": "poison, necrotic"
"damage_resistances": "bludgeoning, piercing, and slashing from nonmagical attacks"
"damage_vulnerabilities": "fire"
"condition_immunities": "poisoned, exhaustion, frightened, charmed"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 18"
"languages": "understands Common and Sylvan but can't speak"
"cr": "14"

"traits":
- "name": "Regeneración Necrótica"
  "desc": "La Simbiosis recupera 10 puntos de golpe al inicio de su turno si tiene al menos 1 punto de golpe y no ha recibido daño por fuego o radiante desde su último turno."

- "name": "Raíces Invasoras"
  "desc": "La Simbiosis puede moverse a través de espacios tan estrechos como 1 pulgada de ancho sin apretujarse. Además, el terreno difícil compuesto de crecimiento no mágico o escombros no le cuesta movimiento extra."

- "name": "Aura de Putrefacción"
  "desc": "Al inicio de cada turno de la Simbiosis, cada criatura a 10 pies de ella debe superar una tirada de salvación de Constitución CD 17 o sufrir 10 (3d6) de daño necrótico y quedar envenenada hasta el final de su próximo turno."

"actions":
- "name": "Ataque Múltiple"
  "desc": "La Simbiosis realiza tres ataques: dos con sus Ramas Serpenteantes y uno con su Mordisco Venenoso."

- "name": "Rama Serpenteante"
  "desc": "Melee Weapon Attack: +11 to hit, reach 15 ft., one target. Hit: 18 (2d10 + 7) bludgeoning damage plus 7 (2d6) necrotic damage. Si el objetivo es una criatura, debe superar una tirada de salvación de Fuerza CD 18 o ser arrastrado 10 pies hacia la Simbiosis y quedar apresado (escape CD 18)."

- "name": "Mordisco Venenoso"
  "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 15 (2d6 + 8) piercing damage plus 24 (7d6) poison damage. El objetivo debe realizar una tirada de salvación de Constitución CD 17. En caso de fallo, el objetivo queda envenenado durante 1 minuto y sufre 11 (2d10) de daño necrótico al inicio de cada uno de sus turnos mientras esté envenenado."

- "name": "Esporas Necróticas (Recarga 5-6)"
  "desc": "La Simbiosis libera una nube de esporas en un radio de 30 pies. Cada criatura en esa área debe realizar una tirada de salvación de Constitución CD 17. En caso de fallo, la criatura sufre 35 (10d6) de daño necrótico y queda cegada durante 1 minuto. En caso de éxito, sufre la mitad del daño y no queda cegada. Una criatura cegada puede repetir la tirada de salvación al final de cada uno de sus turnos, terminando el efecto sobre sí misma en caso de éxito."

"legendary_actions":
- "name": "Ataque de Rama"
  "desc": "La Simbiosis realiza un ataque de Rama Serpenteante."

- "name": "Movimiento Subterráneo"
  "desc": "La Simbiosis puede moverse hasta la mitad de su velocidad sin provocar ataques de oportunidad, hundiéndose parcialmente en el suelo y reemergiendo."

- "name": "Absorción de Vida (Cuesta 2 Acciones)"
  "desc": "El ESQUELETO de la Simbiosis elige una criatura apresada por ella y drena su fuerza vital. El objetivo debe realizar una tirada de salvación de Constitución CD 17. En caso de fallo, sufre 21 (6d6) de daño necrótico y la Simbiosis recupera puntos de golpe igual a la mitad del daño infligido."

"source":
- "Telduria"

```
^statblock
