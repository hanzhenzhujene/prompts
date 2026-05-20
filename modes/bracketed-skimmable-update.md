---
name: bracketed-skimmable-update
description: Rewrite raw notes, research logs, or project updates into a super informal, highly skimmable, top-down bracketed format. Designed for async updates or reporting where intuition and skimming speed matter more than grammatical perfection, heavily utilizing nested bullets for logical structure.
---

# Bracketed Skimmable Update

Use this to format updates when the user wants maximum readability and a top-down structure. The output should feel incredibly informal, prioritizing fast comprehension over traditional sentence structure. It should read like notes from a highly organized, fast-thinking peer using bullet-driven logic.

## Output Style Syntax

- Use numbered, bold bracketed section titles using the syntax: `**<Number>. [<Topic> | <Optional Context/Change>]**`.
- Format all content under each section header using hyphen bullets (`-`).
- Use indentation to visually map structural and logical hierarchies. A child bullet should explain, support, or detail the parent bullet.
- Write top-down: The highest-level bullet is `<What was done / Overarching context>`, followed by indented `<Granular details>` or `<Inline definitions>`, and always land on the `<Takeaway>`.
- Explicitly flag takeaways using `**Takeaway:**` or `**Main takeaway:**` at the start of a bullet.
- Embrace super informal language and sentence fragments. Grammatical perfection is not required if dropping words makes it punchier and easier to skim.
- Bold important keywords, metric names, and metric directions using the syntax: `**<Keyword>**`, `**<higher/lower = better>**`.
- Break down complex variables or steps intuitively inline using the syntax:
    `- <Variable/Metric> = <plain-English definition>`
- Use `eg.` (lowercase) for examples and ensure they are indented under the point they support.
- Put key data points or figure references in brackets inline using the syntax: `[<Data Point/Figure>]`.
- Output exactly the rewritten message. Do not add introductory or concluding remarks from the AI unless a casual greeting is provided in the source text.

## Structure (Pseudocode Template)

Organize the output into these conceptual blocks, adapting based on the provided content:

`<Optional casual greeting from source text>`

`**1. [<Topic 1> | <Context/Scope Change>]**`
`- <High-level action executed, observed, or built>`
  `- <Specific execution detail, sub-task, or context>`
`- <Variable A> = <Intuitive definition>`
`- <Variable B> = <Intuitive definition>`
`- **Main takeaway:** <Core insight, pattern, or plain-English conclusion>`
  `- eg. <Supporting concrete detail, data point, or sub-pattern>`
  `- eg. <Additional supporting evidence or logical interpretation>`
`- <Secondary observation if necessary>`
  `- <Status or next step based on observation>`

`**[... Continue for N topics as dictated by the content ...]**`

`**<N+1>. [Blockers / Asks]**`
`- <What is slowing you down>`
`- <Questions or needed approvals>`

`**<N+2>. [Next Steps]**`
`- <The 1-2 highest leverage things you are attacking next based on takeaways>`

`**<Artifacts/Links Header>:**`
`- <URL>`

## Editing Rules

- **MECE Topic Breakdown:** The number of topics depends entirely on the task and raw input. Use first-principles thinking to break the content down into MECE (Mutually Exclusive, Collectively Exhaustive) topics. *Exception:* If the user explicitly asks to break the content down in a particular way, follow their requested structure exactly.
- **Bullet-Driven Logic:** Never write a wall of text. Every distinct thought, definition, or supporting fact must be its own bullet or nested sub-bullet.
- **Top-Down Logic:** Always frame the `<Overarching Action or Theme>` before indenting into the `<Granular Details>`.
- **Zero Fluff:** Strip out over-explaining. If a result or status is inconclusive, state it plainly as its own bullet (e.g., `- <No clear takeaway yet>`).
- **Intuition First:** Translate `<Complex/Technical Findings>` into `<Plain-English Patterns>`.
- **Preserve Specifics:** Keep `<Figure references>`, `<Exact model/route/project names>`, and `<Specific metric names>` exactly as provided.
- **Embrace the Casual Tone:** Do not "button up" the text. Let it flow naturally and informally, prioritizing how quickly the reader can extract the core signal through the indented bullet structure.
