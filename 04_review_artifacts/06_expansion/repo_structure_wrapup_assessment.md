# Repo Structure Wrap-Up Assessment

Date: 2026-05-29

Scope: non-destructive repository-structure assessment for the final systematic-review wrap-up. No files were moved, deleted, renamed, or overwritten outside `04_review_artifacts/06_expansion/`.

## Current Repo Layers

- source/intake layer: `02_LitRev_Sistematica/`, especially `02_LitRev_Sistematica/04_indexes/`.
- atomic question-note layer: `03_notes/questions/`, with 98 per-paper notes.
- consolidated paper-note layer: `03_notes/papers/`, with 14 source-level consolidated notes.
- cluster synthesis layer: `03_notes/clusters/`, with 32 thematic cluster notes.
- extraction/matrix artifact layer: `04_review_artifacts/02_extraction/`.
- synthesis and memo-architecture artifact layer: `04_review_artifacts/03_synthesis/` and `04_review_artifacts/04_memo_architecture/`.
- draft layer: `06_drafts/`.
- validation layer: `06_drafts/reference_validation/`.
- expansion layer: `04_review_artifacts/06_expansion/`.
- skills layer: `SKILLS/`.

## Assessment

### What Is Tidy

- The note layers are now cleanly separated: `questions` is atomic provenance, `papers` is the main reading layer, and `clusters` is thematic synthesis.
- The draft layer is separate from review artifacts, which reduces the risk of confusing prose outputs with extraction infrastructure.
- The reference-validation outputs are isolated under `06_drafts/reference_validation/`.
- The active expansion folder is `04_review_artifacts/06_expansion/`, and it already contains the paragraph-level expansion plan and repo-tidying audit.
- The source index, question index, and cluster index create a stable route from source ID to paper notes, question notes, and cluster notes.

### What Is Confusing

- `06_drafts/` contains several v1 draft variants. Their sequence is recoverable, but not obvious without an active artifact map.
- `04_review_artifacts/06_expansion/repo_tidying_audit.md` still contains stale references to `04_review_artifacts/05_expansion/`.
- Older reports and protocol files contain stale `05_skills/` references even though the active skill folder is `SKILLS/`.
- `SKILLS/` contains legacy bootstrap/orchestrator files as well as the newer Phase 3 synthesis skill. This is useful for audit history but can confuse an agent if the active skill is not specified.
- A PDF exists under `07_pdf_outputs/`, but original source PDFs were not found in the working tree during this assessment.

### What Is Redundant

- The initial weak draft, reference-validated draft, and scholarly-humanized draft all remain in `06_drafts/`. They should remain for audit history until the expanded draft is stabilized.
- Prior phase reports repeat some path and status information. They are useful provenance but should not govern the final pass.
- The consolidated paper notes duplicate material from question notes by design. They should be treated as a reading layer, not a replacement for provenance.

### What Is Risky For The Final Pass

- The final expansion pass could accidentally use the wrong draft if it does not explicitly start from `v1_systematic_review_draft_scholarly_humanized.md`.
- Stale `05_expansion` references could route a future agent toward a non-active folder.
- Stale `05_skills` references could route a future agent toward nonexistent or renamed skill paths.
- Citation closure is not ready for publication because original source PDFs are still not available as a validation base.
- The final pass must not cite NotebookLM notes, cluster notes, consolidated paper notes, or expansion plans as sources.

### What Should Remain Untouched

- `03_notes/questions/`: atomic provenance layer.
- `03_notes/clusters/`: thematic synthesis layer.
- `03_notes/papers/`: consolidated reading layer.
- `04_review_artifacts/02_extraction/`: extraction matrix and ledgers.
- `04_review_artifacts/03_synthesis/`: synthesis artifacts.
- `04_review_artifacts/04_memo_architecture/`: paragraph-function architecture.
- `06_drafts/reference_validation/`: validation ledger and audit.
- `SKILLS/`: skill/protocol history.

### What Should Be Cleaned Only After Final Draft Stabilization

- Archive superseded drafts in `06_drafts/` after the final expanded version is accepted.
- Replace stale `05_expansion` references with `06_expansion`.
- Normalize stale `05_skills` references to `SKILLS/` in historical reports only if those reports are intended to remain active guidance.
- Add a short README section that names the active draft and active artifact map.
- Decide whether the rendered PDF in `07_pdf_outputs/` should be regenerated from the final draft or archived as an earlier output.

## Readiness Judgment

Repo structure is conditionally ready for the final systematic-review wrap-up. The next pass can run without ambiguity if it is explicitly bound to:

- active draft: `06_drafts/v1_systematic_review_draft_scholarly_humanized.md`;
- active expansion plan: `04_review_artifacts/06_expansion/review_expansion_opportunities.md`;
- main reading layer: `03_notes/papers/`;
- provenance layer: `03_notes/questions/`;
- thematic synthesis layer: `03_notes/clusters/`;
- citation validation layer: `06_drafts/reference_validation/`.

The main condition before final circulation is source-PDF restoration and page-level citation closure.
