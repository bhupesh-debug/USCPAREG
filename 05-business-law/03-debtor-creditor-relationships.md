# 03 — Debtor-Creditor Relationships

## Overview

This module covers three major areas:
1. **Secured transactions** (UCC Article 9) — how creditors protect their loans with collateral
2. **Bankruptcy** — what happens when debtors can't pay
3. **Suretyship** — when a third party guarantees payment of a debt

---

## Part I: Secured Transactions (UCC Article 9)

### What Is a Secured Transaction?

A **secured transaction** is a loan or credit arrangement where the creditor (secured party) takes a **security interest** in the debtor's personal property (collateral) as protection against default.

✅ When you buy a car on credit, the bank keeps a "lien" on the car. If you stop making payments, they can take the car. That lien is a security interest — the bank is "secured." The loan is backed by collateral, not just your promise to pay.

**UCC Article 9 governs:** Security interests in personal property (NOT real property — real property uses mortgages governed by state real property law).

---

### 🧠 Mnemonic: "AVR" — Attachment Requirements

For a security interest to be **enforceable against the debtor**, three things must happen (attachment):

> **A**greement — security agreement authenticated/signed by debtor describing collateral  
> **V**alue — creditor must give value (loan funds, commitment to lend, past debt)  
> **R**ights — debtor must have rights in the collateral  

All three must occur for attachment. Order doesn't matter, but all are required.

---

### Attachment vs. Perfection

| Concept | What It Does | Who It Protects Against |
|---------|-------------|------------------------|
| **Attachment** | Makes security interest enforceable | Only the debtor |
| **Perfection** | Gives priority over other creditors | Third parties, other creditors, trustees in bankruptcy |

✅ Attachment is between you and your borrower. Perfection is about the whole world. Without perfection, if the borrower goes bankrupt, you might lose your security interest to the bankruptcy trustee.

---

### Methods of Perfection

| Method | When Used |
|--------|-----------|
| **Filing a financing statement (UCC-1)** | Most common; covers most personal property |
| **Possession** | Pledged collateral (jewelry, stocks, negotiable instruments) |
| **Control** | Deposit accounts, investment property |
| **Automatic perfection** | PMSI in consumer goods (see below) |

**Financing Statement (UCC-1) requirements:**
- Debtor's name (must be exact legal name)
- Secured party's name
- Description of the collateral

**Duration:** Financing statement effective for **5 years** from filing; can be continued by filing a continuation statement within 6 months before expiration.

---

### Purchase Money Security Interest (PMSI)

A **PMSI** arises when the secured party finances the purchase of the collateral itself.

| PMSI Type | Automatic Perfection? | Timing Rule |
|-----------|----------------------|------------|
| **PMSI in consumer goods** | **YES — automatic** at time of attachment | No filing needed |
| **PMSI in inventory** | **No** — must file before delivery | Must notify prior holders |
| **PMSI in other goods** | **No** — must file within **20 days** of debtor receiving collateral | Gets super-priority |

✅ When you buy furniture on credit from a furniture store, the store automatically has a perfected security interest in that furniture — no filing required. This is the automatic perfection for PMSI in consumer goods.

---

### Priority Rules

**General priority order:**

1. **Perfected secured creditors** (with earlier perfection date take priority over later perfected)
2. **Lien creditors** (judicial liens)
3. **Unperfected secured creditors**
4. **Unsecured creditors (general)**

**Special PMSI priority:**
- PMSI in inventory: beats earlier perfected creditors IF: (1) PMSI perfected before/when debtor gets collateral, AND (2) prior inventory lien holder notified in writing before delivery
- PMSI in non-inventory: super-priority over prior perfected security interests if perfected within 20 days of debtor receiving collateral

**Buyers in the ordinary course of business (BIOC):** A person who buys goods in the ordinary course of a seller's business **takes free** of the seller's security interest — even if the buyer knows of it.

---

## Part II: Bankruptcy

### Overview of Bankruptcy Chapters

| Chapter | Who Uses It | Purpose |
|---------|-------------|---------|
| **Chapter 7** | Individuals, businesses | **Liquidation** — sell assets, distribute to creditors, discharge remaining debts |
| **Chapter 11** | Businesses (and some individuals) | **Reorganization** — restructure debts while continuing operations |
| **Chapter 13** | Individuals with regular income | **Individual reorganization** — repay debts over 3-5 year plan |
| **Chapter 12** | Farmers and fishermen | Family farmer/fisherman reorganization |

✅ Chapter 7 is the "fresh start" option — you give up what you have, creditors get paid what they can, and the slate is wiped clean (for dischargeable debts). Chapter 13 is more like a payment plan — you keep your stuff but commit to paying back a portion over time.

---

### The Automatic Stay

**The automatic stay** kicks in the moment a bankruptcy petition is filed. It immediately **stops all collection actions** against the debtor:
- Lawsuits and judgments
- Foreclosures
- Wage garnishments
- Phone calls from creditors
- Repossessions
- IRS collection (generally)

✅ The automatic stay is like pressing a giant PAUSE button on everything the creditors are doing to collect. It gives the debtor breathing room to reorganize or let the bankruptcy process work.

**Relief from automatic stay:** Creditors can petition the bankruptcy court to "lift" the stay — for example, a secured creditor whose collateral is depreciating rapidly may be granted relief to repossess.

---

### Bankruptcy Estate — What's Included?

The bankruptcy estate includes:
- All legal and equitable interests of the debtor in property as of the petition date
- Property acquired within 180 days after filing by inheritance, life insurance proceeds, or divorce settlements
- Property the trustee recovers through avoidance powers (fraudulent transfers, preferences)

---

### Exempt Property (Chapter 7)

✅ Even in Chapter 7, debtors keep certain property. The government doesn't want people to be completely destitute after bankruptcy.

**Federal exemptions** (where states allow the federal list):
- Homestead equity (up to ~$27,900)
- Motor vehicle (up to ~$4,450)
- Household goods (~$700 per item)
- Jewelry (~$1,875)
- Life insurance cash value (~$14,875)
- Health aids (unlimited)
- Social Security, unemployment, veterans' benefits (unlimited)
- Retirement accounts (unlimited in most cases)

Many states have opted out of federal exemptions and provide their own lists.

---

### Discharge of Debts

**Chapter 7 discharge:** Eliminates personal liability for most debts. Discharge is granted after non-exempt assets are distributed to creditors.

**Chapter 13 discharge:** Broader than Chapter 7 (some debts dischargeable in 13 but not 7). Granted after completing the 3-5 year repayment plan.

---

### 🧠 Mnemonic: "FAST" — Non-Dischargeable Debts

> **F**raud — debts obtained by fraud or false pretenses  
> **A**limony and child support — domestic support obligations  
> **S**tudent loans — educational loans (unless undue hardship)  
> **T**axes — federal/state/local taxes due within 3 years of filing (and others)  

**Other non-dischargeable debts include:**
- Criminal fines and restitution
- DUI-related death/personal injury debts
- Willful and malicious injury to another person or property
- Debts from embezzlement, larceny, or fiduciary fraud
- Debts not listed in bankruptcy schedules (if creditor didn't know of bankruptcy)

✅ Even after bankruptcy, you still owe these debts. Student loans, back taxes, child support, and fraud-based debts follow you through bankruptcy and cannot be erased.

---

### Preferences (Avoidable Transfers)

The bankruptcy trustee can **avoid** (undo) transfers made before filing if they were **preferential**:

**Requirements:**
1. Transfer of debtor's property
2. To or for the benefit of a creditor
3. On account of an existing debt
4. Made while the debtor was insolvent
5. Within **90 days** before filing (or **1 year** for insider creditors)
6. That gives the creditor more than they would receive in Chapter 7 liquidation

✅ The preference rules prevent a debtor from paying their favorite creditors (like relatives) in the weeks before filing. The trustee can "claw back" those payments and distribute them equally to all creditors.

**Exceptions to preference rules:**
- Contemporaneous exchange for new value
- Payments in the ordinary course of business
- Enabling loans (PMSI)
- Domestic support obligations

---

## Part III: Suretyship

### Surety vs. Guarantor

| Type | Primarily Liable? | When Can Be Sued? |
|------|------------------|--------------------|
| **Surety** | **Yes** — primarily liable with the debtor | Immediately upon default; creditor doesn't have to try debtor first |
| **Guarantor** | **No** — secondarily liable | Only after creditor has made demand on debtor AND debtor has defaulted |

✅ A surety is like a co-signer on a loan — if you don't pay, the bank can immediately come after your co-signer without trying to collect from you first. A guarantor is more like a backup — they're only on the hook after the creditor has exhausted remedies against the primary debtor.

---

### 🧠 Mnemonic: Suretyship — "Surety = Simultaneous; Guarantor = Goes After"

> **Surety** can be sued at the same time as the debtor (simultaneous liability)  
> **Guarantor** can only be sued AFTER the creditor goes after the debtor first  

---

### Defenses Available to Surety

| Defense | Available to Surety? |
|---------|---------------------|
| **Real defenses** (fraud, duress, incapacity, illegality, payment) | **Yes** — can assert against creditor |
| **Personal defenses of the debtor** (breach of contract by creditor) | **Yes** — can assert the debtor's defenses |
| **Personal defenses of the surety** | Yes |
| **Modification of principal contract** (without surety's consent) | **Yes** — material modification releases surety |
| **Release of principal debtor** (without surety's consent) | Releases surety unless creditor reserves rights against surety |
| **Release of collateral** (without surety's consent) | Releases surety to the extent of the collateral value |

**Co-sureties and contribution:** When there are multiple sureties, each is liable for their proportionate share. If one surety pays more than their share, they have the right of **contribution** from the other co-sureties.

---

## Fair Debt Collection Practices Act (FDCPA)

**Applies to:** Third-party **debt collectors** (not original creditors collecting their own debts).

### Prohibited Practices

| Category | Prohibited Acts |
|---------|----------------|
| **Harassment** | Threats of violence, obscene language, repeated calls to annoy |
| **False representations** | Misrepresenting amount owed, misrepresenting as attorney/government, threatening legal action not authorized |
| **Unfair practices** | Collecting unauthorized fees, threatening to take non-exempt property, depositing post-dated checks early |

### Consumer Rights Under FDCPA

| Right | Rule |
|-------|------|
| **Validation of debt** | Collector must provide within 5 days of first contact; 30-day window to dispute |
| **Cease communication** | Consumer can demand in writing; collector must stop (except to confirm cessation or file suit) |
| **Time restrictions** | Can only call between **8 AM and 9 PM** at consumer's local time |
| **Work restrictions** | Cannot call at work if consumer says employer prohibits it |
| **Attorney contact** | If consumer has an attorney, must contact attorney instead |

**Penalty for violation:** Up to $1,000 per action + actual damages + attorney fees

---

## Exam Tips

> **Tip 1:** **Automatic perfection** only applies to PMSI in **consumer goods** — not commercial goods. A PMSI in inventory requires a UCC-1 filing AND prior notification to existing inventory lienholders.

> **Tip 2:** The **"FAST" non-dischargeable debts** are the most tested: Fraud, Alimony/child support, Student loans, Taxes. Know these cold — they appear in almost every bankruptcy question.

> **Tip 3:** **Priority rules for creditors:** Perfected secured > lien creditors > unperfected secured > unsecured. BIOC (buyer in ordinary course) takes free of the security interest even with knowledge.

> **Tip 4:** **Preferences** look back 90 days (or 1 year for insiders). The trustee must prove the debtor was insolvent at the time. Insolvent is presumed for the 90 days before filing.

> **Tip 5:** A **surety** can be sued immediately upon the debtor's default — no need to first exhaust remedies against the debtor. A **guarantor** can only be pursued after trying the primary debtor.

> **Tip 6:** Material **modification of the debt without the surety's consent** releases the surety from liability. This is a classic exam trap — creditor and debtor quietly change the terms, and the surety walks free.
