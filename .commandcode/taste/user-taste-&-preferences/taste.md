# User Taste & Preferences
- Requires strict anti-hallucination discipline: AI-generated artifacts must derive only from explicitly documented source requirements — never invent features, behaviors, error codes, API endpoints, error message text, or expected results. Confidence: 0.9
- Prefers traceability: every claim/test case should cite its explicit source (e.g., PRD line number or requirement ID) so it can be verified against the original. Confidence: 0.85
- Prefers explicit gap-flagging: where source material lacks critical details, this must be documented as "Insufficient information to determine" rather than filled with assumptions or invented defaults. Confidence: 0.9
- Prefers a structured, multi-step workflow: extract verified facts → identify missing info → generate from verified facts → self-validate against stated rules. Confidence: 0.75
- Expects a final self-validation pass against explicit rules (e.g., checking for no invented features, no fabricated sources, no unresolved contradictions) before marking work complete. Confidence: 0.75
- Values progressive disclosure: read source files, search for related rule files, explore the working directory for context before producing output. Confidence: 0.7
- Prefers structured output with clear sections (e.g., Verified Facts, Missing Information, Generated Test Cases, Self-Validation Check). Confidence: 0.75
- Uses markdown tables to present structured gap/missing-information analysis. Confidence: 0.7
- Maintains a professional, direct tone that separates verified facts from uncertainty and never presents assumptions as facts. Confidence: 0.7
