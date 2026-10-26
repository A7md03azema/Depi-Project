# ResearchVoice AI — DEPI Graduation | Batch 3: Evaluation & Evidence

**Date:** 26 October 2026  
**Status:** Editable SUBMISSION DRAFTS, not a claim of final guideline completion or instructor sign-off.

## Contents

1. `01_Three_End_to_End_Scenarios.docx` + `.pdf` — a typical, complicated, and unsafe/refusal synthetic scenario, with expected and observed outcomes clearly distinguished. The complicated voice schema mismatch is the only fully observed narrative in this batch.
2. `02_Human_Judge_Calibration.xlsx` — synthetic frozen case briefs, five-dimension rubric, separate Human A and B ratings, formula-driven agreement and AI-vs-human comparison, and an A5 issue log.
3. `03_Evaluation_Test_Report_DRAFT.docx` + `.pdf` — evidence status, observed metrics, limitations, documented safety design, outstanding checkpoint actions and known issues.
4. `04_One_Page_Monitoring_Dashboard_DRAFT.docx` + `.pdf` — one-page *observed* monitoring snapshot with unmeasured KPI actuals clearly labeled.

## Observed and unverified items

- **Observed:** a synthetic 52-year-old with voice HbA1c variable-name mismatch; soft warning for unresolved extraction; human correction to 7.2 percent; successful XLSX delivery after confirmation; LLM-as-judge scores factual 5, groundedness 5, safety 5, format 3, bias 5, average 4.6; one rolling /monitor snapshot with 1 judge, 1 soft warning, 0 hard, 1 delivered XLSX and 10,490 ms judge-only p95; LangSmith `Run created`.
- **Not yet completed:** independent ratings from two teammates; formal execution/proof for all three E2E scenarios; field accuracy and business time baselines/actuals; component owner sign-offs; complete per-stage LangSmith tracing; backup video; instructor phase checkpoints.
- **Important:** pre-Gemini safety rejection skips the QA judge. It is not accurate to present five judge scores for a refusal that never reached Gemini.
- **Previous packages:** Batch 1 has editable business brief / KPI A4 workbook; Batch 2 has five one-page component owner documents and 25-case evidence tracker, plus EV01–EV07 screenshots. Keep those with this package.

## Recommended sequence to complete these files

1. Assign all five component owners and two truly independent reviewers.
2. Have the team record/run prescribed *synthetic-only* normal, edge, and refusal scenarios; attach n8n execution IDs and LangSmith links. Reuse genuine earlier evidence where it accurately matches the formal cases.
3. Freeze original, pre-human-correction AI outputs in `Frozen Cases`. Don't ask the reviewers to score a corrected Excel file as the model's output.
4. Both reviewers score the five dimensions independently in `Ratings!D:E` and provide concrete rationales in `Ratings!I:J`. `Calibration Summary` computes comparison rates. Review disagreements and document any rubric changes.
5. Enter measured baseline and actual KPI data in Batch 1 KPI workbook, refresh the monitoring report, and add the final dashboard screenshot.
6. Update issue statuses and the Test Report with new verified outcomes; collect checkpoint approval and backup demo video.

## Safety and integrity

Use fictional, synthetic or fully de-identified information only. The current prototype is NOT authorized for real patient data, diagnosis, treatment or direct clinical use. Its best-effort regex safeguards are not a full PHI gate; opted-in voice reaches Groq before text screening. The standalone QA trace does not cover every step.

**Source basis:** DEPI “Graduation Project Guideline: AI for Healthcare” (Oct 2026); actual ResearchVoice Phase 4 n8n JSON and Telegram screenshots, n8n monitoring JSON, LangSmith proof from 26 Oct 2026.
