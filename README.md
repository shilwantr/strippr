# Strippr SEO & Crawler Configuration

This repository contains the crawler indexing (`robots.txt`) and SEO sitemaps for **[strippr.online](https://strippr.online)**.

## Files Overview

| File | Description |
|---|---|
| `robots.txt` | Standard robots directives explicitly allowing all major search engine web crawlers and AI search agents (Googlebot, Bingbot, GPTBot, ClaudeBot, Applebot, Perplexity, etc.) while protecting sensitive paths (`/admin`, `/api/`, `/private/`). |
| `sitemap.xml` | Single consolidated XML sitemap containing all ~29 core pages, model profiles, and category hubs. |
| `sitemap_index.xml` | Standard sitemap index referencing partitioned sub-sitemaps for scalable indexing. |
| `sitemap-main.xml` | Core platform pages (Home, Explore, Live, Chat, Voice, Gallery, Legal, Compliance). |
| `sitemap-models.xml` | Individual interactive model profile pages. |
| `sitemap-categories.xml` | Niche category landing pages (AI Companions, Live Cam, Roleplay, etc.). |

## Sitemaps Structure

Canonical sitemaps referenced in `robots.txt`:
- `https://strippr.online/sitemap_index.xml`
- `https://strippr.online/sitemap.xml`

### Indexed URL Categories:
- **Core Platform**: `/`, `/explore`, `/models`, `/live`, `/chat`, `/voice`, `/gallery`, `/categories`, `/pricing`, `/creators`, `/about`, `/faq`, `/age-verification`, `/terms`, `/privacy`
- **Model Profiles**: `/models/aria`, `/models/chloe`, `/models/scarlett`, `/models/elena`, `/models/valeria`, `/models/maya`, `/models/lucy`, `/models/zara`
- **Categories**: `/category/ai-companions`, `/category/live-cam`, `/category/interactive-chat`, `/category/roleplay`, `/category/anime-cosplay`, `/category/virtual-reality`
