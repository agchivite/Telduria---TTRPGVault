```encounter
name: Encounter Name
party: Telduria´s Party
creatures:
 - 1: Goblin, 5, 5, 2
 # TO MODIFY -> 1 goblin with HP: 5, AC: 5, MOD: 2
```

```encounter-table
name: Encounter Name
party: Telduria´s Party
creatures:
 - 1: Goblin, 7, 10, 2
 # TO MODIFY -> 1 goblin with HP: 7, AC: 10, MOD: 2
---

name: Encounter Name 2
creatures:
 - 1: Thug
 - 5: Bandit
---
```

| **`dice: D6`** | **Encounter**                                |     |     |     |
| -------------- | -------------------------------------------- | --- | --- | --- |
| 1              | `encounter: 4: Kobold`                       |     |     |     |
| 2              | `encounter: 1d6: Kobold, 1d4: Winged Kobold` |     |     |     |
| 3              | Do something else                            |     |     |     |
| 4              | `encounter: 1: Lechuzo`                      |     |     |     |
|                |                                              |     |     |     |
