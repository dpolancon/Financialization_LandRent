# Stale Path Cleanup Plan

Date: 2026-05-29

This plan records stale routing references without moving, deleting, archiving, or patching historical files.

## Stale References Detected

| Stale reference | Location | Classification | Recommendation |
|---|---|---|---|
| `05_skills/` | `04_review_artifacts/00_protocol/phase3_synthesis_protocol.md` | historical_do_not_edit | Leave during expansion. Patch only if this protocol is promoted back to active guidance. |
| `05_skills/` | `04_review_artifacts/05_reports/phase3a_execution_report_2026-05-29.md` | historical_do_not_edit | Preserve as historical report. Do not patch before final draft stabilization. |
| `04_review_artifacts/05_expansion/` | `04_review_artifacts/06_expansion/repo_tidying_audit.md` | patch_after_final_draft | Historical audit from the consolidation pass. Do not govern active routing. Patch or archive after the final draft stabilizes. |
| `04_review_artifacts/05_expansion/` | `04_review_artifacts/06_expansion/repo_structure_wrapup_assessment.md` | historical_do_not_edit | Assessment correctly identifies the stale path. No patch needed now. |
| `05_expansion` warning | `04_review_artifacts/06_expansion/v1_systematic_review_expansion_audit.md` | historical_do_not_edit | The warning is valid and should remain. |
| `05_expansion` warning | `04_review_artifacts/06_expansion/stale_path_and_duplicate_artifact_audit.md` | historical_do_not_edit | The audit is supposed to record this stale path. |

## Ambiguous Role References Checked

| Ambiguity | Result | Classification | Recommendation |
|---|---|---|---|
| `01_memo_ejecutivo_V0.1/` treated as active draft | No active routing file should treat it as the active systematic-review draft after this pass. | safe_to_patch_now | README and manifest now classify it as the pre-systematic-review memo layer. |
| `02_LitRev_Sistematica/` treated as active notes | Active routing should treat it as development, index, and source-routing infrastructure only. | safe_to_patch_now | README and manifest now route active notes through `03_notes/`. |
| `04_review_artifacts/05_expansion/` as active expansion folder | Stale references remain only in historical/audit files. | patch_after_final_draft | Do not use. Active folder is `04_review_artifacts/06_expansion/`. |
| `05_skills/` as active skill folder | Stale references remain only in historical Phase 3A artifacts. | historical_do_not_edit | Do not use. Active folder is `SKILLS/`. |

## Cleanup Timing

Patch now:

- README routing.
- Active artifact map routing.
- Final pass plan routing.
- Final write-up manifest.

Patch after final draft stabilization:

- Historical audits that still point to `04_review_artifacts/05_expansion/`, if they are kept as active guidance.
- Any old report promoted into the active reading path.

Archive after final draft stabilization:

- Superseded drafts, after the final draft and final citation audit are accepted.
- Legacy bootstrap prompts, if the project owner wants a cleaner active skill folder.

Do not edit:

- Source notes.
- Cluster notes.
- Consolidated paper notes.
- Extraction matrices.
- Reference-validation ledgers.
- Skills.
