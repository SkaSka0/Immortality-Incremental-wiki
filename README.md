# Immortality Incremental — Wiki

A personal reference wiki for **Immortality Incremental** (Roblox), a wuxia/cultivation-themed
incremental game. Tracks upgrade boards, prestige layers, and the Marks gacha system as data is
discovered in-game.

This repo exists mainly to give the data a proper version history (via git) and a stable source
of truth that an AI assistant (Claude) can read from and edit directly.

---

## File index

| File | Contents |
|---|---|
| [`map-1-mortal-realm.md`](./map-1-mortal-realm.md) | Map 1 — Mortal Realm. Base Qi Upgrades + prestige layers Insight, Essence, Soulfire, Karma (each with its own reset info + upgrade board), plus the map's Other Features. |
| [`map-2-spirit-realm.md`](./map-2-spirit-realm.md) | Map 2 — Spirit Realm. Prestige layers Stars, Nebulae, Quasar, plus the map's Other Features. |
| [`map-3-underworld.md`](./map-3-underworld.md) | Map 3 — Underworld. Prestige layers Miasma, Ash, Laws, plus the map's Other Features. |
| [`marks-database.md`](./marks-database.md) | Catalog of all Marks (permanent gacha system) and their items, plus the global Stats Roll history (Luck/Bulk/Speed/Clone/MPS over time). Stays separate from the per-map files. |
| [`number-suffixes.md`](./number-suffixes.md) | Legend for the large-number suffix notation used across all files (K, M, B, ... up to combination suffixes like `QagCent`). |

More map files may be added later as new maps are discovered/accessed (e.g. Immortal Realm,
Infinite Forest) — this table should be kept up to date whenever a new file is introduced.

---

## Game structure (as currently understood)

- **Maps** contain multiple **prestige layers**. Each prestige layer has its own currency,
  upgrade board, and Mark. Each map file also holds one **Other Features** section (per-map
  extra mechanics), placed at the bottom of the file — details still to be filled in as it's
  explored.
- **Reset groups** cascade — resetting at the last layer of a group resets all layers in that
  group. Confirmed so far: Group 1 = Insight → Essence → Soulfire (Map 1).
- Known maps and their layers so far:
  - **Map 1 — Mortal Realm**: Insight → Essence → Soulfire → Karma
  - **Map 2 — Spirit Realm**: Stars → Nebulae → Quasar
  - **Map 3 — Underworld**: Miasma → Ash → Laws
  - **Immortal Realm**, **Infinite Forest** — map names known, but not yet reached/no layer
    data yet.
- **Marks** are permanent (not reset by prestige) and are rolled using their linked layer's
  currency.

Anything not yet confirmed in-game is marked `*(no data yet)*`, `*(TBD)*`, or explicitly flagged
as a guess — never presented as settled fact until confirmed.

---

## Data conventions

- **Numbers**: always written exactly as shown in-game, using the native suffix (K, M, B, T, Qa,
  Sx, Ud, Dc, Cent, etc.) — never converted to scientific notation. See
  [`number-suffixes.md`](./number-suffixes.md) for the full suffix legend and combination-suffix
  notes (e.g. `QagCent`-style tiers past Centillion).
- **Upgrade tables**: `| Upgrade | Level (snapshot) | Effect at MAX |`
- **Mark item tables**: `| Item | Chance | Amount owned | Stat boost | Status |`
  - `Chance` = drop odds, or `Locked` once an item can no longer be rolled.
  - `Status` = `MAX`, or the total items still needed to reach MAX.
- **Unknown data**: always kept as `*(no data yet)*` / `*(TBD)*` — rows are never deleted, so the
  structure stays ready to be filled in later.
- **Stats Roll (Global)** section in `marks-database.md` is the one exception that keeps full
  history — new snapshots are always **appended** as a new dated row, never overwritten.
- Names (Mark / layer / map) must stay identical across all files — e.g. always
  `Mark of Insight`, never `Mark Insight` or `MoInsight`.

---

## Editing rules

- Edit existing files directly rather than duplicating them.
- If new info conflicts with what's already recorded, flag it and confirm before overwriting.
- When adding a new entity (new Mark / layer / map), check whether it needs to be reflected in
  more than one file (e.g. a new Mark usually touches both `marks-database.md` and the
  relevant `map-N-name.md` file).
- Screenshots: if a value is ambiguous, cropped, blurry, or partially visible, don't guess —
  leave it as `*(TBD)*` until a clear source is available.

---

## Language

- All wiki content (headers, tables, notes) is written in **English**.
- Game-specific terms (upgrade names, Mark names, stat names) are kept exactly as they appear
  in-game — never translated or rephrased.# Immortality Incremental — Wiki

A personal reference wiki for **Immortality Incremental** (Roblox), a wuxia/cultivation-themed
incremental game. Tracks upgrade boards, prestige layers, and the Marks gacha system as data is
discovered in-game.

This repo exists mainly to give the data a proper version history (via git) and a stable source
of truth that an AI assistant (Claude) can read from and edit directly.

---

## File index

| File | Contents |
|---|---|
| [`map-1-mortal-realm.md`](./map-1-mortal-realm.md) | Map 1 — Mortal Realm. Base Qi Upgrades + prestige layers Insight, Essence, Soulfire, Karma (each with its own reset info + upgrade board), plus the map's Random Feature. |
| [`map-2-spirit-realm.md`](./map-2-spirit-realm.md) | Map 2 — Spirit Realm. Prestige layers Stars, Nebulae, Quasar, plus the map's Random Feature. |
| [`map-3-underworld.md`](./map-3-underworld.md) | Map 3 — Underworld. Prestige layers Miasma, Ash, Laws, plus the map's Random Feature. |
| [`marks-database.md`](./marks-database.md) | Catalog of all Marks (permanent gacha system) and their items, plus the global Stats Roll history (Luck/Bulk/Speed/Clone/MPS over time). Stays separate from the per-map files. |
| [`number-suffixes.md`](./number-suffixes.md) | Legend for the large-number suffix notation used across all files (K, M, B, ... up to combination suffixes like `QagCent`). |

More map files may be added later as new maps are discovered/accessed (e.g. Immortal Realm,
Infinite Forest) — this table should be kept up to date whenever a new file is introduced.

---

## Game structure (as currently understood)

- **Maps** contain multiple **prestige layers**. Each prestige layer has its own currency,
  upgrade board, and Mark. Each map file also holds one **Random Feature** section (per-map
  random mechanic), placed at the bottom of the file — details still to be filled in as it's
  explored.
- **Reset groups** cascade — resetting at the last layer of a group resets all layers in that
  group. Confirmed so far: Group 1 = Insight → Essence → Soulfire (Map 1).
- Known maps and their layers so far:
  - **Map 1 — Mortal Realm**: Insight → Essence → Soulfire → Karma
  - **Map 2 — Spirit Realm**: Stars → Nebulae → Quasar
  - **Map 3 — Underworld**: Miasma → Ash → Laws
  - **Immortal Realm**, **Infinite Forest** — map names known, but not yet reached/no layer
    data yet.
- **Marks** are permanent (not reset by prestige) and are rolled using their linked layer's
  currency.

Anything not yet confirmed in-game is marked `*(no data yet)*`, `*(TBD)*`, or explicitly flagged
as a guess — never presented as settled fact until confirmed.

---

## Data conventions

- **Numbers**: always written exactly as shown in-game, using the native suffix (K, M, B, T, Qa,
  Sx, Ud, Dc, Cent, etc.) — never converted to scientific notation. See
  [`number-suffixes.md`](./number-suffixes.md) for the full suffix legend and combination-suffix
  notes (e.g. `QagCent`-style tiers past Centillion).
- **Upgrade tables**: `| Upgrade | Level (snapshot) | Effect at MAX |`
- **Mark item tables**: `| Item | Chance | Amount owned | Stat boost | Status |`
  - `Chance` = drop odds, or `Locked` once an item can no longer be rolled.
  - `Status` = `MAX`, or the total items still needed to reach MAX.
- **Unknown data**: always kept as `*(no data yet)*` / `*(TBD)*` — rows are never deleted, so the
  structure stays ready to be filled in later.
- **Stats Roll (Global)** section in `marks-database.md` is the one exception that keeps full
  history — new snapshots are always **appended** as a new dated row, never overwritten.
- Names (Mark / layer / map) must stay identical across all files — e.g. always
  `Mark of Insight`, never `Mark Insight` or `MoInsight`.

---

## Editing rules

- Edit existing files directly rather than duplicating them.
- If new info conflicts with what's already recorded, flag it and confirm before overwriting.
- When adding a new entity (new Mark / layer / map), check whether it needs to be reflected in
  more than one file (e.g. a new Mark usually touches both `marks-database.md` and the
  relevant `map-N-name.md` file).
- Screenshots: if a value is ambiguous, cropped, blurry, or partially visible, don't guess —
  leave it as `*(TBD)*` until a clear source is available.

---

## Language

- All wiki content (headers, tables, notes) is written in **English**.
- Game-specific terms (upgrade names, Mark names, stat names) are kept exactly as they appear
  in-game — never translated or rephrased.
