# Manufacturing - Sector Cyber Resilience & Credit Intelligence: Research Record Q01-Q15 (merged)

**Document type:** research record (no slide production). **Version:** 1.1-R (research update of the 16 October 2026 baseline edition).
**Research date of this update:** 28 October 2026.
**Evidence base and cut-offs:**
- Q01-Q07: unchanged from the baseline edition (public sources; evidence cut-off 16 October 2026; reporting period 1 September 2025 to 16 October 2026; all sources accessed 16 October 2026).
- Q10-Q14: updated on 28 October 2026 by merging the baseline evidence with a user-supplied research input written in Portuguese (file `fc0b3cea-manufacturing.md`, SHA-256 `e296acccd6ca125d8d0736112f1b9c1a2b71060b8b4e9f18dd30a3aa4a76fdba`). The input states an evidence cut-off of "up to October 2026", recent evidence in the last 30 days, trends over 12 months to October 2026 and historical landmarks before 2020. Its content was translated into English (UK) for this record. Per user instruction, the user-supplied information was accepted and merged **without source validation**.
- Q15, Q08 and Q09: synthesised from all of the above. The four ratings follow the user-supplied rating matrix and are neither raised nor lowered here.

**Geography:** global baseline; primary focus on the European Union (EU), European Economic Area (EEA) and United Kingdom (UK) in the baseline edition; the user input states a global scope with distinct attention to the United States (US), the UK and the EU, and adds Brazilian and Japanese fraud and governance evidence.
**Audience:** Senior Credit Officers and First Line of Defence (1LoD) operational management; second-line reviewers.
**Boundary:** public external evidence plus a user-supplied research input. No internal bank, client or borrower data. Sector findings describe inherent exposure only; they are not a borrower creditworthiness assessment, a control audit or a compliance finding.
**Status:** Provisional (no approved rating rubric and no questionnaire item list supplied). NEEDS_REVIEW items are listed in section F; conflicts between the two evidence sets are listed in section E.

---

## 0. Reading guide

**Source identifiers.**
- `S-001` to `S-096`: public sources from the baseline edition, accessed on 16 October 2026 (full list in section G1). Tier 1 = official, legal, regulatory, statistics office, central bank, affected organisation; Tier 2 = independent research with disclosed method; Tier 3 = media, commentary and reproductions.
- `U-000`: the user-supplied input as a whole, for statements that cite no numbered source. `U-001` to `U-010`: the ten sources listed in the input (its section G, numbered 1 to 10). All were merged on 28 October 2026 without validation (section G2). `U-011` to `U-013` record items the input cites without a source-list entry (a Toshiba reference marked "[48]", an Industrial Cyber report on Masimo, and legal instruments named "without a direct source"). All U- material is labelled **User-supplied (not validated)** wherever it supports a finding. Tiers were not assigned to U- items because their sources were not reviewed; the input's own source-type and confidence labels are reproduced in G2.
- The input's "[48]" is the input's own numbering and is not the baseline source S-048 (a CircleID report on a German textile finisher).

**Evidence labels.** Observed (external fact from a named source); Benchmark (sector statistic with stated population); Proxy (indirect or derived measure); Judgement (analytical judgement); Assumption (scenario assumption); Action (management recommendation); User-supplied (not validated).

**Merge rules applied.**
1. Baseline evidence (S-) is retained in full and Q01-Q07 are unchanged in substance; they are only reorganised by research question.
2. User-supplied information (U-) is added where it addresses Q10 to Q15. Where the two sets describe the same event (Fairlife, July 2026), both are shown with their own references; where they describe different events with similar names (Bridgestone), they are kept as separate records.
3. Conflicts are shown, not resolved (section E). Where a cut-off matters, the baseline cut-off of 16 October 2026 governs statements drawn from the baseline and the input's "October 2026" governs statements drawn from the input.
4. Nothing in the user input was re-checked against its sources. Translation follows the input's meaning; where a Portuguese term would translate into a word excluded by the editorial rules, a neutral equivalent is used (for example "key supplier" or "essential infrastructure").

**Subsector map used in this record.** The user input lists subsectors by International Standard Industrial Classification (ISIC) and North American Industry Classification System (NAICS) code ranges; the baseline used nine evidence subsectors. They map as follows.

| User-input subsector (ISIC C15-C37; NAICS 31-33) | Baseline-edition subsector | Main evidence in this record |
|---|---|---|
| Automotive and transport equipment | Automotive OEMs and suppliers | JLR (S-), Honda 2021 (U-) |
| Aeronautics, aerospace and defence | Aerospace and defence | Egide, RTX (S-); Rolls-Royce, Airbus, Iris Kim (U-) |
| Industrial machinery and equipment | (within OT and refrigeration controller makers; machinery benchmarks) | Refrigeration controllers (S-); Black Kite subsector shares (S-) |
| Consumer and professional electronics, engineering | Electronics and EMS | Foxconn summary (S-); Toshiba (U-) |
| Chemicals and pharmaceuticals | Chemicals, metals and basic materials; medical devices and pharmaceutical components | West Pharmaceutical, Stryker, Boston Scientific (S-); Masimo (U-) |
| Food and beverages | Food and beverage | Asahi, Fairlife (S-); Fairlife (U-) |
| Textiles, clothing and footwear | Textiles and apparel | German finisher insolvency (S-, Tier 3) |
| Metals and metallurgy | Chemicals, metals and basic materials | Nucor (U-) |
| Wood and paper; plastics and rubber; furniture; household appliances; other consumer goods | Consumer goods; chemicals, metals and basic materials | Hasbro, Bridgestone Americas (S-); Bridgestone via LockBit (U-) |

[U-000] [U-013] The input defines the sector as industries transforming raw materials into finished goods, from vertically integrated production to outsourcing, original equipment manufacturer (OEM) and contract-manufacturing models and global supply chains (User-supplied definition, adopted for this record).

---

## A. Scope statement

**Sector definition.** [U-001] [U-000] Manufacturing corresponds to ISIC divisions C15-C37 (NAICS 31-33) and covers food and beverages, textiles and clothing, wood and paper, petrochemicals, chemicals and pharmaceuticals, metals, plastics and rubber, automotive and transport equipment, electronics and engineering, household appliances, furniture and other goods (User-supplied).

**Horizons.**
- Baseline edition (Q01-Q07): reporting period 1 September 2025 to 16 October 2026; 18-month rolling horizon for patterns and loss cases; older material labelled contextual or historical; last 30 days before the 16 October 2026 cut-off.
- User input (Q10-Q14): last 30 days to October 2026 "identified and flagged"; 12-month trends to October 2026; historical landmark cases before 2020. The input does not date any named event inside a last-30-days window; its most recent named event is Fairlife (July 2026) (gap, section F).
- Several user-supplied cases are historical (Rolls-Royce 1989-2013, Airbus 2001-2018, Iris Kim 2011-2018, Toshiba 2011-2015, Honda 2021) and are labelled as such.

**Jurisdictions.** EU, EEA and UK primary for cyber, operational resilience and regulation, with US, Japanese and other comparators (baseline); US, UK and EU primary for fraud, governance and fraud-related rules, with Brazil as an example (user input).

---

## B. Executive summary for Senior Credit Officers

**Provisional ratings (no approved rubric; as proposed in the user input):**
- **Fraud: Medium, confidence Medium** - high supplier-payment volumes and physical assets; large bribery cases at multinationals (Rolls-Royce, Airbus); no sector loss statistics [U-002, U-003].
- **Cyber / ICT: High, confidence Medium** - connected information technology (IT) and operational technology (OT), legacy systems, about 65% of manufacturers reporting ransomware in one survey [U-007]; baseline cases Jaguar Land Rover (JLR), Asahi, Stryker, Boston Scientific [S-001, S-016, S-021, S-027].
- **Operational resilience / third-party risk management (TPRM): Medium, confidence Medium (summary) or Low (matrix)** - production stops after cyber incidents (Fairlife, Nucor) but no consolidated duration or loss data [U-005, U-006]; conflict E-01.
- **Governance / operating model: Medium, confidence Low** - multinational structures, joint ventures and outsourcing; oversight gaps over intermediaries [U-002, U-003].

**Five key findings.**
1. [U-007] [S-041] Manufacturing is a high-value ransomware target because of intensive digitalisation and continuous operation.
2. [S-001] [S-039] Production loss runs mainly through enterprise IT, not direct OT manipulation.
3. [S-010] [S-009] One OEM stop transmits liquidity stress to thousands of suppliers.
4. [U-002] [U-003] [U-004] Bribery, procurement and payment-instruction fraud are documented at large manufacturers.
5. [S-057] [S-066] Product law, not entity regimes, reaches most manufacturers.

**Three borrower questions** [U-000] [S-010]: How are supplier bank-detail changes authorised and segregated? Is email authenticated and multi-factor authentication (MFA) enforced? Which key suppliers (enterprise resource planning (ERP), cloud) could stop production, and for how many weeks could liquidity absorb it?

---

## C. Four-dimension rating matrix (Q15)

| Dimension | Proposed rating | Status | Confidence | Principal drivers (as supplied) | Key evidence | Lender consequence (as supplied) | Fraud-Cyber overlap note | Main gaps |
|---|---|---|---|---|---|---|---|---|
| Fraud | Medium | Provisional | Medium | High volume of payment flows to global suppliers; density of globalised suppliers and subcontractors; target and incentive pressure [U-000] | Rolls-Royce (GBP 497m deferred prosecution agreement (DPA) in the matrix; GBP 671m total in the case table) [U-002]; Airbus (USD 4bn DPA in the matrix) [U-003]; Sophos study: one third of email fraud affects industry (proxy) [U-007] | Direct fraud losses of millions in documented cases plus investigation and remediation cost; liquidity effect of unplanned payments; reputation in mergers and acquisitions and credit; low proportional recovery [U-000] | Cyber-enabled fraud where computer accounts are compromised (business email compromise (BEC), phishing): penetration of IT is mapped to Cyber, the fraudulent payment operation to Fraud [U-000] | No sector-specific fraud statistics (proxies only: Association of Certified Fraud Examiners (ACFE), FBI Internet Crime Complaint Center (IC3)); few public reports of internal or third-party fraud in manufacturing beyond large cases; small internal frauds hard to quantify [U-000] |
| Cyber / ICT | High | Provisional | Medium | Intensive IT/OT integration (automation, supervisory control and data acquisition (SCADA), programmable logic controllers (PLCs)); global connectivity (supply chain, cloud ERP, application programming interfaces (APIs)); legacy heterogeneous systems; public exposure of key assets and executives (spear-phishing) [U-000] | Willis Towers Watson (WTW)/Sophos 2023: 65% of manufacturers hit by ransomware, 75% encryption, USD 1.67m average recovery cost [U-007]; LockBit against manufacturers incl. Bridgestone; Honda global stop 2021; Nucor and Fairlife production stops [U-005, U-006]; baseline: JLR, Asahi, Stryker, Boston Scientific, refrigeration controllers [S-001, S-016, S-021, S-027, S-035]; 25.2% of EU ransomware claims [S-041] | Revenue lost to stopped production (millions a day at large plants); urgent mitigation cost (forensics, ransom negotiation, penalties); potential physical asset damage via industrial control system attacks; short-term liquidity and long-term value effects [U-000] | Cyber-means fraud methods (BEC, phishing) cross dimensions: IT compromise is Cyber and diversion of funds is Fraud; social-engineering BEC is hybrid; evidence recorded in both [U-000] | Few comparative sector studies; available statistics (Sophos, Dragos) rest on limited reports; companies often do not disclose [U-000] |
| Operational resilience / TPRM | Medium | Provisional | Low (matrix) / Medium (summary) - conflict E-01 | Dependence on continuous processes (24/7 assembly lines); exposure to single suppliers (key raw materials, specialised tier-1); concentration in few global suppliers (semiconductors, software-as-a-service (SaaS) ERP); essential infrastructure (energy, logistics) [U-000] | Fairlife: production halted at US plants after a cyberattack [U-005]; Nucor: temporary steel-plant stop after an IT intrusion [U-006]; input flags a global logistics-software disruption "(NASA/Boeing hack? limited)" as unconfirmed; baseline: JLR cascade to over 5,000 UK organisations (modelled) [S-010]; supplier prepayment and GBP 1.5bn state-guaranteed loan [S-003, S-009] | Direct cost of idle lines, delivery delays and lost revenue; cascade effects on customers' balance sheets; excess or short inventory (working capital); extra capital expenditure on resilience (duplication, backup) [U-000] | Third-party weaknesses that enable fraud (fraudulent onboarding) touch Fraud; evidence indicates third-party disruptions (cyber or failure) are cyber-operational rather than direct fraud [U-000] | Scarce quantitative data on TPRM-induced disruption (point reports, mainly cyber); no concentration statistics (market share per supplier) [U-000]; baseline: market shares of ERP, manufacturing execution system (MES) and OT vendors not retrieved (Q01 dependency analysis) |
| Governance / operating model | Medium | Provisional | Low | Complex corporate structures (parent plus subsidiaries in several countries, joint ventures); variable internal-control policies; decentralised payment authorisation; evolving compliance (anti-corruption, Sarbanes-Oxley Act (SOX) or equivalent); audit and whistleblowing practices not always robust in subsidiaries [U-000] | Rolls-Royce and Airbus investigations revealed supervision failures over chains of intermediary agents [U-002, U-003]; Toshiba fraudulent accounting (2015) [U-011]; UK Bribery Act failure-to-prevent offence applied to Airbus [U-003]; baseline: NIS2 management-body duties and UK Ministry of Defence (MOD) supplier flow-down [S-049, S-081] | Regulatory fines (large DPAs affect earnings before interest, taxes, depreciation and amortisation (EBITDA)); reputational risk from internal fraud scandals affecting access to credit; fragmented decision-making slowing incident response [U-000] | Some documented failures (executive involvement, anonymity of reports) cross into typical corporate fraud; the evidence mainly shows omissions (failure-to-prevent liability) [U-000] | Limited manufacturing-specific evidence of governance gaps; public records concern individual cases; difficult to isolate a governance cause without internal analysis [U-000] |

**Rating rules applied.** No approved rubric was supplied, so all ratings are Provisional. Ratings are reproduced exactly as proposed in the user input; this record does not create, raise or lower a rating. Confidence reflects evidence quality and is stated separately. Complexity is not treated as proof of weak governance. The baseline migrated edition (1.0-M) had rated Fraud and Governance as Not assessable and Cyber / ICT and Operational resilience / TPRM as High with Medium confidence; the change of Operational resilience / TPRM from High to Medium follows the user input and is recorded as conflict E-02.

---

# Part A - Core sector intelligence (Q01-Q07, unchanged from the baseline edition)

## Q01 - Sector operating model and key dependencies

**Sector footprint (Benchmark).**
- [S-043] EU manufacturing had about 2.2 million enterprises, 30.2 million persons employed (18.5% of business-economy employment) and about EUR 2.5 trillion of value added (23.1%) in 2023, with machinery, food and motor vehicles the largest divisions by value added.
- [S-044] Across the EU business economy, micro and small firms are 99% of enterprises while large firms produce 49% of value added; in manufacturing supply chains this means many small suppliers depend on few large customers (Judgement).
- [S-009] In the UK, JLR alone employs 34,000 people and supports a supply chain of about 120,000.
- [U-000] The user input adds the ISIC C15-C37 definition and a business-model range from vertically integrated production to outsourcing and contract manufacturing (User-supplied; see section A).

**Essential processes.** Production scheduling and release (ERP, manufacturing execution system (MES)); order-to-cash and logistics release; quality release; supplier call-offs and payment; plant control (OT); identity and endpoint administration; product support for fielded connected equipment.

**Subsector coverage in the baseline evidence.**

| Subsector | In-period public evidence | Evidence strength | Main gap |
|---|---|---|---|
| Automotive OEMs and suppliers | JLR shutdown and supplier scheme (UK, Slovakia) | Company filings, statistics office, central bank, Cyber Monitoring Centre (CMC) model | Supplier-level losses and failures |
| Medical devices and pharmaceutical components | Stryker, Boston Scientific, West Pharmaceutical | SEC material-incident filings | Quantified cost; EU plant effects |
| Food and beverage | Asahi (Japan); Fairlife (US, media only) | Company disclosures; Tier 3 | No EU or UK case with Tier 1 outcome |
| OT and refrigeration controller makers | French controller compromise; US PLC advisory | National computer emergency response team (CERT) alert; US advisory title | Units affected; vendor liability |
| Aerospace and defence | Egide (France); RTX passenger-processing product | Exchange release; SEC filing | Duration and cost |
| Consumer goods | Hasbro (US) | SEC filing | Manufacturing effect not stated |
| Electronics and electronics manufacturing services (EMS) | Foxconn US sites (vendor summary) | Tier 2 | Primary disclosure not retrieved |
| Chemicals, metals and basic materials | Leak-site benchmarks only | Tier 2 | No named in-period case with Tier 1 outcome |
| Textiles and apparel | German finisher insolvency (media) | Tier 3 | Official causal confirmation |

[S-039] [S-040] [S-041] Claim-based datasets agree that manufacturing is the most frequently named ransomware victim sector and that European victims rose in 2026 (Benchmark). They count visible claims and disclosures, not attack rates, and are not combined because their windows and methods differ.

**Dependency map (documented dependencies only).**

| Dependency | Evidence | Concentration pathway | Who is exposed |
|---|---|---|---|
| Enterprise IT that releases production (ERP, MES, identity) | [S-001] [S-016] [S-027] JLR, Asahi, Boston Scientific | Plant stops when enterprise systems stop | Manufacturers, suppliers, dealers |
| Endpoint and identity administration planes | [S-023] [S-025] Media reports on Stryker; US Cybersecurity and Infrastructure Security Agency (CISA) alert (organisation unnamed) | One administrative tool reaches every device | Multi-site manufacturers |
| OT vendors' installed base | [S-035] [S-089] French controller case; US PLC advisory | One product family exposed across many sites | Customers of equipment makers; the makers themselves |
| Integrators, engineering firms and managed IT providers | [S-039] [S-034] Dragos ICS ecosystem counts; Egide | One provider's access reaches several plants | Manufacturers using shared service providers |
| Just-in-time supplier tiers | [S-010] JLR and CMC model | Customer stop transmits to thousands of small suppliers | Tier-1 to tier-3 suppliers and their lenders |
| Manufacturer-supplied software used by customers | [S-037] RTX passenger-processing product | Product incident becomes customers' outage | Customers in other sectors |

[S-001] [S-016] [S-027] [S-021] [S-025] [S-035] [S-089] [S-039] [S-034] [S-010] [S-037] Dependencies are named only where a source supports them; market shares of ERP, MES and OT vendors in manufacturing were not retrieved and no platform is described as dominant (Observed and Judgement). [U-000] The user input adds dependence on single suppliers of key raw materials and specialised tier-1 parts, concentration in semiconductors and SaaS ERP, and dependence on energy and logistics infrastructure (User-supplied; Q12).

**Disclosure asymmetry (Judgement).** [S-021] [S-027] [S-030] US securities rules generate most quantified cases; EU and UK private manufacturers and small suppliers rarely disclose. [U-000] The user input makes the same point: large firms disclose incidents, while small and medium-sized enterprises, numerous in manufacturing, may not, which understates real frequency (User-supplied).

**Financial-system relevance (conditional channels).** (a) Corporate working capital and covenants, [S-006] as JLR's GBP 1.5 billion quarterly cash outflow, which had cyber and non-cyber causes, shows (Observed); (b) supplier finance and receivables, [S-003] as JLR used a banking partner to prepay suppliers (Observed); (c) state-backed lending, [S-009] as with the UK Export Finance (UKEF) guarantee (Observed); (d) insurance gaps, [S-010] as the CMC notes cyber cover typically excludes losses caused by disruption at a key customer (Benchmark); and (e) product liability and market reaction for manufacturers of connected products (Judgement). These are conditional transmission channels and not statements about any institution's exposure, losses, capital or Risk Appetite Framework (RAF) position.

## Q02 - Historical and recent cyber incidents, including case studies

**Selection criteria.** Named incidents qualify only if (1) the event or its disclosed outcome falls within 1 September 2025 to 16 October 2026; (2) its existence and main consequence are supported by a Tier 1 source; (3) the affected organisation or its products belong to a Manufacturing subsector in scope; and (4) the case adds a distinct operational or financial lesson. Leak-site and hacktivist claims are not accepted as incidents.

**Top five named incidents in the period.**

| # | Incident | Subsector | Place and date | Operational vulnerability | Consequence | Evidence strength | Sector relevance |
|---|---|---|---|---|---|---|---|
| 1 | Jaguar Land Rover shutdown | Automotive OEM | UK and Slovakia; from early September 2025 | Enterprise systems shut down proactively; production dependent on IT | About five weeks of halted production; GBP 260 million cyber costs over two quarters; officially recorded motor-vehicle output fall; state-guaranteed loan | Company filings, Office for National Statistics (ONS), Bank of England, CMC | Highest: supplier cascade and output effect |
| 2 | Asahi Group ransomware | Beverages and food | Japan; from 29 September 2025 | Data-centre network entered via network equipment at a group site | Shipments halted; about JPY 40 billion 2025 impact; results delayed five months; up to about 1.9 million records potentially exposed | Company disclosures | High: process manufacturer recovery tail |
| 3 | Stryker global IT disruption | Medical devices | Global (US-based); from 11 March 2026 | Global IT disruption; media report a device wipe through an endpoint-management platform (not confirmed by the company) | Material Q1 effect; manufacturing network and ordering restored by 9 April 2026 | SEC filings; media-reported claim unconfirmed | High: material effect on a global manufacturing network |
| 4 | Boston Scientific outage | Medical devices | Global; from 25 August 2026 | Unauthorised activity in IT systems; network outage | Manufacturing, ordering and shipping disrupted; guidance unlikely to be met | SEC material-incident filing | High: material guidance effect |
| 5 | Refrigeration controller compromise | OT and refrigeration equipment makers | France (other EU states reported); 11-13 October 2026 | Internet-reachable, partly end-of-life controllers | Numerous compromises; hundreds of stores affected per relayed official statements | National CERT alert; Tier 3 scale | High: product fleet becomes exposure |

**Incident notes.**
- **Jaguar Land Rover (September 2025).** [S-001] On 2 September 2025 JLR said it had proactively shut down its systems and that retail and production were disrupted (Observed). [S-003] [S-005] It restarted on a phased basis from 8 October 2025 and production returned to normal by mid-November (Observed). Detailed case study below.
- **Asahi Group (September 2025).** [S-016] Asahi found encrypted files at about 07:00 on 29 September 2025, disconnected its network and isolated the data centre by 11:00; the intruder had entered through network equipment at a group site and deployed ransomware to servers and some PCs; impact was limited to systems managed in Japan (Observed). [S-017] Sales of its Japanese brewery, soft-drink and food units in October-December 2025 were roughly 80%, 70% and 90% of the prior year, and the FY2025 results announcement was postponed (Observed). [S-019] [S-018] The company estimated a 2025 impact of about JPY 40 billion and reported Japanese brewery sales at 84% of the prior year in January-March 2026 (Observed). [S-020] Results for 2025 were published on 8 July 2026 (Observed, Tier 3 corroboration of company data).
- **Stryker (March 2026).** [S-021] Stryker determined that an incident identified on 11 March 2026 had a material impact on operations and Q1 2026 results, and reported its global manufacturing network and its ordering and distribution systems restored by 9 April 2026 (Observed). [S-023] [S-024] Trade media describe a wipe of devices through a legitimate endpoint-management platform, claimed by a group they describe as Iran-linked; the claim and mechanism are not confirmed by the company (Observed; claim unconfirmed). [S-022] Stryker maintained full-year guidance (Observed).
- **Boston Scientific (August-September 2026).** [S-026] Boston Scientific identified unauthorised activity in IT systems on 25 August 2026 that disrupted order processing and shipping (Observed). [S-027] On 8 September 2026 it reported that manufacturing had also been disrupted and had resumed at most facilities, that a material impact on Q3 and full-year results was likely and that it was unlikely to meet guidance (Observed). [S-029] Reuters reported a 2.3% share-price fall on the day of the guidance statement (Observed, Tier 3). [S-028] Trade media report that new remote-monitoring activations for some implanted cardiac devices were affected (Observed, Tier 3).
- **Refrigeration controller compromise (October 2026).** [S-035] CERT-FR, the French national computer emergency response team, reported numerous compromises of remote controllers for refrigeration installations (Danfoss AK-SC and AK-SM series, Copeland and Dixell xweb) on 12-13 October 2026, warned that campaigns were probably still under way and advised removing internet exposure and resetting compromised units (Observed). [S-036] Media relaying the French finance minister put the number of affected supermarkets at about 700; vendors described affected units as outdated or end-of-life; no group had claimed responsibility (Observed, Tier 3 relay). Interpretation: this is a direct OT compromise, but of manufacturers' products in customer premises; the product-security, liability and reporting consequences fall on the manufacturers (Judgement).

**Considered but not selected (baseline).**
- [S-030] West Pharmaceutical Services (May 2026): data exfiltrated, systems encrypted and global operations disrupted, with manufacturing restarting progressively (Observed). Pathway duplicates incident 4; used as pattern evidence and in Scenario 3.
- [S-034] Egide (October 2026): a French listed supplier of hermetic packages for sensitive electronic components was hit through an external IT provider, leading to a precautionary partial interruption at Bollène (Observed). No outcome yet disclosed.
- [S-031] [S-032] Hasbro (March 2026): systems taken offline with order, shipping and invoicing delays and guidance reiterated; manufacturing is not mentioned (Observed).
- [S-037] RTX (September 2025): ransomware on systems supporting its passenger-processing product disrupted European airports; RTX reported no material impact (Observed). Cross-sector analogue in Scenario 1.
- [S-033] [S-038] [S-048] Fairlife (US dairy, July 2026), Bridgestone Americas (September 2025) and a German textile finisher's insolvency (2026) are recorded only from Tier 3 sources in the baseline and are excluded as named incidents.

**User-input incidents (merged for Q10-Q14; Q02 selection unchanged).** [U-005] The user input records Fairlife (Coca-Cola) halting US production after a cyberattack, citing Reuters of 16 July 2026 as a first-hand source; [U-006] Nucor pausing steel operations after an IT network intrusion disclosed in a Form 8-K in May 2025; [U-012] Masimo disclosing an unauthorised intrusion in April 2025; and [U-000] historical events (LockBit against manufacturers including Bridgestone in 2021-2023, a global Honda stop in 2021). These are User-supplied (not validated). They do not change the baseline top five: Nucor and Masimo fall before the baseline reporting period, and Fairlife's baseline source is Tier 3 while its user-supplied source was not reviewed (conflicts E-04 to E-06; unified event register, section D).

**Shortfall statement.** [S-040] [S-039] Five incidents meet the standard, but only two (JLR and the French controller case) are in the EU or UK. This reflects disclosure asymmetry, not evidence that EU manufacturers are less affected; claim-based data show European manufacturing victims rising in 2026 (Benchmark).

**Last 30 days before the 16 October 2026 cut-off.** [S-034] Egide site interruption (6-9 October 2026); [S-035] refrigeration-controller compromises (12-13 October 2026).

**Timeline of in-period developments.**
- [S-001] [S-011] [S-012] [S-013] September to November 2025: ONS recorded a 28.6% fall in UK motor-vehicle output in September 2025 and relayed the trade body's attribution to the JLR stoppage; the Bank of England cited the disruption as one reason Q3 growth was weaker than expected.
- [S-016] [S-019] September 2025 to July 2026: Asahi's ransomware halted Japanese shipments, delayed its results by five months and cost about JPY 40 billion in 2025.
- [S-021] [S-030] [S-027] March to September 2026: three US-listed medical-technology and pharmaceutical-component manufacturers filed material-incident reports after production and shipping disruption.
- [S-039] [S-040] Q2 2026: industrial ransomware rose 12% quarter on quarter, with manufacturing at about 65% and European victims rising (Benchmark).
- [S-046] [S-051] December 2025 to July 2026: Germany's NIS2 law came into force; four Member States were referred to the Court of Justice for non-transposition.
- [S-057] 11 September 2026: manufacturers' product vulnerability and incident reporting obligations began.
- [S-035] [S-034] 6-13 October 2026: an aerospace and defence component supplier in France was disrupted through an IT provider, and refrigeration controllers in French supermarkets were compromised.

### Detailed case study 1 (baseline): Jaguar Land Rover cyber incident

**Why this case.**

| Candidate | Recency | Sector relevance | Causal clarity | Disclosed outcome | Evidence quality | Decision |
|---|---|---|---|---|---|---|
| Jaguar Land Rover | September 2025 to May 2026 | Highest (automotive OEM, supplier cascade) | High | Costs, volumes, cash, macro, government support | Company, statistics office, central bank, CMC | Selected |
| Asahi Group | September 2025 to July 2026 | High (process manufacturing) | High | Costs, sales, data | Company disclosures | Top 5 incident |
| Stryker | March to April 2026 | High (medical devices) | Medium | Materiality only | SEC filings | Top 5 incident; Scenario 2 |
| Boston Scientific | August to October 2026 | High (medical devices) | Medium | Guidance effect | SEC filings | Top 5 incident; results pending |
| West Pharmaceutical | May 2026 | Medium-high | Medium | Restart only | SEC filing | Pattern and scenario evidence |
| Refrigeration controllers | October 2026 | High (OT products) | Low (days old) | None official | CERT-FR | Monitor for next edition |

[S-004] [S-009] [S-011] [S-010] Judgement: JLR is the only in-period case combining company filings over four quarters, a statistics-office and central-bank record of output effects, a government loan guarantee, a supplier-financing response and an independent loss model, and it is in the UK.

**Timeline.**

| Date | Event (Observed) |
|---|---|
| Late August to 2 September 2025 | Incident begins; JLR proactively shuts down systems; production and retail disrupted |
| 4 September 2025 | Unconfirmed claim of responsibility reported; National Crime Agency (NCA) engaged |
| 9 September 2025 | House of Commons Business and Trade Committee writes to JLR on supplier impact and taxpayer support |
| 22 September 2025 | GBP 2 billion bridge facility signed |
| 28 September 2025 | Government announces guarantee to unlock up to GBP 1.5 billion of bank lending |
| 7 October 2025 | Restart sequence and supplier financing scheme announced; Q2 wholesales down 24.2% |
| 8 October 2025 | Phased restart begins with engine and battery assembly |
| 22 October 2025 | CMC classes event as Category 3 and models GBP 1.9 billion UK loss |
| 24 October 2025 | Society of Motor Manufacturers and Traders (SMMT) reports September car output down 27.1% |
| October 2025 | GBP 1.5 billion UKEF-guaranteed loan secured |
| November 2025 | Bank of England cites the disruption in weaker Q3 growth |
| 13 November 2025 | ONS records 28.6% fall in motor-vehicle output for September |
| 14 November 2025 | Q2 results: GBP 196 million cyber-related costs |
| Mid-November 2025 | Production back to normal levels |
| 5 January 2026 | Q3 wholesales down 43.3% |
| 5 February 2026 | Q3 results: GBP 64 million further cyber-related costs |
| 14 May 2026 | Full-year results: UKEF-guaranteed loan undrawn; production recovered in Q4 |

[S-010] [S-001] [S-015] [S-014] [S-004] [S-009] [S-003] [S-002] [S-012] [S-013] [S-011] [S-005] [S-006] [S-007] The timeline is compiled from company statements and results, the government release, the parliamentary letter, the CMC statement, ONS, SMMT and Bank of England publications; the claim of responsibility is recorded only as a media-reported claim (Observed).

**Mechanism.** [S-001] JLR's first statement says it took immediate action by proactively shutting down its systems (Observed). [S-010] The CMC notes that fewer technical details have emerged than usual, that the extent of OT impact is unclear and that the early-October restart may indicate limited OT impact (Benchmark). [S-001] [S-004] [S-015] No attribution or initial access route was published in company releases; a criminal group's claim reported by media was not confirmed by JLR or the NCA (Observed). Interpretation: the evidence supports an IT-dependency stop rather than a demonstrated manipulation of plant control systems (Judgement).

**Operational consequences.**
- [S-002] [S-003] Production stopped across UK plants and Nitra; restart began on 8 October 2025 with engine and battery assembly, then Slovakia and Solihull (Observed).
- [S-005] [S-006] Production returned to normal by mid-November, but vehicle distribution took longer; Q3 wholesales fell 43.3%, with Europe down 47.6% and North America down 64.4% (Observed; tariffs and model wind-down also contributed).
- [S-003] JLR set up a supplier help desk, settled invoices manually and re-established automated supplier payments in the week of 7 October (Observed).

**Public financial, macro and government outcomes.** [S-004] [S-006] Cyber-related exceptional costs were GBP 196 million in Q2 and GBP 64 million in Q3 (Observed). [S-007] Full-year revenue fell 20.9% to GBP 22.9 billion and free cash outflow reached GBP 2.2 billion, with production stoppages one of several cited causes (Observed). [S-009] The government guarantee was explicitly framed as support for the supply chain and skilled jobs (Observed). [S-011] [S-012] [S-013] ONS recorded the September fall in motor-vehicle output and relayed SMMT's attribution, and the Bank of England cited the disruption as one reason for weaker Q3 growth (Observed). [S-010] The CMC modelled a UK loss of GBP 1.9 billion and over 5,000 affected organisations (Benchmark).

**Recovery constraints.** [S-005] [S-006] Restoring production took about five weeks and restoring distribution took longer, so the financial effect extended across two quarters (Observed). [S-010] The CMC identifies the recovery profile, OT impact and failure of hard-to-replace suppliers as the main sensitivities of the loss estimate (Benchmark). [S-008] JLR's annual report states the company is still investing in its IT systems and has learned lessons, without quantifying the full-year cost (Observed).

**Applicability of regulation.** [S-049] Motor-vehicle manufacturing (NACE C29) is an Annex II NIS2 activity, so JLR's Slovak manufacturing entity could fall within national NIS2 law subject to size and national transposition; this was not confirmed (Judgement). [S-095] In the UK, manufacturing is not an essential-service sector under the NIS Regulations 2018 (Observed), and [S-075] the Cyber Security and Resilience Bill had not received Royal Assent at the cut-off (Observed). [S-071] As a vehicle manufacturer, JLR must hold a cyber security management system certificate under UN Regulation No. 155 for type approval (Observed).

**Sector lesson.**
- [S-001] [S-010] [S-039] For manufacturers: plant OT can be intact while production stops; IT-OT dependency mapping and the ability to release production manually determine stop length (Judgement).
- [S-003] [S-009] [S-010] For supply chains: one OEM's stop transfers liquidity stress to suppliers within weeks; customer-funded prepayment and state guarantees were used to bridge it (Judgement).
- [S-004] [S-003] [S-009] For banks (generic): counterparty liquidity, supplier-finance programmes and state-guarantee channels are where such an event becomes visible (Judgement).

**What the case does not establish.** The initial access route, the attacker's identity, any ransom, the OT state, the full-year cyber cost, insurance recoveries, or any supplier insolvency caused by the event. The GBP 1.9 billion figure is modelled. The case concerns one automotive OEM with just-in-time supply; process and buffered-inventory manufacturers may behave differently.

**Second and third case studies.** Not reconstructed in the baseline (gap G-05 of the migrated edition). The user input supplies case material for fraud and governance (Rolls-Royce, Airbus, Toshiba) and operational disruption (Fairlife, Nucor) but no reconstruction with a timeline; they are recorded in Q10.2 and section D, not as detailed case studies (gap, section F).

## Q03 - Threat assessment, attack pathways and exploited weaknesses

| Pathway (pattern) | Operational vulnerability | Systemic or concentration translation | Evidence base |
|---|---|---|---|
| P1 Ransomware and data extortion against enterprise IT | Encryption of ERP, MES, identity and virtualisation layers forces precautionary plant stops | Few groups (EU Agency for Cybersecurity (ENISA): Qilin, Akira, SafePay) hit many manufacturers; Europe rising | [S-041] [S-039] [S-040] ENISA 2026; Dragos Q2 2026; Black Kite 2026 |
| P2 Destructive misuse of administrative platforms | Endpoint-management or identity tools used to wipe devices across sites | One administrative plane reaches every plant and office | [S-023] [S-025] Media reporting on Stryker; CISA alert (organisation unnamed) |
| P3 Internet-exposed OT and fielded products | End-of-life or default-configured controllers reachable online | A manufacturer's installed base becomes a fleet-wide exposure | [S-035] [S-089] CERT-FR alert; US PLC advisory |
| P4 Supplier and service-provider compromise | Managed IT, integrators and component suppliers carry access or single-source parts | One provider reaches many customers | [S-034] [S-039] [S-030] Egide; ICS ecosystem counts; West Pharmaceutical |
| P5 Data theft, intellectual-property and export-control exposure | Exfiltration from engineering and corporate systems | Trade-secret, export-control and personal-data liabilities follow production loss | [S-016] [S-030] [S-041] Asahi; West Pharmaceutical; ENISA exfiltration share |

**Benchmarks.**
- [S-041] ENISA recorded manufacturing as the fourth most affected EU sector (6.9% of 8,257 incidents in 2025) but the largest share of ransomware claims (25.2%), led by Qilin, Akira and SafePay; it also observed a shift towards exfiltration (73.3% of technique observations) over encryption (13.7%) and more unconfirmed hacktivist claims against manufacturing OT.
- [S-039] Dragos counted 747 manufacturing incidents in Q2 2026 (about 65% of 1,140 industrial incidents) and 117 in the industrial control system (ICS) ecosystem of engineering firms, integrators and equipment makers.
- [S-040] Black Kite reports machinery (15.2%), fabricated metal (11.2%), transport equipment (9.2%), chemicals (9.2%), electronics (8.8%) and food (7.8%) as the most frequently named manufacturing subsectors since 2023.
- [S-042] A vendor incident-response dataset relayed by trade media ranked manufacturing the most attacked industry in 2025, with exploitation of public-facing applications the leading entry route (context, Tier 3).
- [U-007] [U-000] User-supplied additions (not validated): 65% of manufacturers reported ransomware against a 46% all-sector average (Sophos 2023 via WTW); manufacturing at 17-20% of reported cases globally in 2022 ("market studies", no source given); LockBit exploitation of VMware vulnerabilities used in factories in 2023 (no source given). The Sophos 65% is a share of surveyed manufacturers; the Dragos 65% is a share of industrial ransomware incidents; they are different statistics (conflict E-07).

**Principal judgements (baseline).**
1. **Production loss runs mainly through IT dependency, not direct OT compromise (confidence medium).** [S-001] [S-016] [S-021] [S-027] JLR, Asahi, Stryker and Boston Scientific stopped or slowed production after IT incidents (Observed). [S-039] Dragos found no Q2 2026 ransomware case that reached control-system manipulation (Benchmark). Competing explanation: [S-010] companies rarely disclose OT state, and the CMC noted the OT impact at JLR was unclear. Would change: disclosure of control-system manipulation causing physical damage or safety events.
2. **Supplier cascade and liquidity are the systemic pathway in just-in-time manufacturing (confidence medium).** [S-010] The CMC modelled that the JLR stop affected over 5,000 UK organisations (more than 2,700 in its Category 3 criteria section) and assumed key suppliers would stay solvent (Benchmark). [S-003] [S-009] JLR prepaid qualifying suppliers through a banking partner and the UK Government backed a GBP 1.5 billion loan (Observed). Competing explanation: buffered or high-mix production may absorb short stops. [S-047] Would change: official evidence that lower-tier suppliers absorbed multi-week stops without support; the German Government holds no information on cyber-caused insolvencies (Observed).
3. **Financial transmission is dominated by lost output and working capital, not response cost (confidence medium).** See Q05.
4. **State-linked activity is rising, but no official source in the period attributed a manufacturing disruption to a state actor (confidence low).** See Q07.
5. **Regulation reaches most manufacturers through product law and contracts rather than entity-level regimes (confidence medium).** See Q06.

**Ranking (migrated judgement, not measured outcome).** 1 P1 ransomware against enterprise IT - High; 2 P2 administrative platforms - High; 3 P3 internet-exposed OT and fielded products - High; 4 P4 supplier and service-provider compromise - Medium; 5 P5 data theft and export-control exposure - Medium. Direction: rising in claim-based data [S-040]; no trend series from a prior edition.

**Cyber-enabled fraud pathways (user input, cross-reference to Q10).** [U-000] BEC through compromised cloud email, supplier-portal takeover and phishing that imitates key component suppliers are added as cyber-enabled fraud pathways (User-supplied); they are mapped to Fraud for the deception and payment step and to Cyber for the compromise step.

## Q04 - Cyber resilience capabilities and sector control benchmarks

| Priority capability | Weakness evidenced | Control objective | Action or challenge question | Role type | Horizon | Confidence |
|---|---|---|---|---|---|---|
| A1 IT-OT production dependency | [S-001] [S-016] [S-027] Plants stop when ERP, MES or identity stop | Produce and ship safely during IT loss | Ask the largest manufacturing counterparties for evidence of manual production release and tested IT-loss recovery | 1LoD sector risk owner | 0-6 months | Medium |
| A2 Administrative planes | [S-023] [S-025] Endpoint and identity tools can wipe every device | Constrain destructive administrative actions | Challenge whether counterparty assessments cover multi-administrator approval for wipe actions and separation of admin identities | 1LoD third-party risk | 0-3 months | Medium |
| A3 Supplier liquidity cascade | [S-010] [S-003] Small suppliers depend on one customer | See and bridge supplier stress early | Map revenue concentration of supplier-finance participants and test a four-week customer stop | 1LoD credit and supply-chain finance | 0-6 months | Medium |
| A4 Fielded OT and product fleets | [S-035] [S-036] End-of-life controllers reachable online | Know and reduce installed-base exposure | Ask equipment-maker counterparties for exposure monitoring and end-of-support plans | 1LoD sector risk owner | 3-12 months | Medium |
| A5 Service providers and integrators | [S-034] [S-039] Provider access into plants | Contain provider-borne compromise | Check that counterparties restrict and log provider remote access to OT | 1LoD third-party risk | 3-12 months | Medium |
| A6 Product-law readiness | [S-057] [S-066] Reporting since September 2026; liability from December 2026 | Meet reporting and liability duties | Ask manufacturing counterparties for reporting procedures and support-period policies | 1LoD credit and legal | 0-6 months | High |
| A7 Insurance and contracts | [S-010] [S-049] Customer-side disruption often uninsured | Align cover and clauses with dependency | Review whether lending and guarantee documentation reflects cyber disruption and notification terms | 1LoD credit and legal | 6-12 months | Medium |

| Exposure | Evidence of completion | Residual dependency | External monitoring trigger |
|---|---|---|---|
| A1 | Documented manual-release procedure; recovery test results | Single ERP or MES instance | Company production-pause notice or exchange filing |
| A2 | Assessment evidence on admin controls | Cloud administration outside counterparty control | Government alert on administrative-tool misuse |
| A3 | Concentration map; stress-test record | Lower-tier suppliers outside programme | OEM incident notice; supplier short-time work announcements |
| A4 | Exposure and end-of-support register | Customers who do not patch | National CERT alert naming a product family |
| A5 | Access inventory and logs | Provider's own security | Exchange disclosure citing an IT provider |
| A6 | Reporting procedure; support-period statements | National liability laws pending | First enforcement or reporting statistics |
| A7 | Documentation review record | Market capacity for supply-chain cover | Insurer product changes; government support thresholds |

[S-035] CERT-FR's recommended actions for affected controllers are reusable for any OT product fleet: remove internet exposure, restrict access to secured remote connections, apply vendor hardening and firmware updates, change default credentials and treat a reset alone as insufficient (Observed).

**Framework reference mapping (voluntary or contractual; not law).** [S-092] [S-093] A1: NIST CSF 2.0 Identify and Recover, NIST SP 800-82, IEC 62443, ISO 22301; A2: Protect, ISO/IEC 27001 and 27002, CIS Controls; A3: Govern (supply-chain risk), ISO/IEC 27036, VDA ISA and TISAX; A4: Identify and Protect, IEC 62443-4-1 and 4-2, ETSI EN 303 645, software bill of materials (SBOM) practice; A5: Protect and Detect, IEC 62443-2-4, MITRE ATT&CK for ICS; A6: Govern and Respond, ISO/SAE 21434; A7: Govern, ISO/IEC 27036. NIST SP 800-82 Rev. 3 is final with a Rev. 4 draft open for comment and the NIST manufacturing profile for CSF 2.0 was an initial public draft; other standards are named as vocabularies and their texts were not reviewed (Judgement).

**Maturity benchmark.** No sector cyber-maturity survey was available in the baseline (gap). [U-007] [U-009] [U-000] The user input adds that security maturity is generally below the financial sector, offensive testing is rare, the average time to remediate vulnerabilities is the longest among sectors at 122 days (Cobalt, 2023), an in-house security operations centre (SOC) is frequently absent, with reliance on managed service providers (MSPs) or reactive response plans, and rising cyber insurance take-up signals recognition of the need to invest (User-supplied; Q11).

## Q05 - Financial impact, disruption trends and credit transmission

**Bottom line.** [S-004] [S-019] [S-027] Public financial evidence is concentrated in a few listed companies and is dominated by lost output and cash rather than by response cost (Judgement). [S-010] The only economy-wide estimate is modelled, for one UK event (Benchmark). [S-047] No official source attributes a supplier insolvency to a cyber incident (Observed).

| Case | Metric type | Value | Period | Population | Comparability note | Source |
|---|---|---|---|---|---|---|
| JLR | Cyber-related exceptional costs | GBP 196 million (Q2) and GBP 64 million (Q3) | July-December 2025 | One OEM | Direct costs only; full year not disclosed | [S-004] [S-006] |
| JLR | Quarterly revenue change | -24% (Q2) and -39% (Q3) | July-December 2025 | One OEM | Q2: stoppage and Jaguar wind-down; Q3: also tariffs and China | [S-004] [S-006] |
| JLR | Free cash flow | GBP -791 million (Q2), GBP -1.5 billion (Q3) | July-December 2025 | One OEM | Includes non-cyber drivers | [S-004] [S-006] |
| JLR | Wholesale volume change | -43.3% (Q3) | October-December 2025 | One OEM | Provisional; several causes | [S-005] |
| JLR event | Modelled UK loss | GBP 1.9 billion (range 1.6-2.1) | Late August 2025 to early January 2026 | UK organisations | Modelled; excludes overseas and data losses | [S-010] |
| UK motor vehicle output | Monthly output change | -28.6% | September 2025 | NACE 29, UK | Statistics office relays trade-body attribution | [S-011] |
| Asahi | Total 2025 impact | About JPY 40 billion | Calendar 2025 | One beverage and food group | Core operating profit decline plus JPY 17 billion incident-related expenses | [S-019] |
| Stryker | Materiality | Material effect on Q1 2026; guidance kept | Q1 2026 | One device maker | Not quantified | [S-021] [S-022] |
| Boston Scientific | Guidance | Q3 and full-year 2026 guidance unlikely to be met | Q3 2026 | One device maker | Not quantified; results due 28 October 2026 | [S-027] |
| Hasbro | Revenue timing | Some Q2 impact; guidance reiterated | Q2 2026 | One consumer-goods maker | Not quantified | [S-032] |
| Manufacturers surveyed (User-supplied) | Average ransomware recovery cost | USD 1.67 million | 2022 | About 1,000 firms globally (Sophos via WTW) | Survey, self-reported; insurer focus | [U-007] |
| Manufacturers (User-supplied) | Average ransom demand paid | USD 2.4 million; 60% pay | Not stated | Not stated ("insurance reports") | No source given; not comparable with the above | [U-000] |
| Fairlife, Nucor (User-supplied) | Loss | Not disclosed (production halted; partial stop) | July 2026; May 2025 | One company each | Absence of data is not zero | [U-005] [U-006] |

[S-004] [S-006] JLR booked GBP 196 million of cyber-related exceptional costs in Q2 and GBP 64 million in Q3 of fiscal year 2025/26; Q2 revenue fell 24% to GBP 4.9 billion and Q3 revenue 39% to GBP 4.5 billion; free cash outflow was GBP 791 million and GBP 1.5 billion (Observed). [S-007] Full-year free cash outflow was GBP 2.2 billion and pre-tax profit before exceptional items fell to GBP 14 million from GBP 2.5 billion (Observed; several causes). [S-019] Asahi's JPY 40 billion combines a fall in core operating profit, about JPY 20 billion of it lost marginal profit, and JPY 17 billion of expenses for inventory disposal, restoration staff and cancelled promotions (Observed). [S-010] The CMC estimate is a scenario model using public data and expert input, UK operations only, assuming about GBP 108 million of weekly loss at JLR and roughly 1,000 tier-1 suppliers affected on the same profile (Benchmark).

**Comparability.** Values differ in currency, statistic type, population and period and are never summed or averaged. The only derived figure, GBP 260 million, adds two quarters of the same JLR expense line. No sector-wide loss estimate is produced. User-supplied survey averages are not combined with company disclosures.

**Impact types.**

| Impact type | Public evidence in scope | Status |
|---|---|---|
| Production stoppage | [S-005] [S-021] [S-027] JLR about five weeks; Stryker about four weeks; Boston Scientific partial; [U-005] [U-006] Fairlife and Nucor (User-supplied) | Observed for named cases |
| Delivery and order backlog | [S-005] [S-017] [S-032] JLR Q3 wholesales -43.3%; Asahi sales ratios; Hasbro delays | Observed |
| Response, recovery and incident-related cost | [S-004] [S-006] [S-019] JLR GBP 260 million; Asahi JPY 17 billion; [U-007] USD 1.67 million survey average (User-supplied) | Observed for two companies |
| Revenue effect | [S-004] [S-019] [S-027] JLR (mixed causes); Asahi lost margin; Boston Scientific guidance | Partly attributable |
| Working capital and liquidity | [S-004] [S-003] JLR cash outflow, bridge facility and supplier prepayment | Observed |
| Supplier cascade | [S-010] CMC model of over 5,000 UK organisations | Modelled only |
| Supplier insolvency | [S-047] No official attribution | Not evidenced |
| Ransom | No ransom disclosed by any named company; [U-000] USD 2.4 million average and 60% payment rate (User-supplied, no source) | Not evidenced for named cases |
| Insurance | [S-010] Cover gaps for customer-side disruption; no claim values disclosed | Qualitative only |
| Regulatory and data | [S-016] [S-034] Asahi personal-data notification; Egide CNIL notification | Observed; no fines in period |
| Fraud and bribery outcomes | [U-002] [U-003] Rolls-Royce and Airbus settlements (historical; User-supplied); see Q10 | User-supplied |
| Macro-economic | [S-011] [S-013] ONS and Bank of England record JLR output effect | Observed |
| Government support | [S-009] UKEF guarantee for up to GBP 1.5 billion | Observed |

**Credit transmission (conditional channels).**
- **Corporate liquidity and covenants.** [S-004] [S-007] JLR signed a GBP 2 billion bridge facility on 22 September 2025, secured a GBP 1.5 billion UKEF-guaranteed loan in October and held GBP 6.9 billion of liquidity at 31 March 2026 with the guaranteed loan undrawn; the undrawn bridge amount fell from GBP 2.0 billion at 30 September 2025 to GBP 1.0 billion at 31 March 2026 (Observed). Judgement: the bank-relevant signals are facility drawdown and covenant headroom.
- **Supplier finance and receivables.** [S-003] [S-004] JLR's scheme, run with a banking partner, prepaid qualifying suppliers instead of on 60-day terms, accelerating payment by up to 120 days; the Q2 release describes a GBP 500 million financing solution (Observed). Judgement: supply-chain finance programmes and receivables lines are where supplier stress becomes visible first.
- **State-backed lending.** [S-009] The UKEF Export Development Guarantee typically covers up to 80% of lender risk; the JLR loan runs for five years (Observed).
- **Insurance gap.** [S-010] Cyber insurance typically covers an insured's own losses and supplier failure but not disruption at a key customer (Benchmark).
- **Macro and sector output.** [S-011] [S-013] The 28.6% fall in UK motor-vehicle output contributed -0.17 percentage points to a 0.1% fall in monthly GDP (Observed).
- **Product liability and fleet remediation.** [S-035] [S-066] Compromise of fielded controllers creates replacement, warranty and potential liability costs, which the revised liability directive extends to software and missing security updates (Judgement based on observed legal text).
- **Fraud and governance channel (User-supplied).** [U-000] Unplanned payments drain liquidity; large settlements reduce EBITDA; reputational effects can reach mergers and acquisitions and access to credit (User-supplied; Q10.6).

**Worst-case scenarios (structured stress narratives; not forecasts or loss estimates; no probabilities).**

| Element | Scenario 1 - Common digital-dependency failure | Scenario 2 - Targeted operational disruption | Scenario 3 - Third- or fourth-party supply-chain concentration |
|---|---|---|---|
| Trigger (Assumption) | [S-024] [S-025] Multi-day loss or destructive misuse of a common enterprise platform (identity or endpoint management, MES or ERP service, electronic data interchange (EDI) or supplier portal) used by many manufacturers and suppliers | [S-001] [S-027] Ransomware or destructive intrusion at one high-volume OEM or tier-1 supplier triggers a precautionary global shutdown | [S-035] [S-034] Compromise of a shared supplier layer: an OT vendor's fielded controllers, an integrator or IT provider with plant access, or a widely used component supplier |
| Affected service | Order-to-cash, production scheduling, logistics release, quality release, supplier payment | Vehicle, device or consumer-goods production and delivery; supplier call-offs | Field equipment at customers; customer production lines; component availability |
| Propagation | [S-037] [S-039] A manufacturer's software product on many customer networks failed at once (cross-sector analogue); OT stops when enterprise layers are lost | [S-010] [S-003] Just-in-time call-offs stop; tier-1 to tier-3 suppliers idle; restart phased by plant | [S-035] [S-034] [S-039] Numerous controllers compromised at once; supplier hit through its IT provider; 117 ICS-ecosystem incidents in one quarter |
| Impact drivers | Simultaneous precautionary stops, missed delivery windows, manual workarounds | Weeks of lost output, fixed-cost absorption, expedited freight, overtime | Fleet-wide remediation, customer losses, reporting, recall or replacement |
| Financial transmission | Correlated output gaps, concurrent working-capital draws, delay-clause disputes | [S-004] [S-009] OEM cash outflow in the hundreds of millions per quarter, emergency facilities, possible state-backed lending; supplier liquidity stress | Correlated customer claims, warranty and liability costs, downstream shortages |
| Early signposts | Provider outage or breach notices; alerts on platform misuse; known-exploited-vulnerability additions | Incident notices and filings; extended production pauses; supplier short-time work; requests for state support | CERT alerts naming products; disclosures citing an IT provider; end-of-support notices |
| Limiting conditions | Offline production fallback; tenant isolation; manual release | [S-021] Segmented estates restored within weeks; buffered inventory; multi-sourcing | [S-036] Patches for current firmware; customer segmentation |
| Assumptions | Platform unavailable three to ten days; no OT compromise; not observed in the period | Four- to eight-week stop anchored to JLR's about five weeks plus distribution lag | Exposure persists in end-of-life fleets; anchored to the national-scale controller campaign |
| Management question | Which shared platforms do the largest counterparties depend on to release production, and can they produce and ship for two weeks without them? | How many weeks of stop can liquidity absorb, and which suppliers depend on them for most of their revenue? | Which counterparties sell connected controllers or machinery with long field lives, and do they track exposure and end-of-support status? |

[U-005] [U-006] The user input's Fairlife and Nucor stops are further anchors for Scenario 2 (single-firm production halts) but carry no duration or loss data (User-supplied).

**Illustrative disruption bands (not forecasts; no loss per band).**

| Band | Mechanism | Duration evidence | Credit channel |
|---|---|---|---|
| 1 week | Common digital dependency (shared enterprise platform) | Duration not evidenced: baseline assumption of three to ten days; no multi-firm outage observed | Correlated delivery gaps; concurrent working-capital draws |
| 4 weeks | Targeted disruption at a segmented manufacturer | [S-021] Stryker restored manufacturing and ordering in about four weeks (Tier 1) | Deferred revenue; material quarterly effect |
| 8 weeks | Targeted disruption at a just-in-time OEM | [S-005] [S-006] JLR about five weeks halted, normal production by mid-November, distribution later (Tier 1) | OEM cash outflow, emergency facilities, supplier prepayment, state guarantee |

Supply-chain concentration (Scenario 3): mechanism kept, band duration not evidenced. Five-year cost trends and sector business-interruption benchmarks were not available in either evidence set (gap).

## Q06 - Regulatory authorities and cyber resilience expectations

| Regime | Jurisdiction | Legal status | Obligation type | Key dates | Applicability to Manufacturing |
|---|---|---|---|---|---|
| NIS2 Directive (EU) 2022/2555 | EU | Binding via national law | Risk management incl. supply chain; 24h, 72h and one-month reporting; management accountability | In force 16 January 2023; transposition 17 October 2024 | Annex II: medical devices and in-vitro diagnostic devices (IVD); NACE C26-C30; chemicals; industrial food. Annex I: C21 pharmaceuticals and emergency-list devices. Others only by national extension |
| NIS2 enforcement | EU | Court referral | Penalties requested | Referral 8 July 2026 (IE, ES, FR, NL) | Uneven obligations for multinationals |
| German NIS2 law | Germany | Binding | Registration, measures, reporting | In force 6 December 2025 | 4,739 manufacturing registrations by 30 September 2026 |
| CER Directive (EU) 2022/2557 | EU | Binding via national law | Resilience of designated entities | Transposition 17 October 2024; identification by 17 July 2026 | Manufacturing not a listed sector; food and health entities may be designated |
| Cyber Resilience Act (CRA), Regulation (EU) 2024/2847 | EU | Directly applicable | Vulnerability and incident reporting; later essential requirements | Reporting from 11 September 2026; full application 11 December 2027 | Manufacturers of in-scope products with digital elements; excludes medical devices, IVD, type-approved vehicles, civil aviation, marine equipment and products made exclusively for national security or defence |
| Machinery Regulation (EU) 2023/1230 | EU | Directly applicable | Protection against corruption; safe control systems | Applies 20 January 2027 | Machinery makers and integrators |
| Regulation (EU) 2026/1744 (AI Act amendments) | EU | Directly applicable | Deferred high-risk dates; machinery AI rules via delegated acts | In force 27 July 2026; Annex I high-risk 2 August 2028 | AI safety components in machinery and vehicles |
| Product Liability Directive (EU) 2024/2853 | EU | Binding via national law | Strict liability incl. software and missing security updates | Transposition by 9 December 2026 | All manufacturers |
| Radio-equipment cybersecurity act and repeal (EU) 2026/339 | EU | Delegated acts | Wireless product security | Repeal in force 19 May 2026; old act ends after 10 December 2027 | Wireless product makers |
| Data Act (EU) 2023/2854 | EU | Directly applicable | Connected-product data access | Applies 12 September 2025 | Industrial machinery makers |
| UN Regulation No. 155 | EU and UNECE | Binding for type approval | Cyber security management system | All new M, N, O vehicles from 1 July 2024 | Vehicle OEMs and suppliers |
| GMP Annex 11 revision | EU | Draft guidance | Computerised-system controls | Consultation closed 7 October 2025 | Pharmaceutical manufacturers |
| Revised FDI Screening Regulation | EU | Adopted; applies after 18 months | Investment screening | Published 26 June 2026 | Dual-use and advanced-technology manufacturers |
| UK NIS Regulations 2018 | UK | Binding | Operators of essential services | In force since 2018 | Manufacturing not in scope |
| Cyber Security and Resilience Bill | UK | Bill (Lords report stage) | MSPs, data centres, designated suppliers | Bill version 7 September 2026; no Royal Assent | Could reach providers serving manufacturers |
| Ransomware proposals | UK | Proposals | Payment ban, prevention, reporting | Response 22 July 2025; no bill | Private manufacturers in prevention and reporting regimes |
| COMAH 2015 and Health and Safety Executive (HSE) OG86 | Great Britain | Binding duties; guidance | Industrial automation and control system cyber as part of safety | OG86 March 2017 | Major-hazard chemical sites |
| NSI Act 2021 | UK | Binding | Mandatory notification in 17 areas | In force 2022 | Advanced materials, robotics, defence, dual-use |
| MOD Cyber Security Model v4 | UK | Contractual | Def Stan 05-138 controls; flow-down | Updated 6 March 2026 | Defence suppliers |
| PSTI product security regime | UK | Binding | Passwords, vulnerability reporting, update periods | 29 April 2024 | Consumer connected-product makers |
| SEC Item 1.05 and Item 106 | US (comparative) | Binding | Material-incident and annual disclosure | Compliance from December 2023 | US-listed manufacturers |
| CMMC via DFARS | US (comparative) | Binding contract clause | Cybersecurity certification | Effective 10 November 2025; next phase 10 November 2026 | Defence-industrial base incl. foreign subsidiaries |
| FDA section 524B | US (comparative) | Binding statute | Premarket cyber plans, SBOM | 29 March 2023 | Medical-device makers |
| CIRCIA rule; chemical facility standards | US (comparative) | Not final; lapsed | Reporting; chemical security | Rule at White House review 1 October 2026; authority lapsed July 2023 | US manufacturers |

[S-049] [S-050] [S-051] [S-052] [S-045] [S-046] [S-054] [S-053] [S-057] [S-056] [S-055] [S-059] [S-058] [S-063] [S-064] [S-065] [S-061] [S-060] [S-062] [S-066] [S-067] [S-068] [S-069] [S-071] [S-070] [S-073] [S-074] [S-075] [S-076] [S-077] [S-078] [S-079] [S-080] [S-081] [S-082] [S-095] [S-083] [S-084] [S-096] [S-094] [S-086] [S-087] [S-088] The table records legal status, obligation type and date basis from the primary instrument or official page where available; dates taken from secondary sources are flagged in the baseline regulatory register (Observed).

**NIS2 scope and obligations.** [S-049] [S-050] Annex II lists manufacturing of medical devices and IVD and NACE divisions C26-C30; chemicals and industrial food production are separate Annex II sectors; Annex I health covers C21 pharmaceuticals and emergency-list medical devices (Observed). [S-049] The directive applies at or above medium-enterprise size, with national discretion for smaller sole or systemic providers; management bodies must approve and oversee measures; supply-chain security is required; incidents need a 24-hour early warning, 72-hour notification and one-month final report; maximum fines are at least EUR 10 million or 2% of worldwide turnover for essential and EUR 7 million or 1.4% for important entities (Observed). For metals, basic materials, consumer goods and textiles no NIS2 route exists unless a Member State extends scope (Judgement); supply-chain duties of in-scope customers reach out-of-scope suppliers through contracts (Judgement). [S-051] [S-052] On 8 July 2026 the Commission referred Ireland, Spain, France and the Netherlands to the Court of Justice (Observed). [S-046] [S-045] Germany's law entered into force on 6 December 2025; by 30 September 2026 the German Federal Office for Information Security (BSI) recorded 20,373 registrations against about 29,500 expected entities, 4,739 selecting manufacturing (Observed).

**Product-security, machinery and liability rules.** [S-057] [S-056] Since 11 September 2026 manufacturers must report actively exploited vulnerabilities and severe incidents in their products through ENISA's Single Reporting Platform (24-hour early warning, 72-hour notification); main essential requirements apply from 11 December 2027 (Observed). [S-058] Important and Annex IV product categories require standards-based or third-party conformity assessment; the technical description was adopted on 28 November 2025 (Observed). [S-063] [S-064] The Machinery Regulation applies from 20 January 2027 (Observed). [S-060] [S-061] Regulation (EU) 2026/1744 defers high-risk AI obligations for product safety components to 2 August 2028 (Observed). [S-066] [S-067] The revised Product Liability Directive must be transposed by 9 December 2026 (Observed).

**Fraud, anti-corruption and governance rules (user input; cross-reference to Q10.7).** [U-013] The user input adds the US Foreign Corrupt Practices Act (FCPA) and False Claims Act, the UK Bribery Act 2010 and Companies Act 2006 (sections 172-173), payment services rules (PSD2), Financial Conduct Authority (FCA) and Prudential Regulation Authority (PRA) guidance, NIS2, the EU Whistleblowing Directive (EU) 2019/1937, EU public-procurement directives (Directive 2014/24/EU) and Brazil's Anti-Corruption Law 12.846/2013 (User-supplied; status and conflicts in Q10.7 and E-08 to E-10).

**Hazardous processes.** [S-079] [S-072] HSE treats industrial automation and control system security at COMAH sites as part of plant safety; the Commission's 2025 Seveso III implementation report does not address cyber events as accident initiators (Observed).

**Not assessed beyond naming (baseline).** EU Trade Secrets Directive, Dual-Use Regulation, Chips Act, raw-materials regulation, Economic Security Strategy, Medical Devices Regulation guidance, UK Data (Use and Access) Act, UK Market Abuse Regulation, Japan METI factory guidelines, Australia SOCI and the US Cyber Trust Mark.

**Forward monitoring horizon.** [S-027] 28 October 2026: Boston Scientific Q3 results and outlook; [S-035] October-December 2026: French controller campaign counts, remediation and attribution; [S-096] 10 November 2026: next CMMC phase; [S-092] 30 November 2026: NIST SP 800-82 Rev. 4 comment deadline; [S-067] 9 December 2026: Product Liability Directive transposition; [S-075] [S-086] late 2026: UK Bill Royal Assent and US CIRCIA final rule; [S-063] 20 January 2027: Machinery Regulation; [S-056] 11 December 2027: full CRA application; [S-051] 2026-2027: NIS2 Court cases, national extensions and CER designations.

## Q07 - Geopolitical cyber threats and systemic exposure

| Driver | Baseline evidence | Manufacturing exposure | Attribution status |
|---|---|---|---|
| State-linked PLC targeting | [S-089] [S-090] US joint advisory on Iranian-affiliated actors exploiting internet-facing PLCs, April 2026 | Makers and industrial users of the same controllers | Government advisory; per a vendor summary, manufacturing not a named sector |
| Destructive activity claimed by a state-linked persona | [S-023] [S-024] Stryker device wipe, March 2026 (media reports) | Multi-site manufacturers through administrative tools | Claim unconfirmed; no US government attribution |
| Nation-state share of national incidents | [S-091] UK National Cyber Security Centre (NCSC): most nationally significant UK incidents originate directly or indirectly from nation states | UK economy-wide, no manufacturing split | Official statement, not sector attribution |
| Endpoint-management hardening | [S-025] CISA alert after an attack on an unnamed US organisation | Multi-site manufacturers | No attribution in the alert |
| Hacktivist claims against OT | [S-041] More unconfirmed hacktivist intrusion claims against manufacturing OT in 2025 | OT-exposed manufacturers | Claims only |
| Economic security and ownership | [S-073] [S-074] [S-080] Revised EU investment-screening regulation published 26 June 2026; UK NSI Act covers 17 areas | Dual-use, advanced-technology and defence manufacturers | Policy context, not attribution |
| Defence supply-chain gates | [S-084] [S-096] [S-081] CMMC clause since 10 November 2025; MOD Cyber Security Model flow-down | Defence suppliers incl. foreign subsidiaries | Not applicable |

**Judgement (confidence low).** State-linked activity is a rising threat to industrial controllers and enterprise estates, but no official source in the period attributed a manufacturing disruption to a state actor; most production losses were financially motivated ransomware. State-linked activity is treated as a monitoring trigger rather than a rating driver. Would change: official attribution of a European manufacturing disruption to a state actor.

**User-input geopolitical content.** [U-002] [U-003] The input adds no state-linked cyber evidence. Its bribery cases (Rolls-Royce in the UK, US and Brazil; Airbus in France, the UK and the US) show cross-border enforcement exposure of aerospace and defence manufacturers, and [U-000] it names emerging regulation and generative AI as future drivers without mature evidence (User-supplied). Dedicated geopolitical analysis, exposed-region mapping, espionage and intellectual-property theft by state actors, and sanctions and export-control links remain unresearched (gap).

---

# Part B - Classification evidence (Q10-Q14, updated 28 October 2026)

All U- content below is **User-supplied (not validated)** and translated from Portuguese. Baseline (S-) cross-references are labelled as such.

## Q10 - Sector fraud exposure and financial consequences

**Baseline position.** The baseline edition did not research fraud (gap G-02 of the migrated edition); it held only cyber-incident evidence, a judgement that supply-chain finance and receivables are where supplier stress becomes visible [S-003], and the absence of any disclosed ransom [S-004]. The user input supplies the material below.

### Q10.1 Typology screen

| Typology | Materiality | Category | Detail and justification (as supplied) | Source |
|---|---|---|---|---|
| Payment diversion (mandate fraud) | Material | Hybrid (cyber plus human) | Industry depends on large payments to international suppliers; classic BEC-type fraud reported across sectors, though few public manufacturing-specific cases; usually starts with phishing or intrusion to change suppliers' bank details (RIB/IBAN) | [U-000] [U-008] |
| Business email compromise (BEC) | Material | Cyber-enabled | BEC hits industrial companies to the same extent; FBI and IC3 report billions in losses (above USD 26 billion globally); manufacturers are no exception | [U-008] |
| Invoice and procurement fraud | Material | Hybrid | False invoices or manipulated purchase contracts, as in the Iris Kim defence case; the sector has many purchasing processes and therefore many potential vectors | [U-004] |
| Supplier impersonation | Possible | Cyber-enabled | BEC variant in which fraudsters pose as a supplier to capture payment; no sector statistics, but plausible given global supply chains | [U-000] |
| Executive impersonation (CEO/CFO) | Possible | Cyber-enabled | Less common, but recent voice and video deepfake cases (CEO and CFO fraud) indicate potential risk (for example a German case in 2020); no public manufacturing-specific case documented | [U-000] |
| Account takeover (ERP or portal) | Possible | Cyber-enabled | Remote ERP systems are potential vectors: intrusion allows false payments to be authorised; no public manufacturing case found, but a known vector in other sectors | [U-000] [U-012] |
| Insider fraud | Material | Non-cyber (insider) | Managers may steal assets (inventory, equipment) or divert internal funds; investigations by the Association of Certified Fraud Examiners (ACFE) show manufacturing among sectors with internal fraud | [U-000] |
| Physical asset misappropriation | Material | Non-cyber | Manufacturing holds inventories (raw materials, finished goods) and valuable equipment; employee misappropriation found; often the leading category by number of cases in occupational fraud studies | [U-000] |
| Accounting and financial statement fraud | Possible | Non-cyber | Large conglomerates have inflated revenue or hidden costs (for example Toshiba), but such cases are exceptional in manufacturing; involves senior management and affects lenders through false financial statements | [U-011] |
| Corruption and bribery | Material | Hybrid | Rolls-Royce and Airbus illustrate systemic bribery in tenders and public contracts in aerospace manufacturing; FCPA, UK Bribery Act and OECD anti-bribery rules apply | [U-002] [U-003] |
| Identity and synthetic identity fraud | Possible | Hybrid | Schemes using false identities for credit or contracts; no highlighted manufacturing case, but a sector receiving government credit (subsidies) may be vulnerable | [U-000] |
| Subsidy and tax fraud | Possible | Non-cyber | Manufacturers receiving subsidies or tax rebates may inflate costs or falsify documents (for example value added tax (VAT) fraud in global chains); few sector cases documented | [U-000] |
| Fraud against customers | Possible | Non-cyber | Sale of defective or adulterated products (for example food adulteration) can lead to refunds and recalls; in food the focus is safety more than financial loss | [U-000] |

**Category note.** The input classes corruption and bribery as Hybrid; the baseline holds no fraud typology to compare (no conflict). The input classes identity and synthetic fraud as Hybrid in the typology table and the synthetic-identity chargeback technique as Hybrid in the emerging-techniques table (consistent).

### Q10.2 Documented fraud and related cases (as supplied)

| Case | Subsector | Country | Scheme | Perpetrator | Channel | Payment rail | Period | Detection | Loss | Recovery | Control or oversight failure | Enforcement outcome | Source (input's type) |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Rolls-Royce plc (historical) | Aerospace (engines) | UK, US, Brazil | Global bribery of intermediaries | Senior management | Various (correspondence) | International payments | 1989-2013 | Investigation by the UK fraud prosecution authority (SFO) after a Rolls-Royce self-report | GBP 671m total (as given: "RRA and DPA") | GBP 585m (SFO, US Department of Justice (DOJ), Brazilian Federal Prosecutor) | Supervision failure over payments to agents; ineffective compliance control | SFO DPA (2017); DOJ DPA (2017); Brazil agreements (2016) | [U-002] Reuters (first-hand) |
| Airbus SE (historical) | Aeronautics and aviation | France, UK, US | Widespread bribery | Senior management | Emails, contracts | Bank transfers and advances | 2001-2018 | UK, US and French authorities (six-year investigation) | EUR 3.6bn (fines and penalties) | About EUR 3bn paid (UK, France, US) | Use of local intermediaries without control; unclear compliance | DPAs in France, the UK and the US (2020) | [U-003] Washington Post (Reuters) |
| Iris Kim, Inc. (historical) | Defence parts manufacturing | US | Public-contract fraud | Owner and employees | False contracts | US Department of Defense (DoD) payments | 2011-2018 | Naval Criminal Investigative Service (NCIS) and DOJ investigation; indictment about 2018 | More than USD 7m | Not disclosed | False country of origin ("Made in USA"); false documents in the tender process | Owner sentenced to 58 months (2021) | [U-004] DOJ (primary) |
| Masimo Corporation | Medical devices | US | Cyber intrusion (account takeover) | Unknown | Internal portal | - | April 2025 | SEC Form 8-K report | Not disclosed | - | Unauthorised access to internal network; network operations centre (NOC) response; no preventive detection | Case ongoing | [U-012] Industrial Cyber (secondary) |
| Toshiba Corp. (historical) | Electronics and equipment | Japan | Accounting fraud (overstatement) | Management (CFO) | Financial reports | - | 2011-2014 | Internal audit (October 2015) | About USD 1.2bn inflated | - | Profit pressure; insufficient supervision of executives | Japanese regulator fines; resignation of top executives | [U-011] "[48]" (not listed) |
| Fairlife (Coca-Cola) | Food (dairy) | US | Cyberattack (IT exploitation) | Unidentified group | Production systems | - | July 2026 | Internal monitoring; immediate incident response | Not applicable (production stopped) | - | Unauthorised access to production systems | Under investigation; authorities notified (2026) | [U-005] Reuters |
| Nucor Corp. | Steel | US | Cyberattack (IT network) | Unknown | IT systems | - | May 2025 | SEC Form 8-K disclosure | Not applicable (partial stop) | - | Outsourced access; preventive interruption on detecting an anomaly | Investigation ongoing (2025) | [U-006] Industrial Cyber (SEC 8-K) |

**Rejected candidates (as supplied).** [U-000] Purely financial cases or cases without a direct manufacturing link were excluded. A growing deepfake and synthetic-voice pattern ("fake CEO") was considered, but no official documentation involving a manufacturer was found by the input's cut-off.

**Classification note (Judgement).** Masimo, Fairlife and Nucor appear in the input's fraud-case table but are cyber incidents with no fraud loss disclosed; this record maps them to Cyber / ICT (Q11) and Operational resilience (Q12) and keeps them here only as supplied. The fraud cases proper (Rolls-Royce, Airbus, Iris Kim, Toshiba) are all historical (before 2020 in period, with enforcement outcomes from 2016 to 2021). No in-period manufacturing fraud case is documented in either evidence set, and no EU or UK payment-diversion case is documented (gap).

**Baseline cross-reference.** [S-003] [S-004] JLR's manual invoice settlement during its outage and its supplier prepayment scheme show a period of abnormal supplier-payment processing after a cyber incident (Observed); the risk that such periods enable payment-diversion attempts is a Judgement, with no case evidenced.

### Q10.3 Quantitative evidence (as supplied)

| Source and study | Data type | Currency or unit | Period | Population or sample | Statistic | Observation | Input confidence | Notes | Source |
|---|---|---|---|---|---|---|---|---|---|
| FBI IC3 public service announcement (PSA) "The USD 26 Billion Scam" | BEC complaints | USD | 2013-2019 | Global IC3 complaints | 166,000 incidents; USD 26.2bn exposed losses (all industries) | All 50 US states and 177 countries | High | Shows BEC scale across all sectors; not segmented | [U-008] |
| Sophos 2023 (via WTW) | Ransomware survey | USD | 2022 | About 1,000 firms globally (input adds "65% manuf.") | 65% of manufacturers reported ransomware; 75% encryption; average recovery cost USD 1.67m | Market study (insured companies) | Medium | Insurer focus; self-reported | [U-007] |
| FBI IC3 Report 2023 (wire and ACH) | Wire-fraud complaints | USD | 2022 | US IC3 complaints | USD 3.1bn lost via BEC and fraudulent transfers in the US | - | Medium | BEC predominates (87% of the USD 1.6bn of fraudulent transfers); all industries | [U-000] (no source entry) |
| Cobalt State of Pentesting Report | Average days to remediate vulnerabilities | Days | 2023 report | Penetration-test matrix | Industry remediates in 122 days on average (longest among sectors) | Concentration in manufacturing | Low | Market research; not academic | [U-009] |
| Internal checks (for example ACFE) | Management fraud (industry) | USD or percent | 2018, 2020 | Investigated cases | Manufacturing about 15% of occupational fraud cases (ACFE) | Limited data | Low | Primary source not accessible (ACFE industry research) | [U-000] (no source entry) |

**Dataset-type rule.** Complaint (IC3), survey (Sophos) and investigated-case (ACFE) datasets measure different populations and are never combined. The USD 26.2bn and USD 3.1bn figures are all-industry figures, not manufacturing figures. The two IC3 statements (USD 3.1bn; 87% of USD 1.6bn) are reproduced as given; their relationship is not stated in the input (conflict E-11).

### Q10.4 Structural fraud exposure

| Feature | Applies? | Evidence (as supplied unless marked) |
|---|---|---|
| Payment intensity and supplier-payment volume | Yes | High volume of payment flows to global suppliers [U-000] |
| Supplier and subcontractor density | Yes | Globalised supplier and subcontractor density [U-000]; baseline: thousands of small suppliers on one OEM [S-010] |
| Intermediaries and agents | Yes | Bribery through local intermediaries and agents at Rolls-Royce and Airbus [U-002, U-003] |
| Public contracts, subsidies and tax rebates | Yes | Defence contract fraud (Iris Kim) [U-004]; subsidy and VAT fraud exposure [U-000]; EU public-procurement rules [U-013] |
| Decentralised operations and payment authority | Yes | Decentralised payment authorisations in multinational structures [U-000] |
| Physical inventory and equipment | Yes | Raw materials, finished goods and equipment susceptible to misappropriation [U-000] |
| Target and incentive pressure | Yes | Target and financial incentive pressure [U-000]; Toshiba profit pressure [U-011] |
| Executive exposure | Yes | High exposure of executive data (media, LinkedIn) used for spear-phishing [U-000] |
| Customer-facing payment flows | Limited | Chargeback and synthetic-identity fraud in loyalty or warranty credit programmes [U-000] |

### Q10.5 Controls, detection and governance failures (as supplied)

| Control failure | Source or observation | Notes | Input confidence |
|---|---|---|---|
| Authorisation of supplier bank-detail changes | General BEC cases: no dual verification (for example email only) | Procedure often informal, which facilitates payment diversion | High |
| Absence of segregation of duties | Corporate judgments (for example Rolls-Royce) and guidelines (SOX implicit) | Executives manipulating reports without review | Medium |
| Limited internal audit | Accounting investigations (Toshiba, Airbus): errors detected late | Weak internal controls delay identification of fraud | Medium |
| Weak supplier onboarding | Procurement fraud studies: insufficient document checks | Allows false or corrupt suppliers to be inserted | Medium |
| No ERP and portal monitoring | Masimo report (Industrial Cyber): internal network intrusion went unnoticed | Legacy system, no 24/7 monitoring | Medium |
| Ineffective whistleblowing intake | Little public sector information; SFO and SEC trends | Cultural barriers may hinder internal reporting | Low |

Sources: [U-000] [U-002] [U-003] [U-011] [U-012].

### Q10.6 Consequences

- **Direct losses** [U-000]: millions in documented incidents, plus investigation and remediation cost.
- **Liquidity** [U-000]: unplanned payments drain cash.
- **Earnings and fines** [U-000] [U-002] [U-003]: large DPAs affect EBITDA; Rolls-Royce paid GBP 585m and Airbus about EUR 3bn (historical).
- **Reputation and credit access** [U-000]: fraud scandals can affect mergers and acquisitions and access to credit.
- **Low proportional recovery** [U-000]: documented cases leave net losses.
- **Baseline cross-reference** [S-003] [S-010]: supplier-finance and receivables programmes are where supplier stress becomes visible (Judgement); a diverted supplier payment during an outage would surface in the same channels (Judgement).

### Q10.7 Rules and expectations (as supplied)

| Jurisdiction | Instrument | Type | Scope | Date or status | Areas affected and notes | Primary source (as named) |
|---|---|---|---|---|---|---|
| US | Foreign Corrupt Practices Act (FCPA) | Federal law (input: "1934") | Public and private companies | Effective since 1977 | Prohibits bribery of foreign officials; requires accounting controls; applies to global manufacturers listed in the US | DOJ and FBI (FCPA legislation) [U-013] |
| US | False Claims Act | Federal law (1863, recently amended) | Government contractors | Input: "Obama amendment 2010" | Penalises defrauding federal programmes; used in defence-contract and subsidy fraud cases | 31 USC 3729-3733 [U-013] |
| UK | Bribery Act 2010 | Law (2010) | Companies with a UK presence | In force (2011) | Three offences: active bribery, passive bribery and failure to prevent; broad reach including outsourced parties; Airbus DPA paid a record penalty | UK legislation [U-013] [U-003] |
| UK | Companies Act 2006 (sections 172-173) | Law (2006) | Companies incorporated in the UK | In force (2009) | Directors must act in the company's interest; used in governance-failure cases | UK legislation [U-013] |
| UK (as placed in the input) | Payment Services Regulations (PSD2) | EU regulation, transposed | Payment institutions | Applicable (EU: 2019) | Partial reimbursement of card and payment fraud victims; requires strong customer authentication | EU regulation (PSD2) [U-013] |
| UK | FCA and PRA (Bank of England) | Supervisory regulation | Banks and insurers | Ongoing guidance | Requires anti-fraud controls and adequate internal audit (for example PRA operational-risk guidance) | FCA and PRA guidance [U-013] |
| EU | NIS2 Directive | Directive (input: "binding law 2023") | Input: providers of essential infrastructure | Input: adopted 2022, transposition pending | Covers essential operators including manufacturing of high importance; mandatory cybersecurity requirements and incident notification | NIS2 Directive (EU 2022) [U-013] |
| EU | Whistleblowing Directive (EU) 2019/1937 | Directive (input: "mandatory for EUA 2021") | All large companies | Transposition 2021 | Requires secure reporting channels for irregularities including fraud and corruption; applies to manufacturers with more than 50 employees | Input: "EU Regulation (2019)" [U-013] |
| EU | Public procurement directives (for example Directive 2014/24/EU) | Directive and regulation | Public tenders | In force; transposed with deadlines | Integrity clauses and sanctions for fraud in public manufacturing contracts | Directive 2014/24/EU [U-013] |
| Brazil (example) | Anti-Corruption Law 12.846/2013 | Federal law | Large companies | In force (2014) | Holds companies liable for harmful acts against public administrations; increases accountability for bribery in manufacturing contracts | Brazilian Law 12.846/13 [U-013] |

**Baseline comparison.** [S-049] [S-051] [S-046] The baseline records NIS2 as in force since 16 January 2023 with a transposition deadline of 17 October 2024, Germany's law in force since 6 December 2025 and four Member States referred to the Court of Justice on 8 July 2026; it scopes manufacturing through named Annex I and II activities rather than as "essential infrastructure". Both descriptions are kept (conflict E-08). The input's FCPA date, PSD2 placement and Whistleblowing Directive wording are reproduced as supplied (conflicts E-09 and E-10). The UK failure-to-prevent-fraud offence under the Economic Crime and Corporate Transparency Act 2023 and payee-confirmation and reimbursement rules were not covered in either evidence set (gap).

### Q10.8 Emerging techniques (last 12 months and 30 days, as supplied)

| Technique | Case example or alert | Category | Channel | Control that interrupts it | Source |
|---|---|---|---|---|---|
| Voice or video deepfake (CFO/CEO) | Global attacks showed synthesised executive voices (for example a large German distributor, Q2 2023) | Cyber-enabled | Telephone or video (Zoom); requests for immediate transfer | Verification by code or physical contact with the real person | [U-000] |
| BEC via cloud email compromise | Groups exploit Office 365 and G Suite; recent cases in the automotive sector (account takeover via phishing and SIM swap) | Cyber-enabled | Business email (SaaS) | MFA and payment-account change policies independent of email | [U-000] |
| Supplier-portal takeover (ERP e-procurement) | Infiltration of SAP Ariba and supplier portals; industrial security alerts note growth in remote-access proxies | Cyber-enabled | Web-based ERP and procurement portals | Anomalous-login monitoring; separation of test and production environments | [U-000] |
| Customer-data fraud (chargeback) | Synthetic identities in loyalty programmes or warranty credits (for example a manufacturing fintech) | Hybrid | Email and customer portal | Strengthened checks of personal data before reversing payments | [U-000] |
| Supply-chain-targeted phishing | Recent reports (APWG 2026) indicate rising phishing that imitates key suppliers (electronic components) | Cyber-enabled | Business email, social networks | Staff training to identify false emails; domain authentication | [U-000] |
| Instant-payment scams | Abuse of PIX and instant-payment systems in Latin America (supply-chain fraud) | Cyber-enabled | Immediate transfer (PIX, SEPA Instant) | Additional review of non-recurring immediate transfers | [U-000] |

**Dating note.** The deepfake example is dated Q2 2023 and the typology screen cites a German case in 2020; neither is inside the stated 12-month window. The only 2026-dated item is the APWG 2026 reference, which has no source entry (gap).

**Preliminary inherent fraud exposure:** Medium (Provisional), confidence Medium (user-supplied rating).

## Q11 - Sector ICT exposure and cybersecurity maturity

| Item | Finding | Evidence | Label |
|---|---|---|---|
| Digital dependency | Intensive use of industrial automation (robots, internet of things (IoT)) and management systems (ERP, MES); growing IT/OT convergence; manufacturing leads in number of attacks (17-20% of reported cases globally in 2022) | [U-000] | User-supplied |
| Digital dependency (baseline) | Production release depends on ERP, MES and identity; plants stop when they stop | [S-001] [S-016] [S-027] [S-039] | Observed and Benchmark |
| Legacy IT/OT and cloud | Many SCADA systems on old Windows versions; partial migration to public cloud (Azure, AWS) for ERP and design; LockBit exploited VMware vulnerabilities used in factories in 2023 | [U-000] | User-supplied |
| Attack surface | Broad (control systems, corporate networks, connected devices); email authentication and corporate identities often insufficient (phishing); insurer reports: manufacturers paid millions in ransomware demands (average USD 2.4m), 60% pay | [U-000] | User-supplied |
| Attack surface (baseline) | Internet-exposed and end-of-life controllers; endpoint-management planes; exploitation of public-facing applications | [S-035] [S-025] [S-042] | Observed; Tier 3 for the last item |
| Cyber-enabled fraud attack surface | Compromised email used for payment instructions; ERP systems as secondary targets; high exposure of executive data | [U-000] [U-008] | User-supplied |
| Incident patterns | Ransomware, corporate phishing and network intrusion follow patterns similar to other sectors, but cause direct production stops (Fairlife, Nucor); 65% of manufacturers affected by ransomware against a 46% all-sector average | [U-005] [U-006] [U-007] | User-supplied |
| Incident patterns (baseline) | 25.2% of EU ransomware claims; about 65% of industrial ransomware incidents in Q2 2026; exfiltration 73.3% of technique observations | [S-041] [S-039] | Benchmark |
| Security maturity | Generally below the financial sector; little offensive testing; longer average patch time (122 days), the longest of any sector to remediate flaws | [U-000] [U-009] | User-supplied |
| Preparedness and detection | Frequent absence of an in-house SOC; reliance on MSPs or reactive response plans; penetration tests and red teaming rare; Nucor detected only after a significant incident; WTW: rising insurance take-up signals recognition of the need to invest | [U-000] [U-006] [U-007] | User-supplied |
| Recovery preparedness (baseline) | JLR about five weeks to restart production; Stryker about four weeks; Asahi recovery tail into 2026 | [S-005] [S-021] [S-018] | Observed |

**Analytical judgement.** Inherent ICT exposure is High: the sector combines IT/OT convergence, legacy control systems, broad attack surfaces and production that stops when enterprise IT stops. The user input and the baseline agree on direction; observed maturity is not measurable at sector level (no sector maturity survey in either set). Preliminary exposure: High (Provisional), confidence Medium (user-supplied rating).

## Q12 - Operational resilience and third-party concentration

### Q12.1 Documented disruptions

Baseline cyber disruptions: JLR, Asahi, Stryker, Boston Scientific, West Pharmaceutical, Egide, Hasbro, RTX product outage, refrigeration controllers [S-001, S-016, S-021, S-027, S-030, S-034, S-031, S-037, S-035]. User input: Fairlife (production halted at US plants, July 2026) [U-005]; Nucor (temporary partial stop of steel operations, May 2025) [U-006]. The input also mentions a global supply-chain interruption through a software failure on a logistics platform, flagged in the input itself as "(NASA/Boeing hack? limited)"; it is recorded as unconfirmed and not used as evidence.

### Q12.2 Essential operational functions and dependencies (as supplied)

1. Continuous processes: 24/7 assembly lines [U-000].
2. Single suppliers: key raw materials and highly specialised tier-1 suppliers [U-000].
3. Concentration in few global suppliers: semiconductors and SaaS ERP [U-000].
4. Essential infrastructure: energy and logistics [U-000].

### Q12.3 Dependency and concentration matrix

| Dependency category | Concentration or single-point risk | Operational effect of failure | Substitutability | Source |
|---|---|---|---|---|
| Enterprise IT releasing production (ERP, MES, identity) | Single instance per group | Precautionary plant stops | Low during an incident | Baseline [S-001] [S-016] [S-027] |
| SaaS ERP and cloud | Concentration in few global providers | Production scheduling and order-to-cash halted | Not evidenced | User-supplied [U-000]; baseline Scenario 1 |
| Semiconductors and specialised tier-1 parts | Single or few sources | Line stops for downstream manufacturers | Not evidenced | User-supplied [U-000] |
| Key raw materials | Single suppliers | Production halt | Not evidenced | User-supplied [U-000] |
| Endpoint and identity administration planes | One tool reaches every device | Global device loss | Not evidenced | Baseline [S-023] [S-025] |
| OT vendors' installed base | One product family across many sites | Fleet-wide remediation | Not evidenced | Baseline [S-035] |
| Integrators and managed IT providers (MSPs) | One provider's access reaches several plants | Partial site stops | Not evidenced | Baseline [S-034] [S-039]; user input: reliance on MSPs [U-000] |
| Just-in-time supplier tiers | Thousands of suppliers on one OEM | Supplier idling and liquidity stress | Not applicable | Baseline [S-010] |
| Energy and logistics | Shared infrastructure | Plant and delivery stops | Not evidenced | User-supplied [U-000] |

Market shares per supplier are not public in either evidence set [U-000]; no provider is described as dominant.

### Q12.4 Disruption durations and losses

| Indicator | Value | Source type |
|---|---|---|
| JLR production halt | About five weeks; normal by mid-November 2025; distribution later | Tier 1 [S-005] [S-006] |
| Stryker restoration | About four weeks (11 March to 9 April 2026) | Tier 1 [S-021] |
| Asahi | Brewery sales at 84% of prior year in January-March 2026 | Tier 1 [S-018] |
| Boston Scientific | Manufacturing resumed at most facilities by 8 September 2026 | Tier 1 [S-027] |
| Fairlife | Production halted; duration not stated | User-supplied [U-005] |
| Nucor | Partial stop; duration not stated | User-supplied [U-006] |
| Supplier cascade | Over 5,000 UK organisations (modelled) | Benchmark [S-010] |

The input states that consolidated data on duration and losses are generally lacking [U-000]; this matches the baseline finding that only listed companies disclose.

### Q12.5 Consequences, continuity and propagation

- **Consequences (as supplied)** [U-000]: direct costs of idle lines; delivery delays and lost revenue; cascade effects on customers' balance sheets; excess or short inventory affecting working capital; extra capital expenditure on resilience (duplication and backup).
- **Propagation (baseline)**: [S-010] one OEM stop to thousands of suppliers; [S-035] one product family to many sites; [S-037] one product incident to customers in other sectors.
- **Limiting conditions (baseline)**: [S-021] segmentation; buffered inventory and multi-sourcing; [S-035] removal of internet exposure; [S-003] supplier prepayment.
- **Fraud through third parties (as supplied)** [U-000]: fraudulent supplier onboarding touches Fraud; third-party disruptions are cyber-operational rather than direct fraud.

**Preliminary exposure:** Medium (Provisional), confidence Low per the input's matrix or Medium per its executive summary (user-supplied rating; conflict E-01). The baseline migrated edition rated this dimension High (conflict E-02).

## Q13 - Governance structure and operating-model complexity

**Operating models (as supplied).**
- **Multinational manufacturers:** parent plus subsidiaries in several countries, joint ventures and extensive outsourcing, requiring rigorous controls [U-000].
- **Outsourced and contract manufacturing:** OEM and contract-manufacturing models in global supply chains [U-000].
- **Subsidiaries:** internal-control policies vary; payment authorisations are decentralised; audit and whistleblowing practices are not always robust [U-000].

**Governance failures and control deficits.**

| Governance category | Observed weakness | Effect on fraud and operational risk | Reference case |
|---|---|---|---|
| Oversight of intermediaries and agents | Supervision failures over chains of intermediary agents | Large DPAs and fines (historical) | Rolls-Royce, Airbus [U-002] [U-003] |
| Internal control and financial reporting | Profit pressure; insufficient supervision of executives | Accounting fraud; executive resignations; regulator fines | Toshiba (2015) [U-011] |
| Failure-to-prevent liability | UK Bribery Act failure-to-prevent offence | Record penalty in the Airbus DPA | Airbus [U-003] [U-013] |
| Compliance programmes | Anti-corruption and SOX-equivalent compliance still evolving | Exposure under FCPA, Bribery Act and Brazilian law | [U-013] |
| Whistleblowing | Cultural barriers; channels not always robust in subsidiaries | Late detection | [U-000] |
| Decision-making in incidents | Fragmented processes may slow incident response | Higher incident cost | [U-000] |
| Cybersecurity accountability (baseline) | NIS2 requires management bodies to approve and oversee cybersecurity measures and follow training, where the entity is in scope | Personal accountability in scope entities | [S-049] |
| Defence supply-chain flow-down (baseline) | MOD Cyber Security Model requires controls flowed down to subcontractors | Contractual governance reach | [S-081] |
| Board disclosure (baseline) | SEC Item 1.05 and Item 106 require material-incident and annual governance disclosure | Source of most quantified incident evidence | [S-083] |

**Offsets (as supplied).** [U-000] Legal mechanisms (UK and US anti-bribery law, financial controls) are broad, and there is no evidence of universal inherent weakness; governance varies greatly by company.

**Analytical judgement.** Complexity is concentrated in multinational structures, joint ventures, intermediaries and decentralised payment authority. Documented governance failures are historical enforcement cases at very large firms; there is no in-period governance case and no evidence on internal-audit coverage at mid-market manufacturers. Complexity is not treated as evidence of weak governance. Preliminary exposure: Medium (Provisional), confidence Low (user-supplied rating).

## Q14 - Cross-sector comparative analysis

**Position of the user input.** [U-000] The input states that a formal comparison with other sectors (for example percentage of companies attacked or percentage of revenue lost) is lacking and that insurer and IC3 sources do not separate manufacturing (User-supplied). It nevertheless supplies four comparative indicators, listed below.

| Dimension | Comparator | Dataset type | Manufacturing position | Limitation | Source |
|---|---|---|---|---|---|
| Cyber / ICT | Share of surveyed firms reporting ransomware | Survey (Sophos 2023 via WTW) | 65% against a 46% all-sector average | Self-reported; insurer focus | [U-007] (User-supplied) |
| Cyber / ICT | Share of reported attack cases globally, 2022 | "Market studies" | 17-20%, leading sector | No source entry | [U-000] (User-supplied) |
| Cyber / ICT | Average time to remediate vulnerabilities | Penetration-test dataset (Cobalt 2023) | 122 days, longest among sectors | Market research; low confidence | [U-009] (User-supplied) |
| Cyber / ICT | Security maturity relative to financial sector | Qualitative statement | Below the financial sector | No dataset named | [U-000] (User-supplied) |
| Fraud | Share of occupational fraud cases | Investigated cases (ACFE 2018, 2020) | About 15% | Primary source not accessible; low confidence | [U-000] (User-supplied) |
| Cyber / ICT (baseline) | Share of EU incidents and of ransomware claims, 2025 | Institutional analysis (ENISA) | Fourth by incidents (6.9%); first by ransomware claims (25.2%) | Claim-based visibility | [S-041] |
| Cyber / ICT (baseline) | Share of industrial ransomware incidents, Q2 2026 | Vendor dataset (Dragos) | About 65% of 1,140 | Industrial sectors only | [S-039] |
| Cyber / ICT (baseline) | Most attacked industry, 2025 | Vendor incident-response dataset relayed by trade media | First | Tier 3 relay | [S-042] |
| Operational resilience | No comparable duration or concentration indicator | - | Not assessable comparatively | Gap | - |
| Governance | No comparable complexity indicator | - | Not assessable comparatively | Gap | - |

**Comparability notes (Judgement, not validation).** The 65% figures from Sophos (share of surveyed manufacturers) and Dragos (share of industrial incidents) are different statistics and are not compared. Survey, claim-based and investigated-case datasets are not combined. No 24-sector comparison universe is available; ratings are not calibrated against peer sectors (gap).

---

# Part C - Synthesis

## Q15 - Four-dimension classification (detail)

Ratings are reproduced as proposed in the user input. Drivers and evidence combine both sets; neither set changes another's rating.

### Fraud - Medium (Provisional), confidence Medium
- **Drivers:** (1) high supplier-payment volumes to global suppliers [U-000]; (2) supplier and subcontractor density [U-000, S-010]; (3) intermediaries and agents in international contracts [U-002, U-003]; (4) public contracts, subsidies and tax rebates [U-004, U-000]; (5) decentralised payment authority [U-000]; (6) physical inventory and equipment [U-000]; (7) target and incentive pressure [U-000, U-011].
- **Strongest evidence (all historical):** Rolls-Royce bribery (1989-2013; GBP 671m total; DPAs 2017) [U-002]; Airbus bribery (2001-2018; DPAs 2020) [U-003]; Iris Kim procurement fraud (more than USD 7m; 58-month sentence 2021) [U-004]; Toshiba accounting overstatement (about USD 1.2bn) [U-011].
- **Cyber / non-cyber split:** cyber-enabled and hybrid (payment diversion, BEC, supplier and executive impersonation, ERP or portal takeover) and non-cyber (insider fraud, asset misappropriation, accounting fraud, corruption, subsidy and tax fraud) are both present; material typologies are payment diversion, BEC, invoice and procurement fraud, insider fraud, asset misappropriation and corruption [U-000].
- **Datasets:** IC3 BEC USD 26.2bn 2013-2019 (complaints, all industries) [U-008]; ACFE about 15% of occupational fraud cases (investigated cases; low confidence) [U-000].
- **Consequences:** direct losses, liquidity, EBITDA effects of fines, reputation and credit access, low recovery [U-000].
- **Limitations:** no sector loss statistics; no in-period or EU/UK manufacturing fraud case; small internal frauds unquantified [U-000].

### Cyber / ICT - High (Provisional), confidence Medium
- **Drivers:** IT/OT integration and automation [U-000]; global connectivity, cloud ERP and APIs [U-000]; legacy heterogeneous systems [U-000]; executive exposure to spear-phishing [U-000]; production release dependent on enterprise IT [S-001, S-039]; internet-exposed controllers [S-035].
- **Evidence:** Sophos 2023 65% ransomware, 75% encryption, USD 1.67m recovery [U-007]; Fairlife, Nucor [U-005, U-006]; JLR, Asahi, Stryker, Boston Scientific [S-001, S-016, S-021, S-027]; ENISA 25.2% of EU ransomware claims [S-041]; Dragos about 65% of industrial ransomware [S-039].
- **Consequences:** lost production revenue; mitigation cost; potential physical damage via control systems; liquidity and value effects [U-000]; JLR GBP 260m costs and GBP 1.5bn quarterly cash outflow (mixed causes) [S-004, S-006].
- **Limitations:** few comparative sector studies; non-disclosure [U-000]; no sector maturity survey.

### Operational resilience / TPRM - Medium (Provisional), confidence Low (matrix) / Medium (summary)
- **Drivers:** continuous 24/7 processes; single suppliers; concentration in semiconductors and SaaS ERP; energy and logistics dependence [U-000]; just-in-time supplier tiers [S-010].
- **Evidence:** Fairlife and Nucor production stops [U-005, U-006]; JLR cascade, supplier prepayment and state-guaranteed loan [S-010, S-003, S-009].
- **Consequences:** idle-line cost, delivery delays, cascade to customers, working-capital swings, resilience capital expenditure [U-000].
- **Limitations:** scarce quantitative disruption data; no concentration statistics [U-000]; supplier-level losses and insolvencies not evidenced [S-047].
- **Conflicts:** confidence differs within the input (E-01); the baseline migrated rating was High (E-02).

### Governance / operating model - Medium (Provisional), confidence Low
- **Drivers:** multinational structures and joint ventures; variable internal controls; decentralised payment authorisation; evolving compliance; uneven subsidiary audit and whistleblowing [U-000].
- **Evidence:** Rolls-Royce and Airbus intermediary oversight failures [U-002, U-003]; Toshiba [U-011]; UK Bribery Act failure to prevent [U-003, U-013]; baseline NIS2 management-body duties and MOD flow-down [S-049, S-081].
- **Offsets:** broad anti-bribery and financial-control law; no evidence of universal weakness [U-000].
- **Limitations:** case-specific public records only; governance cause hard to isolate without internal analysis [U-000].

**Rating sensitivity (Judgement).** The input supplies no movement triggers. Sector ratings would change only with sector evidence, for example: a manufacturing-cut loss dataset or an in-period EU or UK payment-diversion case (Fraud); a sector maturity survey or normalised incident rates (Cyber / ICT); quantified durations and supplier market shares, or official evidence of cyber-caused supplier insolvency (Operational resilience); internal-audit coverage data for mid-market manufacturers (Governance).

## Q08 - Questionnaire mapping and Credit Officer engagement (Provisional)

No questionnaire item list was supplied; identifiers use the PROV- prefix and are placeholders, not questionnaire items. PROV-01 to PROV-07 come from the migrated edition; PROV-08 to PROV-11 are added from the user input's borrower questions. Borrower answers are self-reported, are not confirmed evidence and never trigger an automatic adverse credit judgement.

| PROV ID and topic | Threat and evidence | Operational -> credit consequence | Suggested client questions | Materiality factors |
|---|---|---|---|---|
| PROV-01 Production without IT | P1; JLR, Asahi [S-001, S-016]; ERP and cloud key-supplier dependency [U-000] | Plants stop -> revenue and cash loss | Can you release production and ship without ERP, MES and identity services for two weeks? How mature are continuity plans for key software and cloud suppliers? | Just-in-time versus buffered production |
| PROV-02 Administrative tool controls | P2; Stryker (media-reported) [S-023] | All devices lost -> global stop | Do destructive administrative actions need a second approver? | Number of sites on one administrative plane |
| PROV-03 Customer and supplier concentration | Cascade; JLR, CMC model [S-010, S-003]; single suppliers [U-000] | Customer or supplier stop -> receivables and liquidity stress | What share of revenue comes from your largest customer, which single suppliers could stop you, and how many weeks of stop could you finance? | Customer concentration; liquidity headroom |
| PROV-04 Installed-base exposure | P3; refrigeration controllers [S-035] | Fleet compromise -> remediation and liability | Do you track internet exposure and end-of-support status of products you have sold? | Installed-base size; product field life |
| PROV-05 Provider remote access | P4; Egide [S-034]; reliance on MSPs [U-000] | Provider compromise -> partial site stop | Is provider remote access to OT restricted and logged? Do you run an in-house or outsourced SOC? | Outsourced IT and OT services |
| PROV-06 Product-law readiness | Reporting and liability rules [S-057, S-066] | Non-compliance -> liability and market access | How do you meet product vulnerability reporting that began in September 2026? | Products with digital elements sold in the EU |
| PROV-07 Insurance and contracts | Customer-side gap [S-010] | Uninsured loss -> margin and covenant pressure | Does your cyber cover include disruption at a key customer? | Cover terms |
| PROV-08 Supplier bank-detail change control | Payment diversion, BEC [U-000, U-008]; informal change procedures [U-000] | Diverted payments -> cash loss | What dual-authorisation and call-back controls apply to supplier bank-detail changes, and how are financial duties segregated (sample-tested)? | Payment volume; supplier churn |
| PROV-09 Email authentication and MFA | Cloud email BEC; supply-chain phishing [U-000] | Account compromise -> fraud and intrusion | Is email domain authentication in place and MFA enforced, including for ERP and supplier portals? | Use of cloud email and portals |
| PROV-10 Anti-corruption and intermediary oversight | Rolls-Royce, Airbus [U-002, U-003]; Bribery Act, FCPA [U-013] | Bribery -> fines, debarment, reputation | How are agents and intermediaries selected, monitored and audited, and how is anti-corruption compliance tested? | Public-sector and export contract share |
| PROV-11 Internal audit and whistleblowing | Toshiba, Airbus late detection [U-011, U-003]; whistleblowing duties [U-013] | Late detection -> restatement and fines | What internal-audit coverage exists in subsidiaries, and are reporting channels secure, anonymous and followed up? | Number and spread of subsidiaries |

**Early-warning indicators.** Production-pause notices, exchange filings or material-incident reports by large manufacturers [S-021, S-027]; national CERT or joint government alerts naming an OT product family or administrative tool [S-035, S-025]; supplier short-time work, lay-off or insolvency announcements linked to a customer's incident [S-047]; requests for state support [S-009]; enforcement actions or DPAs against manufacturers for bribery or procurement fraud [U-002, U-003, U-004]; legal milestones (UK Bill Royal Assent, Product Liability Directive transposition, first CRA enforcement, NIS2 Court rulings) [S-075, S-067, S-057, S-051].

**Specialist referral triggers (Judgement).** No tested production release without IT; destructive administrative actions without a second approver; supplier bank-detail changes accepted by email alone; reliance on intermediaries without documented due diligence; a disruption of four to eight weeks that would cross a covenant or contractual milestone.

## Q09 - Final synthesis and report assembly

**Sector narrative.** Manufacturing combines IT/OT convergence, legacy control systems and just-in-time supply chains. In the baseline period, production losses ran mainly through enterprise IT that releases production, with financial effects arriving through lost output, working capital, supplier liquidity and, in the JLR case, state-backed lending. The user input adds a fraud and governance layer: payment diversion and BEC risk from high supplier-payment volumes, and historical bribery, procurement and accounting fraud at large multinationals that exposed weak oversight of intermediaries and executives.

**Credit relevance.** Inherent exposure is High on Cyber / ICT and Medium on Fraud, Operational resilience / TPRM and Governance, all Provisional (user-supplied ratings). Borrower materiality depends on production release without IT, customer and supplier concentration, liquidity headroom for a four- to eight-week stop, installed-base exposure for equipment makers, supplier-payment controls and intermediary oversight.

**Assembly map for a future full report (11 fixed headings).**

| Report heading | Sections of this record |
|---|---|
| Executive Sector Assessment | B, C, Q15 |
| Sector Operating Model & Dependencies | Q01, Q12.2-Q12.3 |
| Cyber Threat Landscape & Attack Scenarios | Q03, Q05 scenarios, Q10.8 |
| Geopolitical Cyber Exposure | Q07 |
| Major Cyber Incidents & Case Studies | Q02, D, Q10.2 |
| Control Weaknesses & Resilience Priorities | Q04, Q10.5, Q11 |
| Regulatory & Supervisory Resilience Expectations | Q06, Q10.7 |
| Operational & Financial Consequences and Credit Transmission | Q05, Q10.6, Q12.4-Q12.5 |
| Questionnaire Mapping & Credit Officer Engagement | Q08 |
| Methodology, Confidence & Limitations | 0, E, F, I |
| References | G1, G2 |

**Product scope of this update.** Research record only; no slide deck, report re-issue or evidence annex was produced, at the user's request.

---

## D. Unified event register (one event, one record)

| ID | Event | Subsector and country | Date | Type | Baseline record | User-input record | Status in this record |
|---|---|---|---|---|---|---|---|
| EV-01 | Jaguar Land Rover shutdown | Automotive; UK, Slovakia | From September 2025 | Cyber, production stop | Top 5 no. 1 and case study [S-001 to S-015] | Not mentioned | Named incident |
| EV-02 | Asahi Group ransomware | Beverages and food; Japan | From 29 September 2025 | Cyber, production stop | Top 5 no. 2 [S-016 to S-020] | Not mentioned | Named incident |
| EV-03 | Stryker global IT disruption | Medical devices; global | From 11 March 2026 | Cyber, production stop | Top 5 no. 3 [S-021 to S-025] | Not mentioned | Named incident |
| EV-04 | Boston Scientific outage | Medical devices; global | From 25 August 2026 | Cyber, production stop | Top 5 no. 4 [S-026 to S-029] | Not mentioned | Named incident |
| EV-05 | Refrigeration controller compromise | OT equipment makers; France | 11-13 October 2026 | Cyber, product fleet | Top 5 no. 5 [S-035] [S-036] | Not mentioned | Named incident |
| EV-06 | West Pharmaceutical Services | Pharmaceutical components; global | May 2026 | Cyber, production stop | Considered [S-030] | Not mentioned | Pattern evidence |
| EV-07 | Egide | Aerospace and defence components; France | 6-9 October 2026 | Cyber via IT provider | Considered [S-034] | Not mentioned | Pattern evidence |
| EV-08 | Hasbro | Consumer goods; US | March 2026 | Cyber, order and shipping delays | Considered [S-031] [S-032] | Not mentioned | Context |
| EV-09 | RTX passenger-processing product | Aerospace product; Europe | September 2025 | Cyber, product outage at customers | Considered [S-037] | Not mentioned | Cross-sector analogue |
| EV-10 | Fairlife (Coca-Cola) production halt | Dairy; US | July 2026 | Cyber, production stop | Considered, Tier 3 only [S-033] | Reuters, 16 July 2026 [U-005] | Recorded from both sets; not a named incident (E-04) |
| EV-11 | Bridgestone Americas incident | Tyres; US | September 2025 | Cyber | Considered, Tier 3 only [S-038] | Not mentioned | Context |
| EV-12 | LockBit against manufacturers incl. Bridgestone | Tyres and others | 2021-2023 | Cyber, ransomware campaign | Not mentioned | Matrix C and section B [U-000] | Historical; distinct from EV-11 (E-05) |
| EV-13 | German textile finisher insolvency | Textiles; Germany | 2026 | Cyber-linked insolvency (media) | Considered, Tier 3 only [S-048] | Not mentioned | Context |
| EV-14 | Nucor operations pause | Steel; US | May 2025 | Cyber, partial stop | Not mentioned | Industrial Cyber citing Form 8-K [U-006] | Before the baseline period; Q11-Q12 evidence (E-06) |
| EV-15 | Masimo intrusion | Medical devices; US | April 2025 | Cyber, account takeover | Not mentioned | Industrial Cyber (no source entry) [U-012] | Before the baseline period; Q10.5 and Q11 evidence |
| EV-16 | Honda global stop | Automotive; global | 2021 (as supplied) | Cyber, production stop | Not mentioned | Matrix C and section B [U-000] | Historical; no source entry |
| EV-17 | LockBit exploitation of VMware in factories | Manufacturing generally | 2023 | Cyber, vulnerability exploitation | Not mentioned | Section E [U-000] | Historical pattern; no source entry |
| EV-18 | Rolls-Royce bribery | Aerospace; UK, US, Brazil | 1989-2013; DPAs 2017 | Fraud (corruption) | Not mentioned | [U-002] [U-010] | Historical fraud case |
| EV-19 | Airbus bribery | Aeronautics; France, UK, US | 2001-2018; DPAs 2020 | Fraud (corruption) | Not mentioned | [U-003] [U-010] | Historical fraud case |
| EV-20 | Iris Kim procurement fraud | Defence parts; US | 2011-2018; sentence 2021 | Fraud (procurement) | Not mentioned | [U-004] | Historical fraud case |
| EV-21 | Toshiba accounting fraud | Electronics; Japan | 2011-2014; audit 2015 | Fraud (financial statements) | Not mentioned | [U-011] | Historical fraud and governance case |
| EV-22 | German executive voice deepfake | Not manufacturing-specific; Germany | 2020 and Q2 2023 (as supplied) | Fraud (impersonation) | Not mentioned | [U-000] | Technique example; dating unclear (E-12) |

---

## E. Conflict register (shown, not resolved)

| ID | Topic | Baseline (File A) | User input (File B) | Treatment |
|---|---|---|---|---|
| E-01 | Operational resilience / TPRM confidence | - | Executive summary: Medium; rating matrix: Low | Both shown; the input's two values are not reconciled |
| E-02 | Operational resilience / TPRM rating | Migrated edition 1.0-M: High (Provisional, Medium) | Medium (Provisional) | User-input rating used for Q15, as instructed; migrated rating kept in the change log |
| E-03 | Fraud and Governance ratings | Migrated edition: Not assessable | Medium and Medium | User-input ratings used; the baseline had no Q10 or Q13 research |
| E-04 | Fairlife source quality | Tier 3 (Cybersecurity Dive) only; excluded as a named incident | Reuters, described as first-hand, high confidence | Baseline top five unchanged; user source not reviewed |
| E-05 | Bridgestone | Bridgestone Americas incident, September 2025 (Tier 3) | LockBit against manufacturers including Bridgestone, 2021-2023 | Treated as two events (EV-11, EV-12) |
| E-06 | Nucor and Masimo period | Baseline reporting period starts 1 September 2025 | Events dated May 2025 and April 2025 | Kept as user-supplied evidence outside the baseline period |
| E-07 | "65%" statistics | Dragos: manufacturing about 65% of industrial ransomware incidents, Q2 2026 | Sophos via WTW: 65% of surveyed manufacturers reported ransomware, 2022 | Different statistics; never compared or combined |
| E-08 | NIS2 description | In force 16 January 2023; transposition deadline 17 October 2024; German law in force; four Member States referred; manufacturing scoped by named Annex I and II activities | "Binding law 2023"; adopted 2022, transposition pending; covers essential operators including manufacturing of high importance | Both kept; each statement carries its own reference |
| E-09 | FCPA dates | - | "Federal law (1934)" and "effective since 1977" in the same row | Reproduced as supplied |
| E-10 | PSD2 and Whistleblowing Directive wording | - | PSD2 placed under the UK and described as an EU regulation; Whistleblowing Directive described as "mandatory for EUA 2021" and sourced as an "EU Regulation (2019)" | Reproduced as supplied; "EUA" is the Portuguese abbreviation for the US and may be a typing slip for the EU (Judgement, not corrected) |
| E-11 | IC3 2022 figures | - | USD 3.1bn lost via BEC and fraudulent transfers; BEC 87% of USD 1.6bn of fraudulent transfers | Reproduced as supplied; relationship not stated |
| E-12 | Deepfake case dates | - | German case in 2020 (typology) and a large German distributor in Q2 2023 (emerging techniques) | Kept as two references; not confirmed as one or two events |
| E-13 | Rolls-Royce amounts | - | GBP 497m DPA (matrix); GBP 671m total and GBP 585m recovered (case table) | All three shown with their own labels |
| E-14 | Airbus amounts and currency | - | USD 4bn DPA (matrix and source 3 title); EUR 3.6bn fines and about EUR 3bn paid (case table) | All shown; currencies not converted |
| E-15 | Reference "[48]" | S-048 is CircleID on a German textile finisher | "[48]" cited for Toshiba, not in the input's source list | Recorded as U-011; not linked to S-048 |
| E-16 | Geography emphasis | EU, EEA and UK primary | Global with US, UK and EU attention | Both kept; each section states its basis |
| E-17 | Cut-off | 16 October 2026 | "Up to October 2026" | Each governs the statements drawn from its own set |

---

## F. Gaps, limitations and NEEDS_REVIEW items

1. **User-supplied information not validated** (U-000 to U-013), at the user's instruction. Several material figures have no source entry in the input (average ransom USD 2.4m and 60% payment rate; 17-20% share of attacks in 2022; IC3 2023 figures; ACFE about 15%; LockBit VMware exploitation; Honda 2021; APWG 2026; Masimo; Toshiba). They should be confirmed against primary reports before external use (analyst note; no content changed).
2. **Fraud:** no sector-specific fraud loss statistics; all documented fraud cases are historical and concern very large aerospace, defence or electronics firms; no in-period, EU or UK payment-diversion case; no manufacturing deepfake case; small internal frauds unquantified [U-000].
3. **Operational resilience:** no consolidated duration or loss data beyond listed companies; no supplier market-share or concentration statistics; supplier insolvencies caused by cyber incidents not evidenced [U-000, S-047]; the 1-week band and the supply-chain concentration band have no duration evidence.
4. **Governance:** limited manufacturing-specific evidence; no internal-audit coverage data for mid-market firms; governance cause hard to isolate without internal analysis [U-000].
5. **Cross-sector comparison (Q14):** no formal comparison in either set; comparative items use different datasets; no 24-sector universe; ratings uncalibrated.
6. **Q07 geopolitical:** fragments only; the user input adds no state-linked cyber evidence.
7. **30-day windows:** nothing after 16 October 2026 was researched for Q01-Q07; the user input dates no named event in its last-30-days window.
8. **Case studies:** only one detailed reconstruction (JLR); second and third case studies not produced.
9. **Regulation:** UK failure-to-prevent-fraud offence (Economic Crime and Corporate Transparency Act 2023), payee-confirmation and reimbursement rules, and the regimes named but not assessed in Q06 were not reviewed; fraud-rule rows rest on the user input.
10. **Reporting bias:** large firms disclose; small and medium-sized manufacturers may not, which understates frequency [U-000].
11. **Fast change:** emerging AI-enabled techniques and new regulation may change exposure faster than evidence matures [U-000].
12. **No approved rubric or questionnaire:** ratings and mapping are Provisional.
13. **Classification marking** not specified.

---

---
## G. Source list

### G1. Public sources from the baseline edition (accessed 16 October 2026)

Titles are given by their citation label; full original titles, methodology, limitations and relevance notes are held in the baseline source register (`02_source_register.csv`). Source numbers [n] in the baseline report correspond to S-0nn here. S-085 is held in the baseline register but is not cited in the baseline report body or in this record.

| ID | Source (citation label) | Publisher | Published (basis) | Tier | Temporal class | Locator | URL |
|---|---|---|---|---|---|---|---|
| S-001 | JLR - Statement on cyber incident, 2 September 2025 | Jaguar Land Rover Automotive plc | 2025-09-02 (exact) | 1 | H2_prior | Statement body (single statement dated 2 September 2025) | https://media.jlr.com/corporate/news/2025/09/statement-cyber-incident |
| S-002 | JLR - Q2 FY26 volumes release | Jaguar Land Rover Automotive plc | 2025-10-07 (exact) | 1 | H2_prior | Volume summary and CEO statement | https://media.jlr.com/corporate/news/2025/10/jlr-volumes-down-challenging-quarter |
| S-003 | JLR - Restart and supplier financing release | Jaguar Land Rover Automotive plc | 2025-10-07 (exact) | 1 | H2_prior | Restart sequence paragraphs; supplier financing scheme section | https://media.jaguarlandrover.com/news/2025/10/jlr-restarts-manufacturing-and-introduces-new-financing-solution-pay-jlr-suppliers |
| S-004 | JLR - Q2 FY26 results release | Jaguar Land Rover Automotive plc | 2025-11-14 (exact) | 1 | H2_prior | Headline summary; exceptional items paragraph; cash and liquidity section; outlook | https://media.jlr.com/corporate/news/2025/11/jlr-performance-impacted-challenging-quarter |
| S-005 | JLR - Q3 FY26 volumes release | Jaguar Land Rover Automotive plc | 2026-01-05 (exact) | 1 | current | Headline volumes; regional table; cyber incident statements | https://www.jlr.com/news/2026/01/jlr-q3-sales-impacted-cyber-incident-previously-indicated |
| S-006 | JLR - Q3 FY26 results release | Jaguar Land Rover Automotive plc | 2026-02-05 (exact) | 1 | current | Financial summary; exceptional items; liquidity; recovery status | https://media.jlr.com/corporate/news/2026/02/jlr-q3-performance-impacted-previously-indicated-challenges |
| S-007 | TMPV - Q4 FY26 results release | Tata Motors Passenger Vehicles Ltd | 2026-05-14 (exact) | 1 | current | JLR revenue, PBT, free cash flow and liquidity paragraphs | https://cars.tatamotors.com/article/press-release/tmpv-consolidated-q4fy26-results.html |
| S-008 | JLR - Annual Report 2026 web summary | Jaguar Land Rover Automotive plc | undated (undated) | 1 | contextual | Chairman and CEO statements on the cyber incident | https://www.jlr.com/annual-report-2026 |
| S-009 | UK Government - JLR loan guarantee | UK Government (Department for Business and Trade, HM Treasury, UK Export Finance) | 2025-09-28 (exact) | 1 | H2_prior | Release body and notes to editors (EDG description, five-year term, supply-chain purpose, 34,000 direct and about 120,000 supply-chain jobs) | https://www.gov.uk/government/news/government-backs-jaguar-land-rover-with-15-billion-loan-guarantee |
| S-010 | CMC - JLR categorisation statement | Cyber Monitoring Centre (CMC) | 2025-10-22 (exact) | 2 | H2_prior | Summary; Category 3 criteria; loss components 1-6; limitations; insurance and government-support sections | https://cybermonitoringcentre.com/2025/10/22/cyber-monitoring-centre-statement-on-the-jaguar-land-rovercyber-incident-october-2025/ |
| S-011 | ONS - GDP monthly estimate, September 2025 | Office for National Statistics (ONS) | 2025-11-13 (exact) | 1 | H2_prior | Main points; production section on manufacture of motor vehicles (fall of 28.6%, -0.17 percentage-point contribution) | https://www.ons.gov.uk/economy/grossdomesticproductgdp/bulletins/gdpmonthlyestimateuk/september2025 |
| S-012 | SMMT - September 2025 vehicle output | Society of Motor Manufacturers and Traders (SMMT) | 2025-10-24 (exact) | 2 | H2_prior | Headline figures for car and commercial vehicle output; chief executive statement | https://www.smmt.co.uk/cyber-attack-hits-vehicle-output-with-new-risk-arising-from-tax-charge-on-auto-workers/ |
| S-013 | Bank of England - Monetary Policy Report, November 2025 | Bank of England | 2025-11 (month_only) | 1 | H2_prior | Section 1.2 Activity, headline GDP growth paragraph | https://www.bankofengland.co.uk/monetary-policy-report/2025/november-2025 |
| S-014 | Business and Trade Committee - Letter to JLR, 9 September 2025 | House of Commons Business and Trade Committee | 2025-09-09 (exact) | 1 | H2_prior | Letter body (15 questions; response requested by 19 September 2025) | https://committees.parliament.uk/publications/49443/documents/263268/default/ |
| S-015 | ITV - JLR claim of responsibility report | ITV News | 2025-09-04 (exact) | 3 | H2_prior | Article body: Telegram claim, JLR and NCA statements | https://www.itv.com/news/central/2025-09-04/m-and-s-hackers-claim-to-be-behind-jaguar-land-rover-cyber-attack |
| S-016 | Asahi - Investigation results, 27 November 2025 | Asahi Group Holdings, Ltd. | 2025-11-27 (exact) | 1 | H2_prior | Attack timeline; initial access and ransomware; personal-records table; preventive measures | https://www.asahigroup-holdings.com/newsroom/detail/20251127-0204.html |
| S-017 | Asahi - Business progress update, February 2026 | Asahi Group Holdings, Ltd. | 2026-02-26 (exact) | 1 | current | Sales percentages October-December 2025; delayed results; restoration aim | https://www.asahigroup-holdings.com/en/newsroom/detail/20260226-0109.html |
| S-018 | Asahi - Business progress update, May 2026 | Asahi Group Holdings, Ltd. | 2026-05-22 (exact) | 1 | current | Jan-Mar 2026 sales ratios; distribution normalisation; results dates | https://www.asahigroup-holdings.com/en/newsroom/detail/20260522-0204.html |
| S-019 | Asahi - FY2025 results briefing Q&A | Asahi Group Holdings, Ltd. | 2026-07 (month_only) | 1 | current | Q4 and Q5 answers (revenue, marginal profit, Others expenses, total 2025 impact of about JPY 40.0 billion, Q1 2026 outlook) | https://www.asahigroup-holdings.com/en/ir/event/presentation/2025/qa_yearend.html |
| S-020 | Jiji via Nippon.com - Asahi 2025 results | Nippon.com (Jiji Press) | 2026-07-08 (exact) | 3 | current | Article body | https://www.nippon.com/en/news/yjj2026070800564/ |
| S-021 | Stryker - Form 8-K/A, 9 April 2026 | Stryker Corporation (SEC filing) | 2026-04-09 (exact) | 1 | current | Item 1.05 text: materiality determination, restoration of manufacturing network and ordering and distribution systems | https://www.sec.gov/Archives/edgar/data/310764/000119312526149607/d112875d8ka.htm |
| S-022 | Stryker - Q1 2026 results release | Stryker Corporation (SEC filing) | 2026-04-30 (exact) | 1 | current | CEO statement; guidance; forward-looking statements | https://www.sec.gov/Archives/edgar/data/0000310764/000031076426000025/sykex991earningsq12026.htm |
| S-023 | MedTech Dive - Stryker disruption report | MedTech Dive | 2026-03-13 (exact) | 3 | current | Article body: 8-K accession numbers, company statements, Handala claim, researcher assessments | https://www.medtechdive.com/news/strykers-manufacturing-shipping-disrupted-after-cyberattack/814667/ |
| S-024 | The Record - CISA and FBI endpoint-management guidance | The Record (Recorded Future News) | 2026-03-19 (exact) | 3 | current | Article body: CISA recommendations, FBI website seizure banner wording, attribution framing | https://therecord.media/fbi-cisa-warn-of-microsoft-intune-risks-stryker |
| S-025 | CISA - Endpoint management hardening alert | Cybersecurity and Infrastructure Security Agency (CISA) | 2026-03-18 (exact) | 1 | current | Alert title and date (page body did not render in the retrieval tool) | https://www.cisa.gov/news-events/alerts/2026/03/18/cisa-urges-endpoint-management-system-hardening-after-cyberattack-against-us-organization |
| S-026 | Boston Scientific - Form 8-K, 26 August 2026 | Boston Scientific Corporation (SEC filing) | 2026-08-26 (exact) | 1 | current | Item 8.01 text | https://www.sec.gov/Archives/edgar/data/0000885725/000088572526000056/bsx-20260826.htm |
| S-027 | Boston Scientific - Form 8-K Item 1.05, 8 September 2026 | Boston Scientific Corporation (SEC filing) | 2026-09-08 (exact) | 1 | current | Item 1.05 text: operational status, guidance statement, materiality | https://www.sec.gov/Archives/edgar/data/0000885725/000088572526000059/bsx-20260907.htm |
| S-028 | MedTech Dive - Boston Scientific manufacturing report | MedTech Dive | 2026-08-28 (exact) | 3 | current | Article body: patient-device monitoring effects | https://www.medtechdive.com/news/boston-scientific-says-cyberattack-has-disrupted-product-manufacturing/829086/ |
| S-029 | Reuters via Business Insurance - Boston Scientific guidance | Business Insurance (Reuters) | 2026-09-08 (exact) | 3 | current | Article body: guidance figures, share price move, analyst comments, sector context | https://www.businessinsurance.com/boston-scientific-says-unlikely-to-meet-sales-forecast-after-cyberattack/ |
| S-030 | West Pharmaceutical - Form 8-K Item 1.05, May 2026 | West Pharmaceutical Services, Inc. (SEC filing) | 2026-05-11 (exact) | 1 | current | Item 1.05 text | https://www.sec.gov/Archives/edgar/data/0000105770/000010577026000068/wst-20260507.htm |
| S-031 | Hasbro - Form 8-K, 1 April 2026 | Hasbro, Inc. (SEC filing) | 2026-04-01 (exact) | 1 | current | Item 8.01 text | https://www.sec.gov/Archives/edgar/data/46080/000004608026000013/has-20260401.htm |
| S-032 | Hasbro - Release of 23 April 2026 | Hasbro, Inc. (SEC filing) | 2026-04-23 (exact) | 1 | current | Incident paragraphs; guidance | https://www.sec.gov/Archives/edgar/data/0000046080/000004608026000016/exhibit991-apr232026.htm |
| S-033 | Cybersecurity Dive - Fairlife production halt | Cybersecurity Dive | 2026-07-17 (exact) | 3 | current | Article body; Food and Ag-ISAC statistics | https://www.cybersecuritydive.com/news/ransomware-attack-coca-cola-suspend-production-dairy/825540/ |
| S-034 | Egide - Cyber incident release, 9 October 2026 | Groupe Egide (via GlobeNewswire) | 2026-10-09 (exact) | 1 | current | Release body (attack via an external IT provider; partial interruption of the Bollène site; CNIL notified; complaint filed) | https://www.globenewswire.com/news-release/2026/10/09/3378286/0/fr/egide-incident-cyber.html |
| S-035 | CERT-FR - Refrigeration controller alert | CERT-FR (ANSSI) | 2026-10-12 (exact) | 1 | current | Alert versions of 12 and 13 October 2026: affected products, numerous compromises, recommendations | https://cert.cyber.gouv.fr/alerte/CERTFR-2026-ALE-012/ |
| S-036 | ComplexDiscovery - French refrigeration incident synthesis | ComplexDiscovery | 2026-10-14 (exact) | 3 | current | Sections on scale, official statements, vendor positions, exposure figures, attribution | https://complexdiscovery.com/refrigeration-hack-affected-about-700-french-supermarkets-government-says-as-danfoss-interfaces-stay-online/ |
| S-037 | RTX - Form 8-K on MUSE incident | RTX Corporation (SEC filing) | 2025-09-24 (exact) | 1 | H2_prior | Item 8.01 text | https://www.sec.gov/Archives/edgar/data/101829/000010182925000036/rtx-20250919.htm |
| S-038 | BleepingComputer - Bridgestone Americas incident | BleepingComputer | 2025-09 (month_only) | 3 | H2_prior | Article body: company statement | https://www.bleepingcomputer.com/news/security/tire-giant-bridgestone-confirms-cyberattack-impacts-manufacturing/ |
| S-039 | Dragos - Industrial ransomware Q2 2026 | Dragos | 2026-08-10 (exact) | 2 | current | Key findings; sector and subsector counts; regional distribution; top groups; OT impact assessment; named incidents | https://www.dragos.com/blog/dragos-industrial-ransomware-analysis-q2-2026 |
| S-040 | Black Kite - 2026 manufacturing ransomware report | Black Kite | 2026 (year_only) | 2 | current | Key statistics: annual totals, Jan-Jul 2026 comparison, subsectors, countries, groups, methodology | https://blackkite.com/reports/2026-manufacturing-distribution |
| S-041 | ENISA - Threat Landscape 2026 | European Union Agency for Cybersecurity (ENISA) | 2026-09 (month_only) | 1 | current | pp. 7, 9-14, 31-33 (manufacturing), 46-51 (ransomware) | https://www.enisa.europa.eu/sites/default/files/2026-09/ENISA%20Threat%20Landscape%202026_Final.pdf |
| S-042 | Manufacturing Dive - IBM X-Force 2026 findings | Manufacturing Dive | 2026-02-26 (exact) | 3 | current | Article body | https://www.manufacturingdive.com/news/manufacturing-sector-saw-most-cyberattacks-in-2025-IBM-X-Force/813063/ |
| S-043 | Eurostat - Businesses in the manufacturing sector | Eurostat | 2025-12 (month_only) | 1 | H2_prior | Key figures: enterprises, persons employed, value added, largest divisions | https://ec.europa.eu/eurostat/statistics-explained/SEPDF/cache/10086.pdf |
| S-044 | Eurostat - EU business economy 2023 | Eurostat | 2025-10-13 (exact) | 1 | H2_prior | News body: size-class shares | https://ec.europa.eu/eurostat/web/products-eurostat-news/w/ddn-20251013-2 |
| S-045 | BSI - NIS-2 in figures, Q3 2026 | Bundesamt für Sicherheit in der Informationstechnik (BSI) | 2026-10-07 (page_update) | 1 | current | Registration table; Annex 2 sector breakdown (manufacturing 4,739; chemicals 821; food 1,986); reports | https://www.bsi.bund.de/DE/Themen/Regulierte-Wirtschaft/NIS-2-regulierte-Unternehmen/NIS-2-in-Zahlen/nis-2-in-zahlen.html |
| S-046 | BSI - German NIS2 law in force | Bundesamt für Sicherheit in der Informationstechnik (BSI) | 2025-12-05 (exact) | 1 | H2_prior | Release body: entry into force, about 29,500 supervised entities, registration steps | https://www.bsi.bund.de/DE/Service-Navi/Presse/Pressemitteilungen/Presse2025/251205_NIS-2-Umsetzungsgesetz_in_Kraft.html |
| S-047 | Bundestag - Drucksache 21/8046 | Deutscher Bundestag | 2026-09-16 (exact) | 1 | current | Answer to question 7 (no information on cyber-caused insolvencies); statistics answers (BKA ransomware cases 2025; damage estimates); preamble (questioners' case references) | https://dserver.bundestag.de/btd/21/080/2108046.pdf |
| S-048 | CircleID - Zego insolvency report | CircleID | 2026-07-14 (exact) | 3 | current | Article body | https://circleid.com/posts/zegos-cyberattack-pushes-bavarian-textile-firm-into-insolvency |
| S-049 | EUR-Lex - NIS2 Directive | Publications Office of the EU (EUR-Lex) | 2022-12-27 (exact) | 1 | contextual | ELI metadata (publication 27.12.2022; in force 16.1.2023); Arts 2(1)-(2), 3(1)-(4), 20, 21(2)(d) and 21(3), 23(4), 34(4)-(5), 41(1); Annexes I and II | https://eur-lex.europa.eu/eli/dir/2022/2555/oj/eng |
| S-050 | Streamlex - NIS2 Annex II text | Streamlex | undated (undated) | 3 | contextual | Annex II sectors 3, 4 and 5 | https://streamlex.eu/annexes/nis2-en-annex-ii/ |
| S-051 | European Commission - NIS2 Court referral | European Commission (Shaping Europe's digital future) | 2026-07-08 (exact) | 1 | current | News body: referral, penalties requested, letters of formal notice 28 November 2024, reasoned opinions 7 May 2025 | https://digital-strategy.ec.europa.eu/en/news/commission-refers-ireland-spain-france-and-netherlands-court-justice-failing-transpose-rules |
| S-052 | European Commission - NIS2 transposition page | European Commission (Shaping Europe's digital future) | 2025-07-01 (page_update) | 1 | H2_prior | Reasoned opinion list (19 Member States, 7 May 2025); referral note | https://digital-strategy.ec.europa.eu/en/policies/nis-transposition |
| S-053 | European Commission - CER Court referral (IP/26/910) | European Commission (Press corner) | 2026 (year_only) | 1 | current | Release title and description (body and date not rendered) | https://ec.europa.eu/commission/presscorner/detail/en/ip_26_910 |
| S-054 | EUR-Lex - CER Directive | Publications Office of the EU (EUR-Lex) | 2022-12-27 (exact) | 1 | contextual | ELI metadata (document 14.12.2022; publication 27.12.2022; in force 16.1.2023); Arts 6(1), 26(1); Annex sectors | https://eur-lex.europa.eu/eli/dir/2022/2557/oj/eng |
| S-055 | EUR-Lex - Regulation (EU) 2024/2847 | Publications Office of the EU (EUR-Lex) | 2024-11-20 (exact) | 1 | contextual | ELI metadata (document 23.10.2024; in force 10.12.2024); Arts 2, 7-8, 14, 71; Annexes III and IV | https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng |
| S-056 | European Commission - Regulation (EU) 2024/2847 summary | European Commission (Shaping Europe's digital future) | undated (undated) | 1 | contextual | Scope; conformity assessment; manufacturer obligations; reporting obligations; timeline; penalties | https://digital-strategy.ec.europa.eu/en/policies/cra-summary |
| S-057 | ENISA - Single Reporting Platform launch | ENISA | 2026-09-11 (exact) | 1 | current | Release body: initial operating capability; reporting from 11 September 2026; routing | https://www.enisa.europa.eu/news/the-cra-single-reporting-platform-is-launched |
| S-058 | EUR-Lex - Implementing Regulation (EU) 2025/2392 | Publications Office of the EU (EUR-Lex) | 2025-11-28 (exact) | 1 | H2_prior | ELI metadata: date of document 28.11.2025; entry into force 21.12.2025 | https://eur-lex.europa.eu/eli/reg_impl/2025/2392/oj/eng |
| S-059 | Springlex - Regulation (EU) 2024/2847 Article 2 | Springlex | undated (undated) | 3 | contextual | Article 2 paragraphs on exclusions | https://www.springlex.eu/en/packages/cra/cra-regulation/article-2/ |
| S-060 | DBT - Explanatory memorandum on Regulation (EU) 2026/1744 | UK Department for Business and Trade (Office for Product Safety and Standards) | 2026-08-03 (exact) | 1 | current | Paras 2, 9, 12, 13, 17 | https://www.niassembly.gov.uk/globalassets/committee-blocks/windsor-framework-democratic-scrutiny-committee/reg-eu-20261744/regulation-eu-2026_1744-em.pdf |
| S-061 | ERTICO - Digital Omnibus on AI entry into force | ERTICO - ITS Europe | 2026-08-07 (exact) | 3 | current | Article body: OJ 24 July 2026, in force 27 July 2026, Annex III 2 December 2027, Annex I 2 August 2028 | https://ertico.com/digital-omnibus-on-ai-enters-into-force |
| S-062 | euaiact.com - Regulation (EU) 2026/1744 sectoral amendments | EU AI Act (euaiact.com) | undated (undated) | 3 | contextual | Article 3 amendments to Regulation (EU) 2023/1230 (Arts 8, 20, 47); recital 42 | https://www.euaiact.com/digital-omnibus-ai/sectoral-amendments |
| S-063 | EU-OSHA - Machinery Regulation page | European Agency for Safety and Health at Work (EU-OSHA) | 2025-01-16 (page_update) | 1 | contextual | Page body: application date; scope note on connected equipment and AI safety functions | https://osha.europa.eu/en/legislation/directive/regulation-20231230eu-machinery |
| S-064 | KAN - Machinery cybersecurity requirements brief | Commission for Occupational Health and Safety and Standardization (KAN) | 2025 (year_only) | 2 | contextual | Article body: Annex III 1.1.9 and 1.2.1; prEN 50742; application 20 January 2027 | https://www.kan.de/en/publications/kanbrief/2025/2-25/combating-vulnerabilities-with-standards-new-eu-cybersecurity-rules/ |
| S-065 | EUR-Lex - Machinery Regulation consolidated | Publications Office of the EU (EUR-Lex) | 2026-07-27 (page_update) | 1 | current | ELI metadata: consolidated version dated 27 July 2026; Annex III points 1.1.9 and 1.2.1 | https://eur-lex.europa.eu/eli/reg/2023/1230 |
| S-066 | EUR-Lex - Product Liability Directive | Publications Office of the EU (EUR-Lex) | 2024-10-23 (exact) | 1 | contextual | ELI metadata (document 23.10.2024; in force 8.12.2024); Arts 4(1), 7(2), 11(2), 22(1) | https://eur-lex.europa.eu/eli/dir/2024/2853/oj/eng |
| S-067 | Inside Privacy - Product liability transposition update | Covington & Burling (Inside Privacy) | 2026-08-17 (page_update) | 3 | current | Update of 17 August 2026: transposition deadline; national bills and adopted laws | https://www.insideprivacy.com/uncategorized/eu-member-states-begin-rolling-out-new-product-liability-rules/ |
| S-068 | EUR-Lex - Delegated Regulation (EU) 2026/339 | Publications Office of the EU (EUR-Lex) | 2026-02-16 (exact) | 1 | current | ELI metadata: date of act 16.2.2026; first entry into force 19.5.2026; date no longer in force 10.12.2027 | https://eur-lex.europa.eu/eli/reg_del/2026/339/oj/eng |
| S-069 | European Commission - Data Act page | European Commission (Shaping Europe's digital future) | undated (undated) | 1 | contextual | Page body: entry into force and application; connected products including industrial machinery | https://digital-strategy.ec.europa.eu/en/policies/data-act |
| S-070 | European Commission - GMP Annex 11 consultation | European Commission (DG SANTE) | undated (undated) | 1 | contextual | Page body: status closed; opening 7 July 2025; deadline 7 October 2025; documents | https://health.ec.europa.eu/consultations/stakeholders-consultation-eudralex-volume-4-good-manufacturing-practice-guidelines-chapter-4-annex_en |
| S-071 | Official Journal - UN Regulation No. 155 | Publications Office of the EU (Official Journal) | 2025-01-10 (exact) | 1 | contextual | Paras 1.1, 6, 6.7, 7.2.2.1, 7.3.1, 7.3.4 | https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ%3AL_202500005 |
| S-072 | European Commission - Seveso III implementation report | European Commission | 2025-09-19 (exact) | 1 | H2_prior | Report body: security-related risks paragraph; listed triggers | https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex:52025DC0508 |
| S-073 | Council of the EU - FDI screening adoption | Council of the European Union | 2026-06-08 (exact) | 1 | current | Release body: adoption, minimum scope, timeline | https://www.consilium.europa.eu/en/press/press-releases/2026/06/08/foreign-investment-screening-council-signs-off-on-updated-framework/ |
| S-074 | European Commission - FDI screening publication | European Commission (DG Trade and Economic Security) | 2026-06-26 (exact) | 1 | current | News body: OJ publication 26 June 2026 (OJ L 2026/1386 reference), 18-month implementation, minimum scope | https://policy.trade.ec.europa.eu/news/eu-strengthens-its-foreign-investment-screening-framework-2026-06-26_en |
| S-075 | UK Parliament - Cyber Security and Resilience Bill page | UK Parliament | 2026-10-15 (page_update) | 1 | current | Bill page: House of Lords, Report stage linked; HL Bill 49 as amended in Grand Committee dated 7 September 2026; no Royal Assent | https://bills.parliament.uk/bills/4035 |
| S-076 | DSIT - Bill summary factsheet | Department for Science, Innovation and Technology (DSIT) | 2026-06-30 (page_update) | 1 | current | Sections on managed service providers, data centres, designated suppliers, incident reporting, penalties, powers | https://www.gov.uk/government/publications/cyber-security-and-resilience-network-and-information-systems-bill-factsheets/summary-of-the-bill |
| S-077 | Home Office - Ransomware proposals response | Home Office | 2025-07-22 (exact) | 1 | H2_prior | pp. 26-27 (ban), 28 and 40-41 (prevention regime), 42 and 47 (reporting) | https://assets.publishing.service.gov.uk/media/6899a4ddad0cbc0e276431e3/Government_Response_Ransomware_proposals_to_increase_incident_reporting_and_reduce_payments_to_criminals.pdf |
| S-078 | LGA - Ransomware proposals briefing | Local Government Association | undated (undated) | 2 | contextual | Page body: proposals described as proposals; economy-wide versus threshold reporting | https://www.local.gov.uk/our-support/cyber-digital-and-technology/cyber-digital-and-technology-policy-team/ransomware |
| S-079 | HSE - Cyber security for industrial automation and control systems | Health and Safety Executive (HSE) | 2026-06-29 (page_update) | 1 | current | Page body: COMAH interpretation; OG86 (March 2017); referenced standards | https://www.hse.gov.uk/eci/cyber-security.htm |
| S-080 | Cabinet Office - NSI Act notifiable acquisitions guidance | Cabinet Office | 2024-02-06 (page_update) | 1 | contextual | List of 17 areas; advanced materials, advanced robotics, computing hardware, defence, military and dual-use sections | https://www.gov.uk/government/publications/national-security-and-investment-act-guidance-on-notifiable-acquisitions/national-security-and-investment-act-guidance-on-notifiable-acquisitions |
| S-081 | MOD - Cyber Security Model | Ministry of Defence | 2026-03-06 (page_update) | 1 | current | Page body: CSM version 4; Def Stan 05-138 Issue 4; DEFCON 658 flow-down | https://www.gov.uk/guidance/cyber-security-model |
| S-082 | DSIT - Product security regime guidance | Department for Science, Innovation and Technology | 2024-05-02 (page_update) | 1 | contextual | Page body: start date, duty holders, three requirements, OPSS enforcement | https://www.gov.uk/government/publications/the-uk-product-security-and-telecommunications-infrastructure-product-security-regime |
| S-083 | SEC - Cyber disclosure rules fact sheet | US Securities and Exchange Commission | undated (undated) | 1 | historical | Item 1.05; Item 106; compliance dates | https://www.sec.gov/files/33-11216-fact-sheet.pdf |
| S-084 | Federal Register - DFARS CMMC final rule | Office of the Federal Register (Department of Defense) | 2025-09-10 (exact) | 1 | H2_prior | Summary; effective date; clause 252.204-7021; phase description | https://www.federalregister.gov/documents/2025/09/10/2025-17359/defense-federal-acquisition-regulation-supplement-assessing-contractor-implementation-of |
| S-085 | Squire Patton Boggs - CMMC phases | Squire Patton Boggs | 2025-09 (month_only) | 3 | H2_prior | Phased rollout section (32 CFR 170.3) | https://www.squirepattonboggs.com/insights/publications/the-cmmc-dfars-final-rule-goes-live-ready-or-not-here-it-comes/ |
| S-086 | Paubox - CIRCIA final rule status | Paubox | 2026-10-08 (exact) | 3 | current | Article body: submission to OMB on 1 October 2026; missed target dates | https://www.paubox.com/blog/circia-final-rule-white-house-deadlines-set-scope-open |
| S-087 | CISA - CFATS lapse statement | CISA | 2023-11 (month_only) | 1 | historical | Article body | https://www.cisa.gov/news-events/news/resilience-time-uncertainty-national-chemical-security-during-cfats-lapse |
| S-088 | J. J. Keller - CFATS status | J. J. Keller | 2024-12-31 (exact) | 3 | contextual | Article body | https://jjkellercompliancenetwork.com/regsense/what-happened-to-cfats-chemical-facility-anti-terrorism-standards-at-6-cfr-27-are-the-cfats-withdrawn |
| S-089 | CISA and partners - PLC advisory AA26-097A | CISA and partner agencies | 2026-04-07 (exact) | 1 | current | Advisory title and identifier (body not retrievable in this run) | https://www.cisa.gov/news-events/cybersecurity-advisories/aa26-097a |
| S-090 | Picus - Summary of advisory AA26-097A | Picus Security | 2026 (year_only) | 3 | current | Blog body: date, agencies, sectors, impacts, vendor named | https://www.picussecurity.com/resource/blog/cisa-alert-aa26-097a-iranian-affiliated-actors-target-plcs-across-us-%63ritical-infrastructure |
| S-091 | NCSC - CEO keynote, CYBERUK 2026 | National Cyber Security Centre (NCSC) | 2026-04-22 (exact) | 1 | current | Speech text: four nationally significant incidents a week; state actors China, Russia, Iran | https://www.ncsc.gov.uk/speech/ncsc-ceo-keynote-speech-cyberuk-2026 |
| S-092 | NIST - SP 800-82 Rev. 3 | NIST | 2023-09-28 (exact) | 1 | historical | Publication page: date, status, abstract; planning note on Rev. 4 initial public draft dated 21 September 2026 | https://csrc.nist.gov/pubs/sp/800/82/r3/final |
| S-093 | NIST - CSF 2.0 Manufacturing Profile draft | NIST | 2025-09-29 (exact) | 1 | H2_prior | Publication page: status, comment period, abstract | https://csrc.nist.gov/pubs/ir/8183/r2/ipd |
| S-094 | FDA - Medical device cybersecurity FAQs | US Food and Drug Administration | 2025-06-26 (page_update) | 1 | H1_prior | FAQ answers on section 524B requirements, effective date and cyber device definition | https://www.fda.gov/medical-devices/digital-health-center-excellence/cybersecurity-medical-devices-frequently-asked-questions-faqs |
| S-095 | legislation.gov.uk - NIS Regulations 2018 schedules | legislation.gov.uk (The National Archives) | 2018-04-19 (exact) | 1 | historical | Schedule 1 sector table (energy, transport, health, drinking water, digital infrastructure); Schedule 2 essential services and thresholds | https://www.legislation.gov.uk/uksi/2018/506/schedules/data.xht |
| S-096 | eCFR - 32 CFR Part 170 CMMC Program | Electronic Code of Federal Regulations (eCFR) | undated (undated) | 1 | contextual | Section 170.3(e) phased implementation | https://www.ecfr.gov/current/title-32/subtitle-A/chapter-I/subchapter-G/part-170 |

### G2. Sources cited in the user-supplied research input (merged 28 October 2026; not validated)

Numbering U-000 to U-010 follows the input's source list (items 1 to 10). Titles and dates are reproduced as given, translated where the input described them in Portuguese; the input's own source-type and confidence labels are shown. URLs, access dates and locators were not given in the input and were not looked up.

| ID | Source and title (as given) | Publisher | Date (as given) | Input's source type | Input's confidence | Used in |
|---|---|---|---|---|---|---|
| U-000 | User-supplied research input as a whole (sections A-F), for statements that cite no numbered source | User-supplied | Cut-off October 2026 | Analytical input | Not stated | 0, A, B, C, Q01-Q15, E, F |
| U-001 | DataBank Glossary, Manufacturing (% of GDP): definition of manufacturing as ISIC C15-C37 | World Bank | 2026 | Original (national-accounts glossary) | High | A |
| U-002 | "Rolls-Royce settles bribery probes in UK, U.S. and Brazil" | Reuters | 17 January 2017 | Secondary (case table: first-hand); evidences bribery fines and 24 years of corruption cases in aerospace; value GBP 671m | High | C, Q07, Q10, Q13, Q15, Q08, D |
| U-003 | "Airbus agrees to $4B settlement in international corruption case" | Washington Post (via Reuters) | 31 January 2020 | Secondary; Airbus admits a global bribery scheme; agreements in three jurisdictions | High | C, Q07, Q10, Q13, Q15, Q08, D |
| U-004 | "U.S. Defense Contractor and Employees Sentenced for Procurement Fraud Scheme" | US Department of Justice, Eastern District of Virginia | 18 August 2021 | Primary; manufacturer of parts; military contract fraud of about USD 7m | High | Q10, Q15, D |
| U-005 | "Coca-Cola says fairlife halts US production after cyber attack" | Reuters | 16 July 2026 | Primary (as labelled); cyberattack halted Fairlife dairy production | High | B, C, Q02, Q05, Q10-Q12, Q15, D |
| U-006 | "Nucor reports cybersecurity incident, pauses operations" | Industrial Cyber | 15 May 2025 | Primary (as labelled), SEC Form 8-K communication; steel producer suspended operations after intrusion | Medium-High | B, C, Q02, Q05, Q10-Q12, Q15, D |
| U-007 | "Cyber threat trends in the manufacturing industry" | Willis Towers Watson (WTW) | April 2024 | Secondary; contains Sophos 2023 ransomware statistics for manufacturing | Medium | B, C, Q03-Q05, Q10, Q11, Q14, Q15 |
| U-008 | "Business Email Compromise: The $26 Billion Scam" (public service announcement) | FBI Internet Crime Complaint Center (IC3) | 10 September 2019 | Primary; official PSA; BEC statistics 2013-2019 | High | Q10, Q11, Q15, Q08 |
| U-009 | "State of Pentesting Report" (Cobalt, 2023) | Industrial Cyber | 2023 | Secondary; manufacturing takes 122 days to remediate vulnerabilities | Medium | Q04, Q10, Q11, Q14 |
| U-010 | Corporate reports (Rolls-Royce 2016, Airbus 2019), cited in the sources above | Rolls-Royce plc; Airbus SE (as consolidated by Reuters) | 2016; 2019 | Primary company sources | Medium-High | D |
| U-011 | Toshiba reference marked "[48]" in the input's case table; not in its source list | Not stated | Not stated | Not stated | Not stated | Q10, Q13, Q15, Q08, D, E |
| U-012 | Industrial Cyber report on Masimo (SEC Form 8-K, April 2025), named in the input's case table; not in its source list | Industrial Cyber (as named) | Not stated | Secondary (as labelled) | Not stated | Q02, Q10, D |
| U-013 | Legal and regulatory instruments named in the input "without a direct source" (FCPA, False Claims Act, Bribery Act 2010, Companies Act 2006, PSD2, FCA and PRA guidance, NIS2, Directive (EU) 2019/1937, Directive 2014/24/EU, Law 12.846/2013) | Official legislation (as stated in the input) | As listed in Q10.7 | Legislation | Not stated | Q06, Q10, Q13, Q08 |


---

## H. Change log and merge log against the baseline edition

| Area | Change |
|---|---|
| Q01-Q07 | No change in evidence; reorganised by research question from the 16 October 2026 report and registers. User-input items are added as labelled cross-references only (Q01 business-model range; Q02 user-input incidents; Q03 Sophos and cyber-enabled fraud pathways; Q04 maturity statements; Q05 survey averages, scenario anchors and fraud channel; Q06 fraud-rule pointer; Q07 cross-border enforcement note) |
| Q02 | Top five unchanged; Fairlife, Nucor, Masimo, Honda and LockBit/Bridgestone recorded in the unified event register (section D) |
| Q10 | New: 13-typology screen, seven documented cases (four fraud cases, three cyber cases as supplied), five quantitative datasets, structural drivers, six control failures, consequences, ten rule rows (US, UK, EU, Brazil), six emerging techniques |
| Q11 | New: IT/OT convergence, legacy SCADA and cloud, attack surface, ransom statistics, maturity and SOC preparedness, merged with baseline benchmarks |
| Q12 | New: four essential dependencies, nine-row dependency matrix combining both sets, durations table, consequences |
| Q13 | New: operating models and nine governance categories (six user-supplied, three baseline) |
| Q14 | New: comparative indicators from both sets with comparability notes; the input states that no formal comparison exists |
| Q15 | Updated: Fraud from Not assessable to Medium (Provisional, Medium); Governance from Not assessable to Medium (Provisional, Low); Operational resilience / TPRM from High to Medium (Provisional; confidence Low or Medium, E-01); Cyber / ICT unchanged at High (Provisional, Medium) |
| Q08 | Extended: PROV-08 to PROV-11 added (supplier bank-detail change control, email authentication and MFA, anti-corruption and intermediary oversight, internal audit and whistleblowing); PROV-01, -03 and -05 extended with user-input evidence |
| Q09 | Updated narrative, credit relevance and an assembly map to the 11 fixed report headings |
| Registers | Unified event register (22 records), conflict register (17 items), source mapping (S-001 to S-096 retained; U-000 to U-013 added) |
| Translation | Portuguese to English (UK); neutral equivalents used where a literal translation would have produced a word excluded by the editorial rules; the UK fraud prosecutor is referred to by its acronym, SFO |
| Baseline edition status | The 16 October 2026 seven-slide edition and the 12-slide migrated edition (1.0-M) are unchanged and remain the published editions; this record supersedes neither |

---

## I. Completeness check

| Question | Covered in | Evidence sets used | Status |
|---|---|---|---|
| Q01 Operating model and dependencies | Q01, Q12.2-Q12.3 | Baseline; user cross-reference | Complete for baseline scope |
| Q02 Incidents and case studies | Q02, D | Baseline; user incidents in register | Partial: one detailed case study |
| Q03 Threats and attack pathways | Q03 | Baseline; user benchmarks | Complete |
| Q04 Resilience capabilities and benchmarks | Q04 | Baseline; user maturity statements | Partial: no sector maturity survey |
| Q05 Financial impact and credit transmission | Q05 | Baseline; user survey averages | Partial: no multi-year series or ransom data for named cases |
| Q06 Regulation | Q06, Q10.7 | Baseline; user fraud rules | Partial: fraud-rule rows not reviewed |
| Q07 Geopolitics | Q07 | Baseline fragments; user note | Partial (gap) |
| Q08 Questionnaire mapping | Q08 | Both | Provisional (no item list) |
| Q09 Final synthesis | Q09 | Both | Complete as research record; no report or annex produced |
| Q10 Fraud (Q10A-Q10D) | Q10.1-Q10.8 | User input; baseline cross-references | Complete as supplied; not validated |
| Q11 ICT exposure and maturity | Q11 | Both | Complete as supplied |
| Q12 Operational resilience and concentration | Q12 | Both | Partial: no concentration statistics |
| Q13 Governance | Q13 | Both | Partial: historical cases only |
| Q14 Cross-sector comparison | Q14 | Both | Partial: no formal comparison |
| Q15 Classification | C, Q15 | User ratings; both evidence sets | Provisional; conflict E-01 open |

**Status: NEEDS_REVIEW** - user-supplied evidence not validated; conflict E-01 unresolved; Q07, Q12 and Q14 partial; no approved rubric or questionnaire.
