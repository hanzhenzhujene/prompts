# prompts

Personal prompt library for AI assistants. Principle-based, generic, composable.

## Usage

Paste `core.md`. Optionally append one mode file. Then state the task.

```
[core.md]
[modes/<task-type>.md]    # optional
<your specific task>
```

## Files

| File | When to layer in |
|---|---|
| `core.md` | Always |
| `modes/analyze.md` | Research, analysis, thinking through problems |
| `modes/code.md` | Writing, debugging, or reviewing code |
| `modes/write.md` | Essays, documents, prose |

## What this encodes

MECE decomposition. First principles. Decision-orientation. Clarity, simple words, no fluff.

## Design note

Specific prompts overfit. Transferable principles work across more situations than situation-specific scripts. When in doubt, leave it out. Add a new mode only when an existing one demonstrably fails on a recurring task type.
