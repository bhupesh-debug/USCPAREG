# 01 — C Corporations

## What Is a C Corporation?

A **C corporation** is a separate legal and tax entity — it files its own tax return (Form 1120), pays its own taxes, and the shareholders pay taxes again on dividends received. This creates **double taxation**.

✅ A C corporation is like a completely separate person in the eyes of the IRS. The company earns money and pays tax on it. Then if the company distributes profits to shareholders (dividends), the shareholders pay tax again on what they receive. The same money gets taxed twice — once at the corporate level, once at the shareholder level.

---

## Formation — Section 351

**Rule:** No gain or loss is recognized when property is transferred to a corporation **solely in exchange for stock**, if the transferors (collectively) control the corporation immediately after the exchange.

### Section 351 Requirements

| Requirement | Detail |
|------------|--------|
| **Transfer of property** | Cash, property, or both; services alone don't count |
| **In exchange for stock** | Transferor receives stock (not bonds or notes) |
| **Control immediately after** | Transferors collectively own **≥ 80%** of all classes of stock |
| **"Solely" for stock** | Boot received triggers gain recognition |

✅ Forming a corporation and contributing property to it is generally tax-free — as long as you (and all contributors together) end up owning at least 80% of the company right afterward. The government doesn't want to tax people just for starting a business.

---

## 🧠 Mnemonic: "Forming A Corporation? Eighty Percent!" — Section 351 Control Test

> When you form a C corporation, you need **80% control** immediately after the transfer to avoid recognizing gain. Below 80%? You recognize gain on the appreciated property contributed.

### Section 351 with Boot

If a transferor receives **boot** (money or other property in addition to stock):
- Recognized gain = **lesser of** (1) gain realized or (2) boot received
- Losses are **never** recognized in a Section 351 exchange
- Basis in stock received = adjusted basis of property transferred + gain recognized − boot received

---

## Corporate Tax Rate

**Flat rate: 21%** (established by TCJA, effective 2018)

✅ Before TCJA, corporations had graduated rates up to 35%. Now there's just one flat rate of 21% on all corporate taxable income. Simple math: corporate income × 21% = corporate tax.

---

## Dividends Received Deduction (DRD)

When one C corporation receives dividends from another corporation, the DRD prevents triple (or more) taxation:

| Ownership in Paying Corp | DRD Percentage |
|--------------------------|---------------|
| Less than 20% | **50% DRD** |
| 20% or more (but <80%) | **65% DRD** |
| 80% or more (affiliated group) | **100% DRD** |

✅ If Corp A owns stock in Corp B and gets dividends, they can deduct 50-100% of those dividends to avoid paying full tax on money that was already taxed at Corp B. The more you own, the bigger the deduction.

**DRD Taxable Income Limitation:** The DRD is generally limited to the applicable percentage (50%/65%) multiplied by **taxable income before the DRD**. Exception: If taking the full DRD creates or increases a net operating loss, the limitation does not apply.

---

## Accumulated Earnings Tax (AET)

**What it is:** A **20% penalty tax** on accumulated earnings beyond reasonable business needs.

| Feature | Detail |
|---------|--------|
| Rate | 20% |
| Applied to | Accumulated Taxable Income (ATI) |
| Trigger | Accumulation beyond reasonable business needs |
| Reasonable accumulation | $250,000 general; $150,000 for service corps (health, law, accounting, consulting, architecture, engineering, performing arts, actuarial science) |
| Defense | Business purpose for retention |

✅ The AET is the IRS saying: "If you're just hoarding cash in your corporation to avoid paying dividends to shareholders (who'd have to pay personal taxes on them), we're going to penalize you for it."

---

## Personal Holding Company (PHC) Tax

**What it is:** Another 20% penalty tax for corporations that are "passive investment vehicles."

**PHC Test (both required):**
1. More than **60% of adjusted ordinary gross income** is PHC income (dividends, interest, rents, royalties, compensation from certain sources)
2. More than **50%** of stock owned by 5 or fewer individuals at any point in second half of tax year

**PHC tax rate:** 20% on undistributed PHC income

---

## Corporate Charitable Contributions

- **Limit:** 10% of **taxable income before** the charitable deduction, DRD, capital loss carryback, and NOL deduction
- Excess contributions carry forward **5 years**
- Different from individual limit (60% for cash to public charities)

---

## Net Operating Loss (NOL) Rules

| Feature | Rule |
|---------|------|
| **Carryback** | **2 years** (for certain farming NOLs and casualty/disaster losses) |
| **Carryforward** | **Indefinitely** |
| **Deduction limit** | 80% of taxable income in carryforward years (post-TCJA) |
| **C corp special** | No TCJA 80% limitation for farming losses |

---

## Schedule M-1 — Book-to-Tax Reconciliation

**Purpose:** Reconciles **book income** (GAAP) to **taxable income**.

**Formula:**
```
Net Income per Books
+ Items on books not deductible for tax
+ Items taxable but not in book income
− Items in book income not taxable
− Deductions on tax return not in books
= Taxable Income
```

### Common Book-Tax Differences

| Item | Book Treatment | Tax Treatment |
|------|---------------|--------------|
| Federal income taxes | Expense | Not deductible |
| Life insurance proceeds | Income | Excluded |
| Officer life insurance premiums | Expense | Not deductible |
| Meals (50% disallowed) | Full expense | Only 50% deductible |
| Tax depreciation > book depreciation | Lower expense | Higher deduction |
| Accrued expenses not yet paid | Expense | May not be deductible yet |
| Tax-exempt interest | Income | Not in taxable income |

---

## Constructive Dividends

When a corporation provides a benefit to a shareholder that is not properly characterized as deductible compensation or expense, it is treated as a **constructive dividend** — taxable to the shareholder as ordinary income.

**Common constructive dividend situations:**
- Excessive compensation to shareholder-employees
- Shareholder using corporate property for personal use (below-market rent)
- Below-market loans from corporation to shareholders
- Corporate payment of personal expenses of shareholders
- Sales of property at below-market prices to shareholders

✅ The IRS treats these disguised benefits as if the corporation distributed a dividend and the shareholder used it to buy the benefit. The shareholder reports the benefit as dividend income; the corporation gets no deduction.

---

## 🧠 Mnemonic: "DRD = Don't Remember Dividend (tax it less!)" — 50/65/100

> **50%** you own less than 20% of payer  
> **65%** you own 20–79% of payer  
> **100%** you own 80%+ of payer  
> The bigger your ownership stake, the more you can deduct.

---

## 🧠 Mnemonic: "FACE the Formation" — Section 351

> **F**orm the corporation  
> **A**ll contributing property (not just services)  
> **C**ontrol required (80%+) immediately after  
> **E**xchange stock for the property  

---

## Corporate Tax Calendar

| Event | Form | Due Date |
|-------|------|---------|
| C corporation return | Form 1120 | 15th day of 4th month after year-end |
| Estimated tax payments | Form 1120-W | 15th day of 4th, 6th, 9th, 12th months |
| Extension | Form 7004 | 6-month extension available |

For calendar-year corporations:
- Return due: **April 15** (extension to October 15)
- Estimated tax due: April 15, June 15, September 15, December 15

---

## Exam Tips

> **Tip 1:** **Section 351 requires 80% control** — not 50%, not a majority, not 2/3. It's 80% of each class of stock.

> **Tip 2:** **Services do not count** as "property" for the 80% control test. Only cash and property contributions count. However, receiving stock for services is ordinary income to the service provider.

> **Tip 3:** The DRD **taxable income limitation** is a classic MCQ trap. The deduction is limited to 50% (or 65%) of taxable income — but this limitation doesn't apply if applying it would create or increase an NOL.

> **Tip 4:** **Charitable contributions** for C corporations cap at **10% of TI** (not 60%). The excess carries forward 5 years — same as individuals.

> **Tip 5:** Know the **Schedule M-1 additions and subtractions**. The most common exam item is that **federal income taxes are not deductible** by corporations — they get added back to book income.

> **Tip 6:** **Accumulated earnings tax** threshold for service corporations is **$150,000**, not $250,000. Service corps include health, law, accounting, consulting, architecture, engineering.
