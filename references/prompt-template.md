# Prompt Template

Use one prompt for one standalone image. Fill the variables from the current brief.

```text
Use case: illustration-story
Asset type: 16:9 Chinese AI tutorial illustration
Input images: the bundled black-cat-witch reference for identity; the brand reference for palette and texture when available
Primary request: turn {one core idea} into one clear physical action
Subject: a cute rounded pixel-art black cat witch with charcoal fur, soft triangular ears, powder-pink or pale-blue eyes, deep-blue cloak, and one pink-blue brooch; she must perform the core action
Environment: a clear hand-drawn ink/marker explanation scene with slightly organic outlines, simple flat forms, crisp edges, and generous negative space
Mechanism: choose exactly one of {workflow / system slice / comparison / state / metaphor / layering / path / mini-comic}; do not combine two names
Composition: {where the cat is, what she is doing, one main object or object group, and how the idea reads}
Palette: grey, deep blue, pale blue, pale pink, dusty pink, dark ink; no dominant yellow, gold, orange, tan, neon, or rainbow gradient
Materials: chunky limited-palette pixels for the cat; clear hand-drawn ink/marker lines and flat grey-blue-pink fills for the environment; restrained paper texture only
Text: no generated text unless explicitly requested; leave clean space for later Chinese labels
Constraints: one idea, one mechanism, rounded forms, soft blunt silhouettes, no combined mechanism labels, no dense UI, no formal PPT, no extra characters, no watermark
```

For edits, state the invariants first:

```text
Edit the provided image. Preserve the cat's silhouette, pixel construction, facial identity, and the hand-drawn environment. Change only {requested change}. Keep the grey-blue-pink palette, rounded forms, one main mechanism, and all negative space. Remove any yellow/gold/orange cast. Do not add text, a logo, or a watermark.
```
