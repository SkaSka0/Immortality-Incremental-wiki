# Map 1 — Mortal Realm

> Layers: Insight → Essence → Soulfire → Karma. Base (pre-prestige) board: Qi Upgrades.
> For the Mark catalog (gacha items per layer), see `marks-database.md`.

**Access requirement:** none

Reset groups (cascading once each group completes): **Group 1 = Insight → Essence → Soulfire**
(resetting at Soulfire resets all three). The next groups are expected to follow the same
pattern, 3 layers per group — *(not yet reconfirmed for Karma onward, pattern may not stay
fixed at 3)*.

---

## Qi Upgrades
- *Base layer: Realm/Qi (before any prestige)*
- **Currency:** Qi

| Upgrade | Level (snapshot) | Effect at MAX |
|---|---|---|
| More Qi | 100/100 (MAX) | x894.34Qi Qi |
| More Luck | 100/100 (MAX) | x24.01B Luck |
| More Mark Bulk | 20/20 (MAX) | +20 Mark Bulk |

---

## Insight
*Layer 1*

- **Reset:** Realm, Qi, and Qi Upgrades → converted into **Insight** points
- **Unlock requirement:** Realm **Foundation V [#10]**
- **Example gain on reset (snapshot):** +253.94Uvg Insight
- **Use of Insight points:** level up Insight Upgrades (below) + roll gacha for **Mark of Insight**
- **Reset effect:** cascading — resetting at the group's last layer (Soulfire) will also reset Insight
- **Currency:** Insight

### Insight Upgrades

| Upgrade | Level (snapshot) | Effect at MAX |
|---|---|---|
| More Insight | 75/75 (MAX) | x1.62M Insight |
| More Qi | 75/75 (MAX) | x130K Qi |
| More Luck | 75/75 (MAX) | x18.53K Luck |
| More Mark Speed | 5/5 (MAX) | x1.5 Mark Speed |

---

## Essence
*Layer 2*

- **Reset:** *N/A*
- **Unlock requirement:** *N/A*
- **Example gain on reset:** *N/A*
- **Use of Essence points:** level up Essence Upgrades + roll gacha for **Mark of Essence**
- **Currency:** Essence

### Essence Upgrades

| Upgrade | Level (snapshot) | Effect at MAX |
|---|---|---|
| More Essence | 75/75 (MAX) | x28.43Qi Essence (currency for Essence) |
| More Upgrades | 1/1 (MAX) | Unlocks new upgrade board (Extra Upgrades) |
| Essence spawn rate | 25/25 (MAX) | 0.25s spawn time |
| Essence speed | 25/25 (MAX) | x17 Essence speed |

#### Extra Upgrades
*Unlocked via "More Upgrades" above*

| Upgrade | Level (snapshot) | Effect at MAX |
|---|---|---|
| More Luck | 75/75 (MAX) | x91.12B Luck |
| More Qi | 75/75 (MAX) | x5.95B Qi |
| More Insight | 50/50 (MAX) | x1.08K Insight |

---

## Soulfire
*Layer 3 (resetting here resets Insight + Essence + Soulfire all at once)*

- **Reset:** Soul Forging resets Realm, Qi, Insight, Essence, and their upgrades for Soulfire. Soulfire gain is based on your current Essence.
- **Unlock requirement:** 1Sx Essence
- **Example gain on reset (snapshot):** +18.32Nod Soulfire
- **Use of Soulfire points:** level up Soulfire Upgrades + roll gacha for **Mark of Soulfire** (5K Soulfire/roll — see `marks-database.md`)
- **Currency:** Soulfire

### Soulfire Upgrades

| Upgrade | Level (snapshot) | Effect at MAX |
|---|---|---|
| More Essence | 70/70 (MAX) | x5.31Qad Essence |
| More Luck | 50/50 (MAX) | x1.13Qa Luck |
| More Qi | 50/50 (MAX) | x717.9Sx Qi |
| Soulfire boosts Karma | 1/1 (MAX) | x798 Karma |
| Unlock Automations | 1/1 (MAX) | Soul automations unlocked |

### Soul Focused
*Choose one mana to activate at a time — effect differs depending on which is active*

| Focus | Effect |
|---|---|
| Essence Focus | x8 Essence, x2.75 Soulfire |
| Qi Focus | x7 Damage (Feature — confirmed: [Bear Hunt](#bear-hunt), see Other Features section below) |
| Luck Focus | x6 Beast Remnants, x2 Beast Core Chance (Feature — confirmed: [Bear Hunt](#bear-hunt), see Other Features section below) |

### Soul Automations
*Permanent — not reset by Soul Forging*

| Upgrade | Level (snapshot) | Effect at MAX |
|---|---|---|
| Auto Breakthrough | 5/5 (MAX) | +5 Base Roll Attempts/s |
| Auto Qi Upgrades | 1/1 (MAX) | Qi autobuy |
| Passive Insight | 1/1 (MAX) | Passive Insight |
| Auto Insight Upgrade | 1/1 (MAX) | Insight autobuy |
| Auto Essence Upgrades | 1/1 (MAX) | Essence autobuy |

---

## Karma
*Layer 4*

- **Mechanic:** Karma Meter — step on and hold a button to earn Karma every second while standing on it (different from the reset/convert mechanic used by Insight/Essence/Soulfire).
- **Reset:** *N/A*
- **Unlock requirement:** *N/A*
- **Example gain on reset:** *N/A*
- **Use of Karma points:** unlock **Karma Milestones** (stat boosts + feature unlocks, see table below) + roll gacha for **Mark of Karma**
- **Currency:** Karma

### Karma Milestones

| Total Karma | Stat Boosts | Status |
|---|---|---|
| 50 | x2 Karma gain, x20 Soulfire, Karma gain doubles every 10x | Unlocked |
| 250 | x250 Essence, x250 Soulfire, x1.5 Mark Speed, new Soulfire upgrade | Unlocked |
| 1K | +1 Mark Clone, x1.35 Mark Luck, x150 Soulfire | Unlocked |
| 10K | x3 Karma | Unlocked |
| 1M | x67 Luck, x67K Qi, x25 Essence, x35 Soulfire | Unlocked |
| 50B | x150 Luck, x15K Qi, x21 Soulfire | Unlocked |
| 10T | x2 Mark Bulk, +1 Realm Bulk | Unlocked |
| 50Qi | +1 Mark Clone, x250 Luck, x250 Qi | Unlocked |
| 1No | x10K Qi, x1K Nebulae | Unlocked |
| 500Dd | x3 Mark Speed, x4 Quasar, +1 Mark Clone | Unlocked |
| 1Spd | Auto Karma | Unlocked |

---

## Other Features (Map 1):

### Temper (Body Tempering)

- **Mechanic:** milestone-style system tied to **Realm level** — each tier unlocks
  automatically once the required Realm level/title is reached (not a reset/convert
  mechanic like Insight/Essence/Soulfire, and not a "hold button" mechanic like the Karma
  Meter).
- **Requirement format:** `[#level] Realm title`.

| Tier | Requirement | Boost |
|---|---|---|
| Iron | [#30] Void Refinement V | Unlock Essence Refining (unlocks **Essence**, Layer 2), x2 Luck, x3 Qi, x5 Insight |
| Bronze | [#45] Heaven Emperor V | x25 Essence, x2 Mark Bulk, x2 Mark Speed, x10 Luck, Qi Upgrade caps doubled, +1 Realm Bulk |
| Gold | [#85] Dao Ancestor V | Unlock Soulfire Refinement (unlocks **Soulfire**, Layer 3) and Bear Hunt |
| Platinum | [#100] Primordial Sovereign X | x5 Soulfire, x1.25 Beast Core Chance, x25 Qi, unlock upgrade on Beast Remnant board (Remnant Upgrades) |
| Diamond | [#110] True Immortal X | Unlock Karma Meter, x1.5 Mark Speed |
| Solar | [#170] Heavenly Myth X | x10 Stars, x2 Damage (Bear Hunt), x2 Mark Speed, x1.5 Mark Luck, x5 Nebulae |

*Note: **confirmed by user** — "Essence Refining" (Iron) and "Soulfire Refinement" (Gold)
unlock **access to the Essence/Soulfire layers themselves** (whether the feature exists/is
visible at all). This is a separate requirement from the `Unlock requirement` field listed in
each layer's own section above (e.g. Soulfire's `1Sx Essence`, Insight's `Realm Foundation V
[#10]`) — those fields specify the minimum needed to **perform the reset** on an
already-accessible layer, not to unlock the layer's existence. No conflict — both
requirements apply independently (layer must first be unlocked via Temper, then the
layer's own reset requirement must be met to actually reset).*

*Note: confirmed by user — Temper has many more tiers with cross-map boosts (e.g. Solar here
boosts Map 2's Stars/Nebulae); only the Map 1–relevant tiers/effects have been entered so far,
more to be added later as they're sent.*

---

### Bear Hunt

*Confirmed connection: the **Luck Focus** effect in Soul Focused (Soulfire section above),
"x6 Beast Remnants, x2 Beast Core Chance", boosts this feature.*

- **Mechanic:** kill bears on a stage-based track to earn **Remnant** (currency used to level
  up this feature's own upgrade board, Remnant Upgrades) and **Beast Core** items.
- **Stage ranges:**
  - Stage 1–100: **Lesser Bear** → drops **Lesser Beast Core**
  - Stage 101–200: **Greater Bear** → drops **Greater Beast Core**
  - *(TBD — whether stage range/naming continues past 200, not yet observed)*
- **Progression:** defeating 10 bears on a stage clears it and unlocks the next stage.
- **Stage Cleared timer:** when playing at your current **Highest Stage**, a countdown of
  **~60 seconds** is shown next to "Stage Cleared" — the time limit to defeat 10 bears and
  clear the stage.
- **Per-stage scaling:** each stage increases bear HP, Remnant reward, and Beast Core chance.
  Exact scaling formula is **unknown** (not derivable from data collected so far).
- **Modifiers:** Beast Core chance and Remnant gain can be boosted by other multipliers/effects
  from elsewhere in the game (e.g. Soul Focused → Luck Focus: x6 Beast Remnants, x2 Beast Core
  Chance).
- **Beast Core usage:** confirmed — **Lesser Beast Core** is the currency used for the
  **Bloodlines** feature (gacha roll cost + item upgrade cost). See [Bloodlines](#bloodlines)
  below. *(Greater Beast Core usage still TBD.)*

### Remnant Upgrades
**Currency:** Remnant

| Upgrade | Level (snapshot) | Effect at MAX |
|---|---|---|
| More Damage | 87/150 | x17.75T damage |
| Faster Hunt Strikes | 30/30 (MAX) | 0.26s attack speed interval |
| Longer Hunt Time | 25/25 (MAX) | 65s hunt time |
| More Beast Remnants | 50/50 (MAX) | x1.08K Beast Remnant |
| Apex Pursuit | 1/1 (MAX) | Qi boost based on highest beast stage |

### Stage Snapshots

| Date | Stage viewed | Bear Type | Defeated | Beast Core Chance | Highest Stage |
|---|---|---|---|---|---|
| 26 Jul 2026 | 150 | Lesser Bear | 10/10 | 9.59% | 156 |

*Note: "Stage viewed" (navigated via Previous/Next, or jump via "To 1"/"To Max") may differ
from the live "Highest Stage" — in this snapshot the viewed stage (150) is behind the actual
highest stage reached (156), so the 9.59% Beast Core Chance and 10/10 Defeated values reflect
stage 150 specifically, not necessarily the live highest stage.*

---

### Bloodlines

- **Mechanic:** gacha system with 8 items (Bloodlines), each equippable one at a time. Only
  the equipped Bloodline's effect is active. Each item can be leveled up independently
  (0/10 → 10/10 MAX), with effect strength scaling per level — exact per-level values
  *(TBD, only MAX-level effect confirmed so far, see Qilin below)*.
- **Currency:** **Lesser Beast Core** (see [Bear Hunt](#bear-hunt) above) — used for both:
  - **Roll** (gacha pull for Bloodline items) — cost seen: **5 Cores**/roll
  - **Auto** (auto-roll) — cost seen: **5 Cores** (same rate as manual Roll, per snapshot)
  - **Upgrade** (leveling up an owned Bloodline item, 0/10 → 10/10) — also funded by Lesser
    Beast Core, exact cost per level *(TBD)*
- **Roll rates (snapshot, 26 Jul 2026):**

| Item | Rate |
|---|---|
| Wolf | 45.0% |
| Serpent | 24.0% |
| Crane | 14.0% |
| Turtle | 8.0% |
| Tiger | 4.5% |
| Phoenix | 2.5% |
| Qilin | 1.4% |
| Dragon | 0.6% |

- **Item effects:** all 8 items now confirmed at MAX level (10/10) — see table below.
  Per-level scaling below MAX is still *(TBD)*, only the MAX-level effect has been recorded
  for each item so far.

| Item | Level (snapshot) | Effect (at snapshot level) | Status |
|---|---|---|---|
| Wolf | 10/10 (MAX) | x6.6 Luck | MAX |
| Serpent | 10/10 (MAX) | x6.6 Qi, x6.6 Essence | MAX |
| Crane | 10/10 (MAX) | x4.8 Mark Speed | MAX |
| Turtle | 10/10 (MAX) | x4.5 Mark Bulk, x6.6 Luck, x4.5 Karma | MAX |
| Tiger | 10/10 (MAX) | x9 Soulfire, x3.6 Mark Luck, x7.5 Essence | MAX |
| Phoenix | 10/10 (MAX) | x9 Insight, x8.4 Soulfire, x7.5 Karma | MAX |
| Qilin | 10/10 (MAX) | x4.5 W1 Stats, x5.4 Mark Bulk, x4.2 Mark Luck, x4.5 Mark Speed | MAX |
| Dragon | 10/10 (MAX) | x6 W1 Stats, x6 Mark Bulk, x4.5 Mark Luck, x6 Mark Speed, +1 Mark Clone | Equipped, MAX |

*Note: "W1 Stats" = blanket multiplier applied to all Map 1 currencies (Insight, Essence,
Soulfire, Karma) — **confirmed by user**. General convention: `W<N> Stats` refers to a
blanket multiplier across all prestige-layer currencies belonging to Map N (e.g. `W2 Stats`
would cover Stars, Nebulae, Quasar; `W3 Stats` would cover Miasma, Ash, Laws) — this
generalization itself is *(not yet directly observed in-game for W2/W3, flagged as expected
pattern based on the confirmed W1 case)*.

---

### Hidden Providence

- **Mechanic:** a hidden, one-time-purchase feature — one item found per map so far. No
  upgrade progression (not 0/10 like Bloodlines); each item is a single purchase (0/1 → 1/1
  MAX). Effect is fixed at MAX, no per-level scaling.
- **Currency:** each item's cost uses a **different map's own currency**, not necessarily the
  map it's found in — **confirmed by user**: the item found in Map 1 costs **Stars** (Map 2's
  layer-1 currency), and a separate item (found in Map 4, name/location TBD — see note below)
  costs **Divinity** (Map 4's currency, not yet documented elsewhere in this wiki).
- **Effect pattern (early signal, not yet confirmed as fixed rule):** effects seen so far touch
  either specific stats (Remnants, Damage, Beast Core Drop) or a blanket **all-Stats** boost
  (x1 → x2 Stats) — exact scope of "Stats" *(TBD, possibly Luck/Bulk/Speed/Clone/MPS from the
  Stats Roll (Global) system, unconfirmed)*.

| Item | Cost | Stat boost | Level |
|---|---|---|---|
| Hunter | *(TBD — Stars quantity forgotten)* Stars | x2 Remnants, x2 Damage, +1 Base Beast Core Drop | 1/1 (MAX) |
| Hegemony | 10Qa Divinity | x1 Stats → x2 Stats | 0/1 |

*Note: "Stars" (Hunter) and "Divinity" (Hegemony) are both currencies that belong to **other
maps**, not Map 1 — confirmed by user. Stars is Map 2's layer-1 currency (see
`map-2-spirit-realm.md`); Divinity is Map 4's currency, not yet documented elsewhere in this
wiki since Map 4 has no dedicated file yet. Confirmed pattern: Hidden Providence items can be
found in one map but require a currency belonging to a different map — this is new, not seen
elsewhere in the wiki (all other Mark/upgrade costs so far use only the map's own
currencies).*

---

## Suffix Breakdown (Map 1 — Theory, unconfirmed)

*Breakdown below is the user's own theory of how each Map-1-specific suffix decomposes into
Latin prefixes (per the formula in `number-suffixes.md`: Exponent = 3n + 3). Marked as
**theory**, not settled fact, until confirmed. This table is kept local to Map 1 only — it is
not merged into `number-suffixes.md`, which stays a general-purpose reference.*

| Suffix | Appears in (context) | Theorized breakdown | n (sum) | Exponent (10^x) |
|---|---|---|---|---|
| Uvg | Insight — Example gain on reset (253.94Uvg) | Un (1) + Vg (20) | 21 | 10^66 |
| Nod | Soulfire — Example gain on reset (18.32Nod) | No (9) + Dc (10) | 19 | 10^60 |
| Qad | Soulfire Upgrades — "More Essence" effect (x5.31Qad) | Qa (4) + Dc (10) | 14 | 10^45 |
| Dd | Karma Milestone threshold (500Dd) | Du (2) + Dc (10) | 12 | 10^39 |
| Spd | Karma Milestone threshold (1Spd) | Sp (7) + Dc (10) | 17 | 10^54 |
| Spvg | Referenced in Karma Milestones note (compared to Spd) | Sp (7) + Vg (20) | 27 | 10^84 |
