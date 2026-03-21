# Minimalist UI

**Command:** `/minimalist-ui`
**Source:** [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)

## What It Does

Generates ultra-minimalist, document-style web interfaces — think Notion, Linear, or high-end workspace platforms. Enforces warm monochrome palettes, bespoke typography, extreme whitespace, and flat bento-grid layouts.

## Design Language

### Palette
- **Background:** Pure White `#FFFFFF` or Warm Off-White `#F7F6F3`
- **Text:** Off-black `#111111` or `#2F3437` (never pure black)
- **Secondary text:** Muted gray `#787774`
- **Borders:** Ultra-light `#EAEAEA` or `rgba(0,0,0,0.06)`
- **Accents:** Highly desaturated pastels only (pale red, blue, green, yellow)

### Typography
- **Headlines:** Lyon Text, Newsreader, Playfair Display, or Instrument Serif — tight tracking, 1.1 line-height
- **Body:** SF Pro Display, Geist Sans, Switzer — relaxed leading, 65ch max-width
- **Mono:** Geist Mono, JetBrains Mono — for code, metadata, keystrokes

## Key Rules

- No gradients, neon colors, or heavy glassmorphism
- No pill shapes (`rounded-full`) for large containers or buttons
- No emojis — replace with Phosphor or Radix icons
- No AI clichés: "Elevate", "Seamless", "Unleash", "Next-Gen"
- Cards use exactly `border: 1px solid #EAEAEA` with max `12px` radius
- Buttons: solid `#111111` background, `4–6px` radius, no box-shadow
- Motion is invisible — `translateY(12px)` + opacity fade over 600ms

## When to Use

Productivity apps, documentation sites, clean dashboards, editorial blogs — anything that needs to feel calm, focused, and expensive without being showy.
