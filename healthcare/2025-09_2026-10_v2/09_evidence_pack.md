# Healthcare Cyber Sectorial Analysis - Evidence Pack

**Run ID:** 20261014-healthcare-global-eu-uk-2025-09_2026-10-r2 (revision 2, 25 October 2026)
**Reporting period:** 1 September 2025 to 14 October 2026. **Evidence cut-off:** 14 October 2026. **Report date:** 14 October 2026. **Access date for all sources:** 15 October 2026 (actual retrieval date).
**Analytical boundary:** external public data only. **Audience:** 1LoD operational management and Risk Committee.
**Status of this pack:** supporting audit material for 14_sectorial_report.md and 15_sectorial_report.docx; it does not replace the full report.

## Evidence base summary

| Measure | Value |
|---|---|
| Sources in register | 73 (see 02_source_register.csv) |
| Tier 1 sources | 56 |
| Tier 2 sources | 3 |
| Tier 3 sources | 14 (context or paired with Tier 1 only) |
| Claims in ledger | 71 (see 03_claim_ledger.json) |
| Metrics defined | 36 (see 04_metric_dictionary.csv) |
| Regulatory rows | 22 (see 05_regulatory_relevance_register.csv) |
| Scenarios | 3 (see 06_scenario_assumption_register.csv) |

## Evidence-led conclusions

1. [1] [12] [15] Three manufacturers (Stryker, Boston Scientific, West Pharmaceutical) filed SEC Item 1.05 material cybersecurity incident reports between March and September 2026 describing global disruption to manufacturing, ordering or shipping. Claims C-010, C-014, C-017.
2. [3] [2] NHS England moved six Stryker product lines to controlled allocation on 18 March 2026 with about two weeks of UK stock; Stryker stated some patient cases were rescheduled for shipping delays. Claims C-011, C-012.
3. [28] [29] The Dutch cervical screening operator suspended an outsourced laboratory after a July 2025 breach; backup laboratories ran at about 150% capacity for six months and primary invitations were reduced by 50% from 22 December 2025; the health inspectorate found the laboratory non-compliant with NEN 7510 on 13 May 2026. Claims C-044, C-045.
4. [17] [25] [30] Data exposure in the period ran mainly through credential and access abuse at software vendors and providers (Cegedim Sante MLM, Veradigm vendor API, Hopital Prive de la Loire), with an in-period CNIL fine of EUR 500,000. Claims C-019, C-023, C-025.
5. [32] [31] [33] ENISA placed health in its risk zone (May 2026); health ranks among the top five sectors in Member State NIS2 reporting for 2025; France recorded 288 of 764 health incident reports with degraded or interrupted care in 2025. Claims C-001, C-002, C-003.

Reference numbers in square brackets match the report reference list and the report_reference_number column of the source register.

## Financial and operational transmission

The evidence supports conditional transmission channels rather than a loss calculation:

1. Intrusion reaches a supplier's identity or IT platform, a vendor's application, or an operator's clinical systems.
2. The organisation isolates systems or the purchaser suspends the supplier.
3. Manufacturing, ordering, laboratory throughput or clinical information becomes unavailable; stock buffers or substitute capacity absorb the shock for a limited time.
4. Effects reach hospitals (controlled allocation, rescheduled procedures, diversion), programmes (invitation reductions) and corporate earnings (Q1 2026 Stryker; Q3 2026 Boston Scientific guidance).
5. Financial-system relevance arises through counterparty earnings and working capital, provider liquidity when claims stop (historical Change Healthcare loans of USD 8.9 billion), regulatory penalties, litigation and public budgets.

This is an analytic judgement (claims C-009, C-038). It is not a forecast, probability, capital assessment or bank-specific loss model.

## Scenario assumptions

| Scenario | Assumption | Evidence basis | Boundary |
|---|---|---|---|
| SC-001 Common digital-dependency failure | A shared EHR, clinical cloud, identity or claims platform used concurrently by many providers is compromised | [17] [25] [32] [37] [68] | No named provider, duration, probability or loss |
| SC-002 Targeted operational disruption | Ransomware or destructive intrusion forces shutdown at a major hospital group, pathology or diagnostic provider | [20] [31] [33] [39] [69] | Single operator; no clinical-outcome assumption |
| SC-003 Third- or fourth-party concentration | A manufacturer, distributor or outsourced laboratory serving many providers is disrupted or suspended | [1] [3] [12] [15] [27] [28] | No named supplier assumed to fail |

## Case study evidence - Dutch Screening Laboratory Breach

Primary sources: Bevolkingsonderzoek Nederland notices of 19 and 29 August 2025 [26] [27], its 2025 annual accountability report pp. 6, 12 and 25-26 [28], and the IGJ finding of 13 May 2026 [29]. All are Tier 1. The case trigger (July 2025) precedes the reporting period; the care-continuity consequence (22 December 2025) and regulatory finding (13 May 2026) fall within it. No incident cost, clinical outcome or attacker identity is disclosed. Claims C-042 to C-047.

## Source-handling controls

- No leaked dataset, leak-site content, patient record or personal health information was accessed. Attacker-claimed record counts (for example in the McKesson case) are excluded because they are not confirmed by Tier 1 or Tier 2 sources.
- Breach-notification figures are recorded as notification populations, not as evidence of root cause or financial outcome.
- Media-reported clinical-impact statements about the 2024 Synnovis attack are recorded only as a limitation (claim C-070); no patient harm is attributed to any incident.
- Embedded instructions in retrieved pages were treated as data; none were acted on.
- Where an official name contains a restricted word, the name appears only in the source and regulatory registers; report and slide text use neutral descriptors.

## Material gaps and limitations

| Gap | Effect on conclusions | Coverage row |
|---|---|---|
| No in-period EU or UK provider cost disclosure | Financial chapter relies on listed-company filings and penalties | operational_and_financial_outcomes |
| No telehealth incident with disclosed outcome | Telehealth treated as a gap, not as low exposure | sector_footprint |
| AZ Monica impact detail only in Tier 3 media | Medium confidence on hospital-level detail; occurrence confirmed by Tier 1 | threats_and_named_incidents |
| McKesson scope undetermined | Distribution subsector coverage partial | threats_and_named_incidents |
| Boston Scientific quantification due 28 October 2026 | Second manufacturer effect unquantified at cut-off | operational_and_financial_outcomes |
| Insurance recoveries undisclosed | Insurance channel described as unavailable | operational_and_financial_outcomes |
| Partial extracts of some legal texts | Annex scope from national authority summary; dates from Commission pages; recorded per row | systemic_dependencies_and_regulation |

## Validation sequence

The evidence-only research-bundle validation was run after the source register, claim ledger, metric dictionary, regulatory register and scenario register were complete and before the report was finalised and before any slide specification existed. It returned PASS for evidence structure only. Full-stage, deck, publication and release validations are recorded in 11_presentation_qc.json and 12_run_manifest.json.

## Correction log

| Date | Change | Reason |
|---|---|---|
| 15 October 2026 | ENISA NIS360 reference changed from the news page to the full May 2026 report | News page URL contained a restricted word; full report provides page locators |
| 15 October 2026 | West Pharmaceutical product description limited to company segment names | Earlier description was not supported by a retrieved source |
| 15 October 2026 | AZ Monica incident evidence paired with Tier 1 parliamentary record and labelled Tier 3 for impact detail | Primary hospital statement not retrievable |
| 15 October 2026 | Stryker Q1 2026 results source moved from an aggregator page to SEC Exhibit 99.1 (Tier 1) | Editorial challenge objection O10 |
| 25 October 2026 | Revision 2: slide readout redesigned with charts and diagrams; metrics M-028 to M-036 and judgement C-071 added; report gains the Stryker guidance range and an outage-versus-stock-cover table in Chapter 4; editorial challenge objections E-01 to E-11 resolved (C-071 reworded so that the comparison covers manufacturers only and states a days-not-weeks margin with no stock-out reported) | User request for a more visual readout; every new plotted value traced to an existing Tier 1 source, or labelled media-reported where Tier 3 |
