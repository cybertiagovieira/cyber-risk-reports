# Healthcare - Sectorial Cyber Risk Intelligence

**Report date:** 14 October 2026. **Reporting period:** 1 September 2025 to 14 October 2026. **Evidence cut-off:** 14 October 2026. **Rolling evidence horizon:** 18 months for patterns, comparisons and public loss cases; older material is labelled historical or legal context.

**Geography:** Global, with primary focus on the European Union (EU), European Economic Area (EEA) and United Kingdom (UK); North American evidence is used for comparison, cross-border dependencies and transferable lessons. No single jurisdiction or health-system funding model is treated as representative of the global sector.

**Audience:** First Line of Defence (1LoD) operational management and Risk Committee. **Boundary:** public external data only. No internal, client, patient or bank-specific information is used or implied. No leaked dataset, leak-site content or personal health information was accessed or reproduced. **Edition:** baseline; no prior Healthcare edition exists, so change is described against the period rather than against an earlier report. **Revision 2 (25 October 2026):** the seven-slide readout was redesigned with charts and varied layouts; the report adds the Stryker guidance range and an outage-versus-stock-cover comparison in Chapter 4. Evidence cut-off and findings are unchanged.

**Evidence labels used throughout:** Observed (external fact from a named source), Benchmark (sector statistic with stated population), Proxy (indirect measure), Judgement (analytic judgement by this report), Assumption (scenario assumption), Action (management recommendation or challenge question). Each statement is preceded by its source reference in the form [Source - Title][n]. Tier 1 sources are official, regulatory, legal, law-enforcement or affected-organisation records; Tier 2 sources are research with disclosed methods; Tier 3 sources are media or aggregators and are never the sole support for a material finding. Full details are in the References section and in 02_source_register.csv.

## Sector Exposure & Executive Risk Outlook

### Bottom line

[Stryker - Form 8-K/A April 2026][1] [NHS England - Stryker supply disruption letter][3] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [West Pharmaceutical - Form 8-K May 2026][15] [BVO Nederland - Annual report 2025][28] Judgement: the most consequential Healthcare cyber events of the period disrupted care through suppliers rather than through attacks on clinical devices. Two global medical-device manufacturers and one pharmaceutical-component manufacturer declared material incidents that disrupted manufacturing, ordering or shipping, and a Dutch screening programme halved its primary invitations after an outsourced laboratory breach removed one of three laboratories from service. [Stryker - Customer updates on network disruption][2] [BOA - Stryker update 27 March 2026][4] Observed: in the Stryker case the National Health Service (NHS) in England moved six product lines to controlled allocation and some patient cases were rescheduled, while UK orthopaedic societies reported on 27 March that production had resumed. [ANS CERT Sante - Observatory 2025][33] Observed: at provider level, the French national health incident observatory recorded 288 reports in 2025 involving degraded-mode operation or interrupted care. [Stryker - Form 10-Q Q1 2026][5] [Conduent - Form 10-Q Q2 2026][41] Judgement: public financial disclosure is concentrated in listed, mostly US-domiciled manufacturers and processors; publicly funded EU and UK providers rarely publish incident costs, so the absence of a European loss figure is an evidence gap, not evidence of low loss. For a bank, relevance is conditional and indirect: corporate counterparty earnings and working capital, provider cash flow when claims or supply chains stop, regulatory and litigation outcomes, and public-budget absorption. No assertion is made about any specific institution's exposure.

### Principal judgements

**1. Supplier and manufacturer outages were the most publicly evidenced care-continuity channel in the period (Judgement; confidence medium).** [Stryker - Form 8-K/A April 2026][1] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [West Pharmaceutical - Form 8-K May 2026][15] Three manufacturers filed material cybersecurity incident reports with the US Securities and Exchange Commission (SEC) under Item 1.05 between March and September 2026, each describing global disruption to manufacturing, order processing or shipping. [NHS England - Stryker supply disruption letter][3] [Stryker - Customer updates on network disruption][2] In the Stryker case, NHS England required acute, community, mental-health and ambulance trusts to report dependency through a situation report (SitRep), and the company stated that some patient cases were rescheduled because of shipping delays. **Competing explanation:** manufacturers are listed companies with mandatory disclosure duties, while providers are not, so the supplier pathway may be over-represented in public evidence. **Relationship to judgement 2:** judgement 1 concerns which channel is most visible in public disclosure across many providers at once; judgement 2 concerns the mechanism behind care disruption once it occurs, which at providers is mostly loss of clinical information. **What would change this judgement:** disclosure of provider-originated disruptions in the EU or UK with comparable breadth.

**2. Loss of trusted clinical information, not device compromise, drives most observed care disruption (Judgement; confidence medium).** [ANS CERT Sante - Observatory 2025][33] The French observatory recorded 288 of 764 reports in 2025 involving degraded-mode operation or interrupted care. [VRT NWS - AZ Monica EPR restart][21] [Belgian Chamber - Committee record 3 February 2026][23] At AZ Monica in Belgium, a precautionary shutdown of servers in January 2026 forced about three weeks of paper-based operation before electronic patient records were restored (impact detail is Tier 3 media-relayed; the attack is confirmed by a Tier 1 parliamentary record). [Stryker - Customer updates on network disruption][2] [Boston Scientific - Cyber update 8 September 2026][13] Both disrupted manufacturers stated that connected products or product function were not impaired, but one temporarily could not activate new remote cardiac monitoring. **What would change this judgement:** an authority-confirmed in-period incident in which a connected medical device was manipulated with clinical effect.

**3. Credential and access abuse at software vendors and providers is the main data-exposure pathway and transmits through regulation and litigation (Judgement; confidence medium-high).** [Cegedim Sante - Statement 4 March 2026][17] A French clinical software vendor reported that a published file held 15.8 million administrative patient records from one software product. [Veradigm - Form 8-K September 2026][25] A US electronic health record (EHR) vendor reported that a third-party vendor's application programming interface (API) credentials were used to download patient personal data. [EDPB - CNIL fine on Hopital Prive de la Loire][30] The French data protection authority (CNIL) fined a private hospital EUR 500,000 in September 2026 after remote access without multi-factor authentication (MFA) enabled a breach affecting 524,867 patients. **What would change this judgement:** evidence that ransomware encryption rather than access abuse dominated EU data-exposure notifications in the period.

**4. State-linked hacktivist activity has reached the healthcare supply chain (Judgement; confidence medium).** [HIPAA Journal - Stryker cyberattack][9] [FBI - FLASH on Iranian MOIS actors][10] A persona named Handala claimed the Stryker attack (claim reported by media), and the US Federal Bureau of Investigation (FBI) separately assesses that Handala is linked to an online entity operated by Iran's Ministry of Intelligence and Security (MOIS). [Stryker - Form 8-K/A April 2026][1] Stryker's own filings do not attribute the attack, and descriptions of device wiping come from media and researchers, not from the company. The geopolitical threat therefore converts into a macro-financial exposure through manufacturer earnings and hospital supply, not through patient data alone. **What would change this judgement:** official attribution by a government authority of the Stryker incident to a state actor, or evidence that the claim was opportunistic.

**5. EU sector maturity remains below its sector importance, and EU legal coverage is uneven at the cut-off (Judgement; confidence medium).** [ENISA - NIS360 2026][32] The EU Agency for Cybersecurity (ENISA) placed health in its "risk zone" in May 2026, defined as lower-than-average maturity with sector importance (ENISA's measure of how much the sector matters) exceeding maturity, while noting that health maturity improved within the moderate band. [European Commission - NIS2 CJEU referral][46] [European Commission - CER CJEU referral][48] The Commission referred Ireland, Spain, France and the Netherlands to the Court of Justice on 8 July 2026 for not notifying full transposition of the NIS2 Directive, and, in a separate 2026 decision (IP/26/910), referred seven Member States, including France and the Netherlands, for not transposing the CER Directive (Directive (EU) 2022/2557). [ENISA - NIS360 2026][32] ENISA also reports that healthcare providers struggle more than pharmaceutical manufacturers with best practice, citing budgets and skilled staff, and that compromise of a managed service provider or software vendor can give access to many hospitals at once. **What would change this judgement:** completed transposition notifications and a higher health maturity score in the next ENISA cycle.

### What changed in the period

| Development | Date | Why it matters | Evidence type |
|---|---|---|---|
| [BVO Nederland - Annual report 2025][28] Dutch cervical screening primary invitations reduced by 50% after loss of one laboratory | From 22 December 2025 | Shows a data breach can reduce public-health service capacity months later through supplier substitution limits | Observed, Tier 1 |
| [Stryker - Form 8-K/A April 2026][1] Stryker material cybersecurity incident | Identified 11 March 2026 | First large medical-device manufacturer outage with documented NHS supply measures | Observed, Tier 1 |
| [West Pharmaceutical - Form 8-K May 2026][15] [West Pharmaceutical - Cyberattack updates][73] West Pharmaceutical encryption and exfiltration | Detected 4 May 2026 | Extends the manufacturing pathway to pharmaceutical packaging components and delivery devices | Observed, Tier 1 |
| [IGJ - Clinical Diagnostics finding][29] Dutch Health and Youth Care Inspectorate (IGJ) finds laboratory non-compliant with NEN 7510 | 13 May 2026 | Regulator expects providers to verify laboratory security | Observed, Tier 1 |
| [ENISA - NIS360 2026][32] Health remains in ENISA risk zone | 28 May 2026 | EU-level maturity signal | Observed, Tier 1 |
| [European Commission - NIS2 CJEU referral][46] NIS2 Court of Justice referral of four Member States | 8 July 2026 | Legal perimeter incomplete in France and the Netherlands | Observed, Tier 1 |
| [EUR-Lex - Digital Omnibus on AI][55] AI Act high-risk date for regulated products moved to 2 August 2028 | In force 27 July 2026 | Defers AI obligations for AI in medical devices | Observed, Tier 1 |
| [Boston Scientific - Form 8-K Item 1.05 September 2026][12] Boston Scientific expects to miss Q3 and full-year guidance | 8 September 2026 | Second medical-device manufacturer with material financial effect | Observed, Tier 1 |
| [European Commission - CRA summary][53] Cyber Resilience Act (CRA) reporting obligations apply | 11 September 2026 | Vulnerability reporting for non-device health software and components | Observed, Tier 1 |
| [EDPB - CNIL fine on Hopital Prive de la Loire][30] CNIL fines a private hospital EUR 500,000 | Decision 3 September 2026 | GDPR enforcement for missing MFA and detection | Observed, Tier 1 |
| [UK Parliament - Cyber Security and Resilience Bill][60] UK Cyber Security and Resilience Bill at House of Lords Report stage | At 14 October 2026 | UK reform not yet law | Observed, Tier 1 |

### Sector footprint and subsector coverage

[ENISA - Threat Landscape 2026][31] Observed: ENISA's 2026 threat landscape, covering 2025 incidents, places health among the five sectors most represented in Member State incident reporting under NIS2, records that unauthorised access against health was led by financially motivated attacks (46%) with ransomware at 26.8%, and that healthcare providers accounted for 63.6% of health data breaches and 85.5% of DDoS (distributed denial of service) claims against the sector. [ENISA - Threat Landscape 2026][31] Limitation: ENISA states its dataset is mainly open-source, sector categorisation is imperfect, and the health share of all incidents is shown only in a figure. [CCB - NIS2 scope visual][45] Observed: the NIS2 health sector covers healthcare providers, EU reference laboratories, research and development of medicinal products, manufacture of basic pharmaceutical products and preparations, and manufacture of medical devices considered necessary during a public health emergency, while manufacturers of medical devices and in vitro diagnostic medical devices sit in the NIS2 manufacturing sector.

| Subsector | Coverage in this report | Principal evidence | Status |
|---|---|---|---|
| Hospitals and integrated systems | AZ Monica; French observatory; CNIL fine | [ANS CERT Sante - Observatory 2025][33] [EDPB - CNIL fine on Hopital Prive de la Loire][30] [Belgian Chamber - Committee record 3 February 2026][23] | Supported |
| Primary and community care | GP and practice software breach | [Cegedim Sante - Statement 4 March 2026][17] | Supported |
| Mental-health and long-term care | Observatory includes medico-social structures; NHS SitRep included mental-health trusts | [ANS CERT Sante - Observatory 2025][33] [NHS England - Stryker supply disruption letter][3] | Partial |
| Emergency and ambulance | AZ Monica mobile teams; NHS SitRep included ambulance trusts | [The Record - AZ Monica cyberattack][20] [NHS England - Stryker supply disruption letter][3] | Partial |
| Laboratories, pathology and imaging | Dutch screening laboratory; Synnovis (historical) | [BVO Nederland - Annual report 2025][28] [NHS England London - Synnovis clinical impact update][39] | Supported |
| Blood and transplant | Synnovis historical only | [NHS England London - Synnovis clinical impact update][39] | Partial, historical |
| Pharmaceutical manufacturing and components | West Pharmaceutical | [West Pharmaceutical - Form 8-K May 2026][15] | Supported |
| Medical-device and IVD manufacturers | Stryker; Boston Scientific | [Stryker - Form 8-K/A April 2026][1] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] | Supported |
| Pharmaceutical distribution | McKesson (limited disclosure) | [McKesson - Form 8-K August 2026][24] | Partial |
| Payers and claims processing | Conduent; Change Healthcare (historical) | [Conduent - Form 10-Q Q2 2026][41] [UnitedHealth - Q3 2024 results release][37] | Supported |
| EHR and clinical software vendors | Cegedim Sante; Veradigm | [Cegedim Sante - Statement 4 March 2026][17] [Veradigm - Form 8-K September 2026][25] | Supported |
| Health-data platforms | European Health Data Space | [European Commission - EHDS timeline][51] | Regulatory only |
| Telehealth | No in-scope public incident with disclosed outcome found | Targeted search completed | Gap |
| Connected devices and clinical OT | Remote-monitoring activation disruption; product-safety statements | [Boston Scientific - Cyber update 8 September 2026][13] [Stryker - Customer updates on network disruption][2] | Partial |
| Managed IT and outsourced support | UK penalty on an NHS software and IT provider | [ICO - Advanced penalty][43] | Partial, contextual |
| Public health authorities | Dutch screening programme operator | [BVO Nederland - Annual report 2025][28] | Supported |

### Financial-system relevance

[Stryker - Q1 2026 results release][6] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [UnitedHealth - Q3 2024 results release][37] [EDPB - CNIL fine on Hopital Prive de la Loire][30] Judgement: the evidence supports five conditional transmission channels to the financial system, none of which is asserted for any specific institution. First, corporate counterparty earnings and working capital at listed manufacturers and processors, shown by a quarterly earnings decline and a guidance withdrawal. Second, provider liquidity when claims clearing stops, shown historically by USD 8.9 billion of loans advanced to care providers in nine months of 2024 after the Change Healthcare attack. Third, regulatory fines and notification costs under data-protection law. Fourth, litigation following large notifications. Fifth, public-budget absorption of recovery costs at publicly funded providers, which is largely undisclosed. Insurance recoveries were not disclosed in any filing reviewed.

## Key Threats & Top 5 Cyber Attacks

### Selection criteria

Judgement: incidents qualify for the Top 5 when they (a) were identified or disclosed between 1 September 2025 and 14 October 2026, (b) have at least one Tier 1 source confirming occurrence, (c) disclose an operational, care-continuity, financial or regulatory outcome, and (d) represent a distinct Healthcare subsector or pathway. Ranking weighs breadth of affected service, concentration or propagation potential, evidence strength, financial transmission and action relevance. Five incidents meet the standard; they are named incidents, not threat categories. The case study in Chapter 5 (a July 2025 laboratory breach with in-period consequences) is assessed separately because its trigger precedes the period.

### Threat pathways (patterns, not incidents)

| Pattern | Operational vulnerability | Systemic or concentration risk | Evidence |
|---|---|---|---|
| P1 Identity and administration-plane abuse | Privileged or administrative identities control many endpoints or tenants at once | One compromised identity plane can stop manufacturing or expose a vendor's whole customer base | [Stryker - Customer updates on network disruption][2] [Health-ISAC - ShinyHunters identity campaign alert][68] [Veradigm - Form 8-K September 2026][25] |
| P2 Ransomware and destructive intrusion against operators | Encryption or precautionary shutdown removes EPR, laboratory and ordering systems | Regional care capacity loss and diversion to neighbouring providers | [ENISA - Threat Landscape 2026][31] [West Pharmaceutical - Form 8-K May 2026][15] [The Record - AZ Monica cyberattack][20] |
| P3 Credential and remote-access abuse at software vendors and providers | Accounts without MFA or adequate access scoping allow bulk extraction | Data exposure across many practices from one vendor | [Cegedim Sante - Statement 4 March 2026][17] [EDPB - CNIL fine on Hopital Prive de la Loire][30] [ANS CERT Sante - Observatory 2025][33] |
| P4 Outsourced clinical-service concentration | Few qualified laboratories or suppliers with limited spare capacity | Loss of one supplier reduces programme throughput | [BVO Nederland - Annual report 2025][28] [NHS England - Stryker supply disruption letter][3] |
| P5 Geopolitical and hacktivist targeting | Destructive intent rather than extortion lengthens recovery | Supply-chain targets selected for symbolic or national affiliation | [FBI - FLASH on Iranian MOIS actors][10] [ENISA - Threat Landscape 2026][31] |

[ENISA - Threat Landscape 2026][31] Observed: ENISA names Qilin, INC Ransom and SafePay as the most deployed ransomware strains against health in 2025, and names Hezi Rash, Dark Storm Team and Keymous+ as the most active DDoS groups. [ANS CERT Sante - Observatory 2025][33] Observed: France recorded 28 ransomware incidents in health in 2025, down 30% from 2024, while compromise of messaging accounts made up 50% of system-compromise vectors; this indicates a shift from encryption towards account abuse in that national population.

### Top 5 named incidents in the period

| Rank | Incident | Subsector and geography | Period | Operational vulnerability | Consequence | Evidence strength | Sector relevance |
|---|---|---|---|---|---|---|---|
| 1 | Stryker global network disruption | Medical-device manufacturer; global, Irish international headquarters; UK supply effect | Identified 11 March 2026; fully operational 1 April 2026 | Internal Microsoft environment; malicious file used to run commands | Manufacturing, ordering and shipping disrupted for about three weeks; NHS controlled allocation of six lines; some patient cases rescheduled; material Q1 impact | Tier 1 filings, company updates and NHS England letter | Single supplier outage reaching hospitals across countries |
| 2 | Boston Scientific global disruption | Medical-device manufacturer; global | Identified 25 August 2026; restoration early September 2026 | Unauthorised activity on IT systems limiting operating systems and business applications | Global manufacturing, order processing and shipping disrupted; guidance expected to be missed; remote-monitoring activations paused | Tier 1 filings and updates; CEO remarks Tier 3 | Repeat of the manufacturer pathway within six months |
| 3 | Cegedim Sante MLM software breach | Primary-care practice software; France | Detected late 2025; disclosed 26 February 2026 | Abnormal application queries on doctor accounts (Tier 3 detail) | 15.8 million administrative records published; about 165,000 with free-text notes; ministers summoned the vendor | Tier 1 company statement; ministerial detail Tier 3 | Vendor concentration across about 1,500 doctor users (Tier 3) |
| 4 | West Pharmaceutical encryption and exfiltration | Pharmaceutical packaging components and delivery devices; global, including German manufacturing | Detected 4 May 2026 | Systems encrypted and data exfiltrated; global systems taken offline | Global operations disrupted; manufacturing restarted site by site; fully operational 20 May 2026 | Tier 1 filings and company updates | Upstream input to pharmaceutical manufacturers |
| 5 | AZ Monica hospital shutdown | Acute hospital; Belgium | 13 January 2026 to about mid-February 2026 | Server compromise prompting shutdown at both campuses | Scheduled surgeries cancelled; seven unstable patients transferred; emergency department at reduced capacity; mobile emergency teams unavailable; three weeks on paper | Tier 1 parliamentary record of the attack; impact detail Tier 3 relaying hospital statements | Direct EU acute-care disruption |

**1. Stryker (medical-device manufacturer).** [Stryker - Form 8-K/A April 2026][1] Observed: Stryker identified the incident on 11 March 2026, determined that it had a material impact on operations with a resulting effect on first-quarter 2026 results, and reported on 9 April 2026 that it was fully operational across its global manufacturing network with ordering and distribution restored. [Stryker - Customer updates on network disruption][2] Observed: the company described the event as contained to its internal Microsoft environment, stated that connected products remained safe, reported on 19 March that some personalised implant customers were disrupted and some patient cases in the week of 16 March were rescheduled because of shipping delays, and on 23 March described a malicious file used to run commands and hide activity. [HIPAA Journal - Stryker cyberattack][9] Context (Tier 3): media and researchers reported abuse of the device-management platform to wipe corporate devices; Stryker's own disclosures do not use that description. [NHS England - Stryker supply disruption letter][3] Observed: on 18 March 2026 NHS England estimated UK supply-chain stock at about two weeks at normal ordering volumes, cancelled orders placed between 11 and 16 March, placed six NHS Supply Chain lines under control demand management, required mutual aid between trusts and set a SitRep deadline of 19 March. [BOA - Stryker update 27 March 2026][4] Observed: on 27 March the British Orthopaedic Association relayed that production had resumed and trauma and elective orthopaedic procedures could continue as planned.

**2. Boston Scientific (medical-device manufacturer).** [Boston Scientific - Form 8-K 26 August 2026][11] Observed: Boston Scientific identified an incident on 25 August 2026 that disrupted access to information systems and its ability to process and ship orders globally. [Boston Scientific - Form 8-K Item 1.05 September 2026][12] Observed: on 8 September it reported that manufacturing, order processing and shipping had been affected, that it was unlikely to meet net sales growth and adjusted earnings-per-share guidance for the third quarter and full year 2026, that it expected to recover part of the lost revenue, and that it did not expect a material impact on long-term financial condition. [Boston Scientific - Cyber update 8 September 2026][13] Observed: sterilisation facilities were operational, major distribution centres were shipping at or above normal levels, and new LATITUDE remote-monitoring activations, which had been disrupted, were restored. [Healthcare Dive - Boston Scientific restoration][14] Context (Tier 3): the chief executive was reported as saying all plants and distribution centres were shut globally and some procedures were lost because of hospital supply shortages.

**3. Cegedim Sante MonLogicielMedical (MLM) breach (clinical software vendor).** [Cegedim Sante - Statement 4 March 2026][17] Observed: Cegedim Sante stated that the incident was detected at the end of 2025, that a malicious actor published a file containing 15.8 million administrative records after deduplication (names, dates of birth and partial contact details), that about 165,000 records (about 1%) contained a doctor's free-text note that may hold sensitive information, that only MLM was affected, and that the CNIL was informed and a criminal complaint filed. [Egora - Cegedim summoned by ministers][18] Context (Tier 3): 1,500 of 3,800 MLM doctor users were reported as affected, and the health and digital ministers summoned the company on 5 March 2026 and asked it to accelerate NIS2 and CRA compliance and generalise MFA.

**4. West Pharmaceutical Services (pharmaceutical components manufacturer).** [West Pharmaceutical - Form 8-K May 2026][15] Observed: West detected an intrusion on 4 May 2026, determined on 7 May that the attack was material, reported that data was exfiltrated and systems were encrypted, took systems offline globally, and reported that shipping, receiving and manufacturing had restarted at some sites with no full restoration timeline. [West Pharmaceutical - Q2 2026 results release][16] Observed: second-quarter non-GAAP adjustments include USD 6.9 million of nonrecurring professional fees that combine the cyber incident with certain legal matters; the cyber share is not separated. [West Pharmaceutical - Cyberattack updates][73] Observed: company updates show high-value product, standard packaging (including seals) and delivery-device sites, including Eschweiler in Germany, resuming shipping or ramping manufacturing by 15 May, and the company fully operational across manufacturing, supply chain and commercial sites on 20 May 2026.

**5. AZ Monica (acute hospital).** [Belgian Chamber - Committee record 3 February 2026][23] Observed (Tier 1): the cyberattack on AZ Monica was the subject of a parliamentary question answered by the federal health minister on 3 February 2026. [VRT NWS - Belgian hospital cyber readiness][19] [The Record - AZ Monica cyberattack][20] Media-relayed hospital statements (Tier 3): on 13 January 2026 the hospital shut down servers at its Antwerp and Deurne campuses, cancelled scheduled surgery, transferred seven unstable patients with Red Cross support, ran its emergency department at reduced capacity and reported mobile emergency and paramedic intervention teams unavailable. [VRT NWS - AZ Monica EPR restart][21] [VRT NWS - AZ Monica six months on][22] Media-relayed (Tier 3): electronic patient records were restarted on 5 February 2026, activity reached 70-80% after one week and full operation after about four weeks; the hospital refused a ransom, restored from intact backups, reported no sign of data theft, and still had no patient wireless network in August 2026. Evidence boundary: no primary hospital or authority statement on these impact details was retrievable at the cut-off, so confidence in the detail is medium.

### Considered but not selected

| Incident | Reason not in Top 5 | Evidence |
|---|---|---|
| McKesson pharmaceutical distributor incident (discovered 25 August 2026) | Company had not determined scope or materiality at filing | [McKesson - Form 8-K August 2026][24] |
| Veradigm third-party API credential misuse (8-K 8 September 2026) | No operational disruption; company does not expect material impact | [Veradigm - Form 8-K September 2026][25] |
| Hôpital Privé de la Loire breach (summer 2025) | Event precedes the period; used for the in-period regulatory outcome | [EDPB - CNIL fine on Hopital Prive de la Loire][30] |
| DXS International NHS supplier incident (December 2025) | Tier 3 evidence only; NHS England reported no patient-service impact | [The Register - DXS International incident][71] |
| Other 2026 medical-technology incidents (for example UFP Technologies, Medtronic, Abbott, Cook Medical) | Discovery list only; outcomes not disclosed or not material | [MedTech Dive - Medtech cyberattacks 2026][70] |
| Synnovis pathology attack (June 2024) | Historical; used as benchmark for laboratory dependency | [NHS England London - Synnovis clinical impact update][39] |

## Financial Impact: Healthcare

### Bottom line

[Stryker - Q1 2026 results release][6] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [Conduent - Form 10-Q Q2 2026][41] [EDPB - CNIL fine on Hopital Prive de la Loire][30] Judgement: in-period public financial evidence comes from corporate filings and regulatory penalties; none of the in-period EU or UK provider incidents disclosed a cost figure. The quantified outcomes are not additive: they differ in currency, period, statistic and population, and are shown separately below. Care-service disruption is evidenced in counts of cancelled or deferred activity and in service reductions, not in money.

### Public operational and financial outcomes

| Case | Impact type | Metric as disclosed | Period | Evidence |
|---|---|---|---|---|
| Stryker | Revenue timing and margin | Q1 2026 net sales USD 6,020 million (+2.6% reported, +2.4% organic); adjusted EPS USD 2.60 (-8.5%); adjusted operating margin 21.1% (-180 basis points); full-year guidance maintained at 8.0-9.5% organic growth | Q1 2026 | [Stryker - Q1 2026 results release][6] [Stryker - Form 10-Q Q1 2026][5] |
| Stryker | Production interruption | About three weeks from the 11 March disruption to the 1 April statement that manufacturing was fully operational; management also said it could not make product for almost three weeks (call transcript, Tier 3) and cited lost manufacturing absorption alongside tariffs | Q1 2026 | [Stryker - Customer updates on network disruption][2] [Stryker - Form 8-K/A April 2026][1] [Motley Fool - Stryker Q1 2026 call transcript][7] |
| Stryker | Recovery | Q2 2026 net sales USD 6,589 million, organic growth 9.0%; guidance narrowed to 8.3-9.3% organic growth | Q2 2026 | [Stryker - Q2 2026 results release][8] |
| Boston Scientific | Revenue and guidance | Unlikely to meet Q3 and full-year 2026 net sales growth and adjusted EPS guidance; amount not quantified before 28 October 2026 | Q3 2026 | [Boston Scientific - Form 8-K Item 1.05 September 2026][12] |
| West Pharmaceutical | Response cost (combined) | USD 6.9 million pre-tax nonrecurring professional fees including the cyber incident and legal matters | Q2 2026 | [West Pharmaceutical - Q2 2026 results release][16] |
| Conduent (claims and payments processor) | Direct response cost | USD 25 million direct response costs for the January 2025 cyber event (pre-period event and cost; comparative) | Six months to 30 June 2025 | [Conduent - Form 10-Q Q2 2026][41] |
| Hôpital Privé de la Loire | Regulatory outcome | EUR 500,000 CNIL fine; 524,867 patients and 202,246 trusted third parties affected | Decision 3 September 2026 | [EDPB - CNIL fine on Hopital Prive de la Loire][30] |
| Advanced Computer Software Group (NHS IT provider) | Regulatory outcome (contextual, pre-period) | GBP 3,076,320 ICO fine; 79,404 people affected | Announced 27 March 2025 | [ICO - Advanced penalty][43] |
| Dutch screening programme | Care-service reduction | Primary cervical screening invitations reduced by 50% from 22 December 2025; backup laboratories at about 150% capacity for six months | December 2025 onwards | [BVO Nederland - Annual report 2025][28] |
| AZ Monica | Care-service disruption | Scheduled surgery cancelled on day one; seven patient transfers; about four weeks to full operation (Tier 3 detail) | January - February 2026 | [The Record - AZ Monica cyberattack][20] [VRT NWS - AZ Monica six months on][22] |
| Change Healthcare (historical) | Total cost and liquidity support | USD 2,457 million pre-tax total impacts in nine months of 2024 (USD 1,710 million direct response, USD 747 million business disruption); USD 8,904 million loans advanced to care providers, USD 3,189 million repaid | Nine months to 30 September 2024 | [UnitedHealth - Q3 2024 results release][37] |
| Change Healthcare (historical) | Notification scale | About 192.7 million individuals impacted | Figure as of 31 July 2025 | [HHS OCR - Change Healthcare FAQ][38] |
| Synnovis pathology (historical) | Care-service disruption | 10,152 acute outpatient appointments and 1,710 elective procedures postponed (unvalidated management information) | 3 June - 22 September 2024 | [NHS England London - Synnovis clinical impact update][39] |

### Sector benchmarks

| Benchmark | Value | Population and method | Comparability limit | Evidence |
|---|---|---|---|---|
| Average ransomware recovery cost excluding ransom | USD 1.02 million (2024 survey: USD 2.57 million) | 292 healthcare respondents in 17 countries hit by ransomware; organisations of 100-5,000 employees; fieldwork January-March 2025 | Vendor-commissioned survey; excludes large systems; self-reported | [Sophos - Ransomware in Healthcare 2025][34] |
| Median ransom paid; share paying | USD 150,000; 36% paid | Same survey | As above | [Sophos - Ransomware in Healthcare 2025][34] |
| Recovery within one week | 58% of respondents | Same survey | As above | [Sophos - Ransomware in Healthcare 2025][34] |
| Average cost of a data breach, all sectors | USD 4.99 million, up 12% | Ponemon Institute study for IBM, 2026 edition | Global cross-sector; method not reviewed in full | [IBM - Cost of a Data Breach 2026][35] |
| Average cost of a healthcare data breach | USD 6.64 million, costliest sector, down 10.5% from USD 7.42 million | As relayed from the 2026 IBM study | Figure read from trade-press summary, not the full report | [IBM - Cost of a Data Breach 2026][35] [HIPAA Journal - IBM 2026 summary][36] |
| National incident reports involving degraded or interrupted care | 288 of 764 reports (38%) | Mandatory reports from French health establishments and medico-social structures, 2025 | Reporting obligation and thresholds specific to France | [ANS CERT Sante - Observatory 2025][33] |

Judgement: these benchmarks are not applied to any entity. The survey and breach-cost figures describe different populations, cost definitions and periods and must not be combined with the case outcomes above.

### Impact types: what is and is not publicly evidenced

| Impact type | Evidence in the period | Status |
|---|---|---|
| Care-service disruption (cancelled procedures, diversion, diagnostic delay) | [The Record - AZ Monica cyberattack][20] [Stryker - Customer updates on network disruption][2] [BVO Nederland - Annual report 2025][28] Cancelled surgery, transfers, rescheduled cases, screening reduction | Observed, counts limited |
| Response cost | [Conduent - Form 10-Q Q2 2026][41] [West Pharmaceutical - Q2 2026 results release][16] USD 25 million direct response; USD 6.9 million combined line | Observed, few cases |
| Recovery cost | No in-period entity disclosure; survey benchmark only | Benchmark only |
| Revenue and cash-flow effect | [Stryker - Q1 2026 results release][6] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] Earnings decline and guidance miss at manufacturers; claims-delay liquidity effect evidenced only historically | Observed for manufacturers |
| Contractual and supplier impact | [BVO Nederland - Annual report 2025][28] [NHS England - Stryker supply disruption letter][3] Laboratory contract suspended; NHS orders cancelled and controlled allocation | Observed, unquantified |
| Data-breach notification and remediation cost | [Cegedim Sante - Statement 4 March 2026][17] [BVO Nederland - Breach larger than reported][27] Mass notification undertaken; cost not disclosed | Unquantified |
| Regulatory outcome | [EDPB - CNIL fine on Hopital Prive de la Loire][30] [IGJ - Clinical Diagnostics finding][29] Fine and inspectorate finding | Observed |
| Litigation and settlement | [HIPAA Journal - Stryker cyberattack][9] [HIPAA Journal - Conduent breach][42] Employee and class actions reported (Tier 3); no in-period settlement amount confirmed in Tier 1 sources | Context only |
| Insurance effect | No insurance recovery disclosed in filings reviewed | Unavailable |
| Public-funding or government-support effect | [UnitedHealth - Q3 2024 results release][37] Historical provider loan programme by a private payer; EU and UK public recovery budgets undisclosed | Historical proxy |
| Wider economic transmission | [NHS England - Stryker supply disruption letter][3] National supply response coordination; no macroeconomic estimate | Qualitative |

### Financial-system transmission (conditional channels)

[Stryker - Form 8-K/A April 2026][1] [Stryker - Q2 2026 results release][8] Judgement: for large diversified manufacturers, the in-period evidence shows a timing shock rather than a solvency event: Stryker reported a material first-quarter effect, maintained its full-year guidance and reported 9.0% organic growth in the second quarter. [Boston Scientific - Form 8-K Item 1.05 September 2026][12] Judgement: the second manufacturer case moved from timing to guidance, which is the signal a credit or market counterparty would monitor; its quantified effect falls after the cut-off. [UnitedHealth - Q3 2024 results release][37] Judgement: claims-clearing outages transmit directly into provider liquidity; the historical USD 8.9 billion provider loan programme indicates the scale of bridging finance a single clearing outage required in the US system. [BVO Nederland - Annual report 2025][28] Judgement: publicly funded programmes absorb disruption as reduced throughput rather than as a reported loss, which means financial transmission appears later through budgets, backlog funding and supplier contracts. Limitation: no evidence reviewed links any of these cases to losses at a financial institution, and no such inference is made.

## Financial Impact: Worst-Case Scenarios

Scenarios are structured stress narratives built from public evidence and explicit assumptions. They are not forecasts, probability estimates, patient-harm estimates or bank loss estimates. No numerical likelihood is assigned because no defensible external base rate exists for these specific configurations.

### Scenario 1 - Common digital-dependency failure

| Element | Description |
|---|---|
| Trigger | [Cegedim Sante - Statement 4 March 2026][17] [Health-ISAC - ShinyHunters identity campaign alert][68] [Veradigm - Form 8-K September 2026][25] Assumption: a shared EHR, clinical cloud, identity or claims-processing service used concurrently by many providers is compromised through credential or administration-plane abuse |
| Affected service | Scheduling, records access, e-prescribing, laboratory ordering or claims submission across many independent providers at once |
| Propagation pathway | [ENISA - NIS360 2026][32] [Stryker - Customer updates on network disruption][2] [UnitedHealth - Q3 2024 results release][37] Common-mode failure (ENISA notes one vendor or managed-service compromise can reach many hospitals): the platform is withdrawn or isolated, so every dependent organisation loses the function simultaneously; the Change Healthcare precedent shows the claims variant |
| Impact drivers | Number of dependent providers, availability of offline or paper modes, duration of isolation, data exposure triggering mass notification |
| Financial transmission | Provider revenue-cycle and cash-flow delay; vendor liability, notification and remediation cost; GDPR enforcement; possible bridging finance demand from providers |
| Early signposts | Vendor SEC or stock-exchange disclosures; ISAC identity-campaign alerts; regulator statements on vendor breaches; ministerial intervention as in the Cegedim case |
| Limiting conditions | Offline operation of clinical systems; provider-held local copies; segmented tenants; rapid credential revocation |
| Assumptions | No named provider, duration or loss amount is assumed; concurrency is the defining feature |
| Management questions | Which shared EHR, identity, practice-software or claims platforms serve many clients or counterparties at once? What is the documented offline mode and how long can it run? |

### Scenario 2 - Targeted operational disruption

| Element | Description |
|---|---|
| Trigger | [ENISA - Threat Landscape 2026][31] [The Record - AZ Monica cyberattack][20] Assumption: ransomware or destructive intrusion against a major hospital group, pathology or diagnostic provider, or manufacturer forces a precautionary shutdown |
| Affected service | Emergency department capacity, elective surgery, imaging, laboratory results, payroll and ordering |
| Propagation pathway | [The Record - AZ Monica cyberattack][20] [NHS England London - Synnovis clinical impact update][39] Loss of EPR and laboratory systems forces paper operation; unstable patients and urgent work divert to neighbouring providers, which absorb load |
| Impact drivers | [ANS CERT Sante - Observatory 2025][33] [HSSIB - EPR thematic review][69] Duration of degraded mode; backup integrity; regional spare capacity; data re-entry backlog; patient-safety risk from manual workarounds |
| Financial transmission | Activity-based revenue loss for private groups; overtime and recovery spend; public recovery funding; regulatory notification and possible fines; earnings and covenant pressure for listed or leveraged operators |
| Early signposts | Ransomware claims against regional providers; emergency diversion notices; authority statements on hospital readiness; national observatory data on degraded mode |
| Limiting conditions | [VRT NWS - AZ Monica six months on][22] Intact offline backups allowed AZ Monica to restore without paying; regional mutual aid |
| Assumptions | Single operator directly attacked; no assumption about attacker, duration or clinical outcome |
| Management questions | For hospital-group or diagnostic counterparties, what recovery time is evidenced by tested restoration rather than stated? How dependent is regional capacity on one operator? |

### Scenario 3 - Third- or fourth-party supply-chain concentration

| Element | Description |
|---|---|
| Trigger | [Stryker - Form 8-K/A April 2026][1] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [West Pharmaceutical - Form 8-K May 2026][15] [BVO Nederland - Annual report 2025][28] Assumption: a manufacturer, distributor or outsourced laboratory that serves many providers or a national programme is disrupted or suspended |
| Affected service | Implants, instruments, consumables, pharmaceutical packaging components, screening or pathology throughput |
| Propagation pathway | [NHS England - Stryker supply disruption letter][3] Stock buffers (about two weeks in the UK Stryker case) deplete; controlled allocation and mutual aid follow; procedures are rescheduled; substitute suppliers or laboratories run above capacity until backlog forces service reduction |
| Fourth-party element | [Stryker - Customer updates on network disruption][2] [BVO Nederland - Breach larger than reported][27] The Stryker incident ran through the supplier's internal Microsoft environment; the Dutch operator stated the laboratory data may have been obtained through another client of the laboratory |
| Impact drivers | Number of qualified substitutes; stock buffer; regulatory approval needed to switch suppliers; personalised or make-to-order products |
| Financial transmission | Manufacturer revenue deferral and guidance changes; hospital procedure deferral and lost activity income; procurement cost of substitutes; public-programme backlog funding |
| Early signposts | SEC Item 1.05 filings by medical-technology and pharmaceutical suppliers; NHS Supply Chain or national supply notices; inspectorate findings on outsourced laboratories |
| Limiting conditions | Consigned inventory at hospitals; multi-sourcing; contractual backup protocols such as the Dutch laboratory back-up arrangement |
| Assumptions | No named supplier is assumed to fail; scenario combines documented mechanisms, not a specific forecast event |
| Management questions | Which corporate counterparties depend on a single upstream manufacturer or outsourced laboratory? How long can stock or backup capacity absorb a three-week production halt? |

### Outage length against stock cover (observed single cases)

| Case | Measure | Days | Evidence |
|---|---|---|---|
| Stryker | 11 March disruption to 1 April statement of full manufacturing operation | 21 | [Stryker - Customer updates on network disruption][2] |
| West Pharmaceutical | 4 May detection to 20 May statement of full operation | 16 | [West Pharmaceutical - Cyberattack updates][73] |
| Boston Scientific | 25 August identification to 8 September report of substantial recovery | About 14 | [Boston Scientific - Form 8-K Item 1.05 September 2026][12] |
| UK stock of Stryker products | NHS England estimate on 18 March (day 7 of the outage) of remaining stock at normal ordering volumes | About 14 more, to about day 21 | [NHS England - Stryker supply disruption letter][3] |

[Stryker - Customer updates on network disruption][2] [West Pharmaceutical - Cyberattack updates][73] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [NHS England - Stryker supply disruption letter][3] Judgement: the three manufacturer outages lasted about two to three weeks, and the UK stock estimate made a week into the Stryker outage implied cover to about the day full manufacturing resumed; the recovery margin was therefore days rather than weeks, and buffers can be exhausted before technical recovery completes. Limitation: these are single cases with different end-points (full versus substantial recovery), the stock estimate applies only to Stryker products in the UK, no source reports that UK stock ran out, and the comparison is not a forecast.

### Scenario distinctness

| Test | Scenario 1 | Scenario 2 | Scenario 3 |
|---|---|---|---|
| Point of failure | Shared digital platform | Single directly attacked operator | Upstream supplier or outsourced service |
| Mode | Simultaneous loss across many users | Local loss with regional spill-over | Sequential depletion of buffers and capacity |
| Main financial channel | Provider cash flow and vendor liability | Operator revenue and recovery cost | Supplier earnings and downstream activity |

## Case Study: Dutch Screening Laboratory Breach

### Why this case

[BVO Nederland - Annual report 2025][28] [IGJ - Clinical Diagnostics finding][29] Judgement: the Clinical Diagnostics NMDL breach in the Netherlands was selected after discovery because it is the only EU or UK case in the evidence base that combines Tier 1 operator and regulator evidence, an in-period care-continuity consequence (halving of primary screening invitations from 22 December 2025), an in-period regulatory outcome (inspectorate finding of 13 May 2026) and a clear third-party concentration mechanism. The trigger in July 2025 precedes the reporting period; its consequences fall within it. The Stryker case scored higher on financial disclosure but lower on EU primary-source depth for patient-service effects, and is covered in Chapters 2 to 4.

Judgement: the qualitative comparison below records the trade-off. The Dutch case was preferred because it is European, its care-continuity and regulatory consequences are documented by the operator and the regulator, and its mechanism (supplier concentration) generalises; its weaknesses are a pre-period trigger and no disclosed financial outcome. Stryker is stronger on recency and financial disclosure and also has Tier 1 patient-service evidence (the NHS England letter and the company's rescheduled-cases statement), but its operational base and attribution sit outside Europe.

| Criterion | Dutch screening laboratory | Stryker | AZ Monica |
|---|---|---|---|
| Recency | Trigger July 2025 (pre-period); consequences December 2025 to May 2026 | March 2026 | January 2026 |
| Sector and geographic relevance | EU public-health programme and laboratory | Global manufacturer; UK supply effect | EU acute hospital |
| Causal clarity | Breach, supplier suspension, capacity limit, invitation cut | Network disruption, production and shipping halt, supply allocation | Shutdown and paper operation; cause detail Tier 3 |
| Operational and patient-service outcome | 50% invitation reduction (Tier 1) | Rescheduled cases and controlled allocation (Tier 1) | Cancelled surgery and transfers (Tier 3) |
| Financial or regulatory outcome | Inspectorate finding; DPA investigation; no cost disclosed | Material Q1 effect; full-year guidance kept | None disclosed |
| Transferability | High: any outsourced clinical service with few substitutes | High: any single-source supplier | Medium: single-site event |
| Evidence quality | Tier 1 operator and regulator | Tier 1 filings and NHS letter | Tier 1 record of occurrence only |

### Timeline

| Date | Event | Evidence |
|---|---|---|
| July 2025 | Hack of Clinical Diagnostics systems; the laboratory informed the programme operator more than a month later | [BVO Nederland - Annual report 2025][28] |
| 5-7 August 2025 | Operator informed (foreword cites 5 August); crisis structure activated 6 August; Dutch Data Protection Authority (AP), national public health institute (RIVM) and IGJ notified 7 August | [BVO Nederland - Annual report 2025][28] |
| 11 August 2025 | Media informed; file covering about 485,000 people | [BVO Nederland - 405,000 participants notified][26] [BVO Nederland - Annual report 2025][28] |
| 19-20 August 2025 | About 405,000 participants linked and notified by letter; tests rerouted to other laboratories | [BVO Nederland - 405,000 participants notified][26] |
| 29 August 2025 | About 230,000 further people confirmed; operator to write to all 941,000 participants whose data was shared with the laboratory since 2017; inspectorate and prosecution investigations announced | [BVO Nederland - Breach larger than reported][27] |
| August 2025 onwards | Backup laboratories ran at about 150% of regular capacity for six months | [BVO Nederland - Annual report 2025][28] |
| December 2025 | Inspectorate visit; work in progress no longer manageable within the programme's framework | [IGJ - Clinical Diagnostics finding][29] [BVO Nederland - Annual report 2025][28] |
| 22 December 2025 | Primary invitations reduced by 50%; follow-up tests continued at 100% | [BVO Nederland - Annual report 2025][28] |
| January 2026 | Review of whether deficiencies can be remedied and cooperation resumed | [BVO Nederland - Annual report 2025][28] |
| 13 May 2026 | IGJ finds the laboratory did not meet NEN 7510 at the time of the hack or the December 2025 inspection | [IGJ - Clinical Diagnostics finding][29] |

### Disruption mechanism

[BVO Nederland - Breach larger than reported][27] Observed: the stolen data included identity and contact details, sex, date of birth, citizen service number, test type and result, and the name of the participant's general practitioner; the operator stated that the data may have been obtained through another client of the laboratory. [IGJ - Clinical Diagnostics finding][29] Observed: the inspectorate found that the laboratory had no independent information security audit and had not periodically mapped the risks in its data processing. [BVO Nederland - Annual report 2025][28] Judgement: the service effect did not come from encryption of laboratory systems but from the operator's decision to suspend a supplier that could no longer be trusted, which removed one of three laboratories from a national programme.

### Operational and patient-service consequences

[BVO Nederland - Annual report 2025][28] Observed: work was transferred under a backup protocol to the laboratories of the Jeroen Bosch Ziekenhuis and Symbiant, which ran at about 150% of regular capacity for six months; by December 2025 accumulated work could no longer be absorbed, and from 22 December 2025 primary invitations to cervical screening were reduced by 50% while follow-up tests continued in full. [BVO Nederland - 405,000 participants notified][26] Observed: the operator stated that results already sent or still to come were not affected and that screened women did not need to be retested. Evidence boundary: no source reviewed reports a clinical outcome attributable to the breach or to the invitation reduction, and none is inferred.

### Public financial and regulatory outcomes

[IGJ - Clinical Diagnostics finding][29] Observed: the inspectorate asked the laboratory to demonstrate NEN 7510 compliance in the short term, noted it cannot impose punitive measures under the Dutch act on supplementary provisions for processing personal data in healthcare (Wabvpz), stated that the AP is investigating under the General Data Protection Regulation (GDPR), and called on care providers that use laboratories or other third parties to verify those parties' information security actively. [BVO Nederland - Annual report 2025][28] Observed: the sections of the operator's annual report reviewed disclose no incident cost, provision, claim or insurance amount. The financial outcome is therefore unavailable, not zero.

### Recovery constraints

[BVO Nederland - Annual report 2025][28] Judgement: recovery was constrained by the scarcity of qualified substitute laboratories and by the need to re-establish trust in the original supplier before resuming cooperation, not by technical restoration. [BVO Nederland - Breach larger than reported][27] Observed: notification of 941,000 participants required careful processing of large data volumes and an external call centre.

### Sector lesson and read-across

[IGJ - Clinical Diagnostics finding][29] [BVO Nederland - Annual report 2025][28] Judgement: a confidentiality breach at an outsourced clinical service can become an availability problem for a whole programme when the purchaser must suspend the supplier and substitutes have little spare capacity. [NHS England - Stryker supply disruption letter][3] Judgement: the same mechanism appears in the Stryker supply case, where stock buffers rather than technical recovery set the time available. Read-across for management: supplier assurance needs both security evidence (certification or independent assessment) and a tested substitution plan with capacity figures.

### What the case does not establish

[BVO Nederland - Annual report 2025][28] The case does not establish any clinical harm, the cost of the incident, the identity of the attacker, or that other laboratories in the Netherlands or elsewhere have similar control gaps. It concerns one national screening programme with three laboratories; programmes with more suppliers may absorb a similar loss differently.

## Systemic Dependencies & Regulatory Outlook

### Dependency chains

| Dependency | Chain | Evidence | Status |
|---|---|---|---|
| Supplier identity and IT platform | Supplier's internal Microsoft environment - manufacturing, ordering and shipping - hospital stock - procedures | [Stryker - Customer updates on network disruption][2] [NHS England - Stryker supply disruption letter][3] | Observed |
| Outsourced laboratory | Laboratory - national screening programme - backup laboratories - invitation volumes | [BVO Nederland - Annual report 2025][28] | Observed |
| Clinical practice software | Vendor platform - about 1,500 doctor users - administrative records of patients | [Cegedim Sante - Statement 4 March 2026][17] [Egora - Cegedim summoned by ministers][18] | Observed (user count Tier 3) |
| Vendor API credentials | Third-party vendor - EHR vendor API - patient personal data of customers | [Veradigm - Form 8-K September 2026][25] | Observed |
| Claims clearing | Clearing house - payer and provider claims - provider cash flow | [UnitedHealth - Q3 2024 results release][37] [HHS OCR - Change Healthcare FAQ][38] | Historical |
| Pharmaceutical components | Packaging and delivery-device manufacturer - pharmaceutical customers - medicine supply | [West Pharmaceutical - Form 8-K May 2026][15] [West Pharmaceutical - Cyberattack updates][73] | Observed upstream; downstream effect not disclosed |
| Remote cardiac monitoring | Manufacturer IT - activation service - new implant monitoring | [Boston Scientific - Cyber update 8 September 2026][13] | Observed |

### Regulatory perimeter (status and dates)

| Regime | Jurisdiction and scope | Status and date basis | Healthcare relevance | Evidence |
|---|---|---|---|---|
| NIS2 Directive (EU) 2022/2555 | EU; health entities in Annex I; medical-device and IVD manufacturers in Annex II | In force since 16 January 2023; transposition deadline 17 October 2024; four Member States referred to the Court of Justice on 8 July 2026 | Risk-management measures including supply-chain security and, where appropriate, MFA or continuous authentication (Article 21(2)(d) and (j)); early warning within 24 hours, notification within 72 hours, final report within one month (Article 23(4)) | [EUR-Lex - NIS2 Directive][44] [CCB - NIS2 scope visual][45] [European Commission - NIS2 CJEU referral][46] |
| CER Directive (EU) 2022/2557 | EU; health sector entities identified by Member States | Member States to identify designated entities by 17 July 2026 (Article 6(1)); seven Member States referred for non-transposition (IP/26/910) | Resilience measures and incident notification within 24 hours (Articles 13 and 15); does not apply to matters covered by NIS2 (Article 1(2)) | [EUR-Lex - CER Directive][47] [European Commission - CER CJEU referral][48] |
| GDPR (EU) 2016/679 | EU; any controller or processor of health data | Applicable law | Health data is a special category (Article 9(1)); security of processing (Article 32); authority notification within 72 hours where feasible (Article 33(1)); communication to individuals for high risk (Article 34(1)) | [EUR-Lex - GDPR][49] [EDPB - CNIL fine on Hopital Prive de la Loire][30] |
| European Health Data Space (EU) 2025/327 | EU; EHR systems, health-data access bodies, data holders | Published 5 March 2025; in force 26 March 2025; most obligations from March 2029; second priority data group March 2031 | EHR systems must include harmonised interoperability and logging components with self-assessed security; general product security handled by the CRA | [EUR-Lex - EHDS Regulation][50] [European Commission - EHDS timeline][51] |
| MDR (EU) 2017/745 and IVDR (EU) 2017/746 with MDCG 2019-16 Rev.1 | EU; medical-device and IVD manufacturers | Binding device requirements; MDCG guidance not legally binding (July 2020) | Software security and minimum IT security requirements (MDR Annex I 17.2, 17.4; IVDR Annex I 16.2, 16.4); shared responsibility with operators | [MDCG - 2019-16 Rev.1][52] |
| Cyber Resilience Act (EU) 2024/2847 | EU; products with digital elements, excluding products covered by MDR and IVDR | In force 10 December 2024; notified-body provisions from 11 June 2026; reporting obligations from 11 September 2026; main obligations from 11 December 2027 | Applies to non-device health software and components; not to regulated medical devices | [EUR-Lex - Cyber Resilience Act][54] [European Commission - CRA summary][53] |
| AI Act (EU) 2024/1689 as amended by (EU) 2026/1744 | EU; AI in regulated products including medical devices (Annex I) | Amendment in force 27 July 2026; Annex I high-risk date 2 August 2028; Annex III date 2 December 2027 | Defers high-risk AI obligations for AI medical devices | [EUR-Lex - Digital Omnibus on AI][55] |
| EU action plan on hospital cybersecurity | EU; hospitals and healthcare providers | Non-legislative policy launched January 2025 | Four pillars (prevent, detect, respond and recover, deter); EU early warning subscription service planned by 2026 | [European Commission - Hospital cybersecurity action plan][56] |
| UK NIS Regulations 2018 (health, England) | England; NHS trusts and foundation trusts, integrated care boards and certain independent providers | In force; Department of Health and Social Care (DHSC) guidance September 2023 | Incident reporting within 72 hours via the Data Security and Protection Toolkit (DSPT); thresholds include drug or device unavailability over 24 hours; penalties up to GBP 17 million | [DHSC - NIS health sector guide (England)][57] |
| NHS DSPT 2025-26 | England; organisations with access to NHS patient data | Version 8 aligned to Cyber Assessment Framework (CAF) 3.4; submission deadline 30 June 2026 | Assurance route for NHS bodies and suppliers | [NHS England - DSPT 2025-26][58] |
| Cyber Security and Resilience Bill | UK | Bill only: House of Lords Report stage, HL Bill 49 dated 7 September 2026; no Royal Assent at 14 October 2026 | Proposed expansion of NIS duties; not law at cut-off | [UK Parliament - Cyber Security and Resilience Bill][60] |
| UK medical-device regulation (MHRA) | Great Britain | Post-market surveillance amendments in force 16 June 2025; device cybersecurity legislation planned, not enacted | General device incident-reporting deadline shortened to 15 days (previously 30); shorter deadlines for the most urgent categories are not detailed in the source read; planned cyber work package | [MHRA - Post-market surveillance regulations][61] [MHRA - Software and AI roadmap][62] |
| NHS supplier cyber security charter | England; IT suppliers to the NHS | Voluntary statement of intent; list updated 1 October 2026 | MFA, patching, immutable backups, 24/7 monitoring, board exercises, incident reporting | [NHS England - Supplier cyber security charter][59] |
| HIPAA Security Rule amendments (US, comparative) | US covered entities and business associates | Proposed rule published 6 January 2025; agenda estimate of May 2026 not met; no final rule identified at cut-off; trade press reports deferral to 2027 | Proposal only; relevant to multinational providers and vendors | [Federal Register - HIPAA Security Rule NPRM][63] [Reginfo - HIPAA Security Rule agenda][64] [HIPAA Journal - HIPAA Security Rule timing][65] |
| FD&C Act section 524B (US, comparative) | US premarket submissions for cyber devices | Effective 29 March 2023 | Software bill of materials, vulnerability monitoring plan and patching processes | [FDA - Medical device cybersecurity FAQ][66] |
| HHS HPH Cybersecurity Performance Goals (US, comparative) | US healthcare and public health | Voluntary | Essential goals include MFA and vendor cybersecurity requirements | [HHS - HPH Cybersecurity Performance Goals][67] |

### Interaction of device and horizontal regulation

[EUR-Lex - Cyber Resilience Act][54] [MDCG - 2019-16 Rev.1][52] [CCB - NIS2 scope visual][45] [EUR-Lex - EHDS Regulation][50] Judgement: product cybersecurity for a regulated medical device is governed by MDR or IVDR essential requirements, not by the CRA, which excludes those products; the same manufacturer is separately within NIS2 for the security of its own networks and services; EHR systems fall under the EHDS for their harmonised components and under the CRA for general product security. The Stryker and Boston Scientific events were enterprise-network incidents of this NIS2 type rather than device-cybersecurity failures. Limitation: national transposition, entity size thresholds and Member State identification decisions change applicability for individual entities.

### Voluntary frameworks (not binding law)

Judgement: the following are used in this report only as voluntary or technical reference names for control design: ISO/IEC 27001 and 27002 (information security management), ISO 27799 (health informatics security), ISO/IEC 27036 (supplier relationships), IEC 62304 (medical device software lifecycle), IEC 81001-5-1 (health software security lifecycle), IEC 80001-1 (risk management for networks incorporating medical devices), ISO 14971 (medical device risk management), IEC 62443 (industrial automation and control system security), Health Sector Coordinating Council guidance, NIST Cybersecurity Framework 2.0, CISA guidance and CIS Controls. Limitation: the full texts of these standards were not reviewed in this run, and no compliance claim is made against them.

### Forward monitoring horizon

| Date | Milestone | Why it matters | Evidence |
|---|---|---|---|
| 28 October 2026 | Boston Scientific third-quarter results with quantified incident effect | First quantified effect of the second manufacturer event | [Boston Scientific - Form 8-K Item 1.05 September 2026][12] |
| Pending | UK Cyber Security and Resilience Bill final stages and Royal Assent | Determines UK supplier and managed-service perimeter | [UK Parliament - Cyber Security and Resilience Bill][60] |
| Pending | Court of Justice proceedings on NIS2 and CER transposition | Legal certainty in the referred Member States: Ireland, Spain, France and the Netherlands for NIS2; seven Member States, including France and the Netherlands, for CER | [European Commission - NIS2 CJEU referral][46] [European Commission - CER CJEU referral][48] |
| Pending | Dutch Data Protection Authority decision on Clinical Diagnostics | Possible GDPR penalty for an outsourced laboratory | [IGJ - Clinical Diagnostics finding][29] |
| March 2027 | EHDS implementing acts due | Detailed EHR security and logging rules | [European Commission - EHDS timeline][51] |
| 11 December 2027 | CRA main obligations apply | Security requirements for non-device health software | [European Commission - CRA summary][53] |
| 2 August 2028 | AI Act obligations for AI in regulated medical devices | Deferred high-risk AI duties | [EUR-Lex - Digital Omnibus on AI][55] |

## Mitigation Strategies & Security Framework

Actions are sector-informed management priorities and challenge questions derived from the evidence above. They are not claims about the control status or remediation needs of any specific bank or counterparty.

### Evidence-linked action table

| Priority exposure | Operational vulnerability | Control objective | Action or challenge question | Role type | Horizon | Evidence of completion | Residual dependency | External monitoring trigger |
|---|---|---|---|---|---|---|---|---|
| A1 Administration-plane abuse at suppliers | [Stryker - Customer updates on network disruption][2] [Health-ISAC - ShinyHunters identity campaign alert][68] One internal identity or management environment controls manufacturing and order systems | Limit blast radius of privileged identities | Challenge: for Healthcare counterparties, is there evidence of phishing-resistant MFA, privileged-access separation and approval controls for mass device actions? | 1LoD relationship and credit owners with 2LoD cyber risk | 0-6 months | Counterparty attestation or public disclosure of control changes after incidents | Supplier cloud and identity providers | ISAC identity-campaign alerts; supplier Item 1.05 filings |
| A2 Manufacturer outage and stock buffers | [NHS England - Stryker supply disruption letter][3] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] Weeks-long production halts against stock buffers of about two weeks in the UK Stryker case | Bound the time to downstream impact | Challenge: which Healthcare counterparties rely on single-source implants, consumables or components, and what buffer in days is evidenced? | 1LoD sector coverage teams | 0-6 months | Documented single-source map with buffer days | Make-to-order and personalised products | National supply-disruption notices; manufacturer guidance changes |
| A3 Outsourced laboratory concentration | [BVO Nederland - Annual report 2025][28] [IGJ - Clinical Diagnostics finding][29] Few qualified laboratories; substitutes ran at about 150% for six months | Assured substitution capacity | Action: require independent security assessment of outsourced clinical services and a tested substitution plan with capacity figures | Operators' procurement and clinical-governance owners (sector priority) | 6-12 months | Certificate or independent assessment; exercised backup protocol | Specialist laboratory market | Inspectorate findings; programme invitation changes |
| A4 Vendor credential and API misuse | [Veradigm - Form 8-K September 2026][25] [Cegedim Sante - Statement 4 March 2026][17] Third-party credentials and doctor accounts used for bulk extraction | Detect and constrain bulk data access | Challenge: are API and user accounts rate-limited, scoped and monitored for abnormal query volumes at vendors serving many practices? | Vendor security owners; 2LoD third-party risk | 0-6 months | Monitoring rules and alert tests documented | Vendor-held customer data | Vendor disclosures; DPA decisions |
| A5 Missing MFA and detection at providers | [EDPB - CNIL fine on Hopital Prive de la Loire][30] [ICO - Advanced penalty][43] Remote access without MFA; no real-time alerting | Close access paths named in enforcement | Action: treat MFA on remote clinical access and real-time alerting as baseline expectations, consistent with NIS2 Article 21(2)(j), which calls for MFA or continuous authentication where appropriate | Provider IT and data-protection officers (sector priority) | 0-3 months | MFA coverage evidence; alert response tests | Legacy clinical systems | GDPR fines citing Article 32 |
| A6 Precautionary shutdown and paper operation | [VRT NWS - AZ Monica six months on][22] [ANS CERT Sante - Observatory 2025][33] [HSSIB - EPR thematic review][69] Weeks of degraded mode; data re-entry backlog; patient-safety risk in workarounds | Tested recovery and safe degraded mode | Challenge: for hospital-group counterparties, is restoration time evidenced by a test and are offline backups isolated? | Operators' executive and clinical safety leads (sector priority) | 6-12 months | Restoration test reports; downtime procedures | Regional spare capacity | Emergency diversion notices; observatory degraded-mode data |
| A7 Claims and revenue-cycle concentration | [UnitedHealth - Q3 2024 results release][37] [Conduent - Form 10-Q Q2 2026][41] Clearing outage stops provider cash flow | Liquidity resilience to claims interruption | Challenge: which provider counterparties depend on one clearing or claims processor, and what bridging arrangement exists? | 1LoD lending and treasury coverage | 6-12 months | Dependency map; contingency funding terms | Payer and clearing-house market structure | Processor disclosures; payer advance programmes |
| A8 Regulatory perimeter change | [UK Parliament - Cyber Security and Resilience Bill][60] [European Commission - NIS2 CJEU referral][46] [European Commission - CRA summary][53] Obligations differ by jurisdiction and timing | Accurate legal-status tracking | Action: maintain a register distinguishing enacted, applicable, transitional and proposed Healthcare cyber obligations | 2LoD regulatory and compliance | Ongoing | Register reviewed against primary instruments quarterly | National transposition | Royal Assent; CJEU rulings; implementing acts |

### 1LoD and Risk Committee challenge questions

- [Stryker - Form 8-K/A April 2026][1] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] Which Healthcare corporate counterparties have disclosed material cyber incidents in 2026, and has the credit view been refreshed for guidance changes?
- [NHS England - Stryker supply disruption letter][3] Where a counterparty depends on a single manufacturer, what stock buffer in days is evidenced, and how does it compare with the roughly three-week production halt observed in the Stryker case?
- [BVO Nederland - Annual report 2025][28] For outsourced clinical services, is there a substitute with stated spare capacity, and has the switch been exercised?
- [EDPB - CNIL fine on Hopital Prive de la Loire][30] Are MFA on remote clinical access and real-time detection treated as baseline expectations in Healthcare client assessments?
- [UnitedHealth - Q3 2024 results release][37] Which provider clients would need bridging liquidity if a claims-clearing platform stopped for several weeks?
- [UK Parliament - Cyber Security and Resilience Bill][60] Does the regulatory register distinguish the UK Bill (not law) from enacted NIS duties?

### Monitoring triggers

| Trigger | Threshold for escalation | Evidence basis |
|---|---|---|
| SEC Item 1.05 or stock-exchange cyber disclosure by a Healthcare manufacturer, distributor or processor | Any disclosure citing manufacturing, ordering or claims disruption | [Stryker - Form 8-K/A April 2026][1] [West Pharmaceutical - Form 8-K May 2026][15] |
| National supply-disruption notice citing a cyber incident | Controlled allocation of product lines | [NHS England - Stryker supply disruption letter][3] |
| Inspectorate or DPA finding on an outsourced clinical service | Finding of non-compliance or service suspension | [IGJ - Clinical Diagnostics finding][29] |
| ISAC alert on identity-provider or SaaS campaigns targeting health | Active campaign with observed MFA bypass | [Health-ISAC - ShinyHunters identity campaign alert][68] |
| ENISA or national observatory change in degraded-care share | Year-on-year increase in degraded-mode reports | [ANS CERT Sante - Observatory 2025][33] |
| UK Bill Royal Assent; NIS2 and CER court rulings | Change in legal status | [UK Parliament - Cyber Security and Resilience Bill][60] [European Commission - NIS2 CJEU referral][46] |

## Methodology and Evidence Limitations

**Method.** Research followed the skill sequence: input contract, coverage plan, wide discovery, primary-source deep research, normalisation, claim ledger, scenario and regulatory registers, then drafting. Sources were accessed on 15 October 2026; access dates are actual retrieval dates. The report date and evidence cut-off remain 14 October 2026 as specified for this edition: only material published on or before 14 October 2026 is used, and retrieval one day later does not extend the evidence window. Evidence was prioritised by publication date within 2026, then the second and first halves of 2025; older material is labelled historical or contextual with a continuing-relevance rationale in the source register.

**Source tiers and independence.** Tier 1 sources dominate material findings. Tier 3 sources are used only as context or alongside Tier 1 corroboration and are labelled in the text. Repeated media reporting of one incident is grouped under one independence group in the register and is not counted as corroboration.

**Breach-notification data.** Notification counts are treated as evidence of notification, not of root cause, attacker identity or financial outcome.

**Clinical-impact attribution.** [The Record - Synnovis continuing disruption][40] Media reported continuing pathology workarounds and a trust-recorded death in which the 2024 Synnovis attack was considered a contributing factor; these statements were not traced to a published clinical-governance or regulatory report in this review, so they are not used as evidence of patient harm. [King's College Hospital - Synnovis update][72] The affected trust's own November 2025 statement addresses data notification only. No patient harm, mortality or clinical outcome is attributed to any cyber incident in this report.

**Principal gaps.** No in-period EU or UK provider disclosed an incident cost. No telehealth incident with a disclosed outcome was found. Pharmaceutical distribution evidence is limited to an early-stage disclosure. Boston Scientific's quantified impact falls after the cut-off. Insurance recoveries were not disclosed in any filing reviewed. AZ Monica impact details rely on Tier 3 reporting of hospital statements. Some legal instruments were read in partial extracts; annex scope was taken from a national authority summary and dates from official Commission pages, as recorded in the regulatory register.

**Comparability.** Corporate filings, regulatory penalties, surveys and service counts measure different things in different currencies and periods. No totals are computed across them and no sector loss or frequency is extrapolated from the cases.

**Confidence.** Judgements are rated high, medium or low by evidence strength, independence and consistency. Confidence labels are not probabilities.

## References

[1]: https://www.sec.gov/Archives/edgar/data/310764/000119312526149607/d112875d8ka.htm "Stryker - Form 8-K/A April 2026 - Stryker Corporation (SEC) - published 2026-04-09 - accessed 2026-10-15 - Tier 1 - current - Item 1.05"
[2]: https://www.stryker.com/us/en/about/news/2026/a-message-to-our-customers-03-2026.html "Stryker - Customer updates on network disruption - Stryker Corporation - updated 2026-04-01 - accessed 2026-10-15 - Tier 1 - current - dated updates 11 March to 1 April 2026"
[3]: https://www.england.nhs.uk/long-read/stryker-medical-cyber-attack-disruption-supply-medical-equipment-consumables/ "NHS England - Stryker supply disruption letter - NHS England PRN02438 - published 2026-03-18 - accessed 2026-10-15 - Tier 1 - current - Actions 1-3"
[4]: https://www.boa.ac.uk/resource/update-regarding-stryker-cyber-attack-27th-march.html "BOA - Stryker update 27 March 2026 - British Orthopaedic Association - published 2026-03-27 - accessed 2026-10-15 - Tier 1 - current - update body"
[5]: https://www.sec.gov/Archives/edgar/data/310764/000031076426000031/syk-20260331.htm "Stryker - Form 10-Q Q1 2026 - Stryker Corporation (SEC) - filed 2026-05-11 - accessed 2026-10-15 - Tier 1 - current - statements of earnings"
[6]: https://www.sec.gov/Archives/edgar/data/0000310764/000031076426000025/sykex991earningsq12026.htm "Stryker - Q1 2026 results release - Stryker Corporation (SEC Exhibit 99.1) - published 2026-04-30 - accessed 2026-10-15 - Tier 1 - current - release body"
[7]: https://www.fool.com/earnings/call-transcripts/2026/04/30/stryker-syk-q1-2026-earnings-transcript/ "Motley Fool - Stryker Q1 2026 call transcript - The Motley Fool - published 2026-04-30 - accessed 2026-10-15 - Tier 3 - current - prepared remarks"
[8]: https://www.sec.gov/Archives/edgar/data/0000310764/000031076426000048/sykex991earningsq22026.htm "Stryker - Q2 2026 results release - Stryker Corporation (SEC Exhibit 99.1) - published 2026-07-30 - accessed 2026-10-15 - Tier 1 - current - release body"
[9]: https://www.hipaajournal.com/stryker-cyberattack-iran/ "HIPAA Journal - Stryker cyberattack - HIPAA Journal - published 2026-04 - accessed 2026-10-15 - Tier 3 - current - method and lawsuits sections"
[10]: https://www.ic3.gov/CSA/2026/260320.pdf "FBI - FLASH on Iranian MOIS actors - Federal Bureau of Investigation FLASH-20260320-001 - published 2026-03-20 - accessed 2026-10-15 - Tier 1 - current - actor background"
[11]: https://www.sec.gov/Archives/edgar/data/885725/000088572526000056/bsx-20260826.htm "Boston Scientific - Form 8-K 26 August 2026 - Boston Scientific Corporation (SEC) - published 2026-08-26 - accessed 2026-10-15 - Tier 1 - current - Item 8.01"
[12]: https://www.sec.gov/Archives/edgar/data/0000885725/000088572526000059/bsx-20260907.htm "Boston Scientific - Form 8-K Item 1.05 September 2026 - Boston Scientific Corporation (SEC) - published 2026-09-08 - accessed 2026-10-15 - Tier 1 - current - Item 1.05"
[13]: https://news.bostonscientific.com/9-8-26-cyber-update-archive "Boston Scientific - Cyber update 8 September 2026 - Boston Scientific Corporation - published 2026-09-08 - accessed 2026-10-15 - Tier 1 - current - updates of 5 and 8 September"
[14]: https://www.healthcaredive.com/news/boston-scientific-fully-restores-operations-after-cyberattack/830261/ "Healthcare Dive - Boston Scientific restoration - Healthcare Dive - published 2026-09-11 - accessed 2026-10-15 - Tier 3 - current - article body"
[15]: https://www.sec.gov/Archives/edgar/data/105770/000010577026000068/wst-20260507.htm "West Pharmaceutical - Form 8-K May 2026 - West Pharmaceutical Services (SEC) - filed 2026-05-11 - accessed 2026-10-15 - Tier 1 - current - Item 1.05"
[16]: https://www.sec.gov/Archives/edgar/data/105770/000010577026000097/exh991q22026earningsrelease.htm "West Pharmaceutical - Q2 2026 results release - West Pharmaceutical Services (SEC Exhibit 99.1) - published 2026-07-23 - accessed 2026-10-15 - Tier 1 - current - footnote 5"
[17]: https://www.cegedim-sante.com/le-blog/precisions-complementaires-cp-mlm/ "Cegedim Sante - Statement 4 March 2026 - Cegedim Sante - published 2026-03-04 - accessed 2026-10-15 - Tier 1 - current - full statement"
[18]: https://www.egora.fr/actus-pro/sante-numerique/cyberattaque-ciblant-1500-medecins-cegedim-convoque-par-les-ministres "Egora - Cegedim summoned by ministers - Egora - published 2026-03 - accessed 2026-10-15 - Tier 3 - current - chronology section"
[19]: https://www.vrt.be/vrtnws/en/2026/01/14/three-quarters-of-hospitals-dont-yet-have-adequate-cyber-securit.consumer/ "VRT NWS - Belgian hospital cyber readiness - VRT NWS - published 2026-01-14 - accessed 2026-10-15 - Tier 3 - current - article body"
[20]: https://therecord.media/belgium-hospital-cyberattack-antwerp-az-monica "The Record - AZ Monica cyberattack - Recorded Future News - published 2026-01-14 - accessed 2026-10-15 - Tier 3 - current - article body"
[21]: https://www.vrt.be/vrtnws/nl/2026/02/05/az-monica-antwerpen-elektronisch-patientendossier-cyberaanval/ "VRT NWS - AZ Monica EPR restart - VRT NWS - published 2026-02-05 - accessed 2026-10-15 - Tier 3 - current - article body"
[22]: https://www.vrt.be/vrtnws/nl/2026/08/14/half-jaar-na-cyberaanval-az-monica-nog-altijd-geen-wifi-voor-pat/ "VRT NWS - AZ Monica six months on - VRT NWS - published 2026-08-14 - accessed 2026-10-15 - Tier 3 - current - article body"
[23]: https://www.lachambre.be/doc/CCRI/pdf/56/ic312.pdf "Belgian Chamber - Committee record 3 February 2026 - Chamber of Representatives CRIV 56 COM 312 - published 2026-02-03 - accessed 2026-10-15 - Tier 1 - current - question 56012428C p. 51"
[24]: https://www.sec.gov/Archives/edgar/data/927653/000092765326000247/mck-20260825.htm "McKesson - Form 8-K August 2026 - McKesson Corporation (SEC) - published 2026-08-28 - accessed 2026-10-15 - Tier 1 - current - Item 7.01"
[25]: https://www.sec.gov/Archives/edgar/data/1124804/000119312526385249/mdrx-20260908.htm "Veradigm - Form 8-K September 2026 - Veradigm Inc. (SEC) - published 2026-09-08 - accessed 2026-10-15 - Tier 1 - current - Item 8.01"
[26]: https://www.bevolkingsonderzoeknederland.nl/nieuws/ruim-405000-deelnemers-bevolkingsonderzoek-baarmoederhalskanker-ontvangen-brief-na-datalek/ "BVO Nederland - 405,000 participants notified - Bevolkingsonderzoek Nederland - published 2025-08-19 - accessed 2026-10-15 - Tier 1 - H2 2025 - news item"
[27]: https://www.bevolkingsonderzoeknederland.nl/nieuws/datalek-veel-groter-dan-eerder-vermeld/ "BVO Nederland - Breach larger than reported - Bevolkingsonderzoek Nederland - published 2025-08-29 - accessed 2026-10-15 - Tier 1 - H2 2025 - news item"
[28]: https://www.bevolkingsonderzoeknederland.nl/media/01zbqsvn/jaarverantwoording-2025.pdf "BVO Nederland - Annual report 2025 - Bevolkingsonderzoek Nederland - published 2026 - accessed 2026-10-15 - Tier 1 - current - pp. 6, 12, 25-26"
[29]: https://www.igj.nl/actueel/nieuws/2026/05/13/clinical-diagnostics-voldeed-niet-aan-wettelijke-norm-voor-informatiebeveiliging "IGJ - Clinical Diagnostics finding - Inspectie Gezondheidszorg en Jeugd - published 2026-05-13 - accessed 2026-10-15 - Tier 1 - current - news item"
[30]: https://www.edpb.europa.eu/news/health-data-breach-the-cnil-fined-hopital-prive-de-la-loire-500-000-eur_nl "EDPB - CNIL fine on Hopital Prive de la Loire - European Data Protection Board - published 2026-09-09 - accessed 2026-10-15 - Tier 1 - current - news item"
[31]: https://www.enisa.europa.eu/sites/default/files/2026-09/ENISA%20Threat%20Landscape%202026_Final.pdf "ENISA - Threat Landscape 2026 - ENISA - published 2026-09 - accessed 2026-10-15 - Tier 1 - current - pp. 9-10, 19, 38, 49-50"
[32]: https://www.enisa.europa.eu/sites/default/files/2026-05/ENISA%20NIS360%202026.pdf "ENISA - NIS360 2026 - ENISA - published 2026-05 - accessed 2026-10-15 - Tier 1 - current - pp. 5, 8, 12-13, 31-32"
[33]: https://esante.gouv.fr/sites/default/files/media/document/ANS_CERTSante_Rapport_Public_Observatoire_Signalements_ISSIS_2025_VF_1.pdf "ANS CERT Sante - Observatory 2025 - Agence du Numerique en Sante - published 2026 - accessed 2026-10-15 - Tier 1 - current - pp. 4-5, 10, 24, 27-30, 34"
[34]: https://assets.sophos.com/X24WTUEQ/at/cq9bfnh5g9kpw874qqg5th/sophos-state-of-ransomware-in-healthcare-2025.pdf "Sophos - Ransomware in Healthcare 2025 - Sophos - published 2025 - accessed 2026-10-15 - Tier 2 - contextual - pp. 2-4, 9-13"
[35]: https://www.ibm.com/reports/data-breach "IBM - Cost of a Data Breach 2026 - IBM with Ponemon Institute - published 2026-07 - accessed 2026-10-15 - Tier 2 - current - key findings"
[36]: https://www.hipaajournal.com/2026-cost-data-breach-study-ibm/ "HIPAA Journal - IBM 2026 summary - HIPAA Journal - published 2026-07-29 - accessed 2026-10-15 - Tier 3 - current - article body"
[37]: https://www.sec.gov/Archives/edgar/data/731766/000073176624000320/a2024q3exhibit991.htm "UnitedHealth - Q3 2024 results release - UnitedHealth Group (SEC Exhibit 99.1) - published 2024-10-15 - accessed 2026-10-15 - Tier 1 - historical - cyberattack impacts table"
[38]: https://www.hhs.gov/hipaa/for-professionals/special-topics/change-healthcare-cybersecurity-incident-frequently-asked-questions/index.html "HHS OCR - Change Healthcare FAQ - US HHS Office for Civil Rights - reviewed 2025-08-13 - accessed 2026-10-15 - Tier 1 - H2 2025 - affected individuals answer"
[39]: https://www.england.nhs.uk/london/2024/09/26/update-on-cyber-incident-clinical-impact-in-south-east-london-thursday-26-september-2024/ "NHS England London - Synnovis clinical impact update - NHS England London - published 2024-09-26 - accessed 2026-10-15 - Tier 1 - historical - cumulative figures"
[40]: https://therecord.media/ransomware-nhs-cyberattack-disruption "The Record - Synnovis continuing disruption - Recorded Future News - published 2026-04-17 - accessed 2026-10-15 - Tier 3 - current - article body"
[41]: https://www.sec.gov/Archives/edgar/data/1677703/000167770326000092/cndt-20260630.htm "Conduent - Form 10-Q Q2 2026 - Conduent Incorporated (SEC) - published 2026 - accessed 2026-10-15 - Tier 1 - current - Note 4 footnote 1"
[42]: https://www.hipaajournal.com/conduent-business-solutions-data-breach/ "HIPAA Journal - Conduent breach - HIPAA Journal - published 2026-06-04 - accessed 2026-10-15 - Tier 3 - current - notification and litigation sections"
[43]: https://ico.org.uk/about-the-ico/media-centre/news-and-blogs/2025/03/software-provider-fined-3m-following-2022-ransomware-attack/ "ICO - Advanced penalty - Information Commissioner's Office - published 2025-03-27 - accessed 2026-10-15 - Tier 1 - contextual - news item"
[44]: https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:02022L2555-20221227 "EUR-Lex - NIS2 Directive - Official Journal of the EU - published 2022-12-27 - accessed 2026-10-15 - Tier 1 - contextual - Articles 21(2), 23(4)"
[45]: https://ccb.belgium.be/sites/default/files/NIS-2%20Scope%20visual.pdf "CCB - NIS2 scope visual - Centre for Cybersecurity Belgium - undated - accessed 2026-10-15 - Tier 1 - contextual - Annex I sector 5, Annex II sector 5"
[46]: https://digital-strategy.ec.europa.eu/en/news/commission-refers-ireland-spain-france-and-netherlands-court-justice-failing-transpose-rules "European Commission - NIS2 CJEU referral - European Commission - published 2026-07-08 - accessed 2026-10-15 - Tier 1 - current - news item"
[47]: https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32022L2557 "EUR-Lex - CER Directive - Official Journal of the EU - published 2022-12-27 - accessed 2026-10-15 - Tier 1 - contextual - Articles 1(2), 6(1), 13, 15"
[48]: https://ec.europa.eu/commission/presscorner/detail/en/ip_26_910 "European Commission - CER CJEU referral - European Commission IP/26/910 - published 2026 - accessed 2026-10-15 - Tier 1 - current - press release summary"
[49]: https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:02016R0679-20160504 "EUR-Lex - GDPR - Official Journal of the EU - published 2016-05-04 - accessed 2026-10-15 - Tier 1 - contextual - Articles 4(15), 9(1), 32, 33(1), 34(1)"
[50]: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX%3A32025R0327 "EUR-Lex - EHDS Regulation - Official Journal of the EU - published 2025-03-05 - accessed 2026-10-15 - Tier 1 - contextual - recitals 36, 39"
[51]: https://health.ec.europa.eu/ehealth-digital-health-and-care/european-health-data-space-regulation-ehds_en "European Commission - EHDS timeline - European Commission DG SANTE - undated - accessed 2026-10-15 - Tier 1 - contextual - timeline section"
[52]: https://health.ec.europa.eu/document/download/b23b362f-8a56-434c-922a-5b3ca4d0a7a1_en?filename=md_cybersecurity_en.pdf "MDCG - 2019-16 Rev.1 - Medical Device Coordination Group - published 2020-07 - accessed 2026-10-15 - Tier 1 - historical - Table 1 and responsibilities section"
[53]: https://digital-strategy.ec.europa.eu/en/policies/cra-summary "European Commission - CRA summary - European Commission - undated - accessed 2026-10-15 - Tier 1 - contextual - timeline section"
[54]: https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ:L_202402847 "EUR-Lex - Cyber Resilience Act - Official Journal of the EU - published 2024-11-20 - accessed 2026-10-15 - Tier 1 - contextual - Article 2(2)(a)-(b); recital 25"
[55]: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX%3A32026R1744 "EUR-Lex - Digital Omnibus on AI - Official Journal of the EU - published 2026-07-24 - accessed 2026-10-15 - Tier 1 - current - recitals 18, 40, 46"
[56]: https://health.ec.europa.eu/ehealth-digital-health-and-care/digital-health-and-care/european-action-plan-cybersecurity-hospitals-and-healthcare-providers_en "European Commission - Hospital cybersecurity action plan - European Commission DG SANTE - published 2025-01 - accessed 2026-10-15 - Tier 1 - contextual - page body"
[57]: https://www.gov.uk/government/publications/network-and-information-systems-regulations-2018-health-sector-guide/the-network-and-information-systems-regulations-2018-guide-for-the-health-sector-in-england "DHSC - NIS health sector guide (England) - Department of Health and Social Care - published 2023-09-27 - accessed 2026-10-15 - Tier 1 - historical - OES, thresholds, reporting, penalties"
[58]: https://www.dsptoolkit.nhs.uk/News/161 "NHS England - DSPT 2025-26 - NHS England - published 2025-09-18 - accessed 2026-10-15 - Tier 1 - H2 2025 - news item"
[59]: https://digital.nhs.uk/cyber-and-data-security/guidance-and-resources/cyber-security-charter-for-suppliers-to-the-nhs "NHS England - Supplier cyber security charter - NHS England Digital - updated 2026-09-28 - accessed 2026-10-15 - Tier 1 - current - commitments 1-8"
[60]: https://bills.parliament.uk/bills/4035 "UK Parliament - Cyber Security and Resilience Bill - UK Parliament - updated 2026-10-14 - accessed 2026-10-15 - Tier 1 - current - bill stages"
[61]: https://www.gov.uk/government/news/first-major-overhaul-of-medical-device-regulation-comes-into-force-across-great-britain "MHRA - Post-market surveillance regulations - MHRA - published 2025-06-16 - accessed 2026-10-15 - Tier 1 - H1 2025 - news item"
[62]: https://www.gov.uk/government/publications/software-and-ai-as-a-medical-device-change-programme/software-and-ai-as-a-medical-device-change-programme-roadmap "MHRA - Software and AI roadmap - MHRA - updated 2023-06-14 - accessed 2026-10-15 - Tier 1 - historical - work package 5"
[63]: https://www.federalregister.gov/documents/2025/01/06/2024-30983/hipaa-security-rule-to-strengthen-the-cybersecurity-of-electronic-protected-health-information "Federal Register - HIPAA Security Rule NPRM - US HHS OCR - published 2025-01-06 - accessed 2026-10-15 - Tier 1 - contextual - document header"
[64]: https://www.reginfo.gov/public/do/eAgendaViewRule?pubId=202504&RIN=0945-AA22 "Reginfo - HIPAA Security Rule agenda - OIRA Unified Agenda Spring 2025 - published 2025 - accessed 2026-10-15 - Tier 1 - contextual - timetable"
[65]: https://www.hipaajournal.com/final-rule-implementing-hipaa-security-rule-updates-edges-closer/ "HIPAA Journal - HIPAA Security Rule timing - HIPAA Journal - published 2026-03-20 - accessed 2026-10-15 - Tier 3 - current - July 2026 update"
[66]: https://www.fda.gov/medical-devices/digital-health-center-excellence/cybersecurity-medical-devices-frequently-asked-questions-faqs "FDA - Medical device cybersecurity FAQ - US Food and Drug Administration - updated 2025-06-26 - accessed 2026-10-15 - Tier 1 - H1 2025 - section 524B answers"
[67]: https://hhscyber.hhs.gov/cybersecurity-performance-goals.html "HHS - HPH Cybersecurity Performance Goals - US Department of Health and Human Services - undated - accessed 2026-10-15 - Tier 1 - contextual - page body"
[68]: https://www.aha.org/system/files/media/file/2026/08/h-isac-cyber-incidents-tlp-white-shinyhunters-linked-social-engineering-and-identity-targeting-campaign-8-24-26.pdf "Health-ISAC - ShinyHunters identity campaign alert - Health-ISAC alert 04207192 - published 2026-08-24 - accessed 2026-10-15 - Tier 2 - current - techniques and mitigations"
[69]: https://www.hssib.org.uk/news-events-blog/ongoing-risk-of-harm-linked-to-electronic-patient-record-systems/ "HSSIB - EPR thematic review - Health Services Safety Investigations Body - published 2025-11-27 - accessed 2026-10-15 - Tier 1 - H2 2025 - news item"
[70]: https://www.medtechdive.com/news/cyberattacks-have-plagued-the-medtech-industry-in-2026/828489/ "MedTech Dive - Medtech cyberattacks 2026 - MedTech Dive - published 2026-09 - accessed 2026-10-15 - Tier 3 - current - incident table"
[71]: https://www.theregister.com/2025/12/18/nhs_tech_supplier_cyberattack/ "The Register - DXS International incident - The Register - published 2025-12-18 - accessed 2026-10-15 - Tier 3 - H2 2025 - article body"
[72]: https://www.kch.nhs.uk/news/synnovis-cyber-attack-update/ "King's College Hospital - Synnovis update - King's College Hospital NHS Foundation Trust - published 2025-11-10 - accessed 2026-10-15 - Tier 1 - H2 2025 - news item"
[73]: https://www.westpharma.com/support/cyberattack-updates "West Pharmaceutical - Cyberattack updates - West Pharmaceutical Services - updated 2026-05-27 - accessed 2026-10-15 - Tier 1 - current - updates of 7 to 27 May 2026"
