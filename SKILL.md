---
name: zoscription
description: "ZoScription HQ — Subscription tracker and optimizer for Zo Space. Analyzes waste, value, and savings across all your subscriptions with 8 views including dashboard, analytics, detox mode, and AI intelligence."
compatibility: "Created for Zo Computer"
metadata:
  author: dagawdnyc.zo.computer
  version: "1.0.0"
---

## Install

Ask Zo:

> Install ZoScription from `Skills/zoscription/`

Or manually:

1. **Create the page route** — Copy the contents of `routes/page-zoscription.tsx` into a new Zo Space page at `/zoscription`
2. **Upload the Pegasus logo** — Upload any small logo as `/images/pegasus.png` in your Space assets (or remove the `<img>` from the header)
3. **Set visibility** — Make the page public or private as you prefer

## Privacy

- **100% client-side** — All data lives in your browser's localStorage
- **Zero server storage** — No API routes, no database, no files
- **No cross-contamination** — Each user's subscriptions are isolated in their own browser
- **No API keys needed** — Works out of the box

## Features

- **Dashboard** — Monthly/yearly spend, health score, waste alerts, renewal watchlist, cancellation recs, savings scenarios
- **Table** — Full subscription list with sorting, search, and inline edit/delete
- **Analytics** — Category pie chart, cost bar chart, value vs cost scatter, renewal timeline
- **Quick Control** — Mobile-friendly swipe-to-keep/cancel interface
- **Detox** — Subscription bloat analysis with cut/keep/review tiers
- **Smart Views** — Filtered views: wasted money, renewing soon, high cost, low value, best value, free alternatives
- **Intelligence** — Top 3 to cancel/keep, hidden costs, optimization plan, value score breakdown
- **Weekly Review** — Checklist to maintain subscription hygiene

## Tabs

| Tab | Purpose |
|-----|---------|
| Dashboard | Overview with stats, renewals, waste groups, recommendations |
| Table | Full CRUD table with sort/search |
| Analytics | Charts and visualizations |
| Quick Control | Mobile-optimized action cards |
| Detox | Bloat analysis and minimum viable set |
| Smart Views | Pre-filtered insight panels |
| Intelligence | AI-style recommendations and optimization plan |
| Weekly | Review checklist with progress tracking |

## Light/Dark Mode

Toggle between dark and light themes. Preference saved in localStorage.
