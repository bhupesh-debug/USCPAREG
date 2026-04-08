# 02 — S Corporations

## What Is an S Corporation?

An **S corporation** is a corporation that has made a special election to be taxed as a **pass-through entity**. Income, losses, deductions, and credits flow through to shareholders and are reported on their individual returns. The corporation itself pays no federal income tax (with a few exceptions).

✅ An S corp is like a regular corporation with a "tax transparency" superpower. The company itself doesn't pay federal income tax — instead, the profits and losses pass through to the owners' personal tax returns, just like a partnership. This avoids the double taxation problem of C corporations.

---

## 🧠 Mnemonic: "S-QUID" — S Corporation Eligibility Requirements

> **S**mall corporation (≤ 100 shareholders)  
> **Q**ualified shareholders only (US citizens/resident aliens, certain trusts/estates)  
> **U**S domestic corporation only  
> **I**ndividual/trust shareholders (no corporations, no partnerships as shareholders)  
> **D**omestic corporation (must be incorporated in the US)  
> One class of **S**tock only  

---

## S Corporation Eligibility Requirements

A corporation can elect S status only if ALL of the following are met:

| Requirement | Rule |
|------------|------|
| **Number of shareholders** | **100 or fewer** (family members may be treated as one shareholder) |
| **Type of shareholders** | US citizens and resident aliens; certain trusts; estates. **No nonresident aliens, corporations, or partnerships** |
| **Type of corporation** | Domestic corporation only (not LLC electing corp treatment in all cases) |
| **Classes of stock** | **Only one class of stock** (differences in voting rights are permitted; differences in economic rights are not) |
| **Eligible corporation** | Cannot be a financial institution using reserve method, an insurance company, a DISC, or certain other entities |

---

## Making the S Election

| Rule | Detail |
|------|--------|
| **Form** | File Form 2553 |
| **Timing** | Must file by the **15th day of the 3rd month** of the tax year for the election to be effective that year ("2.5-month rule") |
| **Late election** | IRS may grant relief for late elections if reasonable cause shown |
| **Who must consent** | ALL shareholders (both current and prior-year if election is retroactive) |

✅ The 2.5-month rule means: if you want S corp status for 2024, you need to file by March 15, 2024. After March 15, you can only get S status starting in 2025 (unless you get IRS relief).

---

## Termination of S Status

S status terminates if:

1. **Voluntary revocation** — majority of shareholders consent; effective prospectively (or retroactively if specified date is within the tax year)
2. **Ceasing to be eligible** — exceeding 100 shareholders, adding an ineligible shareholder, creating a second class of stock
3. **Passive income test** — if the corporation has **accumulated C corporation earnings and profits (E&P)** AND **passive investment income > 25% of gross receipts** for 3 consecutive years

After an involuntary termination, there is a **5-year waiting period** before re-electing S status (unless IRS consents to earlier re-election).

---

## Pass-Through Taxation: How It Works

S corporations file an information return (Form 1120-S) but pay no corporate income tax. Each shareholder receives a **Schedule K-1** showing their share of:
- Ordinary business income or loss
- Separately stated items (capital gains, charitable contributions, credits, etc.)

✅ The S corp is like a pipe — money flows through it straight to the shareholders. The pipe itself doesn't pay taxes; the shareholders pay taxes on what flows through to them, whether or not they actually receive a cash distribution.

---

## Shareholder Basis Calculation

Shareholders track their **stock basis** to determine:
1. Whether losses can be deducted (can't deduct below zero basis)
2. Whether distributions are taxable

### Basis Ordering Rules

```
Starting Basis (initial investment or purchase price)
+ Additional capital contributions
+ Share of ordinary income
+ Share of separately stated income items
+ Share of tax-exempt income
− Distributions received (nontaxable to extent of basis)
− Share of nondeductible/noncapitalizable expenses
− Share of ordinary losses
− Share of separately stated loss/deduction items
= Ending Stock Basis (floor: zero)
```

**Critical ordering:** Increase basis for income items BEFORE decreasing for losses. Basis cannot go below zero.

✅ Think of stock basis as your "bank account" in the S corp. Income deposits money, distributions withdraw it, losses spend it. You can't spend more than you have — losses above your basis are suspended until you get more basis.

---

## 🧠 Mnemonic: "PAID" — Shareholder Basis Changes

> **P**lus: contributions + income items + tax-exempt income  
> **A**gainst (reduce): distributions paid out  
> **I**ncludes: none (S corps don't allocate debt to shareholders unlike partnerships)  
> **D**educt: losses and nondeductible items (in that order)  

**Key distinction from partnerships:** S corporation shareholders do NOT get basis for their share of corporate debt. Partners DO get basis for their share of partnership debt.

---

## Debt Basis

An S corp shareholder may also have **debt basis** (loans made directly by the shareholder to the corporation). Debt basis can also absorb losses if stock basis reaches zero.

```
Loss deductibility order:
1. First use stock basis
2. Then use debt basis
(Cannot go below zero on either)
```

---

## AAA — Accumulated Adjustments Account

The **AAA** tracks post-1982 undistributed S corporation income that has already been taxed to shareholders.

**Why it matters:** Distributions from AAA come out **tax-free** to shareholders (they already paid tax on this income).

### Distribution Ordering from S Corp with Prior C Corp E&P

| Order | Source | Tax Treatment |
|-------|--------|--------------|
| 1st | AAA | Tax-free (already taxed) |
| 2nd | Prior C corp E&P | **Taxable dividend** |
| 3rd | OAA (Other Adjustments Account) | Tax-free |
| 4th | Remaining stock basis | Tax-free return of basis |
| 5th | Excess over basis | Capital gain |

---

## Built-In Gains Tax (BIG Tax)

If a **C corporation converts to S status**, the built-in gains tax applies to:
- Pre-conversion appreciation on assets sold within **5 years** of S election

**Rate:** 21% (corporate rate) on the net recognized built-in gain
**Purpose:** Prevents corporations from converting to S status solely to avoid corporate-level tax on appreciated assets

---

## LIFO Recapture

If a C corporation using LIFO inventory converts to S status:
- Must include LIFO recapture amount in income in the last C corp year
- Paid ratably over 4 years

---

## Fringe Benefits for 2% Shareholders

**2% shareholders** (own more than 2% of S corp stock) are treated like **partners** for fringe benefit purposes:
- Cannot exclude employer-provided health insurance from income
- Health insurance premiums included in W-2 wages, BUT
- The 2% shareholder-employee CAN deduct the premiums as a self-employed health insurance deduction (above-the-line)

| Benefit | 2% S Corp Shareholder | Regular Employee |
|---------|----------------------|-----------------|
| Health insurance | Included in W-2; deductible as SE health | Excluded from income |
| Group term life (≤ $50K) | Included in income | Excluded |
| Dependent care FSA | Not eligible to exclude | Excluded up to $5,000 |
| Cafeteria plan benefits | Not eligible | Eligible |

---

## S Corporation vs. C Corporation Quick Comparison

| Feature | S Corporation | C Corporation |
|---------|--------------|--------------|
| Federal income tax | None (pass-through) | 21% flat rate |
| Double taxation | No | Yes (corp + shareholder) |
| Shareholder limit | 100 max | Unlimited |
| Eligible shareholders | US individuals/certain trusts | Anyone |
| Classes of stock | One only | Multiple allowed |
| QBI deduction | Shareholders eligible (20% of QBI) | Not applicable |
| Loss deductibility | Limited to basis | Not applicable to shareholders |
| SE tax | No SE tax on distributions | N/A |

---

## Exam Tips

> **Tip 1:** The S election deadline is the **15th day of the 3rd month** of the tax year — for calendar-year corps, that's **March 15**. A day late means the election applies the following year.

> **Tip 2:** S corp shareholders do **NOT** include their share of corporate debt in their basis. This is the critical difference from partnerships (where partners do get basis for their share of liabilities).

> **Tip 3:** The **built-in gains tax** applies for **5 years** after conversion from C to S (post-TCJA). Don't confuse with the old 10-year period from pre-TCJA law.

> **Tip 4:** Distributions reduce stock basis. If distributions exceed stock basis, the excess is a **capital gain**. This is different from partnerships where distributions can reduce basis to zero first.

> **Tip 5:** The **one class of stock** rule allows differences in voting rights (voting vs. nonvoting shares are OK), but you cannot have different economic rights (like preferred stock with priority dividends).

> **Tip 6:** Fringe benefits for **2% shareholders** are treated differently. Health insurance premiums are taxable wages to the shareholder BUT are deductible by the shareholder above-the-line as SE health insurance.
