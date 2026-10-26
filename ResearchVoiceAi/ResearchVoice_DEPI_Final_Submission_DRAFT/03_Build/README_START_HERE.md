# ResearchVoice AI — DEPI individual workflow documentation / Batch 2

**Five one-page component-owner documents** based on Phase 4 n8n JSON and Phase 2 Solution Design.

**Important instructor exception:** This is ONE integrated n8n workflow divided into FIVE documented functional ownership areas, not five independent deployed workflows. The team reports instructor approval of this exception; attach written proof if available.

## Individual ownership map
- C1 — Study & Variable Schema — [Member 1 — assign]
- C2 — Voice / Text Intake & Privacy — [Member 2 — assign]
- C3 — Schema-Constrained Extraction — [Member 3 — assign]
- C4 — Independent QA & Monitoring — [Member 4 — assign]
- C5 — Human Approval & XLSX Export — [Member 5 — assign]

## Status and evidence integrity
- These one-page documents are editable draft specifications with actual node chains, prompt references, safe failures, and a test matrix.
- Rows labeled **Observed in shared demo** refer to existing joint demonstration evidence; they do **not** certify that each member independently ran all five cases.
- Rows labeled **Formal record needed** have no verified individual-case test artifact yet.
- The embedded image is a crop of an actual Phase 4 n8n execution canvas and is an **overview**, not a focused component screenshot. Replace with a focused node screenshot for each owner before final submission.
- Only synthetic/de-identified demonstrations. Voice is sent to Telegram/Groq before transcript content can be screened.
- The LangSmith QA checkpoint does **not** yet trace every individual model call/step as requested by the guideline.

## Required next actions
1. Assign all five owners and the Team Lead, Integration Owner, Evaluation Owner.
2. Each owner replaces the overview with a close-up n8n screenshot of their node path.
3. Each owner logs 3 normal, 1 edge, 1 unsafe outcomes (expected vs actual) in the companion test workbook, linking to evidence. Existing valid runs may count if fully documented; do not fabricate runs.
4. Review component ownership with instructor given the single-workflow exception.
5. Proceed to the three end-to-end scenarios, calibration against two human reviewers, KPI actuals, Test Report and backup video.

**Sources:** DEPI Graduation Project Guideline (Oct 2026), ResearchVoice AI Phase 4 n8n JSON, joint Telegram/n8n screenshots shared 26 Oct 2026, Phase 2 Solution Design.
