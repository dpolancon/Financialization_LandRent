# Skill Toolkit Status

Date: 2026-05-29

## Skills Inspected

| File | Classification | Next-pass status | Rationale |
|---|---|---|---|
| `SKILLS/SKILL_drafting_systematic_review.md` | active_final_pass_skill | Use first | Governs systematic-review drafting, paragraph functions, source discipline, and reconstruction-before-critique sequence. |
| `SKILLS/SKILL_PHASE3_LANDRENT_SYNTHESIS.md` | active_synthesis_skill | Use second | Supplies corpus boundaries, claim extraction discipline, concept distinctions, transportability rules, and anti-scope constraints. |
| `SKILLS/SKILL_editing_systematic_review.md` | active_editing_skill | Use after expansion | Governs post-draft prose editing while preserving claims, citations, markers, and conceptual distinctions. |
| `SKILLS/SYSTEMATIC_REVIEW_ORCHESTRATOR.md` | orchestrator_history | Do not govern next pass | Earlier protocol with historical value, but superseded by the active drafting and Phase 3 synthesis skills. |
| `SKILLS/SKILL_SYSTEMATIC_REVIEW_LANDRENT.md` | orchestrator_history | Do not govern next pass | Earlier operational checklist, useful for project history but superseded for the next writing pass. |
| `SKILLS/codex_prompt_bootstrap.md` | legacy_bootstrap_skill | Do not use | First-pass artifact creation prompt with older path assumptions. |
| `SKILLS/review_matrix_schema.csv` | do_not_use_for_next_pass | Support artifact only | Schema reference for extraction history, not a writing skill. |
| `SKILLS/README.md` | do_not_use_for_next_pass | Reference only | Folder index, not a governing protocol. |

## Active Skill Stack For Next Pass

1. `SKILLS/SKILL_drafting_systematic_review.md`
2. `SKILLS/SKILL_PHASE3_LANDRENT_SYNTHESIS.md`
3. `SKILLS/SKILL_editing_systematic_review.md`

The drafting skill should govern the controlled expansion. The Phase 3 synthesis skill should constrain concepts, claims, and scope. The editing skill should be held for the later cleanup pass, not used to expand argumentation.

## Legacy Or Superseded Skills

- `SKILLS/codex_prompt_bootstrap.md`
- `SKILLS/SYSTEMATIC_REVIEW_ORCHESTRATOR.md`
- `SKILLS/SKILL_SYSTEMATIC_REVIEW_LANDRENT.md`

These files should remain in the repo for audit history, but they should not route the next writing pass.

## Skills To Ignore For Next Pass

- Any reference to `05_skills/`
- Any instruction that treats `notes/questions/` or `review_artifacts/` as the current canonical paths when `03_notes/` and `04_review_artifacts/06_expansion/` exist
- Any instruction that treats NotebookLM notes as citable sources

## Skill Conflicts Or Ambiguities

- Older skill and protocol files include pre-Phase-3 routing assumptions.
- The editing skill is active, but only after the expanded draft exists.
- The Phase 3 synthesis skill should override generic expansion if a paragraph risks conflating land rent, housing rent, land price, real estate value, wealth, or productive capital.

## Recommended Skill Invocation Order

For the next pass, read and apply:

1. `SKILLS/SKILL_drafting_systematic_review.md`
2. `SKILLS/SKILL_PHASE3_LANDRENT_SYNTHESIS.md`
3. `04_review_artifacts/06_expansion/review_expansion_opportunities.md`
4. `06_drafts/v1_systematic_review_draft_scholarly_humanized.md`

Use `SKILLS/SKILL_editing_systematic_review.md` only after `06_drafts/v1_systematic_review_draft_expanded.md` exists.
