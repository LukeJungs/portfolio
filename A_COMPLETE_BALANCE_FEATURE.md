# A Complete Balance — Homepage Feature Specification

## Positioning

**A Complete Balance** is the homepage’s lead work and the first meaningful visual encounter after navigation. It presents Luke Heesun Jung as a designer working across **Media Art, Healthcare Storytelling, and Generative AI**, while the existing portfolio grid remains available as supporting practice.

## Hero Hierarchy

| Layer | Content | Purpose |
|---|---|---|
| Eyebrow | Featured Work · 2026 | Establishes recency and priority |
| Title | A Complete Balance | Makes the project the homepage’s dominant statement |
| Thesis | A poetic media-art experience about AI, medical imagery, and the human body. | Explains the work without overclaiming |
| Disciplines | Media Art · Healthcare Storytelling · Generative AI | Uses the exact requested categories |
| Primary action | Enter the case study ↗ | Opens the permanent case-study URL |
| Secondary action | Watch the film | Jumps to the film section on the case-study page |

## Visual Direction

The lead section uses the project’s warm Bauhaus stage image as a full-bleed, high-key backdrop. Dark charcoal typography sits in a solid warm-paper panel on the right-side negative space, guaranteeing contrast. A cobalt rule, vermilion index block, and yellow micro-accent echo the artwork without converting the existing portfolio into a themed microsite.

The prior typewriter introduction is retained as a compact identity statement below the featured work rather than competing with it above the fold. The existing selected-work grid follows, with A Complete Balance repeated as the first wide card for users who enter through the work anchor.

## Permanent Links and Assets

The homepage stores the hero and brand mark locally in `assets/a-complete-balance/` so GitHub Pages does not depend on a temporary asset host. The case-study destination is `https://balancecase-nppyehfn.manus.space/`; the film anchor is `https://balancecase-nppyehfn.manus.space/#film`.

## Accessibility and Motion

The hero image receives descriptive alt text. Text does not sit directly on variable-brightness image areas. All calls to action remain keyboard-focusable. Hover motion is limited to transform and opacity, and nonessential entrance motion is disabled under `prefers-reduced-motion`.

## References

[1]: https://balancecase-nppyehfn.manus.space/ "A Complete Balance case study"
[2]: https://lukejungs.github.io/portfolio/index.html "Luke Heesun Jung portfolio"
