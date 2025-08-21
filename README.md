# Exeunt — Minimal Essays Site (Astro)

A minimalist site with an off-white/off-black palette, Big Caslon headings, a sleek modern serif body, and a dark/light toggle.

## Quickstart

```bash
npm i
npm run dev
```

## Content model

Place Markdown files in `src/content/essays/` with this front matter:

```yaml
---
title: "Your Essay Title"
date: "YYYY-MM-DD"
summary: "1–3 sentence summary for the homepage."
banner: "/images/your-image.jpg"  # path under /public
draft: false
---
```

Images go in `public/images/`.

## Fonts

Headings use **Big Caslon** if present on the system. For the web, the layout falls back to **Libre Caslon Display** (loaded from Google Fonts). Body text uses **Source Serif 4**.

To use actual Big Caslon webfonts, add your `@font-face` kit and keep the family name `Big Caslon` in CSS.
