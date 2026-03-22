# Scroll-Stop Prompter

**Command:** `/scroll-stop-prompter`
**Location:** Global (`~/.claude/skills/`)

## What It Does

Generates a coordinated set of 3 copy-paste text prompts for AI image and video generators. Not websites or code — just prompts you paste into Midjourney, Flux, Runway, Kling, etc.

Delivers them in a beautiful HTML page that opens automatically, with one-click copy buttons and confetti on each copy.

## The 3 Prompts It Creates

### Prompt A — Assembled Shot
Clean hero product image on a pure white background. Optimized for AI image generators. Photorealistic, 16:9, Apple-style product photography.

### Prompt B — Deconstructed / Exploded View
The same object elegantly taken apart — every internal component floating in space on a white background, maintaining spatial relationships. Includes a real component list specific to your object type (laptops, phones, shoes, food/beverages, etc.).

### Prompt C — Video Transition (two versions)
**C1 — With References:** For when you've already generated A and B. Upload A as start frame, B as end frame, and paste C1 as the motion prompt. Saves tokens — the model uses your images as visual anchors.

**C2 — Standalone:** A fully self-contained prompt you paste directly into any video model with no images needed. Describes the assembled object, the deconstruction motion, and the final exploded state all in one go. Use this to skip generating A and B entirely and go straight to video.

## Workflow

1. Give it an object name ("laptop") or a full brief ("tech company laptop that disassembles by layers")
2. It generates all 3 prompts immediately — no clarifying questions if you gave enough context
3. A `prompts.html` file opens in your browser with tabbed A/B/C navigation and copy buttons
4. Paste each prompt into your preferred AI tool

## Tips

- Always generate Prompt A first, then reference it when generating Prompt B for visual consistency
- The reverse animation (parts assembling) is often just as compelling — ask for it
- Works best for objects with interesting internals: electronics, shoes, vehicles, food

## When to Use

Say: `"scroll-stop prompt"`, `"deconstruction prompt"`, `"exploded view prompt"`, `"product animation prompt"`, or ask for prompts to create scroll-stopping video content.
