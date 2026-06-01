# Final Write-Up Manifest

Date: 2026-05-29

## Canonical Inputs And Outputs

canonical_input_draft: `06_drafts/v1_systematic_review_draft_scholarly_humanized.md`

canonical_next_output_draft: `06_drafts/v1_systematic_review_draft_expanded.md`

canonical_expansion_plan: `04_review_artifacts/06_expansion/review_expansion_opportunities.md`

canonical_memo_precursor_layer: `01_memo_ejecutivo_V0.1/`

canonical_development_bundle_layer: `02_LitRev_Sistematica/`

canonical_source_routing_indexes: `02_LitRev_Sistematica/04_indexes/`

canonical_reading_layer: `03_notes/papers/`

canonical_provenance_layer: `03_notes/questions/`

canonical_cluster_layer: `03_notes/clusters/`

canonical_extraction_matrix: `04_review_artifacts/02_extraction/extraction_matrix.csv`

canonical_citation_ledger: `06_drafts/reference_validation/paragraph_citation_ledger.csv`

canonical_drafting_skill: `SKILLS/SKILL_drafting_systematic_review.md`

canonical_editing_skill: `SKILLS/SKILL_editing_systematic_review.md`

canonical_synthesis_skill: `SKILLS/SKILL_PHASE3_LANDRENT_SYNTHESIS.md`

## Do Not Use Paths

- `04_review_artifacts/05_expansion/`
- `05_skills/`
- `01_memo_ejecutivo_V0.1/` as an active systematic-review draft
- `02_LitRev_Sistematica/` as an active note layer

## Do Not Edit Paths During The Next Writing Pass

- `00_Intakes/`
- `01_memo_ejecutivo_V0.1/`
- `02_LitRev_Sistematica/`
- `03_notes/`
- `04_review_artifacts/02_extraction/`
- `04_review_artifacts/03_synthesis/`
- `04_review_artifacts/04_memo_architecture/`
- `06_drafts/reference_validation/`
- `SKILLS/`
- `90_zip_files/`

## Final Wrap-Up Sequence

1. Produce `06_drafts/v1_systematic_review_draft_expanded.md` from the active input draft and expansion plan.
2. Audit the expansion in `04_review_artifacts/06_expansion/v1_systematic_review_expansion_audit.md`.
3. Compress and balance the expanded draft if it becomes too long or repetitive.
4. Restore or locate original PDFs and perform page-level citation closure.
5. Normalize bibliography labels, including repeated Hirano-Stiglitz year suffixes.
6. Run a final editorial pass under `SKILLS/SKILL_editing_systematic_review.md`.
7. Produce the final Markdown draft and any PDF or DOCX circulation outputs.

## Stop Conditions

Stop before external circulation if:

- original PDFs or verified source text are unavailable for citation closure;
- any substantive source claim lacks page validation or a source-gap marker;
- NotebookLM notes, cluster notes, or consolidated paper notes are cited as original sources;
- Latin American empirical claims enter the review without an approved external comparator-literature pass;
- bibliography entries remain placeholders;
- multiple draft files could plausibly be treated as the active draft without this manifest.
