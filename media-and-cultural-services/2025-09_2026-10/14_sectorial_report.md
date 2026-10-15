# Media & Cultural Services - Sectorial Cyber Risk Intelligence

**Report date:** 15 October 2026. **Reporting period:** 1 September 2025 to 15 October 2026. **Evidence cut-off:** 15 October 2026. **Rolling evidence horizon:** 18 months for patterns and public loss cases, with older material labelled historical.

**Geography:** Global, with primary focus on the European Union (EU), European Economic Area (EEA) and United Kingdom (UK); North American, Japanese and other evidence is used for comparison. **Audience:** First Line of Defence (1LoD) operational management and Risk Committee. **Boundary:** public external data only; no internal, client or bank-specific information is used or implied. **Edition:** baseline edition; no prior publication exists for this sector, so changes are described against the period, not an earlier report.

**Evidence labels used throughout:** Observed (external fact from a named source), Benchmark (sector statistic with stated population), Proxy (indirect or derived measure), Judgement (analytic judgement by this report), Assumption (scenario assumption), Action (management recommendation). Each statement is preceded by its source reference in the form [Source/Title][n]; full details are in the References section.

## Sector Exposure & Executive Risk Outlook

### Bottom line

[Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [CMN - Ticketing personal data notice][8] [AWS - US-EAST-1 post-event summary][38] [Cloudflare - 18 November 2025 outage report][39] The best-documented Media & Cultural Services disruption pathway in the period runs through front-of-house digital services and shared platforms - online ticketing, shops and payments, content delivery networks (CDNs) and cloud regions - rather than through loss of content or collections (Judgement). [Lee Enterprises - FY2025 Form 10-K][30] [KADOKAWA - FY2025/3 results release][32] [British Library - Annual Report 2025/26][34] Where financial effects are public, they arrive through revenue-line disruption and long recovery tails; ransom payments are rarely disclosed, so their role cannot be assessed (Judgement). [FCC - FCC 26-38 alerting systems order][14] [Geo News - Satellite feed hijack statement][18] Broadcast signal and content-insertion integrity is an active exposure in the available US and Pakistani evidence, and a US regulator has started to address it with a binding baseline (Judgement, based on observed regulator and broadcaster records). [Cloudflare - DDoS Threat Report H1 2026][42] [EEAS - 4th FIMI Threats Report][43] Media is the most targeted industry for distributed denial-of-service (DDoS) traffic on Cloudflare's network and a priority target for foreign information manipulation and interference (FIMI) (Benchmark); these campaigns rarely produce disclosed operational or financial outcomes (Judgement). For a bank, relevance is conditional and indirect - through leveraged media-group credit, advertising, subscription and ticketing cash flows, payment-fraud follow-on, insurance and public-funding channels - not through any asserted exposure of a specific institution.

### Principal judgements

**1. Shared front-of-house platforms are the best-documented propagation pathway (Judgement; confidence medium).** [CMN - Ticketing personal data notice][8] [Musee Guimet - Online ticketing unavailable notice][7] [ActuaLitte - Vivaticket attack on cultural institutions][9] [L'Echo touristique - CMN ticketing cyberattack][10] Independent French outlets relaying institution statements report that a ransomware attack on one ticketing provider in March 2026 removed online ticketing at France's national monuments network, the national library and several museums at once (Tier 3 relays; Tier 1 sources confirm only the provider dependency and one undated outage notice), while [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [SKD - Recovery update, 29 January 2026][3] the Dresden State Art Collections (SKD) lost its online shop, visitor services and card payment for at least a week after a direct attack (Observed). [AWS - US-EAST-1 post-event summary][38] [Cloudflare - 18 November 2025 outage report][39] Two non-malicious provider failures in October and November 2025 showed the same single-point effect for cloud and CDN dependencies (Observed). **Competing explanation:** public institutions publish access effects while back-office and content losses go unreported, so front-office effects may be over-represented. **What would change this judgement:** disclosure of large content, archive or production losses exceeding access effects.

**2. Broadcast signal and content-insertion integrity is under-secured in the available evidence (Judgement; confidence medium).** [FCC - FCC 26-38 alerting systems order][14] The US Federal Communications Commission (FCC) adopted mandatory password, patching and segmentation requirements in June 2026 for equipment that inserts content into broadcast streams, after a run of stream hijacks through improperly secured, remotely accessible equipment in late 2025 that the order itself records (Observed). [Geo News - Satellite feed hijack statement][18] [Dawn - CERT investigation of TV channel hacks][19] In March 2026 Pakistani news channels' satellite feeds were hijacked; no attribution has been published (Observed). The evidence is one US and one Pakistani pattern. **Competing explanation:** these cases may be opportunistic and concentrated outside the EU and UK. **What would change this judgement:** evidence that EU and UK playout and transmission estates already meet equivalent baselines, or continued absence of EU and UK cases.

**3. DDoS and FIMI pressure is high but outcome-light (Judgement; confidence medium).** [Cloudflare - DDoS Threat Report H1 2026][42] Media, Production and Publishing received 14.2% of mitigated HTTP DDoS requests on Cloudflare's network in H1 2026, nearly four times the next industry (Benchmark). [EEAS - 4th FIMI Threats Report][43] The European External Action Service (EEAS) recorded 540 FIMI incidents in 2025 and names the media sector a priority target, including impersonation of established outlets (Benchmark). [ENISA - Threat Landscape 2026][41] ENISA reports broadcast media mostly faced hacktivist disruption of public-facing platforms (Benchmark). **Competing explanation:** undisclosed DDoS losses in advertising or subscriptions may be larger than visible. **What would change this judgement:** public evidence of multi-day DDoS outages with quantified revenue effect.

**4. Financial transmission runs through revenue lines, credit and long recovery tails (Judgement; confidence medium).** [Lee Enterprises - FY2025 Form 10-K][30] [Lee Enterprises - Q3 FY2026 Form 10-Q][31] Lee Enterprises lost USD 10.5 million of cash flows and, separately, added USD 11.3 million of debt through lender and landlord waivers after a February 2025 attack (not additive: the debt reflects waived payments); [KADOKAWA - FY2025/3 results release][32] KADOKAWA estimated JPY 8.3 billion of lost sales from a June 2024 attack; [British Library - Annual Report 2025/26][34] the British Library restored its main catalogue only in December 2025, more than two years after its October 2023 attack (Observed; historical observations, with disclosures from May 2025 to July 2026). **Competing explanation:** disclosed cases are the most severe and over-state typical outcomes. **What would change this judgement:** in-period EU or UK disclosures showing short, low-cost recoveries.

**5. The regulatory perimeter is indirect but tightening (Judgement; confidence high).** [European Commission - NIS2 FAQs][49] [European Commission - Entity resilience policy page][50] [legislation.gov.uk - NIS Regulations 2018][63] Media and culture are not named sectors under the EU NIS2 Directive, the EU CER Directive on entity resilience or the UK NIS Regulations 2018 (Observed). [European Commission - NIS2 FAQs][49] Under NIS2, obligations arrive through providers such as CDNs, cloud and managed service providers; [DSIT - Cyber Security and Resilience Bill summary][62] [UK Parliament - Cyber Security and Resilience Bill][61] in the UK, managed service providers would be added only if the Cyber Security and Resilience Bill is enacted; obligations also arrive through [European Commission - Cyber Resilience Act page][55] product rules such as Cyber Resilience Act (CRA) reporting from 11 September 2026, [European Commission - European Media Freedom Act page][51] [European Commission - AI Act Article 50 FAQ][53] media-specific rules on journalistic source protection and synthetic-media transparency, and [EUR-Lex - GDPR][60] data protection (Observed). **What would change this judgement:** national NIS2 measures that designate media or cultural entities directly.

### What changed in the period

- [BleepingComputer - SoundCloud breach][24] [NOS - RTV Noord hack][25] November-December 2025: a Dutch regional public broadcaster and an audio streaming platform disclosed cyber incidents through media statements (Observed; Tier 3 only, context).
- [Radio Ink - FCC warning after Houston hijack][13] 23 November 2025: a US radio station's live output was hijacked through backup streaming equipment, followed by an FCC bureau warning (Observed).
- [SDNY - Anna's Archive preliminary injunction][15] 20 January 2026: a US federal court issued a worldwide injunction against a shadow library that scraped music files from Spotify (Observed).
- [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] 21 January 2026: the Dresden State Art Collections were hit by a targeted cyberattack (Observed).
- [Geo News - Satellite feed hijack statement][18] 1 March 2026: Pakistani news channels' satellite feeds were hijacked (Observed).
- [L'Echo touristique - CMN ticketing cyberattack][10] [ActuaLitte - Vivaticket attack on cultural institutions][9] 2 March 2026: ransomware at the ticketing provider used by France's national monuments network disrupted online ticketing at many cultural sites (Tier 3 relays; Tier 1 confirms only the provider dependency).
- [FCC - FCC 26-38 alerting systems order][14] 25 June 2026: the FCC adopted binding cyber requirements for broadcast alerting and content-insertion equipment (Observed).
- [European Commission - AI Act Article 50 FAQ][53] [EUR-Lex - Digital Omnibus on AI][54] [iubenda - AI Omnibus and Article 50][85] 2 August 2026: AI Act Article 50 transparency obligations began to apply; the Digital Omnibus on AI entered into force on 27 July 2026 and is reported to have left that date unchanged, with Article 50(2) marking for systems already on the market from 2 December 2026 (Observed; Omnibus amending text not read).
- [European Commission - Cyber Resilience Act page][55] 11 September 2026: CRA manufacturer reporting obligations began (Observed).
- [UK Parliament - Cyber Security and Resilience Bill][61] 14 October 2026: the UK Cyber Security and Resilience Bill remained at House of Lords report stage (Observed).

### Sector footprint and subsector coverage

[Eurostat - EU cultural employment 2025][45] The EU cultural sector employed 8.9 million people in 2025, 4.3% of total employment (Benchmark). [DCMS - Sectors GVA 2024 (provisional)][46] UK creative industries generated GBP 145.8 billion of gross value added (GVA) in 2024, 5.5% of UK GVA, and the cultural sector GBP 40.3 billion, 1.5%, with overlap between the two (Benchmark).

| **Subsector** | **In-period public evidence** | **Evidence strength** | **Main gap** |
| --- | --- | --- | --- |
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

[Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [Lee Enterprises - FY2025 Form 10-K][30] [KADOKAWA - FY2025/3 results release][32] [British Library - Annual Report 2025/26][34] [SDNY - Anna's Archive preliminary injunction][15] Interpretation: disclosure is asymmetric. Public cultural bodies publish chronologies but rarely costs, listed groups disclose costs and revenue effects, and private platforms surface mainly through notices, litigation or attacker claims (Judgement). Absence of cost disclosure for cultural bodies is a data gap, not evidence of low loss.

### Financial-system relevance

The sector matters to a bank through generic, evidence-supported channels: (a) credit to leveraged media groups, where [Lee Enterprises - Q3 FY2026 Form 10-Q][31] Lee's post-incident waivers became additional debt; (b) advertising, subscription and licensing revenue, where [Lee Enterprises - FY2025 Form 10-K][30] [KADOKAWA - FY2025/3 results release][32] print advertising capacity and online video revenue were curtailed; (c) ticketing and payment flows, where [ActuaLitte - Vivaticket attack on cultural institutions][9] [L'Echo touristique - CMN ticketing cyberattack][10] exposed customer contact data creates phishing and payment-diversion risk even when card data is held by a separate provider; (d) insurance, where [Lee Enterprises - FY2025 Form 10-K][30] Lee filed claims for USD 6.8 million and [Hasbro - Q1 2026 results release][23] Hasbro, a cross-sector comparator, warned that reimbursement may lag expense recognition; and (e) public-funding absorption for cultural bodies, as [British Library - Annual Report 2024/25][33] the British Library's funding support shows. These are conditional transmission channels and not statements about any institution's exposure, losses, capital or Risk Appetite Framework (RAF) position.

## Key Threats & Top 5 Cyber Attacks

### Selection criteria

Named incidents qualify only if (1) the event or its regulatory or judicial outcome falls inside 1 September 2025 to 15 October 2026; (2) existence is supported by at least one Tier 1 or Tier 2 source; (3) the affected organisation belongs to a subsector in scope; and (4) the case adds a distinct operational lesson. Hacktivist and threat-actor claims, leak-site entries and Tier 3-only reports are excluded as named incidents. Threat pathways are shown separately and are patterns, not attacks.

### Threat pathways (patterns)

| **Pathway (pattern)** | **Operational vulnerability** | **Systemic or concentration translation** | **Evidence base** |
| --- | --- | --- | --- |
| P1 Ransomware and extortion against institutions and publishers | Encryption or isolation of ticketing, shop, newsroom, playout and catalogue systems | Recovery of legacy estates can take months to years | Dresden 2026; Lee 2025 (historical); British Library 2023 (historical) |
| P2 Shared front-of-house platforms and SaaS integrations | Ticketing, payment and analytics providers hold tokens and customer data for many institutions | One supplier incident removes revenue channels at hundreds of sites | Ticketing provider 2026 (Tier 3 detail); games publisher via analytics integration 2026 (Tier 3) |
| P3 Broadcast signal and content-insertion compromise | Default passwords and remote access on streaming encoders, studio-transmitter links and alerting devices | Hijacked live output or false alerts reach audiences directly | FCC 2025-2026; Pakistani satellite feeds 2026 |
| P4 Hacktivist DDoS and FIMI around conflicts, elections and live events | Public-facing news sites and brands are impersonated or flooded | Coordinated campaigns hit many outlets at once | Cloudflare H1 2026; ENISA 2026; EEAS 2026 |
| P5 Content and intellectual-property theft | Automated scraping through many accounts and circumvention of technical protection | Catalogue value at risk across rights holders | Spotify scraping 2025-2026 |
| P6 Personal data exposure and litigation | Subscriber, player, donor, staff and ticket-holder data in ancillary systems | Class actions and regulator scrutiny follow notification | Audio platform and ticketing exposures 2025-2026 (Tier 3) |

[Cloudflare - DDoS Threat Report H1 2026][42] Cloudflare attributes the media sector's leading DDoS share in H1 2026 to coverage of the wars in Iran and Ukraine and to the World Cup (Benchmark). [ENISA - Threat Landscape 2026][41] ENISA analysed 8,257 EU incidents in 2025; business services were 8.45% of events, with hospitality, consultancy and broadcast media together 55.3% of those, and the hacktivist group NoName057(16) accounted for 35.8% of ideology-driven claims in that group (Benchmark). [Europol - Operation Eastwood][47] Europol's Operation Eastwood disrupted that group's infrastructure in July 2025 and Germany issued six arrest warrants (Observed). [EEAS - 4th FIMI Threats Report][43] The EEAS reports that FIMI actors impersonated established outlets and fabricated media brands in 2025 and lists 2026 elections at risk (Benchmark). [DSIT - Cyber Security Breaches Survey 2025/26][44] In the UK, 63% of information and communication businesses and 28% of charities reported breaches or attacks in the year to the 2025/26 survey; only 35% of charities held cyber insurance (Benchmark).

### Top 5 named incidents in the period

| **#** | **Incident** | **Subsector** | **Place and date** | **Operational vulnerability** | **Consequence** | **Evidence strength** | **Sector relevance** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Dresden State Art Collections cyberattack | National cultural institution | Germany; 17-21 January 2026 onward | Corporate IT, online shop, visitor services and payments | Online shop and ticketing offline; cash-only sales; special police commission | Tier 1 institution, ministry, prosecutor and police | High: recent EU case with the most complete primary chronology |
| 2 | US radio stream hijacks via studio-transmitter-link devices | Broadcast radio | United States; November 2025 onward | Unsecured streaming and alerting equipment | Live output replaced with unauthorised audio; regulator warning and new rule | Tier 1 regulator order records the attacks; station detail Tier 3 | High: live-output and alert integrity |
| 3 | Pakistani news channels' satellite feed hijacks | Broadcast television | Pakistan; 1 March 2026 | Satellite feed and possible uplink path | Unauthorised content aired on several channels; national CERT investigation | Tier 1 broadcaster statement; breadth Tier 3 | Medium-high: satellite signal integrity |
| 4 | Spotify catalogue scraping by a shadow library | Audio streaming and recorded music | Global; December 2025 - April 2026 | Account-based scraping and circumvention of technical protection | Worldwide injunction; reported USD 322 million judgment unlikely to be collected | Tier 1 court order; amounts Tier 3 | Medium: intellectual-property value channel |
| 5 | Live-events group breach notice and class actions (Live Nation) | Live events and ticketing | United States; October 2026 | Identity and health data in corporate systems (scope per company statement, Tier 3) | Regulator notice; at least one federal class action within a week; company reports no operational impact | Tier 1 regulator register and court complaint; statement Tier 3 | Medium: data-exposure and litigation pathway |

**1. Dresden State Art Collections (January 2026).** [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [SKD - Cyberattack press release][2] A deliberate attack on 21 January 2026 affected large parts of SKD's digital infrastructure; the online shop and visitor services were unavailable while the security system remained operational and museums stayed open (Observed). Chapter 5 reconstructs this case.

**2. US radio stream hijacks (November 2025).** [FCC - FCC 26-38 alerting systems order][14] The FCC's June 2026 order records recent attacks in which improperly secured, remotely accessible equipment was used to air unauthorised audio including alert tones and offensive content, cites a Houston station hack of 23 November 2025, and states that successful attacks continued into 2026 (Observed). [Radio Ink - FCC warning after Houston hijack][13] On 23 November 2025 a Houston sports radio station's programme was replaced with unauthorised offensive audio through backup streaming equipment activated after a power outage; the FCC public safety bureau warned that similar attacks had inserted simulated or real Emergency Alert System (EAS) tones and obscene material through unsecured studio-transmitter-link devices (Observed; Tier 3 detail). [FCC - FCC 26-38 alerting systems order][14] In June 2026 the FCC required EAS participants to replace default passwords, patch promptly and segment remote management for equipment that inserts content into the programme stream (Observed).

**3. Pakistani satellite feed hijacks (March 2026).** [Geo News - Satellite feed hijack statement][18] Geo News stated that its satellite feed was hacked at the start of its 9 pm bulletin on 1 March 2026 after 24 hours of repeated attempts and that unauthorised content was displayed (Observed). [Dawn - CERT investigation of TV channel hacks][19] [Digital Rights Monitor - Pakistani channel takeovers][20] Reporting indicates Samaa TV and ARY News were also affected, that Pakistan's National CERT opened a formal investigation examining a possible uplink intrusion, and that no definitive findings or attribution had been published (Observed; Tier 3 for breadth). This report does not reproduce the broadcast content.

**4. Spotify catalogue scraping (December 2025 - April 2026).** [SDNY - Anna's Archive preliminary injunction][15] On 20 January 2026 the Southern District of New York found the plaintiffs likely to prove infringement by scraping from Spotify, issued a worldwide injunction, ordered registries, registrars and hosting providers to disable the defendant's domains and noted the defendant appeared unable to satisfy a judgment from US assets (Observed). [Music Business Worldwide - Anna's Archive lawsuit][16] [MusicTech - Anna's Archive judgment][17] The complaint alleges about 86 million music files were copied using thousands of accounts; media report a USD 322 million judgment on 14 April 2026 with collection doubtful (Observed; amounts Tier 3).

**5. Live-events group breach notice and class actions (October 2026).** [Vermont Attorney General - Security breach notices][86] Live Nation Entertainment reported a security breach to the Vermont Attorney General on 1 October 2026 covering Social Security numbers, government ID numbers and health records; the register lists two Vermont residents and notes totals may rise (Observed; notification evidence only). [Court complaint - Gosman v. Live Nation][87] A proposed class action filed on 7 October 2026 in the Central District of California alleges that notice came more than four months after the company learned of the breach; several allegations are made on information and belief and none has been tested (Observed). [Music Business Worldwide - Live Nation class actions][74] Trade media report three near-identical complaints and a company statement that the incident was limited in scope with no operational impact (Tier 3). Interpretation: in the live-events subsector a limited data incident can become litigation exposure within days, independently of any service disruption.

### Considered but not selected

- **Shared ticketing provider ransomware (Vivaticket), March 2026 - highest relevance, not selected as a named incident.** No Tier 1 source records the incident itself: the national library's own outage notice could not be read (server error), the CMN ticketing site confirms only the provider dependency and the Guimet notice is undated and gives no cause. The event is therefore analysed as a pattern case in Chapters 2, 4 and 6 rather than as a named incident. [CMN - Ticketing personal data notice][8] [L'Echo touristique - CMN ticketing cyberattack][10] The official ticketing site of the Centre des monuments nationaux (CMN), which manages about a hundred national monuments, names Vivaticket S.p.A. as the provider that hosts and transmits its ticketing data (Observed). [Musee Guimet - Online ticketing unavailable notice][7] The Musee Guimet published a notice that online reservations were unavailable and redirected visitors to a third-party ticket office and on-site sales (Observed; notice undated). [L'Echo touristique - CMN ticketing cyberattack][10] [ActuaLitte - Vivaticket attack on cultural institutions][9] [Lyon Mag - Lyon municipal museums ticketing attack][11] Independent French outlets relaying CMN, City of Lyon and national library (BnF) statements report that the provider was hit by ransomware on 2 March 2026, that online ticketing became unavailable at the BnF, Louvre-Lens, Musee des Arts et Metiers, Guimet and four Lyon municipal museums, that CMN reopened online sales on 12 March while the BnF still could not sell online on 19 March, and that the data protection authority (CNIL), the national cyber agency (ANSSI) and the Ministry of Culture were informed and the Paris prosecutor opened an investigation (Observed; Tier 3 relays). [SC Media - Vivaticket platform breach brief][12] Reported scope reached nearly 3,500 European sites; institutions said contact and purchase data may have been exposed while bank-card data, handled by a separate payment provider, was not; a ransomware group's claim is unconfirmed (Observed; Tier 3, low confidence). Interpretation: the event shows how one supplier removes public-access revenue channels across a national heritage network simultaneously.
- [NOS - RTV Noord hack][25] [NL Times - RTV Noord broadcast disruption][26] RTV Noord, Netherlands: a regional public broadcaster lost its systems on 6 November 2025 to untargeted ransomware, kept radio on air with CDs and vinyl, and refused to pay; the broadcaster's own pages could not be retrieved, so the case rests on Tier 3 reporting and is used as context only.
- [BleepingComputer - SoundCloud breach][24] SoundCloud: in December 2025 the platform said an ancillary dashboard was accessed and email and public-profile data taken, with denial-of-service and VPN disruption following (Tier 3 relay of company statement; context only).
- [TechCrunch - Anodot integration breach][21] Rockstar Games via Anodot: in April 2026 attackers stole integration tokens from an analytics provider and used them against at least a dozen companies' cloud data; the publisher said there was no impact on players (Tier 3; context for P2).
- [Hasbro - Form 8-K, 1 April 2026][22] [Hasbro - Q1 2026 results release][23] Hasbro: unauthorised network access identified on 28 March 2026 with systems offline for weeks; not selected because the group is not a core sector entity and no segment effect was disclosed (Tier 1).
- [Artribune - Uffizi incident claims and response][27] Uffizi Galleries, Italy: press claims of a months-long intrusion were disputed by the director; the national cyber agency opened an investigation (Tier 3; contested).
- [t-online - Leipzig cultural enterprises attack][28] [Quotenmeter - Cyberattacks on journalism][29] Leipzig municipal IT provider (July 2026) and a German regional publishing group DDoS (August 2026): limited disclosed effect (Tier 3).
- [Lee Enterprises - FY2025 Form 10-K][30] [KADOKAWA - FY2025/3 results release][32] [British Library - Annual Report 2024/25][33] Lee Enterprises (February 2025), KADOKAWA (June 2024) and the British Library (October 2023): observation dates fall before the period; their in-period financial and recovery disclosures are used in Chapter 3.

Shortfall statement: five incidents meet the standard, but only one is in the EU and none in the UK has a retrievable Tier 1 statement. The most relevant EU event, the March 2026 shared ticketing ransomware, is excluded as a named incident because its existence rests on Tier 3 relays. This reflects disclosure asymmetry and access limits, not absence of EU or UK incidents.

## Financial Impact: Media & Cultural Services

### Bottom line

Public financial evidence for the sector is sparse and cannot be added up. No EU or UK entity disclosed a quantified cyber cost for an in-period incident. The quantified cases are a US newspaper group and a Japanese publisher and platform group, both with attacks before the period and financial disclosure during or just before it. The dominant mechanism in all quantified cases is revenue-line disruption and recovery time, with credit and insurance effects following.

### Public operational and financial outcomes

| **Case** | **Metric type** | **Value** | **Period** | **Population** | **Comparability note** |
| --- | --- | --- | --- | --- | --- |
| Lee Enterprises | Loss of cash flows attributed to incident | USD 10.5 million | Fiscal year to 28 September 2025 | One US newspaper group | Includes amounts claimed from insurers |
| Lee Enterprises | Restoration cost expensed | USD 3.7 million | Fiscal year to 28 September 2025 | One US newspaper group | Subset of the USD 10.5 million |
| Lee Enterprises | Insurance claims filed | USD 6.8 million | Fiscal year to 28 September 2025 | One US newspaper group | Claim, not recovery |
| Lee Enterprises | Debt added by lender and landlord waivers | USD 11.3 million | As at 28 September 2025 | One US newspaper group | Non-cash credit effect |
| KADOKAWA | Sales effect (company estimate) | JPY 8.3 billion | Fiscal year to 31 March 2025 | One Japanese publisher and platform group | Estimate; attack June 2024 |
| KADOKAWA | Operating profit effect (company estimate) | JPY 4.7 billion | Fiscal year to 31 March 2025 | One Japanese publisher and platform group | Estimate; not additive with special loss |
| KADOKAWA | Special loss | JPY 2.4 billion | Fiscal year to 31 March 2025 | One Japanese publisher and platform group | Accounting loss |
| British Library | KPIs within 10% of target | 72.8% versus 81.8% prior year | 2025/26 | One national library | Not all shortfall attributed to the attack |
| British Library | Time to new main catalogue (derived) | About 26 months | October 2023 - December 2025 | One national library | Derived from Tier 1 dates |
| Dresden State Art Collections | Time to website restoration (derived) | 5 days | 21-26 January 2026 | One state museum network | Some functions still unavailable |
| Dresden State Art Collections | Time to online booking (derived upper bound) | 30 days or fewer | 21 January - 20 February 2026 | One state museum network | End date from Tier 3 report |
| CMN ticketing (shared provider) | Time to reopen online sales (derived) | 10 days | 2-12 March 2026 | National monuments network | Based on Tier 3 relays |
| Spotify and labels | Reported damages award to plaintiffs | USD 322 million | Judgment 14 April 2026 | One civil case | Award, not a loss measure; Tier 3; collection doubtful |
| Dresden State Art Collections | Cost, data, insurance | Not disclosed | 2026 | One state museum network | Absence of data is not zero |

[Lee Enterprises - FY2025 Form 10-K][30] Lee attributes a USD 10.5 million loss of cash flows to the 3 February 2025 attack, of which about USD 3.7 million was expensed as restoration cost, with insurance claims for the remaining USD 6.8 million; print advertising capacity was limited for several months and the incident contributed to digital advertising decline and a temporary liquidity disruption (Observed; historical observation). [Lee Enterprises - Q3 FY2026 Form 10-Q][31] Lee's lender and landlord waived three months of interest and lease payments, increasing debt by USD 11.3 million, and Lee reported USD 6.4 million of insurance proceeds in the nine months to 28 June 2026 without explicitly linking them to the incident in the reviewed text (Observed; link is a Proxy). [KADOKAWA - FY2025/3 results release][32] KADOKAWA estimated the June 2024 attack reduced group sales by about JPY 8.3 billion and operating profit by about JPY 4.7 billion, with Web Services sales down about JPY 3.95 billion and domestic print publishing sales down about JPY 3.65 billion, plus a special loss of about JPY 2.4 billion (Observed; historical observation). [British Library - Annual Report 2025/26][34] The British Library's 2025/26 report states that performance continues to be significantly affected by the attack, and records digital legal deposit performance measured at zero and website visits 14% below target and below historic levels following the attack (Observed).

Comparability: these values cannot be summed or averaged. They differ in currency (USD, JPY), statistic type (cash-flow loss, expense, claim, estimate, accounting loss, performance share, duration), population and accounting regime. No sector-wide loss estimate is produced.

### Impact types: what is and is not publicly evidenced

| **Impact type** | **Public evidence in scope** | **Status** |
| --- | --- | --- |
| Service disruption (output, publication, platform, access) | Dresden online shop and ticketing; shared ticketing outage; radio and satellite hijacks; cloud and CDN outages | Observed; durations partly derived |
| Response cost | Lee USD 3.7 million expensed; Hasbro legal and remediation costs from Q2 2026 unquantified | Observed for one company |
| Recovery and rebuild cost (legacy, archive, collection systems) | British Library rebuild programme; Louvre audit on underinvestment | Qualitative; costs not read |
| Revenue and cash-flow effect (advertising, subscription, ticketing, licensing) | Lee print and digital advertising; KADOKAWA Web Services and print; British Library footfall-linked income | Observed (historical observations) |
| Contractual and supplier impact (rights, make-goods, distribution) | None disclosed in period | Not evidenced |
| Content and intellectual-property loss | Spotify scraping injunction and reported judgment | Observed; collection doubtful (Tier 3) |
| Data-breach notification and remediation | Live-events group regulator notice (Tier 1); ticketing customer data and audio platform data (Tier 3) | Observed |
| Regulatory outcome | Investigations opened (Paris prosecutor, Saxony special commission, Pakistan CERT); FCC rule | Observed; no penalty in period |
| Litigation and settlement | Live-events group class actions filed October 2026 (Tier 1 complaint); Lee litigation ongoing | Observed; no outcome |
| Insurance effect | Lee USD 6.8 million claimed; Hasbro claims documented; 35% of UK charities insured | Observed; recoveries lag |
| Public funding, reserves or government support | British Library DCMS support and grant-in-aid uplift | Observed |
| Wider economic transmission | Lee debt increase through waivers | Observed for one borrower |

[Hasbro - Q1 2026 results release][23] Hasbro said legal and remediation costs began in the second quarter of 2026 and that insurance reimbursement timing may not match expense recognition (Observed). [Lee Enterprises - FY2025 Form 10-K][30] Lee reports ongoing litigation related to its incident (Observed). [Vermont Attorney General - Security breach notices][86] [Court complaint - Gosman v. Live Nation][87] [Music Business Worldwide - Live Nation class actions][74] Separately, a US live-events group's 1 October 2026 breach notice was followed by a federal class action on 7 October and, per trade media, two further complaints (Observed; complaint allegations untested). [British Library - Annual Report 2024/25][33] The British Library reports DCMS support for financial stabilisation and a confirmed grant-in-aid uplift for 2025/26, and lower footfall-linked income (Observed). [Toronto Auditor General - Toronto Public Library audit][36] Toronto's Auditor General reported a cybersecurity audit of Toronto Public Library in May 2026, after its October 2023 attack, with findings in a confidential attachment and implementation cost not determinable (Observed). [Cour des comptes - Louvre public establishment summary][37] The Cour des comptes found the Louvre allocated EUR 26.7 million to maintenance and compliance against EUR 105.4 million to acquisitions and recommended a full information systems and digital directorate by end-2026 (Observed; context, not cyber-specific).

### Financial-system transmission (conditional channels)

- **Recovery long tail.** [British Library - Annual Report 2025/26][34] [Museums Association - British Library recovery][35] The British Library expects UK Web Archive access in autumn 2026 and, in September 2026, public access remained unavailable for a number of its catalogues (Observed; status Tier 3). Judgement: legacy-heavy cultural estates absorb multi-year performance and income effects.
- **Credit to leveraged media groups.** [Lee Enterprises - Q3 FY2026 Form 10-Q][31] Lee's waivers converted a cyber disruption into USD 11.3 million of additional debt (Observed). Judgement: lenders to leveraged media groups may face waiver requests and covenant pressure after an incident; the bank-relevant signal is unscheduled waiver or amendment activity.
- **Advertising and subscription revenue.** [Lee Enterprises - FY2025 Form 10-K][30] [KADOKAWA - FY2025/3 results release][32] Print advertising capacity and online platform revenue were curtailed for months (Observed). Judgement: in the two quantified cases, revenue effects arose from production and distribution outages rather than from data theft.
- **Ticketing and payment flows.** [ActuaLitte - Vivaticket attack on cultural institutions][9] [L'Echo touristique - CMN ticketing cyberattack][10] Exposed contact and purchase data at a ticketing provider prompted phishing warnings even though card data sat with a separate provider (Observed; Tier 3). Judgement: payment-diversion and card-not-present fraud attempts can follow ticketing exposures, affecting acquiring and issuing banks.
- **Intellectual-property value.** [SDNY - Anna's Archive preliminary injunction][15] A court found likely infringement at catalogue scale and noted the defendant appeared unable to satisfy a judgment from US assets (Observed). Judgement: catalogue-scale scraping may reduce the value of exclusivity; no public evidence of a valuation or collateral effect exists.
- **Insurance timing.** [Hasbro - Q1 2026 results release][23] [DSIT - Cyber Security Breaches Survey 2025/26][44] Recoveries lag expense recognition and only 35% of UK charities hold cyber insurance (Observed; Benchmark). Judgement: uninsured cultural charities absorb losses through reserves or public funding.
- **Concentration.** [AWS - US-EAST-1 post-event summary][38] [Cloudflare - 18 November 2025 outage report][39] Single cloud and CDN failures lasted from about 6 to 14.5 hours (Observed). Judgement: correlated outages across many media, games and venue borrowers can coincide with high-value live events.

## Financial Impact: Worst-Case Scenarios

The three scenarios below are structured stress narratives, not forecasts, audience-harm estimates or loss estimates for any institution. No probabilities are assigned because no defensible external basis exists.

### Scenario 1 - Common digital-dependency failure

- **Trigger (Assumption).** [AWS - US-EAST-1 post-event summary][38] [Cloudflare - 18 November 2025 outage report][39] A multi-hour failure or attack on a shared cloud region, CDN, identity service or shared satellite capacity operator during a major live event such as a final, an election night or a premiere.
- **Affected service.** Live streaming and catch-up, online game services, ticket sales and news publication.
- **Propagation pathway.** [AWS - US-EAST-1 post-event summary][38] The October 2025 AWS regional disruption lasted about 14 hours 32 minutes and affected many dependent services; [PPC Land - AWS outage effects][40] games including Fortnite, Roblox and Dead by Daylight were reported disrupted (Observed; Tier 3 for customers).
- **Impact drivers.** [Cloudflare - DDoS Threat Report H1 2026][42] Media already receives the largest share of DDoS traffic, so an attack can coincide with peak audience moments (Benchmark).
- **Financial transmission.** Lost live audiences and advertising inventory, advertiser make-goods, rights-holder disputes, refund and re-sale costs, and correlated revenue dips across many counterparties at once.
- **Early signposts.** Provider status incidents, regional cloud impairment, DDoS spikes against media and hacktivist announcements before live events.
- **Limiting conditions.** [AWS - US-EAST-1 post-event summary][38] [Cloudflare - 18 November 2025 outage report][39] Both 2025 provider failures were non-malicious and restored within a day; multi-provider delivery and pre-recorded fallbacks limit the effect (Observed).
- **Management questions.** Which shared cloud, CDN and identity providers do the largest media and live-event counterparties depend on, and is there evidence of tested failover before rights-sensitive events?
- **Assumptions.** A multi-hour availability failure, without data compromise, coincides with a live event; the 6 to 14.5-hour durations of the 2025 provider events are illustrative, not predictive; no probability is assigned.

### Scenario 2 - Targeted operational disruption

- **Trigger (Assumption).** [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [FCC - FCC 26-38 alerting systems order][14] [Geo News - Satellite feed hijack statement][18] Ransomware or intrusion at a major broadcaster, news organisation or national cultural institution, or compromise of content-insertion, satellite or alerting equipment during an election or live event.
- **Affected service.** Live output and playout, newsroom publication, public access to collections and venues, emergency alerting.
- **Propagation pathway.** [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [SKD - Recovery update, 29 January 2026][3] Containment isolates ticketing, shop and payment systems (Dresden); [Radio Ink - FCC warning after Houston hijack][13] [Geo News - Satellite feed hijack statement][18] hijacked output reaches audiences directly (US radio, Pakistani satellite feeds) (Observed).
- **Impact drivers.** [Lee Enterprises - FY2025 Form 10-K][30] [British Library - Annual Report 2025/26][34] Months of curtailed advertising capacity (Lee) and years of reduced public access for legacy estates (British Library) (Observed; historical observations).
- **Financial transmission.** Off-air or degraded output, lost advertising and subscriptions, recovery and rebuild cost, regulatory scrutiny of broadcast licensees, and public-funding draw for cultural bodies.
- **Early signposts.** Regulator warnings on content-insertion devices, conflict escalation, election calendars, sector incident notices and claims by hacktivist groups.
- **Limiting conditions.** [NL Times - RTV Noord broadcast disruption][26] A regional broadcaster kept radio on air with physical media (Tier 3); [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] the security system remained operational and museums stayed open (Observed).
- **Management questions.** For broadcast and cultural counterparties, is there evidence of segregated playout and security networks, tested manual fallback and hardened content-insertion devices?
- **Assumptions.** One counterparty is affected for days to months; the Dresden (days to weeks), Lee (months) and British Library (years) recoveries illustrate the range and are not predictions; no probability is assigned.

### Scenario 3 - Third- or fourth-party supply-chain concentration

- **Trigger (Assumption).** [CMN - Ticketing personal data notice][8] [ActuaLitte - Vivaticket attack on cultural institutions][9] Compromise (not an availability failure of shared infrastructure, which is Scenario 1) of an application-layer supplier - ticketing, collection-management, library-management, newsroom, playout or media asset management software, or the managed service provider operating it - or theft of its integration tokens.
- **Affected service.** Online ticketing and payments, collection and catalogue access, newsroom and playout tools, customer data.
- **Propagation pathway.** [CMN - Ticketing personal data notice][8] [L'Echo touristique - CMN ticketing cyberattack][10] [ActuaLitte - Vivaticket attack on cultural institutions][9] One ticketing provider served about a hundred national monuments and many museums (Observed), and its reported compromise removed online sales across them (Tier 3 relays); [TechCrunch - Anodot integration breach][21] an analytics provider's stolen tokens reached at least a dozen companies' cloud data (Tier 3).
- **Impact drivers.** Simultaneous loss of revenue channels, notification duties, phishing follow-on and supplier disputes.
- **Financial transmission.** Correlated ticketing revenue loss, customer-fraud exposure, supplier insolvency or contract disputes, and regulator reviews of customers.
- **Early signposts.** Supplier breach notices, prosecutor or regulator statements naming a provider, attacker claims against suppliers.
- **Limiting conditions.** [Musee Guimet - Online ticketing unavailable notice][7] Alternative ticket offices and on-site sales kept venues open (Observed).
- **Management questions.** Which suppliers serve a large share of museums, venues or broadcasters in a market, and do counterparties hold exit, fallback and data-segregation arrangements? [European Commission - NIS2 FAQs][49] [DSIT - Cyber Security and Resilience Bill summary][62] Is the supplier itself regulated as a managed service or digital infrastructure provider?
- **Assumptions.** The supplier serves hundreds to thousands of institutions, as reported for the March 2026 ticketing provider (Tier 3); customers lack immediate alternative channels; no probability is assigned.

### Scenario distinctness

| **Dimension** | **Scenario 1** | **Scenario 2** | **Scenario 3** |
| --- | --- | --- | --- |
| Point of failure | Availability failure of shared cloud, CDN, identity service or satellite capacity operator | One major broadcaster, publisher or institution, or its own signal chain | Compromise of one application-layer supplier serving many institutions |
| Breadth | Many organisations at once, short duration | One organisation, deep and long effect | Many customers of one supplier |
| Main cost driver | Lost live audience and advertising | Output loss, rebuild and regulatory scrutiny | Correlated revenue loss and data notification |
| Key limiting condition | Multi-provider delivery | Segregation and manual fallback | Alternative sales channels and supplier diversity |

## Case Study: Dresden State Art Collections Cyberattack

### Why this case

| **Candidate** | **Recency** | **Sector relevance** | **Causal clarity** | **Disclosed outcome** | **Evidence quality** | **Decision** |
| --- | --- | --- | --- | --- | --- | --- |
| Dresden State Art Collections | January 2026 | High (national cultural institution) | Medium | Service restoration dates; investigation | Three distinct Tier 1 releases (22 January, 29 January, 19 February) | Selected |
| Shared ticketing provider | March 2026 | Highest (many institutions) | Medium | Outage dates; data scope | Tier 3 relays; Tier 1 only for provider dependency | Pattern case in Chapters 2, 4 and 6; monitor |
| British Library | October 2023 attack; 2026 status | High | High | Recovery milestones and performance | Tier 1 annual reports | Historical; Chapters 3 and 6 |
| Lee Enterprises | February 2025 attack | Medium (US publisher) | Medium | Cost and credit effects | Tier 1 filings | Historical; Chapter 3 |
| RTV Noord | November 2025 | High (public broadcaster) | Low | Continuity detail | Tier 3 only | Context only |

[Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [SKD - Recovery update, 29 January 2026][3] [Prosecutor and LKA Saxony - SKD investigation release][4] Judgement: Dresden is the only recent EU case with a Tier 1 chronology from the affected institution, its ministry, the prosecutor and the state criminal police, and it shows how a national cultural institution's revenue and access channels fail and recover.

### Timeline

| **Date** | **Event** | **Evidence** |
| --- | --- | --- |
| 17-21 January 2026 | Attack activity over several days according to a ministerial answer to a parliamentary question | Observed; Tier 3 relay |
| 21 January 2026 | Deliberate cyberattack on SKD (ministry release); large parts of digital infrastructure affected; crisis team formed | Observed; Tier 1 |
| 22 January 2026 | Online shop and visitor services unavailable; telephone and digital contact limited; security system unaffected; museums open | Observed; Tier 1 |
| 26 January 2026 | Website available again except some functions | Observed; Tier 1 |
| 29 January 2026 | Telephone restored; online shop offline; on-site sales cash only; pre-booked tickets valid | Observed; Tier 1 |
| 19 February 2026 | State criminal police special commission under prosecutor direction announced | Observed; Tier 1 |
| By 20 February 2026 | Online tickets bookable again | Observed; Tier 3 |
| July 2026 | Case against unknown persons still pending under the Saxon cybercrime prosecution unit | Observed; Tier 3 relay |

[dpa via Volksstimme - SKD attack duration][6] [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [SKD - Cyberattack press release][2] [SKD - Recovery update, 29 January 2026][3] [Prosecutor and LKA Saxony - SKD investigation release][4] [t-online - SKD special commission report][5] The timeline is compiled from the institution, ministry, prosecutor and police releases and from regional reporting of later status (Observed).

### Disruption mechanism

[Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] The ministry described a deliberate attack affecting large parts of the digital infrastructure (Observed). [dpa via Volksstimme - SKD attack duration][6] A ministerial answer relayed by dpa places attack activity between 17 and 21 January 2026 (Observed; Tier 3 relay). No initial access vector, attacker identity, ransom demand or data exfiltration has been published. Interpretation: activity over several days before containment suggests a detection lag in a state cultural body's corporate IT.

### Operational and public-access consequences

- [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [SKD - Cyberattack press release][2] Online shop and visitor services were unavailable and telephone and digital contact severely limited, while the museums stayed open and the security system remained operational (Observed).
- [SKD - Recovery update, 29 January 2026][3] After the website returned on 26 January, on-site ticket sales were cash only and the online shop stayed offline; tickets booked before the attack remained valid (Observed).
- [t-online - SKD special commission report][5] Online booking was reported available again by 20 February 2026 (Observed; Tier 3).

### Public financial and regulatory outcomes

[Prosecutor and LKA Saxony - SKD investigation release][4] The prosecutor and the state criminal police set up a special investigation commission (Observed). [dpa via Volksstimme - SKD attack duration][6] The case remained pending against unknown persons in July 2026 (Observed; Tier 3 relay). No cost, insurance, data-protection notification or penalty had been published by the evidence cut-off. [t-online - SKD special commission report][5] Regional media relayed an unconfirmed tabloid report linking the attack to a planned theft; investigators neither confirmed nor denied it (Observed; low confidence; not used as a finding).

### Recovery constraints

[SKD - Recovery update, 29 January 2026][3] Information channels returned first and transactional and payment channels last: the website within five days, the online shop and card payment later (Observed). Interpretation: a museum network's front-of-house revenue channels depend on the same corporate IT that attackers reach; physical security appears to have been outside the affected systems, although the reason was not disclosed.

### Sector lesson and read-across

- For cultural institutions: [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [SKD - Recovery update, 29 January 2026][3] the security system remained operational and museums stayed open, while ticketing, shop and payment channels recovered last (Observed); segregation of security systems from corporate IT is a plausible but unconfirmed reason (Judgement).
- For venues and broadcasters selling access digitally: alternative and offline sales channels are the main limiting condition.
- For banks (generic): public cultural counterparties can lose card-payment and online-sales revenue for weeks; acquiring and merchant-service relationships see the effect first.

### What the case does not establish

The case does not show any quantified cost, data loss, insurance recovery, attacker identity, initial access vector or link to physical crime. It concerns one German state museum network.

## Systemic Dependencies & Regulatory Outlook

### Dependency chains

| **Dependency** | **Evidence** | **Concentration pathway** | **Who is exposed** |
| --- | --- | --- | --- |
| Shared ticketing and visitor platforms | Vivaticket and the national monuments network | One provider hosts sales and data for many institutions | Museums, monuments, libraries, venues and their payment providers |
| Hyperscale cloud regions | AWS US-EAST-1 October 2025 | One region failure affects many dependent services | Streaming, online games, publishers |
| Content delivery networks | Cloudflare November 2025 | One configuration error causes global errors | News sites, streaming, ticketing |
| Analytics and SaaS integrations | Anodot token theft April 2026 (Tier 3) | Stolen integration tokens reach customers' cloud data | Games publishers and platforms |
| Broadcast content-insertion and satellite paths | US streaming encoders; Pakistani satellite feeds | Remote access or uplink path inserts content into live output | Broadcasters and their audiences |
| Municipal and public-sector shared IT | Leipzig municipal IT provider (Tier 3) | One provider serves opera, concert hall, theatre and city services | Publicly owned cultural bodies |

[CMN - Ticketing personal data notice][8] [AWS - US-EAST-1 post-event summary][38] [Cloudflare - 18 November 2025 outage report][39] [TechCrunch - Anodot integration breach][21] [FCC - FCC 26-38 alerting systems order][14] [Geo News - Satellite feed hijack statement][18] [t-online - Leipzig cultural enterprises attack][28] Dependencies are named only where a source supports them; market shares of ticketing, playout and collection-management providers are not public and no provider is described as dominant (Observed and Judgement).

### Regulatory perimeter (status and dates)

| **Regime** | **Jurisdiction** | **Legal status** | **Obligation type** | **Key dates** | **Applicability to Media & Cultural Services** |
| --- | --- | --- | --- | --- | --- |
| NIS2 Directive (EU) 2022/2555 | EU | Binding directive via national law | Risk management, reporting, governance | In force 16 January 2023; transposition by 17 October 2024; NIS1 repealed from 18 October 2024 | Media and culture not listed; reached through CDN, cloud, DNS, data centre, communications, managed service and space providers, digital providers and electronics manufacturing; state-owned cultural bodies may fall in scope as public administration subject to national definition; Member State discretion |
| CER Directive (EU) 2022/2557 (entity resilience) | EU | Binding directive via national law | Resilience measures by designated entities | Applies 18 October 2024; identification by 17 July 2026 | Eleven sectors; media and culture not listed |
| European Media Freedom Act (EU) 2024/1083 | EU | Directly applicable regulation | Protection of journalistic sources including against intrusive surveillance software | Most provisions applied 8 August 2025 | Media service providers and journalists |
| Political advertising Regulation (EU) 2024/900 | EU | Directly applicable regulation | Labelling, targeting consent, third-country sponsor restriction | Applies 10 October 2025 | Publishers and advertising services |
| AI Act (EU) 2024/1689, Article 50 | EU | Directly applicable regulation | Synthetic-content marking, deepfake disclosure, labelling of AI text on public-interest matters | Applies 2 August 2026; Article 50(2) marking for systems placed on the market before 2 August 2026 from 2 December 2026 (reported transition; source not confirmed in amending text) | Newsrooms, producers, platforms; editorial-control exception |
| Digital Omnibus on AI (EU) 2026/1744 | EU | Directly applicable amending regulation | Amends AI Act timelines | Adopted 8 July 2026 (document date); in force 27 July 2026 | Reported to leave the 2 August 2026 Article 50 date unchanged; amending text not read (open item) |
| Cyber Resilience Act (EU) 2024/2847 | EU | Directly applicable regulation | Manufacturer vulnerability and incident reporting; essential requirements | In force 10 December 2024; reporting 11 September 2026; main obligations 11 December 2027 | Broadcast and production equipment, connected televisions, set-top boxes, apps and games as products |
| Radio Equipment Directive delegated act (EU) 2022/30 | EU | Delegated regulation | Cybersecurity, data and fraud essential requirements | Applied August 2025; repealed with effect 11 December 2027 | Connected radio equipment until CRA applies |
| Digital Services Act (EU) 2022/2065 | EU | Directly applicable regulation | Systemic risk assessment including media freedom and electoral processes | Published 27 October 2022; application dates not shown in the sources reviewed | Largest platforms distributing media content |
| GDPR (EU) 2016/679 | EU and EEA | Directly applicable regulation | Security; breach notification within 72 hours; communication to individuals | Applies 25 May 2018 | Subscriber, audience, player, donor and ticket-holder data; Article 85 lets national law derogate for journalistic and artistic purposes |
| Audiovisual Media Services Directive 2010/13/EU as amended by (EU) 2018/1808 | EU | Binding directive via national law | Audiovisual and video-sharing platform content rules | Transposition of the amendment by 19 September 2020 (date from a Tier 3 tracker) | Broadcasters and on-demand services; cyber relevance not assessed |
| Live-event piracy Recommendation (EU) 2023/1018 | EU | Non-binding recommendation | Notice and injunction cooperation | Stock-take 20 November 2025 | Content-piracy context only |
| European Democracy Shield | EU | Commission Communication | Funding, coordination, fact-checking | 12 November 2025 | Media resilience support; no binding duties |
| UK NIS Regulations 2018 | UK | Binding regulations | Essential services; digital services limited to marketplaces, search engines, cloud | In force 10 May 2018 | Media and culture outside scope except as providers |
| Cyber Security and Resilience Bill | UK | Bill at Lords report stage | Would add managed service providers, data centres, designated suppliers; 24/72-hour reporting | Lords report stage at 14 October 2026; no Royal Assent | Could reach media suppliers once enacted |
| Telecoms security framework (Communications Act 2003 ss. 105A-105Z; Security Measures Regulations 2022) | UK | Binding duties (Act and 2022 Regulations); code of practice is statutory guidance | Security duties for providers of public electronic communications networks and services; code tiers set implementation expectations | In force 1 October 2022; code version 1.1 dated 14 July 2026 | Broadcast transmission in scope only if it is a public electronic communications network; not confirmed |
| Media Act 2024 | UK | Binding legislation | Public service broadcasting and on-demand regulation | Royal Assent 24 May 2024; staged commencement not reviewed | Broadcasters; no cyber obligations in the text read |
| Online Safety Act 2023 | UK | Binding legislation | Illegal content and child safety duties for platforms | Illegal content duties enforceable 17 March 2025 | Platforms distributing media content, not outlets as such |
| National Security Act 2023, section 13 | UK | Binding criminal law | Foreign interference offences; no duties on media | In force 20 December 2023; amended from 8 July 2026 | State-linked interference targeting media |
| Consumer connectable product security regime | UK | Binding regulations | No universal default passwords; vulnerability and update information | Applies 29 April 2024 | Connected televisions and streaming devices where in scope |
| Data Protection Act 2018 special purposes | UK | Binding legislation | Exempts listed UK GDPR provisions; security and regulator notification not listed | Act dated 23 May 2018 | Newsrooms and arts bodies |
| Ransomware payment proposals | UK | Proposals; no legislation evidenced | Payment ban for public bodies and regulated operators; reporting | Government response 22 July 2025 | Publicly funded cultural bodies if enacted |
| Government Cyber Action Plan | UK | Government plan | Accountability of arm's-length bodies to lead departments | 6 January 2026 | DCMS-sponsored museums and libraries |
| SEC Form 8-K Item 1.05 | US (comparative) | Binding for SEC registrants | Material incident disclosure within four business days | Compliance from 18 December 2023 | Listed media, entertainment and games groups |
| FCC 26-38 alerting order | US (comparative) | Adopted rule; enforceable 60 days after Federal Register publication (publication status at cut-off unconfirmed) | Passwords, patching and segmentation for content-insertion equipment | Released 29 June 2026 | Broadcasters and cable operators |
| COPPA Rule amendments | US (comparative) | Binding rule | Children's data obligations | Federal Register publication 22 April 2025; effective and compliance dates not shown in the source read | Games and children's services |
| SOCI Act 2018, s. 12E (infrastructure security) | Australia (comparative) | Binding legislation | Infrastructure security regime naming broadcasting assets | Compilation dated June 2026 (not a commencement date; s. 12E commencement not confirmed) | Broadcast transmission operators meeting site or prescription tests; obligations not confirmed |

[EUR-Lex - NIS2 Directive][48] [European Commission - NIS2 FAQs][49] [European Commission - Entity resilience policy page][50] [European Commission - European Media Freedom Act page][51] [European Commission - Political advertising rules apply][52] [European Commission - AI Act Article 50 FAQ][53] [EUR-Lex - Digital Omnibus on AI][54] [European Commission - Cyber Resilience Act page][55] [European Commission - Radio Equipment Directive page][56] [EUR-Lex - Digital Services Act][73] [European Commission - Digital Services Act page][57] [EUR-Lex - GDPR][60] [European Commission - Live-event piracy Recommendation stock-take][58] [European Commission - European Democracy Shield][59] [legislation.gov.uk - NIS Regulations 2018][63] [UK Parliament - Cyber Security and Resilience Bill][61] [DSIT - Cyber Security and Resilience Bill summary][62] [OPSS - Consumer connectable product security][64] [legislation.gov.uk - DPA 2018 special purposes][65] [Home Office - Ransomware proposals consultation][66] [Goodwin - UK ransomware strategy alert][67] [DSIT - Government Cyber Action Plan][68] [SEC - Cyber disclosure compliance guide][69] [FCC - FCC 26-38 alerting systems order][14] [FTC - COPPA final rule amendments][70] The table records legal status, obligation type and date basis from the primary instrument or official page for each regime (Observed). [EUR-Lex - Digital Omnibus on AI][54] [European Commission - AI Act Article 50 FAQ][53] [iubenda - AI Omnibus and Article 50][85] The Digital Omnibus on AI entered into force on 27 July 2026; the Omnibus is reported to have left the 2 August 2026 application of Article 50 unchanged, and Commission guidance and commentary report a transition to 2 December 2026 for Article 50(2) marking by systems placed on the market before 2 August 2026 (Observed; amending text not read, so whether the transition originates in the Omnibus is an open item; commentary Tier 3). [EUR-Lex - GDPR][60] [GDPR-Text - Article 85][83] GDPR Article 85 requires Member States to provide exemptions or derogations, where necessary, from Chapters II to VII and IX for journalistic, academic, artistic and literary purposes, so newsroom security and breach-notification duties can differ by Member State (Observed; text read via an unofficial verbatim reproduction, Tier 3; national laws not surveyed). [legislation.gov.uk - DPA 2018 special purposes][65] By contrast, the UK special purposes exemption does not list the security duty or breach notification to the regulator (Observed). [DSIT - Telecommunications Security Code of Practice 2026][78] [Ofcom - Arqiva electronic communications network statement][79] UK telecoms security duties attach to providers of public electronic communications networks and services, with code-of-practice tiers setting implementation expectations; Ofcom has recorded that the main terrestrial transmission operator provides an electronic communications network supporting television and radio broadcasting, but whether that network is a public network within the duties is not confirmed (Observed; Ofcom record historical). [legislation.gov.uk - Media Act 2024][76] [GOV.UK - Online Safety Act explainer][77] [legislation.gov.uk - National Security Act 2023 s13][75] The Media Act 2024 carries no cyber duties in the text reviewed, the Online Safety Act regulates platforms rather than outlets, and the National Security Act 2023 criminalises foreign interference without placing duties on media (Observed). [Home Affairs - Infrastructure asset definition paper][80] [Federal Register of Legislation - SOCI Act 2018 compilation][81] Australia is the only jurisdiction found whose infrastructure security law names broadcasting assets, defined by prescribed sites, a 50-site threshold or prescribed entities (Observed; comparative). [Digital Policy Alert - AVMSD transposition deadline][82] The Audiovisual Media Services Directive transposition date is taken from a policy tracker (Tier 3). [Hunton - CIRCIA timing][72] Legal commentary expected a final US cyber incident reporting rule for infrastructure operators in September 2026; its status at the cut-off is unconfirmed (Tier 3; context only). Interpretation: for most sector entities, cyber obligations are product, data-protection, media-specific and contractual rather than horizontal cyber regulation; the main in-period movements were AI Act transparency, CRA reporting and the FCC rule.

### Voluntary frameworks (not binding law)

[EBU - R 148 networked media equipment tests][71] EBU R 148 defines minimum security tests for networked media equipment; it was published in April 2018 and has not been updated since (Observed). ISO/IEC 27001 and 27002, ISO/IEC 27036 (supplier relationships), ISO 14721 (digital preservation reference model), NIST Cybersecurity Framework 2.0, CIS Controls, EBU R 143, AMWA NMOS and SMPTE guidance for IP production, the MPA Trusted Partner Network, C2PA content-provenance specifications, ETSI EN 303 645, PCI DSS v4.0.1 and IFLA and ICOM guidance are used in Chapter 7 only as reference vocabularies; this run did not review their texts and makes no claim about their specific requirements.

### Forward monitoring horizon

| **Date or window** | **Item to monitor** |
| --- | --- |
| October-December 2026 | Ticketing provider and French investigation outcomes; any CNIL action |
| Late 2026 | UK Cyber Security and Resilience Bill report stage outcome and Royal Assent |
| From 11 September 2026 | CRA vulnerability and incident reports from broadcast, consumer and games product makers |
| 2 December 2026 | AI Act Article 50(2) marking applies to systems placed on the market before 2 August 2026 |
| 60 days after Federal Register publication | FCC content-insertion equipment requirements become enforceable |
| Autumn 2026 - end 2026 | British Library UK Web Archive access and electronic legal deposit restoration |
| Ongoing | Dresden investigation; DDoS and FIMI campaigns around elections and major live events |

## Mitigation Strategies & Security Framework

Actions below are sector-informed management priorities derived from the public evidence. They are not statements about any institution's control gaps. Role types are generic.

### Evidence-linked action table

| **Exposure** | **Operational vulnerability** | **Control objective** | **Action or challenge question** | **Role type** | **Horizon** |
| --- | --- | --- | --- | --- | --- |
| A1 Shared front-of-house platforms | Ticketing, payment, CDN and cloud single points of failure | Know and limit concentration | Map which ticketing, payment, CDN and cloud providers the largest media and cultural counterparties depend on; ask for tested fallback sales and delivery channels | 1LoD sector risk owner | 0-6 months |
| A2 Broadcast content insertion and signal paths | Default passwords and remote access on encoders, studio-transmitter links, alerting and satellite uplinks | Prevent hijacked output and false alerts | Ask broadcast counterparties for evidence of password, patching and segmentation baselines equivalent to the FCC rule | 1LoD operational resilience | 0-6 months |
| A3 Ransomware against institutions and publishers | Corporate IT shared with ticketing, shop, newsroom and playout | Segregate and recover | Ask whether security, building and playout systems are segregated from corporate IT and whether recovery of transactional channels is tested | 1LoD third-party risk | 3-12 months |
| A4 Payment and phishing follow-on | Exposed ticket-holder, subscriber and donor contact data | Stop payment diversion and card fraud | Monitor fraud typologies after sector ticketing or subscriber exposures; confirm out-of-band verification in merchant and donor payment flows | 1LoD payments and fraud | 0-3 months |
| A5 Brand impersonation and synthetic media | Spoofed outlets, fabricated brands, AI-generated content | Protect provenance and trust | Ask media counterparties how they detect impersonation and meet AI Act transparency duties | 1LoD sector risk owner | 6-12 months |
| A6 Long recovery tails and funding | Legacy estates and thin insurance | Align credit and funding expectations | Ask leveraged media borrowers and public cultural counterparties about recovery time objectives, insurance cover and waiver triggers | 1LoD credit | 6-12 months |

| **Exposure** | **Evidence of completion** | **Residual dependency** | **External monitoring trigger** |
| --- | --- | --- | --- |
| A1 Shared front-of-house platforms | Dependency map for top sector counterparties; fallback test records | Providers outside counterparty control | Provider outage or breach notice; prosecutor statement naming a supplier |
| A2 Broadcast content insertion and signal paths | Baseline attestation for content-insertion equipment | Legacy devices that cannot be patched | Regulator warning on content-insertion devices; satellite hijack report |
| A3 Ransomware against institutions and publishers | Segregation and restoration test evidence | Shared public-sector IT | Sector incident notice; ransomware advisory naming media |
| A4 Payment and phishing follow-on | Fraud typology monitoring and verification procedure | Compromised legitimate customer accounts | Ticketing or subscriber data exposure notice |
| A5 Brand impersonation and synthetic media | Provenance and labelling procedure | Platform distribution outside counterparty control | EEAS or national FIMI alert; election calendar |
| A6 Long recovery tails and funding | Recovery objectives, insurance schedule, covenant terms | Public-funding decisions | Waiver or amendment request; annual report recovery disclosures |

[CMN - Ticketing personal data notice][8] [AWS - US-EAST-1 post-event summary][38] [Cloudflare - 18 November 2025 outage report][39] [FCC - FCC 26-38 alerting systems order][14] [Radio Ink - FCC warning after Houston hijack][13] [Saxon culture ministry - SKD cyberattack release, 22 January 2026][1] [SKD - Recovery update, 29 January 2026][3] [ActuaLitte - Vivaticket attack on cultural institutions][9] [L'Echo touristique - CMN ticketing cyberattack][10] [EEAS - 4th FIMI Threats Report][43] [European Commission - AI Act Article 50 FAQ][53] [Lee Enterprises - Q3 FY2026 Form 10-Q][31] [British Library - Annual Report 2025/26][34] [DSIT - Cyber Security Breaches Survey 2025/26][44] Each action links to an exposure evidenced in Chapters 2 to 6: A1 to the ticketing, cloud and CDN evidence; A2 to the FCC rule and stream hijacks; A3 to Dresden; A4 to the ticketing data exposure; A5 to EEAS impersonation findings and AI Act Article 50; A6 to Lee's waivers, British Library recovery and UK charity insurance coverage (Action).

### Framework reference mapping (voluntary)

| **Action** | **NIST CSF 2.0 function** | **Other voluntary references** |
| --- | --- | --- |
| A1 Shared front-of-house platforms | Govern (supply-chain risk) and Identify | ISO/IEC 27036; PCI DSS v4.0.1 |
| A2 Broadcast content insertion and signal paths | Protect and Detect | EBU R 148 and R 143; AMWA NMOS; SMPTE |
| A3 Ransomware against institutions and publishers | Protect, Respond and Recover | ISO/IEC 27001 and 27002; CIS Controls; ISO 14721 for archives |
| A4 Payment and phishing follow-on | Protect and Detect | PCI DSS v4.0.1 |
| A5 Brand impersonation and synthetic media | Govern and Detect | C2PA content provenance |
| A6 Long recovery tails and funding | Govern and Recover | IFLA and ICOM guidance for cultural bodies |

[EBU - R 148 networked media equipment tests][71] The mapping is an analyst reference aid; frameworks are voluntary and are not presented as legal requirements (Judgement).

### 1LoD and Risk Committee challenge questions

- Which ticketing, payment, CDN and cloud providers do our largest media, live-event and cultural counterparties share, and what evidence shows they can sell and deliver without them for a week?
- Do broadcast counterparties meet a password, patching and segmentation baseline for content-insertion and alerting equipment comparable to the June 2026 FCC rule?
- How would a ten-day loss of online ticketing at a shared provider, as in March 2026, show up in merchant-acquiring volumes and fraud alerts?
- Which leveraged media borrowers would need covenant or payment waivers after a multi-month advertising disruption, as Lee did?
- How do media counterparties detect impersonation of their brands and meet AI Act transparency duties from August 2026?

### Monitoring triggers

- A supplier incident notice or prosecutor statement naming a ticketing, playout, newsroom or collection-management provider.
- A regulator warning or hijack report affecting broadcast content-insertion or satellite paths.
- DDoS or FIMI alerts naming media ahead of elections or major live events.
- Waiver, amendment or liquidity requests from media borrowers after an incident.
- Legal milestones: UK bill Royal Assent; AI Act Article 50(2) on 2 December 2026; FCC compliance date; first CRA reporting statistics.

## Methodology and Evidence Limitations

**Method.** Wide discovery across broadcasters, transmission and satellite distribution, news publishers, streaming, music and rights, film and games, advertising technology, ticketing and venues, museums, libraries and archives, media technology vendors, CDNs and managed service providers, using English, French, German, Dutch and Italian queries, followed by primary-source research. Sources were classified as Tier 1 (official, legal, regulatory, court, affected organisation, government), Tier 2 (independent research with disclosed method) or Tier 3 (media and discovery). Tier 3 sources are never the sole support for a material finding; where Tier 3 detail is shown it is labelled. Publication date and observation period are recorded separately; repeated reporting of one incident is counted once. Leaked data, leak-site content, stolen or pirated content and broadcast hijack content were not accessed or reproduced. All sources were accessed on 15 October 2026.

**Evidence limitations.**

- No EU or UK entity disclosed a quantified cyber cost for an in-period incident; quantified cases are US and Japanese with earlier attack dates.
- No EU or UK broadcaster incident had a retrievable Tier 1 statement; RTV Noord's own pages could not be retrieved.
- Shared ticketing incident detail (date, scale, data) rests on Tier 3 relays of institution statements; Tier 1 sources confirm only the provider dependency and one undated outage notice, so the event is not counted as a named incident.
- The live-events group breach is evidenced by a notification register and an untested complaint; neither establishes root cause, attacker or total population.
- Dresden cost, data and attribution were not disclosed; the attack duration comes from a ministerial answer relayed by media.
- DDoS and FIMI benchmarks measure targeting, not impact; Cloudflare data reflect one network.
- No in-period Tier 1 or Tier 2 incident was found for advertising technology, audience measurement, post-production and visual effects, or collective rights management.
- Partly reviewed: Media Act 2024 (Part 1 only), Australian infrastructure security law (section headings and a 2021 consultation paper), UK telecoms security rules (scope and legal status; broadcast transmission status unconfirmed) and the Digital Omnibus on AI (metadata and commentary). Not reviewed in primary text: Audiovisual Media Services Directive, Ofcom broadcasting licence conditions under the Communications Act 2003, national GDPR Article 85 laws, ePrivacy national rules, the UK Data (Use and Access) Act 2025 commencement and US state breach, video privacy and incident-reporting (CIRCIA) rules beyond the items cited.
- National NIS2 transpositions were not surveyed; [Advisera - Italian NIS2 decree overview][84] commentary on Italy's decree reports that entities carrying out activities of cultural interest can be classified as important entities under specific conditions, which is not confirmed in primary text here (Tier 3).
- Information-integrity, public-trust and heritage effects are not monetised; no such effect is attributed to a cyber incident in this report.
- No numerical probabilities are assigned; scenarios are stress narratives.

**Confidence.** Confidence is high for the Dresden, FCC, court and filing facts and for the status of NIS2, CER, CRA, the UK NIS Regulations, the UK bill and the special purposes exemption; medium-high for the remaining regulatory rows, with the Digital Omnibus effect on Article 50, the Audiovisual Media Services Directive, national Article 85 laws and UK telecoms security scope recorded as open items; medium for the principal judgements; and low for the shared ticketing scale and for scenario durations.

## References

Each entry: number, source and title, publisher, publication date and basis, access date, tier, temporal class, observation period, locator. URLs are given in the reference definitions below this list.

- [1] Saxon culture ministry - SKD cyberattack release, 22 January 2026. Saxon State Ministry for Culture and Tourism (Medienservice Sachsen) on behalf of SKD, Cyberangriff auf Staatliche Kunstsammlungen Dresden (Cyberattack on the Dresden State Art Collections). Published 2026-01-22 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 21-22 January 2026. Locator: Press release body (PDF): incident, affected services, unaffected security network, investigation, crisis team. Source ID S-001.

- [2] SKD - Cyberattack press release. Staatliche Kunstsammlungen Dresden (SKD), Cyberattack on the Dresden State Art Collections (press release). Published 2026-01-22 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 21-22 January 2026. Locator: Press release dated 22 January 2026, 13:03; sections on affected and unaffected systems. Source ID S-002.

- [3] SKD - Recovery update, 29 January 2026. Staatliche Kunstsammlungen Dresden via Medienservice Sachsen, Webseite der Staatlichen Kunstsammlungen Dresden nach Cyberangriff wieder erreichbar (Website reachable again after cyberattack). Published 2026-01-29 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 21-29 January 2026. Locator: Release of 29 January 2026, 13:04: website since 26 January, telephone, online shop, cash payment, investigation. Source ID S-003.

- [4] Prosecutor and LKA Saxony - SKD investigation release. Generalstaatsanwaltschaft Dresden and Landeskriminalamt Sachsen (joint release), Joint media release on the cyberattack on the IT infrastructure of the Staatliche Kunstsammlungen Dresden. Published 2026-02-19 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 21 January - 19 February 2026. Locator: Release body: special investigation commission set up by LKA under prosecutor direction. Source ID S-004.

- [5] t-online - SKD special commission report. t-online (Dresden regional edition), Dresden: Zwinger-Raub geplant? Was ueber die Arbeit der SKD-Soko bekannt ist. Published 2026-02-20 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: January-February 2026. Locator: Article body: online ticket booking restored; Bild report on planned theft; LKA response. Source ID S-005.

- [6] dpa via Volksstimme - SKD attack duration. Volksstimme (dpa wire), Cyberkriminalitaet: Cyberangriff auf SKD dauerte mehrere Tage. Published 2026-07-28 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: 17-21 January 2026; investigation status July 2026. Locator: Article body citing the Saxon Justice Ministry answer to a Kleine Anfrage by MP Rico Gebhardt. Source ID S-006.

- [7] Musee Guimet - Online ticketing unavailable notice. Musee national des arts asiatiques - Guimet, Museum online ticketing service unavailable. Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: March 2026 (inferred from related reporting; page undated). Locator: Notice body: online reservations unavailable; FNAC ticket office and on-site purchase. Source ID S-007.

- [8] CMN - Ticketing personal data notice. Centre des monuments nationaux (official ticketing site), Donnees personnelles (personal data notice). Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: Current page. Locator: Section naming the ticketing provider (Vivaticket S.p.A.) as host and transmitter of ticketing data. Source ID S-008.

- [9] ActuaLitte - Vivaticket attack on cultural institutions. ActuaLitte, Cyberattaque : des musees et institutions culturelles perturbes, dont la BnF. Published 2026-03-19 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: 2-19 March 2026. Locator: Article body: affected institutions, CMN reopening 12 March, notifications, prosecutor investigation. Source ID S-009.

- [10] L'Echo touristique - CMN ticketing cyberattack. L'Echo touristique, Billetterie : les monuments nationaux victimes d'une cyberattaque. Published 2026-03-08 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: 2-8 March 2026. Locator: Article body quoting the CMN customer email: ransomware at ticketing provider on 2 March 2026; data categories. Source ID S-010.

- [11] Lyon Mag - Lyon municipal museums ticketing attack. Lyon Mag, La billetterie des musees municipaux de Lyon victime d'une cyber-attaque. Published 2026-03-11 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: March 2026. Locator: Article body: four municipal museums without online ticketing; data categories; city statement. Source ID S-011.

- [12] SC Media - Vivaticket platform breach brief. SC Media, Thousands of European tourist sites impacted by ticketing platform breach. Published 2026-04-06 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: Early March - April 2026. Locator: Brief body: nearly 3,500 sites; Irec SAS subsidiary; RansomHouse claim; Vivaticket statement on card data. Source ID S-012.

- [13] Radio Ink - FCC warning after Houston hijack. Radio Ink, FCC Issues Cybersecurity Warning After Houston Barix Hack. Published 2025-12-02 (exact). Accessed 2026-10-15. Tier 3. Temporal class: H2 prior. Observation period: 22-23 November 2025. Locator: Article body: KFNC hijack during NFL coverage; station investigation; FCC bureau warning and recommended measures. Source ID S-013.

- [14] FCC - FCC 26-38 alerting systems order. US Federal Communications Commission, Modernization of the Nation's Alerting Systems - Report and Order and Further Notice of Proposed Rulemaking (FCC 26-38). Published 2026-06-29 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Adopted 25 June 2026; released 29 June 2026. Locator: Report and Order para 16 and n.61 (recent hijack incidents incl. Houston, 23 November 2025); adopted requirements (passwords, patching, segmentation); compliance timing; no incident-reporting requirement. Source ID S-014.

- [15] SDNY - Anna's Archive preliminary injunction. US District Court, Southern District of New York (via CourtListener RECAP), Atlantic Recording Corp. et al. v. Anna's Archive, No. 26-cv-00002 (JSR), Document 17 - Preliminary Injunction. Published 2026-01-20 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: December 2025 - January 2026. Locator: Preliminary Injunction: findings on likely infringement by scraping, irreparable harm, worldwide injunction, third-party compliance. Source ID S-015.

- [16] Music Business Worldwide - Anna's Archive lawsuit. Music Business Worldwide, Record labels, Spotify sue pirate group Anna's Archive over scraping and brazen theft of millions of tracks. Published 2026-01-21 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: December 2025 - January 2026. Locator: Article body: claims, alleged scale, Spotify statement, relief sought. Source ID S-016.

- [17] MusicTech - Anna's Archive judgment. MusicTech, Judge orders Anna's Archive to pay 322 million dollars for scraping 86 million tracks from Spotify. Published 2026-04-23 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: Judgment 14 April 2026. Locator: Article body: judgment amount, date, distribution, collectability. Source ID S-017.

- [18] Geo News - Satellite feed hijack statement. Geo News (Jang Media Group), Repeated attempts to hack Geo News foiled, channel disowns malicious broadcast message. Published 2026-03-01 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 28 February - 1 March 2026. Locator: Statement body: repeated attempts over 24 hours; satellite feed hacked at 9 pm bulletin; request for investigation. Source ID S-018.

- [19] Dawn - CERT investigation of TV channel hacks. Dawn, CERT investigates cyberattacks on TV channels, websites. Published 2026-03-03 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: 1-3 March 2026. Locator: Article body: National CERT formal investigation; uplink hypothesis; platforms restored. Source ID S-019.

- [20] Digital Rights Monitor - Pakistani channel takeovers. Digital Rights Monitor, Several Pakistani TV channels briefly taken over by unauthorised broadcasts. Published 2026-03-02 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: 1 March 2026. Locator: Article body: Geo News, Samaa TV and ARY News; no regulator statement; no claim of responsibility. Source ID S-020.

- [21] TechCrunch - Anodot integration breach. TechCrunch, Hack at Anodot leaves over a dozen breached companies facing extortion. Published 2026-04-13 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: 4-13 April 2026. Locator: Article body: stolen integration tokens, at least a dozen companies, Rockstar Games statement. Source ID S-021.

- [22] Hasbro - Form 8-K, 1 April 2026. Hasbro, Inc. (SEC EDGAR), Form 8-K (Item 8.01) dated 1 April 2026. Published 2026-04-01 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 28 March - 1 April 2026. Locator: Item 8.01: unauthorized network access identified 28 March 2026; systems offline; interim measures for several weeks. Source ID S-022.

- [23] Hasbro - Q1 2026 results release. Hasbro, Inc. (SEC EDGAR), Exhibit 99.1 - First quarter 2026 results release. Published 2026-05-20 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Q1 2026. Locator: Release text on the IT incident: containment, legal and remediation costs from Q2, insurance claims. Source ID S-023.

- [24] BleepingComputer - SoundCloud breach. BleepingComputer, SoundCloud confirms breach after member data stolen, VPN access disrupted. Published 2025-12-15 (exact). Accessed 2026-10-15. Tier 3. Temporal class: H2 prior. Observation period: December 2025. Locator: Article body: SoundCloud statement on ancillary dashboard access, data types, DoS, VPN disruption. Source ID S-024.

- [25] NOS - RTV Noord hack. NOS, Privegegevens gestolen bij hack RTV Noord, 'was geen gerichte aanval'. Published 2025-11-14 (exact). Accessed 2026-10-15. Tier 3. Temporal class: H2 prior. Observation period: 6-14 November 2025. Locator: Article body: employee data stolen; untargeted ransomware; ransom refused; radio continuity. Source ID S-025.

- [26] NL Times - RTV Noord broadcast disruption. NL Times (ANP), RTV Noord hack (broadcast and platform disruption). Published 2025-11-07 (exact). Accessed 2026-10-15. Tier 3. Temporal class: H2 prior. Observation period: 6-7 November 2025. Locator: Article body: discovery before morning broadcast; radio on CDs and vinyl; website and app workaround; TV normal. Source ID S-026.

- [27] Artribune - Uffizi incident claims and response. Artribune, L'attacco hacker agli Uffizi. Le rivelazioni del Corriere della Sera e la risposta di Simone Verde. Published 2026-04-03 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: January-April 2026. Locator: Article body separating Corriere claims from the director's statements; ACN investigation. Source ID S-027.

- [28] t-online - Leipzig cultural enterprises attack. t-online (Leipzig regional edition, dpa), Cyberangriff trifft staedtische Kulturbetriebe in Leipzig. Published 2026-07-20 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: July 2026. Locator: Article body: municipal IT provider Lecos; Gewandhaus, Opera, Schauspiel, music school; directory data taken. Source ID S-028.

- [29] Quotenmeter - Cyberattacks on journalism. Quotenmeter, Die neue Druckmaschine steht im Rechenzentrum: Wenn Cyberangriffe den Journalismus treffen. Published 2026-09-10 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: August-September 2026. Locator: Article body: Mediengruppe Presse Nord overload attack end of August 2026; editor statement. Source ID S-029.

- [30] Lee Enterprises - FY2025 Form 10-K. Lee Enterprises, Inc. (SEC EDGAR), Form 10-K for fiscal year ended 28 September 2025. Published 2025-11-26 (exact). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: Fiscal year to 28 September 2025; incident 3 February 2025. Locator: Item 1A Risk Factors; Item 1C Cybersecurity (Material Effects); Item 7 Executive Overview, Operating Revenue, Operating Activities and Liquidity. Source ID S-030.

- [31] Lee Enterprises - Q3 FY2026 Form 10-Q. Lee Enterprises, Inc. (SEC EDGAR), Form 10-Q for the quarter ended 28 June 2026. Published 2026 (year only). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Nine months to 28 June 2026. Locator: Note 8 Debt (waivers); Consolidated Statements of Income (insurance proceeds). Source ID S-031.

- [32] KADOKAWA - FY2025/3 results release. KADOKAWA CORPORATION, KADOKAWA, 2025年3月期 通期決算を発表 (FY ended March 2025 full-year results). Published 2025-05 (month only). Accessed 2026-10-15. Tier 1. Temporal class: H1 prior. Observation period: Fiscal year to 31 March 2025; attack June 2024. Locator: Release text on cyberattack effects: group sales and operating profit, special loss, Web Services and domestic print publishing. Source ID S-032.

- [33] British Library - Annual Report 2024/25. British Library (via GOV.UK), British Library Annual Report and Accounts 2024/25. Published 2025-07-15 (exact). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: 1 April 2024 - 31 March 2025. Locator: pp. 4, 9, 13, 32-39 (recovery, Rebuild and Renew, DCMS support, income effects). Source ID S-033.

- [34] British Library - Annual Report 2025/26. British Library (HC 328, via GOV.UK), British Library Annual Report and Accounts 2025/26. Published 2026-07-14 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 1 April 2025 - 31 March 2026. Locator: pp. 4, 7, 11, 32-39 (catalogue, Library Services Platform, legal deposit, UK Web Archive, KPIs). Source ID S-034.

- [35] Museums Association - British Library recovery. Museums Association, New leadership for British Library as cyber attack recovery continues. Published 2026-09-22 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: September 2026. Locator: Article body: catalogues still unavailable to the public. Source ID S-035.

- [36] Toronto Auditor General - Toronto Public Library audit. Toronto Auditor General, Cybersecurity Audit of Toronto Public Library. Published 2026-05-15 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Audit following the October 2023 attack. Locator: pp. 1-4: scope, confidential attachment, cost not determinable. Source ID S-036.

- [37] Cour des comptes - Louvre public establishment summary. Cour des comptes (France), The public establishment of the Louvre Museum - financial years 2018-2024 (summary). Published 2025-11 (month only). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: Financial years 2018-2024. Locator: Summary pp. 4-5 (maintenance and security underinvestment), p. 9 recommendations 9 and 10. Source ID S-037.

- [38] AWS - US-EAST-1 post-event summary. Amazon Web Services, Summary of the Amazon DynamoDB Service Disruption in the Northern Virginia (US-EAST-1) Region. Published 2025-10 (month only). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: 19-20 October 2025. Locator: Summary body: root cause, timeline, affected AWS services, remediation. Source ID S-038.

- [39] Cloudflare - 18 November 2025 outage report. Cloudflare, Cloudflare outage on November 18, 2025. Published 2025-11-18 (exact). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: 18 November 2025. Locator: Post body: root cause, UTC timeline, affected services, statement that no attack was involved. Source ID S-039.

- [40] PPC Land - AWS outage effects. PPC Land, Amazon outage breaks the internet: Snapchat, Fortnite, banks go dark. Published 2025-10 (month only). Accessed 2026-10-15. Tier 3. Temporal class: H2 prior. Observation period: 20 October 2025. Locator: Article body: gaming services reported affected; company acknowledgements. Source ID S-040.

- [41] ENISA - Threat Landscape 2026. European Union Agency for Cybersecurity (ENISA), ENISA Threat Landscape 2026. Published 2026-09 (month only). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 1 January - 31 December 2025. Locator: p. 9 (method, 8,257 incidents); p. 14 (top sectors, FIMI-aligned hacktivism); pp. 25-26 (business services, broadcast media, hacktivist claims). Source ID S-041.

- [42] Cloudflare - DDoS Threat Report H1 2026. Cloudflare (Cloudforce One), Cloudflare DDoS Threat Report H1 2026. Published 2026-08-11 (exact). Accessed 2026-10-15. Tier 2. Temporal class: current. Observation period: 1 January - 30 June 2026. Locator: Sections 'Most-attacked industries' and 'Media under siege: the most attacked industry'. Source ID S-042.

- [43] EEAS - 4th FIMI Threats Report. European External Action Service (EEAS), 4th EEAS Report on Foreign Information Manipulation and Interference Threats. Published 2026-03-12 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 1 January - 31 December 2025. Locator: pp. 7, 10 (540 incidents), 11 (targets incl. media sector), 15 (elections), 29-31 (impersonation of outlets). Source ID S-043.

- [44] DSIT - Cyber Security Breaches Survey 2025/26. Department for Science, Innovation and Technology and Home Office (GOV.UK), Cyber security breaches survey 2025/2026. Published 2026-04-30 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Fieldwork August-December 2025. Locator: Summary and sector findings: prevalence for businesses, charities and information and communication sector; charity governance and insurance. Source ID S-044.

- [45] Eurostat - EU cultural employment 2025. Eurostat, EU cultural sector in 2025: 8.9 million people employed. Published 2026-07-10 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 2025. Locator: News body: employment count, share and definition. Source ID S-045.

- [46] DCMS - Sectors GVA 2024 (provisional). Department for Culture, Media and Sport (GOV.UK), DCMS Sectors Economic Estimates: Gross Value Added 2024 (provisional). Published 2026-02-05 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Calendar year 2024. Locator: Headline GVA for creative industries and cultural sector; overlap note. Source ID S-046.

- [47] Europol - Operation Eastwood. Europol, Global operation targets NoName057(16) pro-Russian cybercrime network. Published 2025-07 (month only). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: 14-17 July 2025. Locator: Press release body and metadata: Operation Eastwood, infrastructure disruption, arrest warrants. Source ID S-047.

- [48] EUR-Lex - NIS2 Directive. EUR-Lex (Official Journal of the EU), Directive (EU) 2022/2555 (NIS 2 Directive) - document metadata. Published 2022-12-27 (exact). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: In force 16 January 2023. Locator: ELI metadata: document date 14 December 2022, publication 27 December 2022, entry into force 16 January 2023. Source ID S-048.

- [49] European Commission - NIS2 FAQs. European Commission (Shaping Europe's digital future), Directive on measures for a high common level of cybersecurity across the Union (NIS2 Directive) - FAQs. Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: Current page. Locator: FAQs 'Which sectors and types of entities will the NIS2 cover?', 'What are the key elements of the NIS2 Directive?', jurisdiction FAQ. Source ID S-049.

- [50] European Commission - Entity resilience policy page. European Commission (DG Migration and Home Affairs), European Commission - Entity resilience policy page. Published 2026-01-13 (page update). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Current page. Locator: Sections on the CER Directive: eleven sectors; key dates including 17 July 2026 identification. Source ID S-050.

- [51] European Commission - European Media Freedom Act page. European Commission, European Media Freedom Act. Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: Current page. Locator: Page body: entry into force, application of most provisions on 8 August 2025, protection of journalistic sources against intrusive surveillance software. Source ID S-051.

- [52] European Commission - Political advertising rules apply. European Commission, New EU rules on political advertising come into effect. Published 2025-10-10 (exact). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: From 10 October 2025. Locator: News body: application date, labelling, targeting consent, third-country sponsor restriction, exclusions. Source ID S-052.

- [53] European Commission - AI Act Article 50 FAQ. European Commission (Shaping Europe's digital future), Transparency obligations under Article 50 of the AI Act (FAQ). Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: Current page. Locator: FAQ: application 2 August 2026; Article 50(2) grace to 2 December 2026; deployer duties; editorial-control and artistic exceptions. Source ID S-053.

- [54] EUR-Lex - Digital Omnibus on AI. EUR-Lex (Official Journal of the EU), Regulation (EU) 2026/1744 (Digital Omnibus on AI) - document metadata. Published 2026-07-08 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Entry into force 27 July 2026. Locator: EUR-Lex metadata: adoption 8 July 2026; first entry into force 27 July 2026. Source ID S-054.

- [55] European Commission - Cyber Resilience Act page. European Commission (Shaping Europe's digital future), Cyber Resilience Act. Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: Current page. Locator: Key dates; scope examples (apps, computer programs, computer games). Source ID S-055.

- [56] European Commission - Radio Equipment Directive page. European Commission (DG GROW), Radio Equipment Directive (RED). Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: Current page. Locator: Section on cybersecurity delegated act 2022/30 (application August 2025) and repeal by 2026/339 effective 11 December 2027. Source ID S-056.

- [57] European Commission - Digital Services Act page. European Commission (Shaping Europe's digital future), The Digital Services Act. Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: Current page. Locator: Systemic risks and enforcement sections. Source ID S-057.

- [58] European Commission - Live-event piracy Recommendation stock-take. European Commission (Shaping Europe's digital future), Commission takes stock of the progress made in the take up of the measures of its 2023 Recommendation on combatting online piracy of sports and other live events. Published 2025-11-20 (exact). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: 2023-2025. Locator: News body: uptake, impact finding, further action under consideration. Source ID S-058.

- [59] European Commission - European Democracy Shield. European Commission (DG Enlargement and Eastern Neighbourhood), European Democracy Shield and EU Strategy for Civil Society pave the way for stronger and more resilient democracies. Published 2025-11-12 (exact). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: From 12 November 2025. Locator: News body: nature as Communication; Centre for Democratic Resilience; Media Resilience Programme; fact-checkers network. Source ID S-059.

- [60] EUR-Lex - GDPR. EUR-Lex (Official Journal of the EU), Regulation (EU) 2016/679 (General Data Protection Regulation) - consolidated text. Published 2016-05-04 (exact). Accessed 2026-10-15. Tier 1. Temporal class: historical. Observation period: Applies from 25 May 2018. Locator: Articles 33(1) and 34(1). Source ID S-060.

- [61] UK Parliament - Cyber Security and Resilience Bill. UK Parliament, Cyber Security and Resilience (Network and Information Systems) Bill - bill page. Published 2026-10-14 (page update). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Bill stages to 14 October 2026. Locator: Bill page: current stage House of Lords Report; HL Bill 49 as amended in Grand Committee dated 7 September 2026; no Royal Assent shown. Source ID S-061.

- [62] DSIT - Cyber Security and Resilience Bill summary. Department for Science, Innovation and Technology (GOV.UK), Cyber Security and Resilience (Network and Information Systems) Bill factsheets: summary of the Bill. Published 2026-06-30 (page update). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: First published 12 November 2025; updated 30 June 2026. Locator: Summary: managed service providers, data centres, designated suppliers, 24/72-hour reporting. Source ID S-062.

- [63] legislation.gov.uk - NIS Regulations 2018. legislation.gov.uk, The Network and Information Systems Regulations 2018 (SI 2018/506). Published 2018 (year only). Accessed 2026-10-15. Tier 1. Temporal class: historical. Observation period: In force 10 May 2018. Locator: Regs 1(1), 1(2), 1(3)(e). Source ID S-063.

- [64] OPSS - Consumer connectable product security. Office for Product Safety and Standards (GOV.UK), Regulations: consumer connectable product security. Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: In force 29 April 2024. Locator: Guidance body: in-force date, three requirements, exclusions. Source ID S-064.

- [65] legislation.gov.uk - DPA 2018 special purposes. legislation.gov.uk, Data Protection Act 2018, Schedule 2, paragraph 26 (journalistic, academic, artistic and literary purposes). Published 2018-05-23 (exact). Accessed 2026-10-15. Tier 1. Temporal class: historical. Observation period: Current version with amendments to 30 September 2026. Locator: Sch 2 para 26(1)-(9): conditions and listed provisions. Source ID S-065.

- [66] Home Office - Ransomware proposals consultation. Home Office (GOV.UK), Ransomware: proposals to increase incident reporting and reduce payments to criminals (consultation outcome). Published 2025-07-22 (exact). Accessed 2026-10-15. Tier 1. Temporal class: H2 prior. Observation period: Consultation 13 January - 8 April 2025; response 22 July 2025. Locator: Page body: consultation dates and response publication. Source ID S-066.

- [67] Goodwin - UK ransomware strategy alert. Goodwin Procter, The UK's Ransomware Strategy: What the UK Government's Response Signals. Published 2026-02-12 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: July 2025 - February 2026. Locator: Alert body: three proposals, no legislation introduced. Source ID S-067.

- [68] DSIT - Government Cyber Action Plan. Department for Science, Innovation and Technology (GOV.UK), Government Cyber Action Plan. Published 2026-01-06 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 2026-2029 phases. Locator: Sections on arm's-length bodies, Government Cyber Unit, delivery phases, relationship to the 2022-2030 strategy. Source ID S-068.

- [69] SEC - Cyber disclosure compliance guide. US Securities and Exchange Commission, Cybersecurity Risk Management, Strategy, Governance, and Incident Disclosure - small entity compliance guide. Published undated (undated). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: Compliance from 18 December 2023. Locator: Guide sections on Form 8-K Item 1.05, Regulation S-K Item 106, compliance dates, foreign private issuers. Source ID S-069.

- [70] FTC - COPPA final rule amendments. US Federal Trade Commission, 16 CFR Part 312: COPPA - Final Rule Amendments. Published 2025-04-22 (exact). Accessed 2026-10-15. Tier 1. Temporal class: H1 prior. Observation period: Federal Register publication 22 April 2025. Locator: Notice page: publication date and link to Federal Register text. Source ID S-070.

- [71] EBU - R 148 networked media equipment tests. European Broadcasting Union (EBU Technology and Innovation), EBU R 148 - Minimum Security Tests for Networked Media Equipment. Published 2018-04-27 (exact). Accessed 2026-10-15. Tier 1. Temporal class: historical. Observation period: Published 27 April 2018; not updated since. Locator: Publication page: purpose, annex of tests, update status. Source ID S-071.

- [72] Hunton - CIRCIA timing. Hunton Andrews Kurth, CISA plans to finalize cyber incident reporting regulations in September 2026. Published 2026-07-17 (exact). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: April 2024 - July 2026. Locator: Blog body citing the Unified Agenda preview. Source ID S-072.

- [73] EUR-Lex - Digital Services Act. EUR-Lex (Official Journal of the EU), Regulation (EU) 2022/2065 (Digital Services Act) - document metadata. Published 2022-10-27 (exact). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: Adopted 19 October 2022. Locator: ELI metadata: document date 19 October 2022; OJ publication 27 October 2022. Source ID S-073.

- [74] Music Business Worldwide - Live Nation class actions. Music Business Worldwide, Live Nation hit with class action lawsuits over data breach involving Social Security numbers and health records. Published 2026-10 (month only). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: October 2026. Locator: Article body: Vermont Attorney General notice 1 October; three complaints filed 6-7 October in the Central District of California; company statement 8 October. Source ID S-074.

- [75] legislation.gov.uk - National Security Act 2023 s13. legislation.gov.uk (The National Archives), National Security Act 2023, section 13 (Foreign interference). Published 2023-07-11 (exact). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: 20 December 2023 - 15 October 2026. Locator: Section 13(1)-(3); commencement note (S.I. 2023/1272 reg 2(a), 20 December 2023); amendment by the National Security (State Threats) Act 2026 effective 8 July 2026. Source ID S-075.

- [76] legislation.gov.uk - Media Act 2024. legislation.gov.uk (The National Archives), Media Act 2024. Published 2024-05-24 (exact). Accessed 2026-10-15. Tier 1. Temporal class: contextual. Observation period: 24 May 2024 - 15 October 2026. Locator: Long title and Act date (24 May 2024); Part 1 sections on public service television and Ofcom information powers (ss. 18-19). Source ID S-076.

- [77] GOV.UK - Online Safety Act explainer. UK Government (DSIT), Online Safety Act: explainer. Published 2025-04-24 (page update). Accessed 2026-10-15. Tier 1. Temporal class: H1 prior. Observation period: January 2025 - Summer 2025. Locator: Sections on duties in force: illegal content duties enforceable from 17 March 2025; children's risk assessments by 24 July 2025; categorised services thresholds and register. Source ID S-077.

- [78] DSIT - Telecommunications Security Code of Practice 2026. UK Government (DSIT), Telecommunications Security Code of Practice 2026 (version 1.1). Published 2026-07-14 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: 1 October 2022 - 15 October 2026. Locator: Section 1 paras 0.13-0.26 (tiering, legal status); legal basis ss. 105A-105Z Communications Act 2003 and Electronic Communications (Security Measures) Regulations 2022 in force 1 October 2022. Source ID S-078.

- [79] Ofcom - Arqiva electronic communications network statement. Ofcom, Application by Arqiva Limited for the application of the Electronic Communications Code - explanatory statement. Published 2018 (year only). Accessed 2026-10-15. Tier 1. Temporal class: historical. Observation period: January - July 2018. Locator: Paragraphs 1.13 (Arqiva's electronic communications network) and 1.15 (sites support terrestrial television and radio broadcast transmission). Source ID S-079.

- [80] Home Affairs - Infrastructure asset definition paper. Australian Government Department of Home Affairs, Home Affairs - Infrastructure asset definition paper. Published 2021-04 (month only). Accessed 2026-10-15. Tier 1. Temporal class: historical. Observation period: April 2021. Locator: Page 6 (section 12E broadcasting asset limbs: prescribed transmission site; at least 50 sites excluding re-transmission assets; prescribed entity); page 4 (positive security obligations). Source ID S-080.

- [81] Federal Register of Legislation - SOCI Act 2018 compilation. Federal Register of Legislation (Australia), Federal Register of Legislation - SOCI Act 2018 compilation. Published 2026-06-04 (page update). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Compilation in force June 2026. Locator: Table of contents: s. 12E (broadcasting asset definition); Part 2 Register; Part 2A s. 30AB; Part 2B ss. 30BB-30BD. Source ID S-081.

- [82] Digital Policy Alert - AVMSD transposition deadline. Digital Policy Alert, Directive amending Audiovisual Media Services Directive (2010/13/EU): deadline for transposition expired (No. 2018/1808). Published undated (undated). Accessed 2026-10-15. Tier 3. Temporal class: historical. Observation period: 14 November 2018 - 19 September 2020. Locator: Event entry: adoption 14 November 2018; transposition deadline 19 September 2020. Source ID S-082.

- [83] GDPR-Text - Article 85. GDPR-Text.com, Article 85 GDPR - Processing and freedom of expression and information. Published undated (undated). Accessed 2026-10-15. Tier 3. Temporal class: contextual. Observation period: Regulation (EU) 2016/679 as published. Locator: Article 85(1)-(3). Source ID S-083.

- [84] Advisera - Italian NIS2 decree overview. Advisera, Panoramica della legge italiana NIS2 e confronto con la direttiva UE NIS2. Published undated (undated). Accessed 2026-10-15. Tier 3. Temporal class: contextual. Observation period: D.Lgs. 138/2024. Locator: Article body: entities carrying out activities of cultural interest classified as important entities under specific conditions. Source ID S-084.

- [85] iubenda - AI Omnibus and Article 50. iubenda, AI Omnibus adopted: what still applies from August 2. Published 2026-07 (month only). Accessed 2026-10-15. Tier 3. Temporal class: current. Observation period: June - December 2026. Locator: Sections on Article 50: obligations from 2 August 2026 not moved; Article 50(2) marking for legacy systems by 2 December 2026; new systems from 2 August 2026 without grace period. Source ID S-085.

- [86] Vermont Attorney General - Security breach notices. Office of the Vermont Attorney General, Security Breach Notices (table of notices reported to the Attorney General). Published 2026-10-01 (page update). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Notice reported 1 October 2026. Locator: Table row: Live Nation Entertainment, Inc.; date reported 10-1-2026; type Other Commercial; Vermont residents affected 2; categories Social Security numbers, government ID numbers, health records. Source ID S-086.

- [87] Court complaint - Gosman v. Live Nation. US District Court, Central District of California (complaint hosted by Music Business Worldwide), Gosman v. Live Nation Entertainment, Inc., complaint, Case No. 2:26-cv-11664. Published 2026-10-07 (exact). Accessed 2026-10-15. Tier 1. Temporal class: current. Observation period: Filed 7 October 2026. Locator: Caption and paragraphs 1, 25 (notice to Vermont Attorney General about 1 October 2026), 27 (data types), 103 (notice more than four months after learning of the breach), 136 (class size on information and belief). Source ID S-087.

[1]: https://www.medienservice.sachsen.de/medien/news/1094410/download_pdf "Saxon culture ministry - SKD cyberattack release, 22 January 2026"

[2]: https://www.skd.museum/en/besucherservice/presse/2026/cyberattack-on-the-dresden-state-art-collections/ "SKD - Cyberattack press release"

[3]: https://www.medienservice.sachsen.de/medien/news/1094571 "SKD - Recovery update, 29 January 2026"

[4]: https://medienservice.sachsen.de/medien/news/1095116/download_pdf "Prosecutor and LKA Saxony - SKD investigation release"

[5]: https://dresden.t-online.de/region/dresden/id_101137618/dresden-zwinger-raub-geplant-was-ueber-die-arbeit-der-skd-soko-bekannt-ist.html "t-online - SKD special commission report"

[6]: https://www.volksstimme.de/panorama/cyberangriff-auf-skd-dauerte-mehrere-tage-4292567 "dpa via Volksstimme - SKD attack duration"

[7]: https://www.guimet.fr/en/museum-online-ticketing-service-unavailable "Musee Guimet - Online ticketing unavailable notice"

[8]: https://tickets.monuments-nationaux.fr/fr-FR/donnees-personnelles "CMN - Ticketing personal data notice"

[9]: https://actualitte.com/article/130017/usages-numeriques/cyberattaque-des-musees-et-institutions-culturelles-perturbes-dont-la-bnf "ActuaLitte - Vivaticket attack on cultural institutions"

[10]: https://www.lechotouristique.com/article/billetterie-les-monuments-nationaux-victimes-dune-cyberattaque "L'Echo touristique - CMN ticketing cyberattack"

[11]: https://www.lyonmag.com/article/150751/la-billetterie-des-musees-municipaux-de-lyon-victime-d-une-cyber-attaque "Lyon Mag - Lyon municipal museums ticketing attack"

[12]: https://www.scworld.com/brief/thousands-of-european-tourist-sites-impacted-by-ticketing-platform-breach "SC Media - Vivaticket platform breach brief"

[13]: https://radioink.com/2025/12/02/fcc-issues-cybersecurity-warning-after-houston-barix-hack/ "Radio Ink - FCC warning after Houston hijack"

[14]: https://docs.fcc.gov/public/attachments/FCC-26-38A1.pdf "FCC - FCC 26-38 alerting systems order"

[15]: https://storage.courtlistener.com/recap/gov.uscourts.nysd.655608/gov.uscourts.nysd.655608.17.0.pdf "SDNY - Anna's Archive preliminary injunction"

[16]: https://www.musicbusinessworldwide.com/record-labels-spotify-sue-pirate-group-annas-archive-over-scraping-and-brazen-theft-of-86m-tracks "Music Business Worldwide - Anna's Archive lawsuit"

[17]: https://musictech.com/news/industry/judge-orders-annas-archive-to-pay-322-million/ "MusicTech - Anna's Archive judgment"

[18]: https://www.geo.tv/latest/653574-geo-news-says-aired-message-after-hack-not-linked-to-channel "Geo News - Satellite feed hijack statement"

[19]: https://www.dawn.com/news/1977705 "Dawn - CERT investigation of TV channel hacks"

[20]: https://digitalrightsmonitor.pk/several-pakistani-tv-channels-briefly-taken-over-by-unauthorised-broadcasts/ "Digital Rights Monitor - Pakistani channel takeovers"

[21]: https://techcrunch.com/2026/04/13/hack-at-anodot-leaves-over-a-dozen-breached-companies-facing-extortion/ "TechCrunch - Anodot integration breach"

[22]: https://www.sec.gov/Archives/edgar/data/46080/000004608026000013/has-20260401.htm "Hasbro - Form 8-K, 1 April 2026"

[23]: https://www.sec.gov/Archives/edgar/data/0000046080/000004608026000029/exhibit991q12026.htm "Hasbro - Q1 2026 results release"

[24]: https://bleepingcomputer.com/news/security/soundcloud-confirms-breach-after-member-data-stolen-vpn-access-disrupted "BleepingComputer - SoundCloud breach"

[25]: https://nos.nl/artikel/2590462-privegegevens-gestolen-bij-hack-rtv-noord-was-geen-gerichte-aanval "NOS - RTV Noord hack"

[26]: https://nltimes.nl/node/84401 "NL Times - RTV Noord broadcast disruption"

[27]: https://www.artribune.com/professioni-e-professionisti/politica-e-pubblica-amministrazione/2026/04/uffizi-attacco-hacker-scoop-risposta-direttore-verde/ "Artribune - Uffizi incident claims and response"

[28]: https://leipzig.t-online.de/region/leipzig/id_101351990/cyberangriff-trifft-staedtische-kulturbetriebe-in-leipzig.html "t-online - Leipzig cultural enterprises attack"

[29]: https://www.quotenmeter.de/n/175372/die-neue-druckmaschine-steht-im-rechenzentrum-wenn-cyberangriffe-den-journalismus-treffen "Quotenmeter - Cyberattacks on journalism"

[30]: https://www.sec.gov/Archives/edgar/data/58361/000005836125000040/lee-20250928.htm "Lee Enterprises - FY2025 Form 10-K"

[31]: https://www.sec.gov/Archives/edgar/data/0000058361/000005836126000060/lee-20260628.htm "Lee Enterprises - Q3 FY2026 Form 10-Q"

[32]: https://www.kadokawa.co.jp/topics/13832/ "KADOKAWA - FY2025/3 results release"

[33]: https://assets.publishing.service.gov.uk/media/68778282760bf6cedaf5bcda/WEB_ACCESSIBLE_British_Library_Annual_Report_and_Accounts_FY_2024_25.pdf "British Library - Annual Report 2024/25"

[34]: https://assets.publishing.service.gov.uk/media/6a57634e6d6d5c7e2845c9c0/British_Library_Annual_Report_and_Accounts_2025-26_WEB_NAO_14_July_v2.pdf "British Library - Annual Report 2025/26"

[35]: https://www.museumsassociation.org/museums-journal/news/2026/09/new-leadership-for-british-library-as-cyber-attack-recovery-continues/ "Museums Association - British Library recovery"

[36]: https://www.torontoauditor.ca/wp-content/uploads/2026/05/Cybersecurity-Audit-of-Toronto-Public-Library-CVR-May-15-2026.pdf "Toronto Auditor General - Toronto Public Library audit"

[37]: https://www.ccomptes.fr/sites/default/files/2025-12/20251106-summary-The-public-establishment-of-the-Louvre-Museum.pdf "Cour des comptes - Louvre public establishment summary"

[38]: https://aws.amazon.com/message/101925/ "AWS - US-EAST-1 post-event summary"

[39]: https://blog.cloudflare.com/18-november-2025-outage/ "Cloudflare - 18 November 2025 outage report"

[40]: https://ppc.land/amazon-outage-breaks-the-internet-snapchat-fortnite-banks-go-dark/ "PPC Land - AWS outage effects"

[41]: https://www.enisa.europa.eu/sites/default/files/2026-09/ENISA%20Threat%20Landscape%202026_Final.pdf "ENISA - Threat Landscape 2026"

[42]: https://blog.cloudflare.com/ddos-threat-report-2026-h1/ "Cloudflare - DDoS Threat Report H1 2026"

[43]: https://www.eeas.europa.eu/sites/default/files/2026/documents/EEAS%204th%20Threat%20Report_web.pdf "EEAS - 4th FIMI Threats Report"

[44]: https://www.gov.uk/government/statistics/cyber-security-breaches-survey-20252026/cyber-security-breaches-survey-20252026 "DSIT - Cyber Security Breaches Survey 2025/26"

[45]: https://ec.europa.eu/eurostat/en/web/products-eurostat-news/w/ddn-20260710-2 "Eurostat - EU cultural employment 2025"

[46]: https://www.gov.uk/government/statistics/dcms-economic-estimates-gva-2024-provisional/dcms-sectors-economic-estimates-gross-value-added-2024-provisional "DCMS - Sectors GVA 2024 (provisional)"

[47]: https://www.europol.europa.eu/media-press/newsroom/news/global-operation-targets-noname05716-pro-russian-cybercrime-network "Europol - Operation Eastwood"

[48]: https://eur-lex.europa.eu/eli/dir/2022/2555/oj/eng "EUR-Lex - NIS2 Directive"

[49]: https://digital-strategy.ec.europa.eu/en/faqs/directive-measures-high-common-level-cybersecurity-across-union-nis2-directive-faqs "European Commission - NIS2 FAQs"

[50]: https://home-affairs.ec.europa.eu/policies/internal-security/counter-terrorism-and-radicalisation/protection/%63ritical-infrastructure-resilience-eu-level_en "European Commission - Entity resilience policy page"

[51]: https://commission.europa.eu/topics/democracy/eu-actions-protect-democracy/european-media-freedom-act_en "European Commission - European Media Freedom Act page"

[52]: https://commission.europa.eu/news-and-media/news/new-eu-rules-political-advertising-come-effect-2025-10-10_en "European Commission - Political advertising rules apply"

[53]: https://digital-strategy.ec.europa.eu/en/faqs/transparency-obligations-under-article-50-ai-act "European Commission - AI Act Article 50 FAQ"

[54]: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202601744 "EUR-Lex - Digital Omnibus on AI"

[55]: https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act "European Commission - Cyber Resilience Act page"

[56]: https://single-market-economy.ec.europa.eu/sectors/electrical-and-electronic-engineering-industries-eei/radio-equipment-directive-red_en "European Commission - Radio Equipment Directive page"

[57]: https://digital-strategy.ec.europa.eu/en/policies/digital-services-act "European Commission - Digital Services Act page"

[58]: https://digital-strategy.ec.europa.eu/en/news/commission-takes-stock-progress-made-take-measures-its-2023-recommendation-combatting-online-piracy "European Commission - Live-event piracy Recommendation stock-take"

[59]: https://enlargement.ec.europa.eu/news/european-democracy-shield-and-eu-strategy-civil-society-pave-way-stronger-and-more-resilient-2025-11-12_en "European Commission - European Democracy Shield"

[60]: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX%3A02016R0679-20160504 "EUR-Lex - GDPR"

[61]: https://bills.parliament.uk/bills/4035 "UK Parliament - Cyber Security and Resilience Bill"

[62]: https://www.gov.uk/government/publications/cyber-security-and-resilience-network-and-information-systems-bill-factsheets/summary-of-the-bill "DSIT - Cyber Security and Resilience Bill summary"

[63]: https://www.legislation.gov.uk/uksi/2018/506 "legislation.gov.uk - NIS Regulations 2018"

[64]: https://www.gov.uk/guidance/regulations-consumer-connectable-product-security "OPSS - Consumer connectable product security"

[65]: https://www.legislation.gov.uk/ukpga/2018/12/schedule/2/paragraph/26 "legislation.gov.uk - DPA 2018 special purposes"

[66]: https://www.gov.uk/government/consultations/ransomware-proposals-to-increase-incident-reporting-and-reduce-payments-to-criminals "Home Office - Ransomware proposals consultation"

[67]: https://www.goodwinlaw.com/en/insights/publications/2026/02/alerts-technology-dpc-the-uks-ransomware-strategy "Goodwin - UK ransomware strategy alert"

[68]: https://www.gov.uk/government/publications/government-cyber-action-plan/government-cyber-action-plan "DSIT - Government Cyber Action Plan"

[69]: https://www.sec.gov/resources-small-businesses/small-business-compliance-guides/cybersecurity-risk-management-strategy-governance-incident-disclosure "SEC - Cyber disclosure compliance guide"

[70]: https://www.ftc.gov/legal-library/browse/federal-register-notices/16-cfr-part-312-coppa-final-rule-amendments "FTC - COPPA final rule amendments"

[71]: https://tech.ebu.ch/publications/r148 "EBU - R 148 networked media equipment tests"

[72]: https://www.hunton.com/privacy-and-cybersecurity-law-blog/cisa-plans-to-finalize-cyber-incident-reporting-regulations-in-september-2026 "Hunton - CIRCIA timing"

[73]: https://eur-lex.europa.eu/eli/reg/2022/2065/oj/eng "EUR-Lex - Digital Services Act"

[74]: https://www.musicbusinessworldwide.com/live-nation-hit-with-class-action-lawsuits-over-data-breach-involving-social-security-numbers-and-health-records/ "Music Business Worldwide - Live Nation class actions"

[75]: https://www.legislation.gov.uk/ukpga/2023/32/section/13 "legislation.gov.uk - National Security Act 2023 s13"

[76]: https://www.legislation.gov.uk/ukpga/2024/15 "legislation.gov.uk - Media Act 2024"

[77]: https://gov.uk/government/publications/online-safety-act-explainer/online-safety-act-explainer "GOV.UK - Online Safety Act explainer"

[78]: https://www.gov.uk/government/publications/revised-telecommunications-security-code-of-practice-2026-version-11/telecommunications-security-code-of-practice-2026-version-11 "DSIT - Telecommunications Security Code of Practice 2026"

[79]: https://www.ofcom.org.uk/siteassets/resources/documents/consultations/category-3-4-weeks/114661--code-powers-arqiva-limited/associated-documents/arqiva-limited-explanatory-statement.pdf "Ofcom - Arqiva electronic communications network statement"

[80]: https://www.homeaffairs.gov.au/reports-and-pubs/files/%63ritical-infrastructure-asset-definition-rules-paper.pdf "Home Affairs - Infrastructure asset definition paper"

[81]: https://www.legislation.gov.au/C2018A00029/latest/text "Federal Register of Legislation - SOCI Act 2018 compilation"

[82]: https://digitalpolicyalert.org/event/42898-directive-amending-audiovisual-media-services-directive-201013eu-deadline-for-transposition-expired-no-20181808 "Digital Policy Alert - AVMSD transposition deadline"

[83]: https://gdpr-text.com/uk/read/article-85 "GDPR-Text - Article 85"

[84]: https://advisera.com/it/articoli/italiano-nis2-decreto-legislativo/ "Advisera - Italian NIS2 decree overview"

[85]: https://www.iubenda.com/en/blog/ai-omnibus-adopted-august-2-obligations-july-2026/ "iubenda - AI Omnibus and Article 50"

[86]: https://ago.vermont.gov/categories/security-breaches "Vermont Attorney General - Security breach notices"

[87]: https://www.musicbusinessworldwide.com/files/2026/10/Gosman-v-Live-Nation.pdf "Court complaint - Gosman v. Live Nation"

Media & Cultural Services cyber sectorial analysis - external data only
