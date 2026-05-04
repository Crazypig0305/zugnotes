---
title: "Staking Rewards in Switzerland: Why They're Taxed as Income (And What That Means for You)"
date: 2022-04-08
lastmod: 2026-05-04
description: "Swiss law taxes staking rewards as ordinary income, not capital gains. Why, the wealth tax double-layer, and what it means staking in Zug versus Geneva."
categories: ["holding"]
tags: ["crypto staking tax switzerland", "swiss staking income tax", "staking rewards switzerland", "SFTA crypto income", "wealth tax staking", "DeFi tax switzerland", "canton tax staking"]
draft: false
image: hero.jpg
readtime: 8
glossary:
  - term: "Kapitalertrag (Capital Income)"
    def: "The Swiss tax category for income earned from movable assets — dividends, interest, and staking rewards all fall here. Unlike capital gains (which are tax-free for private investors), Kapitalertrag is taxable as ordinary income at both federal and cantonal levels."
  - term: "SFTA Working Paper on Cryptocurrencies"
    def: "The Swiss Federal Tax Administration's primary guidance document on crypto tax classification, last significantly updated in December 2021. It establishes that staking rewards and mining rewards are taxable income (not capital gains), taxable at market value in CHF on the date of receipt."
  - term: "Kapitalgewinn (Capital Gain)"
    def: "The increase in value of a capital asset between purchase and sale. For private investors in Switzerland, capital gains on crypto are completely tax-free — this is the structural advantage Switzerland offers. Staking rewards are explicitly NOT treated as capital gains."
  - term: "Vermögenssteuer (Wealth Tax)"
    def: "The annual cantonal tax on net assets calculated as of December 31st. Staked tokens that you hold on December 31st are included in the wealth tax base — meaning you pay wealth tax on them even if you have already paid income tax on the staking rewards that generated them."
  - term: "Proof-of-Stake (PoS)"
    def: "The consensus mechanism used by Ethereum (post-Merge, September 2022), Cardano, Solana, and other networks. Validators lock tokens to participate in block validation and receive staking rewards. The Merge in September 2022 made Ethereum staking much more accessible, which is part of why Swiss tax authorities formalized their staking guidance around 2021-2022."
sources:
  - name: "SFTA Working Paper — Cryptocurrencies (December 2021)"
    url: "https://www.estv.admin.ch/estv/en/home/direct-federal-tax/directives-circulars.html"
    desc: "Swiss Federal Tax Administration — primary guidance establishing staking rewards as taxable capital income (Kapitalertrag), not capital gains. The definitive source for staking tax classification in Switzerland."
  - name: "Taxea.ch — Mining and Staking: How Crypto Income is Taxed in Switzerland"
    url: "https://www.taxea.ch/en/tips/mining-and-staking-tax-treatment-in-switzerland"
    desc: "Taxea.ch — detailed breakdown of Swiss staking income tax treatment, including pool staking and wealth tax interaction."
  - name: "Blockpit — Switzerland Crypto Tax Guide 2026"
    url: "https://www.blockpit.io/tax-guides/crypto-tax-guide-switzerland"
    desc: "Blockpit — comprehensive 2026 guide covering staking income classification and cantonal wealth tax rates."
  - name: "Crypto Valley Journal — DACH Crypto Tax Comparison 2025"
    url: "https://cryptovalleyjournal.com/education/basics/crypto-taxes-in-the-dach-comparison-germany-austria-and-switzerland-2025/"
    desc: "Crypto Valley Journal — comparison of Swiss staking tax treatment versus Germany and Austria, with cantonal rate data."
  - name: "Zug Notes — The Swiss Crypto Tax Advantage: A Plain-Language Guide"
    url: "/posts/swiss-crypto-tax-advantage-guide/"
    desc: "Zug Notes H01 pillar — full field guide to capital gains exemption, wealth tax structure, and private investor status. The structural context that makes staking income treatment surprising to most people."
  - name: "Zug Notes — Declaring Crypto on Your Swiss Tax Return"
    url: "/posts/declaring-crypto-swiss-tax-return/"
    desc: "Zug Notes H03 — practical step-by-step on where staking rewards go in the cantonal tax form, separate from the securities schedule."
  - name: "Zug Notes — Using Crypto Day-to-Day in Zug"
    url: "/posts/crypto-day-to-day-zug/"
    desc: "Zug Notes H06 — staking as part of everyday crypto use in Crypto Valley: what workflows look like in practice."
---

> 📅 Field note from: April 2022 | Last updated: May 2026
> Originally written when Swiss tax authorities first issued clear staking guidance; updated with current cantonal practice and post-Merge staking context in May 2026.

Most explanations of Swiss crypto tax policy start with the good news: capital gains are tax-free for private investors. That part is accurate and important.

What those same explanations often understate is what happens when your crypto generates yield. Staking rewards do not fall under the capital gains exemption. They are taxed as ordinary income — and understanding exactly why, and what that means across different staking setups and Swiss cantons, takes a bit more unpacking than the headline suggests.

This field note covers the logic behind the income classification, the interaction with wealth tax (which creates a double-layer effect that catches people off guard), and the practical differences between staking in Zug versus Zurich versus Geneva.

## Why Staking Rewards Are Not Capital Gains

The Swiss Federal Tax Administration's (SFTA) position on staking rewards has been consistent since its December 2021 working paper on cryptocurrency taxation: staking rewards are taxable income, not capital gains.

The legal reasoning follows from how Swiss tax law categorizes asset returns. Capital gains — the increase in value of an asset you bought and later sold — are tax-free for private investors. But income earned *through* holding an asset (dividends, interest, and by analogy, staking rewards) falls into a different category: **Kapitalertrag**, or capital income from movable assets.

When you stake ETH or ADA and receive staking rewards, the SFTA treats this as analogous to receiving interest on a savings account or dividends on a share. The tokens you receive are income in the year you receive them.

{{< num-highlight number="Market Value in CHF on Date of Receipt" label="The amount you declare as income for each batch of staking rewards — not the value when you eventually sell them" >}}

The practical implication is that you have two separate tax events when staking:

1. **Income event:** When rewards are credited to your wallet, you declare the CHF value at that moment as taxable income.
2. **Wealth tax event:** Any tokens you hold on December 31st — including the staking rewards you received during the year — are included in your annual wealth tax base.

The subsequent price movement of those reward tokens is a capital gain or loss, but since you are (presumably) a private investor, that part remains tax-free. The taxable moment is receipt, not sale.

## The Double-Layer Effect: Income Tax Plus Wealth Tax

Here is the situation that surprises most people who come from other jurisdictions.

Say you receive ETH staking rewards worth CHF 5,000 during the year. You declare that CHF 5,000 as income. Depending on your canton and marginal rate, you might pay CHF 1,100–2,160 in income tax on it (using Zug's ~22% versus Geneva's ~43%).

Then December 31st arrives. Those same ETH tokens — assuming you still hold them — are counted in your wealth tax base. At a typical cantonal wealth tax rate of 0.1–0.3%, the additional cost on CHF 5,000 is CHF 5–15.

The wealth tax portion on a CHF 5,000 staking reward position is modest. But if you are staking at scale — say CHF 50,000 in annual rewards — the interaction is more material. And the wealth tax applies to your entire portfolio value, not just the rewards themselves. A validator running significant ETH at year-end is paying wealth tax on the full staked position.

{{< skip-box title="Is there a deduction for this overlap?" >}}
There is no specific Swiss tax mechanism to offset income already paid on staking rewards against the subsequent wealth tax on those same tokens. The two taxes are assessed separately under different legal frameworks — income tax on the receipt event, wealth tax on the year-end snapshot. For smaller stakers, the wealth tax portion is low enough that this is mostly an accounting consideration. For larger staking operations, it is worth quantifying with a Swiss tax professional.
{{< /skip-box >}}

## How Swiss Cantons Treat Staking Income Differently

The federal position on staking rewards as income is uniform. But Switzerland's cantonal tax system means that the *cost* of that income classification varies significantly based on where you live.

{{< budget-table title="Approximate marginal income tax rates for staking rewards: key cantons" >}}
| Canton | Approx. marginal income tax rate (CHF 100,000 taxable income) | Wealth tax rate (typical) | Notes |
|---|---|---|---|
| Zug | ~22% | ~0.10% | Lowest in Switzerland; Zug Stadt specifically is among the lowest communes |
| Schwyz | ~23–27% | ~0.05–0.15% | Cantons like Wollerau and Freienbach have very low communal rates |
| Zurich | ~38–40% | ~0.25–0.30% | City of Zurich significantly higher than Zug |
| Geneva | ~41–43% | ~0.25–0.45% | Highest among major Swiss cantons; Geneva city rates are at the top |
| Bern | ~38–42% | ~0.30–0.40% | Similar bracket to Zurich |
{{< /budget-table >}}

The same CHF 5,000 in staking rewards costs roughly CHF 1,100 in income tax for a Zug resident and roughly CHF 2,150 for a Geneva resident. The difference compounds at scale.

This is not a novel observation — it is why a disproportionate share of Swiss crypto holders, validators, and staking operations are based in Zug and Schwyz. The cantonal income tax treatment of staking rewards is one of the variables that makes Crypto Valley's location relevant to something other than the weather.

## Pool Staking, Liquid Staking, and DeFi: Where Treatment Gets More Complex

The basic income-at-receipt rule applies cleanly to direct staking: you validate, you receive rewards, you declare them. But the staking landscape has grown more complicated since 2022, and Swiss tax guidance has not fully caught up with every variant.

**Pool staking** (delegating to a validator pool like Lido's stETH, RocketPool, or a centralized exchange staking product) is treated the same as direct staking for income purposes. Each distribution of rewards is a taxable income event at receipt-date CHF value. If rewards accumulate automatically (auto-compounding pools), the point of "receipt" is typically when the rewards become separately claimable or transferred — though this is an area where cantonal offices can differ in interpretation.

**Liquid staking tokens** (stETH, rETH, cbETH, and similar) add a layer of complexity. When you deposit ETH into Lido, you receive stETH — a token that accrues staking rewards by increasing in value rather than distributing periodic rewards directly. The SFTA has not issued specific guidance on liquid staking tokens as of 2025. Practitioner consensus is that the accrued value of liquid staking tokens is treated as income when it becomes realizable (i.e., when you unstake and receive ETH), but this remains an area of genuine uncertainty. If you hold significant liquid staking positions, this is worth discussing with a Swiss tax advisor before year-end.

**DeFi yield farming and lending protocols** fall into the same income category as staking, but with more case-by-case judgment. Yield from lending ETH or stablecoins on Aave or Compound is treated as capital income at receipt. Complex DeFi positions — impermanent loss compensation, governance token rewards, protocol incentives — are often assessed individually by cantonal offices. The principle remains: if you receive tokens as compensation for providing capital or services, that is income.

{{< num-highlight number="Date of Receipt" label="The valuation date for all staking and DeFi reward income — not the date you sell, swap, or unstake" >}}

## AHV Contributions: When Staking Becomes Self-Employment

For most stakers, AHV (Swiss social security) is not relevant. The SFTA's position is that staking by private individuals as a passive income activity does not trigger AHV contributions — it is analogous to receiving interest on a bond, not to running a business.

The exception: solo validation at scale. If you are running Ethereum validators full-time as a business activity, managing significant infrastructure, or treating staking as your primary professional occupation, cantonal tax authorities may reclassify this as self-employment income. That triggers AHV contributions on top of the income tax — currently around 10.6% for self-employed individuals (combined AHV/IV/EO rate, 2024-2025 rate).

For the vast majority of people who stake through platforms or delegate to pools, this threshold is not reached. But if you are a professional validator or have structured your staking activity as a business, the AHV question is worth addressing explicitly.

## The Practical Filing Sequence for Stakers

Staking rewards go into the *income* section of your cantonal tax return, not the *securities* section. This is the clearest structural difference from how most people intuitively think about crypto taxes.

The complete picture at filing time:

**Income section (Vermögenserträge / income from movable assets):**
- Sum of all staking rewards received during the year, valued at CHF market value on each receipt date
- Yield from DeFi lending or liquidity provision, similarly valued at receipt date
- Mining rewards (same treatment as staking)

**Securities section (Wertschriftenverzeichnis / wealth declaration):**
- Total crypto portfolio value on December 31st, using SFTA Kursliste rates (or exchange rates for unlisted assets)
- This includes any staked tokens you hold on December 31st — even those locked in a smart contract or validator contract

{{< skip-box title="Reconstructing receipt-date values from staking history" >}}
Most staking platforms (and centralized exchanges) provide downloadable transaction history that includes reward distributions with timestamps. For tax purposes, you need the CHF value at each receipt date — which means cross-referencing the reward amount with SFTA rates or CMC historical prices for that specific date. Tools like Koinly or Blockpit can automate most of this for common networks, but you should verify the outputs against your actual reward history.
{{< /skip-box >}}

The full practical sequence for declaring staking rewards is covered in the [Swiss tax return field note](/posts/declaring-crypto-swiss-tax-return/). The [Swiss Crypto Tax Advantage guide](/posts/swiss-crypto-tax-advantage-guide/) covers the broader framework — particularly the private investor status criteria that keep your underlying capital gains tax-free even as your staking income is taxed.

## What This Actually Means for Long-Term Stakers

The Swiss staking tax picture is not punitive by international standards — it is just different from what the "capital gains free" headline implies.

For a private investor in Zug staking ETH:
- Capital gains on ETH itself: **zero**
- Staking rewards: **taxed as income at ~22% marginal rate** (at CHF 100,000 income level)
- Wealth tax on total portfolio (including staked ETH): **~0.1% annually**

Compared to most European jurisdictions, where capital gains on crypto are also taxed, this is still favorable. Germany taxes both capital gains and staking income (with a one-year holding exemption for capital gains but no blanket exemption for staking). The UK taxes staking rewards as income and capital gains on disposal. France taxes both.

Switzerland's structural advantage for stakers is that the underlying appreciation of your staked assets remains outside the income tax net. Only the rewards — the income generated by staking — are taxed. If you are staking a position that grows 3x in value over five years, the 3x appreciation is yours tax-free; only the periodic rewards along the way were taxable income events.

The canton you choose matters significantly. A Zug-based staker versus a Geneva-based staker faces roughly double the income tax on the same staking rewards. This is one of the practical consequences of Switzerland's federalist tax structure that shows up clearly in the staking context.

For anyone actively managing staking at significant scale in Switzerland, the combination of receipt-date income tax, December 31st wealth tax, and cantonal rate variation makes advance planning worthwhile — particularly around year-end portfolio positions and which canton to establish residency in.

---

*Not tax advice. Swiss tax treatment of crypto and staking income depends on individual circumstances, cantonal variation, and annual SFTA guidance. This field note describes the general framework as understood in Zug in 2022 and updated through May 2026. Consult a qualified Swiss tax professional for your specific situation.*
