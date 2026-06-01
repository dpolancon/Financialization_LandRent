# Cluster Synthesis Migration Report

Date: 2026-06-01

Branch: `codex/cluster-note-synthesis-reorg`

## 1. Summary of folder reorganization

The `03_notes/` question-note architecture was reorganized as follows:

- `03_notes/clusters/` now contains only synthesized per-cluster notes.
- `03_notes/questions/paper/` now contains the paper-level question notes formerly stored directly under `03_notes/questions/`.
- `03_notes/questions/clusters/` now contains the cluster-level question notes formerly stored under `03_notes/clusters/`.

No source notes were deleted. All note moves were performed with `git mv`. Existing indexes and registries that pointed to the old `03_notes/questions/PDF*_Q*.md` and `03_notes/clusters/C*_Q*.md` paths were mechanically updated to the new paths.

Tests are not applicable for this documentation-only reorganization. Validation was performed through file counts, path checks, diff inspection, and `git status`.

## 2. Files moved

### Paper-level question notes

Moved from `03_notes/questions/` to `03_notes/questions/paper/`:

- `PDF001_Q01.md` through `PDF001_Q07.md`
- `PDF002_Q01.md` through `PDF002_Q07.md`
- `PDF003_Q01.md` through `PDF003_Q07.md`
- `PDF004_Q01.md` through `PDF004_Q07.md`
- `PDF005_Q01.md` through `PDF005_Q07.md`
- `PDF006_Q01.md` through `PDF006_Q07.md`
- `PDF007_Q01.md` through `PDF007_Q07.md`
- `PDF008_Q01.md` through `PDF008_Q07.md`
- `PDF009_Q01.md` through `PDF009_Q07.md`
- `PDF010_Q01.md` through `PDF010_Q07.md`
- `PDF011_Q01.md` through `PDF011_Q07.md`
- `PDF012_Q01.md` through `PDF012_Q07.md`
- `PDF013_Q01.md` through `PDF013_Q07.md`
- `PDF014_Q01.md` through `PDF014_Q07.md`

Total paper-level question notes moved: 98.

### Cluster-level question notes

Moved from `03_notes/clusters/` to `03_notes/questions/clusters/`:

- `C1_Q01.md` through `C1_Q05.md`
- `C2_Q01.md` through `C2_Q05.md`
- `C3_Q01.md` through `C3_Q06.md`
- `C4_Q01.md` through `C4_Q05.md`
- `C5_Q01.md` through `C5_Q05.md`
- `C6_Q01.md` through `C6_Q06.md`

Total cluster-level question notes moved: 32.

Total files moved: 130.

## 3. New per-cluster notes created

- `03_notes/clusters/C1_measurement_wealth_capital_rent_capitalization.md`
- `03_notes/clusters/C2_wobbly_dynamics_phase_transitions_land_price_instability.md`
- `03_notes/clusters/C3_credit_land_speculation_low_rates_capital_crowding_out.md`
- `03_notes/clusters/C4_unbalanced_growth_leverage_land_bubbles_overvaluation.md`
- `03_notes/clusters/C5_land_r_versus_g_infinite_debt_rollover.md`
- `03_notes/clusters/C6_policy_henry_george_regulation_fondecyt_translation.md`

Total synthesized cluster notes created: 6.

## 4. Source files used for each cluster note

### C1: Measurement, wealth-capital distinction, and rent capitalization

Source cluster-question notes:

- Old `03_notes/clusters/C1_Q01.md`, now `03_notes/questions/clusters/C1_Q01.md`
- Old `03_notes/clusters/C1_Q02.md`, now `03_notes/questions/clusters/C1_Q02.md`
- Old `03_notes/clusters/C1_Q03.md`, now `03_notes/questions/clusters/C1_Q03.md`
- Old `03_notes/clusters/C1_Q04.md`, now `03_notes/questions/clusters/C1_Q04.md`
- Old `03_notes/clusters/C1_Q05.md`, now `03_notes/questions/clusters/C1_Q05.md`

Paper/page anchors preserved from source notes: PDF009 pp. 1, 2, 4, 11; PDF010 pp. 16, 17, 18; PDF011 pp. 10, 11, 28.

### C2: Wobbly dynamics, phase transitions, and land-price instability

Source cluster-question notes:

- Old `03_notes/clusters/C2_Q01.md`, now `03_notes/questions/clusters/C2_Q01.md`
- Old `03_notes/clusters/C2_Q02.md`, now `03_notes/questions/clusters/C2_Q02.md`
- Old `03_notes/clusters/C2_Q03.md`, now `03_notes/questions/clusters/C2_Q03.md`
- Old `03_notes/clusters/C2_Q04.md`, now `03_notes/questions/clusters/C2_Q04.md`
- Old `03_notes/clusters/C2_Q05.md`, now `03_notes/questions/clusters/C2_Q05.md`

Paper/page anchors preserved from source notes: PDF004 pp. 3, 4, 9, 17, 34, 49; PDF006 pp. 1, 2, 10; PDF007 pp. 7, 24, 46, 47.

### C3: Credit, land speculation, low rates, and capital crowding-out

Source cluster-question notes:

- Old `03_notes/clusters/C3_Q01.md`, now `03_notes/questions/clusters/C3_Q01.md`
- Old `03_notes/clusters/C3_Q02.md`, now `03_notes/questions/clusters/C3_Q02.md`
- Old `03_notes/clusters/C3_Q03.md`, now `03_notes/questions/clusters/C3_Q03.md`
- Old `03_notes/clusters/C3_Q04.md`, now `03_notes/questions/clusters/C3_Q04.md`
- Old `03_notes/clusters/C3_Q05.md`, now `03_notes/questions/clusters/C3_Q05.md`
- Old `03_notes/clusters/C3_Q06.md`, now `03_notes/questions/clusters/C3_Q06.md`

Paper/page anchors preserved from source notes: PDF003 p. 1; PDF013 pp. 1, 15, 33, 38.

### C4: Unbalanced growth, leverage, land bubbles, and overvaluation

Source cluster-question notes:

- Old `03_notes/clusters/C4_Q01.md`, now `03_notes/questions/clusters/C4_Q01.md`
- Old `03_notes/clusters/C4_Q02.md`, now `03_notes/questions/clusters/C4_Q02.md`
- Old `03_notes/clusters/C4_Q03.md`, now `03_notes/questions/clusters/C4_Q03.md`
- Old `03_notes/clusters/C4_Q04.md`, now `03_notes/questions/clusters/C4_Q04.md`
- Old `03_notes/clusters/C4_Q05.md`, now `03_notes/questions/clusters/C4_Q05.md`

Paper/page anchors preserved from source notes: PDF001 pp. 1, 3, 4; PDF008 pp. 2, 3, 9; PDF012 pp. 1, 2, 3.

### C5: Land, R versus G, and infinite debt rollover

Source cluster-question notes:

- Old `03_notes/clusters/C5_Q01.md`, now `03_notes/questions/clusters/C5_Q01.md`
- Old `03_notes/clusters/C5_Q02.md`, now `03_notes/questions/clusters/C5_Q02.md`
- Old `03_notes/clusters/C5_Q03.md`, now `03_notes/questions/clusters/C5_Q03.md`
- Old `03_notes/clusters/C5_Q04.md`, now `03_notes/questions/clusters/C5_Q04.md`
- Old `03_notes/clusters/C5_Q05.md`, now `03_notes/questions/clusters/C5_Q05.md`

Paper/page anchors preserved from source notes: PDF002 pp. 1, 2, 16, 17; PDF014 p. 4. Additional page references exist in paper-level notes and extraction artifacts and should be checked before final quotation.

### C6: Policy, Henry George, regulation, and Fondecyt translation

Source cluster-question notes:

- Old `03_notes/clusters/C6_Q01.md`, now `03_notes/questions/clusters/C6_Q01.md`
- Old `03_notes/clusters/C6_Q02.md`, now `03_notes/questions/clusters/C6_Q02.md`
- Old `03_notes/clusters/C6_Q03.md`, now `03_notes/questions/clusters/C6_Q03.md`
- Old `03_notes/clusters/C6_Q04.md`, now `03_notes/questions/clusters/C6_Q04.md`
- Old `03_notes/clusters/C6_Q05.md`, now `03_notes/questions/clusters/C6_Q05.md`
- Old `03_notes/clusters/C6_Q06.md`, now `03_notes/questions/clusters/C6_Q06.md`

Paper/page anchors preserved from source notes: PDF001 pp. 1, 3, 4; PDF002 pp. 1, 2, 16, 17; PDF003 p. 1; PDF004 pp. 3, 4, 9, 17, 34, 49; PDF005 pp. 327, 329, 335, 345; PDF006 pp. 1, 2, 10; PDF007 pp. 7, 24, 46, 47; PDF008 pp. 2, 3, 9; PDF009 pp. 1, 2, 4, 11; PDF010 pp. 16, 17, 18; PDF011 pp. 10, 11, 28; PDF012 pp. 1, 2, 3; PDF013 pp. 1, 15, 33, 38; PDF014 p. 4.

## 5. Filename collisions and ambiguous classifications

No filename collisions were detected during migration.

No ambiguous classifications remained after inspection:

- Files named `PDF*_Q*.md` under `03_notes/questions/` were classified as paper-level question notes.
- Files named `C*_Q*.md` under `03_notes/clusters/` were classified as cluster-level question notes because their front matter identified `type: literature_cluster_note`, `cluster_id`, and `cluster_question_id`.

The repository also contains older copies under `02_LitRev_Sistematica/01_per_paper_question_notes/` and `02_LitRev_Sistematica/02_cluster_question_notes/`. Those were not moved because the requested target architecture specifically concerned `03_notes/`.

## 6. Missing or inconsistent clusters

No cluster was blocked by missing source notes.

All six clusters had source cluster-question notes:

- C1: 5 notes
- C2: 5 notes
- C3: 6 notes
- C4: 5 notes
- C5: 5 notes
- C6: 6 notes

Some model expressions and policy claims in the former cluster-question notes were not tied to a precise page number in those notes. The new synthesis notes preserve those claims only with `[page reference missing in source note]` flags where used.

## 7. Final checklist

- [x] Old paper-level question notes are in `03_notes/questions/paper/`.
- [x] Old cluster-level question notes are in `03_notes/questions/clusters/`.
- [x] New synthesized cluster notes are in `03_notes/clusters/`.
- [x] No source notes were deleted.
- [x] No citations/page references were silently dropped from the synthesized source maps; available page anchors were carried into the source maps.
- [x] Stale path references in the main Markdown/CSV indexes and registries were mechanically updated.
- [x] `03_notes/clusters/` no longer contains old `C*_Q*.md` per-question cluster notes.
- [x] Tests are not applicable; this is a notes and documentation reorganization.
- [x] `git status` was checked. The working tree contains intended migration/synthesis changes only, rather than unrelated pre-existing changes.
