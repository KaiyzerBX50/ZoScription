# ZoScription HQ — Subscription Tracker for Zo Space

A full-featured subscription management dashboard that runs on your Zo Computer. Track, analyze, and optimize every subscription with waste scoring, value analysis, detox mode, and savings scenarios.

![Screenshot](assets/screenshot.png)

## Quick Install

Ask Zo:

```
Install ZoScription — create a page route at /zoscription and an API route at /api/zoscription using the code from Skills/zoscription/routes/. Make it public.
```

## Manual Install

1. In your Zo Space, create an **API route** at `/api/zoscription`
2. Paste the contents of `routes/api-zoscription.ts` as the code
3. Create a **page route** at `/zoscription`
4. Paste the contents of `routes/page-zoscription.tsx` as the code
5. Visit `https://yourhandle.zo.space/zoscription`

## Features

- **8 tabs**: Dashboard, Table, Analytics, Quick Control, Detox, Smart Views, Intelligence, Weekly
- **Waste scoring**: Identifies subscriptions draining your wallet
- **Value analysis**: Rates each subscription's worth (Excellent → Weak)
- **Savings scenarios**: See impact of 10%, 25%, 50% cuts
- **Detox mode**: Find your minimum viable subscription set
- **Dark/Light mode**: Toggle themes with localStorage persistence
- **Mobile-friendly**: Quick Control tab designed for phone use
- **Data persists**: Server-side storage survives browser cache clearing

## Privacy & Data Isolation

- ✅ **Per-user data isolation** — Each browser instance gets a unique ID; data is completely separated
- ✅ **Server-side persistence** — Datastored in `/home/workspace/.zoscription/` with isolated JSON files per user
- ✅ **No cross-contamination** — User A cannot access User B's subscriptions
- ✅ **No API keys required** — Works immediately after install
- ✅ **No personal data in this repo** — Clean install = empty board

## Data Architecture

```
Browser (unique ID in localStorage) 
    ↓
API Route /api/zoscription?userId=<unique-id>
    ↓
Server file: /home/workspace/.zoscription/<unique-id>.json
```

Each user's subscriptions are stored in a separate JSON file identified by a browser-generated unique ID. This ensures:
- Data survives browser clears (server-side storage)
- Complete isolation between users
- No shared global state

## Built by

**DaGreatGAWDNYC** · Built with **Zo Computer** · ⢕⣿⢀⣏⣿⢳⡕⣆⢺⣋⢟
