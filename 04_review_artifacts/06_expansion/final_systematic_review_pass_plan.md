# Final Systematic Review Pass Plan

Date: 2026-05-29

This plan describes the final wrap-up pathway after the controlled expansion pass. It does not execute cleanup, citation closure, or redrafting.

## Active Routing Confirmation

- Current input draft: `06_drafts/v1_systematic_review_draft_scholarly_humanized.md`
- Next expected draft: `06_drafts/v1_systematic_review_draft_expanded.md`
- Expansion guide: `04_review_artifacts/06_expansion/review_expansion_opportunities.md`
- Main reading layer: `03_notes/papers/`
- Atomic provenance layer: `03_notes/questions/`
- Thematic synthesis layer: `03_notes/clusters/`
- Source-routing infrastructure: `02_LitRev_Sistematica/04_indexes/`
- Development bundle, not active notes: `02_LitRev_Sistematica/`
- Pre-systematic-review memo layer, not active draft: `01_memo_ejecutivo_V0.1/`
- Do not use stale paths: `04_review_artifacts/05_expansion/`, `05_skills/`

## 1. Immediate Next Step After Expanded Draft

Create a non-destructive expanded draft:

- input: `06_drafts/v1_systematic_review_draft_scholarly_humanized.md`
- expansion guide: `04_review_artifacts/06_expansion/review_expansion_opportunities.md`
- reading layer: `03_notes/papers/`
- provenance layer: `03_notes/questions/`
- synthesis layer: `03_notes/clusters/`
- output: `06_drafts/v1_systematic_review_draft_expanded.md`
- audit: `04_review_artifacts/06_expansion/v1_systematic_review_expansion_audit.md`

The expansion should prioritize high-priority paragraphs and selected medium-priority paragraphs only. Low-priority and no-expansion paragraphs should remain compact unless a human reviewer requests otherwise.

## 2. Whether Compression Is Needed

Compression is likely needed after expansion. The current scholarly-humanized draft is compact; an expanded draft may become uneven if every high-priority paragraph is enlarged.

Recommended compression rule:

- preserve expanded conceptual and mechanism paragraphs;
- compress repeated summaries;
- keep source-gap paragraphs concise;
- avoid adding a second conclusion inside mechanism sections;
- keep final review length aligned with the intended systematic-review deliverable rather than the shorter memo deliverable.

## 3. Whether PDF Citation Closure Is Needed

Yes. Final citation closure is required before external circulation or publication-style use.

Current status:

- Reference validation is index/note/extraction based.
- `06_drafts/reference_validation/paragraph_citation_ledger.csv` covers P01-P43.
- Original source PDFs were not found in the working tree during this assessment.
- `07_pdf_outputs/v1_systematic_review_draft_scholarly_humanized.pdf` is a rendered review output, not a source PDF.

Required input before citation closure:

- original PDFs or verified source text for PDF001-PDF014;
- stable bibliography metadata for all 14 sources;
- page-level verification for repaired and index-only citations.

## 4. Bibliography Normalization Plan

After the expanded draft stabilizes:

1. Build a canonical bibliography table from `02_LitRev_Sistematica/04_indexes/I03_source_index.md` and `04_review_artifacts/01_registries/source_registry.csv`.
2. Normalize author names, years, titles, working-paper numbers, journal status, and version labels.
3. Decide how to distinguish multiple Hirano-Stiglitz 2025 papers: 2025a, 2025b, 2025c.
4. Resolve the PDF013 label, which appears as stored 2021 but cited as 2024 in the active draft.
5. Replace the bibliography placeholder with a normalized bibliography section.
6. Run a final citation-to-bibliography crosscheck.

## 5. Final Editorial Pass Plan

After expansion and citation closure:

1. Run a structural pass: check section balance, paragraph order, and duplicated claims.
2. Run a concept pass: check land rent, housing rent, land price, real estate value, wealth, productive capital, bubble, and overvaluation distinctions.
3. Run a citation pass: ensure every substantive claim has a source citation or a source-gap marker.
4. Run a prose pass using `SKILLS/SKILL_editing_systematic_review.md`.
5. Run a final audit pass: list remaining page gaps, source gaps, and project translations.

## 6. Final Output Formats

Recommended final outputs:

- Markdown canonical draft: `06_drafts/v1_systematic_review_final.md`
- Final citation audit: `06_drafts/reference_validation/final_citation_audit.md`
- Final PDF render: `07_pdf_outputs/v1_systematic_review_final.pdf`
- Optional DOCX render if needed for circulation.

## 7. Files To Preserve

- `03_notes/questions/`
- `03_notes/papers/`
- `03_notes/clusters/`
- `04_review_artifacts/02_extraction/extraction_matrix.csv`
- `04_review_artifacts/03_synthesis/thematic_synthesis_map.md`
- `04_review_artifacts/04_memo_architecture/paragraph_function_map.csv`
- `06_drafts/reference_validation/`
- all current v1 draft lineage files until final acceptance.

## 8. Files To Archive Later

Archive only after final draft stabilization:

- `06_drafts/v1_systematic_review_draft.md`
- `06_drafts/v1_systematic_review_draft_reference_validated.md`
- pre-final rendered PDFs in `07_pdf_outputs/`
- legacy bootstrap prompts if the project owner wants a cleaner active skill folder.

## 9. Files That Should Become Canonical

- `03_notes/papers/` as the main reading layer.
- `03_notes/questions/` as the atomic provenance layer.
- `03_notes/clusters/` as the thematic synthesis layer.
- `04_review_artifacts/06_expansion/review_expansion_opportunities.md` as the expansion plan.
- `04_review_artifacts/06_expansion/active_artifact_map.md` as the active routing map.
- `06_drafts/v1_systematic_review_draft_expanded.md` after the next pass.
- `06_drafts/v1_systematic_review_final.md` after citation closure and final editing.

## 10. Stop Conditions Before Final Submission Or Circulation

Stop before final submission or external circulation if any of the following remain true:

- original source PDFs are unavailable for citation closure;
- any substantive source claim lacks page validation;
- a source-gap marker has been converted into a supported claim without new corpus evidence;
- NotebookLM notes, consolidated paper notes, or cluster notes are cited as sources;
- Latin American empirical claims enter the draft without an approved external comparator-literature pass;
- the bibliography remains a placeholder;
- multiple draft files remain plausible active drafts without an updated active artifact map.

## Recommended Next Prompt

```text
Use 06_drafts/v1_systematic_review_draft_scholarly_humanized.md as input and 04_review_artifacts/06_expansion/review_expansion_opportunities.md as the expansion guide. Create 06_drafts/v1_systematic_review_draft_expanded.md non-destructively. Expand only high-priority and selected medium-priority paragraphs using 03_notes/papers/, 03_notes/questions/, 03_notes/clusters/, and 04_review_artifacts/02_extraction/extraction_matrix.csv. Preserve citations, source-gap markers, project-translation boundaries, and all conceptual distinctions. Write 04_review_artifacts/06_expansion/v1_systematic_review_expansion_audit.md.
```
