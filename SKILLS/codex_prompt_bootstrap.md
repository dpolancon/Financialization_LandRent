# Codex Prompt — Build Systematic Review Artifacts from Question Notes

You are working in the local repository:

`C:\ReposGitHub\Financialization_LandRent`

Task: build the first-pass systematic review infrastructure from the note repository at:

`notes/questions`

Do not rewrite the notes. Do not draft the full review yet. Create review artifacts that make the review draftable.

## Required outputs

Create:

```text
review_artifacts/
  00_protocol/systematic_review_protocol.md
  00_protocol/inclusion_exclusion_criteria.md
  01_registries/source_registry.csv
  01_registries/question_registry.csv
  01_registries/note_integrity_report.md
  02_extraction/extraction_matrix_template.csv
  02_extraction/concept_dictionary_template.md
  02_extraction/mechanism_ledger_template.md
  03_synthesis/thematic_synthesis_map_template.md
  04_draft/draft_outline_template.md
```

## Required audit

Scan every markdown file under `notes/questions`.

Infer:

- source_id from filename or frontmatter;
- question_id from filename or frontmatter;
- paper_key if available;
- question text;
- whether answer body exists;
- whether page references exist;
- whether the note already separates definitions, mechanisms, causality, variables/parameters, and theory/evidence.

Create `note_integrity_report.md` with:

- number of notes found;
- number of unique source IDs;
- duplicate IDs;
- notes missing metadata;
- notes missing page references;
- notes that look draft-ready;
- notes requiring PDF validation.

## Extraction schema

Use the five locked dimensions:

1. definition;
2. mechanism;
3. causality;
4. variables_parameters;
5. theory_evidence.

The extraction matrix must use one row per claim, not one row per note.

Columns:

```csv
claim_id,source_id,question_id,paper_key,page_ref,dimension,concept,definition,mechanism,causal_chain,variables_parameters,theory_evidence_status,claim_text,project_use,validation_status,reviewer_comment
```

## Review architecture

Use this draft outline:

1. Introduction: why this literature matters for land rent and financialization.
2. Method: corpus, notes, extraction protocol, screening, synthesis.
3. Conceptual objects: land, rent, wealth, capital, real estate, bubble.
4. Mechanism I: land-price inflation and capital-formation crowding-out.
5. Mechanism II: credit expansion, collateral, leverage, and monetary policy.
6. Mechanism III: unbalanced growth and the Land Overvaluation Theorem.
7. Mechanism IV: R versus G, land, and infinite debt rollover.
8. Critical appraisal: assumptions, scope, Latin American transportability.
9. Research agenda: what the Fondecyt project should retain, modify, or reject.
10. Conclusion.

## Guardrails

- Do not conflate land rent, housing rent, land price, real estate value, wealth, and productive capital.
- Do not import external literatures before reconstructing the SHT branch on its own terms.
- Mark all unvalidated claims as `needs_page`.
- Do not draft from unsupported notes.
- Keep artifacts plain Markdown and CSV.
