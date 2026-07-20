# Flash Website MVP

Marketing landing page for Flash, a clinical memory and patient-management product. It is built with Astro and uses GSAP for scroll-driven interactions.

## Requirements

- Node.js 18 or newer
- npm

## Getting started

Install dependencies:

```bash
npm install
```

Start the local development server:

```bash
npm run dev
```

Astro will print the local URL in the terminal, usually `http://localhost:4321`.

## Available commands

- `npm run dev` — start the development server with Astro telemetry disabled
- `npm run build` — create the production build in `dist/`
- `npm run preview` — preview the production build locally

## Project structure

```text
src/
  pages/index.astro    Main landing page and page content
  styles/global.css    Global styles, responsive layout, and animations
public/assets/          Product screenshots, illustrations, logo, and video
astro.config.mjs        Astro configuration
```

The interactive page behavior is defined in the inline script in `src/pages/index.astro`. It uses GSAP, `ScrollTrigger`, and `Draggable` for the hero motion, card gathering sequence, and workflow reveals.

## Production build

Run the build before deployment:

```bash
npm run build
```

The generated static site is written to `dist/`.
