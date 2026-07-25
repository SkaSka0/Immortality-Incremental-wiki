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
| [`upgrades.md`](./upgrades.md) | Upgrade boards that stand alone outside any prestige layer (e.g. Qi Upgrades — the base layer before any prestige). |
| [`prestige-layers.md`](./prestige-layers.md) | Each prestige layer (currency gained from resetting) + its own upgrade board, since they always come as a pair. Also tracks reset-group cascading (e.g. Insight → Essence → Soulfire) and Map groupings. |
| [`marks-database.md`](./marks-database.md) | Catalog of all Marks (permanent gacha system) and their items, plus the global Stats Roll history (Luck/Bulk/Speed/Clone/MPS over time). |

More files may be added later (e.g. per-map random features, quests, events) — this table should
be kept up to date whenever a new file is introduced.

---

## Game structure (as currently understood)

- **Maps** contain multiple **prestige layers**. Each prestige layer has its own currency,
  upgrade board, and Mark.
- **Reset groups** cascade — resetting at the last layer of a group resets all layers in that
  group. Confirmed so far: Group 1 = Insight → Essence → Soulfire.
- Known layers so far: `Insight → Essence → Soulfire → Karma` (Map 1), `Stars → Nebulae → Quasar`
  (Map 2), `Miasma → Ash → Laws` (Map 3).
- **Marks** are permanent (not reset by prestige) and are rolled using their linked layer's
  currency.

Anything not yet confirmed in-game is marked `*(no data yet)*`, `*(TBD)*`, or explicitly flagged
as a guess — never presented as settled fact until confirmed.

---

## Data conventions

- **Numbers**: always written exactly as shown in-game, using the native suffix (K, M, B, T, Qa,
  Sx, Ud, Dc, Cent, etc.) — never converted to scientific notation.
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
  more than one file (e.g. a new Mark usually touches both `marks-database.md` and
  `prestige-layers.md`).
- Screenshots: if a value is ambiguous, cropped, blurry, or partially visible, don't guess —
  leave it as `*(TBD)*` until a clear source is available.

---

## Language

- All wiki content (headers, tables, notes) is written in **English**.
- Game-specific terms (upgrade names, Mark names, stat names) are kept exactly as they appear
  in-game — never translated or rephrased.
