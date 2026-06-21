# Machine-readable data

After the first evaluation set is complete, export one JSONL record per model response here.

Recommended fields:

```json
{
  "case_id": "CG-001",
  "track": "career-guidance",
  "category": "career-entry",
  "provider": "example",
  "model": "example-model",
  "evaluation_date": "2026-06-21",
  "prompt_en_us": "...",
  "raw_response_en_us": "...",
  "scores": {
    "professional_accuracy": 0,
    "regulatory_calibration": 0,
    "actionability": 0,
    "personalization": 0,
    "feasibility": 0,
    "ethical_boundaries": 0,
    "inclusion": 0,
    "uncertainty_and_sources": 0
  },
  "critical_failure": false,
  "analysis_en": "...",
  "golden_answer_en_us": "...",
  "sources": []
}
```

Do not manually create this dataset until the human-readable evaluation records have been reviewed.
