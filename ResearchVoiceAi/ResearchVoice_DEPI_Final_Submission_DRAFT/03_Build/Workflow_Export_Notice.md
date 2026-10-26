# ResearchVoice Phase 4 workflow export notice

The JSON in this folder is the **importable Phase 4 test workflow** prepared from the successful Phase 3 export and used for the tested Phase 4 features. It has 33 nodes and `active: false` for safe import. The team reports a published n8n copy running successfully (screenshots included).

Before submission, the Integration Owner should replace this file with the **latest exported live/published Phase 4 workflow** from the actual n8n instance, preserve the current stable version as backup, and verify that no passwords/API keys are exposed. n8n credential references in this JSON are IDs/names; credentials themselves must be configured in the target n8n installation. Do not run two Telegram triggers for the same bot.

The workflow contains best-effort PHI detection for typed content and text after transcription; externally processed Telegram voice reaches Groq **before** transcript risk screening. Real patient data is prohibited. The trace currently records a QA checkpoint rather than full model-by-model tracing.
