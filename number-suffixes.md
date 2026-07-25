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
