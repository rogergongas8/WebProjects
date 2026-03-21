# Redesign Existing Projects

**Command:** `/redesign-existing-projects`
**Source:** [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)

## What It Does

Audits an existing website or app and upgrades it to premium quality. Works with any existing stack — does not rewrite from scratch, does not migrate frameworks. Fixes what's there.

## How It Works

1. **Scan** — reads the codebase, identifies framework and styling method
2. **Diagnose** — runs through a comprehensive audit checklist
3. **Fix** — applies targeted upgrades in priority order

## Fix Priority Order

1. Font swap — biggest instant improvement, lowest risk
2. Color palette cleanup — remove clashing/oversaturated colors
3. Hover and active states — makes the interface feel alive
4. Layout and spacing — proper grid, max-width, consistent padding
5. Replace generic components — swap cliché patterns for modern alternatives
6. Add loading, empty, and error states — makes it feel finished
7. Polish typography scale and spacing — the premium final touch

## What It Audits

**Typography:** Default fonts, headline presence, body width, weight range, letter-spacing

**Color:** Pure black backgrounds, oversaturated accents, multiple accent colors, warm/cool gray mixing, AI purple gradient aesthetic

**Layout:** Everything centered, 3-column equal cards, `100vh` sections, no max-width container, uniform border-radius

**Interactivity:** Missing hover states, no active feedback, instant transitions, missing focus rings, no loading/empty/error states

**Content:** Generic names (John Doe, Acme), round fake numbers (99.99%), AI copywriting clichés, Lorem Ipsum

**Components:** Generic cards, pill "New" badges, accordion FAQs, 3-card carousel testimonials, modal overuse

**Code Quality:** Div soup, inline styles, hardcoded pixel widths, missing alt text, arbitrary z-index, dead code

## Rules

- Works with the existing tech stack only
- Does not break existing functionality
- Checks package.json before importing any new library
- Checks Tailwind version (v3 vs v4) before modifying config

## When to Use

Any time you want to upgrade the quality of an existing project without a full rewrite. Point it at a file or describe what you have.
