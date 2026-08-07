---
title: "Self-Hosting Marklog on Vercel"
description: "Deploy your own Marklog instance in 3 minutes. Free tier, no credit card needed."
date: 2024-03-10
author: "Jask"
category: "Tutorial"
featured: false
tags: ["deployment", "vercel", "self-hosting"]
---

# Self-Hosting Marklog on Vercel

Prefer to run your own instance? Here's how.

## Step 1: Clone

```bash
git clone https://github.com/respectevery01/marklog.git
cd marklog
npm install
```

## Step 2: Deploy

Push to your GitHub account, then import the repo on [Vercel](https://vercel.com). Vercel auto-detects Next.js. No configuration needed.

Click Deploy. You're live in about 60 seconds.

## Step 3: Custom domain

In Vercel project settings, add your domain. Update DNS records as prompted. Done.

## Why self-host?

- Custom domain support
- Your own analytics
- No dependency on marklog.xyz uptime
- Full control over themes and customization
- It's MIT licensed, do whatever you want

## Updating

```bash
git pull origin main
npm install
```

Push to main. Vercel redeploys automatically.
