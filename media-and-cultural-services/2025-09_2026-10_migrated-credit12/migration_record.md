# Migration Record - Media & Cultural Services, Sector Cyber Resilience & Credit Intelligence (Version 1.0-M)

**Status:** NEEDS_REVIEW - migrated edition, not a v4 edition (see MIGRATION_NOTE.md). **Edition state:** DRAFT (migration). **Migration date:** 27 October 2026.
**Evidence cut-off:** 15 October 2026 (unchanged from the source edition). **Reporting period:** 1 September 2025 to 15 October 2026. **Research performed in this migration:** none - no web search or source retrieval.

## 1. Source edition and resolved placeholders

| Brief placeholder | Resolved value (kept from the source edition) |
|---|---|
| OLD_DECK_FILE | `13_cyber_sectorial_analysis.pptx` (seven-slide readout) |
| OLD_REPORT_FILE | `15_sectorial_report.docx` / `14_sectorial_report.md` |
| Evidence files | `09_evidence_pack.md`, `02_source_register.csv`, `03_claim_ledger.json`, `06_scenario_assumption_register.csv` and the other registers of the run |
| ORIGINAL_PERIOD | 1 September 2025 to 15 October 2026 |
| ORIGINAL_CUTOFF | 15 October 2026 |
| ORIGINAL_VERSION | 1.0 (baseline edition; the source manifest carries no edition number) - migrated version 1.0-M |
| CLASSIFICATION | Not specified in the source edition; the cover states this and the external-data-only boundary |
| Rating rubric | none supplied - all ratings Provisional |
| Questionnaire item list | none supplied - Provisional PROV- map |
| Output file name | `Media & Cultural Services_credit_intelligence_briefing_migrated.pptx`. The brief's output line names Building & Public Works, which reads as template residue; the file is named for the sector migrated. |

Source edition location: private repository `cybertiagovieira/cyber-risk-reports`, folder `media-and-cultural-services/2025-09_2026-10/` (artefact commit 4ddd469, receipt commit bae406b). The source edition is not modified by this migration and is not marked SUPERSEDED, because a migrated edition is not a v4 re-issue.

Input hashes (SHA-256) of the source files used:

- `02_source_register.csv`: `02cc4078bfaa42938ba55d2818fae01af9cbe04c696f7fc2b0c69ff5ea5ca9b1`
- `03_claim_ledger.json`: `f6383631621b209029bd6e07fce52f22bdc0263309d56265eadf184dc8c3fec4`
- `06_scenario_assumption_register.csv`: `b3c4e3c681d6847e22c448e2b50b0ef5bd2674644eac814a03132e101e4f587d`
- `09_evidence_pack.md`: `e7e63dce632286047533547308eb49e47772738fea97fa2642e23c2fe374eb64`
- `13_cyber_sectorial_analysis.pptx`: `a57a9871a4a885b981163a726898c841d23804d01d1304984b485288716ec100`
- `14_sectorial_report.md`: `6c38170e7d410f8e7517dac19d45f15e29535f8a1ee93217a8b0ee48837eca45`
- `15_sectorial_report.docx`: `e79992903c2c11fb949ccc2b6bec0ce6dad6fd897e3630a3144736d414470e67`

## 2. Legacy reference -> S- ID mapping

The legacy report numbers its references [1] to [87] by source-register order; each legacy reference [n] maps to S- ID S-nnn in the same order (identity mapping). Tier and period are taken from the legacy source register.

| Legacy reference | S- ID | Short title | Tier | Observation period |
|---|---|---|---|---|
| [1] | S-001 | Saxon culture ministry - SKD cyberattack release, 22 January 2026 | 1 | 21-22 January 2026 |
| [2] | S-002 | SKD - Cyberattack press release | 1 | 21-22 January 2026 |
| [3] | S-003 | SKD - Recovery update, 29 January 2026 | 1 | 21-29 January 2026 |
| [4] | S-004 | Prosecutor and LKA Saxony - SKD investigation release | 1 | 21 January - 19 February 2026 |
| [5] | S-005 | t-online - SKD special commission report | 3 | January-February 2026 |
| [6] | S-006 | dpa via Volksstimme - SKD attack duration | 3 | 17-21 January 2026; investigation status July 2026 |
| [7] | S-007 | Musee Guimet - Online ticketing unavailable notice | 1 | March 2026 (inferred from related reporting; page undated) |
| [8] | S-008 | CMN - Ticketing personal data notice | 1 | Current page |
| [9] | S-009 | ActuaLitte - Vivaticket attack on cultural institutions | 3 | 2-19 March 2026 |
| [10] | S-010 | L'Echo touristique - CMN ticketing cyberattack | 3 | 2-8 March 2026 |
| [11] | S-011 | Lyon Mag - Lyon municipal museums ticketing attack | 3 | March 2026 |
| [12] | S-012 | SC Media - Vivaticket platform breach brief | 3 | Early March - April 2026 |
| [13] | S-013 | Radio Ink - FCC warning after Houston hijack | 3 | 22-23 November 2025 |
| [14] | S-014 | FCC - FCC 26-38 alerting systems order | 1 | Adopted 25 June 2026; released 29 June 2026 |
| [15] | S-015 | SDNY - Anna's Archive preliminary injunction | 1 | December 2025 - January 2026 |
| [16] | S-016 | Music Business Worldwide - Anna's Archive lawsuit | 3 | December 2025 - January 2026 |
| [17] | S-017 | MusicTech - Anna's Archive judgment | 3 | Judgment 14 April 2026 |
| [18] | S-018 | Geo News - Satellite feed hijack statement | 1 | 28 February - 1 March 2026 |
| [19] | S-019 | Dawn - CERT investigation of TV channel hacks | 3 | 1-3 March 2026 |
| [20] | S-020 | Digital Rights Monitor - Pakistani channel takeovers | 3 | 1 March 2026 |
| [21] | S-021 | TechCrunch - Anodot integration breach | 3 | 4-13 April 2026 |
| [22] | S-022 | Hasbro - Form 8-K, 1 April 2026 | 1 | 28 March - 1 April 2026 |
| [23] | S-023 | Hasbro - Q1 2026 results release | 1 | Q1 2026 |
| [24] | S-024 | BleepingComputer - SoundCloud breach | 3 | December 2025 |
| [25] | S-025 | NOS - RTV Noord hack | 3 | 6-14 November 2025 |
| [26] | S-026 | NL Times - RTV Noord broadcast disruption | 3 | 6-7 November 2025 |
| [27] | S-027 | Artribune - Uffizi incident claims and response | 3 | January-April 2026 |
| [28] | S-028 | t-online - Leipzig cultural enterprises attack | 3 | July 2026 |
| [29] | S-029 | Quotenmeter - Cyberattacks on journalism | 3 | August-September 2026 |
| [30] | S-030 | Lee Enterprises - FY2025 Form 10-K | 1 | Fiscal year to 28 September 2025; incident 3 February 2025 |
| [31] | S-031 | Lee Enterprises - Q3 FY2026 Form 10-Q | 1 | Nine months to 28 June 2026 |
| [32] | S-032 | KADOKAWA - FY2025/3 results release | 1 | Fiscal year to 31 March 2025; attack June 2024 |
| [33] | S-033 | British Library - Annual Report 2024/25 | 1 | 1 April 2024 - 31 March 2025 |
| [34] | S-034 | British Library - Annual Report 2025/26 | 1 | 1 April 2025 - 31 March 2026 |
| [35] | S-035 | Museums Association - British Library recovery | 3 | September 2026 |
| [36] | S-036 | Toronto Auditor General - Toronto Public Library audit | 1 | Audit following the October 2023 attack |
| [37] | S-037 | Cour des comptes - Louvre public establishment summary | 1 | Financial years 2018-2024 |
| [38] | S-038 | AWS - US-EAST-1 post-event summary | 1 | 19-20 October 2025 |
| [39] | S-039 | Cloudflare - 18 November 2025 outage report | 1 | 18 November 2025 |
| [40] | S-040 | PPC Land - AWS outage effects | 3 | 20 October 2025 |
| [41] | S-041 | ENISA - Threat Landscape 2026 | 1 | 1 January - 31 December 2025 |
| [42] | S-042 | Cloudflare - DDoS Threat Report H1 2026 | 2 | 1 January - 30 June 2026 |
| [43] | S-043 | EEAS - 4th FIMI Threats Report | 1 | 1 January - 31 December 2025 |
| [44] | S-044 | DSIT - Cyber Security Breaches Survey 2025/26 | 1 | Fieldwork August-December 2025 |
| [45] | S-045 | Eurostat - EU cultural employment 2025 | 1 | 2025 |
| [46] | S-046 | DCMS - Sectors GVA 2024 (provisional) | 1 | Calendar year 2024 |
| [47] | S-047 | Europol - Operation Eastwood | 1 | 14-17 July 2025 |
| [48] | S-048 | EUR-Lex - NIS2 Directive | 1 | In force 16 January 2023 |
| [49] | S-049 | European Commission - NIS2 FAQs | 1 | Current page |
| [50] | S-050 | European Commission - Entity resilience policy page | 1 | Current page |
| [51] | S-051 | European Commission - European Media Freedom Act page | 1 | Current page |
| [52] | S-052 | European Commission - Political advertising rules apply | 1 | From 10 October 2025 |
| [53] | S-053 | European Commission - AI Act Article 50 FAQ | 1 | Current page |
| [54] | S-054 | EUR-Lex - Digital Omnibus on AI | 1 | Entry into force 27 July 2026 |
| [55] | S-055 | European Commission - Cyber Resilience Act page | 1 | Current page |
| [56] | S-056 | European Commission - Radio Equipment Directive page | 1 | Current page |
| [57] | S-057 | European Commission - Digital Services Act page | 1 | Current page |
| [58] | S-058 | European Commission - Live-event piracy Recommendation stock-take | 1 | 2023-2025 |
| [59] | S-059 | European Commission - European Democracy Shield | 1 | From 12 November 2025 |
| [60] | S-060 | EUR-Lex - GDPR | 1 | Applies from 25 May 2018 |
| [61] | S-061 | UK Parliament - Cyber Security and Resilience Bill | 1 | Bill stages to 14 October 2026 |
| [62] | S-062 | DSIT - Cyber Security and Resilience Bill summary | 1 | First published 12 November 2025; updated 30 June 2026 |
| [63] | S-063 | legislation.gov.uk - NIS Regulations 2018 | 1 | In force 10 May 2018 |
| [64] | S-064 | OPSS - Consumer connectable product security | 1 | In force 29 April 2024 |
| [65] | S-065 | legislation.gov.uk - DPA 2018 special purposes | 1 | Current version with amendments to 30 September 2026 |
| [66] | S-066 | Home Office - Ransomware proposals consultation | 1 | Consultation 13 January - 8 April 2025; response 22 July 2025 |
| [67] | S-067 | Goodwin - UK ransomware strategy alert | 3 | July 2025 - February 2026 |
| [68] | S-068 | DSIT - Government Cyber Action Plan | 1 | 2026-2029 phases |
| [69] | S-069 | SEC - Cyber disclosure compliance guide | 1 | Compliance from 18 December 2023 |
| [70] | S-070 | FTC - COPPA final rule amendments | 1 | Federal Register publication 22 April 2025 |
| [71] | S-071 | EBU - R 148 networked media equipment tests | 1 | Published 27 April 2018; not updated since |
| [72] | S-072 | Hunton - CIRCIA timing | 3 | April 2024 - July 2026 |
| [73] | S-073 | EUR-Lex - Digital Services Act | 1 | Adopted 19 October 2022 |
| [74] | S-074 | Music Business Worldwide - Live Nation class actions | 3 | October 2026 |
| [75] | S-075 | legislation.gov.uk - National Security Act 2023 s13 | 1 | 20 December 2023 - 15 October 2026 |
| [76] | S-076 | legislation.gov.uk - Media Act 2024 | 1 | 24 May 2024 - 15 October 2026 |
| [77] | S-077 | GOV.UK - Online Safety Act explainer | 1 | January 2025 - Summer 2025 |
| [78] | S-078 | DSIT - Telecommunications Security Code of Practice 2026 | 1 | 1 October 2022 - 15 October 2026 |
| [79] | S-079 | Ofcom - Arqiva electronic communications network statement | 1 | January - July 2018 |
| [80] | S-080 | Home Affairs - Infrastructure asset definition paper | 1 | April 2021 |
| [81] | S-081 | Federal Register of Legislation - SOCI Act 2018 compilation | 1 | Compilation in force June 2026 |
| [82] | S-082 | Digital Policy Alert - AVMSD transposition deadline | 3 | 14 November 2018 - 19 September 2020 |
| [83] | S-083 | GDPR-Text - Article 85 | 3 | Regulation (EU) 2016/679 as published |
| [84] | S-084 | Advisera - Italian NIS2 decree overview | 3 | D.Lgs. 138/2024 |
| [85] | S-085 | iubenda - AI Omnibus and Article 50 | 3 | June - December 2026 |
| [86] | S-086 | Vermont Attorney General - Security breach notices | 1 | Notice reported 1 October 2026 |
| [87] | S-087 | Court complaint - Gosman v. Live Nation | 1 | Filed 7 October 2026 |

S- IDs cited on slides: 58 of 87 (S-001, S-002, S-003, S-004, S-005, S-006, S-007, S-008, S-009, S-010, S-013, S-014, S-015, S-017, S-018, S-019, S-023, S-030, S-031, S-032, S-033, S-034, S-037, S-038, S-039, S-041, S-042, S-043, S-044, S-045, S-046, S-047, S-048, S-049, S-050, S-051, S-052, S-053, S-055, S-059, S-060, S-061, S-063, S-064, S-065, S-066, S-068, S-069, S-070, S-071, S-072, S-074, S-075, S-076, S-081, S-083, S-086, S-087). All exist in this table.

## 3. Slide-by-slide map (legacy statement -> slide element)

Legacy statement references use claim IDs (C-nnn) from the legacy claim ledger and report locations (Ch1 to Ch8 of the seven-chapter report; 'legacy slide n' for the seven-slide deck). Every element is placed verbatim on the slide.

### Slide 01 - Sector Intelligence Cover

- **kicker:** Sector Cyber Resilience & Credit Intelligence <- Product name per credit_12 profile
- **sector:** Media & Cultural Services <- Report header: sector
- **period:** Reporting period: 1 September 2025 - 15 October 2026 <- Report header: reporting period
- **geography:** Geography: global, primary focus EU, EEA and UK; North American and other evidence comparative <- Report header: geography
- **cutoff:** Migrated edition - evidence as of 15 October 2026; no research update <- Report header: evidence cut-off
- **classification:** Classification: not specified in source edition (external public data only) <- Report header: boundary; no classification in source edition
- **version:** Version 1.0-M (migrated from the 15 October 2026 baseline) - Status: NEEDS_REVIEW, not a v4 edition <- Report header: edition (baseline)
- **audience:** Audience: Senior Credit Officers; inherent sector exposure, not a borrower assessment. <- Report header: audience; boundary

### Slide 02 - Executive Sector Risk Snapshot

- **Headline:** Cyber/ICT and operational-resilience exposure is provisionally High, driven by shared platforms and live-output integrity; fraud and governance are not assessable from the source edition. <- C-070, C-071, C-072, Ch1 principal judgements 1-3
- **evidence:** Key messages: (1) disruption runs through shared ticketing, payment, CDN and cloud platforms; (2) live-output integrity is under-secured in US and Pakistani evidence; (3) losses arrive through revenue lines, lender waivers and multi-year recovery. <- C-070, C-071, C-073
- **significance:** Threat direction: not assessable - baseline edition, no trend series. DDoS and information-manipulation pressure is high but rarely produces disclosed losses. <- Report header: baseline edition, C-072
- **credit_lens:** Leveraged media borrowers may need waivers after a multi-month disruption, as Lee did (USD 11.3 million added debt); ticketing-dependent clients can lose online sales for days to weeks. <- C-027, C-077, C-002, C-008
- **limitation:** Provisional: no approved rubric and no 24-sector calibration; ratings are migrated analytical judgements with confidence capped at Medium, not borrower assessments. <- Migration rule 6
- **Source strip:** Sources: S-001, S-003, S-008, S-014, S-030, S-031, S-034, S-037, S-038, S-039, S-068 (Tier 1); S-042 (Tier 2); S-010 (Tier 3) - Period: Oct 2023 (historical) - Oct 2026 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Dimension | Rating | Status | Confidence | Justification from source edition | Legacy statements |
|---|---|---|---|---|---|
| Fraud | Not assessable | Not covered in source edition | - | Only a judgement that phishing and payment diversion can follow ticketing data exposure; no fraud research (Q10). | C-077, C-009, Ch3 ticketing and payment flows |
| Cyber / ICT | High | Provisional | Medium | Media drew 14.2% of mitigated HTTP DDoS requests on one network in H1 2026; regulator-recorded live-output hijacks; state museum network attack. | C-016, C-011, C-001, C-071 |
| Operational Resilience / TPRM | High | Provisional | Medium | Single points in cloud (14.5-hour AWS event), CDN and shared ticketing; British Library catalogue restored after about 26 months. | C-023, C-025, C-006, C-030, C-070, C-076 |
| Governance / Operating Model | Not assessable | Not covered in source edition | - | Fragments only (an audit recommending a Louvre information systems directorate); no governance research (Q13). | C-033, C-056 |

### Slide 03 - Sector Anatomy: Key Operations & Dependencies

- **Headline:** Sector operations depend on a few shared digital layers - ticketing and payment, cloud regions, content delivery, and content-insertion and satellite paths - where one failure reaches many organisations. <- C-070, Ch6 dependency chains
- **evidence:** Footprint: 8.9 million people in EU cultural employment in 2025 (4.3% of jobs); UK creative industries GBP 145.8 billion GVA in 2024 (5.5% of UK GVA). Eleven subsectors are covered, from broadcasters to museums and media technology providers. <- C-021, C-022, Ch1 subsector table
- **significance:** Front-of-house revenue channels - ticketing, shop, card payment - run on the same corporate IT and shared platforms that attacks and outages reach; at Dresden the security system stayed operational while these channels recovered last. <- C-078, C-070
- **credit_lens:** Ask which ticketing, payment, cloud and delivery providers a borrower shares with peers, and whether it can sell and deliver without them for a week. <- C-090, Ch7 challenge question 1
- **limitation:** Market shares of ticketing, playout and collection-management providers are not public, so no provider is described as dominant. Not covered in source edition: operating-model and governance complexity (Q13). <- Ch6 dependency note, Gap G-03
- **Source strip:** Sources: S-001, S-007, S-008, S-014, S-018, S-038, S-039, S-045, S-046 (Tier 1) - Period: Oct 2025 - Mar 2026; footprint 2024-2025 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Subsector and process | Key dependency | Single point or bottleneck | Substitute or fallback | Legacy statements |
|---|---|---|---|---|
| Museums, monuments, libraries: visitor sales | Shared ticketing platform (Vivaticket for the national monuments network) | One provider hosts sales and data for many institutions | Alternative ticket offices and on-site sales | C-006, C-007, Ch6 dependency row 1 |
| Streaming, online games, publishers: delivery | Hyperscale cloud region (AWS US-EAST-1) | One region failure affects many dependent services | Multi-provider delivery | C-023, C-080, Ch4 scenario 1 limiting conditions |
| News sites, streaming, ticketing: web delivery | Content delivery network (Cloudflare) | One configuration error caused global errors | Multi-provider delivery; pre-recorded fallback | C-025, Ch6 dependency row 3, Ch4 scenario 1 limiting conditions |
| Broadcasters: live output | Content-insertion equipment and satellite uplinks | Remote access or uplink path inserts content into live output | Not evidenced at Tier 1 or 2 in source edition | C-010, C-012, Ch6 dependency row 5 |

### Slide 04 - Cyber Threat Landscape & Attack Scenarios

- **Headline:** Shared platforms and live-output compromise carry the highest operational impact; DDoS and information manipulation are frequent but rarely produce disclosed losses. <- C-070, C-071, C-072
- **evidence:** Last 12 months: five named incidents from November 2025 to October 2026. Last 30 days before cut-off: live-events group breach notice (1 October 2026) and class action (7 October 2026). Content theft (P5) rests on one court case and ranks below the five. <- Ch2 Top 5, C-067, C-014
- **significance:** Hijacked live output and shared-platform outages reach audiences and customers within hours; ransomware against legacy estates sets the longest recovery tails. <- C-071, C-076, C-023
- **credit_lens:** Weight borrower discussions toward shared suppliers and live-output equipment, not only the borrower's own network. <- Legacy slide 2 management implication, C-090
- **limitation:** Impact levels are migrated judgements from the source edition's sector-relevance ratings, not measured outcomes. Not covered in source edition: developments after the 15 October 2026 cut-off. <- Ch2 Top 5 sector relevance column, Gap G-01
- **Source strip:** Sources: S-001, S-008, S-014, S-018, S-030, S-034, S-038, S-039, S-043, S-086, S-087 (Tier 1); S-042 (Tier 2); S-009, S-010 (Tier 3) - Period: Oct 2023 (historical); Nov 2025 - Oct 2026 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Rank | Pathway (pattern, not an attack) | Observed evidence in source edition | Impact level (migrated judgement) | Legacy statements |
|---|---|---|---|---|
| 1 | P2 Shared front-of-house platforms and SaaS integrations (supply-chain concentration) | Ticketing provider ransomware, March 2026 (Tier 3 detail); cloud and CDN outages, October-November 2025 | High | Ch2 P2, C-070, C-008, C-023, C-025 |
| 2 | P3 Broadcast signal and content-insertion compromise (targeted disruption) | Regulator-recorded stream hijacks from November 2025; Pakistani satellite feeds, March 2026 | High | Ch2 P3, C-011, C-012, C-071 |
| 3 | P1 Ransomware and extortion against institutions and publishers (targeted disruption) | Dresden 2026; Lee 2025 and British Library 2023 (historical) | High | Ch2 P1, C-001, C-026, C-030 |
| 4 | P4 Hacktivist DDoS and information manipulation | 14.2% of mitigated HTTP DDoS requests in H1 2026; 540 FIMI incidents in 2025 | Medium | Ch2 P4, C-016, C-018, C-072 |
| 5 | P6 Personal data exposure and litigation | Live-events group breach notice and class action, October 2026 | Medium | Ch2 P6, C-067 |

### Slide 05 - Geopolitical Cyber Threat Outlook

- **Headline:** Conflicts, elections and major live events drive DDoS and information-manipulation pressure on media, but the source edition holds no confirmed state attribution for a sector incident. <- C-016, C-018, C-072, C-012
- **evidence:** Policy responses: European Democracy Shield (Commission Communication, 12 November 2025); European Media Freedom Act source protection from 8 August 2025; UK foreign interference offences in force since 20 December 2023. <- C-049, C-042, C-060
- **significance:** Brand impersonation and availability attacks matter most around elections, conflicts and major live events, when audiences, advertisers and rights holders concentrate. <- C-072 sector relevance, C-080
- **credit_lens:** Ask media borrowers how they detect impersonation of their brands and prepare for event-period DDoS; treat state-linked activity as a monitoring trigger rather than a rating driver. <- Ch7 challenge question 5, Ch7 monitoring trigger 3
- **limitation:** Not covered in source edition: dedicated geopolitical analysis (Q07), exposed-region mapping and state-linked espionage against media; only fragments exist. Benchmarks measure targeting, not impact. <- Gap G-04, Ch8 limitations
- **Source strip:** Sources: S-018, S-041, S-043, S-047, S-051, S-059, S-075 (Tier 1); S-042 (Tier 2) - Period: 2025 - Oct 2026 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Geopolitical-to-cyber pathway | Source-edition evidence | Attribution status | Legacy statements |
|---|---|---|---|
| Conflict coverage -> DDoS against media | Cloudflare links media's 14.2% DDoS share in H1 2026 to coverage of the wars in Iran and Ukraine and to the World Cup | Provider interpretation; no actor named | C-016 |
| Hacktivist DDoS networks | NoName057(16) made 35.8% of ideology-driven claims in ENISA's business-services group (2025); Europol disrupted its infrastructure in July 2025; Germany issued six arrest warrants against suspects in Russia | Law-enforcement action; group claims stay claims | C-017, C-019 |
| Information manipulation against media brands | EEAS: 540 FIMI incidents in 2025; impersonation of established outlets and fabricated media brands; 2026 elections listed as at risk | Institutional reporting; not reproduced per incident | C-018 |
| Satellite broadcast hijack | Pakistani news channels' satellite feeds hijacked on 1 March 2026 | No attribution published | C-012 |

### Slide 06 - Major Cyber Incidents & Lessons Learned

- **Headline:** Five named incidents meet the evidence standard but only one is in the EU; the Dresden case shows revenue channels failing first and recovering last. <- Ch2 shortfall statement, C-078
- **evidence:** Selection: in-period event or outcome, Tier 1 or 2 support, in-scope subsector, distinct lesson. The March 2026 shared ticketing ransomware is excluded: its detail rests on Tier 3 relays. <- Ch2 selection criteria, Ch2 considered but not selected
- **significance:** Disclosure is asymmetric: public cultural bodies publish chronologies but rarely costs; listed groups disclose costs; platforms surface through litigation. <- C-075
- **credit_lens:** Treat card-payment and online-sales loss at public cultural counterparties as a foreseeable multi-week event, and ask how merchant and donor flows continue. <- Legacy slide 5 management implication
- **limitation:** Not covered in source edition: the second and third detailed case studies and incidents after 15 October 2026. Case study 1 does not establish cost, data loss, attacker or access vector. <- Gap G-05, Gap G-01, Ch5 what the case does not establish
- **Source strip:** Sources: S-001, S-002, S-003, S-004, S-014, S-015, S-018, S-086, S-087 (Tier 1); S-006, S-013, S-017, S-019, S-074 (Tier 3) - Period: Nov 2025 - Oct 2026 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Organisation and period | Vector or documented weakness | Disruption | Financial consequence | Lesson | Legacy statements |
|---|---|---|---|---|---|
| 1 Dresden State Art Collections, Jan 2026 (case study 1) | Not disclosed; activity over several days before containment (media-relayed ministerial answer) | Shop, visitor services and card payment lost; website back after 5 days | Not disclosed | Sales recover last | C-001, C-002, C-004, Ch5 |
| 2 US radio stations, Nov 2025 onward | Improperly secured, remotely accessible streaming and alerting equipment | Live output replaced with unauthorised audio | Not disclosed; FCC rule June 2026 | Harden insertion devices | C-011, C-010 |
| 3 Pakistani news channels, Mar 2026 | Satellite feed; possible uplink path | Unauthorised content aired at the 9 pm bulletin | Not disclosed | Signal path is exposed | C-012, C-013 |
| 4 Spotify and labels, Dec 2025 - Apr 2026 | Account-based scraping; circumvention of protection | Catalogue copying alleged at scale | Reported USD 322 million award (media-reported); collection doubtful | Remedies may not recover value | C-014, C-015 |
| 5 Live Nation, Oct 2026 | Identity and health data exposure | No operational impact (company statement, media-reported) | Class action within a week | Notice turns into litigation | C-067 |

### Slide 07 - Control Weaknesses & Resilience Priorities

- **Headline:** Six resilience priorities follow from observed attacks; hardening live-output equipment, fallback for shared suppliers and segregation of transactional systems address the highest-impact pathways. <- C-090, Ch7 action table
- **evidence:** Frameworks named in the source edition - NIST CSF 2.0, ISO/IEC 27001 and 27036, EBU R 148, C2PA, PCI DSS v4.0.1 - are reference vocabularies, not law; EBU R 148 dates from April 2018. <- Ch7 framework mapping, C-059
- **significance:** In the two quantified cases, revenue effects came from production and distribution outages rather than data theft, so continuity capabilities carry the cash-flow weight. <- Ch3 advertising and subscription revenue judgement, C-073
- **credit_lens:** Ask for completion evidence - dependency maps, baseline attestations, restoration tests - rather than policy statements; only the US alerting order sets a mandatory equipment baseline. <- Ch7 evidence of completion column, C-010
- **limitation:** Priorities are sector-informed, not findings about any borrower's controls; confidence is taken from the linked source-edition judgement. <- Ch7 preamble, Ledger confidence
- **Source strip:** Sources: S-001, S-003, S-008, S-014, S-018, S-034, S-038, S-039, S-043, S-044, S-053, S-071, S-086 (Tier 1); S-009 (Tier 3) - Period: Apr 2018 (standard) - Oct 2026 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Weakness observed | Linked evidence | Capability that contains disruption | Horizon | Confidence | Legacy statements |
|---|---|---|---|---|---|
| A1 Single points in ticketing, payment, CDN and cloud | Ticketing outage 2026 (Tier 3); 2025 cloud and CDN outages | Tested fallback sales and delivery channels | 0-6 months | Medium | Ch7 A1, C-070 |
| A2 Default passwords and remote access on insertion and alerting devices | Regulator-recorded hijacks; satellite hijacks | Password, patching and segmentation baseline | 0-6 months | Medium | Ch7 A2, C-071, C-010 |
| A3 Corporate IT shared with ticketing, shop, newsroom and playout | Dresden 2026 | Segregation and tested restoration of transactional channels | 3-12 months | Medium | Ch7 A3, C-078 |
| A4 Exposed ticket-holder, subscriber and donor data | Ticketing exposure (Tier 3); live-events notice | Fraud typology monitoring; out-of-band payment verification | 0-3 months | Medium | Ch7 A4, C-077, C-067 |
| A5 Spoofed outlets and synthetic media | EEAS impersonation findings | Provenance and labelling procedures | 6-12 months | Medium | Ch7 A5, C-018, C-044 |
| A6 Legacy estates and thin insurance | British Library; 35% of UK charities insured | Recovery objectives, insurance and waiver triggers | 6-12 months | Medium | Ch7 A6, C-076, C-020 |

### Slide 08 - Regulatory & Supervisory Resilience Expectations

- **Headline:** EU and UK horizontal cyber law does not name media or culture; obligations arrive through providers, products, media and data rules, and US disclosure and broadcast rules. <- C-074, C-040, C-051, C-057, C-010
- **evidence:** Status from primary instruments or official pages in the source edition; Australia's infrastructure security law alone names broadcasting assets. <- Ch6 regulatory perimeter note, C-064
- **significance:** In-period movement came from AI transparency, product reporting and a US broadcast rule; the UK bill is not yet law. <- Legacy slide 6 interpretation, C-052
- **credit_lens:** Ask whether key suppliers are regulated as managed service, cloud or delivery providers, and how AI Act transparency duties are met. <- Ch4 scenario 3 management question, Ch7 challenge question 5
- **limitation:** Open items: Digital Omnibus effect on Article 50, AVMSD text, national Article 85 laws, UK telecoms security scope for broadcast transmission. Not covered in source edition: supervisory priorities, sanction consequences, US state breach and video privacy rules. <- Ch8 confidence paragraph, Ch8 partly reviewed list, Gap G-06
- **Source strip:** Sources: S-014, S-048, S-049, S-050, S-051, S-052, S-053, S-055, S-060, S-061, S-063, S-064, S-065, S-066, S-069, S-070, S-075, S-076, S-081 (Tier 1); S-072, S-083 (Tier 3) - Period: Legal milestones 2016-2027 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Theme | EU | UK | US (comparative) | Legacy statements |
|---|---|---|---|---|
| Horizontal cyber law | NIS2 (binding via national law): media not listed; reached through CDN, cloud and managed service providers | NIS Regulations 2018 in force, media outside scope; Cyber Security and Resilience Bill at Lords report stage | CIRCIA final rule status unconfirmed | C-040, C-051, C-052, Ch6 CIRCIA sentence |
| Products and equipment | Cyber Resilience Act reporting from 11 September 2026; main obligations 11 December 2027 | Connectable product security regime since 29 April 2024 | FCC alerting order adopted June 2026 | C-045, C-053, C-010 |
| Media and information integrity | Media Freedom Act from 8 August 2025; AI Act Article 50 from 2 August 2026; political advertising rules from 10 October 2025 | Media Act 2024 (no cyber duties in text read); foreign interference offences | Not covered in source edition | C-042, C-044, C-043, C-061, C-060 |
| Data and disclosure | GDPR breach notification within 72 hours; Article 85 national derogations | Special purposes exemption does not list security or regulator notification | SEC 8-K Item 1.05 within four business days; COPPA amendments | C-050, C-065, C-054, C-057, C-058 |
| Designated entities and ransomware | CER Directive: media and culture not among eleven sectors | Ransomware payment ban: proposal only | Not covered in source edition | C-041, C-055 |

### Slide 09 - Financial Impact of Cyber Incidents

- **Headline:** Public loss evidence is sparse and not additive; quantified effects come through curtailed revenue lines, debt added through waivers and multi-year recovery. <- Ch3 bottom line, C-073
- **evidence:** No EU or UK entity disclosed a quantified cyber cost for an in-period incident. Ransom payments are rarely disclosed, so their role cannot be assessed. <- Ch3 bottom line, Ch1 bottom line
- **significance:** Recovery tails run from days (Dresden website) to more than two years (British Library catalogue); revenue dips followed production and distribution outages in both quantified cases. <- C-002, C-030, Ch3 revenue judgement
- **credit_lens:** Watch for unscheduled waiver or amendment requests, merchant-volume drops and fraud alerts at media and cultural counterparties after a sector incident. <- Legacy slide 3 management implication
- **limitation:** Values differ in currency, statistic type and population and are never summed; both quantified attacks predate the period. Not covered in source edition: five-year cost trend and sector business-interruption benchmarks. <- Ch3 comparability, Gap G-07
- **Source strip:** Sources: S-001, S-003, S-030, S-031, S-032, S-033, S-034 (Tier 1) - Period: Attacks Oct 2023 - Jan 2026; disclosures May 2025 - Jul 2026 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Case | Metric | Value | Period | Legacy statements |
|---|---|---|---|---|
| Lee Enterprises (US newspaper group) | Loss of cash flows attributed to the February 2025 attack | USD 10.5 million | FY to 28 Sep 2025 | C-026 |
| Lee Enterprises | Restoration cost expensed (subset of the loss) | USD 3.7 million | FY to 28 Sep 2025 | C-026 |
| Lee Enterprises | Insurance claims filed (claim, not recovery) | USD 6.8 million | FY to 28 Sep 2025 | C-026 |
| Lee Enterprises | Debt added through waivers (not additive) | USD 11.3 million | At 28 Sep 2025 | C-027 |
| KADOKAWA (Japanese publisher and platform group) | Sales effect, company estimate (June 2024 attack) | JPY 8.3 billion | FY to 31 Mar 2025 | C-028 |
| British Library | KPIs within 10% of target | 72.8% vs 81.8% | 2025/26 vs 2024/25 | C-030 |
| Dresden State Art Collections | Cost, data and insurance | Not disclosed | 2026 | Ch3 outcomes table |

### Slide 10 - Cyber-to-Credit Risk Transmission & Stress Scenarios

- **Headline:** Illustrative, not a forecast or loss estimate: 1 week hits live revenue, 4 weeks of supplier outage hit ticketing cash flow, 8 weeks of targeted disruption reach margins and debt service. <- Ch4 scenarios 1-3, Ch3 transmission channels
- **evidence:** Transmission: disruption -> lost output, publication or sales -> advertising, subscription and ticketing cash flow -> temporary liquidity disruption (Lee) -> waivers and debt service (USD 11.3 million added debt at Lee) -> insurance recovery that lags costs. <- Ch3 financial-system transmission, C-026, C-027, C-034
- **significance:** Duration, not data loss, drives the cash-flow effect; correlated outages across many borrowers can coincide with high-value live events. Offsets: multi-provider delivery, alternative sales channels, segregation and manual fallback. <- Ch3 concentration judgement, Ch4 limiting conditions
- **credit_lens:** Borrower data needed: reliance on online and live-event revenue, shared suppliers, recovery time objectives, insurance cover and waiver triggers. <- Ch7 A6, Ch7 challenge question 1
- **limitation:** Illustrative only: no probabilities, no numerical loss per band; durations come from single cases and several rest on Tier 3 reporting. <- Ch4 preamble, Ch4 assumptions
- **Source strip:** Sources: S-001, S-003, S-008, S-023, S-030, S-031, S-032, S-034, S-038, S-039 (Tier 1); S-005, S-009, S-010 (Tier 3) - Period: Oct 2023 - Mar 2026 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Band | Mechanism | Duration evidence in source edition | Operational effect | Credit channel | Legacy statements |
|---|---|---|---|---|---|
| 1 week | Common digital-dependency failure | AWS event about 14.5 hours; Cloudflare outage about 6 hours; Dresden website back after 5 days | Live streams, games, ticket sales and news publication stop | Lost live audience and advertising, make-goods, refunds | C-080, C-023, C-025, C-002 |
| 4 weeks | Third- or fourth-party supply-chain concentration | Monuments network reopened online sales after 10 days and the national library was still unable on 19 March; Dresden online booking within about a month (all Tier 3) | Online ticketing and payments lost across many institutions | Correlated ticketing cash-flow loss; phishing and payment fraud | C-082, C-008, C-005, Ch3 outcomes table |
| 8 weeks | Targeted operational disruption | Lee print advertising capacity limited for several months; British Library catalogue about 26 months | Output loss, rebuild, regulatory scrutiny | Margin pressure, waivers, covenant pressure, public-funding draw | C-081, C-026, C-030, Ch4 scenario 2 financial transmission |

### Slide 11 - Questionnaire-to-Sector Intelligence Mapping

- **Headline:** Provisional map: six generic discussion items link sector threats and incident evidence to credit consequences; no questionnaire was supplied, so no real item IDs are used. <- Ch7 A1-A6, Ch2 P1-P6, Migration rule 7
- **evidence:** Derived from the source edition's actions A1-A6 and pathways P1-P6; no borrower answers are ingested. <- Ch7 action table, Ch2 pathways
- **significance:** Borrower factors that change materiality: multi-provider delivery, alternative sales channels, segregated playout, manual fallback, insurance cover and public-funding support. <- Ch4 limiting conditions, Ch3 public funding
- **credit_lens:** Use answers as discussion input only; self-reported answers are not confirmed evidence and trigger no automatic adverse judgement. <- Publication standard s.7 (reframed)
- **limitation:** Provisional: no questionnaire supplied; replace PROV- IDs with actual item IDs once an approved item list is provided. <- Migration rule 7
- **Source strip:** Sources: S-001, S-008, S-014, S-018, S-030, S-034, S-038, S-039, S-043, S-086 (Tier 1); S-009 (Tier 3) - Period: Oct 2023 (historical); Oct 2025 - Oct 2026 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| ID and item | Threat -> incident evidence | Operational -> credit consequence | Suggested question | Legacy statements |
|---|---|---|---|---|
| PROV-01 Shared suppliers | P2 -> ticketing outage 2026 (Tier 3); 2025 cloud and CDN outages | Sales and delivery stop -> correlated revenue loss | Which ticketing, payment, cloud and delivery providers do you share with peers? | Ch7 A1, C-070 |
| PROV-02 Live-output equipment | P3 -> regulator-recorded and satellite hijacks | Hijacked output -> regulatory scrutiny | Do insertion and alerting devices meet a password, patch and segmentation baseline? | Ch7 A2, C-071 |
| PROV-03 Segregation and recovery | P1 -> Dresden 2026 | Shop and card payment down -> weeks of lost online sales | Are security, building and playout systems separate from corporate IT? | Ch7 A3, C-078 |
| PROV-04 Customer data and fraud | P6 -> live-events notice; ticketing exposure | Notification -> litigation and fraud losses | How are ticket-holder and subscriber data exposures monitored? | Ch7 A4, C-067, C-077 |
| PROV-05 Brand provenance | P4 -> EEAS impersonation findings | Impersonation -> brand integrity | How do you detect impersonation and meet AI Act transparency duties? | Ch7 A5, C-072 |
| PROV-06 Recovery and funding | P1 -> Lee; British Library | Long recovery -> waivers, funding draw | What recovery time, insurance and waiver triggers apply? | Ch7 A6, C-027, C-076 |

### Slide 12 - Credit Officer Engagement: Key Questions & Actions

- **Headline:** Five client discussion topics, each with an early-warning indicator, let credit officers test continuity of sales, output and debt service without assessing borrower controls. <- Ch7 challenge questions, Ch7 monitoring triggers
- **evidence:** Topics reframe the source edition's five Risk Committee challenge questions and its monitoring triggers for client discussion. <- Ch7 challenge questions, Ch7 monitoring triggers
- **significance:** Practical improvements a client can evidence: dependency map, fallback sales channel, baseline attestation for insertion devices, restoration test, insurance schedule. <- Ch7 evidence of completion column
- **credit_lens:** Refer to cyber specialists when an indicator fires or a client cannot evidence a fallback; the proportionate next step is to record and monitor, not to change a rating. <- Legacy slide 7 management implication (reframed)
- **limitation:** Questions address inherent sector exposure; answers are self-reported and are not an audit, compliance or creditworthiness finding. <- Ch7 preamble, Publication standard L13
- **Source strip:** Sources: S-008, S-014, S-030, S-031, S-043, S-053, S-086 (Tier 1); S-009 (Tier 3) - Period: Oct 2025 - Oct 2026 - Cut-off 15 Oct 2026 - v1.0-M Migrated

| Topic | Question for the client | Early-warning indicator | Legacy statements |
|---|---|---|---|
| Shared suppliers | Which providers could stop your sales or delivery for a week, and what is your fallback? | Provider outage or breach notice; prosecutor statement naming a supplier | Ch7 question 1, Ch7 trigger 1 |
| Live-output integrity | Do content-insertion and alerting devices meet a baseline comparable to the June 2026 FCC rule? | Regulator device warning; hijack report | Ch7 question 2, Ch7 trigger 2 |
| Online sales loss | How would a ten-day loss of online ticketing show up in your sales and fraud alerts? | Ticketing or subscriber data notice; merchant-volume drop | Ch7 question 3, Ch7 A4 trigger, Legacy slide 3 implication |
| Debt service after disruption | Would a multi-month advertising disruption require covenant or payment waivers, as at Lee? | Waiver, amendment or liquidity request | Ch7 question 4, Ch7 trigger 4 |
| Impersonation and AI content | How do you detect brand impersonation and meet AI Act transparency duties? | DDoS or FIMI alert ahead of elections or live events | Ch7 question 5, Ch7 trigger 3 |

## 4. Gap register

| ID | Gap | Slide(s) | Why not covered | What a full v4 run would research |
|---|---|---|---|---|
| G-01 | 30-day developments after the original cut-off | 04, 06 | Migration rule 1: no research after 15 October 2026 | Q01-Q03 30-day window: new incidents, updates to Dresden, the ticketing provider and the live-events case |
| G-02 | Fraud beyond cyber-enabled payment fraud (Q10) | 02, 11 | Source edition researched cyber incidents only; fraud appears only as a phishing and payment-diversion judgement | Q10 sector fraud typologies: ticketing and subscription fraud, advertising fraud, royalty and rights fraud, donor fraud, with loss data |
| G-03 | Governance and operating-model complexity (Q13) | 02, 03 | Not a research question in the source edition; fragments only (Louvre audit, UK Government Cyber Action Plan) | Q13 ownership, public-funding and arm's-length structures, IT governance maturity, outsourcing models |
| G-04 | Dedicated geopolitical analysis (Q07) | 05 | Source edition holds fragments only (Cloudflare interpretation, ENISA, Europol, EEAS, Pakistani hijacks) | Q07 state-linked campaigns, espionage against newsrooms, exposed regions, attribution with confidence |
| G-05 | Second and third detailed case studies | 06 | Source edition has one case study (Dresden) | Q04 two further reconstructions, for example a broadcaster and a ticketing or platform case with disclosed outcomes |
| G-06 | US regulation beyond comparative items | 08 | Source edition scope was EU and UK primary with US comparative only | Q11 US state breach laws, Video Privacy Protection Act litigation, FCC licensee duties, CIRCIA final rule status, COPPA effective dates |
| G-07 | Supervisory priorities and consequences of non-compliance | 08 | Not researched in the source edition | Q11 regulator enforcement records and supervisory work programmes (EU, UK, US) |
| G-08 | Five-year cost trend and sector business-interruption benchmarks | 09 | Source edition has single-company disclosures only | Q06 multi-year loss series, insurer and survey benchmarks with method notes |
| G-09 | Cross-sector comparison (Q14) and 24-sector rating calibration | 02 | No cross-sector benchmark in the source edition | Q14 benchmark register against other sectors; calibration of ratings across the 24-sector universe |
| G-10 | Approved rating rubric | 02 | None supplied | Formal ratings against an approved rubric with recorded hash |
| G-11 | Questionnaire item list | 11 | None supplied | Live Q08 mapping with actual item IDs |
| G-12 | Tier 1 or Tier 2 evidence of broadcaster fallback; 4-week band duration evidence | 03, 10 | Broadcaster fallback rests on one Tier 3 case; the 4-week band rests on Tier 3 relays (monuments network, national library, Dresden booking) | Primary statements from broadcasters and ticketing institutions on restoration times |
| G-13 | Full v4 report (11 headings) and evidence annex A1-A7 | all | Outside the migration brief's outputs | Q09 report and annex A1-A7 built from the v4 registers |
| G-14 | Classification marking | 01 | Not specified in the source edition | Classification supplied by the publishing owner |

Duration bands (rule 8): all three bands carry legacy duration evidence - 1 week (AWS event about 14.5 hours, Cloudflare about 6 hours, Dresden website after 5 days; Tier 1), 4 weeks (Tier 3 only, gap G-12), 8 weeks (Lee several months, British Library about 26 months; Tier 1). No band is marked 'duration not evidenced'.

## 5. Rating table (Slide 02)

No approved rubric was supplied, so every rating is Provisional; confidence is capped at Medium for migrated ratings. Ratings are migrated analytical judgements, not borrower assessments, and are not calibrated against the 24-sector universe.

| Dimension | Rating | Status | Confidence | Justification (legacy evidence) | Legacy statements |
|---|---|---|---|---|---|
| Fraud | Not assessable | Not covered in source edition | - | Only a judgement that phishing and payment diversion can follow ticketing data exposure; no fraud research (Q10). | C-077, C-009, Ch3 ticketing and payment flows |
| Cyber / ICT | High | Provisional | Medium | Media drew 14.2% of mitigated HTTP DDoS requests on one network in H1 2026; regulator-recorded live-output hijacks; state museum network attack. | C-016, C-011, C-001, C-071 |
| Operational Resilience / TPRM | High | Provisional | Medium | Single points in cloud (14.5-hour AWS event), CDN and shared ticketing; British Library catalogue restored after about 26 months. | C-023, C-025, C-006, C-030, C-070, C-076 |
| Governance / Operating Model | Not assessable | Not covered in source edition | - | Fragments only (an audit recommending a Louvre information systems directorate); no governance research (Q13). | C-033, C-056 |

## 6. Reframed judgements (labelled analytical judgement)

| ID | Slide | Reframed statement | Legacy basis |
|---|---|---|---|
| RJ-01 | 02 | Provisional High ratings for Cyber / ICT and Operational Resilience / TPRM | Synthesised from legacy principal judgements 1-3 (C-070, C-071, C-072), the DDoS benchmark (C-016), the FCC record (C-011), cloud and CDN outages (C-023, C-025) and British Library recovery (C-030, C-076); the source edition assigned no ratings |
| RJ-02 | 02 | Threat direction 'not assessable' | Source edition is a baseline with no prior edition or trend series (report header) |
| RJ-03 | 04 | Ranking and impact levels of pathways P1-P6 | Derived from the legacy Top 5 sector-relevance column (Highest/High/Medium-high/Medium) and principal judgements; P5 ranked below the five |
| RJ-04 | 05 | Treat state-linked activity as a monitoring trigger rather than a rating driver | Reframes the legacy monitoring trigger on DDoS and FIMI alerts (Ch7) and the absence of confirmed state attribution (C-012, C-016) |
| RJ-05 | 07 | Continuity capabilities carry the cash-flow weight | Reframes the legacy Ch3 judgement that revenue effects arose from production and distribution outages in the two quantified cases (C-073) |
| RJ-06 | 10 | Mapping of mechanisms to 1-week, 4-week and 8-week bands | Each band's duration evidence is a legacy figure; assigning the common-dependency, supply-chain and targeted mechanisms to the bands is a migration judgement |
| RJ-07 | 10 | Duration, not data loss, drives the cash-flow effect | Reframes legacy Ch3 transmission and concentration judgements |
| RJ-08 | 11 | PROV-01 to PROV-06 items and their threat-to-credit chains | Derived from legacy actions A1-A6 and pathways P1-P6 (Ch7, Ch2) |
| RJ-09 | 12 | Refer to cyber specialists when an indicator fires; record and monitor rather than change a rating | Reframes the legacy slide 7 implication (escalate to the Risk Committee when a trigger fires) for a lender audience |
| RJ-10 | 02-12 | All Credit Lens statements | Each reframes a legacy management implication, challenge question or action for client discussion; none adds a bank- or borrower-specific claim |

## 7. Pre-delivery checks

| Check | Result |
|---|---|
| 12 slides, fixed labels, correct order | PASS |
| Headline, Evidence, Significance, Credit Lens, Limitation and source strip on Slides 02-12 | PASS |
| Every element and table cell placed verbatim on the exported slide | PASS |
| Every S- ID on a slide exists in the mapping table; no URLs on slides | PASS |
| Every number on slides appears in the legacy files (band labels 1/4/8 weeks, version 1.0-M, question IDs and slide numbers excepted) | PASS |
| Provisional (02, 11), Not assessable (02), Illustrative (10), Migrated (01) labels | PASS |
| Notes carry no substantive text; no footer, date or slide-number placeholders | PASS |
| Office package validation (pptx skill validate.py) | PASS |
| Language rules (core check_language_rules.py) on migration_record.md, MIGRATION_NOTE.md, slide text and spec | PASS |
| Visual inspection of all 12 exported slides at normal reading size | PASS - see section 8 |
| Density bands (diagnostic) | Flagged: slide 1: 81 words outside band 20-80; slide 2: 285 words outside band 120-260; slide 6: 352 words outside band 150-320; slide 8: 352 words outside band 150-320. Excess comes mainly from the mandatory source strips (for example 22 source IDs on Slide 08) and, on Slide 06, the timeline month labels; no evidence was cut to meet a band. |

Visible words per slide: 1: 81, 2: 285, 3: 303, 4: 300, 5: 292, 6: 352, 7: 320, 8: 352, 9: 293, 10: 312, 11: 300, 12: 284.

## 8. Visual review

Visual revision 2 (27 October 2026, on request): content, sources and labels unchanged; one visual form per slide within the same palette (white background, dark text 1A1A1A, emerald 00915E with flat emerald tints, grey hairlines). No gradients, shadows, rounded corners, icons or imagery.

| Slide | Visual form |
|---|---|
| 01 | Emerald side panel with sector name; metadata in ruled rows; typographic, no image |
| 02 | Four rating scorecard tiles (rating word printed on its tint, status, confidence, justification) |
| 03 | Dependency map: subsector -> dependency -> single point -> fallback, with arrows |
| 04 | Ranked pathway rows with rank numerals and a four-step impact meter (word printed beside it) |
| 05 | Pathway flow: driver block -> evidence -> attribution status |
| 06 | Incident timeline September 2025 - October 2026 with numbered markers, above the incident table |
| 07 | Weakness rows with a 0-12 month horizon bar chart and confidence column |
| 08 | Three-jurisdiction matrix with emerald header; 'Not covered in source edition' cells greyed |
| 09 | Stat tiles per metric (value, metric, case, period); 'Not disclosed' tile greyed |
| 10 | Duration bars proportional to 1, 4 and 8 weeks, labelled Illustrative |
| 11 | Mapping table with emerald header, emerald PROV- IDs and alternating row shading |
| 12 | Numbered engagement rows with an emerald rule beside each early-warning indicator |

Inspection: all 12 slides rendered with LibreOffice (pptx skill soffice wrapper) and inspected as 80 dpi images. Issues found and fixed during the revision: text-column collisions on Slides 06 and 07, header overlap on Slides 03 and 04, stat-tile wrapping on Slide 09, narrow-bar labels on Slide 07, missing column gutters on Slides 04, 10 and 12. Final render: no clipped or overlapping text. Slide 12 topic cells no longer carry a leading number; the number is drawn as a numeral. The first layout is retained in the run folder as render/deck_v1_layout.pptx.

## 9. Release status

NEEDS_REVIEW. This migrated deck will not pass the full v4 release gate: Q07, Q10, Q13 and Q14, the 30-day window and the three case studies were not researched, ratings are Provisional without an approved rubric, the questionnaire map is Provisional, and no v4 report or annex A1-A7 exists. See MIGRATION_NOTE.md.
