# Healthcare - Cyber Sectorial Analysis

**Edition:** baseline, revision 2 (25 October 2026). **State:** see 12_run_manifest.json. **Supersedes:** the slide design in `healthcare/2025-09_2026-10/`, which is retained unchanged; evidence cut-off and findings are the same.
**Reporting period:** 1 September 2025 to 14 October 2026. **Evidence cut-off:** 14 October 2026. **Report date:** 14 October 2026.
**Geography:** global, primary focus EU/EEA/UK; North American evidence for comparison. **Audience:** 1LoD operational management and Risk Committee.
**Boundary:** public external data only; no internal, client, patient or bank-specific information; no leaked data accessed or reproduced.
**Case study:** Dutch Screening Laboratory Breach (Clinical Diagnostics NMDL, selected after discovery; trigger July 2025, consequences in period).

## Read first

1. `15_sectorial_report.docx` (or `14_sectorial_report.md`) - full standalone report with sources, exact dates and locators.
2. `13_cyber_sectorial_analysis.pptx` - seven-slide analytical readout. Slides carry no sources or dates of publication by design; the report is the auditable companion.

## Package contents

| Artefact | Purpose |
|---|---|
| `00_input_contract.json` | Scope, period, cut-off and destination |
| `01_research_plan.md` | Decision questions, coverage map, case selection |
| `02_source_register.csv` | 73 sources with dates, tiers, locators, limitations |
| `03_claim_ledger.json` | 71 claims with sources, confidence and alternatives |
| `04_metric_dictionary.csv` | Metric definitions and comparability groups |
| `05_regulatory_relevance_register.csv` | Legal status, applicability and milestones |
| `06_scenario_assumption_register.csv` | Three distinct stress scenarios |
| `07_executive_story.md` | Slide storyline and element mapping summary |
| `08_slide_spec.json` | Element-level slide specification |
| `09_evidence_pack.md` | Evidence audit pack |
| `10_visual_review.json` | Rendered-slide and Word-page inspection record |
| `11_presentation_qc.json` | Quality gates (structural, editorial, delivery kept separate) |
| `12_run_manifest.json` | Hashes, gates and delivery receipt |
| `13_cyber_sectorial_analysis.pptx` | Seven-slide readout |
| `14_sectorial_report.md` | Full report source |
| `15_sectorial_report.docx` | Full report (Word) |
| `16_editorial_review.json` | Separate editorial challenge with objections, resolutions and hashes |
| `17_research_coverage.csv` | Coverage and targeted-gap results |

## What changed in revision 2

- Slides redesigned: headline-figure strip, incident timeline, small-multiple charts, scenario diagrams with an outage-versus-buffer chart, case timeline with capacity and notification charts, dependency chains with a regulatory roadmap, and a priority matrix. Colour scheme unchanged.
- Evidence additions for the charts: metrics M-028 to M-036 and judgement C-071, all traced to sources already in the register.
- Report: Stryker guidance range added; new Chapter 4 table "Outage length against stock buffers (observed single cases)".

## Principal limitations

No in-period EU or UK provider disclosed an incident cost; public financial evidence is concentrated in listed, mostly US-domiciled manufacturers and processors. AZ Monica impact detail relies on media relaying hospital statements. Boston Scientific's quantified effect falls after the cut-off. No patient harm is attributed to any cyber incident. No schedule was created or changed by this run.
