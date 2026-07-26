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
*Base layer: Realm/Qi (before any prestige)*

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
- **Use of Insight points:** level up Insight Upgrades (below) + roll gacha for **Mark of Insight** (250 Insight/roll — see `marks-database.md`)
- **Reset effect:** cascading — resetting at the group's last layer (Soulfire) will also reset Insight

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
| Qi Focus | x7 Damage (Feature) |
| Luck Focus | x6 Beast Remnants, x2 Beast Core Chance (Feature — confirmed: **Bear**, see Other Features section below) |

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

*Note: milestone thresholds above use suffixes not yet listed in `number-suffixes.md`
("No", "Dd", "Spd") — flagged there as TBD pending confirmation of exact power-of-10. Also
worth double-checking: the "1Spd" milestone suffix looks similar to, but is not identical to,
the current Karma snapshot suffix "Spvg" — please confirm these are meant to be different
tiers and not a typo.*

---

## Other Features (Map 1):
### Bear

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
- **Beast Core usage:** *(TBD — not yet confirmed what Lesser/Greater Beast Core are used for)*

### Remnant Upgrades
*Funded by Remnant*

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
