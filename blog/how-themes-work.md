---
title: "How Marklog Themes Work"
description: "One CSS file per theme. Swap with a single line in your config. Here's the system."
date: 2024-03-15
author: "Jask"
category: "Design"
featured: false
tags: ["themes", "css", "design"]
---

# How Marklog Themes Work

Marklog themes are just CSS files. No build step, no preprocessor, no JavaScript theme switcher.

## How to use a theme

Add this to your `blog.config.yaml`:

```yaml
theme: ghibli
```

Options: `light`, `dark`, `ghibli`, `pixel`.

That's it. The theme CSS loads from the Marklog server.

## What each theme looks like

- **Light** — Clean white background, black text. Minimal.
- **Dark** — Inverted. Easy on the eyes at night.
- **Ghibli** — Warm tones. Inspired by Studio Ghibli color palettes.
- **Pixel** — Retro 8-bit aesthetic. Monospace fonts.

## Contributing a theme

Themes live in the `public/themes/` directory. Each theme is one CSS file using CSS custom properties.

Fork the repo, add `public/themes/your-theme.css`, submit a PR. If it looks good, it ships.
