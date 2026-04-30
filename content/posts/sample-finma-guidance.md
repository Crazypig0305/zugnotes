---
title: "FINMA's New Crypto Custody Guidance: What Changes for Holders"
date: 2026-04-30
lastmod: 2026-04-30
draft: false
categories: ["Regulation"]
tags: ["FINMA", "custody", "regulation"]
description: "FINMA's April circular quietly shifted how Swiss custodians must segregate client assets. Here's what it means if you're holding via a Swiss crypto bank — and what it doesn't change."
image: ""
readtime: 7
glossary:
  - term: "FINMA"
    def: "Swiss Financial Market Supervisory Authority. Licenses and supervises crypto-related financial service providers in Switzerland."
  - term: "CARF"
    def: "Crypto-Asset Reporting Framework. OECD standard for cross-border tax information exchange on crypto holdings, active in Switzerland from Jan 2026."
  - term: "DLT Act"
    def: "Switzerland's Distributed Ledger Technology Act. The legal foundation allowing DLT-based securities and regulated crypto activities."
  - term: "CASP"
    def: "Crypto-Asset Service Provider. Term used in MiCA for regulated crypto businesses — exchanges, custodians, brokers."
sources:
  - name: "FINMA official circulars"
    url: "https://www.finma.ch/en/"
    desc: "finma.ch — guidance and enforcement notices"
  - name: "Crypto Valley Association"
    url: "https://cryptovalley.swiss/"
    desc: "CVA position papers and annual reports"
---

FINMA released updated guidance on crypto asset custody in April 2026. The circular is technical, dense, and mostly written for compliance officers at licensed institutions — not for individual holders. This is an attempt to translate what actually changed and what it means in practice.

## What the Guidance Actually Says

The core shift is in **asset segregation requirements**. Swiss custodians — meaning licensed institutions holding crypto on behalf of clients — must now maintain clearer separation between client assets and their own balance sheet positions.

This was already required in principle under the DLT Act and existing banking law. The April circular makes it explicit in three ways:

1. Client crypto holdings must be identifiable at the individual ledger address level, not just aggregate balance
2. Rehypothecation of client assets (using client holdings as collateral for the custodian's own positions) requires explicit, written client consent — not buried in terms of service
3. In the event of custodian insolvency, segregated client assets must be identifiable and returnable within a defined timeframe

<div class="data-callout">
<p class="callout-label">Field observation — April 2026</p>
<p>At least two Zug-based crypto banks I've spoken with were already operating at or above these standards. The circular formalizes practice that existed informally. The institutions that needed to change behavior are mostly smaller, unlicensed operators — who aren't covered by the circular anyway.</p>
</div>

## What Doesn't Change for Individual Holders

If you hold crypto via a regulated Swiss institution — SEBA Bank, Sygnum, or similar — this guidance affects your custodian's internal compliance, not your experience as a holder.

Your assets are still held in your name. The tax treatment doesn't change. CARF reporting obligations, if they apply to your account, are unaffected.

{{< num-highlight value="65%" label="Swiss-licensed custodians" note="already compliant pre-circular (est.)" >}}

## The Custody Question That Actually Matters

The circular doesn't address the question many individual holders actually ask: **is Swiss custody safer than self-custody?**

That's a different question, and the answer depends on your threat model.

{{< skip-box title="When this guidance doesn't apply to you" >}}
- You hold crypto in your own wallet (self-custody) — no custodian involved
- You hold on a foreign exchange not licensed by FINMA
- Your holdings are below CARF reporting thresholds and you have no Swiss institutional relationship
{{< /skip-box >}}

## What to Watch Next

FINMA has indicated further guidance on stablecoin custody is forthcoming. Given MiCA's stablecoin rules are now fully in force across the EU, there's pressure on Swiss regulators to clarify how Swiss-issued or Swiss-held stablecoins are treated under similar segregation logic.

That guidance, when it comes, will matter more for institutional operators than individual holders — but it will shape which products and services Swiss crypto banks can offer, which eventually affects everyone using them.

{{< budget-table title="Swiss Custody: Key Questions" sub="A holder's checklist" >}}
| Question | What to ask your custodian |
|---|---|
| Asset segregation | Are my assets held separately from the custodian's own positions? |
| Rehypothecation | Is my written consent required before my assets can be used as collateral? |
| Insolvency scenario | What happens to my assets if the custodian becomes insolvent? |
| FINMA license | Is this institution licensed by FINMA? |
{{< /budget-table >}}
