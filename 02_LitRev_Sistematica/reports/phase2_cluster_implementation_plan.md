# Phase 2 Cluster Implementation Plan

Date: 2026-05-28  
Phase: `2_cluster_synthesis`  
Objective: Generate NotebookLM-backed cluster synthesis notes from the completed Phase 1 per-paper evidence base.

## Registry Structure

Cluster questions are stored in the Excel registry sheet `04_Cluster_Questions`. The parsed JSON registry at `02_LitRev_Sistematica/config/registry_parsed.json` has been extended with a machine-readable `cluster_questions` section derived from that sheet.

The registry now includes:

- `papers`: 14 paper metadata records from `01_Paper_Registry`
- `clusters`: 6 cluster metadata records from `03_Clusters`
- `questions`: 98 Phase 1 per-paper questions
- `cluster_questions`: 32 Phase 2 cluster questions

## Cluster Question Count

Total cluster questions: 32

Counts by cluster:

- `C1`: 5
- `C2`: 5
- `C3`: 6
- `C4`: 5
- `C5`: 5
- `C6`: 6

## Cluster IDs And Source Membership

Cluster IDs are represented as `C1` through `C6`.

Source membership:

- `C1`: `PDF009`, `PDF010`, `PDF011`
- `C2`: `PDF006`, `PDF007`, `PDF004`
- `C3`: `PDF013`, `PDF003`
- `C4`: `PDF008`, `PDF001`, `PDF012`
- `C5`: `PDF002`, `PDF014`
- `C6`: all 14 sources

The original C6 registry field says `PDF005 plus selected PDFs from C1-C5`. Because the selected PDFs are not enumerated and C6 questions are corpus-level policy/Fondecyt synthesis questions, Phase 2 uses all 14 sources for C6. This deterministic inference is recorded in `registry_parsed.json`.

## Phase 1 Evidence Use

Completed Phase 1 notes are used as evidence infrastructure rather than rewritten. In the current repo layout, the completed notes are under:

- `03_notes/questions/PDFXXX_QYY.md`

The Phase 2 evidence-map script also supports `notes/questions/` if that path exists in a future layout.

The derived evidence map is written to:

- `02_LitRev_Sistematica/derived/cluster_evidence_map.json`

For each cluster, the map contains:

- cluster ID
- source IDs
- source titles
- per-paper note IDs
- note paths
- question texts
- distilled notes
- evidence/page-anchor sections

Cluster notes will link to all relevant Phase 1 per-paper notes from the same cluster. C6 links to all Phase 1 per-paper notes because it is a whole-corpus policy and translation cluster.

## Scripts Added

Added:

- `scripts/build_cluster_evidence_map.py`
  - Scans Phase 1 notes and creates `cluster_evidence_map.json`.

- `scripts/fetch_cluster_notebooklm_answers.py`
  - Loads cluster questions from `registry_parsed.json`.
  - Resolves related paper source IDs to NotebookLM source IDs.
  - Sends cluster questions to NotebookLM with source constraints.
  - Renders Markdown notes under `notes/clusters/`.
  - Supports `--limit`, `--only`, `--overwrite`, `--new-chat`, `--dry-run`, `--source-map`, `--registry`, and `--output-dir`.

- `scripts/validate_phase2_clusters.py`
  - Validates note existence, frontmatter, required sections, NotebookLM markers, related Phase 1 links, duplicate IDs, and placeholder/Qwen markers.
  - Writes `02_LitRev_Sistematica/reports/phase2_cluster_validation_report.md`.

## Execution Command

Phase 2 execution command:

```powershell
python scripts/fetch_cluster_notebooklm_answers.py --registry 02_LitRev_Sistematica/config/registry_parsed.json --source-map 02_LitRev_Sistematica/config/notebooklm_source_map.json --output-dir notes/clusters --new-chat
```

NotebookLM authentication must pass:

```powershell
notebooklm auth check --test --json
```

If authentication expires, run:

```powershell
notebooklm login
```
