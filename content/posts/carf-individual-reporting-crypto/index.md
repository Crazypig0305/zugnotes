---
title: "What CARF Actually Reports About You: A Plain Reading of the Framework for Individuals"
date: 2025-11-18
lastmod: 2026-09-23
description: "When CARF runs, your Swiss exchange or bank collects your name, TIN, tax residency, and aggregate transaction data. Here is a plain-language breakdown of exactly what gets reported, how individual reporting differs from entities, how CARF compares to FATCA and CRS, and why the Swiss postponement means none of it is happening in 2026."
categories: ["holding"]
tags: ["CARF", "individual reporting", "crypto asset reporting framework", "FATCA", "CRS", "swiss crypto regulation", "AEOI", "privacy", "tax transparency"]
draft: false
readtime: 12
glossary:
  - term: "CARF"
    def: "Crypto-Asset Reporting Framework. The OECD standard published in 2022 that requires Reporting Crypto-Asset Service Providers to collect individual and entity user data and report it to domestic tax authorities for automatic cross-border exchange. Switzerland has the legal basis on its statute book, but the crypto-asset provisions do not apply in 2026; implementation can begin on 1 January 2027 at the earliest."
  - term: "RCASP"
    def: "Reporting Crypto-Asset Service Provider. Any individual or entity that, as a business, provides services to effectuate crypto-asset transactions — including exchanges, custodians, brokers, and certain wallet providers. Under CARF, RCASPs are the direct reporting obligation holders, not individual asset holders."
  - term: "TIN"
    def: "Taxpayer Identification Number. The country-specific tax reference number (AHV in Switzerland, Social Security Number in the US, UTR in the UK, etc.) that links a person to their domestic tax authority. RCASPs must collect and verify TINs for all reportable account holders."
  - term: "CRS"
    def: "Common Reporting Standard. The OECD framework from 2014 for automatic exchange of traditional financial account information — bank accounts, securities, insurance. CARF is structurally modelled on CRS but designed specifically for crypto assets, covering transaction data rather than account balances."
  - term: "FATCA"
    def: "Foreign Account Tax Compliance Act. A US law requiring foreign financial institutions worldwide to identify and report on US-person account holders. FATCA is bilateral (US-driven) and focuses on account balances; CRS and CARF are multilateral and cover a wider jurisdictional scope."
  - term: "Reportable jurisdiction"
    def: "A country that participates in the automatic exchange agreement under CARF. If you are tax-resident in a reportable jurisdiction and hold crypto through a Swiss RCASP, your transaction data is reportable once the framework runs. The Swiss Federal Council proposed 74 partner jurisdictions, but Parliament has not approved them: the National Council committee suspended the bill in November 2025."
  - term: "Aggregate reporting"
    def: "The CARF principle that individual transactions are not reported one by one. Instead, gross proceeds from dispositions, fair market value of transfers, and total amounts received are aggregated by crypto-asset type and transaction category, then reported annually."
sources:
  - name: "OECD — Crypto-Asset Reporting Framework (official text)"
    url: "https://www.oecd.org/tax/exchange-of-tax-information/crypto-asset-reporting-framework-and-amendments-to-the-common-reporting-standard.htm"
    desc: "OECD — the primary CARF framework document including due diligence, reporting, and definitional rules"
  - name: "OECD FAQs on CARF (2024)"
    url: "https://www.oecd.org/content/dam/oecd/en/topics/policy-issues/tax-transparency-and-international-co-operation/faqs-crypto-asset-reporting-framework.pdf"
    desc: "OECD — frequently asked questions clarifying scope, individual vs entity distinctions, and self-custody treatment"
  - name: "CARF 2025 Monitoring and Implementation Update — OECD"
    url: "https://www.oecd.org/content/dam/oecd/en/networks/global-forum-tax-transparency/crypto-asset-reporting-framework-monitoring-implementation-update-2025.pdf"
    desc: "OECD — status of 76 jurisdictions' commitment as of December 2025, first exchange timelines"
  - name: "Alpadis — Switzerland Delays Exchange of Crypto-Asset Information to 2027"
    url: "https://www.alpadis.com/insights/switzerland-delays-exchange-of-crypto-asset-information-to-2027"
    desc: "alpadis.com — analysis of the Federal Council's 26 November 2025 decision to postpone CARF crypto-asset exchange to 2027, and what it means for holders"
  - name: "Blockpit — Tax Authorities Will Get Your Crypto Data: CARF, DAC8"
    url: "https://www.blockpit.io/tax-guides/tax-authorities-will-get-your-crypto-data"
    desc: "blockpit.io — RCASP obligations, transaction scope, first exchange timeline"
  - name: "Transworld Compliance — CARF vs FATCA vs CRS"
    url: "https://blog.transworldcompliance.com/en/carf-vs-fatca-vs-crs-how-crypto-asset-reporting-is-reshaping-global-tax-compliance"
    desc: "transworldcompliance.com — structural comparison of the three frameworks for financial institutions and individuals"
  - name: "Coincub — Your Exchange Will Tell On You: CARF and DAC8"
    url: "https://coincub.com/exchange-carf-dac8-end-crypto-secrecy/"
    desc: "coincub.com — plain-language breakdown of what exchanges report and what the data trail looks like"
---

> 📅 Field note from: November 2025 | Last updated: September 2026
> Originally written when [CARF](https://www.oecd.org/tax/exchange-of-tax-information/crypto-asset-reporting-framework-and-amendments-to-the-common-reporting-standard.htm) implementation timelines were being finalised across [OECD](https://www.oecd.org/) jurisdictions; corrected in September 2026 against the State Secretariat for International Finance FAQ, which is clearer than the contemporaneous coverage about how much of the framework Switzerland actually switched off.

Most coverage of CARF focuses on the timeline: when will data cross borders, which countries are included, what does the Swiss delay actually mean. Those are reasonable questions, and I have written about them separately.

What this field note covers is a different question: when CARF does operate, exactly what does it report about you?

That question matters more than the timeline. The timeline tells you when. The data tells you what your exchange already knows — and what tax authorities will eventually receive.

## What CARF Is Actually Designed to Collect

CARF was published by the OECD in 2022 and modelled structurally on the Common Reporting Standard that has governed traditional bank account reporting since 2014. The design logic is the same: identify the institution holding the data, require that institution to collect standardized information, and create a mechanism for sharing it automatically between tax authorities.

For traditional banking under CRS, the relevant institution is the bank and the relevant data is account balances. For CARF, the relevant institution is the Reporting Crypto-Asset Service Provider — your exchange, your custodian, your Swiss crypto bank — and the relevant data is transaction activity.

This is the first structural difference from what most people expect. CARF is not primarily about what you hold. It is about what you do.

<div class="data-callout">
<p class="callout-label">Field observation — November 2025</p>
<p>Several people I know in Zug assumed that CARF would work like a crypto version of CRS: report the balance, share the balance. The actual framework is more transactional. It is your trading history, your transfers, your proceeds — not a static snapshot of holdings — that ends up in the report. That distinction has real implications for how you think about compliance planning.</p>
</div>

## The Four Categories of Data Collected About You

Under the CARF framework, RCASPs must collect and retain four categories of information about individual account holders.

**Category 1: Identity data.** Your full legal name, date of birth, current residential address, and jurisdiction of tax residence. For individuals, this is the KYC data your exchange already collects — CARF formalizes which elements must be verified and retained.

**Category 2: Tax identification.** Your Taxpayer Identification Number (TIN) in each jurisdiction where you are tax-resident. For Swiss residents, that is your AHV number. If you are a foreign national with obligations in another jurisdiction, RCASPs must collect the TIN for that country too. Entities must also provide their global intermediary identification number or equivalent.

**Category 3: Transaction data — by type, not individually.** This is the category that surprises most people. CARF does not require your exchange to submit a line-by-line record of every trade you made. Instead, it requires aggregate reporting by transaction category and by crypto-asset type. The categories are:

- Exchanges of crypto for fiat currency (gross proceeds, by asset)
- Crypto-to-crypto swaps (fair market value of assets disposed of, by asset)
- Transfers to external wallets not associated with another RCASP (fair market value of assets transferred)
- Retail payments made in crypto (fair market value)

Each category is reported on an annual aggregate basis — total amount received, total fair market value disposed of, for each relevant asset type across the full reporting year.

**Category 4: Transfer destination indicators.** When you transfer crypto out of your exchange to a wallet not held by another RCASP, the service provider must indicate whether the destination is your own self-hosted wallet or a third-party wallet. This "transfer wallet" element exists specifically to flag movements to self-custody — not to penalize self-custody (which is legal and common in Switzerland), but to allow tax authorities to trace the data trail when assets move off-exchange.

{{< num-highlight value="4" label="Data categories" note="Identity / TIN / Transaction aggregates / Transfer destination indicators — all collected at RCASP level, reported annually" >}}

## What CARF Does Not Report

The framework has clear limits, and understanding them is as important as understanding the scope.

**[DeFi](https://en.wikipedia.org/wiki/Decentralized_finance) and decentralized protocols are out of scope.** If you interact directly with a decentralized exchange, a lending protocol, or a yield farm — without a Swiss-supervised intermediary involved — there is no RCASP to report on your behalf. CARF's reporting obligation falls on institutional service providers. Peer-to-peer transactions and direct smart contract interactions remain outside the framework as currently written — a category that includes the ordinary [wallet-to-wallet USDT transfer on TRON](/posts/tron-usdt-transfer-fees-energy-rental/), where no RCASP is involved at any step.

**Self-custodied assets held without service provider involvement are out of scope.** If you acquired crypto outside Switzerland, hold it in a hardware wallet, and have never transferred it through a Swiss exchange or custodian, no Swiss RCASP has collected information on those holdings. CARF reporting would not apply. This does not affect your Swiss [wealth tax](https://en.wikipedia.org/wiki/Wealth_tax) obligations, which exist independently.

**Non-tradable digital collectibles are excluded.** The framework covers assets that "can be used for payment or investment purposes." NFTs with no secondary market, limited-use gaming tokens, and similar assets fall outside the definition of relevant crypto-assets.

**Account balances are not the primary reporting element.** Unlike CRS, which reports ending balances, CARF focuses on transaction flows. A holder who buys [Bitcoin](https://en.wikipedia.org/wiki/Bitcoin) through a Swiss exchange and does nothing else for a year would have limited reportable activity — the acquisition event itself, and potentially a fair market value figure for any fiat-to-crypto exchange.

{{< skip-box title="What about non-reporting assets?" >}}
CBDC (central bank digital currencies) are explicitly excluded from CARF's scope. Stablecoins issued by regulated financial institutions may also be excluded depending on their classification. The framework includes a mechanism for jurisdictions to remove specific assets from scope if those assets are already covered by other reporting regimes. Check the OECD's current asset classification guidance if you hold instruments at the boundary of the definition.
{{< /skip-box >}}

## Individual vs. Entity: How CARF Treats Them Differently

This distinction is often collapsed in general coverage but matters practically for people with corporate holding structures.

For **individuals**, CARF reporting is triggered when an individual holds a reportable account — meaning they hold crypto-assets through an RCASP and are tax-resident in a reportable jurisdiction. The data collected is personal: name, address, TIN, and transaction aggregates on their behalf.

For **entities** (companies, foundations, trusts, partnerships), the reporting obligation is more layered. RCASPs must look through the entity to identify its controlling persons — the natural individuals who ultimately own or control the entity. This is the same beneficial ownership standard used under CRS. An entity that holds crypto through a Swiss exchange triggers reporting on both the entity itself and on its controlling persons, if those persons are tax-resident in reportable jurisdictions.

<!-- IG-data: Side-by-side breakdown of CARF's individual vs. entity reporting — the look-through obligation and passive-NFI rule that general CARF coverage collapses into a single "reporting" label, assembled here from the OECD framework text -->

{{< budget-table title="CARF: Individual vs. Entity Reporting — Key Differences" sub="How the framework treats personal and corporate crypto holdings differently" >}}
| | Individual Holder | Entity Holder |
|---|---|---|
| Primary reportable person | The individual directly | The entity + controlling persons |
| Identity data required | Name, address, DOB, tax residency | Entity name, registration, jurisdiction + controlling person details |
| TIN required | Individual TIN | Entity TIN + individual TIN of controlling persons |
| Transaction data | Aggregated by asset type and category | Same, at account level |
| Look-through obligation | N/A | Yes — RCASP must identify beneficial owners |
| Passive NFI rule | N/A | Entities with primarily passive income must identify controlling persons |
{{< /budget-table >}}

The practical implication: if you hold crypto through a Zug-registered foundation or GmbH rather than personally, CARF does not let the entity structure shield you from personal identification. The look-through rule exists precisely to prevent that.

## How CARF Compares to FATCA and CRS

Readers who have followed the older international tax transparency frameworks will recognize the structural DNA. CARF was designed to extend and complement — not replace — the existing system.

**CRS (Common Reporting Standard, 2014):** The multilateral framework that Switzerland and 100+ countries use to exchange traditional financial account information. CRS reports account balances, interest and dividend income, gross proceeds from sales of financial instruments. It covers bank accounts, securities accounts, and similar. CARF is the crypto extension of CRS — same multilateral architecture, same exchange mechanism, different asset class and reporting logic (transactions, not balances).

**FATCA (2010):** The US law that requires non-US financial institutions to identify and report on US-person account holders. Unlike CRS and CARF, FATCA is bilateral — it runs between the US and individual countries through intergovernmental agreements, rather than through a multilateral exchange network. Switzerland has a FATCA IGA in place. How crypto held at a foreign platform sits inside FATCA's "specified foreign financial asset" definition is a question the IRS has not answered with a dedicated rule, so US persons with Swiss crypto positions are working from general principles and their advisers' reading of them rather than from a bright line.

The interaction between the three frameworks is formally managed to avoid duplication: where a transaction is already reportable under CRS, CARF is designed to turn off overlapping reporting. The deduplication logic is built into the framework.

{{< budget-table title="CARF vs. CRS vs. FATCA — Structural Comparison" sub="How the three international reporting frameworks differ in scope and design" >}}
| | CARF | CRS | FATCA |
|---|---|---|---|
| Primary asset class | Crypto-assets | Bank accounts, securities | All foreign financial accounts |
| Architecture | Multilateral (OECD) | Multilateral (OECD) | Bilateral (US-driven) |
| What is reported | Transaction aggregates | Account balances + income | Account balances + income |
| Who reports | RCASPs | Financial institutions | Foreign financial institutions |
| Effective for Switzerland | Legal basis in place, provisions not applicable in 2026; 2027 at the earliest | Active, ongoing | Active (FATCA IGA since 2014) |
| DeFi coverage | No (no RCASP involved) | No | No |
{{< /budget-table >}}

The key insight from this comparison: CARF is not a rupture with the existing transparency system. It is a logical extension. Countries that have already adapted to CRS — which includes Switzerland, which has been a CRS participant since 2017 — already have the institutional infrastructure for CARF. The new piece is crypto-specific reporting at the RCASP level.

## The Swiss Postponement: What It Switches Off and What It Does Not

Switzerland has the legal basis for CARF on its statute book — Parliament approved the multilateral agreement in its final vote of 26 September 2025. But the Federal Council can only ratify that agreement once Parliament has approved the partner states, and in November 2025 the National Council's Economic Affairs and Taxation Committee suspended exactly that bill, by 18 votes to zero with four abstentions, pending clarity on how other states are proceeding and how the standard is read internationally. On 26 November 2025 the Federal Council confirmed the consequence.

The postponement is wider than "delayed exchange," which is how most of the coverage framed it.

Nothing at the RCASP level is running. The State Secretariat for International Finance states plainly that the due-diligence provisions relating to CARF "will not apply in 2026" and that "reporting providers of crypto services will not be required to exercise due diligence under Swiss law in 2026." There is no CARF registration duty this year either, and Switzerland will not receive crypto-asset data from abroad for the 2026 calendar year in return. Implementation can start on 1 January 2027 at the earliest, on a date Parliament sets.

The practical implication for privacy-conscious holders is not the one the January coverage suggested. There is no pool of CARF data sitting in Swiss institutional hands waiting for a border to open, because 2026 generated none. What your exchange holds is the KYC and transaction history it kept anyway, for its own AML and commercial purposes — the same material it held before CARF was drafted. Some providers have voluntarily aligned their self-certifications with the OECD format from January 2026, which SIF explicitly permits; that is a commercial decision, not a legal duty, and it varies by platform.

<div class="data-callout">
<p class="callout-label">Insider observation — Zug, 2026</p>
<p>The postponement was received with some relief in parts of the local crypto community, and the compliance people I know read it more narrowly than the relief suggests. Nothing is being collected under CARF now, which makes the window genuinely quiet — but it closes on a date Parliament has not announced, and the twelve-month self-certification clock for existing users only starts the day before activation. The time is for reviewing your holding structure and checking that your domestic filings are accurate, not for assuming the system went away. Those are different things, and conflating them is the planning error I keep seeing.</p>
</div>

## The Privacy and Compliance Trade-Off: A Plain Read

CARF is a transparency framework. Its stated purpose is to close the gap that allowed crypto-asset holders to hold and transact in ways that were invisible to tax authorities who relied on traditional financial reporting.

Whether that is a good thing depends on your starting position.

For holders with clean filing histories — Swiss residents who declare their crypto portfolios in the annual wealth tax return, who report [staking](https://en.wikipedia.org/wiki/Proof_of_stake) income as capital income, who have not used foreign exchanges specifically to avoid domestic reporting — CARF adds a reporting layer at the institutional level but does not change their legal position. They are already in compliance. CARF confirms what their filings already reflect.

For holders with material unreported crypto positions — in any jurisdiction, not just Switzerland — CARF represents a genuine shift in risk. The window is the period before Switzerland activates the framework with a first partner state, which cannot happen before 1 January 2027 and needs a parliamentary decision that has not been taken. Self-disclosure mechanisms exist in Switzerland (Nachdeklaration) and in most other jurisdictions. The mechanics and timelines vary by country; professional advice specific to your situation is the relevant first step, not general reading.

For holders in jurisdictions not on the reportable list — countries that are not CARF partner states — the distinction only starts to matter on the day Switzerland switches the framework on. From that point, a Swiss RCASP will collect and hold your data under its due-diligence duties like anyone else's, but there is no partner state for it to be exchanged with, so it stays in Switzerland. Before that day — which includes all of 2026 — nothing is being collected under CARF at all, for residents of partner and non-partner countries alike. This is a meaningful distinction for holders in the US (which has FATCA but is not a CARF exchange partner in the conventional multilateral sense), in China, and in Saudi Arabia.

{{< skip-box title="This is not advice on your specific situation" >}}
Nothing in this field note is legal or tax advice. The application of CARF to any specific holder depends on their tax residency, the type of assets held, which Swiss institutions they use, the laws of their home country, and the status of exchange agreements at the time data is transmitted. The landscape is evolving. A professional who knows your situation is the appropriate first call.
{{< /skip-box >}}

## What to Do With This Information

The purpose of understanding CARF's reporting scope is not to find gaps to exploit — most gaps in the current version will not survive the next update cycle. The purpose is to understand what information already exists at your exchange or bank, what will eventually reach foreign tax authorities, and whether your current filing practices reflect that accurately.

Three practical questions worth working through:

**Is your tax residency information current at every Swiss institution you use?** RCASPs are required to collect self-certifications from account holders confirming tax residency. If you have moved countries, changed your primary residence, or have dual obligations, your exchange's records may not reflect your current situation. CARF will create a formal self-certification obligation once Switzerland activates the framework, and for accounts that already exist on the day before activation the provider gets a twelve-month window to collect it — so the request will land in your inbox some time after the switch, not before it. Outdated residency information at the institutional level creates compliance risk regardless: your domestic filing duty does not wait for CARF.

**Are your foreign tax filings consistent with what your Swiss exchange holds?** The transaction data your exchange reports — aggregate exchanges, gross proceeds, transfer amounts — should be consistent with what you have declared to your domestic tax authority. Where there are gaps, the exchange between Switzerland and your home country (when it begins) will create an audit trail that did not exist before.

**Do you hold crypto through an entity structure?** If so, the look-through rules matter. The controlling person identification at your Swiss custodian should reflect accurate beneficial ownership. Entity structures do not create opacity under CARF — they create a second layer of reporting.

---

*Related field notes: [Switzerland's CARF Delay Explained](/posts/switzerland-carf-delay-2027/) covers the 2027 timing question in detail — what the delay actually means for the exchange schedule and why Switzerland paused. [The Swiss Crypto Tax Advantage](/posts/swiss-crypto-tax-advantage-guide/) covers the wealth tax and capital gains regime that operates independently of CARF — the tax obligations that exist whether or not any data is exchanged. [Declaring Crypto on Your Swiss Tax Return](/posts/declaring-crypto-swiss-tax-return/) walks through the annual declaration process that CARF data is ultimately designed to cross-reference.*
