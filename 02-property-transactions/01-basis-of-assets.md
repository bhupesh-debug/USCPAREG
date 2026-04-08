# 01 — Basis of Assets

## What Is Basis?

**Basis** is your starting point for calculating gain or loss when you sell property. It's roughly "how much you paid for it" — adjusted over time.

✅ Basis is like the receipt you keep when you buy something. When you sell it later, the IRS looks at your receipt (basis) and compares it to the sale price to figure out how much you made (gain) or lost (loss). Without a basis, you'd pay taxes on the full sale price instead of just the profit.

**Gain or Loss Formula:**
```
Amount Realized (sale price + debt relieved)
- Adjusted Basis
= Realized Gain (or Loss)
```

---

## 🧠 Mnemonic: "CIA" — Basis Adjustments

> **C**ost (original purchase price)  
> **I**mprovements added over time  
> **A**ccumulated depreciation subtracted over time  

**Adjusted Basis Formula:**
```
Original Cost Basis
+ Capital Improvements
- Accumulated Depreciation (and other reductions)
= Adjusted Basis
```

---

## 1. Cost Basis

**General Rule:** Basis = **cost of property** at acquisition.

What's included in cost basis:
- Purchase price paid
- Sales tax on purchase
- Freight and installation costs
- Legal fees related to acquisition
- Amounts assumed on debt when property is purchased

✅ If you buy a building for $500,000 and pay $10,000 in legal fees to close the deal, your cost basis is $510,000 — not just the purchase price.

---

## 2. Adjusted Basis

**Adjusted basis** = cost basis, modified over time for events that affect the property:

| Adjustment | Effect on Basis |
|-----------|----------------|
| Capital improvements | **Increase** basis |
| Depreciation deductions taken | **Decrease** basis |
| Casualty losses (deducted) | **Decrease** basis |
| Insurance reimbursements used for repairs | May decrease basis |
| Tax-free return of capital distributions | Decrease basis (to zero, then taxable) |
| Special assessments for local improvements | Increase basis |

---

## 3. Gifted Property Basis — The "Double Basis" Rule

**When you receive property as a gift**, your basis depends on what happens when you later sell it:

### Rule 1: If FMV at date of gift ≥ Donor's Adjusted Basis
- Your basis = **Donor's adjusted basis** (carryover basis)
- You "step into the shoes" of the donor

### Rule 2 (The "Double Basis" Rule): If FMV at date of gift < Donor's Adjusted Basis
The donee has **two different basis amounts** depending on whether the sale results in a gain or a loss:

| If You Sell At... | Your Basis Is... | Purpose |
|------------------|-----------------|---------|
| **Gain** (sale price > donor's basis) | **Donor's adjusted basis** | Normal gain calculation |
| **Loss** (sale price < FMV at gift) | **FMV at date of gift** | Loss calculation |
| **In between** (FMV ≤ price ≤ donor's basis) | **No gain, no loss** | Neither |

✅ Imagine Grandma bought stock for $10,000, and now it's only worth $6,000. She gives it to you. If you sold it for $4,000, your loss is only $2,000 (from the $6,000 FMV, not from Grandma's $10,000 cost). If you sold it for $12,000, your gain is $2,000 (from Grandma's $10,000 basis). The IRS doesn't let you claim a bigger loss than the actual decline in value since you got the gift.

**Gift Tax Paid:** If the donor paid gift tax, the donee's basis increases by the gift tax attributable to the appreciation.

---

## 4. Inherited Property — Stepped-Up Basis

**Rule:** Inherited property receives a **new basis equal to FMV at the date of the decedent's death** (or alternate valuation date).

✅ This is a HUGE deal. If Grandpa bought land for $10,000 and it's worth $500,000 when he dies, the heir's basis is $500,000. The $490,000 of appreciation is never taxed as income to anyone. It disappears!

**Alternate Valuation Date:** The estate may elect to value assets 6 months after death if:
1. The election reduces both the gross estate value AND the estate tax
2. If an asset is sold within 6 months, it uses the sale price, not the 6-month value

| | Date of Death | Alternate Date |
|---|-------------|----------------|
| When used | Default | Only if reduces estate AND tax |
| Value used | FMV at death | FMV 6 months after death |
| If sold before 6 months | N/A | Use actual sale price |

**What if value went DOWN after death?** The alternate valuation election would use the lower value, reducing estate tax AND giving the heir a lower basis.

### Inherited Property — Holding Period

- Inherited property is **always long-term** regardless of how long the heir holds it
- Even if sold the day after inheriting, it gets long-term capital gain/loss treatment

---

## 5. Property Received for Services

**Rule:** If you receive property as compensation for services, your basis = **FMV of the property at the time received**.

✅ If your employer gives you stock worth $50,000 as a bonus, you report $50,000 of income AND your basis in the stock is $50,000. You got the fair value, you paid tax on it, now you own it at that value.

---

## 6. Property Received in a Like-Kind Exchange (Section 1031)

**Rule:** Basis in new property = Basis of old property + boot paid - boot received + gain recognized

(Covered in detail in the 1031 Exchange file.)

---

## 7. Related Party Transactions

**Loss disallowance rule (Section 267):** Losses are **disallowed** between related parties.

**Related parties include:**
- Family members (siblings, spouse, ancestors, lineal descendants)
- Individual and corporation where individual owns >50%
- Two corporations with >50% common ownership
- Grantor and trust
- Executor and beneficiary

✅ If you sell your car to your brother at a loss, you can't deduct that loss. The IRS says family members shouldn't be able to generate paper losses by transferring property to each other.

**The "Suspended Loss" Twist:** If the buyer later sells the property at a gain, they can use the previously disallowed loss to offset that gain (but not to create a loss).

---

## 🧠 Mnemonic: Gift Basis — "GAPPED" — Gain at Donor's Basis, Partial = No Gain No Loss, Elevated FMV = Donor's basis

For gifted property where FMV < donor's basis (the tricky case):
> **G**ain → use **D**onor's basis  
> **L**oss → use **F**MV at date of gift  
> **In between** → **N**either (no gain, no loss)

---

## 🧠 Mnemonic: Inherited Property — "DEAD = STEPPED UP"

> When property passes at **death**, the basis **steps up** to FMV. The accumulated gain of a lifetime is erased.

---

## Basis Summary Reference Table

| How Property Acquired | Basis Rule |
|----------------------|-----------|
| **Purchase** | Cost (purchase price + acquisition costs) |
| **Gift (FMV ≥ donor's basis)** | Donor's carryover basis |
| **Gift (FMV < donor's basis)** | Double basis rule (FMV for losses, donor's for gains) |
| **Inheritance** | FMV at date of death (stepped-up or stepped-down) |
| **Like-kind exchange** | Carryover basis ± adjustments |
| **Received for services** | FMV when received (income recognized) |
| **Related party purchase** | Cost, but losses disallowed on the sale from related party |

---

## Exam Tips

> **Tip 1:** The **double basis rule for gifts** is a classic exam question. Draw a number line: if selling price is above donor's basis = gain; below FMV = loss; between FMV and donor's basis = no gain/no loss.

> **Tip 2:** Inherited property is **always long-term** for capital gain/loss purposes. This is frequently tested.

> **Tip 3:** The **alternate valuation date** can only be elected for the ENTIRE estate — you can't pick and choose assets. And it must reduce both estate value AND estate tax (both conditions required).

> **Tip 4:** Related party loss disallowance — the buyer CAN use the disallowed loss to offset a future gain on the same property. The loss isn't truly lost, just suspended until the property leaves the related-party chain.

> **Tip 5:** Gift tax paid by donor increases the donee's basis, but only for the gift tax attributable to the **net appreciation** (not the full gift tax on the total value).

> **Tip 6:** Watch for properties received in exchange for services — the FMV becomes both the income amount AND the new basis. Dual treatment.
