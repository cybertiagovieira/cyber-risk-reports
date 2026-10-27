# Media & Cultural Services - Sector Cyber Resilience & Credit Intelligence: Research Record Q01-Q15

**Document type:** research record (no slide production). **Version:** 1.1-R (research update of the 15 October 2026 baseline edition).
**Research date of this update:** 27 October 2026.
**Evidence base and cut-offs:**
- Q01-Q07: unchanged from the baseline edition (public sources; evidence cut-off 15 October 2026; reporting period 1 September 2025 to 15 October 2026; all sources accessed 15 October 2026).
- Q10-Q14: updated on 27 October 2026 by merging the baseline evidence with a user-supplied research input, *Sector Risk Intelligence Report: Media & Cultural Services Inherent Risk Analysis* (file `Media_Risk_Intelligence_Metaplan.pdf`, SHA-256 `8c32535629377e89dac3c8e6210ba3a1cd4491f8c64e341a502e99f22ae69065`). The input states an evidence cut-off of 27 October 2026, a last-30-days window of 28 September to 27 October 2026, a rolling 12-month window of 28 October 2025 to 27 October 2026 and a historical horizon before 28 October 2025. Per user instruction, the user-supplied information was accepted and merged **without source validation**.
- Q15, Q08 and Q09: synthesised from all of the above. The four ratings follow the user-supplied rating matrix.

**Geography:** global baseline; primary focus on the European Union (EU), European Economic Area (EEA) and United Kingdom (UK) in the baseline edition; the user input adds dedicated EU, UK and United States (US) fraud and governance coverage. Japanese, Pakistani and Australian evidence is used for comparison.
**Audience:** Senior Credit Officers and First Line of Defence (1LoD) operational management; second-line reviewers.
**Boundary:** public external evidence plus a user-supplied research input. No internal bank, client or borrower data. Sector findings describe inherent exposure only; they are not a borrower creditworthiness assessment, a control audit or a compliance finding.
**Status:** Provisional (no approved rating rubric and no questionnaire item list supplied). NEEDS_REVIEW items are listed in section F.

---

## 0. Reading guide

**Source identifiers.**
- `S-001` to `S-087`: public sources from the baseline edition, accessed on 15 October 2026 (full list in section G1). Tier 1 = official, legal, regulatory, court, affected organisation; Tier 2 = independent research with disclosed method; Tier 3 = media and discovery.
- `U-001` to `U-033`: references cited in the user-supplied research input, numbered as in that input (its footnotes 1 to 33), merged on 27 October 2026 without validation (section G2). They are labelled **User-supplied (not validated)** wherever they support a finding. Tiers were not assigned to them because their sources were not reviewed.

**Evidence labels.** Observed (external fact from a named source); Benchmark (sector statistic with stated population); Proxy (indirect or derived measure); Judgement (analytical judgement); Assumption (scenario assumption); Action (management recommendation); User-supplied (not validated).

**Merge rule.** Baseline evidence (S-) is retained in full. User-supplied information (U-) is added where it addresses Q10 to Q15. Where the two sets describe the same event (the British Library attack), both are shown with their own references and any difference in what they measure is stated, not reconciled. Nothing in the user input was re-checked against its sources.

**Subsector map used in this record.** The user input defines six subsectors; the baseline edition used eleven finer subsectors. They map as follows.

| User-input subsector | Business model (as supplied) | Baseline-edition subsectors |
|---|---|---|
| Broadcasting & Streaming | Subscription and advertising video on demand (SVOD, AVOD), user subscriptions, linear carriage fees | Broadcasters (TV and radio); transmission, playout and distribution; streaming platforms (video and audio) |
| Film & Music Production and Distribution | Intellectual property (IP) licensing, royalty collection, box-office revenue sharing, milestone-based project finance | Music, publishing and rights management; film, TV, post-production and visual effects |
| Publishing & Information Services | Business-to-business (B2B) and consumer subscriptions, advertising, open-access author fees, syndication | News agencies and publishers; advertising technology and audience measurement |
| Performing Arts & Live Events | Advance ticket sales, sponsorship, venue concessions, public cultural grants | Live events, ticketing and venues |
| Cultural Heritage & Public Institutions | Public funding, municipal grants, philanthropy, admissions, commercial licensing | Museums, libraries, archives and heritage |
| Digital Gaming & Interactive Media | Storefront sales, in-game purchases, battle passes, sponsorship | Games and online game services |
| (cross-cutting) | - | Media technology, content delivery networks (CDNs), cloud and managed services |

[U-001] [U-004] The user input states that subsectors are evaluated separately where evidence diverges and that findings from one subsector are not treated as representative without justification (User-supplied).

---

## A. Scope statement

**Sector definition.** [U-001] Media & Cultural Services comprises entities that create, produce, aggregate, preserve, license and distribute information, cultural artefacts and entertainment content (User-supplied definition, adopted for this record).

**Horizons.**
- Baseline edition (Q01-Q07): historical landmarks labelled historical; reporting period 1 September 2025 to 15 October 2026; 30 days before the 15 October 2026 cut-off.
- User input (Q10-Q14): last 30 days 28 September to 27 October 2026; rolling 12 months 28 October 2025 to 27 October 2026, including the FBI Internet Crime Complaint Center (IC3) 2025 dataset published in April 2026 [U-004]; historical landmarks before 28 October 2025 [U-001].
- The user input reports no named event dated inside its own last-30-days window (gap, section F).

**Jurisdictions.** EU, UK and US primary for fraud, governance and regulation (user input); EU, EEA and UK primary for cyber and operational resilience, with US, Japanese, Pakistani and Australian comparators (baseline).

---

## B. Executive summary for Senior Credit Officers

**Provisional ratings (no approved rubric):**
- **Fraud: High, confidence Medium** - high production turnover, decentralised disbursement authority in project special purpose entities (SPEs), complex licensing and royalty chains and reliance on public grants and tax credits; the sector has documented US enforcement cases, but sector-cut quantitative data are survey or investigated-case datasets only [U-004, U-008, U-015].
- **Cyber / ICT: High, confidence High** - universal digital dependency, large public-facing attack surfaces, legacy IT in public cultural bodies and extortion over unreleased content; in-period cases include the Dresden State Art Collections and regulator-recorded broadcast hijacks [S-001, S-014, U-001, U-002].
- **Operational resilience / TPRM: High, confidence High** - dense concentration in cloud hosting, CDNs and ticketing platforms, where one supplier failure halts revenue for many organisations at once [S-008, S-038, S-039, U-002, U-010].
- **Governance / operating model: Medium, confidence Medium** - non-standard SPE structures, fragmented IP ownership and heavy use of intermediaries, partly offset by established governance norms at large listed groups [U-004, U-008, U-012, U-017].

**Three key findings.**
1. [S-001] [S-034] [U-001] Legacy infrastructure combined with compromised privileged credentials produces multi-month to multi-year disruption at public cultural bodies, as the British Library and Dresden cases show; transactional and payment channels recover last.
2. [S-008] [S-038] [S-039] [U-010] Concentrated reliance on shared ticketing, cloud and CDN providers creates single points of failure that stop sales and delivery across many borrowers at once.
3. [U-004] [U-029] [U-031] The UK failure-to-prevent-fraud offence under the Economic Crime and Corporate Transparency Act 2023 (ECCTA), in force since 1 September 2025, adds corporate liability for fraud by associated persons, including sales agents and intermediaries, at large organisations.

**What a lender should ask a Media & Cultural Services borrower** [U-001] [U-004] [U-008]: what dual-authorisation controls apply to bank-detail changes across vendor, project and royalty payments; what tested recovery time objectives (RTOs) exist for cloud, CDN and digital asset management dependencies; how third-party sales agents and intermediaries are monitored under the ECCTA associated-person regime; and which shared ticketing, payment and delivery providers could stop sales or output for a week (baseline challenge question) [S-008, S-038].

---

## C. Four-dimension rating matrix (Q15)

| Dimension | Proposed rating | Status | Confidence | Principal drivers | Key evidence | Lender consequence | Fraud-Cyber overlap note | Main gaps |
|---|---|---|---|---|---|---|---|---|
| Fraud | High | Provisional | Medium | Production churn; decentralised SPE disbursement authority; complex royalty and licensing structures; grant and tax-credit reliance [U-004] | US v. Brown (USD 12m film-fund misappropriation) [U-008]; ACFE 2026 global median loss USD 104,000 [U-015]; SEC v. IRL (USD 170m offering fraud) [U-003]; baseline: phishing and payment-diversion risk after ticketing data exposure [S-009, S-010] | Working-capital depletion, covenant breaches, earnings restatements, legal defence costs [U-004] | Compromise mechanism mapped to Cyber; deception, false representation and payment diversion mapped to Fraud [U-004] | No subsector-specific complaint totals in law-enforcement datasets [U-005]; private SPE losses rarely disclosed [U-004] |
| Cyber / ICT | High | Provisional | High | Universal digital dependency; legacy systems in public bodies; large attack surfaces; high IP value [U-001] | British Library 2023 ransomware (GBP 1.6m direct cost; 18-month renewal) [U-002, U-011]; FBI IC3 2025 [U-005]; Dresden 2026 [S-001]; FCC-recorded stream hijacks [S-014]; media 14.2% of mitigated HTTP DDoS requests in H1 2026 [S-042] | Multi-month interruption, revenue loss, infrastructure replacement, reputation damage [U-002] | Initial access and lateral movement mapped to Cyber; downstream extortion payment demands mapped to Fraud [U-002] | No breakout for unlisted digital media firms in global incident datasets [U-001] |
| Operational resilience / TPRM | High | Provisional | High | High vendor density (CDNs, cloud, ticketing, visual effects); low immediate substitutability; single points of failure [U-002] | British Library rebuild delayed by legacy application lock-in [U-001]; DBIR 2025 30% third-party breach share [U-010]; shared ticketing outage March 2026 (Tier 3 detail) [S-008, S-010]; AWS and Cloudflare outages 2025 [S-038, S-039] | Cash-flow disruption, ticket refunds, contractual penalties from distribution delays [U-001] | Intrusion via a third-party supply chain mapped to TPRM and Cyber; fraudulent payment instructions via a compromised vendor mapped to Fraud [U-004] | No quantified losses for mid-tier live-event hosting disruptions [U-001]; supplier market shares not public [S-008] |
| Governance / operating model | Medium | Provisional | Medium | Complex SPE networks; fragmented IP rights ownership; heavy use of external talent and agents; variable board oversight [U-008] | SEC v. Icaro Media Group [U-012]; SEC v. BF Borgers (USD 14m penalty for audit fraud) [U-017]; ECCTA section 199 liability [U-004]; Cour des comptes Louvre findings [S-037] | Failure-to-prevent fines, debt acceleration after restatement, loss of sponsor backing [U-004] | Fraudulent financial reporting mapped to Governance; execution via unauthorised accounting-portal access mapped to Cyber [U-012] | No data on internal-audit coverage at non-listed mid-market production entities [U-001] |

**Rating rules applied.** No approved rubric, so all ratings are Provisional. Confidence reflects evidence quality and is stated separately. Fraud confidence is held at Medium because its sector evidence combines enforcement cases with multi-sector survey and investigated-case datasets. Complexity is not treated as proof of weak governance. The ratings in this matrix are those proposed in the user input; the baseline migrated edition had rated Fraud and Governance as Not assessable and Cyber / ICT and Operational resilience as High with Medium confidence (change log, section H).

---

# Part A - Core sector intelligence (Q01-Q07, unchanged from the baseline edition)

## Q01 - Sector operating model and key dependencies

**Sector footprint (Benchmark).**
- [S-045] The EU cultural sector employed 8.9 million people in 2025, 4.3% of total employment.
- [S-046] UK creative industries generated GBP 145.8 billion of gross value added (GVA) in 2024, 5.5% of UK GVA, and the cultural sector GBP 40.3 billion, 1.5%, with overlap between the two.

**Essential processes.** Live output and playout; newsroom publication; content production, rights management and licensing; streaming and online game delivery; online ticketing, shops and card payment; public access to collections, catalogues and archives; advertising sales and subscriptions.

**Subsector coverage in the baseline evidence.**

| Subsector | In-period public evidence | Evidence strength | Main gap |
|---|---|---|---|
| Broadcasters (TV and radio) | US radio stream hijacks; Pakistani satellite feed hijacks; Dutch regional broadcaster ransomware | Tier 1 regulator and broadcaster statements; Dutch case Tier 3 only | No EU or UK broadcaster incident with a retrievable Tier 1 statement |
| Transmission, playout and distribution | FCC content-insertion rules; satellite feed hijack | Tier 1 | No EU or UK transmission-provider incident |
| News agencies and publishers | Lee Enterprises costs (historical attack); German regional publisher DDoS | Tier 1 filing; Tier 3 for DDoS | No in-period EU publisher cost disclosure |
| Streaming platforms (video and audio) | Spotify catalogue scraping; audio platform data exposure | Tier 1 court order; Tier 3 | No quantified streaming revenue loss |
| Music, publishing and rights management | Label and platform litigation | Tier 1 court order | No collecting-society incident found |
| Film, TV, post-production and visual effects | None in period | Not available | Pre-release leak pathway evidenced only historically |
| Games and online game services | Cloud outage effects; games publisher hit via a fourth-party integration | Tier 3; Tier 1 for the cloud event | No quantified in-period games cost |
| Advertising technology and audience measurement | Political advertising rules | Tier 1 legal | No in-period incident evidence |
| Live events, ticketing and venues | Live-events group breach notice and class actions; shared ticketing provider ransomware | Tier 1 regulator notice and court complaint; ticketing ransomware Tier 3 except provider dependency | No provider-confirmed scale or cost for the ticketing outage |
| Museums, libraries, archives and heritage | Dresden State Art Collections; British Library recovery; Louvre audit | Tier 1 | No cost disclosure for Dresden |
| Media technology, CDN, cloud and managed services | AWS and Cloudflare outages; municipal IT provider attack in Leipzig | Tier 1 provider reports; Tier 3 | Market shares not public |

**Dependency map (documented dependencies only).**

| Dependency | Evidence | Concentration pathway | Who is exposed |
|---|---|---|---|
| Shared ticketing and visitor platforms | [S-008] Vivaticket and the national monuments network | One provider hosts sales and data for many institutions | Museums, monuments, libraries, venues and their payment providers |
| Hyperscale cloud regions | [S-038] AWS US-EAST-1, October 2025 | One region failure affects many dependent services | Streaming, online games, publishers |
| Content delivery networks | [S-039] Cloudflare, November 2025 | One configuration error causes global errors | News sites, streaming, ticketing |
| Analytics and SaaS integrations | [S-021] Anodot token theft, April 2026 (Tier 3) | Stolen integration tokens reach customers' cloud data | Games publishers and platforms |
| Broadcast content-insertion and satellite paths | [S-014] [S-018] US streaming encoders; Pakistani satellite feeds | Remote access or uplink path inserts content into live output | Broadcasters and their audiences |
| Municipal and public-sector shared IT | [S-028] Leipzig municipal IT provider (Tier 3) | One provider serves opera, concert hall, theatre and city services | Publicly owned cultural bodies |

[S-008] [S-038] [S-039] [S-021] [S-014] [S-018] [S-028] Dependencies are named only where a source supports them; market shares of ticketing, playout and collection-management providers are not public and no provider is described as dominant (Observed and Judgement).

**Disclosure asymmetry (Judgement).** [S-001] [S-030] [S-032] [S-034] [S-015] Public cultural bodies publish chronologies but rarely costs, listed groups disclose costs and revenue effects, and private platforms surface mainly through notices, litigation or attacker claims. Absence of cost disclosure for cultural bodies is a data gap, not evidence of low loss.

**Financial-system relevance (conditional channels).** (a) Credit to leveraged media groups, where [S-031] Lee's post-incident waivers became additional debt; (b) advertising, subscription and licensing revenue, where [S-030] [S-032] print advertising capacity and online video revenue were curtailed; (c) ticketing and payment flows, where [S-009] [S-010] exposed customer contact data creates phishing and payment-diversion risk even when card data is held by a separate provider; (d) insurance, where [S-030] Lee filed claims for USD 6.8 million and [S-023] Hasbro, a cross-sector comparator, warned that reimbursement may lag expense recognition; (e) public-funding absorption for cultural bodies, as [S-033] the British Library's funding support shows. These are not statements about any institution's exposure, losses, capital or Risk Appetite Framework (RAF) position.

## Q02 - Historical and recent cyber incidents, including case studies

**Selection criteria.** Named incidents qualify only if (1) the event or its regulatory or judicial outcome falls inside 1 September 2025 to 15 October 2026; (2) existence is supported by at least one Tier 1 or Tier 2 source; (3) the affected organisation belongs to a subsector in scope; and (4) the case adds a distinct operational lesson. Hacktivist and threat-actor claims, leak-site entries and Tier 3-only reports are excluded as named incidents.

**Top five named incidents in the period.**

| # | Incident | Subsector | Place and date | Operational vulnerability | Consequence | Evidence strength | Sector relevance |
|---|---|---|---|---|---|---|---|
| 1 | Dresden State Art Collections (SKD) cyberattack | National cultural institution | Germany; 17-21 January 2026 onward | Corporate IT, online shop, visitor services and payments | Online shop and ticketing offline; cash-only sales; special police commission | Tier 1 institution, ministry, prosecutor and police [S-001 to S-004] | High: recent EU case with the most complete primary chronology |
| 2 | US radio stream hijacks via studio-transmitter-link devices | Broadcast radio | United States; November 2025 onward | Unsecured streaming and alerting equipment | Live output replaced with unauthorised audio; regulator warning and new rule | Tier 1 regulator order records the attacks [S-014]; station detail Tier 3 [S-013] | High: live-output and alert integrity |
| 3 | Pakistani news channels' satellite feed hijacks | Broadcast television | Pakistan; 1 March 2026 | Satellite feed and possible uplink path | Unauthorised content aired on several channels; national CERT investigation | Tier 1 broadcaster statement [S-018]; breadth Tier 3 [S-019, S-020] | Medium-high: satellite signal integrity |
| 4 | Spotify catalogue scraping by a shadow library | Audio streaming and recorded music | Global; December 2025 - April 2026 | Account-based scraping and circumvention of technical protection | Worldwide injunction; reported USD 322 million judgment unlikely to be collected | Tier 1 court order [S-015]; amounts Tier 3 [S-016, S-017] | Medium: IP value channel |
| 5 | Live-events group breach notice and class actions (Live Nation) | Live events and ticketing | United States; October 2026 | Identity and health data in corporate systems (scope per company statement, Tier 3) | Regulator notice; at least one federal class action within a week; company reports no operational impact | Tier 1 regulator register and court complaint [S-086, S-087]; statement Tier 3 [S-074] | Medium: data-exposure and litigation pathway |

**Incident notes.**
- **Dresden (January 2026).** [S-001] [S-002] A deliberate attack on 21 January 2026 affected large parts of SKD's digital infrastructure; the online shop and visitor services were unavailable while the security system remained operational and museums stayed open (Observed). Detailed case study below.
- **US radio stream hijacks (November 2025).** [S-014] The FCC's June 2026 order records attacks in which improperly secured, remotely accessible equipment was used to air unauthorised audio including alert tones, cites a Houston station hack of 23 November 2025 and states that successful attacks continued into 2026 (Observed). [S-013] The Houston station's programme was replaced through backup streaming equipment activated after a power outage; the FCC public safety bureau warned that similar attacks had inserted simulated or real Emergency Alert System (EAS) tones through unsecured studio-transmitter-link devices (Observed; Tier 3 detail). [S-014] In June 2026 the FCC required EAS participants to replace default passwords, patch promptly and segment remote management for content-insertion equipment (Observed).
- **Pakistani satellite feed hijacks (March 2026).** [S-018] Geo News stated that its satellite feed was hacked at the start of its 9 pm bulletin on 1 March 2026 after 24 hours of repeated attempts (Observed). [S-019] [S-020] Samaa TV and ARY News were reportedly also affected; Pakistan's National CERT opened an investigation into a possible uplink intrusion with no published findings or attribution (Observed; Tier 3 for breadth). The broadcast content is not reproduced.
- **Spotify catalogue scraping (December 2025 - April 2026).** [S-015] On 20 January 2026 the Southern District of New York found likely infringement by scraping from Spotify, issued a worldwide injunction, ordered registries, registrars and hosting providers to disable the defendant's domains and noted the defendant appeared unable to satisfy a judgment from US assets (Observed). [S-016] [S-017] The complaint alleges about 86 million music files copied using thousands of accounts; media report a USD 322 million judgment on 14 April 2026 with collection doubtful (Observed; amounts Tier 3).
- **Live Nation (October 2026).** [S-086] Live Nation Entertainment reported a security breach to the Vermont Attorney General on 1 October 2026 covering Social Security numbers, government ID numbers and health records; the register lists two Vermont residents and notes totals may rise (Observed; notification evidence only). [S-087] A proposed class action filed on 7 October 2026 in the Central District of California alleges notice came more than four months after the company learned of the breach; allegations are untested (Observed). [S-074] Trade media report three near-identical complaints and a company statement of limited scope and no operational impact (Tier 3). Judgement: a limited data incident can become litigation exposure within days, independently of any service disruption.

**Considered but not selected.**
- **Shared ticketing provider ransomware (Vivaticket), March 2026 - highest relevance; pattern case.** [S-008] The official ticketing site of the Centre des monuments nationaux (CMN), which manages about a hundred national monuments, names Vivaticket S.p.A. as the provider hosting and transmitting its ticketing data (Observed). [S-007] The Musee Guimet notice shows online reservations unavailable with redirection to a third-party office and on-site sales (Observed; undated). [S-010] [S-009] [S-011] French outlets relaying CMN, City of Lyon and national library (BnF) statements report ransomware at the provider on 2 March 2026, loss of online ticketing at the BnF, Louvre-Lens, Musee des Arts et Metiers, Guimet and four Lyon municipal museums, CMN reopening online sales on 12 March while the BnF still could not sell online on 19 March, and notification of the data protection authority (CNIL), the national cyber agency (ANSSI) and the Ministry of Culture, with a Paris prosecutor investigation (Tier 3 relays). [S-012] Reported scope reached nearly 3,500 European sites; contact and purchase data may have been exposed while bank-card data, held by a separate payment provider, was not; a ransomware group's claim is unconfirmed (Tier 3, low confidence). Not counted as a named incident because no Tier 1 source records the incident itself.
- [S-025] [S-026] RTV Noord, Netherlands: regional public broadcaster lost its systems on 6 November 2025 to untargeted ransomware, kept radio on air with CDs and vinyl and refused to pay (Tier 3; context).
- [S-024] SoundCloud, December 2025: ancillary dashboard accessed, email and public-profile data taken, with denial-of-service and VPN disruption following (Tier 3; context).
- [S-021] Rockstar Games via Anodot, April 2026: stolen integration tokens of an analytics provider used against at least a dozen companies' cloud data; publisher reported no player impact (Tier 3; context for P2).
- [S-022] [S-023] Hasbro: unauthorised network access identified 28 March 2026 with systems offline for weeks; not a core sector entity (Tier 1; comparator).
- [S-027] Uffizi Galleries, Italy: press claims of a months-long intrusion disputed by the director; national cyber agency investigation (Tier 3; contested).
- [S-028] [S-029] Leipzig municipal IT provider (July 2026) and a German regional publishing group DDoS (August 2026): limited disclosed effect (Tier 3).
- [S-030] [S-032] [S-033] Lee Enterprises (February 2025), KADOKAWA (June 2024) and the British Library (October 2023): attacks before the period; in-period financial and recovery disclosures are used in Q05.

**Shortfall statement.** Five incidents meet the standard, but only one is in the EU and none in the UK has a retrievable Tier 1 statement. The most relevant EU event, the March 2026 shared ticketing ransomware, is excluded as a named incident because its existence rests on Tier 3 relays. This reflects disclosure asymmetry and access limits, not absence of EU or UK incidents.

**Last 30 days before the 15 October 2026 cut-off.** [S-086] [S-087] Live Nation breach notice (1 October 2026) and class action (7 October 2026); [S-061] UK Cyber Security and Resilience Bill at House of Lords report stage (14 October 2026).

**Timeline of in-period developments.**
- [S-024] [S-025] November-December 2025: a Dutch regional public broadcaster and an audio streaming platform disclosed incidents through media statements (Tier 3; context).
- [S-013] 23 November 2025: US radio station live output hijacked through backup streaming equipment; FCC bureau warning.
- [S-015] 20 January 2026: US federal court worldwide injunction against a shadow library that scraped music files from Spotify.
- [S-001] 21 January 2026: Dresden State Art Collections hit by a targeted cyberattack.
- [S-018] 1 March 2026: Pakistani news channels' satellite feeds hijacked.
- [S-010] [S-009] 2 March 2026: ransomware at the ticketing provider used by France's national monuments network (Tier 3 relays).
- [S-014] 25 June 2026: FCC adopted binding cyber requirements for broadcast alerting and content-insertion equipment.
- [S-053] [S-054] [S-085] 2 August 2026: AI Act Article 50 transparency obligations began to apply; the Digital Omnibus on AI entered into force on 27 July 2026 and is reported to have left that date unchanged.
- [S-055] 11 September 2026: Cyber Resilience Act (CRA) manufacturer reporting obligations began.

### Detailed case study 1 (baseline): Dresden State Art Collections cyberattack

**Why this case.** [S-001] [S-003] [S-004] Dresden is the only recent EU case with a Tier 1 chronology from the affected institution, its ministry, the prosecutor and the state criminal police (Judgement).

| Candidate | Recency | Sector relevance | Causal clarity | Disclosed outcome | Evidence quality | Decision |
|---|---|---|---|---|---|---|
| Dresden State Art Collections | January 2026 | High (national cultural institution) | Medium | Service restoration dates; investigation | Three Tier 1 releases (22 January, 29 January, 19 February) | Selected |
| Shared ticketing provider | March 2026 | Highest (many institutions) | Medium | Outage dates; data scope | Tier 3 relays; Tier 1 only for provider dependency | Pattern case (case study 3) |
| British Library | October 2023 attack; 2026 status | High | High | Recovery milestones and performance | Tier 1 annual reports; user input adds cost and root cause | Historical (case study 2) |
| Lee Enterprises | February 2025 attack | Medium (US publisher) | Medium | Cost and credit effects | Tier 1 filings | Historical; Q05 |
| RTV Noord | November 2025 | High (public broadcaster) | Low | Continuity detail | Tier 3 only | Context only |

**Timeline.**

| Date | Event | Evidence |
|---|---|---|
| 17-21 January 2026 | Attack activity over several days per a ministerial answer to a parliamentary question | [S-006] Tier 3 relay |
| 21 January 2026 | Deliberate cyberattack (ministry release); large parts of digital infrastructure affected; crisis team formed | [S-001] Tier 1 |
| 22 January 2026 | Online shop and visitor services unavailable; telephone and digital contact limited; security system unaffected; museums open | [S-001] [S-002] Tier 1 |
| 26 January 2026 | Website available again except some functions | [S-003] Tier 1 |
| 29 January 2026 | Telephone restored; online shop offline; on-site sales cash only; pre-booked tickets valid | [S-003] Tier 1 |
| 19 February 2026 | State criminal police special commission under prosecutor direction announced | [S-004] Tier 1 |
| By 20 February 2026 | Online tickets bookable again | [S-005] Tier 3 |
| July 2026 | Case against unknown persons still pending under the Saxon cybercrime prosecution unit | [S-006] Tier 3 relay |

**Mechanism.** [S-001] [S-006] Deliberate attack affecting large parts of the digital infrastructure, with activity between 17 and 21 January 2026. No initial access vector, attacker identity, ransom demand or data exfiltration has been published. Judgement: activity over several days before containment suggests a detection lag in a state cultural body's corporate IT.

**Outcomes.** [S-004] A special investigation commission was set up; [S-006] the case remained pending in July 2026. No cost, insurance, data-protection notification or penalty was published by the cut-off. [S-005] An unconfirmed tabloid report linking the attack to a planned theft was neither confirmed nor denied by investigators (low confidence; not used as a finding).

**Recovery constraints and lesson.** [S-003] Information channels returned first and transactional and payment channels last: the website within five days, the online shop and card payment later (Observed). Judgement: a museum network's front-of-house revenue channels depend on the same corporate IT that attackers reach; physical security appears to have been outside the affected systems, a plausible but unconfirmed reason being segregation. For banks (generic): public cultural counterparties can lose card-payment and online-sales revenue for weeks, and acquiring and merchant-service relationships see the effect first.

**What the case does not establish.** No quantified cost, data loss, insurance recovery, attacker identity, initial access vector or link to physical crime. It concerns one German state museum network.

### Detailed case study 2 (historical, baseline plus user input): British Library ransomware, October 2023

- **Attack and access (User-supplied, not validated).** [U-002] In October 2023 the British Library suffered a ransomware attack by the Rhysida group. [U-001] Initial access was through compromised privileged credentials on a legacy domain controller without multi-factor authentication (MFA). [U-002] Attackers encrypted key server infrastructure and exfiltrated sensitive operational data; physical Reading Rooms reopened shortly after, while digital catalogues, online collection access and internal administration were destroyed.
- **Recovery (User-supplied).** [U-001] Full recovery required an 18-month "Rebuild & Renew" modernisation programme to replace legacy applications. [U-011] [U-016] Direct financial losses were reported at GBP 1.6 million by June 2024, with long-term renewal costs absorbed through government funding requests and reserve repurposing.
- **Recovery status (baseline, Observed).** [S-034] The main catalogue was restored only in December 2025, about 26 months after the attack (derived from Tier 1 dates); [S-034] 2025/26 performance continued to be significantly affected, with 72.8% of KPIs within 10% of target against 81.8% the prior year, digital legal deposit performance measured at zero and website visits 14% below target; [S-033] DCMS supported financial stabilisation with a grant-in-aid uplift for 2025/26; [S-035] in September 2026 public access was still unavailable for several catalogues (status Tier 3).
- **Difference in measures.** The user input's 18 months describes the duration of the modernisation programme; the baseline's 26 months is the time to a new main catalogue, and the baseline records functions still unavailable in 2026. Both are kept.
- **Lesson.** Legacy-heavy public estates turn a single intrusion into a multi-year performance and funding effect.
- **Does not establish.** Total cost of renewal, ransom-related outcomes or effects on lenders.

### Detailed case study 3 (pattern case, baseline): shared ticketing provider ransomware, March 2026

[S-008] [S-010] [S-009] [S-011] [S-012] One ticketing provider serving about a hundred national monuments and many museums was reportedly compromised on 2 March 2026; online sales stopped across many sites; CMN reopened online sales after 10 days (derived, Tier 3 relays) and the BnF still could not sell online on 19 March. [S-007] Alternative ticket offices and on-site sales kept venues open. Lesson: one supplier can remove public-access revenue channels across a national heritage network at once. Does not establish: provider-confirmed scale, cost, data volumes or attacker identity.

**Cyber-enabled fraud in the baseline.** [S-009] [S-010] Exposed contact and purchase data at the ticketing provider prompted phishing warnings even though card data sat with a separate provider (Tier 3). No named in-period sector business email compromise (BEC) victim with primary disclosure was found in the baseline research.

## Q03 - Threat assessment, attack pathways and exploited weaknesses

| Pathway (pattern) | Operational vulnerability | Systemic or concentration translation | Evidence base |
|---|---|---|---|
| P1 Ransomware and extortion against institutions and publishers | Encryption or isolation of ticketing, shop, newsroom, playout and catalogue systems | Recovery of legacy estates can take months to years | Dresden 2026 [S-001]; Lee 2025 [S-030] (historical); British Library 2023 [S-034] (historical) |
| P2 Shared front-of-house platforms and SaaS integrations | Ticketing, payment and analytics providers hold tokens and customer data for many institutions | One supplier incident removes revenue channels at hundreds of sites | Ticketing provider 2026 [S-008, S-012] (Tier 3 detail); games publisher via analytics integration 2026 [S-021] (Tier 3) |
| P3 Broadcast signal and content-insertion compromise | Default passwords and remote access on streaming encoders, studio-transmitter links and alerting devices | Hijacked live output or false alerts reach audiences directly | FCC 2025-2026 [S-014]; Pakistani satellite feeds 2026 [S-018] |
| P4 Hacktivist DDoS and foreign information manipulation and interference (FIMI) around conflicts, elections and live events | Public-facing news sites and brands are impersonated or flooded | Coordinated campaigns hit many outlets at once | Cloudflare H1 2026 [S-042]; ENISA 2026 [S-041]; EEAS 2026 [S-043] |
| P5 Content and IP theft | Automated scraping through many accounts and circumvention of technical protection | Catalogue value at risk across rights holders | Spotify scraping 2025-2026 [S-015] |
| P6 Personal data exposure and litigation | Subscriber, player, donor, staff and ticket-holder data in ancillary systems | Class actions and regulator scrutiny follow notification | Live-events notice [S-086]; audio platform and ticketing exposures 2025-2026 [S-024, S-012] (Tier 3) |

**Benchmarks.**
- [S-042] Media, Production and Publishing received 14.2% of mitigated HTTP DDoS requests on Cloudflare's network in H1 2026, nearly four times the next industry; Cloudflare attributes this to coverage of the wars in Iran and Ukraine and to the World Cup.
- [S-041] ENISA analysed 8,257 EU incidents in 2025; business services were 8.45% of events, with hospitality, consultancy and broadcast media together 55.3% of those; NoName057(16) accounted for 35.8% of ideology-driven claims in that group; broadcast media mostly faced hacktivist disruption of public-facing platforms.
- [S-043] The EEAS recorded 540 FIMI incidents in 2025, names the media sector a priority target and reports impersonation of established outlets and fabricated media brands.
- [S-044] In the UK, 63% of information and communication businesses and 28% of charities reported breaches or attacks in the year to the 2025/26 survey.

**Principal judgements (baseline; confidence medium unless stated).**
1. Shared front-of-house platforms are the best-documented propagation pathway [S-008, S-001, S-038, S-039]. Competing explanation: public institutions publish access effects while back-office and content losses go unreported. Would change: disclosure of large content, archive or production losses exceeding access effects.
2. Broadcast signal and content-insertion integrity is under-secured in the available evidence [S-014, S-018]. Competing explanation: cases may be opportunistic and concentrated outside the EU and UK. Would change: evidence that EU and UK playout estates meet equivalent baselines.
3. DDoS and FIMI pressure is high but outcome-light [S-042, S-043, S-041]. Competing explanation: undisclosed advertising or subscription losses. Would change: multi-day DDoS outages with quantified revenue effect.

**Ranking (migrated judgement, not measured outcome).** 1 P2 shared platforms - High; 2 P3 live-output compromise - High; then P1, P4 and P6, with P5 resting on one court case. Direction: not assessable from a baseline edition without a trend series.

## Q04 - Cyber resilience capabilities and sector control benchmarks

| Priority capability | Weakness evidenced | Control objective | Action or challenge question | Role type | Horizon | Confidence |
|---|---|---|---|---|---|---|
| A1 Shared front-of-house platforms | [S-008] [S-038] [S-039] Ticketing, payment, CDN and cloud single points of failure | Know and limit concentration | Map which ticketing, payment, CDN and cloud providers the largest counterparties depend on; ask for tested fallback sales and delivery channels | 1LoD sector risk owner | 0-6 months | Medium |
| A2 Broadcast content insertion and signal paths | [S-014] [S-013] Default passwords and remote access on encoders, studio-transmitter links, alerting and satellite uplinks | Prevent hijacked output and false alerts | Ask for evidence of password, patching and segmentation baselines equivalent to the FCC rule | 1LoD operational resilience | 0-6 months | Medium |
| A3 Ransomware against institutions and publishers | [S-001] [S-003] Corporate IT shared with ticketing, shop, newsroom and playout | Segregate and recover | Ask whether security, building and playout systems are segregated from corporate IT and whether recovery of transactional channels is tested | 1LoD third-party risk | 3-12 months | Medium |
| A4 Payment and phishing follow-on | [S-009] [S-010] Exposed ticket-holder, subscriber and donor contact data | Stop payment diversion and card fraud | Monitor fraud typologies after sector exposures; confirm out-of-band confirmation in merchant and donor payment flows | 1LoD payments and fraud | 0-3 months | Medium |
| A5 Brand impersonation and synthetic media | [S-043] [S-053] Spoofed outlets, fabricated brands, AI-generated content | Protect provenance and trust | Ask how impersonation is detected and AI Act transparency duties met | 1LoD sector risk owner | 6-12 months | Medium |
| A6 Long recovery tails and funding | [S-031] [S-034] [S-044] Legacy estates and thin insurance | Align credit and funding expectations | Ask about RTOs, insurance cover and waiver triggers | 1LoD credit | 6-12 months | Medium |

| Exposure | Evidence of completion | Residual dependency | External monitoring trigger |
|---|---|---|---|
| A1 | Dependency map for top sector counterparties; fallback test records | Providers outside counterparty control | Provider outage or breach notice; prosecutor statement naming a supplier |
| A2 | Baseline attestation for content-insertion equipment | Legacy devices that cannot be patched | Regulator warning on content-insertion devices; satellite hijack report |
| A3 | Segregation and restoration test evidence | Shared public-sector IT | Sector incident notice; ransomware advisory naming media |
| A4 | Fraud typology monitoring and confirmation procedure | Compromised legitimate customer accounts | Ticketing or subscriber data exposure notice |
| A5 | Provenance and labelling procedure | Platform distribution outside counterparty control | EEAS or national FIMI alert; election calendar |
| A6 | Recovery objectives, insurance schedule, covenant terms | Public-funding decisions | Waiver or amendment request; annual report recovery disclosures |

**Voluntary frameworks (not law).** [S-071] EBU R 148 defines minimum security tests for networked media equipment; published April 2018 and not updated since. NIST CSF 2.0 (Govern, Identify, Protect, Detect, Respond, Recover), ISO/IEC 27001 and 27002, ISO/IEC 27036 (supplier relationships), ISO 14721 (digital preservation), CIS Controls, EBU R 143, AMWA NMOS and SMPTE guidance, the MPA Trusted Partner Network, C2PA content provenance, ETSI EN 303 645, PCI DSS v4.0.1 and IFLA and ICOM guidance are used as reference vocabularies only; their texts were not reviewed in the baseline run.

**Maturity benchmark.** [S-044] Only 35% of UK charities held cyber insurance in the 2025/26 survey (Benchmark). No sector cyber-maturity survey was available in the baseline (gap); the user input adds structural weaknesses under Q11.

## Q05 - Financial impact, disruption trends and credit transmission

**Bottom line.** Public financial evidence is sparse and cannot be added up. No EU or UK entity disclosed a quantified cyber cost for an in-period incident. The quantified cases are a US newspaper group and a Japanese publisher and platform group, with attacks before the period and disclosure during or just before it. The dominant mechanism is revenue-line disruption and recovery time, with credit and insurance effects following.

| Case | Metric type | Value | Period | Population | Comparability note | Source |
|---|---|---|---|---|---|---|
| Lee Enterprises | Loss of cash flows attributed to incident | USD 10.5 million | FY to 28 September 2025 | One US newspaper group | Includes amounts claimed from insurers | [S-030] |
| Lee Enterprises | Restoration cost expensed | USD 3.7 million | FY to 28 September 2025 | Same | Subset of the USD 10.5 million | [S-030] |
| Lee Enterprises | Insurance claims filed | USD 6.8 million | FY to 28 September 2025 | Same | Claim, not recovery | [S-030] |
| Lee Enterprises | Debt added by lender and landlord waivers | USD 11.3 million | As at 28 September 2025 | Same | Non-cash credit effect | [S-031] |
| KADOKAWA | Sales effect (company estimate) | JPY 8.3 billion | FY to 31 March 2025 | One Japanese publisher and platform group | Estimate; attack June 2024 | [S-032] |
| KADOKAWA | Operating profit effect (estimate) | JPY 4.7 billion | FY to 31 March 2025 | Same | Not additive with special loss | [S-032] |
| KADOKAWA | Special loss | JPY 2.4 billion | FY to 31 March 2025 | Same | Accounting loss | [S-032] |
| British Library | KPIs within 10% of target | 72.8% versus 81.8% prior year | 2025/26 | One national library | Not all shortfall attributed to the attack | [S-034] |
| British Library | Time to new main catalogue (derived) | About 26 months | October 2023 - December 2025 | Same | Derived from Tier 1 dates | [S-034] |
| British Library | Direct financial loss (User-supplied) | GBP 1.6 million | By June 2024 | Same | User-supplied, not validated; renewal costs excluded | [U-011] [U-016] |
| Dresden State Art Collections | Time to website restoration (derived) | 5 days | 21-26 January 2026 | One state museum network | Some functions still unavailable | [S-001] [S-003] |
| Dresden State Art Collections | Time to online booking (derived upper bound) | 30 days or fewer | 21 January - 20 February 2026 | Same | End date from Tier 3 report | [S-005] |
| CMN ticketing (shared provider) | Time to reopen online sales (derived) | 10 days | 2-12 March 2026 | National monuments network | Tier 3 relays | [S-010] |
| Spotify and labels | Reported damages award | USD 322 million | Judgment 14 April 2026 | One civil case | Award, not a loss measure; Tier 3; collection doubtful | [S-017] |
| Dresden State Art Collections | Cost, data, insurance | Not disclosed | 2026 | One state museum network | Absence of data is not zero | [S-001] |

[S-030] Lee attributes USD 10.5 million of lost cash flows to the 3 February 2025 attack, of which about USD 3.7 million was expensed as restoration cost, with insurance claims for the remaining USD 6.8 million; print advertising capacity was limited for several months and the incident contributed to digital advertising decline and a temporary liquidity disruption. [S-031] The lender and landlord waived three months of interest and lease payments, increasing debt by USD 11.3 million; USD 6.4 million of insurance proceeds in the nine months to 28 June 2026 are not explicitly linked to the incident (link is a Proxy). [S-032] KADOKAWA's estimate splits Web Services sales down about JPY 3.95 billion and domestic print publishing down about JPY 3.65 billion.

**Comparability.** Values differ in currency, statistic type, population and accounting regime; they are never summed or averaged and no sector-wide loss estimate is produced.

**Impact types.**

| Impact type | Public evidence in scope | Status |
|---|---|---|
| Service disruption | [S-001] [S-008] [S-014] [S-018] [S-038] [S-039] Dresden shop and ticketing; shared ticketing outage; radio and satellite hijacks; cloud and CDN outages | Observed; durations partly derived |
| Response cost | [S-030] [S-023] Lee USD 3.7 million; Hasbro costs from Q2 2026 unquantified | Observed for one company |
| Recovery and rebuild cost | [S-034] [S-037] [U-001] British Library rebuild; Louvre audit on underinvestment | Qualitative; baseline costs not read |
| Revenue and cash-flow effect | [S-030] [S-032] [S-033] Lee advertising; KADOKAWA Web Services and print; British Library footfall-linked income | Observed (historical) |
| Contractual and supplier impact | None disclosed in period | Not evidenced |
| Content and IP loss | [S-015] [S-017] Spotify scraping injunction and judgment | Observed; collection doubtful |
| Data-breach notification and remediation | [S-086] [S-012] [S-024] Live-events notice; ticketing and audio platform data | Observed |
| Regulatory outcome | [S-010] [S-004] [S-019] [S-014] Investigations opened; FCC rule | Observed; no penalty in period |
| Litigation | [S-087] [S-030] Live-events class actions; Lee litigation | Observed; no outcome |
| Insurance effect | [S-030] [S-023] [S-044] Lee USD 6.8 million claimed; Hasbro; 35% of UK charities insured | Observed; recoveries lag |
| Public funding or reserves | [S-033] [U-011] British Library DCMS support; reserve repurposing (User-supplied) | Observed and User-supplied |
| Wider economic transmission | [S-031] Lee debt increase through waivers | Observed for one borrower |

[S-036] Toronto's Auditor General reported a cybersecurity audit of Toronto Public Library in May 2026, after its October 2023 attack, with findings in a confidential attachment and implementation cost not determinable. [S-037] The Cour des comptes found the Louvre allocated EUR 26.7 million to maintenance and compliance against EUR 105.4 million to acquisitions and recommended a full information systems and digital directorate by end-2026 (context, not cyber-specific).

**Credit transmission.** Disruption -> lost output, publication or sales -> advertising, subscription and ticketing cash flow -> temporary liquidity disruption [S-030] -> waivers and debt service [S-031] -> insurance recovery that lags costs [S-023]. Channels:
- Recovery long tail [S-034, S-035]: legacy-heavy cultural estates absorb multi-year performance and income effects (Judgement).
- Credit to leveraged media groups [S-031]: the bank-relevant signal is unscheduled waiver or amendment activity (Judgement).
- Advertising and subscription revenue [S-030, S-032]: in the two quantified cases, revenue effects arose from production and distribution outages rather than from data theft (Judgement).
- Ticketing and payment flows [S-009, S-010]: payment-diversion and card-not-present fraud attempts can follow ticketing exposures, affecting acquiring and issuing banks (Judgement).
- IP value [S-015]: catalogue-scale scraping may reduce the value of exclusivity; no evidence of a valuation or collateral effect (Judgement).
- Insurance timing [S-023, S-044]: uninsured cultural charities absorb losses through reserves or public funding (Judgement).
- Concentration [S-038, S-039]: single cloud and CDN failures lasted about 6 to 14.5 hours; correlated outages across many borrowers can coincide with high-value live events (Judgement).

**Worst-case scenarios (structured stress narratives; not forecasts or loss estimates; no probabilities).**

| Element | Scenario 1 - Common digital-dependency failure | Scenario 2 - Targeted operational disruption | Scenario 3 - Third- or fourth-party supply-chain concentration |
|---|---|---|---|
| Trigger (Assumption) | [S-038] [S-039] Multi-hour failure or attack on a shared cloud region, CDN, identity service or satellite capacity operator during a major live event | [S-001] [S-014] [S-018] Ransomware or intrusion at a major broadcaster, news organisation or national cultural institution, or compromise of content-insertion, satellite or alerting equipment during an election or live event | [S-008] [S-009] Compromise of an application-layer supplier (ticketing, collection management, newsroom, playout, media asset management or its managed service provider) or theft of its integration tokens |
| Affected service | Live streaming, online games, ticket sales, news publication | Live output and playout, publication, public access, emergency alerting | Online ticketing and payments, catalogue access, newsroom and playout tools, customer data |
| Propagation | [S-038] [S-040] AWS October 2025 disruption about 14 hours 32 minutes; games reported disrupted (Tier 3 for customers) | [S-003] [S-013] [S-018] Containment isolates ticketing, shop and payments; hijacked output reaches audiences | [S-008] [S-010] [S-021] One provider served about a hundred monuments and many museums; analytics tokens reached at least a dozen companies |
| Impact drivers | [S-042] Media already draws the largest DDoS share | [S-030] [S-034] Months of curtailed advertising; years of reduced access | Simultaneous loss of revenue channels, notification duties, phishing follow-on |
| Financial transmission | Lost live audiences and advertising inventory, make-goods, refunds, correlated revenue dips | Off-air output, lost advertising and subscriptions, rebuild cost, licensee scrutiny, public-funding draw | Correlated ticketing revenue loss, customer-fraud exposure, supplier disputes, regulator reviews |
| Early signposts | Provider status incidents, DDoS spikes, hacktivist announcements before live events | Regulator device warnings, conflict escalation, election calendars, sector notices | Supplier breach notices, prosecutor statements naming a provider, attacker claims |
| Limiting conditions | [S-038] [S-039] 2025 failures were non-malicious and restored within a day; multi-provider delivery | [S-026] [S-001] Broadcaster kept radio on air with physical media (Tier 3); museums stayed open | [S-007] Alternative ticket offices and on-site sales |
| Management question | Which shared cloud, CDN and identity providers do the largest counterparties depend on, with tested failover before rights-sensitive events? | Is there evidence of segregated playout and security networks, manual fallback and hardened insertion devices? | Which suppliers serve a large share of museums, venues or broadcasters, and do counterparties hold exit and fallback arrangements? [S-049] [S-062] Is the supplier itself regulated? |
| Assumption | 6 to 14.5-hour durations illustrative, not predictive | Dresden (days to weeks), Lee (months), British Library (years) illustrate the range | Supplier serves hundreds to thousands of institutions (Tier 3); no immediate alternative channel |

**Illustrative disruption bands (not forecasts; no loss per band).**

| Band | Mechanism | Duration evidence | Credit channel |
|---|---|---|---|
| 1 week | Common digital-dependency failure | [S-038] [S-039] [S-003] AWS about 14.5 hours; Cloudflare about 6 hours; Dresden website back after 5 days | Lost live audience and advertising, make-goods, refunds |
| 4 weeks | Supply-chain concentration | [S-010] [S-005] Monuments network reopened online sales after 10 days, national library still unable on 19 March; Dresden booking within about a month (Tier 3) | Correlated ticketing cash-flow loss; phishing and payment fraud |
| 8 weeks | Targeted operational disruption | [S-030] [S-034] Lee print advertising limited for several months; British Library recovery over years | Margins, waivers and debt service |

Five-year cost trends and sector business-interruption benchmarks were not available in the baseline (gap).

## Q06 - Regulatory authorities and cyber resilience expectations

| Regime | Jurisdiction | Legal status | Obligation type | Key dates | Applicability to Media & Cultural Services | Source |
|---|---|---|---|---|---|---|
| NIS2 Directive (EU) 2022/2555 | EU | Binding directive via national law | Risk management, reporting, governance | In force 16 January 2023; transposition by 17 October 2024 | Media and culture not listed; reached through CDN, cloud, DNS, data centre, managed service and digital providers; state-owned cultural bodies may fall in scope as public administration subject to national definition | [S-048] [S-049] |
| CER Directive (EU) 2022/2557 | EU | Binding directive via national law | Resilience measures by designated entities | Applies 18 October 2024; identification by 17 July 2026 | Media and culture not listed | [S-050] |
| European Media Freedom Act (EU) 2024/1083 | EU | Directly applicable regulation | Protection of journalistic sources including against intrusive surveillance software | Most provisions applied 8 August 2025 | Media service providers and journalists | [S-051] |
| Political advertising Regulation (EU) 2024/900 | EU | Directly applicable regulation | Labelling, targeting consent, third-country sponsor restriction | Applies 10 October 2025 | Publishers and advertising services | [S-052] |
| AI Act (EU) 2024/1689, Article 50 | EU | Directly applicable regulation | Synthetic-content marking, deepfake disclosure, labelling of AI text on public-interest matters | Applies 2 August 2026; Article 50(2) marking for systems already on the market from 2 December 2026 (reported transition) | Newsrooms, producers, platforms; editorial-control exception | [S-053] [S-085] |
| Digital Omnibus on AI (EU) 2026/1744 | EU | Amending regulation | Amends AI Act timelines | In force 27 July 2026 | Reported to leave the Article 50 date unchanged; amending text not read | [S-054] |
| Cyber Resilience Act (EU) 2024/2847 | EU | Directly applicable regulation | Manufacturer reporting; essential requirements | Reporting 11 September 2026; main obligations 11 December 2027 | Broadcast and production equipment, connected TVs, set-top boxes, apps and games as products | [S-055] |
| Radio Equipment Directive delegated act (EU) 2022/30 | EU | Delegated regulation | Cybersecurity, data and fraud essential requirements | Applied August 2025; repealed with effect 11 December 2027 | Connected radio equipment until CRA applies | [S-056] |
| Digital Services Act (EU) 2022/2065 | EU | Directly applicable regulation | Systemic risk assessment incl. media freedom and electoral processes | Published 27 October 2022 | Largest platforms distributing media content | [S-073] [S-057] |
| GDPR (EU) 2016/679 | EU and EEA | Directly applicable regulation | Security; breach notification within 72 hours | Applies 25 May 2018 | Subscriber, audience, player, donor and ticket-holder data; Article 85 national derogations for journalistic and artistic purposes | [S-060] [S-083] |
| Audiovisual Media Services Directive as amended by (EU) 2018/1808 | EU | Binding directive via national law | Audiovisual and video-sharing content rules | Transposition by 19 September 2020 (Tier 3 tracker) | Cyber relevance not assessed | [S-082] |
| Live-event piracy Recommendation (EU) 2023/1018 | EU | Non-binding recommendation | Notice and injunction cooperation | Stock-take 20 November 2025 | Piracy context only | [S-058] |
| European Democracy Shield | EU | Commission Communication | Funding, coordination, fact-checking | 12 November 2025 | No binding duties | [S-059] |
| NIS Regulations 2018 | UK | Binding regulations | Essential services; limited digital services | In force 10 May 2018 | Media and culture outside scope except as providers | [S-063] |
| Cyber Security and Resilience Bill | UK | Bill at Lords report stage | Would add managed service providers, data centres, designated suppliers; 24/72-hour reporting | Report stage at 14 October 2026; no Royal Assent | Could reach media suppliers once enacted | [S-061] [S-062] |
| Telecoms security framework (Communications Act 2003 ss. 105A-105Z; 2022 Regulations) | UK | Binding duties; code is statutory guidance | Security duties for public electronic communications providers | In force 1 October 2022; code v1.1 of 14 July 2026 | Broadcast transmission in scope only if a public network; not confirmed | [S-078] [S-079] |
| Media Act 2024 | UK | Binding legislation | Public service broadcasting and on-demand regulation | Royal Assent 24 May 2024 | No cyber obligations in the text read | [S-076] |
| Online Safety Act 2023 | UK | Binding legislation | Platform illegal-content and child-safety duties | Enforceable 17 March 2025 | Platforms, not outlets as such | [S-077] |
| National Security Act 2023, s. 13 | UK | Binding criminal law | Foreign interference offences | In force 20 December 2023; amended from 8 July 2026 | State-linked interference targeting media | [S-075] |
| Consumer connectable product security regime | UK | Binding regulations | No universal default passwords; update information | Applies 29 April 2024 | Connected TVs and streaming devices | [S-064] |
| Data Protection Act 2018 special purposes | UK | Binding legislation | Exempts listed UK GDPR provisions; security and regulator notification not listed | 23 May 2018 | Newsrooms and arts bodies | [S-065] |
| Ransomware payment proposals | UK | Proposals | Payment ban for public bodies; reporting | Government response 22 July 2025 | Publicly funded cultural bodies if enacted | [S-066] [S-067] |
| Government Cyber Action Plan | UK | Government plan | Accountability of arm's-length bodies | 6 January 2026 | DCMS-sponsored museums and libraries | [S-068] |
| SEC Form 8-K Item 1.05 | US (comparative) | Binding for registrants | Material incident disclosure within four business days | From 18 December 2023 | Listed media, entertainment and games groups | [S-069] |
| FCC 26-38 alerting order | US (comparative) | Adopted rule; enforceable 60 days after Federal Register publication (status at cut-off unconfirmed) | Passwords, patching, segmentation for content-insertion equipment | Released 29 June 2026 | Broadcasters and cable operators | [S-014] |
| COPPA Rule amendments | US (comparative) | Binding rule | Children's data | Federal Register 22 April 2025 | Games and children's services | [S-070] |
| SOCI Act 2018, s. 12E | Australia (comparative) | Binding legislation | Infrastructure security regime naming broadcasting assets | Compilation June 2026 | Broadcast transmission operators meeting tests | [S-080] [S-081] |

**Interpretation (Judgement).** For most sector entities, cyber obligations are product, data-protection, media-specific and contractual rather than horizontal cyber regulation; the main in-period movements were AI Act transparency, CRA reporting and the FCC rule. [S-084] Commentary on Italy's NIS2 decree reports that entities with activities of cultural interest can be classified as important entities under conditions (Tier 3; not confirmed in primary text). [S-072] A final US cyber incident reporting rule (CIRCIA) was expected in September 2026; status unconfirmed (Tier 3). Fraud-prevention and corporate-governance law is covered in Q10.7 and Q13 from the user input.

**Forward monitoring horizon.** October-December 2026: ticketing provider and French investigation outcomes; late 2026: UK bill Royal Assent; from 11 September 2026: CRA reports; 2 December 2026: AI Act Article 50(2); FCC compliance date; autumn-end 2026: British Library UK Web Archive and electronic legal deposit restoration; ongoing: Dresden investigation and event-period DDoS and FIMI.

## Q07 - Geopolitical cyber threats and systemic exposure

| Geopolitical-to-cyber pathway | Baseline evidence | Attribution status |
|---|---|---|
| Conflict coverage -> DDoS against media | [S-042] Cloudflare links media's 14.2% DDoS share in H1 2026 to coverage of the wars in Iran and Ukraine and to the World Cup | Provider interpretation; no actor named |
| Hacktivist DDoS networks | [S-041] [S-047] NoName057(16) made 35.8% of ideology-driven claims in ENISA's business-services group (2025); Europol's Operation Eastwood disrupted its infrastructure in July 2025 and Germany issued six arrest warrants | Law-enforcement action; group claims remain claims |
| Information manipulation and brand impersonation | [S-043] EEAS recorded 540 FIMI incidents in 2025, impersonation of established outlets and fabricated brands; 2026 elections listed at risk | Institutional assessment |
| Broadcast signal hijack | [S-018] [S-019] Pakistani satellite feeds, March 2026 | No attribution published |
| Policy responses | [S-059] European Democracy Shield (12 November 2025); [S-051] European Media Freedom Act source protection (from 8 August 2025); [S-075] UK foreign interference offences (from 20 December 2023) | Not applicable |

**Judgement.** Conflicts, elections and major live events drive DDoS and information-manipulation pressure on media, but the evidence holds no confirmed state attribution for a sector incident. Brand impersonation and availability attacks matter most around elections, conflicts and live events, when audiences, advertisers and rights holders concentrate. State-linked activity is a monitoring trigger rather than a rating driver. Dedicated geopolitical analysis, exposed-region mapping and state-linked espionage against newsrooms were not researched (gap). The user input adds no geopolitical evidence.

---

# Part B - Classification evidence (Q10-Q14, updated 27 October 2026)

All U- content below is **User-supplied (not validated)**.

## Q10 - Sector fraud exposure and financial consequences

**Baseline position.** The baseline edition did not research fraud; it held only a judgement that phishing and payment diversion can follow ticketing data exposure [S-009, S-010] and the payment-control action A4. The user input supplies the material below.

### Q10.1 Typology screen

| Typology | Materiality | Cyber classification | Structural subsector vulnerability (as supplied) | Source |
|---|---|---|---|---|
| Payment diversion | Material | Hybrid (digital deception plus process weakness) | High in Film & Music Production and Live Events: frequent onboarding of temporary suppliers and high invoice volume | [U-004] |
| Business email compromise (BEC) | Material | Cyber-enabled | Universal; finance teams targeted through spoofed executive and vendor domains | [U-004] |
| Invoice and procurement fraud | Material | Hybrid | High in film production and cultural-heritage capital projects; unconfirmed vendor modifications | [U-004] |
| Supplier impersonation | Material | Cyber-enabled | Broadcasting and Gaming; fraudulent licensing agents intercepting distribution fees | [U-004] |
| Executive impersonation (incl. voice or video) | Material | Hybrid / AI-enabled | Corporate publishing and broadcasting; deepfake audio used to authorise urgent wires | [U-004] |
| Account takeover (ERP, banking) | Material | Cyber-enabled | Digital platforms and publishing; credential theft through infostealer malware | [U-010] |
| Insider fraud and embezzlement | Material | Non-cyber / process | Performing Arts and local production units; management override and dual-custody failures | [U-007] |
| Asset misappropriation | Material | Non-cyber | Physical distribution, live venues, cultural heritage (equipment and cash theft) | [U-007] |
| Financial statement fraud | Material | Non-cyber / governance | Micro-cap and private production and media-technology firms seeking capital; revenue misstatement | [U-006] |
| Corruption and bribery | Material | Non-cyber | International filming-location permits, public procurement, broadcasting-rights distribution | [U-004] |
| Synthetic identity fraud | Possible | Cyber-enabled | Digital Gaming and streaming account registration | [U-005] |
| Grant, subsidy and tax fraud | Material | Non-cyber / process | Film production (tax credits); Cultural Heritage and Performing Arts (public grants) | [U-004] |
| Fraud against the sector's customers | Material | Hybrid | Ticket-scalping fraud, fake event bookings, unauthorised subscription charges creating chargeback liabilities | [U-005] |
| Other sector-specific: box-office and royalty report fraud | Material (sector-specific) | Non-cyber / analytical | Under-reporting of box-office receipts or streaming counts to reduce licensor royalty payouts | [U-006] |

**Baseline cross-reference.** [S-009] [S-010] [S-012] The March 2026 ticketing exposure (Tier 3) is the baseline's only sector-specific cyber-enabled fraud precursor: contact and purchase data exposure followed by phishing warnings. [S-016] The Spotify scraping case is an IP-theft case, not a fraud case, and is not counted here.

### Q10.2 Documented fraud cases

| Case and jurisdiction | Subsector | Scheme and typology | Perpetrator and channel | Payment rail | Period and discovery | Loss and recovery | Documented control failures | Primary source (as cited) |
|---|---|---|---|---|---|---|---|---|
| US v. David Brown (US, C.D. Cal.) | Film production | Misappropriation of film-budget funds and investor fraud (USD 12m scheme) | Management / producer; falsified documentation and contracts | Commercial wire transfers; escrow accounts | December 2021 - August 2025; arrested August 2025 after federal investigation | Loss USD 12,000,000; minimal documented recovery | No independent dual-signatory controls on SPE bank accounts; no segregation of investor funds | US Attorney's Office, C.D. Cal. press release, 27 August 2025 [U-008] |
| SEC v. IRL and founder (US, S.D.N.Y.) | Digital media / social | Offering fraud (USD 170m raised) using fabricated user metrics and automated bot networks | Executive / founder; falsified platform dashboards | Equity capital | 2021-2024; SEC charges July 2024 | USD 170,000,000 equity capital; recovery pending litigation | Total reliance on self-reported operational KPIs without external data audit | SEC release, 31 July 2024 [U-003] |
| SEC v. Icaro Media Group, Inc. (US, S.D.N.Y.) | Digital media and broadcasting | Multi-million-dollar offering fraud with false revenue and fake distribution contracts | Executive / CEO (Paul H. Feller); paper reports, investor presentations | Investor wire transfers | 2021-2024; complaint 17 April 2024 | Multi-million USD; civil penalties sought | No independent board oversight; management override of financial reporting | SEC Litigation Release No. 25979, 17 April 2024 [U-012] |
| SEC v. BF Borgers CPA PC (US, federal) | Media and technology (auditor) | Systemic audit fraud ("sham audit mill") affecting public media companies including Trump Media | External auditor; fabricated audit work papers across 1,500 filings | Audit service fees | January 2021 - May 2024; settlement 3 May 2024 | USD 14,000,000 penalty (USD 12m firm, USD 2m owner); permanent ban | Complete breakdown of external audit independence and quality control | SEC press release and order, 3 May 2024 [U-017] [U-020] |
| SEC v. The Movie Studio, Inc. (US, S.D. Fla.) - historical baseline | Film distribution | False representation of film library size, fake production assets, false blockchain licensing claims | Executive / CEO; press releases and OTC disclosures | Micro-cap equity issuances | 2018-2021; SEC Litigation Release 13 August 2021 | Investor capital dilution; civil injunctions | No confirmed asset register for IP rights; unvalidated marketing claims | SEC Litigation Release No. 25166, 13 August 2021 [U-006] |

**Candidates rejected (as supplied).** Retail ticket-scalping rings (no direct institutional borrower impact), consumer piracy operations without corporate fraud elements, and unconfirmed media reports without court dockets or prosecutor releases [U-001].

**Coverage note (Judgement).** All five documented cases are US federal civil or criminal matters; no EU or UK sector fraud case is documented in either source set, and three of the five concern listed or quoted equity rather than operating fraud against a sector entity.

### Q10.3 Quantitative evidence

| Dataset and publisher | Dataset type | Geography | Observation period | Sector cut | Key metrics | Source |
|---|---|---|---|---|---|---|
| ACFE Occupational Fraud 2026 | Investigated cases (sample size not stated in the input) | Global, 143 countries | January 2024 - September 2025 | Arts, Entertainment and Recreation included | Global median loss USD 104,000; average USD 1,457,000; median duration 12 months; corruption in 45% of cases; asset misappropriation in 90% | [U-009] [U-015] [U-018] [U-007] |
| ACFE Occupational Fraud 2024 | Investigated cases (sample size not stated) | Global, 133 countries | January 2022 - September 2023 | Arts, Entertainment and Recreation included | Global median loss USD 145,000; owner or executive median loss USD 459,000; 43% detected through tips | [U-021] [U-022] |
| FBI IC3 Internet Crime Report 2025 | Reported complaints (sample size not stated) | United States (global victims) | January - December 2025 | Multi-sector total; media not separately shown (proxy) | Total reported loss USD 20.877 billion; BEC USD 3.05 billion; investment fraud USD 8.65 billion; AI-enabled crime USD 893 million | [U-005] |
| Verizon Data Breach Investigations Report (DBIR) 2025 | Incident and breach dataset (22,052 incidents, 12,195 breaches as transcribed from the input) | Global | November 2023 - October 2024 | Information and Entertainment patterns analysed | Third-party breach share 30%; ransomware in 44% of breaches; stolen credentials in 22%; human error in 60% | [U-010] [U-025] [U-026] |

**Dataset-type rule.** Investigated-case, complaint and breach datasets measure different populations and are never combined. The USD 104,000 figure is an all-industry global median, not a Media & Cultural Services figure (Judgement on the supplied label).

### Q10.4 Structural fraud exposure

| Feature | Applies? | Evidence (as supplied) |
|---|---|---|
| Payment intensity and urgency | Yes | Film production and live touring require rapid disbursement of high cash volumes to short-term vendors and freelancers under scheduling pressure that undermines standard confirmation [U-004] |
| Supplier and subcontractor density | Yes | Continuous onboarding of local subcontractors, caterers, equipment rental firms and technical crews creates high vendor-master-file churn, enabling mandate fraud and fake invoices [U-004] |
| Intermediaries and agents | Yes | Overseas sales agents, sub-distributors and regional licensing brokers create opaque reporting in which box-office receipts and streaming counts can be understated or manipulated [U-004] |
| Public funding and grants | Yes | Cultural institutions, independent films and performing-arts bodies rely on public grants, subsidies and film tax credits, creating exposure to grant inflation and subsidy misappropriation [U-004] |
| Decentralised operations and payment authority | Yes | Individual films and touring productions operate through autonomous SPEs with local bank accounts and delegated disbursement authority, often without direct oversight by parent finance functions [U-004] |
| Revenue-recognition complexity | Yes | Royalty and licensing chains; box-office and streaming-count reporting [U-004] [U-006] |
| Customer-facing payment flows | Yes | Ticketing, subscriptions and chargebacks [U-005]; baseline ticketing data exposure [S-009] |

### Q10.5 Controls, detection and governance failures

| Control category | Observed failure mechanism | Impacted subsectors | Illustrative evidence |
|---|---|---|---|
| Segregation of duties | One individual handles vendor set-up, invoice checks and disbursement approval [U-004] | Film production, live events, cultural heritage [U-008] | Unchecked wire transfers in project SPE accounts (US v. Brown) [U-008] |
| Management override | Executives bypass procurement controls to award contracts to connected parties [U-012] | Digital media, broadcasting [U-012] | ACFE 2024 data showing executive override behind major loss escalation [U-022] |
| Supplier onboarding | Vendor bank accounts updated on unconfirmed email or phone requests [U-004] | Universal [U-004] | Widespread BEC and payment-diversion incidents [U-004] |
| Whistleblower mechanisms | No secure anonymous channels or no follow-up of employee tips [U-015] | Performing arts, non-profit cultural bodies [U-018] | ACFE 2026: organisations without formal hotlines suffer 50% higher median losses [U-018] |

### Q10.6 Consequences

- **Direct working-capital depletion** [U-005]: diverted wires drain cash reserves and hit payroll and production commitments.
- **Covenant breaches and debt acceleration** [U-004]: misappropriated project funds lead to overruns, valuation write-downs and covenant defaults.
- **Regulatory penalties and restatements** [U-003]: misstated user metrics or fraudulent reporting lead to SEC enforcement, fines and loss of investor confidence.
- **Baseline cross-reference** [S-009] [S-010]: acquiring and issuing banks can see payment-diversion and card-not-present fraud attempts after ticketing data exposures (Judgement).

### Q10.7 Rules and expectations

| Jurisdiction | Instrument | In-scope entities | Legal status | Provisions | Key dates | Source |
|---|---|---|---|---|---|---|
| UK | ECCTA 2023, section 199 (failure to prevent fraud) | Large bodies meeting size criteria (more than 250 staff, more than GBP 36m turnover, more than GBP 18m assets) | Binding legislation | Strict corporate liability for fraud by associated persons for the organisation's benefit; statutory defence of "reasonable procedures" | Enacted October 2023; guidance November 2024; in force 1 September 2025 | [U-004] [U-030]; see also [U-013] [U-014] [U-029] [U-031] [U-033] |
| EU | Whistleblower Protection Directive (EU) 2019/1937 | Private companies with more than 50 workers and public entities | Binding directive | Internal reporting channels, protection against retaliation, external reporting channels | Transposition deadlines December 2021 and December 2023 across Member States | [U-015] |
| US | Sarbanes-Oxley Act (SOX) sections 302 and 404 and SEC regulations | Publicly traded media and broadcasting corporations | Binding federal law | Internal control over financial reporting (ICFR); officer certification | In force since 2002; enforced through SEC actions | [U-012] |
| US (comparative, baseline) | SEC Form 8-K Item 1.05 | Registrants | Binding | Material cyber incident disclosure | From 18 December 2023 | [S-069] |

Payee-confirmation, reimbursement and sector-specific grant-fraud rules were not covered in either source set (gap).

### Q10.8 Emerging techniques

| Technique | Target subsectors | Enabling digital weakness | Deception step | Payment rail | Primary control defence | Source |
|---|---|---|---|---|---|---|
| AI deepfake executive audio | Broadcasting, publishing, production | No mandatory out-of-band call-back | Synthetic voice instructs finance staff to make an urgent payment | High-value wire | Strict out-of-band verbal authentication using pre-agreed secondary numbers | [U-004] |
| Vendor email compromise (VEC) | Film production, live events | Weak email authentication (no SPF, DKIM or DMARC) at subcontractors [U-005] | Attacker intercepts a legitimate email thread and alters bank-detail attachments | Commercial ACH and wire | Independent dual-control confirmation of bank-detail changes using physical documents or a known phone contact | [U-004] |
| Automated bot metric inflation | Digital media, streaming, gaming | Unauthenticated API endpoints; no anti-bot telemetry | Automated accounts simulate traffic to inflate advertising and investment valuations | Equity capital and advertising fee payouts | Independent third-party telemetry audits and cryptographic user authentication | [U-003] |

**Preliminary inherent fraud exposure:** High (Provisional), confidence Medium.

## Q11 - Sector ICT exposure and cybersecurity maturity

| Item | Finding | Evidence | Label |
|---|---|---|---|
| Digital dependency | Workflows are fully digitised; streaming, digital news and interactive gaming run 100% cloud-native distribution; broadcasting and film rely on bandwidth-heavy cloud rendering, digital asset management (DAM) repositories and fast file transfer; public institutions rely on digitised catalogues, archive databases and web ticketing | [U-010] [U-001] | User-supplied |
| Digital dependency (baseline) | Shared ticketing, cloud and CDN dependencies documented | [S-008] [S-038] [S-039] | Observed |
| Legacy systems in cultural heritage | Public cultural institutions often keep unsupported operating systems because of funding constraints, exposing networks to unpatched vulnerabilities | [U-001] | User-supplied |
| Infostealers and remote access | Remote editing and freelancers using personal devices expose credentials to infostealer malware, bypass MFA and grant access to cloud ERPs and asset storage | [U-010] | User-supplied |
| Extortion trends | Exfiltration with double extortion targets unreleased footage, game source code and subscriber databases | [U-002] | User-supplied |
| Live-output equipment | Default passwords and remote access on encoders and alerting devices; FCC baseline adopted June 2026 | [S-014] [S-013] | Observed |
| Public-facing attack surface | Media leads DDoS targeting (14.2% of mitigated HTTP DDoS requests, H1 2026); broadcast media faces hacktivist disruption | [S-042] [S-041] | Benchmark |
| Breach patterns | DBIR 2025: ransomware in 44% of breaches; stolen credentials in 22%; human error in 60% | [U-010] | User-supplied |
| Cyber-enabled fraud attack surface | Finance mailboxes and vendor email (BEC, VEC); ERP and banking account takeover | [U-004] [U-010] | User-supplied |
| Maturity evidence | No sector maturity survey; individual weaknesses: British Library domain controller without MFA [U-001]; Dresden detection lag (Judgement) [S-006]; Louvre underinvestment in information systems [S-037]; 35% of UK charities insured [S-044] | Mixed | Mixed |
| Recovery preparedness | Dresden website in 5 days, shop later [S-003]; British Library 18-month programme [U-001] and about 26 months to main catalogue [S-034]; broadcaster on air with physical media [S-026] | Mixed | Mixed |

**Analytical judgement.** Inherent ICT exposure is High: the sector combines universal digital dependency with legacy estates in public bodies and high-value content that supports extortion. Observed maturity is not measurable at sector level. Preliminary exposure: High (Provisional), confidence High.

## Q12 - Operational resilience and third-party concentration

### Q12.1 Documented disruptions

Baseline cyber or ICT disruptions: Dresden; shared ticketing provider; AWS US-EAST-1; Cloudflare; Leipzig municipal IT; RTV Noord (see Q02) [S-001, S-008, S-038, S-039, S-028, S-025]. User input: British Library (Q02 case study 2) [U-001, U-002].

### Q12.2 Essential operational functions (as supplied)

1. CDNs and cloud infrastructure: video streaming, digital publishing and games storefronts depend on global cloud service providers (AWS, Azure, GCP) and CDNs to serve high-volume traffic [U-010].
2. Ticketing and access-control platforms: venues and heritage sites depend on cloud-hosted ticketing portals for admissions and revenue intake [U-001].
3. Proprietary rights management and post-production SaaS: studios and broadcasters rely on specialised cloud software for scheduling, royalty calculation and remote editing [U-004].

### Q12.3 Dependency and concentration matrix

| Vendor category | Primary concentration risk | Operational impact of failure | Substitutability and switching complexity | Source |
|---|---|---|---|---|
| Cloud service providers (CSPs) | High concentration in AWS, Azure, Google Cloud [U-011] | Total blackout of streaming platforms, digital archives and publishing portals [U-002] | Very high complexity; multi-month migration [U-002] | User-supplied; baseline AWS event [S-038] |
| Content delivery networks | High concentration in Cloudflare, Fastly, Akamai | Inability to deliver video streams or serve news sites; immediate revenue loss | Medium; fallback routing possible if pre-configured | User-supplied (no reference given); baseline Cloudflare event [S-039] |
| Ticketing platforms | Market concentration in major ticketing platforms | Complete halt to ticket sales, venue access disruption, customer backlash [U-001] | High complexity during active sales cycles | User-supplied; baseline Vivaticket pattern [S-008] |
| Visual effects (VFX) and post-production SaaS | Specialised proprietary software vendors | Production delays, missed release dates, contractual penalties | High; proprietary file formats and specialised workflows | User-supplied (no reference given) |
| Analytics and SaaS integrations | Integration tokens shared across customers | Cloud data access at many customers | Not evidenced | Baseline [S-021] (Tier 3) |
| Broadcast content-insertion and satellite paths | Remote access and uplink paths | Hijacked live output | Not evidenced | Baseline [S-014] [S-018] |
| Municipal shared IT | One provider for several cultural bodies | Concurrent outage | Not evidenced | Baseline [S-028] (Tier 3) |

The baseline records that market shares of ticketing, playout and collection-management providers are not public [S-008]; the user input's concentration statements for CDNs and VFX carry no reference.

### Q12.4 Disruption durations and losses

| Indicator | Value | Source type |
|---|---|---|
| AWS US-EAST-1 regional disruption | About 14 hours 32 minutes (October 2025) | Provider post-event summary [S-038] |
| Cloudflare global outage | About 6 hours (18 November 2025) | Provider report [S-039] |
| Shared ticketing, time to reopen online sales | 10 days (CMN); BnF still unable on 19 March (17 days, derived) | Tier 3 relays [S-010] [S-009] |
| Dresden online booking | 30 days or fewer | Tier 3 [S-005] |
| British Library | 18-month renewal programme [U-001]; about 26 months to main catalogue [S-034] | User-supplied; Tier 1 derived |
| Third-party share of breaches | 30% (DBIR 2025) | User-supplied [U-010] |

Quantified losses for mid-tier live-event hosting disruptions and private SaaS outages are not available; they are mostly settled privately [U-001] [U-005].

### Q12.5 Continuity and propagation

- Limiting conditions documented: [S-007] alternative ticket offices and on-site sales; [S-026] physical media for radio (Tier 3); [S-001] segregated security system; [S-038] [S-039] restoration within a day for provider failures.
- Propagation: one ticketing provider to about a hundred monuments and many museums [S-008] [S-010]; one region or CDN to many services [S-038] [S-039]; one integration provider to at least a dozen companies [S-021].
- Fraud through third parties: VEC through compromised subcontractor email [U-004]; fraudulent licensing agents intercepting distribution fees [U-004]; sub-distributor under-reporting [U-004].

**Preliminary exposure:** High (Provisional), confidence High.

## Q13 - Governance structure and operating-model complexity

**Operating models (as supplied).**
- **Listed media conglomerates:** multi-tier holding structures with subsidiaries across jurisdictions, established governance frameworks and complex legacy reporting systems [U-013].
- **Independent production SPEs:** project-specific entities for single film or TV productions with brief lifespans, small administrative teams and highly delegated payment authority, creating structural control gaps [U-004].
- **Non-profit cultural bodies:** museums and performing-arts organisations governed by municipal boards or charitable trusts, with slow IT investment cycles and limited in-house security oversight [U-001].

**Governance failures and control deficits.**

| Governance category | Observed structural weakness | Impact on fraud and operational risk | Reference case |
|---|---|---|---|
| Board oversight of IT and cyber risk | Cyber treated as an IT issue rather than an enterprise risk [U-001] | Failure to allocate capital for legacy modernisation [U-001] | British Library incident review [U-001] |
| Intermediary oversight | Limited due diligence on overseas sales agents and sub-distributors [U-004] | High corporate liability under ECCTA section 199 [U-004] | Home Office ECCTA guidance [U-004] [U-031] |
| Auditor independence | Selection of low-cost audit providers without rigorous quality control [U-017] | Undetected financial statement manipulation and asset misstatement [U-012] | SEC v. BF Borgers CPA PC [U-017] |
| Board oversight of financial reporting | No independent board oversight; management override [U-012] | Offering fraud through false revenue and contracts | SEC v. Icaro Media Group [U-012] |
| Public-body IT governance (baseline) | [S-037] Louvre allocated EUR 26.7m to maintenance and compliance against EUR 105.4m to acquisitions; recommended an information systems and digital directorate by end-2026 | Underinvestment in information systems | Cour des comptes (context, not cyber-specific) |
| Arm's-length accountability (baseline) | [S-068] UK Government Cyber Action Plan makes arm's-length bodies accountable to lead departments | DCMS-sponsored museums and libraries | Government plan, 6 January 2026 |
| Audit follow-up (baseline) | [S-036] Toronto Public Library cybersecurity audit after its 2023 attack; findings confidential | Implementation cost not determinable | Toronto Auditor General, May 2026 |

**Management accountability rules.** ECCTA section 199 [U-004]; SOX sections 302 and 404 [U-012]; EU Whistleblower Protection Directive [U-015]; SEC Form 8-K Item 1.05 [S-069]; NIS2 management-body accountability only where an entity is in scope [S-048].

**Analytical judgement.** Complexity is concentrated in SPE networks, fragmented IP ownership and intermediary chains, while large listed groups operate under established governance norms. Documented governance failures are US enforcement cases; EU and UK evidence is limited to public-body audit findings. Complexity is not treated as evidence of weak governance. Preliminary exposure: Medium (Provisional), confidence Medium.

## Q14 - Cross-sector comparative analysis

**User-supplied comparison (not validated).**

| Metric | Media & Cultural Services | Financial Services | Healthcare | Retail / Consumer | Manufacturing | Comparative source (as cited) |
|---|---|---|---|---|---|---|
| Inherent cyber exposure | High (public web exposure, IP target) [U-001] | High (financial assets; tightly regulated) [U-025] | High (PHI target; operational safety impact) [U-025] | Medium-High (card and customer data) [U-025] | Medium-High (OT/ICS disruption) [U-025] | Verizon DBIR 2025; IBM Cost of a Data Breach 2025 [U-010] |
| Third-party breach share | 30% (software and cloud reliance) [U-010] | 25% (audited vendor management) | 35% (medical device and SaaS density) | 28% (e-commerce supply chain) | 32% (supplier network integration) | Verizon DBIR 2025 [U-010] |
| Occupational fraud median loss | USD 104,000 (ACFE 2026 global) [U-015] | USD 200,000 (higher-value flows) [U-022] | USD 150,000 [U-009] | USD 120,000 [U-009] | USD 150,000 [U-009] | ACFE Report to the Nations 2024 / 2026 [U-015] |
| Ransomware involvement in breaches | 44% [U-010] | 22% (advanced endpoint detection) | 38% [U-025] | 35% [U-025] | 48% (operational leverage) [U-025] | Verizon DBIR 2025 [U-010] |

**Comparability notes (Judgement, not validation).** The Media column for fraud uses the ACFE 2026 all-industry global median, while the peer columns use industry figures attributed to the 2024 and 2026 editions; the row therefore does not show Media below peers on a like-for-like basis. Several peer cells carry no reference in the input. Percentages come from breach datasets with different scopes and are not combined with fraud figures.

**Baseline comparators.**

| Dimension | Comparator | Dataset type | Media position | Limitation |
|---|---|---|---|---|
| Cyber / ICT | [S-042] Share of mitigated HTTP DDoS requests by industry, H1 2026 | One provider network | First, 14.2%, nearly four times the next industry | Targeting, not impact |
| Cyber / ICT | [S-041] ENISA EU incident analysis 2025 | Institutional analysis | Broadcast media within the 55.3% share of business-services events | Grouped category |
| Cyber / ICT | [S-044] UK breaches or attacks in the year | Official survey | Information and communication 63%; charities 28% | Survey, self-reported |
| Fraud | No sector-cut law-enforcement complaint data | - | Not assessable comparatively | [U-005] gap |
| Governance | No comparable complexity indicator | - | Not assessable comparatively | Gap |

No 24-sector comparison universe is available; ratings are not calibrated against peer sectors (gap).

---

# Part C - Synthesis

## Q15 - Four-dimension classification (detail)

### Fraud - High (Provisional), confidence Medium
- **Drivers:** (1) payment intensity and project velocity [U-004]; (2) supplier onboarding churn [U-004]; (3) intermediaries and distribution agents with opaque reporting [U-004]; (4) public funding and tax-credit reliance [U-004]; (5) decentralised SPE disbursement authority [U-004]; (6) customer-facing ticketing and subscription flows [U-005, S-009].
- **Strongest evidence:** US v. Brown (USD 12m, no dual signatories on SPE accounts) [U-008]; SEC v. IRL (USD 170m) [U-003]; SEC v. Icaro [U-012]; SEC v. BF Borgers (USD 14m penalty) [U-017].
- **Cyber / non-cyber split:** cyber-enabled and hybrid (BEC, VEC, deepfake executive audio, account takeover, payment diversion) and non-cyber (embezzlement, financial statement fraud, grant and tax-credit fraud, royalty under-reporting, corruption) are both material.
- **Datasets:** ACFE 2026 global median USD 104,000 (investigated cases) [U-015]; FBI IC3 2025 BEC USD 3.05 billion (complaints, all sectors) [U-005].
- **Consequences:** working-capital depletion, covenant breaches, restatements, ECCTA exposure [U-004, U-005, U-003].
- **Limitations:** no EU or UK sector case; no sector-cut complaint data; private SPE losses rarely disclosed; confidence held at Medium.

### Cyber / ICT - High (Provisional), confidence High
- **Drivers:** universal digital dependency [U-010]; legacy estates in public bodies [U-001]; infostealer and remote-access exposure [U-010]; double extortion over unreleased content [U-002]; live-output equipment weaknesses [S-014]; leading DDoS targeting [S-042].
- **Consequences:** multi-month to multi-year recovery [U-001, S-034]; lost online sales for days to weeks [S-003, S-010]; revenue and credit effects [S-030, S-031, S-032].
- **Cross-sector:** ransomware in 44% of breaches against 22% to 48% for peers (user-supplied) [U-010, U-025].
- **Limitations:** no sector maturity survey; no breakout for unlisted firms [U-001].

### Operational resilience / TPRM - High (Provisional), confidence High
- **Drivers:** concentration in cloud, CDN and ticketing providers [U-011, U-001, S-008]; low substitutability for cloud and VFX software [U-002]; rights-management and post-production SaaS [U-004].
- **Consequences:** halted sales and delivery, refunds, contractual penalties [U-001]; correlated outages across many counterparties [S-038, S-039].
- **Limitations:** no quantified mid-tier live-event losses; supplier market shares not public; several concentration statements carry no reference.

### Governance / operating model - Medium (Provisional), confidence Medium
- **Drivers:** SPE networks [U-004]; fragmented IP ownership and intermediaries [U-008]; non-profit board structures with slow IT investment [U-001]; auditor quality [U-017].
- **Offsets:** established governance norms at large listed groups [U-013]; SOX and SEC disclosure duties [U-012, S-069].
- **Limitations:** no internal-audit coverage data for non-listed mid-market producers [U-001]; no cross-sector governance benchmark.

**Rating sensitivity triggers (as supplied).**
- Fraud would move from Provisional High to Provisional Medium if a borrower demonstrated automated, dual-signatory bank-detail confirmation and independent audit oversight across all operating SPEs [U-004].
- Cyber / ICT would move from Provisional High to Provisional Medium if a borrower documented 100% MFA coverage across access endpoints, network segmentation isolating core digital assets and no legacy operating systems [U-001].
- These triggers concern a borrower-level view; sector inherent ratings would change only with sector evidence, for example a sector maturity survey, normalised incident rates, documented fast substitutability of providers or EU and UK enforcement findings (Judgement).

## Q08 - Questionnaire mapping and Credit Officer engagement (Provisional)

No questionnaire item list was supplied; identifiers use the PROV- prefix and are placeholders, not questionnaire items. Borrower answers are self-reported, are not confirmed evidence and never trigger an automatic adverse credit judgement.

| PROV ID and topic | Threat and evidence | Operational -> credit consequence | Suggested client questions | Materiality factors |
|---|---|---|---|---|
| PROV-01 Shared suppliers | P2; ticketing outage 2026 (Tier 3) and 2025 cloud and CDN outages [S-008, S-038, S-039]; CSP, CDN and ticketing concentration [U-002, U-011] | Sales and delivery stop -> correlated revenue loss | Which ticketing, payment, cloud and delivery providers do you share with peers? What are your tested RTOs for cloud, CDN and DAM dependencies? | Share of online and live-event revenue |
| PROV-02 Live-output equipment | P3; regulator-recorded and satellite hijacks [S-014, S-018] | Hijacked output -> regulatory scrutiny | Do insertion and alerting devices meet a password, patch and segmentation baseline? | Broadcast licence dependence |
| PROV-03 Segregation and recovery | P1; Dresden 2026 [S-001]; British Library legacy domain controller without MFA [U-001] | Shop and card payment down -> weeks of lost online sales | Are security, building and playout systems separate from corporate IT? Is MFA enforced on privileged accounts and are legacy systems retired? | Legacy estate share |
| PROV-04 Customer data and fraud | P6; live-events notice [S-086]; ticketing exposure [S-009]; customer-facing fraud [U-005] | Notification -> litigation and fraud losses | How are ticket-holder and subscriber data exposures monitored, and how are chargebacks managed? | Customer data volume |
| PROV-05 Brand provenance | P4; EEAS impersonation findings [S-043]; deepfake executive audio [U-004] | Impersonation -> brand integrity and payment loss | How do you detect impersonation and meet AI Act transparency duties? | News and publishing share |
| PROV-06 Recovery and funding | P1; Lee waivers [S-031]; British Library [S-034, U-011] | Long recovery -> waivers, funding draw | What recovery time, insurance and waiver triggers apply? | Leverage; public funding |
| PROV-07 Payment-detail change control | BEC, VEC and payment diversion [U-004]; US v. Brown [U-008] | Diverted payments -> cash loss | What dual-authorisation controls apply to bank-detail changes across vendor, project and royalty payments? | Payment volume; vendor churn |
| PROV-08 Intermediary and agent oversight | ECCTA section 199 associated-person liability [U-004, U-031]; sub-distributor under-reporting [U-004] | Failure-to-prevent liability; royalty loss | How are sales agents, sub-distributors and licensing brokers selected, monitored and audited? | UK nexus and size criteria; agent-dependent revenue |
| PROV-09 SPE governance and fund segregation | Decentralised SPE disbursement authority [U-004]; US v. Brown [U-008] | Misappropriation -> overruns and covenant default | Are investor and production funds segregated and are SPE accounts under dual signatories and parent oversight? | Number of active SPEs; production budgets |
| PROV-10 Reported metrics, grants and royalties | SEC v. IRL, Icaro, BF Borgers [U-003, U-012, U-017]; grant and tax-credit fraud [U-004]; box-office and royalty under-reporting [U-006] | Restatement, penalties, clawback -> debt acceleration | Are user metrics, royalty statements and grant claims independently audited? Who is the external auditor? | Listed or quoted equity; grant reliance |

**Early-warning indicators.** Supplier incident notices or prosecutor statements naming a ticketing, playout, newsroom or collection-management provider; regulator warnings on content-insertion devices; DDoS or FIMI alerts before elections or live events; waiver, amendment or liquidity requests after an incident; SEC or prosecutor actions against sector issuers or auditors; ECCTA prosecutions or deferred prosecution agreements; legal milestones (UK bill Royal Assent; AI Act Article 50(2) on 2 December 2026; FCC compliance date; first CRA reporting statistics) [S-008, S-014, S-042, S-043, S-031, S-061, S-053, S-055, U-004, U-017].

**Specialist referral triggers (Judgement).** Reliance on one ticketing or delivery provider without a tested fallback; legacy systems or privileged access without MFA; no dual authorisation of bank-detail changes; SPE accounts without dual signatories; reliance on unaudited user metrics; a disruption of one to four weeks that would cross a covenant or contractual milestone.

## Q09 - Final synthesis

**Sector narrative.** Media & Cultural Services combines fully digital production and distribution with public-facing platforms, legacy estates in publicly funded bodies and project structures with delegated payment authority. Cyber disruption in the baseline period ran mainly through shared front-of-house platforms and live-output equipment, with financial effects arriving through revenue lines, lender waivers and long recovery tails. The user input adds a fraud and governance layer: payment diversion and impersonation in high-velocity production and touring, misappropriation in SPEs, financial-statement and metric fraud at listed or quoted media issuers, and new UK corporate liability for fraud by intermediaries.

**Credit relevance.** Inherent exposure is High on Fraud, Cyber / ICT and Operational resilience and Medium on Governance, all Provisional. Borrower materiality depends on online and live-event revenue share, reliance on shared ticketing, cloud and CDN providers, legacy estate and recovery capability, SPE and intermediary controls, leverage and insurance, and public-funding dependence.

**Product scope of this update.** Research record only; no slide deck, report re-issue or evidence annex was produced, at the user's request.

---

## F. Gaps, limitations and NEEDS_REVIEW items

1. **User-supplied information not validated** (U-001 to U-033), at the user's instruction. Many U- references are secondary commentary on primary documents (for example law-firm notes on ECCTA, vendor blogs on the DBIR and ACFE reports); material figures should be confirmed against the primary reports before external use (analyst note; no content changed). Sample sizes for the ACFE and IC3 datasets are blank in the input.
2. **Fraud:** all documented cases are US; no EU or UK sector fraud case; no subsector-specific complaint totals in law-enforcement datasets, which aggregate media, entertainment and information [U-005]; private SPE fraud losses rarely disclosed unless indicted [U-004].
3. **Operational resilience:** losses from localised SaaS vendor outages are mostly settled privately [U-005]; no quantified mid-tier live-event losses; CDN and VFX concentration statements in the input carry no reference; supplier market shares not public.
4. **Governance:** no internal-audit coverage data for non-listed mid-market production entities [U-001]; no cross-sector governance indicator.
5. **Cross-sector comparison (Q14):** peer-sector figures in the input mix editions and lack references in several cells; no 24-sector universe; ratings uncalibrated.
6. **Q07 geopolitical:** fragments only; no dedicated analysis; the user input adds none.
7. **30-day windows:** nothing after 15 October 2026 was researched for Q01-Q07; the user input reports no named event in 28 September to 27 October 2026.
8. **EU and UK incidents:** no EU or UK broadcaster incident with a retrievable Tier 1 statement; shared ticketing detail rests on Tier 3 relays; Dresden cost and attribution undisclosed.
9. **Regulation partly reviewed (baseline):** Media Act 2024, Australian SOCI Act, UK telecoms security scope and the Digital Omnibus on AI; not reviewed in primary text: AVMSD, Ofcom licence conditions, national GDPR Article 85 laws, national NIS2 transpositions and US state rules. ECCTA, SOX and the Whistleblower Directive rows rest on the user input.
10. **No approved rubric or questionnaire:** ratings and mapping are Provisional.
11. **Search strategy of the user input (as supplied):** US federal court dockets, DOJ and SEC press releases, UK Home Office and UK Finance guidance and published post-incident reviews (British Library) [U-002].

---
## G. Source list

### G1. Public sources from the baseline edition (accessed 15 October 2026)

Titles are given by their citation label; full original titles, methodology, limitations and relevance notes are held in the baseline source register (`02_source_register.csv`).

| ID | Source (citation label) | Publisher | Published (basis) | Tier | Temporal class | Locator | URL |
|---|---|---|---|---|---|---|---|
| S-001 | Saxon culture ministry - SKD cyberattack release, 22 January 2026 | Saxon State Ministry for Culture and Tourism (Medienservice Sachsen) on behalf of SKD | 2026-01-22 (exact) | 1 | current | Press release body (PDF): incident, affected services, unaffected security network, investigation, crisis team | https://www.medienservice.sachsen.de/medien/news/1094410/download_pdf |
| S-002 | SKD - Cyberattack press release | Staatliche Kunstsammlungen Dresden (SKD) | 2026-01-22 (exact) | 1 | current | Press release dated 22 January 2026, 13:03; sections on affected and unaffected systems | https://www.skd.museum/en/besucherservice/presse/2026/cyberattack-on-the-dresden-state-art-collections/ |
| S-003 | SKD - Recovery update, 29 January 2026 | Staatliche Kunstsammlungen Dresden via Medienservice Sachsen | 2026-01-29 (exact) | 1 | current | Release of 29 January 2026, 13:04: website since 26 January, telephone, online shop, cash payment, investigation | https://www.medienservice.sachsen.de/medien/news/1094571 |
| S-004 | Prosecutor and LKA Saxony - SKD investigation release | Generalstaatsanwaltschaft Dresden and Landeskriminalamt Sachsen (joint release) | 2026-02-19 (exact) | 1 | current | Release body: special investigation commission set up by LKA under prosecutor direction | https://medienservice.sachsen.de/medien/news/1095116/download_pdf |
| S-005 | t-online - SKD special commission report | t-online (Dresden regional edition) | 2026-02-20 (exact) | 3 | current | Article body: online ticket booking restored; Bild report on planned theft; LKA response | https://dresden.t-online.de/region/dresden/id_101137618/dresden-zwinger-raub-geplant-was-ueber-die-arbeit-der-skd-soko-bekannt-ist.html |
| S-006 | dpa via Volksstimme - SKD attack duration | Volksstimme (dpa wire) | 2026-07-28 (exact) | 3 | current | Article body citing the Saxon Justice Ministry answer to a Kleine Anfrage by MP Rico Gebhardt | https://www.volksstimme.de/panorama/cyberangriff-auf-skd-dauerte-mehrere-tage-4292567 |
| S-007 | Musee Guimet - Online ticketing unavailable notice | Musee national des arts asiatiques - Guimet | undated (undated) | 1 | contextual | Notice body: online reservations unavailable; FNAC ticket office and on-site purchase | https://www.guimet.fr/en/museum-online-ticketing-service-unavailable |
| S-008 | CMN - Ticketing personal data notice | Centre des monuments nationaux (official ticketing site) | undated (undated) | 1 | contextual | Section naming the ticketing provider (Vivaticket S.p.A.) as host and transmitter of ticketing data | https://tickets.monuments-nationaux.fr/fr-FR/donnees-personnelles |
| S-009 | ActuaLitte - Vivaticket attack on cultural institutions | ActuaLitte | 2026-03-19 (exact) | 3 | current | Article body: affected institutions, CMN reopening 12 March, notifications, prosecutor investigation | https://actualitte.com/article/130017/usages-numeriques/cyberattaque-des-musees-et-institutions-culturelles-perturbes-dont-la-bnf |
| S-010 | L'Echo touristique - CMN ticketing cyberattack | L'Echo touristique | 2026-03-08 (exact) | 3 | current | Article body quoting the CMN customer email: ransomware at ticketing provider on 2 March 2026; data categories | https://www.lechotouristique.com/article/billetterie-les-monuments-nationaux-victimes-dune-cyberattaque |
| S-011 | Lyon Mag - Lyon municipal museums ticketing attack | Lyon Mag | 2026-03-11 (exact) | 3 | current | Article body: four municipal museums without online ticketing; data categories; city statement | https://www.lyonmag.com/article/150751/la-billetterie-des-musees-municipaux-de-lyon-victime-d-une-cyber-attaque |
| S-012 | SC Media - Vivaticket platform breach brief | SC Media | 2026-04-06 (exact) | 3 | current | Brief body: nearly 3,500 sites; Irec SAS subsidiary; RansomHouse claim; Vivaticket statement on card data | https://www.scworld.com/brief/thousands-of-european-tourist-sites-impacted-by-ticketing-platform-breach |
| S-013 | Radio Ink - FCC warning after Houston hijack | Radio Ink | 2025-12-02 (exact) | 3 | H2_prior | Article body: KFNC hijack during NFL coverage; station investigation; FCC bureau warning and recommended measures | https://radioink.com/2025/12/02/fcc-issues-cybersecurity-warning-after-houston-barix-hack/ |
| S-014 | FCC - FCC 26-38 alerting systems order | US Federal Communications Commission | 2026-06-29 (exact) | 1 | current | Report and Order para 16 and n.61 (recent hijack incidents incl. Houston, 23 November 2025); adopted requirements (passwords, patching, segmentation); compliance timing; no incident-reporting requirement | https://docs.fcc.gov/public/attachments/FCC-26-38A1.pdf |
| S-015 | SDNY - Anna's Archive preliminary injunction | US District Court, Southern District of New York (via CourtListener RECAP) | 2026-01-20 (exact) | 1 | current | Preliminary Injunction: findings on likely infringement by scraping, irreparable harm, worldwide injunction, third-party compliance | https://storage.courtlistener.com/recap/gov.uscourts.nysd.655608/gov.uscourts.nysd.655608.17.0.pdf |
| S-016 | Music Business Worldwide - Anna's Archive lawsuit | Music Business Worldwide | 2026-01-21 (exact) | 3 | current | Article body: claims, alleged scale, Spotify statement, relief sought | https://www.musicbusinessworldwide.com/record-labels-spotify-sue-pirate-group-annas-archive-over-scraping-and-brazen-theft-of-86m-tracks |
| S-017 | MusicTech - Anna's Archive judgment | MusicTech | 2026-04-23 (exact) | 3 | current | Article body: judgment amount, date, distribution, collectability | https://musictech.com/news/industry/judge-orders-annas-archive-to-pay-322-million/ |
| S-018 | Geo News - Satellite feed hijack statement | Geo News (Jang Media Group) | 2026-03-01 (exact) | 1 | current | Statement body: repeated attempts over 24 hours; satellite feed hacked at 9 pm bulletin; request for investigation | https://www.geo.tv/latest/653574-geo-news-says-aired-message-after-hack-not-linked-to-channel |
| S-019 | Dawn - CERT investigation of TV channel hacks | Dawn | 2026-03-03 (exact) | 3 | current | Article body: National CERT formal investigation; uplink hypothesis; platforms restored | https://www.dawn.com/news/1977705 |
| S-020 | Digital Rights Monitor - Pakistani channel takeovers | Digital Rights Monitor | 2026-03-02 (exact) | 3 | current | Article body: Geo News, Samaa TV and ARY News; no regulator statement; no claim of responsibility | https://digitalrightsmonitor.pk/several-pakistani-tv-channels-briefly-taken-over-by-unauthorised-broadcasts/ |
| S-021 | TechCrunch - Anodot integration breach | TechCrunch | 2026-04-13 (exact) | 3 | current | Article body: stolen integration tokens, at least a dozen companies, Rockstar Games statement | https://techcrunch.com/2026/04/13/hack-at-anodot-leaves-over-a-dozen-breached-companies-facing-extortion/ |
| S-022 | Hasbro - Form 8-K, 1 April 2026 | Hasbro, Inc. (SEC EDGAR) | 2026-04-01 (exact) | 1 | current | Item 8.01: unauthorized network access identified 28 March 2026; systems offline; interim measures for several weeks | https://www.sec.gov/Archives/edgar/data/46080/000004608026000013/has-20260401.htm |
| S-023 | Hasbro - Q1 2026 results release | Hasbro, Inc. (SEC EDGAR) | 2026-05-20 (exact) | 1 | current | Release text on the IT incident: containment, legal and remediation costs from Q2, insurance claims | https://www.sec.gov/Archives/edgar/data/0000046080/000004608026000029/exhibit991q12026.htm |
| S-024 | BleepingComputer - SoundCloud breach | BleepingComputer | 2025-12-15 (exact) | 3 | H2_prior | Article body: SoundCloud statement on ancillary dashboard access, data types, DoS, VPN disruption | https://bleepingcomputer.com/news/security/soundcloud-confirms-breach-after-member-data-stolen-vpn-access-disrupted |
| S-025 | NOS - RTV Noord hack | NOS | 2025-11-14 (exact) | 3 | H2_prior | Article body: employee data stolen; untargeted ransomware; ransom refused; radio continuity | https://nos.nl/artikel/2590462-privegegevens-gestolen-bij-hack-rtv-noord-was-geen-gerichte-aanval |
| S-026 | NL Times - RTV Noord broadcast disruption | NL Times (ANP) | 2025-11-07 (exact) | 3 | H2_prior | Article body: discovery before morning broadcast; radio on CDs and vinyl; website and app workaround; TV normal | https://nltimes.nl/node/84401 |
| S-027 | Artribune - Uffizi incident claims and response | Artribune | 2026-04-03 (exact) | 3 | current | Article body separating Corriere claims from the director's statements; ACN investigation | https://www.artribune.com/professioni-e-professionisti/politica-e-pubblica-amministrazione/2026/04/uffizi-attacco-hacker-scoop-risposta-direttore-verde/ |
| S-028 | t-online - Leipzig cultural enterprises attack | t-online (Leipzig regional edition, dpa) | 2026-07-20 (exact) | 3 | current | Article body: municipal IT provider Lecos; Gewandhaus, Opera, Schauspiel, music school; directory data taken | https://leipzig.t-online.de/region/leipzig/id_101351990/cyberangriff-trifft-staedtische-kulturbetriebe-in-leipzig.html |
| S-029 | Quotenmeter - Cyberattacks on journalism | Quotenmeter | 2026-09-10 (exact) | 3 | current | Article body: Mediengruppe Presse Nord overload attack end of August 2026; editor statement | https://www.quotenmeter.de/n/175372/die-neue-druckmaschine-steht-im-rechenzentrum-wenn-cyberangriffe-den-journalismus-treffen |
| S-030 | Lee Enterprises - FY2025 Form 10-K | Lee Enterprises, Inc. (SEC EDGAR) | 2025-11-26 (exact) | 1 | H2_prior | Item 1A Risk Factors; Item 1C Cybersecurity (Material Effects); Item 7 Executive Overview, Operating Revenue, Operating Activities and Liquidity | https://www.sec.gov/Archives/edgar/data/58361/000005836125000040/lee-20250928.htm |
| S-031 | Lee Enterprises - Q3 FY2026 Form 10-Q | Lee Enterprises, Inc. (SEC EDGAR) | 2026 (year_only) | 1 | current | Note 8 Debt (waivers); Consolidated Statements of Income (insurance proceeds) | https://www.sec.gov/Archives/edgar/data/0000058361/000005836126000060/lee-20260628.htm |
| S-032 | KADOKAWA - FY2025/3 results release | KADOKAWA CORPORATION | 2025-05 (month_only) | 1 | H1_prior | Release text on cyberattack effects: group sales and operating profit, special loss, Web Services and domestic print publishing | https://www.kadokawa.co.jp/topics/13832/ |
| S-033 | British Library - Annual Report 2024/25 | British Library (via GOV.UK) | 2025-07-15 (exact) | 1 | H2_prior | pp. 4, 9, 13, 32-39 (recovery, Rebuild and Renew, DCMS support, income effects) | https://assets.publishing.service.gov.uk/media/68778282760bf6cedaf5bcda/WEB_ACCESSIBLE_British_Library_Annual_Report_and_Accounts_FY_2024_25.pdf |
| S-034 | British Library - Annual Report 2025/26 | British Library (HC 328, via GOV.UK) | 2026-07-14 (exact) | 1 | current | pp. 4, 7, 11, 32-39 (catalogue, Library Services Platform, legal deposit, UK Web Archive, KPIs) | https://assets.publishing.service.gov.uk/media/6a57634e6d6d5c7e2845c9c0/British_Library_Annual_Report_and_Accounts_2025-26_WEB_NAO_14_July_v2.pdf |
| S-035 | Museums Association - British Library recovery | Museums Association | 2026-09-22 (exact) | 3 | current | Article body: catalogues still unavailable to the public | https://www.museumsassociation.org/museums-journal/news/2026/09/new-leadership-for-british-library-as-cyber-attack-recovery-continues/ |
| S-036 | Toronto Auditor General - Toronto Public Library audit | Toronto Auditor General | 2026-05-15 (exact) | 1 | current | pp. 1-4: scope, confidential attachment, cost not determinable | https://www.torontoauditor.ca/wp-content/uploads/2026/05/Cybersecurity-Audit-of-Toronto-Public-Library-CVR-May-15-2026.pdf |
| S-037 | Cour des comptes - Louvre public establishment summary | Cour des comptes (France) | 2025-11 (month_only) | 1 | H2_prior | Summary pp. 4-5 (maintenance and security underinvestment), p. 9 recommendations 9 and 10 | https://www.ccomptes.fr/sites/default/files/2025-12/20251106-summary-The-public-establishment-of-the-Louvre-Museum.pdf |
| S-038 | AWS - US-EAST-1 post-event summary | Amazon Web Services | 2025-10 (month_only) | 1 | H2_prior | Summary body: root cause, timeline, affected AWS services, remediation | https://aws.amazon.com/message/101925/ |
| S-039 | Cloudflare - 18 November 2025 outage report | Cloudflare | 2025-11-18 (exact) | 1 | H2_prior | Post body: root cause, UTC timeline, affected services, statement that no attack was involved | https://blog.cloudflare.com/18-november-2025-outage/ |
| S-040 | PPC Land - AWS outage effects | PPC Land | 2025-10 (month_only) | 3 | H2_prior | Article body: gaming services reported affected; company acknowledgements | https://ppc.land/amazon-outage-breaks-the-internet-snapchat-fortnite-banks-go-dark/ |
| S-041 | ENISA - Threat Landscape 2026 | European Union Agency for Cybersecurity (ENISA) | 2026-09 (month_only) | 1 | current | p. 9 (method, 8,257 incidents); p. 14 (top sectors, FIMI-aligned hacktivism); pp. 25-26 (business services, broadcast media, hacktivist claims) | https://www.enisa.europa.eu/sites/default/files/2026-09/ENISA%20Threat%20Landscape%202026_Final.pdf |
| S-042 | Cloudflare - DDoS Threat Report H1 2026 | Cloudflare (Cloudforce One) | 2026-08-11 (exact) | 2 | current | Sections 'Most-attacked industries' and 'Media under siege: the most attacked industry' | https://blog.cloudflare.com/ddos-threat-report-2026-h1/ |
| S-043 | EEAS - 4th FIMI Threats Report | European External Action Service (EEAS) | 2026-03-12 (exact) | 1 | current | pp. 7, 10 (540 incidents), 11 (targets incl. media sector), 15 (elections), 29-31 (impersonation of outlets) | https://www.eeas.europa.eu/sites/default/files/2026/documents/EEAS%204th%20Threat%20Report_web.pdf |
| S-044 | DSIT - Cyber Security Breaches Survey 2025/26 | Department for Science, Innovation and Technology and Home Office (GOV.UK) | 2026-04-30 (exact) | 1 | current | Summary and sector findings: prevalence for businesses, charities and information and communication sector; charity governance and insurance | https://www.gov.uk/government/statistics/cyber-security-breaches-survey-20252026/cyber-security-breaches-survey-20252026 |
| S-045 | Eurostat - EU cultural employment 2025 | Eurostat | 2026-07-10 (exact) | 1 | current | News body: employment count, share and definition | https://ec.europa.eu/eurostat/en/web/products-eurostat-news/w/ddn-20260710-2 |
| S-046 | DCMS - Sectors GVA 2024 (provisional) | Department for Culture, Media and Sport (GOV.UK) | 2026-02-05 (exact) | 1 | current | Headline GVA for creative industries and cultural sector; overlap note | https://www.gov.uk/government/statistics/dcms-economic-estimates-gva-2024-provisional/dcms-sectors-economic-estimates-gross-value-added-2024-provisional |
| S-047 | Europol - Operation Eastwood | Europol | 2025-07 (month_only) | 1 | H2_prior | Press release body and metadata: Operation Eastwood, infrastructure disruption, arrest warrants | https://www.europol.europa.eu/media-press/newsroom/news/global-operation-targets-noname05716-pro-russian-cybercrime-network |
| S-048 | EUR-Lex - NIS2 Directive | EUR-Lex (Official Journal of the EU) | 2022-12-27 (exact) | 1 | contextual | ELI metadata: document date 14 December 2022, publication 27 December 2022, entry into force 16 January 2023 | https://eur-lex.europa.eu/eli/dir/2022/2555/oj/eng |
| S-049 | European Commission - NIS2 FAQs | European Commission (Shaping Europe's digital future) | undated (undated) | 1 | contextual | FAQs 'Which sectors and types of entities will the NIS2 cover?', 'What are the key elements of the NIS2 Directive?', jurisdiction FAQ | https://digital-strategy.ec.europa.eu/en/faqs/directive-measures-high-common-level-cybersecurity-across-union-nis2-directive-faqs |
| S-050 | European Commission - Entity resilience policy page | European Commission (DG Migration and Home Affairs) | 2026-01-13 (page_update) | 1 | current | Sections on the CER Directive: eleven sectors; key dates including 17 July 2026 identification | home-affairs.ec.europa.eu - full URL in the baseline source register (path contains a term excluded by the editorial rules) |
| S-051 | European Commission - European Media Freedom Act page | European Commission | undated (undated) | 1 | contextual | Page body: entry into force, application of most provisions on 8 August 2025, protection of journalistic sources against intrusive surveillance software | https://commission.europa.eu/topics/democracy/eu-actions-protect-democracy/european-media-freedom-act_en |
| S-052 | European Commission - Political advertising rules apply | European Commission | 2025-10-10 (exact) | 1 | H2_prior | News body: application date, labelling, targeting consent, third-country sponsor restriction, exclusions | https://commission.europa.eu/news-and-media/news/new-eu-rules-political-advertising-come-effect-2025-10-10_en |
| S-053 | European Commission - AI Act Article 50 FAQ | European Commission (Shaping Europe's digital future) | undated (undated) | 1 | contextual | FAQ: application 2 August 2026; Article 50(2) grace to 2 December 2026; deployer duties; editorial-control and artistic exceptions | https://digital-strategy.ec.europa.eu/en/faqs/transparency-obligations-under-article-50-ai-act |
| S-054 | EUR-Lex - Digital Omnibus on AI | EUR-Lex (Official Journal of the EU) | 2026-07-08 (exact) | 1 | current | EUR-Lex metadata: adoption 8 July 2026; first entry into force 27 July 2026 | https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202601744 |
| S-055 | European Commission - Cyber Resilience Act page | European Commission (Shaping Europe's digital future) | undated (undated) | 1 | contextual | Key dates; scope examples (apps, computer programs, computer games) | https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act |
| S-056 | European Commission - Radio Equipment Directive page | European Commission (DG GROW) | undated (undated) | 1 | contextual | Section on cybersecurity delegated act 2022/30 (application August 2025) and repeal by 2026/339 effective 11 December 2027 | https://single-market-economy.ec.europa.eu/sectors/electrical-and-electronic-engineering-industries-eei/radio-equipment-directive-red_en |
| S-057 | European Commission - Digital Services Act page | European Commission (Shaping Europe's digital future) | undated (undated) | 1 | contextual | Systemic risks and enforcement sections | https://digital-strategy.ec.europa.eu/en/policies/digital-services-act |
| S-058 | European Commission - Live-event piracy Recommendation stock-take | European Commission (Shaping Europe's digital future) | 2025-11-20 (exact) | 1 | H2_prior | News body: uptake, impact finding, further action under consideration | https://digital-strategy.ec.europa.eu/en/news/commission-takes-stock-progress-made-take-measures-its-2023-recommendation-combatting-online-piracy |
| S-059 | European Commission - European Democracy Shield | European Commission (DG Enlargement and Eastern Neighbourhood) | 2025-11-12 (exact) | 1 | H2_prior | News body: nature as Communication; Centre for Democratic Resilience; Media Resilience Programme; fact-checkers network | https://enlargement.ec.europa.eu/news/european-democracy-shield-and-eu-strategy-civil-society-pave-way-stronger-and-more-resilient-2025-11-12_en |
| S-060 | EUR-Lex - GDPR | EUR-Lex (Official Journal of the EU) | 2016-05-04 (exact) | 1 | historical | Articles 33(1) and 34(1) | https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX%3A02016R0679-20160504 |
| S-061 | UK Parliament - Cyber Security and Resilience Bill | UK Parliament | 2026-10-14 (page_update) | 1 | current | Bill page: current stage House of Lords Report; HL Bill 49 as amended in Grand Committee dated 7 September 2026; no Royal Assent shown | https://bills.parliament.uk/bills/4035 |
| S-062 | DSIT - Cyber Security and Resilience Bill summary | Department for Science, Innovation and Technology (GOV.UK) | 2026-06-30 (page_update) | 1 | current | Summary: managed service providers, data centres, designated suppliers, 24/72-hour reporting | https://www.gov.uk/government/publications/cyber-security-and-resilience-network-and-information-systems-bill-factsheets/summary-of-the-bill |
| S-063 | legislation.gov.uk - NIS Regulations 2018 | legislation.gov.uk | 2018 (year_only) | 1 | historical | Regs 1(1), 1(2), 1(3)(e) | https://www.legislation.gov.uk/uksi/2018/506 |
| S-064 | OPSS - Consumer connectable product security | Office for Product Safety and Standards (GOV.UK) | undated (undated) | 1 | contextual | Guidance body: in-force date, three requirements, exclusions | https://www.gov.uk/guidance/regulations-consumer-connectable-product-security |
| S-065 | legislation.gov.uk - DPA 2018 special purposes | legislation.gov.uk | 2018-05-23 (exact) | 1 | historical | Sch 2 para 26(1)-(9): conditions and listed provisions | https://www.legislation.gov.uk/ukpga/2018/12/schedule/2/paragraph/26 |
| S-066 | Home Office - Ransomware proposals consultation | Home Office (GOV.UK) | 2025-07-22 (exact) | 1 | H2_prior | Page body: consultation dates and response publication | https://www.gov.uk/government/consultations/ransomware-proposals-to-increase-incident-reporting-and-reduce-payments-to-criminals |
| S-067 | Goodwin - UK ransomware strategy alert | Goodwin Procter | 2026-02-12 (exact) | 3 | current | Alert body: three proposals, no legislation introduced | https://www.goodwinlaw.com/en/insights/publications/2026/02/alerts-technology-dpc-the-uks-ransomware-strategy |
| S-068 | DSIT - Government Cyber Action Plan | Department for Science, Innovation and Technology (GOV.UK) | 2026-01-06 (exact) | 1 | current | Sections on arm's-length bodies, Government Cyber Unit, delivery phases, relationship to the 2022-2030 strategy | https://www.gov.uk/government/publications/government-cyber-action-plan/government-cyber-action-plan |
| S-069 | SEC - Cyber disclosure compliance guide | US Securities and Exchange Commission | undated (undated) | 1 | contextual | Guide sections on Form 8-K Item 1.05, Regulation S-K Item 106, compliance dates, foreign private issuers | https://www.sec.gov/resources-small-businesses/small-business-compliance-guides/cybersecurity-risk-management-strategy-governance-incident-disclosure |
| S-070 | FTC - COPPA final rule amendments | US Federal Trade Commission | 2025-04-22 (exact) | 1 | H1_prior | Notice page: publication date and link to Federal Register text | https://www.ftc.gov/legal-library/browse/federal-register-notices/16-cfr-part-312-coppa-final-rule-amendments |
| S-071 | EBU - R 148 networked media equipment tests | European Broadcasting Union (EBU Technology and Innovation) | 2018-04-27 (exact) | 1 | historical | Publication page: purpose, annex of tests, update status | https://tech.ebu.ch/publications/r148 |
| S-072 | Hunton - CIRCIA timing | Hunton Andrews Kurth | 2026-07-17 (exact) | 3 | current | Blog body citing the Unified Agenda preview | https://www.hunton.com/privacy-and-cybersecurity-law-blog/cisa-plans-to-finalize-cyber-incident-reporting-regulations-in-september-2026 |
| S-073 | EUR-Lex - Digital Services Act | EUR-Lex (Official Journal of the EU) | 2022-10-27 (exact) | 1 | contextual | ELI metadata: document date 19 October 2022; OJ publication 27 October 2022 | https://eur-lex.europa.eu/eli/reg/2022/2065/oj/eng |
| S-074 | Music Business Worldwide - Live Nation class actions | Music Business Worldwide | 2026-10 (month_only) | 3 | current | Article body: Vermont Attorney General notice 1 October; three complaints filed 6-7 October in the Central District of California; company statement 8 October | https://www.musicbusinessworldwide.com/live-nation-hit-with-class-action-lawsuits-over-data-breach-involving-social-security-numbers-and-health-records/ |
| S-075 | legislation.gov.uk - National Security Act 2023 s13 | legislation.gov.uk (The National Archives) | 2023-07-11 (exact) | 1 | contextual | Section 13(1)-(3); commencement note (S.I. 2023/1272 reg 2(a), 20 December 2023); amendment by the National Security (State Threats) Act 2026 effective 8 July 2026 | https://www.legislation.gov.uk/ukpga/2023/32/section/13 |
| S-076 | legislation.gov.uk - Media Act 2024 | legislation.gov.uk (The National Archives) | 2024-05-24 (exact) | 1 | contextual | Long title and Act date (24 May 2024); Part 1 sections on public service television and Ofcom information powers (ss. 18-19) | https://www.legislation.gov.uk/ukpga/2024/15 |
| S-077 | GOV.UK - Online Safety Act explainer | UK Government (DSIT) | 2025-04-24 (page_update) | 1 | H1_prior | Sections on duties in force: illegal content duties enforceable from 17 March 2025; children's risk assessments by 24 July 2025; categorised services thresholds and register | https://gov.uk/government/publications/online-safety-act-explainer/online-safety-act-explainer |
| S-078 | DSIT - Telecommunications Security Code of Practice 2026 | UK Government (DSIT) | 2026-07-14 (exact) | 1 | current | Section 1 paras 0.13-0.26 (tiering, legal status); legal basis ss. 105A-105Z Communications Act 2003 and Electronic Communications (Security Measures) Regulations 2022 in force 1 October 2022 | https://www.gov.uk/government/publications/revised-telecommunications-security-code-of-practice-2026-version-11/telecommunications-security-code-of-practice-2026-version-11 |
| S-079 | Ofcom - Arqiva electronic communications network statement | Ofcom | 2018 (year_only) | 1 | historical | Paragraphs 1.13 (Arqiva's electronic communications network) and 1.15 (sites support terrestrial television and radio broadcast transmission) | https://www.ofcom.org.uk/siteassets/resources/documents/consultations/category-3-4-weeks/114661--code-powers-arqiva-limited/associated-documents/arqiva-limited-explanatory-statement.pdf |
| S-080 | Home Affairs - Infrastructure asset definition paper | Australian Government Department of Home Affairs | 2021-04 (month_only) | 1 | historical | Page 6 (section 12E broadcasting asset limbs: prescribed transmission site; at least 50 sites excluding re-transmission assets; prescribed entity); page 4 (positive security obligations) | homeaffairs.gov.au - full URL in the baseline source register (path contains a term excluded by the editorial rules) |
| S-081 | Federal Register of Legislation - SOCI Act 2018 compilation | Federal Register of Legislation (Australia) | 2026-06-04 (page_update) | 1 | current | Table of contents: s. 12E (broadcasting asset definition); Part 2 Register; Part 2A s. 30AB; Part 2B ss. 30BB-30BD | https://www.legislation.gov.au/C2018A00029/latest/text |
| S-082 | Digital Policy Alert - AVMSD transposition deadline | Digital Policy Alert | undated (undated) | 3 | historical | Event entry: adoption 14 November 2018; transposition deadline 19 September 2020 | https://digitalpolicyalert.org/event/42898-directive-amending-audiovisual-media-services-directive-201013eu-deadline-for-transposition-expired-no-20181808 |
| S-083 | GDPR-Text - Article 85 | GDPR-Text.com | undated (undated) | 3 | contextual | Article 85(1)-(3) | https://gdpr-text.com/uk/read/article-85 |
| S-084 | Advisera - Italian NIS2 decree overview | Advisera | undated (undated) | 3 | contextual | Article body: entities carrying out activities of cultural interest classified as important entities under specific conditions | https://advisera.com/it/articoli/italiano-nis2-decreto-legislativo/ |
| S-085 | iubenda - AI Omnibus and Article 50 | iubenda | 2026-07 (month_only) | 3 | current | Sections on Article 50: obligations from 2 August 2026 not moved; Article 50(2) marking for legacy systems by 2 December 2026; new systems from 2 August 2026 without grace period | https://www.iubenda.com/en/blog/ai-omnibus-adopted-august-2-obligations-july-2026/ |
| S-086 | Vermont Attorney General - Security breach notices | Office of the Vermont Attorney General | 2026-10-01 (page_update) | 1 | current | Table row: Live Nation Entertainment, Inc.; date reported 10-1-2026; type Other Commercial; Vermont residents affected 2; categories Social Security numbers, government ID numbers, health records | https://ago.vermont.gov/categories/security-breaches |
| S-087 | Court complaint - Gosman v. Live Nation | US District Court, Central District of California (complaint hosted by Music Business Worldwide) | 2026-10-07 (exact) | 1 | current | Caption and paragraphs 1, 25 (notice to Vermont Attorney General about 1 October 2026), 27 (data types), 103 (notice more than four months after learning of the breach), 136 (class size on information and belief) | https://www.musicbusinessworldwide.com/files/2026/10/Gosman-v-Live-Nation.pdf |

### G2. References cited in the user-supplied research input (merged 27 October 2026; not validated)

Numbering follows the input's footnotes (U-0nn = footnote nn). Titles are reproduced as given in the input, which truncates some of them; publisher is taken from the title or domain. Access dates, publication dates, tiers and locators were not recorded in the input and were not checked.

| ID | Title (as given) | Publisher / site | URL | Used in |
|---|---|---|---|---|
| U-001 | British Library shares learnings from cyber attack | Arts Professional | https://www.artsprofessional.co.uk/news/british-library-shares-learnings-cyber-attack | A, B, C, Q02, Q10, Q11, Q12, Q13, Q15, Q08 |
| U-002 | British Library security incident | Ally Incident Briefings | https://www.ally.security/incidents/british-library-security-incident-2023 | C, Q02, Q11, Q12, Q15, F |
| U-003 | SEC Charges Founder of Social Media Company "IRL" with $170 (title truncated in input) | Newsfile | https://www.newsfilecorp.com/release/218475/SEC-Charges-Founder-of-Social-Media-Company-IRL-with-170-Million-Fraud | C, Q10, Q15, Q08 |
| U-004 | ECCTA Failure to Prevent Fraud. Reasonable Procedures | Boru Consulting | https://www.boruconsulting.com/blog/eccta-failure-to-prevent-fraud-procedures | A, B, C, Q10, Q12, Q13, Q15, Q08, F |
| U-005 | FBI Internet Crime Report: What the Cybercrime Data Means | Seedpod Cyber | https://seedpodcyber.com/fbi-internet-crime-report-cyber-insurance/ | C, Q10, Q12, Q14, Q15, F |
| U-006 | SEC Litigation Release / MVES - The Movie Studio, Inc. | OTC Markets | https://www.otcmarkets.com/stock/MVES/news/SEC-Litigation-Release?id=316262 | Q10, Q08 |
| U-007 | What the 2026 ACFE Report Reveals About Fraud in Not-for-Profits | KMCO | https://www.kmco.com/insights/what-the-2026-acfe-report-reveals-about-fraud-in-not-for-profits/ | Q10 |
| U-008 | Movie Producer Arrested on Federal Indictment Charging Him with (title truncated in input) | US Attorney's Office, Central District of California | https://www.justice.gov/usao-cdca/pr/movie-producer-arrested-federal-indictment-charging-him-12-million-schemes-defraud | B, C, Q10, Q15, Q08 |
| U-009 | Occupational Fraud 2026: A Report to the Nations | ACFE Japan | https://www.acfe.jp/wp-content/uploads/2026/05/RTTN_2026-Digital.pdf | Q10, Q14 |
| U-010 | 2025 Verizon Data Breach Investigations Report | Keepnet Labs | https://keepnetlabs.com/blog/2025-verizon-data-breach-investigations-report | B, C, Q10, Q11, Q12, Q14, Q15 |
| U-011 | British Library Cyber Attack - 10 Lessons | I by IMD | https://www.imd.org/ibyimd/technology/full-transparency-10-lessons-from-the-cyber-attack-on-the-british-library/ | Q02, Q05, Q12, Q15, Q08 |
| U-012 | Icaro Media Group, Inc., et al. (Litigation Release No. 25979) | US SEC | https://www.sec.gov/enforcement-litigation/litigation-releases/lr-25979 | B, C, Q10, Q13, Q15, Q08 |
| U-013 | ECCTA - your questions answered | Simmons & Simmons | https://www.simmons-simmons.com/en/publications/cmcxen78m00fuu1lcx0v3mmbw/eccta-your-questions-answered | Q10, Q13, Q15 |
| U-014 | Fraud: The Government guidance for the 'failure to prevent fraud' (title truncated in input) | KPMG UK | https://kpmg.com/uk/en/insights/legal/government-guidance-for-failure-to-prevent-fraud-offence.html | Q10 |
| U-015 | ACFE 2026 Report: The Importance Of Whistleblower Mechanisms | Legal 500 | https://www.legal500.com/intelligence/turkey/corporate-commercial-law/acfe-2026-report-the-importance-of-whistleblower-mechanisms-in-combating-fraud | B, C, Q10, Q13, Q14, Q15 |
| U-016 | British Library to renew entire IT system as it reveals GBP 1.6m cyber (title truncated in input) | Civil Society | https://www.civilsociety.co.uk/news/british-library-to-renew-entire-it-system-amid-cuver-attack-loss.html (as given) | Q02, Q05 |
| U-017 | SEC charges Trump Media auditor with 'massive fraud' | The Guardian | https://www.theguardian.com/business/article/2024/may/03/trump-media-auditor-sec | B, C, Q10, Q13, Q15, Q08 |
| U-018 | ACFE Report to the Nations 2026: Why Whistleblowers Still Lead | Ethicontrol | https://ethicontrol.com/en/blog/acfe-report-to-the-nations-2026 | Q10 |
| U-019 | Securities Enforcement 2024 Year-End Update | Gibson Dunn | https://www.gibsondunn.com/securities-enforcement-2024-year-end-update/ | Listed in the input; not cited in its body |
| U-020 | Trump Media's newly hired auditing firm was just busted by the SEC | AP News | https://apnews.com/article/trump-media-auditor-sec-fraud-c6dbfc8a2e6b8a99c6c20547ad0e4cb5 | Q10 |
| U-021 | Internal & external fraud: key statistics | Supervizor | https://www.supervizor.com/blog/internal-external-fraud-key-stats | Q10 |
| U-022 | Occupational Fraud 2024: A Report to the Nations | ACFE | https://www.acfe.com/en-us/-/media/files/acfe/pdfs/rttn/2024/2024-report-to-the-nations.pdf | Q10, Q14 |
| U-023 | Protecting Creativity and Patrons: Data Loss Prevention in Arts | Zecurion | https://zecurion.com/blog/protecting-creativity-and-patrons-data-loss-prevention-in-arts-entertainment-and-recreation/ | Listed in the input; not cited in its body |
| U-024 | FBI Releases Its 2025 Internet Crime Report and Highlights | Bressler | https://www.bressler.com/news-fbi-releases-its-2025-internet-crime-report-and-highlights-significant-cyber-threats-to-financial-institutions-and-their-customers | Listed in the input; not cited in its body |
| U-025 | Data Breach Statistics 2025-2026: Global Trends & Costs | DeepStrike | https://deepstrike.io/blog/data-breach-statistics-2025 | Q10, Q14, Q15 |
| U-026 | 2025 Data Breach Investigations Report (SMB snapshot) | Verizon | https://www.verizon.com/business/resources/infographics/2025-dbir-smb-snapshot.pdf | Q10 |
| U-027 | ACFE Releases the Occupational Fraud 2026: A Report to the Nations | Cerebra | https://www.cerebra.com.tr/acfe-2026-report-to-the-nations/ | Listed in the input; not cited in its body |
| U-028 | Prevent Fraud Losses by Educating Your Nonprofit's Staffers | MBK CPA | https://www.mbkcpa.com/prevent-fraud-losses-by-educating-your-nonprofits-staffers | Listed in the input; not cited in its body |
| U-029 | The Economic Crime and Corporate Transparency Act 2023 (SI 2025/349) | legislation.gov.uk | https://www.legislation.gov.uk/uksi/2025/349/made | B, Q10 |
| U-030 | UK Government publishes guidance on new failure to prevent fraud (offence) | HLC | https://www.hlc.com/en/publications/the-clock-is-ticking-uk-government-publishes-guidance-on-new-failure-to-prevent-fraud-offence | Q10 |
| U-031 | Economic Crime and Corporate Transparency Act 2023: Guidance to organisations on the offence of failure to prevent fraud | GOV.UK (Home Office) | https://www.gov.uk/government/publications/offence-of-failure-to-prevent-fraud-introduced-by-eccta/economic-crime-and-corporate-transparency-act-2023-guidance-to-organisations-on-the-offence-of-failure-to-prevent-fraud-accessible-version | B, Q10, Q13, Q08 |
| U-032 | Occupational Fraud 2024: A Report to the Nations | Ivey Business School (host) | https://www.ivey.uwo.ca/media/kjljj5cy/2024-report-to-the-nations.pdf | Listed in the input; not cited in its body |
| U-033 | Guidance on the failure to prevent fraud offence (ECCTA 2023) | UK Finance | https://www.ukfinance.org.uk/policy-and-guidance/guidance/guidance-failure-prevent-fraud-offence-eccta-2023 | Q10 |

URLs were rejoined where the input broke them across lines; U-016 is reproduced with the spelling given in the input.

---

## H. Change log against the baseline edition

| Area | Change |
|---|---|
| Q01-Q07 | No change in evidence; reorganised by research question from the 15 October 2026 report and registers. The British Library case (Q02 case study 2) adds user-supplied root cause and cost alongside the baseline recovery data; the shared ticketing event is shown as case study 3 (pattern case) |
| Q10 | New: 14-typology screen, five documented US cases, four quantitative datasets, structural drivers, control failures, consequences, ECCTA, EU Whistleblower Directive and SOX, three emerging techniques |
| Q11 | New: digital dependency, legacy systems, infostealer and extortion trends, DBIR breach patterns |
| Q12 | New: three essential functions, dependency and concentration matrix with substitutability |
| Q13 | New: three operating models and four governance-failure categories, combined with baseline public-body audit findings |
| Q14 | New: five-sector comparison (user-supplied) with comparability notes |
| Q15 | Updated: Fraud from Not assessable to High (Provisional, Medium); Governance from Not assessable to Medium (Provisional, Medium); Cyber / ICT confidence from Medium to High; Operational resilience confidence from Medium to High; rating sensitivity triggers added |
| Q08 | Extended: PROV-07 to PROV-10 added (payment-detail change control, intermediary oversight, SPE governance, reported metrics, grants and royalties); PROV-01, -03, -04 and -05 extended with user-input evidence |
| Baseline edition status | The 15 October 2026 edition and the 12-slide migrated edition are unchanged and remain the published editions; this record supersedes neither |
