---
title: "Swiss Six-Month Crypto Rule: Why It Alone Won't Keep You Tax-Free"
date: 2020-09-14
lastmod: 2026-10-13
description: "Holding crypto six months does not make your Swiss gains tax-free — it is only 1 of 5 safe-harbour tests. The five SFTA criteria, the one that quietly catches active traders, and what reclassification really costs."
categories: ["holding"]
tags: ["switzerland crypto private investor status", "six month holding rule crypto", "SFTA KS 36", "professional trader classification switzerland", "swiss crypto tax safe harbour", "capital gains tax free switzerland"]
draft: false
readtime: 7
glossary:
  - term: "KS 36 / Kreisschreiben Nr. 36"
    def: "The Swiss Federal Tax Administration's Circular No. 36, issued July 2012, which defines the five safe-harbour criteria for distinguishing private asset management from professional securities trading. In December 2021, the SFTA formally confirmed that these criteria apply to cryptocurrency trading."
  - term: "Private investor (Privatanleger)"
    def: "The classification you want. A private investor's capital gains — including crypto capital gains — are completely tax-free in Switzerland. The classification is not guaranteed; it depends on your trading behaviour meeting the KS 36 safe-harbour criteria."
  - term: "Professional securities dealer (gewerbsmässiger Wertschriftenhändler)"
    def: "The classification you want to avoid. If the SFTA or cantonal tax authorities determine that your crypto activity constitutes professional trading, your capital gains are reclassified as taxable income — and AHV (Swiss social security) contributions may apply on top."
  - term: "AHV (Alters- und Hinterlassenenversicherung)"
    def: "Swiss old-age and survivors' insurance, the core component of Swiss social security. Professional traders are treated as self-employed for AHV purposes. The 2026 combined AHV/IV/EO rate for the self-employed is 10.0% on annual earned income of CHF 60,500 or more, with a degressive scale below that. (The 10.6% rate often quoted is the employee figure — employer and employee halves combined.) Private investors are not subject to AHV on their investment returns."
  - term: "Transaction volume threshold"
    def: "One of the five KS 36 safe-harbour criteria: the sum of all your crypto purchases and sales in a calendar year must not exceed five times the value of your crypto holdings at the start of that year. This criterion is easy to violate in volatile markets if you are actively rotating between positions."
sources:
  - name: "Swiss Federal Tax Administration — Kreisschreiben Nr. 36 (KS 36)"
    url: "https://www.estv.admin.ch/en/cryptocurrencies-taxation"
    desc: "ESTV — the federal working paper on crypto taxation, which applies the five safe-harbour criteria of Circular No. 36 (27 July 2012) to crypto-assets. Updated December 2021."
  - name: "Taxea.ch — Cryptocurrencies in the Swiss Tax Return"
    url: "https://www.taxea.ch/en/faq-taxes/cryptocurrencies-in-the-swiss-tax-return-how-to-declare-them"
    desc: "Taxea.ch — practical breakdown of how KS 36 criteria apply to crypto, including the holding period and transaction volume tests."
  - name: "Bucher Tax — From Crypto Trader to Securities Dealer?"
    url: "https://en.bucher-tax.ch/blog/vom-crypto-trader-zum-wertschriftenhandler"
    desc: "Bucher Tax — detailed analysis of when KS 36 criteria are difficult to meet for crypto traders, including the five cumulative requirements and their real-world challenges."
  - name: "AHV/IV — Contributions of self-employed persons (Merkblatt 2.02)"
    url: "https://www.ahv-iv.ch/p/2.02.d"
    desc: "Swiss social security information centre — official AHV/IV/EO contribution rates for self-employed persons, including the degressive scale below CHF 60,500."
  - name: "Taxolution — Capital Gains Tax Switzerland 2026: Tax-Free Rules"
    url: "https://www.taxolution.ch/swiss-tax-guide/tax-exemption-of-capital-gains/"
    desc: "Taxolution Advisory — current overview of the safe-harbour rules and how cantonal practice varies in applying them."
  - name: "Zug Notes — The Swiss Crypto Tax Advantage: Capital Gains Free, But Wealth Tax Is Real"
    url: "/posts/swiss-crypto-tax-advantage-guide/"
    desc: "Zug Notes — the Swiss crypto tax advantage pillar guide: the full framework: capital gains exemption, wealth tax structure, and private investor status in one place."
  - name: "Zug Notes — Staking Rewards in Switzerland: Why They're Taxed as Income (And What That Means for You)"
    url: "/posts/staking-rewards-swiss-income-tax/"
    desc: "Zug Notes — the staking rewards field note: how staking income interacts with private investor status, and why the income/capital gains distinction matters."
  - name: "Zug Notes — The Wealth Tax Calculation: How Switzerland Values Your Crypto Portfolio on New Year's Eve"
    url: "/posts/swiss-wealth-tax-crypto-calculation/"
    desc: "Zug Notes — the wealth tax calculation field note: wealth tax applies to all crypto holders regardless of investor status; how the December 31 portfolio valuation works."
---

> 📅 Last updated: October 2026
> The SFTA's professional-trader criteria read from Circular No. 36 and the federal crypto working paper, with the 2026 AHV rates.

The Swiss crypto tax headline is simple: capital gains are tax-free for private investors. Most people stop reading there.

What the headline omits is that "private investor" is not a default state. It is a classification you need to actively maintain — and the Swiss [Federal Tax Administration](https://www.estv.admin.ch/en) has published five specific criteria that determine whether you qualify.

The six-month holding rule is the most frequently cited of the five. It is also the most misunderstood. Holding for six months does not automatically make you a private investor. It is one condition among five, and failing any one of them can put your entire capital gains exemption at risk.

This field note covers all five criteria, what borderline cases actually look like, and why cantonal practice matters more than the written rules suggest.

## Why Classification Matters: The Tax Gap Between Private and Professional

Before getting into the criteria, it helps to understand what is actually at stake.

A private investor who sells CHF 500,000 worth of [Bitcoin](https://en.wikipedia.org/wiki/Bitcoin) at a gain: pays zero capital gains tax. None. The same outcome in Germany, France, or the UK would trigger a substantial tax bill.

The same person, reclassified as a professional securities dealer: pays income tax on those same gains. At Zug's marginal rates, that could be 18–25%. At Geneva's rates, closer to 40–43%. And on top of income tax, AHV contributions apply — 10.0% on the taxable income from trading, because a professional trader is self-employed in the eyes of Swiss social security.

The financial gap between the two classifications is significant. This is why the KS 36 criteria matter, and why cantons take reclassification seriously.

## The Five Safe-Harbour Criteria (KS 36)

The Swiss Federal Tax Administration's Kreisschreiben Nr. 36, issued in July 2012 and formally applied to crypto in December 2021, defines five conditions. Meeting all five creates a strong presumption of private investor status. These conditions are cumulative — the intent is that you need to satisfy all of them, not a majority.

{{< budget-table title="SFTA KS 36 — Five safe-harbour criteria for private investor status" >}}
| # | Criterion | What it means in practice |
|---|---|---|
| 1 | **Holding period ≥ 6 months** | Each position you sell must have been held for at least six months before the sale. Individual coin tracking matters here — FIFO or specific identification. |
| 2 | **Transaction volume ≤ 5× opening balance** | The sum of all purchases and sales in a calendar year must not exceed five times the value of your crypto portfolio at the start of that year. |
| 3 | **Capital gains < 50% of net income** | Your realized crypto gains for the year must not represent more than half of your total taxable income. If trading profits are your primary income source, this criterion fails. |
| 4 | **No debt financing** | You are not using borrowed money (loans, margin, leverage) to fund crypto positions. Or if you are, the income from your crypto assets exceeds the interest cost. |
| 5 | **Derivatives for hedging only** | Options, futures, and other derivatives are used only to hedge existing positions — not as standalone speculative instruments. |
{{< /budget-table >}}

<!-- IG-angle: Identifying which of the five cumulative criteria actually produces reclassifications — the six-month rule carries the name and the attention, but the transaction-volume test (5x opening balance, where every swap counts as both a sale and a purchase) is the one that catches active holders without warning; worked out from the arithmetic of the criteria themselves (a swap-heavy year multiplies volume fast), not from observing individual cases, which is not claimed -->

## Where People Actually Run Into Problems

The holding period criterion is the most visible, but on the arithmetic of the five tests it is not the one most likely to catch an active holder by surprise.

**The transaction volume criterion catches active traders.** If you started 2020 with CHF 100,000 in crypto and executed CHF 550,000 in combined purchases and sales during the year, you have exceeded the five-times threshold. This can happen faster than people expect during volatile markets when they are rotating between Bitcoin, ETH, and altcoins. Each swap is a sale plus a purchase — both sides count.

{{< num-highlight value="5×" label="The maximum transaction volume relative to your opening portfolio balance — above this, the volume criterion fails" >}}

**The income criterion catches people who had a very good year.** If your salary is CHF 80,000 and you realized CHF 50,000 in crypto gains, the gains represent roughly 62% of your total taxable income. That exceeds the 50% threshold. The criterion is designed to identify people for whom trading has essentially become their primary income source.

**The debt financing criterion catches leveraged traders.** If you took out a loan or used margin to fund crypto purchases, you are likely failing this criterion unless the yield from your crypto assets clearly exceeds the interest cost — which at the interest rates of the last few years is harder to demonstrate than it was in the near-zero era.

**The derivatives criterion catches anyone speculating on futures or options beyond simple hedges.** If you are actively trading perpetual futures or buying options for directional exposure, this is probably a failing criterion regardless of your holding period on spot positions.

## The Six-Month Rule in Practice: Per-Position, Not Portfolio-Wide

One clarification that often surprises people: the six-month holding requirement applies to each individual position you sell, not to your overall portfolio.

You cannot hold a diversified portfolio for two years and then sell a position you bought last month and claim the holding period is satisfied because "most of my portfolio has been held longer." The taxable event is the specific coins sold, and their individual acquisition date is what matters.

In practice, this means:
- If you use FIFO accounting, selling any amount means the oldest coins go first — which helps with the holding period.
- If you specifically identify coins to sell (a method some cantons allow), you can choose which acquisition dates apply to each sale.
- Staking rewards and airdropped tokens have their own acquisition dates from when they were received — which can complicate holding period tracking if you sell those positions.

{{< skip-box title="What about DCA (regular purchases)?" >}}
Dollar-cost averaging into a position over months creates multiple acquisition dates. If you buy small amounts of Bitcoin weekly for six months and then sell the entire position at month seven, only the earliest purchases meet the six-month threshold under strict FIFO. This is an area where using a crypto tax tool that tracks individual lot acquisition dates is worthwhile rather than trying to reconstruct from memory.
{{< /skip-box >}}

## Cantonal Practice: The Gap Between the Written Rule and Reality

Here is what the formal KS 36 documentation does not fully capture: cantonal application of these criteria is not uniform, and in several cantons, the safe-harbour thresholds are applied conservatively in ways that go beyond the literal text.

Published practitioner commentary, such as [Bucher Tax's analysis of when crypto traders become securities dealers](https://en.bucher-tax.ch/blog/vom-crypto-trader-zum-wertschriftenhandler), makes the same point: a canton can look at the overall picture of your trading activity, not just the five thresholds one by one. Frequency of trading, sophistication of strategy, use of professional tools, and whether you spend significant time on crypto activity can all factor into a cantonal tax office's assessment, even if each individual criterion technically passes.

Where income tax rates are higher — Geneva is the usual example — the same reclassification costs more in absolute terms.

The practical implication is that KS 36 is a safe harbour in the sense that clearly meeting all five criteria makes it very difficult for cantonal authorities to reclassify you. But borderline cases — where one criterion is close to the threshold, or where your overall activity pattern looks like systematic trading — create genuine uncertainty that the written thresholds alone do not resolve.

If you are actively managing a portfolio and want confidence about your classification, getting a written tax ruling (Ruling) from your cantonal tax office is the only way to get certainty before you file.

## The Interaction with Wealth Tax and Staking Income

Private investor status affects capital gains tax — it does not change your [wealth tax](https://en.wikipedia.org/wiki/Wealth_tax) obligations. Every crypto holder in Switzerland, regardless of classification, pays annual cantonal wealth tax on their portfolio value as of December 31st.

The [Swiss Crypto Tax Advantage guide](/posts/swiss-crypto-tax-advantage-guide/) covers the full structure: what qualifies for the capital gains exemption, how wealth tax works separately, and why the combination is still favorable compared to most European jurisdictions.

Staking income adds another layer. If you stake ETH while holding it as part of a long-term private investor strategy, the [staking](https://en.wikipedia.org/wiki/Proof_of_stake) rewards themselves are taxed as income — that part is unaffected by your private investor classification. The classification only matters for capital gains. The [staking income field note](/posts/staking-rewards-swiss-income-tax/) covers this distinction in detail.

Spending is the other everyday case. For a private investor, a gain on disposing of crypto is a tax-free private capital gain, so paying with a crypto card in Switzerland does not create the per-swipe taxable event it does in the US or UK. Each swipe is still a sale of crypto, though, so it counts toward the transaction-volume and holding-period tests above — the [crypto card field note](/posts/crypto-card-switzerland-tax-angle/) covers where that advantage stops.

And separately, the [wealth tax calculation field note](/posts/swiss-wealth-tax-crypto-calculation/) explains how the December 31st portfolio snapshot works, including the SFTA Kursliste reference rates — which applies to all crypto holders, private investors and professional traders alike.

## A Practical Summary

The "six-month rule" is shorthand for a more complete picture. For most long-term holders with a clear investment strategy and no leverage:

- Hold positions for at least six months before selling any of them
- Do not trade so actively that annual transaction volume exceeds five times your starting portfolio size
- Make sure crypto gains do not become your primary income source
- Avoid leverage and speculative derivatives

Meeting these conditions does not guarantee a clean classification in every cantonal dispute, but it gets you close to the safe-harbour zone the SFTA designed. The further you deviate — particularly on holding period and transaction volume — the more you look like a professional securities dealer under Swiss tax law, regardless of how you characterize your own activity.

The stakes are real. Capital gains tax-free is a meaningful structural advantage. Preserving it requires understanding the conditions it depends on.

---

*Not tax advice. Swiss tax treatment of crypto depends on individual circumstances, cantonal variation, and annual SFTA guidance. This field note describes the general framework as set out in published SFTA and cantonal guidance, reviewed through October 2026. Consult a qualified Swiss tax professional for your specific situation.*
