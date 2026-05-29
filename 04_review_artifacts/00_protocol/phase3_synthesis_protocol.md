# Phase 3A Synthesis Protocol

Generated: 2026-05-29

## Purpose

Phase 3A converts completed NotebookLM-backed Phase 1 and Phase 2 notes into systematic synthesis infrastructure for a later Fondecyt working memo. It does not fetch new NotebookLM answers and does not draft the final memo.

## Governing Protocol

`05_skills/SYSTEMATIC_REVIEW_ORCHESTRATOR.md` governs the review logic. `05_skills/SKILL_SYSTEMATIC_REVIEW_LANDRENT.md` supplies the operational checklist. `05_skills/review_matrix_schema.csv` supplies the hard extraction schema. `05_skills/codex_prompt_bootstrap.md` is treated as a legacy bootstrap artifact only.

## Note Paths

- Per-paper notes: `03_notes/questions`
- Cluster notes: `03_notes/clusters`
- Registry: `02_LitRev_Sistematica/config/registry_parsed.json`
- Cluster evidence map: `02_LitRev_Sistematica/derived/cluster_evidence_map.json`

The repository has migrated from earlier `notes/...` paths to `03_notes/...`; Phase 3A uses `03_notes/...` as canonical.

## Extraction Rule

The extraction unit is one claim. Per-paper notes supply source-level claims. Cluster notes supply synthesis claims and source-specific evidence map claims where available. Claims without page references are marked `needs_page`.

## Validation Categories

`validated_exact`, `validated_paraphrase`, `needs_page`, `unclear`, `not_supported`, `outside_scope`.

## C6 Handling

C6 is corpus-level synthesis and must be interpreted as all-source inference. It is not a normal bounded cluster.

## No-Fetch / No-Draft Boundary

This phase only builds review infrastructure. It does not call NotebookLM, does not replace NotebookLM with another model, does not import external literature, and does not draft final memo prose.
