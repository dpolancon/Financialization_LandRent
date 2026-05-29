# SKILL — Systematic Review Outline, Argumentation, and Drafting from Validated Notes

## Mission

Turn an already-normalized and validated repository of NotebookLM-derived research notes into a systematic narrative review with a clear outline, controlled argumentation, properly referenced claims, and draft-ready prose.

This SKILL assumes that fetching, normalization, source matching, and PDF validation are already in motion or completed. Its task begins after the note system has produced validated claims, source IDs, page references, and thematic tags.

## Core orientation

The review is not a generic literature review. It is a theory-led systematic narrative review of the Hirano–Stiglitz–Toda branch on land bubbles, land overvaluation, credit, unbalanced growth, land speculation, capital formation, wealth measurement, and debt rollover.

The review must first reconstruct the literature on its own terms. Critique and project translation come after reconstruction.

## Inputs

Expected inputs:

```text
review_artifacts/
  01_registries/source_registry.csv
  01_registries/question_registry.csv
  02_extraction/extraction_matrix.csv
  02_extraction/concept_dictionary.md
  02_extraction/mechanism_ledger.md
  02_extraction/variable_parameter_ledger.md
  03_synthesis/thematic_synthesis_map.md
```

Optional inputs:

```text
notes/questions/
  PDF001_Q01.md
  PDF001_Q02.md
  ...

sources/
  PDF001.pdf
  PDF002.pdf
  ...
```

The draft must only use claims marked as:

```text
validated_exact
validated_paraphrase
```

Claims marked as `needs_page`, `unclear`, `not_supported`, or `outside_scope` may inform research planning but cannot enter the final draft as evidence.

## Output bundle

Create or update:

```text
review_artifacts/
  03_synthesis/
    argument_spine.md
    section_synthesis_tables.md
    contradiction_and_tension_map.md
    project_translation_memo.md

  04_draft/
    systematic_review_outline.md
    paragraph_plan.md
    systematic_review_draft.md
    citation_audit.md
    revision_log.md
```

## Review question

How does the Hirano–Stiglitz–Toda literature explain the relationship between land-price inflation, credit expansion, unbalanced growth, productive capital formation, land overvaluation, and debt rollover?

## Governing subquestions

1. How does land-price inflation affect productive capital formation and long-run growth?
    
2. How does private credit expansion, collateral valuation, and leverage amplify land-price inflation?
    
3. What is the Land Overvaluation Theorem, and how does it depend on unbalanced growth?
    
4. How does land speculation change the relation between R, G, dynamic efficiency, and debt rollover?
    
5. How does the literature distinguish land, land rent, housing rent, real estate value, wealth, productive capital, and bubbles?
    
6. Which assumptions travel to the Fondecyt project on land rent and financialization, and which require modification?
    

## Argumentative spine

The review should develop the following argument:

```text
The HST literature begins from a distinction between land as a fixed, non-produced asset and productive capital as an accumulable input. Because land can function simultaneously as a factor of production, a store of value, and collateral, increases in land prices do not necessarily represent an expansion of productive capacity. Under credit expansion, leverage, or low-interest-rate conditions, land-price inflation can divert savings and financing away from productive investment. Under unbalanced growth, especially when non-land sectors experience faster productivity growth and land remains valuable as a store of value, land prices can become overvalued relative to land rents. This changes standard conclusions about bubbles, R versus G, dynamic efficiency, and debt rollover. For the Fondecyt project, the literature is valuable because it formalizes a macro-financial mechanism through which land valuation, credit allocation, and growth become internally linked; however, its models require careful translation before being applied to urban land rent, institutional land markets, and Latin American financialization.
```

## Mandatory conceptual distinctions

Before drafting mechanisms, define and separate:

- land;
    
- land rent;
    
- housing rent;
    
- real estate value;
    
- land price;
    
- productive capital;
    
- wealth;
    
- capitalized rent;
    
- fundamental value;
    
- land bubble;
    
- land overvaluation;
    
- collateral value;
    
- leverage;
    
- unbalanced growth;
    
- R;
    
- G;
    
- debt rollover.
    

Do not use these concepts interchangeably.

## Section architecture

### Section 1 — Introduction

Function: establish the problem and explain why this branch of literature matters.

Required moves:

- State that land-price inflation poses a macroeconomic problem because land is both a non-produced asset and a financial store of value.
    
- Explain that increases in measured wealth can reflect capitalized rents rather than productive-capacity formation.
    
- Introduce the four central mechanisms: crowding-out, credit/leverage, unbalanced growth/overvaluation, and debt rollover.
    
- State that the review reconstructs the literature first, then assesses its usefulness for the project.
    

Do not begin with a generic history of land theory.

### Section 2 — Method and corpus

Function: explain how the review was produced.

Required moves:

- Identify the corpus as a bounded set of HST-related papers and validated question notes.
    
- Explain that NotebookLM notes were used as extraction aids, not as citable sources.
    
- State that claims were included only if traceable to validated notes and PDF page references.
    
- Define the five extraction dimensions: definition, mechanism, causality, variables/parameters, and theory/evidence.
    
- Explain that synthesis is organized by mechanisms rather than only by chronology.
    

### Section 3 — Conceptual foundations

Function: define the objects.

Required moves:

- Distinguish wealth from productive capital.
    
- Distinguish land price from land rent.
    
- Distinguish housing/real-estate value from pure land value.
    
- Explain why land is special: fixed supply, durability, non-produced character, collateral function, and store-of-value role.
    
- Explain why these distinctions matter for interpreting growth and financialization.
    

### Section 4 — Mechanism I: Land-price inflation and capital-formation crowding-out

Function: explain how land speculation affects productive investment.

Required moves:

- Define the crowding-out mechanism.
    
- Explain how savings can be diverted from productive capital into land.
    
- Distinguish short-run asset booms from long-run growth effects.
    
- Identify conditions under which the mechanism holds.
    
- Clarify the welfare distribution across landholders, savers, entrepreneurs, workers, and future generations where the sources permit.
    

### Section 5 — Mechanism II: Credit, collateral, leverage, and monetary policy

Function: explain the financial channel.

Required moves:

- Define the credit expansion mechanism.
    
- Explain the difference between credit to productive sectors and credit to real estate/construction/land.
    
- Explain how collateral values can amplify land-price inflation.
    
- Explain why lower interest rates or looser credit do not automatically increase productive investment.
    
- Identify the general-equilibrium reversal: what appears investment-enhancing in partial equilibrium may reduce productive investment once land-price effects are included.
    

### Section 6 — Mechanism III: Unbalanced growth and land overvaluation

Function: explain the Land Overvaluation Theorem and related bubble logic.

Required moves:

- Define unbalanced growth.
    
- Define land overvaluation as land price exceeding the present value of land rents.
    
- Explain why balanced-growth models tend to suppress dividend-paying asset bubbles.
    
- Explain how faster productivity growth in non-land sectors, combined with sufficient substitutability or store-of-value demand, can separate land prices from land rents.
    
- State the theorem in plain language before introducing formal notation.
    
- Use formalization only when it clarifies the mechanism.
    

### Section 7 — Mechanism IV: R versus G and debt rollover

Function: explain how land changes debt-rollover logic.

Required moves:

- Define R and G.
    
- Explain the conventional land argument: with balanced growth and productive land, land returns tend to imply R > G.
    
- Explain how unbalanced growth reopens the possibility of low-interest-rate environments, land bubbles, and infinite debt rollover.
    
- Distinguish Pareto efficiency from debt-rollover possibility.
    
- Clarify why the result is not simply the standard Diamond landless economy result.
    

### Section 8 — Policy implications

Function: synthesize policy mechanisms.

Required moves:

- Discuss land taxation.
    
- Discuss credit allocation and financial regulation.
    
- Discuss collateral rules.
    
- Discuss monetary policy limits.
    
- Explain why the policy implication is not simply “restrict credit,” but redirect financial flows away from land speculation and toward productive investment.
    

### Section 9 — Critical appraisal and Fondecyt translation

Function: assess usefulness and limits.

Required moves:

- Identify what the literature contributes to the project.
    
- Identify model assumptions that may not travel directly: OLG structure, representative sectors, stylized land markets, abstraction from institutions, limited urban specificity, and weak treatment of Latin American historical land regimes.
    
- Explain what must be added: institutional land markets, zoning, metropolitan rent gradients, developer finance, banking regulation, state planning, legal property regimes, and dependency/peripheral financialization.
    
- Preserve the distinction between critique and rejection. The point is to translate, not discard.
    

### Section 10 — Conclusion

Function: close the review.

Required moves:

- Restate the central synthesis.
    
- Identify the most robust mechanisms.
    
- Identify unresolved theoretical and empirical questions.
    
- State how the review prepares the next phase of the project.
    

## Paragraph planning rule

Before drafting, create `paragraph_plan.md`.

Each paragraph must have:

```text
paragraph_id:
section:
paragraph_function:
core_claim:
supporting_sources:
required_page_refs:
concepts:
mechanism:
variables:
citation_status:
draft_status:
```

Allowed paragraph functions:

- define concept;
    
- distinguish concepts;
    
- state mechanism;
    
- explain causal chain;
    
- identify variables/parameters;
    
- compare papers;
    
- synthesize cluster;
    
- state theorem;
    
- appraise assumption;
    
- translate to project;
    
- introduce section;
    
- conclude section.
    

No paragraph should do more than two functions.

## Drafting rule

Every substantive paragraph must satisfy at least one of the following:

- defines an object;
    
- explains a mechanism;
    
- specifies a causal relation;
    
- distinguishes variables;
    
- states a theorem or model result;
    
- compares results across papers;
    
- appraises assumptions;
    
- translates implications for the project.
    

Avoid decorative transitions and generic literature-review filler.

## Citation rule

Use author-year citation style in the draft.

Preferred format:

```text
(Hirano and Stiglitz, 2025, p. xx)
(Hirano, Jinnai, and Toda, 2024, pp. xx–xx)
(Stiglitz, 2015, p. xx)
```

If exact pages are not available, mark the paragraph with:

```text
[CITATION CHECK: page needed]
```

Do not fabricate page numbers.

Do not cite NotebookLM. Cite the original paper.

## Argumentation rule

The review must move from object to mechanism to consequence.

Preferred sequence:

```text
definition → mechanism → causal chain → variables → model result → implication → limitation
```

Avoid sequence drift:

```text
paper summary → paper summary → paper summary → generic critique
```

The review is organized by relations, not by one-paper-after-another summaries.

## Synthesis cluster logic

Build the synthesis around these clusters:

### Cluster A — Land, wealth, and capital

Purpose: establish why land-price inflation may raise measured wealth without raising productive capacity.

### Cluster B — Land speculation and capital formation

Purpose: explain how land absorbs savings and financing that could otherwise support productive capital.

### Cluster C — Credit and collateral

Purpose: explain why credit expansion can become growth-retarding when routed through land and real estate.

### Cluster D — Unbalanced growth and overvaluation

Purpose: explain why land prices can separate from land rents under nonstationary growth dynamics.

### Cluster E — R versus G and debt rollover

Purpose: explain why land modifies standard debt-sustainability arguments.

### Cluster F — Policy and institutional translation

Purpose: assess what the project can use and what must be adapted.

## Review voice

Use direct scholarly prose.

Avoid:

- “This section explores…”
    
- “This paper aims to…”
    
- “It is important to note…”
    
- “The literature shows a complex relationship…”
    
- “In today’s world…”
    
- “This provides valuable insights…”
    

Prefer:

- “The mechanism is…”
    
- “The result depends on…”
    
- “The distinction matters because…”
    
- “The model implies…”
    
- “The claim does not travel directly because…”
    

## Anti-conflation rules

Never conflate:

- land rent with housing rent;
    
- land price with real-estate price;
    
- wealth with productive capital;
    
- capital gain with productive accumulation;
    
- credit expansion with productive investment;
    
- low interest rates with higher growth;
    
- land overvaluation with any increase in land price;
    
- bubble with irrationality;
    
- R < G with automatic inefficiency;
    
- Pareto efficiency with impossibility of debt rollover.
    

## Formalization rule

Use equations only when necessary.

Permitted formal objects:

```text
P_t = land price
D_t = land rent or dividend
K_t = productive capital
R = gross return or interest factor
G = growth factor
P_t > fundamental value = land overvaluation
```

A formal expression must be followed by a plain-language interpretation.

Do not let the review become a theorem-by-theorem technical appendix.

## Critical appraisal rule

Critique should be organized around transportability.

Ask:

- What does the model clarify?
    
- What does it abstract from?
    
- Which assumptions are necessary for the result?
    
- Which assumptions are restrictive for Latin American urban land markets?
    
- What would need to be added for Fondecyt?
    
- Does the mechanism survive when institutions, state policy, and urban spatial differentiation are introduced?
    

## Minimum draft standard

A complete first draft must include:

- review question;
    
- corpus description;
    
- method paragraph;
    
- conceptual definitions;
    
- four mechanism sections;
    
- policy implications;
    
- critical appraisal;
    
- conclusion;
    
- bibliography placeholder;
    
- citation audit.
    

## Citation audit

After drafting, create `citation_audit.md` with:

```text
paragraph_id:
claim:
citation:
page_ref:
source_id:
validation_status:
problem:
fix_needed:
```

No final draft is complete until every substantive paragraph has a citation audit entry.

## Final command behavior

When asked to draft, proceed in this order:

1. Read the source registry.
    
2. Read the extraction matrix.
    
3. Read the concept dictionary.
    
4. Read the mechanism ledger.
    
5. Build the argument spine.
    
6. Build the section outline.
    
7. Build the paragraph plan.
    
8. Draft section by section.
    
9. Run citation audit.
    
10. Produce revision log.
    

Do not skip the paragraph plan.