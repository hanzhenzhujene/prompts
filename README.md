# prompt-kitchen

Personal prompt library for AI assistants. Principle-based, generic, composable.

## Usage

Paste `core.md`. Optionally append one or more mode files. Then state the task.

```
[core.md]
[modes/<task-type>.md]    # optional, repeat as needed
<your specific task>
```

## Files

| File | When to layer in |
|---|---|
| `core.md` | Always |
| `modes/analyze.md` | Research, analysis, thinking through problems |
| `modes/business.md` | Business framing, strategy, decision memos |
| `modes/code.md` | Writing, debugging, or reviewing code |
| `modes/communication.md` | Structured communication, executive briefings |
| `modes/bracketed-skimmable-update.md` | Quick chat syncs, communicating up |
| `modes/continue.md` | Resuming agentic work mid-session |
| `modes/readme-infrastructure-map.md` | README-style plain-text diagrams |
| `modes/write.md` | Essays, documents, prose |

## Recipes

| Task | Use |
|---|---|
| Quick communicating-up chat sync | `core.md` + `modes/communication.md` + `modes/bracketed-skimmable-update.md` |
| Verbal team update | `core.md` + `modes/communication.md` + `modes/business.md` |
| Business analysis | `core.md` + `modes/analyze.md` + `modes/business.md` |
| Coding agent work | `core.md` + `modes/code.md` |
| Resume interrupted coding work | `core.md` + `modes/continue.md` + `modes/code.md` |
| README or project diagram | `core.md` + `modes/readme-infrastructure-map.md` |
| Prose or email drafting | `core.md` + `modes/write.md` |

## What this encodes

MECE decomposition. First principles. Decision-orientation. Clarity, simple words, no fluff.

## Design note

Specific prompts overfit. Transferable principles work across more situations than situation-specific scripts. When in doubt, leave it out. Add a new mode only when an existing one demonstrably fails on a recurring task type.
