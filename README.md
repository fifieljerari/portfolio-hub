# Portfolio Hub — Fifi El Jerari, Beauty Marketing

A single landing page linking four working marketing tools: Market Entry
Dossier (research) → Retail Moment Finder (timing) → Launch Planner
(execution) → Shelf Ready (content). No backend and no AI calls of its own
at runtime — it's a static page that just introduces and links out to the
four live tools.

**Live:** https://portfolio-hub-blush.vercel.app/

**Model:** None — static HTML/CSS only.

Built with AI-assisted development — I directed the strategy, content,
and architecture; AI executed the code under my review.

---

## Local setup

This is a single static `index.html` file with no build step and no
dependencies.

**Quickest option:** just double-click `index.html` to open it in a
browser.

**To preview it the same way it's served in production:**
```
npx vercel dev
```
Then open the local URL it prints.

## Redeploying

```
npx vercel --prod
```

## What's in this folder
- `index.html` — the entire page (hero, the four project cards, footer)
