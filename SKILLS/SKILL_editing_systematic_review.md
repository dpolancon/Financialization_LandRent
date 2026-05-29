# SKILL — Post-Draft Editorial Pass for Systematic Review Prose

## Mission

Revise a completed systematic-review draft to restore scholarly voice, remove generic AI-like prose patterns, compress over-structured writing, and improve argumentative flow without changing the underlying claims, citations, evidence, or section architecture.

This is a post-drafting skill. It must not replace the systematic-review drafting skill. It begins only after a draft, paragraph plan, and citation audit already exist.

## Inputs

Expected inputs:

```text
review_artifacts/
  04_draft/
    systematic_review_draft.md
    paragraph_plan.md
    citation_audit.md
```

Optional inputs:

```text
review_artifacts/
  03_synthesis/
    argument_spine.md
    section_synthesis_tables.md
    contradiction_and_tension_map.md
```

## Outputs

Create or update:

```text
review_artifacts/
  04_draft/
    systematic_review_draft_edited.md
    editorial_change_log.md
    unresolved_style_or_claim_flags.md
```

## Core principle

Edit prose, not evidence.

Do not add new claims.  
Do not remove citations.  
Do not invent page numbers.  
Do not alter the theoretical meaning of a claim.  
Do not flatten conceptual distinctions.  
Do not convert uncertainty into certainty.

## Editorial objective

Make the draft read like a controlled scholarly review written by the author, not like a generic synthesis machine.

The edited version should be:

- less signposted;
    
- less formulaic;
    
- less repetitive;
    
- more argumentative;
    
- more precise;
    
- more conceptually grounded;
    
- more fluent at the paragraph level;
    
- faithful to the validated evidence.
    

## Patterns to remove

Remove or rewrite phrases such as:

```text
This section explores...
This paper aims to...
It is important to note that...
The literature highlights...
This provides valuable insights...
A complex relationship exists between...
In today's world...
This review seeks to understand...
The findings suggest that...
```

Replace them with direct claims:

```text
The mechanism is...
The result depends on...
The distinction matters because...
The model implies...
The claim travels only under...
The mechanism becomes unstable when...
```

## Paragraph-level rules

Each paragraph should do one main job.

Allowed paragraph functions:

- define a concept;
    
- distinguish concepts;
    
- explain a mechanism;
    
- specify a causal chain;
    
- compare model results;
    
- identify variables;
    
- state a theorem;
    
- appraise assumptions;
    
- translate implications for the project.
    

If a paragraph performs more than two functions, split or compress it.

## Sentence-level rules

Prefer sentences that carry argument.

Each sentence should do at least one of the following:

- define an object;
    
- specify a relation;
    
- state a condition;
    
- explain a mechanism;
    
- mark a contrast;
    
- report a result;
    
- qualify a claim;
    
- connect the model to the project.
    

Delete sentences that merely announce structure.

## Anti-flattening rule

Do not replace precise terms with generic ones.

Preserve distinctions between:

- land rent and housing rent;
    
- land price and real-estate value;
    
- wealth and productive capital;
    
- capital gains and capital formation;
    
- credit expansion and productive investment;
    
- land overvaluation and land-price increase;
    
- bubble and irrationality;
    
- R < G and dynamic inefficiency;
    
- Pareto efficiency and debt-rollover possibility.
    

## Compression rule

Compress by removing scaffolding, not substance.

Preferred cuts:

- redundant topic sentences;
    
- duplicated transitions;
    
- excessive “however/therefore” scaffolding;
    
- inflated summaries;
    
- repeated restatement of the review question;
    
- generic implications.
    

Do not cut:

- definitions;
    
- conditions;
    
- causal links;
    
- citations;
    
- theoretical distinctions;
    
- project-specific appraisal.
    

## Citation rule

Citations must remain attached to the claims they support.

If editing moves a claim, move its citation with it.

If a sentence becomes broader than the original citation supports, add:

```text
[CITATION SCOPE CHECK]
```

If a paragraph has no citation but makes a substantive claim, add:

```text
[CITATION NEEDED]
```

## Voice rule

Use direct scholarly prose.

Avoid grand synthesis language.

Prefer:

```text
Hirano and Stiglitz do not treat land-price inflation as a neutral asset-market adjustment. Their mechanism turns on the allocation of savings between land and productive capital.
```

Avoid:

```text
This section explores how Hirano and Stiglitz provide valuable insights into the complex relationship between land-price inflation and productive capital formation.
```

## Argument continuity rule

Paragraphs should link through concepts, not through announcements.

Weak transition:

```text
Having discussed credit, the next section turns to unbalanced growth.
```

Stronger transition:

```text
Credit expansion matters because it changes the valuation of land; unbalanced growth matters because it changes the relation between that valuation and the rent stream that supposedly anchors it.
```

## Critique rule

Critique must be specific.

Avoid:

```text
The models have limitations.
```

Prefer:

```text
The models clarify the macro-financial mechanism, but their abstraction from zoning, legal property regimes, developer finance, and metropolitan rent gradients limits direct transfer to Latin American urban land markets.
```

## Editing sequence

Run the pass in this order:

1. Check that every paragraph has a clear function.
    
2. Remove generic section-announcement prose.
    
3. Compress repetitive transitions.
    
4. Restore conceptual precision.
    
5. Strengthen causal verbs.
    
6. Preserve citations and page references.
    
7. Flag unsupported or broadened claims.
    
8. Produce an edited draft.
    
9. Produce an editorial change log.
    

## Change log format

For each major edit, record:

```text
paragraph_id:
edit_type:
before_problem:
after_solution:
claim_changed: yes/no
citation_changed: yes/no
flag:
```

## Prohibited behavior

Do not rewrite the draft into a different argument.

Do not remove the systematic-review method section.

Do not make the prose more dramatic than the evidence allows.

Do not turn the review into a polemic.

Do not erase uncertainty markers where the source requires them.

Do not claim the text is “AI-free” or “undetectable.” The goal is authorial clarity and scholarly prose quality, not detector evasion.