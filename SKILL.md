---
name: black-cat-witch-illustrations
description: Use when generating Chinese AI or technology tutorial illustrations, article images, workflow explainers, or visual metaphors that need a recurring cute pixel-art black cat witch, a clear hand-drawn ink/marker explanation environment, and a restrained grey-blue-pink personal-brand palette.
---

# Black Cat Witch Illustrations

## Overview

Use this skill to turn one clear idea from Chinese AI, design, product, or creator content into a memorable illustration. Keep the personal IP stable: a cute pixel-art black cat witch performs the core action inside a clear, slightly organic hand-drawn ink/marker explanation scene.

The default output is one standalone 16:9 image. The character carries recognition; the hand-drawn scene carries explanation; the grey-blue-pink system carries brand consistency.

## Core rules

- Make the black cat witch perform the central conceptual action. If removing her leaves the metaphor unchanged, redesign the action.
- Keep the character pixel-art and the surrounding explanation scene hand-drawn with clear ink/marker outlines, flat fills, slight organic variation, and readable negative space. Do not silently turn the whole scene into pixel art or a sterile vector infographic.
- Choose exactly one visual mechanism per image: workflow, system slice, comparison, state, metaphor, layering, path, or short comic. A path may show sequential change, but do not label the same image as a path plus workflow or mini-comic.
- Express one core idea per image. Do not turn an illustration into a dense dashboard, formal flowchart, or course slide.
- Use the grey-blue-pink brand system. Do not introduce dominant yellow, gold, orange, tan, neon, or rainbow gradients.
- Generate image text only when the user explicitly needs it. Prefer leaving clean space and adding Chinese labels during layout.
- Do not add a witch hat, wand, laptop, spellbook, or other signature prop by default. Add at most one or two props when the current concept requires them.
- Use the bundled reference images only for identity and palette calibration; do not copy their exact composition.

## Workflow

### 1. Extract the visual claim

Read the supplied article, script, notes, screenshot, or topic and reduce it to:

- one sentence stating the claim;
- one concrete action that makes the claim visible;
- one mechanism: workflow, system slice, comparison, state, metaphor, layering, path, or comic;
- one location for the cat and one main object or object group.

If the user asks only for planning, return a short shot list. For each shot include placement, topic, core meaning, exactly one mechanism, cat action, suggested elements, and optional short labels. Use 1–6 shots unless the brief clearly needs more.

### 2. Choose the visual mode

Use the hybrid mode by default:

- **Character:** rounded, limited-palette pixel-art black cat witch.
- **Environment:** clear hand-drawn ink or marker illustration with slightly organic line variation, simple flat shapes, crisp readable edges, and restrained paper texture.
- **Structure:** one simple hand-drawn explanation area, optionally inside one restrained grey retro window with a blue header strip.

Use full-scene pixel art only when the user asks for a cover, opening frame, game-like special, or explicit full-pixel treatment. Use all-hand-drawn only when the user asks to remove the pixel distinction.

### 3. Build the image prompt

Read the relevant references before generating:

- `references/brand-dna.md` for colors, materials, and window structure.
- `references/black-cat-witch-ip.md` for identity, expression, props, and forbidden drift.
- `references/composition-patterns.md` when the mechanism is not obvious.
- `references/prompt-template.md` for the image-generation prompt shape.
- `references/qa-checklist.md` after generation.

Use `assets/approved-style-reference.png` as the primary style reference when available. Use `assets/black-cat-witch-reference.png` only for the original silhouette and identity; it is an early reference and its yellow eyes and warm cast must not be copied. Use `assets/brand-reference.png` only for supplemental palette calibration. Do not copy any reference image's exact composition.

### 4. Generate

For a requested image, use the built-in image-generation tool and generate each asset separately. Preserve the character invariants and change only the requested subject, action, or composition. Do not wait for confirmation after the user has explicitly asked for generation.

### 5. Inspect and iterate

Run the QA checklist. If a check fails, make one targeted revision at a time: first correct identity or palette, then composition, then text or small artifacts. If the image is too busy, remove elements before adding detail.

## Output format

When planning, output the shot list only after the visual claim is clear. When generating, report the number of images, each image's purpose, the saved path when applicable, and which result is the strongest. Keep the explanation brief; the image is the primary deliverable.
