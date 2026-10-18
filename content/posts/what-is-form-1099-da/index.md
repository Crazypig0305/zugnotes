---
title: "What Is Form 1099-DA? The Crypto Tax Form, Explained Box by Box"
date: 2026-10-18
lastmod: 2026-10-18
description: "Form 1099-DA is the IRS form US crypto brokers send for your digital asset sales. What it reports for 2025 and 2026 sales, what each box means, and how it maps onto Form 8949."
categories: ["holding"]
tags: ["Form 1099-DA", "what is 1099-da", "crypto tax form", "Form 8949", "digital asset broker reporting", "cost basis", "IRS crypto", "US crypto tax"]
draft: false
readtime: 10
glossary:
  - term: "Form 1099-DA"
    def: "Digital Asset Proceeds From Broker Transactions. An IRS information return that US digital asset brokers file with the IRS and send to customers for each sale of crypto they handle. It first covered sales made in 2025."
  - term: "Covered security (for Form 1099-DA)"
    def: "A digital asset acquired after 2025 in an account where the broker provided custody, and held in that account until the broker sold it. For these, the broker must report your cost basis to the IRS."
  - term: "Noncovered security"
    def: "Any digital asset that is not a covered security — for example, crypto bought before 2026, or crypto you transferred into the broker from another wallet. The broker reports the sale proceeds but does not have to report basis."
  - term: "Cost basis"
    def: "What you paid for the asset, including allowable costs. Gain or loss is proceeds minus basis. If the 1099-DA leaves basis blank, the job of proving it falls to you and your own records."
  - term: "Form 8949"
    def: "The IRS form where you list each sale of a capital asset before totals go onto Schedule D. From the 2025 tax year it has separate boxes (G to L) for digital asset transactions."
sources:
  - name: "IRS — About Form 1099-DA, Digital Asset Proceeds From Broker Transactions"
    url: "https://www.irs.gov/forms-pubs/about-form-1099-da"
    desc: "irs.gov — current form, instructions, and recent developments"
  - name: "IRS — Instructions for Form 1099-DA (2026)"
    url: "https://www.irs.gov/instructions/i1099da"
    desc: "irs.gov — 2026 instructions: covered vs noncovered securities, de minimis rules ($10,000 qualifying stablecoins, $600 specified NFTs and payment processors), box-by-box guidance"
  - name: "IRS — Instructions for Form 1099-DA (2025)"
    url: "https://www.irs.gov/pub/irs-prior/i1099da--2025.pdf"
    desc: "irs.gov — 2025 instructions: gross proceeds mandatory, basis reporting not required for sales effected in 2025"
  - name: "IRS — Instructions for Form 8949 (2025)"
    url: "https://www.irs.gov/pub/irs-pdf/i8949.pdf"
    desc: "irs.gov — new boxes G, H, I (short-term) and J, K, L (long-term) for digital asset transactions"
  - name: "IRS — Notice 2025-33"
    url: "https://www.irs.gov/pub/irs-drop/n-25-33.pdf"
    desc: "irs.gov — extends backup withholding relief to digital asset sales in calendar year 2026"
  - name: "IRS — Publication 1099 (2026), General Instructions for Certain Information Returns"
    url: "https://www.irs.gov/pub/irs-pdf/p1099.pdf"
    desc: "irs.gov — recipient statement for Form 1099-DA due February 15 of the following year"
  - name: "IRS — Revenue Procedure 2024-28"
    url: "https://www.irs.gov/pub/irs-drop/rp-24-28.pdf"
    desc: "irs.gov — safe harbor for allocating unused basis to each wallet or account as of 1 January 2025"
  - name: "Congress.gov — H.J.Res. 25 (Public Law 119-5)"
    url: "https://www.congress.gov/bill/119th-congress/house-joint-resolution/25"
    desc: "congress.gov — April 2025 disapproval of the IRS rule on brokers effectuating digital asset sales (the DeFi broker rule)"
---

<!-- IG-synthesis: Read from the IRS's own 2025 and 2026 Instructions for Form 1099-DA, the 2025 Instructions for Form 8949, Notice 2025-33 and Publication 1099; the year-by-year table and the 1099-DA-to-8949 mapping are assembled from those documents, and the two worked examples use invented round numbers to show the mechanics. No first-hand filing experience is claimed. -->

> 📅 Last updated: 18 October 2026
> Checked against the IRS's 2026 Instructions for Form 1099-DA (dated February 2026) and the irs.gov form page on 18 October 2026.

Form 1099-DA is the tax form a US crypto broker sends you, and the IRS, for every sale of digital assets it handled for you during the year. Its full name is "Digital Asset Proceeds From Broker Transactions." The first ones covered sales made in 2025 and showed only what you received. For sales from 1 January 2026 onward, brokers must also report what you paid — your cost basis — for crypto you bought on that platform after 2025 and kept there until you sold.

If you sell crypto through a US exchange in 2026, expect a 1099-DA in early 2027. The recipient copy is due by 15 February of the following year under the IRS's [Publication 1099](https://www.irs.gov/pub/irs-pdf/p1099.pdf). It does not tell you how much tax you owe. It tells the IRS what your broker saw, and your return has to reconcile with it.

---

## What Form 1099-DA Covers — and What It Does Not

The 2026 instructions define a sale broadly: swapping crypto for dollars, for "different digital assets," or for services provided by the broker all count. So a crypto-to-crypto trade on an exchange is a reportable sale, not just a cash-out.

Three limits matter for an ordinary holder:

- **Only US brokers file it.** The instructions say: "Generally, only a U.S. digital asset broker is required to report on Form 1099-DA." A platform outside the US generally will not send you one.
- **Wallet software alone is not a broker.** Under the instructions, a business is not a digital asset middleman if it "only provide[s] hardware or software... that permits users to control private keys," without other services.
- **DeFi front-ends are out.** A separate IRS rule that would have made some decentralized-finance front-ends report as brokers was disapproved by Congress and signed as [Public Law 119-5](https://www.congress.gov/bill/119th-congress/house-joint-resolution/25) on 10 April 2025.

There are also small-amount thresholds. Under the [2026 instructions](https://www.irs.gov/instructions/i1099da), a broker using the optional method for stablecoins does not have to report your stablecoin sales if they total $10,000 or less for the year; the equivalent line for specified NFTs is $600, and payment processors have their own $600 threshold.

{{< num-highlight value="$10,000" label="Stablecoin de minimis per broker, per year" note="optional reporting method; above it, all are reported" >}}

{{< num-highlight value="Feb 15" label="Recipient copy due" note="of the year after the sales" >}}

---

## The Year-by-Year Timeline

This is the table most explanations leave out. What appears on your 1099-DA depends on the year you sold and when and where you bought.

{{< budget-table title="Form 1099-DA by sale year" sub="From the IRS 2025 and 2026 instructions and Notice 2025-33" >}}
| Sales made in… | Form arrives | Proceeds reported? | Cost basis reported? | Backup withholding |
|---|---|---|---|---|
| 2025 | Early 2026 | Yes, mandatory | Not required; broker may add it voluntarily | Not required (Notice 2025-33) |
| 2026 | Early 2027 | Yes, mandatory | Yes for covered securities (bought on that platform after 2025 and kept there); optional for everything else | Not required for 2026 sales (Notice 2025-33) |
| 2027 and later | Early 2028 onward | Yes, mandatory | Same covered / noncovered split | Can apply if the broker lacks a certified TIN for you; limited 2027 relief for pre-existing customers (Notice 2025-33) |
{{< /budget-table >}}

The backup-withholding row is the one people miss. Notice 2025-33 states that backup withholding "will not be required on any digital asset sale effected by a broker during calendar year 2025 or calendar year 2026." That relief runs out for 2027 sales. If a US platform has asked you for a Form W-9, that is why.

---

## Covered vs Noncovered: Why Your Basis Box May Be Blank

The single most confusing thing about a 1099-DA is a blank cost-basis box next to a large proceeds figure. It is usually not an error.

The 2026 instructions call a digital asset a covered security only if it was "acquired in an account for which the broker provided custodial services and was held in that account until the broker effects the disposition." Everything else is noncovered, and the instructions list the usual cases:

- crypto **acquired before 2026**;
- crypto **transferred in** to the broker from another wallet or platform;
- crypto the broker did not hold in custody when you acquired it.

For noncovered sales the broker may tick box 9 and leave the basis blank. Your gain is still real; the IRS simply expects the basis to come from your own records. That is also why basis on a 1099-DA can differ from what a portfolio tracker shows: a broker only sees the lots in its own account. The IRS's [Rev. Proc. 2024-28](https://www.irs.gov/pub/irs-drop/rp-24-28.pdf) gave holders a safe harbor for allocating their unused basis to the digital assets held in each wallet or account as of 1 January 2025 — in other words, basis now travels with the account the asset sits in.

---

## Form 1099-DA Explained, Box by Box

The boxes a holder actually needs, with what each one means and where it goes. Box descriptions follow the [2026 instructions](https://www.irs.gov/instructions/i1099da).

{{< budget-table title="Reading a 1099-DA" sub="Boxes that matter to an individual holder" >}}
| Box | What it shows | What to do with it |
|---|---|---|
| Applicable checkbox on Form 8949 | A letter: G (short-term, basis reported), H (short-term, basis not reported), J (long-term, basis reported), K (long-term, basis not reported), Y (holding period unknown) | Tells you which box to tick on Form 8949 |
| 1a / 1b | Token code and name | Match each form to the asset in your records |
| 1c | Units sold, to 18 decimal places | Check against your own transaction history |
| 1d / 1e | Date acquired / date sold | 1d may be blank for noncovered sales or mixed lots |
| 1f | Proceeds — already reduced by transaction fees | Goes in column (d) of Form 8949 |
| 1g | Cost basis | Column (e) if box 2 is checked; if blank, use your own records |
| 2 | Basis reported to IRS | Checked = the IRS already has the basis figure |
| 4 | Federal income tax withheld | Backup withholding, if any; claim it on your return |
| 6 | Short-term / long-term / ordinary | Sets Part I or Part II of Form 8949 |
| 9 | Noncovered security | Checked = broker was not required to report basis |
| 11a–11c | Optional aggregate reporting | Stablecoins or NFTs reported as one total |
| 12a / 12b | Units and date transferred in | Clue that the basis must come from your earlier records |
{{< /budget-table >}}

---

## From 1099-DA to Form 8949: Two Worked Examples

Form 8949 gained six digital-asset boxes for the 2025 tax year. The [2025 instructions](https://www.irs.gov/pub/irs-pdf/i8949.pdf) say digital asset transactions "should not be reported using box C or F" and should use boxes G, H or I for short-term and J, K or L for long-term. The examples below use invented round numbers.

**Example 1 — covered, short-term.** You buy 0.5 ETH on a US exchange in March 2026 for $1,800 including the fee, and sell it there in September 2026 for $2,100, paying a $5 fee. Your 1099-DA should show proceeds of $2,095 in box 1f (the instructions require proceeds net of transaction costs), $1,800 in box 1g, box 2 checked, and code G. On Form 8949 you tick box G in Part I and report a $295 gain.

**Example 2 — noncovered, long-term.** You bought 0.1 BTC in 2021, moved it to a US exchange in 2024, and sold it there in 2026 for $9,000. Because it was acquired before 2026 and transferred in, the broker may tick box 9, leave box 1g blank and use code K. On Form 8949 you tick box K in Part II, enter $9,000 in column (d), and enter your 2021 purchase cost from your own records in column (e). If you cannot document that cost, the proceeds on the form are what the IRS sees.

If you sold crypto somewhere that sent no 1099-DA — a non-US platform, or a direct wallet-to-wallet sale — the sale still goes on Form 8949, using box I (short-term) or box L (long-term).

---

## What to Do Before Your Form Arrives

- **Export your full history now** from every platform you used, including ones you have left. A 1099-DA only covers the platform that issued it.
- **Find the original cost of anything you transferred in.** Those are the sales most likely to arrive with a blank basis.
- **Answer the W-9 request** if a US platform sends one; backup withholding relief ends with 2026 sales.
- **Compare each 1099-DA line to your records in February**, not in April. A broker can issue a corrected form; that takes time.
- **Keep the wallet-by-wallet view.** Basis follows the account the asset sits in, which is how the broker sees it too.

---

## If You Hold Crypto Outside the US

The 1099-DA is a US domestic form. For holders whose platforms are elsewhere, the reporting that matters is different. Outside the US, the main international framework is the OECD's Crypto-Asset Reporting Framework, under which platforms collect data for tax authorities to exchange with each other — see [what CARF actually reports about you](/posts/carf-individual-reporting-crypto/). Switzerland, for one, has postponed its start to 1 January 2027 at the earliest; the [CARF delay explained](/posts/switzerland-carf-delay-2027/) covers why. If you file in Switzerland, the closer equivalent to this note is [declaring crypto on a Swiss tax return](/posts/declaring-crypto-swiss-tax-return/). And if you are following the US side of crypto rules more broadly, the market-structure bill is a separate story: [what the CLARITY Act is](/posts/what-is-the-clarity-act/).

---

## What to Track Next

- **The 2027 instructions**, usually published late in the year; they will show any change for the first year without backup-withholding relief.
- **Corrections on irs.gov's Form 1099-DA page.** The IRS posted corrections to the 2025 instructions in January 2026; the "Recent developments" list on the [form page](https://www.irs.gov/forms-pubs/about-form-1099-da) is the place to check.
- **Your own first basis-reporting form** in early 2027 — the first one where covered-security basis is mandatory.

---

## Frequently Asked Questions

**What is Form 1099-DA?**

It is the IRS information return a US digital asset broker files for each crypto sale it handles for you, with a copy sent to you. It reports proceeds and, for sales from 2026 of assets bought and held on that platform after 2025, your cost basis.

**When will I get a 1099-DA?**

By 15 February of the year after the sales, under IRS Publication 1099. Sales made in 2026 will appear on forms sent in early 2027.

**Why is the cost basis missing on my 1099-DA?**

For 2025 sales, brokers were not required to report basis at all. For 2026 sales, basis is required only for covered securities — crypto acquired after 2025 in that broker's custody and held there until sold. Crypto bought before 2026 or transferred in from elsewhere is noncovered, so the basis box may be blank and you supply it from your records.

**Do I need to report crypto if I did not get a 1099-DA?**

The form is a report of what a broker saw, not the trigger for your obligation. Sales without a 1099-DA still go on Form 8949, in box I (short-term) or box L (long-term).

**Is a transfer between my own wallets on a 1099-DA?**

A transfer between your own wallets is not in the instructions' list of sales, which covers dispositions for cash, other digital assets, services, or certain property. When crypto is transferred into a broker, the 1099-DA for its later sale shows the units and date in boxes 12a and 12b.

---

## What I Take Away

The 1099-DA is less a new tax than a new witness. Crypto sales were always reportable; what changed is that a US broker now tells the IRS about them, and from 2026 sales it tells the IRS what you paid too — but only for the lots it can see. The gap between what the broker sees and what you actually did is where most mistakes will happen, and closing it is a records job you can start before the form arrives.

*This is a field note, not tax, investment or legal advice. Rules described are those in the IRS's 2025 and 2026 instructions as of 18 October 2026; check irs.gov and a qualified tax professional for your situation.*
