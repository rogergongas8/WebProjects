# Stitch Design Taste

**Command:** `/stitch-design-taste`
**Source:** [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)

## What It Does

Generates a `DESIGN.md` file optimized for [Google Stitch](https://labs.google.com/stitch) screen generation. Translates premium anti-slop design directives into Stitch's native semantic design language — natural-language rules paired with precise values that Stitch's AI agent can interpret.

The `DESIGN.md` it creates becomes the single source of truth for prompting Stitch to generate new screens that match a curated, high-agency design language.

## What the Generated DESIGN.md Contains

1. **Visual atmosphere** — mood, density, variance, motion intensity
2. **Color calibration** — neutrals, accents, and banned patterns with hex codes
3. **Typographic architecture** — font stacks, scale hierarchy, anti-patterns
4. **Component behaviors** — buttons, cards, inputs with interaction states
5. **Layout principles** — grid systems, spacing philosophy, responsive strategy
6. **Motion philosophy** — spring physics, perpetual micro-interactions
7. **Anti-patterns** — explicit list of banned AI design clichés

## Default Design Dials

Same as design-taste-frontend: Variance 8, Motion 6, Density 4. Adapts based on your described vibe.

## Key Enforced Rules

- Max 1 accent color, saturation < 80%
- No AI purple/blue neon aesthetic
- Inter font banned — use Geist, Outfit, Cabinet Grotesk, or Satoshi
- Generic serifs banned — if editorial, use Fraunces, Gambarino, or Editorial New
- Centered hero layouts banned when variance > 4
- 3-column equal card grids banned
- No overlapping elements — every element has its own clean spatial zone
- Inline image typography in heroes (photos between words as visual punctuation)

## When to Use

When working with Google Stitch and you want consistent, premium screen generation that doesn't look generic. Run this once per project to create your DESIGN.md, then reference it in all Stitch prompts.
