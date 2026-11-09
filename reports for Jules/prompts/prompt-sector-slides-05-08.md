Produce slides 05-08 of the {SECTOR} edition of the 12-slide "Sector Cyber Resilience & Credit Intelligence" briefing as one .pptx file. Work end to end without asking for approval. Do not start any new research, web search or data validation.

ATTACHED FILES
- Banking_Slide_05-08.pptx: the layout template. Keep every shape, position, colour, font and slide number; change only the text and the speaker notes.
- sectorial-analysis-new-method.md: defines what each slide must contain (05 Geopolitical Cyber Threat Outlook, 06 Major Cyber Incidents & Lessons Learned, 07 Control Weaknesses & Resilience Priorities, 08 Regulatory & Supervisory Resilience Expectations).
- {SECTOR}_Q01-Q15_merged.md: the only evidence base. Use Q07 for slide 05, Q02 and Q03 for slide 06, Q03, Q04 and Q11 for slide 07, and Q06 for slide 08, plus the registers (INC, THR, CTL, GEO, REG, FIN, BMK).
- Optional: {SECTOR} complementary file(s). Use them only where the merged research is silent; where the two disagree, prefer the Tier 1 source.

AUDIENCE
Senior Credit Officers (SCO) and Credit Committees. Each slide must stand on its own without a presenter.

SLIDE CONTENT (keep the banking zone structure)
- 05 Geopolitical cyber pressure on {sector}:
  - Summary band.
  - Three columns of four items each: "How the threat changes", "Contexts shaping exposure", "SCO escalation signals".
  - Four "Areas of heightened exposure" tiles (subsectors).
  - Bottom message starting "Nationality alone provides an unreliable proxy for geopolitical exposure."
- 06 Major cyber incidents and lessons learned. Replace the banking topic with the method's Slide 06 content, in the same three-column layout:
  - "Five defining incidents": three blocks; combine incidents so that all five of the research's top five appear.
  - "Exploited weaknesses": four items.
  - "Consequences and lessons": three items.
  - Bottom message: when a borrower with the same weaknesses becomes a credit concern.
  - If one of the research's top five is non-cyber (for example a geopolitical supply event), move it to slide 05 and say so in the notes.
- 07 Where {sector} resilience is most exposed:
  - Five-row table: Exposure area | Why the sector is exposed (cite the observed attack) | Evidence of effective resilience.
  - Four evidence anchors: figure plus caption.
  - Keep the banking bottom message.
  - Footer with the evidence cut-off.
- 08 Regulatory landscape and resilience expectations for {sector}:
  - EU, UK and US instruments, with one note line for other material rules.
  - Five "Common sector expectations".
  - Four exposure tiles.
  - Bottom message.
  - Footer with the evidence cut-off.
  - Use statutory maximum fines only if the research states them. Otherwise show observed penalties and legal status, and relabel the tile header "OBSERVED PENALTIES AND STATUS, NOT EXPECTED LOSSES".
- Header on every slide: "SECTORIAL CREDIT INTELLIGENCE  /  {SECTOR IN CAPITALS}".
- Evidence cut-off: the research's stated cut-off. If none is stated, use the gap-fill access date as "(research access date)".

METHOD
1. Unzip the template. In each ppt/slides/slideN.xml, replace the <a:t> text runs one for one, by position. Do not add or delete runs or shapes.
2. Keep each new text no longer than the banking text it replaces, so nothing overflows.
3. Escape XML characters.
4. Rewrite each slide's speaker notes:
   - the slide's purpose;
   - evidence distinctions and limitations;
   - the source question IDs and S- IDs from the research;
   - the evidence cut-off.
5. Repack with `zip -qXrD`, which excludes folder entries.
6. Run the pptx validator with --original set to the template.

LANGUAGE
- English (UK). Direct, impersonal, active voice. Credit language.
- Define acronyms at first use on each slide.
- Never use "serious", "critical", "extreme" or "verified".
- Never use the em dash or en dash; use a spaced hyphen.
- No sector or bank names left over from the banking template.

CHECKS BEFORE DELIVERY
- Run the validator and the language-rule check.
- Grep the slide text for "bank".
- Render every slide to an image and fix any overflow, overlap or wrapped numbers you introduced. Shorten text; do not move shapes.

OUTPUT
- Deliver {SECTOR}_Slide_05-08.pptx.
- Then give a short summary:
  - what each slide shows;
  - any deviation from the banking layout or the method;
  - figures you derived, such as sums;
  - which content came only from a complementary file.
