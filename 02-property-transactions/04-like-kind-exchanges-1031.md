# 04 — Like-Kind Exchanges (Section 1031)

## What Is a Like-Kind Exchange?

A **Section 1031 like-kind exchange** allows a taxpayer to **defer** (not eliminate) gain on the sale of real property if they reinvest in another "like-kind" real property.

✅ Imagine you sell an apartment building for $1 million and made a $400,000 profit. Normally you'd owe taxes on that gain. But if you immediately reinvest in another investment property, the government says: "You haven't really cashed out — you just swapped one investment for another. We'll wait to collect taxes until you actually sell without reinvesting." You defer the tax, not eliminate it.

**Key principle:** Section 1031 is a **deferral** mechanism — the gain is postponed, not forgiven. The deferred gain is embedded in the reduced basis of the new property and will be recognized when the new property is eventually sold.

---

## 🧠 Mnemonic: "45-180" — The Critical Deadlines

> **45 days** to identify replacement property  
> **180 days** to complete the exchange (or tax filing date if earlier)  

These are the two most important numbers for Section 1031.

---

## Post-TCJA Rule: Real Property Only

**Before 2018:** Like-kind exchanges applied to both real property AND personal property (equipment, vehicles, etc.)

**After 2017 (TCJA):** Like-kind exchanges apply **only to real property** (land and buildings). Personal property exchanges no longer qualify. Equipment, vehicles, aircraft, intangibles — cannot use Section 1031 after 2017.

✅ Before TCJA, you could do a like-kind exchange of a delivery truck for another truck. After 2017, you can only exchange real estate for real estate. If you swap business equipment, you must recognize the gain.

---

## "Like-Kind" Defined for Real Property

The definition of "like-kind" is very **broad** for real property:
- Apartment building exchanged for raw land ✅
- Rental house exchanged for a shopping center ✅
- Industrial warehouse exchanged for farmland ✅
- US property exchanged for US property ✅

**NOT like-kind:**
- US real property exchanged for foreign real property ✗
- Real property exchanged for personal property ✗
- Property held for sale (dealer property/inventory) ✗
- Primary residence (not held for investment) ✗

---

## Qualified Intermediary Requirement

In a **deferred exchange** (the most common type), a **qualified intermediary (QI)** facilitates the exchange:

1. Taxpayer sells the "relinquished property" to a buyer
2. QI holds the sale proceeds (taxpayer cannot touch the money!)
3. Taxpayer identifies replacement property within 45 days
4. QI uses the held proceeds to purchase the replacement property
5. Exchange is complete

**Critical rule:** If the taxpayer receives the cash themselves (even temporarily), the exchange fails and the entire gain is immediately taxable.

---

## The 45-Day and 180-Day Rules

| Requirement | Rule |
|-------------|------|
| **Identification period** | Must identify replacement property within **45 days** of transferring relinquished property |
| **Exchange period** | Must receive replacement property by the **earlier of**: (1) 180 days after transfer, or (2) due date (including extensions) of the taxpayer's return |
| **Written identification** | Must be in writing, signed, delivered to QI or seller of replacement property |

### Identification Rules

You can identify up to:
- **3 properties** regardless of value ("3-property rule"), OR
- Any number of properties if **total FMV ≤ 200%** of relinquished property FMV ("200% rule"), OR
- Any number of properties if you actually acquire properties representing **95% of the total identified FMV** ("95% rule")

---

## Boot Received = Recognized Gain

**Boot** = any non-like-kind property received in the exchange (cash, debt relief, personal property).

**Rule:** Recognized gain = **lesser of (1) boot received, or (2) realized gain**.

✅ "Boot" is anything extra you get in the swap that isn't the new real property. Getting cash from the exchange = boot. If the other property's mortgage is less than yours, you're being relieved of debt = boot (the IRS treats debt relief like cash).

### Types of Boot

| Type of Boot | How It Arises |
|-------------|--------------|
| **Cash boot** | Receiving cash in the exchange |
| **Mortgage relief** | Taxpayer's debt on old property > debt on new property; difference = boot |
| **Personal property** | Receiving anything other than real property |

**Netting debt:**
- Debt assumed by taxpayer (on new property) offsets debt relieved
- If mortgage on new property > mortgage on old property → taxpayer is taking on more debt → not boot; reduces cash needed
- If mortgage on old property > mortgage on new property → debt relief = boot

---

## Gain Calculation in a Section 1031 Exchange

```
Step 1: Calculate Realized Gain
  Amount Realized = FMV of new property + Boot received + Debt relieved
  Realized Gain = Amount Realized − Adjusted Basis of old property

Step 2: Calculate Recognized Gain
  Recognized Gain = Lesser of (1) Realized Gain or (2) Boot Received
  (If no boot → No recognized gain, regardless of realized gain amount)

Step 3: Calculate Basis of New Property
  Basis of New Property = Adjusted Basis of Old Property
                         + Gain Recognized
                         + Boot Paid
                         − Boot Received
                         + Debt assumed on new property
                         − Debt relieved on old property
```

---

## Basis Calculation in New Property — Alternative Formula

```
Basis of New Property = FMV of New Property − Deferred Gain

OR equivalently:

Basis of New Property = Adjusted Basis of Old Property
                        + Gain Recognized
                        − Boot Received
                        + Boot Paid
```

✅ The basis in the new property is deliberately **set lower** than its FMV. This is how the deferred gain is "baked in" — when you eventually sell the new property, you'll have a lower basis and therefore a larger gain, which will include the original deferred amount.

---

## Example: Like-Kind Exchange with Boot

| Item | Amount |
|------|--------|
| Old property adjusted basis | $200,000 |
| Old property FMV | $500,000 |
| Mortgage on old property | $100,000 |
| New property FMV | $450,000 |
| Mortgage on new property | $50,000 |
| Cash received | $0 |

**Step 1: Amount Realized**
= $450,000 (FMV of new) + $0 (cash) + $100,000 (debt relieved) − $50,000 (debt assumed)
= $500,000

**Step 2: Realized Gain**
= $500,000 − $200,000 = **$300,000**

**Step 3: Boot Received**
= $100,000 (debt relieved) − $50,000 (debt assumed) = **$50,000 net boot**

**Step 4: Recognized Gain**
= Lesser of $300,000 (realized) or $50,000 (boot) = **$50,000**

**Step 5: Basis in New Property**
= $200,000 + $50,000 − $50,000 = **$200,000** (or: $450,000 − $250,000 deferred = $200,000)

---

## Related Party Rules

**Special rules apply** when like-kind exchanges are between related parties (family members, controlled entities):

- Both parties must **hold the acquired property for at least 2 years** after the exchange
- If either party disposes within 2 years → gain must be recognized retroactively
- Exception: disposition due to death, involuntary conversion, or tax avoidance not a principal purpose

---

## Section 1031 vs. Taxable Sale Comparison

| Feature | Section 1031 Exchange | Taxable Sale |
|---------|----------------------|-------------|
| Gain recognized immediately | No (unless boot) | Yes |
| New basis in property | Carryover (lower) | FMV (stepped up) |
| Depreciation going forward | Lower (continued from old) | Higher (based on FMV) |
| Flexibility | Must use QI, meet deadlines | No restrictions |
| Best for | Long-term holders who want to reinvest | Those who want to cash out |

---

## 🧠 Mnemonic: 1031 Boot Rule — "Boot = Pay Tax on What You Pocket"

> If you **pocket** anything (cash or net debt relief), you pay tax on it — up to your total realized gain. If you **put in** more than you take out (pay boot), no tax. Only **receiving** boot triggers recognition.

---

## Exam Tips

> **Tip 1:** The **45-day identification rule** and **180-day completion rule** are the two most frequently tested facts about 1031 exchanges. Memorize both.

> **Tip 2:** **Post-TCJA: only real property qualifies.** If the exam describes exchanging equipment, vehicles, or personal property after 2017, the exchange does NOT qualify.

> **Tip 3:** **Mortgage relief is boot.** If taxpayer's old mortgage ($300K) > new mortgage ($100K), the $200K difference is boot received (even if no cash changes hands).

> **Tip 4:** If taxpayer receives NO boot → NO recognized gain, regardless of how large the realized gain is. The entire gain is deferred.

> **Tip 5:** The new property's basis is always lower than its FMV by the amount of deferred gain. This is the mechanism for carrying the deferred gain forward.

> **Tip 6:** The exchange must be for property "held for productive use in a trade or business or for investment." A primary residence or dealer inventory does NOT qualify.
