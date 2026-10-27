# Healthcare - Sector Cyber Resilience & Credit Intelligence Report

**Edition:** 2026-10. **Version:** 2.0 (research document; supersedes the seven-slide edition 1.1 of 25 October 2026 and the migrated deck 1.1-M of 26 October 2026 as the Healthcare research record). **Reporting period:** 1 September 2025 - 27 October 2026. **Evidence cut-off:** composite - Q01-Q07 evidence as of 14 October 2026 (source edition, not refreshed); Q10-Q15 evidence as of 27 October 2026 (owner-supplied research). **Geography:** Worldwide, with EU, UK and US analysis. **Audience:** Senior Credit Officers; annex for analysts and second-line review. **Research mode:** Claude research (Q01-Q07, 15 October 2026) merged with owner-supplied research for Q10-Q15 (27 October 2026). **Rating status:** provisional - no approved rubric. **Questionnaire mapping:** provisional - no questionnaire supplied. **Classification:** not specified by owner.

**Boundary:** public external evidence only. This report rates inherent sector exposure. It is not a cybersecurity audit, a compliance assessment or a borrower credit rating. No internal, client, patient or bank-specific information is used or implied. No leaked dataset, leak-site content or personal health information was accessed or reproduced.

**Evidence labels:** Observed (external fact from a named source), Benchmark (sector statistic with stated population), Proxy (indirect measure), Judgement (analytical judgement), Assumption (scenario assumption), Rating proposal, Unconfirmed (allegation or charge not decided). Each statement is preceded by its reference in the form [Source - Title][n]. References [1]-[73] are the source-edition sources (S-001 to S-073); references [74]-[106] come from the owner-supplied Q10-Q15 research (S-074 to S-106) and were accepted as supplied on the owner's instruction, without re-tracing in this run.

**Scope of this document.** It answers the full research library: Q01-Q07 (core sector intelligence), Q10-Q14 (classification evidence, including the full fraud screen), Q15 (four-dimension classification), Q08 (provisional questionnaire mapping) and Q09 (assembly). No slide deck is produced in this run, at the owner's request.

## Executive Sector Assessment

### Four-dimension exposure classification

[Owner-supplied Q10-Q15 research, sections B and C] Rating proposal: all four dimensions are proposed as High. Every rating is provisional because no approved rating rubric exists, and no 24-sector calibration was available.

| Dimension | Proposed rating | Status | Confidence | One-line justification |
|---|---|---|---|---|
| Fraud | High | Provisional | Medium | [DOJ - Ahold Delhaize USA settlement][76] [DOJ - Labtech plea and settlement][75] [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] Public reimbursement, complex pricing and claims, supplier-payment flows and referral intermediaries create several routes to loss; dominant typologies are false billing and claims fraud, referral kickbacks (non-cyber) and supplier payment diversion (hybrid). |
| Cyber / ICT | High | Provisional | Medium | [HHS OIG - Southeastern hospital audit][97] [ENISA - Threat Landscape 2026][31] [Stryker - Form 8-K/A April 2026][1] Care delivery, diagnostics and transactions depend on connected systems; internet-facing applications, remote identities and shared administration planes form the access surface. |
| Operational Resilience / TPRM | High | Provisional | Medium | [UnitedHealth - Form 10-K FY2024][101] [NHS England - Synnovis questions and answers][102] [NHS England - Stryker supply disruption letter][3] Shared diagnostics, claims infrastructure and specialised equipment supply transmit disruption between organisations; manufacturer outages lasted 14-21 days, while UK stock of Stryker products was estimated on day 7 to last about two more weeks. |
| Governance / Operating Model | High | Provisional | Low | [NHS England - Synnovis questions and answers][102] [C&AG Ireland - HSE cyber attack financial impact][103] [DOJ - Labtech plea and settlement][75] Joint ownership, distributed clinical and technology responsibilities and contracting chains complicate accountability; representative sector-wide measures are absent, so confidence is Low. |

[Owner-supplied Q10-Q15 research, section C] Judgement: the Fraud / Cyber overlap is split as follows - credential theft and mailbox compromise count under Cyber / ICT; impersonation, changed payment instructions and diverted funds count under Fraud; neither piece of evidence is used as a full driver in both dimensions. Cyber-enabled and hybrid fraud (supplier email compromise, payment diversion, provider-portal phishing) is a minority of the documented fraud record; non-cyber fraud (false billing, pricing, referral kickbacks, fabricated tests) dominates the selected cases.

### Principal findings

1. **Liquidity transmission through shared transaction infrastructure is the most consequential lender channel (Judgement; confidence Medium-High).** [UnitedHealth - Form 10-K FY2024][101] Observed: the Change Healthcare attack (February 2024) led to more than USD 9 billion of interest-free provider loans through December 2024, alongside USD 2.2 billion of direct response costs and USD 867 million of estimated business-disruption impacts for FY2024. [UnitedHealth - Q3 2024 results release][37] Observed: USD 8,904 million had already been advanced by 30 September 2024. These are financing support and company costs, not provider losses, and they are not added together. What would change it: evidence that providers can reroute claims within days through pre-arranged alternatives.
2. **Supplier and manufacturer outages were the most publicly evidenced care-continuity channel in 2026 (Judgement; confidence Medium).** [Stryker - Form 8-K/A April 2026][1] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [West Pharmaceutical - Form 8-K May 2026][15] Three manufacturers filed material cybersecurity incident reports between March and September 2026, each describing global disruption to manufacturing, ordering or shipping. Competing explanation: listed manufacturers have mandatory disclosure duties, so this pathway may be over-represented. What would change it: disclosure of provider-originated disruptions of comparable breadth.
3. **Outsourced diagnostics turn a single supplier failure into multi-provider disruption (Judgement; confidence Medium-High).** [NHS England - Synnovis questions and answers][102] [BVO Nederland - Annual report 2025][28] Synnovis (London, June 2024) and the Dutch screening laboratory breach (July 2025, consequences to 2026) show that the loss of one laboratory reduces capacity for several providers or a national programme, with restoration measured in months.
4. **Fraud exposure is structural and mostly non-cyber, concentrated in reimbursement-driven subsectors (Judgement; confidence Medium).** [DOJ NJ - Paterson pharmacy owner plea][77] [DOJ - Ahold Delhaize USA settlement][76] [DOJ - Illinois laboratory owner indictment][78] Documented cases cluster in pharmacies and laboratories (false claims, pricing, fabricated tests, referral payments). [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] The documented hybrid route is supplier email compromise leading to a bank-detail change (USD 5.3 million transferred, about USD 4 million recovered). [NHSCFA - Strategic Intelligence Assessment 2026][81] For England, NHSCFA estimates GBP 1.301 billion of NHS funding vulnerable to fraud, bribery and corruption in 2025-2026 (0.66% of GBP 198.095 billion), an estimate of vulnerability, not realised loss.
5. **EU maturity remains below sector importance, and the legal perimeter is uneven (Judgement; confidence Medium).** [ENISA - NIS360 2026][32] ENISA placed health in its "risk zone" in May 2026. [European Commission - NIS2 CJEU referral][46] Four Member States were referred to the Court of Justice on 8 July 2026 for incomplete NIS2 transposition. [UK Parliament - Cyber Security and Resilience Bill][60] The UK reform remained a bill at 14 October 2026, and [Federal Register - HIPAA Security Rule NPRM][63] the US HIPAA Security Rule update remained a proposal.

### Top risks for lenders

| Risk | Mechanism | Lender channel | Evidence |
|---|---|---|---|
| Claims and payment platform outage | Shared clearing or eligibility platform stops | Provider receipts delayed; bridging finance demand; working-capital strain | [UnitedHealth - Form 10-K FY2024][101] |
| Manufacturer or component supplier outage | Production, ordering and shipping halt for two to three weeks | Supplier revenue deferral and guidance changes; provider procedure deferral | [Stryker - Q1 2026 results release][6] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] |
| Outsourced diagnostic failure | Laboratory loss with little spare capacity elsewhere | Lost activity income; backlog costs; contract disputes | [NHS England - Synnovis questions and answers][102] [BVO Nederland - Annual report 2025][28] |
| Reimbursement and referral fraud | False claims, pricing, kickbacks | Settlements, repayments, unsustainable revenue | [DOJ - Ahold Delhaize USA settlement][76] [DOJ - Labtech plea and settlement][75] |
| Supplier payment diversion | Supplier mailbox compromise and bank-detail change | Direct cash loss; capital expenditure funding exposed | [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] |
| Data exposure through vendors | Credential and API misuse | Notification cost, fines, litigation | [Cegedim Sante - Statement 4 March 2026][17] [EDPB - CNIL fine on Hopital Prive de la Loire][30] |

### Threat direction

[ANS CERT Sante - Observatory 2025][33] Judgement (confidence Low-Medium): in the French reporting population, ransomware incidents fell 30% in 2025 while messaging-account compromise made up 50% of system-compromise vectors, indicating a shift from encryption towards account abuse. [Stryker - Form 8-K/A April 2026][1] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [West Pharmaceutical - Form 8-K May 2026][15] Judgement (confidence Low): disruption of manufacturers is rising in public disclosure in 2026, with three material filings in six months; disclosure rules may explain part of this. [FBI IC3 - 2025 Internet Crime Report][84] Benchmark: healthcare and public health recorded 460 ransomware complaints in calendar 2025, the highest count among the sectors shown; this is a reporting count, not an incidence rate. [FBI IC3 - Impersonation PSA July 2026][87] [Microsoft DCU - YAM, CoGUI and Iron Man pleadings][88] Judgement: AI-enabled impersonation and phishing-service ecosystems are an emerging fraud technique; no healthcare deepfake-payment loss is documented in the evidence.

### Credit discussion implications

[Owner-supplied Q10-Q15 research, section B] Judgement: the most useful borrower questions are which services and receipts stop if the principal technology or supplier fails; how long cash generation and clinical activity can continue; whether alternatives have been exercised; who independently authorises supplier bank-detail changes; and who owns risks shared between clinical teams, finance, subsidiaries and external providers. The evidence does not support a worldwide incident probability or a uniform Very High classification across subsectors.

### What changed against the prior edition

| Change | Effect |
|---|---|
| Q10 fraud screen, five fraud cases, fraud metrics and fraud rules added | Fraud is now rated (High, provisional, Medium) instead of not assessable |
| Q11-Q14 evidence added (ICT exposure, five operational disruptions, governance, cross-sector) | Governance is now rated (High, provisional, Low); cross-sector comparison provided within datasets only |
| Change Healthcare FY2024 figures added | Full-year cost and loan programme supersede the nine-month figures as the latest disclosure |
| Historical landmarks (HSE 2021, WannaCry 2017, Synnovis 2024) documented from primary audits | Historical top five and three case studies now complete |
| Q01-Q07 evidence | Unchanged at the 14 October 2026 cut-off; Q07 remains partial |

### Classification evidence by dimension (Q10-Q14 summary)

Full drivers, evidence, sensitivity and gaps are in Annex A5; fraud detail is in the financial consequences section and Annex A3.

**Fraud (Q10).** [NHSCFA - SIA procurement and commissioning][82] [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] [DOJ - Ahold Delhaize USA settlement][76] Judgement: material typologies are false billing and reimbursement fraud, referral kickbacks and corruption, invoice and procurement fraud, supplier and executive impersonation, payment diversion and business email compromise, with identity fraud material in laboratories, pharmacies and payers. Synthetic identities are not evidenced. Structural drivers are public reimbursement and procurement, revenue and incentive complexity, payment volume and urgency, and intermediaries in laboratory and referral models.

**Cyber / ICT (Q11).** [HHS OIG - Southeastern hospital audit][97] [ENISA - Health Threat Landscape 2023][99] [CISA - Endpoint management hardening alert][100] Judgement: digital dependency is inherent across subsectors; the attack surface includes internet-facing applications, remote identities and shared administration tools. One hospital audit cannot establish sector maturity. The cyber-enabled fraud surface (supplier mailboxes, provider-finance portals, payment-processor accounts) is documented by cases and warnings, but sector email-authentication posture and executive data exposure are not measured.

**Operational Resilience / TPRM (Q12).** [UnitedHealth - Form 10-K FY2024][101] [NHS England - Synnovis questions and answers][102] [C&AG Ireland - HSE cyber attack financial impact][103] [NAO - WannaCry investigation][104] [NHS England - Stryker supply disruption letter][3] Judgement: five documented disruptions (Change Healthcare, Synnovis, HSE, WannaCry, Stryker) show propagation through transactions, diagnostics, networks and equipment supply, with restoration from about three weeks (Stryker) to 130 days (HSE applications) and about six months (Synnovis services). Supplier shares, tested switching times and representative recovery distributions are missing. Third-party fraud runs through supplier email and bank-detail changes (Children's Healthcare of Atlanta) and through intermediaries in laboratory referral and specimen-collection chains (Labtech, Illinois laboratory, alleged).

**Governance / Operating Model (Q13).** [NHS England - Synnovis questions and answers][102] [C&AG Ireland - HSE cyber attack financial impact][103] [NAO - WannaCry investigation][104] [DOJ - Labtech plea and settlement][75] [HHS OIG - Audit report A-18-22-08021][98] Judgement: joint public and private ownership, network trust across organisations, a historical assurance gap (WannaCry), referral incentives hidden in contracts, and the gap between having a framework and having effective application controls are the documented mechanisms. [UK legislation - ECCTA 2023 s.199][89] Qualifying healthcare bodies in the UK are exposed to the failure-to-prevent-fraud offence from 1 September 2025. Typical subsidiary counts, acquisition-related fragmentation, internal audit coverage and restatement rates are not evidenced, hence Low confidence.

**Cross-sector comparison (Q14).** Comparisons are made only within one dataset and edition. No combined ranking or synthetic score is produced.

| Dimension | Dataset type | Healthcare | Comparators in the same dataset | Permitted interpretation | Evidence |
|---|---|---|---|---|---|
| Fraud | Investigated cases (ACFE 2024 edition; cases January 2022 - September 2023; global) | Median loss USD 100,000; n=112 | Manufacturing USD 267,000 (n=174); insurance USD 190,000 (n=68); retail USD 48,000 (n=78); education USD 50,000 (n=68) | Healthcare median is below manufacturing and insurance and above retail and education among investigated cases; not a ranking of exposure or incidence | [ACFE - Occupational Fraud 2024][79] |
| Cyber / ICT | Reported complaints (FBI IC3, calendar 2025) | 460 ransomware complaints | Manufacturing 355; financial services 258; information technology 232 | Highest count in this dataset; no adjustment for organisations, size or reporting propensity; not a probability | [FBI IC3 - 2025 Internet Crime Report][84] |
| Resilience / TPRM | Company disclosures and official records | Change Healthcare, Synnovis, Stryker | No matched disruption-duration or loss dataset for energy, transport or finance | Cross-sector rank not assessable | [UnitedHealth - Form 10-K FY2024][101] |
| Governance | None available | - | - | No defensible comparative rank | - |

[Owner-supplied Q10-Q15 research, section E5] Judgement: healthcare adds patient and provider identity, medical-necessity and reimbursement-price complexity to generic supplier-payment fraud exposure; clinical providers combine information dependence with time-sensitive service delivery; delayed care and payment-processing interruption create distinct propagation channels. The evidence does not show that healthcare has higher fraud frequency than finance, retail or manufacturing, higher compromise probability than all peers, or uniformly higher resilience exposure than utilities, transport or financial infrastructure. The 24-sector universe was not available, so ratings are not calibrated against it.

## Sector Operating Model & Dependencies

### Subsector map

[Owner-supplied Q10-Q15 research, section A] The sector boundary used throughout is below. General-purpose technology suppliers are assessed as dependencies, not counted as healthcare organisations; healthcare-specific transaction infrastructure is included. [CCB - NIS2 scope visual][45] Observed: under NIS2, healthcare providers, EU reference laboratories, medicinal-product research and basic pharmaceutical manufacturing sit in the health sector, while medical-device and IVD manufacturers sit in the manufacturing sector.

| Subsector | Included business models | Essential processes | Principal dependency to investigate | Evidence in this edition |
|---|---|---|---|---|
| Hospitals and integrated systems | Public, charitable and commercial hospitals; hospital-owned networks | Admission, surgery, emergency care, records, prescribing | EHR, laboratory, imaging, scheduling, communications, clinical downtime workflows | [ANS CERT Sante - Observatory 2025][33] [Belgian Chamber - Committee record 3 February 2026][23] [HHS OIG - Audit report A-18-22-08021][98] |
| Ambulatory and community care | Primary care, dental, outpatient surgery, mental health, home health, long-term care | Consultations, prescribing, referrals | Practice software, e-prescribing, claims | [Cegedim Sante - Statement 4 March 2026][17] |
| Diagnostics | Pathology, laboratories, imaging, screening | Sample tracking, result delivery | Laboratory information systems, connected hospitals | [NHS England - Synnovis questions and answers][102] [BVO Nederland - Annual report 2025][28] |
| Pharmacies and distribution | Retail and hospital pharmacies; wholesalers | Dispensing, eligibility, reimbursement, ordering | Claims processors, ordering platforms | [McKesson - Form 8-K August 2026][24] [DOJ NJ - Paterson pharmacy owner plea][77] |
| Pharmaceuticals and biotechnology | Research-led and generic manufacturers; contract research and manufacturing; components | Research, manufacturing, distribution | Production systems, packaging and component supply | [West Pharmaceutical - Form 8-K May 2026][15] |
| Medical technology | Devices, IVD, implants, connected products | Production, orders, distribution, product support | Enterprise identity and endpoint administration, remote monitoring | [Stryker - Customer updates on network disruption][2] [Boston Scientific - Cyber update 8 September 2026][13] |
| Payers and transaction infrastructure | Insurers, managed care, pharmacy benefit management, claims, eligibility | Claims adjudication, provider payment | Clearing houses and processors | [UnitedHealth - Form 10-K FY2024][101] [Conduent - Form 10-Q Q2 2026][41] |

[ENISA - NIS360 2026][32] Observed: ENISA reports that healthcare providers struggle more than pharmaceutical manufacturers with best practice, citing budgets and skilled staff. Telehealth is not separately evidenced: a targeted search in the source edition found no in-scope incident with a disclosed outcome.

### Key IT and OT systems

[HHS OIG - Southeastern hospital audit][97] Observed: the HHS Office of Inspector General (OIG) describes increasing reliance on technology for care, telemedicine and records. [Stryker - Customer updates on network disruption][2] Observed: Stryker distinguished internal enterprise disruption from product safety and stated that connected products remained safe. [Boston Scientific - Cyber update 8 September 2026][13] Observed: Boston Scientific temporarily could not activate new LATITUDE remote cardiac monitoring. Judgement: the observed failure points are enterprise identity, endpoint administration, EHR and laboratory systems, ordering and shipping, and claims platforms, rather than clinical devices themselves.

### Dependency and concentration matrix

| ID | Essential process | Dependency and evidence anchor | Propagation | Substitutability and switching evidence | Structural assessment |
|---|---|---|---|---|---|
| DEP-01 | Clinical diagnostics | [NHS England - Synnovis questions and answers][102] [BVO Nederland - Annual report 2025][28] Shared pathology provider; national screening laboratories | Laboratory loss delays decisions, procedures and throughput across client organisations | [BVO Nederland - Annual report 2025][28] Dutch substitutes ran at about 150% of capacity for six months, then invitations were halved; no general alternate-laboratory activation time exists | High sensitivity where spare capacity is constrained |
| DEP-02 | Claims and cash collection | [UnitedHealth - Form 10-K FY2024][101] Shared processing infrastructure | Claims delay affects receipts, working capital and provider funding | No representative rerouting-time dataset | High cash-flow sensitivity |
| DEP-03 | Medical equipment supply | [NHS England - Stryker supply disruption letter][3] Manufacturer production and distribution | Order and shipping failure affects scheduled procedures and stock | UK stock about two weeks at day 7 of the Stryker outage; substitutes need suitability, training and procurement time | High for specialised products; not universal |
| DEP-04 | Pharmaceutical components | [West Pharmaceutical - Cyberattack updates][73] Packaging and delivery-device manufacturer | Upstream input to medicine manufacturers | Downstream effect not disclosed | Observed upstream; downstream unknown |
| DEP-05 | Integrated clinical network | [C&AG Ireland - HSE cyber attack financial impact][103] National health network | Trusted connections transmit compromise or force protective disconnection | Better monitoring at some connected entities limited consequences | High shared-network exposure; preparedness varies |
| DEP-06 | Clinical software and records | [Cegedim Sante - Statement 4 March 2026][17] [Veradigm - Form 8-K September 2026][25] Practice software; EHR vendor API | One vendor exposes many practices' data | Not assessed | Concentration by vendor market share not measured |
| DEP-07 | Enterprise identity and endpoint administration | [CISA - Endpoint management hardening alert][100] [Stryker - Customer updates on network disruption][2] | One administrative plane reaches many endpoints | Hardening is preparedness | Broad reach where shared |
| DEP-08 | Cloud and managed services | [ENISA - NIS360 2026][32] Candidate infrastructure dependency; one managed-service compromise can reach many hospitals | Common platform outage affects several applications or providers | Healthcare-specific provider shares and tested failover absent | Concentration not assessable quantitatively |
| DEP-09 | Medicines and consumables | Candidate supply dependency | Production or logistics interruption constrains treatment | No supplier-share, inventory or switching dataset | Borrower-specific assessment required |
| DEP-10 | Supplier-payment administration | [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] Vendor identity and payment master data | Compromised supplier communications redirect legitimate payments | Bank-detail confirmation can interrupt the chain | Fraud channel, not service-outage concentration |

[Owner-supplied Q10-Q15 research, section E3] Judgement: one supplier is not sufficient evidence of Very High exposure. The decisive questions are how essential the service is, whether alternatives have usable capacity, and whether switching can occur before operational or liquidity tolerances are exceeded.

### Single points of failure and cross-sector concentration

[NHS England - Stryker supply disruption letter][3] [BVO Nederland - Annual report 2025][28] [UnitedHealth - Q3 2024 results release][37] Judgement: documented single points of failure are a sole manufacturer for specialised implants or consumables, one of few qualified laboratories in a programme, and a dominant claims clearing house. [Stryker - Customer updates on network disruption][2] [BVO Nederland - Breach larger than reported][27] Observed fourth-party elements: the Stryker incident ran through the supplier's internal Microsoft environment, and the Dutch operator stated that laboratory data may have been obtained through another client of the laboratory. Cross-sector concentration in cloud, telecommunications and energy is not quantified in this edition.

### Structural governance considerations

[NHS England - Synnovis questions and answers][102] Observed: Synnovis is co-owned by two NHS foundation trusts and SYNLAB, a documented public and private joint-service model. [Owner-supplied Q10-Q15 research, section E4] Judgement: responsibilities can span the owner, operator, clinical organisation and technology provider; shared services create dependencies outside a single borrower's authority; referral, procurement and reimbursement incentives require oversight across functions; and group-wide assurance must reach local applications and contracts. Complexity is not evidence of weak governance.

## Cyber Threat Landscape & Attack Scenarios

### Actors and activity indicators

[ENISA - Threat Landscape 2026][31] Observed: ENISA's 2026 threat landscape (2025 incidents) places health among the five sectors most represented in Member State NIS2 incident reporting; unauthorised access against health was led by financially motivated attacks (46%), ransomware accounted for 26.8%, healthcare providers accounted for 63.6% of health data breaches and 85.5% of DDoS (distributed denial of service) claims. ENISA names Qilin, INC Ransom and SafePay as the most deployed ransomware strains against health in 2025 and Hezi Rash, Dark Storm Team and Keymous+ as the most active DDoS groups. Limitation: the dataset is mainly open-source and sector categorisation is imperfect. [ENISA - Health Threat Landscape 2023][99] Benchmark (historical): ENISA analysed 215 publicly reported incidents in the EU and neighbouring countries from January 2021 to March 2023, of which 116 (54%) involved ransomware; this is incident composition, not attack probability. [FBI IC3 - 2025 Internet Crime Report][84] Benchmark: the FBI Internet Crime Complaint Center (IC3) recorded 460 healthcare and public-health ransomware complaints and 182 data-breach complaints in 2025.

### Five prioritised threat scenarios

| ID | Scenario | Actors and motivation | Pathway and enabling weakness | Mechanism tag | Exploitation status | Evidence incidents | Direction | Confidence |
|---|---|---|---|---|---|---|---|---|
| THR-01 | Identity and administration-plane abuse | Financially motivated groups; hacktivist personas claiming state-linked aims | Privileged or administrative identities control many endpoints or tenants; endpoint-management misuse | common_dependency | Confirmed | [Stryker - Customer updates on network disruption][2] [CISA - Endpoint management hardening alert][100] [Health-ISAC - ShinyHunters identity campaign alert][68] | Rising in 2026 disclosure (Judgement) | Medium |
| THR-02 | Ransomware or destructive intrusion against an operator | Ransomware affiliates (Qilin, INC Ransom, SafePay named by ENISA) | Encryption or precautionary shutdown removes EPR, laboratory and ordering systems; backup integrity decides recovery | targeted_disruption | Confirmed | [West Pharmaceutical - Form 8-K May 2026][15] [The Record - AZ Monica cyberattack][20] [C&AG Ireland - HSE cyber attack financial impact][103] | Mixed: French ransomware count down 30% in 2025 | Medium |
| THR-03 | Credential, API and remote-access abuse at vendors and providers | Financially motivated data theft and extortion | Accounts without MFA or adequate scoping; third-party API credentials; web-application authentication and input-validation weaknesses | common_dependency | Confirmed | [Cegedim Sante - Statement 4 March 2026][17] [Veradigm - Form 8-K September 2026][25] [EDPB - CNIL fine on Hopital Prive de la Loire][30] [HHS OIG - Audit report A-18-22-08021][98] | Rising share of account abuse in France (50% of compromise vectors) | Medium-High |
| THR-04 | Outsourced clinical-service and supplier concentration | Any actor; disruption by suspension or outage of a shared supplier | Few qualified laboratories or manufacturers with limited spare capacity; stock buffers of about two weeks | supply_chain_concentration | Confirmed | [BVO Nederland - Annual report 2025][28] [NHS England - Synnovis questions and answers][102] [NHS England - Stryker supply disruption letter][3] | Stable to rising (Judgement) | Medium |
| THR-05 | Cyber-enabled and hybrid payment fraud | External fraudsters; phishing-service operators | Supplier mailbox compromise, provider-finance impersonation, payment-processor account takeover; deception step changes bank details | other | Confirmed (hospital diversion); warnings for newer techniques | [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] [Texas HHSC - QIPP provider phishing alert][86] [FBI IC3 - Healthcare payment processor warning 2022][85] | Emerging techniques (AI impersonation) warned, not documented in sector | Medium |

[ENISA - NIS360 2026][32] Judgement: THR-01 and THR-03 are the common-dependency variants because compromise of a managed service provider or software vendor can give access to many hospitals at once. [Stryker - Customer updates on network disruption][2] [HIPAA Journal - Stryker cyberattack][9] Observed and limitation: Stryker described a malicious file used to run commands; descriptions of device wiping through the device-management platform come from media and researchers (Tier 3), not from the company. [FBI IC3 - Healthcare payment processor warning 2022][85] Observed (historical): the FBI described healthcare examples from 2018-2022 in which credentials and social engineering were used to alter banking instructions at payment processors, one involving ACH. No incident count is converted into a probability.

### Last 12 months

[ANS CERT Sante - Observatory 2025][33] Observed: France recorded 28 ransomware incidents in health in 2025, down 30% from 2024, while compromise of messaging accounts made up 50% of system-compromise vectors, and 288 of 764 reports involved degraded-mode operation or interrupted care. [Stryker - Form 8-K/A April 2026][1] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [West Pharmaceutical - Form 8-K May 2026][15] Observed: three manufacturers declared material incidents between March and September 2026. [Cegedim Sante - Statement 4 March 2026][17] [Veradigm - Form 8-K September 2026][25] Observed: vendor-level credential and API misuse exposed patient administrative data. [Texas HHSC - QIPP provider phishing alert][86] Observed: on 25 February 2026 Texas HHSC warned of emails falsely presenting as its Provider Finance Department; completed payment diversion was not established.

### Last 30 days (28 September - 27 October 2026)

| Development | Date | New or update | Evidence |
|---|---|---|---|
| Microsoft Digital Crimes Unit and Health-ISAC legal action against phishing-service operators (YAM, CoGUI, Iron Man) | Published 14 October 2026 | New legal development; allegations not adjudicated | [Microsoft DCU - YAM, CoGUI and Iron Man pleadings][88] |
| Illinois laboratory owner indicted over fabricated COVID-19 test results | Indicted 19 October 2026; published 20 October 2026 | New charge concerning conduct of May 2021 - April 2022 | [DOJ - Illinois laboratory owner indictment][78] |
| UK Cyber Security and Resilience Bill at House of Lords Report stage | Status at 14 October 2026 | Update | [UK Parliament - Cyber Security and Resilience Bill][60] |
| NHS supplier cyber security charter list updated | 1 October 2026 | Update | [NHS England - Supplier cyber security charter][59] |
| Operational incidents | - | [Owner-supplied Q10-Q15 research, section E2] No last-30-day operational incident with a complete primary evidence trail was established; no new healthcare payment-diversion incident met the evidence threshold | - |

Limitation: for Q01-Q07 topics, developments between 15 and 27 October 2026 were not researched; Boston Scientific's quantified third-quarter effect is due on 28 October 2026, after the cut-off.

## Geopolitical Cyber Exposure

**Coverage status: partial.** The source edition did not run a dedicated Q07 geopolitical analysis, and this edition did not add one. The section records the geopolitical evidence that exists in the research record and the gaps.

### Drivers and observed campaigns

| ID | Campaign or driver | Attribution and who made it | Attribution confidence | Exposed subsector | Evidence |
|---|---|---|---|---|---|
| GEO-01 | Handala persona claim of the Stryker attack (March 2026) | Claim reported by media; the FBI separately assesses Handala as linked to an online entity operated by Iran's Ministry of Intelligence and Security (MOIS) | Unconfirmed for the Stryker attack: Stryker's filings do not attribute it | Medical technology; downstream hospitals | [HIPAA Journal - Stryker cyberattack][9] [FBI - FLASH on Iranian MOIS actors][10] [Stryker - Form 8-K/A April 2026][1] |
| GEO-02 | Hacktivist DDoS against health (2025) | ENISA names Hezi Rash, Dark Storm Team and Keymous+ as most active DDoS groups; providers 85.5% of DDoS claims | Group claims, not state attribution | Healthcare providers | [ENISA - Threat Landscape 2026][31] |
| GEO-03 | Policy response: EU action plan on hospital cybersecurity (January 2025) | Non-legislative policy; EU early warning subscription service planned by 2026 | Not applicable | Hospitals | [European Commission - Hospital cybersecurity action plan][56] |

[FBI - FLASH on Iranian MOIS actors][10] [Stryker - Form 8-K/A April 2026][1] Judgement (confidence Low-Medium): if the claim is accurate, geopolitical intent converts into macro-financial exposure through manufacturer earnings and hospital supply rather than through patient data; destructive intent, rather than extortion, lengthens recovery. Supply-chain targets may be chosen for symbolic or national affiliation.

### Exposed subsectors, regions and propagation

[ENISA - Threat Landscape 2026][31] [NHS England - Stryker supply disruption letter][3] Judgement: exposed points are providers (DDoS and disruption claims) and globally distributed manufacturers whose outage propagates across health systems in several countries; the Stryker outage reached UK hospitals through supply. Regional exposure has not been mapped.

### Early warning indicators

- [FBI - FLASH on Iranian MOIS actors][10] Government advisories naming state-linked actors targeting health or medical technology.
- [ENISA - Threat Landscape 2026][31] Hacktivist DDoS campaigns announced against health providers in a specific country.
- [Stryker - Form 8-K/A April 2026][1] Manufacturer Item 1.05 filings that coincide with persona claims.

### Gaps

Not covered: state-linked espionage against pharmaceutical research; sanctions-related targeting; conflict-driven campaigns by region; a geographic exposure view; attribution by a government authority for any 2026 health incident; documented correlated disruption from a geopolitical campaign. These remain open for a dedicated Q07 run.

## Major Cyber Incidents & Case Studies

### Selection criteria

Judgement: incidents qualify when they have at least one Tier 1 source confirming occurrence, disclose an operational, care-continuity, financial or regulatory outcome, and represent a distinct subsector or pathway. Ranking weighs breadth of affected service, propagation potential, evidence strength, financial transmission and decision value. Several reports of one event are counted once; a recent publication about an older event is an update, not a new incident. The most publicised incidents are not statistically representative.

### Historical landmark top five

| Rank | Incident | Subsector and geography | Date | Mechanism | Disruption and recovery | Financial or regulatory consequence | Lesson | Evidence |
|---|---|---|---|---|---|---|---|---|
| 1 | Change Healthcare | Claims and transaction infrastructure; US | 21 February 2024 | Intrusion; systems isolated | Majority of services restored or replaced by the reporting point | FY2024: USD 2.2 billion direct response costs; USD 867 million estimated business-disruption impacts; more than USD 9 billion interest-free provider loans; about 192.7 million individuals notified (figure as of 31 July 2025) | Shared transaction interruption transmits into provider cash flow | [UnitedHealth - Form 10-K FY2024][101] [HHS OCR - Change Healthcare FAQ][38] |
| 2 | Synnovis pathology | Diagnostics; London, UK | 3 June 2024 | Ransomware attack on outsourced pathology | Diagnostic capacity reduced; 10,152 acute outpatient appointments and 1,710 elective procedures postponed to 22 September 2024; all pre-attack services restored by December 2024 | No complete financial-loss measure | Joint ownership and shared pathology transmit effects across providers | [NHS England - Synnovis questions and answers][102] [NHS England London - Synnovis clinical impact update][39] |
| 3 | Health Service Executive (HSE) | National health service; Ireland | 14 May 2021 | Ransomware; national network shutdown | 99% of applications restored by 21 September 2021, 130 days after encryption | Full economic cost not established in the cited conclusion | Network trust and staged restoration matter for shared services | [C&AG Ireland - HSE cyber attack financial impact][103] |
| 4 | WannaCry and NHS England | Hospitals; England | 12 May 2017 | Self-propagating ransomware exploiting a common vulnerability | At least 81 of 236 trusts affected; 6,912 cancelled appointments identified, over 19,000 estimated (not additive) | Not stated in cited findings | Common vulnerability, precautionary shutdown, untested local response plan | [NAO - WannaCry investigation][104] |
| 5 | Advanced Computer Software Group | Managed IT supplier to the NHS; UK | August 2022 | Ransomware entering through a customer account lacking MFA (per ICO) | NHS 111 disrupted | GBP 3,076,320 ICO fine announced 27 March 2025; 79,404 people affected | Supplier security failures attract regulatory penalties | [ICO - Advanced penalty][43] |

### Rolling 12-month top five (1 September 2025 - 14 October 2026 evidence window)

| Rank | Incident | Subsector and geography | Period | Operational vulnerability | Consequence | Evidence strength |
|---|---|---|---|---|---|---|
| 1 | Stryker global network disruption | Medical-device manufacturer; global; UK supply effect | Identified 11 March 2026; fully operational 1 April 2026 | Internal Microsoft environment; malicious file used to run commands | Manufacturing, ordering and shipping disrupted about three weeks; NHS controlled allocation of six lines; some patient cases rescheduled; material Q1 effect | Tier 1 filings, company updates, NHS England letter, CISA alert |
| 2 | Boston Scientific global disruption | Medical-device manufacturer; global | Identified 25 August 2026; restoration early September | Unauthorised activity limiting systems and business applications | Global manufacturing, ordering and shipping disrupted; Q3 and full-year guidance expected to be missed; remote-monitoring activations paused | Tier 1 filings and updates |
| 3 | Cegedim Sante MLM software breach | Primary-care practice software; France | Detected late 2025; disclosed 26 February 2026 | Abnormal queries on doctor accounts (Tier 3 detail) | 15.8 million administrative records published; about 165,000 with free-text notes | Tier 1 company statement |
| 4 | West Pharmaceutical encryption and exfiltration | Pharmaceutical components; global | Detected 4 May 2026; fully operational 20 May 2026 | Systems encrypted, data exfiltrated, global systems offline | Global operations disrupted; site-by-site restart | Tier 1 filings and updates |
| 5 | AZ Monica hospital shutdown | Acute hospital; Belgium | 13 January - about mid-February 2026 | Server compromise prompting shutdown | Surgery cancelled; seven unstable patients transferred; about three weeks on paper | Tier 1 parliamentary record of the attack; impact detail Tier 3 |

[Stryker - Form 8-K/A April 2026][1] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [Cegedim Sante - Statement 4 March 2026][17] [West Pharmaceutical - Form 8-K May 2026][15] [Belgian Chamber - Committee record 3 February 2026][23] Full narratives and supporting references for these five incidents are in Annex A1. [McKesson - Form 8-K August 2026][24] [Veradigm - Form 8-K September 2026][25] [MedTech Dive - Medtech cyberattacks 2026][70] Considered but not selected: McKesson (materiality not determined at filing), Veradigm (no operational disruption), DXS International (Tier 3 only) and other 2026 medical-technology incidents (outcomes not disclosed).

### Cyber-enabled fraud incident

[DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] Observed: around 13 June 2023 an external hacker compromised a furniture vendor's email, impersonated its employee and changed payment details; Children's Healthcare of Atlanta transferred USD 5.3 million, of which about USD 4 million was recovered. This is recorded once as an incident (INC-12, cyber-enabled fraud) and once as a fraud record (FRD-01), linked.

### Three case studies

Full reconstructions are in Annex A2.

**Case study 1 - Dutch screening laboratory breach (Clinical Diagnostics NMDL, July 2025 - May 2026).** [BVO Nederland - Annual report 2025][28] [IGJ - Clinical Diagnostics finding][29] Observed: a July 2025 hack of an outsourced laboratory led the programme operator to suspend it; two backup laboratories ran at about 150% of capacity for six months, and from 22 December 2025 primary cervical screening invitations were reduced by 50%. The Health and Youth Care Inspectorate (IGJ) found on 13 May 2026 that the laboratory did not meet NEN 7510. Lesson: a confidentiality breach at a supplier becomes an availability problem when substitutes lack spare capacity. Does not establish: clinical harm, incident cost, attacker identity or similar gaps at other laboratories.

**Case study 2 - Change Healthcare claims-clearing outage (February 2024, historical landmark).** [UnitedHealth - Q3 2024 results release][37] [UnitedHealth - Form 10-K FY2024][101] Observed: the attack isolated a clearing platform used across the US system; by 30 September 2024 USD 8,904 million of loans had been advanced to care providers (USD 3,189 million repaid), and by December 2024 more than USD 9 billion. Lesson: a shared transaction platform transmits a single intrusion into provider liquidity at scale. Does not establish: provider-level losses, a sector-wide loss total, or how quickly other markets with different payment structures would be affected.

**Case study 3 - Stryker global disruption and NHS supply response (March-April 2026).** [Stryker - Customer updates on network disruption][2] [NHS England - Stryker supply disruption letter][3] [Stryker - Q1 2026 results release][6] [CISA - Endpoint management hardening alert][100] Observed: production, ordering and shipping were disrupted for about three weeks; NHS England estimated about two weeks of UK stock on day 7, placed six lines under controlled allocation and required mutual aid; Stryker reported a material first-quarter effect but kept full-year guidance; CISA recommended hardening endpoint-management configurations. Lesson: recovery margin over stock cover was days, not weeks. Does not establish: attacker identity (claimed, not officially attributed), product compromise, or that UK stock ran out.

## Control Weaknesses & Resilience Priorities

These are sector-informed priorities derived from documented incidents and enforcement. They are not findings about any borrower's or bank's controls.

### Weaknesses linked to observed attacks

| ID | Weakness | Observed in | Linked threat | Status | Evidence |
|---|---|---|---|---|---|
| CTL-01 | Remote access and accounts without MFA | Hôpital Privé de la Loire breach; Advanced (NHS supplier) ransomware | THR-03 | Confirmed by regulator decisions | [EDPB - CNIL fine on Hopital Prive de la Loire][30] [ICO - Advanced penalty][43] |
| CTL-02 | Privileged identity and endpoint-management misuse | Stryker | THR-01 | Confirmed by company and agency advisory | [Stryker - Customer updates on network disruption][2] [CISA - Endpoint management hardening alert][100] |
| CTL-03 | Web-application authentication and input-validation weaknesses | One large southeastern US hospital (four web applications examined) | THR-03 | Confirmed for one organisation only | [HHS OIG - Audit report A-18-22-08021][98] |
| CTL-04 | No independent security audit or periodic risk mapping at an outsourced laboratory | Clinical Diagnostics NMDL | THR-04 | Confirmed by inspectorate | [IGJ - Clinical Diagnostics finding][29] |
| CTL-05 | Third-party API credential scoping and bulk-extraction monitoring | Veradigm; Cegedim Sante | THR-03 | Confirmed occurrence; control detail partial | [Veradigm - Form 8-K September 2026][25] [Cegedim Sante - Statement 4 March 2026][17] |
| CTL-06 | Network trust between connected entities; monitoring differences | HSE (historical) | THR-02 | Confirmed by audit office | [C&AG Ireland - HSE cyber attack financial impact][103] |
| CTL-07 | No formal mechanism to check local compliance with advice; untested local response plan | WannaCry and NHS (historical) | THR-02 | Confirmed by audit office | [NAO - WannaCry investigation][104] |
| CTL-08 | Supplier bank-detail change accepted from a compromised supplier mailbox | Children's Healthcare of Atlanta | THR-05 | Confirmed route; exact missing approval or callback step not published | [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] |
| CTL-09 | Claims not reconciled to actual service or dispensing; referral remuneration not tested for substance | Paterson pharmacy; Labtech; Illinois laboratory (alleged) | Fraud (non-cyber) | Confirmed admission (pharmacy); allegations (others) | [DOJ NJ - Paterson pharmacy owner plea][77] [DOJ - Labtech plea and settlement][75] [DOJ - Illinois laboratory owner indictment][78] |

### Prioritised capabilities

| Priority | Capability | Protected process | Mitigates | Classification | Evidence of completion | Monitoring trigger |
|---|---|---|---|---|---|---|
| 1 | Phishing-resistant MFA, privileged-access separation and approval for mass endpoint actions | Manufacturing, ordering, clinical records | THR-01, THR-03 | Mandatory for in-scope EU entities as a risk-management measure (NIS2 Article 21(2)(j) calls for MFA or continuous authentication where appropriate); good practice elsewhere | MFA coverage evidence; privileged-access design | [Health-ISAC - ShinyHunters identity campaign alert][68] identity-campaign alerts |
| 2 | Tested restoration and isolated offline backups; safe degraded mode | Emergency care, surgery, diagnostics | THR-02 | Context-dependent; NIS2 business continuity measures for in-scope entities | Restoration test reports; downtime procedures | [ANS CERT Sante - Observatory 2025][33] degraded-mode data |
| 3 | Supplier assurance and tested substitution with capacity figures | Diagnostics, implants, components | THR-04 | NIS2 supply-chain security for in-scope entities; IGJ expects providers to verify laboratory security | Independent assessment; exercised backup protocol | [IGJ - Clinical Diagnostics finding][29] inspectorate findings |
| 4 | API and account scoping, rate limits and bulk-query monitoring at vendors | Records held by vendors | THR-03 | GDPR Article 32 security of processing (binding) | Monitoring rules and alert tests | [Veradigm - Form 8-K September 2026][25] vendor disclosures |
| 5 | Independent supplier callbacks, dual approval and change alerts for bank details | Supplier payments | THR-05 | Good practice; links to UK failure-to-prevent-fraud defence for qualifying bodies | Change records with callback evidence | [FBI IC3 - Impersonation PSA July 2026][87] impersonation warnings |
| 6 | Claims-to-service reconciliation; referral remuneration and beneficial-interest checks | Reimbursement revenue | Non-cyber fraud | US False Claims Act and Anti-Kickback Statute exposure (binding statutes) | Reconciliation and exception reports | [DOJ - Illinois laboratory owner indictment][78] enforcement releases |
| 7 | Claims-platform contingency and bridging liquidity | Provider cash collection | DEP-02 | Context-dependent | Dependency map; contingency funding terms | [UnitedHealth - Form 10-K FY2024][101] processor disclosures |
| 8 | Legal-status tracking of obligations | All | Perimeter change | Good practice | Register reviewed quarterly | [UK Parliament - Cyber Security and Resilience Bill][60] Royal Assent; CJEU rulings |

### Sector benchmarks and recurring preparedness gaps

[ENISA - NIS360 2026][32] Benchmark: ENISA rates health maturity as moderate and below sector importance ("risk zone"), with providers behind pharmaceutical manufacturers. [Sophos - Ransomware in Healthcare 2025][34] Benchmark (vendor survey, 292 healthcare respondents): 58% recovered from ransomware within one week. [HHS - HPH Cybersecurity Performance Goals][67] Observed: US essential goals include MFA and vendor cybersecurity requirements (voluntary). [NHS England - Supplier cyber security charter][59] Observed: the NHS supplier charter asks for MFA, patching, immutable backups, 24/7 monitoring and board exercises (voluntary). Judgement: the recurring gaps are MFA on remote access, supplier assurance depth and untested recovery. [Owner-supplied Q10-Q15 research, section E1] Unresolved: sector email-authentication posture, cloud-provider shares, remote-access prevalence, unsupported asset proportions, executive and finance-staff exposure, device-patching constraints and representative detection, containment and recovery maturity. The absence of a specific technology does not by itself indicate inadequate resilience.

## Regulatory & Supervisory Resilience Expectations

Legal status and milestone types follow the primary instrument where recorded. Proposals are not presented as binding law. Applicability depends on transposition, entity size and identification.

### Cyber and operational resilience

| ID | Instrument | Jurisdiction and scope | Legal status and milestone | Key obligations | Credit relevance | Evidence |
|---|---|---|---|---|---|---|
| REG-01 | NIS2 Directive (EU) 2022/2555 | EU; health entities (Annex I); device and IVD manufacturers (Annex II) | Directive; in force 16 January 2023; transposition deadline 17 October 2024; four Member States referred to the Court of Justice 8 July 2026 | Risk management including supply-chain security and MFA where appropriate (Article 21); 24-hour early warning, 72-hour notification, one-month report (Article 23); management accountability | Compliance cost; penalties; uneven national application | [EUR-Lex - NIS2 Directive][44] [CCB - NIS2 scope visual][45] [European Commission - NIS2 CJEU referral][46] |
| REG-02 | CER Directive (EU) 2022/2557 | EU; health entities identified by Member States | Directive; identification deadline 17 July 2026; seven Member States referred | Resilience measures; 24-hour incident notification | Designated entities face continuity duties | [EUR-Lex - CER Directive][47] [European Commission - CER CJEU referral][48] |
| REG-03 | GDPR (EU) 2016/679 | EU; controllers and processors of health data | Regulation; applicable since 25 May 2018 | Security of processing (Article 32); 72-hour notification (Article 33); communication to individuals (Article 34) | Fines; enforcement observed (CNIL EUR 500,000, September 2026) | [EUR-Lex - GDPR][49] [EDPB - CNIL fine on Hopital Prive de la Loire][30] |
| REG-04 | European Health Data Space (EU) 2025/327 | EU; EHR systems, data holders | Regulation; in force 26 March 2025; most obligations from March 2029 | Interoperability and logging components | Future EHR vendor obligations | [EUR-Lex - EHDS Regulation][50] [European Commission - EHDS timeline][51] |
| REG-05 | MDR (EU) 2017/745 and IVDR (EU) 2017/746 | EU; device and IVD manufacturers | Binding; MDCG 2019-16 guidance not binding | Software security requirements; shared responsibility with operators | Product approval and liability | [MDCG - 2019-16 Rev.1][52] |
| REG-06 | Cyber Resilience Act (EU) 2024/2847 | EU; products with digital elements, excluding MDR/IVDR devices | Regulation; reporting obligations from 11 September 2026; main obligations from 11 December 2027 | Vulnerability reporting; product security | Non-device health software vendors | [EUR-Lex - Cyber Resilience Act][54] [European Commission - CRA summary][53] |
| REG-07 | AI Act as amended by (EU) 2026/1744 | EU; AI in regulated products including devices | Amendment in force 27 July 2026; Annex I high-risk date 2 August 2028 | Deferred high-risk duties for AI devices | Deferred cost | [EUR-Lex - Digital Omnibus on AI][55] |
| REG-08 | NIS Regulations 2018 (health, England) | England; NHS trusts, integrated care boards, certain independent providers | In force; DHSC guidance September 2023 | 72-hour reporting via DSPT; penalties up to GBP 17 million | Enforcement risk for in-scope bodies | [DHSC - NIS health sector guide (England)][57] |
| REG-09 | NHS DSPT 2025-26 | England; organisations with NHS patient data access | Assurance standard; deadline 30 June 2026 | CAF-aligned assurance | Supplier access condition | [NHS England - DSPT 2025-26][58] |
| REG-10 | Cyber Security and Resilience Bill | UK | Bill only; House of Lords Report stage; no Royal Assent at 14 October 2026 | Proposed expansion of NIS duties to managed services | Future perimeter change | [UK Parliament - Cyber Security and Resilience Bill][60] |
| REG-11 | MHRA post-market surveillance | Great Britain | In force 16 June 2025; device cyber legislation planned | Shortened incident-reporting deadlines | Device manufacturer obligations | [MHRA - Post-market surveillance regulations][61] [MHRA - Software and AI roadmap][62] |
| REG-12 | HIPAA Security Rule amendments | US covered entities and business associates | Proposal (published 6 January 2025); no final rule at cut-off | Proposed stronger security requirements | Possible future compliance cost | [Federal Register - HIPAA Security Rule NPRM][63] [Reginfo - HIPAA Security Rule agenda][64] |
| REG-13 | FD&C Act section 524B | US premarket cyber devices | Statute; effective 29 March 2023 | SBOM, vulnerability monitoring, patching | Product approval | [FDA - Medical device cybersecurity FAQ][66] |
| REG-14 | HPH Cybersecurity Performance Goals | US healthcare and public health | Voluntary | MFA, vendor requirements | Benchmark only | [HHS - HPH Cybersecurity Performance Goals][67] |

### Fraud-prevention, payment and integrity rules

| ID | Instrument | Jurisdiction and scope | Legal status and milestone | Relevance | Evidence |
|---|---|---|---|---|---|
| REG-15 | Economic Crime and Corporate Transparency Act 2023, s.199 (with ss.201-202) | UK; qualifying large organisations | Legislation; failure-to-prevent-fraud offence commenced 1 September 2025 | Offence requires associated-person fraud intended to benefit the organisation; being a victim is not sufficient; relevant to qualifying healthcare bodies | [UK legislation - ECCTA 2023 s.199][89] |
| REG-16 | Bribery Act 2010, s.7 | UK; relevant commercial organisations | Legislation; enacted 2010 (commencement instrument not retrieved) | Failure to prevent bribery; referral and procurement incentives | [UK legislation - Bribery Act 2010][90] |
| REG-17 | PSR Specific Direction 20 and PS24/7 | UK; in-scope payment service providers | Binding direction; applies from 7 October 2024; maximum reimbursement GBP 85,000 per claim | Authorised push payment reimbursement is not a blanket promise for large healthcare companies | [PSR - Specific Direction 20][91] |
| REG-18 | Regulation (EU) 2024/886 (instant payments, payee checking, Article 5c) | EU; payment service providers | Binding regulation; adopted 13 March 2024; euro-area payee checking from 9 October 2025; non-euro-area 9 July 2027 | Healthcare firms are users; does not establish reimbursement for authorised fraud | [EUR-Lex - Regulation (EU) 2024/886][92] |
| REG-19 | Directive 2014/24/EU, Articles 24 and 57 | EU; covered public procurement | Directive requiring national implementation; adopted 26 February 2014 | Conflicts of interest and exclusion grounds | [EUR-Lex - Directive 2014/24/EU][93] |
| REG-20 | Directive (EU) 2019/1937 | EU; qualifying reports of covered EU-law breaches | Directive; transposition deadline 17 December 2021 (private-entity channels 17 December 2023) | Whistleblowing protection; reporting route for fraud | [EUR-Lex - Directive (EU) 2019/1937][94] |
| REG-21 | False Claims Act, 31 USC 3729 | US; claims involving government money | Federal statute; codified text in effect 9 September 2026 (text-currency date) | Liability for knowing false claims; basis for settlements such as Ahold | [US Code - 31 USC 3729][95] |
| REG-22 | Anti-Kickback Statute, 42 USC 1320a-7b(b) | US; federally funded healthcare business | Federal statute; codified text in effect 10 September 2026 (text-currency date) | Prohibits specified remuneration for referrals; basis for Labtech plea | [US Code - 42 USC 1320a-7b][96] |

### Supervisory priorities and enforcement observed

[EDPB - CNIL fine on Hopital Prive de la Loire][30] Observed: CNIL fined a private hospital EUR 500,000 in September 2026 for remote access without MFA and inadequate detection (524,867 patients affected). [IGJ - Clinical Diagnostics finding][29] Observed: IGJ called on care providers that use laboratories or other third parties to verify their information security actively. [ICO - Advanced penalty][43] Observed: the ICO fined an NHS IT supplier GBP 3,076,320 (March 2025, contextual). [DOJ - Ahold Delhaize USA settlement][76] [DOJ - Labtech plea and settlement][75] Observed: US enforcement in 2026 resolved pricing and referral cases through settlements and pleas.

### Interaction and gaps

[EUR-Lex - Cyber Resilience Act][54] [MDCG - 2019-16 Rev.1][52] Judgement: device product security falls under MDR or IVDR, not the CRA; the same manufacturer is within NIS2 for its own networks; the 2026 manufacturer events were enterprise-network incidents of the NIS2 type. Gaps: UK GDPR and Data Protection Act 2018, the US HIPAA Breach Notification Rule and the existing HIPAA Security Rule, US state law, UK payee-confirmation directions, complete UK procurement and whistleblowing instruments, EU Member-State criminal and internal-control laws, US issuer internal-control requirements and published supervisory priority statements were not covered. No conclusion that these requirements are absent should be drawn.

## Operational & Financial Consequences and Credit Transmission

### Bottom line

[Stryker - Q1 2026 results release][6] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] [UnitedHealth - Form 10-K FY2024][101] [DOJ - Ahold Delhaize USA settlement][76] Judgement: public financial evidence comes from corporate filings, regulatory penalties and enforcement outcomes; no in-period EU or UK provider disclosed an incident cost. The quantified outcomes differ in currency, period, statistic and population and are never added together. Care-service disruption is evidenced in counts of cancelled or deferred activity and service reductions, not in money. A defensible five-year cost trend is not available for the sector from a single dataset.

### Cyber incident outcomes (disclosed)

| Case | Impact type | Metric as disclosed | Period | Evidence |
|---|---|---|---|---|
| Change Healthcare (historical) | Response cost and business disruption | USD 2.2 billion direct response costs; USD 867 million estimated business-disruption impacts (separate measures) | FY2024 | [UnitedHealth - Form 10-K FY2024][101] |
| Change Healthcare (historical) | Same, interim | USD 2,457 million pre-tax total (USD 1,710 million direct response; USD 747 million disruption) | Nine months to 30 September 2024 | [UnitedHealth - Q3 2024 results release][37] |
| Change Healthcare (historical) | Liquidity support (financing, not loss) | USD 8,904 million loans advanced, USD 3,189 million repaid (to 30 September 2024); more than USD 9 billion interest-free loans through December 2024 | 2024 | [UnitedHealth - Q3 2024 results release][37] [UnitedHealth - Form 10-K FY2024][101] |
| Stryker | Revenue timing and margin | Q1 2026 net sales USD 6,020 million (+2.6% reported); adjusted EPS USD 2.60 (-8.5%); adjusted operating margin 21.1% (-180 basis points); full-year guidance maintained | Q1 2026 | [Stryker - Q1 2026 results release][6] |
| Stryker | Recovery | Q2 2026 net sales USD 6,589 million; organic growth 9.0% | Q2 2026 | [Stryker - Q2 2026 results release][8] |
| Boston Scientific | Guidance | Unlikely to meet Q3 and full-year 2026 net sales growth and adjusted EPS guidance; amount due 28 October 2026 | Q3 2026 | [Boston Scientific - Form 8-K Item 1.05 September 2026][12] |
| West Pharmaceutical | Response cost (combined) | USD 6.9 million nonrecurring professional fees including the cyber incident and legal matters | Q2 2026 | [West Pharmaceutical - Q2 2026 results release][16] |
| Conduent | Direct response cost | USD 25 million for the January 2025 event (comparative) | Six months to 30 June 2025 | [Conduent - Form 10-Q Q2 2026][41] |
| Hôpital Privé de la Loire | Regulatory outcome | EUR 500,000 CNIL fine; 524,867 patients affected | Decision 3 September 2026 | [EDPB - CNIL fine on Hopital Prive de la Loire][30] |
| Advanced (NHS IT supplier) | Regulatory outcome (contextual) | GBP 3,076,320 ICO fine; 79,404 people affected | 27 March 2025 | [ICO - Advanced penalty][43] |
| Dutch screening programme | Care-service reduction | Primary invitations reduced 50% from 22 December 2025; backup laboratories at about 150% capacity for six months | December 2025 onwards | [BVO Nederland - Annual report 2025][28] |
| HSE (historical) | Restoration | 99% of applications restored by 21 September 2021, 130 days after encryption (application share, not clinical service share) | 2021 | [C&AG Ireland - HSE cyber attack financial impact][103] |
| WannaCry and NHS (historical) | Care disruption | 6,912 cancelled appointments identified; over 19,000 estimated (not additive) | May 2017 | [NAO - WannaCry investigation][104] |
| Synnovis (historical) | Care disruption | 10,152 acute outpatient appointments and 1,710 elective procedures postponed (unvalidated management information) | 3 June - 22 September 2024 | [NHS England London - Synnovis clinical impact update][39] |

### Cyber benchmarks

| Benchmark | Value | Population and method | Limit | Evidence |
|---|---|---|---|---|
| Ransomware recovery cost excluding ransom | Average USD 1.02 million | 292 healthcare respondents, 17 countries, 100-5,000 employees; January-March 2025 | Vendor survey; self-reported | [Sophos - Ransomware in Healthcare 2025][34] |
| Ransom paid | Median USD 150,000; 36% paid | Same survey | As above | [Sophos - Ransomware in Healthcare 2025][34] |
| Healthcare data breach cost | Average USD 6.64 million | IBM 2026 study, as relayed | Read from trade-press summary | [IBM - Cost of a Data Breach 2026][35] [HIPAA Journal - IBM 2026 summary][36] |
| Reports involving degraded or interrupted care | 288 of 764 (38%) | Mandatory French reports, 2025 | France only | [ANS CERT Sante - Observatory 2025][33] |

### Fraud figures by dataset type

Figures from different dataset types are not combined, averaged or ranked.

| Dataset type | Figure | Period, population and sample | Permitted interpretation | Evidence |
|---|---|---|---|---|
| Investigated cases | Healthcare median loss USD 100,000; 112 cases | ACFE 2024 edition; cases investigated January 2022 - September 2023; global, investigator-submitted | Median of selected investigated cases; not a sector average, annual loss or probability | [ACFE - Occupational Fraud 2024][79] |
| Investigated cases (all sectors, proxy) | Typical case lasts 12 months before detection | ACFE 2024; 1,921 cases | Publisher's description; not a healthcare benchmark | [ACFE - Occupational Fraud 2024 release][80] |
| Official statistics (estimate) | GBP 1.301 billion vulnerable to fraud, bribery and corruption; 0.66% of GBP 198.095 billion | NHSCFA 2026; NHS England funding 2025-2026 | Estimated vulnerability, not measured loss; methodology changed, so no trend is built | [NHSCFA - Strategic Intelligence Assessment 2026][81] [NHSCFA - SIA vulnerability method][83] |
| Official statistics (intelligence reports) | 8,048 reports, of which 7,645 in twelve thematic areas | NHSCFA; April 2025 - March 2026 | Reporting workload, not adjudicated offences | [NHSCFA - Strategic Intelligence Assessment 2026][81] |
| Reported complaints (all sectors, proxy) | 24,768 BEC complaints; USD 3,046,598,558 reported losses | FBI IC3; calendar 2025 | No healthcare cut; counts and losses are separate statistics | [FBI IC3 - 2025 Internet Crime Report][84] |
| Enforcement | Settlements, pleas and charges in the five cases below | Case-specific | Documented schemes and outcomes; not frequency or typical loss | [DOJ - Ahold Delhaize USA settlement][76] |

Gaps: representative healthcare fraud frequency, healthcare mean losses, detection-method shares, detection-time distributions, insurer-claims evidence and a stable five-year series.

### Ranked documented fraud cases

Ordering reflects relevance and evidence quality, not loss size. Several cases concern organisations allegedly committing fraud rather than losing money to it.

| Rank | ID | Case | Subsector; geography | Typology; classification | Perpetrator; channel; rail | Outcome and status | Evidence |
|---|---|---|---|---|---|---|---|
| 1 | FRD-01 | Children's Healthcare of Atlanta supplier payment diversion | Paediatric health system (victim); US | Payment diversion via supplier impersonation; hybrid | External hacker plus money launderer; email and banking; source mentions ACH details and describes a wire | USD 5.3 million transferred (around 13 June 2023); about USD 4 million recovered; launderer convicted 12 February 2026, sentenced 22 July 2026 to four years; USD 682,860 restitution (not additional recovery) | [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] |
| 2 | FRD-02 | Labtech Diagnostics (LTD Holding LLC) | Clinical laboratory; US | Corruption and bribery (referral kickbacks disguised as rent, phlebotomy and services); non-cyber | Management and doctors; contracts, certifications, some hand-delivered money orders | At least USD 6.8 million civil settlement plus contingent payment; agreement to plead guilty to five kickback counts; USD 103,551.90 restitution (7 January 2026); settled allegations remain allegations | [DOJ - Labtech plea and settlement][75] |
| 3 | FRD-03 | Ahold Delhaize USA pharmacies | Supermarket pharmacies; US | Other sector-specific (inflated usual and customary prices on federal claims); non-cyber | Corporate pricing and claims process; rail not established | USD 40 million settlement (10 June 2026); whistleblower action; no determination of liability | [DOJ - Ahold Delhaize USA settlement][76] |
| 4 | FRD-04 | Paterson pharmacy owner (Nestor Jaime) | Owner-operated pharmacy; US | Other sector-specific (claims for drugs not purchased or dispensed); non-cyber | Owner; reimbursement claims | At least about USD 2.5 million Medicare reimbursements on false claims (December 2019 - December 2021); guilty plea 19 November 2025 | [DOJ NJ - Paterson pharmacy owner plea][77] |
| 5 | FRD-05 | Illinois laboratory (Rajesh Patel) | Clinical laboratory; US | Other sector-specific (fabricated negative test results); non-cyber | Co-owner and COO; specimen-collection intermediary (alleged) | Unconfirmed: indicted 19 October 2026; about USD 66.2 million alleged claims, USD 44.1 million alleged payments, USD 28 million alleged personal proceeds (distinct, non-additive); charges are not a conviction | [DOJ - Illinois laboratory owner indictment][78] |

[Bloomberg Law - Florida health system settlement][105] [Yahoo News - Queens pharmacy scheme][106] Candidate exclusions: a Florida health system settlement and a Queens pharmacy buyback scheme were identified as Tier 3 leads without sufficient primary detail; an orthotic-prescription case was not selected because its adjudication preceded the preferred window. Exclusion does not mean disproved. Shortfall: all five cases are US; EU and UK named-case coverage is insufficient for a global comparison.

### Fraud consequences

[DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] [DOJ - Ahold Delhaize USA settlement][76] [DOJ - Labtech plea and settlement][75] Judgement: diversion reduces available cash and exposed capital expenditure funding; settlements and repayments consume liquidity; revenue based on false claims may not be sustainable; investigations and remediation raise costs. Contract loss, restatement, penalties beyond disclosed outcomes and reputational effects are scenario assumptions, not disclosed outcomes for these cases. Recovery and detection evidence counts as preparedness, not as lower inherent exposure.

### Credit transmission channels

| Channel | Mechanism | Strongest evidence | Status |
|---|---|---|---|
| Provider liquidity and working capital | Claims clearing stops; receipts delayed | [UnitedHealth - Form 10-K FY2024][101] more than USD 9 billion provider loans | Observed (historical, US) |
| Supplier earnings and guidance | Production and shipping halt | [Stryker - Q1 2026 results release][6] [Boston Scientific - Form 8-K Item 1.05 September 2026][12] | Observed |
| Activity income and backlog cost | Diagnostic or EPR loss; procedures deferred | [NHS England London - Synnovis clinical impact update][39] [BVO Nederland - Annual report 2025][28] | Observed in counts; money undisclosed |
| Regulatory and litigation cost | GDPR and data-protection fines; class actions | [EDPB - CNIL fine on Hopital Prive de la Loire][30] [ICO - Advanced penalty][43] | Observed |
| Fraud cash leakage and settlements | Diversion; false claims settlements | [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] [DOJ - Ahold Delhaize USA settlement][76] | Observed |
| Public-budget absorption | Recovery funded by health budgets | [BVO Nederland - Annual report 2025][28] | Largely undisclosed |

Judgement: for large diversified manufacturers, 2026 evidence shows a timing shock rather than a solvency event (Stryker kept guidance and recovered in Q2); the second case moved to a guidance miss, the signal a lender would monitor. Insurance recoveries were not disclosed in any filing reviewed. No evidence links these cases to losses at any financial institution.

### Outage length against stock cover

| Case | Measure | Days | Evidence |
|---|---|---|---|
| Stryker | 11 March disruption to 1 April statement of full manufacturing operation | 21 | [Stryker - Customer updates on network disruption][2] |
| West Pharmaceutical | 4 May detection to 20 May full operation | 16 | [West Pharmaceutical - Cyberattack updates][73] |
| Boston Scientific | 25 August identification to 8 September substantial recovery | About 14 | [Boston Scientific - Form 8-K Item 1.05 September 2026][12] |
| UK stock of Stryker products | NHS England estimate on day 7 of remaining stock | About 14 more, to about day 21 | [NHS England - Stryker supply disruption letter][3] |

Judgement: the recovery margin over stock cover was days rather than weeks. Limitation: single cases with different end-points; no source reports that UK stock ran out.

### Illustrative disruption scenarios (1 week, 4 weeks, 8 weeks)

**Illustrative - not forecasts, averages or loss estimates.** No probabilities or monetary loss estimates are assigned.

| Element | SCN-01: 1 week - targeted operator disruption | SCN-02: 4 weeks - supplier concentration | SCN-03: 8 weeks - common dependency |
|---|---|---|---|
| Mechanism | targeted_disruption | supply_chain_concentration | common_dependency |
| Duration basis | [Sophos - Ransomware in Healthcare 2025][34] 58% of surveyed organisations recovered within a week; [VRT NWS - AZ Monica EPR restart][21] EPR restarted after about three weeks, activity 70-80% one week later (Tier 3) | [Stryker - Customer updates on network disruption][2] [West Pharmaceutical - Cyberattack updates][73] manufacturer outages of 14-21 days; [VRT NWS - AZ Monica six months on][22] about four weeks to full hospital operation (Tier 3) | [C&AG Ireland - HSE cyber attack financial impact][103] 130 days to 99% of applications; [NHS England - Synnovis questions and answers][102] services restored by December 2024 (about six months); [BVO Nederland - Annual report 2025][28] six months of substitute operation |
| Affected processes | EPR, laboratory results, scheduling, emergency capacity at one hospital group or laboratory | Implants, consumables, pharmaceutical components; procedure scheduling | Claims and eligibility, or shared pathology across many providers |
| Operational effect | Paper operation; elective surgery cancelled; urgent work diverted | Stock buffers deplete after about two weeks; controlled allocation; procedures rescheduled | Simultaneous loss of a function across providers; receipts or diagnostics delayed for weeks |
| Financial transmission | Activity income loss; overtime and recovery spend; notification cost | Supplier revenue deferral and guidance change; provider lost activity; substitute procurement cost | Provider receipts delayed; bridging finance demand; backlog cost |
| Credit channels | Margin and covenant headroom for leveraged operators | Supplier earnings; provider working capital | Liquidity, working capital and debt service of providers; processor liability |
| Offsets | Intact offline backups; regional mutual aid | Consigned inventory; multi-sourcing; mutual aid | Payer advance programmes; alternative clearing; manual claims |
| Key assumptions | Single operator; no data loss assumed | One sole-source supplier; normal demand | One shared platform; no pre-arranged alternative |
| Borrower data needed | Tested restoration time; revenue by service line; cash days | Single-source map with buffer days; supplier contract terms | Share of receipts through one platform; cash days and committed facilities |
| Early signposts | Ransomware claims; diversion notices | Supplier Item 1.05 filings; national supply notices | Processor disclosures; payer advance programmes |
| Limitations | Survey is self-reported and excludes large systems | Single cases; end-points differ | Historical cases in specific systems; no rerouting-time data |

## Questionnaire Mapping & Credit Officer Engagement

**Mapping status: provisional.** No questionnaire item list was supplied, so the map uses generic PROV- identifiers derived from the evidence. No borrower answers are used, and an adverse answer is a prompt for discussion, not an automatic credit judgement.

### Priority provisional items

| ID | Control area | Weakness an adverse answer may indicate | Threat and incident link | Dependency or regulation | Credit consequence | Conditions that change materiality |
|---|---|---|---|---|---|---|
| PROV-01 | Identity and administration planes | Privileged identities without phishing-resistant MFA or approval for mass actions | THR-01; [Stryker - Customer updates on network disruption][2] [CISA - Endpoint management hardening alert][100] | DEP-07; NIS2 Article 21 | Production or service halt; earnings timing | Size of estate managed centrally; segmentation |
| PROV-02 | Single-source products and stock | No mapped single-source dependencies or buffer days | THR-04; [NHS England - Stryker supply disruption letter][3] | DEP-03, DEP-04 | Procedure deferral; working capital | Make-to-order products; consigned stock |
| PROV-03 | Outsourced clinical services | No independent assurance or exercised substitution for laboratories | THR-04; [BVO Nederland - Annual report 2025][28] [NHS England - Synnovis questions and answers][102] | DEP-01; IGJ expectation | Lost activity income; backlog costs | Number of qualified substitutes; spare capacity |
| PROV-04 | Vendor accounts and APIs | Unscoped third-party credentials; no bulk-query monitoring | THR-03; [Veradigm - Form 8-K September 2026][25] | DEP-06; GDPR Article 32 | Notification cost; fines; litigation | Volume of patient data held by vendors |
| PROV-05 | Remote access and detection | Remote clinical access without MFA; no real-time alerting | THR-03; [EDPB - CNIL fine on Hopital Prive de la Loire][30] | GDPR; NIS2 | Fines; breach costs | Legacy clinical systems |
| PROV-06 | Restoration and downtime | Restoration time stated but not tested; backups not isolated | THR-02; [C&AG Ireland - HSE cyber attack financial impact][103] [VRT NWS - AZ Monica six months on][22] | NIS2 continuity | Weeks of degraded activity; recovery spend | Regional mutual aid; offline modes |
| PROV-07 | Claims and revenue cycle | Dependence on one clearing or claims processor; no bridging arrangement | DEP-02; [UnitedHealth - Form 10-K FY2024][101] | Payer structure | Receipts delay; liquidity demand | Share of receipts through one platform; committed facilities |
| PROV-08 | Regulatory status tracking | Obligations not distinguished by enacted, applicable and proposed status | [UK Parliament - Cyber Security and Resilience Bill][60] [European Commission - NIS2 CJEU referral][46] | REG-01 to REG-14 | Compliance cost surprises | Jurisdictions of operation |
| PROV-09 | Supplier bank-detail changes | No independent callback through established contacts or dual approval | THR-05; FRD-01; [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] | DEP-10; REG-17, REG-18 | Direct cash loss; exposed capital expenditure funding | Payment volume and urgency; supplier churn |
| PROV-10 | Claims integrity and referral arrangements | Claims not reconciled to service or dispensing; referral remuneration not tested; beneficial interests not checked | FRD-02 to FRD-05; [DOJ - Labtech plea and settlement][75] [DOJ NJ - Paterson pharmacy owner plea][77] | REG-21, REG-22, REG-16 | Settlements, repayments, unsustainable revenue | Share of publicly funded revenue; intermediary use |
| PROV-11 | Whistleblowing and group assurance | Escalation channels or audit coverage do not reach subsidiaries and outsourced processes | [DOJ - Ahold Delhaize USA settlement][76] [NAO - WannaCry investigation][104] | REG-15, REG-20 | Investigation and remediation cost | Number of sites, subsidiaries and joint ventures |

### Five priority discussion topics

1. [UnitedHealth - Form 10-K FY2024][101] Which services and receipts stop if the principal technology platform or claims processor fails, and how many days of cash cover exist?
2. [NHS England - Stryker supply disruption letter][3] [BVO Nederland - Annual report 2025][28] Which supplier, laboratory or product has no qualified substitute, and has the switch been exercised with capacity figures?
3. [C&AG Ireland - HSE cyber attack financial impact][103] How long can clinical activity continue on paper or offline, and is restoration time evidenced by a test?
4. [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] Who independently authorises supplier bank-detail changes, and is confirmation done through established contacts?
5. [DOJ - Labtech plea and settlement][75] [NHS England - Synnovis questions and answers][102] Who owns risks shared between clinical teams, finance, subsidiaries, joint ventures and external providers, and how are referral and pricing arrangements reviewed?

### Practical improvements to discuss

[Owner-supplied Q10-Q15 research, sections D5 and D7] Phishing-resistant authentication and constrained account recovery; independent supplier callbacks, dual approval and change alerts; claims-to-service reconciliation; referral remuneration and beneficial-interest checks; independent confirmation through established contacts for voice or video payment requests; exception reporting; whistleblowing escalation; audit coverage across subsidiaries and outsourced processes; documented single-source maps with buffer days; exercised substitution plans for laboratories.

### Early warning indicators and specialist-referral triggers

| Trigger | Threshold for referral to specialist review | Evidence basis |
|---|---|---|
| Material cyber disclosure by a healthcare manufacturer, distributor or processor | Any filing citing manufacturing, ordering or claims disruption | [Stryker - Form 8-K/A April 2026][1] [West Pharmaceutical - Form 8-K May 2026][15] |
| National supply-disruption notice citing a cyber incident | Controlled allocation of product lines | [NHS England - Stryker supply disruption letter][3] |
| Inspectorate or data-protection finding on an outsourced clinical service | Non-compliance finding or service suspension | [IGJ - Clinical Diagnostics finding][29] |
| Enforcement action naming the borrower or its laboratories or pharmacies | Settlement, plea, indictment or civil investigative demand | [DOJ - Ahold Delhaize USA settlement][76] [DOJ - Illinois laboratory owner indictment][78] |
| Payment-diversion or impersonation loss disclosed | Any confirmed diversion | [DOJ NDGA - Children's Healthcare of Atlanta laundering sentence][74] |
| Identity-campaign alert targeting health | Active campaign with observed MFA bypass | [Health-ISAC - ShinyHunters identity campaign alert][68] |
| Legal-status change | UK Bill Royal Assent; NIS2 and CER court rulings | [UK Parliament - Cyber Security and Resilience Bill][60] [European Commission - NIS2 CJEU referral][46] |

## Methodology, Confidence & Limitations

**Research mode and origin mix.** Q01-Q07 were researched by Claude from public sources accessed on 15 October 2026 (73 sources; evidence cut-off 14 October 2026) and are carried forward unchanged. Q10-Q15 come from an owner-supplied research file dated 27 October 2026 (inputs/Healthcare_Q10_to_Q15-2026-10-27.docx, SHA-256 b9fb9d3a34761d2febba3ddcf3669db1957739abff3ea8b2a170fe7bbc8f78c9), which cites 33 further sources. On the owner's instruction these were merged as supplied and were not re-traced in this run; their trace status is recorded as "accepted as supplied" in Annex A7. Q08 (provisional mapping) and Q09 (assembly) were completed in this run. Research order followed Q01-Q07, Q10-Q14, Q15, Q08, Q09.

**Question coverage.**

| Question | Coverage | Main residual gap |
|---|---|---|
| Q01 Operating model and dependencies | Covered | Cloud and managed-service concentration not quantified |
| Q02 Incidents and case studies | Covered: historical top five, 12-month top five, 30-day developments, three case studies | 30-day operational incidents 15-27 October not searched for Q02 |
| Q03 Threat scenarios | Covered: five scenarios | Threat direction is judgement with Low-Medium confidence |
| Q04 Capabilities and benchmarks | Covered | Control confidence per capability not rated |
| Q05 Financial impact and scenarios | Covered | No five-year trend; insurance recoveries undisclosed |
| Q06 Regulation | Covered for EU, UK, US with listed gaps | UK GDPR/DPA 2018; HIPAA Breach Notification Rule; supervisory priority statements |
| Q07 Geopolitical | Partial | Dedicated analysis not run |
| Q10 Fraud | Covered: typology screen, five cases, metrics, structure, controls, rules, emerging techniques | All cases US; no representative frequency |
| Q11-Q14 | Covered | Normalised cross-sector data and 24-sector universe absent |
| Q15 Ratings | Provisional | No approved rubric |
| Q08 Mapping | Provisional | No questionnaire |

**Source hierarchy and tiers.** Tier 1 sources dominate material findings. Tier 3 sources (media, transcripts, aggregators) are used only as context or leads and are labelled. The two Tier 3 fraud leads were not used to support any finding. Several reports of one event are counted once; a recent publication about an older event is treated as an update.

**Temporal layers.** Rolling 12 months: 28 October 2025 - 27 October 2026 for Q10-Q15; the Q01-Q07 window is 1 September 2025 - 14 October 2026. Last 30 days: 28 September - 27 October 2026 for Q10-Q15; for Q01-Q07 only events to 14 October 2026 are captured. Historical items (WannaCry 2017, HSE 2021, Change Healthcare and Synnovis 2024, the 2022 FBI payment-processor warning, ENISA 2023, ACFE 2024) are labelled historical and retained for structural lessons, not current frequency.

**Comparability.** Filings, penalties, surveys, investigated-case studies, complaint counts and official estimates measure different things. No totals are computed across them, no fraud figures of different dataset types are combined, and no sector frequency or probability is extrapolated.

**Rating method.** Ratings follow the four-dimension rules: inherent exposure only, three to five drivers per dimension, separate confidence, Fraud / Cyber overlap split, preparedness evidence kept out of drivers, Fraud confidence capped at Medium. Without an approved rubric and the 24-sector universe, all ratings are provisional and uncalibrated.

**Clinical-impact attribution.** [The Record - Synnovis continuing disruption][40] [King's College Hospital - Synnovis update][72] Media reports linking a death to the Synnovis attack were not traced to a clinical-governance or regulatory report, so no patient harm, mortality or clinical outcome is attributed to any cyber incident in this report.

**Instruction handling.** Retrieved and supplied content was treated as evidence, not instructions. The supplied file states that website prompts and notices were not followed.

**Principal limitations.** No in-period EU or UK provider disclosed an incident cost. All five fraud cases are US. AZ Monica impact detail relies on Tier 3 reporting. Boston Scientific's quantified effect falls after the cut-off. One supplied citation for an excluded fraud case points to an unrelated DOJ release, so that case is not described. Some legal instruments were read in partial extracts. Absence of public evidence is not evidence of absence.

**Release status: NEEDS_REVIEW.** Open items: Q07 dedicated geopolitical analysis; Q01-Q07 not refreshed between 15 and 27 October 2026; Q10-Q15 sources accepted without re-tracing on owner instruction; no approved rubric or 24-sector calibration; no questionnaire; no slide deck in this run (owner scope); listed regulatory gaps; EU and UK fraud case coverage.

## References

Each entry lists source label, publisher, publication date, access basis, tier, temporal class and locator. References [1]-[73] were accessed on 2026-10-15 (Q01-Q07 research); references [74]-[106] come from the owner-supplied Q10-Q15 research and were accepted as supplied. Origin, observation period and geography are in Annex A7.

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
[74]: https://www.justice.gov/usao-ndga/pr/former-cpa-sentenced-federal-prison-laundering-funds-stolen-childrens-healthcare "DOJ NDGA - Children's Healthcare of Atlanta laundering sentence - US Department of Justice, Northern District of Georgia - published 2026-07-23 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - narrative and sentencing paragraphs"
[75]: https://www.justice.gov/opa/pr/south-carolina-laboratory-pleads-guilty-and-agrees-pay-least-68m-settle-allegations "DOJ - Labtech plea and settlement - US Department of Justice, Office of Public Affairs - published 2026-01-07 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - agreement, conduct and whistleblower paragraphs"
[76]: https://www.justice.gov/opa/pr/ahold-delhaize-usa-inc-pay-40m-allegedly-reporting-inflated-drug-prices-claims-federal "DOJ - Ahold Delhaize USA settlement - US Department of Justice, Office of Public Affairs - published 2026-06-10 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - pricing, resolution, qui tam and liability paragraphs"
[77]: https://www.justice.gov/usao-nj/pr/new-jersey-pharmacy-owner-pleads-guilty-health-care-fraud-scheme-involving-billing "DOJ NJ - Paterson pharmacy owner plea - US Department of Justice, District of New Jersey - published 2025-11-24 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - H2 2025 - According to documents paragraphs"
[78]: https://www.justice.gov/opa/pr/illinois-laboratory-owner-charged-66m-covid-19-testing-fraud-scheme "DOJ - Illinois laboratory owner indictment - US Department of Justice, Office of Public Affairs - published 2026-10-20 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current (last 30 days) - court-document narrative and presumption-of-innocence paragraph"
[79]: https://www.acfe.com/en-us/-/media/files/acfe/pdfs/rttn/2024/2024-report-to-the-nations.pdf "ACFE - Occupational Fraud 2024 - Association of Certified Fraud Examiners - published 2024 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 2 - contextual - introduction p.7; industry statistical table p.51"
[80]: https://www.acfe.com/acfe-insights-blog/blog-detail?s=acfe-releases-rttn-2024 "ACFE - Occupational Fraud 2024 release - Association of Certified Fraud Examiners - published 2024 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 2 - contextual - release body"
[81]: https://cfa.nhs.uk/about-nhscfa/corporate-publications/SIA/SIA-introduction "NHSCFA - Strategic Intelligence Assessment 2026 - NHS Counter Fraud Authority - published 2026 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - Introduction, financial-vulnerability and reporting paragraphs"
[82]: https://cfa.nhs.uk/about-nhscfa/corporate-publications/SIA/SIA-procurement-and-commissioning "NHSCFA - SIA procurement and commissioning - NHS Counter Fraud Authority - published 2026 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - procurement and commissioning section"
[83]: https://cfa.nhs.uk/about-nhscfa/corporate-publications/SIA/SIA-how-we-calculate-vulnerability "NHSCFA - SIA vulnerability method - NHS Counter Fraud Authority - published 2026 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - calculation method section"
[84]: https://www.ic3.gov/AnnualReport/Reports/2025_IC3Report.pdf "FBI IC3 - 2025 Internet Crime Report - Federal Bureau of Investigation, Internet Crime Complaint Center - published 2026 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - pp.7-8, 14 and 16"
[85]: https://www.ic3.gov/CSA/2022/220914-2.pdf "FBI IC3 - Healthcare payment processor warning 2022 - Federal Bureau of Investigation - published 2022-09-14 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - historical - PDF p.2, examples and indicators"
[86]: https://content.govdelivery.com/accounts/TXHHSC/bulletins/40b97d2 "Texas HHSC - QIPP provider phishing alert - Texas Health and Human Services Commission - published 2026-02-25 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - opening and phishing description"
[87]: https://www.ic3.gov/PSA/2026/PSA260720 "FBI IC3 - Impersonation PSA July 2026 - Federal Bureau of Investigation, Internet Crime Complaint Center - published 2026-07-20 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - AI-generated video and protective-advice sections"
[88]: https://www.microsoft.com/en-us/corporate-responsibility/customer-security-trust/digital-crimes-unit/notice-of-pleadings/yam-cogui-ironman/ "Microsoft DCU - YAM, CoGUI and Iron Man pleadings - Microsoft Digital Crimes Unit - published 2026-10-14 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current (last 30 days) - Civil Action 1:26-cv-26998-JEM; pleadings and court-order index"
[89]: https://www.legislation.gov.uk/ukpga/2023/56/section/199 "UK legislation - ECCTA 2023 s.199 - legislation.gov.uk - published 2023 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - contextual (legal background) - s.199 with ss.201-202; commencement information"
[90]: https://www.legislation.gov.uk/ukpga/2010/23/data.html "UK legislation - Bribery Act 2010 - legislation.gov.uk - published 2010 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - contextual (legal background) - s.7 and associated-person provisions"
[91]: https://www.psr.org.uk/media/ppblc3kf/amended-specific-direction-20-july-2024-compared.pdf "PSR - Specific Direction 20 - Payment Systems Regulator - published 2024-07 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - contextual (legal background) - para.3.2; PS24/7"
[92]: https://eur-lex.europa.eu/eli/reg/2024/886/oj "EUR-Lex - Regulation (EU) 2024/886 - Official Journal of the European Union - published 2024-03-13 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - contextual (legal background) - Article 5c"
[93]: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32014L0024 "EUR-Lex - Directive 2014/24/EU - Official Journal of the European Union - published 2014-02-26 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - contextual (legal background) - Articles 24 and 57"
[94]: https://eur-lex.europa.eu/legal-content/EN/LSU/?uri=celex%3A32019L1937 "EUR-Lex - Directive (EU) 2019/1937 - Official Journal of the European Union - published 2019-11-26 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - contextual (legal background) - internal-reporting provisions; transposition dates"
[95]: https://uscode.house.gov/view.xhtml?edition=prelim&f=treesort&num=0&req=granuleid%3AUSC-prelim-title31-section3729 "US Code - 31 USC 3729 - Office of the Law Revision Counsel, US House of Representatives - published 2026-09-09 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - contextual (legal background) - section 3729(a)(1)"
[96]: https://uscode.house.gov/view.xhtml?edition=prelim&num=0&req=granuleid%3AUSC-prelim-title42-section1320a-7b "US Code - 42 USC 1320a-7b - Office of the Law Revision Counsel, US House of Representatives - published 2026-09-10 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - contextual (legal background) - section 1320a-7b(b)"
[97]: https://oig.hhs.gov/reports/all/2026/a-large-southeastern-hospital-could-improve-certain-security-controls-to-enhance-its-ability-to-prevent-and-detect-cyberattacks/ "HHS OIG - Southeastern hospital audit - HHS Office of Inspector General - published 2026-01 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - report summary"
[98]: https://oig.hhs.gov/documents/audit/11461/A-18-22-08021.pdf "HHS OIG - Audit report A-18-22-08021 - HHS Office of Inspector General - published 2026-01 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - highlights and findings"
[99]: https://www.enisa.europa.eu/sites/default/files/publications/Health%20Threat%20Landscape.pdf "ENISA - Health Threat Landscape 2023 - European Union Agency for Cybersecurity - published 2023-07 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - historical - methodology and section 2.1"
[100]: https://content.govdelivery.com/accounts/USDHSCISA/bulletins/40ef439 "CISA - Endpoint management hardening alert - Cybersecurity and Infrastructure Security Agency - published 2026-03-18 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - current - opening and hardening recommendations"
[101]: https://www.sec.gov/Archives/edgar/data/731766/000073176625000063/unh-20241231.htm "UnitedHealth - Form 10-K FY2024 - UnitedHealth Group (SEC) - published 2025 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - historical - p.24, Change Healthcare Cyberattack"
[102]: https://www.england.nhs.uk/synnovis-cyber-incident/questions-and-answers/ "NHS England - Synnovis questions and answers - NHS England - published 2025-11-10 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - H2 2025 - Q1-Q2"
[103]: https://www.audit.gov.ie/en/find-report/publications/2022/12-financial-impact-of-cyber-security-attack.pdf "C&AG Ireland - HSE cyber attack financial impact - Office of the Comptroller and Auditor General, Ireland - published 2022 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - historical - Chapter 12, Figure 12.2 and conclusions"
[104]: https://www.nao.org.uk/reports/investigation-wannacry-cyber-attack-and-the-nhs/ "NAO - WannaCry investigation - National Audit Office - published 2017-10-27 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 1 - historical - key findings on scope, cancellations, preparation and response"
[105]: https://news.bloomberglaw.com/litigation/florida-health-system-agrees-to-542-million-fraud-settlement "Bloomberg Law - Florida health system settlement - Bloomberg Law - published 2026-08-27 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 3 - current - lead only"
[106]: https://www.yahoo.com/news/us/articles/queens-pharmacy-owner-accused-paying-182823716.html "Yahoo News - Queens pharmacy scheme - Yahoo News - published 2026-10-12 - accessed via owner-supplied research 2026-10-27, not re-accessed - Tier 3 - current (last 30 days) - lead only"
