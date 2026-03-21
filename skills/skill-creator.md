# Skill Creator

**Command:** `/skill-creator`
**Location:** Global (`~/.claude/skills/`)

## What It Does

Helps you create new skills, improve existing ones, and measure how well they work. Handles the full loop: drafting, testing, evaluating results, iterating, and optimizing how reliably a skill triggers.

## The Loop

1. **Capture intent** — figure out what the skill should do, when it should trigger, and what it outputs
2. **Interview** — ask about edge cases, formats, examples, and success criteria
3. **Write SKILL.md** — draft the skill file
4. **Run test cases** — spawn test runs with and without the skill to compare
5. **Review results** — opens a browser viewer with qualitative outputs + quantitative benchmarks
6. **Iterate** — improve the skill based on feedback, repeat
7. **Optimize description** — run an automated loop to improve how reliably the skill triggers

## When to Use It

- You want to create a brand new skill from scratch
- You want to improve or fix an existing skill
- You want to benchmark how much a skill actually improves output
- You want to optimize a skill's description so it triggers more reliably

## What a Skill Is

A skill is a folder with a `SKILL.md` file (plus optional scripts, references, and assets):

```
my-skill/
├── SKILL.md          ← required, has YAML frontmatter + instructions
├── scripts/          ← reusable scripts for repetitive tasks
├── references/       ← docs loaded into context as needed
└── assets/           ← templates, icons, files used in output
```

The `description` field in the frontmatter is what Claude reads to decide whether to use the skill — it's the most important part for reliable triggering.

## Notes

- It adapts to your technical level — no jargon if you don't need it
- You can skip the eval loop if you just want to vibe and iterate quickly
- Description optimization runs an automated multi-iteration test loop (takes a few minutes)
