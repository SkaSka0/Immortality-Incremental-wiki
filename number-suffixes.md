# Number Suffixes Legend

> Reference for the suffix notation used on large numbers throughout this wiki (Qi, currency
> amounts, Mark item counts, upgrade effects, etc.).
>
> Instead of maintaining a long, ever-growing list of every individual suffix (the list would
> get extremely long past Centillion), this file records the **short-scale naming formula**
> below, plus a Latin prefix reference table. Any suffix — no matter how high the tier — can
> be decoded/constructed on demand from this formula.

---

## Short Scale Formula

To find the exponent ($10^x$) for a name ending in **-illion**, use:

$$\text{Exponent} = 3n + 3$$

- **$n$** = the total combined index value of all Latin prefixes used (Units + Tens + Hundreds).

---

## Latin Prefix Reference Table

Combine prefixes in the order **Units + Tens + Hundreds** to form the full number name, then
sum all their $n$ values.

### 1. Units

| Prefix Name | Abbreviation | $n$ Value | Exponent (10^x) |
|---|---|---|---|
| Un | Un | 1 | 10^6 |
| Duo | Du | 2 | 10^9 |
| Tre | Tr | 3 | 10^12 |
| Quattuor | Qa | 4 | 10^15 |
| Quin | Qi | 5 | 10^18 |
| Sex | Sx | 6 | 10^21 |
| Septem | Sp | 7 | 10^24 |
| Octo | Oc | 8 | 10^27 |
| Novem | No | 9 | 10^30 |

### 2. Tens

| Prefix Name | Abbreviation | $n$ Value | Exponent (10^x) |
|---|---|---|---|
| Decillion | Dc | 10 | 10^33 |
| Vigintillion | Vg | 20 | 10^63 |
| Trigintillion | Tg | 30 | 10^93 |
| Quadragintillion | Qg | 40 | 10^123 |
| Quintagintillion | Pg | 50 | 10^153 |
| Sexagintillion | Sg | 60 | 10^183 |
| Septuagintillion | St | 70 | 10^213 |
| Octogintillion | Og | 80 | 10^243 |
| Nonagintillion | Ng | 90 | 10^273 |

### 3. Hundreds

| Prefix Name | Abbreviation | $n$ Value | Exponent (10^x) |
|---|---|---|---|
| Centillion | Ct / Cent | 100 | 10^303 |
| Ducentillion | Duc | 200 | 10^603 |
| Trecentillion | Tc | 300 | 10^903 |
| Quadringentillion | Qd | 400 | 10^1203 |
| Quingentillion | Qn | 500 | 10^1503 |
| Sescentillion | Ss | 600 | 10^1803 |
| Septingentillion | Si | 700 | 10^2103 |
| Octingentillion | Ot | 800 | 10^2403 |
| Nongentillion | Nn | 900 | 10^2703 |

---

## Worked Examples

### Example 1: Centillion (Cent)
1. Find $n$: Centillion → $n = 100$
2. Apply formula: $\text{Exponent} = 3(100) + 3 = 303$
3. Result: Cent = **$10^{303}$**

### Example 2: Combination UnVgCt (Unviginticentillion)
1. Find $n$ per part:
   - Un (Units) = 1
   - Vigintillion (Tens) = 20
   - Centillion (Hundreds) = 100
   - Total $n = 1 + 20 + 100 = 121$
2. Apply formula: $\text{Exponent} = 3(121) + 3 = 366$
3. Result: UnVgCt = **$10^{366}$**

### Example 3: SpVg (Septemvigintillion)
1. Find $n$ per part:
   - Septem (Units) = 7
   - Vigintillion (Tens) = 20
   - Total $n = 7 + 20 = 27$
2. Apply formula: $\text{Exponent} = 3(27) + 3 = 84$
3. Result: SpVg = **$10^{84}$**

  `SpQagCent`) still need their exact prefix breakdown matched against the table above to
  lock in the pattern — flag as `*(TBD)*` in data tables until confirmed.
