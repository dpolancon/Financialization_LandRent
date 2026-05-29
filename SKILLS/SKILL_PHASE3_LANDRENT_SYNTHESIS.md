# Phase 3 Land-Rent Synthesis Skill

## Review Type

Theory-led systematic narrative review.

## Governing Review Question

How does the Hirano-Stiglitz-Toda branch explain the relation between land-price inflation, credit expansion, unbalanced growth, capital formation, land overvaluation, and debt rollover, and how can that reconstruction be translated cautiously to Latin American land-rent financialization contexts?

## Six Subquestions

1. How does land-price inflation affect productive capital formation and growth?
2. How do private credit expansion, real-estate credit, and collateral financing amplify land-price inflation?
3. What do the Land Overvaluation Theorem and unbalanced growth explain?
4. How does land speculation alter R versus G and infinite debt rollover conditions?
5. How must land, housing, real estate, productive capital, wealth, rents, and bubbles be distinguished?
6. Which assumptions travel, fail to travel, or require empirical validation for Latin American urban land-rent financialization cases?

## Included Corpus Boundaries

- The 14-source SHT/Hirano-Stiglitz-Toda corpus registered in `02_LitRev_Sistematica/config/registry_parsed.json`.
- NotebookLM-backed Phase 1 per-paper notes and Phase 2 cluster notes.
- Land as fixed or non-produced factor, store of value, collateral object, and rent-generating asset.
- Land price, land rent, land overvaluation, bubbles, credit, collateral, leverage, unbalanced growth, wealth-capital distinction, R versus G, debt rollover, wobbly dynamics, and policy implications inside this corpus.

## Excluded and Quarantine Boundaries

- Do not import generic financialization, urban economics, housing studies, Marxian rent theory, generic OLG theory, or asset-pricing literature before reconstructing the SHT branch on its own terms.
- External literatures may later enter only as controlled comparators after Phase 3A.
- Claims without note support remain quarantined and cannot enter memo drafting.

## Source ID Convention

- Per-paper sources use `PDF001` through `PDF014`.
- Per-paper questions use `PDFXXX_QYY`.
- Cluster questions use `C#_Q##`.
- C6 is corpus-level synthesis. It must be marked as all-source inference and not treated as a normal bounded cluster.

## Extraction Dimensions

Use exactly one primary dimension per extracted claim:

- `definition`
- `mechanism`
- `causality`
- `variables_parameters`
- `theory_evidence`

## One-Row-Per-Claim Rule

Each row in the extraction matrix must represent one claim, not one paper and not one note. Split cluster-level claims into source-level claims where evidence anchors permit. If a cluster synthesis cannot be traced to one source, use `source_id=MULTI` and list related sources in `reviewer_comment`.

## Validation Categories

- `validated_exact`: exact source wording and page anchor are available.
- `validated_paraphrase`: source-grounded paraphrase and page anchor are available.
- `needs_page`: grounded in a note but lacking precise page reference.
- `unclear`: parser or reviewer cannot isolate a defensible claim.
- `not_supported`: claim is not supported by the note base.
- `outside_scope`: claim belongs outside the bounded SHT reconstruction.

## Concept Dictionary Rules

Every concept entry must include preferred term, alternatives, definition, source papers, page references or `needs_page`, distinctions from neighboring concepts, project relevance, and a Latin American transportability note.

Mandatory distinctions: land rent, housing rent, land price, real estate value, wealth, and productive capital must never be conflated.

## Mechanism Ledger Rules

Each mechanism entry must include source papers, starting condition, transmission channel, endpoint, variables/parameters, assumptions, theoretical status, policy implication, Fondecyt translation risk, source note links, and validation status.

## Thematic Synthesis Rules

Synthesis must be built from extracted claims. Cluster notes are evidence infrastructure, not final prose. The synthesis map should preserve a reconstruction-before-critique sequence.

## Fondecyt Transportability Rules

For Latin American urban land-rent and financialization cases, mark whether a claim is directly usable, requires institutional translation, requires empirical validation, depends on advanced-economy assumptions, or identifies a missing link.

## Anti-Scope Rules

- Do not draft from unsupported claims.
- Do not treat cluster notes as final memo prose.
- Do not treat C6 as a normal bounded cluster.
- Do not import external literature during Phase 3A.
- Do not fabricate page references.

## Paragraph Quality Gates

Any paragraph later entering the memo must have one primary function, explicit claim IDs, source IDs, note IDs, concepts, mechanisms, variables/parameters where relevant, validation status, and a concept-conflation risk check. Paragraphs using `not_supported`, `outside_scope`, or `unclear` claims are not draft-ready.

Generated: 2026-05-29
