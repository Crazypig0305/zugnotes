---
title: "Declaring Crypto on Your Swiss Tax Return: What \"Market Value on December 31st\" Actually Means"
date: 2025-02-14
lastmod: 2026-05-04
description: "Every Swiss canton tax form asks for the market value of your crypto on December 31st. Here is a plain-language field guide to where you find that number, how to handle multiple wallets and non-CHF assets, and what happens with staking, DeFi, and NFTs."
categories: ["holding"]
tags: ["crypto tax return switzerland", "swiss crypto declaration", "wealth tax crypto", "SFTA rate list", "canton tax software", "staking tax switzerland", "DeFi tax", "self-disclosure"]
draft: false
image: hero.jpg
readtime: 11
glossary:
  - term: "SFTA / FTA / ESTV"
    def: "Swiss Federal Tax Administration (German: Eidgenössische Steuerverwaltung, ESTV). The federal body that publishes the official crypto reference values (Kursliste) each December 31st. Cantonal tax offices use these values to calculate your wealth tax base. The official rate list is at estv.admin.ch."
  - term: "Vermögenssteuer (Wealth Tax)"
    def: "The annual cantonal tax on net assets — bank accounts, securities, real estate, and crypto — calculated on December 31st. There is no federal wealth tax in Switzerland; each canton and municipality sets its own rate. Most Swiss cantons assess this on total portfolio value above a cantonal exemption threshold."
  - term: "Wertschriftenverzeichnis"
    def: "The 'securities and credits schedule' in the Swiss tax return — the section where crypto holdings are declared alongside shares, bonds, and fund units. This is the standard place to list crypto, valued as of December 31st at the official SFTA rate."
  - term: "Nachdeklaration (Self-Disclosure)"
    def: "The voluntary self-disclosure procedure available in all Swiss cantons. If you forgot to declare crypto in previous years, Nachdeklaration allows you to come forward, pay the back taxes and interest, and generally avoid criminal penalties — but only if authorities have not already started an investigation."
  - term: "SFTA rate list (Kursliste)"
    def: "The annual list of official December 31st crypto values published by the Swiss Federal Tax Administration. Bitcoin and Ethereum are always listed. For other assets not on the list, cantonal offices generally accept CoinMarketCap year-end prices. The list is at estv.admin.ch/estv/en/home/direct-federal-tax/directives-circulars/kursliste.html"
  - term: "Professional trader classification"
    def: "If cantonal tax authorities determine that your crypto activity is frequent and constitutes a significant part of your income, they can reclassify you as a professional trader. This makes capital gains fully taxable as income. The SFTA's Circular No. 36 defines five safe-haven criteria that protect private investor status."
sources:
  - name: "SFTA Official Crypto Rate List (Kursliste)"
    url: "https://www.estv.admin.ch/estv/en/home/direct-federal-tax/directives-circulars/kursliste.html"
    desc: "ESTV — official December 31st reference values for crypto, used by all Swiss cantons. Updated annually."
  - name: "SFTA Circular No. 36 — Tax Treatment of Crypto-Assets"
    url: "https://www.estv.admin.ch/estv/en/home/direct-federal-tax/directives-circulars/circulars/2022/2-36-2022.html"
    desc: "ESTV — the primary federal guidance on private vs. professional trader classification, staking income, and wealth tax basis."
  - name: "Taxea.ch — Cryptocurrencies in the Swiss Tax Return"
    url: "https://www.taxea.ch/en/faq-taxes/cryptocurrencies-in-the-swiss-tax-return-how-to-declare-them"
    desc: "Taxea.ch — practical breakdown of the SFTA valuation hierarchy and declaration procedure, accessed May 2026."
  - name: "Mt Pelerin — How to Report Crypto in Your Swiss Tax Declaration"
    url: "https://www.mtpelerin.com/blog/how-to-report-crypto-in-your-tax-declaration"
    desc: "Mt Pelerin — section-by-section walkthrough of cantonal tax software fields for crypto, 2025."
  - name: "Caminada — Declaring Cryptos in the Swiss Tax Declaration 2025"
    url: "https://www.caminada.com/en/blog/cryptocurrencies-taxdeclaration"
    desc: "Caminada tax consulting — overview of the securities schedule approach and professional trader risk thresholds."
  - name: "Zug Notes — The Swiss Crypto Tax Advantage: A Plain-Language Guide"
    url: "/posts/swiss-crypto-tax-advantage-guide/"
    desc: "Zug Notes H01 pillar — full field guide to capital gains exemption, wealth tax structure, private investor status, and canton-by-canton rates."
  - name: "Zug Notes — Swiss CARF Delay Explained"
    url: "/posts/switzerland-carf-delay-2027/"
    desc: "Zug Notes R02 — field note on what the 2027 CARF automatic exchange means for Swiss crypto holders."
  - name: "Zug Notes — Swiss Crypto Bank Account"
    url: "/posts/crypto-friendly-bank-account-switzerland/"
    desc: "Zug Notes H02 — bank statements from SEBA/Sygnum can serve as source documentation for your tax declaration."
---

> 📅 Field note from: February 2025 | Last updated: May 2026
> Originally written during the 2024 tax declaration season; updated with current Federal Tax Administration guidance in May 2026.

Switzerland's crypto tax framework is structurally simple: private investors pay no capital gains tax, but they do pay wealth tax on the full market value of their portfolio — and that market value is assessed on one specific date every year.

That date is December 31st.

Understanding what "market value on December 31st" actually means in practice is most of what you need to know to file your return correctly. This field note walks through the mechanics — where the number comes from, how to handle multiple wallets and exchanges, what to do when your assets are priced in USD or EUR rather than CHF, and how the less common categories (DeFi positions, staking rewards, NFTs) get treated. There is also a section at the end on what to do if you have never declared crypto before.

This is a practical guide, not a legal instruction. For complex portfolios, use a professional. For most straightforward holding situations, this should get you to the right form and the right field.

## The Core Concept: Wealth Tax Is an Annual Snapshot, Not a Transaction Tax

Before getting into the mechanics of the declaration form, it helps to be clear about what you are actually being taxed on.

Switzerland does not tax your crypto gains when you sell. It taxes the value you hold — once per year, on December 31st. The wealth tax is a snapshot of your net assets at year-end, and your crypto portfolio is part of that snapshot.

The practical implication: if you bought ETH in October and it has doubled in value by December 31st, you pay wealth tax on the doubled value even though you have not sold anything. If the price then crashes in January, that does not affect last year's tax bill — the snapshot has already been taken.

{{< num-highlight number="December 31st" label="The single valuation date that determines your entire crypto wealth tax position for the year" >}}

For most Swiss residents, this is an annual exercise that takes a few hours: calculate the total CHF value of your crypto holdings on December 31st, enter that figure in the correct section of your cantonal tax return, and declare any income-type events (staking, yield) separately. The mechanics are more bureaucratic than technically difficult.

## Where the December 31st Number Comes From

The Swiss Federal Tax Administration (SFTA, or ESTV in German) publishes an official rate list — the Kursliste — every year that includes the December 31st reference values for the most commonly held cryptocurrencies. This is the primary source you should use.

**The SFTA valuation priority is:**

1. **Official SFTA Kursliste value** (if your asset is listed) — use this number. Non-negotiable.
2. **Year-end price from your trading platform** (if not on the Kursliste) — cantonal offices generally accept this with documentation.
3. **Original purchase price in CHF** (fallback only, for completely illiquid or no-market assets) — use sparingly.

For reference, the SFTA Kursliste 2024 values (December 31, 2024) were:
- Bitcoin: **CHF 88,060**
- Ethereum: **CHF 3,264**

The 2023 year-end values were CHF 37,006 for Bitcoin and CHF 2,151 for Ethereum — which illustrates how dramatically the wealth tax base can shift year to year purely due to market movement.

{{< skip-box title="Where to find the SFTA Kursliste" >}}
Go to **estv.admin.ch**, look under Direct Federal Tax → Directives & Circulars → Rate Lists (Kursliste). The list is published in January or February for the prior December 31st date. It covers Bitcoin, Ethereum, and a selection of other major assets. Anything not on the list defaults to option 2 above.
{{< /skip-box >}}

The implication for planning: the wealth tax is not something you can avoid by timing your trades. Even if you sell all your crypto on December 30th and buy back on January 2nd, the snapshot date catches you either holding or not holding. Some people do time positions around December 31st for wealth tax purposes, but that is an active decision with its own transaction costs.

## Where in the Tax Return to Declare It

Every Swiss canton uses its own tax software (Zug uses ZugTax, Zurich uses ZHTax, Bern uses TaxMe-Online, and so on), but the underlying structure is similar across cantons.

**Crypto goes in the securities and credits schedule** — typically called the "Wertschriftenverzeichnis" or "Liste des titres et créances." This is the same section where you would list shares, bonds, or fund units. Crypto is treated as a movable intangible asset and declared here.

{{< budget-table title="Where to find crypto in Swiss cantonal tax software" >}}
| Asset Type | Tax Software Section | Notes |
|---|---|---|
| BTC, ETH, major altcoins on SFTA list | Securities/Wertschriften schedule | Enter CHF value at SFTA Kursliste rate |
| Altcoins not on SFTA list | Securities/Wertschriften schedule | Enter CHF value at exchange year-end rate |
| Staking rewards received in year | Income schedule (Vermögenserträge) | Declare at CHF market value on date received |
| Mining income | Independent activity / self-employment income | Separate from investment income |
| Crypto held in centralized exchange | "Accounts" or "bank accounts" section (some cantons) | Check your canton's specific guidance |
| Self-custodied crypto | "Securities" or "other assets" | Declare total CHF value as of Dec 31st |
{{< /budget-table >}}

The exact field names vary. Zug-specific: in ZugTax, crypto is declared under "Wertschriften und Guthaben" (Securities and Credits) with the asset name, the number of units, and the CHF value as of December 31st. The software does the multiplication if you provide the unit count and price.

A practical note: some cantons have added a dedicated crypto field in recent software versions (2023-2025 updates). If you see a field specifically labeled "Kryptowährungen" or "virtual currencies," use that. If you do not, the Wertschriften schedule is the correct fallback.

## Multiple Wallets and Exchanges: Aggregate or Itemize?

If you hold crypto across several wallets or exchanges, you have two options for how to declare.

**Aggregating is generally acceptable.** Most cantonal guidance and practitioner consensus is that you can declare the total CHF value of all your crypto holdings as a single line item — you do not need to break down each wallet, each exchange account, or each individual token separately (unless you have tokens with meaningfully different tax treatments, like staking versus holding).

{{< num-highlight number="Total Portfolio Value" label="The number you are declaring — aggregate CHF value across all wallets and exchanges as of December 31st" >}}

**What you should document even if you aggregate:**

- Export year-end balance statements from each exchange and wallet
- Record the CHF conversion for each asset using the SFTA Kursliste or exchange rate
- Keep a worksheet showing the calculation — cantonal tax authorities can ask for it

**When to itemize instead of aggregate:**

- If you have tokens with different income classifications (some held for capital gains, some staked for income)
- If some tokens are on the SFTA Kursliste and some are not (different valuation sources)
- If you have assets across multiple jurisdictions (e.g., a portion on a non-Swiss exchange that might have separate reporting obligations)

For most straightforward holders, a single total line is fine. Keep the supporting documents.

## Non-CHF Base Currency: Converting USD, EUR, and Stablecoin Values

Most crypto assets are priced in USD. The SFTA Kursliste already converts to CHF for the assets it covers (Bitcoin: CHF 88,060 — not USD 95,000 or something you need to convert yourself). Use the Kursliste number directly.

For assets not on the Kursliste: get the December 31st price in USD (or EUR), then convert to CHF using the official SFTA exchange rate for that date. The SFTA also publishes an annual currency exchange rate list (again at estv.admin.ch).

**Stablecoins:** USDC, USDT, and similar USD-pegged stablecoins are declared at their CHF equivalent — essentially the CHF/USD exchange rate on December 31st multiplied by the number of stablecoin units. They are not treated as USD cash. They are treated as crypto assets and go in the securities schedule.

{{< skip-box title="EUR-priced and DAI-type stablecoins" >}}
Euro-pegged stablecoins (EURS, for example) follow the same logic: declare in CHF using the EUR/CHF rate on December 31st. DAI (or other algorithmically stabilized assets) — declare at whatever the actual market value was on December 31st, not at the theoretical USD 1.00 peg.
{{< /skip-box >}}

## The Business vs. Private Investor Line

The declaration mechanics described above apply to **private investors**. If cantonal authorities reclassify you as a professional trader, the framework changes: your capital gains become taxable income, and you owe AHV (social security) contributions on them as well.

The SFTA's Circular No. 36 defines five safe-haven criteria for private investor status. Meeting all five gives you strong protection. Violating any one of them is a yellow flag:

1. Holding period of at least **six months** before any sale
2. Transaction volume below **five times** the opening portfolio balance in the tax year
3. Capital gains below **50% of total taxable income** in the tax year
4. **No debt financing** used to acquire crypto
5. **Derivatives used for hedging only**, not speculation

For the declaration itself, this matters in one concrete way: if you are clearly a private investor, you declare total portfolio value in the securities schedule and move on. If you are borderline — high volume, short holding periods, significant gains relative to other income — you may want to annotate your return and be prepared for cantonal questions. Some people in this situation proactively attach a memo explaining their holding pattern.

The detailed analysis on this classification lives in the [Swiss Crypto Tax Advantage guide](/posts/swiss-crypto-tax-advantage-guide/) — the H01 pillar article covers all five criteria and what "borderline" actually looks like in practice.

## DeFi Positions, Staking Rewards, and NFTs

These three categories require separate attention because each generates something other than a simple static holding.

**Staking rewards:** Treated as investment income (Kapitalertrag) in Switzerland, not capital gains. They are taxable in the year you receive them, at the CHF market value on the date of receipt. You declare them in the income schedule (Vermögenserträge), not in the securities schedule. The fact that you later hold those staking rewards as crypto and their value changes does not retroactively change the income declaration — what was taxed was the income-type event, not the subsequent price movement.

If you stake through a pool (Lido, RocketPool, etc.), the periodic reward distributions count individually at receipt-date value. If you stake solo as a validator, some cantons treat this as self-employment activity rather than investment income — the distinction matters for AHV contributions.

**DeFi yield positions:** Broadly similar to staking in tax treatment. Yield from liquidity provision, lending protocols, or yield farming is treated as income at the moment you receive or can claim it. At December 31st, you also need to declare any tokens still locked in a protocol at their current market value — this is the wealth tax snapshot applied to DeFi positions.

{{< skip-box title="Locked liquidity positions and LP tokens" >}}
If you hold liquidity pool (LP) tokens or have funds locked in a smart contract on December 31st, those assets are still part of your wealth and should be declared. The value to use is the underlying asset value (what your LP position could be redeemed for at that date), not the nominal value of the LP token itself, unless they trade at parity.
{{< /skip-box >}}

**NFTs:** The SFTA has not issued dedicated NFT guidance as of early 2025. The practical approach that most Swiss tax advisors recommend: treat NFTs as intangible assets, declare them at market value on December 31st if that value is determinable (a recent sale, a floor price from a recognized marketplace), or at original purchase price in CHF if no current market value exists. Income from NFT royalties is taxable when received.

## What CARF Means for Your Return Going Forward

Starting in 2027, Swiss crypto platforms will begin reporting account data to the SFTA under the CARF (Crypto Asset Reporting Framework). The first actual data exchange with foreign authorities is expected around 2028.

This does not change what you should be declaring right now — the obligation to declare has always existed. But it does mean that the era of practical obscurity for crypto holdings is ending. If you have not been declaring, the window for clean voluntary disclosure is open now and will narrow once automated reporting begins.

The [CARF delay field note](/posts/switzerland-carf-delay-2027/) covers the 2027 timeline and what it means for Swiss holders in more detail.

## The Nachdeklaration: What to Do If You Have Never Declared

If you have held crypto for several years without declaring it on your tax returns, Switzerland offers a voluntary self-disclosure procedure — Nachdeklaration or spontaneous declaration — that is available in all cantons.

The procedure works roughly as follows:

1. Contact your cantonal tax authority (or engage a tax professional to do so on your behalf)
2. Submit amended tax returns for the prior years showing the crypto holdings you should have declared
3. Pay the back taxes owed plus interest (typically 3-5% per year, depending on canton)
4. In most cases, avoid criminal penalties — the Nachdeklaration is generally treated as a civil correction rather than a criminal matter, provided you come forward voluntarily before authorities have started their own investigation

The interest accumulates from when the tax would originally have been due, so the cost increases the longer you wait. For someone who has held significant crypto since 2017 and never declared, the interest portion alone can be substantial.

{{< num-highlight number="5 years" label="Rough maximum look-back period most cantonal offices pursue for ordinary (non-fraud) undeclared assets" >}}

One practical note: Nachdeklaration requires you to reconstruct your December 31st portfolio value for each prior year. This means pulling historical exchange rates and SFTA Kursliste values going back to when you first held. The SFTA publishes historical rate lists. CoinMarketCap maintains daily historical price data. It is tedious, but the documentation is available.

## The Practical Checklist for Filing Season

Every February-March, when Swiss cantonal tax return deadlines approach, the same sequence applies:

{{< budget-table title="Crypto tax declaration checklist — annual sequence" >}}
| Step | What to do | Notes |
|---|---|---|
| 1 | Export year-end statements from all exchanges | Balance as of December 31st |
| 2 | Check SFTA Kursliste for BTC, ETH, and any listed assets | estv.admin.ch, published Jan-Feb |
| 3 | For unlisted assets, note Dec 31st price from exchange (USD) | CoinMarketCap historical data works |
| 4 | Convert non-CHF prices using SFTA exchange rate list | Same source as Kursliste |
| 5 | Sum total CHF value across all wallets/exchanges | Aggregate figure is fine |
| 6 | Enter in Wertschriften schedule of cantonal tax software | Field labeled "securities" or "crypto" |
| 7 | Separately calculate staking/yield income received in year | Date received × CHF value at that date |
| 8 | Enter staking/yield income in income/revenue section | Separate from wealth declaration |
| 9 | Keep all documentation | Cantonal office can request it for up to 10 years |
{{< /budget-table >}}

The declaration itself is not technically complex — the valuation and conversion calculation is the most time-consuming part for anyone with a diversified portfolio. Software tools like Koinly or Blockpit can automate most of steps 1-5 and generate a report formatted for Swiss cantonal returns.

## A Note on Swiss Bank Statements as Documentation

If you hold crypto through a FINMA-licensed institution like AMINA Bank or Sygnum Bank, your year-end bank statement should show the CHF-valued portfolio balance on December 31st directly. This is one of the practical advantages of the regulated Swiss crypto banking route — the documentation is formatted for Swiss tax purposes from the start.

The [Swiss crypto bank account field note](/posts/crypto-friendly-bank-account-switzerland/) covers what is involved in accessing those institutions, for anyone considering that path.

## Bottom Line

The Swiss approach to crypto taxation is structurally favorable for long-term holders — capital gains stay exempt, and the wealth tax on a buy-and-hold portfolio is relatively predictable year to year. The December 31st snapshot is the mechanism that makes it work.

For the declaration itself: get the SFTA Kursliste number for whatever you hold, convert everything to CHF, add it up, and put the total in the Wertschriften section of your cantonal tax return. Staking income goes in a separate income field. Keep your documentation.

The part that catches people is not the mechanics but the failure to declare at all. If that is your situation, the Nachdeklaration route is clean and available — and the window before CARF reporting begins is the right time to use it.

---

*Not tax advice. Swiss tax treatment of crypto depends on individual circumstances, cantonal variation, and annual SFTA guidance updates. Consult a qualified Swiss tax professional for filing decisions.*
