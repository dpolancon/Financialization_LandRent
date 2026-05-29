# SKILL — Turn Land-Rent Question Notes into a Systematic Narrative Review

## Mission

Transform a repository of question-based notes on the Hirano–Stiglitz–Toda land-bubble literature into a systematic narrative review suitable for a working paper or project report.

## Inputs

Expected repository structure:

```text
Financialization_LandRent/
  03_notes/
    questions/
      PDF001_Q01.md
      PDF001_Q02.md
      ...
  sources/ or papers/
    PDF001.pdf
    PDF002.pdf
    ...
```

If the PDF files are not inside the repository, use the external source folder and map file names through `source_registry.csv`.

## Output bundle

Create or update:

```text
04_review_artifacts/
    00_protocol/
      systematic_review_protocol.md
      inclusion_exclusion_criteria.md
      search_and_scope_log.md
    01_registries/
      source_registry.csv
      question_registry.csv
      note_integrity_report.md
    02_extraction/
      extraction_matrix.csv
      concept_dictionary.md
      mechanism_ledger.md
      variable_parameter_ledger.md
    03_synthesis/
      thematic_synthesis_map.md
      claim_cluster_table.csv
      gap_and_transportability_memo.md
    04_draft/
      draft_outline.md
      systematic_review_draft.md
      revision_log.md
```

## Procedure

### 1. Inventory notes

Scan `notes/questions`.

For each note, infer:

- `source_id`;
- `question_id`;
- paper key if present;
- question text;
- answer body;
- explicit page references;
- cited concepts;
- missing metadata.

Flag:

- duplicate IDs;
- notes without source ID;
- notes without question ID;
- notes with no answer;
- notes with claims but no page references.

### 2. Build source registry

Create one row per paper.

Required columns:

```csv
source_id,paper_key,authors,year,title,venue,file_name,primary_theme,corpus_role,status
```

`corpus_role` values:

- `core_theory`;
- `core_policy`;
- `measurement_foundation`;
- `background`;
- `external_comparator`;
- `quarantine`.

### 3. Build question registry

Create one row per question note.

Required columns:

```csv
question_id,source_id,paper_key,question_text,dimension_primary,dimension_secondary,section_target,answer_status,page_refs_present,validation_status
```

### 4. Extract claims

Use one row per claim.

Required columns:

```csv
claim_id,source_id,question_id,paper_key,page_ref,dimension,concept,definition,mechanism,causal_chain,variables_parameters,theory_evidence_status,claim_text,project_use,validation_status,reviewer_comment
```

Do not collapse several claims into one row. The final review is built from claim rows.

### 5. Validate claims against PDFs

Use the source PDF to check any claim that enters the draft.

Validation values:

- `validated_exact`;
- `validated_paraphrase`;
- `needs_page`;
- `unclear`;
- `not_supported`;
- `outside_scope`.

Do not use `not_supported` claims in the final review.

### 6. Build conceptual dictionary

For each concept, record:

- preferred term;
- alternative terms;
- definition;
- source papers;
- page references;
- distinction from neighboring concepts;
- project relevance.

Mandatory concepts:

- land;
- land rent;
- housing rent;
- real estate;
- productive capital;
- wealth;
- land price;
- fundamental value;
- bubble;
- land overvaluation;
- collateral value;
- leverage;
- unbalanced growth;
- R versus G;
- debt rollover.

### 7. Build mechanism ledger

Each mechanism entry must include:

- mechanism name;
- source papers;
- starting condition;
- transmission channel;
- endpoint;
- variables;
- assumptions;
- policy implication;
- Fondecyt translation risk.

Mandatory mechanisms:

- land speculation crowds out productive capital;
- real-estate credit amplifies land-price inflation;
- leverage creates land-bubble phase transition;
- unbalanced growth separates land prices from rents;
- land changes R versus G and debt-rollover conditions;
- land taxation/regulation redirects savings toward productive investment.

### 8. Build synthesis map

Cluster claims by theoretical relation.

Recommended clusters:

1. Definitions and conceptual separations.
2. Asset-price and wealth-measurement claims.
3. Growth and capital-formation mechanisms.
4. Credit, leverage, collateral, and monetary policy.
5. Unbalanced growth and overvaluation.
6. Debt rollover and dynamic efficiency.
7. Policy and institutional implications.
8. Critical adaptation to urban land-rent financialization.

### 9. Draft

Draft only after the extraction matrix and synthesis map exist.

Each paragraph must have one function:

- define object;
- explain mechanism;
- specify causal chain;
- distinguish variables;
- state theorem/model result;
- appraise evidence;
- translate to Fondecyt.

Avoid generic literature-review prose. Write as a controlled reconstruction of one branch of literature.

## Quality controls

Before finalizing, run checks for:

- unsupported claims;
- missing page references;
- concept conflation;
- duplicate mechanisms;
- excessive chronology;
- unmarked critique;
- unvalidated claims in final draft;
- unclear distinction between theory and evidence.

## Drafting rule

The review should first explain the SHT literature on its own terms. Critique comes only after reconstruction.
