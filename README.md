# prompts

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

## What this encodes

MECE decomposition. First principles. Decision-orientation. Clarity, simple words, no fluff.

## Design note

Specific prompts overfit. Transferable principles work across more situations than situation-specific scripts. When in doubt, leave it out. Add a new mode only when an existing one demonstrably fails on a recurring task type.
