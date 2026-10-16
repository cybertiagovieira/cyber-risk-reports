# Manufacturing - Sectorial Cyber Risk Intelligence

**Report date:** 16 October 2026. **Reporting period:** 1 September 2025 to 16 October 2026. **Evidence cut-off:** 16 October 2026. **Rolling evidence horizon:** 18 months for patterns and public loss cases, with older material labelled contextual or historical.

**Geography:** Global, with primary focus on the European Union (EU), European Economic Area (EEA) and United Kingdom (UK); North American, Japanese and other evidence is used for comparison and cross-border supply-chain effects. **Audience:** First Line of Defence (1LoD) operational management and Risk Committee. **Boundary:** public external data only; no internal, client or bank-specific information is used or implied. **Edition:** baseline edition; no prior publication exists for this sector, so changes are described against the period, not against an earlier report.

**Evidence labels used throughout:** Observed (external fact from a named source), Benchmark (sector statistic with stated population), Proxy (indirect or derived measure), Judgement (analytic judgement by this report), Assumption (scenario assumption), Action (management recommendation). Each statement is preceded by its source reference in the form [Source/Title][n]; full details are in the References section and in the source register.

## Sector Exposure & Executive Risk Outlook

### Bottom line

[JLR - Statement on cyber incident, 2 September 2025][1] [Asahi - Investigation results, 27 November 2025][16] [Stryker - Form 8-K/A, 9 April 2026][21] [Boston Scientific - Form 8-K Item 1.05, 8 September 2026][27] [Dragos - Industrial ransomware Q2 2026][39] The decisive Manufacturing cyber exposure in the period was not the manipulation of production machinery but the loss of the enterprise systems that production depends on: in the four largest disclosed cases, companies stopped or slowed plants after their information technology (IT) estate was encrypted, wiped or isolated, and Dragos found no quarter-two 2026 ransomware case that reached control-system manipulation (Judgement). [JLR - Q2 FY26 results release][4] [CMC - JLR categorisation statement][10] [ONS - GDP monthly estimate, September 2025][11] [UK Government - JLR loan guarantee][9] The best-documented case, the Jaguar Land Rover (JLR) shutdown from September 2025, shows the full transmission chain: about five weeks of halted production, GBP 260 million of disclosed cyber-related costs over two quarters, a modelled UK loss of GBP 1.9 billion, mostly lost output at JLR and its suppliers, an officially recorded fall in motor-vehicle output that the trade body attributed to the stoppage, and a government-guaranteed bank loan (Observed and Benchmark). [CERT-FR - Refrigeration controller alert][35] At the evidence cut-off, French authorities reported numerous compromises of internet-reachable refrigeration controllers made by two manufacturers, the clearest in-period case of direct operational technology (OT) compromise, here of products in customers' premises rather than of factories (Observed). [JLR - Restart and supplier financing release][3] [Bundestag - Drucksache 21/8046][47] For a bank, relevance is conditional and indirect - through counterparty working capital, supplier liquidity and receivables, guarantees and state-backed lending, insurance gaps and product liability - not through any asserted exposure of a specific institution.

### Principal judgements

**1. Production loss runs mainly through IT dependency, not direct OT compromise (Judgement; confidence medium).** [JLR - Statement on cyber incident, 2 September 2025][1] JLR proactively shut down its systems and production stopped (Observed). [Asahi - Investigation results, 27 November 2025][16] Asahi isolated its data centre after ransomware encryption that started from network equipment at a group site (Observed). [Stryker - Form 8-K/A, 9 April 2026][21] [Boston Scientific - Form 8-K Item 1.05, 8 September 2026][27] Stryker and Boston Scientific both reported manufacturing disruption caused by incidents in IT systems (Observed). [Dragos - Industrial ransomware Q2 2026][39] Dragos assessed that operational disruption in industrial ransomware came from encryption or precautionary shutdown of enterprise and virtualisation systems that OT depends on (Benchmark). **Competing explanation:** companies rarely disclose OT state, so some OT effects may be hidden; [CMC - JLR categorisation statement][10] the Cyber Monitoring Centre (CMC) noted that the extent of OT impact at JLR was unclear. **What would change this judgement:** disclosure of control-system manipulation causing physical damage or safety events at a manufacturer.

**2. Supplier cascade and liquidity are the systemic pathway in just-in-time manufacturing (Judgement; confidence medium).** [CMC - JLR categorisation statement][10] The CMC modelled that the JLR stop affected over 5,000 UK organisations (more than 2,700 in its Category 3 criteria section), with most of the GBP 1.9 billion loss falling on lost output at JLR and its suppliers, and assumed key suppliers would stay solvent (Benchmark). [JLR - Restart and supplier financing release][3] [UK Government - JLR loan guarantee][9] JLR prepaid qualifying suppliers through a banking partner and the UK Government backed a GBP 1.5 billion commercial loan to support the supply chain (Observed). **Competing explanation:** buffered or high-mix production, common in process industries, may absorb short stops. [Bundestag - Drucksache 21/8046][47] **What would change this judgement:** official evidence that tier-2 and tier-3 suppliers absorbed multi-week customer stops without liquidity support; the German Government states it has no information on cyber-caused insolvencies (Observed).

**3. Financial transmission is dominated by lost output and working capital, not by response cost (Judgement; confidence medium).** [JLR - Q2 FY26 results release][4] [JLR - Q3 FY26 results release][6] JLR's labelled cyber costs were GBP 196 million and GBP 64 million in two quarters, while quarterly revenue fell 24% and 39% and free cash outflow reached GBP 791 million and GBP 1.5 billion (Observed; revenue falls have several causes). [CMC - JLR categorisation statement][10] For a like-for-like view, the CMC modelled about GBP 108 million a week of fixed cost and lost profit at JLR's UK operations alone, against GBP 196 million of labelled cyber costs in the stop quarter (Benchmark versus Observed; modelled and not additive). [Asahi - FY2025 results briefing Q&A][19] Asahi estimated a JPY 40 billion 2025 impact, of which JPY 17 billion was incident-related expenses (including inventory disposal and restoration staff) and the remainder a decline in core operating profit, about JPY 20 billion of it lost marginal profit (Observed). **Competing explanation:** part of the lost revenue is deferred, not lost; [Stryker - Q1 2026 results release][22] [Hasbro - Release of 23 April 2026][32] Stryker and Hasbro kept full-year guidance (Observed). **What would change this judgement:** disclosures showing response and rebuild costs exceeding lost margin.

**4. State-linked activity is a rising threat to industrial products and enterprise estates, but no official source in the period attributed a manufacturing disruption to a state actor (Judgement; confidence low).** [CISA and partners - PLC advisory AA26-097A][89] [Picus - Summary of advisory AA26-097A][90] United States (US) agencies issued an advisory in April 2026 on Iranian-affiliated actors exploiting internet-facing programmable logic controllers (PLCs) of a vendor widely used in industry; according to a vendor summary, the advisory's named sectors did not include manufacturing, so relevance is through the controllers' makers and industrial users (Observed, content from a vendor summary; Judgement). [MedTech Dive - Stryker disruption report][23] [The Record - CISA and FBI endpoint-management guidance][24] Media report that a group they describe as Iran-linked claimed the Stryker attack and that devices were wiped through an endpoint-management platform; neither point is confirmed by the company or attributed by a US government source (Observed, Tier 3; claim unconfirmed). [CISA - Endpoint management hardening alert][25] CISA issued an endpoint-management hardening alert after an attack on an unnamed US organisation (Observed). [NCSC - CEO keynote, CYBERUK 2026][91] The UK National Cyber Security Centre (NCSC) reported that most nationally significant incidents now originate directly or indirectly from nation states (Observed). **Competing explanation:** state-linked personas may overstate effect; most production losses in the period were financially motivated ransomware. **What would change this judgement:** official attribution of a European manufacturing disruption to a state actor.

**5. Regulation reaches most manufacturers through product law and contracts rather than entity-level regimes such as NIS2 (Judgement; confidence medium).** [EUR-Lex - NIS2 Directive][49] [Streamlex - NIS2 Annex II text][50] The EU Network and Information Systems Directive 2 (NIS2) covers only named manufacturing divisions and sectors above a size threshold (Observed). [ENISA - Single Reporting Platform launch][57] [EU-OSHA - Machinery Regulation page][63] [EUR-Lex - Product Liability Directive][66] Product-security reporting under Regulation (EU) 2024/2847, the Cyber Resilience Act (CRA), has applied to manufacturers of in-scope products with digital elements since 11 September 2026, and the revised Product Liability Directive and the Machinery Regulation follow in December 2026 and January 2027 (Observed). [BSI - NIS-2 in figures, Q3 2026][45] Where NIS2 applies, the population is large: 4,739 German registrations selected manufacturing (Observed). **What would change this judgement:** national NIS2 measures designating manufacturing outside the named divisions.

### What changed in the period

- [JLR - Statement on cyber incident, 2 September 2025][1] [ONS - GDP monthly estimate, September 2025][11] [SMMT - September 2025 vehicle output][12] [Bank of England - Monetary Policy Report, November 2025][13] September to November 2025: ONS recorded a 28.6% fall in UK motor-vehicle output in September 2025 and relayed the trade body's attribution to the JLR stoppage; the Bank of England cited the disruption as one reason Q3 growth was weaker than expected (Observed).
- [Asahi - Investigation results, 27 November 2025][16] [Asahi - FY2025 results briefing Q&A][19] September 2025 to July 2026: Asahi's ransomware halted Japanese shipments, delayed its results by five months and cost about JPY 40 billion in 2025 (Observed).
- [Stryker - Form 8-K/A, 9 April 2026][21] [West Pharmaceutical - Form 8-K Item 1.05, May 2026][30] [Boston Scientific - Form 8-K Item 1.05, 8 September 2026][27] March to September 2026: three US-listed medical-technology and pharmaceutical-component manufacturers filed material-incident reports after production and shipping disruption (Observed).
- [Dragos - Industrial ransomware Q2 2026][39] [Black Kite - 2026 manufacturing ransomware report][40] Q2 2026: industrial ransomware rose 12% quarter on quarter, with manufacturing at about 65% and European victims rising (Benchmark).
- [BSI - German NIS2 law in force][46] [European Commission - NIS2 Court referral][51] December 2025 to July 2026: Germany's NIS2 law came into force; four Member States were referred to the Court of Justice for non-transposition (Observed).
- [ENISA - Single Reporting Platform launch][57] 11 September 2026: manufacturers' product vulnerability and incident reporting obligations began (Observed).
- [CERT-FR - Refrigeration controller alert][35] [Egide - Cyber incident release, 9 October 2026][34] 6-13 October 2026: an aerospace and defence component supplier in France was disrupted through an IT provider, and refrigeration controllers in French supermarkets were compromised (Observed).

### Sector footprint and subsector coverage

[Eurostat - Businesses in the manufacturing sector][43] EU manufacturing had about 2.2 million enterprises, 30.2 million persons employed (18.5% of business-economy employment) and about EUR 2.5 trillion of value added (23.1%) in 2023, with machinery, food and motor vehicles the largest divisions by value added (Observed). [Eurostat - EU business economy 2023][44] Across the EU business economy, micro and small firms are 99% of enterprises while large firms produce 49% of value added (Observed); in manufacturing supply chains this means many small suppliers depend on few large customers (Judgement). [UK Government - JLR loan guarantee][9] In the UK, JLR alone employs 34,000 people and supports a supply chain of about 120,000 (Observed).

| Subsector | In-period public evidence | Evidence strength | Main gap |
| --- | --- | --- | --- |
| Automotive OEMs and suppliers | JLR shutdown and supplier scheme (UK, Slovakia) | Company filings, statistics office, central bank, CMC model | Supplier-level losses and failures |
| Medical devices and pharmaceutical components | Stryker, Boston Scientific, West Pharmaceutical | SEC material-incident filings | Quantified cost; EU plant effects |
| Food and beverage | Asahi (Japan); Fairlife (US, media only) | Company disclosures; Tier 3 | No EU or UK case with Tier 1 outcome |
| OT and refrigeration controller makers | French controller compromise; US PLC advisory | National CERT alert; US advisory title | Units affected; vendor liability |
| Aerospace and defence | Egide (France); RTX passenger-processing product | Exchange release; SEC filing | Duration and cost |
| Consumer goods | Hasbro (US) | SEC filing | Manufacturing effect not stated |
| Electronics and EMS | Foxconn US sites (vendor summary) | Tier 2 | Primary disclosure not retrieved |
| Chemicals, metals and basic materials | Leak-site benchmarks only | Tier 2 | No named in-period case with Tier 1 outcome |
| Textiles and apparel | German finisher insolvency (media) | Tier 3 | Official causal confirmation |

[Dragos - Industrial ransomware Q2 2026][39] [Black Kite - 2026 manufacturing ransomware report][40] [ENISA - Threat Landscape 2026][41] Interpretation: claim-based datasets agree that manufacturing is the most frequently named ransomware victim sector and that European victims rose in 2026 (Benchmark). These count visible claims and disclosures, not attack rates, and cannot be combined because their windows and methods differ.

### Financial-system relevance

The sector matters to a bank through generic, evidence-supported channels: (a) corporate working capital and covenants, [JLR - Q3 FY26 results release][6] as JLR's GBP 1.5 billion quarterly cash outflow, which had cyber and non-cyber causes, shows (Observed); (b) supplier finance and receivables, [JLR - Restart and supplier financing release][3] as JLR used a banking partner to prepay suppliers (Observed); (c) state-backed lending, [UK Government - JLR loan guarantee][9] as with the UK Export Finance (UKEF) guarantee (Observed); (d) insurance gaps, [CMC - JLR categorisation statement][10] as the CMC notes cyber cover typically excludes losses caused by disruption at a key customer (Benchmark); and (e) product liability and market reaction for manufacturers of connected products (Judgement). These are conditional transmission channels and not statements about any institution's exposure, losses, capital or Risk Appetite Framework (RAF) position.

## Key Threats & Top 5 Cyber Attacks

### Selection criteria

Named incidents qualify only if (1) the event or its disclosed outcome falls within 1 September 2025 to 16 October 2026; (2) its existence and main consequence are supported by a Tier 1 source; (3) the affected organisation or its products belong to a Manufacturing subsector in scope; and (4) the case adds a distinct operational or financial lesson. Leak-site and hacktivist claims are not accepted as incidents. Five incidents meet the standard. Threat pathways are shown separately and are patterns, not attacks.

### Threat pathways (patterns)

| Pathway (pattern) | Operational vulnerability | Systemic or concentration translation | Evidence base |
| --- | --- | --- | --- |
| P1 Ransomware and data extortion against enterprise IT | Encryption of ERP, MES, identity and virtualisation layers forces precautionary plant stops | Few groups (ENISA: Qilin, Akira, SafePay) hit many manufacturers; Europe rising | ENISA 2026; Dragos Q2 2026; Black Kite 2026 |
| P2 Destructive misuse of administrative platforms | Endpoint-management or identity tools used to wipe devices across sites | One administrative plane reaches every plant and office | Media reporting on Stryker; CISA alert (organisation unnamed) |
| P3 Internet-exposed OT and fielded products | End-of-life or default-configured controllers reachable online | A manufacturer's installed base becomes a fleet-wide exposure | CERT-FR alert; US PLC advisory |
| P4 Supplier and service-provider compromise | Managed IT, integrators and component suppliers carry access or single-source parts | One provider reaches many customers | Egide; ICS ecosystem counts; West Pharmaceutical |
| P5 Data theft, intellectual-property and export-control exposure | Exfiltration from engineering and corporate systems | Trade-secret, export-control and personal-data liabilities follow production loss | Asahi; West Pharmaceutical; ENISA exfiltration share |

[ENISA - Threat Landscape 2026][41] ENISA recorded manufacturing as the fourth most affected EU sector (6.9% of 8,257 incidents in 2025) but the largest share of ransomware claims (25.2%), led by Qilin, Akira and SafePay; it also observed a shift towards exfiltration (73.3% of technique observations) over encryption (13.7%) and more unconfirmed hacktivist claims against manufacturing OT (Benchmark). [Dragos - Industrial ransomware Q2 2026][39] Dragos counted 747 manufacturing incidents in Q2 2026 (about 65% of 1,140 industrial incidents) and 117 in the ICS ecosystem of engineering firms, integrators and equipment makers (Benchmark). [Black Kite - 2026 manufacturing ransomware report][40] Black Kite reports machinery (15.2%), fabricated metal (11.2%), transport equipment (9.2%), chemicals (9.2%), electronics (8.8%) and food (7.8%) as the most frequently named manufacturing subsectors since 2023 (Benchmark). [Manufacturing Dive - IBM X-Force 2026 findings][42] A vendor incident-response dataset relayed by trade media also ranked manufacturing the most attacked industry in 2025, with exploitation of public-facing applications the leading entry route (context, Tier 3).

### Top 5 named incidents in the period

| # | Incident | Subsector | Place and date | Operational vulnerability | Consequence | Evidence strength | Sector relevance |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Jaguar Land Rover shutdown | Automotive OEM | UK and Slovakia; from early September 2025 | Enterprise systems shut down proactively; production dependent on IT | About five weeks of halted production; GBP 260 million cyber costs over two quarters; officially recorded motor-vehicle output fall; state-guaranteed loan | Company filings, ONS, Bank of England, CMC | Highest: supplier cascade and output effect |
| 2 | Asahi Group ransomware | Beverages and food | Japan; from 29 September 2025 | Data-centre network entered via network equipment at a group site | Shipments halted; about JPY 40 billion 2025 impact; results delayed five months; up to about 1.9 million records potentially exposed | Company disclosures | High: process manufacturer recovery tail |
| 3 | Stryker global IT disruption | Medical devices | Global (US-based); from 11 March 2026 | Global IT disruption; media report a device wipe through an endpoint-management platform (not confirmed by the company) | Material Q1 effect; manufacturing network and ordering restored by 9 April 2026 | SEC filings; media-reported claim unconfirmed | High: material effect on a global manufacturing network |
| 4 | Boston Scientific outage | Medical devices | Global; from 25 August 2026 | Unauthorised activity in IT systems; network outage | Manufacturing, ordering and shipping disrupted; guidance unlikely to be met | SEC material-incident filing | High: material guidance effect |
| 5 | Refrigeration controller compromise | OT and refrigeration equipment makers | France (other EU states reported); 11-13 October 2026 | Internet-reachable, partly end-of-life controllers | Numerous compromises; hundreds of stores affected per relayed official statements | National CERT alert; Tier 3 scale | High: product fleet becomes exposure |

**1. Jaguar Land Rover (September 2025).** [JLR - Statement on cyber incident, 2 September 2025][1] On 2 September 2025 JLR said it had proactively shut down its systems and that retail and production were disrupted (Observed). [JLR - Restart and supplier financing release][3] [JLR - Q3 FY26 volumes release][5] It restarted on a phased basis from 8 October 2025 and production returned to normal by mid-November (Observed). The case-study section reconstructs the case in full.

**2. Asahi Group (September 2025).** [Asahi - Investigation results, 27 November 2025][16] Asahi found encrypted files at about 07:00 on 29 September 2025, disconnected its network and isolated the data centre by 11:00; the intruder had entered through network equipment at a group site and deployed ransomware to servers and some PCs; impact was limited to systems managed in Japan (Observed). [Asahi - Business progress update, February 2026][17] Sales of its Japanese brewery, soft-drink and food units in October-December 2025 were roughly 80%, 70% and 90% of the prior year, and the FY2025 results announcement was postponed (Observed). [Asahi - FY2025 results briefing Q&A][19] [Asahi - Business progress update, May 2026][18] The company estimated a 2025 impact of about JPY 40 billion and reported Japanese brewery sales at 84% of the prior year in January-March 2026 (Observed). [Jiji via Nippon.com - Asahi 2025 results][20] Results for 2025 were published on 8 July 2026 (Observed, Tier 3 corroboration of company data).

**3. Stryker (March 2026).** [Stryker - Form 8-K/A, 9 April 2026][21] Stryker determined that an incident identified on 11 March 2026 had a material impact on operations and Q1 2026 results, and reported its global manufacturing network and its ordering and distribution systems restored by 9 April 2026 (Observed). [MedTech Dive - Stryker disruption report][23] [The Record - CISA and FBI endpoint-management guidance][24] Trade media describe a wipe of devices through a legitimate endpoint-management platform, claimed by a group they describe as Iran-linked; the claim and mechanism are not confirmed by the company (Observed; claim unconfirmed). [Stryker - Q1 2026 results release][22] Stryker maintained full-year guidance (Observed).

**4. Boston Scientific (August-September 2026).** [Boston Scientific - Form 8-K, 26 August 2026][26] Boston Scientific identified unauthorised activity in IT systems on 25 August 2026 that disrupted order processing and shipping (Observed). [Boston Scientific - Form 8-K Item 1.05, 8 September 2026][27] On 8 September 2026 it reported that manufacturing had also been disrupted and had resumed at most facilities, that a material impact on Q3 and full-year results was likely and that it was unlikely to meet guidance (Observed). [Reuters via Business Insurance - Boston Scientific guidance][29] Reuters reported a 2.3% share-price fall on the day of the guidance statement (Observed, Tier 3). [MedTech Dive - Boston Scientific manufacturing report][28] Trade media report that new remote-monitoring activations for some implanted cardiac devices were affected (Observed, Tier 3).

**5. Refrigeration controller compromise (October 2026).** [CERT-FR - Refrigeration controller alert][35] CERT-FR, the French national computer emergency response team, reported numerous compromises of remote controllers for refrigeration installations (Danfoss AK-SC and AK-SM series, Copeland and Dixell xweb) on 12-13 October 2026, warned that campaigns were probably still under way and advised removing internet exposure and resetting compromised units (Observed). [ComplexDiscovery - French refrigeration incident synthesis][36] Media relaying the French finance minister put the number of affected supermarkets at about 700; vendors described affected units as outdated or end-of-life; no group had claimed responsibility (Observed, Tier 3 relay). Interpretation: this is a direct OT compromise, but of manufacturers' products in customer premises; the product-security, liability and reporting consequences fall on the manufacturers (Judgement).

### Considered but not selected

- [West Pharmaceutical - Form 8-K Item 1.05, May 2026][30] West Pharmaceutical Services (May 2026): data exfiltrated, systems encrypted and global operations disrupted, with manufacturing restarting progressively (Observed). Not selected because its pathway duplicates incident 4; used as pattern evidence for P4 and P5 and in Scenario 3.
- [Egide - Cyber incident release, 9 October 2026][34] Egide (October 2026): a French listed supplier of hermetic packages for sensitive electronic components was hit through an external IT provider, leading to a precautionary partial interruption at Bollène (Observed). Not selected because no outcome is yet disclosed; used in Scenario 3 and the dependency analysis.
- [Hasbro - Form 8-K, 1 April 2026][31] [Hasbro - Release of 23 April 2026][32] Hasbro (March 2026): systems taken offline with order, shipping and invoicing delays and guidance reiterated; manufacturing is not mentioned (Observed).
- [RTX - Form 8-K on MUSE incident][37] RTX (September 2025): ransomware on systems supporting its passenger-processing product disrupted European airports; RTX reported no material impact (Observed). Relevant as a manufacturer's software product acting as a shared dependency; used as a cross-sector analogue in Scenario 1.
- [Cybersecurity Dive - Fairlife production halt][33] [BleepingComputer - Bridgestone Americas incident][38] [CircleID - Zego insolvency report][48] Fairlife (US dairy, July 2026), Bridgestone Americas (September 2025) and a German textile finisher's insolvency (2026) are recorded only from Tier 3 sources and are excluded as named incidents.

Shortfall statement: five incidents meet the standard, but only two (JLR and the French controller case) are in the EU or UK. This reflects disclosure asymmetry: US securities rules require material-incident filings, while most EU manufacturers are private or disclose less detail. It is not evidence that EU manufacturers are less affected; [Black Kite - 2026 manufacturing ransomware report][40] [Dragos - Industrial ransomware Q2 2026][39] claim-based data show European manufacturing victims rising in 2026 (Benchmark).

## Financial Impact: Manufacturing

### Bottom line

[JLR - Q2 FY26 results release][4] [Asahi - FY2025 results briefing Q&A][19] [Boston Scientific - Form 8-K Item 1.05, 8 September 2026][27] Public financial evidence is concentrated in a few listed companies and is dominated by lost output and cash rather than by response cost (Judgement). [CMC - JLR categorisation statement][10] The only economy-wide estimate is modelled, for one UK event (Benchmark). [Bundestag - Drucksache 21/8046][47] No official source attributes a supplier insolvency to a cyber incident, and the German Government states it holds no such information (Observed).

### Public operational and financial outcomes

| Case | Metric type | Value | Period | Population | Comparability note |
| --- | --- | --- | --- | --- | --- |
| JLR | Cyber-related exceptional costs | GBP 196 million (Q2) and GBP 64 million (Q3) | July-December 2025 | One OEM | Direct costs only; full year not disclosed |
| JLR | Quarterly revenue change | -24% (Q2) and -39% (Q3) | July-December 2025 | One OEM | Q2: stoppage and Jaguar wind-down; Q3: also tariffs and China |
| JLR | Free cash flow | GBP -791 million (Q2), GBP -1.5 billion (Q3) | July-December 2025 | One OEM | Includes non-cyber drivers |
| JLR | Wholesale volume change | -43.3% (Q3) | October-December 2025 | One OEM | Provisional; several causes |
| JLR event | Modelled UK loss | GBP 1.9 billion (range 1.6-2.1) | Late August 2025 to early January 2026 | UK organisations | Modelled; excludes overseas and data losses |
| UK motor vehicle output | Monthly output change | -28.6% | September 2025 | NACE 29, UK | Statistics office relays trade-body attribution |
| Asahi | Total 2025 impact | About JPY 40 billion | Calendar 2025 | One beverage and food group | Core operating profit decline plus JPY 17 billion incident-related expenses |
| Stryker | Materiality | Material effect on Q1 2026; guidance kept | Q1 2026 | One device maker | Not quantified |
| Boston Scientific | Guidance | Q3 and full-year 2026 guidance unlikely to be met | Q3 2026 | One device maker | Not quantified; results due 28 October 2026 |
| Hasbro | Revenue timing | Some Q2 impact; guidance reiterated | Q2 2026 | One consumer-goods maker | Not quantified |

[JLR - Q2 FY26 results release][4] [JLR - Q3 FY26 results release][6] JLR booked GBP 196 million of cyber-related exceptional costs in Q2 and GBP 64 million in Q3 of its fiscal year 2025/26; Q2 revenue fell 24% to GBP 4.9 billion and Q3 revenue 39% to GBP 4.5 billion; free cash outflow was GBP 791 million and GBP 1.5 billion (Observed). [TMPV - Q4 FY26 results release][7] Full-year free cash outflow was GBP 2.2 billion and pre-tax profit before exceptional items fell to GBP 14 million from GBP 2.5 billion (Observed; several causes). [Asahi - FY2025 results briefing Q&A][19] Asahi's JPY 40 billion combines a fall in core operating profit and JPY 17 billion of expenses for inventory disposal, restoration staff and cancelled promotions (Observed). [CMC - JLR categorisation statement][10] The CMC estimate is a scenario model using public data and expert input, with UK operations only, assuming about GBP 108 million of weekly loss at JLR and roughly 1,000 tier-1 suppliers affected on the same profile (Benchmark).

Comparability: these values cannot be summed or averaged. They differ in currency (GBP, JPY), statistic type (accounting expense, revenue change, cash flow, modelled loss, guidance statement), population and period. The only derived figure in this report, GBP 260 million, adds two quarters of the same JLR expense line. No sector-wide loss estimate is produced.

### Impact types: what is and is not publicly evidenced

| Impact type | Public evidence in scope | Status |
| --- | --- | --- |
| Production stoppage | JLR about five weeks; Stryker about four weeks to full restoration; Boston Scientific partial | Observed for named cases |
| Delivery and order backlog | JLR Q3 wholesales -43.3%; Asahi sales ratios; Hasbro delays | Observed |
| Response, recovery and incident-related cost | JLR GBP 260 million over two quarters; Asahi JPY 17 billion of incident-related expenses incl. inventory write-offs and restoration staff | Observed for two companies |
| Revenue effect | JLR revenue falls (mixed causes); Asahi lost margin; Boston Scientific guidance | Partly attributable |
| Working capital and liquidity | JLR cash outflow, bridge facility and supplier prepayment | Observed |
| Supplier cascade | CMC model of over 5,000 UK organisations (also given as more than 2,700) | Modelled only |
| Supplier insolvency | No official attribution; German Government holds no data | Not evidenced |
| Ransom | No ransom disclosed by any named company | Not evidenced |
| Insurance | CMC notes cover gaps for customer-side disruption; no claim values disclosed | Qualitative only |
| Regulatory and data | Asahi personal-data notification; Egide CNIL notification | Observed; no fines in period |
| Macro-economic | ONS and Bank of England record JLR output effect | Observed |
| Government support | UKEF guarantee for up to GBP 1.5 billion | Observed |

### Financial-system transmission (conditional channels)

- **Corporate liquidity and covenants.** [JLR - Q2 FY26 results release][4] [TMPV - Q4 FY26 results release][7] JLR signed a GBP 2 billion bridge facility on 22 September 2025, secured a GBP 1.5 billion UKEF-guaranteed loan in October and held GBP 6.9 billion of liquidity at 31 March 2026 with the guaranteed loan undrawn (Observed). [JLR - Q2 FY26 results release][4] [JLR - Q3 FY26 results release][6] [TMPV - Q4 FY26 results release][7] The undrawn bridge amount fell from GBP 2.0 billion at 30 September 2025 to GBP 1.5 billion at 31 December 2025 and GBP 1.0 billion at 31 March 2026 (Observed). Judgement: a large manufacturer's first financial response to a multi-week stop is to draw or arrange bank liquidity; the bank-relevant signals are facility drawdown and covenant headroom.
- **Supplier finance and receivables.** [JLR - Restart and supplier financing release][3] JLR's scheme, run with a banking partner, prepaid qualifying suppliers shortly after order instead of on 60-day terms, accelerating payment by up to 120 days, and reimbursed financing costs (Observed); [JLR - Q2 FY26 results release][4] the Q2 release describes a GBP 500 million financing solution (Observed). Judgement: supply-chain finance programmes and receivables lines are where supplier stress becomes visible first.
- **State-backed lending.** [UK Government - JLR loan guarantee][9] The UKEF Export Development Guarantee typically covers up to 80% of lender risk; the JLR loan runs for five years (Observed). [CMC - JLR categorisation statement][10] The CMC recommends that government define thresholds for future support (Benchmark).
- **Insurance gap.** [CMC - JLR categorisation statement][10] The CMC states that cyber insurance typically covers an insured's own losses and supplier failure but not disruption at a key customer (Benchmark). Judgement: tier-1 to tier-3 suppliers may carry uninsured revenue loss when a large customer stops.
- **Macro and sector output.** [ONS - GDP monthly estimate, September 2025][11] [Bank of England - Monetary Policy Report, November 2025][13] ONS recorded a 28.6% fall in UK motor-vehicle output in September 2025, contributing -0.17 percentage points to a 0.1% fall in monthly GDP, and the Bank of England cited the JLR disruption as one reason for weaker Q3 growth (Observed).
- **Product liability and fleet remediation.** [CERT-FR - Refrigeration controller alert][35] [EUR-Lex - Product Liability Directive][66] Compromise of fielded controllers creates replacement, warranty and potential liability costs for manufacturers, which the revised liability directive extends to software and missing security updates (Judgement based on observed legal text).

## Financial Impact: Worst-Case Scenarios

The three scenarios below are structured stress narratives, not forecasts or loss estimates for any institution. No probabilities are assigned because no defensible external basis exists.

### Scenario 1 - Common digital-dependency failure

- **Trigger (Assumption).** [The Record - CISA and FBI endpoint-management guidance][24] [CISA - Endpoint management hardening alert][25] A multi-day loss or destructive misuse of a common enterprise platform - identity or endpoint management, a manufacturing execution system (MES) or enterprise resource planning (ERP) service, or an electronic data interchange (EDI) or supplier-portal service - used by many manufacturers and their suppliers.
- **Affected service.** Order-to-cash, production scheduling, logistics release, quality release and supplier payment.
- **Propagation pathway.** [RTX - Form 8-K on MUSE incident][37] A manufacturer's software product running on many customer networks was disrupted at once in September 2025, forcing customers onto manual processes (Observed; cross-sector analogue, as the customers were airports). [Dragos - Industrial ransomware Q2 2026][39] Dragos found that operational disruption follows when enterprise and virtualisation systems that OT depends on are lost (Benchmark).
- **Impact drivers.** Simultaneous plant stops on precaution, missed delivery windows, manual workarounds and backlog.
- **Financial transmission.** Correlated output and delivery gaps across counterparties, concurrent drawing of working-capital lines, deferred revenue and disputes over delay clauses.
- **Early signposts.** Provider outage or breach notices; government alerts on platform misuse; additions of ERP or file-transfer products to known-exploited-vulnerability lists; leak-site claims against platform users.
- **Limiting conditions.** Offline production fallback, tenant isolation and documented manual release processes.
- **Assumptions.** Platform unavailable for three to ten days; no OT compromise; severity is an analytical stress choice because no multi-firm platform outage was observed in the period; durations illustrative; not a forecast; no probability assigned.
- **Management questions.** Which shared enterprise platforms do the largest manufacturing counterparties depend on to release production, and is there evidence that they can produce and ship for two weeks without them?

### Scenario 2 - Targeted operational disruption

- **Trigger (Assumption).** [JLR - Statement on cyber incident, 2 September 2025][1] [Boston Scientific - Form 8-K Item 1.05, 8 September 2026][27] Ransomware or a destructive intrusion at one high-volume original equipment manufacturer (OEM) or tier-1 supplier triggers a precautionary global shutdown, as at JLR and Boston Scientific.
- **Affected service.** Vehicle, device or consumer-goods production and delivery; supplier call-offs.
- **Propagation pathway.** [CMC - JLR categorisation statement][10] Just-in-time call-offs stop and tier-1 to tier-3 suppliers idle on the same profile; dealers and logistics lose volume (Benchmark). [JLR - Restart and supplier financing release][3] Restart is phased by plant (Observed).
- **Impact drivers.** Weeks of lost output, fixed-cost absorption, expedited freight on restart and recovery overtime.
- **Financial transmission.** [JLR - Q2 FY26 results release][4] [UK Government - JLR loan guarantee][9] OEM cash outflow in the hundreds of millions or more per quarter, emergency bank facilities and possibly state-backed lending; supplier liquidity stress (Observed for JLR).
- **Early signposts.** Company incident notices and exchange or securities filings; announcements extending production pauses; supplier lay-off or short-time work notices; requests for state support.
- **Limiting conditions.** [Stryker - Form 8-K/A, 9 April 2026][21] Segmented estates restored within weeks, as at Stryker (Observed); buffered inventory and multi-sourcing reduce cascade.
- **Assumptions.** Four- to eight-week stop at one large manufacturer, anchored to JLR's about five weeks plus distribution lag; not a forecast; no probability assigned.
- **Management questions.** For the largest manufacturing counterparties, how many weeks of production stop can liquidity absorb, and which suppliers depend on them for most of their revenue?

### Scenario 3 - Third- or fourth-party supply-chain concentration

- **Trigger (Assumption).** [CERT-FR - Refrigeration controller alert][35] [Egide - Cyber incident release, 9 October 2026][34] Compromise or exploitation of a shared supplier layer: an OT vendor's fielded controllers, a system integrator or IT service provider with access to customers' plants, or a widely used component supplier.
- **Affected service.** Field equipment performance and safety at customers; customer production lines; component availability.
- **Propagation pathway.** [CERT-FR - Refrigeration controller alert][35] Numerous controllers from two manufacturers were compromised at once because they were reachable online (Observed). [Egide - Cyber incident release, 9 October 2026][34] A component supplier was disrupted through its IT provider (Observed). [Dragos - Industrial ransomware Q2 2026][39] 117 ransomware incidents hit engineering firms, integrators and equipment makers in one quarter (Benchmark).
- **Impact drivers.** Fleet-wide remediation, customer losses, regulator reporting, product recall or replacement of end-of-life units.
- **Financial transmission.** Correlated customer claims, warranty and liability costs, supply shortages for downstream manufacturers.
- **Early signposts.** National CERT alerts naming products; exchange disclosures citing an IT provider; end-of-support notices; leak-site claims against integrators.
- **Limiting conditions.** [ComplexDiscovery - French refrigeration incident synthesis][36] Vendors state patches exist for current firmware and that affected units were mostly outdated (Observed, Tier 3 relay); customer network segmentation.
- **Assumptions.** Exposure persists in end-of-life fleets; customer segmentation incomplete; severity anchored to the national-scale controller campaign; not a forecast; no probability assigned.
- **Management questions.** Which counterparties sell connected controllers or machinery with long field lives, and do they track internet exposure and end-of-support status of their installed base?

### Scenario distinctness

| Dimension | Scenario 1 | Scenario 2 | Scenario 3 |
| --- | --- | --- | --- |
| Point of failure | Shared enterprise platform | One large manufacturer | Shared supplier or product fleet |
| Breadth | Many firms at once | One firm, deep supplier cascade | Many customers of one supplier |
| Main cost driver | Correlated delay | Lost output and liquidity | Remediation, liability and shortages |
| Key limiting condition | Offline fallback | Segmentation and buffers | Exposure management and support periods |

## Case Study: Jaguar Land Rover Cyber Incident

### Why this case

| Candidate | Recency | Sector relevance | Causal clarity | Disclosed outcome | Evidence quality | Decision |
| --- | --- | --- | --- | --- | --- | --- |
| Jaguar Land Rover | September 2025 to May 2026 | Highest (automotive OEM, supplier cascade) | High | Costs, volumes, cash, macro, government support | Company, statistics office, central bank, CMC | Selected |
| Asahi Group | September 2025 to July 2026 | High (process manufacturing) | High | Costs, sales, data | Company disclosures | Top 5 incident |
| Stryker | March to April 2026 | High (medical devices) | Medium | Materiality only | SEC filings | Top 5 incident; Scenario 2 |
| Boston Scientific | August to October 2026 | High (medical devices) | Medium | Guidance effect | SEC filings | Top 5 incident; results pending |
| West Pharmaceutical | May 2026 | Medium-high | Medium | Restart only | SEC filing | Pattern and scenario evidence |
| Refrigeration controllers | October 2026 | High (OT products) | Low (days old) | None official | CERT-FR | Monitor for next edition |

[JLR - Q2 FY26 results release][4] [UK Government - JLR loan guarantee][9] [ONS - GDP monthly estimate, September 2025][11] [CMC - JLR categorisation statement][10] Judgement: JLR is the only in-period case combining company filings over four quarters, a statistics-office and central-bank record of output effects, a government loan guarantee, a supplier-financing response and an independent loss model, and it is in the UK.

### Timeline

| Date | Event (Observed) |
| --- | --- |
| Late August to 2 September 2025 | Incident begins; JLR proactively shuts down systems; production and retail disrupted |
| 4 September 2025 | Unconfirmed claim of responsibility reported; NCA engaged |
| 9 September 2025 | House of Commons Business and Trade Committee writes to JLR on supplier impact and taxpayer support |
| 22 September 2025 | GBP 2 billion bridge facility signed |
| 28 September 2025 | Government announces guarantee to unlock up to GBP 1.5 billion of bank lending |
| 7 October 2025 | Restart sequence and supplier financing scheme announced; Q2 wholesales down 24.2% |
| 8 October 2025 | Phased restart begins with engine and battery assembly |
| 22 October 2025 | CMC classes event as Category 3 and models GBP 1.9 billion UK loss |
| 24 October 2025 | SMMT reports September car output down 27.1% |
| October 2025 | GBP 1.5 billion UKEF-guaranteed loan secured |
| November 2025 | Bank of England cites the disruption in weaker Q3 growth |
| 13 November 2025 | ONS records 28.6% fall in motor-vehicle output for September |
| 14 November 2025 | Q2 results: GBP 196 million cyber-related costs |
| Mid-November 2025 | Production back to normal levels |
| 5 January 2026 | Q3 wholesales down 43.3% |
| 5 February 2026 | Q3 results: GBP 64 million further cyber-related costs |
| 14 May 2026 | Full-year results: UKEF-guaranteed loan undrawn; production recovered in Q4 |

[CMC - JLR categorisation statement][10] [JLR - Statement on cyber incident, 2 September 2025][1] [ITV - JLR claim of responsibility report][15] [Business and Trade Committee - Letter to JLR, 9 September 2025][14] [JLR - Q2 FY26 results release][4] [UK Government - JLR loan guarantee][9] [JLR - Restart and supplier financing release][3] [JLR - Q2 FY26 volumes release][2] [SMMT - September 2025 vehicle output][12] [Bank of England - Monetary Policy Report, November 2025][13] [ONS - GDP monthly estimate, September 2025][11] [JLR - Q3 FY26 volumes release][5] [JLR - Q3 FY26 results release][6] [TMPV - Q4 FY26 results release][7] The timeline is compiled from company statements and results, the government release, the parliamentary letter, the CMC statement, ONS, SMMT and Bank of England publications; the claim of responsibility is recorded only as a media-reported claim (Observed).

### Disruption mechanism

[JLR - Statement on cyber incident, 2 September 2025][1] JLR's first statement says it took immediate action by proactively shutting down its systems (Observed). [CMC - JLR categorisation statement][10] The CMC notes that fewer technical details have emerged than usual, that the extent of OT impact is unclear and that the early-October restart may indicate limited OT impact (Benchmark). [JLR - Statement on cyber incident, 2 September 2025][1] [JLR - Q2 FY26 results release][4] [ITV - JLR claim of responsibility report][15] No attribution or initial access route was published in company releases; a criminal group's claim reported by media was not confirmed by JLR or the National Crime Agency (NCA) (Observed). Interpretation: the evidence supports an IT-dependency stop - production halted because the enterprise systems that schedule, supply and release production were shut down - rather than a demonstrated manipulation of plant control systems (Judgement).

### Operational consequences

- [JLR - Q2 FY26 volumes release][2] [JLR - Restart and supplier financing release][3] Production stopped across UK plants and Nitra; restart began on 8 October 2025 with engine and battery assembly, then Slovakia and Solihull (Observed).
- [JLR - Q3 FY26 volumes release][5] [JLR - Q3 FY26 results release][6] Production returned to normal by mid-November, but vehicle distribution took longer; Q3 wholesales fell 43.3%, with Europe down 47.6% and North America down 64.4% (Observed; tariffs and model wind-down also contributed).
- [JLR - Restart and supplier financing release][3] JLR set up a supplier help desk, settled invoices manually and re-established automated supplier payments in the week of 7 October (Observed).

### Public financial, macro and government outcomes

[JLR - Q2 FY26 results release][4] [JLR - Q3 FY26 results release][6] Cyber-related exceptional costs were GBP 196 million in Q2 and GBP 64 million in Q3 (Observed). [TMPV - Q4 FY26 results release][7] Full-year revenue fell 20.9% to GBP 22.9 billion and free cash outflow reached GBP 2.2 billion, with production stoppages one of several cited causes (Observed). [UK Government - JLR loan guarantee][9] The government guarantee was explicitly framed as support for the supply chain and skilled jobs (Observed). [ONS - GDP monthly estimate, September 2025][11] [SMMT - September 2025 vehicle output][12] [Bank of England - Monetary Policy Report, November 2025][13] ONS recorded the September fall in motor-vehicle output and relayed SMMT's attribution to the stoppage, and the Bank of England cited the disruption as one reason for weaker Q3 growth (Observed). [CMC - JLR categorisation statement][10] The CMC modelled a UK loss of GBP 1.9 billion and over 5,000 affected organisations (Benchmark).

### Recovery constraints

[JLR - Q3 FY26 volumes release][5] [JLR - Q3 FY26 results release][6] Restoring production took about five weeks and restoring distribution took longer, so the financial effect extended across two quarters (Observed). [CMC - JLR categorisation statement][10] The CMC identifies the recovery profile, OT impact and failure of hard-to-replace suppliers as the main sensitivities of the loss estimate (Benchmark). [JLR - Annual Report 2026 web summary][8] JLR's annual report states the company is still investing in its IT systems and has learned lessons, without quantifying the full-year cost (Observed).

### Applicability of regulation to the case

[EUR-Lex - NIS2 Directive][49] Motor-vehicle manufacturing (NACE C29) is an Annex II NIS2 activity, so JLR's Slovak manufacturing entity could fall within national NIS2 law subject to size and national transposition; this run did not confirm its classification (Judgement). [legislation.gov.uk - NIS Regulations 2018 schedules][95] In the UK, manufacturing is not an essential-service sector under the NIS Regulations 2018 (Observed), and [UK Parliament - Cyber Security and Resilience Bill page][75] the Cyber Security and Resilience Bill had not received Royal Assent at the cut-off (Observed). [Official Journal - UN Regulation No. 155][71] As a vehicle manufacturer, JLR must hold a cyber security management system certificate under UN Regulation No. 155 for type approval (Observed); the regulation addresses vehicle cybersecurity, not plant continuity.

### Sector lesson and read-across

- [JLR - Statement on cyber incident, 2 September 2025][1] [CMC - JLR categorisation statement][10] [Dragos - Industrial ransomware Q2 2026][39] For manufacturers: plant OT can be intact while production stops; IT-OT dependency mapping and the ability to release production manually determine stop length (Judgement).
- [JLR - Restart and supplier financing release][3] [UK Government - JLR loan guarantee][9] [CMC - JLR categorisation statement][10] For supply chains: one OEM's stop transfers liquidity stress to suppliers within weeks; customer-funded prepayment and state guarantees were used to bridge it (Judgement).
- [JLR - Q2 FY26 results release][4] [JLR - Restart and supplier financing release][3] [UK Government - JLR loan guarantee][9] For banks (generic): counterparty liquidity, supplier-finance programmes and state-guarantee channels are where such an event becomes visible (Judgement).

### What the case does not establish

The case does not show the initial access route, the attacker's identity, any ransom, the OT state, the full-year cyber cost, insurance recoveries, or any supplier insolvency caused by the event. The GBP 1.9 billion figure is modelled. The case concerns one automotive OEM with just-in-time supply; process and buffered-inventory manufacturers may behave differently.

## Systemic Dependencies & Regulatory Outlook

### Dependency chains

| Dependency | Evidence | Concentration pathway | Who is exposed |
| --- | --- | --- | --- |
| Enterprise IT that releases production (ERP, MES, identity) | JLR, Asahi, Boston Scientific | Plant stops when enterprise systems stop | Manufacturers, suppliers, dealers |
| Endpoint and identity administration planes | Media reports on Stryker; CISA alert (organisation unnamed) | One administrative tool reaches every device | Multi-site manufacturers |
| OT vendors' installed base | French controller case; US PLC advisory | One product family exposed across many sites | Customers of equipment makers; the makers themselves |
| Integrators, engineering firms and managed IT providers | Dragos ICS ecosystem counts; Egide | One provider's access reaches several plants | Manufacturers using shared service providers |
| Just-in-time supplier tiers | JLR and CMC model | Customer stop transmits to thousands of small suppliers | Tier-1 to tier-3 suppliers and their lenders |
| Manufacturer-supplied software used by customers | RTX passenger-processing product | Product incident becomes customers' outage | Customers in other sectors |

[JLR - Statement on cyber incident, 2 September 2025][1] [Asahi - Investigation results, 27 November 2025][16] [Boston Scientific - Form 8-K Item 1.05, 8 September 2026][27] [Stryker - Form 8-K/A, 9 April 2026][21] [CISA - Endpoint management hardening alert][25] [CERT-FR - Refrigeration controller alert][35] [CISA and partners - PLC advisory AA26-097A][89] [Dragos - Industrial ransomware Q2 2026][39] [Egide - Cyber incident release, 9 October 2026][34] [CMC - JLR categorisation statement][10] [RTX - Form 8-K on MUSE incident][37] Dependencies are named only where a source supports them; market shares of ERP, MES and OT vendors in manufacturing were not retrieved and no platform is described as dominant (Observed and Judgement).

### Regulatory perimeter (status and dates)

| Regime | Jurisdiction | Legal status | Obligation type | Key dates | Applicability to Manufacturing |
| --- | --- | --- | --- | --- | --- |
| NIS2 Directive (EU) 2022/2555 | EU | Binding via national law | Risk management incl. supply chain; 24h, 72h and one-month reporting; management accountability | In force 16 January 2023; transposition 17 October 2024 | Annex II: medical devices and IVD; NACE C26-C30; chemicals; industrial food. Annex I: C21 pharmaceuticals and emergency-list devices. Others only by national extension |
| NIS2 enforcement | EU | Court referral | Penalties requested | Referral 8 July 2026 (IE, ES, FR, NL) | Uneven obligations for multinationals |
| German NIS2 law | Germany | Binding | Registration, measures, reporting | In force 6 December 2025 | 4,739 manufacturing registrations by 30 September 2026 |
| CER Directive (EU) 2022/2557 | EU | Binding via national law | Resilience of designated entities | Transposition 17 October 2024; identification by 17 July 2026 | Manufacturing not a listed sector; food and health entities may be designated |
| Cyber Resilience Act (CRA), Regulation (EU) 2024/2847 | EU | Directly applicable | Vulnerability and incident reporting; later essential requirements | Reporting from 11 September 2026; full application 11 December 2027 | Manufacturers of in-scope products with digital elements; excludes, among others, medical devices, IVD, type-approved vehicles, civil aviation, marine equipment and products made exclusively for national security or defence |
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
| COMAH 2015 and HSE OG86 | Great Britain | Binding duties; guidance | IACS cyber as part of safety | OG86 March 2017 | Major-hazard chemical sites |
| NSI Act 2021 | UK | Binding | Mandatory notification in 17 areas | In force 2022 | Advanced materials, robotics, defence, dual-use |
| MOD Cyber Security Model v4 | UK | Contractual | Def Stan 05-138 controls; flow-down | Updated 6 March 2026 | Defence suppliers |
| PSTI product security regime | UK | Binding | Passwords, vulnerability reporting, update periods | 29 April 2024 | Consumer connected-product makers |
| SEC Item 1.05 and Item 106 | US (comparative) | Binding | Material-incident and annual disclosure | Compliance from December 2023 | US-listed manufacturers |
| CMMC via DFARS | US (comparative) | Binding contract clause | Cybersecurity certification | Effective 10 November 2025; next phase 10 November 2026 | Defence-industrial base incl. foreign subsidiaries |
| FDA section 524B | US (comparative) | Binding statute | Premarket cyber plans, SBOM | 29 March 2023 | Medical-device makers |
| CIRCIA rule; chemical facility standards | US (comparative) | Not final; lapsed | Reporting; chemical security | Rule at White House review 1 October 2026; authority lapsed July 2023 | US manufacturers |

[EUR-Lex - NIS2 Directive][49] [Streamlex - NIS2 Annex II text][50] [European Commission - NIS2 Court referral][51] [European Commission - NIS2 transposition page][52] [BSI - NIS-2 in figures, Q3 2026][45] [BSI - German NIS2 law in force][46] [EUR-Lex - CER Directive][54] [European Commission - CER Court referral (IP/26/910)][53] [ENISA - Single Reporting Platform launch][57] [European Commission - Regulation (EU) 2024/2847 summary][56] [EUR-Lex - Regulation (EU) 2024/2847][55] [Springlex - Regulation (EU) 2024/2847 Article 2][59] [EUR-Lex - Implementing Regulation (EU) 2025/2392][58] [EU-OSHA - Machinery Regulation page][63] [KAN - Machinery cybersecurity requirements brief][64] [EUR-Lex - Machinery Regulation consolidated][65] [ERTICO - Digital Omnibus on AI entry into force][61] [DBT - Explanatory memorandum on Regulation (EU) 2026/1744][60] [euaiact.com - Regulation (EU) 2026/1744 sectoral amendments][62] [EUR-Lex - Product Liability Directive][66] [Inside Privacy - Product liability transposition update][67] [EUR-Lex - Delegated Regulation (EU) 2026/339][68] [European Commission - Data Act page][69] [Official Journal - UN Regulation No. 155][71] [European Commission - GMP Annex 11 consultation][70] [Council of the EU - FDI screening adoption][73] [European Commission - FDI screening publication][74] [UK Parliament - Cyber Security and Resilience Bill page][75] [DSIT - Bill summary factsheet][76] [Home Office - Ransomware proposals response][77] [LGA - Ransomware proposals briefing][78] [HSE - Cyber security for industrial automation and control systems][79] [Cabinet Office - NSI Act notifiable acquisitions guidance][80] [MOD - Cyber Security Model][81] [DSIT - Product security regime guidance][82] [legislation.gov.uk - NIS Regulations 2018 schedules][95] [SEC - Cyber disclosure rules fact sheet][83] [Federal Register - DFARS CMMC final rule][84] [eCFR - 32 CFR Part 170 CMMC Program][96] [FDA - Medical device cybersecurity FAQs][94] [Paubox - CIRCIA final rule status][86] [CISA - CFATS lapse statement][87] [J. J. Keller - CFATS status][88] The table records legal status, obligation type and date basis from the primary instrument or official page where available; dates taken from secondary sources are flagged in the regulatory register (Observed).

### NIS2 scope and obligations for manufacturers

[EUR-Lex - NIS2 Directive][49] [Streamlex - NIS2 Annex II text][50] NIS2 Annex II lists manufacturing of medical devices and in-vitro diagnostic devices and NACE Rev. 2 divisions C26 (computer, electronic and optical products), C27 (electrical equipment), C28 (machinery), C29 (motor vehicles) and C30 (other transport equipment); manufacture and distribution of chemicals under the EU chemicals regulation and industrial food production and processing are separate Annex II sectors; Annex I health covers manufacturers of basic pharmaceutical products and preparations (C21) and of medical devices listed as necessary during a public-health emergency (Observed). [EUR-Lex - NIS2 Directive][49] The directive applies to entities at or above medium-enterprise size, with national discretion to include smaller entities that are sole providers or have significant systemic impact; Annex II entities are important entities unless a Member State designates them essential; management bodies must approve and oversee cybersecurity risk measures and follow training; measures must address supply-chain security; incidents require a 24-hour early warning, a 72-hour notification and a one-month final report; maximum fines are at least EUR 10 million or 2% of worldwide turnover for essential entities and EUR 7 million or 1.4% for important entities (Observed). For metals, basic materials, consumer goods and textiles, no NIS2 route exists unless a Member State extends scope or the entity also performs an in-scope activity (Judgement). Supply-chain duties of in-scope customers reach out-of-scope suppliers through contracts, not law (Judgement).

[European Commission - NIS2 Court referral][51] [European Commission - NIS2 transposition page][52] On 8 July 2026 the Commission referred Ireland, Spain, France and the Netherlands to the Court of Justice, seeking lump-sum and daily penalties; 19 Member States had received reasoned opinions in May 2025 (Observed). [BSI - German NIS2 law in force][46] [BSI - NIS-2 in figures, Q3 2026][45] Germany's law entered into force on 6 December 2025; by 30 September 2026 the BSI recorded 20,373 registrations against about 29,500 expected entities, with 4,739 selecting manufacturing of goods (Observed).

### Product-security, machinery and liability rules

[ENISA - Single Reporting Platform launch][57] [European Commission - Regulation (EU) 2024/2847 summary][56] Since 11 September 2026 manufacturers must report actively exploited vulnerabilities and severe incidents in their products through ENISA's Single Reporting Platform, with a 24-hour early warning and a 72-hour notification; the main essential requirements, vulnerability handling and support-period duties apply from 11 December 2027 (Observed). [EUR-Lex - Regulation (EU) 2024/2847][55] [Springlex - Regulation (EU) 2024/2847 Article 2][59] Products under the medical-device, IVD, vehicle type-approval, civil aviation and marine-equipment regimes, and products developed or modified exclusively for national security or defence, are excluded (Observed). [European Commission - Regulation (EU) 2024/2847 summary][56] [EUR-Lex - Implementing Regulation (EU) 2025/2392][58] Important (Annex III) and Annex IV product categories require standards-based or third-party conformity assessment, and the Commission adopted a technical description of these categories on 28 November 2025, in force from 21 December 2025 (Observed). [EU-OSHA - Machinery Regulation page][63] [KAN - Machinery cybersecurity requirements brief][64] The Machinery Regulation applies from 20 January 2027 and requires machinery to be protected against accidental or intentional corruption from the design stage; a supporting standard was still in development in 2025 (Observed). [DBT - Explanatory memorandum on Regulation (EU) 2026/1744][60] [ERTICO - Digital Omnibus on AI entry into force][61] Regulation (EU) 2026/1744 entered into force on 27 July 2026, deferring high-risk AI obligations for product safety components to 2 August 2028 and moving machinery AI requirements into the Machinery Regulation through delegated acts (Observed). [EUR-Lex - Product Liability Directive][66] [Inside Privacy - Product liability transposition update][67] The revised Product Liability Directive must be transposed by 9 December 2026 and covers software and defects arising from missing security updates (Observed).

### Other regimes relevant to subsectors

- [Official Journal - UN Regulation No. 155][71] Automotive: UN Regulation No. 155 requires a certified cyber security management system covering development, production and post-production for type approval (Observed).
- [European Commission - GMP Annex 11 consultation][70] Pharmaceuticals: the revision of GMP Annex 11 on computerised systems was consulted on until 7 October 2025, with no final adoption evidenced (Observed).
- [HSE - Cyber security for industrial automation and control systems][79] [European Commission - Seveso III implementation report][72] Hazardous processes: HSE treats industrial automation and control system security at COMAH sites as part of plant safety; the Commission's 2025 Seveso III implementation report does not address cyber events as accident initiators (Observed).
- [MOD - Cyber Security Model][81] [Federal Register - DFARS CMMC final rule][84] [eCFR - 32 CFR Part 170 CMMC Program][96] Defence: the MOD Cyber Security Model requires Def Stan 05-138 controls and flow-down to subcontractors; the US Cybersecurity Maturity Model Certification (CMMC) clause has applied since 10 November 2025, and under the programme rule a second phase adding third-party Level 2 assessments starts one year later, on 10 November 2026 (Observed).
- [Council of the EU - FDI screening adoption][73] [European Commission - FDI screening publication][74] [Cabinet Office - NSI Act notifiable acquisitions guidance][80] Strategic manufacturing ownership: the revised EU investment-screening regulation was published on 26 June 2026 and the UK NSI Act requires notification in 17 areas including advanced materials, robotics, computing hardware and military and dual-use (Observed).
- [Home Office - Ransomware proposals response][77] [LGA - Ransomware proposals briefing][78] UK ransomware proposals remain proposals, with no bill identified (Observed).
- [Paubox - CIRCIA final rule status][86] In the US, the incident-reporting rule under the 2022 US statute known as CIRCIA had not been published at the cut-off (Tier 3 only; not confirmed from a primary source). [CISA - CFATS lapse statement][87] [J. J. Keller - CFATS status][88] Chemical facility security authority lapsed in July 2023, with no reauthorisation found (Observed, partly Tier 3).

Not assessed in this run beyond naming: EU Trade Secrets Directive, Dual-Use Regulation, Chips Act, raw-materials regulation, Economic Security Strategy, Medical Devices Regulation guidance, UK Data (Use and Access) Act commencement, UK Market Abuse Regulation, Japan METI factory guidelines, Australia SOCI and the US Cyber Trust Mark. They are recorded as limitations rather than as findings.

### Forward monitoring horizon

| Date or window | Item to monitor |
| --- | --- |
| 28 October 2026 | Boston Scientific Q3 results and updated outlook |
| October-December 2026 | French controller campaign: official counts, vendor remediation, attribution |
| 10 November 2026 | Next CMMC phase for defence suppliers |
| 30 November 2026 | Comment deadline for NIST SP 800-82 Rev. 4 draft |
| 9 December 2026 | Product Liability Directive transposition deadline |
| Late 2026 | UK Cyber Security and Resilience Bill Royal Assent; US CIRCIA final rule |
| 20 January 2027 | Machinery Regulation application |
| 11 December 2027 | Full application of product-security essential requirements |
| 2026-2027 | NIS2 Court cases and national scope extensions; CER designations |

[Boston Scientific - Form 8-K Item 1.05, 8 September 2026][27] [CERT-FR - Refrigeration controller alert][35] [eCFR - 32 CFR Part 170 CMMC Program][96] [NIST - SP 800-82 Rev. 3][92] [Inside Privacy - Product liability transposition update][67] [UK Parliament - Cyber Security and Resilience Bill page][75] [Paubox - CIRCIA final rule status][86] [EU-OSHA - Machinery Regulation page][63] [European Commission - Regulation (EU) 2024/2847 summary][56] [European Commission - NIS2 Court referral][51] The horizon is compiled from the cited filings, alerts and legal sources (Observed).

## Mitigation Strategies & Security Framework

Actions below are sector-informed management priorities derived from public evidence. They are not statements about any institution's control gaps. Role types are generic.

### Evidence-linked action table

| Exposure | Operational vulnerability | Control objective | Action or challenge question | Role type | Horizon |
| --- | --- | --- | --- | --- | --- |
| A1 IT-OT production dependency | Plants stop when ERP, MES or identity stop | Produce and ship safely during IT loss | Ask the largest manufacturing counterparties for evidence of manual production release and tested IT-loss recovery | 1LoD sector risk owner | 0-6 months |
| A2 Administrative planes | Endpoint and identity tools can wipe every device | Constrain destructive administrative actions | Challenge whether counterparty assessments cover multi-administrator approval for wipe actions and separation of admin identities | 1LoD third-party risk | 0-3 months |
| A3 Supplier liquidity cascade | Small suppliers depend on one customer | See and bridge supplier stress early | Map revenue concentration of supplier-finance participants and test a four-week customer stop | 1LoD credit and supply-chain finance | 0-6 months |
| A4 Fielded OT and product fleets | End-of-life controllers reachable online | Know and reduce installed-base exposure | Ask equipment-maker counterparties for exposure monitoring and end-of-support plans | 1LoD sector risk owner | 3-12 months |
| A5 Service providers and integrators | Provider access into plants | Contain provider-borne compromise | Check that counterparties restrict and log provider remote access to OT | 1LoD third-party risk | 3-12 months |
| A6 Product-law readiness | Reporting since September 2026; liability from December 2026 | Meet reporting and liability duties | Ask manufacturing counterparties for reporting procedures and support-period policies | 1LoD credit and legal | 0-6 months |
| A7 Insurance and contracts | Customer-side disruption often uninsured | Align cover and clauses with dependency | Review whether lending and guarantee documentation reflects cyber disruption and notification terms | 1LoD credit and legal | 6-12 months |

| Exposure | Evidence of completion | Residual dependency | External monitoring trigger |
| --- | --- | --- | --- |
| A1 IT-OT production dependency | Documented manual-release procedure; recovery test results | Single ERP or MES instance | Company production-pause notice or exchange filing |
| A2 Administrative planes | Assessment evidence on admin controls | Cloud administration outside counterparty control | Government alert on administrative-tool misuse |
| A3 Supplier liquidity cascade | Concentration map; stress-test record | Lower-tier suppliers outside programme | OEM incident notice; supplier short-time work announcements |
| A4 Fielded OT and product fleets | Exposure and end-of-support register | Customers who do not patch | National CERT alert naming a product family |
| A5 Service providers and integrators | Access inventory and logs | Provider's own security | Exchange disclosure citing an IT provider |
| A6 Product-law readiness | Reporting procedure; support-period statements | National liability laws pending | First enforcement or reporting statistics |
| A7 Insurance and contracts | Documentation review record | Market capacity for supply-chain cover | Insurer product changes; government support thresholds |

[JLR - Statement on cyber incident, 2 September 2025][1] [Asahi - Investigation results, 27 November 2025][16] [Dragos - Industrial ransomware Q2 2026][39] [Stryker - Form 8-K/A, 9 April 2026][21] [The Record - CISA and FBI endpoint-management guidance][24] [CISA - Endpoint management hardening alert][25] [CMC - JLR categorisation statement][10] [JLR - Restart and supplier financing release][3] [Bundestag - Drucksache 21/8046][47] [CERT-FR - Refrigeration controller alert][35] [ComplexDiscovery - French refrigeration incident synthesis][36] [Egide - Cyber incident release, 9 October 2026][34] [CISA and partners - PLC advisory AA26-097A][89] [ENISA - Single Reporting Platform launch][57] [EUR-Lex - Product Liability Directive][66] [EUR-Lex - NIS2 Directive][49] Each action links to an exposure evidenced in the preceding sections: A1 to the JLR, Asahi and Dragos evidence; A2 to media reporting on Stryker and the CISA alert; A3 to the CMC model, the JLR supplier scheme and the German Government answer; A4 to the CERT-FR alert and vendor end-of-life statements; A5 to Egide and the Dragos ICS ecosystem counts; A6 to the product-security and liability rules; A7 to the CMC insurance finding and NIS2 supply-chain duties (Action).

[CERT-FR - Refrigeration controller alert][35] CERT-FR's recommended actions for affected controllers are directly reusable for any OT product fleet: remove internet exposure, restrict access to secured remote connections, apply vendor hardening and firmware updates, change default credentials and treat a reset alone as insufficient (Observed).

### Framework reference mapping (voluntary or contractual)

| Action | NIST CSF 2.0 function | Other references |
| --- | --- | --- |
| A1 IT-OT production dependency | Identify and Recover | NIST SP 800-82; IEC 62443; ISO 22301 |
| A2 Administrative planes | Protect | ISO/IEC 27001 and 27002; CIS Controls |
| A3 Supplier liquidity cascade | Govern (supply-chain risk) | ISO/IEC 27036; VDA ISA and TISAX for automotive |
| A4 Fielded OT and product fleets | Identify and Protect | IEC 62443-4-1 and 4-2; ETSI EN 303 645; SBOM practice |
| A5 Service providers and integrators | Protect and Detect | IEC 62443-2-4; MITRE ATT&CK for ICS for detection mapping |
| A6 Product-law readiness | Govern and Respond | ISO/SAE 21434 for vehicles |
| A7 Insurance and contracts | Govern | ISO/IEC 27036 |

[NIST - SP 800-82 Rev. 3][92] [NIST - CSF 2.0 Manufacturing Profile draft][93] [HSE - Cyber security for industrial automation and control systems][79] [MOD - Cyber Security Model][81] The mapping is an analyst reference aid: NIST SP 800-82 Rev. 3 is final with a Rev. 4 draft open for comment, the NIST manufacturing profile for CSF 2.0 was an initial public draft, and frameworks are voluntary or contractual, not legal requirements; other standards are named as vocabularies and their texts were not reviewed in this run (Judgement).

### 1LoD and Risk Committee challenge questions

- Which of our largest manufacturing counterparties could release production and ship for two weeks without their ERP, MES or identity services, and what evidence shows it?
- Which suppliers in our supply-chain finance and receivables programmes earn most of their revenue from a single manufacturer, and how would a four-week stop at that manufacturer appear in our early-warning indicators?
- Do counterparty assessments test controls over destructive administrative actions, given media reports of a 2026 device wipe through an endpoint-management platform?
- Which equipment-maker counterparties have large installed bases of connected controllers, and do they monitor internet exposure and end-of-support status?
- How would counterparties meet product vulnerability reporting duties that started in September 2026 and liability rules due from December 2026?
- Where cyber insurance excludes disruption at a key customer, how is that gap reflected in credit assessment?

### Monitoring triggers

- A production-pause notice, exchange filing or material-incident report by a large manufacturer.
- A national CERT or joint government alert naming an OT product family or an administrative tool.
- Supplier short-time work, lay-off or insolvency announcements linked by an official source to a customer's cyber incident.
- A request for or grant of state support to a manufacturer or its supply chain after a cyber incident.
- Legal milestones: UK Bill Royal Assent; national liability transposition; first product-security enforcement; NIS2 Court rulings.

## Methodology and Evidence Limitations

**Method.** Wide discovery across automotive, aerospace and defence, chemicals, pharmaceuticals and medical devices, food and beverage, electronics, machinery, metals and basic materials, consumer goods, textiles, OT vendors, enterprise software, integrators and managed providers, using English, French and German queries and the English-language releases of Japanese companies, followed by primary-source research in company filings, government, statistics, central-bank, parliamentary and legal sources. Sources were classified as Tier 1 (official, legal, regulatory, affected organisation, statistics and central bank), Tier 2 (independent research with disclosed method) or Tier 3 (media, commentary and reproductions). Tier 3 sources never stand alone for a material finding; where Tier 3 detail is shown it is labelled. Publication date and observation period are recorded separately; repeated reporting of one incident is counted once. All sources were accessed on 16 October 2026. Leak sites, hacktivist channels, stolen data and exploit material were not accessed.

**Evidence limitations.**

- Disclosure asymmetry: US securities rules generate most quantified cases; EU and UK private manufacturers and small suppliers rarely disclose.
- No company in the period disclosed a ransom payment, an insurance recovery or the OT state of affected plants.
- No official source attributes a supplier insolvency to a cyber incident; the German Government states it holds no such information.
- The JLR economy-wide loss is modelled, with organisation counts that differ between sections of the CMC statement.
- Revenue and cash effects at JLR combine cyber, tariff and model wind-down drivers; only exceptional costs are labelled cyber-related.
- Claim-based benchmarks (ENISA, Dragos, Black Kite) count visibility, use different windows and methods and are not combined.
- The French controller case is days old; scale and losses come from relayed official and company statements.
- Several official pages did not render in the retrieval tool (EUR-Lex bodies, CISA advisories); article content was cross-checked with reproductions or secondary summaries and is flagged in the registers.
- Regimes listed as not assessed were not reviewed and no claims are made about them.
- No numerical probabilities are assigned; scenarios are stress narratives.

**Structure.** The report follows the seven-chapter standard of the installed cyber-sectorial-analysis skill, as requested by the user in the run instruction of 16 October 2026 ("exactly seven self-contained analytical PowerPoint slides"). This departs from the project's five-section, five-slide template; the project context's decision hierarchy places the user's latest explicit request first. The five project analyses map to the Key Threats, Financial Impact, Worst-Case Scenarios, Case Study and Mitigation chapters.

**Confidence.** Confidence is high for regulatory status where the primary page was read and for company-disclosed facts; medium for the principal judgements; and low for scenario durations and the scale of the French controller case.

## References

Each entry: number, source and title, publisher, publication date and basis, access date, tier, temporal class, locator. URLs are given in the reference definitions below this list; the source register gives methods and limitations.

- [1] JLR - Statement on cyber incident, 2 September 2025. Jaguar Land Rover Automotive plc, “Statement on Cyber Incident”. Published 2025-09-02 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: 1-2 September 2025. Locator: Statement body (single statement dated 2 September 2025). Source ID S-001.

- [2] JLR - Q2 FY26 volumes release. Jaguar Land Rover Automotive plc, “JLR volumes down in challenging quarter (Q2 FY26 wholesale and retail volumes)”. Published 2025-10-07 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: 1 July - 30 September 2025. Locator: Volume summary and CEO statement. Source ID S-002.

- [3] JLR - Restart and supplier financing release. Jaguar Land Rover Automotive plc, “JLR restarts manufacturing and introduces new financing solution to pay JLR suppliers early”. Published 2025-10-07 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: September - October 2025. Locator: Restart sequence paragraphs; supplier financing scheme section. Source ID S-003.

- [4] JLR - Q2 FY26 results release. Jaguar Land Rover Automotive plc, “JLR performance impacted in challenging quarter (Q2 FY26 results)”. Published 2025-11-14 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: 1 July - 30 September 2025. Locator: Headline summary; exceptional items paragraph; cash and liquidity section; outlook. Source ID S-004.

- [5] JLR - Q3 FY26 volumes release. Jaguar Land Rover Automotive plc, “JLR Q3 sales impacted by cyber incident as previously indicated”. Published 2026-01-05 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 1 October - 31 December 2025. Locator: Headline volumes; regional table; cyber incident statements. Source ID S-005.

- [6] JLR - Q3 FY26 results release. Jaguar Land Rover Automotive plc, “JLR Q3 performance impacted by previously indicated challenges (Q3 FY26 results)”. Published 2026-02-05 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 1 October - 31 December 2025. Locator: Financial summary; exceptional items; liquidity; recovery status. Source ID S-006.

- [7] TMPV - Q4 FY26 results release. Tata Motors Passenger Vehicles Ltd, “TMPV consolidated Q4 FY26 results (JLR section)”. Published 2026-05-14 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: Fiscal year 1 April 2025 - 31 March 2026. Locator: JLR revenue, PBT, free cash flow and liquidity paragraphs. Source ID S-007.

- [8] JLR - Annual Report 2026 web summary. Jaguar Land Rover Automotive plc, “Annual Report 2026 (web summary)”. Published undated (undated). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: Fiscal year to 31 March 2026. Locator: Chairman and CEO statements on the cyber incident. Source ID S-008.

- [9] UK Government - JLR loan guarantee. UK Government (Department for Business and Trade, HM Treasury, UK Export Finance), “Government backs Jaguar Land Rover with 1.5 billion pound loan guarantee”. Published 2025-09-28 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: September 2025. Locator: Release body and notes to editors (EDG description, five-year term, supply-chain purpose, 34,000 direct and about 120,000 supply-chain jobs). Source ID S-009.

- [10] CMC - JLR categorisation statement. Cyber Monitoring Centre (CMC), “Cyber Monitoring Centre statement on the Jaguar Land Rover cyber incident - October 2025”. Published 2025-10-22 (exact). Accessed 2026-10-16. Tier 2. Temporal class: H2_prior. Observation period: Late August 2025 - early January 2026 (modelled). Locator: Summary; Category 3 criteria; loss components 1-6; limitations; insurance and government-support sections. Source ID S-010.

- [11] ONS - GDP monthly estimate, September 2025. Office for National Statistics (ONS), “GDP monthly estimate, UK: September 2025”. Published 2025-11-13 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: September 2025 and three months to September 2025. Locator: Main points; production section on manufacture of motor vehicles (fall of 28.6%, -0.17 percentage-point contribution). Source ID S-011.

- [12] SMMT - September 2025 vehicle output. Society of Motor Manufacturers and Traders (SMMT), “Cyber attack hits vehicle output with new risk arising from tax charge on auto workers”. Published 2025-10-24 (exact). Accessed 2026-10-16. Tier 2. Temporal class: H2_prior. Observation period: September 2025. Locator: Headline figures for car and commercial vehicle output; chief executive statement. Source ID S-012.

- [13] Bank of England - Monetary Policy Report, November 2025. Bank of England, “Monetary Policy Report - November 2025”. Published 2025-11 (month only). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: Q3 2025. Locator: Section 1.2 Activity, headline GDP growth paragraph. Source ID S-013.

- [14] Business and Trade Committee - Letter to JLR, 9 September 2025. House of Commons Business and Trade Committee, “Letter from the Chair to the Chief Executive of Jaguar Land Rover: Cyber attack on Jaguar Land Rover”. Published 2025-09-09 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: September 2025. Locator: Letter body (15 questions; response requested by 19 September 2025). Source ID S-014.

- [15] ITV - JLR claim of responsibility report. ITV News, “M&S hackers claim to be behind Jaguar Land Rover cyber attack”. Published 2025-09-04 (exact). Accessed 2026-10-16. Tier 3. Temporal class: H2_prior. Observation period: September 2025. Locator: Article body: Telegram claim, JLR and NCA statements. Source ID S-015.

- [16] Asahi - Investigation results, 27 November 2025. Asahi Group Holdings, Ltd., “Investigation results and future measures on cyberattack data exposure”. Published 2025-11-27 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: 29 September - 27 November 2025. Locator: Attack timeline; initial access and ransomware; personal-records table; preventive measures. Source ID S-016.

- [17] Asahi - Business progress update, February 2026. Asahi Group Holdings, Ltd., “Business progress update in view of the delayed FY2025 results announcement”. Published 2026-02-26 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: October 2025 - February 2026. Locator: Sales percentages October-December 2025; delayed results; restoration aim. Source ID S-017.

- [18] Asahi - Business progress update, May 2026. Asahi Group Holdings, Ltd., “Business progress update in view of the delayed FY2026 Q1 results announcement”. Published 2026-05-22 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: January - March 2026. Locator: Jan-Mar 2026 sales ratios; distribution normalisation; results dates. Source ID S-018.

- [19] Asahi - FY2025 results briefing Q&A. Asahi Group Holdings, Ltd., “Main Q&A at the FY2025 financial results briefing”. Published 2026-07 (month only). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: Calendar year 2025 and Q1 2026 outlook. Locator: Q4 and Q5 answers (revenue, marginal profit, Others expenses, total 2025 impact of about JPY 40.0 billion, Q1 2026 outlook). Source ID S-019.

- [20] Jiji via Nippon.com - Asahi 2025 results. Nippon.com (Jiji Press), “Asahi Group's net profit falls 36.7 pct in 2025”. Published 2026-07-08 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: Calendar year 2025. Locator: Article body. Source ID S-020.

- [21] Stryker - Form 8-K/A, 9 April 2026. Stryker Corporation (SEC filing), “Form 8-K/A Amendment No. 1, Item 1.05 Material Cybersecurity Incidents”. Published 2026-04-09 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 11 March - 9 April 2026. Locator: Item 1.05 text: materiality determination, restoration of manufacturing network and ordering and distribution systems. Source ID S-021.

- [22] Stryker - Q1 2026 results release. Stryker Corporation (SEC filing), “Exhibit 99.1 - Stryker reports first quarter 2026 operating results”. Published 2026-04-30 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: Q1 2026. Locator: CEO statement; guidance; forward-looking statements. Source ID S-022.

- [23] MedTech Dive - Stryker disruption report. MedTech Dive, “Stryker's manufacturing, shipping disrupted after cyberattack”. Published 2026-03-13 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: 11-13 March 2026. Locator: Article body: 8-K accession numbers, company statements, Handala claim, researcher assessments. Source ID S-023.

- [24] The Record - CISA and FBI endpoint-management guidance. The Record (Recorded Future News), “FBI, CISA warn of Microsoft Intune risks after Stryker attack”. Published 2026-03-19 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: March 2026. Locator: Article body: CISA recommendations, FBI website seizure banner wording, attribution framing. Source ID S-024.

- [25] CISA - Endpoint management hardening alert. Cybersecurity and Infrastructure Security Agency (CISA), “CISA urges endpoint management system hardening after cyberattack against US organization”. Published 2026-03-18 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: March 2026. Locator: Alert title and date (page body did not render in the retrieval tool). Source ID S-025.

- [26] Boston Scientific - Form 8-K, 26 August 2026. Boston Scientific Corporation (SEC filing), “Form 8-K dated 26 August 2026, Item 8.01”. Published 2026-08-26 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 25-26 August 2026. Locator: Item 8.01 text. Source ID S-026.

- [27] Boston Scientific - Form 8-K Item 1.05, 8 September 2026. Boston Scientific Corporation (SEC filing), “Form 8-K dated 7 September 2026, Item 1.05 Material Cybersecurity Incidents”. Published 2026-09-08 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 25 August - 8 September 2026. Locator: Item 1.05 text: operational status, guidance statement, materiality. Source ID S-027.

- [28] MedTech Dive - Boston Scientific manufacturing report. MedTech Dive, “Boston Scientific says cyberattack has disrupted product manufacturing”. Published 2026-08-28 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: 25-28 August 2026. Locator: Article body: patient-device monitoring effects. Source ID S-028.

- [29] Reuters via Business Insurance - Boston Scientific guidance. Business Insurance (Reuters), “Boston Scientific says unlikely to meet sales forecast after cyberattack”. Published 2026-09-08 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: September 2026. Locator: Article body: guidance figures, share price move, analyst comments, sector context. Source ID S-029.

- [30] West Pharmaceutical - Form 8-K Item 1.05, May 2026. West Pharmaceutical Services, Inc. (SEC filing), “Form 8-K dated 7 May 2026, Item 1.05 Material Cybersecurity Incidents”. Published 2026-05-11 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 4-11 May 2026. Locator: Item 1.05 text. Source ID S-030.

- [31] Hasbro - Form 8-K, 1 April 2026. Hasbro, Inc. (SEC filing), “Form 8-K dated 1 April 2026, Item 8.01”. Published 2026-04-01 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 28 March - 1 April 2026. Locator: Item 8.01 text. Source ID S-031.

- [32] Hasbro - Release of 23 April 2026. Hasbro, Inc. (SEC filing), “Exhibit 99.1 - press release of 23 April 2026”. Published 2026-04-23 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: Q1-Q2 2026. Locator: Incident paragraphs; guidance. Source ID S-032.

- [33] Cybersecurity Dive - Fairlife production halt. Cybersecurity Dive, “Ransomware attack forces Coca-Cola to suspend US production at dairy unit”. Published 2026-07-17 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: 16-17 July 2026. Locator: Article body; Food and Ag-ISAC statistics. Source ID S-033.

- [34] Egide - Cyber incident release, 9 October 2026. Groupe Egide (via GlobeNewswire), “Egide - Incident Cyber”. Published 2026-10-09 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 6-9 October 2026. Locator: Release body (attack via an external IT provider; partial interruption of the Bollène site; CNIL notified; complaint filed). Source ID S-034.

- [35] CERT-FR - Refrigeration controller alert. CERT-FR (ANSSI), “CERTFR-2026-ALE-012 - security incident targeting remote controllers of refrigeration installations”. Published 2026-10-12 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 12-13 October 2026. Locator: Alert versions of 12 and 13 October 2026: affected products, numerous compromises, recommendations. Source ID S-035.

- [36] ComplexDiscovery - French refrigeration incident synthesis. ComplexDiscovery, “Refrigeration hack affected about 700 French supermarkets, government says, as Danfoss interfaces stay online”. Published 2026-10-14 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: 11-14 October 2026. Locator: Sections on scale, official statements, vendor positions, exposure figures, attribution. Source ID S-036.

- [37] RTX - Form 8-K on MUSE incident. RTX Corporation (SEC filing), “Form 8-K dated 19 September 2025, Item 8.01 (MUSE product cybersecurity incident)”. Published 2025-09-24 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: 19-24 September 2025. Locator: Item 8.01 text. Source ID S-037.

- [38] BleepingComputer - Bridgestone Americas incident. BleepingComputer, “Tire giant Bridgestone confirms cyberattack impacts manufacturing”. Published 2025-09 (month only). Accessed 2026-10-16. Tier 3. Temporal class: H2_prior. Observation period: 2-4 September 2025. Locator: Article body: company statement. Source ID S-038.

- [39] Dragos - Industrial ransomware Q2 2026. Dragos, “Industrial Ransomware Analysis for Q2 2026”. Published 2026-08-10 (exact). Accessed 2026-10-16. Tier 2. Temporal class: current. Observation period: 1 April - 30 June 2026. Locator: Key findings; sector and subsector counts; regional distribution; top groups; OT impact assessment; named incidents. Source ID S-039.

- [40] Black Kite - 2026 manufacturing ransomware report. Black Kite, “2026 Manufacturing and Distribution Ransomware Report”. Published 2026 (year only). Accessed 2026-10-16. Tier 2. Temporal class: current. Observation period: January 2023 - July 2026. Locator: Key statistics: annual totals, Jan-Jul 2026 comparison, subsectors, countries, groups, methodology. Source ID S-040.

- [41] ENISA - Threat Landscape 2026. European Union Agency for Cybersecurity (ENISA), “ENISA Threat Landscape 2026”. Published 2026-09 (month only). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 1 January - 31 December 2025. Locator: pp. 7, 9-14, 31-33 (manufacturing), 46-51 (ransomware). Source ID S-041.

- [42] Manufacturing Dive - IBM X-Force 2026 findings. Manufacturing Dive, “Manufacturing sector saw most cyberattacks in 2025: IBM X-Force”. Published 2026-02-26 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: Calendar year 2025. Locator: Article body. Source ID S-042.

- [43] Eurostat - Businesses in the manufacturing sector. Eurostat, “Businesses in the manufacturing sector (Statistics Explained)”. Published 2025-12 (month only). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: Reference year 2023. Locator: Key figures: enterprises, persons employed, value added, largest divisions. Source ID S-043.

- [44] Eurostat - EU business economy 2023. Eurostat, “EU business economy 2023 (news item)”. Published 2025-10-13 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: Reference year 2023. Locator: News body: size-class shares. Source ID S-044.

- [45] BSI - NIS-2 in figures, Q3 2026. Bundesamt für Sicherheit in der Informationstechnik (BSI), “NIS-2 in Zahlen (NIS-2 in figures)”. Published 2026-10-07 (page update). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 6 December 2025 - 30 September 2026. Locator: Registration table; Annex 2 sector breakdown (manufacturing 4,739; chemicals 821; food 1,986); reports. Source ID S-045.

- [46] BSI - German NIS2 law in force. Bundesamt für Sicherheit in der Informationstechnik (BSI), “Cybersicherheitsrecht: NIS-2-Umsetzungsgesetz ab morgen in Kraft”. Published 2025-12-05 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: December 2025. Locator: Release body: entry into force, about 29,500 supervised entities, registration steps. Source ID S-046.

- [47] Bundestag - Drucksache 21/8046. Deutscher Bundestag, “Drucksache 21/8046: Answer of the Federal Government on existence-threatening cyberattacks on German companies”. Published 2026-09-16 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 2022-2025 statistics; 2026 cases cited by questioners. Locator: Answer to question 7 (no information on cyber-caused insolvencies); statistics answers (BKA ransomware cases 2025; damage estimates); preamble (questioners' case references). Source ID S-047.

- [48] CircleID - Zego insolvency report. CircleID, “Zego's cyberattack pushes Bavarian textile firm into insolvency”. Published 2026-07-14 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: March - July 2026. Locator: Article body. Source ID S-048.

- [49] EUR-Lex - NIS2 Directive. Publications Office of the EU (EUR-Lex), “Directive (EU) 2022/2555 (NIS2 Directive)”. Published 2022-12-27 (exact). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: Applies from 18 October 2024. Locator: ELI metadata (publication 27.12.2022; in force 16.1.2023); Arts 2(1)-(2), 3(1)-(4), 20, 21(2)(d) and 21(3), 23(4), 34(4)-(5), 41(1); Annexes I and II. Source ID S-049.

- [50] Streamlex - NIS2 Annex II text. Streamlex, “NIS2 Annex II (consolidated reproduction)”. Published undated (undated). Accessed 2026-10-16. Tier 3. Temporal class: contextual. Observation period: Not stated. Locator: Annex II sectors 3, 4 and 5. Source ID S-050.

- [51] European Commission - NIS2 Court referral. European Commission (Shaping Europe's digital future), “Commission refers Ireland, Spain, France and the Netherlands to the Court of Justice for failing to transpose the rules on cybersecurity”. Published 2026-07-08 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: November 2024 - July 2026. Locator: News body: referral, penalties requested, letters of formal notice 28 November 2024, reasoned opinions 7 May 2025. Source ID S-051.

- [52] European Commission - NIS2 transposition page. European Commission (Shaping Europe's digital future), “NIS2 Directive transposition in EU countries”. Published 2025-07-01 (page update). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: 2024-2026. Locator: Reasoned opinion list (19 Member States, 7 May 2025); referral note. Source ID S-052.

- [53] European Commission - CER Court referral (IP/26/910). European Commission (Press corner), “Commission decides to refer Bulgaria, France, Luxembourg, the Netherlands, Poland, Spain and Sweden to the Court of Justice for failing to transpose the CER Directive (IP/26/910)”. Published 2026 (year only). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 2026. Locator: Release title and description (body and date not rendered). Source ID S-053.

- [54] EUR-Lex - CER Directive. Publications Office of the EU (EUR-Lex), “Directive (EU) 2022/2557 on the resilience of designated entities (CER Directive)”. Published 2022-12-27 (exact). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: Transposition by 17 October 2024; identification by 17 July 2026. Locator: ELI metadata (document 14.12.2022; publication 27.12.2022; in force 16.1.2023); Arts 6(1), 26(1); Annex sectors. Source ID S-054.

- [55] EUR-Lex - Regulation (EU) 2024/2847. Publications Office of the EU (EUR-Lex), “Regulation (EU) 2024/2847 on horizontal cybersecurity requirements for products with digital elements”. Published 2024-11-20 (exact). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: In force 10 December 2024; reporting from 11 September 2026; main obligations 11 December 2027. Locator: ELI metadata (document 23.10.2024; in force 10.12.2024); Arts 2, 7-8, 14, 71; Annexes III and IV. Source ID S-055.

- [56] European Commission - Regulation (EU) 2024/2847 summary. European Commission (Shaping Europe's digital future), “Summary of the legislative text of Regulation (EU) 2024/2847”. Published undated (undated). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: 2024-2028. Locator: Scope; conformity assessment; manufacturer obligations; reporting obligations; timeline; penalties. Source ID S-056.

- [57] ENISA - Single Reporting Platform launch. ENISA, “The Single Reporting Platform under Regulation (EU) 2024/2847 is launched”. Published 2026-09-11 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: From 11 September 2026. Locator: Release body: initial operating capability; reporting from 11 September 2026; routing. Source ID S-057.

- [58] EUR-Lex - Implementing Regulation (EU) 2025/2392. Publications Office of the EU (EUR-Lex), “Commission Implementing Regulation (EU) 2025/2392 on the technical description of product categories under Regulation (EU) 2024/2847”. Published 2025-11-28 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: In force 21 December 2025. Locator: ELI metadata: date of document 28.11.2025; entry into force 21.12.2025. Source ID S-058.

- [59] Springlex - Regulation (EU) 2024/2847 Article 2. Springlex, “Regulation (EU) 2024/2847 Article 2 (reproduction)”. Published undated (undated). Accessed 2026-10-16. Tier 3. Temporal class: contextual. Observation period: Not stated. Locator: Article 2 paragraphs on exclusions. Source ID S-059.

- [60] DBT - Explanatory memorandum on Regulation (EU) 2026/1744. UK Department for Business and Trade (Office for Product Safety and Standards), “Explanatory memorandum on Regulation (EU) 2026/1744 (Windsor Framework scrutiny)”. Published 2026-08-03 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 2026-2028. Locator: Paras 2, 9, 12, 13, 17. Source ID S-060.

- [61] ERTICO - Digital Omnibus on AI entry into force. ERTICO - ITS Europe, “Digital Omnibus on AI enters into force”. Published 2026-08-07 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: 2026-2028. Locator: Article body: OJ 24 July 2026, in force 27 July 2026, Annex III 2 December 2027, Annex I 2 August 2028. Source ID S-061.

- [62] euaiact.com - Regulation (EU) 2026/1744 sectoral amendments. EU AI Act (euaiact.com), “Regulation (EU) 2026/1744, Articles 2 and 3 (sectoral amendments)”. Published undated (undated). Accessed 2026-10-16. Tier 3. Temporal class: contextual. Observation period: 2026-2028. Locator: Article 3 amendments to Regulation (EU) 2023/1230 (Arts 8, 20, 47); recital 42. Source ID S-062.

- [63] EU-OSHA - Machinery Regulation page. European Agency for Safety and Health at Work (EU-OSHA), “Regulation 2023/1230/EU - machinery”. Published 2025-01-16 (page update). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: Applies from 20 January 2027. Locator: Page body: application date; scope note on connected equipment and AI safety functions. Source ID S-063.

- [64] KAN - Machinery cybersecurity requirements brief. Commission for Occupational Health and Safety and Standardization (KAN), “Combating vulnerabilities with standards: new EU cybersecurity rules (KANBrief 2/25)”. Published 2025 (year only). Accessed 2026-10-16. Tier 2. Temporal class: contextual. Observation period: 2025-2027. Locator: Article body: Annex III 1.1.9 and 1.2.1; prEN 50742; application 20 January 2027. Source ID S-064.

- [65] EUR-Lex - Machinery Regulation consolidated. Publications Office of the EU (EUR-Lex), “Regulation (EU) 2023/1230 on machinery (consolidated version)”. Published 2026-07-27 (page update). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: Applies from 20 January 2027. Locator: ELI metadata: consolidated version dated 27 July 2026; Annex III points 1.1.9 and 1.2.1. Source ID S-065.

- [66] EUR-Lex - Product Liability Directive. Publications Office of the EU (EUR-Lex), “Directive (EU) 2024/2853 on liability for defective products”. Published 2024-10-23 (exact). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: In force 8 December 2024; transposition by 9 December 2026. Locator: ELI metadata (document 23.10.2024; in force 8.12.2024); Arts 4(1), 7(2), 11(2), 22(1). Source ID S-066.

- [67] Inside Privacy - Product liability transposition update. Covington & Burling (Inside Privacy), “EU Member States begin rolling out new product liability rules”. Published 2026-08-17 (page update). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: 2024-2026. Locator: Update of 17 August 2026: transposition deadline; national bills and adopted laws. Source ID S-067.

- [68] EUR-Lex - Delegated Regulation (EU) 2026/339. Publications Office of the EU (EUR-Lex), “Commission Delegated Regulation (EU) 2026/339 repealing Delegated Regulation (EU) 2022/30”. Published 2026-02-16 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: In force 19 May 2026; repeal effective after 10 December 2027. Locator: ELI metadata: date of act 16.2.2026; first entry into force 19.5.2026; date no longer in force 10.12.2027. Source ID S-068.

- [69] European Commission - Data Act page. European Commission (Shaping Europe's digital future), “Data Act”. Published undated (undated). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: In force 11 January 2024; applies 12 September 2025. Locator: Page body: entry into force and application; connected products including industrial machinery. Source ID S-069.

- [70] European Commission - GMP Annex 11 consultation. European Commission (DG SANTE), “Stakeholders' consultation on EudraLex Volume 4 - GMP guidelines: Chapter 4, Annex 11 and new Annex 22”. Published undated (undated). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: 7 July - 7 October 2025 consultation. Locator: Page body: status closed; opening 7 July 2025; deadline 7 October 2025; documents. Source ID S-070.

- [71] Official Journal - UN Regulation No. 155. Publications Office of the EU (Official Journal), “UN Regulation No. 155 - uniform provisions concerning the approval of vehicles with regards to cyber security and cyber security management system (OJ L 2025/5)”. Published 2025-01-10 (exact). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: Applicable to new vehicle types since 2022 and to all new M, N, O vehicles since July 2024. Locator: Paras 1.1, 6, 6.7, 7.2.2.1, 7.3.1, 7.3.4. Source ID S-071.

- [72] European Commission - Seveso III implementation report. European Commission, “Report COM(2025) 508 on the implementation of Directive 2012/18/EU (Seveso III), 2019-2022”. Published 2025-09-19 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: 2019-2022. Locator: Report body: security-related risks paragraph; listed triggers. Source ID S-072.

- [73] Council of the EU - FDI screening adoption. Council of the European Union, “Foreign investment screening: Council signs off on updated framework”. Published 2026-06-08 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 2026-2028. Locator: Release body: adoption, minimum scope, timeline. Source ID S-073.

- [74] European Commission - FDI screening publication. European Commission (DG Trade and Economic Security), “EU strengthens its foreign investment screening framework”. Published 2026-06-26 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 2026-2028. Locator: News body: OJ publication 26 June 2026 (OJ L 2026/1386 reference), 18-month implementation, minimum scope. Source ID S-074.

- [75] UK Parliament - Cyber Security and Resilience Bill page. UK Parliament, “Cyber Security and Resilience (Network and Information Systems) Bill - bill page”. Published 2026-10-15 (page update). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: November 2025 - October 2026. Locator: Bill page: House of Lords, Report stage linked; HL Bill 49 as amended in Grand Committee dated 7 September 2026; no Royal Assent. Source ID S-075.

- [76] DSIT - Bill summary factsheet. Department for Science, Innovation and Technology (DSIT), “Cyber Security and Resilience (Network and Information Systems) Bill factsheets: summary of the Bill”. Published 2026-06-30 (page update). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 2025-2026. Locator: Sections on managed service providers, data centres, designated suppliers, incident reporting, penalties, powers. Source ID S-076.

- [77] Home Office - Ransomware proposals response. Home Office, “Ransomware legislative proposals: reducing payments to cyber criminals and increasing incident reporting - government response”. Published 2025-07-22 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: 2025. Locator: pp. 26-27 (ban), 28 and 40-41 (prevention regime), 42 and 47 (reporting). Source ID S-077.

- [78] LGA - Ransomware proposals briefing. Local Government Association, “Ransomware legislative proposals”. Published undated (undated). Accessed 2026-10-16. Tier 2. Temporal class: contextual. Observation period: 2025-2026. Locator: Page body: proposals described as proposals; economy-wide versus threshold reporting. Source ID S-078.

- [79] HSE - Cyber security for industrial automation and control systems. Health and Safety Executive (HSE), “Cyber security (Electrical, Control and Instrumentation)”. Published 2026-06-29 (page update). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 2017-2026. Locator: Page body: COMAH interpretation; OG86 (March 2017); referenced standards. Source ID S-079.

- [80] Cabinet Office - NSI Act notifiable acquisitions guidance. Cabinet Office, “National Security and Investment Act: details of the 17 types of notifiable acquisitions”. Published 2024-02-06 (page update). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: In force since 4 January 2022. Locator: List of 17 areas; advanced materials, advanced robotics, computing hardware, defence, military and dual-use sections. Source ID S-080.

- [81] MOD - Cyber Security Model. Ministry of Defence, “Cyber Security Model”. Published 2026-03-06 (page update). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 2026. Locator: Page body: CSM version 4; Def Stan 05-138 Issue 4; DEFCON 658 flow-down. Source ID S-081.

- [82] DSIT - Product security regime guidance. Department for Science, Innovation and Technology, “The UK Product Security and Telecommunications Infrastructure (Product Security) regime”. Published 2024-05-02 (page update). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: In force since 29 April 2024. Locator: Page body: start date, duty holders, three requirements, OPSS enforcement. Source ID S-082.

- [83] SEC - Cyber disclosure rules fact sheet. US Securities and Exchange Commission, “Fact sheet: Public company cybersecurity disclosures; final rules (Release 33-11216)”. Published undated (undated). Accessed 2026-10-16. Tier 1. Temporal class: historical. Observation period: Compliance from December 2023. Locator: Item 1.05; Item 106; compliance dates. Source ID S-083.

- [84] Federal Register - DFARS CMMC final rule. Office of the Federal Register (Department of Defense), “DFARS: Assessing Contractor Implementation of Cybersecurity Requirements (DFARS Case 2019-D041), 90 FR 43560”. Published 2025-09-10 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: Effective 10 November 2025. Locator: Summary; effective date; clause 252.204-7021; phase description. Source ID S-084.

- [85] Squire Patton Boggs - CMMC phases. Squire Patton Boggs, “The CMMC DFARS final rule goes live: ready or not, here it comes”. Published 2025-09 (month only). Accessed 2026-10-16. Tier 3. Temporal class: H2_prior. Observation period: 2025-2028. Locator: Phased rollout section (32 CFR 170.3). Source ID S-085.

- [86] Paubox - CIRCIA final rule status. Paubox, “CIRCIA final rule: White House deadlines set, scope open”. Published 2026-10-08 (exact). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: 2022-2026. Locator: Article body: submission to OMB on 1 October 2026; missed target dates. Source ID S-086.

- [87] CISA - CFATS lapse statement. CISA, “Resilience in a time of uncertainty: national chemical security during the CFATS lapse”. Published 2023-11 (month only). Accessed 2026-10-16. Tier 1. Temporal class: historical. Observation period: July - November 2023. Locator: Article body. Source ID S-087.

- [88] J. J. Keller - CFATS status. J. J. Keller, “What happened to CFATS? Are the CFATS withdrawn?”. Published 2024-12-31 (exact). Accessed 2026-10-16. Tier 3. Temporal class: contextual. Observation period: 2023-2024. Locator: Article body. Source ID S-088.

- [89] CISA and partners - PLC advisory AA26-097A. CISA and partner agencies, “Iranian-affiliated cyber actors exploit programmable logic controllers (advisory AA26-097A)”. Published 2026-04-07 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: March - July 2026. Locator: Advisory title and identifier (body not retrievable in this run). Source ID S-089.

- [90] Picus - Summary of advisory AA26-097A. Picus Security, “CISA alert AA26-097A: Iranian-affiliated actors target PLCs across US infrastructure”. Published 2026 (year only). Accessed 2026-10-16. Tier 3. Temporal class: current. Observation period: March - April 2026. Locator: Blog body: date, agencies, sectors, impacts, vendor named. Source ID S-090.

- [91] NCSC - CEO keynote, CYBERUK 2026. National Cyber Security Centre (NCSC), “NCSC CEO keynote speech, CYBERUK 2026”. Published 2026-04-22 (exact). Accessed 2026-10-16. Tier 1. Temporal class: current. Observation period: 2025-2026. Locator: Speech text: four nationally significant incidents a week; state actors China, Russia, Iran. Source ID S-091.

- [92] NIST - SP 800-82 Rev. 3. NIST, “SP 800-82 Rev. 3, Guide to Operational Technology (OT) Security”. Published 2023-09-28 (exact). Accessed 2026-10-16. Tier 1. Temporal class: historical. Observation period: 2023; Rev. 4 draft comments to 30 November 2026. Locator: Publication page: date, status, abstract; planning note on Rev. 4 initial public draft dated 21 September 2026. Source ID S-092.

- [93] NIST - CSF 2.0 Manufacturing Profile draft. NIST, “IR 8183 Rev. 2 (initial public draft), Cybersecurity Framework 2.0 Manufacturing Profile”. Published 2025-09-29 (exact). Accessed 2026-10-16. Tier 1. Temporal class: H2_prior. Observation period: 2025. Locator: Publication page: status, comment period, abstract. Source ID S-093.

- [94] FDA - Medical device cybersecurity FAQs. US Food and Drug Administration, “Cybersecurity in Medical Devices Frequently Asked Questions”. Published 2025-06-26 (page update). Accessed 2026-10-16. Tier 1. Temporal class: H1_prior. Observation period: From 29 March 2023. Locator: FAQ answers on section 524B requirements, effective date and cyber device definition. Source ID S-094.

- [95] legislation.gov.uk - NIS Regulations 2018 schedules. legislation.gov.uk (The National Archives), “The Network and Information Systems Regulations 2018 (SI 2018/506), Schedules 1 and 2”. Published 2018-04-19 (exact). Accessed 2026-10-16. Tier 1. Temporal class: historical. Observation period: In force 10 May 2018; amendments to 2024. Locator: Schedule 1 sector table (energy, transport, health, drinking water, digital infrastructure); Schedule 2 essential services and thresholds. Source ID S-095.

- [96] eCFR - 32 CFR Part 170 CMMC Program. Electronic Code of Federal Regulations (eCFR), “32 CFR Part 170 - Cybersecurity Maturity Model Certification (CMMC) Program”. Published undated (undated). Accessed 2026-10-16. Tier 1. Temporal class: contextual. Observation period: Phases from 10 November 2025. Locator: Section 170.3(e) phased implementation. Source ID S-096.

[1]: https://media.jlr.com/corporate/news/2025/09/statement-cyber-incident "JLR - Statement on cyber incident, 2 September 2025"

[2]: https://media.jlr.com/corporate/news/2025/10/jlr-volumes-down-challenging-quarter "JLR - Q2 FY26 volumes release"

[3]: https://media.jaguarlandrover.com/news/2025/10/jlr-restarts-manufacturing-and-introduces-new-financing-solution-pay-jlr-suppliers "JLR - Restart and supplier financing release"

[4]: https://media.jlr.com/corporate/news/2025/11/jlr-performance-impacted-challenging-quarter "JLR - Q2 FY26 results release"

[5]: https://www.jlr.com/news/2026/01/jlr-q3-sales-impacted-cyber-incident-previously-indicated "JLR - Q3 FY26 volumes release"

[6]: https://media.jlr.com/corporate/news/2026/02/jlr-q3-performance-impacted-previously-indicated-challenges "JLR - Q3 FY26 results release"

[7]: https://cars.tatamotors.com/article/press-release/tmpv-consolidated-q4fy26-results.html "TMPV - Q4 FY26 results release"

[8]: https://www.jlr.com/annual-report-2026 "JLR - Annual Report 2026 web summary"

[9]: https://www.gov.uk/government/news/government-backs-jaguar-land-rover-with-15-billion-loan-guarantee "UK Government - JLR loan guarantee"

[10]: https://cybermonitoringcentre.com/2025/10/22/cyber-monitoring-centre-statement-on-the-jaguar-land-rovercyber-incident-october-2025/ "CMC - JLR categorisation statement"

[11]: https://www.ons.gov.uk/economy/grossdomesticproductgdp/bulletins/gdpmonthlyestimateuk/september2025 "ONS - GDP monthly estimate, September 2025"

[12]: https://www.smmt.co.uk/cyber-attack-hits-vehicle-output-with-new-risk-arising-from-tax-charge-on-auto-workers/ "SMMT - September 2025 vehicle output"

[13]: https://www.bankofengland.co.uk/monetary-policy-report/2025/november-2025 "Bank of England - Monetary Policy Report, November 2025"

[14]: https://committees.parliament.uk/publications/49443/documents/263268/default/ "Business and Trade Committee - Letter to JLR, 9 September 2025"

[15]: https://www.itv.com/news/central/2025-09-04/m-and-s-hackers-claim-to-be-behind-jaguar-land-rover-cyber-attack "ITV - JLR claim of responsibility report"

[16]: https://www.asahigroup-holdings.com/newsroom/detail/20251127-0204.html "Asahi - Investigation results, 27 November 2025"

[17]: https://www.asahigroup-holdings.com/en/newsroom/detail/20260226-0109.html "Asahi - Business progress update, February 2026"

[18]: https://www.asahigroup-holdings.com/en/newsroom/detail/20260522-0204.html "Asahi - Business progress update, May 2026"

[19]: https://www.asahigroup-holdings.com/en/ir/event/presentation/2025/qa_yearend.html "Asahi - FY2025 results briefing Q&A"

[20]: https://www.nippon.com/en/news/yjj2026070800564/ "Jiji via Nippon.com - Asahi 2025 results"

[21]: https://www.sec.gov/Archives/edgar/data/310764/000119312526149607/d112875d8ka.htm "Stryker - Form 8-K/A, 9 April 2026"

[22]: https://www.sec.gov/Archives/edgar/data/0000310764/000031076426000025/sykex991earningsq12026.htm "Stryker - Q1 2026 results release"

[23]: https://www.medtechdive.com/news/strykers-manufacturing-shipping-disrupted-after-cyberattack/814667/ "MedTech Dive - Stryker disruption report"

[24]: https://therecord.media/fbi-cisa-warn-of-microsoft-intune-risks-stryker "The Record - CISA and FBI endpoint-management guidance"

[25]: https://www.cisa.gov/news-events/alerts/2026/03/18/cisa-urges-endpoint-management-system-hardening-after-cyberattack-against-us-organization "CISA - Endpoint management hardening alert"

[26]: https://www.sec.gov/Archives/edgar/data/0000885725/000088572526000056/bsx-20260826.htm "Boston Scientific - Form 8-K, 26 August 2026"

[27]: https://www.sec.gov/Archives/edgar/data/0000885725/000088572526000059/bsx-20260907.htm "Boston Scientific - Form 8-K Item 1.05, 8 September 2026"

[28]: https://www.medtechdive.com/news/boston-scientific-says-cyberattack-has-disrupted-product-manufacturing/829086/ "MedTech Dive - Boston Scientific manufacturing report"

[29]: https://www.businessinsurance.com/boston-scientific-says-unlikely-to-meet-sales-forecast-after-cyberattack/ "Reuters via Business Insurance - Boston Scientific guidance"

[30]: https://www.sec.gov/Archives/edgar/data/0000105770/000010577026000068/wst-20260507.htm "West Pharmaceutical - Form 8-K Item 1.05, May 2026"

[31]: https://www.sec.gov/Archives/edgar/data/46080/000004608026000013/has-20260401.htm "Hasbro - Form 8-K, 1 April 2026"

[32]: https://www.sec.gov/Archives/edgar/data/0000046080/000004608026000016/exhibit991-apr232026.htm "Hasbro - Release of 23 April 2026"

[33]: https://www.cybersecuritydive.com/news/ransomware-attack-coca-cola-suspend-production-dairy/825540/ "Cybersecurity Dive - Fairlife production halt"

[34]: https://www.globenewswire.com/news-release/2026/10/09/3378286/0/fr/egide-incident-cyber.html "Egide - Cyber incident release, 9 October 2026"

[35]: https://cert.cyber.gouv.fr/alerte/CERTFR-2026-ALE-012/ "CERT-FR - Refrigeration controller alert"

[36]: https://complexdiscovery.com/refrigeration-hack-affected-about-700-french-supermarkets-government-says-as-danfoss-interfaces-stay-online/ "ComplexDiscovery - French refrigeration incident synthesis"

[37]: https://www.sec.gov/Archives/edgar/data/101829/000010182925000036/rtx-20250919.htm "RTX - Form 8-K on MUSE incident"

[38]: https://www.bleepingcomputer.com/news/security/tire-giant-bridgestone-confirms-cyberattack-impacts-manufacturing/ "BleepingComputer - Bridgestone Americas incident"

[39]: https://www.dragos.com/blog/dragos-industrial-ransomware-analysis-q2-2026 "Dragos - Industrial ransomware Q2 2026"

[40]: https://blackkite.com/reports/2026-manufacturing-distribution "Black Kite - 2026 manufacturing ransomware report"

[41]: https://www.enisa.europa.eu/sites/default/files/2026-09/ENISA%20Threat%20Landscape%202026_Final.pdf "ENISA - Threat Landscape 2026"

[42]: https://www.manufacturingdive.com/news/manufacturing-sector-saw-most-cyberattacks-in-2025-IBM-X-Force/813063/ "Manufacturing Dive - IBM X-Force 2026 findings"

[43]: https://ec.europa.eu/eurostat/statistics-explained/SEPDF/cache/10086.pdf "Eurostat - Businesses in the manufacturing sector"

[44]: https://ec.europa.eu/eurostat/web/products-eurostat-news/w/ddn-20251013-2 "Eurostat - EU business economy 2023"

[45]: https://www.bsi.bund.de/DE/Themen/Regulierte-Wirtschaft/NIS-2-regulierte-Unternehmen/NIS-2-in-Zahlen/nis-2-in-zahlen.html "BSI - NIS-2 in figures, Q3 2026"

[46]: https://www.bsi.bund.de/DE/Service-Navi/Presse/Pressemitteilungen/Presse2025/251205_NIS-2-Umsetzungsgesetz_in_Kraft.html "BSI - German NIS2 law in force"

[47]: https://dserver.bundestag.de/btd/21/080/2108046.pdf "Bundestag - Drucksache 21/8046"

[48]: https://circleid.com/posts/zegos-cyberattack-pushes-bavarian-textile-firm-into-insolvency "CircleID - Zego insolvency report"

[49]: https://eur-lex.europa.eu/eli/dir/2022/2555/oj/eng "EUR-Lex - NIS2 Directive"

[50]: https://streamlex.eu/annexes/nis2-en-annex-ii/ "Streamlex - NIS2 Annex II text"

[51]: https://digital-strategy.ec.europa.eu/en/news/commission-refers-ireland-spain-france-and-netherlands-court-justice-failing-transpose-rules "European Commission - NIS2 Court referral"

[52]: https://digital-strategy.ec.europa.eu/en/policies/nis-transposition "European Commission - NIS2 transposition page"

[53]: https://ec.europa.eu/commission/presscorner/detail/en/ip_26_910 "European Commission - CER Court referral (IP/26/910)"

[54]: https://eur-lex.europa.eu/eli/dir/2022/2557/oj/eng "EUR-Lex - CER Directive"

[55]: https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng "EUR-Lex - Regulation (EU) 2024/2847"

[56]: https://digital-strategy.ec.europa.eu/en/policies/cra-summary "European Commission - Regulation (EU) 2024/2847 summary"

[57]: https://www.enisa.europa.eu/news/the-cra-single-reporting-platform-is-launched "ENISA - Single Reporting Platform launch"

[58]: https://eur-lex.europa.eu/eli/reg_impl/2025/2392/oj/eng "EUR-Lex - Implementing Regulation (EU) 2025/2392"

[59]: https://www.springlex.eu/en/packages/cra/cra-regulation/article-2/ "Springlex - Regulation (EU) 2024/2847 Article 2"

[60]: https://www.niassembly.gov.uk/globalassets/committee-blocks/windsor-framework-democratic-scrutiny-committee/reg-eu-20261744/regulation-eu-2026_1744-em.pdf "DBT - Explanatory memorandum on Regulation (EU) 2026/1744"

[61]: https://ertico.com/digital-omnibus-on-ai-enters-into-force "ERTICO - Digital Omnibus on AI entry into force"

[62]: https://www.euaiact.com/digital-omnibus-ai/sectoral-amendments "euaiact.com - Regulation (EU) 2026/1744 sectoral amendments"

[63]: https://osha.europa.eu/en/legislation/directive/regulation-20231230eu-machinery "EU-OSHA - Machinery Regulation page"

[64]: https://www.kan.de/en/publications/kanbrief/2025/2-25/combating-vulnerabilities-with-standards-new-eu-cybersecurity-rules/ "KAN - Machinery cybersecurity requirements brief"

[65]: https://eur-lex.europa.eu/eli/reg/2023/1230 "EUR-Lex - Machinery Regulation consolidated"

[66]: https://eur-lex.europa.eu/eli/dir/2024/2853/oj/eng "EUR-Lex - Product Liability Directive"

[67]: https://www.insideprivacy.com/uncategorized/eu-member-states-begin-rolling-out-new-product-liability-rules/ "Inside Privacy - Product liability transposition update"

[68]: https://eur-lex.europa.eu/eli/reg_del/2026/339/oj/eng "EUR-Lex - Delegated Regulation (EU) 2026/339"

[69]: https://digital-strategy.ec.europa.eu/en/policies/data-act "European Commission - Data Act page"

[70]: https://health.ec.europa.eu/consultations/stakeholders-consultation-eudralex-volume-4-good-manufacturing-practice-guidelines-chapter-4-annex_en "European Commission - GMP Annex 11 consultation"

[71]: https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ%3AL_202500005 "Official Journal - UN Regulation No. 155"

[72]: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex:52025DC0508 "European Commission - Seveso III implementation report"

[73]: https://www.consilium.europa.eu/en/press/press-releases/2026/06/08/foreign-investment-screening-council-signs-off-on-updated-framework/ "Council of the EU - FDI screening adoption"

[74]: https://policy.trade.ec.europa.eu/news/eu-strengthens-its-foreign-investment-screening-framework-2026-06-26_en "European Commission - FDI screening publication"

[75]: https://bills.parliament.uk/bills/4035 "UK Parliament - Cyber Security and Resilience Bill page"

[76]: https://www.gov.uk/government/publications/cyber-security-and-resilience-network-and-information-systems-bill-factsheets/summary-of-the-bill "DSIT - Bill summary factsheet"

[77]: https://assets.publishing.service.gov.uk/media/6899a4ddad0cbc0e276431e3/Government_Response_Ransomware_proposals_to_increase_incident_reporting_and_reduce_payments_to_criminals.pdf "Home Office - Ransomware proposals response"

[78]: https://www.local.gov.uk/our-support/cyber-digital-and-technology/cyber-digital-and-technology-policy-team/ransomware "LGA - Ransomware proposals briefing"

[79]: https://www.hse.gov.uk/eci/cyber-security.htm "HSE - Cyber security for industrial automation and control systems"

[80]: https://www.gov.uk/government/publications/national-security-and-investment-act-guidance-on-notifiable-acquisitions/national-security-and-investment-act-guidance-on-notifiable-acquisitions "Cabinet Office - NSI Act notifiable acquisitions guidance"

[81]: https://www.gov.uk/guidance/cyber-security-model "MOD - Cyber Security Model"

[82]: https://www.gov.uk/government/publications/the-uk-product-security-and-telecommunications-infrastructure-product-security-regime "DSIT - Product security regime guidance"

[83]: https://www.sec.gov/files/33-11216-fact-sheet.pdf "SEC - Cyber disclosure rules fact sheet"

[84]: https://www.federalregister.gov/documents/2025/09/10/2025-17359/defense-federal-acquisition-regulation-supplement-assessing-contractor-implementation-of "Federal Register - DFARS CMMC final rule"

[85]: https://www.squirepattonboggs.com/insights/publications/the-cmmc-dfars-final-rule-goes-live-ready-or-not-here-it-comes/ "Squire Patton Boggs - CMMC phases"

[86]: https://www.paubox.com/blog/circia-final-rule-white-house-deadlines-set-scope-open "Paubox - CIRCIA final rule status"

[87]: https://www.cisa.gov/news-events/news/resilience-time-uncertainty-national-chemical-security-during-cfats-lapse "CISA - CFATS lapse statement"

[88]: https://jjkellercompliancenetwork.com/regsense/what-happened-to-cfats-chemical-facility-anti-terrorism-standards-at-6-cfr-27-are-the-cfats-withdrawn "J. J. Keller - CFATS status"

[89]: https://www.cisa.gov/news-events/cybersecurity-advisories/aa26-097a "CISA and partners - PLC advisory AA26-097A"

[90]: https://www.picussecurity.com/resource/blog/cisa-alert-aa26-097a-iranian-affiliated-actors-target-plcs-across-us-%63ritical-infrastructure "Picus - Summary of advisory AA26-097A"

[91]: https://www.ncsc.gov.uk/speech/ncsc-ceo-keynote-speech-cyberuk-2026 "NCSC - CEO keynote, CYBERUK 2026"

[92]: https://csrc.nist.gov/pubs/sp/800/82/r3/final "NIST - SP 800-82 Rev. 3"

[93]: https://csrc.nist.gov/pubs/ir/8183/r2/ipd "NIST - CSF 2.0 Manufacturing Profile draft"

[94]: https://www.fda.gov/medical-devices/digital-health-center-excellence/cybersecurity-medical-devices-frequently-asked-questions-faqs "FDA - Medical device cybersecurity FAQs"

[95]: https://www.legislation.gov.uk/uksi/2018/506/schedules/data.xht "legislation.gov.uk - NIS Regulations 2018 schedules"

[96]: https://www.ecfr.gov/current/title-32/subtitle-A/chapter-I/subchapter-G/part-170 "eCFR - 32 CFR Part 170 CMMC Program"

Manufacturing cyber sectorial analysis - external data only
