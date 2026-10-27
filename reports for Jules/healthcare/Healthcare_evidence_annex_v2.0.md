# Healthcare - Evidence Annex

**Edition:** 2026-10. **Version:** 2.0. **Evidence cut-off:** composite - Q01-Q07 as of 14 October 2026; Q10-Q15 as of 27 October 2026. Companion to the Healthcare Sector Cyber Resilience & Credit Intelligence Report (17_sectorial_report.md). Reference numbers [n] resolve to the References section of that report and to the S- IDs (S-0nn = [n]). Rating status: provisional. Questionnaire mapping: provisional.

## A1 Incident Register

Deduplicated; one row per underlying event. Horizon: H = historical landmark; R = rolling 12 months; D = last 30 days. Class: CI = cyber intrusion; CEF = cyber-enabled fraud; OO = operational outage.

| ID | Horizon | Organisation | Subsector; country | Incident / disclosure dates | Class; vector | Attribution (who; confidence) | Disruption and recovery | Financial / regulatory outcome | Sources |
|---|---|---|---|---|---|---|---|---|---|
| INC-01 | R | Stryker | Medical technology; global (UK supply effect) | Identified 11 March 2026; full manufacturing 1 April; fully operational 9 April | CI; internal Microsoft environment, malicious file running commands; device-wiping reports Tier 3 only | Handala persona claim (media); FBI links Handala to MOIS-operated entity; company does not attribute; Low | About three weeks of manufacturing, ordering and shipping disruption; six NHS lines on controlled allocation; some patient cases rescheduled | Material Q1 2026 effect; adjusted EPS -8.5%; guidance kept; Q2 organic growth 9.0% | [1] [2] [3] [4] [5] [6] [7] [8] [9] [10] [100] |
| INC-02 | R | Boston Scientific | Medical technology; global | Identified 25 August 2026; 8-K 26 August; Item 1.05 on 8 September | CI; unauthorised activity on IT systems | None stated | Manufacturing, ordering, shipping disrupted; remote-monitoring activations paused, then restored | Q3 and full-year guidance expected to be missed; quantification due 28 October 2026 | [11] [12] [13] [14] |
| INC-03 | R | Cegedim Sante (MLM) | Primary-care software; France | Detected late 2025; disclosed 26 February 2026 | CI; abnormal queries on doctor accounts (Tier 3) | Not stated | 15.8 million administrative records published; about 165,000 with free-text notes | CNIL informed; criminal complaint; ministers summoned vendor (Tier 3) | [17] [18] |
| INC-04 | R | West Pharmaceutical Services | Pharmaceutical components; global incl. Germany | Detected 4 May 2026; material 7 May; full operation 20 May | CI; encryption and exfiltration | Not stated | Global systems offline; site-by-site restart over 16 days | USD 6.9 million combined nonrecurring fees (cyber and legal) | [15] [16] [73] |
| INC-05 | R | AZ Monica | Acute hospital; Belgium | 13 January 2026 - about mid-February 2026 | CI; server compromise, precautionary shutdown | Not stated | Surgery cancelled; seven patient transfers; EPR restarted 5 February; full operation after about four weeks (Tier 3) | Ransom refused; no cost disclosed | [19] [20] [21] [22] [23] |
| INC-06 | R | McKesson | Pharmaceutical distribution; US | Discovered 25 August 2026 | CI | Not stated | Scope not determined at filing | Materiality not determined | [24] |
| INC-07 | R | Veradigm | EHR vendor; US | 8-K September 2026 | CI; third-party vendor API credentials | Not stated | No operational disruption | No material impact expected | [25] |
| INC-08 | R (consequences) | Clinical Diagnostics NMDL | Screening laboratory; Netherlands | Hack July 2025; consequences to May 2026 | CI; data theft, possibly via another client | Not stated | Laboratory suspended; substitutes at 150% for six months; invitations halved from 22 December 2025 | IGJ non-compliance finding 13 May 2026; AP investigation | [26] [27] [28] [29] |
| INC-09 | R (outcome) | Hôpital Privé de la Loire | Private hospital; France | Breach summer 2025; fine 3 September 2026 | CI; remote access without MFA | Not stated | 524,867 patients affected | EUR 500,000 CNIL fine | [30] |
| INC-10 | H | Change Healthcare | Claims infrastructure; US | 21 February 2024 | CI; systems isolated | Not stated in cited sources | Majority of services restored or replaced by reporting point | FY2024 USD 2.2 billion response; USD 867 million disruption; more than USD 9 billion provider loans; about 192.7 million notified | [37] [38] [101] |
| INC-11 | H | Synnovis | Pathology; London, UK | 3 June 2024; services restored December 2024 | CI; ransomware | Not stated in cited sources | 10,152 outpatient appointments and 1,710 elective procedures postponed to 22 September 2024 | No complete loss measure | [39] [40] [72] [102] |
| INC-12 | H (2026 update) | Children's Healthcare of Atlanta | Health system; US | Transfer around 13 June 2023; sentencing 22 July 2026 | CEF; supplier mailbox compromise and bank-detail change | External hacker unidentified; launderer convicted | Not a service outage | USD 5.3 million transferred; about USD 4 million recovered; FRD-01 | [74] |
| INC-13 | H | HSE | National health service; Ireland | 14 May 2021 | CI; ransomware, national network shutdown | Not stated in cited conclusion | 99% of applications restored by 21 September 2021 (130 days) | Full economic cost not established in cited conclusion | [103] |
| INC-14 | H | NHS England (WannaCry) | Hospitals; England | 12 May 2017 | CI; self-propagating ransomware | Not stated in cited findings | At least 81 of 236 trusts affected; 6,912 cancellations identified, over 19,000 estimated | Not stated | [104] |
| INC-15 | H | Advanced Computer Software Group | Managed IT supplier to NHS; UK | August 2022; fine 27 March 2025 | CI; ransomware via customer account lacking MFA | Not stated | NHS 111 disrupted; 79,404 people affected | GBP 3,076,320 ICO fine | [43] |
| INC-16 | D | Phishing-service operators (YAM, CoGUI, Iron Man) | Cross-sector, health-relevant | Published 14 October 2026 | Legal action, not an incident | Microsoft and Health-ISAC allegations; not adjudicated | Not established | Court orders listed | [88] |

**Considered, not selected:** DXS International NHS supplier incident (December 2025; Tier 3 only, NHS England reported no patient-service impact) [71]; other 2026 medical-technology incidents such as UFP Technologies, Medtronic, Abbott and Cook Medical (discovery list only) [70]; Conduent January 2025 event (pre-period; cost used comparatively) [41] [42].

### Narratives for the rolling 12-month top five

**Stryker.** [Stryker - Form 8-K/A April 2026][1] Observed: Stryker identified the incident on 11 March 2026, determined a material impact on operations and first-quarter results, and reported on 9 April 2026 that it was fully operational with ordering and distribution restored. [Stryker - Customer updates on network disruption][2] Observed: the company described the event as contained to its internal Microsoft environment, stated that connected products remained safe, reported on 19 March that some personalised implant customers were disrupted and some patient cases in the week of 16 March were rescheduled, and on 23 March described a malicious file used to run commands and hide activity. [HIPAA Journal - Stryker cyberattack][9] Context (Tier 3): media and researchers reported abuse of the device-management platform to wipe corporate devices; Stryker does not use that description. [NHS England - Stryker supply disruption letter][3] Observed: on 18 March NHS England estimated UK stock at about two weeks at normal ordering volumes, cancelled orders placed between 11 and 16 March, placed six NHS Supply Chain lines under control demand management, required mutual aid and set a SitRep deadline of 19 March. [BOA - Stryker update 27 March 2026][4] Observed: on 27 March the British Orthopaedic Association relayed that production had resumed. [CISA - Endpoint management hardening alert][100] Observed: on 18 March 2026 CISA recommended hardening endpoint-management configurations against misuse.

**Boston Scientific.** [Boston Scientific - Form 8-K 26 August 2026][11] Observed: an incident identified on 25 August 2026 disrupted access to information systems and the ability to process and ship orders globally. [Boston Scientific - Form 8-K Item 1.05 September 2026][12] Observed: on 8 September the company reported effects on manufacturing, order processing and shipping, said it was unlikely to meet third-quarter and full-year guidance, expected to recover part of the lost revenue and did not expect a material long-term impact. [Boston Scientific - Cyber update 8 September 2026][13] Observed: sterilisation facilities were operational and LATITUDE remote-monitoring activations restored. [Healthcare Dive - Boston Scientific restoration][14] Context (Tier 3): the chief executive was reported as saying all plants and distribution centres were shut globally.

**Cegedim Sante.** [Cegedim Sante - Statement 4 March 2026][17] Observed: detected at the end of 2025; a file of 15.8 million administrative records after deduplication was published; about 165,000 records contained a doctor's free-text note; only MLM was affected; CNIL informed and complaint filed. [Egora - Cegedim summoned by ministers][18] Context (Tier 3): 1,500 of 3,800 MLM doctor users reported affected; ministers summoned the company on 5 March 2026.

**West Pharmaceutical.** [West Pharmaceutical - Form 8-K May 2026][15] Observed: intrusion detected 4 May 2026, material on 7 May, data exfiltrated and systems encrypted, systems taken offline globally. [West Pharmaceutical - Q2 2026 results release][16] Observed: USD 6.9 million nonrecurring professional fees combine the cyber incident with legal matters. [West Pharmaceutical - Cyberattack updates][73] Observed: sites including Eschweiler resumed by 15 May; fully operational 20 May 2026.

**AZ Monica.** [Belgian Chamber - Committee record 3 February 2026][23] Observed (Tier 1): the attack was the subject of a parliamentary question answered on 3 February 2026. [VRT NWS - Belgian hospital cyber readiness][19] [The Record - AZ Monica cyberattack][20] [VRT NWS - AZ Monica EPR restart][21] [VRT NWS - AZ Monica six months on][22] Media-relayed (Tier 3): servers shut down on 13 January 2026 at two campuses; surgery cancelled; seven unstable patients transferred; EPR restarted 5 February; 70-80% activity after one week and full operation after about four weeks; ransom refused; restored from intact backups.

## A2 Detailed Case Studies

### Case study 1 - Dutch screening laboratory breach (Clinical Diagnostics NMDL)

**Why selected.** [BVO Nederland - Annual report 2025][28] [IGJ - Clinical Diagnostics finding][29] It is the only EU or UK case combining Tier 1 operator and regulator evidence, an in-period care-continuity consequence, an in-period regulatory outcome and a clear third-party concentration mechanism. The trigger (July 2025) precedes the reporting period; its consequences fall within it.

**Timeline.**

| Date | Event | Evidence |
|---|---|---|
| July 2025 | Hack of Clinical Diagnostics systems; operator informed more than a month later | [BVO Nederland - Annual report 2025][28] |
| 5-7 August 2025 | Operator informed; crisis structure activated; AP, RIVM and IGJ notified | [BVO Nederland - Annual report 2025][28] |
| 11 August 2025 | Media informed; file covering about 485,000 people | [BVO Nederland - 405,000 participants notified][26] |
| 19-20 August 2025 | About 405,000 participants notified; tests rerouted | [BVO Nederland - 405,000 participants notified][26] |
| 29 August 2025 | About 230,000 further people confirmed; letters to all 941,000 participants whose data was shared since 2017 | [BVO Nederland - Breach larger than reported][27] |
| August 2025 onwards | Backup laboratories at about 150% of capacity for six months | [BVO Nederland - Annual report 2025][28] |
| 22 December 2025 | Primary invitations reduced by 50%; follow-up tests continued in full | [BVO Nederland - Annual report 2025][28] |
| 13 May 2026 | IGJ finds the laboratory did not meet NEN 7510 at the time of the hack or the December 2025 inspection | [IGJ - Clinical Diagnostics finding][29] |

**Mechanism.** [BVO Nederland - Breach larger than reported][27] Observed: stolen data included identity and contact details, citizen service number, test type and result and general practitioner name; data may have been obtained through another client of the laboratory. [IGJ - Clinical Diagnostics finding][29] Observed: no independent information security audit and no periodic mapping of processing risks. Judgement: the service effect came from suspending a supplier that could no longer be trusted, which removed one of three laboratories.

**Effects, recovery and outcome.** [BVO Nederland - Annual report 2025][28] Observed: work moved to the Jeroen Bosch Ziekenhuis and Symbiant laboratories; by December 2025 backlog could not be absorbed. [IGJ - Clinical Diagnostics finding][29] Observed: IGJ cannot impose punitive measures under the Wabvpz; the AP is investigating under GDPR; IGJ called on providers to verify third parties' security. No incident cost, provision or insurance amount was disclosed; the financial outcome is unavailable, not zero. Recovery was constrained by scarce qualified substitutes, not technical restoration.

**Lesson.** A confidentiality breach at an outsourced clinical service becomes an availability problem when the purchaser must suspend the supplier and substitutes lack capacity.

**What it does not establish.** Clinical harm, incident cost, attacker identity, or similar gaps at other laboratories.

### Case study 2 - Change Healthcare claims-clearing outage (historical landmark)

**Why selected.** [UnitedHealth - Form 10-K FY2024][101] [UnitedHealth - Q3 2024 results release][37] It is the clearest public evidence of cyber-to-liquidity transmission across many providers, with audited company disclosure of costs and financing. It is historical (2024) and US-specific; it is retained for its structural lesson.

**Timeline.**

| Date | Event | Evidence |
|---|---|---|
| 21 February 2024 | Attack; affected systems isolated | [UnitedHealth - Form 10-K FY2024][101] |
| To 30 September 2024 | USD 2,457 million pre-tax impacts (USD 1,710 million direct response; USD 747 million disruption); USD 8,904 million loans advanced to providers, USD 3,189 million repaid | [UnitedHealth - Q3 2024 results release][37] |
| To 31 December 2024 | USD 2.2 billion direct response costs; USD 867 million estimated business-disruption impacts; more than USD 9 billion interest-free provider loans; majority of services restored or replaced | [UnitedHealth - Form 10-K FY2024][101] |
| To 31 July 2025 | About 192.7 million individuals notified | [HHS OCR - Change Healthcare FAQ][38] |

**Mechanism and effects.** [UnitedHealth - Form 10-K FY2024][101] Observed: isolation of a shared clearing platform interrupted claims and payments for providers that had not themselves been attacked; the loan programme bridged their cash flow. Initial access detail is not part of the cited record.

**Lesson.** Shared transaction infrastructure converts one intrusion into a sector-wide liquidity demand; bridging finance, not technical recovery, defined the credit channel.

**What it does not establish.** Provider-level losses, a sector-wide loss total, the outstanding loan balance at year-end, or transmission speed in systems with different payer structures (for example EU or UK public funding).

### Case study 3 - Stryker global disruption and NHS supply response

**Why selected.** [Stryker - Form 8-K/A April 2026][1] [NHS England - Stryker supply disruption letter][3] It is the most recent large event with Tier 1 evidence on both the supplier side (filings, updates, results) and the buyer side (NHS England measures), plus an agency advisory.

**Timeline.**

| Date | Event | Evidence |
|---|---|---|
| 11 March 2026 | Network disruption identified | [Stryker - Customer updates on network disruption][2] |
| 11-16 March 2026 | NHS orders placed in this window cancelled | [NHS England - Stryker supply disruption letter][3] |
| 18 March 2026 | NHS England estimates about two weeks of UK stock; six lines under control demand management; mutual aid; CISA advisory on endpoint management | [NHS England - Stryker supply disruption letter][3] [CISA - Endpoint management hardening alert][100] |
| 19 March 2026 | Some personalised implant customers disrupted; some patient cases rescheduled | [Stryker - Customer updates on network disruption][2] |
| 23 March 2026 | Company describes malicious file used to run commands and hide activity | [Stryker - Customer updates on network disruption][2] |
| 27 March 2026 | Production resumed (relayed by BOA) | [BOA - Stryker update 27 March 2026][4] |
| 1 April 2026 | Manufacturing fully operational | [Stryker - Customer updates on network disruption][2] |
| 30 April 2026 | Q1 results: adjusted EPS -8.5%; margin -180 basis points; guidance kept | [Stryker - Q1 2026 results release][6] |
| 30 July 2026 | Q2 organic growth 9.0% | [Stryker - Q2 2026 results release][8] |

**Mechanism.** [Stryker - Customer updates on network disruption][2] [CISA - Endpoint management hardening alert][100] Observed: disruption contained to the internal Microsoft environment; CISA recommended hardening endpoint-management configurations. [HIPAA Journal - Stryker cyberattack][9] [FBI - FLASH on Iranian MOIS actors][10] Context: Handala persona claim (media) and FBI assessment of Handala's MOIS link; no official attribution of this incident.

**Effects and recovery.** Production, ordering and shipping halted for about three weeks; UK stock cover at day 7 extended to about day 21; recovery margin was days, not weeks. Financial effect was a quarter-timing shock with recovery in Q2.

**Lesson.** Buyer-side buffers, not supplier technical recovery, set the time available; a shared administrative plane widens blast radius.

**What it does not establish.** Attacker identity, product or device compromise (the company states products remained safe), that UK stock ran out, or patient harm.

## A3 Sector Fraud, Cyber & Resilience Metrics

### Fraud typology materiality screen (Q10 Pass A)

Source: owner-supplied Q10-Q15 research, section D1, anchored on [NHSCFA - SIA procurement and commissioning][82], [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74], [FBI IC3 - Healthcare payment processor warning 2022][85] and the pharmacy and laboratory records [75]-[78]. M = material structural consideration; P = possible, insufficient evidence here; NE = not evidenced in reviewed records (not zero exposure). Columns: H hospitals; A ambulatory, community and long-term care; L laboratories; R pharmacies and distribution; P/B pharmaceuticals and biotechnology; MT medical technology; I/T payers and transaction infrastructure. Non-cyber means compromise or digital impersonation is not necessary to the scheme; electronic submission of a false claim alone is not a cyberattack.

| Controlled typology | Sector name | H | A | L | R | P/B | MT | I/T | Classification and reason |
|---|---|---|---|---|---|---|---|---|---|
| payment_diversion | Payment diversion | M | P | P | P | P | P | M | Hybrid where impersonation causes a bank-detail change; cyber-enabled where an account is changed directly |
| business_email_compromise | Business email compromise | M | P | P | P | P | P | M | Hybrid; supplier identity and payment instructions abused |
| invoice_procurement | Invoice and procurement fraud | M | M | P | P | P | P | P | Non-cyber or hybrid; false supply, false invoices, contract deception |
| supplier_impersonation | Supplier impersonation | M | P | P | P | P | P | P | Hybrid; documented hospital supplier-email route |
| executive_impersonation | Executive impersonation | M | P | P | P | P | P | P | Hybrid; NHS intelligence supports email impersonation; healthcare voice or video losses not established |
| account_takeover | ERP, banking or supplier-portal takeover | P | P | P | P | P | P | M | Cyber-enabled or hybrid; payment-processor access documented historically |
| insider_fraud | Insider fraud | P | P | M | M | P | P | P | Usually non-cyber or hybrid; owner or management involvement in claims schemes |
| asset_misappropriation | Asset misappropriation | M | P | P | P | P | P | P | Non-cyber or hybrid; NHS intelligence identifies supplier-related asset concerns |
| financial_statement_fraud | Financial statement fraud | P | P | P | P | P | P | P | Non-cyber or hybrid; no selected restatement case |
| corruption_bribery | Corruption and bribery | M | M | M | P | P | P | P | Non-cyber or hybrid; referral and procurement incentives |
| identity_fraud | Identity fraud | P | P | M | M | P | P | M | Non-cyber, cyber-enabled or hybrid; patient, provider and payment-account identities |
| identity_fraud (synthetic) | Synthetic identities | NE | NE | NE | NE | NE | NE | NE | Fabricated patients do not by themselves establish a synthetic-identity mechanism |
| grant_subsidy_tax_fraud | Grant, subsidy and tax fraud | P | P | M | P | P | P | P | Publicly funded testing claims evidenced; tax-specific evidence missing |
| customer_facing_fraud | Fraud against customers | P | P | P | P | P | P | P | Possible hybrid exposure; a general impersonation warning does not establish provider liability |
| other_sector_specific | False billing, undispensed drugs, fabricated tests, referral kickbacks | M | M | M | M | P | P | M | Primarily non-cyber claims and referral deception; payers can be victims |

Confidence: Medium for the sector screen; Low for subsector extrapolation where marked P. [NHSCFA - SIA procurement and commissioning][82] The NHS assessment distinguishes assessed threats from adjudicated cases, and its procurement estimate changed partly because of methodology.

### Fraud register (Q10 Pass B)

| ID | Organisation | Typology (detail) | Classification | Perpetrator | Channel | Rail | Period; discovery | Loss / outcome; currency | Recovery | Control weakness (documented) | Governance factor | Status | Linked INC | Source |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| FRD-01 | Children's Healthcare of Atlanta | payment_diversion (supplier impersonation via vendor mailbox) | hybrid | external (with launderer) | email | bank_transfer (ACH details; described as wire) | Around 13 June 2023; detected within days by hospital and vendor; mechanism not specified | USD 5.3 million transferred | About USD 4 million recovered; USD 682,860 restitution ordered | Bank-detail change accepted from compromised supplier mailbox; exact approval step not published | Capital expenditure funding exposed | Conviction 12 February 2026; sentence 22 July 2026 (four years) | INC-12 | [74] |
| FRD-02 | LTD Holding LLC (Labtech Diagnostics) | corruption_bribery (kickbacks disguised as rent, phlebotomy, toxicology and equipment services) | non_cyber | management and doctors | paper_document, in_person (money orders) | mixed | 2016 and 2018-2021; whistleblower action; discovery date unknown | At least USD 6.8 million civil settlement plus contingent payment; USD 103,551.90 restitution | Not stated | Alleged false service descriptions and certifications | Founder and CEO based in UAE; management involvement | Agreement to plead guilty to five counts (7 January 2026); allegations qualified | - | [75] |
| FRD-03 | Ahold Delhaize USA | other_sector_specific (inflated usual and customary prices) | non_cyber | unknown (corporate process) | mixed | unknown | Conduct period not stated; pharmacist whistleblower | USD 40 million settlement; not programme loss | - | Pricing interpretation across pharmacy operations | Multi-site pricing governance | Settlement 10 June 2026; no liability determination | - | [76] |
| FRD-04 | Paterson pharmacy (Nestor Jaime) | other_sector_specific (claims for Dificid not purchased or dispensed) | non_cyber | management (owner) | mixed | unknown | December 2019 - December 2021; discovery unknown | At least about USD 2.5 million Medicare reimbursements | Not established | Owner-directed false claims; misuse of provider identifiers | Owner control | Guilty plea 19 November 2025 | - | [77] |
| FRD-05 | Illinois laboratory (Rajesh Patel) | other_sector_specific (fabricated negative COVID-19 results) | non_cyber | management with third-party intermediary (alleged) | mixed | unknown | May 2021 - April 2022; detection unknown | Alleged USD 66.2 million claims; USD 44.1 million payments; USD 28 million personal proceeds (non-additive) | Unknown | Alleged intermediary and fabricated-result dependence | Co-owner and COO | Indicted 19 October 2026; unconfirmed | - | [78] |

### Fraud structural exposure (Q10 item 4)

| Driver | Assessment | Boundary; confidence |
|---|---|---|
| Payment volume, value and urgency | Material: reimbursements and supplier payments create separate incoming and outgoing exposures | Volumes and reliance on email or phone not quantified; Medium |
| Supplier density and onboarding churn | Material contracting exposure; density unmeasured | Borrower-specific; Medium |
| Intermediaries and agents | Material in laboratory referral and specimen-collection models | Not all agents or subsectors; Medium |
| Cash, inventory and movable assets | Possible to material by model (dispensing, NHS asset concerns) | No inventory-theft dataset; Low-Medium |
| Public funding and procurement | Material: public claims, commissioning and procurement recur | Funding is not itself evidence of fraud; Medium |
| Decentralised payment authority | Possible across multi-site operations | Delegation patterns not established; Low |
| Cross-border flows | Possible; international links in selected cases | No sector measure; Low |
| Revenue and incentive complexity | Material: pricing formulas, claims validation, paid referrals | Strongest in pharmacies and laboratories; Medium |
| Customer-facing flows | Possible: patient payments and identity-linked claims | Refund and conduct losses not quantified; Low |

### Fraud controls and detection (Q10 item 5)

| Label | Observation | Limit on inference | Source |
|---|---|---|---|
| Confirmed: hospital payment diversion | Compromised supplier mailbox supported a payment-detail change; discovery and bank tracing enabled recovery | No published control test shows the missing approval or callback step | [74] |
| Confirmed: reporting pathway | Ahold settlement resolved a pharmacist's whistleblower action | Does not show internal reporting was absent | [76] |
| Allegation: contractual disguise | Labtech arrangements allegedly used false service descriptions and certifications | Supports scrutiny of substance over paperwork | [75] |
| Sector intelligence | NHS assessment identifies false invoices, impersonation, conflicts of interest and supplier due-diligence concerns | Assessed intelligence, not an audit failure rate | [82] |

Proposed borrower tests (not findings): independent confirmation of bank-detail changes using established contacts; dual approval; reconciliation of claims to actual service or dispensing; checks on referral remuneration and beneficial interests; exception reporting; whistleblowing escalation; audit coverage across subsidiaries and outsourced processes.

### Emerging techniques (Q10 Pass E)

| Technique | Horizon and evidence | Digital weakness; deception; rail | Sector specificity | Interrupting control | Source |
|---|---|---|---|---|---|
| Vendor email compromise | Rolling-year update (July 2026 sentencing on 2023 diversion) | Supplier mailbox compromise; employee impersonation; bank-detail substitution; ACH/wire | Documented sector case | Supplier callback, dual approval, change alerts | [74] |
| Provider-finance impersonation | Rolling-year warning, 25 February 2026 | Emails posing as Provider Finance Department directing to portal activity; credential theft risk | Sector warning; no completed diversion | Phishing-resistant authentication; portal verification | [86] |
| Phishing-service ecosystem | Last 30 days, 14 October 2026 | Court notice of proceedings; allegations | Health-ISAC party to the proceedings; no healthcare loss established | Phishing-resistant authentication | [88] |
| AI-generated voice and video impersonation | Rolling-year general warning, 20 July 2026 | Authority impersonation, fabricated video, voice cloning | Cross-sector warning | Confirmation through established contacts | [87] |
| Payment-processor account takeover | Historical warning, 14 September 2022 | Credentials and social engineering to alter banking instructions; ACH | Healthcare-specific examples | Constrained account recovery; change alerts | [85] |
| Fabricated testing and identities | Last 30 days, indictment 19 October 2026 | Alleged fabricated results and patient information via intermediary; no compromise established | Sector case (alleged) | Claims-to-service reconciliation | [78] |

Not sufficiently evidenced: healthcare instant-payment abuse losses, ERP takeover frequency, a healthcare deepfake-payment case, customer-refund liabilities from synthetic identities.

### Metric dictionary (cyber and resilience)

| ID | Metric | Value | Unit / currency | Period | Population | Statistic | Disclosed or estimate | Comparability group | Source |
|---|---|---|---|---|---|---|---|---|---|
| FIN-01 | Change Healthcare direct response costs | 2.2 | USD billion | FY2024 | One company | Cost | Disclosed | Company-defined | [101] |
| FIN-02 | Change Healthcare business-disruption impacts | 867 | USD million | FY2024 | One company | Estimate by company | Company estimate | Company-defined | [101] |
| FIN-03 | Provider loans | More than 9 | USD billion | Through December 2024 | US care providers | Cash flow (financing) | Disclosed | Liquidity | [101] |
| FIN-04 | Provider loans advanced / repaid | 8,904 / 3,189 | USD million | Nine months to 30 September 2024 | US care providers | Cash flow | Disclosed | Liquidity | [37] |
| FIN-05 | Stryker Q1 2026 adjusted EPS change | -8.5 | % | Q1 2026 | One company | Change | Disclosed | Earnings | [6] |
| FIN-06 | West combined nonrecurring fees | 6.9 | USD million | Q2 2026 | One company | Cost (combined) | Disclosed | Response cost | [16] |
| FIN-07 | Conduent direct response costs | 25 | USD million | Six months to 30 June 2025 | One company | Cost | Disclosed | Response cost | [41] |
| FIN-08 | CNIL fine | 500,000 | EUR | 3 September 2026 | One hospital | Penalty | Disclosed | Regulatory | [30] |
| FIN-09 | ICO fine | 3,076,320 | GBP | 27 March 2025 | One supplier | Penalty | Disclosed | Regulatory | [43] |
| FIN-10 | Ransomware recovery cost excl. ransom | 1.02 | USD million | Fieldwork January-March 2025 | 292 respondents | Average | Survey | Survey | [34] |
| FIN-11 | Median ransom paid | 150,000 | USD | As above | As above | Median | Survey | Survey | [34] |
| FIN-12 | Healthcare data breach cost | 6.64 | USD million | 2026 edition | IBM study | Average | Study (relayed) | Study | [35] [36] |
| FIN-13 | Reports with degraded or interrupted care | 288 of 764 | Count | 2025 | French mandatory reports | Count | Official | National | [33] |
| FIN-14 | HSE applications restored | 99% by day 130 | Share | 2021 | HSE applications | Share | Official audit | Restoration | [103] |
| FIN-15 | WannaCry cancellations | 6,912 identified; over 19,000 estimated | Count | May 2017 | NHS England | Count / estimate | Official audit | Not additive | [104] |
| FIN-16 | Synnovis postponements | 10,152 outpatient; 1,710 elective | Count | 3 June - 22 September 2024 | South-east London | Count (unvalidated) | Official MI | Care disruption | [39] |
| FIN-17 | Healthcare ransomware complaints | 460 | Count | Calendar 2025 | IC3 complainants | Count | Official complaints | Reported complaints | [84] |
| FIN-18 | ENISA health incidents involving ransomware | 116 of 215 (54%) | Count / share | January 2021 - March 2023 | Public reports | Share | Agency analysis | Historical | [99] |

Fraud metrics (ACFE, NHSCFA, IC3 BEC) are listed by dataset type in the report section Operational & Financial Consequences and Credit Transmission and are not repeated here.

## A4 Regulatory Requirements by Jurisdiction

The full register rows REG-01 to REG-22 (instrument, scope, legal status, milestone, obligations, credit relevance, sources) are in the report section Regulatory & Supervisory Resilience Expectations. This module adds milestone typing, applicability limits, the forward horizon and voluntary references.

### Milestone typing and applicability

| ID | Jurisdiction | Legal status | Milestone type and date | Applicability limits |
|---|---|---|---|---|
| REG-01 NIS2 | EU | Directive | Entry into force 16 January 2023; transposition deadline 17 October 2024; CJEU referral 8 July 2026 | National transposition; size thresholds; Annex I versus Annex II |
| REG-02 CER | EU | Directive | Identification deadline 17 July 2026 | Only entities identified by Member States; excludes NIS2-covered matters |
| REG-03 GDPR | EU | Regulation | Application 25 May 2018 | Any controller or processor of health data |
| REG-04 EHDS | EU | Regulation | Entry into force 26 March 2025; main application March 2029 | EHR systems and data holders |
| REG-05 MDR/IVDR | EU | Regulation; MDCG guidance non-binding | In application | Device and IVD manufacturers |
| REG-06 CRA | EU | Regulation | Reporting application 11 September 2026; main application 11 December 2027 | Excludes MDR/IVDR devices |
| REG-07 AI Act amendment | EU | Regulation | Entry into force 27 July 2026; Annex I date 2 August 2028 | AI in regulated products |
| REG-08 UK NIS (health) | England | Regulations | In force; guidance September 2023 | NHS trusts, ICBs, certain independent providers |
| REG-09 DSPT | England | Assurance standard | Submission deadline 30 June 2026 | Organisations with NHS patient data access |
| REG-10 CS&R Bill | UK | Proposal (bill) | Lords Report stage at 14 October 2026 | Not law |
| REG-11 MHRA PMS | Great Britain | Regulations | Application 16 June 2025 | Device manufacturers |
| REG-12 HIPAA Security Rule amendments | US | Proposal | Published 6 January 2025 | Not final at cut-off |
| REG-13 FD&C 524B | US | Statute | Effective 29 March 2023 | Premarket cyber devices |
| REG-14 HPH CPGs | US | Voluntary | Current | Benchmark only |
| REG-15 ECCTA s.199 | UK | Legislation | Commencement 1 September 2025 | Qualifying large organisations; intended-benefit condition; statutory defences |
| REG-16 Bribery Act s.7 | UK | Legislation | Enacted 2010 (commencement instrument not retrieved) | Relevant commercial organisations |
| REG-17 PSR SD20 | UK | Binding direction | Application 7 October 2024 | In-scope PSPs; eligibility and exceptions; GBP 85,000 per claim |
| REG-18 Reg 2024/886 | EU | Regulation | Adopted 13 March 2024; euro-area payee checking 9 October 2025; non-euro 9 July 2027 | Obligations on PSPs; users not regulated |
| REG-19 Dir 2014/24 | EU | Directive (national implementation) | Adopted 26 February 2014 | Covered public procurement only |
| REG-20 Dir 2019/1937 | EU | Directive (national implementation) | Published 26 November 2019; transposition 17 December 2021; private channels 17 December 2023 | Covered EU-law breaches |
| REG-21 31 USC 3729 | US | Federal statute | Text current 9 September 2026 (not commencement) | Government money claims |
| REG-22 42 USC 1320a-7b(b) | US | Federal statute | Text current 10 September 2026 (not commencement) | Federally funded healthcare business; safe harbours |

### Forward monitoring horizon

| Date | Milestone | Why it matters | Evidence |
|---|---|---|---|
| 28 October 2026 | Boston Scientific Q3 results | First quantified effect of the second manufacturer event | [12] |
| Pending | UK Cyber Security and Resilience Bill Royal Assent | UK supplier and managed-service perimeter | [60] |
| Pending | CJEU proceedings on NIS2 and CER transposition | Legal certainty in referred Member States | [46] [48] |
| Pending | Dutch AP decision on Clinical Diagnostics | Possible GDPR penalty for an outsourced laboratory | [29] |
| March 2027 | EHDS implementing acts | EHR security and logging rules | [51] |
| 9 July 2027 | Non-euro-area payee checking under Reg 2024/886 | Payment-fraud control at PSPs | [92] |
| 11 December 2027 | CRA main obligations | Non-device health software security | [53] |
| 2 August 2028 | AI Act obligations for AI medical devices | Deferred high-risk duties | [55] |

### Voluntary and technical references (not binding law)

ISO/IEC 27001 and 27002, ISO 27799, ISO/IEC 27036, IEC 62304, IEC 81001-5-1, IEC 80001-1, ISO 14971, IEC 62443, Health Sector Coordinating Council guidance, NIST Cybersecurity Framework 2.0, CISA guidance and CIS Controls are reference names only; their full texts were not reviewed and no compliance claim is made.

### Legal inventory gaps

UK GDPR and Data Protection Act 2018; UK payee-confirmation directions; complete UK procurement and whistleblowing instruments; EU Member-State criminal and internal-control laws; existing HIPAA Security and Breach Notification Rules; US whistleblower, procurement, issuer internal-control and state-law requirements; US payment-fraud reimbursement treatment; supervisory priority statements.

## A5 Exposure Rating Methodology & Justification

**Rubric status:** none approved; no SHA-256 recorded. All ratings are provisional. **Calibration:** the 24-sector universe was not available; ratings are not calibrated against it. **Convention used (owner-supplied research, section A):** High denotes substantial structural exposure supported by evidence; Very High is not assigned sector-wide without stronger evidence of pervasive, difficult-to-substitute dependencies. These are descriptive conventions, not an approved rubric.

### Rating matrix

| Dimension | Proposed rating | Status | Confidence | Structural drivers (evidence IDs) | Key evidence | Lender consequence | Overlap note | Main gaps |
|---|---|---|---|---|---|---|---|---|
| Fraud | High | Provisional | Medium (capped: investigated-case, complaint and enforcement data only) | 1 Public funding, reimbursement and procurement (FRD-03, FRD-04, [81] [82]); 2 Revenue and incentive complexity (FRD-02, FRD-03); 3 Payment intensity and supplier-payment flows (FRD-01, DEP-10); 4 Intermediaries and agents (FRD-02, FRD-05) | Pharmacy billing admission; Ahold settlement; laboratory referral arrangements; hospital supplier-email diversion | Cash leakage, repayments, settlement expenditure, reduced margins and investment capacity | Credential theft and mailbox compromise counted under Cyber / ICT; impersonation, changed payment instructions and diverted funds counted under Fraud | Geographic imbalance (all cases US); few manufacturer and payer cases; no incidence denominator |
| Cyber / ICT | High | Provisional | Medium | 1 Digital care and transaction workflows (DEP-01, DEP-02, [97]); 2 Internet-facing applications and remote identities (CTL-01, CTL-03, [98] [30]); 3 Shared administration planes and vendors (THR-01, THR-03, [100] [17] [25]); 4 Ransomware targeting of operators (THR-02, [31] [99] [84]) | Official hospital audit; ENISA incident research; Stryker; IC3 complaints | Lost activity, response expenditure, notification costs, claims-processing delay | Access and compromise only; diverted-payment losses not a second full driver | Email authentication, legacy assets, cloud concentration not measured sector-wide |
| Operational Resilience / TPRM | High | Provisional | Medium | 1 Time-sensitive care with limited downtime capacity (INC-05, INC-13); 2 Shared diagnostics (DEP-01, INC-08, INC-11); 3 Claims infrastructure concentration (DEP-02, INC-10); 4 Specialised equipment and component supply (DEP-03, DEP-04, INC-01, INC-04) | Synnovis, Change Healthcare, HSE, WannaCry, Stryker | Delayed collections, backlog costs, inventory shortages, working-capital demand, debt-service pressure | Measures interruption and propagation, not the original intrusion | Supplier shares, tested switching times, representative recovery distributions |
| Governance / Operating Model | High | Provisional | Low | 1 Joint public and private ownership of shared services ([102]); 2 Distributed clinical, technology and network responsibilities (INC-13, INC-14, [103] [104]); 3 Contracting chains and incentive divergence between referral, delivery and reimbursement (FRD-02, FRD-05); 4 Group-wide assurance reach to local applications (CTL-03, [98]) | Synnovis ownership; HSE review; WannaCry review; laboratory contracting arrangements | Remediation costs, slower decisions, disputes, contingent liabilities | Accountability assessed separately from access weakness or fraud loss | No cross-sector complexity dataset; subsidiaries, acquisitions and delegated authority not evidenced |

Preparedness evidence (recoveries, detection, whistleblower routes, restoration milestones) affects confidence and borrower questions, not the drivers.

### Subsector variation

- [Owner-supplied Q10-Q15 research, section C] Hospitals, diagnostic networks and integrated systems can warrant a Very High resilience assessment at borrower level where essential dependencies cannot be substituted within operational tolerances; the sector evidence does not establish that for every organisation.
- Laboratories and pharmacies carry the strongest documented reimbursement-fraud evidence.
- Pharmaceutical and medical-technology businesses need separate analysis of production, research, distribution and product dependencies; hospital findings are not a substitute.
- Small single-site providers may have less organisational complexity but concentrated reliance on a few external systems.

### Cyber / ICT subsector interpretation (Q11)

| Subsector | Principal dependency | Evidence limitation |
|---|---|---|
| Hospitals and community care | Records, prescribing, diagnostics, scheduling, communications, downtime workflows | No representative asset inventory or tested offline-capacity measure |
| Diagnostics | Laboratory systems, sample tracking, result delivery | Synnovis is one shared-service example, not a global concentration estimate |
| Pharmacies and distribution | Dispensing, eligibility, reimbursement, ordering | Outage and account-control measures missing |
| Pharmaceuticals and biotechnology | Research data, contract operations, manufacturing, distribution | Hospital ransomware data cannot quantify manufacturing exposure |
| Medical technology | Enterprise administration, production, orders, distribution, product support | Product compromise must be distinguished from internal network disruption |
| Payers and transaction infrastructure | Claims, eligibility, provider payments, information exchange | Entity counts, market shares and rerouting times missing |

### Governance evidence (Q13)

| Label | Evidence | What it establishes | Source |
|---|---|---|---|
| Confirmed: joint ownership | Synnovis co-owned by two NHS foundation trusts and SYNLAB | Documented public and private joint-service model; not weak governance by itself | [102] |
| Historical official finding | Network trust enabled access between connected entities; better monitoring elsewhere limited consequences | Shared technology crosses organisational boundaries | [103] |
| Historical official finding | No formal mechanism to check local compliance with advice; untested local response plan | A specific historical assurance gap | [104] |
| Allegation and confirmed settlement | Referral payments allegedly concealed through contracts and certifications | Documentary approvals alone do not establish economic substance | [75] |
| Confirmed audit finding | Application testing exposed authentication and validation weaknesses despite other safeguards | A framework is not the same as effective application controls | [98] |

### Rating sensitivity: what would change each rating

| Dimension | Evidence for a higher rating | Evidence for a lower rating |
|---|---|---|
| Fraud | Representative evidence of pervasive high-value public and supplier flows, more intermediary dependence, broader subsector cases | Simpler payment and reimbursement models; limited exposure to relevant flows (stronger controls change preparedness, not inherent exposure) |
| Cyber / ICT | Pervasive unsupported assets, exposed remote administration, unusually broad connected dependency | Material activities can function with limited network and application dependence |
| Resilience / TPRM | Essential services with no practicable substitute within tolerances, supported by tested capacity and switching evidence | Demonstrated substitutability, available capacity, usable inventories, tolerable interruption windows |
| Governance | Representative evidence of more layered ownership and fragmented responsibility than peers | Representative evidence of simpler structures and fewer material interfaces |

Borrower evidence priorities: process-level revenue and cash dependency maps; supplier and technology concentration; alternative-routing tests; clinical downtime capacity; supplier-payment change records; claims reconciliation; referral contracts; delegated authorities; group and local accountability.

## A6 Questionnaire-Control-to-Threat Mapping

**Status: provisional.** No questionnaire supplied; PROV- identifiers are generic and must be replaced with actual question IDs when a questionnaire is supplied. No borrower answers are held.

| ID | Control area | Linked registers | Follow-up questions (non-technical) | Practical improvement | Escalation indicator |
|---|---|---|---|---|---|
| PROV-01 | Identity and administration planes | THR-01, CTL-02, DEP-07, REG-01 | Who can change many systems at once, and what second approval applies? Is MFA phishing-resistant for administrators? | Privileged-access separation; approval for mass actions | Identity-campaign alert; supplier outage linked to admin tooling |
| PROV-02 | Single-source products and stock | THR-04, DEP-03, DEP-04, SCN-02 | Which products have one supplier? How many days of stock exist? | Single-source map with buffer days; consigned stock | National supply notice; supplier Item 1.05 filing |
| PROV-03 | Outsourced clinical services | THR-04, CTL-04, DEP-01, INC-08, INC-11 | Which laboratory could replace the main one, with what capacity? Has the switch been tested? | Independent assurance; exercised substitution | Inspectorate finding; service suspension |
| PROV-04 | Vendor accounts and APIs | THR-03, CTL-05, DEP-06, REG-03 | Which vendors hold patient data, and how is bulk access monitored? | Scoped credentials; rate limits; alerts | Vendor breach disclosure |
| PROV-05 | Remote access and detection | THR-03, CTL-01, INC-09, INC-15 | Is every remote route protected by MFA? How fast are alerts acted on? | MFA on all remote clinical access; real-time alerting | Regulator fine citing MFA |
| PROV-06 | Restoration and downtime | THR-02, CTL-06, CTL-07, INC-05, INC-13, SCN-01 | When was restoration last tested, and how long did it take? How long can paper operation run? | Isolated backups; downtime drills | Diversion notices; prolonged paper operation |
| PROV-07 | Claims and revenue cycle | DEP-02, INC-10, SCN-03 | What share of receipts runs through one platform? What bridging is available? | Alternative clearing; contingency funding | Processor disclosure; payer advance programme |
| PROV-08 | Regulatory status tracking | REG-01 to REG-22 | Which rules apply now, which are transitional, which are proposals? | Quarterly register review | Royal Assent; CJEU ruling |
| PROV-09 | Supplier bank-detail changes | THR-05, CTL-08, FRD-01, DEP-10, REG-17, REG-18 | Who approves a change to supplier bank details, and how is it confirmed? | Callback through established contacts; dual approval; change alerts | Confirmed diversion; impersonation alert |
| PROV-10 | Claims integrity and referrals | CTL-09, FRD-02 to FRD-05, REG-21, REG-22, REG-16 | How are claims reconciled to services delivered? How are referral payments reviewed? | Reconciliation and exception reporting; beneficial-interest checks | Settlement, plea, indictment or civil investigative demand |
| PROV-11 | Whistleblowing and group assurance | FRD-03, CTL-07, REG-15, REG-20 | Do reporting channels and internal audit reach subsidiaries and outsourced processes? | Group-wide audit plan; escalation route | Whistleblower action; audit-office finding |

## A7 Confidence, Assumptions, Sources & Methodology

**Research mode and origin mix.** Q01-Q07: Claude research, 73 sources (S-001 to S-073), accessed 15 October 2026, cut-off 14 October 2026, recorded in the source-edition register (healthcare/2025-09_2026-10_v2/02_source_register.csv). Q10-Q15: owner-supplied research file dated 27 October 2026 (SHA-256 b9fb9d3a34761d2febba3ddcf3669db1957739abff3ea8b2a170fe7bbc8f78c9), 33 additional sources (S-074 to S-106). Silobreaker: none. Gap fill: none.

**Tracing results.** S-001 to S-073: primary, traced in the source edition. S-074 to S-106: accepted as supplied on the owner's instruction (27 October 2026), not re-traced in this run. Two supplied citations were not used to support findings: a Tier 3 media lead each for the Florida health system settlement and the Queens pharmacy scheme. One supplied citation for the Singh orthotic case points to an unrelated DOJ release about a US Attorney resignation, so the Singh case is not described.

**Unconfirmed items (annex only or labelled).** Illinois laboratory charges (FRD-05); Labtech settled allegations; Ahold underlying conduct; Handala attribution of Stryker; device-wiping descriptions; AZ Monica impact detail (Tier 3); Synnovis-linked death reports (not used).

**Scenario assumptions.** SCN-01 to SCN-03 assume one affected operator, supplier or platform, normal demand and no pre-arranged alternative unless stated; no named borrower, probability or loss amount is assumed. The source-edition scenarios SC-001 to SC-003 (common dependency, targeted disruption, supply-chain concentration) are re-expressed as the 8-week, 1-week and 4-week bands respectively.

**Temporal classification.** Current (2026): most incident, enforcement and regulatory sources. H2 2025: [77] [102] and several source-edition items. Contextual or historical (older than 18 months, retained for structural lessons or legal background): [37] [38] [39] [43] [79] [80] [85] [89]-[96] [99] [101] [103] [104].

### Source register summary by tier

| Tier | Source-edition (S-001 to S-073) | Owner-supplied (S-074 to S-106) | Use |
|---|---|---|---|
| Tier 1 | 56 | 29 | Material findings, rating drivers, metrics |
| Tier 2 | 3 | 2 (ACFE) | Benchmarks with disclosed method |
| Tier 3 | 14 | 2 | Context and leads only |

### Owner-supplied sources (S-074 to S-106)

| S- ID | Label | Publisher | Published | Observation period; geography | Tier | Locator |
|---|---|---|---|---|---|---|
| S-074 | DOJ NDGA - Children's Healthcare of Atlanta laundering sentence | US Department of Justice, Northern District of Georgia | 2026-07-23 | June 2023 transfer; February and July 2026 proceedings; US | 1 | narrative and sentencing paragraphs |
| S-075 | DOJ - Labtech plea and settlement | US Department of Justice, Office of Public Affairs | 2026-01-07 | 2016 and 2018-2021 conduct; 2026 agreements; US | 1 | agreement, conduct and whistleblower paragraphs |
| S-076 | DOJ - Ahold Delhaize USA settlement | US Department of Justice, Office of Public Affairs | 2026-06-10 | Earlier pricing conduct; settlement 2026; US | 1 | pricing, resolution, qui tam and liability paragraphs |
| S-077 | DOJ NJ - Paterson pharmacy owner plea | US Department of Justice, District of New Jersey | 2025-11-24 | December 2019 - December 2021; plea 19 November 2025; US | 1 | According to documents paragraphs |
| S-078 | DOJ - Illinois laboratory owner indictment | US Department of Justice, Office of Public Affairs | 2026-10-20 | May 2021 - April 2022 conduct; indictment 19 October 2026; US | 1 | court-document narrative and presumption-of-innocence paragraph |
| S-079 | ACFE - Occupational Fraud 2024 | Association of Certified Fraud Examiners | 2024 | Cases investigated January 2022 - September 2023; Global | 2 | introduction p.7; industry statistical table p.51 |
| S-080 | ACFE - Occupational Fraud 2024 release | Association of Certified Fraud Examiners | 2024 | 1,921 cases, 2024 edition; Global | 2 | release body |
| S-081 | NHSCFA - Strategic Intelligence Assessment 2026 | NHS Counter Fraud Authority | 2026 | Funding 2025-2026; reports April 2025 - March 2026; England | 1 | Introduction, financial-vulnerability and reporting paragraphs |
| S-082 | NHSCFA - SIA procurement and commissioning | NHS Counter Fraud Authority | 2026 | 2025-2026 assessment; England | 1 | procurement and commissioning section |
| S-083 | NHSCFA - SIA vulnerability method | NHS Counter Fraud Authority | 2026 | 2025-2026 assessment; England | 1 | calculation method section |
| S-084 | FBI IC3 - 2025 Internet Crime Report | Federal Bureau of Investigation, Internet Crime Complaint Center | 2026 | Calendar 2025; US reporting population | 1 | pp.7-8, 14 and 16 |
| S-085 | FBI IC3 - Healthcare payment processor warning 2022 | Federal Bureau of Investigation | 2022-09-14 | Examples 2018-2022; US | 1 | PDF p.2, examples and indicators |
| S-086 | Texas HHSC - QIPP provider phishing alert | Texas Health and Human Services Commission | 2026-02-25 | February 2026; Texas, US | 1 | opening and phishing description |
| S-087 | FBI IC3 - Impersonation PSA July 2026 | Federal Bureau of Investigation, Internet Crime Complaint Center | 2026-07-20 | Ongoing scheme; General population, US | 1 | AI-generated video and protective-advice sections |
| S-088 | Microsoft DCU - YAM, CoGUI and Iron Man pleadings | Microsoft Digital Crimes Unit | 2026-10-14 | 2026 civil proceedings; US court; international activity alleged | 1 | Civil Action 1:26-cv-26998-JEM; pleadings and court-order index |
| S-089 | UK legislation - ECCTA 2023 s.199 | legislation.gov.uk | 2023 | Commenced 1 September 2025; UK | 1 | s.199 with ss.201-202; commencement information |
| S-090 | UK legislation - Bribery Act 2010 | legislation.gov.uk | 2010 | Enacted 2010; UK | 1 | s.7 and associated-person provisions |
| S-091 | PSR - Specific Direction 20 | Payment Systems Regulator | 2024-07 | Applies from 7 October 2024; UK | 1 | para.3.2; PS24/7 |
| S-092 | EUR-Lex - Regulation (EU) 2024/886 | Official Journal of the European Union | 2024-03-13 | Staged application 2025-2027; EU | 1 | Article 5c |
| S-093 | EUR-Lex - Directive 2014/24/EU | Official Journal of the European Union | 2014-02-26 | Adopted 26 February 2014; EU | 1 | Articles 24 and 57 |
| S-094 | EUR-Lex - Directive (EU) 2019/1937 | Official Journal of the European Union | 2019-11-26 | Transposition 2021-2023; EU | 1 | internal-reporting provisions; transposition dates |
| S-095 | US Code - 31 USC 3729 | Office of the Law Revision Counsel, US House of Representatives | 2026-09-09 | Text current to 9 September 2026; US | 1 | section 3729(a)(1) |
| S-096 | US Code - 42 USC 1320a-7b | Office of the Law Revision Counsel, US House of Representatives | 2026-09-10 | Text current to 10 September 2026; US | 1 | section 1320a-7b(b) |
| S-097 | HHS OIG - Southeastern hospital audit | HHS Office of Inspector General | 2026-01 | Audit testing period not established; US | 1 | report summary |
| S-098 | HHS OIG - Audit report A-18-22-08021 | HHS Office of Inspector General | 2026-01 | Audit testing period not established; US | 1 | highlights and findings |
| S-099 | ENISA - Health Threat Landscape 2023 | European Union Agency for Cybersecurity | 2023-07 | January 2021 - March 2023; EU and neighbouring countries | 1 | methodology and section 2.1 |
| S-100 | CISA - Endpoint management hardening alert | Cybersecurity and Infrastructure Security Agency | 2026-03-18 | March 2026; US and global | 1 | opening and hardening recommendations |
| S-101 | UnitedHealth - Form 10-K FY2024 | UnitedHealth Group (SEC) | 2025 | FY ended 31 December 2024; US | 1 | p.24, Change Healthcare Cyberattack |
| S-102 | NHS England - Synnovis questions and answers | NHS England | 2025-11-10 | Attack June 2024; services restored December 2024; UK | 1 | Q1-Q2 |
| S-103 | C&AG Ireland - HSE cyber attack financial impact | Office of the Comptroller and Auditor General, Ireland | 2022 | May - September 2021; Ireland | 1 | Chapter 12, Figure 12.2 and conclusions |
| S-104 | NAO - WannaCry investigation | National Audit Office | 2017-10-27 | May 2017; England | 1 | key findings on scope, cancellations, preparation and response |
| S-105 | Bloomberg Law - Florida health system settlement | Bloomberg Law | 2026-08-27 | 2026; US | 3 | lead only |
| S-106 | Yahoo News - Queens pharmacy scheme | Yahoo News | 2026-10-12 | 2026; US | 3 | lead only |

Full URLs and access basis are in the report References. No URL-level or locator-level checks were run on S-074 to S-106 in this edition.
