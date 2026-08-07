---
title: "How Marklog Themes Work"
description: "One CSS file per theme. Swap with a single line in your config. Here's the system."
date: 2024-03-15
author: "Jask"
category: "Design"
featured: false
image:
  url: "https://images.unsplash.com/photo-1502691876148-a84978e59af8?w=800&h=400&fit=crop"
  alt: "Colorful paint swatches fanned out"
tags: ["themes", "css", "design"]
---

# How Marklog Themes Work

Marklog themes are just CSS variables. No build step, no preprocessor, no JavaScript theme switcher.

## How to use a theme

Add this to your `blog.config.yaml`:

```yaml
theme: ghibli
```

Options: `light`, `dark`, `ghibli`, `pixel`.

That's it. The theme applies automatically.

## What each theme looks like

- **Light** — Clean white background, black text. Minimal.
- **Dark** — Inverted. Easy on the eyes at night.
- **Ghibli** — Warm tones. Inspired by Studio Ghibli color palettes.
- **Pixel** — Retro 8-bit aesthetic. Monospace fonts.

## Contributing a theme

Themes are defined as CSS custom properties. Fork the repo, add your variables, submit a PR. If it looks good, it ships.
