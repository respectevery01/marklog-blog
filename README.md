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

## Blog config (`blog.config.yaml`)

Add this file to the root of your repo to customize your blog. All fields are optional — without a config, Marklog uses sensible defaults.

```yaml
# Blog title and description (shows in header and browser tab)
title: "My Blog"
description: "Thoughts on code and life"

# Theme: light | dark | ghibli | pixel
theme: "light"

# Language: en | zh-cn
language: "en"

# Author info (shows in sidebar)
author:
  name: Your Name
  bio: Developer. Writes about code.
  avatar: https://example.com/avatar.jpg

# Social links (shows in sidebar)
social:
  github: https://github.com/username
  twitter: https://twitter.com/username

# Navigation links
nav:
  - label: Home
    url: /
  - label: About
    url: /about
```

| Field | Description | Default |
|-------|-------------|---------|
| `title` | Blog name, shows in header and browser tab | Your repo name |
| `description` | Short tagline below the title | Your repo description |
| `theme` | Visual theme: `light`, `dark`, `ghibli`, `pixel` | `light` |
| `language` | Interface language: `en`, `zh-cn` | `en` |
| `author.name` | Your display name | Your GitHub username |
| `author.bio` | Short bio text | `"Creator of {repo}"` |
| `author.avatar` | Avatar image URL | Your GitHub avatar |
| `social` | Object with `github`, `twitter`, `linkedin`, `website` | None |
| `nav` | Array of `{ label, url }` objects | Home + GitHub links |

## Make your own blog

1. Fork or clone this repo
2. Replace the files in `blog/` with your own posts
3. Edit `blog.config.yaml` with your info
4. Visit `marklog.xyz/your-username/your-repo`

That's it. No database, no CMS, no signup.

## License

MIT
