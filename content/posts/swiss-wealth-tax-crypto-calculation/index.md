---
title: "The Wealth Tax Calculation: How Switzerland Values Your Crypto Portfolio on New Year's Eve"
date: 2021-11-15
lastmod: 2026-05-04
description: "Switzerland's wealth tax hits your crypto portfolio every December 31st, even if you never sold. Here's the exact SFTA Kursliste mechanism, how Zug's 0.13% compares to Geneva's 1%+, and what happens when your altcoin isn't on the list."
categories: ["holding"]
tags: ["swiss wealth tax crypto calculation", "crypto portfolio value switzerland", "SFTA Kursliste crypto", "wealth tax switzerland crypto", "canton wealth tax rates zug", "December 31 crypto valuation", "ICTax crypto switzerland", "altcoin wealth tax", "DeFi holdings switzerland"]
draft: false
image: hero.jpg
readtime: 12
glossary:
  - term: "Vermögenssteuer (Wealth Tax)"
    def: "The annual cantonal tax on net assets — calculated on December 31st each year. There is no federal wealth tax in Switzerland; each of the 26 cantons plus its municipalities set their own rate. Crypto holdings count as movable intangible assets (Fahrhabe) and are fully included in the wealth tax base at their December 31st valuation."
  - term: "SFTA / FTA / ESTV"
    def: "Swiss Federal Tax Administration (German: Eidgenössische Steuerverwaltung, ESTV). Publishes the official Kursliste — the end-of-year reference price list for securities and cryptocurrencies. All Swiss cantons use this list as the authoritative valuation source for wealth tax declarations."
  - term: "Kursliste (Rate List / ICTax)"
    def: "The official list of December 31st closing prices for securities and crypto published annually by the SFTA. Accessible at ictax.admin.ch. For 2025, Bitcoin was listed at 69,571.99 CHF and Ethereum at 2,364.08 CHF. Coins not on the Kursliste require a fallback valuation method."
  - term: "Steuerwert (Tax Value)"
    def: "The official valuation figure used for wealth tax purposes, derived from the SFTA Kursliste. This is not necessarily the live market price on December 31st — it is the SFTA's annual average of exchange prices, which can differ from the exact midnight spot price on any individual exchange."
  - term: "Gemeindesteuerfuss (Municipal Tax Multiplier)"
    def: "Each Swiss municipality applies a multiplier on top of the cantonal wealth tax rate. In the city of Zug itself, this multiplier is among the lowest in Switzerland, making the effective combined rate far below what you see in cantonal rate tables. The full bill is canton rate × municipal multiplier × your net taxable wealth."
  - term: "Nachdeklaration (Self-Disclosure)"
    def: "Voluntary self-disclosure procedure available in all Swiss cantons. If you have crypto wealth that was not previously declared, Nachdeklaration allows you to come forward, pay back-taxes and interest, and generally avoid criminal penalties — provided authorities have not yet started an investigation."
sources:
  - name: "SFTA Official Crypto Rate List (ICTax / Kursliste)"
    url: "https://www.ictax.admin.ch/extern/en.html"
    desc: "Swiss Federal Tax Administration — official December 31st reference values for crypto and securities, updated annually. The definitive source for wealth tax valuation."
  - name: "Taxea.ch — Wealth Tax in Switzerland: Who Pays and How Much"
    url: "https://www.taxea.ch/en/faq-taxes/wealth-tax-in-switzerland-who-pays-and-how-much"
    desc: "Taxea.ch — overview of cantonal wealth tax rates, thresholds, and how crypto is valued. Accessed May 2026."
  - name: "Crypto Valley Journal — Crypto Taxes Switzerland 2025: FTA Rate List and Tax Return"
    url: "https://cryptovalleyjournal.com/focus/background/crypto-taxes-switzerland-2025-fta-rate-list-and-tax-return/"
    desc: "Crypto Valley Journal — detailed 2025 Kursliste values, unlisted coin handling, and staking guidance. Accessed May 2026."
  - name: "Taxolution Advisory — Swiss Wealth Tax 2026: Rates by Canton"
    url: "https://www.taxolution.ch/swiss-tax-guide/wealth-tax/"
    desc: "Taxolution — canton-by-canton wealth tax calculation table (CHF 500K to CHF 5M portfolio tiers) for 2026. Accessed May 2026."
  - name: "RSM Switzerland — Cryptocurrency Tax Treatment"
    url: "https://www.rsm.global/switzerland/en/news/cryptocurrency-tax-treatment-switzerland"
    desc: "RSM Switzerland — professional tax advisory breakdown of Swiss crypto classification, valuation hierarchy, and cantonal treatment."
  - name: "Taxea.ch — Cryptocurrencies in the Swiss Tax Return"
    url: "https://www.taxea.ch/en/faq-taxes/cryptocurrencies-in-the-swiss-tax-return-how-to-declare-them"
    desc: "Taxea.ch — practical guide to declaration, including unlisted coins, DeFi, and multi-wallet aggregation."
  - name: "Zug Notes — The Swiss Crypto Tax Advantage: A Plain-Language Guide"
    url: "/posts/swiss-crypto-tax-advantage-guide/"
    desc: "Zug Notes H01 pillar — full field guide to capital gains exemption, wealth tax structure, and private investor status."
  - name: "Zug Notes — Declaring Crypto on Your Swiss Tax Return"
    url: "/posts/declaring-crypto-swiss-tax-return/"
    desc: "Zug Notes H03 — step-by-step on where to enter crypto in the cantonal tax form, including the Wertschriftenverzeichnis (securities schedule)."
  - name: "Zug Notes — Staking Rewards in Switzerland: Why They're Taxed as Income"
    url: "/posts/staking-rewards-swiss-income-tax/"
    desc: "Zug Notes H04 — explains the wealth tax double-layer that hits staking holders: income tax on rewards received, then wealth tax on the accumulated tokens at year-end."
---

> 📅 Field note from: November 2021 | Last updated: May 2026
> Originally written shortly before the 2021 year-end valuation deadline; updated with five years of practical observations in May 2026.

Every November here in Zug, I notice the same pattern in the community. Someone who has been happily holding since January starts asking a very specific question: "What does my portfolio actually look like on December 31st — and what does that mean for my tax bill?"

The confusion is understandable. Switzerland's most famous crypto advantage — the capital gains exemption — gets all the attention. You buy BTC, it goes up, you sell, you pay nothing. That story spreads fast and spreads far. What travels less is the other side of the ledger: the wealth tax. It runs quietly in the background every year, calculated on the value of every coin you still hold when midnight hits on December 31st.

I have watched people arrive in Zug, absorb the capital gains story, and miss the wealth tax entirely — until their first tax return arrives. This note is for them. And for anyone who has been here longer but still wonders exactly how the number gets calculated.

## Why December 31st Is the Only Date That Matters

Switzerland's wealth tax is an annual snapshot tax. Once per year, the cantonal tax authority looks at your net assets on a single date — December 31st — and calculates your tax based on what you held at that moment.

This is different from, say, a mark-to-market system that tracks value continuously throughout the year, or a realisation-based system tied to when you sell. The Swiss approach is simpler and, for long-term holders, considerably more predictable. It does not matter if your portfolio was worth twice as much in March. It does not matter if it dropped by 40% in October. What matters is the snapshot.

For crypto specifically, this creates an interesting practical reality. A bull run that peaks in October and then partially retraces by December reduces your wealth tax base — even if your total gains for the year were substantial. Conversely, a portfolio that climbed steadily into year-end means you pay wealth tax on the higher December figure.

The practical implication: if you are considering a significant withdrawal or restructuring for other reasons, the timing relative to December 31st affects your wealth tax base for that year.

## The SFTA Kursliste: Where the Official Number Comes From

The Swiss Federal Tax Administration (SFTA, or ESTV in German) publishes an official price list — the Kursliste, accessible through the ICTax portal at ictax.admin.ch — every year. This list is updated annually and contains the official December 31st valuation for the most commonly held cryptocurrencies.

{{< num-highlight number="69,571.99 CHF" label="Bitcoin official SFTA tax value — December 31, 2025" >}}

{{< num-highlight number="2,364.08 CHF" label="Ethereum official SFTA tax value — December 31, 2025" >}}

These are not necessarily the exact spot prices you see on Coinbase or Kraken at midnight on December 31st. The SFTA calculates an average of prices across multiple exchanges for the reference date. The result is the Steuerwert — the legally recognised tax value that you use when filling in the securities and credits schedule (Wertschriftenverzeichnis) in your cantonal tax form.

The practical workflow is straightforward for major assets: you look up Bitcoin on the ICTax list, note the CHF value per unit, multiply by how many BTC you held on December 31st, and enter the total. The Swiss system has made this as mechanical as possible for the major assets.

Where it gets more complicated is when you move beyond BTC, ETH, and the small number of other major coins that appear on the official list.

## The Valuation Hierarchy: What Happens When Your Coin Is Not on the List

The SFTA Kursliste covers a limited number of cryptocurrencies. If you hold anything beyond the mainstream — altcoins, newer layer-1 tokens, governance tokens, smaller DeFi protocol tokens — you are outside the official list. This is where the valuation hierarchy applies:

**Level 1 — Official SFTA rate:** If your coin appears on the Kursliste, use that rate. End of story.

**Level 2 — CoinMarketCap or CoinGecko year-end rate:** If the coin does not appear on the Kursliste but is traded on major exchanges, the standard cantonal practice is to accept the December 31st rate from CoinMarketCap or CoinGecko as the reference. You document the rate, save a screenshot showing the December 31st price, and declare accordingly.

**Level 3 — Cost basis (purchase price):** For tokens that are genuinely illiquid or newly launched, with no reliable market price, Swiss tax authorities generally accept the original purchase price (cost basis) as the valuation floor. This is the default when no credible market rate exists.

**Level 4 — Zero value:** The only circumstance where a canton will accept zero as the declared value is when the token is demonstrably worthless — meaning the project has collapsed entirely, there is no exchange listing at any price, and there is documented evidence of worthlessness. This is a high bar. "It went down a lot" does not qualify. A project that still trades at fractions of a cent technically has a non-zero value.

{{< skip-box title="Practical note on Level 2 documentation" >}}
If you use CoinMarketCap or CoinGecko for Level 2 valuations, save a PDF or screenshot of the historical data page showing the December 31st closing price. Cantonal tax software varies in how it handles manual entry for non-Kursliste assets, but having clear documentation of how you arrived at your figure significantly reduces friction if your return is reviewed.
{{< /skip-box >}}

## Cantonal Rates: The Number That Actually Determines Your Bill

Here is where the Switzerland-is-not-one-country reality hits. Once you know the December 31st value of your portfolio, the tax you pay on it depends almost entirely on which canton you live in.

Wealth tax in Switzerland is levied exclusively at cantonal and municipal level. The federal government does not levy wealth tax on private individuals. And the cantonal variation is substantial.

{{< budget-table title="Wealth tax on a CHF 1,000,000 crypto portfolio — selected cantons, 2026" >}}
| Canton | Estimated annual wealth tax |
|---|---|
| Zug | ~CHF 1,368 |
| Zurich | ~CHF 1,744 |
| Bern | ~CHF 4,027 |
| Geneva | ~CHF 5,115 |
{{< /budget-table >}}

Source: Taxolution Advisory, 2026 cantonal data (married couple filing, cantonal capital residence, no church tax)

The Zug number deserves a closer look. At CHF 1,368 per year on a CHF 1,000,000 portfolio, the effective rate is about 0.14%. On a CHF 500,000 portfolio, the bill drops to roughly CHF 412. That is the combination of Zug's low cantonal rate and its relatively low municipal multiplier in the city of Zug itself.

Geneva, on the other end, runs approximately 3.7 times higher on the same portfolio value.

For a CHF 5,000,000 crypto position, the gap widens considerably: roughly CHF 10,200 per year in Zug versus CHF 38,100 per year in Geneva. Over a decade, that difference compounds into real money — which is a non-trivial factor in why a certain class of crypto holders deliberately chose Zug when establishing their Swiss tax residence.

One important nuance: these figures are progressive in most cantons. The effective rate on the first CHF 500,000 of taxable wealth is lower than the rate on the next CHF 500,000. Most cantons also have exemption thresholds — in Zug, the threshold is around CHF 100,000-200,000 depending on filing status, meaning portfolios below that level owe nothing.

## Multi-Wallet, Cold Storage, and DeFi: The Aggregation Reality

A question I hear frequently from people running complex portfolios: does it matter how many wallets or exchanges your crypto is spread across?

For wealth tax purposes, the answer is no — and yes.

No: distributing assets across five hardware wallets or three exchanges does not reduce your wealth tax obligation. You aggregate all holdings across all addresses and accounts you control as of December 31st and declare the total. A transfer between your own wallets does not create a taxable event and does not affect the total.

Yes: the complexity comes in documentation. The cantonal tax office does not automatically know what you hold on cold storage. You are responsible for aggregating all positions accurately and providing evidence if asked. This means:

- An end-of-year holdings export from each exchange
- A record of cold wallet balances as of December 31st (your own records, or a blockchain explorer snapshot)
- For DeFi positions: documentation of your net balance locked in protocols on December 31st

DeFi creates the most grey area. If you have liquidity provided to an AMM pool, or tokens locked in a yield protocol, those assets are still yours on December 31st — they count toward your wealth tax base at their December 31st value. The practical challenge is that some protocols make it less straightforward to extract a clean "here is what you owned on December 31st" figure. Crypto tax software (Koinly, Blockpit, CoinTracking) has improved at pulling these positions, but it is worth reviewing the output carefully rather than relying on automation alone.

For staked tokens, a related complication: your staked position is counted in your wealth tax base, and the staking rewards you received during the year are taxed as income — a double-layer that catches people off guard. I covered this in more detail in the [staking income field note](/posts/staking-rewards-swiss-income-tax/).

## The Part Nobody Explains Well: Cantonal Valuation Differences

Here is a wrinkle that even many people who have been in Switzerland for years do not fully understand: not only do cantonal rates differ, but the actual valuation of certain asset types can differ between cantons.

For standard listed securities and major cryptocurrencies on the Kursliste, all cantons use the same SFTA figures. There is no room for cantonal discretion here — the Steuerwert is set federally.

The divergence appears for:

**Real estate:** Cantons use their own assessed "tax values" for property, which vary significantly from market value and differ across cantons. Less relevant for pure crypto holders, but relevant if you own Swiss real estate alongside your digital assets.

**Unlisted or illiquid tokens:** When a coin is not on the Kursliste and you are using a Level 2 or Level 3 valuation, different cantonal tax officers may apply scrutiny differently. One canton might routinely accept a CoinMarketCap price for a small-cap altcoin; another might flag it for review. This is an area where having a local tax advisor who knows your canton's practice is genuinely useful — not just as general prudence, but because the practical outcome can differ.

**DeFi protocol positions:** The tax treatment of LP tokens, staked derivative tokens (like stETH), and protocol governance tokens is still evolving. The SFTA has not issued specific Kursliste entries for most DeFi protocol tokens. The Level 2 / Level 3 hierarchy applies, but cantonal practice on complex DeFi positions varies.

## Comparing Switzerland to Other Jurisdictions

One question I get from people considering Zug as a base: how does this compare to the US, Singapore, or Dubai?

The structural answer: Switzerland is one of a small number of countries that still levies a recurring annual wealth tax on individuals. Most of the world does not.

The United States does not have a federal wealth tax. Capital gains are taxed on realisation, and there is no annual levy on the portfolio itself. Americans holding crypto in the US pay nothing on unrealised gains from year to year.

Singapore eliminated its wealth tax in 1984. Crypto capital gains are generally not taxed for individual investors. No annual portfolio levy.

Dubai (UAE) has no personal income tax and no wealth tax. The tax-free status is more comprehensive than Switzerland's in some respects — but Switzerland still offers the capital gains exemption, which achieves the same zero-tax result on crypto appreciation for private investors.

The meaningful comparison within Europe: several EU member states have maintained or introduced wealth tax variants. France's IFI (Impôt sur la Fortune Immobilière) covers real estate, and Spain has a Patrimonio tax that currently includes financial assets. Neither is exactly like Switzerland's cantonal system, but both illustrate that recurring net worth taxes exist in advanced economies.

For crypto specifically, what makes Switzerland interesting is the combination: no capital gains tax on appreciation (the advantage everyone knows) plus a modest, predictable wealth tax levied at transparent rates (the part that is less discussed). In Zug, the effective combination is considerably more favourable than the raw headline rate in Geneva would suggest, and far more favourable than holding in a high-rate EU jurisdiction.

## What You Are Actually Paying For

I have found it useful to reframe how I think about the Zug wealth tax. At roughly 0.14% per year on my total crypto position, it is effectively a very small annual fee for the privilege of holding in a jurisdiction where:

- Capital gains on the same position are completely tax-free
- The regulatory environment has been relatively clear and stable for years
- Banking access for crypto holders, while not trivial, is genuinely available in a way it is not in most jurisdictions

Framed that way, the wealth tax is less of a burden and more of a structural feature of the Swiss approach — a small, predictable, recurring cost in exchange for the elimination of the larger, variable, unpredictable cost that capital gains taxation would represent.

The December 31st number matters. You should know what it is and how it is calculated. But for most holders in Zug, when you run the actual arithmetic — portfolio value × roughly 0.14% — it is considerably less alarming than the word "wealth tax" initially sounds.

---

For how the year-end portfolio value feeds into the actual tax return form, see the [field note on declaring crypto on your Swiss tax return](/posts/declaring-crypto-swiss-tax-return/). For the broader picture of why Switzerland's tax structure is what it is for crypto holders, the [Swiss crypto tax advantage guide](/posts/swiss-crypto-tax-advantage-guide/) covers the full framework.

*This field note reflects the tax framework as of May 2026. Tax rules change; nothing here is legal or tax advice. Consult a qualified Swiss tax advisor for your specific situation.*
