# Design Taste Frontend

**Command:** `/design-taste-frontend`
**Source:** [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)

## What It Does

The core high-agency frontend skill. Acts as a senior UI/UX engineer that overrides default LLM design biases. Enforces metric-based rules, strict component architecture, CSS hardware acceleration, and balanced design engineering.

## Design Dials (Default Values)

| Dial | Default | Range | Meaning |
|---|---|---|---|
| `DESIGN_VARIANCE` | 8 | 1–10 | 1 = perfect symmetry, 10 = artsy chaos |
| `MOTION_INTENSITY` | 6 | 1–10 | 1 = static, 10 = cinematic/magic physics |
| `VISUAL_DENSITY` | 4 | 1–10 | 1 = art gallery/airy, 10 = cockpit/packed |

You can override these in your chat prompt (e.g. "use motion intensity 9").

## Key Rules It Enforces

- **Framework:** React/Next.js with Server Components by default
- **Styling:** Tailwind CSS (checks v3 vs v4 first)
- **Icons:** Phosphor or Radix UI only (no Lucide)
- **Fonts:** Geist, Outfit, Cabinet Grotesk, or Satoshi — Inter is banned
- **No emojis** anywhere in code or markup
- **No `h-screen`** — always `min-h-[100dvh]` for mobile safety
- **No 3-column equal card layouts**
- **No purple/blue AI gradient aesthetic**
- **No pure black** (#000000) — use Zinc-950 or charcoal

## What It Generates

- Full interaction cycles (loading skeletons, empty states, error states, active feedback)
- Magnetic buttons, liquid glass effects, staggered animations
- Bento grid layouts, asymmetric heroes, cinematic scroll reveals
- Framer Motion with spring physics (`stiffness: 100, damping: 20`)
- Hardware-accelerated animations (transform + opacity only)

## When to Use

Any new frontend component, page, or feature where you want non-generic, premium output.
