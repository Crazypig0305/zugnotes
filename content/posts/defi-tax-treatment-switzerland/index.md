---
title: "DeFi Tax Treatment in Switzerland: Liquidity Providing, Yield Farming, and Governance Tokens Field Notes"
date: 2023-09-22T11:00:00+01:00
lastmod: 2026-10-13
description: "Switzerland's DeFi tax framework remains piecemeal in 2026. This field note walks through liquidity providing, yield farming rewards, governance token airdrops, and impermanent loss — applying staking precedent and SFTA general crypto guidance where no DeFi-specific rules exist."
categories: ["holding"]
tags: ["defi tax switzerland", "swiss defi tax", "liquidity providing tax switzerland", "yield farming tax switzerland", "governance token tax switzerland", "impermanent loss tax", "SFTA defi guidance", "uniswap tax switzerland"]
draft: false
readtime: 11
---

<!-- IG-synthesis: Applying the SFTA's staking logic, its crypto working paper and the Circular 36 safe harbour by analogy to DeFi primitives — LP deposit, fee accrual and withdrawal, yield claims, airdrops, year-end LP valuation — where no DeFi-specific SFTA rules exist; built from SFTA documents and published tax-tool guides, no personal filing experience is claimed -->

Switzerland's federal Distributed Ledger Technology (DLT) Act cleared parliament in September 2020 and came into force in two stages: 1 February 2021 for the ledger-based securities provisions in the Code of Obligations, and 1 August 2021 for the financial market pieces, including the DLT trading facility licence. Together they gave crypto assets clearer legal standing under Swiss private law. Five years on, the Swiss Federal Tax Administration (SFTA) has issued substantive guidance on direct holding, staking, and ICO tokens — but **decentralized finance (DeFi) primitives remain largely uncovered by specific tax rules**.

This is not the same as "DeFi is untaxed." It means a Swiss resident participating in DeFi must reason from first principles: which existing Swiss tax categories — capital gains, income, wealth tax, VAT, self-employment — apply to liquidity providing, yield farming rewards, governance token airdrops, and the various synthetic positions DeFi protocols generate.

This field note walks through what's defensible to declare in 2026, built from the SFTA's published guidance and applied by analogy where that guidance is silent. **It is not legal or tax advice** — Swiss tax practice varies cantonally, and DeFi specifically depends heavily on transaction-by-transaction facts.

## The Three Swiss Tax Categories That Apply to DeFi

Three Swiss federal tax categories cover virtually all DeFi positions a private investor will encounter:

| Category | DeFi Activity | Rate |
|---|---|---|
| **Income tax** (federal + cantonal) | Yield farming rewards, lending interest, governance token airdrops claimed as income, liquidity mining incentives | Ordinary marginal rate (federal 0–11.5% + cantonal 0–25%) |
| **Wealth tax** (cantonal and municipal only — there is no federal wealth tax) | All DeFi positions held on December 31 (LP tokens, deposited liquidity, governance tokens, vesting positions) | Effective rate on CHF 1m of taxable net wealth, 2026: Zug ~0.14%, Zurich ~0.17%, Geneva ~0.51% |
| **Capital gains** (private investor) | Net realized gain on token sales | Tax-free under [SFTA private investor exemption](https://www.estv.admin.ch/en/cryptocurrencies-taxation) — if investor remains classified as private |

The capital gains exemption is the key Swiss advantage. But — and this matters significantly for DeFi participants — the exemption applies only to **private investors**, not professional traders. High-frequency yield farming or LP rotation can knock an individual out of the SFTA's [five-criteria safe harbour for private investors](https://www.estv.admin.ch/de/kryptowaehrungen-besteuerung), which is what opens the door to their entire crypto activity being reclassified as self-employment income.

## Liquidity Providing (LP) — Three Tax Events Per Position

Adding liquidity to an automated market maker (AMM) like Uniswap, Curve, or Balancer involves more tax events than first appears:

### Event 1: The Deposit

Depositing token pair A+B into the AMM and receiving LP tokens in return. **Conservative interpretation:** the LP token is treated as a *receipt* representing your share of the pool, not a token swap. On that reading, depositing ETH+USDC to receive a UNI-V3 LP token NFT is not itself a taxable disposition for a private investor. It is the conservative reading; the SFTA has not published a position on LP tokens specifically.

**Open question:** when LP tokens themselves accrue fees (rebasing or auto-compounding LPs), some cantonal tax offices may view subsequent accruals as income. There is no published SFTA position as of 2026.

### Event 2: Fee Accrual

LP fees earned while the position is open. **Two defensible treatments:**

1. **Accrual basis (conservative):** treat each fee accrual block as ordinary income at receipt, regardless of withdrawal. Mirrors [staking treatment per 2021 SFTA working paper](https://www.estv.admin.ch/estv/de/home/direkte-bundessteuer/dbst-fachinformationen/kryptowaehrungen.html).
2. **Realization basis (taxpayer-friendly):** treat fees as income only when LP position is withdrawn or fees are claimed separately. More aligned with capital appreciation treatment, but the less conservative of the two.

Accrual basis is the safer default: it matches staking precedent and avoids retroactive reclassification risk.

### Event 3: The Withdrawal

Burning LP tokens to retrieve underlying pair. **Same conservative interpretation:** not a taxable disposition (LP token = receipt). The retrieved tokens enter your portfolio at their then-current market value.

**Impermanent loss is not directly tax-relevant** because Swiss capital gains for private investors are already tax-free — so a "loss" relative to HODL is invisible to the tax system. However, the income side (LP fees taxed at accrual) is asymmetric: you owe income tax on fees even if your final position value is lower than initial deposit due to impermanent loss.

This asymmetry currently has no SFTA guidance.

## Yield Farming Rewards — Apply Staking Precedent

Yield farming rewards (claimed in protocol governance tokens — UNI, CRV, CVX, AAVE, etc.) are most defensibly treated as **ordinary income at receipt**, valued at the token's CHF market price on the claim date.

This follows the [SFTA working paper on cryptocurrencies](https://www.estv.admin.ch/de/kryptowaehrungen-besteuerung), which establishes that protocol-derived rewards (block rewards, validator rewards) constitute income when the recipient gains control. The same logic extends naturally to yield farming: the user contributes capital (liquidity, lending deposits), the protocol distributes rewards based on participation.

**Practical implication:** every claim transaction is an income tax event. If you claim CRV weekly, that's 52 income events per year, each valued at the CRV/CHF rate at claim time. Tracking this manually is infeasible — tools such as [Koinly](https://koinly.io/), [CoinTracking](https://cointracking.info/), or [Blockpit](https://www.blockpit.io/tax-guides/crypto-tax-guide-switzerland) can generate CHF-denominated income reports for cantonal filing. If you are working from an older Swiss guide that recommends Accointing, note that Blockpit acquired it and shut the standalone platform down at the end of January 2024; accointing.com now redirects to Blockpit.

## Governance Token Airdrops — Receipt-Based Income

Receiving governance tokens via airdrop (UNI 2020, ENS 2021, ARB 2023, OP multi-rounds, BLUR, JTO, etc.) is treated as ordinary income at the CHF market value on the **receipt date** — not claim date or sale date.

This creates a Swiss-specific timing issue: if you were eligible for an airdrop in February but only claimed in November, the income event is generally the receipt date (when you become entitled), not the claim date. Cantonal practice can differ on this, and no canton has published a position on retrospective airdrops. If the amount matters, ask your cantonal tax office before you file, or state in the return which date basis you used.

If the airdropped token has zero or near-zero CHF market value at receipt (illiquid, no listed price), the income event value is effectively zero. Subsequent appreciation is capital gain (tax-free for private investors).

## Wealth Tax — Snapshot December 31

All DeFi positions are wealth-taxable on December 31 of each tax year. The valuation challenge is non-trivial:

- **LP tokens** must be valued at the pro-rata share of underlying assets at year-end CHF rates. The [SFTA publishes year-end CHF/crypto reference rates](https://www.ictax.admin.ch/extern/en.html#/ratelist) for major tokens, but not for LP tokens. Without a reference rate, the defensible approach is a user-supplied valuation supported by on-chain proof (LP token balance × year-end pool composition × token CHF rates), with the calculation kept for the file.
- **Locked tokens** (vesting governance tokens, locked stakes, time-locked liquidity) are still wealth-taxable — do not assume an illiquidity discount will be accepted; none is set out in the SFTA guidance.
- **Staked or restaked tokens** (rETH, stETH, EigenLayer restaked positions) are wealth-taxable at the underlying token value, not the wrapper value, unless the wrapper has an independent CHF market price.

## The Professional Trader Reclassification Risk

The biggest unspoken DeFi tax risk for Swiss residents is **involuntary reclassification from private investor to professional trader**. The direction of the test is worth getting right, because it is often stated backwards: SFTA Circular 36 lists five criteria that work as a safe harbour. Meeting all five keeps you a private investor with the capital gains exemption intact. Failing them is what opens the door to reclassification as self-employment.

DeFi participants are particularly exposed because each of the five is easy to fail here:

1. **Holding period < 6 months** is common (rotating between yield farms, LP positions, governance staking)
2. **Trade frequency** can be high (weekly/monthly rebalancing across protocols)
3. **Debt financing** (any borrowing against crypto, including DeFi leverage like Aave/MakerDAO loans) materially weakens the private investor classification
4. **Use of derivatives** (perp DEXes, options protocols like Lyra/Dopex/Premia) is a strong professional trader signal
5. **Gains as a substantial income source** — the criterion is that realised capital gains stay below 50% of net income; a good year on token appreciation can break it on its own

The [SFTA private investor safe harbor](https://www.estv.admin.ch/de/kryptowaehrungen-besteuerung) (holding > 6 months, no leverage, no derivatives, profits < 50% of income, no professional structure) is workable for most passive DeFi positions but not for actively-managed yield farming.

## Related Field Notes

This DeFi tax treatment extends the [staking rewards income tax framework]({{< ref "posts/staking-rewards-swiss-income-tax" >}}) and the [Swiss wealth tax crypto calculation methodology]({{< ref "posts/swiss-wealth-tax-crypto-calculation" >}}). For NFT-specific tax considerations including the creator vs collector distinction, see the [NFT tax treatment three-tier framework]({{< ref "posts/nft-tax-treatment-switzerland" >}}). The broader Swiss crypto private investor framework is covered in [the six-month rule for Swiss private investors]({{< ref "posts/six-month-rule-swiss-private-investor" >}}).

## What's Still Unclear in 2026

Three DeFi-specific tax questions remain unresolved by SFTA guidance and merit watching:

1. **Auto-compounding LP and re-staking layers** — whether rebasing fees inside the LP token are income at each rebase or only at withdrawal
2. **CARF reporting scope for DeFi** — [Switzerland's CARF implementation](https://www.sif.admin.ch/de/automatischer-informationsaustausch-ueber-kryptowerte) covers exchanges and custodians, but the treatment of self-custodied DeFi positions is unclear. The timing is also still open: the crypto provisions are not applied in 2026 at all, 1 January 2027 is the earliest date the rules can start, the first actual exchange of data would come later, and parliament has not yet decided which partner jurisdictions are in. Expect cantonal practice to evolve through 2027-2028
3. **Cross-chain bridge transfers** — whether moving assets via bridge constitutes a taxable swap or a non-event; there is no published guidance; a native-asset bridge (e.g. Circle's USDC bridge) is arguably a non-event, while a wrapped-asset bridge is more ambiguous

The field-note approach: file conservatively on the known categories (income at accrual, wealth tax at year-end snapshot), keep complete on-chain records of all transactions for SFTA audit defensibility, and consult a Swiss tax advisor specializing in crypto for positions exceeding CHF 100,000 in annual flow.

**Not legal or tax advice.** Swiss crypto tax practice continues to evolve cantonally, and DeFi specifically generates novel facts not addressed by published SFTA guidance.
