# Migration Record - Manufacturing, Sector Cyber Resilience & Credit Intelligence (Version 1.0-M)

**Status:** NEEDS_REVIEW - migrated edition, not a v4 edition (see MIGRATION_NOTE.md). **Edition state:** DRAFT (migration). **Migration date:** 27 October 2026.
**Evidence cut-off:** 16 October 2026 (unchanged from the source edition). **Reporting period:** 1 September 2025 to 16 October 2026. **Research performed in this migration:** none - no web search or source retrieval.

## 1. Source edition and resolved placeholders

| Brief placeholder | Resolved value (kept from the source edition and the earlier migrations) |
|---|---|
| Legacy structure {5 or 7} | 7-slide legacy structure (seven-chapter report) |
| OLD_DECK_FILE | `13_cyber_sectorial_analysis.pptx` (seven-slide readout) |
| OLD_REPORT_FILE | `15_sectorial_report.docx` / `14_sectorial_report.md` |
| Evidence files | `09_evidence_pack.md`, `02_source_register.csv`, `03_claim_ledger.json`, `06_scenario_assumption_register.csv` and the other registers of the run |
| ORIGINAL_PERIOD | 1 September 2025 to 16 October 2026 |
| ORIGINAL_CUTOFF | 16 October 2026 |
| ORIGINAL_VERSION | 1.0 (baseline edition; the source manifest carries no edition number) - migrated version 1.0-M |
| CLASSIFICATION | Not specified in the source edition; the cover states this and the external-data-only boundary (as in the earlier migrated editions) |
| Rating rubric | none supplied - all ratings Provisional |
| Questionnaire item list | none supplied - Provisional PROV- map |
| Output file name | `Manufacturing_credit_intelligence_briefing_migrated.pptx`. The brief's output line names Building & Public Works, which reads as template residue; the file is named for the sector migrated, as in the Media & Cultural Services migration. |
| Standards paths | The brief cites `core/references/...`; the installed cyber-sectorial-intelligence skill holds them under `skills/cyber-sectorial-analysis/core/`. Read: slide_design_standard.md, publication_standard.md sections 2, 5, 6, 7 and 13, templates/slide_profile_credit_12.json. |
| Visual design | On request, a new set of visual forms within the same palette (white, dark text 1A1A1A, emerald 00915E with flat emerald tints, grey hairlines); see section 8. |

Source edition location: private repository `cybertiagovieira/cyber-risk-reports`, folder `manufacturing/2025-09_2026-10/` (artefact commit 562d218, receipt commit ff4756c). The source edition is not modified by this migration and is not marked SUPERSEDED, because a migrated edition is not a v4 re-issue.

Input hashes (SHA-256) of the source files used:

- `02_source_register.csv`: `3d23228a2612d10cd979949a3acd33ab0f1657075b9db78fcb516bfa0013ad74`
- `03_claim_ledger.json`: `c79e5152b9f167905b1f3ffe295996eacdfec3cd34c7bd60a67f9f7630f4dba1`
- `04_metric_dictionary.csv`: `0e813c1a5e67eb004152d293092c06614d25346389f562e37870116de47cc5c4`
- `05_regulatory_relevance_register.csv`: `f6463fc46d2500ecc2f11faae2c45c5b1a641a62df0497ff5e9acf28a7699e80`
- `06_scenario_assumption_register.csv`: `598e78241d65c0d34bc933fc2691fe321acca346c539a05aca913eaa548a2f8a`
- `09_evidence_pack.md`: `75ac7935d8e187d8069232e0ad377139159306ed18edd621bd1fda16dc929b64`
- `13_cyber_sectorial_analysis.pptx`: `747d3a13872f3a25c15da1646e2fefc452ead604f5a50ac5051a2d74054216ae`
- `14_sectorial_report.md`: `c80c2ab4adc0828e39c87ae54a2a0e6e0a8798a3eb9b26cc2acfdbdad8fb6d02`
- `15_sectorial_report.docx`: `c47d30be601736c2f939050c6ab96b50b5d7108568db2dc8405b76774d47d915`

## 2. Legacy reference -> S- ID mapping

The legacy report numbers its references [1] to [96] in source-register order; each legacy reference [n] maps to S- ID S-nnn in the same order (identity mapping). Tier and observation period are taken from the legacy source register. URLs stay in the legacy report and register; none appears on a slide.

| Legacy reference | S- ID | Short title | Tier | Observation period |
|---|---|---|---|---|
| [1] | S-001 | JLR - Statement on cyber incident, 2 September 2025 | 1 | 1-2 September 2025 |
| [2] | S-002 | JLR - Q2 FY26 volumes release | 1 | 1 July - 30 September 2025 |
| [3] | S-003 | JLR - Restart and supplier financing release | 1 | September - October 2025 |
| [4] | S-004 | JLR - Q2 FY26 results release | 1 | 1 July - 30 September 2025 |
| [5] | S-005 | JLR - Q3 FY26 volumes release | 1 | 1 October - 31 December 2025 |
| [6] | S-006 | JLR - Q3 FY26 results release | 1 | 1 October - 31 December 2025 |
| [7] | S-007 | TMPV - Q4 FY26 results release | 1 | Fiscal year 1 April 2025 - 31 March 2026 |
| [8] | S-008 | JLR - Annual Report 2026 web summary | 1 | Fiscal year to 31 March 2026 |
| [9] | S-009 | UK Government - JLR loan guarantee | 1 | September 2025 |
| [10] | S-010 | CMC - JLR categorisation statement | 2 | Late August 2025 - early January 2026 (modelled) |
| [11] | S-011 | ONS - GDP monthly estimate, September 2025 | 1 | September 2025 and three months to September 2025 |
| [12] | S-012 | SMMT - September 2025 vehicle output | 2 | September 2025 |
| [13] | S-013 | Bank of England - Monetary Policy Report, November 2025 | 1 | Q3 2025 |
| [14] | S-014 | Business and Trade Committee - Letter to JLR, 9 September 2025 | 1 | September 2025 |
| [15] | S-015 | ITV - JLR claim of responsibility report | 3 | September 2025 |
| [16] | S-016 | Asahi - Investigation results, 27 November 2025 | 1 | 29 September - 27 November 2025 |
| [17] | S-017 | Asahi - Business progress update, February 2026 | 1 | October 2025 - February 2026 |
| [18] | S-018 | Asahi - Business progress update, May 2026 | 1 | January - March 2026 |
| [19] | S-019 | Asahi - FY2025 results briefing Q&A | 1 | Calendar year 2025 and Q1 2026 outlook |
| [20] | S-020 | Jiji via Nippon.com - Asahi 2025 results | 3 | Calendar year 2025 |
| [21] | S-021 | Stryker - Form 8-K/A, 9 April 2026 | 1 | 11 March - 9 April 2026 |
| [22] | S-022 | Stryker - Q1 2026 results release | 1 | Q1 2026 |
| [23] | S-023 | MedTech Dive - Stryker disruption report | 3 | 11-13 March 2026 |
| [24] | S-024 | The Record - CISA and FBI endpoint-management guidance | 3 | March 2026 |
| [25] | S-025 | CISA - Endpoint management hardening alert | 1 | March 2026 |
| [26] | S-026 | Boston Scientific - Form 8-K, 26 August 2026 | 1 | 25-26 August 2026 |
| [27] | S-027 | Boston Scientific - Form 8-K Item 1.05, 8 September 2026 | 1 | 25 August - 8 September 2026 |
| [28] | S-028 | MedTech Dive - Boston Scientific manufacturing report | 3 | 25-28 August 2026 |
| [29] | S-029 | Reuters via Business Insurance - Boston Scientific guidance | 3 | September 2026 |
| [30] | S-030 | West Pharmaceutical - Form 8-K Item 1.05, May 2026 | 1 | 4-11 May 2026 |
| [31] | S-031 | Hasbro - Form 8-K, 1 April 2026 | 1 | 28 March - 1 April 2026 |
| [32] | S-032 | Hasbro - Release of 23 April 2026 | 1 | Q1-Q2 2026 |
| [33] | S-033 | Cybersecurity Dive - Fairlife production halt | 3 | 16-17 July 2026 |
| [34] | S-034 | Egide - Cyber incident release, 9 October 2026 | 1 | 6-9 October 2026 |
| [35] | S-035 | CERT-FR - Refrigeration controller alert | 1 | 12-13 October 2026 |
| [36] | S-036 | ComplexDiscovery - French refrigeration incident synthesis | 3 | 11-14 October 2026 |
| [37] | S-037 | RTX - Form 8-K on MUSE incident | 1 | 19-24 September 2025 |
| [38] | S-038 | BleepingComputer - Bridgestone Americas incident | 3 | 2-4 September 2025 |
| [39] | S-039 | Dragos - Industrial ransomware Q2 2026 | 2 | 1 April - 30 June 2026 |
| [40] | S-040 | Black Kite - 2026 manufacturing ransomware report | 2 | January 2023 - July 2026 |
| [41] | S-041 | ENISA - Threat Landscape 2026 | 1 | 1 January - 31 December 2025 |
| [42] | S-042 | Manufacturing Dive - IBM X-Force 2026 findings | 3 | Calendar year 2025 |
| [43] | S-043 | Eurostat - Businesses in the manufacturing sector | 1 | Reference year 2023 |
| [44] | S-044 | Eurostat - EU business economy 2023 | 1 | Reference year 2023 |
| [45] | S-045 | BSI - NIS-2 in figures, Q3 2026 | 1 | 6 December 2025 - 30 September 2026 |
| [46] | S-046 | BSI - German NIS2 law in force | 1 | December 2025 |
| [47] | S-047 | Bundestag - Drucksache 21/8046 | 1 | 2022-2025 statistics; 2026 cases cited by questioners |
| [48] | S-048 | CircleID - Zego insolvency report | 3 | March - July 2026 |
| [49] | S-049 | EUR-Lex - NIS2 Directive | 1 | Applies from 18 October 2024 |
| [50] | S-050 | Streamlex - NIS2 Annex II text | 3 | Not stated |
| [51] | S-051 | European Commission - NIS2 Court referral | 1 | November 2024 - July 2026 |
| [52] | S-052 | European Commission - NIS2 transposition page | 1 | 2024-2026 |
| [53] | S-053 | European Commission - CER Court referral (IP/26/910) | 1 | 2026 |
| [54] | S-054 | EUR-Lex - CER Directive | 1 | Transposition by 17 October 2024; identification by 17 July 2026 |
| [55] | S-055 | EUR-Lex - Regulation (EU) 2024/2847 | 1 | In force 10 December 2024; reporting from 11 September 2026; main obligations 11 December 2027 |
| [56] | S-056 | European Commission - Regulation (EU) 2024/2847 summary | 1 | 2024-2028 |
| [57] | S-057 | ENISA - Single Reporting Platform launch | 1 | From 11 September 2026 |
| [58] | S-058 | EUR-Lex - Implementing Regulation (EU) 2025/2392 | 1 | In force 21 December 2025 |
| [59] | S-059 | Springlex - Regulation (EU) 2024/2847 Article 2 | 3 | Not stated |
| [60] | S-060 | DBT - Explanatory memorandum on Regulation (EU) 2026/1744 | 1 | 2026-2028 |
| [61] | S-061 | ERTICO - Digital Omnibus on AI entry into force | 3 | 2026-2028 |
| [62] | S-062 | euaiact.com - Regulation (EU) 2026/1744 sectoral amendments | 3 | 2026-2028 |
| [63] | S-063 | EU-OSHA - Machinery Regulation page | 1 | Applies from 20 January 2027 |
| [64] | S-064 | KAN - Machinery cybersecurity requirements brief | 2 | 2025-2027 |
| [65] | S-065 | EUR-Lex - Machinery Regulation consolidated | 1 | Applies from 20 January 2027 |
| [66] | S-066 | EUR-Lex - Product Liability Directive | 1 | In force 8 December 2024; transposition by 9 December 2026 |
| [67] | S-067 | Inside Privacy - Product liability transposition update | 3 | 2024-2026 |
| [68] | S-068 | EUR-Lex - Delegated Regulation (EU) 2026/339 | 1 | In force 19 May 2026; repeal effective after 10 December 2027 |
| [69] | S-069 | European Commission - Data Act page | 1 | In force 11 January 2024; applies 12 September 2025 |
| [70] | S-070 | European Commission - GMP Annex 11 consultation | 1 | 7 July - 7 October 2025 consultation |
| [71] | S-071 | Official Journal - UN Regulation No. 155 | 1 | Applicable to new vehicle types since 2022 and to all new M, N, O vehicles since July 2024 |
| [72] | S-072 | European Commission - Seveso III implementation report | 1 | 2019-2022 |
| [73] | S-073 | Council of the EU - FDI screening adoption | 1 | 2026-2028 |
| [74] | S-074 | European Commission - FDI screening publication | 1 | 2026-2028 |
| [75] | S-075 | UK Parliament - Cyber Security and Resilience Bill page | 1 | November 2025 - October 2026 |
| [76] | S-076 | DSIT - Bill summary factsheet | 1 | 2025-2026 |
| [77] | S-077 | Home Office - Ransomware proposals response | 1 | 2025 |
| [78] | S-078 | LGA - Ransomware proposals briefing | 2 | 2025-2026 |
| [79] | S-079 | HSE - Cyber security for industrial automation and control systems | 1 | 2017-2026 |
| [80] | S-080 | Cabinet Office - NSI Act notifiable acquisitions guidance | 1 | In force since 4 January 2022 |
| [81] | S-081 | MOD - Cyber Security Model | 1 | 2026 |
| [82] | S-082 | DSIT - Product security regime guidance | 1 | In force since 29 April 2024 |
| [83] | S-083 | SEC - Cyber disclosure rules fact sheet | 1 | Compliance from December 2023 |
| [84] | S-084 | Federal Register - DFARS CMMC final rule | 1 | Effective 10 November 2025 |
| [85] | S-085 | Squire Patton Boggs - CMMC phases | 3 | 2025-2028 |
| [86] | S-086 | Paubox - CIRCIA final rule status | 3 | 2022-2026 |
| [87] | S-087 | CISA - CFATS lapse statement | 1 | July - November 2023 |
| [88] | S-088 | J. J. Keller - CFATS status | 3 | 2023-2024 |
| [89] | S-089 | CISA and partners - PLC advisory AA26-097A | 1 | March - July 2026 |
| [90] | S-090 | Picus - Summary of advisory AA26-097A | 3 | March - April 2026 |
| [91] | S-091 | NCSC - CEO keynote, CYBERUK 2026 | 1 | 2025-2026 |
| [92] | S-092 | NIST - SP 800-82 Rev. 3 | 1 | 2023; Rev. 4 draft comments to 30 November 2026 |
| [93] | S-093 | NIST - CSF 2.0 Manufacturing Profile draft | 1 | 2025 |
| [94] | S-094 | FDA - Medical device cybersecurity FAQs | 1 | From 29 March 2023 |
| [95] | S-095 | legislation.gov.uk - NIS Regulations 2018 schedules | 1 | In force 10 May 2018; amendments to 2024 |
| [96] | S-096 | eCFR - 32 CFR Part 170 CMMC Program | 1 | Phases from 10 November 2025 |

## 3. Slide-by-slide map (legacy statement -> slide element)

Legacy statement references use claim IDs (C-nnn), metric IDs (M-nnn) and scenario IDs (SC-nnn) from the legacy registers, and report locations (Ch1 to Ch8 of the seven-chapter report; "legacy slide n" for the seven-slide deck). Every element and table cell is placed verbatim on the slide.

### Slide 01 - Sector Intelligence Cover

- **kicker:** Sector Cyber Resilience & Credit Intelligence <- Product name per credit_12 profile
- **sector:** Manufacturing <- Report header: sector
- **period:** Reporting period: 1 September 2025 - 16 October 2026 <- Report header: reporting period
- **geography:** Geography: global, primary focus EU, EEA and UK; North American and East Asian evidence comparative <- Report header: geography, Input contract geography
- **cutoff:** Migrated edition - evidence as of 16 October 2026; no research update <- Report header: evidence cut-off
- **classification:** Classification: not specified in source edition (external public data only) <- Report header: boundary; no classification in source edition
- **version:** Version 1.0-M (migrated from the 16 October 2026 baseline) - Status: NEEDS_REVIEW, not a v4 edition <- Report header: edition (baseline)
- **audience:** Audience: Senior Credit Officers; inherent sector exposure, not a borrower assessment. <- Report header: audience; boundary

### Slide 02 - Executive Sector Risk Snapshot

- **Headline:** Cyber/ICT and operational-resilience exposure is provisionally High, driven by IT-dependent production and supplier cascades; fraud and governance are not assessable. <- C-039, C-041, C-040, Ch1 principal judgements 1-3
- **evidence:** Key messages: (1) production stops when enterprise IT stops, not mainly through plant control systems; (2) one OEM stop cascades to thousands of suppliers; (3) losses arrive through lost output and cash, not response cost. <- C-039, C-041, C-040
- **significance:** Threat direction: rising in claim-based data (European manufacturing ransomware victims up 85.4% in January-July 2026 year on year); no prior edition exists for a trend comparison. <- C-008, Report header: baseline edition
- **credit_lens:** Most consequential credit implication: a multi-week stop at a large manufacturer drains cash (JLR free cash outflow of GBP 1.5 billion in one quarter, mixed causes) and transfers liquidity stress to suppliers. <- C-016, C-041
- **limitation:** Provisional: no approved rubric and no 24-sector calibration; ratings are migrated analytical judgements with confidence capped at Medium, not borrower assessments. <- Migration rule 6
- **Source strip:** Sources: S-001, S-004, S-006, S-009, S-041, S-045, S-049, S-081 (Tier 1); S-010, S-039, S-040 (Tier 2) - Period: Sep 2025 - Oct 2026; 2025 benchmarks - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register tiers and periods

Rating rows: see section 5.

### Slide 03 - Sector Anatomy: Key Operations & Dependencies

- **Headline:** Manufacturing output depends on the enterprise systems that release production and on just-in-time supplier tiers; one OEM or one shared tool can stop many firms at once. <- C-039, C-041, Ch6 dependency chains
- **evidence:** Footprint: about 2.2 million EU manufacturing enterprises in 2023, with machinery, food and motor vehicles the largest divisions by value added; JLR employs 34,000 people in the UK. <- C-001, C-018
- **significance:** Plant control systems can be intact while production stops: JLR, Asahi, Stryker and Boston Scientific halted or slowed plants after IT shutdowns or outages. <- C-039, C-012, C-027, C-029, C-031
- **credit_lens:** Ask whether a borrower can release production and ship without ERP, MES and identity services, and which single customer or supplier accounts for most of its revenue. <- C-066, Ch7 challenge questions 1-2
- **limitation:** Market shares of ERP, MES and OT vendors are not public, so no platform is described as dominant. Not covered in source edition: operating-model and governance complexity (Q13). <- Ch6 dependency note, Gap G-03
- **Source strip:** Sources: S-001, S-003, S-009, S-016, S-021, S-025, S-027, S-034, S-035, S-043, S-089 (Tier 1); S-010, S-039 (Tier 2); S-024 (Tier 3) - Period: Sep 2025 - Oct 2026; footprint 2023 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

| Figure | Label | Legacy |
|---|---|---|
| 30.2 million | EU manufacturing employment, 2023 (18.5% of business economy) | C-001 |
| 23.1% | Share of EU business-economy value added, 2023 | C-001 |
| About 120,000 | UK supply-chain jobs supported by JLR alone | C-018 |

Flow: Shared providers and admin tools -> Enterprise IT (ERP, MES, identity) -> Production release at plants -> OEM output and delivery -> Tier-1 to tier-3 suppliers

| Dependency | Evidence in source edition | Single point or bottleneck | Fallback in source edition | Legacy statements |
|---|---|---|---|---|
| Enterprise IT that releases production | JLR, Asahi, Boston Scientific | Plants stop when enterprise systems stop | Offline production release (scenario limiting condition) | C-012, C-027, C-031, C-063 |
| Endpoint and identity administration | Stryker (mechanism media-reported); CISA alert | One administrative tool reaches every device | Approval controls on mass wipe actions (action A2) | C-029, C-030, C-066 |
| OT vendors' installed base | French controller compromise; US PLC advisory | One product family exposed across many sites | Remove internet exposure; supported firmware | C-033, C-042, C-065 |
| Just-in-time supplier tiers | JLR and the CMC model | One customer stop reaches thousands of suppliers | Buffered inventory, multi-sourcing, customer prepayment | C-020, C-019, C-064 |
| Integrators and managed IT | Egide; 117 ICS-ecosystem incidents | One provider's access reaches several plants | Restricted, logged provider access (action A5) | C-035, C-007, C-066 |

### Slide 04 - Cyber Threat Landscape & Attack Scenarios

- **Headline:** Ransomware against enterprise IT and misuse of administrative tools carry the highest disclosed production impact; exposed OT products and providers spread it across customers. <- C-039, C-030, C-033, C-035, Ch2 threat pathways
- **evidence:** Last 12 months: five named incidents; industrial ransomware rose 12% from Q1 to Q2 2026, with manufacturing about 65%. Last 30 days before cut-off: Egide site interruption (6-9 October 2026) and refrigeration-controller compromises (12-13 October 2026). <- C-005, C-035, C-033
- **significance:** Dragos found no Q2 2026 ransomware case reaching control-system manipulation; disruption came from losing the enterprise and virtualisation layers that OT depends on. <- C-006
- **credit_lens:** Weight borrower discussions toward IT-OT production dependency, control of administrative tools and the exposure of products already sold, not ransomware claim counts. <- Legacy slide 2 management implication
- **limitation:** Ranking and impact levels are migrated judgements, not measured outcomes; claim counts measure visibility, not attack rates. Not covered in source edition: developments after the 16 October 2026 cut-off. <- RJ-03, C-044, Gap G-01
- **Source strip:** Sources: S-001, S-016, S-021, S-025, S-027, S-030, S-034, S-035, S-041, S-089 (Tier 1); S-039, S-040 (Tier 2); S-023 (Tier 3) - Period: Sep 2025 - Oct 2026; benchmarks 2023 - Q2 2026 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

| Rank | Pathway (pattern, not an attack) and mechanism | Observed evidence in source edition | Impact level (migrated judgement) | Legacy statements |
|---|---|---|---|---|
| 1 | P1 Ransomware and data extortion against enterprise IT (targeted disruption) | JLR and Asahi, Sep 2025; Boston Scientific, Aug 2026; 25.2% of EU ransomware claims in 2025 | High | C-012, C-027, C-031, C-003 |
| 2 | P2 Destructive misuse of administrative platforms (common dependency) | Stryker, Mar 2026 (mechanism media-reported); CISA endpoint-management alert | High | C-029, C-030 |
| 3 | P3 Internet-exposed OT and fielded products (supply-chain concentration) | Numerous refrigeration-controller compromises, Oct 2026; US PLC advisory, Apr 2026 | High | C-033, C-042 |
| 4 | P4 Supplier and service-provider compromise (supply-chain concentration) | Egide via an IT provider, Oct 2026; 117 ICS-ecosystem incidents in Q2 2026 | Medium | C-035, C-007 |
| 5 | P5 Data theft, intellectual-property and export-control exposure (other) | Asahi up to about 1.9 million records; West Pharmaceutical exfiltration, May 2026 | Medium | C-027, C-032 |

### Slide 05 - Geopolitical Cyber Threat Outlook

- **Headline:** State-linked activity is a rising threat to industrial controllers and enterprise estates, but no official source in the period attributed a manufacturing disruption to a state actor. <- C-042, Ch1 principal judgement 4
- **evidence:** Unconfirmed claims: a criminal group's claim for JLR was not confirmed by the company or the NCA; ENISA recorded more unconfirmed hacktivist intrusion claims against manufacturing OT in 2025. <- C-025, C-004
- **significance:** Defence, medical-device and OT-vendor manufacturers face added intent: US defence certification gates have applied since 10 November 2025 and controller fleets are reachable online. <- C-042, C-056, C-033
- **credit_lens:** Treat state-linked activity as a monitoring trigger rather than a rating driver; ask defence and OT-vendor borrowers about certification status and installed-base exposure. <- RJ-04, Ch7 monitoring trigger 2
- **limitation:** Not covered in source edition: dedicated geopolitical analysis (Q07), exposed-region mapping and espionage against manufacturers; evidence is US-centred and official attribution is absent. <- Gap G-04, C-042 limitations
- **Source strip:** Sources: S-025, S-035, S-041, S-073, S-074, S-080, S-084, S-089, S-091, S-096 (Tier 1); S-015, S-023, S-024, S-090 (Tier 3) - Period: 2025 - Oct 2026 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

| Driver | Source-edition evidence | Manufacturing exposure | Attribution status | Legacy statements |
|---|---|---|---|---|
| State-linked PLC targeting | US joint advisory on Iranian-affiliated actors exploiting internet-facing PLCs, Apr 2026 | Makers and industrial users of the same controllers | Government advisory; manufacturing not a named sector | C-042 |
| Destructive activity claimed by a state-linked persona | Stryker device wipe, Mar 2026 (media reports) | Multi-site manufacturers through administrative tools | Claim unconfirmed; no US government attribution | C-030 |
| Nation-state share of national incidents | NCSC: most nationally significant UK incidents originate directly or indirectly from nation states | UK economy-wide, no manufacturing split | Official statement, not sector attribution | C-042 |
| Economic security and ownership | Revised EU investment-screening regulation published 26 Jun 2026; UK NSI Act covers 17 areas | Dual-use, advanced-technology and defence manufacturers | Policy context, not attribution | C-058, C-043 |

### Slide 06 - Major Cyber Incidents & Lessons Learned

- **Headline:** Five named incidents meet the evidence standard; four stopped production through IT, and the JLR case shows the path from shutdown to supplier liquidity and state support. <- Ch2 Top 5, Ch5 case study, C-039
- **evidence:** Selection: in-period event or outcome, Tier 1 support, manufacturing subsector and a distinct lesson. Considered but not selected: West Pharmaceutical, Egide, Hasbro and RTX. <- Ch2 selection criteria, Ch2 considered but not selected
- **significance:** Disclosure is asymmetric: two of five cases come from US securities filings and one from a Japanese company; only JLR and the controller case are EU or UK. <- Ch2 shortfall statement, C-044
- **credit_lens:** Treat a multi-week stop at a large OEM as a foreseeable credit event for its supplier base; ask how a borrower would bridge a key customer's stop. <- Legacy slide 5 management implication, C-041
- **limitation:** Not covered in source edition: the second and third detailed case studies (only JLR is reconstructed) and developments after 16 October 2026; JLR's access route, OT state and full-year cyber cost were not disclosed. <- Gap G-05, Gap G-01, Ch5 what the case does not establish
- **Source strip:** Sources: S-001, S-003, S-004, S-006, S-009, S-016, S-019, S-021, S-022, S-026, S-027, S-030, S-031, S-034, S-035, S-037 (Tier 1); S-023, S-036 (Tier 3) - Period: Sep 2025 - Oct 2026 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

| Date | Organisation | Vector and documented weakness | Disruption and financial consequence | Lesson | Legacy statements |
|---|---|---|---|---|---|
| Sep 2025 | Jaguar Land Rover - automotive, UK and Slovakia | Enterprise systems shut down proactively; access route not disclosed | About five weeks of halted production; GBP 260 million cyber costs over two quarters | Supplier liquidity needs a bridge (case study) | C-012, C-013, C-015, C-019 |
| Sep 2025 | Asahi Group - beverages and food, Japan | Data-centre network entered via network equipment at a group site | Shipments halted; about JPY 40 billion 2025 impact; results delayed five months | Recovery tail outlasts the outage | C-027, C-028 |
| Mar 2026 | Stryker - medical devices, global | Global IT disruption; device wipe media-reported | Material Q1 effect; manufacturing and ordering restored in about four weeks | One administrative plane reaches every site | C-029, C-030 |
| Aug 2026 | Boston Scientific - medical devices, global | Unauthorised activity in IT systems; network outage | Manufacturing, ordering and shipping disrupted; guidance unlikely to be met | An IT outage reaches guidance | C-031 |
| Oct 2026 | Refrigeration controller makers - France | Internet-reachable, partly end-of-life controllers | Numerous compromises; hundreds of stores affected; cost not disclosed | Products already sold become exposure | C-033, C-034 |

### Slide 07 - Control Weaknesses & Resilience Priorities

- **Headline:** Seven resilience priorities follow the observed attacks; production release without IT, control of administrative tools and supplier liquidity address the highest-impact pathways. <- Ch7 action table, C-066
- **evidence:** Capabilities that contain disruption in the source edition: offline production release, segmentation (Stryker restored in about four weeks), buffered inventory, multi-sourcing and supported firmware. <- C-063, C-064, C-065, C-029
- **significance:** Labelled cyber costs were small beside lost output and cash, so continuity capabilities carry the cash-flow weight. <- RJ-05, C-040
- **credit_lens:** Use the priorities as discussion topics with borrowers; they are not a control audit or a compliance finding. <- Ch7 framing, L13
- **limitation:** Priorities are sector-informed; scenario links and confidence are migrated judgements; no control-effectiveness data exists for any firm. <- RJ-06, Ch7 framing
- **Source strip:** Sources: S-001, S-003, S-016, S-021, S-025, S-027, S-034, S-035, S-057, S-066 (Tier 1); S-010, S-039 (Tier 2); S-023 (Tier 3) - Period: Sep 2025 - Oct 2026 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

| Priority and weakness observed | Linked evidence | 1 Common dependency | 2 Targeted disruption | 3 Supply-chain concentration | Horizon | Confidence | Legacy statements |
|---|---|---|---|---|---|---|---|
| A1 Production depends on ERP, MES and identity | JLR, Asahi, Boston Scientific | Primary | Primary | - | 0-6 months | Medium | C-039, C-012, C-027, C-031 |
| A2 Administrative tools can wipe every device | Stryker (media-reported); CISA alert | Primary | Secondary | - | 0-3 months | Medium | C-030 |
| A3 Suppliers depend on one customer | JLR supplier scheme; CMC model | - | Primary | Secondary | 0-6 months | Medium | C-019, C-020, C-041 |
| A4 End-of-life controllers reachable online | CERT-FR alert | - | - | Primary | 3-12 months | Medium | C-033, C-034 |
| A5 Provider access into plants | Egide; ICS-ecosystem counts | Secondary | - | Primary | 3-12 months | Medium | C-035, C-007 |
| A6 New product reporting and liability duties | Product cybersecurity and liability rules | - | - | Secondary | 0-6 months | High | C-049, C-052 |
| A7 Customer-side disruption often uninsured | CMC insurance finding | - | Primary | Secondary | 6-12 months | Medium | C-021 |

### Slide 08 - Regulatory & Supervisory Resilience Expectations

- **Headline:** EU product law reaches in-scope connected-product makers and NIS2 covers named activities; UK NIS law does not reach manufacturing; US rules act through listing, defence and devices. <- C-043, C-068, Ch6 regulatory perimeter
- **evidence:** Status at cut-off: German NIS2 law in force since 6 December 2025, with 4,739 manufacturing registrations; four Member States referred to the Court of Justice on 8 July 2026; UK Bill without Royal Assent. <- C-048, C-010, C-047, C-054
- **significance:** Supply-chain duties of in-scope customers reach out-of-scope suppliers through contracts, and liability for software and missing security updates applies once national laws are in place. <- Ch6 NIS2 scope judgement, C-052
- **credit_lens:** Check that lending documentation reflects product-security reporting, liability exposure and customer-imposed cyber clauses; ask defence suppliers about certification status. <- Legacy slide 6 management implication, C-056
- **limitation:** Not covered in source edition: supervisory priorities and consequences of non-compliance beyond fine maxima; national NIS2 extensions not surveyed; US items comparative only. <- Gap G-06, Gap G-07, Ch8 limitations
- **Source strip:** Sources: S-045, S-046, S-049, S-051, S-055, S-056, S-057, S-063, S-065, S-066, S-075, S-076, S-077, S-079, S-081, S-083, S-084, S-087, S-094, S-095, S-096 (Tier 1); S-050, S-059, S-067, S-086, S-088 (Tier 3) - Period: Legal milestones 2018 - 2027; status at 16 Oct 2026 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

| Jurisdiction | Instrument | Legal status | Meaning for Manufacturing | Legacy statements |
|---|---|---|---|---|
| European Union | NIS2 Directive | Binding via national law | Named activities only: NACE C26-C30, medical devices, chemicals, food, pharmaceuticals | C-045, C-046 |
| European Union | Cyber Resilience Act | Directly applicable | Reporting since 11 September 2026; full application 11 December 2027 | C-049 |
| European Union | Machinery Regulation | Directly applicable | Applies 20 January 2027; protection against corruption | C-050 |
| European Union | Product Liability Directive | Transposition due | By 9 December 2026; software and missing security updates | C-052 |
| United Kingdom | NIS Regulations 2018 | Binding | Manufacturing not an essential-service sector | C-068 |
| United Kingdom | Cyber Security and Resilience Bill | Bill, not law | Lords report stage; would add MSPs and designated suppliers | C-054 |
| United Kingdom | Ransomware measures | Proposals | No bill identified at the cut-off | C-055 |
| United Kingdom | COMAH and MOD Cyber Security Model | Binding duties; contractual | Major-hazard sites; Def Stan 05-138 flow-down | C-060, C-061 |
| United States (comparative) | SEC Item 1.05 and Item 106 | Binding disclosure | Source of most quantified incident evidence | C-031, Ch6 regulatory table |
| United States (comparative) | CMMC via DFARS | Contract requirement | Effective 10 November 2025; next phase 10 November 2026 | C-056 |
| United States (comparative) | FDA section 524B | Binding statute | Device cyber plans and SBOM since 29 March 2023 | Ch6 regulatory table |
| United States (comparative) | CIRCIA rule; chemical facility standards | Not final; lapsed | Rule not published at cut-off (Tier 3); authority lapsed July 2023 | C-057 |

### Slide 09 - Financial Impact of Cyber Incidents

- **Headline:** Public financial evidence is thin and cannot be added up, but it shows lost output and cash, not response cost, drive the effect. <- C-040, Ch3 bottom line
- **evidence:** JLR booked GBP 196 million and GBP 64 million of cyber-related exceptional costs in two quarters, while free cash outflow reached GBP 791 million and GBP 1.5 billion with cyber and non-cyber causes. <- C-015, C-016
- **significance:** Recovery tails outlast outages: JLR production was normal by mid-November 2025, but wholesales fell 43.3% in the following quarter; Asahi delayed its FY2025 results by five months. <- C-013, C-014, C-028
- **credit_lens:** Watch facility drawdown and receivables concentration after a major customer incident; JLR's undrawn bridge fell from GBP 2.0 billion to GBP 1.0 billion by 31 March 2026. <- C-017, Ch3 transmission channels
- **limitation:** Values differ in currency, statistic type and population and are not summed. Not covered in source edition: five-year cost trend, sector business-interruption benchmarks and ransom data. <- Ch3 comparability, Gap G-08
- **Source strip:** Sources: S-004, S-005, S-006, S-007, S-011, S-017, S-019, S-021, S-027, S-047 (Tier 1); S-010, S-012 (Tier 2) - Period: Jul 2025 - Sep 2026 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

| Figure | Label | Legacy |
|---|---|---|
| GBP 1.9 billion | Modelled UK loss from the JLR event (range 1.6-2.1); modelled, not observed | C-020, M-011 |
| About JPY 40 billion | Asahi 2025 impact, incl. JPY 17 billion incident-related expenses | C-028, M-015, M-016 |
| -28.6% | UK motor-vehicle output, September 2025; ONS relays trade-body attribution | C-022, M-012 |
| Material | Stryker Q1 2026 effect; full-year guidance kept | C-029 |
| Guidance at risk | Boston Scientific: unlikely to meet Q3 and full-year 2026 guidance | C-031 |
| Not disclosed | Ransom, insurance recoveries and supplier insolvencies | C-067, C-011 |

Chart: JLR by quarter, GBP million (same company and quarters; not additive) - categories Q2 FY26 (Jul-Sep 2025), Q3 FY26 (Oct-Dec 2025); Cyber-related exceptional costs: 196, 64; Free cash outflow (cyber and non-cyber causes): 791, 1500 <- M-001, M-002, M-006, M-007

### Slide 10 - Cyber-to-Credit Risk Transmission & Stress Scenarios

- **Headline:** Illustrative - not a forecast or loss estimate: longer stops move the effect from delayed cash to working-capital drain and then to supplier liquidity and debt service. <- Ch3 transmission channels, Ch4 scenarios
- **evidence:** Transmission evidence: JLR's GBP 2 billion bridge facility, GBP 1.5 billion UKEF-guaranteed loan and supplier prepayment through a banking partner; the CMC modelled about GBP 108 million a week of JLR fixed cost and lost profit. <- C-017, C-018, C-019, C-021
- **significance:** Duration and supplier dependence, not data loss, drive the cash-flow effect; buffered inventory, multi-sourcing and offline production release shorten it. <- RJ-07, C-063, C-064
- **credit_lens:** Borrower data needed: weeks of liquidity at zero output, revenue share of the largest customer, supply-chain finance use and insurance cover for customer-side disruption. <- Legacy slide 4 management implication, C-021
- **limitation:** Illustrative: no probabilities and no loss estimates; the 1-week band and the supply-chain mechanism have no duration evidence in the source edition. <- Migration rule 8, Ch4 assumptions
- **Source strip:** Sources: S-001, S-003, S-004, S-005, S-006, S-009, S-021, S-025, S-035, S-037 (Tier 1); S-010, S-039 (Tier 2); S-024 (Tier 3) - Period: Sep 2025 - Oct 2026 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

Flow: Cyber disruption -> Production and shipping stop -> Revenue deferred or lost -> Working capital and cash drawn -> Liquidity facilities and state support -> Supplier receivables and debt service

| Band | Mechanism | Duration evidence in source edition | Operational effect | Credit channel | Legacy statements |
|---|---|---|---|---|---|
| 1 week | Common digital dependency (shared enterprise platform) | Duration not evidenced: legacy assumption of three to ten days; no multi-firm outage observed | Many plants stop on precaution while OT is untouched | Correlated delivery gaps; concurrent working-capital draws | C-063, SC-001 |
| 4 weeks | Targeted disruption at a segmented manufacturer | Stryker restored manufacturing and ordering in about four weeks (Tier 1) | Production and shipping lost for weeks | Deferred revenue; material quarterly effect | C-029, SC-002 |
| 8 weeks | Targeted disruption at a just-in-time OEM | JLR: about five weeks halted, normal production by mid-November, distribution later (Tier 1) | Supplier tiers idle; dealers lose volume | OEM cash outflow, emergency facilities, supplier prepayment, state guarantee | C-013, C-016, C-017, C-018, C-019, SC-002 |

Band note: Supply-chain concentration (scenario 3): mechanism kept, band duration not evidenced; the controller case was days old at the cut-off. <- SC-003, C-065, C-034

### Slide 11 - Questionnaire-to-Sector Intelligence Mapping

- **Headline:** Provisional map: seven generic discussion items link sector threats and incident evidence to credit consequences; no questionnaire was supplied, so no real item IDs are used. <- Ch7 actions A1-A7, Ch2 pathways P1-P5
- **evidence:** Derived from the source edition's seven actions (A1-A7) and five threat pathways (P1-P5); PROV IDs are placeholders, not questionnaire items. <- Ch7 action table, Ch2 pathways
- **significance:** Factors that change materiality: just-in-time versus buffered production, customer concentration, segmentation, installed-base size, defence or device regulation and liquidity headroom. <- C-041, C-064, C-065, C-056
- **credit_lens:** Borrower answers are self-reported, not confirmed evidence, and trigger no automatic adverse credit judgement. <- Publication standard 7
- **limitation:** Provisional: no questionnaire item list was supplied; the map must be rebuilt against actual item IDs. <- Migration rule 7, Gap G-11
- **Source strip:** Sources: S-001, S-003, S-016, S-021, S-034, S-035, S-057, S-066 (Tier 1); S-010 (Tier 2); S-024 (Tier 3) - Period: Sep 2025 - Oct 2026 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

| ID and topic | Threat -> incident evidence | Operational -> credit consequence | Suggested question | Legacy statements |
|---|---|---|---|---|
| PROV-01 Production without IT | P1 -> JLR, Asahi | Plants stop -> revenue and cash loss | Can you release production and ship without ERP, MES and identity services for two weeks? | C-012, C-027, C-066 |
| PROV-02 Administrative tool controls | P2 -> Stryker (media-reported) | All devices lost -> global stop | Do destructive administrative actions need a second approver? | C-030 |
| PROV-03 Customer concentration | Cascade -> JLR, CMC model | Customer stop -> receivables and liquidity stress | What share of revenue comes from your largest customer, and how many weeks of stop could you finance? | C-019, C-020, C-041 |
| PROV-04 Installed-base exposure | P3 -> refrigeration controllers | Fleet compromise -> remediation and liability | Do you track internet exposure and end-of-support status of products you have sold? | C-033, C-034 |
| PROV-05 Provider remote access | P4 -> Egide | Provider compromise -> partial site stop | Is provider remote access to OT restricted and logged? | C-035 |
| PROV-06 Product-law readiness | Reporting and liability rules | Non-compliance -> liability and market access | How do you meet product vulnerability reporting that began in September 2026? | C-049, C-052 |
| PROV-07 Insurance and contracts | Customer-side gap -> CMC finding | Uninsured loss -> margin and covenant pressure | Does your cyber cover include disruption at a key customer? | C-021 |

### Slide 12 - Credit Officer Engagement: Key Questions & Actions

- **Headline:** Five client discussion topics, each with an early-warning indicator, let credit officers test continuity of production, supplier liquidity and debt service without assessing borrower controls. <- Ch7 challenge questions, Ch7 monitoring triggers
- **evidence:** Topics reframe the source edition's six challenge questions and five monitoring triggers for client discussion. <- Ch7 challenge questions, Ch7 monitoring triggers
- **significance:** Practical improvements a client can make: documented manual release, second-approver controls, revenue diversification, exposure monitoring, restricted provider access and aligned cover. <- Ch7 action table
- **credit_lens:** Proportionate next steps: raise topics at review, record answers as self-reported and escalate to the Risk Committee when a trigger fires. <- Legacy slide 7 management implication
- **limitation:** Topics are sector-informed priorities, not findings on any borrower's controls or creditworthiness. <- Legacy slide 7 limitation, L13
- **Source strip:** Sources: S-001, S-003, S-025, S-034, S-035, S-057, S-066 (Tier 1); S-010 (Tier 2); S-024 (Tier 3) - Period: Sep 2025 - Oct 2026 - Cut-off 16 Oct 2026 - v1.0-M Migrated <- Legacy source register

| Discussion topic | Question for the client | Early-warning indicator | Legacy statements |
|---|---|---|---|
| Production without IT | How long can you release production and ship without ERP, MES and identity services? | Production-pause notice or exchange filing | C-066, Ch7 question 1, Ch7 trigger 1 |
| Customer and supplier concentration | Which customer stop would stop you, and how would you bridge four weeks? | OEM incident notice; supplier short-time work | C-041, Ch7 question 2, Ch7 trigger 3 |
| Administrative tools and provider access | Who can wipe or reach every device and plant, and who approves it? | Government alert on administrative-tool misuse; disclosure citing an IT provider | C-030, C-035, Ch7 question 3, Ch7 trigger 2 |
| Products already sold | How many of your connected units are online or out of support? | National CERT alert naming a product family | C-033, Ch7 question 4, Ch7 trigger 2 |
| Cover, contracts and product law | Is disruption at a key customer insured, and are reporting and liability duties met? | Insurer product change; first enforcement action | C-021, C-049, Ch7 questions 5-6, Ch7 trigger 5 |

Referral line: Specialist referral: involve cyber specialists when an indicator fires or answers show no tested fallback; record and monitor rather than change a rating. <- RJ-09, Legacy slide 7 implication

## 4. Gap register

| ID | Gap | Slide(s) | Why not covered | What a full v4 run would research |
|---|---|---|---|---|
| G-01 | 30-day developments after the original cut-off | 04, 06 | Migration rule 1: no research after 16 October 2026 | Q01-Q03 30-day window: Boston Scientific Q3 results (due 28 October 2026), French controller campaign counts and attribution, Egide outcome |
| G-02 | Fraud beyond cyber-enabled payment fraud (Q10) | 02, 11 | The source edition researched cyber incidents only | Q10 sector fraud typologies: procurement and supplier-invoice fraud, payment diversion in supply chains, counterfeit parts, warranty fraud, with loss data |
| G-03 | Governance and operating-model complexity (Q13) | 02, 03 | Not a research question in the source edition; fragments only (NIS2 management-body duties, MOD flow-down) | Q13 ownership models (listed, private-equity, family, state), multi-site IT governance, outsourcing and shared-service models |
| G-04 | Dedicated geopolitical analysis (Q07) | 05 | Source edition holds fragments only (US PLC advisory, unconfirmed Stryker claim, NCSC statement, investment screening) | Q07 state-linked campaigns against manufacturers, espionage and intellectual-property theft, exposed regions, sanctions and export-control links, attribution with confidence |
| G-05 | Second and third detailed case studies | 06 | Source edition reconstructs one case (Jaguar Land Rover) | Q04 two further reconstructions, for example Asahi (process manufacturing) and a medical-device case with disclosed results |
| G-06 | US regulation beyond comparative items | 08 | Source edition scope was EU and UK primary with US comparative only | Q11 state breach laws, securities litigation, ITAR and EAR export controls, CIRCIA final text, supervisory practice for SEC disclosures |
| G-07 | Supervisory priorities and consequences of non-compliance | 08 | Not researched in the source edition beyond NIS2 fine maxima | Q11 enforcement records and supervisory work programmes (EU, UK, US) |
| G-08 | Five-year cost trend, business-interruption benchmarks and ransom data | 09 | Source edition has single-company disclosures and one modelled estimate only | Q06 multi-year loss series, insurer and survey benchmarks with method notes |
| G-09 | Cross-sector comparison (Q14) and 24-sector rating calibration | 02 | No cross-sector benchmark in the source edition | Q14 benchmark register against other sectors; calibration of ratings across the 24-sector universe |
| G-10 | Approved rating rubric | 02 | None supplied | Formal ratings against an approved rubric with recorded hash |
| G-11 | Questionnaire item list | 11 | None supplied | Live Q08 mapping with actual item IDs |
| G-12 | Duration evidence for the 1-week band and for the supply-chain concentration mechanism | 10 | The 1-week band rests on a legacy scenario assumption (three to ten days); the controller case was days old at the cut-off | Q05 primary restoration timelines for short platform outages and for supplier-layer compromises |
| G-13 | Full v4 report (11 headings) and evidence annex A1-A7 | all | Outside the migration brief's outputs | Q09 report and annex A1-A7 built from the v4 registers |
| G-14 | Classification marking | 01 | Not specified in the source edition | Classification supplied by the publishing owner |
| G-15 | Regimes named but not assessed in the source edition | 08 | Trade Secrets Directive, Dual-Use Regulation, Chips Act, raw-materials regulation, Economic Security Strategy, MDR guidance, UK Data (Use and Access) Act, UK Market Abuse Regulation, Japan METI guidelines, Australia SOCI, US Cyber Trust Mark | Q11 legal status and applicability for each regime |

Duration bands (rule 8): 1 week - duration not evidenced (legacy assumption only, gap G-12); 4 weeks - Stryker restoration in about four weeks (Tier 1, C-029); 8 weeks - JLR about five weeks halted and normal production by mid-November 2025, with distribution later (Tier 1, C-013). The supply-chain concentration mechanism is kept with its band marked "duration not evidenced".

## 5. Rating table (Slide 02)

No approved rubric was supplied, so every rating is Provisional; confidence is capped at Medium for migrated ratings. Ratings are migrated analytical judgements, not borrower assessments, and are not calibrated against the 24-sector universe. The source edition assigned no ratings.

| Dimension | Rating | Status | Confidence | Justification (legacy evidence) | Legacy statements |
|---|---|---|---|---|---|
| Fraud | Not assessable | Not covered in source edition | - | No fraud research (Q10); the source edition covers cyber incidents and their outcomes only. | Ch8 methodology scope, Gap G-02 |
| Cyber / ICT | High | Provisional | Medium | Manufacturing held 25.2% of EU ransomware claims in 2025 and about 65% of industrial ransomware in Q2 2026; four of five named incidents stopped production through IT. | C-003, C-005, C-039 |
| Operational Resilience / TPRM | High | Provisional | Medium | One OEM stop was modelled to affect over 5,000 UK organisations; supplier prepayment and a GBP 1.5 billion state-guaranteed loan followed. | C-020, C-018, C-019, C-041 |
| Governance / Operating Model | Not assessable | Not covered in source edition | - | Fragments only (NIS2 management-body accountability; MOD supplier flow-down); no governance research (Q13). | C-046, C-061 |

## 6. Reframed judgements (labelled analytical judgement)

| ID | Slide | Reframed statement | Legacy basis |
|---|---|---|---|
| RJ-01 | 02 | Provisional High ratings for Cyber / ICT and Operational Resilience / TPRM | Synthesised from legacy principal judgements 1-3 (C-039, C-040, C-041), ENISA and Dragos benchmarks (C-003, C-005) and the JLR cascade, support and model evidence (C-018, C-019, C-020) |
| RJ-02 | 02 | Threat direction "rising in claim-based data" with no trend comparison | Black Kite year-on-year comparison (C-008); source edition is a baseline with no prior edition |
| RJ-03 | 04 | Ranking and impact levels of pathways P1-P5 | Derived from the legacy Top 5 sector-relevance column (Highest/High) and principal judgements 1 and 4; not measured outcomes |
| RJ-04 | 05 | Treat state-linked activity as a monitoring trigger rather than a rating driver | Reframes legacy monitoring trigger 2 (government alerts) and the absence of official attribution (C-042, C-030) |
| RJ-05 | 07 | Continuity capabilities carry the cash-flow weight | Reframes legacy principal judgement 3 (C-040) |
| RJ-06 | 07, 10 | Primary and secondary links between priorities A1-A7 and the three scenarios; mapping of mechanisms to 1-week, 4-week and 8-week bands | Each band's duration evidence is a legacy figure; the scenario links and band assignment are migration judgements |
| RJ-07 | 10 | Duration and supplier dependence, not data loss, drive the cash-flow effect | Reframes legacy Ch3 transmission channels and principal judgements 2-3 |
| RJ-08 | 11 | PROV-01 to PROV-07 items and their threat-to-credit chains | Derived from legacy actions A1-A7 (Ch7) and pathways P1-P5 (Ch2) |
| RJ-09 | 12 | Involve cyber specialists when an indicator fires; record and monitor rather than change a rating | Reframes the legacy slide 7 implication (escalate to the Risk Committee when a trigger fires) for a lender audience |
| RJ-10 | 02-12 | All Credit Lens statements | Each reframes a legacy management implication, challenge question or action for client discussion; none adds a bank- or borrower-specific claim |

## 7. Pre-delivery checks

| Check | Result |
|---|---|
| 12 slides, fixed labels, correct order | PASS |
| Headline, Evidence, Significance, Credit Lens, Limitation and source strip on Slides 02-12 | PASS |
| Every element and table cell placed verbatim on the exported slide (python-pptx extraction against the spec) | PASS |
| Every S- ID on a slide exists in the mapping table; no URLs on slides | PASS |
| Every number on slides appears in the legacy files (automated comparison against report, registers, evidence pack and legacy slide spec) | PASS |
| Provisional (02, 11), Not assessable (02), Illustrative (10), Migrated (all slides) labels | PASS |
| No footer, date or slide-number placeholders on slides; notes carry no substantive text (notes pages hold only the automatic slide-number field) | PASS |
| Office package validation (pptx skill validate.py) | PASS |
| Language rules (core check_language_rules.py) on migration_record.md, MIGRATION_NOTE.md, slide text and spec | PASS |
| Visual inspection of all 12 exported slides at normal reading size | PASS - see section 8 |
| Density bands (diagnostic) | Flagged: slide 1: 87 words (band 20-80); slide 2: 314 (120-260); slides 3, 4, 6, 8, 10: 360, 330, 359, 370, 353 (150-320); slide 11: 324 is inside its 150-340 band. Excess comes mainly from the mandatory source strips (26 source IDs on Slide 08) and table labels; no evidence was cut to meet a band. |

Visible words per slide: 1: 87, 2: 314, 3: 360, 4: 330, 5: 290, 6: 359, 7: 283, 8: 370, 9: 270, 10: 353, 11: 324, 12: 297.

## 8. Visual review

Visual design (27 October 2026, on request): a new set of visual forms, distinct from the earlier migrated editions, within the same palette (white background, dark text 1A1A1A, emerald 00915E with flat emerald tints C8E6D8 and E8F5EF, grey hairlines D9D9D9). No gradients, shadows, rounded corners, icons or imagery. Every analytical slide keeps the same frame: numbered fixed label, section and "Migrated 1.0-M" marker, one-sentence headline, Evidence and Significance under emerald rules, Credit Lens on a flat emerald tint, limitation and source strip below a grey hairline. "Provisional" and "Illustrative" appear as tinted tags beside the label on Slides 02, 10 and 11.

| Slide | Visual form |
|---|---|
| 01 | Full-width emerald band with sector name and migrated cut-off; metadata in a two-by-two grid under emerald rules; typographic, no image |
| 02 | Rating scale rows: Medium / High / Very High segments with the rated level filled emerald and the word printed; Not assessable as a grey bar; status, confidence and justification per row |
| 03 | Footprint figures column; five-step dependency chain with arrows (enterprise IT step filled); dependency table with single points and fallbacks |
| 04 | Ranked heat matrix: rank numerals, pathway, evidence and impact cell tinted by level (word printed); zones in a right column |
| 05 | Four driver lanes: driver (emerald) -> evidence -> manufacturing exposure -> attribution status (tint), with arrows |
| 06 | Vertical timeline September 2025 - October 2026 with markers; the case-study entry filled; three text columns per incident |
| 07 | Control-to-scenario matrix: Primary cells emerald, Secondary cells light tint, horizon and confidence columns |
| 08 | Three jurisdiction columns with header bars (US comparative in dark grey); legal-status tags tinted, Bill, proposal and not-final items on grey |
| 09 | Native clustered column chart of JLR quarterly cyber costs and free cash outflow (labelled not additive) beside six stat tiles; Not disclosed tile greyed |
| 10 | Six-step transmission chain; band table with week bars on a 0-8 week scale (solid = evidenced, dashed outline = not evidenced) |
| 11 | Mapping table with emerald PROV- IDs and alternating row tint |
| 12 | Large emerald numerals for five topics; emerald rule beside each early-warning indicator; grey referral bar |

Inspection: all 12 slides rendered with LibreOffice (pptx skill soffice wrapper) and inspected at 70-80 dpi. Issues found and fixed: three-line headlines on Slides 02, 04, 06 and 08 overlapping content (headlines shortened without changing meaning, size 18.5 pt); Slide 04 and 07 tables overlapping their notes; Slide 08 instrument names wrapping into descriptions; Slide 09 tile value wrapping; Slide 10 band table and right-column text overflow (moved to full-width table with zones below). Final render: no clipped or overlapping text. Type sizes: headlines 18.5 pt, zone text 11-11.5 pt, tables 9.5-11.5 pt, source strips 8.5 pt; these sit below the standard's pixel bands because of the mandatory zones and source strips, a density trade-off recorded for editorial review.

## 9. Release status

NEEDS_REVIEW. This migrated deck will not pass the full v4 release gate: Q07, Q10, Q13 and Q14, the 30-day window and the three case studies were not researched, ratings are Provisional without an approved rubric, the questionnaire map is Provisional, and no v4 report or annex A1-A7 exists. See MIGRATION_NOTE.md.
