# Number Suffixes Legend

> Reference for the suffix notation used on large numbers throughout this wiki (Qi, currency
> amounts, Mark item counts, upgrade effects, etc.). Numbers are always recorded using the
> game's own suffix, never converted to scientific notation.
> 
> *Note: This table follows the standard short-scale incremental convention. Where the standard notation and observed in-game naming differ slightly, both are listed using the `Standard / In-Game` format.*

---

## Suffixes List

This table contains the complete, sequential progression of large number suffixes based on the standard short-scale incremental-game numbering convention.

| Suffix | Full name | ~10^n |
|---|---|---|
| K | Thousand | 10^3 |
| M | Million | 10^6 |
| B | Billion | 10^9 |
| T | Trillion | 10^12 |
| Qa | Quadrillion | 10^15 |
| Qi | Quintillion | 10^18 |
| Sx | Sextillion | 10^21 |
| Sp | Septillion | 10^24 |
| Oc | Octillion | 10^27 |
| Nod / No | Nonillion | 10^30 |
| Dc | Decillion | 10^33 |
| Ud | Undecillion | 10^36 |
| Dd | Duodecillion | 10^39 |
| Td | Tredecillion | 10^42 |
| Qad | Quattuordecillion | 10^45 |
| Qid | Quindecillion | 10^48 |
| Sxd | Sexdecillion | 10^51 |
| Spd / SpDc | Septendecillion | 10^54 |
| Ocd | Octodecillion | 10^57 |
| Nvd / Nod | Novemdecillion | 10^60 |
| Vg | Vigintillion | 10^63 |
| Uvg | Unvigintillion | 10^66 |
| Dvg | Duovigintillion | 10^69 |
| Tvg | Tresvigintillion | 10^72 |
| Qavg | Quattuorvigintillion | 10^75 |
| Qivg | Quinvigintillion | 10^78 |
| Sxvg | Sexvigintillion | 10^81 |
| Spvg | Septenvigintillion | 10^84 |
| Ocvg | Octovigintillion | 10^87 |
| Novg | Novemvigintillion | 10^90 |
| Tg | Trigintillion | 10^93 |
| Utg | Untrigintillion | 10^96 |
| Dtg | Duotrigintillion | 10^99 |
| Cent | Centillion | 10^303 |

> **Editing rule:** this table must always be kept sorted from **smallest to largest ~10^n** — never by discovery order or alphabetically. Whenever a new suffix is inserted, re-sort the whole table by ~10^n.

---

## Combination Suffixes (beyond Cent)

Combined suffixes: **`QiQagCent`** and **`SpQagCent`** (e.g. `434.84QiQagCent/sec`, `1.81SpQagCent`).

This suggests that past Centillion, the game starts **prefixing** Cent with another suffix
(`Qag` in this case) to form a higher tier — similar to how spreadsheet columns go
`A, B, ... Z, AA, AB, ...`.

- Possible reading: `Qag` = its own suffix tier (maybe "Quadragintillion", ~10^123 in standard notation?) combined with Cent as `[prefix]Cent`, where prefix cycles through the base suffix list again (Qi, Sp, Oc, ... ) each representing a step up from Centillion.
- Need at least 2–3 more examples at different magnitudes (ideally with visible relative ordering, e.g. does `QiQagCent` come before or after `SpQagCent`?) to lock in the actual power-of-10 pattern.

**Do not use this section to infer exact values yet — flag any `...Cent` combo suffix as `*(TBD)*` until the pattern is confirmed.**

---

## Open Questions

- Full ordered list from Tg → Cent (many tiers are structurally missing from the table above due to the massive gap up to 10^303).
- Confirmed pattern for combination suffixes past Cent (see above).
