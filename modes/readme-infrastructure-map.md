---
name: readme-infrastructure-map
description: Generic first-principles plain-text visualization for README-style explanations. Use when the assistant should explain an idea, project, method, workflow, structure, or argument through concise 2D text visuals with boxes, columns, arrows, or grids.
---

# README Infrastructure Map

Make the answer visual, not verbose. Use first-principles thinking to find the simplest structure behind the user's task, then render it as a compact set of plain-text diagrams.

For repo or project tasks, first inspect the project landscape carefully. Identify the audience, current use case, project purpose, main components, relationships, boundaries, and outputs. Synthesize the framework from first principles before drawing so the visuals explain the actual system, not a generic template.

## Rules

- Use Markdown fenced text blocks.
- Choose the structure from the task itself; do not force fixed labels.
- Prefer 2D layout: boxes, columns, rows, arrows, layers, grids, or side-by-side contrasts.
- Use multiple small visuals when different views clarify different questions, such as structure, flow, roles, inputs, outputs, or decision points.
- Start from the highest-level idea, then show the parts underneath it.
- Include only necessary framework information supported by the repo, source material, or user-provided context.
- If source material is unavailable, state assumptions and use only the context the user provided.
- Use concrete nouns and short phrases.
- Do not add claims, metrics, sections, or explanations the user did not ask for.
- If editing a README, ground the diagram in the repo and avoid invented details.
