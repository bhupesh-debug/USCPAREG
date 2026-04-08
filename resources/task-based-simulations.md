# Task-Based Simulations (TBS) — The REG Exam's Heavy Hitter

> **TBS account for 50% of your REG score.** This guide covers the most-asked simulation types, breaks them down like a top 1% teacher would, and gives you the master framework to crush any TBS.

---

## ✅ What Are Task-Based Simulations?

Think of TBS as "open-book homework problems on steroids." Instead of picking A/B/C/D, you are dropped into a real-world scenario — you get exhibits, documents, tax forms, and spreadsheets — and you have to figure out the answer by applying multiple concepts together.

🧠 **Key Insight:** A single TBS often chains 3–5 calculations together. For example: Calculate basis → Determine gain → Determine character of gain → Apply to partner's return. If you only practice MCQs, TBS will blindside you.

---

## REG TBS Structure

| Testlet | Content |
|---------|---------|
| Testlet 3 | 2 TBS |
| Testlet 4 | 3 TBS |
| Testlet 5 | 3 TBS |
| **Total** | **8 TBS = 50% of your score** |

**Time Strategy:** You have ~4 hours total. Budget roughly 15–20 minutes per TBS after finishing MCQs. Read ALL exhibits before answering.

---

## 🏆 The 10 Most-Tested TBS Topics (Ranked by Frequency)

Based on AICPA released simulations, exam candidate reports, and blueprint analysis:

| Rank | Topic | Area | Why It's Heavily Tested |
|------|-------|------|------------------------|
| 1 | **Individual Tax Return (Form 1040) Preparation** | Individuals | Chains together gross income, adjustments, deductions, credits |
| 2 | **S Corporation Shareholder Basis** | Entities | Multi-year tracking, contributions, income, distributions, losses |
| 3 | **Partnership Basis & K-1 Allocations** | Entities | Inside vs. outside basis, guaranteed payments, special allocations |
| 4 | **Property Transactions — Basis & Gain/Loss** | Property | Gift basis, inherited basis, Section 1231/1245/1250 recapture |
| 5 | **Corporate Distributions & E&P** | Entities | Taxable vs. nontaxable, return of capital, capital gain |
| 6 | **Depreciation & Cost Recovery (MACRS/179)** | Property | Convention rules, Section 179 limits, bonus depreciation |
| 7 | **Schedule C (Sole Proprietor) Deductions** | Individuals | Business meals, home office, auto expenses, document review |
| 8 | **Contract Law — Formation & Defenses** | Business Law | Statute of Frauds, offer/acceptance, void vs. voidable |
| 9 | **Tax Preparer Penalties & Ethics** | Ethics | Section 6694(a) vs. 6694(b), authority standards |
| 10 | **Like-Kind Exchanges (1031)** | Property | Boot, basis in new property, 45/180 day rules |

---

## 🥇 TBS #1: Individual Tax Return Preparation (Form 1040)

### ✅ What the Exam Asks

You get a taxpayer scenario with multiple income sources, deductions, and credits. You must walk through the entire Form 1040 and compute the final tax liability or refund.

### The Master Formula (Memorize This Cold)

```
  Gross Income (all sources)
- Adjustments (above-the-line)
= Adjusted Gross Income (AGI)
- Standard Deduction OR Itemized Deductions (whichever is greater)
= Taxable Income Before QBI
- QBI Deduction (Section 199A)
= Taxable Income
× Tax Rate (from tax tables)
= Tax
- Credits (nonrefundable first, then refundable)
+ Other Taxes (SE tax, NII tax, additional Medicare)
- Payments (withholding, estimated payments)
= Tax Due or Refund
```

### 🧠 Mnemonic: **"GAASTQ-TCP"** — Gross, Adjustments, AGI, Standard/itemized, Taxable, QBI, Tax, Credits, Payments

### Key Traps the Exam Sets

| Trap | What They Do | How to Avoid |
|------|-------------|--------------|
| **Municipal bond interest** | Include it in a list of income items | Remember: tax-exempt — do NOT include in gross income |
| **Social Security** | Give you total SS received | Only up to 85% is taxable — calculate based on provisional income |
| **Child support vs. alimony** | Mix them together | Child support = NEVER taxable/deductible. Alimony (pre-2019) = taxable/deductible |
| **Standard vs. itemized** | Give itemized deductions less than standard | Always compare — taxpayer takes the GREATER amount |
| **Phase-outs** | Give income right at a phase-out threshold | Apply the correct phase-out formula for credits |

### Worked Example (Top 1% Teacher Style)

**Scenario:** Sarah, single, age 35, has the following for 2023:
- Wages: $85,000
- Bank interest: $2,500
- Municipal bond interest: $1,000
- Student loan interest paid: $2,000
- Traditional IRA contribution: $3,000
- Medical expenses: $8,000
- State income taxes: $6,000
- Mortgage interest: $9,000
- Charitable cash contributions: $3,000
- Federal income tax withheld: $12,000

**Step-by-step solution:**

| Step | Calculation | Amount |
|------|------------|--------|
| **Gross Income** | $85,000 + $2,500 (muni bond = excluded!) | **$87,500** |
| **Adjustments** | Student loan $2,000 + IRA $3,000 | **($5,000)** |
| **AGI** | $87,500 - $5,000 | **$82,500** |
| **Itemized vs. Standard** | Medical: $8,000 - (7.5% × $82,500) = $8,000 - $6,187.50 = **$1,812.50**; SALT: $6,000; Mortgage: $9,000; Charity: $3,000; Total itemized = **$19,812.50** vs. Standard = $13,850 | Take **itemized: $19,812.50** |
| **Taxable Income** | $82,500 - $19,812.50 | **$62,687.50** |
| **Tax** | Apply 2023 brackets for single filer | ~**$9,279** |
| **Credits** | None given | $0 |
| **Tax Due/(Refund)** | $9,279 - $12,000 withheld | **($2,721) Refund** |

🧠 **Top 1% Insight:** The muni bond interest ($1,000) is the trap. Many candidates add it to gross income. It's tax-exempt. Period. The exam loves this trick.

---

## 🥇 TBS #2: S Corporation Shareholder Basis

### ✅ What the Exam Asks

You receive a multi-year scenario with contributions, income/loss pass-throughs, distributions, and loans. You must track the shareholder's stock basis AND debt basis year by year, finding errors in a client-provided schedule.

### The Master Framework

```
  Beginning Stock Basis
+ Contributions (adjusted basis for Sec. 351; FMV if not)
+ Share of Income Items (ordinary income + separately stated income + tax-exempt income)
- Distributions
- Nondeductible Expenses (e.g., 50% meals, penalties)
- Share of Loss Items (ordinary loss + separately stated losses)
= Ending Stock Basis (CANNOT go below zero)
```

**Debt Basis (tracked separately):**
```
  Beginning Debt Basis
+ New Direct Loans to Corporation
- Loan Repayments
+ Restored Basis (from net income in future years, after stock basis is fully restored)
= Ending Debt Basis
```

### 🧠 Mnemonic: **"ACID-NL"** — Add contributions, add Income, subtract Distributions, subtract Nondeductible, subtract Losses

### The ORDER Matters (This Is What Separates Top 1% from Everyone Else)

The sequence of adjustments is critical and HEAVILY tested:

1. **First:** Add income items and contributions (increases)
2. **Second:** Subtract distributions (but not below zero)
3. **Third:** Subtract nondeductible/non-capital expenses
4. **Fourth:** Subtract loss/deduction items (but not below zero)

🧠 **Why the order matters:** If you subtract losses before distributions, you get the wrong basis and wrong gain recognition on distributions.

### Key Traps

| Trap | Details |
|------|---------|
| **Section 351 vs. Non-351 contributions** | If 80% control test is met → basis = adjusted basis of property. If not → basis = FMV |
| **Loan guarantees** | Guaranteeing a bank loan does NOT increase S corp debt basis (unlike partnerships!) |
| **Direct loans only** | Only DIRECT loans from shareholder to corporation create debt basis |
| **Loan repayment with reduced debt basis** | If debt basis was reduced by losses, repayment triggers gain |
| **Transposition errors** | The AICPA deliberately puts transposed numbers in client schedules for you to catch |

### Worked Example

**Year 1:** Shareholder X contributes property (basis $100K, FMV $125K) for 50% stock in a 351 transaction. S corp has $40K ordinary income. Distribution of $15K to X.

| Item | Stock Basis |
|------|------------|
| Beginning | $0 |
| + Contribution (Sec. 351 = adj basis) | +$100,000 |
| + 50% of $40K income | +$20,000 |
| - Distribution | -$15,000 |
| **Ending Stock Basis** | **$105,000** |

🧠 **Top 1% Trap:** A common error is using FMV ($125K) instead of adjusted basis ($100K) for the Section 351 contribution. The exam WILL test this.

---

## 🥇 TBS #3: Partnership Basis & K-1 Allocations

### ✅ What the Exam Asks

Calculate a partner's outside basis after formation, operations, distributions, and changes in liabilities. Allocate income/loss items correctly per the partnership agreement.

### The Master Framework

```
  Cash Contributed
+ Adjusted Basis of Property Contributed
+ Share of Partnership Liabilities (recourse and nonrecourse)
+ Share of Income
- Distributions Received
- Share of Losses (limited to basis, then at-risk, then passive activity)
= Ending Outside Basis
```

### 🧠 Mnemonic: **"CLIP" for basis increases:** Cash, Liabilities (share of), Income, Property (adj basis)

### 🧠 Mnemonic: **"DLL" for basis decreases:** Distributions, Losses, Liability reductions

### Three-Layer Loss Limitation (The Exam's Favorite Chain)

Losses are deductible ONLY if they pass through ALL three filters in order:

```
Layer 1: BASIS limitation     → Loss ≤ Partner's basis
Layer 2: AT-RISK limitation   → Loss ≤ Amount at risk
Layer 3: PASSIVE ACTIVITY     → Loss ≤ Passive income (unless material participation)
```

🧠 **Mnemonic: "BAP"** — Basis, At-risk, Passive. Apply in this order, always.

### Key Differences: Partnership vs. S Corporation Basis

| Feature | Partnership | S Corporation |
|---------|------------|---------------|
| Liability share increases basis? | **YES** (both recourse and nonrecourse) | **NO** (only direct loans from shareholder) |
| Guaranteed payments | Not included in basis | N/A |
| Loss limitation | Basis → At-risk → Passive | Basis → At-risk → Passive |
| Contribution basis | Always adjusted basis (no gain unless liabilities exceed basis) | Sec. 351 rules apply |

---

## 🥇 TBS #4: Property Transactions — Basis & Gain/Loss Character

### ✅ What the Exam Asks

Given a property sale or exchange, determine: (1) basis, (2) amount realized, (3) gain/loss realized, (4) gain/loss recognized, and (5) character (ordinary, Section 1231, capital).

### The Decision Tree (Top 1% Framework)

```
Step 1: What is the BASIS?
  → Purchased? → Cost
  → Gift? → Donor's basis (gains) / Lesser of donor's basis or FMV (losses)
  → Inherited? → FMV at date of death
  → Converted from personal? → Lesser of cost or FMV at conversion

Step 2: What is AMOUNT REALIZED?
  → Cash + FMV of property received + liabilities assumed by buyer

Step 3: GAIN/LOSS = Amount Realized - Adjusted Basis

Step 4: What is the CHARACTER?
  → Held ≤ 1 year? → Short-term capital or ordinary
  → Section 1231 property (business, held > 1 year)?
      → Apply Section 1245 recapture first (ordinary up to depreciation taken)
      → Then Section 1250 recapture (25% rate on unrecaptured)
      → Remaining = Section 1231 gain (LTCG rates)
```

### 🧠 Mnemonic for Recapture Order: **"1-2-3-1"**

- Section **1**231 → Section **1**2**4**5 → Section **1**2**5**0 → back to **1**231
- Personal property depreciation recaptured as ordinary under 1245
- Real property depreciation recaptured at 25% under 1250
- Remaining gain gets favorable 1231 (LTCG) treatment

### Gift Basis — The "Double Basis" Rule

| Scenario | Basis for GAIN | Basis for LOSS |
|----------|---------------|---------------|
| FMV > Donor's Basis | Donor's Basis | Donor's Basis |
| FMV < Donor's Basis | Donor's Basis | **FMV** |
| Selling price between FMV and donor's basis | **NO gain, NO loss** | **NO gain, NO loss** |

🧠 **Memory Trick:** "Gifts have a gray zone — if the sale price falls between FMV and donor's basis, it's a no-man's land. Zero gain, zero loss."

---

## 🥇 TBS #5: Corporate Distributions & E&P

### ✅ What the Exam Asks

A C corporation makes distributions to shareholders. Determine for each shareholder: (1) dividend income, (2) nontaxable return of capital, and (3) capital gain.

### The Waterfall (Memorize This)

```
Distribution received by shareholder:

Step 1: Taxable DIVIDEND → to the extent of C corp's Current E&P + Accumulated E&P
Step 2: Nontaxable RETURN OF CAPITAL → to the extent of shareholder's stock basis
Step 3: CAPITAL GAIN → any excess above basis
```

🧠 **Mnemonic: "DRC"** — Dividend first, Return of capital second, Capital gain last. Think "Distribution Runs a Course."

### Current vs. Accumulated E&P

| Rule | Details |
|------|---------|
| Current E&P is positive | Allocate pro rata to all distributions during the year |
| Accumulated E&P is positive | Use on a chronological (first-in-first-out) basis |
| Current E&P is negative | Net against accumulated E&P |
| Both negative | Entire distribution = return of capital (then capital gain if exceeds basis) |

### Worked Example

**Facts:** Corporation distributes $33,300 to sole shareholder. Current E&P = $19,100. Shareholder basis = $10,000.

| Step | Amount | Classification |
|------|--------|---------------|
| Dividend (up to E&P) | $19,100 | **Taxable dividend** |
| Return of capital (up to basis) | $10,000 | **Nontaxable** (reduces basis to $0) |
| Capital gain (excess) | $4,200 | **Capital gain** |
| **Total** | **$33,300** | |

🧠 **Top 1% Insight:** On TBS, ALWAYS fill in zeros for categories that don't apply. Leaving them blank tells the grading system you didn't attempt it. Writing "$0" shows you understand that portion doesn't apply.

---

## 🥇 TBS #6: Depreciation & Cost Recovery

### ✅ What the Exam Asks

Compute depreciation for multiple assets using MACRS, determine whether to apply half-year or mid-quarter convention, calculate Section 179 expensing, and determine bonus depreciation.

### Convention Decision Tree

```
Is more than 40% of personal property placed in service in Q4?
  → YES → Mid-Quarter Convention for ALL personal property
  → NO → Half-Year Convention for personal property

Real Property? → ALWAYS Mid-Month Convention
```

### 🧠 Mnemonic: **"Personal = HALF (or Quarter if 40% in Q4), Real = MONTH"**

### Section 179 Quick Rules (2023)

| Rule | Amount |
|------|--------|
| Maximum deduction | $1,160,000 |
| Phase-out begins | $2,890,000 |
| Dollar-for-dollar reduction above phase-out | Yes |
| Limited to taxable income | Yes (carryforward allowed) |
| Applies to | Tangible personal property, some real property improvements |

---

## 🥇 TBS #7: Schedule C Deductions (Document Review Simulation)

### ✅ What the Exam Asks

This is a **Document Review Simulation (DRS)** — you review a letter, memo, or schedule prepared by a staff accountant and correct errors. You click on underlined text and select the correct option.

### Most Commonly Tested Items

| Item | Key Rule |
|------|----------|
| **Business meals** | 50% deductible (was 100% for 2021-2022 restaurant meals only) |
| **Entertainment** | NOT deductible (post-TCJA) |
| **Home office** | Regular & exclusive use test; simplified method = $5/sq ft up to 300 sq ft |
| **Charitable contributions** | NOT deductible on Schedule C — goes on Schedule A |
| **Club dues** | NOT deductible (country clubs, social clubs, etc.) |
| **Business gifts** | $25 per person per year limit |
| **Auto expenses** | Actual method vs. standard mileage rate (67 cents/mile in 2024) |

🧠 **Top 1% Trap:** The exam loves to put charitable contributions in a sole proprietor's Schedule C. Charitable contributions are ALWAYS a personal itemized deduction on Schedule A, never a business deduction.

---

## 🥇 TBS #8-10: Quick Coverage

### Contract Formation & Statute of Frauds TBS

The exam gives you a scenario and asks which contracts must be in writing. 

🧠 **Mnemonic: "MY LEGS"**
- **M**arriage (promises in consideration of)
- **Y**ear (cannot be performed within 1 year)
- **L**and (sale or transfer of interest)
- **E**xecutor (promises to pay estate debts from personal funds)
- **G**oods ($500+ under UCC)
- **S**urety (promises to answer for another's debt)

### Tax Preparer Penalties TBS

| Penalty | Trigger | Amount |
|---------|---------|--------|
| Section 6694(a) | Unreasonable position | Greater of $1,000 or 50% of preparer income |
| Section 6694(b) | Willful/reckless conduct | Greater of $5,000 or 75% of preparer income |

🧠 **Standards Ladder (low → high):** Reasonable Basis → Substantial Authority → More-Likely-Than-Not

### Like-Kind Exchange TBS

Key numbers: **45 days** to identify replacement property, **180 days** to close.

Basis in new property = Basis of old property - Boot received + Gain recognized + Liabilities assumed on new property - Liabilities relieved on old property

---

## 📋 TBS Master Strategy Checklist

- [ ] **Read ALL exhibits first** before answering anything
- [ ] **Identify the chain** — what calculation feeds into the next?
- [ ] **Watch for traps:** FMV vs. basis, municipal bond interest, entertainment vs. meals
- [ ] **Fill in zeros** — never leave TBS cells blank
- [ ] **Track basis separately** for stock basis vs. debt basis in S-corp problems
- [ ] **Apply loss limitations in order:** Basis → At-Risk → Passive (BAP)
- [ ] **Check your math twice** on multi-step calculations
- [ ] **Use the order rule** for S-corp basis: Income → Distributions → Nondeductible → Losses
- [ ] **Practice 40-50 TBS minimum** before exam day
- [ ] **Time yourself** — 15-20 minutes per TBS

---

## 🎯 Exam Day Strategy from Top Rankers

1. **Do MCQs first, TBS second.** MCQs lock in your adaptive scoring early.
2. **Skip the hardest TBS and come back.** One TBS is a "pretest" (unscored) — don't waste 30 minutes on it.
3. **The last testlet is often the hardest.** Save energy and don't panic.
4. **For DRS (Document Review):** Read the ENTIRE document before clicking any underlined text.
5. **For calculations:** Write out the formula first, then plug in numbers. Don't shortcut.
6. **If stuck:** Eliminate what you know is wrong and make your best educated guess. Partial credit is awarded.

---

## 📚 Additional Resources

| Resource | Link |
|----------|------|
| USCPAREG Blog — Mastering Federal Taxation & Business Law | [uscpareg.blogspot.com](https://uscpareg.blogspot.com/?m=1) |
| Accounting Analytics CPA — AI Learning Tools & Flashcards | [accanalyticscpa.blogspot.com](https://accanalyticscpa.blogspot.com/?m=1) |
| AICPA Sample TBS (CPA Exam) | [aicpa.org](https://www.aicpa.org) |
| CPA Journal — Educator's Roadmap to TBS | [cpajournal.com](https://www.cpajournal.com/2025/03/10/an-accounting-educators-roadmap-to-task-based-simulations-on-the-new-uniform-cpa-examination-2/) |
| CPA Exam Guide — How to Pass REG | [cpaexamguide.com](https://www.cpaexamguide.com/section-guides/how-to-pass-reg-cpa-exam) |
