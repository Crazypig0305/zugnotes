---
title: "The UBS Swiss Franc Stablecoin Sandbox: What It Actually Enables for CHF Crypto Rails"
date: 2026-04-10
lastmod: 2026-09-23
description: "Six Swiss banks including UBS and Sygnum launched a CHF stablecoin sandbox in April 2026; SIX and TWINT joined in September, taking it to nine. Here is what the pilot actually tests, why deposit tokens and stablecoins are different things, and what this means for Switzerland's crypto payment rails."
categories: ["ecosystem"]
tags: ["swiss franc stablecoin", "UBS stablecoin", "CHF crypto rails", "FINMA sandbox", "Swiss Stablecoin AG", "DLT payments switzerland", "deposit token"]
draft: false
readtime: 8
canonicalURL: "https://zugnotes.com/posts/ubs-swiss-franc-stablecoin-sandbox/"
glossary:
  - term: "CHFD"
    def: "The ticker symbol for the Swiss franc stablecoin being tested in the 2026 sandbox. Issued by Swiss Stablecoin AG and pegged 1:1 to the Swiss franc, with reserves held in cash at a regulated Swiss bank."
  - term: "FINMA Fintech Sandbox"
    def: "A regulatory safe harbour under Switzerland's Banking Act that allows innovative financial services to operate with relaxed licensing requirements, provided public deposits stay below CHF 1 million and no interest is paid on deposits. Whether the CHFD pilot relies on this exemption is not stated in any of the participants' published material."
  - term: "Deposit Token"
    def: "A blockchain-based representation of a bank deposit — the issuer is a licensed bank, and the token is a direct claim on that institution. Distinct from a stablecoin, where the issuer may be a non-bank entity holding reserves externally. UBS, PostFinance, and Sygnum completed a first interbank deposit token trial in September 2025."
  - term: "ERC-20"
    def: "The technical token standard on the Ethereum blockchain. The CHF stablecoin sandbox runs on Ethereum using the ERC-20 standard, allowing programmable transfer rules, smart contract integration, and interoperability with existing DeFi infrastructure."
  - term: "FinIA"
    def: "Financial Institutions Act (Finanzinstitutsgesetz). Switzerland's framework law for financial intermediaries. A Federal Council consultation closed in February 2026 proposes two new licence categories under FinIA: payment institutions (for stablecoin issuers) and crypto institutions (for custody)."
  - term: "Project Helvetia"
    def: "The Swiss National Bank's experiment with a wholesale CBDC (Central Bank Digital Currency) on the SIX Digital Exchange. Distinct from the private-sector CHF stablecoin sandbox — Helvetia is a central-bank liability; CHFD is a commercial-bank liability."
sources:
  - name: "UBS official press release — CHF stablecoin sandbox launch"
    url: "https://www.ubs.com/global/en/media/display-page-ndp/en-20260408-stablecoin.html"
    desc: "UBS Media — April 8, 2026 announcement"
  - name: "Sygnum Bank — joint CHF stablecoin sandbox announcement"
    url: "https://www.sygnum.com/news/ubs-postfinance-sygnum-raiffeisen-zurcher-kantonalbank-bcv-and-swiss-stablecoin-ag-launch-joint-chf-stablecoin-sandbox/"
    desc: "Sygnum Bank — April 8, 2026 co-announcement"
  - name: "Ledger Insights — Swiss banks create stablecoin sandbox"
    url: "https://www.ledgerinsights.com/ubs-postfinance-other-swiss-banks-create-stablecoin-sandbox/"
    desc: "Ledger Insights — technical and regulatory analysis, April 2026"
  - name: "Crypto Valley Journal — Swiss banking heavyweights launch CHF stablecoin sandbox"
    url: "https://cryptovalleyjournal.com/focus/blockchain/swiss-banking-heavyweights-launch-chf-stablecoin-sandbox/"
    desc: "Crypto Valley Journal — ecosystem context, April 2026"
  - name: "CoinDesk — Six top Swiss banks launch Swiss franc stablecoin sandbox"
    url: "https://www.coindesk.com/business/2026/04/08/six-top-swiss-banks-including-ubs-launch-swiss-franc-stablecoin-sandbox"
    desc: "CoinDesk — broader market context, April 8, 2026"
  - name: "The Block — Swiss franc stablecoin sandbox"
    url: "https://www.theblock.co/post/396650/swiss-franc-stablecoin-sandbox"
    desc: "The Block — April 2026"
  - name: "UBS — CHF stablecoin sandbox enters test phase, adds SIX and TWINT"
    url: "https://www.ubs.com/global/en/media/display-page-ndp/en-20260908-stablecoin-sandbox.html"
    desc: "UBS Media — September 8, 2026 update: nine participants, CHFD technically live since end of June"
---

On April 8, 2026, [UBS](https://www.ubs.com/global/en.html) put out a press release. Six institutions — UBS, [PostFinance](https://www.postfinance.ch/), [Sygnum](https://www.sygnum.com/), Raiffeisen, Zürcher Kantonalbank, and Banque Cantonale Vaudoise — alongside Swiss Stablecoin AG announced a joint sandbox to test a Swiss franc [stablecoin](https://en.wikipedia.org/wiki/Stablecoin) throughout 2026.

The coverage framed it as a breakthrough moment. Swiss banking heavyweights finally embracing on-chain money.

The structural read is more nuanced than that.

## What Is Actually Being Tested

The sandbox is testing CHFD — a CHF-denominated stablecoin issued by Swiss Stablecoin AG, pegged 1:1 to the Swiss franc, with reserves held in cash at a regulated Swiss bank.

The six banking partners are not issuing the stablecoin themselves. They are participating in a controlled live environment to generate operational experience with using CHFD in real payment flows — settlement, interbank transfers, [DeFi](https://en.wikipedia.org/wiki/Decentralized_finance)-adjacent applications that require programmable CHF liquidity.

The sandbox runs throughout 2026 and is open to additional participants — and additional participants have since joined. The safeguards the partners describe are a limited participant pool and transaction limits; they have not published the size of those limits, and no public figure for a volume cap exists.

{{< num-highlight value="9" label="Sandbox participants as of September 2026" note="The six founding banks plus Swiss Stablecoin AG, joined by SIX and TWINT on September 8, 2026." >}}

## The Regulatory Scaffolding: What Is Settled and What Is Not

This is where the mainstream coverage tends to go thin.

Switzerland does have a fintech sandbox in its Banking Act — it lets a firm take public deposits without a full banking licence provided the total stays under CHF 1 million and no interest is paid. That CHF 1 million ceiling and the CHF 100 million fintech-licence cap mentioned below are two different rungs of the same deposit-taking ladder — a licence-free exemption for small experiments, and a light licence for limited-scale deposit-taking — and neither of them is a regime for issuing a stablecoin, which is precisely the gap the FinIA amendment is meant to fill. Whether CHFD's issuance sits inside that sandbox exemption is not something any of the participants have said publicly, and I would not assume it. What they have said is that this is a closed environment with a limited participant pool and transaction limits: a controlled experiment, not a regulatory green light for scale.

The more consequential regulatory context is happening in parallel. In October 2025, the Federal Council opened a consultation on amending the Financial Institutions Act (FinIA). The consultation closed in February 2026 and proposes two new licence categories:

1. **Payment institutions** — for stablecoin issuers. Unlike the existing fintech licence, which caps deposits at CHF 100 million, the new payment institution category removes that ceiling entirely while requiring AML compliance, governance standards, and reserve segregation.
2. **Crypto institutions** — for custody providers handling digital assets at scale.

Legislative implementation is not expected before 2027. The sandbox running in 2026 is, in part, about generating evidence before that legislative window opens.

<div class="data-callout">
<p class="callout-label">Field observation — May 2026</p>
<p>The pilot is deliberately small. The point is not scale — it is structured learning under live conditions before the FinIA amendment creates the regulatory category that would allow a full commercial launch. The sandbox is building the evidence base, not the product.</p>
</div>

## Stablecoins vs. Deposit Tokens: A Distinction That Matters Here

The April 2026 announcement sits against a backdrop that is easy to conflate.

In September 2025 — seven months before the CHFD sandbox launch — UBS, PostFinance, and Sygnum completed what was described as the first legally binding interbank blockchain payment using deposit tokens. That earlier experiment used a different structure: deposit tokens are direct claims on a licensed bank's balance sheet, not claims on a separate reserve entity.

The CHFD stablecoin being tested now is issued by Swiss Stablecoin AG — a non-bank — with reserves held externally at a regulated bank. The token holder's claim is on Swiss Stablecoin AG, not on UBS or ZKB directly.

This is not a minor distinction for a practitioner audience.

{{< skip-box title="Why this matters if you hold or clear CHF on-chain" >}}
Deposit tokens (bank-issued, direct claim) and stablecoins (non-bank issuer, reserve-backed) carry different counterparty risk profiles, insolvency treatment under Swiss law, and AML identification requirements. The sandbox is specifically designed to stress-test the stablecoin structure — not to replace the September 2025 deposit token experiment, but to run alongside it.
{{< /skip-box >}}

## What the Founding Six-Bank Composition Signals

The participant roster is worth reading carefully.

Sygnum is the obvious entry — Switzerland's crypto-native bank, already offering a [CHF stablecoin](https://en.wikipedia.org/wiki/Stablecoin) limited to institutional clients since before this sandbox. Its presence means the sandbox has institutional DLT credibility from day one.

Zürcher Kantonalbank and Raiffeisen are cantonal and cooperative banking anchors, respectively. Their participation signals that this is not a pure fintech-adjacent experiment — it involves the backbone of Swiss retail banking infrastructure.

PostFinance's presence is consistent with its track record of early DLT engagement. It has been involved in blockchain payment experiments since before the September 2025 deposit token trial.

UBS is the weight that changes the narrative. As the largest Swiss bank and a significant global custodian, UBS joining a CHF stablecoin sandbox sends a different signal than if this were a consortium of smaller institutions. It shifts the question from "can this work technically?" to "when does this become infrastructure?"

<div class="data-callout">
<p class="callout-label">The read I am having</p>
<p>The six-bank composition was deliberate. You need Sygnum for DLT credibility, ZKB and Raiffeisen for domestic reach, PostFinance for interoperability with Swiss postal and retail networks, and UBS for institutional weight. This is not a startup experiment with a banking partner. It is the Swiss banking establishment stress-testing an infrastructure layer they expect to need.</p>
</div>

## CHF Crypto Rails: The Actual Gap Being Addressed

No CHF stablecoin has gained significant traction to date. That sentence from Ledger Insights' coverage cuts to the practical problem.

For anyone building on public blockchains and needing CHF liquidity — DeFi applications, tokenized securities settlement, blockchain-based payment infrastructure for Swiss business — the current state is a friction point. The options have been: use USDC or USDT (USD-denominated, FX exposure — and a transfer-fee model of its own, which I unpacked in [the field note on USDT transfer fees on TRON](/posts/tron-usdt-transfer-fees-energy-rental/)), use Sygnum's CHF stablecoin (institutional access only), or use the [Swiss National Bank](https://www.snb.ch/en)'s Project Helvetia wholesale CBDC (available only to financial market infrastructure participants).

There is no retail-accessible, broadly programmable CHF on-chain asset.

The CHFD sandbox is exploring whether a licensed-but-non-bank issuer model, operating within a clear FINMA framework, can close that gap. The [Ethereum](https://en.wikipedia.org/wiki/Ethereum) ERC-20 choice matters here — it means the token is designed for interoperability with existing DeFi infrastructure from day one, not siloed in a permissioned private chain.

{{< num-highlight value="3" label="Parallel CHF digital money tracks" note="Wholesale CBDC ([SNB](https://www.snb.ch/en)) / Deposit token (banks) / Stablecoin (Swiss Stablecoin AG)" >}}

<!-- IG-angle: Separating the two experiments the launch coverage merges — September 2025 was deposit tokens (bank-issued, direct claim, interbank settlement), April 2026 is CHFD (non-bank issuer, external reserves, programmable access); they carry different counterparty risk and insolvency treatment, address different layers, and are not competing, so reading them as one story misreads the regulatory signal entirely -->

## What Practitioners Are Getting Wrong

The coverage pattern I am seeing conflates two separate things: the proof of concept (completed September 2025, deposit tokens, interbank) and the sandbox (launched April 2026, stablecoin, CHFD, live use cases).

The deposit token experiment was about interbank settlement. The stablecoin sandbox is about broader programmable CHF access — including potentially non-bank participants who need CHF on-chain without needing a banking relationship with each of the six institutions.

Getting these two confused leads to misreading the regulatory signal. The deposit token route is simpler from a counterparty-risk perspective but requires bilateral banking relationships to access. The stablecoin route is more accessible structurally, but requires the FinIA amendment process to complete before it can operate at meaningful scale outside a sandbox's transaction limits.

They are not competing. They are addressing different layers of the same infrastructure problem.

## What This Means in Practice

For DeFi builders and tokenized asset platforms needing CHF settlement: the sandbox is a signal, not a solution yet. A closed pilot with a controlled participant list — one that has grown from six institutions to nine, but only by admitting named newcomers, not by opening the door — and capped transaction sizes does not make this a production rail. The legislative timeline (FinIA amendment expected 2027) is the gate for meaningful scale.

For institutional crypto participants in Switzerland: watch whether the sandbox participants publish operational findings before the FinIA consultation process concludes. The regulatory categories being designed for stablecoin issuers will be shaped partly by what the 2026 sandbox data shows.

For anyone monitoring the broader SNB-CBDC-versus-private-stablecoin question: Project Helvetia and CHFD are running on different tracks for different purposes. A wholesale CBDC addresses central bank settlement finality. A private CHF stablecoin addresses programmable liquidity for a wider participant set. Switzerland appears to be pursuing both — which is consistent with how [FINMA has positioned its regulatory philosophy](/posts/finma-crypto-guidance-01-2026/): not choosing between innovation and oversight, but trying to create frameworks that accommodate both.

## Worth Tracking

The 2026 sandbox is designed to generate data before the regulatory window opens. Two signals worth monitoring:

1. **Whether additional participants join** — this one has already moved. On September 8, 2026 SIX and TWINT joined, taking the roster to nine, and CHFD has been technically live in the sandbox since the end of June, with the test phase running to the end of the year. TWINT is the one that matters: it is the payment app almost every Swiss adult already has, and its presence turns an interbank experiment into a question about consumer rails.
2. **The FinIA consultation outcome** — if the Federal Council's payment institution and crypto institution categories are enacted roughly as proposed, Switzerland will have one of the most structured stablecoin licensing frameworks globally by 2027. If the consultation outcome weakens or delays those categories, the CHFD sandbox remains a proof-of-concept rather than a bridge to a production rail.

The conversation I have been tracking in Zug is less "will there be a CHF stablecoin" and more "which layer of the Swiss financial stack will it sit on, and who gets to issue it." The April 2026 announcement did not answer that question. It created a structured way to ask it.

---

*This is a field note, not financial advice. Participants in the stablecoin sandbox should consult qualified legal counsel on applicable FINMA requirements for their specific use case.*

*For context on the broader Swiss regulatory framework, see [FINMA's Guidance 01/2026 on crypto custody](/posts/finma-crypto-guidance-01-2026/) and [the [DLT Act](https://www.sif.admin.ch/en/dlt-blockchain-en)'s foundational infrastructure changes](/posts/dlt-act-switzerland-explained/).*
