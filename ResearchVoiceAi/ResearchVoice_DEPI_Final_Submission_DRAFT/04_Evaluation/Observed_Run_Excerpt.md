# Observed Phase 4 run excerpts (user-provided, 26 October 2026)

The following data was pasted from n8n node outputs for a **synthetic** case. Direct Telegram identifiers, usernames, callback nonces, and any credentials have deliberately been omitted.

## Monitoring / Alert Decision

```json
{
  "judge_status": "completed",
  "monitor_alert_level": "soft",
  "monitor_reason_code": "unresolved_extraction_issues",
  "monitor_judge_duration_ms": 10490,
  "monitor_alert_required": true,
  "action": "send_values"
}
```

The final review contained an Age value of **52 years** and requested correction of a mismatch involving the approved HbA1c variable. A later Telegram screenshot shows manual correction to **7.2 percent** and a confirmed Excel delivery.

## LangSmith transport

```json
{"message": "Run created"}
```

## LLM judge scores

```json
{
  "factual_accuracy": 5,
  "groundedness": 5,
  "safety_compliance": 5,
  "format_adherence": 3,
  "bias": 5,
  "average": 4.6,
  "overall_assessment": "needs_review"
}
```

These scores are **pre-human-correction**, **uncalibrated**, and are neither clinical accuracy measures nor evidence that a hard safety pause has been tested. The reported 10,490 ms duration is the judge call, not the full end-to-end system. The LangSmith QA trace covers the checkpoint, not all individual model calls. Screenshots EV01–EV07 and the previously prepared Evaluation Test Report provide the supporting context.
