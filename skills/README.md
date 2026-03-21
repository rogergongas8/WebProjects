# Skills

Complete reference for all installed skills. Use slash commands in chat to invoke them.

---

## Global Skills
Installed in `~/.claude/skills/` — available in every project.

| Skill | Command | Purpose |
|---|---|---|
| [Scroll-Stop Builder](scroll-stop-builder.md) | `/scroll-stop-builder` | Takes a video file, builds a full Apple-style scroll-driven animation website |
| [Scroll-Stop Prompter](scroll-stop-prompter.md) | `/scroll-stop-prompter` | Generates 3 AI image/video prompts for product deconstruction animations |
| [Skill Creator](skill-creator.md) | `/skill-creator` | Create, improve, test, and optimize skills |

---

## Project Skills (Taste-Skill Pack)
Installed in `.agents/skills/` — symlinked to `.claude/skills/` for Claude Code.
Source: [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)

| Skill | Command | Purpose |
|---|---|---|
| [Design Taste Frontend](design-taste-frontend.md) | `/design-taste-frontend` | Core high-agency frontend skill with configurable design dials |
| [High-End Visual Design](high-end-visual-design.md) | `/high-end-visual-design` | Awwwards-tier agency design with double-bezel components and spring physics |
| [Minimalist UI](minimalist-ui.md) | `/minimalist-ui` | Editorial clean interfaces — warm monochrome, flat bento grids |
| [Industrial Brutalist UI](industrial-brutalist-ui.md) | `/industrial-brutalist-ui` | Swiss typography meets military terminal aesthetics |
| [Redesign Existing Projects](redesign-existing-projects.md) | `/redesign-existing-projects` | Audits and upgrades existing projects without breaking functionality |
| [Stitch Design Taste](stitch-design-taste.md) | `/stitch-design-taste` | Generates DESIGN.md files for Google Stitch screen generation |
| [Full Output Enforcement](full-output-enforcement.md) | `/full-output-enforcement` | Forces complete code output — bans all truncation and placeholder shortcuts |

---

## Built-In Skills
Always available, no install needed.

| Skill | Command | Purpose |
|---|---|---|
| simplify | `/simplify` | Reviews changed code for quality and efficiency, then fixes issues |
| loop | `/loop` | Runs a prompt or command on a recurring interval |
| claude-api | `/claude-api` | Build apps with the Claude API or Anthropic SDK |
| update-config | `/update-config` | Configure settings.json, hooks, permissions, and env vars |
| keybindings-help | `/keybindings-help` | Customize keyboard shortcuts in Claude Code |

---

## Quick Combos

- **New premium UI** → `/design-taste-frontend` or `/high-end-visual-design`
- **Clean/minimal vibe** → `/minimalist-ui`
- **Raw/industrial vibe** → `/industrial-brutalist-ui`
- **Upgrading existing code** → `/redesign-existing-projects`
- **Need full file output** → add `/full-output-enforcement` to any prompt
- **Google Stitch project** → `/stitch-design-taste`
- **Product animation prompts** → `/scroll-stop-prompter`
- **Scroll-driven video website** → `/scroll-stop-builder`
- **Build or improve a skill** → `/skill-creator`
