---
title: "FINMA's Crypto Guidance 01/2026: What It Actually Means for Custody (Not the Legal Version)"
date: 2026-02-14
lastmod: 2026-05-03
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
    def: "Crypto-Asset Reporting Framework. OECD standard for cross-border tax information exchange on crypto holdings, active in Switzerland from January 2026."
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
  - name: "Post-Trade 360 — FINMA custody guidance analysis"
    url: "https://posttrade360.com/news/regulation/finma-releases-guidance-for-the-custody-of-cryptoassets/"
    desc: "Post-Trade 360 — industry implications, January 2026"
---

On January 12, 2026, FINMA published Guidance 01/2026 — its clearest statement yet on how Swiss regulated institutions must handle crypto-asset custody. The document is dense, technically precise, and written for compliance officers, not individual holders.

This is an attempt to translate what it actually says, what it changes in practice, and where it leaves open questions that still matter if you hold crypto in Switzerland.

## Why FINMA Published This Now

The timing is not accidental. Three things converged at the start of 2026.

First, CARF — the OECD Crypto-Asset Reporting Framework — became active in Switzerland on January 1, 2026. The institutional custody infrastructure that CARF reporting depends on had to be formalized.

Second, MiCA (the EU's Markets in Crypto-Assets Regulation) came fully into force in December 2024. With a large, adjacent jurisdiction now operating a coherent crypto regulatory framework, FINMA faced pressure to clarify how Swiss-supervised institutions should evaluate EU-based custodians.

Third, FINMA had observed in its supervisory work that some Swiss-licensed institutions were not adequately accounting for custody risks when using third-party providers — particularly foreign providers without equivalent oversight. The guidance formalizes what had previously been supervisor expectation rather than written rule.

<div class="data-callout">
<p class="callout-label">Field observation — February 2026</p>
<p>The timing matters: FINMA published this guidance within days of CARF going live. Institutions that handle CARF reporting on behalf of clients need to know whose assets they are holding and under what legal framework — the guidance answers those questions at the infrastructure level.</p>
</div>

## What the Guidance Actually Requires

The guidance addresses five distinct custody scenarios. Each has its own logic and its own set of obligations.

### 1. Swiss Bank Custody (Direct)

When a FINMA-licensed bank holds crypto directly for clients, the assets must be held in a way that is "bankruptcy-remote" — meaning they cannot be claimed by the bank's own creditors if the institution fails.

Swiss law (via the DLT Act and existing banking law) already requires this in principle. The guidance makes it explicit: client assets must be segregated at the individual ledger address level, not just as an aggregate balance. The bank's own holdings must remain separate from client holdings at all times.

{{< num-highlight value="2" label="Custody types FINMA accepts" note="individual segregation or collective custody with documented client shares" >}}

### 2. Delegation to Foreign Custodians

This is the part that has attracted the most legal commentary, and where the practical implications are real.

Swiss institutions can delegate crypto custody to foreign providers — but only if two conditions are independently satisfied:

**Prudential supervision equivalence:** The foreign custodian must face comparable regulatory oversight regarding capital, liquidity, and risk management. This means MiCA-licensed custodians in the EU now have a clear pathway to qualifying — something the guidance explicitly acknowledges.

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

The guidance mostly formalizes expectations that FINMA had already been communicating in supervisory conversations. For the major Swiss crypto banks — SEBA Bank (now rebranded), Sygnum, and others — the operational reality changes less than the compliance documentation requirement.

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

## What the Guidance Does Not Address

Worth being clear about what this document is not.

**It does not address self-custody.** The guidance applies to FINMA-supervised institutions. If you hold crypto in your own wallet, no custodian is involved and the guidance is irrelevant to you.

**It does not change the tax treatment of crypto assets.** Wealth tax obligations, the capital gains exemption for private investors, and CARF reporting thresholds are unaffected by custody structure — they depend on your status as a taxpayer, not on where your assets are held.

**It does not resolve the stablecoin custody question.** FINMA has signaled that guidance on stablecoin custody — particularly relevant given MiCA's stablecoin rules — is forthcoming. The current guidance focuses on crypto assets more broadly and does not distinguish between stablecoins and other tokens in custody terms.

**It does not create an equivalence whitelist.** The guidance tells institutions what the test is but does not publish a list of foreign custodians that automatically qualify. Institutions must conduct their own equivalence assessments, with documentation.

## The Consolidation Effect

One practical consequence of the guidance is a likely consolidation of the institutional custody market toward larger, well-regulated providers.

The dual-requirement test for foreign custodians effectively excludes smaller or offshore providers that may offer competitive pricing but lack the regulatory and legal infrastructure required by the guidance. For Swiss institutions choosing or retaining custodians, the compliance burden of demonstrating equivalence is lower for established, well-supervised providers than for newer entrants.

Post-Trade 360's industry analysis noted that the requirements "may accelerate consolidation toward major regulated custodians while potentially excluding smaller, unregulated crypto custody providers from Swiss institutional business." That reads as accurate from a Zug perspective: the institutions I have spoken with in recent months are increasingly focused on custodian due diligence as a compliance task, not just a risk preference.

## What to Watch Going Forward

Three developments are worth tracking in the months following this guidance:

**FINMA's stablecoin follow-up.** The regulator indicated further guidance on stablecoin custody is forthcoming. Given MiCA's detailed stablecoin framework, the pressure to clarify Swiss treatment is real.

**How institutions document equivalence.** There is no standard template for equivalence assessments. How the industry develops a common approach — and whether FINMA publishes any additional guidance on the methodology — will determine how workable the framework is in practice.

**The written consent transition period.** Institutions with non-compliant existing arrangements that have chosen the consent path rather than restructuring will face ongoing supervisory scrutiny. FINMA's patience with that approach as a permanent solution is likely limited.

<div class="data-callout">
<p class="callout-label">The bottom line</p>
<p>FINMA Guidance 01/2026 is not a radical rewrite of Swiss crypto custody law. It is a clarification of how existing law applies — written out carefully enough that institutions can no longer claim uncertainty about what is expected. For individual holders using Swiss-regulated custodians, the practical effect is mostly invisible. For institutions designing or reviewing custody arrangements, the documentation requirements and the dual test for foreign custodians are the two things that require attention.</p>
</div>

---

*Zug Notes publishes field observations on Swiss crypto regulation and the Crypto Valley ecosystem. Nothing on this site is legal or financial advice. The views expressed are those of the author based on publicly available information.*
