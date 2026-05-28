# NotebookLM Question Notes Bundle

This bundle converts the Excel registry into vault-ready Markdown notes.

Use it as a controlled bridge between the paper registry, NotebookLM, and Obsidian.

## Workflow

1. Open the relevant NotebookLM notebook where the papers are already loaded.
2. Use the batch prompt files in `03_batch_prompts_for_notebooklm/` to ask questions paper-by-paper or cluster-by-cluster.
3. Paste each NotebookLM answer into the matching Markdown note under `## NotebookLM answer`.
4. Distill the answer into the `## Distilled note` section.
5. Add page anchors or quotations under `## Evidence / page anchors`.
6. Change `status: pending_notebooklm` to `status: answered` once the note has been populated.

## Naming logic

Per-paper notes follow the pattern `PDF001_Q01.md`, `PDF001_Q02.md`, and so on.
Cluster notes follow the pattern `C1_Q01.md`, `C2_Q01.md`, and so on.

## Important boundary

These files contain the questions and note containers. They do not contain NotebookLM-generated answers yet. NotebookLM must be run on your side because this chat does not have direct access to your NotebookLM workspace.
