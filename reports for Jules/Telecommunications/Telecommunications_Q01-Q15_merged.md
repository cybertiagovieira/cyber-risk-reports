# Telecommunications - Sector Cyber Resilience & Credit Intelligence Research Q01-Q15 (merged)

**Merge date:** 2026-11-03 | **Merged evidence cut-off:** November 2026 (File A, month precision; earlier of the two, see Section 1.1) | **Status:** Merge of two supplied research files; no new research performed | **Language:** English (UK); both files supplied in English (US spelling converted)

---

## 1. Merge statement

### 1.1 Source files

| Item | File A | File B |
|---|---|---|
| File name | `Telecom_Cyber_Risk_Research_Plan.md` | `Telecom_Sector_Risk_Intelligence.md` |
| Title | Global Telecommunications Sector Cyber Risk Intelligence Report | Telecommunications Sector Risk Intelligence Report: Inherent Exposure Classification and Credit Risk Evidence Base |
| Questions covered (as structured) | Parts 1-9 map to Q01-Q09; Part 10 gaps and limitations | Sections D (fraud, Q10), E Part 2 (Cyber/ICT, Q11), Part 3 (operational resilience and third-party concentration, Q12), Part 4 (governance, Q13), Part 5 (cross-sector, Q14), Sections B and C (classification, Q15); F gaps |
| Research date | Not stated separately | Not stated separately |
| Evidence cut-off | November 2026 (month precision) | 3 November 2026 (exact) |
| Observation horizons | Last 30 days (October - November 2026); rolling 12 months (November 2025 - October 2026); historical landmarks (pre-November 2025) | Last 30 days (October - November 2026); rolling 12 months (November 2025 - November 2026); historical landmarks (C-02) |
| Citations | Numeric superscripts mapped to a 32-item reference list ("Referências citadas") | Numeric superscripts and "[cite: n]" tags mapped to a 45-item reference list; a separate 12-item annotated "Source List" (Section G) |
| Instruction-like text | None. "Issues Requiring Analyst Validation" (Part 9) is analytical guidance for second-line analysts, not an instruction to the merger | None |

**Merged evidence cut-off:** File A states November 2026 without a day; File B states 3 November 2026. The earlier-of-two rule gives **November 2026 (month precision)**; findings carry their own dates and none is presented as later than its source.

**Scope adopted for merged conclusions:** File A defines five subsectors: (1) Mobile Network Operators (MNOs); (2) Fixed-Line & Broadband Service Providers; (3) Subsea Cable & Wholesale Infrastructure Operators; (4) Managed Network, Cloud & UCaaS Providers; (5) Tower Companies & Physical Infrastructure Operators (TowerCos). File B defines four: (1) Wireless MNOs & Mobile Virtual Network Operators (MVNOs); (2) Wireline, Fixed-Line & Broadband Providers; (3) Wholesale Infrastructure, TowerCos & Subsea Cable Operators; (4) Satellite Communications & Specialist Real-Time Communication Providers. The narrower common scope is **MNOs and MVNOs, fixed-line and broadband providers, and wholesale infrastructure (subsea cable, dark fibre, TowerCos)**. File A's managed network, cloud and UCaaS subsector overlaps File B's cloud-hosted real-time communication platforms only for VoIP and session border controllers and is marked **partial scope**; File B's satellite operators and File A's MSSP and SD-WAN services are **outside common scope**; telecom equipment vendors (Ericsson) appear in File B as a fraud case and are **outside common scope** (dependency only) (Section 7.3). Geography: global in both, with detailed EU, UK and US analysis in both; File A adds Ukraine and Australia cases, File B adds Canada and Australia outages.

**Merge statement:** this is a merge only. No web search was performed and no facts, figures, sources, cases, dates or ratings were added. Content is restructured, cross-referenced and converted to UK spelling; citation numbers are replaced with unified S- IDs. Ratings are exactly as proposed in File B.

### 1.2 Step 1 - Inventory

| Inventory item | File A | File B |
|---|---|---|
| Sector definition | Commercial infrastructure, networks and managed services for electronic voice, data, video and internet transmission | Commercial infrastructure, networks, software platforms and operational services for electronic transmission of voice, data, text, video and audio |
| Subsectors | 5 (see 1.1) | 4 (see 1.1) |
| Geography | Global; EU, UK, US detail | Worldwide; EU, UK, US detail |
| Questions covered | Q01-Q09 substantive; Q10 partial (SIM-swap scenario, PROV-007); Q11 partial (control benchmarks); Q12 partial (dependency matrix, supply chain) | Q10-Q15 substantive (no Q10A-Q10D subsections); Q03 partial (SIM swapping); Q05 partial (fraud consequences); Q06 partial (fraud and disclosure rules); Q07 partial (cross-sector contagion) |
| Questions missing or partial | Q13 (governance not analysed), Q14 (no cross-sector comparison), Q15 (A5 "Pending Q10-Q15 research") | Q01-Q09 not in scope of File B; no Q08 questionnaire, no Q09 assembly |
| Sources | 32 references | 45 references + 12-item annotated source list (all 12 duplicate references by URL) |
| Incidents | 6 named (Kyivstar, Optus, AT&T/Snowflake, T-Mobile US, MOVEit, Salt Typhoon) + 1 last-30-days reconnaissance item; register table of 5 | 3 operational disruptions (Rogers 2022, Optus 2023 outage, AT&T 2024 cloud incident) + UK CNI OT benchmark |
| Fraud cases | 0 (SIM-swap typology only) | 4 documented cases (Ericsson, US carriers location data, AT&T, CFCA industry benchmark) + rejected candidates note; 16 typologies; 4 emerging techniques |
| Scenarios | 4 threat scenarios; 3 disruption bands (1, 4, 8 weeks) | 0 |
| Metrics | 5-row metrics table; 3 financial impact cases | 6-row fraud metrics table; 4 Cyber/ICT indicators; outage and CNI metrics |
| Regulatory items | EU/UK/US comparative table (7 features); 3 regional trend notes; further rules in PROV items | 4-row fraud/disclosure statute table |
| Tables | 7 (dependency matrix; incident register; control-weakness matrix; metrics; stress scenarios; regulatory comparison; geopolitical register) | 10 (rating matrix; typology screen; fraud cases; fraud metrics; control failures; statutory requirements; emerging techniques; dependency layers; governance drivers; cross-sector comparison) |
| Ratings / questionnaire | None (A5 pending) / PROV-001 to PROV-010 (Provisional, generic) | Four ratings, all Provisional / None |


### 1.3 Acronyms (defined at first use in this file)

ACFE - Association of Certified Fraud Examiners; AD - Active Directory; APT - advanced persistent threat; API - application programming interface; ARPU - average revenue per user; ASIC - Australian Securities and Investments Commission; BEC - business email compromise; BGP - Border Gateway Protocol; BSS - business support systems; CALEA - US Communications Assistance for Law Enforcement Act; CDR - call detail record; CFCA - Communications Fraud Control Association; CFE - Certified Fraud Examiner; CHIPS - Clearing House Interbank Payments System; CIRCIA - US federal cyber incident reporting statute for essential infrastructure (official name contains a restricted word; cited by acronym); CISA - US Cybersecurity and Infrastructure Security Agency; CLS - cable landing station; CMEK - customer-managed encryption keys; CNI - national infrastructure designated as essential by the UK government (official term cited by acronym); CPNI - customer proprietary network information; CRM - customer relationship management; CSPM - cloud security posture management; DBIR - Verizon Data Breach Investigations Report; DDoS - distributed denial of service; DKIM/DMARC - email authentication standards; DNA - EU Digital Networks Act; DOJ - US Department of Justice; DPA - deferred prosecution agreement; DSIT - UK Department for Science, Innovation and Technology; EBITDA - earnings before interest, taxes, depreciation and amortisation; ECCTA - UK Economic Crime and Corporate Transparency Act 2023; EECC - European Electronic Communications Code; ENISA - EU Agency for Cybersecurity; ERP - enterprise resource planning; FBI - US Federal Bureau of Investigation; FCC - US Federal Communications Commission; FCPA - US Foreign Corrupt Practices Act; FIDO2 - phishing-resistant authentication standard; FTPF - failure to prevent fraud (offence); FTTH/FTTP - fibre to the home / premises; GDPR - EU General Data Protection Regulation; GRE - generic routing encapsulation; GSMA - GSM Association; HLR/HSS - Home Location Register / Home Subscriber Server; HSM - hardware security module; HVAC - heating, ventilation and air conditioning; IC3 - FBI Internet Crime Complaint Center; IMS - IP Multimedia Subsystem; IRSF - international revenue share fraud; IRU - indefeasible right of use; KEV - known exploited vulnerability; LI - lawful intercept; M2M - machine-to-machine; MFA - multi-factor authentication; MNO/MVNO - mobile network operator / mobile virtual network operator; MSS - PRC Ministry of State Security; MSSP - managed security service provider; NCSC - UK National Cyber Security Centre; NEM - network equipment manufacturer; NIS2 - EU Directive (EU) 2022/2555; NMS - network management system; OSS - operations support systems; OT - operational technology; PaaS - platform as a service; PBX - private branch exchange; PRC - People's Republic of China; PROV - provisional questionnaire identifier; RAN - radio access network; RPKI/ROA - Resource Public Key Infrastructure / Route Origin Authorisation; RTO - recovery time objective; SBC - session border controller; SBOM - software bill of materials; SBU - Security Service of Ukraine; SD-WAN - software-defined wide area network; SDNY - US District Court for the Southern District of New York; SEC - US Securities and Exchange Commission; SFO - UK fraud prosecution agency (official name cited by acronym); SLA - service-level agreement; SMB - small and medium-sized business; SOC - security operations centre; SS7 - Signalling System No. 7; TPRM - third-party risk management; TSA - UK Telecommunications (Security) Act 2021; UCaaS - unified communications as a service; USSS - US Secret Service; VoIP - voice over IP; WORM - write once, read many.

**Evidence labels used throughout:** [S-nnn] = unified source ID (Section 10). Evidence-type labels from File A (Confirmed Fact, Analytical Judgement, Scenario Assumption) and File B (Provisional, confidence levels, dataset types) are kept as written. "Merge note" = analysis added during the merge. Where a superscript was attached to a number in the source (e.g. "£100,0005"), the split applied is recorded in Section 7.2.

---

## 2. Executive summary for Senior Credit Officers

**Ratings (File B, all Provisional)**
- **Fraud:** High; Provisional; confidence Medium.
- **Cyber/ICT:** Very High; Provisional; confidence High.
- **Operational resilience / TPRM:** Very High; Provisional; confidence High.
- **Governance / operating model:** High; Provisional; confidence High.

**Five findings**
1. State espionage reached core and lawful intercept systems: Salt Typhoon kept access inside major US carriers for over eight months through unpatched edge routers [S-001, S-002, S-007].
2. Destructive attacks can stop a national network: Kyivstar's December 2023 wiper attack cut service for 24 million users and cost over $100M [S-003, S-004].
3. Cloud credentials without MFA drive mass data theft: AT&T's 2024 Snowflake breach exposed about 109-110 million customers' records and led to a $177M class settlement approved in October 2026 [S-008, S-041, S-044] (C-03).
4. Single outages spread across the economy: Rogers' 15-hour outage (2022) and Optus' 2023 outage hit payments and emergency calls [S-040, S-039].
5. Penalties are large and turnover-based: Ericsson paid over $1.26bn under the FCPA, US carriers $196M for location-data sharing, and UK TSA fines reach 10% of turnover [S-042, S-053, S-005] (C-13).

**Three borrower questions**
1. How are lawful intercept gateways and core routing nodes segregated, and how fast are edge routers patched? (File A)
2. What share of cloud platforms and vendor access points enforce mandatory MFA and credential rotation? (Files A and B)
3. What is the tested recovery time for core switching after a wiper attack or a total provider outage? (Files A and B)

---
## 3. Findings by question

## Q01 - Sector Operating Model & Key Dependencies

*Conclusion (File A): revenue rests on recurring subscriptions, enterprise contracts, wholesale transit and passive leasing, delivered through a small number of core systems (HLR/HSS, lawful intercept gateways, OSS/NMS, BSS) and choke points (signalling hubs, cable landing stations, cloud customer databases) that act as single points of failure. File B's dependency-layer analysis is in Q12 (consistent, except C-17).*

### Q01.1 Subsector operational processes and revenue generation (File A)

Telecommunications operators generate revenue through recurring consumer mobile and fixed subscriptions, enterprise managed network contracts, wholesale bandwidth transit agreements and passive infrastructure leasing. Fixed-line and mobile operators depend on continuous packet routing, session initiation protocols and real-time billing engines to deliver services. Wholesale subsea operators rely on long-term Indefeasible Rights of Use (IRU) contracts and capacity leases across transoceanic fibre backbones. UCaaS and cloud providers rely on multi-tenant data centre hosting and voice-over-IP (VoIP) session border controllers.

### Q01.2 Key IT/OT systems, bottlenecks and single points of failure (File A)

Service delivery relies on an integration of Information Technology (IT) and network Operational Technology (OT). Essential production systems include:
- **Core network switching and routing platforms:** IP Multimedia Subsystem (IMS) and Home Location Register (HLR) / Home Subscriber Server (HSS) databases that maintain mobile subscriber identity and network registration.
- **Lawful Intercept (LI) systems:** specialised infrastructure operated to comply with statutory surveillance obligations, such as Communications Assistance for Law Enforcement Act (CALEA) gateways in the US [S-001].
- **Operations Support Systems (OSS) and Network Management Systems (NMS):** centralised management software controlling physical routers, optical switches and cellular base stations.
- **Business Support Systems (BSS):** customer relationship management (CRM), billing engines and provisioning portals.

System bottlenecks exist at signalling exchange hubs (SS7/Diameter gateways), subsea Cable Landing Stations (CLS) and centralised cloud-hosted customer databases [S-008]. A failure in the HLR/HSS cluster halts network registration for all wireless subscribers, creating a widespread blackout even if physical cell towers remain powered and operational [S-003].

### Q01.3 Essential suppliers and dependency reliance (File A)

Operators rely on upstream energy grids for continuous DC power at central offices and base stations, specialised Network Equipment Manufacturers (NEMs) for proprietary router firmware, Managed Security Service Providers (MSSPs) for security operations centre (SOC) monitoring, and third-party cloud infrastructure for customer analytics and BSS applications [S-002].

### Q01.4 Subsector dependency matrix (File A)

| DEP | Subsector | Business function | Key dependency | Dependency type | Single point of failure | Substitutability | Switching time | Propagation pathway | Evidence type | Primary source (as named) |
|---|---|---|---|---|---|---|---|---|---|---|
| DEP-01 | Mobile Network Operators | Subscriber identity and network registration | Home Subscriber Server (HSS) / HLR | Core OT system | Yes | Low | 24 - 72 hours | Core database corruption halts mobile voice and data sessions nationwide | Confirmed Fact | SBU Disclosures; VEON SEC Filings [S-003] |
| DEP-02 | Mobile Network Operators | Court-ordered surveillance | Lawful Intercept (CALEA) gateways | Regulatory OT | Yes | None | Non-substitutable | Gateway compromise provides lateral access into core transit routers | Confirmed Fact | CISA Advisory AA25-239A [S-002] |
| DEP-03 | Fixed-Line & Broadband | Core IP routing and traffic transit | Border Gateway Protocol (BGP) / edge routers | Network IT/OT | Yes | Medium | 4 - 12 hours | Edge router firmware compromise enables covert traffic redirection | Confirmed Fact | CISA / FBI Advisories [S-002] |
| DEP-04 | Wholesale & Subsea | Transoceanic data transmission | Cable Landing Stations (CLS) and power feed gear | Physical / OT infrastructure | Yes | Low | Weeks to months | Physical or cyber compromise at CLS severs international data backhaul | Analytical Judgement | ENISA Subsea Cable Report [S-012] |
| DEP-05 | Managed Cloud & UCaaS | Customer analytics and storage | Third-party cloud data warehouses | Cloud IT | No | Medium | 1 - 7 days | Compromised API credentials allow mass exfiltration of subscriber records | Confirmed Fact | SEC Form 8-K Filings [S-008] (C-14) |
| DEP-06 | TowerCos | Passive site management | Remote telemetry and HVAC systems | OT / IoT systems | No | High | 12 - 24 hours | Telemetry compromise disables site cooling, forcing safety power shutdowns | Scenario Assumption | Analytical Assessment |

**Cross-references:** Q07, Q12 (File B dependency layers merged into DEP-04, DEP-05 and new DEP-07, DEP-08), Q08; DEP register; conflicts C-14, C-17.

---

## Q02 - Major Cyber Incidents & Case Studies

*Conclusion (File A): the decision-relevant incidents are state espionage inside core and lawful intercept networks (Salt Typhoon), a destructive wiper blackout (Kyivstar) and mass customer-data theft through cloud credentials and unauthenticated APIs (AT&T/Snowflake, Optus, T-Mobile US). File B adds outcome detail for AT&T (US$177M settlement, Oct 2026) and two non-cyber outages (Rogers 2022, Optus 2023) recorded in Q12.*

### Q02.1 Historical landmarks (File A)

1. **Kyivstar infrastructure blackout (Ukraine, December 2023):** a Russian state-sponsored cyber attack (attributed to Sandworm / GRU Unit 74455) wiped virtualised core infrastructure, switches and subscriber databases [S-003]. The attack caused a nationwide service outage for over 24 million mobile and fixed subscribers, disabling air-raid alert systems and point-of-sale banking terminals [S-003]. Financial losses exceeded $100M+ in direct remediation, customer compensation and lost revenue [S-004].
2. **Optus unauthenticated API breach (Australia, September 2022):** cyber criminals exploited an unauthenticated, internet-facing API endpoint to exfiltrate personal identity records for approximately 10 million customers [S-008]. Remediation costs exceeded AU$140 million (~$90 million USD), triggered Australian privacy law reforms and led to the resignation of the Chief Executive Officer [S-008].
3. **AT&T / Snowflake cloud data exfiltration (United States, July 2024):** attackers used stolen single-factor credentials to access an AT&T environment hosted on Snowflake's cloud platform [S-008]. The actors exfiltrated call and text message metadata belonging to nearly 110 million wireless customers [S-008] (C-03). The incident resulted in a $13 million FCC consent decree and extensive credit monitoring liabilities [S-008] (C-05).
4. **T-Mobile US customer data intrusions (United States, August 2021 & January 2023):** credential exploitation and API vulnerabilities enabled malicious actors to steal data belonging to over 76 million customers across multiple events [S-008]. T-Mobile agreed to a $350 million class-action settlement and committed to a mandatory $150 million cybersecurity capital expenditure programme [S-008].
5. **MOVEit Transfer supply-chain campaign (global, May 2023):** the Cl0p ransomware group exploited a zero-day SQL injection vulnerability (CVE-2023-34362) in Progress MOVEit Transfer software [S-008]. The vulnerability impacted over 2,700 organisations globally, including multiple telecom carriers and billing clearinghouses, demonstrating supply-chain risk propagation across regulated enterprise environments [S-008].

### Q02.2 Last 12 months and last 30 days trends (File A)

- **Rolling last 12 months (November 2025 - October 2026):** the sector has been dominated by the Salt Typhoon advanced persistent threat (APT) campaign [S-001]. PRC state-sponsored actors maintained covert persistence inside major US telecommunications networks for over eight months [S-007]. Actors targeted perimeter network hardware (Cisco, Ivanti, Fortinet) to access CALEA wiretap systems, call detail records (CDRs) and communications of high-profile political figures [S-001].
- **Last 30 days (October - November 2026):**
  - *Update:* joint CISA/FBI guidance updates confirm that eviction of Salt Typhoon actors remains challenging due to deep firmware persistence and compromised edge-router administrative credentials across global carrier transit links [S-002].
  - *New:* elevated reconnaissance against subsea cable landing station operational management networks in South-East Asia and the Mediterranean, indicating expanded targeting of wholesale transport infrastructure [S-012].
- **File B last-30-days item:** final approval of the AT&T class action settlement (US$177M), order dated 2 October 2026 [S-041, S-044] (Q10.2).

### Q02.3 Deduplicated incident register (File A; merged register in Section 4.1)

| INC | Organisation | Subsector | Country | Incident date | Disclosure date | Attack type | Incident class | Known initial access | Exploited weakness | Attribution | Attribution confidence | Affected systems | Operational disruption | Recovery duration | Financial loss | Regulatory consequence | Primary source (as named) |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| INC-02 | Kyivstar | Mobile / Fixed | Ukraine | Dec 2023 | Dec 2023 | Destructive wiper | Operational outage | Stolen employee credentials | Lack of MFA on internal admin portal | Sandworm (GRU Unit 74455) | High (SBU / UK NCSC) | Core switches, HLR/HSS, virtualised servers | Complete network blackout for 24M users | 7 - 10 days (C-07) | $100M+ (EBITDA / remediation) | National security investigation | SBU / VEON SEC Filings [S-003] |
| INC-03 | AT&T | Mobile / Fixed | US | Apr 2024 | Jul 2024 | Cloud data exfiltration | Intrusion | Stolen third-party cloud credentials | Absent MFA on cloud data warehouse | Threat Actor / ShinyHunters (C-04) | High (SEC Filings) | Snowflake-hosted data warehouse | None (silent data theft) | N/A | $13M+ (Settlement + Legal) (C-05) | $13M FCC Consent Decree | SEC Form 8-K / FCC Order [S-008] |
| INC-04 | Optus | Mobile / Fixed | Australia | Sep 2022 | Sep 2022 | API data exfiltration | Intrusion | Unauthenticated web API | Exposed test API endpoint without access controls | Threat Actor / "Unlutid" | Medium | Customer database API | None (silent data theft) | 2 - 3 days | AU$140M+ (~$90M USD) | Privacy Act Enforcement / ASIC Review | ASIC / Singtel Filings [S-008] |
| INC-05 | T-Mobile US | Mobile | US | Jan 2023 | Jan 2023 | API data abuse | Intrusion | Malicious API abuse | Inadequate API rate limiting and authentication | Unattributed cyber criminal | Medium | Customer API gateways | None | 1 - 2 days | Part of $500M total settlement/capex | FCC investigation / class action | SEC Filings / FCC Consent [S-008] |
| INC-01 | US telecom carriers | Wholesale / Mobile / Fixed | US | Aug 2024 | Oct 2024 | State espionage / wiretap breach | Intrusion | Edge router vulnerabilities | Unpatched Cisco IOS XE / weak router authentication | Salt Typhoon (PRC MSS) | High (FBI / CISA Joint Advisory) | CALEA wiretap portals, core IP routers | Silent interception / metadata theft | Multi-month eviction effort | High (national security cost / capex) | Senate briefings / FCC mandatory remediation | CISA AA25-239A / FBI Advisory [S-001] |

### Q02.4 Top-five decision-relevant incidents (File A ranking)

1. **Salt Typhoon telecom campaign (2024-2026) - INC-01:** demonstrates nation-state access to lawful intercept infrastructure, proving that statutory access points represent severe operational and national security liabilities [S-001].
2. **Kyivstar cyber blackout (2023) - INC-02:** the global benchmark for catastrophic cyber-warfare impact on telecom cash flows, EBITDA and nationwide societal continuity [S-003].
3. **AT&T cloud data breach (2024) - INC-03:** illustrates how third-party cloud outsourcing without enforced MFA can expose metadata for over 100 million subscribers, triggering direct regulatory sanctions [S-008].
4. **Optus API security failure (2022) - INC-04:** highlights the very large financial loss (AU$140M+; source wording reworded) and reputational damage resulting from basic software development and API governance oversights [S-008].
5. **T-Mobile US security settlements (2021-2023) - INC-05:** highlights the cumulative financial drag of recurring data breaches, forcing hundreds of millions in legally binding security capex [S-008].

### Q02.5 Detailed case studies (File A)

**Case Study 1 - Salt Typhoon core network and wiretap compromise (INC-01).**
- *Selection rationale:* high sector relevance, demonstrating nation-state exploitation of core telecommunications routing and lawful surveillance infrastructure [S-001].
- *Timeline:* 2022 - 2023: initial undetected access established across major carrier edge infrastructure [S-007]. August 2024: the FBI identifies malicious activity inside US telecommunications networks [S-007]. October 2024: public disclosure confirms AT&T, Verizon, T-Mobile and Lumen Technologies were breached [S-001]. August 2025 - 2026: CISA and FBI issue Joint Advisory AA25-239A detailing remediation and ongoing eviction challenges [S-002].
- *Initial access and mechanism:* actors exploited unpatched vulnerabilities in internet-facing network hardware (e.g. Cisco IOS XE web UI flaws CVE-2023-20198 and CVE-2023-20273, Ivanti VPNs and Fortinet edge appliances) [S-002]. They maintained persistence by deploying custom router rootkits (Demodex) and backdoors (GhostSpider) [S-002].
- *Exploited weaknesses:* delayed security patching of perimeter network hardware, weak router administrative access controls and insufficient network segmentation between surveillance gateways and general IP backbones [S-002].
- *Operational and financial effects:* carriers were required to divert significant engineering capital toward hardware replacement, extensive forensics and network re-architecting [S-007]. While immediate subscriber traffic was uninterrupted, long-term credit profiles are burdened by mandatory infrastructure upgrades [S-007].
- *Regulatory outcomes:* prompts strict enforcement of edge-device patching protocols by CISA and the FCC, alongside mandatory audits of lawful intercept access controls [S-007].
- *What it does not establish:* that consumer mobile data traffic suffered catastrophic physical outages or wiper activity.

**Case Study 2 - Kyivstar infrastructure wiper blackout (INC-02).**
- *Selection rationale:* the most severe documented case of cyber-induced operational disruption and physical switch wiping in telecommunications history [S-003].
- *Timeline:* May 2023: initial unauthorised entry into Kyivstar's internal network [S-016]. 12 December 2023: Sandworm actors activate destructive wiper scripts, destroying core switches, virtual machines and billing nodes [S-003]. 20 December 2023: basic mobile voice and data services restored after manual re-configuration [S-003].
- *Initial access and mechanism:* compromise of an employee's administrative account credentials [S-011]. Attackers moved laterally across internal systems for seven months, mapping virtualised infrastructure before triggering coordinated wipe commands [S-016].
- *Exploited weaknesses:* compromised privileged account credentials lacking multi-factor authentication, inadequate internal anomaly monitoring, and centralised backup infrastructure exposed to the same administrative domain [S-011].
- *Operational and financial effects:* 24 million mobile users lost service; ATM networks, retail payment terminals and municipal air-raid warning systems failed across parts of Ukraine [S-003]. Parent company VEON reported lost revenue and customer retention compensation expenses exceeding $100M USD [S-004].
- *Regulatory outcomes:* triggered a nationwide review of essential national infrastructure by the SBU and European telecom security regulators (source wording reworded) [S-003].
- *What it does not establish:* that commercial carriers operating outside active military conflict zones face identical threat actor motivations, though technical tactics remain transferable.

**Case Study 3 - Optus unauthenticated API breach (INC-04).**
- *Selection rationale:* demonstrates how a simple software configuration vulnerability can trigger immediate executive turnover, regulatory investigations and massive cash costs [S-008].
- *Timeline:* 17 September 2022: actor identifies an exposed, unauthenticated API endpoint used for customer identity validation. 22 September 2022: Optus discovers automated exfiltration of customer records and publicly discloses the breach [S-008]. November 2022: Singtel (parent company) discloses initial AU$140M financial impact [S-008].
- *Initial access and mechanism:* web-crawling identified an unauthenticated domain name pointing directly to a production API database containing identity documents [S-008].
- *Exploited weaknesses:* failure to implement API authentication mechanisms, lack of access control testing before moving test interfaces into production environments, and ineffective rate limiting [S-008].
- *Operational and financial effects:* over 10 million identity files stolen, requiring Optus to fund replacement passports and driver's licences for millions of citizens [S-008]. Total remediation, legal and consulting costs exceeded AU$140M (~$90M USD) [S-008].
- *Regulatory outcomes:* led directly to Australia amending its Privacy Act to drastically raise maximum non-compliance penalties to AU$50M+ or 30% of adjusted turnover [S-008].
- *What it does not establish:* core network transit failure or physical service interruption.

**Cross-references:** Q03, Q05, Q07, Q10 (FRD-03 linked to INC-03), Q12 (INC-07, INC-08); INC register; conflicts C-03 to C-08, C-11.

---

## Q03 - Cyber Threat Landscape & Attack Scenarios

*Conclusion (File A): four prioritised scenarios - state espionage via edge hardware into lawful intercept, destructive wipers against core switching, third-party cloud and API data exfiltration, and cyber-enabled vishing and SIM swapping - all enabled by patching delays, missing MFA, weak segmentation and weak identity checks. File B's Cyber/ICT indicators (Q11) are consistent.*

### Q03.1 Prioritised threat scenarios (File A)

**THR-01 - State-sponsored core network and lawful intercept espionage.**
- Mechanism tag: targeted operational disruption and covert intelligence collection via perimeter network hardware [S-001].
- Threat actors and motivations: state-aligned APTs (e.g. Salt Typhoon / PRC MSS) seeking strategic intelligence, surveillance metadata and political communications [S-001].
- Attack path: exploit unpatched vulnerabilities in edge network routers (Cisco, Ivanti, Fortinet) -> establish persistence via custom rootkits -> move laterally into CALEA / lawful intercept management segments -> exfiltrate call detail records (CDRs) and intercept communications [S-002].
- Enabling weaknesses: lagging patch management cycles for edge routers, weak network segmentation between surveillance gateways and general IP backbones, and unmonitored administrative access [S-002].
- Trend direction: Increasing (High Confidence) [S-002].

**THR-02 - Destructive wiper attack on core switching and HLR/HSS.**
- Mechanism tag: targeted operational disruption.
- Threat actors and motivations: state-sponsored military intelligence units (e.g. Sandworm / GRU) or destructive hacktivists seeking economic disruption or military advantage [S-003].
- Attack path: phishing / stolen privileged credentials -> lateral movement via Active Directory / SSH -> map hypervisors, Home Subscriber Servers (HSS) and NMS software -> execute mass wiper payload to overwrite boot sectors and database tables [S-003].
- Enabling weaknesses: absence of MFA on privileged domain administrative accounts, unsegmented management networks, and online backups vulnerable to single-sign-on privilege escalation [S-011].
- Trend direction: Stable to Increasing in high-risk regions (High Confidence).

**THR-03 - Third-party cloud and API customer data exfiltration.**
- Mechanism tag: third-party supply-chain concentration and exposure [S-008].
- Threat actors and motivations: financially motivated cyber criminals and data-broker extortionists (e.g. ShinyHunters, Cl0p) [S-008].
- Attack path: purchase compromised cloud storage credentials on dark web markets -> bypass single-factor authentication -> execute automated database queries via unauthenticated web APIs -> exfiltrate bulk subscriber data -> demand ransom / leak data [S-008].
- Enabling weaknesses: lack of mandatory MFA on cloud infrastructure accounts, inadequate API security hygiene, lack of data tokenisation, and centralised third-party data reliance [S-008].
- Trend direction: Stable (High Confidence) [S-008].

**THR-04 - Cyber-enabled vishing and retail portal SIM swapping.**
- Mechanism tag: operational fraud and access broker exploitation [S-017].
- Threat actors and motivations: cyber-criminal groups targeting high-value enterprise and consumer financial accounts.
- Attack path: voice phishing (vishing) or social engineering of carrier customer service representatives -> gain unauthorised access to retail CRM applications -> execute unauthorised SIM swap -> intercept two-factor authentication (2FA) SMS codes to breach subscriber bank accounts [S-017].
- Enabling weaknesses: weak identity validation procedures at retail stores and call centres, lack of behavioural biometrics, and unsegmented retail CRM portals [S-017].
- Trend direction: Increasing (Medium Confidence).
- File B links: SIM swapping and port-out fraud typology (cyber-enabled, sector-specific) and automated SIM-swapping as an emerging technique (Q10.1, Q10.8); SIM-swap compromise via retail portal credentials or bribed agent staff (Q11.2) [S-038].

### Q03.2 Control-weakness matrix (File A)

| CTL | Control weakness area | Enabled threat scenario | Documented incidents | Affected systems | Operational risk impact |
|---|---|---|---|---|---|
| CTL-W1 | Unpatched edge network firmware | Core network espionage (THR-01) | Salt Typhoon campaign | Border routers, VPN gateways, CALEA nodes | Unauthorised surveillance and loss of competitive/regulatory standing [S-001] |
| CTL-W2 | Absent / ineffective MFA on admin portals | Wiper outage and cloud exfiltration (THR-02, THR-03) | Kyivstar, AT&T / Snowflake | Hypervisors, Active Directory, cloud data warehouses | Total network blackout or massive third-party data breach [S-008] |
| CTL-W3 | Unauthenticated / unprotected APIs | Bulk subscriber data exfiltration (THR-03) | Optus, T-Mobile US | BSS databases, customer CRM portals | Multi-million dollar remediation costs and statutory fines [S-008] |
| CTL-W4 | Weak retail identity validation (source wording reworded) | SIM-swapping and vishing fraud (THR-04) | Global vishing schemes | Retail CRM, mobile number porting portals | Customer litigation, reputational damage, direct fraud loss [S-017] |
| CTL-W5 | Single-domain backup repositories | Bare-metal recovery failure (THR-02) | Kyivstar | Backup servers, SAN storage | Multi-week recovery delays following wiper attacks [S-011] |

**Cross-references:** Q02, Q04, Q07, Q10, Q11 (consistency check 3); THR and CTL registers.

---

## Q04 - Control Weaknesses, Resilience Capabilities & Benchmarks

*Conclusion (File A): Priority 1 capabilities are edge-hardware hardening and emergency patching, MFA on all administrative interfaces and network micro-segmentation; supervisors (Ofcom, CISA, ENISA) report recurring gaps in edge patching, lawful intercept isolation and API visibility. File B adds documented control failures in fraud governance (Q10.5) and the conditions under which its ratings would fall (Q15.4).*

### Q04.1 Priority ranking of key capabilities (File A)

**Priority 1 - high-impact / baseline defence capabilities**
1. **CTL-C1 Perimeter network hardware hardening and emergency patching:** protects edge routing and CALEA infrastructure from covert compromise [S-002]. Mitigates core espionage scenarios (Salt Typhoon) [S-002]. Absence results in long-running stealth intrusion and loss of integrity in lawful intercept systems [S-002]. Mandatory under UK TSA Tier 1/2 [S-005] and EU NIS2 [S-006].
2. **CTL-C2 Multi-factor authentication (MFA) across all administrative interfaces:** secures domain access, cloud consoles and virtualised management planes [S-008]. Mitigates destructive wiper attacks and cloud exfiltration [S-008]. Absence results in direct credential-based takeover of core operations (Kyivstar, AT&T) [S-008]. Mandatory across all jurisdictions [S-006].
3. **CTL-C3 Network micro-segmentation (IT vs OT vs CALEA vs BSS):** isolates commercial IP backbones from internal switching and surveillance gateways [S-002]. Mitigates lateral movement from compromised edge routers to internal systems [S-002]. Absence results in rapid propagation of wipers or surveillance tools [S-002].

**Priority 2 - operational continuity and monitoring capabilities**
4. **CTL-C4 API gateway security and continuous authentication:** secures digital customer portals and external software integrations [S-008]. Mitigates automated bulk exfiltration of subscriber data [S-008]. Absence results in mass privacy leaks, executive resignation and privacy fines (Optus) [S-008].
5. **CTL-C5 Air-gapped immutable backups and bare-metal recovery testing:** enables rapid restoration of core switches, subscriber identity databases (HLR/HSS) and billing platforms [S-011]. Mitigates destructive wiper attacks [S-011]. Absence results in extended multi-week network blackouts [S-003].

**Priority 3 - advanced defence and supply chain assurance (source heading reworded)**
6. **CTL-C6 Third-party cloud security governance and log monitoring:** ensures external vendors adhere to enterprise access standards [S-008]. Mitigates supply-chain credential abuse [S-008]. Absence results in regulatory sanctions for unmonitored partner environments [S-008].

### Q04.2 Sector control benchmarks and supervisory findings (File A)

Supervisory reviews by Ofcom (UK) [S-020], CISA (US) [S-002] and ENISA (EU) reveal recurring implementation gaps:
- **Edge device maintenance:** telecommunications operators frequently fail to patch perimeter network hardware within recommended 14-day windows due to uptime commitments and complex maintenance windows, leaving routers exposed to state APT zero-days [S-002].
- **Surveillance system isolation:** lawful intercept infrastructure is too often connected to main enterprise management networks rather than physically or cryptographically isolated, creating direct access vectors for state actors [S-001].
- **API visibility gaps:** rapid deployment of web-based customer portals has led to "shadow APIs" operating outside centralised security governance [S-008].

**File B links:** control failures in access control, segregation of duties, vendor onboarding, real-time traffic inspection and subsidiary oversight (Q10.5); FIDO2 MFA and edge-device conditions in rating sensitivities (Q15.4).

**Cross-references:** Q03, Q06, Q08, Q10, Q11, Q15; CTL register.

---

## Q05 - Financial Impact, Disruption & Credit Transmission

*Conclusion (File A): cyber incidents transmit to credit through liquidity drain, EBITDA contraction, capex displacement and covenant pressure; documented cases range from a US$13M FCC consent decree (AT&T) to AU$140M+ (Optus) and over $100M with a >50% quarterly EBITDA fall (Kyivstar). File B adds fraud and enforcement consequences (US$1.26bn Ericsson, US$196M location-data fines, US$177M AT&T settlement), recorded in Q10.6 without double counting (check 5).*

### Q05.1 Sector-specific cyber risk metrics (File A)

| FIN | Metric | Benchmark value | Sample / population | Method and source | Limitations |
|---|---|---|---|---|---|
| FIN-A01 | Average cost of a data breach | $4.88M - $5.00M | Global communications sector baseline | IBM / Ponemon annual breach cost study [S-021] | Excludes mega-breaches (>10M records); based on external estimates |
| FIN-A02 | Mega-breach costs (>10M records) | $90M - $140M+ | Publicly disclosed telecom breaches (Optus, T-Mobile) | SEC filings / ASIC regulatory disclosures [S-008] | Highly skewed by legal settlements and capital projects |
| FIN-A03 | Regulatory fine caps (UK TSA) | Up to 10% of global annual turnover (C-09) | All Tier 1/2 UK public telecoms providers | UK Telecommunications Security Act 2021 [S-005] | Represents statutory maximum penalty, not average historical fine |
| FIN-A04 | Regulatory fine caps (EU NIS2) | Up to €10M or 2% of global annual turnover | Essential entities in EU telecoms sector | EU NIS2 Directive (2022/2555) [S-006] | Subject to member-state transposition variations |
| FIN-A05 | Outage recovery duration | 7 to 14 days for core restoration (C-07) | Destructive wiper incidents (Kyivstar) | Victim financial and regulatory disclosures [S-003] | Applies specifically to catastrophic wiper attacks during kinetic warfare |

### Q05.2 Documented financial and credit impact cases (File A)

- **Kyivstar (2023) - FIN-A06:** disclosed local-currency EBITDA contraction of over 50% during the primary outage quarter, driven by lost billing, waived customer fees and manual switch rebuilding costs [S-004].
- **Optus (2022) - FIN-A07:** Singtel financial disclosures confirmed AU$140M+ in direct costs for customer identity replacement programmes, independent forensic audits, external legal counsel and public relations remediation [S-008].
- **AT&T (2024) - FIN-A08:** entered into a $13 million consent decree with the FCC to resolve investigations into cloud data warehouse security posture [S-008] (C-05; File B's US$177M class settlement is FIN-B12).

### Q05.3 Credit risk transmission channels (File A)

1. **Cash conversion and liquidity drain:** emergency response, forensic retainers and customer notification expenses cause immediate cash outflows, reducing short-term liquidity cushions.
2. **EBITDA and margin contraction:** waived billing fees during network outages directly reduce quarterly revenue while operational expenses spike, leading to EBITDA margin compression.
3. **Capex displacement:** post-incident regulatory decrees often compel operators to commit substantial cash toward mandated cybersecurity upgrades, displacing planned capital deployment for 5G network expansion and fibre-to-the-home (FTTH) roll-outs [S-008].
4. **Debt service coverage and covenant pressure:** reductions in EBITDA paired with heightened capex squeeze interest coverage ratios (EBITDA / interest expense) and leverage ratios (net debt / EBITDA), increasing the probability of debt covenant breaches.

**File B consequences (Q10.6):** cash drains from unrecoverable wire transfers, penalties and settlements; reduced liquidity buffers, higher debt-to-EBITDA and interest coverage covenant risk; debarment from public procurement; churn and higher acquisition spending [S-042, S-053, S-041, S-035, S-046]. Lender consequences per dimension are in the File B rating matrix (Q15.2).

### Q05.4 Illustrative disruption stress scenarios (File A) - *Illustrative - not a forecast or loss estimate*

*File A note: the following scenarios are illustrative models designed for credit sensitivity testing; they are not forecasts or historical loss estimates.*

| SCN | Scenario horizon | Affected operational processes | Operational consequences | Financial transmission | Credit impact and channels | Potential offsets | Key assumptions | Required borrower data | Early signposts |
|---|---|---|---|---|---|---|---|---|---|
| SCN-1 | 1-week disruption | BSS billing, web portals, retail SIM porting | Temporary pause in online subscriber onboarding and billing collection; core voice/data unaffected | Minor revenue deferred; elevated call-centre overtime costs | Negligible impact on debt service; short-term working capital friction | Cyber insurance coverage for operational interruption | Core packet switching remains functional throughout | Availability of emergency credit facility | Spike in customer care queue wait times |
| SCN-2 | 4-week disruption | Enterprise managed services, UCaaS, fixed broadband routing | Partial loss of enterprise SLAs; regional broadband network outages; customer churn to competitors | SLA penalty payouts; direct revenue loss; emergency vendor retainers ($10M - $30M) | EBITDA compression of 5 - 15% for the affected quarter; tightened leverage headroom | Contractual liability caps in enterprise service contracts | Backups exist but require slow sequential manual restoration | Ratio of contracted enterprise revenue to consumer revenue | Unscheduled network degradation advisories |
| SCN-3 | 8-week disruption | Complete core network (HLR/HSS, IMS, base station controller NMS) | Total nationwide mobile and fixed blackout; loss of voice, SMS, data and emergency routing | Complete revenue freeze during blackout; $100M+ direct remediation; mass regulatory fines | Severe EBITDA drop (>40%); potential debt covenant breach; credit rating downgrade | Government emergency liquidity subsidies or parent guarantees | Threat actor successfully wipes both active and primary backup systems | Bare-metal recovery time objectives and offsite backup locations | Formal regulatory notice of mandatory network isolation |

**Cross-references:** Q02, Q10, Q12, Q15; FIN and SCN registers; reconciliation check 5.

---

## Q06 - Regulation & Resilience Expectations

*Conclusion (File A): EU NIS2, the UK TSA 2021 and Code of Practice, and US FCC CPNI breach rules set turnover-based fines (up to 10% UK; €10M or 2% EU), short reporting windows (24/72 hours EU; 7 business days US) and supply-chain and board duties. File B adds fraud and disclosure statutes (UK failure to prevent fraud, EU Anti-Corruption Directive, FCPA, SEC Form 8-K Item 1.05) in Q10.7.*

### Q06.1 Jurisdiction-by-jurisdiction comparative framework (File A)

| Feature / requirement | European Union (EU) | United Kingdom (UK) | United States (US) |
|---|---|---|---|
| Primary regulatory instrument | NIS2 Directive (EU 2022/2555) and Digital Networks Act proposals [S-006] | Telecommunications Security Act 2021 (TSA) and Code of Practice v1.1 (2026) [S-005] (C-10) | FCC Data Breach Order (47 CFR Part 64) and CIRCIA [S-018] |
| Competent regulatory body | National NIS2 authorities / ENISA [S-006] | Ofcom (Office of Communications) [S-005] | Federal Communications Commission (FCC) / CISA [S-014] |
| Scope and tiering | Essential entities (all medium and large public electronic communications) [S-006] | Tier 1 (turnover ≥£1B), Tier 2 (£50M - £1B), Tier 3 (<£50M) [S-005] | Covered telecommunications carriers and commercial mobile radio services [S-018] |
| Incident reporting deadlines | 24-hr early warning; 72-hr full incident notification [S-006] | Immediate notification to Ofcom for significant operational breaches [S-005] | 7 business days to FBI/USSS before customer notice; rapid CISA reporting [S-018] |
| Statutory fine penalties | Up to €10M or 2% of global annual turnover, whichever is higher [S-006] | Up to 10% of relevant annual turnover, plus daily fines up to £100,000 [S-005] (C-09) | Regulatory enforcement consent decrees and monetary forfeiture penalties [S-008] |
| Supply chain assurance mandates | Mandatory risk assessments for ICT third-party vendors [S-006] | Statutory requirement to flow down TSA controls to Tier 1/2 suppliers [S-005] | Voluntary CISA performance goals; mandatory federal supply-chain bans |
| Management board liability | Personal liability for board members failing risk oversight duties [S-006] | Corporate accountability enforced via Ofcom compliance assessments [S-005] | SEC governance disclosure rules and corporate officer consent decrees |

### Q06.2 Regulatory trends and enforcement priorities (File A)

- **United Kingdom:** Ofcom is actively monitoring Tier 1 and Tier 2 compliance milestones under the Telecommunications Security Act Code of Practice [S-005]. Operators failing to demonstrate proper isolation of network management tools face fines up to 10% of turnover [S-005].
- **European Union:** the transition from the EECC Article 40 framework to NIS2 has expanded regulatory supervision to include wholesale carriers and data centre operators, introducing direct director liability for cybersecurity oversight failures [S-006].
- **United States:** the FCC's updated CPNI rules under 47 CFR Part 64 remove historical safe harbours, requiring rapid 7-day federal law enforcement notifications for breaches involving customer proprietary network information [S-018].

### Q06.3 File B regulatory items (cross-referenced)

UK ECCTA failure to prevent fraud offence (in force 1 September 2025); EU Anti-Corruption Directive (EU) 2026/1021 (transposition deadline 1 June 2028); US FCPA; SEC Form 8-K Item 1.05 (four business days; effective December 2023) - full table in Q10.7. Telecommunications Security Code of Practice (DSIT/Ofcom): published 1 December 2022 (entry into force), re-issued 14 July 2026 [S-074] (C-10). Regulatory liability intensity comparison in Q14.

**Cross-references:** Q04, Q08, Q10.7, Q13, Q14; REG register; conflicts C-09, C-10, C-16.

---

## Q07 - Geopolitical Cyber Threats & Systemic Exposure

*Conclusion (File A): US-China technology competition (Salt Typhoon) and the Russia-Ukraine war (Sandworm) are active, high-confidence drivers; Middle East DNS hijacking and state-sponsored hacktivist DDoS add medium-to-high confidence exposure. Telecom outages propagate to finance, energy and emergency services; File B's Rogers and Optus outages confirm the payment and emergency-call pathways (Q12).*

### Q07.1 Geopolitical threat register (File A)

| GEO | Geopolitical driver | Campaign / activity | Attribution source and confidence | Status | Exposed subsectors and regions | Primary attack mechanism | Early warning indicators | Primary source (as named) |
|---|---|---|---|---|---|---|---|---|
| GEO-01 | US-China strategic technology competition | Salt Typhoon (OPERATOR PANDA) core intrusion | CISA, FBI, NSA (Joint Advisory) - High Confidence | Active / Observed | US and global MNOs, fixed backbones | Exploitation of unpatched edge routers to access CALEA wiretap networks | Unexplained GRE tunnels and admin login anomalies on edge hardware | CISA AA25-239A / FBI Alerts [S-002] |
| GEO-02 | Russia-Ukraine war and regional conflict | Sandworm destructive wiper operations | Security Service of Ukraine (SBU), UK NCSC - High Confidence | Active / Observed | Eastern European telcos, energy interconnects | Stolen domain admin credentials used to execute bare-metal switch wipers | Phishing campaigns targeting network administrator credentials | SBU / UK NCSC Bulletins [S-003] |
| GEO-03 | Middle East regional tensions | DNS hijacking and traffic redirection | Hunt & Hackett, ENISA - Medium Confidence | Active / Observed | European and Middle Eastern carriers, government networks | Compromise of domain registrar accounts to alter DNS routing tables | Unauthorised modifications to glue records and external DNS zones | CERT-EU / ENISA Threat Intel [S-017] |
| GEO-04 | State-sponsored hacktivism | Distributed denial of service (DDoS) volumetric attacks | National cyber security agencies - High Confidence | Active / Observed | European MVNOs, cloud UCaaS platforms | Multi-terabit volumetric botnet flooding targeting Border Gateway Protocol (BGP) | Escalation in geopolitical rhetoric followed by SYN-flood anomalies | European Cyber Authorities [S-029] |

### Q07.2 Systemic and correlated exposure pathways (File A)

Telecommunications networks serve as the foundational transmission layer for all other essential infrastructure sectors (source wording reworded). Correlated cross-sector disruption propagates through three primary vectors:
1. **Financial sector connectivity:** interruption of mobile data networks disables two-factor authentication SMS delivery and point-of-sale card processing terminals across retail banking [S-003].
2. **Energy and power grid telemetry:** power distribution automation relies on cellular M2M (machine-to-machine) and fixed leased lines; a telco core blackout blinds electrical grid operators to line faults [S-029].
3. **Emergency services and public safety:** disruption to core mobile voice infrastructure disables access to emergency call networks and municipal alert systems [S-003].

**File B propagation evidence:** operational disruptions within major operators propagate into payment rails, transportation signalling, emergency dispatch and enterprise cloud operations [S-039]; Rogers (2022) paralysed Interac payments and 911 access [S-040]; Optus (2023) failed over 600 emergency calls [S-039]; SIM-swap compromise enables downstream account takeovers of corporate banking and ERP systems across sectors [S-038] (Q11, Q12).

**Cross-references:** Q02, Q03, Q11, Q12; GEO register; DEP register (propagation column).

---

## Q08 - Provisional Questionnaire-to-Sector Mapping

*Conclusion (File A): ten generic, Provisional control items (PROV-001 to PROV-010) cover edge patching, lawful intercept isolation, MFA, APIs, backups, cloud governance, SIM-swap controls, BGP/signalling, software supply chain and board readiness. No supplied questionnaire was used. Merged links to File B fraud records are added.*

*File A note: the control mapping is generic and labelled "Provisional" (identifiers PROV-001 through PROV-010). It is designed to assist Senior Credit Officers during client engagements. Adverse responses indicate analytical risk areas, not automatic credit rejection.*

**PROV-001 - Perimeter edge hardware patching and maintenance.** Control area: vulnerability and patch management. Potential weakness: delayed deployment of vendor security updates on internet-facing edge routers and VPN gateways. Related threat scenarios: state-sponsored core espionage (Salt Typhoon) [S-001]. Key dependencies: hardware network equipment manufacturers (NEMs). Regulatory expectations: UK TSA Code of Practice Section 2 [S-019] (parse of "Section 219" ambiguous, C-16); EU NIS2 risk management obligations [S-006]. Plausible operational and credit consequence: undetected persistent foreign state access leading to regulatory enforcement, emergency capital expenditure and potential fine exposure [S-002]. Materiality conditions: highly material for Tier 1 / Tier 2 public operators carrying nation-state transit or government traffic. Follow-up questions: (1) What is the average time-to-patch for high-severity vulnerabilities affecting edge routing hardware (source wording reworded)? (2) How does the organisation maintain operational availability while applying emergency zero-day patches to core edge nodes? Practical improvements: establish automated firmware vulnerability scanning and off-path emergency maintenance windows. Specialist review triggers: inability to confirm patch compliance within 14 days for known exploited vulnerabilities (KEVs). *Merged links:* THR-01, CTL-W1, CTL-C1, INC-01, DEP-03, REG-03, REG-04, REG-01.

**PROV-002 - Lawful intercept (CALEA) infrastructure isolation.** Control area: network segmentation and access control. Potential weakness: inadequate segregation between lawful intercept systems and general commercial IT networks. Related threat scenarios: core surveillance and wiretap exploitation [S-001]. Key dependencies: government surveillance interface standards. Regulatory expectations: FCC CALEA compliance standards; UK TSA Security Measures Regulations [S-005]. Consequence: high-impact national security breach, potential loss of operating licence and severe reputational damage [S-002]. Materiality: applies to licensed MNOs and fixed broadband providers operating under national surveillance mandates [S-001]. Follow-up questions: (1) Is the CALEA / lawful intercept management plane physically or cryptographically air-gapped from commercial enterprise administrative domains? (2) Who oversees access logs for lawful intercept portals, and how frequently are these logs audited by an independent security team? Practical improvements: implement dedicated hardware security modules (HSMs) and out-of-band monitoring for surveillance gateways. Specialist review triggers: shared Active Directory or single-factor access connecting enterprise IT to wiretap systems. *Merged links:* THR-01, CTL-C3, INC-01, DEP-02, REG-10, REG-03.

**PROV-003 - Administrative multi-factor authentication (MFA).** Control area: identity and access management. Potential weakness: single-factor authentication or non-phishing-resistant MFA on internal domain accounts and hypervisors. Related threat scenarios: destructive core switch wiper (Kyivstar) [S-003]; cloud data exfiltration (AT&T) [S-008]. Key dependencies: identity provider (IdP) cloud services. Regulatory expectations: EU NIS2 management oversight [S-006]; FCC 47 CFR Part 64 CPNI rules [S-018]. Consequence: rapid lateral movement resulting in bare-metal switch destruction or multi-million record subscriber leaks [S-008]. Materiality: universal across all subsectors and business models [S-006]. Follow-up questions: (1) Is phishing-resistant MFA (e.g. FIDO2 hardware keys) enforced for 100% of network administrators and third-party contractors? (2) How are legacy operational technology (OT) systems authenticated if they cannot natively support MFA? Practical improvements: mandatory deployment of hardware tokens for all privileged domain credentials. Specialist review triggers: reliance on SMS-based 2FA or password-only access for core administrative functions. *Merged links:* THR-02, THR-03, CTL-W2, CTL-C2, CTL-F1, INC-02, INC-03, FRD-03, REG-01, REG-05.

**PROV-004 - API security governance and public endpoint protection.** Control area: application security and data protection. Potential weakness: internet-facing production or staging APIs accessible without cryptographic authentication. Related threat scenarios: unauthenticated API data exfiltration (Optus, T-Mobile) [S-008]. Key dependencies: enterprise BSS/CRM software providers. Regulatory expectations: GDPR / ePrivacy Directive [S-010]; Australian Privacy Act [S-008]. Consequence: immediate multi-million dollar cash drain for identity replacement programmes, class-action lawsuits and privacy fines [S-008]. Materiality: highly material for consumer-facing MNOs and fixed broadband providers operating self-service customer portals [S-008]. Follow-up questions: (1) How does the organisation inventory and discover all active API endpoints across public-facing web infrastructure? (2) Are automated rate-limiting and continuous authentication controls enforced on all BSS-connected APIs? Practical improvements: implement an API security gateway with automated shadow-API discovery. Specialist review triggers: absence of centralised API gateways or presence of unauthenticated staging APIs exposed to the public internet. *Merged links:* THR-03, CTL-W3, CTL-C4, INC-04, INC-05, REG-08, REG-09.

**PROV-005 - Bare-metal backup integrity and disaster recovery testing.** Control area: business continuity and operational resilience. Potential weakness: backups hosted on the same Active Directory domain or network segment as production systems, leaving them vulnerable to wipers. Related threat scenarios: destructive wiper attack (Kyivstar) [S-003]. Key dependencies: enterprise backup storage vendors. Regulatory expectations: UK TSA remediation and recovery duties [S-019]; EU NIS2 business continuity mandates [S-006]. Consequence: extended network downtime (weeks instead of days), driving severe quarterly EBITDA contraction and potential debt default [S-003]. Materiality: essential for operators owning physical switching, subscriber databases (HLR/HSS) and core transit backbones (source wording reworded) [S-003]. Follow-up questions: (1) Are core database and switch configuration backups stored in an immutable, air-gapped environment isolated from primary enterprise domain credentials? (2) When was the last full-scale bare-metal restoration test conducted for the mobile subscriber database (HLR/HSS)? Practical improvements: maintain immutable, offsite write-once-read-many (WORM) storage for all network gold-image configurations. Specialist review triggers: absence of air-gapped backups or failure to test full system restoration within the past 12 months. *Merged links:* THR-02, CTL-W5, CTL-C5, INC-02, DEP-01, SCN-3, REG-03, REG-01.

**PROV-006 - Third-party cloud data governance.** Control area: third-party risk management (TPRM). Potential weakness: unmonitored third-party cloud data repositories hosting sensitive call detail records (CDRs) or customer data. Related threat scenarios: cloud data warehouse breach (AT&T / Snowflake) [S-008]. Key dependencies: cloud service providers (CSPs). Regulatory expectations: EU NIS2 ICT supply chain security [S-006]; FCC breach reporting rules [S-018]. Consequence: major data breach regulatory enforcement, legal liabilities and reputation loss [S-008]. Materiality: material for operators outsourcing enterprise analytics, data warehousing or customer billing to public cloud environments [S-008]. Follow-up questions: (1) Does the enterprise enforce centralised SOC log monitoring over all third-party cloud data warehouses? (2) Are customer CDRs encrypted at rest using customer-managed encryption keys (CMEK)? Practical improvements: implement cloud security posture management (CSPM) tools with automated credential monitoring. Specialist review triggers: cloud storage environments operating outside central identity provider access controls. *Merged links:* THR-03, CTL-C6, CTL-F1, INC-03, FRD-03, FRD-E2, DEP-05, REG-01, REG-05.

**PROV-007 - Retail CRM and SIM-swapping controls.** Control area: cyber-enabled fraud prevention. Potential weakness: weak customer identity validation mechanisms at retail call centres and partner stores (source wording reworded). Related threat scenarios: cyber-enabled SIM-swapping and financial vishing scams [S-017]. Key dependencies: retail partner networks and customer support call centres. Regulatory expectations: FCC consumer protection standards; national telecom authority anti-fraud guidelines. Consequence: litigation from high-profile fraud victims, regulatory consumer protection fines and brand equity loss. Materiality: material for consumer MNOs and MVNOs. Follow-up questions: (1) What secondary out-of-band authentication measures are required before a retail agent can complete a mobile number port or SIM swap? (2) Are retail CRM systems monitored for anomalous bulk SIM-swap activity by individual store accounts? Practical improvements: deploy biometric identity checks and delay high-risk SIM swaps for 24 hours pending SMS confirmation (source wording reworded). Specialist review triggers: reliance on basic knowledge-based authentication (e.g. address, date of birth) for processing SIM changes. *Merged links:* THR-04, CTL-W4, FRD-T14, FRD-E3, FRD-T07, REG-17.

**PROV-008 - BGP and signalling system (SS7/Diameter) defence.** Control area: network routing and interconnection security. Potential weakness: lack of Resource Public Key Infrastructure (RPKI) deployment and unprotected SS7/Diameter signalling firewalls. Related threat scenarios: traffic hijacking and state surveillance [S-002]. Key dependencies: international wholesale transit brokers and clearinghouses. Regulatory expectations: GSMA Security Accreditation Scheme; National Cyber Security Centre (NCSC) guidance. Consequence: man-in-the-middle traffic interception, loss of wholesale carrier reputation and strategic intelligence leaks. Materiality: material for wholesale carriers, fixed-line operators and international mobile operators. Follow-up questions: (1) Has the organisation fully implemented RPKI Route Origin Authorisation (ROA) to prevent BGP route hijacking? (2) Are signalling firewalls deployed to filter malicious SS7 and Diameter messages at international interconnect boundaries? Practical improvements: enforce strict BGP filtering rules and deploy automated signalling anomaly detection tools. Specialist review triggers: unfiltered SS7 interconnects or missing RPKI validation on core IP backbones. *Merged links:* THR-01, DEP-03, GEO-03, GEO-04, FRD-T15, FRD-T16, REG-11.

**PROV-009 - Supply-chain software lifecycle assurance.** Control area: software supply chain security. Potential weakness: deployment of third-party network management software without active vulnerability scanning or Software Bill of Materials (SBOM) validation. Related threat scenarios: MOVEit / vendor zero-day supply-chain exploitation [S-008]. Key dependencies: enterprise software vendors and NMS developers. Regulatory expectations: UK TSA supply chain duties [S-005]; EU NIS2 ICT product security [S-006]. Consequence: indirect breach exposure via compromised enterprise software, leading to operational downtime and legal exposure [S-008]. Materiality: universal across all telecom subsectors using enterprise software platforms [S-008]. Follow-up questions: (1) How are essential third-party software updates evaluated for security flaws before deployment in production (source wording reworded)? (2) Does the organisation require major software vendors to provide an SBOM? Practical improvements: establish strict vendor risk assessment protocols and isolated staging environments for software patches. Specialist review triggers: direct, unmonitored administrative access granted to third-party software vendors. *Merged links:* THR-03, CTL-C6, INC-06, DEP-07, REG-03, REG-01.

**PROV-010 - Incident response and executive board readiness.** Control area: governance and crisis management. Potential weakness: lack of executive-level crisis response exercises specifically simulating nationwide network blackout scenarios. Related threat scenarios: destructive cyber warfare and sector-wide blackouts [S-003]. Key dependencies: external crisis management advisers and legal counsel. Regulatory expectations: EU NIS2 board training requirements [S-006]; SEC cyber governance disclosure rules. Consequence: delayed crisis response, poor regulatory communication, exacerbated financial losses and board member removal [S-006]. Materiality: universal across all public and large private telecommunications corporate entities [S-006]. Follow-up questions: (1) How frequently does the executive board conduct simulated cyber crisis exercises involving core network loss and ransom demands? (2) Are clear operational protocols in place for regulatory notifications within statutory timelines (e.g. 24-hr / 72-hr NIS2 reporting)? Practical improvements: conduct bi-annual executive table-top exercises led by independent cyber security advisers. Specialist review triggers: absence of formal cyber incident response plans or lack of board-level cybersecurity training. *Merged links:* THR-02, INC-02, SCN-3, Q13 governance drivers (GOV-04), FRD-01 (subsidiary oversight), REG-01, REG-12, REG-16.

**Cross-references:** Q03, Q04, Q06, Q10, Q12, Q13; QMP register.

---

## Q09 - Assembly: Report, Narrative & Annex Outline

*Conclusion: File A's assembly (report outline, 12-slide narrative and annex outline) is carried into Section 5 and updated with File B evidence; the A5 "Pending Q10-Q15 research" placeholder is replaced by File B's classification.*

### Q09.1 File A executive summary (preserved)

The global telecommunications sector faces elevated operational and credit exposure driven by nation-state espionage, third-party supply-chain compromise and destructive cyber warfare [S-001]. Cyber risk in telecommunications represents a structural credit risk that directly threatens corporate cash flow stability, debt service coverage and regulatory compliance standing [S-004]. Senior Credit Officers must monitor three primary exposures across telecommunications borrowers:
1. **Systemic core network espionage:** sustained state-sponsored campaigns, such as Salt Typhoon, have demonstrated that hostile actors can achieve long-term persistence within core IP routers and court-authorised surveillance infrastructure (e.g. CALEA gateways) across major carriers [S-001]. This compromises customer confidentiality and triggers substantial remediation capital expenditure [S-002].
2. **Third-party data and API exposure:** unsecured APIs and unmanaged third-party cloud data repositories expose tens of millions of customer records, resulting in immediate cash outflows for legal defence, customer compensation and statutory penalties [S-008].
3. **Destructive switching and service blackouts:** cyber attacks targeting core switching, Home Subscriber Servers (HSS) and billing engines can physically halt network operations, resulting in immediate revenue loss during outages and severe EBITDA margin contraction [S-003].

From a credit perspective, these exposures result in direct liquidity drains, margin compression, displaced capital expenditure and statutory fines scaled to global turnover under frameworks such as the UK Telecommunications Security Act [S-005] and EU NIS2 Directive [S-006]. **Three priority questions for Senior Credit Officers:** (1) How are court-mandated lawful intercept gateways and core administrative routing nodes segregated and monitored against persistent nation-state intrusion [S-001]? (2) What MFA and continuous access controls govern third-party cloud data warehouses and external customer API endpoints [S-008]? (3) What is the tested bare-metal recovery time objective (RTO) for core switching infrastructure in the event of a destructive wiper attack [S-003]?

### Q09.2 File A assembly carried forward and updates made

File A's report outline (9 sections), 12-slide narrative and annex outline A1-A7 are reproduced in Section 5 with S- IDs. Updates from merged evidence: (a) Annex A5 "Pending Q10-Q15 research" replaced by File B's rating matrix; (b) Slide 02 now shows File B's four ratings; (c) Slide 09 adds File B fraud losses separately by dataset type; (d) report outline sections 10 (Methodology, Confidence & Limitations) and 11 (References), absent in File A, added; (e) Slide 01 classification metadata kept as written.

### Q09.3 File A "Issues Requiring Analyst Validation" (preserved; restricted words reworded)

1. **Confirmation of edge device patching velocity:** second-line analysts must check borrower claims regarding patch deployment timelines on essential perimeter routers against independent vulnerability assessment reports.
2. **Confirmation of CALEA network segmentation:** independent review is required to confirm whether borrower lawful intercept gateways are cryptographically and physically isolated from commercial enterprise management domains [S-001].
3. **Assessment of third-party cloud data encryption:** analysts should confirm whether borrower customer detail records (CDRs) hosted on public cloud platforms use customer-managed encryption keys (CMEK) and enforced MFA [S-008].
4. **Stress testing bare-metal restoration timelines:** technical review is needed to confirm that borrower tested recovery time objectives (RTOs) for core switching databases are sufficient to prevent severe EBITDA impairment under a wiper scenario [S-003].

**Cross-references:** Section 5; Q01 to Q15; Section 8 (File A Part 10 gaps).

---
## Q10 - Fraud Typologies & Loss Drivers

*Conclusion (File B): fraud exposure is driven by high payment velocity, dense supplier and agent networks, cross-border clearing and complex revenue recognition; documented losses are dominated by enforcement (Ericsson US$1.26bn; US carriers US$196M), cloud-breach litigation (AT&T US$177M) and industry-level toll fraud (CFCA US$28.3B, 2019 benchmark). File B contains no Q10A-Q10D subsections. File A contributes the SIM-swap and vishing scenario (THR-04) and PROV-007.*

### Q10.1 Typology materiality screen (File B)

| FRD | Fraud typology | Classification | Materiality and subsector breakdown | Primary driver / mechanism |
|---|---|---|---|---|
| FRD-T01 | Payment diversion | Hybrid | Material: all subsectors | Interception of supplier payment instructions via compromised email or altered bank details [S-035] |
| FRD-T02 | Business email compromise (BEC) | Cyber-enabled | Material: all subsectors | Compromise of executive or finance mailboxes leading to unauthorised fund transfers [S-054] |
| FRD-T03 | Invoice and procurement fraud | Non-cyber | Material: infrastructure, TowerCos, wireline | Fictitious invoicing and inflated supplier billing through collusive vendor relationships [S-035] |
| FRD-T04 | Supplier impersonation | Hybrid | Material: wireline, wireless MNOs | Deceptive vendor portal access and fraudulent bank detail change requests [S-041] |
| FRD-T05 | Executive impersonation | Hybrid | Material: all subsectors | AI-enabled voice or video cloning targeting corporate finance staff to bypass controls [S-054] |
| FRD-T06 | Account takeover (ERP / banking) | Cyber-enabled | Material: all subsectors | Stolen single-factor credentials used to access treasury platforms and billing systems [S-038] |
| FRD-T07 | Insider fraud | Hybrid | Material: wireless MNOs, MVNOs | Unauthorised employee disclosure of customer proprietary network information or SIM re-swapping [S-046] |
| FRD-T08 | Asset misappropriation | Non-cyber | Material: retail wireless, wireline | Theft of high-value inventory (smartphones, fibre optics) and equipment diversion [S-033] |
| FRD-T09 | Financial statement fraud | Non-cyber | Material: all subsectors | Overstatement of subscriber counts (ARPU metrics) and improper capitalisation of operating expenses [S-057] |
| FRD-T10 | Corruption and bribery | Non-cyber | Material: wholesale infrastructure, subsea, global wireless | Illicit payments to foreign officials to secure spectrum allocations, permits or contracts [S-042] |
| FRD-T11 | Identity fraud and synthetic identities | Hybrid | Material: retail wireless, MVNOs, broadband | Subscription fraud using synthetic identities to acquire subsidised devices and unpaid service [S-035] |
| FRD-T12 | Grant, subsidy and tax fraud | Non-cyber | Material: rural broadband, fixed-line | Misappropriation of government universal service funds and rural broadband installation grants [S-035] |
| FRD-T13 | Customer-facing refund / conduct exposure | Hybrid | Material: retail wireless, MVNOs | Unauthorised third-party billing charges (cramming) triggering regulatory reimbursement orders [S-046] |
| FRD-T14 | SIM swapping and port-out fraud | Cyber-enabled | Sector-specific: wireless MNOs, MVNOs | Fraudulent transfer of customer mobile numbers to attacker-controlled SIM cards to bypass multi-factor authentication [S-038] |
| FRD-T15 | International revenue share fraud (IRSF) | Cyber-enabled | Sector-specific: real-time voice transit, wholesale | Unauthorised PBX hacking to direct high-volume call traffic to premium-rate international numbers [S-034] |
| FRD-T16 | Interconnect bypass / box fraud | Non-cyber | Sector-specific: wireline, wholesale voice | Unauthorised routing of international call traffic through local SIM gateways to evade termination fees [S-034] |

### Q10.2 Documented fraud cases (File B)

| FRD | Organisation | Subsector and country | Scheme and fraud type | Perpetrator, channel and rail | Key dates and detection | Loss, recovery and control weakness | Enforcement outcome and source | Linked INC |
|---|---|---|---|---|---|---|---|---|
| FRD-01 | Telefonaktiebolaget LM Ericsson | Telecom equipment and infrastructure / Sweden and global [S-042] (outside common scope; Section 7.3) | Foreign bribery and corruption (FCPA violations); deferred prosecution agreement breach [S-042] | Perpetrator: management and collusive third parties [S-042]. Channel: off-books slush funds, falsified consulting contracts [S-042]. Rail: wire transfers [S-042] | Period: 2000 - 2016 (scheme); March 2023 (breach plea) [S-042]. Discovery: Dec 2019 DPA / March 2023 breach [S-042]. Detection: DOJ/SEC investigation [S-042] | Loss: $1.06B (2019 settlement) + $206.7M (2023 breach fine) [S-042]. Recovery: none [S-052]. Control weakness: intentional management override; concealment of compliance findings [S-042] | Guilty plea to FCPA charges in US Federal Court (SDNY); 1-year monitor extension [S-042]. Source: US DOJ release (2 March 2023); SDNY Docket 19-CR-884 [S-045] | INC-10 |
| FRD-02 | AT&T, T-Mobile, Verizon, Sprint | Wireless MNOs / United States [S-046] | Illicit monetisation of customer location data / privacy fraud [S-046] | Perpetrator: corporate management and data aggregators [S-053]. Channel: API data portals and sub-brokers [S-043]. Rail: commercial contracts [S-043] | Period: 2017 - 2020 [S-053]. Discovery: April 2024 (final order) [S-046]. Detection: congressional and FCC inquiry [S-046] | Loss: $196M combined administrative fines ($80M T-Mobile, $57M AT&T, $47M Verizon, $12M Sprint) [S-053] (C-13). Recovery: administrative penalties assessed [S-053]. Control weakness: inadequate due diligence over aggregator sub-licensing [S-043] | FCC forfeiture orders issued; affirmed upon judicial review in June 2026 [S-046]. Source: FCC Enforcement Bureau orders (29 April 2024) [S-046] | INC-11 |
| FRD-03 | AT&T Inc. | Wireless and fixed telecommunications / United States [S-036] | Third-party cloud data exfiltration / extortion exposure [S-036] | Perpetrator: external threat actor (Mandiant UNC5537) [S-041] (C-04). Channel: stolen single-factor credentials [S-041]. Rail: cryptographic ransom payment ($370,000 alleged) [S-041] | Period: 14 - 25 April 2024 [S-036]. Discovery: 19 April 2024 [S-063]. Detection: threat actor extortion claim [S-062] | Loss: $177M class action litigation settlement (approved Oct 2026) [S-041] (C-05). Recovery: stolen data reportedly deleted [S-041]. Control weakness: absence of MFA on cloud repositories [S-041] | SEC Form 8-K disclosure; FCC investigation; federal class settlement approval [S-044]. Source: SEC Form 8-K (12 July 2024); N.D. Tex. Order (2026) [S-044] | INC-03 |
| FRD-04 | Global telecom industry benchmark | Real-time voice transit and global telecom / worldwide [S-034] | IP-PBX hacking, international revenue share fraud (IRSF) and toll fraud [S-034] | Perpetrator: cybercrime syndicates and intermediaries [S-034]. Channel: SIP trunking, unsecured PBX gateways [S-034]. Rail: interconnect clearinghouses [S-034] | Period: historical benchmark (2019 survey) [S-034]. Discovery: industry survey [S-034]. Detection: automated SBC analytics and CDR audits [S-034] | Loss: $28.3B estimated global annual industry loss ($1.8B from IP-PBX hacking) [S-034]. Recovery: minimal [S-034]. Control weakness: default credentials on PBX equipment; delayed traffic blocking [S-034] | Industry anti-fraud operational guidance published [S-034]. Source: Communications Fraud Control Association (CFCA) survey [S-034] | - |

*File B does not rank the cases; "top-case rank" in the FRD register uses File B's listed order and is marked as such.* Classification per case is not stated in File B; the Q15 overlap notes apply (credential compromise under Cyber; diversion and toll theft under Fraud).

**Rejected candidate cases (File B):** candidate cases involving regional retail store register theft and localised copper wire cable theft were excluded from formal presentation because of their immaterial financial magnitude relative to corporate credit risk evaluations. Unsubstantiated news assertions regarding telecom billing disputes were similarly omitted in accordance with primary evidence guidelines [S-045].

### Q10.3 Quantitative fraud metrics (File B)

| FIN | Dataset name | Publisher | Geography | Observation period | Dataset type | Sample size / population | Statistic type | Metric and currency value | Sector cut vs proxy |
|---|---|---|---|---|---|---|---|---|---|
| FIN-B01 | 2026 Report to the Nations | ACFE | Worldwide | Jan 2024 - Sep 2025 | Investigated CFE cases | 2,402 cases | Median loss | $104,000 per case [S-033] | All-sector benchmark (proxy) [S-033] |
| FIN-B02 | 2026 Report to the Nations | ACFE | Worldwide | Jan 2024 - Sep 2025 | Investigated CFE cases | 2,402 cases | Average loss | $1,457,000 per case [S-033] | All-sector benchmark (proxy) [S-033] |
| FIN-B03 | 2022 Report to the Nations | ACFE | Worldwide | Jan 2020 - Sep 2021 | Investigated CFE cases | 58 cases (information sector) | Median loss | $58,000 per case [S-057] | Telecom / information cut [S-057] |
| FIN-B04 | Global Telecom Fraud Loss Survey | CFCA | Worldwide | 2019 benchmark | Industry survey | Global operator base | Total annual loss | $28.3 billion total ($1.8B IP-PBX hacking) [S-034] | Sector-specific cut [S-034] |
| FIN-B05 | Internet Crime Report 2025 | FBI IC3 | United States | Calendar year 2025 | Complaint dataset | 1,008,597 complaints | Total reported loss | $20.88 billion total (BEC second largest) [S-054] | All-sector benchmark (proxy) [S-054] |
| FIN-B06 | Cyber Claims Report 2026 | Coalition | North America | Calendar year 2025 | Insurer claims | Proprietary policyholder base | Share of claims | 58% of claims involved BEC / funds transfer fraud [S-054] | Multi-sector insurance proxy [S-054] |

*Merge note: rows use different datasets (investigated cases, industry survey, complaints, insurer claims) and are not combined.*

### Q10.4 Structural fraud exposure (File B)

The telecommunications sector exhibits distinct structural characteristics that elevate its inherent fraud exposure across retail, enterprise and wholesale operations.
- **Transactional velocity:** high transactional velocity defines customer-facing payment flows. Billing platforms continuously process millions of daily micro-transactions for mobile data, prepaid voice and streaming subscriptions, creating an expansive baseline volume that complicates automated detection of fraudulent chargebacks or unauthorised third-party billing additions [S-033]. Corporate treasury operations disburse substantial multi-million-dollar wire transfers to capital equipment suppliers and civil infrastructure contractors, creating attractive targets for social engineering [S-035].
- **Supplier and subcontractor density:** network deployment and maintenance require continuous engagement with civil engineering contractors, tower maintenance firms, fibre splicers, hardware vendors and specialised software developers [S-035]. High onboarding churn across local maintenance subcontractors creates friction for vendor bank-detail confirmation, exposing accounts payable to mandate fraud and payment diversion [S-035].
- **Intermediaries and independent agents:** wireless operators rely extensively on third-party retail agent chains, master distributors and independent sales brokers to drive subscriber growth [S-035]. These decentralised entities frequently operate with independent IT systems and variable compliance rigour, facilitating subscription fraud, identity theft and unauthorised data monetisation [S-035].
- **High-value movable assets:** retail store footprints maintain accessible inventories of premium mobile handsets and accessories [S-033]. Tower sites and fibre construction corridors contain substantial quantities of copper cabling, backup generators and specialised electronic components vulnerable to theft [S-057].
- **Public funding, grants and subsidies:** wireline and fixed-broadband operators frequently apply for and receive state subsidies, universal service funds and regional development grants to expand rural fibre coverage [S-035]. Misallocation of public funds, falsification of build-out completion metrics or non-compliance with public procurement integrity rules creates severe statutory liability [S-035].
- **Cross-border clearing:** global voice transit, international roaming settlements and subsea capacity leasing involve complex multi-currency transactions routed through international clearinghouses [S-034]. The operational lag in clearinghouse billing reconciliation enables IRSF and bypass schemes to operate for extended periods before detection [S-034].
- **Revenue-recognition complexity:** multi-play offerings bundling mobile service, fixed broadband, hardware subsidies and third-party streaming content require complex accounting allocations under international reporting standards [S-057]. This provides opportunities for executive management override to manipulate ARPU metrics, accelerate revenue recognition or improperly capitalise routine operating costs [S-057].

### Q10.5 Controls, detection and governance failures (File B)

| CTL | Control dimension | Documented failure mechanism | Primary evidence source | Impact on borrower risk profile |
|---|---|---|---|---|
| CTL-F1 | Access control and authentication | Absence of mandatory MFA on third-party cloud data platforms [S-041] | AT&T Snowflake breach analysis [S-041] | Facilitates mass exfiltration of sensitive records via credential theft [S-036] |
| CTL-F2 | Segregation of duties (SOD) | Management override of internal procurement controls and unchecked agent commission approvals [S-042] | Ericsson FCPA resolutions [S-042] | Enables illicit slush fund creation and unrecorded bribery payments [S-042] |
| CTL-F3 | Vendor onboarding and detail changes | Inadequate out-of-band validation procedures for changes to supplier banking credentials [S-035] | UK Home Office FTPF guidance [S-035] | Results in substantial payment diversion and mandate fraud losses [S-035] |
| CTL-F4 | Real-time traffic inspection | Lack of automated session border controller (SBC) monitoring for suspicious voice traffic spikes [S-034] | CFCA hacking and toll loss studies [S-034] | Causes unrecoverable IRSF and PBX toll fraud losses [S-034] |
| CTL-F5 | Subsidiary compliance oversight | Failure of parent board to enforce unified whistleblowing and anti-corruption policies across foreign units [S-035] | US DOJ v. Ericsson plea agreement [S-042] | Exposes parent entity to massive statutory fines and DPA breach penalties [S-042] |

### Q10.6 Consequences of fraud events (File B)

Direct financial losses from fraud manifest as immediate cash drains through unrecoverable wire transfers, regulatory penalties and civil litigation settlements. Major anti-corruption enforcement has resulted in total cash penalties exceeding $1.26 billion for individual equipment and infrastructure operators [S-042], administrative fines for customer data privacy violations have absorbed $196 million in aggregate operator liquidity [S-053], and class-action litigation arising from vendor cloud repository compromises has required direct settlement funds of $177 million [S-041].

Liquidity and debt service capacity are directly impaired when large regulatory fines or litigation settlements must be disbursed from operating cash balances. Such outflows reduce liquidity buffers, elevate debt-to-EBITDA leverage and risk triggering interest coverage covenants. Fraudulent conduct in public procurement or grant applications can lead to debarment from government contract bidding, cutting off long-term revenue streams in rural infrastructure development [S-035]. Reputational damage from disclosed customer data abuses elevates subscriber churn, forcing operators to increase customer acquisition spending and eroding margins [S-046].

### Q10.7 Statutory and regulatory fraud requirements (File B)

| REG | Jurisdiction | Regulatory instrument / act | Scope and entities covered | Legal status | Key mandates and effective dates |
|---|---|---|---|---|---|
| REG-13 | United Kingdom | Economic Crime and Corporate Transparency Act 2023 (ECCTA) - failure to prevent fraud (FTPF) offence [S-035] | Large corporate entities (>250 employees, >£36m turnover, >£18m balance sheet total) operating in the UK [S-035] | Binding legislation [S-035] | Strict corporate criminal liability if an associated person commits fraud benefiting the entity, unless "reasonable fraud prevention procedures" are established [S-035]. Guidance published Nov 2024; offence came into force **1 September 2025** [S-035] |
| REG-14 | European Union | EU Anti-Corruption Directive (Directive (EU) 2026/1021) [S-035] | All commercial entities operating within EU Member States [S-035] | Binding directive (transposition phase) [S-035] | Harmonised corporate liability for corruption, turnover-based corporate fines, and formal recognition of compliance programmes as mitigating factors [S-035]. Transposition deadline **1 June 2028** [S-035] |
| REG-15 | United States | Foreign Corrupt Practices Act (FCPA) (15 U.S.C. § 78dd-1) [S-042] | US issuers, domestic concerns and foreign firms operating in US capital markets [S-042] | Binding federal law [S-042] | Strict anti-bribery provisions and detailed internal accounting controls and accurate books and records [S-045]. Enacted 1977; continuous enforcement [S-042] |
| REG-16 | United States | SEC material cybersecurity incident reporting (Form 8-K Item 1.05) [S-036] | Publicly traded telecommunications issuers in the US [S-036] | Binding regulation [S-064] | Public disclosure of material cybersecurity incidents within four business days of determining materiality, subject to narrow national security delays [S-036]. Effective Dec 2023 [S-064] |

### Q10.8 Emerging fraud techniques (File B)

| FRD | Emerging technique | Target subsector | Enabling digital weakness | Deception mechanism | Target payment rail | Interrupting control |
|---|---|---|---|---|---|---|
| FRD-E1 | AI voice and video cloning | Enterprise wireline, wholesale | Real-time audio synthesis from public executive media [S-054] | Deepfake phone/video calls to finance managers impersonating the CEO or CFO [S-054] | High-value Fedwire / CHIPS wire transfers [S-054] | Out-of-band secondary authorisation via secondary communication channels [S-054] |
| FRD-E2 | Cloud credential harvesting via PaaS | All subsectors | Unmonitored single-factor third-party cloud data warehouses [S-038] | Infostealer malware targeting contractor personal devices [S-041] | External vendor API credentials [S-041] | Mandatory hardware FIDO2 MFA and IP allow-listing [S-041] |
| FRD-E3 | Automated SIM-swapping attacks | Wireless MNOs, MVNOs | Weak identity validation protocols in retail self-service portals [S-038] | Social engineering or insider collusion at retail agent locations [S-038] | Customer online banking 2FA mechanisms [S-038] | Behaviour-based API anomaly monitoring and restriction of SMS for bank 2FA [S-038] |
| FRD-E4 | GenAI-enhanced vendor phishing | Fixed-line, infrastructure | Unvalidated email communication channels for invoice processing [S-037] | Synthetically generated, highly personalised supplier invoice emails [S-037] | Automated Clearing House (ACH) and wire payments [S-054] | Automated cryptographic email authentication (DMARC/DKIM) and bank account confirmation databases [S-054] |

**Cross-references:** Q02 (INC-03), Q03 (THR-04), Q05, Q06, Q08 (PROV-007), Q13, Q15; FRD and REG registers; conflicts C-04, C-05, C-13.

---

## Q11 - Technology Adoption & Cyber Exposure

*Conclusion (File B): converged IT/OT environments (RAN, SS7, Diameter, 5G standalone core) and large web and API surfaces face rising vulnerability exploitation (20% of breaches, +34%), credential abuse (88% of basic web application attacks), ransomware/extortion (39% of large-enterprise breaches) and third-party involvement (30%); telecoms' role in SMS authentication extends fraud exposure across the economy. Consistent with File A's threat scenarios (check 3).*

### Q11.1 Context (File B)

The telecommunications sector operates highly complex, geographically distributed technology environments with very high digital dependency (source wording reworded). MNOs and fixed-line providers manage converged environments where traditional IT networks intersect with operational technology (OT) and specialised network management systems, including Radio Access Networks (RAN), Signalling System No. 7 (SS7), Diameter routing protocols and 5G standalone core functions [S-038].

### Q11.2 Cyber and ICT assessment indicators (File B)

| FIN | Indicator | Metric | Sector context | Primary source (as named) |
|---|---|---|---|---|
| FIN-B07 | Vulnerability exploitation trend | Vulnerability exploitation accounts for 20% of confirmed breaches in the overall dataset, a 34% year-over-year increase; edge networking devices, VPNs and remote access infrastructure account for 22% of CVE-related breaches [S-049, S-055] | Key subsector vulnerability: edge devices | Verizon 2025 DBIR [S-037]; Tenable Research 2025 [S-049] |
| FIN-B08 | Web application and credential abuse | Use of stolen credentials is the primary action in 88% of basic web application cyberattacks | Mobile operators and ISPs expose large web-based self-service portals and administrative API endpoints | Verizon DBIR 2025 analysis [S-037] / Cequence Security [S-038] |
| FIN-B09 | Ransomware and extortion dynamics | Ransomware and pure extortion present in 39% of large enterprise breaches and 88% of SMB breaches (C-12) | Encryption or exfiltration of customer databases, CDRs and core routing management systems | Verizon 2025 DBIR [S-037]; Halcyon breach analysis [S-070] |
| FIN-B10 | Third-party and cloud security posture | Third-party involvement in breaches doubled to 30% of all incidents in the latest observation period | Centralisation of subscriber records in external cloud data platforms without mandatory MFA | Mandiant UNC5537 cloud campaign review / SEC Form 8-K disclosures [S-041, S-064] |

*Merge note: in File B, indicator sources were given as named publishers and "[cite: n]" tags; named publishers are mapped to their register entries (Section 7.1).*

### Q11.3 Cyber-enabled fraud surface (File B)

The sector's cyber-enabled fraud attack surface is expanded by its role as the communication provider for secondary authentication across the economy. Mobile operators are heavily targeted for SIM-swapping attacks, where threat actors compromise retail portal credentials or bribe internal agent staff to re-route mobile subscriber numbers [S-038]. This enables interception of SMS multi-factor authentication codes, facilitating downstream account takeovers of corporate banking portals and ERP systems across multiple sectors [S-038].

### Q11.4 File A links

Edge-hardware exploitation (THR-01), credential-based wipers (THR-02), cloud/API exfiltration (THR-03), SIM swapping (THR-04); supervisory findings on edge patching, lawful intercept isolation and shadow APIs (Q04.2); average breach cost US$4.88M - US$5.00M (FIN-A01).

**Cross-references:** Q03, Q04, Q07, Q10, Q12, Q15; FIN register; conflict C-12; reconciliation check 3.

---

## Q12 - Third-Party, Concentration & Supply-Chain Cyber Risk

*Conclusion (File B): concentration in cloud data platforms, a small group of core routing vendors and subsea/terrestrial fibre creates single points of failure; the Rogers (2022) and Optus (2023) outages show nationwide collapse of payments and emergency services. File A's dependency matrix and MOVEit supply-chain case are consistent, except that File A rates cloud data warehouses as not a single point of failure while File B rates cloud concentration as high single-point-of-failure risk (C-17).*

### Q12.1 Dependency layers (File B)

Telecommunications infrastructure serves as a core economic dependency; disruptions within major operators propagate rapidly into secondary sectors, disrupting payment rails, transport signalling, emergency dispatch and enterprise cloud operations [S-039].

| DEP | Dependency layer | Dominant providers / entities | Sector concentration level | Single point of failure risk | Observed disruption and case evidence |
|---|---|---|---|---|---|
| DEP-05 (merged with File A DEP-05) | Cloud data repositories | Snowflake, Amazon Web Services (AWS), Microsoft Azure, Google Cloud | Substantially High | High. Compromise of a single cloud tenant impacts tens of millions of records [S-036] (C-17) | AT&T cloud incident (2024): 109 million customer call/text records exfiltrated from Snowflake workspace [S-036] |
| DEP-07 | Core network routing and software | Ericsson, Nokia, Huawei, Cisco, Oracle (session border controllers) | High | Acute. Software update flaws or targeted malware paralyse national routing [S-034] | Rogers Communications outage (July 2022): maintenance update flaw caused a 15-hour nationwide system collapse, severing payments and emergency services [S-040] (INC-07) |
| DEP-04 (merged with File A DEP-04) | Subsea and terrestrial fibre infrastructure | SubCom, Alcatel Submarine Networks, NEC, specialised neutral tower companies | High | High. Physical cable cuts or routing protocol hijacking sever international capacity [S-072] | Optus Australia outage (Nov 2023): core network routing failure affected ~10 million subscribers and disconnected ~600 emergency calls [S-039] (INC-08; C-19) |
| DEP-08 | Operational technology (OT) / network facilities | Specialised industrial control vendors, power grid suppliers, backup battery providers | Medium | Moderate. Power grid or cooling failures disrupt centralised switching hubs [S-051] | UK CNI OT security benchmark: 86% of CNI operators detected OT/ICS cyber incidents within a 12-month period [S-051] |

### Q12.2 Outage evidence (File B)

The concentration of core routing software among a limited cohort of global network vendors creates acute single points of failure. In July 2022, a major routing update failure executed by Rogers Communications triggered a 15-hour nationwide operational outage across Canada [S-040]. The incident paralysed electronic payment networks (Interac), disabled municipal emergency 911 access and interrupted retail banking operations nationwide, demonstrating the systemic risk inherent to core telecommunications failures [S-040] (C-18). In November 2023, a routing collapse at Optus Australia disconnected nearly 10 million subscribers and failed over 600 emergency calls, leading to national parliamentary inquiries and heightened regulatory oversight [S-039].

### Q12.3 File A links

Dependency matrix DEP-01 to DEP-06 (Q01.4); essential suppliers (energy grids, NEMs, MSSPs, third-party cloud) [S-002]; MOVEit supply-chain campaign (INC-06) [S-008]; supply-chain assurance mandates by jurisdiction (Q06.1); PROV-006 and PROV-009 (Q08).

**Cross-references:** Q01, Q02, Q05, Q07, Q08, Q15; DEP and INC registers; conflicts C-17 to C-19.

---

## Q13 - Governance, Ownership & Management Quality

*Conclusion (File B): multi-jurisdictional holding structures, debt-funded M&A with fragmented legacy IT, decentralised retail agent networks and friction in incident disclosure weaken internal control; documented cases are Ericsson (US$1.26bn), the FCC location-data forfeitures and AT&T's disclosure process. File A does not analyse governance; its board-readiness item (PROV-010) and NIS2 board liability (Q06) are consistent.*

### Q13.1 Organisational complexity (File B)

The corporate structures of global telecommunications operators are characterised by substantial organisational complexity. Tier-1 operators typically use multi-layered, multi-jurisdictional holding company models featuring dozens of regional operating subsidiaries, joint ventures and specialised infrastructure vehicles [S-042]. This fragmentation frequently complicates second-line risk monitoring and obscures internal control failures within foreign operating units [S-035].

### Q13.2 Governance risk drivers (File B)

| GOV | Governance risk driver | Operational and organisational mechanism | Impact on internal control environment | Documented case evidence |
|---|---|---|---|---|
| GOV-01 | Multi-jurisdictional holding structures | Use of layered foreign subsidiaries and joint ventures to operate local telecommunications networks [S-042] | Creates severe compliance blind spots and obscures illicit payment flows from parent boards [S-042] | Ericsson FCPA breach: unmonitored subsidiary operations in Djibouti, China and Iraq resulted in $1.26B total penalties [S-042] |
| GOV-02 | Aggressive M&A and technology fragmentation | Rapid acquisition of regional ISPs and legacy network operators without prompt IT integration [S-039] | Leaves unpatched legacy servers, inconsistent security policies and unmonitored administrative backdoors [S-039] | T-Mobile / Sprint post-merger integration: complex legacy infrastructure generated persistent regulatory oversight scrutiny [S-053] |
| GOV-03 | Decentralised retail agent networks | Reliance on thousands of independent retail stores and third-party call centres for subscriber onboarding [S-035] | Impairs direct management oversight of customer identity validation and data-sharing compliance [S-043] | FCC location data forfeitures: unregulated sub-broker networks resold customer location access without consent [S-043] |
| GOV-04 | Board oversight of incident disclosure | Friction between legal, public relations and cybersecurity teams during active breaches [S-036] | Leads to delayed statutory reporting and heightened litigation exposure from institutional investors [S-064] | AT&T SEC Form 8-K disclosure delays: mandatory national security DOJ waivers required before public release [S-036] |

### Q13.3 Legacy IT from M&A (File B)

Organisational complexity is further intensified by decades of debt-funded mergers and acquisitions. Multi-billion-dollar consolidations frequently result in fragmented legacy IT environments where disparate billing engines, ERP platforms and customer databases are loosely interconnected via custom middleware [S-039]. This fragmentation impairs board-level visibility, impedes standardised patch management and hampers consistent enforcement of baseline fraud controls [S-041].

**File A links:** EU NIS2 personal liability of board members; UK corporate accountability via Ofcom; US SEC governance disclosure rules (Q06.1); PROV-010 board readiness (Q08); Optus CEO resignation (INC-04).

**Cross-references:** Q01, Q06, Q08, Q10, Q15; GOV drivers; FRD-01, FRD-02; reconciliation check 3.

---

## Q14 - Peer Benchmarks & Sector Comparators

*Conclusion (File B): telecoms' investigated-case fraud medians are lower than the all-sector median, but sector-specific toll fraud is large; ransomware exposure, third-party concentration and regulatory liability intensity are rated High or Substantially High. Datasets differ by row and are not directly comparable.*

| BMK | Sector dimension | Telecommunications | Financial services | Healthcare | Manufacturing | Dataset and normalisation basis |
|---|---|---|---|---|---|---|
| BMK-01 | Fraud loss profile | Information sector median: $58,000 [S-057]; all-sector median: $104,000 [S-033]. High revenue share leakage via toll theft ($28.3B global) [S-034] | Banking median: ~$150,000+. High wire/ACH payment diversion rates [S-033] | Healthcare median: ~$100,000. High billing and grant fraud incidence [S-033] | Manufacturing median: ~$200,000. Dominant procurement and billing schemes [S-033] | ACFE 2026 / 2022 Reports to the Nations (investigated CFE cases dataset) [S-033] |
| BMK-02 | Ransomware exposure | High: present in 39% of enterprise breaches [S-037]. Focus on exfiltration extortion over immediate system lockup [S-036] | Moderate-High: heavily targeted, but higher baseline backup/recovery resilience | Substantially High: severe operational threat due to life-safety dependencies | Substantially High: present in 88% of SMB breaches; operational line stoppage risks [S-070] (C-12) | Verizon 2025 DBIR [S-037] |
| BMK-03 | Third-party concentration | Substantially High: heavy concentration in cloud data platforms, core equipment and subsea cables [S-036] | Substantially High: concentrated core banking systems and cloud computing providers | Moderate: fragmented medical device and electronic health record software | Moderate-High: concentrated industrial automation and supply chain vendors [S-036] | Verizon DBIR 2025 / Mandiant cloud campaign datasets [S-038] |
| BMK-04 | Regulatory liability intensity | Substantially High: multi-agency oversight (FCC, Ofcom, SEC, data protection authorities) [S-046] | Highest of the four (source label reworded): prudential banking supervisors and anti-money laundering regulators | High: health data privacy regulators (HIPAA/GDPR) | Moderate: environmental and safety regulatory authorities [S-066] | Primary statutory instruments and administrative enforcement actions [S-035] |
| BMK-05 (File A) | Average data breach cost | $4.88M - $5.00M (global communications sector baseline) [S-021] | - | - | - | IBM / Ponemon study via secondary summary; excludes mega-breaches |

*Comparability: BMK-01 mixes 2022 information-sector and 2026 all-sector ACFE datasets (File B states both); BMK-02 to BMK-04 mix quantitative and qualitative ratings.*

**Cross-references:** Q10, Q11, Q12, Q15; BMK register; conflict C-12.

---

## Q15 - Exposure Ratings & Credit Watch-List Triggers

*Conclusion (File B): Fraud High, Cyber/ICT Very High, Operational resilience/TPRM Very High, Governance High; all Provisional. Ratings are reproduced exactly; each row carries a fraud-cyber overlap note (check 2 passes).*

### Q15.1 File B executive summary (preserved)

**Risk classification overview**
- **Fraud exposure: High (Provisional) | Confidence: Medium.** Justification: high transactional velocity, extensive third-party retail agent networks, complex multi-play revenue recognition and pervasive identity abuse drive substantial cash leakage and regulatory refund exposure [S-033].
- **Cyber / ICT exposure: Very High (Provisional) | Confidence: High.** Justification: pervasive digital attack surfaces, extensive multi-cloud migration lacking uniform multi-factor authentication, and intense threat actor targeting create systemic technological vulnerabilities [S-036].
- **Operational resilience / third-party risk management (TPRM): Very High (Provisional) | Confidence: High.** Justification: high reliance on concentrated cloud platforms, subsea fibre routes and specialised core vendors creates single points of failure capable of causing widespread cross-sector outage paralysis [S-039].
- **Governance structure / operating model: High (Provisional) | Confidence: High.** Justification: highly leveraged multi-jurisdictional holding structures, complex legacy technology integration from past mergers and weak oversight of foreign subsidiaries generate substantial internal control gaps [S-035].

**Key risk findings for credit assessment**
1. **Cloud vendor exposure:** unsecured third-party cloud data repositories and single-factor access configurations are the primary channel for massive customer record exfiltrations, triggering severe class-action litigation and regulatory liabilities [S-036].
2. **Enforcement penalties:** non-compliance with customer location data protection rules and international anti-bribery statutes results in multi-hundred-million-dollar cash drains and loss of prosecution cooperation credits [S-042].
3. **Cross-sector outage contagion:** network failures instantly interrupt national payment rails, emergency services and commercial operations, escalating financial liabilities and regulatory intervention [S-039].

**Key enquiries for borrower due diligence**
- What percentage of cloud-hosted data platforms and third-party vendor access points strictly enforce mandatory MFA and automated credential rotation [S-041]?
- How does the borrower monitor and manage legal liability, identity validation and anti-fraud controls across its decentralised retail sales and third-party agent networks [S-035]?
- What subsea cable, core routing and cloud infrastructure single points of failure exist, and what are the tested recovery times for essential services during a total provider outage [S-039]?

### Q15.2 Rating matrix (File B, reproduced exactly)

| Dimension | Proposed rating | Status | Confidence | Structural exposure drivers | Key evidence | Primary lender consequence | Fraud-cyber overlap note | Main gaps |
|---|---|---|---|---|---|---|---|---|
| Fraud exposure | High | Provisional | Medium | High payment velocity; decentralised sales agents; complex revenue-recognition models; extensive customer identity abuse [S-033] | CFCA $28.3B global telecom fraud loss survey [S-034]; ACFE $104k median occupational fraud loss [S-033]; Ericsson FCPA enforcement [S-042] | Direct cash leakage, uncollectible revenue, regulatory fines and clawback of credit lines | Compromise of credentials captured under Cyber; fraudulent payment diversion and toll theft captured under Fraud | Absence of standardised public reporting on non-material internal payment diversion cases |
| Cyber / ICT exposure | Very High | Provisional | High | Broad web/API attack surface; IT/OT convergence; cloud data repository concentration; high vulnerability exploitation rates [S-036] | AT&T Snowflake breach affecting 109m customer records [S-036]; 2025 DBIR showing 20% vulnerability exploitation initial access rate [S-037] | Emergency remediation capital expenditure, reputational damage and class action settlement liabilities [S-044] | Threat actor initial access vectors captured under Cyber; resulting extortion or financial theft captured under Fraud | Lack of granular, subsector-specific cyber incident loss metrics for private MVNOs |
| Operational resilience / TPRM | Very High | Provisional | High | Substantial technological dependency; single points of failure in subsea/core routing; concentrated cloud and vendor reliance [S-039] | Rogers 15-hour nationwide outage [S-040]; Optus 2023 outage breaking 600 emergency calls [S-039]; UK CNI OT attack studies [S-051] | Business interruption, immediate cash flow drops, SLA penalties and debt service distress | System failure caused by malware captured under Cyber; operational outage impact captured under Resilience | Private contract SLA penalty structures remain proprietary and unobservable |
| Governance structure / operating model | High | Provisional | High | Multi-jurisdictional holding companies; aggressive debt-funded M&A; complex legacy IT environments; decentralised agency networks [S-035] | Ericsson DPA breach resulting in $206.7M additional penalty [S-042]; FCC $200M location data fines [S-046] (C-13) | Debt service strain from regulatory penalties, governance remediation costs and management distraction | Failure of IT access governance captured under Cyber; executive management override captured under Governance | Internal audit reports of unlisted middle-market telecom borrowers are inaccessible |

### Q15.3 Watch-list triggers (merged from File A and File B; no new ratings)

From File A: inability to confirm patching of KEVs within 14 days; shared AD or single-factor access to wiretap systems; SMS-based 2FA or password-only admin access; unauthenticated staging APIs; no air-gapped backups or no restoration test in 12 months; cloud storage outside central identity controls; knowledge-based SIM-change authentication; unfiltered SS7 or missing RPKI; unmonitored vendor admin access; no incident response plan or board training (PROV-001 to PROV-010 specialist review triggers); formal regulatory notice of mandatory network isolation (SCN-3 signpost). From File B: the downgrade conditions in Q15.4 are the inverse watch conditions.

### Q15.4 Sensitivities that would alter proposed classifications (File B)

- **Fraud exposure:** would be downgraded from High to Medium if a borrower demonstrates 100% automated vendor bank confirmation, mandatory out-of-band authorisation for all payment changes and zero reliance on third-party retail agent networks [S-035].
- **Cyber / ICT exposure:** would be downgraded from Very High to High if a borrower establishes full hardware-based FIDO2 MFA across all cloud data environments and demonstrates zero legacy unpatched edge access devices [S-041].
- **Operational resilience / TPRM:** would be downgraded from Very High to High if a borrower provides audited proof of full active-active core network redundancy across geographically isolated, non-overlapping fibre paths and non-concentrated cloud hosts [S-039].
- *(File B states no sensitivity for Governance.)*

**Cross-references:** Q02 to Q14; RAT register; reconciliation checks 1 and 2; conflict C-13.

---
## 4. Unified registers

### 4.1 INC - Incident register

| INC | Name | Class | Horizon | Top-five rank (File A) | Case study | Linked FRD | Source file(s) | Questions | S- IDs |
|---|---|---|---|---|---|---|---|---|---|
| INC-01 | Salt Typhoon core network and wiretap compromise (US carriers) | Intrusion | Last 12 months (ongoing; last-30-days update) | 1 | Case 1 | - | A | Q02, Q03, Q04, Q07 | S-001, S-002, S-007, S-013, S-014 |
| INC-02 | Kyivstar wiper blackout | Operational outage (destructive wiper) | Historical landmark | 2 | Case 2 | - | A | Q02, Q03, Q05, Q07 | S-003, S-004, S-011, S-016 |
| INC-03 | AT&T / Snowflake cloud data exfiltration | Intrusion; extortion exposure (File B fraud case) | Historical landmark; settlement approved Oct 2026 (File B last-30-days window) | 3 | - | FRD-03 | A, B | Q02, Q05, Q10, Q12, Q13 | S-008, S-036, S-041, S-044, S-062, S-063, S-064 |
| INC-04 | Optus unauthenticated API breach | Intrusion | Historical landmark | 4 | Case 3 | - | A | Q02, Q04, Q05 | S-008 |
| INC-05 | T-Mobile US customer data intrusions | Intrusion | Historical landmark | 5 | - | - | A | Q02, Q05 | S-008 |
| INC-06 | MOVEit Transfer supply-chain campaign | Intrusion (supply chain) | Historical landmark | - | - | - | A | Q02, Q08, Q12 | S-008 |
| INC-07 | Rogers Communications outage | Operational outage (maintenance / routing update failure) | Historical landmark | - | - | - | B | Q07, Q12, Q15 | S-040 |
| INC-08 | Optus Australia network outage | Operational outage (core routing failure) | Historical landmark | - | - | - | B | Q07, Q12, Q15 | S-039 |
| INC-09 | Reconnaissance against subsea CLS management networks (South-East Asia, Mediterranean) | Threat activity (no confirmed compromise stated) | Last 30 days (New) | - | - | - | A | Q02 | S-012 |
| INC-10 | Ericsson FCPA scheme and DPA breach | Internal fraud (corruption) | Historical landmark | - | - | FRD-01 | B | Q10, Q13 | S-042, S-045, S-052 |
| INC-11 | US carriers' customer location data sharing | Internal fraud / conduct (privacy) | Historical (order April 2024); judicial affirmation June 2026 (last 12 months) | - | - | FRD-02 | B | Q10, Q13 | S-043, S-046, S-053 |

### 4.2 FRD - Fraud register

| FRD | Case / typology | Classification (File B) | Perpetrator / channel / rail | Loss (as stated; statistic and dataset type) | Control weakness | Enforcement outcome | Top-case rank | Linked INC | S- IDs |
|---|---|---|---|---|---|---|---|---|---|
| FRD-01 | Ericsson FCPA / DPA breach | Not stated per case (typology T10 Non-cyber) | Management and collusive third parties / slush funds, falsified contracts / wire transfers | $1.06B + $206.7M penalties (enforcement outcomes) | Management override; concealment | Guilty plea; monitor extension | Listed 1st (not ranked) | INC-10 | S-042, S-045, S-052 |
| FRD-02 | US carriers location data monetisation | Not stated (typologies T07, T13 Hybrid) | Management and aggregators / API portals and sub-brokers / commercial contracts | $196M administrative fines (enforcement outcomes) | Aggregator due diligence | FCC forfeitures affirmed June 2026 | Listed 2nd | INC-11 | S-043, S-046, S-053 |
| FRD-03 | AT&T cloud exfiltration / extortion exposure | Not stated (overlap note: access under Cyber, extortion under Fraud) | UNC5537 / stolen single-factor credentials / ransom ($370,000 alleged) | $177M class settlement (court-approved) | No MFA on cloud repositories | Settlement approval; SEC 8-K; FCC investigation | Listed 3rd | INC-03 | S-036, S-041, S-044, S-062, S-063 |
| FRD-04 | CFCA IRSF / IP-PBX / toll fraud benchmark | Typology T15 Cyber-enabled | Cybercrime syndicates / SIP trunks, PBX / clearinghouses | $28.3B annual industry loss ($1.8B IP-PBX), 2019 survey (industry survey) | Default PBX credentials; delayed blocking | Industry guidance | Listed 4th | - | S-034 |
| FRD-T01 to FRD-T16 | Sixteen typologies (Q10.1) | Hybrid: T01, T04, T05, T07, T11, T13; Cyber-enabled: T02, T06, T14, T15; Non-cyber: T03, T08, T09, T10, T12, T16 | As Q10.1 | Not quantified per typology | As Q10.1 | - | - | T14 linked to THR-04 | S-033 to S-035, S-038, S-041, S-042, S-046, S-054, S-057 |
| FRD-E1 to FRD-E4 | Emerging techniques (Q10.8) | Not stated | As Q10.8 | Not quantified | As Q10.8 | - | - | E3 linked to THR-04 | S-037, S-038, S-041, S-054 |

### 4.3 THR - Threat scenarios (Q03)

THR-01 state espionage via edge hardware into lawful intercept (Increasing, High) [S-001, S-002]; THR-02 destructive wiper on core switching and HLR/HSS (Stable to Increasing in high-risk regions, High) [S-003, S-011]; THR-03 third-party cloud and API data exfiltration (Stable, High) [S-008]; THR-04 cyber-enabled vishing and SIM swapping (Increasing, Medium) [S-017; File B S-038]. Full detail in Q03.1.

### 4.4 CTL - Control weakness and capability matrix

| CTL | Item | Type | Source file | Links | S- IDs |
|---|---|---|---|---|---|
| CTL-W1 | Unpatched edge network firmware | Weakness | A | THR-01, INC-01 | S-001 |
| CTL-W2 | Absent / ineffective MFA on admin portals | Weakness | A | THR-02, THR-03, INC-02, INC-03 | S-008 |
| CTL-W3 | Unauthenticated / unprotected APIs | Weakness | A | THR-03, INC-04, INC-05 | S-008 |
| CTL-W4 | Weak retail identity validation | Weakness | A | THR-04, FRD-T14 | S-017 |
| CTL-W5 | Single-domain backup repositories | Weakness | A | THR-02, INC-02 | S-011 |
| CTL-C1 | Edge hardware hardening and emergency patching (Priority 1) | Capability | A | THR-01 | S-002, S-005, S-006 |
| CTL-C2 | MFA across all administrative interfaces (Priority 1) | Capability | A | THR-02, THR-03 | S-006, S-008 |
| CTL-C3 | Network micro-segmentation (Priority 1) | Capability | A | THR-01, THR-02 | S-002 |
| CTL-C4 | API gateway security (Priority 2) | Capability | A | THR-03 | S-008 |
| CTL-C5 | Air-gapped immutable backups and bare-metal recovery testing (Priority 2) | Capability | A | THR-02 | S-003, S-011 |
| CTL-C6 | Third-party cloud governance and log monitoring (Priority 3) | Capability | A | THR-03 | S-008 |
| CTL-F1 | Access control and authentication failure | Failure (fraud governance) | B | FRD-03 | S-036, S-041 |
| CTL-F2 | Segregation of duties failure | Failure | B | FRD-01 | S-042 |
| CTL-F3 | Vendor onboarding and bank-detail change failure | Failure | B | FRD-T01, FRD-T04 | S-035 |
| CTL-F4 | Real-time traffic inspection failure | Failure | B | FRD-04, FRD-T15 | S-034 |
| CTL-F5 | Subsidiary compliance oversight failure | Failure | B | FRD-01, GOV-01 | S-035, S-042 |
| CTL-B1 | Supervisory benchmark findings (edge patching within 14 days; lawful intercept isolation; shadow APIs) | Benchmark | A | CTL-W1, CTL-W3 | S-001, S-002, S-008, S-020 |

### 4.5 DEP - Dependency matrix

| DEP | Dependency | Source file(s) | Single point of failure | Substitutability / switching time | Propagation (Q07) | S- IDs |
|---|---|---|---|---|---|---|
| DEP-01 | HSS / HLR (MNOs) | A | Yes | Low / 24 - 72 hours | Nationwide halt of mobile voice and data; financial, emergency pathways | S-003 |
| DEP-02 | Lawful intercept (CALEA) gateways | A | Yes | None / non-substitutable | Lateral access into core transit routers | S-002 |
| DEP-03 | BGP / edge routers (fixed and broadband) | A | Yes | Medium / 4 - 12 hours | Covert traffic redirection | S-002 |
| DEP-04 | Cable landing stations and power feed gear; subsea and terrestrial fibre (SubCom, Alcatel Submarine Networks, NEC, neutral tower companies) | A, B (merged) | Yes (A); High (B) | Low / weeks to months (A) | Severs international backhaul | S-012, S-072, S-039 |
| DEP-05 | Third-party cloud data warehouses / repositories (Snowflake, AWS, Microsoft Azure, Google Cloud) | A, B (merged) | No (A) vs High (B) (C-17) | Medium / 1 - 7 days (A); concentration Substantially High (B) | Mass exfiltration of subscriber records | S-008, S-036 |
| DEP-06 | TowerCo remote telemetry and HVAC | A | No | High / 12 - 24 hours | Safety power shutdowns (scenario assumption) | Analytical assessment |
| DEP-07 | Core network routing and software vendors (Ericsson, Nokia, Huawei, Cisco, Oracle SBCs); File A NEMs for router firmware | B; A (NEMs) | Acute (B) | Not stated | National routing paralysis; Rogers outage | S-002, S-034, S-040 |
| DEP-08 | OT / network facilities (industrial control vendors, power grid suppliers, backup batteries); File A upstream energy grids | B; A (energy grids) | Moderate (B) | Not stated | Disruption of centralised switching hubs; grid telemetry pathway (A) | S-002, S-029, S-051 |

Other File A suppliers: MSSPs for SOC monitoring [S-002] (outside common scope as a service line; dependency retained).

### 4.6 GEO - Geopolitical register

GEO-01 US-China technology competition: Salt Typhoon (High) [S-002]; GEO-02 Russia-Ukraine war: Sandworm wipers (High) [S-003]; GEO-03 Middle East tensions: DNS hijacking (Medium) [S-017]; GEO-04 state-sponsored hacktivism: DDoS against BGP (High) [S-029]. Systemic pathways P1 financial sector connectivity [S-003], P2 energy grid telemetry [S-029], P3 emergency services [S-003]; File B propagation evidence: Rogers [S-040], Optus 2023 [S-039], SIM-swap downstream takeovers [S-038]. Full table in Q07.1.

### 4.7 FIN - Financial and quantitative metrics

| FIN | Metric | Value (as stated) | Disclosed vs estimate; dataset type | Source file | S- IDs |
|---|---|---|---|---|---|
| FIN-A01 | Average data breach cost | $4.88M - $5.00M | Estimate; IBM/Ponemon via secondary summary | A | S-021 |
| FIN-A02 | Mega-breach costs (>10M records) | $90M - $140M+ | Disclosed costs (Optus, T-Mobile) | A | S-008 |
| FIN-A03 | UK TSA fine cap | Up to 10% of global (metrics) / relevant (regulatory table) annual turnover; daily fines up to £100,000 | Statutory maximum | A | S-005 |
| FIN-A04 | EU NIS2 fine cap | Up to €10M or 2% of global annual turnover | Statutory maximum | A | S-006 |
| FIN-A05 | Outage recovery duration (wiper) | 7 to 14 days (metrics); 7 - 10 days (register); 12-20 Dec 2023 (timeline) | Disclosed (victim) | A | S-003 |
| FIN-A06 | Kyivstar EBITDA | Over 50% local-currency contraction in primary outage quarter | Disclosed | A | S-004 |
| FIN-A07 | Optus costs | AU$140M+ (~$90M USD) | Disclosed (Singtel) | A | S-008 |
| FIN-A08 | AT&T FCC consent decree | $13 million | Disclosed | A | S-008 |
| FIN-A09 | T-Mobile US | $350M class settlement + $150M mandatory security capex ($500M total) | Disclosed | A | S-008 |
| FIN-A10 | Kyivstar losses | $100M+ (direct remediation, compensation, lost revenue) | Disclosed (VEON) | A | S-004 |
| FIN-A11 | MOVEit reach | >2,700 organisations | Reported | A | S-008 |
| FIN-A12 | Salt Typhoon reach | >200 US organisations and 600 globally (Slide 02); >8 months persistence | Reported | A | S-002, S-007 |
| FIN-A13 | Customers affected | Kyivstar 24M; Optus ~10M; AT&T nearly 110M; T-Mobile >76M | Reported | A | S-003, S-008 |
| FIN-A14 | Australian Privacy Act maximum penalty | AU$50M+ or 30% of adjusted turnover | Statutory | A | S-008 |
| FIN-B01 to FIN-B06 | Fraud datasets (ACFE 2026 median $104,000 and average $1,457,000; ACFE 2022 information sector median $58,000; CFCA $28.3B; IC3 2025 $20.88B; Coalition 58% BEC/FTF claims) | See Q10.3 | Investigated cases; industry survey; complaints; insurer claims | B | S-033, S-034, S-054, S-057 |
| FIN-B07 to FIN-B10 | Cyber/ICT indicators (exploitation 20%, +34%, edge 22%; credentials 88%; ransomware 39%/88%; third party 30%) | See Q11.2 | Multi-contributor incident datasets | B | S-037, S-038, S-041, S-049, S-055, S-064, S-070 |
| FIN-B11 | Ericsson penalties | $1.06B (2019) + $206.7M (2023); >$1.26B total | Enforcement outcomes | B | S-042 |
| FIN-B12 | AT&T settlement and ransom | $177M class settlement (approved Oct 2026); $370,000 ransom (alleged) | Court-approved; alleged | B | S-041, S-044 |
| FIN-B13 | FCC location-data fines | $196M ($80M T-Mobile, $57M AT&T, $47M Verizon, $12M Sprint); "$200M" in rating matrix | Enforcement outcomes | B | S-046, S-053 |
| FIN-B14 | Rogers outage | 15 hours nationwide | Reported | B | S-040 |
| FIN-B15 | Optus 2023 outage | ~10 million subscribers; ~600 emergency calls | Reported | B | S-039 |
| FIN-B16 | UK CNI OT incidents | 86% of CNI operators detected OT/ICS incidents in 12 months | Vendor benchmark | B | S-051 |
| FIN-B17 | AT&T records | 109 million customer call/text records | Reported | B | S-036 |
| FIN-B18 | ECCTA scope thresholds | >250 employees, >£36m turnover, >£18m balance sheet | Statutory | B | S-035 |

*No figures are aggregated across rows; File A's AT&T $13M and File B's $177M are different components (C-05).*

### 4.8 SCN - Disruption scenarios (File A, Q05.4) - *Illustrative - not a forecast or loss estimate*

SCN-1 (1 week): BSS, portals, SIM porting; negligible debt-service impact. SCN-2 (4 weeks): enterprise services, UCaaS, broadband routing; $10M - $30M vendor retainers; EBITDA -5 to 15% for the quarter. SCN-3 (8 weeks): complete core network; $100M+ remediation; EBITDA drop >40%; potential covenant breach and downgrade. Analogues: Kyivstar (INC-02), Rogers (INC-07), Optus 2023 (INC-08).

### 4.9 REG - Regulatory register

| REG | Instrument | Jurisdiction | Legal status / date type (as stated) | Source file | S- IDs |
|---|---|---|---|---|---|
| REG-01 | NIS2 Directive (EU) 2022/2555 | EU | Directive; subject to member-state transposition variations (dates not stated) | A | S-006 |
| REG-02 | Digital Networks Act proposals | EU | Proposal (not binding) | A | S-006 |
| REG-03 | Telecommunications (Security) Act 2021 | UK | Act; entry-into-force date not stated | A | S-005 |
| REG-04 | Telecommunications Security Code of Practice | UK | Statutory code; entry into force 1 Dec 2022; re-issued 14 Jul 2026 (B); "v1.1 (2026)" (A) | A, B | S-005, S-074 |
| REG-05 | FCC data breach order / CPNI rules (47 CFR Part 64) | US | In force (date not stated); 7 business days to FBI/USSS | A | S-018 |
| REG-06 | CIRCIA | US | Status not stated | A | S-018 |
| REG-07 | EECC Article 40 | EU | Superseded by NIS2 (per File A) | A | S-006 |
| REG-08 | Australian Privacy Act amendment | Australia | Amended (date not stated); maximum AU$50M+ or 30% of adjusted turnover | A | S-008 |
| REG-09 | GDPR / ePrivacy Directive | EU | In force | A | S-010 |
| REG-10 | FCC CALEA compliance standards; UK TSA Security Measures Regulations | US / UK | In force (dates not stated) | A | S-005 |
| REG-11 | GSMA Security Accreditation Scheme; NCSC guidance | Industry / UK | Voluntary scheme and guidance | A | - |
| REG-12 | SEC cyber governance disclosure rules | US | Rule (date not stated in File A) | A | - |
| REG-13 | ECCTA failure to prevent fraud offence | UK | Binding legislation; guidance Nov 2024; in force 1 Sep 2025 | B | S-035, S-066 |
| REG-14 | EU Anti-Corruption Directive (EU) 2026/1021 | EU | Binding directive; transposition deadline 1 Jun 2028 | B | S-035 |
| REG-15 | FCPA (15 U.S.C. § 78dd-1) | US | Binding federal law; enacted 1977 | B | S-042, S-045 |
| REG-16 | SEC Form 8-K Item 1.05 | US | Binding regulation; effective Dec 2023 | B | S-036, S-064 |
| REG-17 | FCC consumer protection standards; national telecom authority anti-fraud guidelines | US / national | Not specified | A | - |
| REG-18 | CISA performance goals | US | Voluntary | A | - |
| REG-19 | Federal supply-chain bans | US | Mandatory (instrument not named) | A | - |

### 4.10 BMK - Cross-sector benchmarks

BMK-01 fraud loss profile (ACFE investigated cases; 2022 information-sector vs 2026 all-sector, not directly comparable) [S-033, S-034, S-057]; BMK-02 ransomware exposure (DBIR 2025) [S-036, S-037, S-070]; BMK-03 third-party concentration [S-036, S-038]; BMK-04 regulatory liability intensity [S-035, S-046, S-066]; BMK-05 average breach cost (File A) [S-021]. Full table in Q14.

### 4.11 RAT - Rating matrix (File B, unchanged)

| Dimension | Rating | Status | Confidence | Key evidence IDs |
|---|---|---|---|---|
| Fraud exposure | High | Provisional | Medium | FRD-01, FRD-04, FIN-B01, FIN-B04 |
| Cyber / ICT exposure | Very High | Provisional | High | INC-03, FIN-B07, FIN-B17 |
| Operational resilience / TPRM | Very High | Provisional | High | INC-07, INC-08, FIN-B16 |
| Governance structure / operating model | High | Provisional | High | FRD-01, FRD-02, FIN-B11, FIN-B13 |

### 4.12 QMP - Questionnaire map (File A; Provisional)

PROV-001 to PROV-010 with merged links as listed under each item in Q08. FRD links added: PROV-003 and PROV-006 -> FRD-03 (and FRD-E2); PROV-007 -> FRD-T14, FRD-E3, FRD-T07; PROV-008 -> FRD-T15, FRD-T16; PROV-010 -> FRD-01 (subsidiary oversight).

### 4.13 Step 4 - Cross-question reconciliation results

| Check | Result |
|---|---|
| 1. Q15 drivers cite evidence in merged registers | Pass. All key evidence items exist (FRD-01, FRD-02, FRD-04, INC-03, INC-07, INC-08, FIN-B01, FIN-B07, FIN-B16, FIN-B17). Driver citations "UK CNI OT attack studies" rest on a vendor page [S-051] (NEEDS_REVIEW for source tier, not for existence). |
| 2. Fraud and Cyber split stated | Pass. Each File B rating row has a fraud-cyber overlap note (credentials and access under Cyber; diversion, toll theft, extortion under Fraud). |
| 3a. Q03 vs Q11 | Consistent: edge-device exploitation (THR-01 / FIN-B07), credential abuse (THR-02, THR-03 / FIN-B08), third-party cloud (THR-03 / FIN-B10), SIM swapping (THR-04 / Q11.3). |
| 3b. Q01 vs Q12 | Mostly consistent; inconsistency on cloud single point of failure recorded as C-17; Optus 2023 layer categorisation C-19. |
| 3c. Q13 vs Q01 | Consistent: File B's decentralised agent networks match File A's retail CRM and SIM-swap weakness; holding-structure complexity not covered by File A (no contradiction). |
| 4. Q08 linked to THR, CTL, INC, DEP, REG and FRD | Pass (Q08 merged links; 4.12). |
| 5. Q05 vs Q10 double counting | Pass. AT&T $13M FCC decree (FIN-A08, Q05) and $177M class settlement (FIN-B12, Q10) are separate components and not summed; Ericsson and location-data fines appear only in Q10/Q13 and are referenced, not re-added, in Q05.3. |

Ratings unchanged from File B.

---

## 5. Updated Q09 assembly (merged evidence)

### 5.1 Report outline (each section opens with its conclusion)

1. **Executive Sector Assessment:** telecommunications operators face heightened systemic risk from nation-state core espionage and destructive wiper attacks [S-001]; cyber risk directly impacts debt service capability through revenue disruption, remediation capital deployment and turnover-based fines [S-004]. File B ratings: Fraud High, Cyber/ICT Very High, Operational resilience/TPRM Very High, Governance High (all Provisional).
2. **Sector Operating Model & Dependencies:** core switching nodes (HLR/HSS), CALEA surveillance gateways and subsea landing stations are single points of failure across complex wholesale and retail supply chains [S-001]; File B adds concentration in cloud data platforms and core routing vendors (DEP-05, DEP-07).
3. **Cyber Threat Landscape & Attack Scenarios:** prioritised vectors include state-sponsored edge-router exploitation (Salt Typhoon), core switch wipers (Sandworm), unauthenticated API exfiltration and cyber-enabled SIM swapping [S-001]; File B DBIR indicators confirm edge and credential exposure.
4. **Geopolitical Cyber Exposure:** systemic exposure is heavily driven by Chinese state espionage targeting surveillance infrastructure and Russian cyber warfare targeting core connectivity in regional conflicts [S-001].
5. **Major Cyber Incidents & Case Studies:** landmark cases (Kyivstar, Optus, AT&T / Snowflake) confirm that major breaches lead to multi-million dollar cash drains, executive turnover and regulatory consent decrees [S-004]; File B adds AT&T's $177M settlement and the Rogers and Optus 2023 outages.
6. **Control Weaknesses & Resilience Priorities:** Priority 1 controls require immediate edge network patching, strict network micro-segmentation and mandatory phishing-resistant MFA across all administrative portals [S-002]; File B adds fraud-governance control failures (CTL-F1 to CTL-F5).
7. **Regulatory & Supervisory Resilience Expectations:** enforcement is intensifying under the UK TSA (fines up to 10% of turnover) [S-005], EU NIS2 [S-006] and updated US FCC rules [S-018]; File B adds ECCTA FTPF, the EU Anti-Corruption Directive, FCPA and SEC Item 1.05.
8. **Operational & Financial Consequences and Credit Transmission:** cyber incidents transmit to credit risk via cash flow depletion, margin compression, displaced capital expenditure and covenant tightening [S-004]; fraud and enforcement penalties add cash drains (Q10.6).
9. **Questionnaire Mapping & Credit Officer Engagement:** Provisional mapping (PROV-001 to PROV-010) offers practical guidance without imposing automatic adverse credit decisions.
10. **Methodology, Confidence & Limitations:** merged from two files; many material claims rest on secondary sources (C-14, C-21); ratings Provisional.
11. **References:** unified source register (Section 10).

### 5.2 12-slide narrative

**Slide 01 - Sector Intelligence Cover.** Headline: Sector Cyber Risk Intelligence Briefing: Global Telecommunications. Evidence: reporting period 2024 - 2026; geography: global (US, EU, UK focus); evidence cut-off: November 2026; classification: Confidential / Credit Risk Management; version: 1.0 (File A), merged edition. Significance: establishes sector risk baseline for bank credit evaluation. Credit Lens: core sector intelligence for Senior Credit Officers supporting second line of defence risk governance. Limitation: sector-level assessment; not a borrower-specific credit rating. Source strip: Sector Cyber Risk Intelligence Research (2026). Suggested visual: title cover block with sector classification metadata.

**Slide 02 - Executive Sector Risk Snapshot.**
- Headline: telecommunications cyber risk has moved from consumer data loss to systemic nation-state espionage and core operational warfare [S-001]; File B rates all four dimensions High or Very High.
- Evidence (ratings, File B): Fraud High (Provisional; confidence Medium) - payment velocity, agent networks and identity abuse drive cash leakage. Cyber/ICT Very High (Provisional; High) - wide attack surface and cloud without uniform MFA. Operational resilience/TPRM Very High (Provisional; High) - concentrated cloud, subsea and core vendors create single points of failure. Governance High (Provisional; High) - leveraged multi-jurisdictional holdings and legacy IT weaken control. Incident evidence: over 200 US organisations and 600 globally compromised in Salt Typhoon [S-002]; Kyivstar outage for 24M users [S-003]; Optus AU$140M+ direct costs [S-008].
- Significance: cyber incidents cause cash flow depletion, severe EBITDA contraction and capex displacement toward emergency remediation [S-004].
- Credit Lens: evaluate whether borrower debt service can withstand a multi-week core revenue freeze and statutory fines up to 10% of global turnover [S-005].
- Limitation: private operator incident costs remain under-reported; ratings are Provisional.
- Source strip: S-013 (2025); S-004 (2025); S-008 (2022); S-033 (2026); S-036 (2024); S-039 (2023 event); S-042 (2023).
- Suggested visual: four-tile rating panel plus subsector heatmap.

**Slide 03 - Sector Anatomy: Key Operations & Dependencies.** Headline: core switching databases (HLR/HSS) and subsea landing stations are single points of failure across the communication chain [S-003]. Evidence: HLR/HSS corruption instantly freezes mobile registration nationwide [S-003]; subsea landing stations host concentrated transoceanic fibre backhaul [S-012]; cloud data platforms and five core vendors concentrate dependency (File B) [S-036, S-034]. Significance: disruption at a single bottleneck propagates across the customer base and connected essential infrastructure. Credit Lens: identify whether borrowers maintain geographic and technical redundancy for subscriber databases and wholesale transit links. Limitation: proprietary network architecture is rarely disclosed in public credit filings; File A and File B differ on cloud single-point-of-failure framing (C-17). Source strip: S-012 (2024); S-036 (2024); technical cyber assessments. Suggested visual: operating model diagram (subsea cable -> core switch (HLR/HSS) -> BSS/API -> end subscriber).

**Slide 04 - Cyber Threat Landscape & Attack Scenarios.** Headline: threat actors exploit edge router vulnerabilities and unauthenticated APIs to gain long-term persistence or exfiltrate bulk records [S-002]. Evidence: unpatched Cisco IOS XE flaws enabled 8+ months of undetected nation-state access across US carriers [S-002]; exposed APIs led to 10M-record breaches [S-008]; vulnerability exploitation 20% of breaches (+34%), edge devices 22% of CVE-related breaches (File B) [S-049]. Significance: perimeter edge devices are the primary vector for APTs targeting telecom networks [S-002]. Credit Lens: assess patch-management velocity for internet-facing edge routers and API governance. Limitation: zero-day exploitation frequency cannot be accurately predicted. Source strip: S-013 (2025); S-008 (2022); S-037 (Nov 2023 - Oct 2024 data). Suggested visual: attack pathway flowchart (edge devices -> lateral movement -> CALEA networks).

**Slide 05 - Geopolitical Cyber Threat Outlook.** Headline: telecom infrastructure is a primary arena for state-sponsored intelligence collection and hybrid cyber warfare [S-001]. Evidence: Salt Typhoon (PRC MSS) breached lawful intercept portals across major carriers [S-001]; Sandworm (Russian GRU) deployed destructive wipers against Ukrainian telecom infrastructure [S-003]; DNS hijacking (Middle East) and hacktivist DDoS active [S-017, S-029]. Significance: geopolitical tension raises the probability of targeted intrusion and asset destruction. Credit Lens: scrutinise borrowers in geopolitical hotspots or carrying sensitive government traffic. Limitation: public attribution carries varying governmental confidence. Source strip: S-014 (2025); S-011 (2023). Suggested visual: global map of threat vectors (PRC, Russia, Middle East) against affected regional carriers.

**Slide 06 - Major Cyber Incidents & Lessons Learned.** Headline: unsecured cloud repositories and compromised domain credentials drive major losses and board-level turnover [S-008]. Evidence: Kyivstar lost $100M+ from domain account compromise [S-004]; AT&T faced a $13M FCC penalty after cloud credential abuse [S-008] and a $177M class settlement approved in October 2026 (File B) [S-044]; Optus CEO resigned after API exposure [S-008]; Rogers' 15-hour outage cut payments and 911 access (File B) [S-040]. Significance: material breaches cause cash outflows, legal liabilities and leadership instability. Credit Lens: confirm that borrower identity management enforces phishing-resistant MFA across all administrative domains (source wording reworded). Limitation: indirect costs such as brand equity loss are hard to isolate. Source strip: S-008 (2024); S-004 (2025); S-044 (Oct 2026); S-040 (2022). Suggested visual: comparative incident matrix (cause, loss, recovery, penalty).

**Slide 07 - Control Weaknesses & Resilience Priorities.** Headline: resilience requires network micro-segmentation, mandatory MFA and immutable bare-metal backup architectures [S-002]. Evidence: failure to isolate lawful intercept systems allowed lateral state surveillance [S-002]; un-segmented backups lengthened the Kyivstar blackout [S-011]; File B: absence of MFA on cloud platforms, management override and weak vendor bank-detail checks (CTL-F1 to CTL-F3) [S-041, S-042, S-035]. Significance: priority capabilities prevent outage propagation. Credit Lens: request evidence of air-gapped backup testing and CALEA isolation. Limitation: control quality varies across subsidiary operating companies. Source strip: S-020 (2024); S-002 (2025); S-041 (2024). Suggested visual: capability pyramid (Priority 1 MFA, patching, segmentation to Priority 3).

**Slide 08 - Regulatory & Supervisory Resilience Expectations.** Headline: frameworks set turnover-scaled fines and explicit board liability for cyber failures [S-005]. Evidence: UK TSA penalties up to 10% of turnover plus £100k daily fines [S-005]; EU NIS2 director oversight liability [S-006]; US FCC 7-day breach reporting [S-018]; File B: UK failure to prevent fraud offence in force 1 September 2025; SEC Item 1.05 four-business-day disclosure [S-035, S-036]. Significance: non-compliance brings statutory fines and potential licence revocation. Credit Lens: map borrower revenues against UK TSA, EU NIS2, US FCC and fraud regimes. Limitation: enforcement intensity varies by national authority. Source strip: S-005 (TSA 2021); S-006 (NIS2 2022/2555); S-018 (47 CFR Part 64); S-035 (2025). Suggested visual: regulatory comparison table.

**Slide 09 - Financial Impact of Cyber Incidents.** Headline: cyber breaches create direct cash liabilities that compress EBITDA and disrupt planned capex [S-004]. Evidence (cyber): average breach cost $4.88M - $5M [S-021]; mega-breaches exceed $100M+ [S-004]; T-Mobile committed $150M mandatory security capex post-settlement [S-008]; AT&T $177M class settlement [S-044]. Fraud losses (separate, by dataset type): CFCA $28.3B global annual telecom fraud loss (industry survey, 2019) [S-034]; ACFE median $104,000 per case (investigated cases, all sectors, 2026) and $58,000 (information sector, 2022) [S-033, S-057]; enforcement outcomes Ericsson >$1.26B and FCC $196M [S-042, S-053]. Significance: impact extends into multi-year structural expenditure. Credit Lens: include mandatory post-breach capex and penalties in free cash flow models. Limitation: insurance recoveries are often delayed by coverage litigation; datasets are not additive. Source strip: S-021 (2025); S-008 (2021-2024); S-034 (2019); S-033 (2026); S-042 (2023). Suggested visual: waterfall chart for cyber costs; separate bars for fraud datasets.

**Slide 10 - Cyber-to-Credit Risk Transmission & Stress Scenarios.** *Illustrative - not a forecast or loss estimate.* Headline: extended core outages threaten debt service by halting cash generation and triggering covenant breaches. Evidence: the 8-week blackout scenario models a >40% quarterly EBITDA drop and potential leverage covenant breaches; 4-week scenario 5-15% EBITDA compression. Significance: disruption becomes liquidity strain and reduced interest coverage headroom. Credit Lens: stress-test leverage against 4-week and 8-week revenue interruption. Limitation: assumes static baseline operating costs during outages. Source strip: analytical credit transmission modelling; sector case studies S-004 (2025). Suggested visual: scenario matrix (1, 4, 8 weeks vs EBITDA, liquidity, covenants).

**Slide 11 - Questionnaire-to-Sector Intelligence Mapping.** *Provisional.* Headline: generic control mapping (PROV-001 to PROV-010) helps credit officers identify borrower vulnerability areas. Evidence: questions address edge patching (PROV-001), CALEA segregation (PROV-002), API security (PROV-004) and SIM-swap controls (PROV-007), now linked to File B fraud records. Significance: structured risk identification without automatic adverse decisions. Credit Lens: use gaps to structure engagement and credit agreement undertakings. Limitation: responses are self-reported management assertions requiring independent review. Source strip: Provisional control framework from CISA, Ofcom and ENISA findings S-002 (2025). Suggested visual: mapping table (PROV IDs -> threats -> follow-up questions).

**Slide 12 - Credit Officer Engagement: Key Questions & Actions.** Headline: focus on edge patching velocity, CALEA isolation, immutable backup readiness and cloud MFA. Evidence: state APTs target perimeter routers [S-002]; wiper attacks require bare-metal switch restoration [S-003]; cloud repositories without MFA enabled the AT&T breach [S-041]. Significance: engagement aligns borrower resilience with debt maturity and service requirements. Credit Lens: action plan: (1) review edge patching SLAs; (2) confirm air-gapped backup testing (source wording reworded); (3) assess fine exposure under UK TSA / EU NIS2 [S-005]; (4) ask File B's three due-diligence enquiries (Q15.1). Limitation: borrowers may restrict operational detail citing confidentiality. Source strip: sector recommendations; S-002 (2025); S-003 (2023); S-041 (2024). Suggested visual: action checklist for annual loan reviews.

### 5.3 Evidence annex outline

- **A1 Master Incident Register:** INC-01 to INC-11, by subsector, initial access, financial cost and regulatory outcome [S-003].
- **A2 Extended Case Study Dossiers:** Salt Typhoon, Kyivstar and Optus [S-002]; File B AT&T fraud case detail.
- **A3 Sector Fraud, Cyber & Resilience Metrics Baseline:** breach lifecycle costs, recovery objectives and insurance dynamics [S-008]; File B fraud datasets by type.
- **A4 Regulatory Requirements Matrix by Jurisdiction:** US, UK, EU and Asia-Pacific telecom security obligations [S-005]; REG-01 to REG-19.
- **A5 Cyber Exposure Rating Methodology & Justification:** File B rating matrix, overlap notes and sensitivities (replaces "Pending Q10-Q15 research").
- **A6 Questionnaire-Control-to-Threat Mapping:** PROV-001 to PROV-010 mapped to MITRE ATT&CK enterprise frameworks [S-002] and to merged registers.
- **A7 Confidence, Assumptions, Sources & Methodology:** source confidence scoring, taxonomy definitions and evidence evaluation rules; Sections 6 to 10.

---

## 6. Conflict register

| ID | Item | File A value and source | File B value and source | Treatment | Status |
|---|---|---|---|---|---|
| C-01 | Evidence cut-off | November 2026 (month) | 3 November 2026 | Earlier of two: November 2026 (month precision) | Resolved |
| C-02 | Rolling 12-month window | November 2025 - October 2026 | November 2025 - November 2026 | Both kept; items dated individually | Resolved |
| C-03 | AT&T customers affected | Nearly 110 million wireless customers [S-008] | 109 million customer records [S-036] | Both kept; neither count is cited to the primary 8-K | Open - NEEDS_REVIEW |
| C-04 | AT&T attribution | Threat Actor / ShinyHunters, "High (SEC Filings)" [S-008] | External threat actor (Mandiant UNC5537) [S-041] | Both kept | Open - NEEDS_REVIEW |
| C-05 | AT&T financial loss | $13M+ (Settlement + Legal); $13M FCC consent decree [S-008] | $177M class action settlement approved Oct 2026 [S-041, S-044] | Different components; court order (B, S-044) is the identifiable primary source for the settlement; File A total predates it | Resolved (not additive) |
| C-06 | AT&T date | "July 2024" (landmark heading = disclosure); incident Apr 2024 [S-008] | 14 - 25 April 2024; discovery 19 April 2024 [S-036, S-063] | Consistent; heading uses disclosure date | Resolved |
| C-07 | Kyivstar recovery duration | 7 - 10 days (register); 7 to 14 days (metrics); 12 - 20 Dec 2023 timeline [S-003] | - | All kept (internal File A) | Open - NEEDS_REVIEW |
| C-08 | Kyivstar affected users | "over 24 million mobile and fixed subscribers" vs "24 million mobile users" [S-003] | - | Both kept | Resolved |
| C-09 | UK TSA fine base | "10% of global annual turnover" (metrics) vs "10% of relevant annual turnover" (regulatory table) [S-005] | - | Both kept; primary Act [S-031] listed in File A but not cited for this | Open - NEEDS_REVIEW |
| C-10 | TSA Code of Practice version and dates | "Code of Practice v1.1 (2026)" [S-005] | Published / in force 1 Dec 2022; re-issued 14 Jul 2026 [S-074] | B cites the primary document (gov.uk); B dates preferred; A version label kept | Resolved |
| C-11 | Salt Typhoon dates | Initial access 2022 - 2023; register incident date Aug 2024 (FBI identification); disclosure Oct 2024 [S-001, S-007] | - | Different date types; consistent | Resolved |
| C-12 | Ransomware shares (DBIR) | - | 39% of large enterprise and 88% of SMB breaches (Part 2); 88% of SMB attributed to Manufacturing column (Part 5); cited source title states 44% [S-037, S-070] | All kept (internal File B) | Open - NEEDS_REVIEW |
| C-13 | FCC location-data fines | - | $196M itemised [S-053] vs "FCC $200M location data fines" (rating matrix) [S-046]; source titles state $200 Million [S-043, S-056] | Itemised $196M used in registers; $200M kept where stated | Resolved |
| C-14 | Named primary vs cited source | Primary sources named as "SEC Form 8-K Filings", "ASIC / Singtel Filings", "SEC Filings / FCC Consent" are cited to a secondary breach-cost register [S-008] | - | Kept as named; source tier recorded as secondary | Open - NEEDS_REVIEW |
| C-15 | File B source list vs in-text citations | - | Annotated source list describes primary records (DOJ [S-052], SEC 8-K [S-064], Home Office guidance [S-066], ACFE 2022 [S-076]) while in-text citations point to secondary items ([S-042], [S-036], [S-035], [S-057]) | Both S- IDs kept and cross-mapped (Section 10.1) | Resolved (mapped) |
| C-16 | "UK TSA Code of Practice Section 219" | Parse ambiguous: "Section 2" + citation 19, or "Section 219" [S-019] | - | Rendered "Section 2 [S-019]" | Open - NEEDS_REVIEW |
| C-17 | Cloud data warehouses as single point of failure (Q01 vs Q12) | Not a single point of failure; substitutability Medium; switching 1 - 7 days [S-008] | Single point of failure risk High; concentration Substantially High [S-036] | Both kept; A rates per subsector function, B rates sector concentration | Open - NEEDS_REVIEW |
| C-18 | Rogers outage cause wording | - | "Maintenance update flaw" (table) vs "routing update failure" (text) [S-040] | Both kept | Resolved |
| C-19 | Optus 2023 outage layer | - | Placed under "Subsea & Terrestrial Fiber" layer but described as core network routing failure [S-039] | Kept as written; noted | Open |
| C-20 | ACFE fraud medians | - | Information sector $58,000 (2022, 58 cases) vs all-sector $104,000 (2026, 2,402 cases) [S-033, S-057] | Different datasets and periods; not comparable | Resolved (not comparable) |
| C-21 | Source fit for regulatory claims | EU NIS2 provisions cited to an Australian director survey [S-006] | SEC Item 1.05 effective date cited to AT&T's 8-K [S-064] | Kept; flagged | Open - NEEDS_REVIEW |

---

## 7. Merge log

### 7.1 Duplicates merged and citation handling

| What | From | Into |
|---|---|---|
| AT&T / Snowflake breach | File A landmark, register, case references; File B fraud case, dependency layer, rating evidence, governance driver | INC-03 linked to FRD-03 (C-03 to C-06) |
| File B annotated source list (12 items) | File B Section G | Merged with the File B reference entries of the same URL (Section 10.1) |
| Cloud data warehouses | File A DEP (Managed Cloud & UCaaS) and File B cloud layer | DEP-05 (C-17) |
| Cable landing stations and subsea / terrestrial fibre | File A DEP and File B layer | DEP-04 |
| OT facilities and energy grids | File B OT layer; File A essential suppliers | DEP-08 |
| Core routing vendors and NEMs | File B layer; File A essential suppliers | DEP-07 |
| AT&T 109 million records stated three times | File B executive summary, rating matrix, Part 3 | FIN-B17 |
| Ericsson $1.26B stated twice | File B Q10.6 and governance table | FIN-B11 |
| SIM swapping | File A THR-04; File B typology T14, emerging technique E3, Q11.3 | Separate records cross-linked (not merged: scenario vs typology vs technique) |
| Optus | File A 2022 API breach; File B 2023 outage | Two records (INC-04, INC-08); different events |
| T-Mobile | File A data intrusions; File B location-data fines and Sprint merger | Separate records (INC-05; INC-11; GOV-02) |
| Named publishers in File B Cyber/ICT indicators | "Verizon 2025 DBIR", "Cequence Security", "Halcyon", "Mandiant" | Mapped to S-037, S-038, S-070, S-041 by name; "[cite: n]" tags mapped to S-(32+n) |
| Citation superscripts attached to figures | "Tier 1/25", "v1.1 (2026)5", "£100,0005", "Part 6418", "AA25-239A2", "AA25-239A (2025)13", "19-CR-88413", "202021", "202614", "April 20244", "202431" | Split as figure + citation (e.g. £100,000 [S-005]; 19-CR-884 [S-045]; 2017 - 2020 [S-053]); "Section 219" ambiguous (C-16) |
| Run-together text | "AU$140million(~$90 million USD)"; "$196Mcombinedadministrativefines(...)"; "$28.3Bestimatedglobalannualindustryloss(...)" | Spaced without changing figures |

### 7.2 Items reworded for language controls

*Original wording that used a restricted term is described, not quoted.*

| Location | Original wording (described) | Treatment |
|---|---|---|
| File A top-five (Optus) | Restricted adjective qualifying "financial loss" | "very large financial loss" |
| File A Case 2 regulatory outcome; systemic pathways; Slide 03; File B Part 5 introduction | Restricted adjective qualifying "infrastructure" | "essential (national) infrastructure" |
| File A THR-04, control-weakness matrix, PROV-007 | Noun form of the restricted verb for checking identity | "identity validation" / "identity checks" |
| File A Priority 3 heading | Same noun form ("Supply Chain ...") | "supply chain assurance" |
| File A PROV-001, PROV-009 | Restricted adjective qualifying "vulnerabilities" and "third-party software updates" | "high-severity vulnerabilities"; "essential third-party software updates" |
| File A PROV-005 materiality | Restricted adjective at start of sentence | "Essential for operators" |
| File A Slides 06 and 12 | Restricted verb ("... whether"; "... air-gapped backup testing") | "Confirm" |
| File A analyst validation issues | Restricted noun and verb forms; restricted adjective qualifying "perimeter routers" | "Confirmation"; "confirm"; "essential perimeter routers" |
| File B Part 2 | Restricted adjective qualifying "digital dependency" | "very high digital dependency" |
| File B cross-sector table (financial services) | Adverb form of a restricted adjective + "High" | "Highest of the four (source label reworded)" |
| File B UK CNI references | Official term contains a restricted word | CNI kept as acronym with neutral description |
| File B search strategies | Name of the UK fraud prosecution agency contains a restricted word | SFO (acronym with neutral description) |
| CIRCIA | Official name contains a restricted word | Cited by acronym |
| Source S-051 | Title and URL contain a restricted word | Title shortened; URL kept unchanged for traceability (NEEDS_REVIEW) |

US spellings converted to UK (e.g. fibre, centre, defence, organisation, specialised, centralised, licence (noun), programme, behavioural, modelling); spellings inside source titles kept.

### 7.3 Items flagged as outside or partial scope

| Item | Reason |
|---|---|
| Ericsson (FRD-01, INC-10) | Telecom equipment vendor; outside common scope (dependency DEP-07) |
| Satellite communications (File B subsector) | Outside common scope; no satellite evidence in either file |
| Managed network, cloud, UCaaS, MSSP, SD-WAN (File A subsector) | Partial scope (VoIP/SBC overlap only) |
| DEP-05 cloud providers; DEP-07 vendors | Third parties, not borrowers |
| ACFE, IC3, Coalition, DBIR datasets | All-sector or multi-sector proxies |
| Healthcare, manufacturing and financial services comparisons (BMK) | Benchmarks only |
| Kyivstar (Ukraine) | In scope (MNO / fixed) but in active conflict zone; File A states limits of transferability |

---

## 8. Gaps and limitations (combined, deduplicated)

| ID | Gap | Source file | Questions affected | What would change the findings |
|---|---|---|---|---|
| G-01 | Private telco cost opacity: non-listed operators are not subject to SEC 8-K / 10-K disclosure, biasing data toward listed carriers [S-008] | A | Q02, Q05 | Private-operator loss data |
| G-02 | Undisclosed ransom payments | A | Q02, Q05, Q10 | Ransom disclosure regimes |
| G-03 | State intelligence attribution limits: full indicators rarely disclosed [S-002] | A | Q03, Q07 | Declassified technical detail |
| G-04 | Conditions that would alter findings: structural shift in core routing protocols, universal quantum-resistant encryption, or international treaties banning cyber attacks on civilian communications | A | All | As stated |
| G-05 | No mandatory public reporting for non-material fraud (payment diversion, billing fraud) [S-035] | B | Q10, Q15 | Mandatory reporting |
| G-06 | ACFE investigated-case selection bias (self-selected sample) [S-033] | B | Q10, Q14 | Census-type fraud data |
| G-07 | Confidential insurance claims data; multi-sector proxies used [S-054] | B | Q10, Q11 | Telecom-specific claims data |
| G-08 | Executed searches (SEC EDGAR restatements tied to payment diversion; SFO and DOJ dockets for executive financial statement fraud within 18 months) found shortfalls [S-042] | B | Q10, Q13 | New filings |
| G-09 | No granular, subsector-specific cyber loss metrics for private MVNOs | B | Q11, Q15 | Subsector loss data |
| G-10 | Private SLA penalty structures unobservable | B | Q12, Q15 | Contract data |
| G-11 | Internal audit reports of unlisted middle-market borrowers inaccessible | B | Q13, Q15 | Borrower access |
| G-12 | Proprietary network architectures rarely disclosed; control quality varies across subsidiaries; questionnaire answers self-reported | A (slides) | Q01, Q04, Q08 | Borrower evidence and independent review |
| G-13 | Zero-day exploitation frequency unpredictable; enforcement intensity varies by authority; insurance recoveries delayed; indirect costs hard to isolate | A (slides) | Q03, Q05, Q06 | Longer data series |
| G-14 | Several material claims rest on secondary sources (breach-cost register, blogs, Wikipedia, slide-sharing sites) rather than the primary filings named (C-14, C-15, C-21) | Merge | All | Primary filings and orders |
| G-15 | Citation parsing ambiguities (C-16) | Merge | Q08 | Original citation file |
| G-16 | No satellite subsector evidence; no governance downgrade sensitivity in File B | Merge | Q01, Q15 | Additional research |
| G-17 | No Q10A-Q10D subsections in File B | Merge | Q10 | - |
| G-18 | File A analyst-validation issues (edge patching, CALEA segmentation, cloud encryption, restoration timelines) remain open per borrower | A | Q04, Q08 | Borrower evidence (Q09.3) |

---

## 9. Completeness check

| Question | Covered in A | Covered in B | Merged status | Note |
|---|---|---|---|---|
| Q01 | Yes | Partial (subsector definitions) | Complete | Dependency matrix plus B layers (Q12) |
| Q02 | Yes | Partial (AT&T, outages) | Complete | 11 INC records; top five and 3 case studies from A |
| Q03 | Yes | Partial (SIM swap) | Complete | 4 scenarios; control-weakness matrix |
| Q04 | Yes | Partial (control failures, sensitivities) | Complete | 6 capabilities; supervisory findings |
| Q05 | Yes | Partial (fraud consequences) | Complete | 3 stress bands, illustrative |
| Q06 | Yes | Partial (fraud and disclosure statutes) | Complete | 19 REG rows |
| Q07 | Yes | Partial (contagion) | Complete | 4 GEO rows, 3 pathways |
| Q08 | Yes | No | Complete (Provisional) | PROV-001 to PROV-010; FRD links added |
| Q09 | Yes | No | Complete | Section 5 rebuilt; A5 placeholder replaced |
| Q10 | Partial | Yes | Complete | No Q10A-Q10D |
| Q11 | Partial | Yes | Complete | 4 indicator sets |
| Q12 | Partial | Yes | Complete | C-17 open |
| Q13 | Partial | Yes | Complete | 4 governance drivers |
| Q14 | Partial (breach cost) | Yes | Complete | 4 dimensions x 4 sectors |
| Q15 | No (pending) | Yes | Complete | Ratings unchanged |

**Item-count reconciliation (Step 1 vs merged file):** File A - 32 sources (S-001 to S-032), 5 landmarks + 5-row register + 2 last-30-days items (INC-01 to INC-06, INC-09), 4 threat scenarios, 5 control weaknesses, 6 capabilities, 3 supervisory findings, 5 metrics, 3 impact cases, 4 transmission channels, 3 stress scenarios, 7-row regulatory table, 3 trends, 4 geopolitical rows, 3 pathways, 10 PROV items, 9-section outline, 12 slides, 7 annex items, 4 validation issues, 3 gaps + conditions: all present. File B - 45 references + 12 annotated entries (S-033 to S-077), 4 ratings, 3 key findings, 3 enquiries, 16 typologies, 4 cases + rejected-case note, 6 metric rows, 7 structural factors, 5 control failures, consequences, 4 statutes, 4 emerging techniques, 4 cyber indicators + SIM-swap paragraph, 4 dependency layers + outage text, 4 governance drivers + 2 paragraphs, 4 cross-sector rows, 3 gaps, 2 search strategies, 3 sensitivities: all present. Nothing dropped.

---
## 10. Reference mapping and unified source register

### 10.1 Reference mapping (original reference -> S- ID)

| Original reference | S- ID | Note |
|---|---|---|
| File A ref 1 | S-001 | |
| File A ref 2 | S-002 | |
| File A ref 3 | S-003 | |
| File A ref 4 | S-004 | |
| File A ref 5 | S-005 | |
| File A ref 6 | S-006 | |
| File A ref 7 | S-007 | |
| File A ref 8 | S-008 | |
| File A ref 9 | S-009 | |
| File A ref 10 | S-010 | |
| File A ref 11 | S-011 | |
| File A ref 12 | S-012 | |
| File A ref 13 | S-013 | |
| File A ref 14 | S-014 | |
| File A ref 15 | S-015 | |
| File A ref 16 | S-016 | |
| File A ref 17 | S-017 | |
| File A ref 18 | S-018 | |
| File A ref 19 | S-019 | |
| File A ref 20 | S-020 | |
| File A ref 21 | S-021 | |
| File A ref 22 | S-022 | |
| File A ref 23 | S-023 | |
| File A ref 24 | S-024 | |
| File A ref 25 | S-025 | |
| File A ref 26 | S-026 | |
| File A ref 27 | S-027 | |
| File A ref 28 | S-028 | |
| File A ref 29 | S-029 | |
| File A ref 30 | S-030 | |
| File A ref 31 | S-031 | |
| File A ref 32 | S-032 | |
| File B ref 1 | S-033 | |
| File B ref 2 | S-034 | |
| File B ref 3 | S-035 | |
| File B ref 4 | S-036 | |
| File B ref 5 | S-037 | |
| File B ref 6 | S-038 | |
| File B ref 7 | S-039 | |
| File B ref 8 | S-040 | |
| File B ref 9 | S-041 | |
| File B ref 10 | S-042 | |
| File B ref 11 | S-043 | |
| File B ref 12 | S-044 | |
| File B ref 13 | S-045 | |
| File B ref 14 | S-046 | |
| File B ref 15 | S-047 | |
| File B ref 16 | S-048 | |
| File B ref 17 | S-049 | |
| File B ref 18 | S-050 | |
| File B ref 19 | S-051 | |
| File B ref 20 | S-052 | |
| File B ref 21 | S-053 | |
| File B ref 22 | S-054 | |
| File B ref 23 | S-055 | |
| File B ref 24 | S-056 | |
| File B ref 25 | S-057 | |
| File B ref 26 | S-058 | |
| File B ref 27 | S-059 | |
| File B ref 28 | S-060 | |
| File B ref 29 | S-061 | |
| File B ref 30 | S-062 | |
| File B ref 31 | S-063 | |
| File B ref 32 | S-064 | |
| File B ref 33 | S-065 | |
| File B ref 34 | S-066 | |
| File B ref 35 | S-067 | |
| File B ref 36 | S-068 | |
| File B ref 37 | S-069 | |
| File B ref 38 | S-070 | |
| File B ref 39 | S-071 | |
| File B ref 40 | S-072 | |
| File B ref 41 | S-073 | |
| File B ref 42 | S-074 | |
| File B ref 43 | S-075 | |
| File B ref 44 | S-076 | |
| File B ref 45 | S-077 | |
| File B Source List item 1 | S-033 | Merged by URL with File B ref 1; annotation: ACFE 2026; observation Jan 2024 - Sep 2025; 143 countries; pages 1-12; confidence Medium |
| File B Source List item 2 | S-048 | Merged by URL with File B ref 16; annotation: Deloitte Malta; observation Jan 2024 - Sep 2025; paragraphs 1-8; confidence High |
| File B Source List item 3 | S-076 | Merged by URL with File B ref 44; File B in-text citations for this item use ref 25 (S-057) (C-15); annotation: ACFE 2022; observation Jan 2020 - Sep 2021; 133 countries; page 8 (information industry cut); confidence Medium |
| File B Source List item 4 | S-034 | Merged by URL with File B ref 2; annotation: CFCA / DSP; 2019 survey series; Section 1 "IP-PBX Hacking Losses"; confidence Medium |
| File B Source List item 5 | S-052 | Merged by URL with File B ref 20; File B in-text citations for this item use ref 10 (S-042) (C-15); annotation: US DOJ v. Ericsson; events 6 Dec 2019 (DPA) / 2 Mar 2023 (plea); Docket 19-CR-884 (SDNY); confidence High |
| File B Source List item 6 | S-044 | Merged by URL with File B ref 12; annotation: In re AT&T litigation; Civil Action 3:24-cv-00757, Doc. 534; observation Apr 2024 - Oct 2026; confidence High |
| File B Source List item 7 | S-064 | Merged by URL with File B ref 32; File B in-text citations for this item use ref 4 (S-036) (C-15); annotation: AT&T 8-K; event 19 Apr 2024; observation 14 - 25 Apr 2024; Item 1.05; confidence High |
| File B Source List item 8 | S-046 | Merged by URL with File B ref 14; annotation: FCC forfeiture orders; violations 2017 - 2020; FCC-24-42; confidence High |
| File B Source List item 9 | S-066 | Merged by URL with File B ref 34; File B in-text citations for this item use ref 3 (S-035) (C-15); annotation: ECCTA FTPF guidance; entry into force 1 Sep 2025; Sections 1.3 and 2; confidence High |
| File B Source List item 10 | S-074 | Merged by URL with File B ref 42; annotation: TSA Code of Practice; Section 1; confidence High |
| File B Source List item 11 | S-037 | Merged by URL with File B ref 5; annotation: Verizon 2025 DBIR; observation 1 Nov 2023 - 31 Oct 2024; pages 10-15; 10,747 breaches; confidence High |
| File B Source List item 12 | S-054 | Merged by URL with File B ref 22; annotation: FBI IC3 2025 via Stingrai; calendar 2025; Section 2; confidence Medium |

*No URL appears in both files; cross-file deduplication found no duplicates. File B's 12-item Source List duplicates 12 of its own references by URL and is merged into them.*

### 10.2 Unified source register

**Notes:** dates and tiers are as stated in the files or as evident from the URL or title; "n/s" = not stated. Temporal class is relative to the merge date (3 Nov 2026): current (2026), prior half-year (H2 2025), contextual (H1 2025 within 18 months), historical (older than 18 months; retained for landmark cases or stable legal background). Tier: T1 official, regulator, court or company filing; T2 independent research or association with method; T3 media, vendor, law-firm commentary, aggregator or secondary copy. Original or secondary: T1 and T2 original, T3 secondary. Confidence: as stated by File B for its annotated sources (Section 10.1), otherwise High for T1, Medium for T2, Low-Medium for T3. Locator = URL unless stated in 10.1. Geography and observation period are given in the text where the files state them. "Reference list only" = listed by the file but not cited in its text. URLs containing a restricted word, reproduced unchanged for traceability (NEEDS_REVIEW): S-051.

| S- ID | Cited by | Publisher | Title | URL | Date | Tier | Temporal class | Questions |
|---|---|---|---|---|---|---|---|---|
| S-001 | File A | Wikipedia | 2024 global telecommunications hack | https://en.wikipedia.org/wiki/2024_global_telecommunications_hack | n/s | T3 (encyclopedia; secondary) | Undated (event 2024) | Q01, Q02, Q03, Q04, Q08, Q09 |
| S-002 | File A | DeepStrike | Salt Typhoon: Inside China's Telecom Espionage Campaign | https://deepstrike.io/blog/salt-typhoon | n/s | T3 (vendor blog) | Undated | Q01, Q02, Q03, Q04, Q07, Q08, Q09, Q12 |
| S-003 | File A | FBC News | Ukraine's top mobile operator hit by biggest cyberattack of war | https://www.fbcnews.com.fj/world/ukraines-top-mobile-operator-hit-by-biggest-cyberattack-of-war/ | n/s (event Dec 2023) | T3 (media) | Historical | Q01, Q02, Q03, Q04, Q05, Q07, Q08, Q09 |
| S-004 | File A | SEC (EDGAR) | Filed by Kyivstar Group Ltd. (Form 425) | https://www.sec.gov/Archives/edgar/data/1894176/000121390025051743/ea0244905-425_kyivstar.htm | 2025 (year per accession number and File A slide) | T1 (company filing) | 2025 (half n/s) | Q02, Q05, Q09 |
| S-005 | File A | CyPro | The 2021 Telecommunications Security Act (TSA) | https://cypro.co.uk/insights/the-new-2021-telecommunications-security-act/ | n/s | T3 (consultancy) | Undated | Q04, Q05, Q06, Q08, Q09 |
| S-006 | File A | AICD | Cyber Security Obligations (international cyber security survey, April 2023) | https://www.aicd.com.au/content/dam/aicd/pdf/news-media/research/2023/international-cyber-security-survey-april-2023-v1.pdf | Apr 2023 | T2/T3 (association survey) | Historical | Q04, Q05, Q06, Q08, Q09 |
| S-007 | File A | CloudSkope | Salt Typhoon 2024-25: China US Telecom Hack | https://www.cloudskope.com/breaches/salt-typhoon-telecom-breach-2025 | 2025 (n/s) | T3 (vendor) | 2025 (half n/s) | Q02 |
| S-008 | File A | DataBreachCost | Mega-breach cost register | https://databreachcost.com/breaches | n/s | T3 (aggregator; secondary) | Undated | Q01, Q02, Q03, Q04, Q05, Q06, Q08, Q09, Q12 |
| S-009 | File A | Brodies | New Telecoms Security Regulations and Code of Practice | https://brodies.com/insights/technology/new-telecoms-regulations-and-code-of-practice-introduces-stronger-legal-duties-for-public-telecoms-providers/ | n/s | T3 (law firm) | Undated | Registers or reference list only |
| S-010 | File A | MVNO Index | MVNO Cybersecurity and Privacy Explained | https://mvno-index.com/mvno-cybersecurity-and-privacy/ | n/s | T3 | Undated | Q08 |
| S-011 | File A | Brandefense | Sandworm threat group: profile, targets and tactics | https://brandefense.io/knowledge-hub/apt-groups/sandworm/ | n/s | T3 (vendor) | Undated | Q02, Q03, Q04 |
| S-012 | File A | ENISA | Dive into the Deep Sea: A View of the Subsea Cable Ecosystem | https://www.enisa.europa.eu/news/dive-into-the-deep-sea-a-view-of-the-subsea-cable-ecosystem | 2024 (per File A slide) | T1 (EU agency) | Historical | Q01, Q02 |
| S-013 | File A | CISA | Countering Chinese State-Sponsored Actors Compromise of ... (Advisory AA25-239A) | https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-239a | Aug 2025 | T1 (government) | Prior half-year | Registers or reference list only |
| S-014 | File A | FBI | FBI Announces Joint Cybersecurity Advisory Related to Salt Typhoon (video) | https://www.fbi.gov/video-repository/salttyphoon082725.mp4/view | 27 Aug 2025 (per URL) | T1 (government) | Prior half-year | Q06 |
| S-015 | File A | UpGuard | The 40 Biggest Data Breaches of All Time (Updated July 2026) | https://www.upguard.com/blog/biggest-data-breaches | Jul 2026 | T3 (vendor) | Current | Registers or reference list only |
| S-016 | File A | Patronus | Business Continuity (BCM) in the Age of Cyber Warfare - 5 Lessons | https://patronusec.com/en/business-continuity-cyber-warfare-bcm/ | n/s | T3 (vendor) | Undated | Q02 |
| S-017 | File A | CERT-EU | Cyber Security Brief 24-02 - January 2024 | https://cert.europa.eu/publications/threat-intelligence/cb24-02/ | Jan 2024 | T1 (EU institution) | Historical | Q03, Q07, Q08 |
| S-018 | File A | eCFR | 47 CFR 64.2011 - Notification of customer proprietary network information security breaches | https://www.ecfr.gov/current/title-47/chapter-I/subchapter-B/part-64/subpart-U/section-64.2011 | Current text (n/s) | T1 (regulation) | Current text | Q06, Q08 |
| S-019 | File A | Cortex | What does the new Telecoms (Security) Act 2021 mean for CSPs | https://www.wearecortex.com/what-does-the-new-telecoms-security-act-2021-mean-for-csps/ | n/s | T3 (vendor) | Undated | Q08 |
| S-020 | File A | GOV.UK / Ofcom | Ofcom security report for the period October 2022 to October 2024 | https://www.gov.uk/government/publications/ofcom-security-report-for-the-period-october-2022-to-october-2024/security-report-for-the-period-october-2022-to-october-2024 | 2024 (per File A slide) | T1 (regulator) | Historical | Q04 |
| S-021 | File A | DeepStrike | Cost of a Data Breach 2026: Benchmarks & Drivers (IBM data) | https://deepstrike.io/blog/cost-of-a-data-breach | 2026 | T3 (vendor summary of IBM/Ponemon) | Current | Q05, Q14 |
| S-022 | File A | FEDIL | Position paper on the Digital Networks Act | https://fedil.lu/wp-content/uploads/2026/05/FEDIL_Position-paper_DNA.pdf | May 2026 | T3 (industry association) | Current | Registers or reference list only |
| S-023 | File A | EUR-Lex | COM(2026) 16 final | https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=COM:2026:16:FIN | 2026 | T1 (EU) | Current | Registers or reference list only |
| S-024 | File A | Identomat | United Kingdom Telecom & Mobile Services Compliance Guide | https://www.identomat.com/compliance-guide/guide/telecom-mobile-services-compliance-in-the-united-kingdom | n/s | T3 (vendor) | Undated | Registers or reference list only |
| S-025 | File A | NHIMG | FCC CPNI and Telecom Data Breach Rule Guide | https://nhimg.org/fcc-cpni-and-telecom-data-breach-rule-guide | n/s | T3 | Undated | Registers or reference list only |
| S-026 | File A | Latham & Watkins | FCC Expands Data Breach Notification Rules | https://www.lw.com/en/people/admin/upload/SiteAttachments/FCC-Expands-Data-Breach-Notification-Rules.pdf | n/s | T3 (law firm) | Undated | Registers or reference list only |
| S-027 | File A | EUR-Lex | SWD(2020) 345 final | https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52020SC0345 | 2020 | T1 (EU) | Historical | Registers or reference list only |
| S-028 | File A | Gamma | Telecommunications Security Act: What It Means for Service Providers | https://gammagroup.co/resources/blog/telecommunications-security-act/ | n/s | T3 (vendor) | Undated | Registers or reference list only |
| S-029 | File A | CSIS | Significant Cyber Incidents Since 2006 | https://csis-website-prod.s3.amazonaws.com/s3fs-public/2024-04/240418_Cyber_Events.pdf | 18 Apr 2024 | T2 (think tank) | Historical | Q07 |
| S-030 | File A | PKCERT (Dragos) | OT/ICS Cybersecurity Report 2025: A Year in Review | https://pkcert.gov.pk/uploads/2025/02/Dragos-2025-OT-Cybersecurity-Report-A-Year-in-Review.pdf | Feb 2025 | T2/T3 (vendor report via government mirror) | Historical | Registers or reference list only |
| S-031 | File A | legislation.gov.uk | Telecommunications (Security) Act 2021 | https://www.legislation.gov.uk/ukpga/2021/31 | 2021 | T1 (statute) | Historical (stable legal background) | Registers or reference list only |
| S-032 | File A | Federal Register | Data Breach Reporting Requirements | https://www.federalregister.gov/documents/2024/02/12/2024-01667/data-breach-reporting-requirements | 12 Feb 2024 | T1 (federal rule) | Historical (stable legal background) | Registers or reference list only |
| S-033 | File B | ACFE (via Scribd) | 2026 Report to the Nations | https://www.scribd.com/document/1066651971/2026-Report-to-the-Nations | 2026 (year) | T2 (independent research with disclosed method; File B) | Current | Q10, Q14, Q15 |
| S-034 | File B | DSP (CFCA data) | Securing real-time communications from cyberthreats with AI | https://www.dsp.co.uk/resources/securing-real-time-communications-from-cyberthreats-with-ai | 2019 benchmark / 2024 | T2/T3 (industry association survey via vendor) | Historical (benchmark) | Q10, Q12, Q14, Q15 |
| S-035 | File B | Wikborg Rein | UK government guidance paves way for entry into force of failure to prevent fraud offence | https://www.wr.no/aktuelt/uk-government-guidance-paves-way-for-entry-into-force-of-failure-to-prevent-fraud-offence | n/s | T3 (law firm) | Undated | Q05, Q10, Q13, Q14, Q15 |
| S-036 | File B | IndustryWeek | Cybercriminals Steal Data from 109 Million AT&T Customers | https://www.industryweek.com/technology-and-iiot/article/55126161/cybercriminals-steal-data-from-109-million-att-customers | Jul 2024 | T3 (media) | Historical | Q10, Q12, Q13, Q14, Q15 |
| S-037 | File B | Verizon Business | 2025 Data Breach Investigations Report | https://www.verizon.com/business/resources/reports/2025-dbir-data-breach-investigations-report.pdf | Apr 2025 | T2 (independent research with disclosed method) | Historical | Q10, Q11, Q14, Q15 |
| S-038 | File B | Cequence | Verizon 2025 DBIR Review | https://www.cequence.ai/blog/verizon-2025-dbir-review | 2025 (n/s) | T3 (vendor) | 2025 (half n/s) | Q03, Q07, Q10, Q11, Q14 |
| S-039 | File B | Sydney Times | Senate inquiry urges federal takeover of Triple Zero following Optus outages | https://www.sydneytimes.net.au/sydney-whats-on-guide/senate-inquiry-urges-federal-takeover-of-triple-zero-following-fatal-optus-outages/ | n/s | T3 (media) | Undated | Q07, Q12, Q13, Q15 |
| S-040 | File B | Prezi | Ethical Analysis of the Rogers Communications Outage | https://prezi.com/p/gedfte0ssttr/ethical-analysis-of-the-rogers-communications-outage/ | n/s | T3 (user presentation; low) | Undated | Q07, Q12, Q15 |
| S-041 | File B | OC Security Audit | Snowflake Customer Breaches: Lessons on MFA | https://ocsecurityaudit.com/snowflake-customer-breaches-mfa-lessons/ | n/s | T3 (vendor) | Undated | Q02, Q05, Q10, Q11, Q13, Q15 |
| S-042 | File B | Morrison Foerster | Top 10 International Anti-Corruption Developments for March 2023 | https://www.mofo.com/resources/insights/230411-top-10-international-anti-corruption | 11 Apr 2023 | T3 (law firm) | Historical | Q05, Q10, Q13, Q15 |
| S-043 | File B | Broadband Breakfast | FCC Fines Wireless Carriers $200 Million for Sharing Access to Location Data | https://broadbandbreakfast.com/fcc-fines-wireless-carriers-200-million-for-sharing-access-to-location-data/ | Apr 2024 | T3 (media) | Historical | Q10, Q13 |
| S-044 | File B | US District Court N.D. Texas (via Justia) | In re AT&T Inc. Customer Data Security Breach Litigation, 3:2024cv00757, Doc. 534 (Final Approval Order) | https://law.justia.com/cases/federal/district-courts/texas/txndce/3:2024cv00757/388149/534/ | 2 Oct 2026 | T1 (court order) | Current (File B last-30-days window) | Q02, Q10, Q15 |
| S-045 | File B | Settlements Explained | Ericsson FCPA case: the 2019 DPA, the breach and the guilty plea | https://settlementsexplained.org/ericsson-fcpa-2019/ | n/s | T3 | Undated | Q10 |
| S-046 | File B | FCC | FCC Fines Largest Wireless Carriers for Sharing Location Data (FCC-24-42) | https://www.fcc.gov/document/fcc-fines-largest-wireless-carriers-sharing-location-data | 29 Apr 2024 | T1 (regulator) | Historical | Q05, Q10, Q14, Q15 |
| S-047 | File B | DAC Beachcroft | Failure to prevent fraud offence now in force | https://www.dacbeachcroft.com/en/What-we-think/Failure-to-prevent-fraud-offence-now-in-force | n/s | T3 (law firm) | Undated | Registers or reference list only |
| S-048 | File B | Deloitte Malta | The cost of fraud: Protecting your business from threats outside and inside | https://www.deloitte.com/mt/en/services/consulting/perspectives/the-cost-of-fraud.html | 2026 (year) | T3 (secondary analysis of ACFE) | Current | Registers or reference list only |
| S-049 | File B | Tenable | Verizon 2025 DBIR: Tenable Research Collaboration | https://www.tenable.com/blog/verizon-2025-dbir-tenable-research-collaboration | 2025 (n/s) | T3 (vendor) | 2025 (half n/s) | Q11 |
| S-050 | File B | BleepingComputer | Massive AT&T data breach exposes call logs of 109 million customers | https://www.bleepingcomputer.com/news/security/massive-atandt-data-breach-exposes-call-logs-of-109-million-customers/ | Jul 2024 | T3 (media) | Historical | Registers or reference list only |
| S-051 | File B | Verizon Business | Strengthening your infrastructure security (title shortened) | https://www.verizon.com/business/en-en/solutions/strengthening-your-critical-infrastructure-security/ | n/s | T3 (vendor page) | Undated | Q12, Q15 |
| S-052 | File B | US DOJ Criminal Division | United States v. Telefonaktiebolaget LM Ericsson | https://www.justice.gov/criminal/criminal-fraud/fcpa/cases/united-states-v-telefonaktiebolaget-lm-ericsson | 2 Mar 2023 | T1 (prosecutorial record) | Historical | Q10 |
| S-053 | File B | AP News | FCC fines wireless carriers for sharing user locations without consent | https://apnews.com/article/fcc-fines-carriers-location-data-16acca725c7b4537c1c3c459ff449736 | Apr 2024 | T3 (media) | Historical | Q05, Q10, Q13 |
| S-054 | File B | Stingrai (FBI IC3 data) | Business Email Compromise (BEC) Statistics 2026 | https://www.stingrai.io/blog/business-email-compromise-statistics-2026 | Mar 2026 (per File B) | T3 (secondary aggregation of law-enforcement data) | Current | Q10 |
| S-055 | File B | Verizon Business | 2024 Data Breach Investigations Report | https://www.verizon.com/business/resources/reports/2024-dbir-data-breach-investigations-report.pdf | 2024 | T2 | Historical | Q11 |
| S-056 | File B | CNET | FCC Fines Verizon, T-Mobile and AT&T $200 Million for sharing customer location data | https://www.cnet.com/tech/mobile/fcc-fines-verizon-t-mobile-and-at-t-200-million-for-sharing-customer-location-data/ | Apr 2024 | T3 (media) | Historical | Registers or reference list only |
| S-057 | File B | Studocu (ACFE copy) | ACFE 2022 Occupational Fraud Report: Insights and Key Findings | https://www.studocu.vn/vn/document/truong-dai-hoc-kinh-te-thanh-pho-ho-chi-minh/kiem-soat-noi-bo/acfe-2022-report-to-the-nations/81520607 | n/s (report 2022) | T3 (document-sharing copy) | Historical | Q10, Q14 |
| S-058 | File B | SEC | SEC Enforcement Actions: FCPA Cases | https://www.sec.gov/about/divisions-offices/division-enforcement/enforcement-topics-initiatives/sec-enforcement-actions-fcpa-cases | n/s | T1 (regulator) | Undated | Registers or reference list only |
| S-059 | File B | Stanford FCPA Clearinghouse | Investigation into Ericsson's Activities in Iraq between 2011 and 2019 | https://fcpa.stanford.edu/investigation.html?id=442 | n/s | T2 | Undated | Registers or reference list only |
| S-060 | File B | US Senator Wyden | Wyden Praises FCC Fines on Wireless Carriers in Response to His Investigation into Abuse of Location Data | https://www.wyden.senate.gov/news/press-releases/wyden-praises-fcc-fines-on-wireless-carriers-in-response-to-his-investigation-into-abuse-of-location-data | Apr 2024 | T1 (official statement) | Historical | Registers or reference list only |
| S-061 | File B | The Record | Supreme Court rules FCC fines punishing telecom giants for sharing location data legal | https://therecord.media/supreme-court-rules-fcc-fines-telecom-location-data-legal | n/s (2026 per File B text) | T3 (media) | Undated | Registers or reference list only |
| S-062 | File B | Tech Monitor | AT&T breach sees an estimated 109 million customers' call logs leaked | https://www.techmonitor.ai/technology/cybersecurity/att-breach-sees-an-estimated-109-million-customers-call-logs-leaked | Jul 2024 | T3 (media) | Historical | Q10 |
| S-063 | File B | Foley Hoag | AT&T/Snowflake Breach Hits Most of US - Vendor Exposure Strikes Again | https://foleyhoag.com/news-and-insights/blogs/security-privacy-and-the-law/2024/july/at-t-snowflake-breach-hits-most-of-us-vendor-exposure-strikes-again/ | Jul 2024 | T3 (law firm) | Historical | Q10 |
| S-064 | File B | SEC (EDGAR) | AT&T Inc. Form 8-K (t-20240506), Item 1.05 | https://www.sec.gov/Archives/edgar/data/732717/000073271724000046/t-20240506.htm | 12 Jul 2024 | T1 (company filing) | Historical | Q10, Q11, Q13 |
| S-065 | File B | Howell Advisory Services | About | https://www.howelladvisoryservices.com/about | n/s | T3 | Undated | Registers or reference list only |
| S-066 | File B | UK Home Office (GOV.UK) | Economic Crime and Corporate Transparency Act 2023: Guidance to organisations on the offence of failure to prevent fraud | https://www.gov.uk/government/publications/offence-of-failure-to-prevent-fraud-introduced-by-eccta/economic-crime-and-corporate-transparency-act-2023-guidance-to-organisations-on-the-offence-of-failure-to-prevent-fraud-accessible-version | 6 Nov 2024; updated 10 Oct 2025 | T1 (statutory guidance) | Prior half-year (update) | Q14 |
| S-067 | File B | ACFE (via Ivey) | Occupational Fraud 2024: A Report to the Nations | https://www.ivey.uwo.ca/media/kjljj5cy/2024-report-to-the-nations.pdf | 2024 | T2 | Historical | Registers or reference list only |
| S-068 | File B | Punter Southall | UK Home Office Guidance: Failure to Prevent Fraud | https://puntersouthall.law/insights/uk-home-office-guidance-failure-to-prevent-fraud/ | n/s | T3 (law firm) | Undated | Registers or reference list only |
| S-069 | File B | ENISA (via StandICT) | ENISA Threat Landscape for 5G Networks - Update | https://standict.eu/sites/default/files/2021-02/ENISA%205G%20Threat%20Landscape%20-%20Update.pdf | 2021 | T1 (EU agency via mirror) | Historical | Registers or reference list only |
| S-070 | File B | Halcyon | Verizon DBIR Shows Ransomware Involved in 44% of Data Breaches | https://www.halcyon.ai/blog/verizon-dbir-shows-ransomware-involved-in-44-of-data-breaches | 2025 (n/s) | T3 (vendor) | 2025 (half n/s) | Q11, Q14 |
| S-071 | File B | PA Global | Breach, Loss, Recovery: The True Price of Cyber Failure | https://pa-global.com/insights/breach-loss-recovery-the-true-price-of-cyber-failure/ | n/s | T3 | Undated | Registers or reference list only |
| S-072 | File B | Verizon Business | 2026 Data Breach Investigations Report | https://www.verizon.com/business/resources/T343/reports/2026-dbir-data-breach-investigations-report.pdf | 2026 | T2 | Current | Q12 |
| S-073 | File B | FCPA Professor | Second Circuit Affirms Dismissal Of FCPA Related Securities Fraud Action (Ericsson) | https://fcpaprofessor.com/second-circuit-affirms-dismissal-fcpa-related-securities-fraud-action-ericsson/ | n/s | T3 | Undated | Registers or reference list only |
| S-074 | File B | DSIT / Ofcom (GOV.UK) | Telecommunications Security Code of Practice | https://assets.publishing.service.gov.uk/media/6a4fac891228eb26a4cab6de/Web_Accessible_-_COP.pdf | 1 Dec 2022; re-issued 14 Jul 2026 | T1 (statutory code) | Current (re-issue) | Q06 |
| S-075 | File B | ACFE (via KKC) | Report to the Nations on Occupational Fraud and Abuse (2016) | https://kkc.com/wp-content/uploads/2020/03/2016-report-to-the-nations.pdf | 2016 | T2 | Historical | Registers or reference list only |
| S-076 | File B | ACFE | Occupational Fraud 2022: A Report to the Nations | https://acfepublic.s3.us-west-2.amazonaws.com/2022+Report+to+the+Nations.pdf | 2022 | T2 (independent research with disclosed method) | Historical | Registers or reference list only |
| S-077 | File B | Wiggin | Telecommunications Security Code of Practice now in force | https://www.wiggin.co.uk/insight/telecommunications-security-code-of-practice-now-in-force/ | n/s | T3 (law firm) | Undated | Registers or reference list only |

---
## Final checks

| Check | Result |
|---|---|
| Every question Q01-Q15 has a section | Pass (15 sections, each opening with its conclusion and closing with a "Cross-references" line) |
| Nothing from either file missing (Step 1 counts vs merged file) | Pass; item-count reconciliation in Section 9 |
| Every S- ID used exists in the register | Pass (S-001 to S-077; 0 unknown). 24 sources are listed in a file's reference list but not cited in its text; they are kept and marked "Registers or reference list only" |
| No URLs in the slide narrative (Section 5) | Pass |
| No new facts, figures, sources or ratings | Pass. No research performed; ratings exactly as File B (Fraud High, Cyber/ICT Very High, Operational resilience/TPRM Very High, Governance High; all Provisional) |
| All conflicts in the conflict register | Pass (C-01 to C-21); NEEDS_REVIEW: C-03, C-04, C-07, C-09, C-12, C-14, C-16, C-17, C-21 |
| Language controls | Pass: no restricted words outside URLs; no em or en dashes; UK spelling (source titles unchanged); acronyms defined in Section 1.3. One URL contains a restricted word (S-051, NEEDS_REVIEW) |
| Executive summary length | 249 words (limit 300) |
| Slide labels | Slide 10 "Illustrative - not a forecast or loss estimate"; Slide 11 "Provisional" |
