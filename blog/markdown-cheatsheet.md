---
title: "Markdown Cheatsheet for Blogging"
description: "Everything you need to write blog posts in Markdown. Headings, links, images, code blocks, lists."
date: 2024-03-05
author: "Jask"
category: "Guide"
featured: false
tags: ["markdown", "writing", "guide"]
---

# Markdown Cheatsheet for Blogging

Markdown is all you need to write for Marklog. Here's the syntax that matters.

## Headings

```markdown
# Heading 1
## Heading 2
### Heading 3
```

## Text formatting

```markdown
**bold text**
*italic text*
~~strikethrough~~
> blockquote
```

## Links and images

```markdown
[link text](https://example.com)
![alt text](https://example.com/image.png)
```

## Code blocks

Inline code: `const x = 1`

Code block:

```javascript
function hello() {
  console.log("Hello from Marklog");
}
```

## Lists

```markdown
- unordered item
- another item

1. ordered item
2. another item
```

## Frontmatter

The stuff between `---` at the top of your file is metadata:

```yaml
---
title: My Post
date: 2024-03-01
description: A short summary
category: Technology
tags: ["web", "markdown"]
---
```

That's it. Write Markdown, push to GitHub, your blog updates automatically.
