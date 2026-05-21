---
name: readme-infrastructure-map
description: Generic first-principles plain-text visualization for README-style explanations. Use when the assistant should answer a task by laying out an idea, project, method, workflow, structure, or argument as one or more concise 2D text visuals with boxes, columns, arrows, or grids so readers can grasp it quickly.
---

# README Infrastructure Map

Make the answer visual, not verbose. Use first-principles thinking to find the simplest structure behind the user's task, then render it as a compact plain-text diagram.

Before diagramming a project, inspect the project landscape carefully. Identify the audience, the current use case, the project purpose, the main components, and how those components relate. Synthesize from first principles, then choose the smallest set of visuals needed to explain the project framework clearly.

## Rules

- Use a Markdown fenced text block.
- Choose the structure from the task itself; do not force fixed labels.
- Prefer 2D layout: boxes, columns, rows, arrows, layers, grids, or side-by-side contrasts.
- Use multiple visuals when they clarify different parts of the framework, such as structure, flow, roles, inputs, outputs, or decision points.
- Start from the highest-level idea, then show the parts underneath it.
- Include the necessary project framework information: purpose, audience, use case, components, relationships, boundaries, and outputs.
- Use concrete nouns and short phrases.
- Do not add claims, metrics, sections, or explanations the user did not ask for.
- If editing a README, ground the diagram in the repo and avoid invented details.
