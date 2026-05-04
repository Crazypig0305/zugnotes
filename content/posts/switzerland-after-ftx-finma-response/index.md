---
title: "Switzerland After FTX: How FINMA Responded and What It Changed"
date: 2023-01-12
lastmod: 2026-05-04
description: "FTX collapsed in November 2022. FINMA's response — tighter AML thresholds, mandatory crypto reporting, and stricter enforcement of segregation rules — was incremental, not dramatic. A field note from Zug on what actually changed and why the Swiss banks came out ahead."
categories: ["regulation"]
tags: ["switzerland crypto regulation FTX response", "FINMA 2022 2023", "FTX collapse switzerland", "crypto asset segregation", "FINMA risk monitor", "swiss crypto banks"]
draft: false
image: hero.jpg
readtime: 11
glossary:
  - term: "Client asset segregation"
    def: "The legal requirement that a custodian keep client crypto-assets separate from its own proprietary holdings, and that those assets be protected from the custodian's creditors in bankruptcy. Switzerland's Debt Enforcement and Bankruptcy Act (DEBA) — amended in 2021 as part of the DLT Act — establishes explicit legal ground for this protection, provided the custodian meets specific operational conditions."
  - term: "FINMA Risk Monitor"
    def: "An annual publication by the Swiss Financial Market Supervisory Authority identifying the most significant risks to the Swiss financial sector. The 2022 edition, published November 10, 2022 — three days after FTX filed for bankruptcy — gave elevated prominence to crypto-related risks including asset segregation failures and contagion from unregulated platforms."
  - term: "AMLO-FINMA (Anti-Money Laundering Ordinance)"
    def: "FINMA's implementing ordinance for Switzerland's Anti-Money Laundering Act. A partially revised version entered into force on 1 January 2023, tightening virtual currency transaction thresholds: the CHF 1,000 AML reporting limit now applies to linked transactions across a 30-day window, not per transaction."
  - term: "Incremental enforcement"
    def: "FINMA's characteristic regulatory style: applying existing statutory frameworks to new activities through interpretive guidance and supervisory practice, rather than waiting for new legislation. The post-FTX response is a clear example — FINMA did not need new laws to act, it applied and reinforced what already existed."
  - term: "Travel Rule"
    def: "The FATF requirement that crypto service providers transmit originator and beneficiary information alongside fund transfers. Switzerland's implementation predates many other jurisdictions. Post-FTX, FINMA's AML guidance reinforced this rule's application to virtual asset transfers."
sources:
  - name: "FINMA Risk Monitor 2022"
    url: "https://www.finma.ch/en/~/media/finma/dokumente/dokumentencenter/myfinma/finma-publikationen/risikomonitor/20221110-finma-risikomonitor-2022.pdf"
    desc: "finma.ch — published November 10, 2022, three days after FTX bankruptcy filing"
  - name: "FINMA Risk Monitor 2023"
    url: "https://www.finma.ch/en/~/media/finma/dokumente/dokumentencenter/myfinma/finma-publikationen/risikomonitor/20231109-finma-risikomonitor-2023.pdf"
    desc: "finma.ch — published November 9, 2023"
  - name: "SWI swissinfo.ch — Can Switzerland benefit from the FTX crypto crash?"
    url: "https://www.swissinfo.ch/eng/business/can-switzerland-benefit-from-the-ftx-crypto-crash/48068900"
    desc: "swissinfo.ch — analysis of Swiss crypto sector positioning post-FTX, November 2022"
  - name: "SWI swissinfo.ch — FTX debacle: crypto industry rues latest setback"
    url: "https://www.swissinfo.ch/eng/ftx-debacle--crypto-industry-rues-latest-setback/48047470"
    desc: "swissinfo.ch — Swiss industry reaction to FTX collapse, November 2022"
  - name: "Finews — FTX Crash: Investors Moving Coins to Safe Haven Switzerland"
    url: "https://www.finews.com/news/english-news/54362-ftx-crash-investors-storing-coins-in-switzerland-safe-haven"
    desc: "finews.com — Sygnum CHF 270M+ inflows, November 2022"
  - name: "Sumsub — Switzerland Crypto Regulation Guide 2023"
    url: "https://sumsub.com/blog/switzerland-crypto-regulation-guide/"
    desc: "sumsub.com — overview of 2022-2023 regulatory developments including AMLO-FINMA revision"
  - name: "ICLG — Fintech Laws and Regulations Report 2025 Switzerland"
    url: "https://iclg.com/practice-areas/fintech-laws-and-regulations/switzerland"
    desc: "iclg.com — 2025 country report covering post-FTX regulatory evolution"
  - name: "PWC Switzerland — Swiss DLT law: New regulations"
    url: "https://www.pwc.ch/en/insights/regulation/swiss-dlt-new-regulations.html"
    desc: "pwc.ch — overview of DEBA crypto segregation amendments under the DLT Act"
---

> 📅 Field note from: January 2023 | Last updated: May 2026
> Originally written two months after the FTX collapse from inside Zug; updated with three years of regulatory follow-on observations in May 2026.

November 11, 2022 was a Friday. FTX had filed for Chapter 11 bankruptcy the day before. Sam Bankman-Fried had resigned. Eleven billion dollars in customer funds had vanished.

I remember checking Telegram channels that morning. There was the usual noise — speculation about contagion, lists of which platforms had exposure to FTX or Alameda Research, arguments about whether this was the end of crypto or just another cycle bottom. What struck me, working out of Zug, was a different question: what was FINMA going to do?

The Swiss regulator had been quiet during the collapse. No press releases. No emergency statements. That silence, in FINMA's case, is usually deliberate. It does things when it has something definitive to say.

Over the following three months, the response came — not as a dramatic regulatory overhaul, but in the characteristically Swiss way: incremental, grounded in existing law, and reinforcing frameworks that had already been built.

## What FINMA Already Had Before FTX

To understand FINMA's response, you have to understand what was already in place before November 2022.

Switzerland had been building its crypto regulatory architecture since at least 2018, when FINMA issued its ICO guidelines. The 2019 banking licences for SEBA and Sygnum established the principle that crypto-native firms could operate under full banking supervision. The DLT Act, in force from February 2021, amended the Debt Enforcement and Bankruptcy Act (DEBA) to create explicit legal ground for crypto asset segregation in bankruptcy — meaning that if a licensed Swiss custodian failed, client crypto assets were protected from the custodian's creditors, provided the technical segregation requirements were met.

That last piece — the DEBA amendment — is what made Switzerland's position structurally different from FTX's jurisdiction. FTX operated as a Bahamas-registered exchange. Client funds and proprietary trading funds were commingled. There was no legal segregation requirement that applied, and no regulator enforcing one.

In Switzerland, for firms operating under FINMA supervision, the principle was already the opposite. Client assets had to be segregated. Custodians had to be able to identify and return client assets in bankruptcy. The legal basis existed and was being enforced.

{{< num-highlight value="1 Aug 2021" label="Date Switzerland's DEBA crypto segregation provisions entered into force" note="Part of the broader DLT Act package. Established explicit legal basis for crypto asset protection in bankruptcy — the exact protection FTX's customers lacked when the exchange failed." >}}

## The Risk Monitor That Landed Three Days After the Bankruptcy

FINMA published its 2022 Risk Monitor on November 10, 2022. FTX had filed for bankruptcy on November 9.

The timing was coincidental — the Risk Monitor was already in production — but the document reads, in retrospect, as an almost precise diagnosis of what had just happened on a different continent.

The 2022 Risk Monitor gave elevated prominence to crypto-related risks, flagging the structural vulnerabilities of crypto intermediaries that operated without the segregation, transparency, and supervisory requirements that Swiss law imposed on its licensed institutions. It did not name FTX — the document was finalized before the collapse — but the risk categories it described mapped directly onto the failure modes that FTX exemplified: commingling of client and proprietary funds, inadequate governance, absence of effective supervisory oversight.

The document confirmed what FINMA's posture had suggested throughout 2022: the regulator viewed the unregulated segment of the crypto market as a systemic risk, not because Swiss-licensed entities were exposed to it, but because the credibility of the entire asset class depended on distinguishing regulated from unregulated platforms.

## What FINMA Actually Changed

The response to FTX was not a new law. FINMA does not make law — that is the Swiss Federal Council's domain. What FINMA did was apply and reinforce the tools it already had.

**Tightened AML thresholds for virtual currency transactions.** On 1 January 2023, a revised version of the Anti-Money Laundering Ordinance (AMLO-FINMA) entered into force. Among its provisions: the CHF 1,000 AML reporting threshold for virtual currency transactions was clarified to apply to linked transactions across a 30-day window, not per individual transaction. The revision was designed to close the structuring loophole — the practice of splitting large transactions into smaller amounts to avoid identity checks. FTX had not engaged in this specifically, but the post-FTX environment had heightened FINMA's sensitivity to AML risk in the crypto sector.

**Mandatory standardised crypto reporting.** In February 2023, FINMA introduced standardised reporting requirements for supervised entities engaged in crypto activities. The requirement meant that FINMA received consistent, comparable data across all its regulated crypto firms — not the patchwork of ad-hoc disclosures that characterised the unregulated segment. This was incremental, but operationally significant: it gave FINMA a surveillance capacity over its licensed firms that FTX's regulators conspicuously lacked.

**Continued supervisory focus on custody practices.** Throughout 2023, FINMA's supervisory activity — as reflected in enforcement actions and published guidance — maintained consistent pressure on the segregation and custody practices of regulated firms. The 2023 Risk Monitor reiterated the crypto risk categories from the previous year, with the additional data point that the FTX collapse had confirmed what the regulator had been warning about: unregulated platforms with commingled funds were a structural failure waiting to happen.

{{< skip-box title="What didn't change" >}}
Switzerland did not enact emergency crypto legislation in response to FTX. The Federal Council's position was that the existing legal framework — the DLT Act, the DEBA amendments, FINMA's supervisory authority — was sufficient for the licensed segment. The unregulated segment, by definition, was outside FINMA's direct reach. The post-FTX conversation in Switzerland focused on whether the perimeter of FINMA supervision should be expanded, not on whether the existing framework had failed. That perimeter question eventually led to the 2025 consultation on the crypto-institution license category — see [Two New FINMA License Categories Proposed](/posts/finma-crypto-institution-license-2026/).
{{< /skip-box >}}

## The Swiss Banks and Why They Came Out Ahead

The most visible immediate effect of FTX on the Swiss regulated crypto sector was not regulatory — it was commercial.

Sygnum reported CHF 270 million in net inflows in the weeks following the FTX collapse, with projections suggesting the total would reach at least CHF 400 million by year-end. The reason was not hard to understand. Institutional and professional investors who held crypto through unregulated platforms — many of them custodied at FTX or platforms with FTX exposure — had just watched customer funds evaporate in a bankruptcy that offered no client asset protection. Swiss-licensed banks, operating under FINMA supervision with mandatory segregation requirements, represented the opposite structure.

SEBA's situation was more complicated. Alameda Research — the trading firm at the heart of the FTX scandal — held a stake in SEBA, but the bank was clear that it amounted to less than 1% and carried no voting rights. The exposure was real but not material. SEBA did not see the same asset inflows as Sygnum, but it also did not face any credible risk to its licence or operations from the Alameda connection.

Both banks survived the FTX period without incident. Neither had their FINMA licences reviewed. Neither commingled client and proprietary assets — the specific failure mode that destroyed FTX — because FINMA supervision required otherwise.

{{< num-highlight value="CHF 270M+" label="Sygnum net inflows in weeks after FTX collapse" note="Reported by Finews, November 2022. Figure expected to reach CHF 400M+ by year-end. Reflected institutional investors moving assets from unregulated platforms to FINMA-supervised banks." >}}

## Zug in the Weeks After

The atmosphere in Zug's crypto offices in November and December 2022 was not what I would call panic. The community here had been through the 2018 Crypto Winter — a longer, slower attrition of companies and talent that had genuinely hollowed out parts of the ecosystem. FTX was different: sudden, centralized in one firm, and affecting primarily retail and institutional clients of an offshore exchange.

What I heard most in those weeks was a version of "this is why regulation matters." It was not triumphalism — nobody in Zug was glad that billions in customer funds had been lost. But there was a real sense that the Swiss framework had been designed, consciously, to prevent exactly this. The DEBA segregation rules. The mandatory FINMA oversight. The prohibition on commingling. These were not abstract compliance requirements. They were the specific protections that FTX lacked.

The firms at CV Labs and in the broader Zug ecosystem that were most affected were those with indirect FTX connections — portfolio companies that had raised capital from FTX Ventures, service providers that had FTX as a significant client, or projects with FTX-adjacent token economics. Some of those firms wound down over the following six months. Others restructured. The adjustment was real, but it was not a systemic collapse of the Zug ecosystem.

The ecosystem that emerged from late 2022 and into 2023 was, if anything, better positioned for institutional adoption. The argument that Switzerland's regulatory framework produced safer infrastructure had just been validated by the most dramatic possible counter-example.

## How Switzerland's Response Compared

The contrast with other jurisdictions is worth noting briefly, because it clarifies what was distinctive about FINMA's approach.

**The United States** responded to FTX with a wave of enforcement actions, legislative proposals, and regulatory turf wars between the SEC and CFTC. The regulatory framework was contested and politically charged. It produced litigation — against Coinbase, Binance, Kraken — but not the kind of clear, predictable framework that institutional participants needed.

**The European Union** had MiCA in the pipeline when FTX collapsed, and the event accelerated its final passage. MiCA — which came fully into force in December 2024 — represents a comprehensive statutory overhaul: new license categories, new conduct requirements, new segregation rules. It addressed the regulatory gap by legislating across it.

**Switzerland** did neither. It had no need to legislate — the gap had already been addressed. It had no need for enforcement drama — the firms that failed were outside its jurisdiction. What it did was reinforce and apply the existing framework, tighten the AML thresholds at the margin, and improve its data surveillance of the licensed sector.

The Swiss approach is sometimes characterized as complacency — moving too slowly, relying too heavily on existing frameworks. The post-FTX evidence suggests the opposite interpretation: the frameworks were adequate because they had been built deliberately, with asset segregation and supervisory oversight as non-negotiable baseline requirements.

MiCA, notably, converged toward the Swiss model on its core principles — mandatory segregation, direct regulatory supervision, bankruptcy protection for client assets. The architecture that FTX lacked was the architecture Switzerland already had. MiCA adopted it at EU scale. For a deeper look at how the two frameworks now compare, see [MiCA vs FINMA: A Field Note from Someone Who Watches Both](/posts/mica-vs-finma-field-note/).

## What It Actually Changed for Crypto Holders Here

For people holding crypto in Switzerland through FINMA-regulated custodians — meaning primarily AMINA (formerly SEBA) and Sygnum — FTX changed the KYC and due diligence environment more than anything else.

Both banks had already operated with source-of-funds documentation requirements, blockchain transaction history review, and detailed onboarding procedures. Post-FTX, those requirements became more intensive. The rationale was regulatory: FINMA's heightened sensitivity to AML risk in the crypto sector, and the wider context of scrutiny that followed the collapse, meant that regulated banks could not afford to be associated with assets whose provenance was unclear.

In practical terms, this meant longer onboarding timelines, more documentation requests for crypto assets that had passed through unregulated platforms, and a stricter application of the travel rule to incoming crypto transfers. For someone who had held crypto on FTX or similar platforms and wanted to move it to a Swiss bank account, the due diligence process in 2023 was more demanding than it would have been in 2021.

That tightening was not punitive. It was the regulated sector adjusting to a new risk environment in which the distinction between regulated and unregulated platforms had become, for the first time, commercially and reputationally significant. For a full picture of what opening a crypto account at a Swiss bank actually requires today, see the [field note on crypto-friendly bank accounts in Switzerland](/posts/crypto-friendly-bank-account-switzerland/).

## Three Years On

The FINMA Guidance 01/2026, published in January 2026, extended the post-FTX regulatory trajectory in a specific direction: detailed, prescriptive requirements for crypto custody — segregation mechanics, key management standards, operational continuity, third-party risk. It was the most detailed single document FINMA had published on custody since the 2019 banking licences.

The 2026 guidance is not a response to a new crisis. It is a consolidation of what FTX demonstrated was necessary: not just the principle of segregation, but the operational specificity that makes it real. For the full text of what that guidance requires, see [FINMA's Crypto Guidance 01/2026](/posts/finma-crypto-guidance-01-2026/).

The trajectory from 2019 banking licences to 2021 DLT Act to 2023 AML tightening to 2026 custody guidance is coherent. Each step applied or reinforced the principle that client assets must be identifiable, segregated, and protected. FTX was not a rupture in that trajectory. It was the event that made the trajectory visible.

---

*Related field notes: [When FINMA Gave Crypto Its First Banking Licenses: A 2019 Field Report](/posts/finma-crypto-license-2019/) — the foundational regulatory architecture that Switzerland built before FTX. [Two New FINMA License Categories Proposed](/posts/finma-crypto-institution-license-2026/) — how the post-FTX lessons are now being institutionalized in a new license framework.*
