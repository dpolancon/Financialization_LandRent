# Reference Validation Plan

## Scope

Validate references in `06_drafts/v1_systematic_review_draft.md` without rewriting the argument, broadening the corpus, or overwriting the original draft.

## Source Hierarchy Applied

1. Original source PDFs: searched locally, but no PDFs were present in the working tree.
2. Index artifacts: `I03_source_index.md`, `I02_per_paper_question_index.md`, `I01_cluster_question_index.md`.
3. Extraction artifacts: `extraction_matrix.csv`, concept/mechanism/thematic artifacts.
4. Phase 1 and Phase 2 notes in `03_notes`.
5. NotebookLM routing: unavailable because auth check failed with `token_fetch=false`.
6. Draft text: used only as the object being validated.

## Procedure

- Parse P01-P43 from the draft.
- Extract existing author-year citations and page references.
- Map citations to source IDs through source registry and index artifacts.
- Inspect special unresolved cases P17 and P33 against paper notes and extraction rows.
- Confirm P14 and P31 as source gaps rather than filling them from outside the bounded corpus.
- Create a non-destructive reference-validated draft copy only where page/citation repairs are defensible.

## Patch Policy

The original draft is untouched. Repairs are written only to `v1_systematic_review_draft_reference_validated.md`.
