# Number Suffixes Legend

> Reference for the suffix notation used on large numbers throughout this wiki (Qi, currency
> amounts, Mark item counts, upgrade effects, etc.). Numbers are always recorded using the
> game's own suffix, never converted to scientific notation.

---

## Confirmed suffixes (seen in-game so far)

These have been directly observed in screenshots / data sent so far. Power-of-10 values below
follow the standard short-scale incremental-game numbering convention that matches the seen
suffixes, but are only marked "confirmed" for the **suffix itself**, not necessarily for the
exact power of 10 — that part is still a **guess** pending explicit confirmation.

| Suffix | Full name | ~10^n | Confirmed seen in-game? |
|---|---|---|---|
| K | Thousand | 10^3 | Yes |
| M | Million | 10^6 | Yes |
| B | Billion | 10^9 | Yes |
| T | Trillion | 10^12 | Yes |
| Qa | Quadrillion | 10^15 | Yes |
| Qi | Quintillion | 10^18 | Yes |
| Sx | Sextillion | 10^21 | Yes |
| Sp | Septillion | 10^24 | Yes |
| Oc | Octillion | 10^27 | Yes |
| Nod | Nonillion | 10^30 | Yes |
| Dc | Decillion | 10^33 | Yes |
| Ud | Undecillion | 10^36 | Yes |
| Uvg | Unvigintillion | 10^66 | Yes |
| Sxvg | Sexvigintillion | 10^81 | Yes |
| Qad | Quattuordecillion | 10^45 | Yes |
| Cent | Centillion | 10^303 | Yes |

*(Note: the jump between Ud, Uvg, Sxvg, Qad, Cent in the source data skips a lot of tiers —
those in-between tiers almost certainly exist in-game but just haven't shown up in data sent
yet. Left out of the table above rather than guessed-in.)*

---

## Unconfirmed / TBD suffixes

These have shown up in in-game data but their exact power-of-10 (and in some cases, whether
they're a real distinct tier vs. a typo/rendering issue) has not been confirmed yet.

| Suffix | Seen so far | Notes |
|---|---|---|
| No | Karma Milestone "1No" (map-1-mortal-realm.md); Stats Roll Bulk "463.7No" (27 Jul 2026); Mark of Karma item Nirvana "150.56No" (27 Jul 2026) | Seen 3 times now, likely a real tier — but unclear if same as `Nod` (Nonillion, 10^30) or a distinct suffix. Needs confirmation (e.g. a help/settings screen, or comparing raw values against a known suffix). |
| Dd | Mark of Karma items Mercy "1.65Dd" and Balance "1.2Dd" (27 Jul 2026) | Seen 2 times, same tier both times. Position in list (between Oc-tier and Ud-tier items) suggests it could sit somewhere in the 10^36–10^45 range (e.g. a Duodecillion-style tier), but this is a guess — not confirmed. |
| Dd (Karma Milestone) | "500Dd" milestone (map-1-mortal-realm.md) | Also flagged there previously — worth checking if this is the same "Dd" as above. |
| Spd | Karma Milestone "1Spd" (map-1-mortal-realm.md) | Possibly related to "Spvg" (Karma snapshot suffix) but not confirmed to be the same tier — flagged as possible typo/distinct tier, needs confirmation. |

---

## Combination suffixes (beyond Cent)

Combined suffixes: **`QiQagCent`** and **`SpQagCent`** (e.g. `434.84QiQagCent/sec`, `1.81SpQagCent`).

This suggests that past Centillion, the game starts **prefixing** Cent with another suffix
(`Qag` in this case) to form a higher tier — similar to how spreadsheet columns go
`A, B, ... Z, AA, AB, ...`.

- *(TBD — pattern not yet confirmed.)* Possible reading: `Qag` = its own suffix tier (maybe
  "Quadragintillion", ~10^123 in standard notation?) combined with Cent as `[prefix]Cent`,
  where prefix cycles through the base suffix list again (Qi, Sp, Oc, ... ) each representing
  a step up from Centillion.
- Need at least 2–3 more examples at different magnitudes (ideally with visible relative
  ordering, e.g. does `QiQagCent` come before or after `SpQagCent`?) to lock in the actual
  power-of-10 pattern.

**Do not use this section to infer exact values yet — flag any `...Cent` combo suffix as
`*(TBD)*` until the pattern is confirmed.**

---

## Open questions

- Exact power-of-10 for each suffix — currently assumed to follow the standard short-scale
  incremental-game convention (K, M, B, T, Qa, Qi, Sx, Sp, Oc, Nod, Dc, then teens like UDc/DDc,
  then Vg tier, then Tg, ... up to Cent). Not yet verified against an in-game source (e.g. a
  settings/help screen, or two values whose ratio is known).
- Full ordered list from Dc → Cent (many tiers likely missing from the table above).
- Confirmed pattern for combination suffixes past Cent (see above).
- Resolve the "No" and "Dd" suffixes in the Unconfirmed/TBD table above — both have now shown
  up multiple times and likely need their own confirmed row once verified.
