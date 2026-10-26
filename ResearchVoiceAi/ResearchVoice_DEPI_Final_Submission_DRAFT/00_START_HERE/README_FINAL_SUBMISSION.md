# ResearchVoice AI — DEPI final-submission folder (DRAFT)

**Prepared:** 27 October 2026  
**IMPORTANT:** This is a **consolidated draft package**, not a completed submission or instructor-approved checkpoint. Do not rename it “FINAL / APPROVED” until all missing human evidence and approvals have been inserted.

## Open these files first

1. **Master_Readiness_and_Signoff.xlsx** — main editable status tracker. Use `Readiness` to track each requirement; `Owners` for the five teammates and shared roles; `Checkpoints` for instructor decisions; `Evidence register` for actual screenshots.
2. **Submission_Readiness_Executive_Brief.pdf** — two-minute status overview.
3. **06_Approvals_and_Signoff/Team_and_Instructor_Signoff.docx** — printable signatures and checkpoint decisions (blank until signed).
4. **06_Approvals_and_Signoff/Instructor_Review_Request.docx** — editable letter asking for review and written confirmation of the permitted single integrated workflow exception.

## Folder structure

| Folder | Contents | Current status |
|---|---|---|
| `01_Business_Discovery/` | One-page Business Brief + KPI Excel | Draft; measurements pending |
| `02_Solution_Design/` | Features, five owner spec cards, integration map, safety/evaluation plan | Draft; owners/roles pending |
| `03_Build/` | 33-node Phase 4 importable JSON, five one-page owner documents + individual 25-test tracker | Working prototype demonstrated; formal owner signoffs pending |
| `04_Evaluation/` | Three scenario briefs, human calibration workbook, Test Report draft, one-page monitoring, seven real screenshots and evidence excerpt | One complicated case observed; independent human scoring and full scenario proof pending |
| `05_Pitch/` | 12-slide deck, five-presenter script, demo runbook, Q&A, readiness checklist | Prepared; replace names and unmeasured claims |
| `06_Approvals_and_Signoff/` | Editable team/instructor signoff and checkpoint review request | Not signed / not approved |
| `07_Guideline_Reference/` | Original 13-page DEPI guideline | Reference |

## Findings already supported by evidence

- Synthetic Phase 4 voice case reached transcript review, generated an unresolved schema mismatch, and produced a soft alert.
- Researcher corrected the HbA1c field and approved XLSX delivery.
- Independent LLM judge rated the **draft before correction**: factual 5, groundedness 5, safety 5, format 3, bias 5; mean 4.6/5, needs review.
- `/monitor` showed one completed judge, one soft warning, one confirmed Excel delivery, 0 hard holds, and 10,490 ms judge-only latency.
- LangSmith `/runs` returned `Run created` and a QA checkpoint was visible in LangSmith.

These observations do not prove accuracy across a cohort, measured time savings, complete per-step tracing, or clinical safety.

## What real people still need to finish

1. **Team Lead:** Enter five owner names and the Team Lead, Integration Owner, Evaluation Owner. Capture instructor's written exception approval (if already received) and checkpoint decisions.
2. **Five component owners:** Replace overview screenshots with focused node screenshots and complete the prescribed three normal, one edge and one unsafe test records per component. Sign each one-page document.
3. **Two independent reviewers:** Score the same frozen synthetic *pre-correction model outputs* using `04_Evaluation/02_Human_Judge_Calibration.xlsx`, then document disagreements and rubric changes. Do not invent scores.
4. **Evaluation Owner:** Add links/execution IDs for all three end-to-end scenario runs, complete the tracing-evidence scope, record the guideline-required hard-pause result, and update dashboard/issue log/Test Report.
5. **Business owner:** Measure actual manual baseline and current workflow KPI results. The earlier 8-minute baseline / 5-minute target are explicitly unmeasured planning assumptions. Never present assumed values as observed savings.
6. **Demo presenter:** Actually record the backup MP4 and rehearse the working synthetic Telegram case. The included runbook is not a recording.
7. **Instructor:** Review and approve checkpoints. The documents do not claim sign-off.

## Security and integrity

Use **fictional or fully de-identified data only**. The current prototype is not fit for real patient data or clinical decisions. Voice recordings pass through Telegram and external Groq transcription before the transcript can be screened. The n8n import includes credential references but no credential values; confirm this again when replacing it with the latest live export. Never include actual API keys in the shared submission.

## Guideline mapping

See `Master_Readiness_and_Signoff.xlsx` and the original guideline, especially the final checklist (p. 7), evaluation rubric (pp. 7–8), Templates A1–A5 (pp. 9–10), and Phase 4 requirements (pp. 5–6). The team reports an instructor-approved exception for one integrated n8n workflow with five owned functional stages; the printed guideline normally requires five connected workflows. The instructor's written acceptance should be attached.
