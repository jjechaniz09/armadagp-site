# armadagp.com — Armada Global Partners Website

## Overview
Minimal landing page for Armada Global Partners, an investment platform focused on the US and Mexico. Hosted on **GitHub Pages** from the `master` branch. This is a temporary site — a full website will be built later.

## Hosting & Deployment
- **Repo**: `jjechaniz09/armadagp-site` on GitHub
- **Hosting**: GitHub Pages (auto-deploys on push to `master`)
- **Domain**: `armadagp.com` (registered on GoDaddy)
- **DNS**: A records → GitHub Pages IPs (`185.199.108-111.153`), www CNAME → `jjechaniz09.github.io`
- **HTTPS**: Enforced via GitHub Pages (cert expires 2026-06-14)

## Analytics
- **Google Analytics 4**: Measurement ID `G-J5KZRP77Z2`
- Stream name: "Armada GP", Stream ID: 13916431230
- gtag.js snippet in `index.html` `<head>`

## SEO Setup
- Meta description, Open Graph, and Twitter Card tags in `index.html`
- JSON-LD structured data (`Organization` schema) with US & Mexico area served
- `robots.txt` — allows all crawlers including LLM bots (GPTBot, ClaudeBot, PerplexityBot, ChatGPT-User, Google-Extended)
- `sitemap.xml` — single-page sitemap submitted to Google Search Console
- `llms.txt` — plain text company description for LLM crawlers
- Screen-reader-only `<p>` for crawler content indexing (visually hidden)
- Google Search Console verified and indexing requested (2026-03-16)

## File Structure
```
index.html    — Single-page site with SEO tags, GA4, and sr-only content
CNAME         — Custom domain config for GitHub Pages
robots.txt    — Crawler permissions + sitemap pointer
sitemap.xml   — XML sitemap for search engines
llms.txt      — LLM-friendly company description
```
