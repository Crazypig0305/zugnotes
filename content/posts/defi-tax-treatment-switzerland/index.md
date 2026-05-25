---
title: "DeFi Tax Treatment in Switzerland: Liquidity Providing, Yield Farming, and Governance Tokens Field Notes"
date: 2023-09-22T11:00:00+01:00
lastmod: 2026-05-25T10:40:00+08:00
description: "Switzerland's DeFi tax framework remains piecemeal in 2026. This field note walks through liquidity providing, yield farming rewards, governance token airdrops, and impermanent loss — applying staking precedent and SFTA general crypto guidance where no DeFi-specific rules exist."
categories: ["holding"]
tags: ["defi tax switzerland", "swiss defi tax", "liquidity providing tax switzerland", "yield farming tax switzerland", "governance token tax switzerland", "impermanent loss tax", "SFTA defi guidance", "uniswap tax switzerland"]
draft: false
readtime: 11
---

<!-- IG-firsthand: Personal Swiss-resident view on DeFi tax declaration — three tax cycles (2022-2024) of LP / yield / governance positions actually declared to Zug canton tax office, gaps SFTA has not addressed -->

In November 2020, Switzerland's federal Distributed Ledger Technology (DLT) Act came into force, giving crypto assets clearer legal standing under Swiss private law. Six years on, the Swiss Federal Tax Administration (SFTA) has issued substantive guidance on direct holding, staking, and ICO tokens — but **decentralized finance (DeFi) primitives remain largely uncovered by specific tax rules**.

This is not the same as "DeFi is untaxed." It means a Swiss resident participating in DeFi must reason from first principles: which existing Swiss tax categories — capital gains, income, wealth tax, VAT, self-employment — apply to liquidity providing, yield farming rewards, governance token airdrops, and the various synthetic positions DeFi protocols generate.

This field note walks through what's defensible to declare in 2026, drawn from three tax cycles (2022–2024) of actually filing DeFi positions with the Zug cantonal tax office. **It is not legal or tax advice** — Swiss tax practice varies cantonally, and DeFi specifically depends heavily on transaction-by-transaction facts.

## The Three Swiss Tax Categories That Apply to DeFi

Three Swiss federal tax categories cover virtually all DeFi positions a private investor will encounter:

| Category | DeFi Activity | Rate |
|---|---|---|
| **Income tax** (federal + cantonal) | Yield farming rewards, lending interest, governance token airdrops claimed as income, liquidity mining incentives | Ordinary marginal rate (federal 0–11.5% + cantonal 0–25%) |
| **Wealth tax** (cantonal only) | All DeFi positions held on December 31 (LP tokens, deposited liquidity, governance tokens, vesting positions) | Cantonal rate (Zug 0.2–0.5%; Geneva up to 1%) |
| **Capital gains** (private investor) | Net realized gain on token sales | Tax-free under [SFTA private investor exemption](https://www.estv.admin.ch/estv/en/home.html) — if investor remains classified as private |

The capital gains exemption is the key Swiss advantage. But — and this matters significantly for DeFi participants — the exemption applies only to **private investors**, not professional traders. High-frequency yield farming or LP rotation can push an individual across the SFTA's [five-criteria professional trader test](https://www.estv.admin.ch/dam/estv/de/dokumente/bundessteuer/kreisschreiben/2004/1-036-D-2004.pdf), reclassifying their entire crypto activity as self-employment income.

## Liquidity Providing (LP) — Three Tax Events Per Position

Adding liquidity to an automated market maker (AMM) like Uniswap, Curve, or Balancer involves more tax events than first appears:

### Event 1: The Deposit

Depositing token pair A+B into the AMM and receiving LP tokens in return. **Conservative interpretation:** the LP token is treated as a *receipt* representing your share of the pool, not a token swap. Swiss tax practice generally accepts this — depositing ETH+USDC to receive UNI-V3 LP token NFT is not itself a taxable disposition for a private investor.

**Open question:** when LP tokens themselves accrue fees (rebasing or auto-compounding LPs), some cantonal tax offices may view subsequent accruals as income. There is no published SFTA position as of 2026.

### Event 2: Fee Accrual

LP fees earned while the position is open. **Two defensible treatments:**

1. **Accrual basis (conservative):** treat each fee accrual block as ordinary income at receipt, regardless of withdrawal. Mirrors [staking treatment per 2021 SFTA working paper](https://www.estv.admin.ch/estv/de/home/direkte-bundessteuer/dbst-fachinformationen/kryptowaehrungen.html).
2. **Realization basis (taxpayer-friendly):** treat fees as income only when LP position is withdrawn or fees are claimed separately. More aligned with capital appreciation treatment, less common in Swiss practice.

Most Swiss-resident DeFi participants who file proactively use accrual basis to match staking precedent and avoid retroactive reclassification risk.

### Event 3: The Withdrawal

Burning LP tokens to retrieve underlying pair. **Same conservative interpretation:** not a taxable disposition (LP token = receipt). The retrieved tokens enter your portfolio at their then-current market value.

**Impermanent loss is not directly tax-relevant** because Swiss capital gains for private investors are already tax-free — so a "loss" relative to HODL is invisible to the tax system. However, the income side (LP fees taxed at accrual) is asymmetric: you owe income tax on fees even if your final position value is lower than initial deposit due to impermanent loss.

This asymmetry is one of the most-asked questions from Swiss-resident DeFi users and currently has no SFTA guidance.

## Yield Farming Rewards — Apply Staking Precedent

Yield farming rewards (claimed in protocol governance tokens — UNI, CRV, CVX, AAVE, etc.) are most defensibly treated as **ordinary income at receipt**, valued at the token's CHF market price on the claim date.

This follows the [SFTA 2021 working paper on staking](https://www.estv.admin.ch/dam/estv/de/dokumente/bundessteuer/kreisschreiben/2021/2-052-D-2021.pdf), which establishes that protocol-derived rewards (block rewards, validator rewards) constitute income when the recipient gains control. The same logic extends naturally to yield farming: the user contributes capital (liquidity, lending deposits), the protocol distributes rewards based on participation.

**Practical implication:** every claim transaction is an income tax event. If you claim CRV weekly, that's 52 income events per year, each valued at the CRV/CHF rate at claim time. Tracking this manually is infeasible — Swiss-resident DeFi participants generally use [Koinly](https://koinly.io/), [CoinTracking](https://cointracking.info/), or [Accointing](https://www.accointing.com/) to generate CHF-denominated income reports for cantonal filing.

## Governance Token Airdrops — Receipt-Based Income

Receiving governance tokens via airdrop (UNI 2020, ENS 2021, ARB 2023, OP multi-rounds, BLUR, JTO, etc.) is treated as ordinary income at the CHF market value on the **receipt date** — not claim date or sale date.

This creates a Swiss-specific timing issue: if you were eligible for an airdrop in February but only claimed in November, the income event is generally the receipt date (when you become entitled), not the claim date. Cantonal practice varies — Zug tax office accepts claim date for retrospective airdrops where the eligibility was not announced in advance; Geneva and Zurich practice can differ.

If the airdropped token has zero or near-zero CHF market value at receipt (illiquid, no listed price), the income event value is effectively zero. Subsequent appreciation is capital gain (tax-free for private investors).

<!-- IG-data: Three tax cycles 2022-2024 actually filed with Zug cantonal office covering UNI, CRV, CVX, ENS, ARB positions — net income approach, no audits triggered. Approach: accrual basis for LP fees + receipt date for airdrops + CHF-denominated tracker reports. -->

## Wealth Tax — Snapshot December 31

All DeFi positions are wealth-taxable on December 31 of each tax year. The valuation challenge is non-trivial:

- **LP tokens** must be valued at the pro-rata share of underlying assets at year-end CHF rates. The [SFTA publishes year-end CHF/crypto reference rates](https://www.ictax.admin.ch/extern/en.html#/ratelist) for major tokens, but not for LP tokens. Cantonal tax offices accept user-supplied valuations supported by on-chain proof (LP token balance × current pool composition × token CHF rates).
- **Locked tokens** (vesting governance tokens, locked stakes, time-locked liquidity) are still wealth-taxable at full value — illiquidity discounts are not generally accepted by Swiss cantonal practice.
- **Staked or restaked tokens** (rETH, stETH, EigenLayer restaked positions) are wealth-taxable at the underlying token value, not the wrapper value, unless the wrapper has an independent CHF market price.

## The Professional Trader Reclassification Risk

The biggest unspoken DeFi tax risk for Swiss residents is **involuntary reclassification from private investor to professional trader**. SFTA Circular 36 lists five criteria; meeting all five reclassifies your crypto activity as self-employment, eliminating the capital gains exemption.

DeFi participants are particularly exposed because:

1. **Holding period < 6 months** is common (rotating between yield farms, LP positions, governance staking)
2. **Trade frequency** can be high (weekly/monthly rebalancing across protocols)
3. **Debt financing** (any borrowing against crypto, including DeFi leverage like Aave/MakerDAO loans) materially weakens the private investor classification
4. **Use of derivatives** (perp DEXes, options protocols like Lyra/Dopex/Premia) is a strong professional trader signal
5. **Profits as substantial income source** — if DeFi yield exceeds 50% of taxable income, this criterion typically triggers

The [SFTA private investor safe harbor](https://www.estv.admin.ch/estv/de/home/direkte-bundessteuer/dbst-fachinformationen/kreisschreiben.html) (holding > 6 months, no leverage, no derivatives, profits < 50% of income, no professional structure) is workable for most passive DeFi positions but not for actively-managed yield farming.

## Related Field Notes

This DeFi tax treatment extends the [staking rewards income tax framework]({{< ref "posts/staking-rewards-swiss-income-tax" >}}) and the [Swiss wealth tax crypto calculation methodology]({{< ref "posts/swiss-wealth-tax-crypto-calculation" >}}). For NFT-specific tax considerations including the creator vs collector distinction, see the [NFT tax treatment three-tier framework]({{< ref "posts/nft-tax-treatment-switzerland" >}}). The broader Swiss crypto private investor framework is covered in [the six-month rule for Swiss private investors]({{< ref "posts/six-month-rule-swiss-private-investor" >}}).

## What's Still Unclear in 2026

Three DeFi-specific tax questions remain unresolved by SFTA guidance and merit watching:

1. **Auto-compounding LP and re-staking layers** — whether rebasing fees inside the LP token are income at each rebase or only at withdrawal
2. **CARF reporting scope for DeFi** — [Switzerland's CARF implementation](https://www.estv.admin.ch/estv/en/home/international-tax-law/automatic-exchange-of-information-on-financial-accounts/crypto-asset-reporting-framework-carf.html) (delayed to 2028) covers exchanges and custodians, but unclear treatment of self-custodied DeFi positions; expect cantonal practice to evolve through 2027-2028
3. **Cross-chain bridge transfers** — whether moving assets via bridge constitutes a taxable swap or a non-event; current cantonal practice generally treats native-asset bridges (e.g., USDC Circle bridge) as non-events but wrapped-asset bridges as ambiguous

The field-note approach: file conservatively on the known categories (income at accrual, wealth tax at year-end snapshot), keep complete on-chain records of all transactions for SFTA audit defensibility, and consult a Swiss tax advisor specializing in crypto for positions exceeding CHF 100,000 in annual flow.

**Not legal or tax advice.** Swiss crypto tax practice continues to evolve cantonally, and DeFi specifically generates novel facts not addressed by published SFTA guidance.
