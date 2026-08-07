# Marklog Blog

Demo blog for [Marklog](https://github.com/respectevery01/marklog) — a GitHub-powered blog platform.

This repo is a working example of how Marklog reads Markdown files from any GitHub repo and renders them as a blog.

**Live demo:** [marklog.xyz/respectevery01/marklog-blog](https://marklog.xyz/respectevery01/marklog-blog)

## How it works

1. Markdown files live in the `blog/` folder
2. Each file has frontmatter (title, date, description, category, cover image)
3. Marklog fetches and renders them automatically

## Post format

```markdown
---
title: My Post
date: 2024-03-01
description: A short summary
category: Technology
tags: ["web", "markdown"]
image:
  url: https://example.com/cover.jpg
  alt: Description of the image
---

Write your content here.
```

## Make your own blog

1. Fork or clone this repo
2. Replace the files in `blog/` with your own posts
3. Visit `marklog.xyz/your-username/your-repo`

That's it. No database, no CMS, no signup.

## License

MIT
