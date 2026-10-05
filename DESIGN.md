# Design system

## Direction

An editorial research dossier: warm paper, precise rules, typographic hierarchy, and diagrammatic figures. The interface should feel like a carefully edited scholarly publication rather than a corporate landing page or developer template.

## Tokens

- Paper `#f4f1ea`; deep paper `#e8e3d9`; white `#fffdf8`
- Ink `#17201e`; muted copy `#606965`; rule `#cbc7bd`
- Primary teal `#176b64`; dark teal `#0e4d48`; teal wash `#d9e8e4`
- Secondary rust `#a44f32`
- Display type: Newsreader, variable optical size, weights 400–600
- Interface/body type: DM Sans, weights 400–600
- Content width: `1180px`; body measure: maximum `70ch`
- Motion: restrained `cubic-bezier(.16, 1, .3, 1)` with reduced-motion fallback

## Composition

Pages use generous vertical intervals and thin rules rather than card grids. Serif titles carry the visual identity; compact sans labels and metadata support scanning. Research figures are authored geometric diagrams on warm-white plates. Alternating project rows and asymmetric page grids vary pacing without changing the grammar.

## Components

- Sticky header with compact desktop navigation and an accessible mobile menu.
- Text links for secondary actions; square-corner bordered buttons for primary actions.
- Outline tags reserved for research methods and interests.
- Publication rows use year, citation, and action columns; BibTeX uses native `details`.
- Long research entries pair a sticky title rail with an evidence-rich project body.
- The CV uses date/content rows and collapses cleanly for mobile and print.

## Responsive and accessibility

At `800px`, major grids become single-column and navigation becomes a disclosure menu. At `520px`, dense metadata rows stack. The system includes skip navigation, visible focus rings, high-contrast selection, semantic headings, descriptive figure text, and `prefers-reduced-motion` support.
