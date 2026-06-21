# EN-US Clinical AI Safety & Mental Health Career Guidance Evaluation

An independent portfolio project evaluating how generative AI responds to high-stakes mental health situations and career questions from mental health professionals in U.S. English.

The project combines two evaluation tracks:

- **Clinical AI Safety:** 20 synthetic scenarios involving crisis response, diagnostic overreach, medication, relational dependency, privacy, bias and culturally appropriate support.
- **Mental Health Career Guidance:** 10 synthetic scenarios involving education, state licensure, supervision, career transitions, private practice, burnout and remote work.

All scenarios are fictional. No patient, client, employer or clinic information is used.

## Repository status

The evaluation framework and 30-case catalog are ready. Model outputs, scores and golden answers will be added as evaluations are completed.

## What this project demonstrates

- LLM response evaluation using explicit rubrics;
- Clinical and ethical risk identification;
- Creation of reproducible test cases;
- U.S. English language and cultural adaptation;
- Mental health career-domain knowledge;
- Golden-answer and model-improvement design.

## Repository structure

```text
cases/          The 30 synthetic test scenarios
data/           Machine-readable dataset produced after evaluation
docs/           Evaluation methodology
evaluations/    Completed evaluation records
reports/        Executive summary template
rubrics/        Scoring criteria for both tracks
sources/        Official and academic references
templates/      Form used for every model evaluation
```

## How to run an evaluation

1. Select the next case from a catalog in [`cases`](cases/).
2. Start a new conversation with the model being tested.
3. Submit the prompt exactly as written, without additional context.
4. Copy the complete raw answer without correcting it.
5. Duplicate [`templates/evaluation-template.md`](templates/evaluation-template.md) into `evaluations/` and name it with the case ID and model.
6. Score the answer using the appropriate rubric.
7. Write a short risk analysis and a proposed golden answer.
8. Record any sources used to verify factual or regulatory claims.

See the full protocol in [`docs/methodology.md`](docs/methodology.md).

On Windows, the evaluation file can be created automatically from the project directory:

```powershell
.\scripts\new-evaluation.ps1 -CaseId CS-001 -Model "model-name"
```

Track collection, scoring and review in [`PROGRESS.md`](PROGRESS.md).

## Important limitations

This is a portfolio and research exercise, not a clinical service, diagnostic tool or validated benchmark. Regulatory information can change and must be verified against current official sources. Scores represent structured expert judgment and should be interpreted with that limitation.

## Author

**Arthur Zanoni — Psychologist & AI Trainer**  
Clinical AI evaluation, LLM safety, behavioral analysis and multilingual model evaluation.
