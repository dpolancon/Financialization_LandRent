# Stale Path And Duplicate Artifact Audit

Date: 2026-05-29

Scope: assessment only. No stale paths, drafts, prompts, or folders were edited, moved, archived, renamed, or deleted.

## Stale `05_expansion` References

Detected references:

- `04_review_artifacts/06_expansion/repo_tidying_audit.md:26`: lists `04_review_artifacts/05_expansion/` as a created folder.
- `04_review_artifacts/06_expansion/repo_tidying_audit.md:84`: recommends using `04_review_artifacts/05_expansion/review_expansion_opportunities.md`.

Assessment: stale. The active expansion folder is `04_review_artifacts/06_expansion/`.

Recommendation after final draft stabilization: patch those references to `06_expansion` or regenerate the tidying audit.

## Other Stale Path References

Detected `05_skills/` references:

- `04_review_artifacts/00_protocol/phase3_synthesis_protocol.md`
- `04_review_artifacts/05_reports/phase3a_execution_report_2026-05-29.md`

Assessment: historical reports and protocol text refer to an older path. The active skill folder is `SKILLS/`.

Recommendation after final draft stabilization: either leave them as historical provenance or add a brief correction note in a final wrap-up README section.

## Multiple Active Drafts With Unclear Priority

Files in `06_drafts/`:

- `v1_systematic_review_draft.md`
- `v1_systematic_review_draft_reference_validated.md`
- `v1_systematic_review_draft_scholarly_humanized.md`

Assessment: the active draft is clear only because the current task explicitly names `v1_systematic_review_draft_scholarly_humanized.md`. The filenames alone do not identify a canonical current draft.

Recommendation: after expansion, produce `v1_systematic_review_draft_expanded.md` and update an active artifact map. Do not delete prior drafts until the expanded draft is reviewed.

## Duplicated Prompt Or Skill Files

Files with overlapping workflow roles:

- `SKILLS/codex_prompt_bootstrap.md`
- `SKILLS/SYSTEMATIC_REVIEW_ORCHESTRATOR.md`
- `SKILLS/SKILL_SYSTEMATIC_REVIEW_LANDRENT.md`
- `SKILLS/SKILL_PHASE3_LANDRENT_SYNTHESIS.md`
- `SKILLS/SKILL_drafting_systematic_review.md`
- `SKILLS/SKILL_editing_systematic_review.md`

Assessment: not duplicates in a destructive sense. They represent workflow evolution. The risk is agent confusion if a future prompt does not name the active skill.

Recommendation: keep all files for provenance, but use `SKILL_drafting_systematic_review.md`, `SKILL_PHASE3_LANDRENT_SYNTHESIS.md`, and `SKILL_editing_systematic_review.md` as the active final-pass skills.

## Old Weak Draft Files

- `06_drafts/v1_systematic_review_draft.md` is superseded by later validation and humanization drafts.

Assessment: should remain for audit history until final draft stabilization.

Recommendation: archive later, not now.

## Stale README Claims

- `README.md` is minimal and not wrong, but it does not name the active draft, note layers, expansion folder, or final-pass path.

Assessment: underspecified rather than stale.

Recommendation: after final wrap-up, add a short active-artifact section. Do not edit README in this pass.

## Obsolete Bootstrap Prompts

- `SKILLS/codex_prompt_bootstrap.md` is a legacy first-pass artifact.

Assessment: useful for audit history, not active guidance.

Recommendation: archive later or mark as legacy in README after final draft stabilization.

## Orphan Or Ambiguous Artifacts

- `07_pdf_outputs/v1_systematic_review_draft_scholarly_humanized.pdf` exists, but the active final prose path is still Markdown under `06_drafts/`.
- No original source PDFs were found in this assessment, only the rendered review PDF output.

Assessment: the PDF output is a derived draft artifact, not citation evidence. Original source PDFs remain needed for final citation closure.

Recommendation: regenerate PDF outputs only after the expanded draft and final edits are stable.

## Files That Should Be Archived Later

- Superseded v1 draft variants after final expanded draft approval.
- Old bootstrap prompt after final workflow documentation is stable.
- Rendered PDF outputs from pre-final drafts.
- Historical path-mismatch reports only if they are replaced by a final provenance report.

No archive action was taken in this pass.
