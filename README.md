# Weekly Standup Log

A shared tool for Williams and Tobe to log daily work through the week and pull a formatted report for standup.

## What's in here
- `index.html` — the whole app, one file, no build step.

## How it saves data
Entries are stored in Supabase (project: `majirih's Project`), shared between both users. No login needed to use the app.

## Deploy (no IDE needed)

1. **Upload to GitHub**
   - Go to github.com → **+** → **New repository**
   - Name it (e.g. `standup-log`) → **Create repository**
   - **Add file** → **Upload files** → upload `index.html` → **Commit changes**

2. **Deploy on Vercel**
   - Go to vercel.com → sign in with GitHub → **Add New** → **Project**
   - Select the repo → leave settings as default → **Deploy**
   - You'll get a live link like `standup-log.vercel.app`

Send that link to Tobe. Both of you use the same link going forward.

## Using it
- **Add entries** tab: pick your name, pick the day, choose a category, type what you did, tap add.
- **Standup report** tab: switch between Both / Williams / Tobe, then tap **Copy report text** to paste into standup.

## Updating the app later
Edit `index.html` in the GitHub repo (or re-upload a new version), Vercel redeploys automatically on every commit.
