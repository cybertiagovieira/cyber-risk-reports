# Manufacturing Cyber Sectorial Analysis - Evidence Pack

**Reporting period:** 1 September 2025 to 16 October 2026
**Evidence cut-off:** 16 October 2026
**Analytical boundary:** External public data only
**Audience:** 1LoD operational management and Risk Committee

This pack is supporting audit material for 14_sectorial_report.md. It summarises the evidence base, its quality and the decisions taken on contested items. Full locators, methods and limitations are in 02_source_register.csv; claim-level traceability is in 03_claim_ledger.json.

## Evidence base summary

| Measure | Value |
| --- | --- |
| Sources registered | 96 |
| Tier 1 | 70 |
| Tier 2 | 6 |
| Tier 3 | 20 |
| Claims in ledger | 68 |
| Metrics | 29 |
| Regulatory milestones | 27 |
| Scenarios | 3 |
| Access date for all sources | 16 October 2026 |

## Evidence-led conclusions

1. Production loss in the period ran mainly through IT dependency and precautionary shutdown. JLR, Asahi, Stryker and Boston Scientific all describe IT-side incidents that stopped or slowed manufacturing; Dragos found no Q2 2026 ransomware case reaching control-system manipulation. [S-001; S-016; S-021; S-027; S-039]
2. Direct OT compromise in the period is evidenced for fielded products rather than factories: CERT-FR reported numerous compromises of refrigeration controllers from two manufacturers on 12-13 October 2026. [S-035]
3. The JLR case shows the full transmission chain from IT shutdown to supplier cascade, bank liquidity, state guarantee and national output. [S-001 to S-013]
4. Quantified financial outcomes are dominated by lost output and cash; labelled response costs are smaller. [S-004; S-006; S-019]
5. Supplier insolvency caused by a cyber incident is not evidenced in official sources; the German Government holds no such information. [S-047]
6. Regulation reaches most manufacturers through product law and contracts; NIS2 coverage is limited to named activities but large where it applies (4,739 German manufacturing registrations). [S-049; S-045; S-057; S-063; S-066]

## Source-quality notes and decisions

| Item | Decision | Reason |
| --- | --- | --- |
| JLR attribution | Recorded as unconfirmed claim only | Only Tier 3 reporting of a claim; company and NCA did not confirm [S-015] |
| JLR economy-wide loss | Reported as modelled benchmark | CMC model; organisation counts differ between sections (over 5,000 vs more than 2,700) [S-010] |
| JLR revenue and cash effects | Reported with multiple-cause caveat | Company cites tariffs and Jaguar wind-down as well as the incident [S-004; S-006] |
| GBP 260 million | Derived sum of two quarters of the same expense line | Same company, currency and statistic; full-year total not disclosed |
| Stryker mechanism and claim | Tier 3 context; filings used for facts | Wipe mechanism and Iran-linked claim not confirmed by company or US government [S-021; S-023; S-024] |
| Hasbro manufacturing effect | Not asserted | 8-K does not mention manufacturing; vendor blog did [S-031] |
| French controller scale | Tier 3 relay of ministerial figure | CERT-FR confirms numerous compromises without a count [S-035; S-036] |
| Fairlife, Bridgestone, German textile insolvency | Excluded as named incidents | Tier 3 only [S-033; S-038; S-048] |
| US PLC advisory | Title from Tier 1; content from vendor summary | CISA page did not render; named sectors exclude manufacturing [S-089; S-090] |
| NIS2, CER, CRA, PLD article content | EUR-Lex metadata plus reproductions | EUR-Lex bodies did not render in the retrieval tool [S-049; S-050; S-054; S-055; S-059; S-066] |
| AI Act amendment dates | Tier 3 with Tier 1 memorandum | EUR-Lex text not rendered; UK memorandum confirms machinery changes [S-060; S-061] |
| CMMC phases | Federal Register effective date; phases from commentary | Programme-rule phases not read in primary text [S-084; S-085] |
| CIRCIA and chemical security status | Secondary sources | No primary 2026 status page retrieved [S-086; S-087; S-088] |

## Scenario assumptions

| Scenario | Assumption | Evidence basis | Boundary |
| --- | --- | --- | --- |
| Common digital-dependency failure | Multi-day loss or misuse of a shared enterprise platform across many manufacturers | Administrative-tool wipe; manufacturer software outage at many customers; Dragos IT-dependency finding [S-024; S-025; S-037; S-039] | No in-period multi-day common-platform outage across many manufacturers found |
| Targeted operational disruption | Four- to eight-week precautionary stop at one large manufacturer | JLR and Boston Scientific [S-001; S-004; S-010; S-027] | Duration informed by one case |
| Supply-chain concentration | Compromise of a supplier layer reaches many customers | French controllers; Egide via IT provider; ICS ecosystem counts [S-035; S-034; S-039] | Propagation in the French case was through exposure, not a vendor breach |

No probabilities are assigned.

## Monitoring priorities

- Boston Scientific Q3 results on 28 October 2026 and any quantification of incident cost.
- Official counts, attribution and vendor remediation for the French controller campaign.
- Any official attribution of a supplier insolvency to a customer's cyber incident.
- Product-security reporting statistics from ENISA's Single Reporting Platform.
- UK Bill Royal Assent; liability-directive transposition by 9 December 2026; Machinery Regulation application on 20 January 2027.

## Correction log

- Report draft: "first UK cyber incident recorded by national statistics" removed as unsupported.
- Report draft: Stryker restoration period changed from "under four weeks" to "about four weeks" (11 March to 9 April 2026).
- Report draft: Q3 cash-outflow reference corrected to the Q3 release.
- Reference list: a law-firm title containing a restricted word was neutralised in the report; the original title is kept in the source register.
- Editorial challenge (22 objections): slide 5 and report wording on JLR volumes and cash now record mixed causes; statistics-office wording limited to relayed trade-body attribution; Asahi JPY 17 billion reclassified as incident-related expenses; Judgement 3 lowered to medium with a like-for-like CMC comparison; Stryker renamed "global IT disruption" with mechanism and claim marked unconfirmed; Judgement 4 rewritten and lowered to low; UK NIS scope now cited to SI 2018/506 schedules; structure precedence recorded in methodology; CRA exclusions completed; Data Act design-duty clause removed for lack of a rendered primary text; CMMC phase cited to 32 CFR 170.3(e); law-firm source replaced by the EUR-Lex record of Implementing Regulation (EU) 2025/2392; slide acronyms defined.
- Second editorial pass: Scenario 1 severity anchor reworded; Asahi comparability note corrected; CMMC horizon citation moved to 32 CFR 170.3(e); structure note cites the run instruction of 16 October 2026.
