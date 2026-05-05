# LLM Wiki
A personal knowledge base maintained by any Ai Agent.
Based on Andrej Karpathy's LLM Wiki pattern.
    
## Purpose
- This wiki is a structured, interlinked knowledge base. <for which exact usecase?>
- An AI Agend maintains the wiki. The human curates sources, asks questions, and guides the analysis.

## Folder structure
```
- source/ -- source documents (immutable -- never modify these)
- wiki/ -- markdown pages maintained by Claude
- index.md -- table of contents for the entire wiki
- log.md -- append-only record of all operations
```

# Rules

## Citation rules
- Every factual claim should reference its source file
- Use the format (source: filename.pdf) after the claim
- If two sources disagree, note the contradiction explicitly
- If a claim has no source, mark it as needing verification
## Do
- Always update `index.md` and `log.md` after executing workflows: Insert, Lint, adding of answares as new concepts.
- Keep page names lowercase with hyphens (e.g. `machine-learning.md`)
- Write in clear, plain language.
- When uncertain about how to categorize something, ask the user.

## Dont
- Never modify anything in the `Source/` folder.
- Never write a summary file without referencing the original source from `Source/`.
# Concept wiki Page format
for reference look at: @./Context/Concept_Page_Template.md

# Workflows  
## Insert workflow
for reference look at: @./Context/Insert_Workflow.md

## Question answering
for reference look at: @./Context/Question_Workflow.md

## Lint
for reference look at: @./Context/Lint_Workflow.md