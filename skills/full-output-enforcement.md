# Full Output Enforcement

**Command:** `/full-output-enforcement`
**Source:** [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)

## What It Does

Overrides default LLM truncation behavior. Forces complete, unabridged code generation. Treats every task as production-critical — a partial output is a broken output.

## Banned Output Patterns

**In code blocks:**
- `// ...`, `// rest of code`, `// implement here`, `// TODO`
- `/* ... */`, `// similar to above`, `// continue pattern`
- `// add more as needed`, bare `...` standing in for omitted code

**In prose:**
- "Let me know if you want me to continue"
- "I can provide more details if needed"
- "for brevity", "the rest follows the same pattern"
- "similarly for the remaining", "and so on"
- "I'll leave that as an exercise"

**Structural shortcuts:**
- Outputting a skeleton when a full implementation was asked for
- Showing first and last section while skipping the middle
- Replacing repeated logic with one example + description
- Describing what code should do instead of writing it

## How It Handles Long Outputs

When approaching token limit, it doesn't compress — it stops at a clean breakpoint (end of function/file/section) and outputs:

```
[PAUSED — X of Y complete. Send "continue" to resume from: next section name]
```

On "continue" it picks up exactly where it stopped with no recap.

## When to Use

- When asking for full file implementations
- When generating multiple components at once
- When previous responses were truncated or used placeholder comments
- Combine with any other skill for guaranteed complete output
