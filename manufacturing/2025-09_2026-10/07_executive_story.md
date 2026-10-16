# Manufacturing - Executive Story and Slide Mapping

Reporting period 1 September 2025 to 16 October 2026. Evidence cut-off 16 October 2026. Seven self-contained analytical slides; no speaker notes. Full sources, dates and locators are in 14_sectorial_report.md; slides carry none by design. This file is regenerated from 08_slide_spec.json.

## Storyline

1. Exposure runs through the enterprise systems that release production and reaches the financial system through lost output, supplier liquidity and state-backed lending.
2. Five incidents meet the evidence standard; four stopped production through IT-side compromise and one compromised manufacturers' fielded controllers.
3. Lost output and cash, not response cost, drive the financial effect; one OEM stop coincided with an officially recorded fall in vehicle output and needed state-backed lending.
4. Three distinct stress pathways converge on lost output, supplier liquidity and liability; they are not forecasts.
5. An enterprise-systems shutdown stopped production for about five weeks and transmitted to suppliers, bank liquidity, state guarantees and official vehicle-output statistics.
6. Concentration sits in enterprise systems, administrative tools, OT vendors' installed bases, integrators and supplier tiers; regulation reaches most manufacturers through product law and contracts.
7. Seven priorities address the evidenced pathways, each with a challenge question, completion evidence and external trigger.

## Slide 1: Sector Exposure & Executive Risk Outlook

Decision use: Treat manufacturing cyber risk as an IT-dependent production, supplier-liquidity and product-liability issue.

Visual: Judgement table with confidence and change conditions. Scenario IDs: none. Metric IDs: M-019, M-023, M-025, M-026.

| Element | Role | Visible text | Claim IDs |
| --- | --- | --- | --- |
| conclusion | conclusion | Manufacturing cyber exposure in the period ran through the enterprise systems that release production, not through plant control systems; it reaches the financial system mainly through lost output, supplier liquidity and state-backed lending. | C-039, C-040, C-041 |
| evidence | evidence | Evidence base: public records for the 13-month reporting period across the EU, EEA and UK with global comparison - company and securities filings, a national CERT alert, statistics-office and central-bank publications, an independent loss model, and ENISA, Dragos and Black Kite benchmarks. | C-012, C-022, C-024, C-020, C-033, C-003, C-005, C-008 |
| interpretation | interpretation | Footprint: EU manufacturing employs 30.2 million people and produces 23.1% of business-economy value added. It drew 25.2% of EU ransomware claims in ENISA's latest review and about 65% of industrial ransomware in the latest quarter tracked by Dragos. | C-001, C-003, C-005 |
| t1r1 | evidence | Production loss runs through IT dependency and precautionary shutdown, not direct operational technology (OT) compromise Medium Disclosed control-system manipulation causing damage at a manufacturer | C-039 |
| t1r2 | evidence | Supplier cascade and liquidity are the systemic pathway in just-in-time production Medium Evidence that lower-tier suppliers absorb multi-week stops without support | C-041 |
| t1r3 | evidence | Financial effect is dominated by lost output and cash, not response cost Medium Rebuild and response costs exceeding lost margin | C-040 |
| t1r4 | evidence | State-linked activity targets industrial controllers; no official attribution of a manufacturing disruption Low Official attribution of a European manufacturing disruption to a state | C-042 |
| t1r5 | evidence | Regulation reaches most manufacturers through product law and contracts rather than entity-level regimes Medium National NIS2 designation beyond the named divisions | C-043 |
| implication | implication | Treat large manufacturing counterparties as IT-dependent production systems: ask how long they can release production without enterprise resource planning (ERP), manufacturing execution (MES) and identity services, and which suppliers depend on them for most of their revenue. | C-039, C-041, C-066 |
| limitation | limitation | Quantified outcomes come from listed companies; supplier failures, ransom payments and the state of plant control systems are not publicly disclosed, so their absence is a disclosure gap, not evidence of zero effect. | C-044, C-067 |

## Slide 2: Key Threats & Top 5 Cyber Attacks

Decision use: Weight reviews towards IT-OT production dependency, administrative tools and installed products.

Visual: Named incident table with pattern list. Scenario IDs: none. Metric IDs: M-015, M-018, M-023.

| Element | Role | Visible text | Claim IDs |
| --- | --- | --- | --- |
| conclusion | conclusion | Five incidents meet the evidence standard; four stopped production through IT-side compromise and one compromised manufacturers' controllers in customer premises, so both the enterprise estate and the installed product base are exposure points. | C-012, C-027, C-029, C-031, C-033, C-039 |
| evidence | evidence | Threat pathways (patterns, not attacks): P1 ransomware and data extortion against enterprise IT; P2 destructive misuse of administrative platforms; P3 internet-exposed OT and fielded products; P4 supplier and service-provider compromise; P5 data theft with intellectual-property and export-control exposure. | C-003, C-004, C-030, C-033, C-035, C-032 |
| interpretation | interpretation | ENISA found manufacturing the largest EU ransomware target, with exfiltration overtaking encryption; Dragos found no recent ransomware case reaching control-system manipulation, and 117 incidents at integrators and equipment makers in one quarter. | C-003, C-004, C-006, C-007 |
| t2r1 | evidence | 1 Jaguar Land Rover shutdown Automotive original equipment manufacturer (OEM); UK and Slovakia About five weeks of halted production; supplier cascade; recorded vehicle-output fall Company filings, statistics office, central bank | C-012, C-013, C-022 |
| t2r2 | evidence | 2 Asahi Group ransomware Beverages and food; Japan Shipments halted; about JPY 40 billion impact; results delayed five months Company disclosures | C-027, C-028 |
| t2r3 | evidence | 3 Stryker global IT disruption Medical devices; global Material quarterly effect; manufacturing and ordering restored in about four weeks Securities filings; media-reported claim unconfirmed | C-029, C-030 |
| t2r4 | evidence | 4 Boston Scientific outage Medical devices; global Manufacturing, ordering and shipping disrupted; guidance unlikely to be met Material-incident filing | C-031 |
| t2r5 | evidence | 5 Refrigeration controller compromise OT equipment makers; France Numerous controllers compromised; hundreds of stores affected National CERT alert; scale from media | C-033, C-034 |
| implication | implication | Weight counterparty reviews towards IT-OT production dependency, controls over administrative tools and the exposure of manufacturers' installed products, rather than counting ransomware claims alone. | C-039, C-066 |
| limitation | limitation | Only two of five incidents are EU or UK, reflecting US disclosure rules; chemicals, metals and basic materials have no named case with an official outcome, and the controller case is days old. | C-044, C-034 |

## Slide 3: Financial Impact: Manufacturing

Decision use: Monitor counterparty liquidity and supplier concentration after a major manufacturer incident.

Visual: Impact-type evidence table. Scenario IDs: none. Metric IDs: M-003, M-006, M-007, M-010, M-011, M-012, M-016.

| Element | Role | Visible text | Claim IDs |
| --- | --- | --- | --- |
| conclusion | conclusion | Public financial evidence is thin and cannot be added up, but it consistently shows that lost output and cash, not response cost, drive the effect, and that a single OEM stop can show up in official vehicle-output statistics and require state-backed lending. | C-040, C-022, C-018 |
| evidence | evidence | Evidence base: quarterly and annual company results, securities filings, the UK statistics office and central bank, an industry output series and the Cyber Monitoring Centre model of the JLR event. | C-015, C-016, C-022, C-023, C-024, C-020 |
| interpretation | interpretation | JLR's labelled cyber costs were GBP 260 million over two quarters while quarterly free cash outflow reached GBP 1.5 billion. Transmission ran through a GBP 2 billion bridge facility, supplier prepayment via a banking partner and a government-guaranteed GBP 1.5 billion loan. | C-015, C-016, C-017, C-018, C-019 |
| t3r1 | evidence | Production stoppage About five weeks at JLR; about four weeks to full restoration at Stryker Observed | C-013, C-029 |
| t3r2 | evidence | Incident-related cost GBP 260 million at JLR over two quarters; JPY 17 billion of expenses at Asahi incl. inventory write-offs Observed for two firms | C-015, C-028 |
| t3r3 | evidence | Revenue and delivery JLR quarterly revenue down 24% and 39%; wholesales down 43.3% Mixed causes | C-014, C-015 |
| t3r4 | evidence | Working capital JLR free cash outflow of GBP 791 million and GBP 1.5 billion in two quarters Observed | C-016 |
| t3r5 | evidence | Supplier cascade Over 5,000 UK organisations (also given as more than 2,700); GBP 1.9 billion modelled loss Modelled only | C-020, C-021 |
| t3r6 | evidence | Macro-economic UK motor-vehicle output down 28.6% in the stop month; central bank cites weaker growth Observed | C-022, C-024 |
| t3r7 | evidence | Insurance and insolvency Customer-side disruption often uninsured; no supplier insolvency officially attributed Insurance qualitative; insolvency not evidenced | C-021, C-011 |
| implication | implication | Monitor facility drawdown, supply-chain finance usage and receivables concentration at manufacturing counterparties after a major customer incident, and test how a four-week OEM stop would surface in early-warning indicators. | C-041, C-019, C-066 |
| limitation | limitation | Values differ in currency, statistic type and population and are not summed; JLR revenue and cash effects also reflect tariffs and model wind-down; ransom and insurance recoveries were not disclosed. | C-015, C-067 |

## Slide 4: Financial Impact: Worst-Case Scenarios

Decision use: Identify shared platforms, vendors and supplier dependencies across manufacturing counterparties.

Visual: Scenario comparison table. Scenario IDs: SC-001, SC-002, SC-003. Metric IDs: none.

| Element | Role | Visible text | Claim IDs |
| --- | --- | --- | --- |
| conclusion | conclusion | Three distinct stress pathways - a shared enterprise platform failure, a targeted stop at one large manufacturer and a compromise spreading through a supplier layer - converge on lost output, supplier liquidity and liability; they are stress narratives, not forecasts or loss estimates. | C-063, C-064, C-065 |
| t4r1 | evidence | Trigger Multi-day loss or misuse of identity, endpoint, ERP, MES or supplier-portal services used by many firms Ransomware or wipe at one high-volume OEM or tier-1 supplier for four to eight weeks Compromise of an OT vendor's fielded controllers, an integrator or a component supplier | C-063, C-064, C-065 |
| t4r2 | evidence | Propagation Many plants stop on precaution while OT is untouched Just-in-time call-offs stop; thousands of suppliers idle One supplier's weakness reaches many customers at once | C-063, C-064, C-065, C-020 |
| t4r3 | evidence | Financial transmission Correlated delivery gaps; concurrent working-capital draws Emergency facilities, supplier prepayment, possible state guarantee Remediation, warranty and liability costs; component shortages | C-063, C-064, C-065, C-017 |
| t4r4 | evidence | Early signposts Provider outage notices; government alerts on platform misuse Production-pause extensions; supplier short-time work CERT alerts naming products; disclosures citing an IT provider | C-030, C-064, C-065 |
| t4r5 | evidence | Limiting conditions Offline production release; tenant isolation Segmented estates restored within weeks Exposure management; supported firmware | C-063, C-029, C-033 |
| evidence | evidence | Evidence base: the JLR and medical-device shutdowns, a reported administrative-tool wipe, a cross-sector software outage, the controller compromise and a supplier hit through its IT provider; durations are illustrative. | C-012, C-031, C-030, C-036, C-033, C-035, C-007 |
| interpretation | interpretation | Scenario 1 is broad and shallow, scenario 2 narrow and deep, scenario 3 broad through one supplier; all three reach banks through counterparty liquidity and liability rather than direct loss. | C-063, C-064, C-065, C-040 |
| implication | implication | Ask which counterparties share the same enterprise platforms and OT vendors, and how many weeks of stop the largest manufacturing counterparties and their dependent suppliers can finance. | C-066, C-041 |
| limitation | limitation | No probabilities are assigned because no defensible external basis exists; no multi-day common-platform outage across many manufacturers was observed in the period. | C-063, C-067 |

## Slide 5: Case Study: Jaguar Land Rover Cyber Incident

Decision use: Treat a multi-week OEM stop as a foreseeable credit event for its supplier base.

Visual: Phase timeline table. Scenario IDs: SC-002. Metric IDs: M-001, M-002, M-007, M-009, M-010, M-011, M-012.

| Element | Role | Visible text | Claim IDs |
| --- | --- | --- | --- |
| conclusion | conclusion | A precautionary shutdown of JLR's enterprise systems stopped production for about five weeks; in the following quarter wholesales fell 43% and free cash outflow reached GBP 1.5 billion, with tariffs and model wind-down also contributing. Suppliers needed customer-funded prepayment and the state guaranteed a GBP 1.5 billion bank loan. | C-012, C-013, C-014, C-016, C-018, C-019 |
| evidence | evidence | Evidence base: company statements and four quarterly releases, the government guarantee release, a parliamentary letter, the statistics office, the central bank, an industry output series and the Cyber Monitoring Centre model; selected as the only in-period case with this depth. | C-012, C-015, C-018, C-026, C-022, C-024, C-023, C-020 |
| interpretation | interpretation | Mechanism: production stopped because the systems that schedule, supply and release it were shut down; the plant control state and the initial access route were not disclosed, and a criminal group's claim was not confirmed. | C-012, C-025, C-039 |
| t5r1 | evidence | Shutdown Day 0 Enterprise systems shut down; production and retail disrupted | C-012 |
| t5r2 | evidence | Liquidity Weeks 3-4 GBP 2 billion bridge facility; state guarantee announced to support the supply chain | C-017, C-018 |
| t5r3 | evidence | Restart Week 6 Phased restart from engines and batteries; suppliers prepaid through a bank | C-013, C-019 |
| t5r4 | evidence | Normal production About week 11 Output back to normal; distribution still catching up | C-013, C-014 |
| t5r5 | evidence | Financial trail Two quarters GBP 260 million cyber costs; wholesales down 43.3%; vehicle-output fall recorded | C-015, C-014, C-022 |
| t5r6 | evidence | Year end About month 7 Guaranteed loan undrawn; production recovered | C-017 |
| implication | implication | Treat a multi-week stop at a large OEM as a foreseeable credit event for its supplier base: map supplier revenue concentration and know which supply-chain finance and guarantee channels would be used. | C-041, C-019, C-018 |
| limitation | limitation | The case does not show the access route, plant control state, any ransom, the full-year cyber cost or any supplier insolvency; the economy-wide loss is modelled and covers UK operations only. | C-025, C-020, C-067 |

## Slide 6: Systemic Dependencies & Regulatory Outlook

Decision use: Align counterparty documentation with product-security, liability and supplier obligations.

Visual: Dependency chain list and regulatory status table. Scenario IDs: none. Metric IDs: M-024.

| Element | Role | Visible text | Claim IDs |
| --- | --- | --- | --- |
| conclusion | conclusion | Manufacturing concentration sits in enterprise systems, administrative tools, OT vendors' installed bases, integrators and just-in-time supplier tiers; regulation reaches most manufacturers through product law and contracts, with NIS2 limited to named activities. | C-039, C-041, C-043 |
| evidence | evidence | Evidenced dependency chains: enterprise IT to production release; administrative tools to every device; OT vendor installed base to many customer sites; integrators and managed IT to several plants; one OEM to thousands of suppliers; manufacturer software to customers in other sectors. | C-012, C-030, C-033, C-035, C-007, C-020, C-036 |
| interpretation | interpretation | Where NIS2 applies the population is large: Germany registered 4,739 entities under manufacturing of goods, while four Member States were referred to the Court of Justice for not transposing. | C-010, C-047, C-048 |
| t6r1 | evidence | NIS2 Binding via national law Named activities: electronics, electrical equipment, machinery and vehicles (NACE C26-C30), medical devices, chemicals, food and pharmaceuticals; others only by national extension | C-045, C-046 |
| t6r2 | evidence | Cyber Resilience Act (CRA) Directly applicable; reporting live In-scope connected-product makers report exploited flaws; full duties in about 14 months | C-049 |
| t6r3 | evidence | Machinery Regulation Applies in about three months Protection against corruption becomes a machine safety requirement | C-050 |
| t6r4 | evidence | Product Liability Directive Transposition due within two months Software and missing security updates can create strict liability | C-052 |
| t6r5 | evidence | UN Regulation 155 Binding for vehicle type approval OEMs must manage cyber risk across development, production and suppliers | C-059 |
| t6r6 | evidence | UK Cyber Security and Resilience Bill Bill, not law Could reach managed providers and designated suppliers | C-054 |
| t6r7 | evidence | US defence certification Contract requirement Defence-supply-chain manufacturers face certification gates | C-056 |
| implication | implication | Check that lending and guarantee documentation for manufacturing counterparties reflects product-security reporting, liability exposure and customer-imposed cyber clauses, and track the UK Bill and liability transposition. | C-049, C-052, C-054, C-066 |
| limitation | limitation | National NIS2 extensions were not surveyed exhaustively; several legal texts were confirmed from official metadata and reproductions; market shares of manufacturing software and OT vendors are not public. | C-043, C-045 |

## Slide 7: Mitigation Strategies & Security Framework

Decision use: Assign 1LoD owners and completion evidence to seven evidence-linked priorities.

Visual: Action table with completion evidence and triggers. Scenario IDs: none. Metric IDs: none.

| Element | Role | Visible text | Claim IDs |
| --- | --- | --- | --- |
| conclusion | conclusion | Seven evidence-linked priorities address the pathways: production release without IT, control of administrative tools, supplier liquidity, installed-base exposure, provider access, product-law readiness and insurance alignment. | C-066 |
| t7r1 | evidence | A1 IT-OT production dependency (0-6 months) Can top counterparties release production and ship without ERP, MES and identity? Manual-release procedure; recovery tests Production-pause notice | C-039, C-012 |
| t7r2 | evidence | A2 Administrative tools (0-3 months) Do assessments test approval controls on mass wipe actions? Assessment evidence Alert on administrative-tool misuse | C-030 |
| t7r3 | evidence | A3 Supplier liquidity (0-6 months) Which programme suppliers depend on one customer? Concentration map; stress test OEM incident notice | C-041, C-019 |
| t7r4 | evidence | A4 Installed base (3-12 months) Do equipment makers track exposed and end-of-life units? Exposure and support register CERT alert naming a product | C-033, C-034 |
| t7r5 | evidence | A5 Provider access (3-12 months) Is provider remote access to OT restricted and logged? Access inventory and logs Disclosure citing an IT provider | C-035, C-007 |
| t7r6 | evidence | A6 Product-law readiness (0-6 months) Can counterparties meet new reporting and liability duties? Reporting procedure; support periods First enforcement action | C-049, C-052 |
| t7r7 | evidence | A7 Insurance and contracts (6-12 months) Is customer-side disruption insured or priced? Documentation review Insurer product change | C-021 |
| evidence | evidence | Evidence base: CERT recommendations for exposed controllers, a US alert on administrative tools, the JLR supplier scheme, the independent loss model and the new product rules. | C-033, C-030, C-019, C-020, C-006, C-049, C-052 |
| interpretation | interpretation | Frameworks are reference vocabularies, not law: NIST CSF 2.0 and its draft manufacturing profile, NIST SP 800-82, IEC 62443, ISO/IEC 27001 and 27036, and VDA ISA with TISAX for automotive. | C-066 |
| implication | implication | Give each priority a First Line of Defence (1LoD) owner and a dated completion artefact, and escalate to the Risk Committee when a monitoring trigger fires. | C-066 |
| limitation | limitation | Actions are sector priorities drawn from public evidence, not findings about any institution's controls, losses or risk appetite. | C-066 |
