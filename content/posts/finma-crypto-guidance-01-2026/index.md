---
title: "FINMA's Crypto Guidance 01/2026: What It Actually Means for Custody (Not the Legal Version)"
date: 2026-02-14
lastmod: 2026-10-13
description: "FINMA published Guidance 01/2026 on crypto custody in January 2026. Here is what the circular actually requires — asset segregation, foreign custodian rules, and what changes for individuals holding crypto via Swiss institutions. Plain language, not a law firm memo."
categories: ["regulation"]
tags: ["FINMA", "custody", "swiss crypto regulation", "DLT Act", "asset segregation"]
draft: false
image: hero.jpg
readtime: 9
glossary:
  - term: "FINMA"
    def: "Swiss Financial Market Supervisory Authority (Eidgenössische Finanzmarktaufsicht). Licenses and supervises Swiss banks, securities firms, asset managers, and crypto-related financial service providers."
  - term: "DLT Act"
    def: "Switzerland's Distributed Ledger Technology Act (2021). Created the legal foundation for DLT-based securities and established the uncredited securities ledger — the basis for most Swiss crypto custody law."
  - term: "Bankruptcy-remote custody"
    def: "Crypto assets held in a way that keeps them outside a custodian's insolvency estate. Under Swiss law, this requires clear individual or collective segregation with documented client shares."
  - term: "Rehypothecation"
    def: "The practice of a custodian using client-held assets as collateral for its own positions. FINMA's guidance makes explicit consent requirements for this."
  - term: "MiCA"
    def: "Markets in Crypto-Assets Regulation. EU-wide regulation for crypto-asset service providers, fully in force since December 2024. FINMA guidance now acknowledges MiCA-supervised custodians as potentially meeting Swiss equivalence standards."
  - term: "CASP"
    def: "Crypto-Asset Service Provider. The MiCA term for regulated crypto businesses — exchanges, custodians, brokers — operating within EU jurisdiction."
  - term: "CARF"
    def: "Crypto-Asset Reporting Framework. OECD standard for cross-border tax information exchange on crypto holdings. Switzerland has the legal basis on its statute book, but the provisions do not apply in 2026; implementation can start on 1 January 2027 at the earliest."
sources:
  - name: "FINMA Guidance 01/2026 — official press release"
    url: "https://www.finma.ch/en/news/2026/01/20260112-mm-am-01-26/"
    desc: "finma.ch — original announcement, January 12, 2026"
  - name: "MLL Law — New Regulatory Standards for Crypto Custody"
    url: "https://www.mll-news.com/new-regulatory-standards-for-the-custody-of-cryptobased-assets-finma-guidance-01-2026/?lang=en"
    desc: "MLL Legal — detailed legal commentary, January 2026"
  - name: "Bär & Karrer — FINMA Publishes Guidance 01/2026"
    url: "https://www.baerkarrer.ch/en/publications/finma-publishes-guidance-01/2026-on-the-custody-of-crypto-based-assets"
    desc: "Bär & Karrer — five-scenario breakdown, January 2026"
  - name: "Federal Council — FinIA consultation on two new crypto licence categories"
    url: "https://www.sif.admin.ch/en/newnsb/x4TMWQ1SWofNoFx7XyHhY"
    desc: "sif.admin.ch — consultation opened 22 October 2025, closed 6 February 2026"
  - name: "WAK-N press release — CARF partner-state bill suspended"
    url: "https://www.parlament.ch/press-releases/Pages/mm-wak-n-2025-11-04.aspx"
    desc: "parlament.ch — National Council economic affairs committee, 4 November 2025, 18 votes to 0 with 4 abstentions"
  - name: "Federal Council — crypto-asset AEOI provisions do not apply in 2026"
    url: "https://www.efd.admin.ch/en/newnsb/oAaJyRFS1lqJ7PN3sLJTP"
    desc: "efd.admin.ch — decision of 26 November 2025; CARF implementation in 2027 at the earliest"
  - name: "FINMA Guidance 06/2024 — stablecoins"
    url: "https://www.finma.ch/en/news/2024/07/20240726-m-am-06-24-stablecoins/"
    desc: "finma.ch — 26 July 2024, bank default guarantees and AML identity duties for stablecoin issuers"
  - name: "Post-Trade 360 — FINMA custody guidance analysis"
    url: "https://posttrade360.com/news/regulation/finma-releases-guidance-for-the-custody-of-cryptoassets/"
    desc: "Post-Trade 360 — industry implications, January 2026"
---

On January 12, 2026, [FINMA](https://www.finma.ch/en/) published Guidance 01/2026 — its clearest statement yet on how Swiss regulated institutions must handle crypto-asset custody. The document is dense, technically precise, and written for compliance officers, not individual holders.

This is an attempt to translate what it actually says, what it changes in practice, and where it leaves open questions that still matter if you hold crypto in Switzerland.

## Why FINMA Published This Now

The timing is not accidental, but nothing that set it up happened in January. Three pressures had accumulated by the time the guidance landed, and the most recent of them was already three months old.

First, and closest to the date: the Federal Council [opened its consultation](https://www.sif.admin.ch/en/newnsb/x4TMWQ1SWofNoFx7XyHhY) on the Financial Institutions Act on 22 October 2025, proposing two new licence categories for crypto firms. A structural reform of who gets supervised assumes a settled answer to what supervised custody has to look like, and that answer was scattered across practice rather than written down.

Second, and a year before that: MiCA (the EU's Markets in Crypto-Assets Regulation) became fully applicable on 30 December 2024. With a large, adjacent jurisdiction now operating a coherent crypto regulatory framework, FINMA faced pressure to clarify how Swiss-supervised institutions should evaluate EU-based custodians.

Third, and with no single date on it at all: FINMA had observed in its supervisory work that some Swiss-licensed institutions were not adequately accounting for custody risks when using third-party providers — particularly foreign providers without equivalent oversight. The guidance formalizes what had previously been supervisor expectation rather than written rule.

<div class="data-callout">
<p class="callout-label">Context: the CARF timing</p>
<p>One thing worth correcting from the January commentary: the guidance did not arrive alongside a live CARF regime. At its session of 3–4 November 2025 the National Council's Economic Affairs and Taxation Committee <a href="https://www.parlament.ch/press-releases/Pages/mm-wak-n-2025-11-04.aspx">suspended the partner-state bill</a> by 18 votes to zero with four abstentions, and on 26 November 2025 the Federal Council <a href="https://www.efd.admin.ch/en/newnsb/oAaJyRFS1lqJ7PN3sLJTP">confirmed</a> that the crypto-asset provisions of Swiss automatic-exchange law would not apply in 2026 at all — <a href="/posts/switzerland-carf-delay-2027/">implementation can start on 1 January 2027 at the earliest</a>. The custody guidance stands on its own supervisory logic — who holds whose assets, and what happens in an insolvency — not on a tax-reporting deadline that never started.</p>
</div>

## What the Guidance Actually Requires

The guidance addresses five distinct custody scenarios. Each has its own logic and its own set of obligations.

### 1. Swiss Bank Custody (Direct)

When a FINMA-licensed bank holds crypto directly for clients, the assets must be held in a way that is "bankruptcy-remote" — meaning they cannot be claimed by the bank's own creditors if the institution fails.

Swiss law (via the [DLT Act](https://www.sif.admin.ch/en/dlt-blockchain-en) and existing banking law) already requires this in principle. The guidance makes it explicit: client assets must be segregated at the individual ledger address level, not just as an aggregate balance. The bank's own holdings must remain separate from client holdings at all times.

{{< num-highlight value="2" label="Custody types FINMA accepts" note="individual segregation or collective custody with documented client shares" >}}

### 2. Delegation to Foreign Custodians

This is the part that has attracted the most legal commentary, and where the practical implications are real.

Swiss institutions can delegate crypto custody to foreign providers — but only if two conditions are independently satisfied:

**Prudential supervision equivalence:** The foreign custodian must face comparable regulatory oversight regarding capital, liquidity, and risk management. This means [MiCA](https://en.wikipedia.org/wiki/Markets_in_Crypto-Assets)-licensed custodians in the EU now have a clear pathway to qualifying — something the guidance explicitly acknowledges.

**Bankruptcy protection equivalence:** Foreign law must ensure that client crypto assets are excluded from the custodian's insolvency estate. Supervision alone is not enough. An institution can be well-regulated and still lack the legal mechanism to segregate client assets in bankruptcy.

This dual-requirement approach is tighter than what many institutions had previously assumed. Meeting one condition without the other is not sufficient.

{{< skip-box title="When does this affect you as an individual holder?" >}}
If you hold crypto through a Swiss bank or regulated asset manager — not directly, not on a foreign exchange — your custodian is subject to these rules. The guidance changes the custodian's internal obligations, not your direct relationship with your assets.

If your custodian delegates to a foreign provider that does not meet both conditions above, the guidance requires your custodian to either restructure the arrangement or obtain your explicit written consent acknowledging the elevated risk.
{{< /skip-box >}}

### 3. Portfolio Management (Individual Clients)

For Swiss portfolio managers holding crypto on behalf of clients:

Assets must be held at prudentially supervised institutions — either in Switzerland or at equivalently supervised foreign providers. The key addition is that the segregation must be per-client, not pooled. Each client's assets must be identifiable individually.

Where existing arrangements do not meet this standard, the institution has two options: restructure the custody arrangement, or obtain documented written client consent acknowledging the non-compliant structure and the associated risks. Continuation without one of these two paths is not acceptable.

### 4. Collective Investment Schemes

For funds and collective investment vehicles, the rules are stricter.

The default requirement is that crypto assets be held with a Swiss custodian bank. Delegation to third parties — domestic or foreign — is permitted only where both prudential supervision equivalence and bankruptcy protection equivalence are met, and where investors are explicitly informed of the associated risks in the fund's prospectus.

This is meaningful for the growing number of Swiss-structured crypto funds. The prospectus disclosure requirement gives investors a clearer view of the custodial chain than many current funds provide.

### 5. Structured Products and ETPs

For structured products and exchange-traded products where crypto is held as underlying collateral:

Special purpose entities may issue these products only through prudentially supervised institutions that can provide legally enforceable guarantees or real security over the underlying crypto assets. This applies specifically to retail-accessible products.

The language is targeted at the infrastructure layer of crypto ETPs and structured notes — the part that most individual investors never see but that determines what happens in a default scenario.

## What This Actually Changes in Practice

The guidance mostly formalizes expectations that FINMA had already been communicating in supervisory conversations. For the major Swiss crypto banks — [AMINA Bank](https://en.wikipedia.org/wiki/SEBA_Bank) (SEBA Bank until its rebrand in December 2023), [Sygnum](https://www.sygnum.com/), and others — the operational reality changes less than the compliance documentation requirement.

What does change more materially:

**For smaller or newer institutions:** The explicit dual-requirement test for foreign custodians raises the bar for any institution that had been relying on a foreign provider that meets regulatory standards in its home jurisdiction but lacks clear bankruptcy protection equivalence under that jurisdiction's law.

**For EU custodians:** MiCA compliance now creates a defined pathway to qualifying as an acceptable foreign custodian for Swiss institutions. This is practically significant: it means Swiss firms can continue using or onboarding EU-based custodians without constructing equivalence arguments from scratch.

**For existing non-compliant arrangements:** The written consent mechanism is a transitional provision, not a permanent solution. The implicit message is that institutions should be moving toward compliant structures, with client consent as a documented interim state.

{{< budget-table title="FINMA Guidance 01/2026: What Changed for Each Scenario" sub="Summary across the five custody contexts" >}}
| Scenario | Key Obligation | What's New |
|---|---|---|
| Swiss bank custody | Individual segregation at ledger level | Made explicit (was principle, now written rule) |
| Foreign custodians | Dual test: supervision equivalence + bankruptcy protection | Both required independently; meeting one is insufficient |
| Portfolio management | Per-client segregation; non-compliant arrangements need documented consent | Consent mechanism formalized |
| Collective investment schemes | Swiss custodian bank as default; delegation only if equivalent + disclosed | Prospectus disclosure now required |
| Structured products / ETPs | Legally enforceable guarantees over underlying assets | Retail product collateral chain clarified |
{{< /budget-table >}}

<!-- IG-angle: Reading a compliance-officer circular for the boundary an individual holder actually needs — the four places the guidance stops (self-custody, tax treatment, stablecoin custody, and the absent equivalence whitelist); the legal commentary maps what the document covers, not where it becomes irrelevant to you -->

## What the Guidance Does Not Address

Worth being clear about what this document is not.

**It does not address self-custody.** The guidance applies to FINMA-supervised institutions. If you hold crypto in your own wallet, no custodian is involved and the guidance is irrelevant to you.

**It does not change the tax treatment of crypto assets.** Wealth tax obligations and the capital gains exemption for private investors are unaffected by custody structure — they depend on your status as a taxpayer, not on where your assets are held. The same goes for CARF, whenever it eventually runs.

**It does not resolve the [stablecoin](https://en.wikipedia.org/wiki/Stablecoin) custody question.** FINMA's published position on stablecoins is still [Guidance 06/2024](https://www.finma.ch/en/news/2024/07/20240726-m-am-06-24-stablecoins/), published on 26 July 2024, and that document is about issuance rather than custody — minimum requirements for the bank default guarantees some issuers rely on, and the obligation to verify the identity of everyone holding the token. Guidance 01/2026 covers crypto assets broadly and does not distinguish stablecoins from other tokens in custody terms, so the gap between the two documents is still open.

**It does not create an equivalence whitelist.** The guidance tells institutions what the test is but does not publish a list of foreign custodians that automatically qualify. Institutions must conduct their own equivalence assessments, with documentation.

## The Consolidation Effect

One practical consequence of the guidance is a likely consolidation of the institutional custody market toward larger, well-regulated providers.

The dual-requirement test for foreign custodians effectively excludes smaller or offshore providers that may offer competitive pricing but lack the regulatory and legal infrastructure required by the guidance. For Swiss institutions choosing or retaining custodians, the compliance burden of demonstrating equivalence is lower for established, well-supervised providers than for newer entrants.

Post-Trade 360's industry analysis noted that the requirements "may accelerate consolidation toward major regulated custodians while potentially excluding smaller, unregulated crypto custody providers from Swiss institutional business." For anyone holding crypto through a Swiss institution, the practical consequence is that custodian due diligence becomes a compliance task for that institution, not just a risk preference.

## What to Watch Going Forward

Three developments are worth tracking in the months following this guidance:

**Where stablecoin custody lands.** Nothing has been published since Guidance 06/2024, and the more consequential movement is legislative rather than supervisory: the Federal Council's FinIA proposal would give CHF-pegged stablecoin issuance its own licence category. Two concrete signals of where this is heading are the [UBS Swiss franc stablecoin sandbox](/posts/ubs-swiss-franc-stablecoin-sandbox/) and the [proposed payment instrument institution licence](/posts/finma-crypto-institution-license-2026/) — both field notes on what CHF-denominated crypto rails are actually being built on.

**How institutions document equivalence.** There is no standard template for equivalence assessments. How the industry develops a common approach — and whether FINMA publishes any additional guidance on the methodology — will determine how workable the framework is in practice.

**The written consent transition period.** Institutions with non-compliant existing arrangements that have chosen the consent path rather than restructuring will face ongoing supervisory scrutiny. FINMA's patience with that approach as a permanent solution is likely limited.

<div class="data-callout">
<p class="callout-label">The bottom line</p>
<p>FINMA Guidance 01/2026 is not a radical rewrite of Swiss crypto custody law. It is a clarification of how existing law applies — written out carefully enough that institutions can no longer claim uncertainty about what is expected. For individual holders using Swiss-regulated custodians, the practical effect is mostly invisible. For institutions designing or reviewing custody arrangements, the documentation requirements and the dual test for foreign custodians are the two things that require attention.</p>
</div>

---

*Zug Notes publishes field notes on Swiss crypto regulation and the [Crypto Valley](https://en.wikipedia.org/wiki/Crypto_Valley) ecosystem. Nothing on this site is legal or financial advice. The views expressed are those of the author based on publicly available information.*
