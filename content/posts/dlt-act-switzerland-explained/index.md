---
title: "The DLT Act Explained Without a Law Degree: What Changed for Crypto in Switzerland"
date: 2021-02-01
lastmod: 2026-05-04
description: "Switzerland's DLT Act entered into force February 1, 2021 — amending nine federal laws at once. Here's what three innovations actually changed for crypto firms, custody providers, and anyone holding digital assets in Switzerland."
categories: ["regulation"]
tags: ["DLT act switzerland", "swiss fintech law", "distributed ledger technology switzerland", "ledger-based securities", "swiss crypto regulation 2021"]
draft: false
image: hero.jpg
readtime: 10
glossary:
  - term: "Registerwertrecht (Ledger-Based Security)"
    def: "A new category of uncertificated security introduced by Switzerland's DLT Act, where ownership rights are registered and transferred directly on a distributed ledger rather than via physical certificates or central securities depository bookings. The transfer is legally valid purely through the on-chain technical transfer, without requiring paper documents or written assignment."
  - term: "DLT Trading Facility"
    def: "A new licence category under the Financial Market Infrastructure Act (FMIA), created by the DLT Act in August 2021. Unlike conventional trading facilities (restricted to banks and supervised institutions), DLT Trading Facilities can admit private individuals directly — allowing broader market access, combined trading/custody/clearing operations, and lower intermediary costs."
  - term: "FinTech Licence (Banking License Light)"
    def: "A lighter regulatory authorisation introduced in 2019, which the DLT Act clarified applies to pooled crypto custody — meaning custodians holding client digital assets no longer need a full banking licence. Assets held under a FinTech Licence can be segregated off-balance-sheet in bankruptcy, protecting clients even if the custodian becomes insolvent."
  - term: "Segregation Right"
    def: "Under Switzerland's revised Debt Enforcement and Bankruptcy Act (DEBA), crypto assets held by a licenced custodian on behalf of clients can be legally separated from the custodian's own estate in insolvency. This means clients recover their assets rather than becoming unsecured creditors — a protection not previously guaranteed in Swiss law."
sources:
  - name: "Federal Council — Entry into force of DLT Act provisions"
    url: "https://www.admin.ch/gov/en/start/documentation/media-releases.msg-id-84035.html"
    desc: "admin.ch — official press release, August 2021 full entry into force"
  - name: "MME Legal — New Swiss DLT Regulations to enter into force starting February 2021"
    url: "https://www.mme.ch/en/magazine/articles/new-swiss-dlt-regulations-to-enter-into-force-starting-february-2021"
    desc: "mme.ch — legal analysis of the February and August 2021 provisions"
  - name: "Library of Congress — Switzerland: New Amending Law Adapts Several Acts to DLT"
    url: "https://www.loc.gov/item/global-legal-monitor/2021-03-03/switzerland-new-amending-law-adapts-several-acts-to-developments-in-distributed-ledger-technology/"
    desc: "loc.gov — Global Legal Monitor summary of the DLT Act amendments, March 2021"
  - name: "Loyens and Loeff — Swiss DLT Bill Enters Into Force"
    url: "https://www.loyensloeff.com/insights/news--events/news/entry-into-force-of-swiss-dlt-bill/"
    desc: "loyensloeff.com — legal commentary on entry into force"
  - name: "CMS Law — The New Swiss Blockchain/DLT Laws Finalised"
    url: "https://cms-lawnow.com/en/ealerts/2020/10/the-new-swiss-blockchain-dlt-laws-have-been-finalised-and-presumably-enter-into-force-early-2021"
    desc: "cms-lawnow.com — legal analysis of the finalised DLT Act text, October 2020"
  - name: "Global Legal Insights — Blockchain and Cryptocurrency Laws 2026: Switzerland"
    url: "https://www.globallegalinsights.com/practice-areas/blockchain-cryptocurrency-laws-and-regulations/switzerland/"
    desc: "globallegalinsights.com — Switzerland country chapter, 2026 edition"
---

> 📅 Field note from: February 2021 | Last updated: May 2026
> Originally written shortly after the DLT Act came into force; updated with five years of practical observations in May 2026.

February 1, 2021 is a date that most crypto holders outside Switzerland have never heard of. Inside Zug, the people who cared about it were a specific type: lawyers at firms specialising in digital assets, compliance officers at custody providers, and the handful of startups that had been waiting for this exact legislation before they could build certain products.

The rest of the Crypto Valley was more or less unmoved. The DLT Act is not the kind of law that generates press releases with dramatic headlines. It does not ban anything. It does not require anyone to register immediately. What it does is something more fundamental and, in the long run, more consequential: it amends nine existing Swiss federal laws at once, filling in gaps that had made certain blockchain-based transactions legally ambiguous or unnecessarily expensive.

I want to try to explain what actually changed — without the law degree, and with some context about why Switzerland chose to do this the way it did.

## Why Switzerland Needed a DLT Act at All

The short answer: Swiss law was written for paper.

Switzerland's Code of Obligations — one of the foundational pieces of Swiss private law — was designed around physical certificates and written signatures. A security was something you could hand to someone. A transfer of ownership required either a physical hand-off or a booking through a central securities depository.

In 2018, the Swiss Federal Council commissioned a report examining whether existing law was adequate for the blockchain era. The conclusion was nuanced. In many areas, Swiss law was already flexible enough to accommodate blockchain applications. But in three specific areas — the legal status of securities on a distributed ledger, the treatment of crypto assets in bankruptcy, and the licensing of DLT-based trading platforms — existing frameworks created real problems.

The DLT Act was the response: not a wholesale rewrite of Swiss financial law, but a targeted set of amendments that removed those specific friction points. The Swiss Parliament passed it unanimously in September 2020. The first provisions entered into force on February 1, 2021. The remaining provisions followed on August 1, 2021.

{{< num-highlight value="9" label="Swiss federal laws amended by the DLT Act" note="The DLT Act was not a standalone piece of legislation — it surgically modified nine existing federal laws simultaneously, including the Code of Obligations, the Financial Market Infrastructure Act, and the Debt Enforcement and Bankruptcy Act." >}}

## Innovation One: Ledger-Based Securities (Registerwertrecht)

This was the change that mattered most to people building tokenisation infrastructure.

Before the DLT Act, Swiss law recognised two main categories of securities: certificated securities (physical paper documents) and uncertificated securities (maintained by a central depository). If you wanted to create a security that lived on a blockchain and could be transferred peer-to-peer without going through a central intermediary, you had a legal problem — there was no category that clearly covered it.

The DLT Act introduced a third category: the *Registerwertrecht* (ledger-based security). Under the amended Code of Obligations, a security can now exist exclusively on a distributed ledger, provided the register meets certain technical requirements. Transfer of ownership happens through the on-chain technical transfer. No physical certificate. No written assignment. No central depository booking required.

The practical implications were significant. Before this, tokenising a security in Switzerland required creative legal workarounds — embedding the rights in a contract structure that approximated what the token was supposed to represent. After February 2021, you could issue a bond, a share, or a structured product directly as a ledger-based security, with the blockchain transfer having the same legal effect as any other recognised transfer method.

{{< skip-box title="What 'legally valid transfer' actually means here" >}}
The key word is "exclusively." Before the DLT Act, if you tried to transfer a blockchain-based security, a Swiss court might have asked which recognised legal transfer method you were using — and a pure on-chain transfer would not have clearly qualified. The Registerwertrecht removes that ambiguity: for securities created in this format, the on-chain transfer is the legally recognised method. You do not need paper to back it up.
{{< /skip-box >}}

This matters both for issuers (who can now launch tokenised securities with cleaner legal title) and for investors (whose ownership is legally unambiguous, not dependent on a contract interpretation). It is also why Switzerland moved ahead of most European jurisdictions on tokenisation infrastructure in 2021. France and Germany have since passed comparable legislation, but Switzerland was first.

## Innovation Two: Crypto Custody Without a Full Banking Licence

The second change was less dramatic but commercially significant for custody providers.

Under Swiss law before the DLT Act, if you wanted to hold client crypto assets in pooled custody — commingling client assets in a shared wallet rather than segregating each client in their own wallet — there was a genuine regulatory question about whether this required a full banking licence. Banking licences are expensive, time-consuming to obtain, and come with capital requirements calibrated for deposit-taking institutions, not custody providers.

The DLT Act clarified that pooled crypto custody falls under the FinTech Licence (sometimes called the "Banking License Light"), introduced separately in 2019. The FinTech Licence has substantially lower capital requirements and is faster to obtain than a full banking licence.

The second part of this change matters equally: the DLT Act also amended the Debt Enforcement and Bankruptcy Act (DEBA) to clarify that crypto assets held by a licensed custodian on behalf of clients can be segregated from the custodian's own estate in insolvency.

In plain terms: if your custody provider goes bankrupt, your crypto assets are yours. You are not an unsecured creditor waiting in line behind everyone else. The assets can be separated from the bankruptcy estate and returned to their rightful owners, provided the custodian met the licensing requirements.

{{< num-highlight value="2021" label="Year Swiss law explicitly guaranteed crypto segregation rights in bankruptcy" note="Before the DLT Act, the treatment of client crypto assets in a custodian's insolvency was governed by general civil law principles — the outcome was uncertain. The DLT Act amended the Debt Enforcement and Bankruptcy Act (DEBA) to create an explicit segregation right for crypto assets." >}}

This has ongoing practical significance for anyone holding crypto through a Swiss custodian — including through one of the FINMA-licensed crypto banks like AMINA (formerly SEBA) or Sygnum, which built their custody operations around the expectation that this legal framework would eventually exist. For more on those licences, see the [field note on FINMA's first crypto banking licences in 2019](/posts/finma-crypto-license-2019/).

## Innovation Three: The DLT Trading Facility Licence

The third major innovation came with the August 2021 provisions: a new licence category under the Financial Market Infrastructure Act (FMIA) called the DLT Trading Facility (*DLT-Handelssystem*).

To understand why this mattered, you need to understand a structural feature of conventional Swiss trading platforms. Regulated trading venues — stock exchanges, multilateral trading facilities — are generally only permitted to admit regulated institutions as participants: banks, securities firms, other supervised entities. Private individuals cannot directly participate in trading on these platforms. They access markets through intermediary brokers.

The DLT Trading Facility licence breaks this model. Holders can admit private individuals directly, without requiring a supervised intermediary in between. They can also combine functions that are typically separated: a single DLT Trading Facility can operate trading, clearing, settlement, and custody under one roof. Conventional trading infrastructure requires separate licenced entities for each of these functions.

The licence comes in two versions: a lean version for smaller operations with lower volumes, and a more comprehensive version for higher-volume platforms. This tiered approach was deliberate — Switzerland wanted to make the licence accessible to startups and innovative platforms, not just established financial institutions with the capital to obtain full stock exchange authorisation.

{{< skip-box title="Who this actually affects in Crypto Valley" >}}
In 2021, several Zug-based startups were waiting for the DLT Trading Facility licence framework to finalise before launching products that combined token issuance, trading, and custody in a single platform. The licence created a legal structure for these bundled services that did not exist before. By 2024, several DLT Trading Facility applications had been filed with FINMA — the regulatory pipeline was active, even if the public perception of DLT Act impact remained relatively low outside legal circles.
{{< /skip-box >}}

## What the DLT Act Is Not

A few things worth correcting that come up in conversations around this legislation:

**It is not a standalone law.** The DLT Act is an amending act — it modifies existing laws rather than creating a new code. This is intentional. Switzerland's approach was to make existing legal frameworks work for distributed ledger technology, rather than building a separate regulatory silo. The philosophy is technology-neutral: the law does not require DLT-based structures, it simply accommodates them alongside existing alternatives.

**It is not a blanket legalisation of crypto activity.** Crypto firms in Switzerland still need to comply with FINMA's existing licensing framework — banking licence, securities dealer licence, FinTech licence, or fund management authorisation, depending on what they do. The DLT Act did not create a crypto exception from Swiss financial regulation. It clarified how existing regulations apply to DLT-based structures.

**It is not the same as MiCA.** The EU's Markets in Crypto-Assets regulation is a comprehensive supervisory framework covering crypto-asset issuers and service providers across 27 member states. The DLT Act is narrower in scope and different in approach — it is a set of private law and financial market law amendments, not a new supervisory regime. Switzerland is not an EU member, so MiCA does not directly apply — but Swiss firms accessing EU markets need to account for both. [A field note on MiCA vs FINMA](/posts/mica-vs-finma-field-note/) covers that comparison in more detail.

## Five Years On: What the DLT Act Actually Did

Looking back from 2026, the DLT Act's impact has been real but measured. It did what it was designed to do — remove specific legal friction points — without generating the transformative market expansion that some proponents predicted.

Ledger-based securities exist and are being issued, but the tokenisation market has developed more slowly than 2021 optimism suggested. The legal framework is in place; the commercial demand has taken longer to materialise at scale.

The custody clarifications have had more immediate practical impact. Swiss crypto custodians have operated under the FinTech Licence framework with greater confidence since 2021, and the bankruptcy segregation provisions have provided a genuine client protection that differentiates Swiss-regulated custody from less regulated alternatives.

The DLT Trading Facility licence remains underutilised relative to its potential. The framework is available, but FINMA's thorough application process and the capital requirements mean that obtaining the licence takes time and resources. A handful of licences have been granted; the market has not flooded FINMA with applications.

None of this diminishes what the DLT Act was: a careful, technically sophisticated piece of legislation that positioned Switzerland's legal system for blockchain-based activity before most other jurisdictions had started drafting. The Federal Council's December 2018 report identified the gaps; the September 2020 parliamentary vote closed them. From inside Zug, that sequence — identify, draft, pass, implement — looked deliberate and competent. It still does.

## FAQ

**When did the DLT Act enter into force?**
In two stages: February 1, 2021 (covering the new Registerwertrecht ledger-based securities category and custody/bankruptcy clarifications) and August 1, 2021 (covering the DLT Trading Facility licence under FMIA).

**Do I need to do anything differently if I hold crypto in Switzerland?**
Not directly. The DLT Act creates legal infrastructure for issuers, custodians, and trading platforms. If you hold crypto through a licensed Swiss custodian, the main practical benefit is the clearer bankruptcy segregation right — your assets have an explicit legal claim to segregation if your custodian becomes insolvent.

**Is the DLT Act equivalent to MiCA?**
No. MiCA is a comprehensive supervisory framework for crypto-asset issuers and service providers across the EU. The DLT Act is a set of targeted amendments to existing Swiss private law and financial market law, designed to make those laws work for blockchain-based structures. Switzerland is not an EU member, so MiCA does not directly apply — but Swiss firms accessing EU markets need to account for both frameworks.

**What is a Registerwertrecht in practice?**
It is a security whose existence and transfer are governed exclusively by an electronic register that meets FINMA's technical requirements. Unlike a certificated security (physical paper) or an uncertificated security (central depository entry), a Registerwertrecht requires no physical or intermediated transfer — the on-chain technical transfer is the legally recognised method.

**Are DLT Trading Facilities operating in Switzerland?**
Yes, though the number remains limited. The DLT Trading Facility licence framework has been available since August 2021, and FINMA has received and processed applications. The process is thorough and the capital requirements are real, which has moderated the pace of new licences. The framework exists; implementation continues gradually.
