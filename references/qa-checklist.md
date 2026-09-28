# QA Checklist

## Must pass

- The image is 16:9 by default and still works as a thumbnail or crop.
- The black cat witch is recognizable immediately.
- The character remains pixel-art while the environment remains clear, hand-drawn, and ink/marker-based in hybrid mode.
- The cat performs the core conceptual action; she is not a decorative observer.
- Grey, blue, and pink are the dominant brand signals.
- There is no dominant yellow, gold, orange, tan, neon, or rainbow gradient.
- One image explains one core idea and one visual mechanism.
- The prompt names exactly one mechanism; it does not combine path, workflow, comparison, or comic as separate mechanisms.
- The scene has a clear negative-space area for later Chinese labels.
- The image is rounded, cute, abstract, and approachable without becoming a children's cartoon or sticker.
- There is no dense dashboard, formal flowchart, nested-card stack, or generic AI control panel.
- No unrequested witch hat, wand, laptop, spellbook, potion, extra character, title, logo, or watermark was added.

## Failure signals and targeted fixes

| Failure | Fix |
|---|---|
| Too yellow or warm | Reassert the exact grey-blue-pink tokens; remove yellow/gold/orange/tan and cool the canvas. |
| Too sharp or threatening | Replace pointed forms with rounded ears, paws, cloak, symbols, and soft pixel clusters. |
| Whole image became pixel art | Restore the hybrid contract: pixel cat, hand-drawn ink/marker environment. |
| Too neat or vector-like | Restore slight organic line variation, imperfect corners, flat fills, and a human sketch rhythm without making the image muddy. |
| Cat is only decoration | Give her the physical action that explains the idea. |
| Too literal or crowded | Remove props; keep one main object and one mechanism. |
| Looks like a dashboard or PPT | Remove title bars, grids, nested cards, and excess arrows; keep one restrained window at most. |
| IP drift | Reuse the bundled identity reference and restore the stable invariants. |
| Generated text is broken | Remove image text and reserve clean space for layout-stage typography. |

## Final judgment

The strongest result makes the viewer notice the black cat first, understand the single action within three seconds, and feel the grey-blue-pink brand without being told the palette. If removing half the props improves clarity, remove them.
