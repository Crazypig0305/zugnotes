---
title: "The Swiss Crypto Tax Advantage: Capital Gains Free, But Wealth Tax Is Real — A Plain-Language Guide"
date: 2024-08-12
lastmod: 2026-05-03
description: "Switzerland exempts private investors from crypto capital gains tax — that part is real. But wealth tax applies to your entire crypto portfolio every December 31st, staking income is taxed as ordinary income, and staying classified as a private investor takes active attention. A plain-language field guide to all three."
categories: ["holding"]
tags: ["swiss crypto tax", "capital gains", "wealth tax", "private investor status", "staking income", "SFTA", "canton zug"]
draft: false
image: hero.jpg
readtime: 14
glossary:
  - term: "SFTA / FTA / ESTV"
    def: "Swiss Federal Tax Administration (in German: Eidgenössische Steuerverwaltung, ESTV). The federal body that publishes official crypto reference values each year, used to calculate wealth tax across all Swiss cantons. Also referred to informally as the FTA."
  - term: "Private investor status"
    def: "The classification that makes your crypto capital gains tax-free in Switzerland. If you meet the SFTA's five safe-haven criteria — six-month minimum holding, no debt financing, transaction volume below five times opening balance, gains below 50% of taxable income, and derivatives for hedging only — you qualify. If you don't, you may be reclassified as a professional trader."
  - term: "Wealth tax (Vermögenssteuer)"
    def: "An annual cantonal tax on net assets — property, bank accounts, securities, and crypto — calculated on December 31st of each tax year. Switzerland is one of the few countries that still levies a broad wealth tax. Rates range from roughly 0.05% to 1% depending on canton and asset size, applied to the net total above the cantonal allowance."
  - term: "Professional trader"
    def: "The classification you want to avoid. Under Swiss tax law, if your crypto activity is frequent, systematic, and constitutes a significant part of your income or lifestyle, cantonal authorities can reclassify you as a professional trader — making your capital gains fully taxable as income."
  - term: "Six-Month Rule"
    def: "One of the five SFTA safe-haven criteria for private investor status. Holding crypto assets for at least six months before selling is the most commonly cited rule, but it is only one of five — meeting all five provides the strongest protection. See H05 for a dedicated field note on this rule."
  - term: "Staking income"
    def: "Rewards earned from locking crypto assets on a proof-of-stake network, or from delegating to a staking pool. In Switzerland, staking rewards are treated as taxable capital income (Kapitalertrag), not as capital gains. They are taxed as ordinary income in the year they are received, at market value on the date of receipt."
  - term: "SFTA rate list"
    def: "The annual list of official crypto reference values published by the Swiss Federal Tax Administration for December 31st of each tax year. These are the prices cantonal tax offices use to calculate your wealth tax. Bitcoin's official SFTA rate on December 31, 2024 was CHF 88,060 (2024 figure); the 2023 year-end reference rate was CHF 37,006. Cantons may accept coinmarketcap.com for assets not listed."
sources:
  - name: "Swiss Federal Tax Administration — Circular No. 36 (Tax Treatment of Crypto)"
    url: "https://www.estv.admin.ch/estv/en/home/direct-federal-tax/directives-circulars/circulars/2022/2-36-2022.html"
    desc: "ESTV — the primary legal basis for crypto taxation in Switzerland, including the five safe-haven criteria for private investor status"
  - name: "SFTA Official Crypto Rate List 2024"
    url: "https://www.estv.admin.ch/estv/en/home/direct-federal-tax/directives-circulars/kursliste.html"
    desc: "ESTV — official December 31 reference values used by all Swiss cantons for wealth tax calculation"
  - name: "Crypto Valley Journal — Swiss Crypto Tax 2025: FTA Rate List and Tax Return"
    url: "https://cryptovalleyjournal.com/focus/background/crypto-taxes-switzerland-2025-fta-rate-list-and-tax-return/"
    desc: "Crypto Valley Journal — detailed breakdown of SFTA rate list methodology and cantonal variation, published 2025"
  - name: "RSM Switzerland — Cryptocurrencies for Individuals"
    url: "https://www.rsm.global/switzerland/en/service/tax-and-legal/cryptocurrencies-taxation/cryptocurrencies-for-individuals"
    desc: "RSM Switzerland — professional tax advisory overview of private investor criteria and income classification rules"
  - name: "Blockpit — Switzerland Crypto Tax Guide 2026"
    url: "https://www.blockpit.io/tax-guides/crypto-tax-guide-switzerland"
    desc: "Blockpit — comprehensive 2026 guide covering wealth tax rates by canton, staking income classification, and SFTA valuation methodology"
  - name: "Reichlin Hess — Canton Tax Rates 2025: Zug, Lucerne, Zurich, Schwyz"
    url: "https://www.reichlinhess.ch/en/2025/03/05/corporate-tax-rates-and-tax-rates-for-individuals-for-2025-in-the-cantons-zug-lucerne-zurich-and-schwyz/"
    desc: "Reichlin Hess law firm — official comparative tax rates for key Swiss cantons, 2025 data"
  - name: "The Swiss Crypto Tax Advantage — Related: FINMA Guidance 01/2026"
    url: "/posts/finma-crypto-guidance-01-2026/"
    desc: "Zug Notes — field note on FINMA's January 2026 custody rules, relevant to how crypto is held at Swiss institutions"
---

> 📅 Original post: August 2024 | Last updated: May 2026
> Swiss tax rules verified against SFTA Circular No. 36 and the 2025 FTA rate list. Canton-level wealth tax rates current as of 2025. Rules can change — treat this as a starting map, not a filing instruction.

The headline travels well: Switzerland does not tax capital gains on crypto.

That part is accurate. A private investor in Switzerland who buys ETH, holds it, and sells it at a profit pays zero tax on that profit. The gain is simply not subject to income tax or a separate capital gains levy. In a world where most developed countries are building increasingly aggressive crypto tax regimes, this is a genuine structural advantage.

The part that gets less airtime in the promotional summaries: you will pay wealth tax on the full market value of your portfolio every year, staking rewards are taxed as ordinary income when you receive them, and the "private investor" classification that makes the capital gains exemption possible is not automatic — it requires you to meet five specific criteria, and Swiss cantonal authorities do scrutinize high-volume traders.

This field note is the long version. It covers how the full tax picture actually works for someone holding crypto in Switzerland, where the canton-level differences matter most, and what the year-end December 31st valuation moment means in practice.

## Why Capital Gains on Crypto Are Actually Tax-Free Here

The exemption is not crypto-specific. It is a feature of how Switzerland has always treated private investment.

Under Swiss tax law, gains from the sale of private assets — stocks, bonds, real estate (with some cantonal exceptions), and crypto — are not taxed as income. This principle predates crypto by decades. The Swiss government extended it to digital assets via SFTA Circular No. 36, issued in 2022, which established the framework still in use today.

For a private investor, the logic is: you earned money, paid income tax on it, invested it as private capital, and the appreciation of that capital is not a new income event. The gain is yours, untaxed.

{{< num-highlight value="0%" label="Capital gains tax rate for private crypto investors" note="Switzerland — applies to spot buying/selling. Does not apply to staking rewards, mining income, or professional traders." >}}

This is structurally different from how most jurisdictions treat crypto. The United States taxes crypto capital gains (short or long term depending on holding period). Germany taxes gains on crypto held under a year. The UK has a capital gains tax allowance, then levies gains above it. Australia treats most crypto sales as taxable events.

Switzerland's private capital gains exemption is the real thing. The catch is the word "private" — and what it takes to qualify.

## The Five Criteria That Keep You a Private Investor

The SFTA's Circular No. 36 established five safe-haven criteria. Meeting all five gives you the strongest protection against reclassification as a professional trader. The criteria are:

**1. Minimum six-month holding period.** Each asset should be held for at least six months before sale. This is the most frequently cited rule, but it is not the only one. Selling within six months does not automatically make you a professional trader — it just means you lose one protective factor.

**2. No debt financing.** You must not borrow money to fund your crypto investments. Using leverage — whether through margin trading, crypto-backed loans used to buy more crypto, or external loans earmarked for crypto — disqualifies this criterion.

**3. Transaction volume below five times opening balance.** The total volume of your crypto trades in a given tax year should not exceed five times the value of your crypto portfolio at the start of that year. This is the criterion that catches systematic traders who turn over large volumes even without leverage.

**4. Realized gains below 50% of taxable income.** If your capital gains from crypto in a given year exceed half of your total taxable income from all sources, that signals professional-level activity to cantonal authorities.

**5. Derivatives only for hedging.** Using futures, options, or other derivatives is permissible if used to hedge existing positions. Using them as a primary trading strategy takes you outside the safe-haven rules.

{{< skip-box title="If you miss one criterion" >}}
Missing a single criterion does not automatically reclassify you as a professional trader — Swiss authorities look at the overall picture. But missing multiple criteria, or missing one consistently across multiple tax years, significantly increases the risk of reclassification. Canton Zug's tax office has historically been more tolerant than Zurich's for active crypto holders, but neither offers a written guarantee. If your activity is borderline, the right move is a ruling request (*Steuerruling*) to your cantonal tax authority before filing.
{{< /skip-box >}}

If you are reclassified as a professional trader, your net capital gains become fully taxable as business income — subject to both income tax and AHV (social security contributions, currently 10% for self-employed individuals). This is the scenario the capital gains exemption was designed to avoid.

## The Wealth Tax: What December 31st Actually Means

Here is the tax you will pay regardless of private investor status.

Switzerland levies a cantonal wealth tax (Vermögenssteuer) on net assets once per year. The taxable date is December 31st. Every crypto asset you hold at midnight on the last day of the year is included in your taxable wealth.

The SFTA publishes an official rate list (Kursliste) each year, typically in February or March following the close of the tax year. This list specifies the official CHF value of listed cryptocurrencies on December 31st — the values cantonal tax authorities are required to use.

For the 2024 tax year (filed in 2025): Bitcoin's official SFTA reference value on December 31, 2024 was CHF 88,060. Ethereum's was CHF 3,271. For cryptocurrencies not on the official list, most cantons accept documented market prices from platforms like coinmarketcap.com on that date.

{{< num-highlight value="Dec 31" label="The only date that determines your taxable crypto wealth" note="Hold or sell before midnight: that determines whether the position appears in your wealth tax declaration for that year." >}}

For 2023 (for historical context): Bitcoin's SFTA value was CHF 37,006. The practical implication: a holder who held through the end of 2023 and sold early 2024 would have declared wealth at the 2023 value, then sold at a significantly higher 2024 price — with zero capital gains tax on that difference.

**Wealth tax rates by canton.** The rate you pay on that December 31st value depends on where you live:

{{< budget-table title="Wealth tax comparison: selected Swiss cantons (2025)" sub="On CHF 500,000 net taxable wealth, single individual. Source: Reichlin Hess, 2025 cantonal rates." >}}
| Canton | Approximate wealth tax rate | Notes |
|---|---|---|
| Schwyz | ~0.20–0.25% | One of the lowest in Switzerland |
| Zug | ~0.21–0.30% | Progressive; lowest at lower wealth levels |
| Nidwalden | ~0.15–0.20% | Consistently among the lowest |
| Zurich | ~0.55–0.70% | Progressive; significantly higher than inner cantons |
| Geneva | ~0.65–0.85% | High cantonal rate plus municipal surcharge |
| Neuchâtel | ~0.85–1.00% | Among the highest in Switzerland |
{{< /budget-table >}}

Every canton also provides a tax-free allowance — the amount of net wealth below which no wealth tax is owed. Allowances typically range from CHF 50,000 to CHF 100,000 for single individuals, and from CHF 100,000 to CHF 200,000 for married couples. Amounts vary by canton.

The wealth tax applies to your net position: if you have crypto worth CHF 200,000 on December 31st and no debts, you declare CHF 200,000 in crypto assets (less any applicable allowance) and pay the cantonal rate on the net amount above the threshold.

## Staking Rewards: Not Capital Gains, Taxed as Income

This is the area where the most confusion lives.

Staking rewards — rewards earned for validating transactions on a proof-of-stake blockchain, or for delegating assets to a staking pool — are not treated as capital gains in Switzerland. They are classified as taxable capital income (Kapitalertrag).

The practical difference: capital gains are exempt for private investors. Capital income is taxable as ordinary income for everyone, including private investors.

Staking rewards must be declared in the year they are received, at their CHF market value on the date of receipt. If you receive 0.5 ETH in staking rewards in March 2025 when ETH is trading at CHF 2,800, you declare CHF 1,400 as income for the 2025 tax year — regardless of whether you sell the ETH or hold it. Your marginal income tax rate applies to that amount.

{{< num-highlight value="100%" label="Staking rewards subject to income tax" note="Classified as Kapitalertrag (capital income), not capital gains. Taxed at your marginal rate in the year received, at CHF value on date of receipt." >}}

If you subsequently sell those staked ETH at a profit, the capital gain on the appreciation above your cost basis (the CHF value when received) remains tax-free for private investors. The income event and the capital gains event are separate.

Liquidity mining rewards, lending interest, and yield farming returns are generally treated the same way — as income at time of receipt. Mining income (from proof-of-work networks) is also taxable income, though whether it constitutes self-employment income or capital income depends on the scale and systematic nature of the activity.

**What this means for stakers in Zug specifically:** The income tax rate in Zug is materially lower than in Zurich or Geneva. The effective combined rate (federal + cantonal + municipal) for a single individual earning CHF 100,000 in Zug is roughly 22–24%, compared to 30–35% in Zurich and upward of 40% in Geneva. For high-volume stakers, the canton of residence matters as much as the activity classification.

## How the December 31st Valuation Creates Real Planning Decisions

The combination of wealth tax and no capital gains tax creates a tax structure that rewards different behavior than most people expect.

In a typical capital-gains-tax jurisdiction, the incentive is to delay selling — defer the taxable event as long as possible. In Switzerland, there is no benefit to holding a position to defer a non-existent capital gains tax. Instead, the incentive runs in a different direction: the wealth tax creates a cost of holding that capital gains freedom does not eliminate.

A simple illustration: assume you hold BTC worth CHF 1 million on December 31st and your cantonal wealth tax rate is 0.30%. You owe CHF 3,000 in wealth tax on that position — regardless of whether you intend to sell in January. If BTC then falls 40% by March and you sell, you still paid wealth tax on the December peak value.

{{< skip-box title="The December 31st sell-before-year-end question" >}}
Some crypto holders in Switzerland deliberately reduce positions before December 31st to lower their taxable wealth. This is legal and common. The tax saving is direct: selling CHF 200,000 in crypto before year-end at a 0.30% wealth tax rate saves CHF 600 in wealth tax. The flip side: if you sell and then repurchase in January, you are resetting your holding period, which matters for the six-month private investor criterion. For active holders, these decisions require mapping both the wealth tax exposure and the private investor status implications simultaneously.
{{< /skip-box >}}

## Canton-Level Differences That Actually Matter for Crypto Holders

Switzerland's tax federalism means that effective tax rates vary significantly by location. For crypto-specific decisions, three distinctions matter most:

**Wealth tax rate.** As the table above shows, the difference between living in Zug or Schwyz versus Geneva or Neuchâtel can translate to a factor of 3–4x in annual wealth tax on the same portfolio. For someone holding CHF 2 million in crypto, this difference can be CHF 10,000–20,000 per year.

**Income tax rate.** Since staking rewards are taxed as income, the canton's income tax rate directly affects staking profitability. Zug and Schwyz have materially lower effective income tax rates than Zurich, Geneva, or Basel.

**Cantonal tolerance for active holders.** There is no published guidance on this, but practitioners with experience in multiple cantons consistently note that Zug's tax office has historically been more familiar with — and tolerant of — active crypto holders than inland Swiss cantons. Zurich's Steueramt is known to scrutinize high-transaction-volume filers more aggressively. This is anecdotal and cantonal personnel change, but it is part of why crypto infrastructure concentrates in Zug rather than Zurich.

**No canton makes you immune.** This is worth stating directly. No Swiss canton exempts you from the federal wealth tax component, and no location protects you if you clearly cross the professional trader threshold. The cantonal advantages are real but bounded.

## Crypto Not on the SFTA List: How to Declare It

The SFTA rate list covers the major cryptocurrencies — Bitcoin, Ethereum, and some others. For tokens, DeFi positions, NFTs, and smaller assets, the approach is:

- Use the documented market price on December 31st from a reputable source (coinmarketcap.com is widely accepted by cantonal offices).
- Keep records of the source and the timestamp. Cantons do not always specify a format, but a screenshot with date, platform, and CHF conversion provides a clear audit trail.
- For illiquid or non-market assets (early-stage tokens with no exchange pricing, locked vesting positions, NFTs with no recent sales), the valuation is less clear. Cantonal practice varies. Getting a written ruling in advance is advisable for significant positions.

**Wrapped tokens and DeFi positions:** Generally valued at the market value of the underlying asset on December 31st. If you hold wBTC, you declare its CHF value at the BTC rate. If you hold a liquidity pool position on a DEX, you declare the CHF value of your proportional share of the pool's assets. The layer of complexity here is real — and it is one reason Swiss crypto holders with active DeFi positions increasingly use software to track position values at specific dates.

## The Two Tools Most Swiss Crypto Holders Use for Compliance

Tracking cost basis, year-end valuations, staking income (valued on receipt date), and the transaction volume criteria for private investor status across multiple wallets and exchanges is genuinely complex. The manual approach — building a spreadsheet covering every transaction with CHF values at each date — works but scales poorly.

Two platforms are widely used in Switzerland specifically because they support Swiss tax reporting requirements:

[Koinly](https://koinly.io/guides/switzerland-crypto-tax-guide/) generates Swiss-compatible tax reports including the wealth tax declaration support and income breakdowns by category. It handles the SFTA rate list integration for major assets.

[Blockpit](https://www.blockpit.io/tax-guides/crypto-tax-guide-switzerland) offers similar functionality with explicit Swiss cantonal breakdown support and automated SFTA reference value matching for December 31st positions.

Neither is a substitute for a qualified Swiss tax advisor for complex situations (professional trader threshold, significant DeFi positions, multi-canton residency). Both are useful for building the transaction history that any advisor will need to work with.

## Frequently Asked Questions

**Does the six-month rule mean I definitely pay capital gains tax if I sell before six months?**

No. Selling before six months does not automatically make you a professional trader — it means you lose one of the five safe-haven criteria. Swiss cantonal authorities look at the totality of your activity. A single short-term sale of a small position is unlikely to trigger reclassification. A pattern of high-volume, short-duration trades — especially combined with leverage or where gains exceed 50% of your income — creates much more risk. The six-month rule is a factor in a multi-factor analysis, not a bright-line trigger.

**What happens to crypto held at a Swiss bank or custodian for wealth tax purposes?**

The position is still fully included in your wealth tax declaration. The institution you use to hold crypto does not change the tax treatment — FINMA's custody rules (covered in a [related field note on Guidance 01/2026](/posts/finma-crypto-guidance-01-2026/)) govern how the institution must handle the assets, not whether the assets are taxable. If the institution segregates your crypto properly under the DLT Act framework, it remains your asset and appears in your wealth tax declaration at its December 31st value.

**Is staking income taxed at federal or cantonal rates?**

Both. Switzerland has a three-tier tax structure: federal income tax, cantonal income tax, and municipal income tax. Staking income is subject to all three layers. The federal rate is the same for all Swiss residents; the cantonal and municipal rates are where the significant variation exists (hence the Zug/Geneva difference).

**Are airdrops taxed the same way as staking?**

The SFTA has not issued specific guidance on airdrops separate from general income treatment. In practice, cantonal tax offices generally treat unsolicited airdrops that represent new tokens of economic value as income at the time of receipt (like staking rewards). Retroactive distribution airdrops to existing holders — where the criteria for receiving the airdrop was holding an existing position — may be treated differently. This remains an area of ongoing cantonal-level inconsistency.

**What about crypto received as salary in Switzerland?**

If your employer pays you partly in crypto, the CHF market value of that crypto on the date of receipt is treated as ordinary employment income and taxed the same as salary. The employer must handle AHV and withholding tax on that value. Subsequent appreciation on the crypto you received as salary is then treated under the standard capital gains exemption (for private investors), with your income-tax cost basis being the CHF value at receipt.

## What This Means If You Are Holding Crypto Here

The Swiss crypto tax framework is, in practice, favorable — but not in the simple way the "zero capital gains tax" headline implies.

The real advantage is structural: Switzerland taxes crypto on a wealth model rather than a realization model. You pay a modest annual levy on what you hold, and the appreciation of that holding is permanently exempt from tax upon sale. In a long-term appreciation scenario — buying ETH at CHF 500 and eventually selling at CHF 5,000, or whatever the equivalent looks like a decade from now — the total tax drag is the accumulated wealth tax on the intervening years, not a percentage of the gain itself.

For stakers and active DeFi participants, the picture is more mixed. Staking income is taxed as income, which matters at scale and makes canton choice more consequential than it is for pure holders.

The December 31st date creates real planning decisions around portfolio rebalancing. Private investor status requires attention — not constant anxiety, but awareness of the five criteria and how your activity looks relative to them on a year-by-year basis.

Living in Zug rather than Zurich, and holding positions through December rather than selling at peak, and earning staking income at a lower cantonal rate: these are structural decisions with measurable tax consequences. The framework rewards people who understand them and penalizes nobody for not using leverage or for holding patiently.

That is, as frameworks go, not a bad deal.

---

*Field notes are observations, not legal or tax advice. Swiss cantonal tax law changes and is interpreted with discretion at the cantonal level. For significant positions or complex situations, a qualified Swiss tax advisor or a written cantonal ruling (*Steuerruling*) is the appropriate next step.*

*Related: [FINMA's Crypto Guidance 01/2026 — What It Actually Means for Custody](/posts/finma-crypto-guidance-01-2026/) | [What Crypto Valley Actually Looks Like in 2026](/posts/crypto-valley-2026-snapshot/)*
