# Scroll-Stop Builder

**Command:** `/scroll-stop-builder`
**Location:** Global (`~/.claude/skills/`)

## What It Does

Takes a video file and builds a production-quality website where the video plays forward/backward as you scroll — the same technique Apple uses for product pages. Includes a full interview before building anything so everything is customized to your brand.

## Prerequisites

- FFmpeg installed on your machine
- A video file (MP4, MOV, WebM) — ideally 3–10 seconds
- The **first frame must be on a white background** (hard requirement)

## The Interview (Always Happens First)

Before touching any code, it asks you:
1. Brand/product name
2. Logo file (SVG or PNG preferred)
3. Accent color (hex or description)
4. Background color (dark works best)
5. Overall vibe (premium tech, luxury, playful, minimal, bold...)
6. Content source — existing website URL or paste it in yourself
7. Optional: testimonials, confetti effect, 3D card scanner section

## What Gets Built

A single HTML file with these sections:
1. Animated starscape background
2. Full-screen loader with brand logo + progress bar
3. Scroll progress bar (fixed top)
4. Navbar that morphs from full-width to a floating pill on scroll
5. Hero section with orbs, CTA buttons
6. **Scroll animation** — sticky canvas + annotation cards that snap-stop as you scroll
7. Specs section with count-up numbers
8. Feature cards (glassmorphism)
9. CTA section
10. Testimonials *(if opted in)*
11. 3D card scanner *(if opted in)*
12. Footer

## How It Works Technically

1. FFmpeg extracts frames from your video (targets 60–150 frames total)
2. All frames preload as images with a loading indicator
3. Scroll position maps to a frame index — scroll forward = video advances, scroll back = video reverses
4. Canvas rendering with Retina/HiDPI support

## When to Use

Say: `"scroll-stop build"`, `"scroll animation website"`, `"build the scroll-stop site"`, `"video on scroll"`, or `"Apple-style scroll animation"`
