# Reference Validation Audit

## Files Inspected

- `06_drafts/v1_systematic_review_draft.md`
- `06_drafts/v1_systematic_review_architecture.md`
- `06_drafts/v1_systematic_review_audit.md`
- `SKILLS/`
- `04_review_artifacts/02_extraction/`
- `04_review_artifacts/03_synthesis/`
- `04_review_artifacts/04_memo_architecture/`
- `03_notes/questions/`
- `03_notes/clusters/`
- `02_LitRev_Sistematica/04_indexes/`
- `05_scripts/`

## Index Artifacts Inspected

- `02_LitRev_Sistematica/04_indexes/I03_source_index.md`
- `02_LitRev_Sistematica/04_indexes/I02_per_paper_question_index.md`
- `02_LitRev_Sistematica/04_indexes/I01_cluster_question_index.md`
- `02_LitRev_Sistematica/config/registry_parsed.json`
- `02_LitRev_Sistematica/config/notebooklm_source_map.json`

## NotebookLM / notebooklm-py Availability

NotebookLM CLI is installed and help was inspected. Authentication failed during `notebooklm auth check --test --json` with `token_fetch=false`, so no NotebookLM query was run. The blocker is stale/expired auth; the safe manual command is `notebooklm login`.

## Source PDFs

No original source PDFs were found in the working tree by recursive PDF search. Validation therefore uses index artifacts, source registry, extraction rows, and note evidence. No paragraph is marked `validated_exact`.

## Source IDs Mapped

Mapped all 14 registered sources: PDF001, PDF002, PDF003, PDF004, PDF005, PDF006, PDF007, PDF008, PDF009, PDF010, PDF011, PDF012, PDF013, PDF014.

## Paragraph Validation Counts

- needs_human_review: 11
- page_ref_repaired: 2
- source_gap_confirmed: 2
- validated_index_only: 28

## P17 Result

Status: `page_ref_repaired`.

The `[citation detail needed]` marker is repaired in `v1_systematic_review_draft_reference_validated.md` using local evidence from `PDF003_Q02`, `PDF003_Q04`, `PDF013_Q03`, and `PDF013_Q04`. Recommended citation: `Hirano and Stiglitz, 2024, pp. 4, 7, 10, 15, 33, 38; Hirano and Stiglitz, 2025c, pp. 1, 2, 16, 17, 19, 29`.

## P33 Result

Status: `page_ref_repaired` with a confirmed source gap for the Latin American implementation clause.

The internal land-taxation claim is supported by `PDF005_Q04` pages 327, 328, 335, 344. The implementation claim about cadastres, informality, municipal capacity, political capture, and legal property regimes is not supported by the bounded corpus and is marked as `[source gap: Latin American institutional implementation requires external comparator literature]`.

## P14 and P31 Source-Gap Confirmation

- P14: `source_gap_confirmed`.
- P31: `source_gap_confirmed`.

No attempt was made to fill these from external literature.

## Citation Repairs Made

Repairs were made only in the non-destructive file `06_drafts/v1_systematic_review_draft_reference_validated.md`:

- P17: replaced `Hirano and Stiglitz, 2025c, [citation detail needed]` with page references.
- P33: added an internal-corpus citation to `Hirano and Stiglitz, 2025a, pp. 327, 328, 335, 344` and clarified the Latin American implementation marker.

## Unresolved References

See `unresolved_reference_gaps.md`. The paragraph-level generic citation-detail markers from P17 and P33 are repaired in the validated copy. Direct PDF verification remains unavailable, so these repairs remain index/extraction-confirmed rather than `validated_exact`.

## Claims Requiring Human Review

Synthesis/appraisal paragraphs without direct citations are marked `needs_human_review` in the ledger where appropriate. These do not necessarily fail validation; they require editorial judgment before publication.

## Editorial Readiness

The reference-validated copy is ready for post-draft editorial cleanup at the level of argument and prose. It is not ready for publication-style citation closure until original PDFs are restored or supplied for direct verification.
