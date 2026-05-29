# Systematic Review Orchestrator — Financialization, Land Rent, and Land Bubbles

## 0. Purpose

This artifact orchestrates a systematic review from an existing note repository, rather than starting from a blank database search. The working corpus is assumed to be the notes under:

`Financialization_LandRent/notes/questions`

The source papers are the Hirano–Stiglitz–Toda / Hirano–Toda / Stiglitz land-rent, land-bubble, credit, growth, and wealth-measurement papers already loaded in the project source folder. The immediate objective is not a generic literature review. It is a controlled synthesis that reconstructs what this literature says on its own terms before building a bounded critique for the Fondecyt land-rent/financialization project.

## 1. Review type

Use a **theory-led systematic narrative review**.

This is more appropriate than a meta-analysis because the corpus is mainly theoretical, model-based, and conceptual. It is also more disciplined than a standard narrative review because it records the corpus, inclusion rules, extraction categories, screening decisions, and synthesis logic.

Operationally, the review combines four modes:

1. **Systematic mapping**: identify every note, source paper, question, and answer.
2. **Conceptual extraction**: code definitions, mechanisms, causal claims, variables/parameters, and evidence/theory status.
3. **Narrative synthesis**: group findings by theoretical relation rather than by paper chronology alone.
4. **Critical appraisal**: assess scope, assumptions, transportability to Latin American urban land markets, and usefulness for Fondecyt.

## 2. Governing review question

How does the Hirano–Stiglitz–Toda branch explain the relation between land-price inflation, credit expansion, unbalanced growth, capital formation, land overvaluation, and debt rollover?

## 3. Subquestions

SQ1. How does land-price inflation affect productive capital formation and long-run growth?

SQ2. How does private credit expansion, especially real-estate credit or collateral-based financing, amplify land-price inflation?

SQ3. What is the Land Overvaluation Theorem, and how does it depend on unbalanced growth?

SQ4. How does land speculation alter the conditions for R versus G and infinite debt rollover?

SQ5. How does the literature distinguish land, housing, real estate, productive capital, wealth, rents, and bubbles?

SQ6. What assumptions make the results travel—or fail to travel—to urban land rent and financialization in Latin America?

## 4. Corpus boundaries

### Included

Include papers and notes that directly address at least one of the following:

- land as non-produced asset or fixed factor;
- land price, land rent, housing rent, or land overvaluation;
- land speculation and productive capital formation;
- credit, collateral, leverage, monetary policy, or low interest rates;
- unbalanced growth and asset-price bubbles;
- wealth-capital distinction and land as capitalized rent;
- debt rollover, R versus G, or dynamic efficiency in land economies.

### Excluded or quarantine

Exclude or quarantine texts that only provide generic asset-pricing, generic OLG theory, generic urban economics, or generic financialization unless they are used explicitly as comparison literature. These can enter the review as **context**, but not as part of the primary SHT corpus.

## 5. Source-ID convention

Use the existing literature-review source ID convention:

`PDF001`, `PDF002`, ..., `PDFNNN`

Every note should preserve a stable question code:

`PDF001_Q01`, `PDF001_Q02`, ..., `PDFNNN_QMM`

Every answer note should contain:

```yaml
---
source_id: PDF001
question_id: PDF001_Q01
paper_key: HIRANO_STIGLITZ_2025a
review_status: extracted
evidence_level: primary_argument
dimensions:
  - definition
  - mechanism
  - causality
  - variables_parameters
  - theory_evidence
validated_against_pdf: false
---
```

## 6. Extraction dimensions

Each note must be coded through five dimensions.

### D1. Definition

What object is being defined?

Examples: land bubble, land overvaluation, land rent, housing rent, wealth, capital, collateral value, productive investment, unbalanced growth, R, G.

Minimum extraction:

- concept name;
- definition in the source;
- what the concept is not;
- whether definition is formal, verbal, empirical, or institutional.

### D2. Mechanism

What process links the objects?

Examples:

- land prices crowd out productive capital;
- credit expansion raises collateral values;
- leverage creates a positive feedback loop between land prices and investment;
- unbalanced growth separates land prices from land rents;
- land bubbles make finite land prices compatible with low safe rates.

Minimum extraction:

- mechanism name;
- starting condition;
- transmission channel;
- endpoint;
- whether the mechanism is partial-equilibrium, general-equilibrium, dynamic, or policy-mediated.

### D3. Causality

What causal direction is asserted?

Examples:

- lower interest rates → higher leverage → land speculation → lower productive investment;
- faster productivity growth in non-land sectors + high substitutability → land overvaluation;
- land presence changes R versus G conditions;
- land speculation changes growth path and welfare distribution.

Minimum extraction:

- causal chain;
- necessary conditions;
- sufficient conditions if stated;
- reversal or feedback effects;
- temporal horizon: short run, transition, long run.

### D4. Variables and parameters

What variables and parameters do the authors use?

Examples:

- land price `P_t`;
- land rent/dividend `D_t` or `r_t`;
- capital stock `K_t`;
- productive investment `k_{t+1}`;
- safe interest rate `r` or gross return `R`;
- growth rate `G`;
- leverage or collateral parameters;
- elasticity of substitution between land and non-land factors.

Minimum extraction:

- symbol;
- verbal meaning;
- role in the mechanism;
- exogenous/endogenous status;
- whether it maps cleanly to empirical project variables.

### D5. Theory/evidence status

What is the status of the claim?

Code as:

- `theorem`;
- `proposition`;
- `model_result`;
- `numerical_example`;
- `empirical_motivation`;
- `measurement_claim`;
- `policy_implication`;
- `critical_interpretation`.

Also record whether the source gives direct empirical evidence, stylized facts, external empirical literature, or pure theoretical derivation.

## 7. Workflow

### Stage A — Repository audit

Goal: identify all note files, code all note IDs, detect missing metadata.

Outputs:

- `review_registry.csv`;
- `note_integrity_report.md`;
- list of orphan notes, duplicate question codes, missing source IDs, and unvalidated notes.

### Stage B — Source registry

Goal: map every PDF to a stable source ID.

Outputs:

- `source_registry.csv`;
- columns: `source_id`, `paper_key`, `authors`, `year`, `title`, `venue`, `file_name`, `primary_theme`, `status`.

### Stage C — Question registry

Goal: convert the question-note system into a review protocol.

Outputs:

- `question_registry.csv`;
- columns: `question_id`, `source_id`, `question_text`, `dimension_primary`, `dimension_secondary`, `review_section_target`.

### Stage D — Extraction matrix

Goal: extract coded claims from each note.

Outputs:

- `extraction_matrix.csv`;
- one row per claim, not one row per paper.

Each row should include:

- source ID;
- question ID;
- claim ID;
- exact page reference if available;
- dimension;
- concept;
- mechanism;
- causal chain;
- variables/parameters;
- theoretical status;
- evidence status;
- quote/paraphrase flag;
- validation status;
- reviewer comment.

### Stage E — Cross-validation against PDFs

Goal: avoid note drift.

Each extracted claim must be checked against the original paper if it will be used in the final review.

Validation categories:

- `validated_exact`;
- `validated_paraphrase`;
- `needs_page`;
- `unclear`;
- `not_supported`;
- `outside_scope`.

Do not draft from unsupported claims.

### Stage F — Thematic synthesis

Build synthesis clusters from claims, not from papers.

Core clusters:

1. Land as non-produced asset, store of value, and fixed factor.
2. Wealth-capital distinction and capitalized rents.
3. Land speculation and crowding-out of productive capital.
4. Credit, collateral, leverage, and monetary policy.
5. Unbalanced growth, land overvaluation, and bubble necessity.
6. R versus G, dynamic efficiency, and debt rollover.
7. Policy implications: land taxation, financial regulation, collateral rules.
8. Critical transportability to the Fondecyt project.

### Stage G — Draft architecture

Recommended manuscript structure:

1. Introduction: why this literature matters for land rent and financialization.
2. Method: corpus, notes, extraction protocol, screening, synthesis.
3. Conceptual objects: land, rent, wealth, capital, real estate, bubble.
4. Mechanism I: land-price inflation and capital-formation crowding-out.
5. Mechanism II: credit expansion, collateral, leverage, and monetary policy.
6. Mechanism III: unbalanced growth and the Land Overvaluation Theorem.
7. Mechanism IV: R versus G, land, and infinite debt rollover.
8. Critical appraisal: assumptions, scope, Latin American transportability.
9. Research agenda: what the Fondecyt project should retain, modify, or reject.
10. Conclusion.

## 8. Quality gates

A paragraph can enter the draft only if it passes these gates:

- It identifies a concept, mechanism, causal relation, variable set, or appraisal claim.
- It is traceable to at least one note and preferably to one PDF page range.
- It does not conflate SHT with external literatures.
- It distinguishes land rent, housing rent, land price, real estate price, wealth, and productive capital.
- It specifies whether the claim is theoretical, empirical, or interpretive.
- It states the condition under which the mechanism holds.

## 9. Anti-scope rules

Do not turn the review into:

- a full history of land-rent theory;
- a general review of financialization;
- a Marxist rent-theory chapter;
- a complete urban economics literature review;
- a policy essay on housing affordability;
- a broad macro-finance survey.

Those literatures can appear only as controlled comparison points after the SHT branch is reconstructed on its own terms.

## 10. Minimum viable outputs

MVP-1: `source_registry.csv`

MVP-2: `question_registry.csv`

MVP-3: `extraction_matrix.csv`

MVP-4: `thematic_synthesis_map.md`

MVP-5: `draft_outline.md`

MVP-6: `systematic_review_draft.md`
