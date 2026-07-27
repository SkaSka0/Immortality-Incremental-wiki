# Marks Database

> Catalog of all Marks (permanent gacha system) and their items. Marks are not reset by any prestige layer — once obtained, they're permanent. Each Mark is tied to one prestige layer as the source of its roll currency (see `prestige-layers.md`).

Each map contains 3-4 Marks that can be accessed/rolled. Map access requirements are recorded here once known.

General format per item: **Item name → chance (Locked = "IMPOSSIBLE", can no longer be gained / actual chance = still rollable) → amount owned → boosted stat & multiplier → status (MAX / total items needed to reach MAX)**.

---

## Stats Roll (Global)
*Applies to all Marks, not specific to one Mark. Access requirement: none.*

Stats: **Luck** (lowers gacha odds), **Bulk** (items opened per roll), **Speed** (rolls per second), **Clone** (parallel roll instances), **MPS** (Marks Per Second, combined result of all stats above).

> Rule: this section keeps a full history. When new data comes in, ADD a new row below — never overwrite or delete older rows.
> **% Increase** = overall percent change vs. the immediately previous row, based on MPS (since MPS is already the combined result of all other stats). First snapshot has no prior row, so it's always `N/A`.
 
| Date | Luck | Bulk | Speed | Clone | MPS | % Increase |
|---|---|---|---|---|---|---|
| 24 Jul 2026 | x27.67K | 4.11Sp | 105.82B/s | 7 | 435.12Dc | N/A |
| 25 jul 2026 | x27.9K | 5.63Sp | 117.79B/s | 8 | 662.63Dc | +52.29% |
| 26 Jul 2026 | x42.2K | 18.08Sp | 336.86B/s | 10 | 6.09Ud | +819.02% |
| 27 Jul 2026 | x132.42K | 463.7No | 420.51T/s | 13 | 194.99Qad | +3.20×10¹²% |

*Note: since these stats are global, "Total opened" per Mark likely progresses using this same shared MPS rate, not a separate rate per Mark.*

---

## Map 1
*Access requirement: none*

### Mark of Insight
- **Currency roll:** Insight (250/roll)
- **Total opened (snapshot):** 4.05Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Dim | Locked (formerly 1/1) | 19.79M | x14.5 Luck | MAX |
| Aware | Locked (formerly 1/10) | 2.97B | x23.5 Qi, x1.75 Luck, x2.5 Insight | MAX |
| Keen | Locked | 1.26Sx | x7 Luck, x4 Insight | MAX |
| Clear | Locked | 10.19Dc | x59.5 Qi, x10 Luck, x4 Insight, x1.75 Essence | MAX |
| Piercing | 1/1.12 | 21.92Ud | x112 Qi, x11.5 Luck, x3.25 Essence | MAX |
| Deepseeing | 1/9.04 | 2.73Ud | x224.5 Qi, x5.5 Insight, x3.25 Soulfire | MAX |
| Farsight | 1/3.61K | 6.82Dc | x374.5 Qi, x20.5 Luck, x5.5 Essence | MAX |
| Truesight | 1/36.14B | 681.82Sp | x29.5 Luck, x8.5 Insight, x7 Soulfire, x2.5 Stars, x3.25 Mark Bulk | MAX |
| Omniscience | 1/27.11Ud | 1.67K | x749.5 Qi, x44.5 Luck, x14.5 Insight, x14.5 Essence, x11.5 Soulfire, x7 Remnants, x4 Mark Bulk, x2.5 Mark Luck, x4 Mark Speed | MAX |

### Mark of Essence
- **Currency roll:** Essence (100M/roll)
- **Total opened (snapshot):** 1.69Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Fragment | Locked | 18.1M | x44.5 Qi, x82 Luck | MAX |
| Shard | Locked | 6.47B | x82 Qi, x44.5 Luck, x172 Essence | MAX |
| Node | Locked | 7.75Sx | x37 Luck, x172 Insight | MAX |
| Crest | Locked | 248.06Dc | x17.5 Qi, x86.5 Luck, x32.5 Essence | MAX |
| Ruby | 1/1.07 | 9.62Ud | x59.5 Luck, x62.5 Essence | MAX |
| Nucleus | 1/14.37 | 707.41Dc | x52 Luck, x89.5 Essence, x3.25 Soulfire, x2.12 Mark Speed | MAX |
| Prism | 1/5.38K | 1.89Dc | x119.5 Qi, x14.5 Insight, x239.5 Essence, x3.25 Remnants | MAX |
| Eternal | 1/71.68B | 141.86Sp | x224.5 Qi, x37 Luck, x449.5 Essence, x8.5 Soulfire, x2.5 Stars, x2.5 Mark Bulk, x2.5 Mark Speed | MAX |
| Sanguine | 1/222.96Sxvg | 0 | *(TBD — not obtained yet)* | *(TBD)* |

### Mark of Soulfire
- **Currency roll:** Soulfire (5K/roll)
- **Total opened (snapshot):** 89.9Dc

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Mote | Locked | 276.25M | x14.5 Qi, x11.5 Essence, x2.5 Soulfire | MAX |
| Kindling | Locked | 2.09T | x16 Luck, x26.5 Insight, x5.5 Soulfire | MAX |
| Wraith | Locked | 194.63Dc | x11.5 Qi, x2.5 Karma | MAX |
| Pyre | 1/1.54 | 269.23Dc | x26.5 Luck, x14.5 Soulfire, x5.5 Remnants, x1.75 Mark Speed | MAX |
| Brand | 1/2.91 | 110.78Dc | x52 Qi, x29.5 Luck, x5.5 Karma | MAX |
| Inferno | 1/215.05 | 1.5Dc | x37 Essence, x29.5 Soulfire, x13 Remnants, x2.12 Mark Bulk | MAX |
| Everflame | 1/17.92M | 17.96Oc | x121 Qi, x44.5 Luck, x59.5 Essence, x44.5 Soulfire, x1.38 Beast Core Chance, x2.5 Mark Bulk | MAX |
| Soulnova | 1/71.68Sp | 4.49B | x271 Qi, x91 Soulfire, x2.5 Remnants, x4 Mark Bulk, x2.5 Mark Luck, x3.25 Mark Speed | MAX |

### Mark of Karma
- **Currency roll:** Karma (50/roll)
- **Total opened (snapshot):** 275.82Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Trace | Locked | 605.89M | x7 Qi, x7 Karma | MAX |
| Ledger | Locked | 167.61Sx | x7 Qi, x5.5 Soulfire, x5.5 Karma | MAX |
| Burden | Locked | 94.83Oc | x5.5 Qi, x10 Luck, x5.5 Karma | MAX |
| Mercy | Locked | 1.65Dd | x29.5 Qi, x14.5 Luck, x8.5 Karma, x2.5 Remnant | MAX |
| Balance | 1/1 | 1.2Dd | x29.5 Qi, x22 Luck, x7 Soulfire, x2.5 Karma | MAX |
| Reckoning | 1/226.83 | 5.01Ud | x56.5 Qi, x19 Luck, x23.5 Essence, x2.5 Karma | MAX |
| Samsara | 1/193.64K | 5.87Dc | x18.75K Qi, x187 Luck, x4 Karma, x4 Mark Bulk, x2.5 Mark Speed | MAX |
| Nirvana | 1/7.55M | 150.56No | x18.75K Qi, x562 Luck, x19 Karma, x4 Stars, x2.5 Mark Bulk | MAX |
| Revenge | 1/28.32Ud | 389.27B | x2 Remnant, x1.5 Damage, +2 Mark Clone | MAX |

---

## Map 2
*Access requirement: Level 150*

### Mark of Stars
*(no data yet)*

### Mark of Nebulae
*(no data yet)*

### Mark of Quasar
*(no data yet)*

---

## Map 3
*Access requirement: Level 240*

### Mark of Miasma
*(no data yet)*

### Mark of Ash
*(no item data yet)*

### Mark of Laws
*(no data yet)*

---

*Note: the Mark-per-Map grouping above has been confirmed (Map 1: Insight, Essence, Soulfire, Karma / Map 2: Stars, Nebulae, Quasar / Map 3: Miasma, Ash, Laws). Stats/item data per Mark will be sent later.*# Marks Database

> Catalog of all Marks (permanent gacha system) and their items. Marks are not reset by any prestige layer — once obtained, they're permanent. Each Mark is tied to one prestige layer as the source of its roll currency (see `prestige-layers.md`).

Each map contains 3-4 Marks that can be accessed/rolled. Map access requirements are recorded here once known.

General format per item: **Item name → chance (Locked = "IMPOSSIBLE", can no longer be gained / actual chance = still rollable) → amount owned → boosted stat & multiplier → status (MAX / total items needed to reach MAX)**.

---

## Stats Roll (Global)
*Applies to all Marks, not specific to one Mark. Access requirement: none.*

Stats: **Luck** (lowers gacha odds), **Bulk** (items opened per roll), **Speed** (rolls per second), **Clone** (parallel roll instances), **MPS** (Marks Per Second, combined result of all stats above).

> Rule: this section keeps a full history. When new data comes in, ADD a new row below — never overwrite or delete older rows.
> **% Increase** = overall percent change vs. the immediately previous row, based on MPS (since MPS is already the combined result of all other stats). First snapshot has no prior row, so it's always `N/A`.
 
| Date | Luck | Bulk | Speed | Clone | MPS | % Increase |
|---|---|---|---|---|---|---|
| 24 Jul 2026 | x27.67K | 4.11Sp | 105.82B/s | 7 | 435.12Dc | N/A |
| 25 jul 2026 | x27.9K | 5.63Sp | 117.79B/s | 8 | 662.63Dc | +52.29% |
| 26 Jul 2026 | x42.2K | 18.08Sp | 336.86B/s | 10 | 6.09Ud | +819.02% |
| 27 Jul 2026 | x132.42K | 463.7No | 420.51T/s | 13 | 194.99Qad | +3.20×10¹²% |

*Note: since these stats are global, "Total opened" per Mark likely progresses using this same shared MPS rate, not a separate rate per Mark.*

---

## Map 1
*Access requirement: none*

### Mark of Insight
- **Currency roll:** Insight (250/roll)
- **Total opened (snapshot):** 4.05Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Dim | Locked (formerly 1/1) | 19.79M | x14.5 Luck | MAX |
| Aware | Locked (formerly 1/10) | 2.97B | x23.5 Qi, x1.75 Luck, x2.5 Insight | MAX |
| Keen | Locked | 1.26Sx | x7 Luck, x4 Insight | MAX |
| Clear | Locked | 10.19Dc | x59.5 Qi, x10 Luck, x4 Insight, x1.75 Essence | MAX |
| Piercing | 1/1.12 | 21.92Ud | x112 Qi, x11.5 Luck, x3.25 Essence | MAX |
| Deepseeing | 1/9.04 | 2.73Ud | x224.5 Qi, x5.5 Insight, x3.25 Soulfire | MAX |
| Farsight | 1/3.61K | 6.82Dc | x374.5 Qi, x20.5 Luck, x5.5 Essence | MAX |
| Truesight | 1/36.14B | 681.82Sp | x29.5 Luck, x8.5 Insight, x7 Soulfire, x2.5 Stars, x3.25 Mark Bulk | MAX |
| Omniscience | 1/27.11Ud | 1.67K | x749.5 Qi, x44.5 Luck, x14.5 Insight, x14.5 Essence, x11.5 Soulfire, x7 Remnants, x4 Mark Bulk, x2.5 Mark Luck, x4 Mark Speed | MAX |

### Mark of Essence
- **Currency roll:** Essence (100M/roll)
- **Total opened (snapshot):** 1.69Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Fragment | Locked | 18.1M | x44.5 Qi, x82 Luck | MAX |
| Shard | Locked | 6.47B | x82 Qi, x44.5 Luck, x172 Essence | MAX |
| Node | Locked | 7.75Sx | x37 Luck, x172 Insight | MAX |
| Crest | Locked | 248.06Dc | x17.5 Qi, x86.5 Luck, x32.5 Essence | MAX |
| Ruby | 1/1.07 | 9.62Ud | x59.5 Luck, x62.5 Essence | MAX |
| Nucleus | 1/14.37 | 707.41Dc | x52 Luck, x89.5 Essence, x3.25 Soulfire, x2.12 Mark Speed | MAX |
| Prism | 1/5.38K | 1.89Dc | x119.5 Qi, x14.5 Insight, x239.5 Essence, x3.25 Remnants | MAX |
| Eternal | 1/71.68B | 141.86Sp | x224.5 Qi, x37 Luck, x449.5 Essence, x8.5 Soulfire, x2.5 Stars, x2.5 Mark Bulk, x2.5 Mark Speed | MAX |
| Sanguine | 1/222.96Sxvg | 0 | *(TBD — not obtained yet)* | *(TBD)* |

### Mark of Soulfire
- **Currency roll:** Soulfire (5K/roll)
- **Total opened (snapshot):** 89.9Dc

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Mote | Locked | 276.25M | x14.5 Qi, x11.5 Essence, x2.5 Soulfire | MAX |
| Kindling | Locked | 2.09T | x16 Luck, x26.5 Insight, x5.5 Soulfire | MAX |
| Wraith | Locked | 194.63Dc | x11.5 Qi, x2.5 Karma | MAX |
| Pyre | 1/1.54 | 269.23Dc | x26.5 Luck, x14.5 Soulfire, x5.5 Remnants, x1.75 Mark Speed | MAX |
| Brand | 1/2.91 | 110.78Dc | x52 Qi, x29.5 Luck, x5.5 Karma | MAX |
| Inferno | 1/215.05 | 1.5Dc | x37 Essence, x29.5 Soulfire, x13 Remnants, x2.12 Mark Bulk | MAX |
| Everflame | 1/17.92M | 17.96Oc | x121 Qi, x44.5 Luck, x59.5 Essence, x44.5 Soulfire, x1.38 Beast Core Chance, x2.5 Mark Bulk | MAX |
| Soulnova | 1/71.68Sp | 4.49B | x271 Qi, x91 Soulfire, x2.5 Remnants, x4 Mark Bulk, x2.5 Mark Luck, x3.25 Mark Speed | MAX |

### Mark of Karma
- **Currency roll:** Karma (50/roll)
- **Total opened (snapshot):** 275.82Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Trace | Locked | 605.89M | x7 Qi, x7 Karma | MAX |
| Ledger | Locked | 167.61Sx | x7 Qi, x5.5 Soulfire, x5.5 Karma | MAX |
| Burden | Locked | 94.83Oc | x5.5 Qi, x10 Luck, x5.5 Karma | MAX |
| Mercy | Locked | 1.65Dd | x29.5 Qi, x14.5 Luck, x8.5 Karma, x2.5 Remnant | MAX |
| Balance | 1/1 | 1.2Dd | x29.5 Qi, x22 Luck, x7 Soulfire, x2.5 Karma | MAX |
| Reckoning | 1/226.83 | 5.01Ud | x56.5 Qi, x19 Luck, x23.5 Essence, x2.5 Karma | MAX |
| Samsara | 1/193.64K | 5.87Dc | x18.75K Qi, x187 Luck, x4 Karma, x4 Mark Bulk, x2.5 Mark Speed | MAX |
| Nirvana | 1/7.55M | 150.56No | x18.75K Qi, x562 Luck, x19 Karma, x4 Stars, x2.5 Mark Bulk | MAX |
| Revenge | 1/28.32Ud | 389.27B | x2 Remnant, x1.5 Damage, +2 Mark Clone | MAX |

---

## Map 2
*Access requirement: Level 150*

### Mark of Stars
*(no data yet)*

### Mark of Nebulae
*(no data yet)*

### Mark of Quasar
*(no data yet)*

---

## Map 3
*Access requirement: Level 240*

### Mark of Miasma
*(no data yet)*

### Mark of Ash
*(no item data yet)*

### Mark of Laws
*(no data yet)*

---

*Note: the Mark-per-Map grouping above has been confirmed (Map 1: Insight, Essence, Soulfire, Karma / Map 2: Stars, Nebulae, Quasar / Map 3: Miasma, Ash, Laws). Stats/item data per Mark will be sent later.*# Marks Database

> Catalog of all Marks (permanent gacha system) and their items. Marks are not reset by any prestige layer — once obtained, they're permanent. Each Mark is tied to one prestige layer as the source of its roll currency (see `prestige-layers.md`).

Each map contains 3-4 Marks that can be accessed/rolled. Map access requirements are recorded here once known.

General format per item: **Item name → chance (Locked = "IMPOSSIBLE", can no longer be gained / actual chance = still rollable) → amount owned → boosted stat & multiplier → status (MAX / total items needed to reach MAX)**.

---

## Stats Roll (Global)
*Applies to all Marks, not specific to one Mark. Access requirement: none.*

Stats: **Luck** (lowers gacha odds), **Bulk** (items opened per roll), **Speed** (rolls per second), **Clone** (parallel roll instances), **MPS** (Marks Per Second, combined result of all stats above).

> Rule: this section keeps a full history. When new data comes in, ADD a new row below — never overwrite or delete older rows.
> **% Increase** = overall percent change vs. the immediately previous row, based on MPS (since MPS is already the combined result of all other stats). First snapshot has no prior row, so it's always `N/A`.
 
| Date | Luck | Bulk | Speed | Clone | MPS | % Increase |
|---|---|---|---|---|---|---|
| 24 Jul 2026 | x27.67K | 4.11Sp | 105.82B/s | 7 | 435.12Dc | N/A |
| 25 jul 2026 | x27.9K | 5.63Sp | 117.79B/s | 8 | 662.63Dc | +52.29% |
| 26 Jul 2026 | x42.2K | 18.08Sp | 336.86B/s | 10 | 6.09Ud | +819.02% |
| 27 Jul 2026 | x132.42K | 463.7No | 420.51T/s | 13 | 194.99Qad | +3.20×10¹²% |

*Note: since these stats are global, "Total opened" per Mark likely progresses using this same shared MPS rate, not a separate rate per Mark.*

---

## Map 1
*Access requirement: none*

### Mark of Insight
- **Currency roll:** Insight (250/roll)
- **Total opened (snapshot):** 4.05Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Dim | Locked (formerly 1/1) | 19.79M | x14.5 Luck | MAX |
| Aware | Locked (formerly 1/10) | 2.97B | x23.5 Qi, x1.75 Luck, x2.5 Insight | MAX |
| Keen | Locked | 1.26Sx | x7 Luck, x4 Insight | MAX |
| Clear | Locked | 10.19Dc | x59.5 Qi, x10 Luck, x4 Insight, x1.75 Essence | MAX |
| Piercing | 1/1.12 | 21.92Ud | x112 Qi, x11.5 Luck, x3.25 Essence | MAX |
| Deepseeing | 1/9.04 | 2.73Ud | x224.5 Qi, x5.5 Insight, x3.25 Soulfire | MAX |
| Farsight | 1/3.61K | 6.82Dc | x374.5 Qi, x20.5 Luck, x5.5 Essence | MAX |
| Truesight | 1/36.14B | 681.82Sp | x29.5 Luck, x8.5 Insight, x7 Soulfire, x2.5 Stars, x3.25 Mark Bulk | MAX |
| Omniscience | 1/27.11Ud | 1.67K | x749.5 Qi, x44.5 Luck, x14.5 Insight, x14.5 Essence, x11.5 Soulfire, x7 Remnants, x4 Mark Bulk, x2.5 Mark Luck, x4 Mark Speed | MAX |

### Mark of Essence
- **Currency roll:** Essence (100M/roll)
- **Total opened (snapshot):** 1.69Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Fragment | Locked | 18.1M | x44.5 Qi, x82 Luck | MAX |
| Shard | Locked | 6.47B | x82 Qi, x44.5 Luck, x172 Essence | MAX |
| Node | Locked | 7.75Sx | x37 Luck, x172 Insight | MAX |
| Crest | Locked | 248.06Dc | x17.5 Qi, x86.5 Luck, x32.5 Essence | MAX |
| Ruby | 1/1.07 | 9.62Ud | x59.5 Luck, x62.5 Essence | MAX |
| Nucleus | 1/14.37 | 707.41Dc | x52 Luck, x89.5 Essence, x3.25 Soulfire, x2.12 Mark Speed | MAX |
| Prism | 1/5.38K | 1.89Dc | x119.5 Qi, x14.5 Insight, x239.5 Essence, x3.25 Remnants | MAX |
| Eternal | 1/71.68B | 141.86Sp | x224.5 Qi, x37 Luck, x449.5 Essence, x8.5 Soulfire, x2.5 Stars, x2.5 Mark Bulk, x2.5 Mark Speed | MAX |
| Sanguine | 1/222.96Sxvg | 0 | *(TBD — not obtained yet)* | *(TBD)* |

### Mark of Soulfire
- **Currency roll:** Soulfire (5K/roll)
- **Total opened (snapshot):** 89.9Dc

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Mote | Locked | 276.25M | *(TBD)* | MAX |
| Kindling | Locked | 2.09T | *(TBD)* | MAX |
| Wraith | Locked | 194.63Dc | *(TBD)* | MAX |
| Pyre | 1/1.54 | 269.23Dc | *(TBD)* | MAX |
| Brand | 1/2.91 | 110.78Dc | *(TBD)* | MAX |
| Inferno | 1/215.05 | 1.5Dc | *(TBD)* | MAX |
| Everflame | 1/17.92M | 17.96Oc | *(TBD)* | MAX |
| Soulnova | 1/71.68Sp | 4.49B | *(TBD)* | MAX |

### Mark of Karma
- **Currency roll:** Karma (50/roll)
- **Total opened (snapshot):** 275.82Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Trace | Locked | 605.89M | x7 Qi, x7 Karma | MAX |
| Ledger | Locked | 167.61Sx | x7 Qi, x5.5 Soulfire, x5.5 Karma | MAX |
| Burden | Locked | 94.83Oc | x5.5 Qi, x10 Luck, x5.5 Karma | MAX |
| Mercy | Locked | 1.65Dd | x29.5 Qi, x14.5 Luck, x8.5 Karma, x2.5 Remnant | MAX |
| Balance | 1/1 | 1.2Dd | x29.5 Qi, x22 Luck, x7 Soulfire, x2.5 Karma | MAX |
| Reckoning | 1/226.83 | 5.01Ud | x56.5 Qi, x19 Luck, x23.5 Essence, x2.5 Karma | MAX |
| Samsara | 1/193.64K | 5.87Dc | x18.75K Qi, x187 Luck, x4 Karma, x4 Mark Bulk, x2.5 Mark Speed | MAX |
| Nirvana | 1/7.55M | 150.56No | x18.75K Qi, x562 Luck, x19 Karma, x4 Stars, x2.5 Mark Bulk | MAX |
| Revenge | 1/28.32Ud | 389.27B | x2 Remnant, x1.5 Damage, +2 Mark Clone | MAX |

---

## Map 2
*Access requirement: Level 150*

### Mark of Stars
*(no data yet)*

### Mark of Nebulae
*(no data yet)*

### Mark of Quasar
*(no data yet)*

---

## Map 3
*Access requirement: Level 240*

### Mark of Miasma
*(no data yet)*

### Mark of Ash
*(no item data yet)*

### Mark of Laws
*(no data yet)*

---

*Note: the Mark-per-Map grouping above has been confirmed (Map 1: Insight, Essence, Soulfire, Karma / Map 2: Stars, Nebulae, Quasar / Map 3: Miasma, Ash, Laws). Stats/item data per Mark will be sent later.*# Marks Database

> Catalog of all Marks (permanent gacha system) and their items. Marks are not reset by any prestige layer — once obtained, they're permanent. Each Mark is tied to one prestige layer as the source of its roll currency (see `prestige-layers.md`).

Each map contains 3-4 Marks that can be accessed/rolled. Map access requirements are recorded here once known.

General format per item: **Item name → chance (Locked = "IMPOSSIBLE", can no longer be gained / actual chance = still rollable) → amount owned → boosted stat & multiplier → status (MAX / total items needed to reach MAX)**.

---

## Stats Roll (Global)
*Applies to all Marks, not specific to one Mark. Access requirement: none.*

Stats: **Luck** (lowers gacha odds), **Bulk** (items opened per roll), **Speed** (rolls per second), **Clone** (parallel roll instances), **MPS** (Marks Per Second, combined result of all stats above).

> Rule: this section keeps a full history. When new data comes in, ADD a new row below — never overwrite or delete older rows.
> **% Increase** = overall percent change vs. the immediately previous row, based on MPS (since MPS is already the combined result of all other stats). First snapshot has no prior row, so it's always `N/A`.
 
| Date | Luck | Bulk | Speed | Clone | MPS | % Increase |
|---|---|---|---|---|---|---|
| 24 Jul 2026 | x27.67K | 4.11Sp | 105.82B/s | 7 | 435.12Dc | N/A |
| 25 jul 2026 | x27.9K | 5.63Sp | 117.79B/s | 8 | 662.63Dc | +52.29% |
| 26 Jul 2026 | x42.2K | 18.08Sp | 336.86B/s | 10 | 6.09Ud | +819.02% |
| 27 Jul 2026 | x132.42K | 463.7No | 420.51T/s | 13 | 194.99Qad | +3.20×10¹²% |

*Note: since these stats are global, "Total opened" per Mark likely progresses using this same shared MPS rate, not a separate rate per Mark.*

---

## Map 1
*Access requirement: none*

### Mark of Insight
- **Currency roll:** Insight (250/roll)
- **Total opened (snapshot):** 4.05Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Dim | Locked (formerly 1/1) | 19.79M | x14.5 Luck | MAX |
| Aware | Locked (formerly 1/10) | 2.97B | x23.5 Qi, x1.75 Luck, x2.5 Insight | MAX |
| Keen | Locked | 1.26Sx | x7 Luck, x4 Insight | MAX |
| Clear | Locked | 10.19Dc | x59.5 Qi, x10 Luck, x4 Insight, x1.75 Essence | MAX |
| Piercing | 1/1.12 | 21.92Ud | x112 Qi, x11.5 Luck, x3.25 Essence | MAX |
| Deepseeing | 1/9.04 | 2.73Ud | x224.5 Qi, x5.5 Insight, x3.25 Soulfire | MAX |
| Farsight | 1/3.61K | 6.82Dc | x374.5 Qi, x20.5 Luck, x5.5 Essence | MAX |
| Truesight | 1/36.14B | 681.82Sp | x29.5 Luck, x8.5 Insight, x7 Soulfire, x2.5 Stars, x3.25 Mark Bulk | MAX |
| Omniscience | 1/27.11Ud | 1.67K | x749.5 Qi, x44.5 Luck, x14.5 Insight, x14.5 Essence, x11.5 Soulfire, x7 Remnants, x4 Mark Bulk, x2.5 Mark Luck, x4 Mark Speed | MAX |

### Mark of Essence
- **Currency roll:** Essence (100M/roll)
- **Total opened (snapshot):** 1.69Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Fragment | Locked | 18.1M | *(TBD)* | MAX |
| Shard | Locked | 6.47B | *(TBD)* | MAX |
| Node | Locked | 7.75Sx | *(TBD)* | MAX |
| Crest | Locked | 248.06Dc | *(TBD)* | MAX |
| Ruby | 1/1.07 | 9.62Ud | *(TBD)* | MAX |
| Nucleus | 1/14.37 | 707.41Dc | *(TBD)* | MAX |
| Prism | 1/5.38K | 1.89Dc | *(TBD)* | MAX |
| Eternal | 1/71.68B | 141.86Sp | *(TBD)* | MAX |
| Sanguine | 1/222.96Sxvg | 0 | *(TBD)* | *(TBD)* |

### Mark of Soulfire
- **Currency roll:** Soulfire (5K/roll)
- **Total opened (snapshot):** 89.9Dc

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Mote | Locked | 276.25M | *(TBD)* | MAX |
| Kindling | Locked | 2.09T | *(TBD)* | MAX |
| Wraith | Locked | 194.63Dc | *(TBD)* | MAX |
| Pyre | 1/1.54 | 269.23Dc | *(TBD)* | MAX |
| Brand | 1/2.91 | 110.78Dc | *(TBD)* | MAX |
| Inferno | 1/215.05 | 1.5Dc | *(TBD)* | MAX |
| Everflame | 1/17.92M | 17.96Oc | *(TBD)* | MAX |
| Soulnova | 1/71.68Sp | 4.49B | *(TBD)* | MAX |

### Mark of Karma
- **Currency roll:** Karma (50/roll)
- **Total opened (snapshot):** 275.82Ud

| Item | Chance | Amount owned | Stat boost | Status |
|---|---|---|---|---|
| Trace | Locked | 605.89M | x7 Qi, x7 Karma | MAX |
| Ledger | Locked | 167.61Sx | x7 Qi, x5.5 Soulfire, x5.5 Karma | MAX |
| Burden | Locked | 94.83Oc | x5.5 Qi, x10 Luck, x5.5 Karma | MAX |
| Mercy | Locked | 1.65Dd | x29.5 Qi, x14.5 Luck, x8.5 Karma, x2.5 Remnant | MAX |
| Balance | 1/1 | 1.2Dd | x29.5 Qi, x22 Luck, x7 Soulfire, x2.5 Karma | MAX |
| Reckoning | 1/226.83 | 5.01Ud | x56.5 Qi, x19 Luck, x23.5 Essence, x2.5 Karma | MAX |
| Samsara | 1/193.64K | 5.87Dc | x18.75K Qi, x187 Luck, x4 Karma, x4 Mark Bulk, x2.5 Mark Speed | MAX |
| Nirvana | 1/7.55M | 150.56No | x18.75K Qi, x562 Luck, x19 Karma, x4 Stars, x2.5 Mark Bulk | MAX |
| Revenge | 1/28.32Ud | 389.27B | x2 Remnant, x1.5 Damage, +2 Mark Clone | MAX |

---

## Map 2
*Access requirement: Level 150*

### Mark of Stars
*(no data yet)*

### Mark of Nebulae
*(no data yet)*

### Mark of Quasar
*(no data yet)*

---

## Map 3
*Access requirement: Level 240*

### Mark of Miasma
*(no data yet)*

### Mark of Ash
*(no item data yet)*

### Mark of Laws
*(no data yet)*

---

*Note: the Mark-per-Map grouping above has been confirmed (Map 1: Insight, Essence, Soulfire, Karma / Map 2: Stars, Nebulae, Quasar / Map 3: Miasma, Ash, Laws). Stats/item data per Mark will be sent later.*
