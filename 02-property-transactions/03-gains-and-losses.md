# 03 — Gains and Losses on Property Transactions

## Realized vs. Recognized Gain or Loss

**Realized gain/loss** = what you actually made or lost economically (the "math" result).
**Recognized gain/loss** = what you must report on your tax return (taxable or deductible).

✅ You might "realize" a $100,000 gain when you sell your house, but if you qualify for the home sale exclusion, you only "recognize" $0 of that gain. Realized = what really happened. Recognized = what the tax code makes you report.

**Default rule:** All realized gains are recognized unless a specific exclusion or deferral provision applies. Realized losses are recognized unless specifically disallowed (e.g., related-party sales, personal-use property).

```
Amount Realized
− Adjusted Basis
= Realized Gain (Loss)
```

---

## Capital Assets and Capital Gains

**Capital asset** = all property EXCEPT:
- Inventory/stock in trade
- Accounts or notes receivable from sales in the ordinary course of business
- Depreciable property or real estate used in a trade or business (Section 1231 property — covered below)
- Copyrights/creative works created by the taxpayer
- US government publications acquired at reduced cost
- Certain commodity derivatives and hedging transactions

✅ The easiest way to remember capital assets: stocks, bonds, collectibles, personal residence, investment real estate = capital assets. Your business's product inventory and equipment = NOT capital assets.

### Capital Gain Rates

| Holding Period | Tax Rate |
|---------------|---------|
| Short-term (≤ 1 year) | Ordinary income tax rates (up to 37%) |
| Long-term (> 1 year) | **0%, 15%, or 20%** based on taxable income |

**Long-term capital gains rates (2024):**

| Filing Status | 0% Rate | 15% Rate | 20% Rate |
|--------------|---------|---------|---------|
| Single | Up to $47,025 | $47,026–$518,900 | Over $518,900 |
| MFJ | Up to $94,050 | $94,051–$583,750 | Over $583,750 |

### Net Capital Gain Calculation

```
Step 1: Separate all capital transactions:
  - Net Short-Term Capital Gain (Loss) = STCG - STCL
  - Net Long-Term Capital Gain (Loss) = LTCG - LTCL

Step 2: If both net amounts are gains → tax separately at applicable rates
Step 3: If one is a gain and one is a loss → net them against each other
```

**Capital loss limitation:** Net capital losses deductible against ordinary income are limited to **$3,000 per year** ($1,500 MFS). Excess carries forward indefinitely, retaining its character (short vs. long-term).

---

## Section 1231 — Business Property

**Section 1231 property** = depreciable real property AND depreciable personal property used in a trade or business (held more than 1 year).

✅ Section 1231 is the "best of both worlds" property. If you sell business property at a gain, it gets treated like long-term capital gain (favorable rates). If you sell at a loss, it's treated like an ordinary loss (fully deductible, no $3,000 cap). Congress was generous here.

### Section 1231 Netting Rules

```
Step 1: Net all Section 1231 gains and losses together for the year

If Net Result is a GAIN:
  → Treated as long-term capital gain (favorable rates)
  → BUT first check the Section 1231 lookback rule

If Net Result is a LOSS:
  → Treated as ordinary loss (fully deductible, not limited to $3,000)
```

### Section 1231 Lookback Rule

If there have been **net Section 1231 losses in any of the prior 5 years**, the current year's Section 1231 gain is "recaptured" as ordinary income (to the extent of those prior losses).

---

## 🧠 Mnemonic: "1-2-3-1" — The Property Transaction Sequence

> When you sell business property, apply the sections in this order:  
> **1245** recapture first → **1250** recapture second → **1231** netting last  
> Remember: **1245 → 1250 → 1231** (biggest to most favorable treatment)

---

## Section 1245 Recapture

**What it covers:** Depreciable **personal property** (equipment, machinery, furniture) and certain amortizable intangibles.

**The rule:** When you sell Section 1245 property at a gain, the depreciation previously taken is "recaptured" as **ordinary income**. Only the excess gain above total depreciation taken gets Section 1231 treatment.

```
Sale Price − Adjusted Basis = Total Gain

Recaptured as Ordinary Income (Section 1245) =
  Lesser of (1) Total Gain or (2) Total Depreciation Taken

Remainder (if any) = Section 1231 Gain
```

✅ Think of it this way: When you took depreciation deductions, you reduced your ordinary income each year. Now when you sell, the IRS wants those ordinary income benefits back. They "recapture" the depreciation by taxing it at ordinary income rates.

**Example:**
- Machine purchased for $100,000
- Depreciation taken: $60,000
- Adjusted basis: $40,000
- Sale price: $110,000
- Total gain: $70,000
- Section 1245 recapture = lesser of $70,000 gain or $60,000 depreciation = **$60,000 ordinary income**
- Section 1231 gain = $70,000 − $60,000 = **$10,000**

---

## Section 1250 Recapture

**What it covers:** Depreciable **real property** (buildings).

**The rule:** Section 1250 only recaptures depreciation taken in **excess** of straight-line depreciation. Since most real property under MACRS uses straight-line already, Section 1250 recapture is rare for property placed in service after 1986.

**Unrecaptured Section 1250 Gain:** Even though the excess depreciation recapture is minimal, **all** straight-line depreciation on real property results in "unrecaptured Section 1250 gain," taxed at a maximum **25% rate** (not 0%/15%/20%).

```
When real property is sold at a gain:

Step 1: Section 1250 recapture = Excess of accelerated over SL depreciation
        (Usually $0 for post-1986 MACRS real property)

Step 2: Unrecaptured Section 1250 gain = all SL depreciation taken
        → Taxed at max 25% rate (special long-term capital gain rate)

Step 3: Remaining gain above all depreciation = Section 1231 gain → 0/15/20%
```

✅ For a rental building: Any depreciation you've taken comes back at 25% when you sell at a profit. The pure appreciation above your original purchase price might qualify for the 15% or 20% capital gains rate, but the depreciation benefit gets clawed back at 25%.

---

## Capital Loss Limitations and Carryforward

| Rule | Detail |
|------|--------|
| Max ordinary income offset | **$3,000/year** ($1,500 MFS) |
| Carryforward | Indefinite (retains ST vs. LT character) |
| C corporation | Cannot deduct capital losses against ordinary income; can only carry back 3 years and forward 5 years |

---

## Wash Sale Rule

**Rule:** A **loss** is **disallowed** if you sell a security at a loss and, within **30 days before or after** the sale, you buy substantially identical stock or securities.

✅ You can't sell your Apple stock at a loss on December 30 and buy it right back on January 5 to lock in the tax loss. The IRS calls this "washing" the loss — you didn't really give up the investment, so you don't get the tax benefit.

**60-day window:** 30 days before sale + date of sale + 30 days after sale.

**Consequences:**
- Loss is **disallowed** (not lost forever)
- The disallowed loss is **added to the basis** of the repurchased shares
- Holding period of old shares carries over to new shares

**Does NOT apply to:**
- Gains (you can sell at a gain and immediately repurchase)
- Business inventory
- Related party sales (those losses are disallowed under different rules)

---

## Related Party Loss Disallowance (Section 267)

**Rule:** Losses on sales between **related parties** are **permanently disallowed** (unless the buyer later sells to an unrelated party at a gain).

**Related parties include:**
- Brothers, sisters, spouse, ancestors, lineal descendants
- Individual and > 50%-owned corporation
- Two corporations with common >50% ownership

✅ Can't sell your car to your mom at a loss and deduct it. The loss is disallowed. (See Basis file for more detail on the "recovery" rule when she sells it.)

---

## Home Sale Exclusion (Section 121)

**Rule:** Taxpayers can exclude up to:
- **$250,000** of gain (single)
- **$500,000** of gain (MFJ)

**Requirements:**
- Owned AND used as principal residence for at least **2 of the last 5 years** before sale
- Cannot be used more than once in any **2-year period**
- Prorated exclusion available for partial use if sale due to health, employment change, or unforeseen circumstances

---

## 🧠 Mnemonic: Recapture Order — "Eat Ordinary First (1245), Then Get Fancy (1250/1231)"

> **Section 1245** = ordinary income recapture (the most ordinary treatment)  
> **Section 1250** = 25% unrecaptured gain (middle ground)  
> **Section 1231** = capital gain treatment (the best outcome)  
> When selling business property, work from most-recaptured to most-favorable.

---

## Summary: Tax Treatment When Selling Business Property

| Sale Scenario | Tax Treatment |
|--------------|--------------|
| Sell 1245 property at gain | Ordinary income up to depreciation taken; 1231 gain beyond |
| Sell 1245 property at loss | 1231 loss (ordinary loss) |
| Sell 1250 property at gain | 25% unrecaptured 1250 gain; then 0/15/20% for excess |
| Sell 1250 property at loss | 1231 loss (ordinary loss) |
| Net 1231 gain | Long-term capital gain (subject to lookback rule) |
| Net 1231 loss | Ordinary loss |
| Sell personal investment at gain (> 1 year) | 0%/15%/20% long-term capital gain |
| Net capital loss | Up to $3,000 against ordinary income; rest carries forward |

---

## Exam Tips

> **Tip 1:** **Section 1245 recapture** is tested frequently. Remember: ordinary income = lesser of (total gain) or (total depreciation taken). Anything above = Section 1231.

> **Tip 2:** **Unrecaptured Section 1250 gain** is taxed at max **25%** — not the regular 0/15/20 capital gains rates. Know this distinction for real property sales.

> **Tip 3:** The **wash sale rule** only applies to **losses** — never gains. Also applies to substantially identical securities (treasury notes ≠ substantially identical to different notes; stock in the same company = identical).

> **Tip 4:** **Capital losses** limited to $3,000/year against ordinary income is the individual rule. C corporations can't deduct capital losses against ordinary income at all.

> **Tip 5:** The **Section 1231 lookback rule** converts current year Section 1231 gains back to ordinary income if there were net 1231 losses in any of the **prior 5 years**. Easy to forget on exam.

> **Tip 6:** Home sale exclusion: 2 of 5 year ownership AND use test; $250K/$500K exclusion. Gain above exclusion is taxable — and remember, depreciation taken on the home (if it was ever rented) creates unrecaptured 1250 gain taxed at 25%.
