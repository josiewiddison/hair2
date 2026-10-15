# Atelier 01 — Hair2 salon demo

Responsive salon concept inspired by the hair2 section of the website design Pinterest board. Created with MagicPath and the gpt-taste design workflow.

## Run locally

Requires Node.js 20.19+ (Node.js 22 recommended) and pnpm.

```sh
pnpm install
pnpm dev
```

## Production

```sh
pnpm build
pnpm preview
```

Deploy the generated `dist/` directory to a static host. Vite serves imagery from `public/assets/`. Google Fonts are loaded externally; local system fonts are available as fallbacks.

## Features

- Responsive desktop and mobile navigation
- Expandable service menu
- Native modal booking demonstration with keyboard support
- GSAP pinned circular-window portrait reveal with reduced-motion support
- Six object-photography service tiles with descriptions, durations, prices and expandable details
- Semantic headings, image alternatives, labels, and visible focus styles

## Demo content

Atelier 01 is a fictional salon. Prices and copy are illustrative. The booking flow stores no personal data and makes no reservation. Add verified business details and a real booking integration before a business launch.

Photography: Unsplash images by their original photographers. Sources:
- https://images.unsplash.com/photo-1524504388940-b1c1722653e1
- https://images.unsplash.com/photo-1562322140-8baeececf3df
- https://images.unsplash.com/photo-1522337360788-8b13dee7a37e

## Editorial redesign

The cover follows the approved Bold Fashion direction. Portraits use clearer inset counterparts from an earlier concept as temporary sources; full-size original photographs remain the outstanding image replacement. Service-object photography was generated for this project. DESIGN_WORKFLOW.md records the three-concept approval workflow.
