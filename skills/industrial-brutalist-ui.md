# Industrial Brutalist UI

**Command:** `/industrial-brutalist-ui`
**Source:** [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)

## What It Does

Architects interfaces that fuse mid-century Swiss typography, industrial manufacturing manuals, and retro-futuristic aerospace/military terminal aesthetics. Raw functionality, mechanical precision, high data density.

## Two Modes (Pick One Per Project)

### Swiss Industrial Print
- Light mode on newsprint/off-white substrate
- Monolithic heavy sans-serif typography
- Visible grid lines, aggressive asymmetric negative space
- Oversized viewport-bleeding numerals
- Heavy primary red as the only accent

### Tactical Telemetry / CRT Terminal
- Dark mode exclusive (`#0A0A0A` background)
- High-density tabular data, monospaced typography
- ASCII framing devices, crosshairs, technical brackets
- Simulated CRT scanlines, phosphor glow effects
- Optional terminal green `#4AF626` for one specific element only

## Typography Rules

| Type | Fonts | Size | Case |
|---|---|---|---|
| Macro Headers | Archivo Black, Monument Extended | `clamp(4rem, 10vw, 15rem)` | UPPERCASE |
| Data/Telemetry | JetBrains Mono, IBM Plex Mono, VT323 | 10–14px | UPPERCASE |
| Artistic Disruption | Playfair Display (degraded with halftone) | Sparse use | Mixed |

## Color Rules

- Max 2 colors: substrate + foreground + one red accent (`#E61919`)
- No gradients, soft shadows, or modern translucency
- All corners are exactly 90 degrees — no `border-radius`

## Signature Effects

- **CRT Scanlines:** `repeating-linear-gradient` over the background
- **Halftone/Dithering:** Images converted to dot-matrix patterns
- **Mechanical Noise:** Global low-opacity SVG noise filter on DOM root
- **Blueprint Grid:** `display: grid; gap: 1px` with contrasting colors for razor-thin dividers

## When to Use

Data-heavy dashboards, developer portfolios, editorial sites, or anything that needs to feel like a declassified blueprint or military operations terminal.
