# WOLFMODE

> Discipline is non-negotiable.

A Progressive Web App (PWA) daily task tracker with brutal accountability. Add your tasks once, check them off daily, get shamed hard if you fail.

---

## Features

- Daily task list that resets at your chosen time
- Per-task day scheduling (Mon–Sun)
- History log — view any past day's performance
- Brutal shame screen when you fail tasks
- Praise screen when you go perfect
- Works offline (service worker cached)
- Installable on Android as a home screen app

---

## Deploy to GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it `wolfmode` (or anything you want)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the files

Upload all 5 files to the root of your repo:
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.png`
- `icon-512.png`

You can drag and drop them via the GitHub web interface (click "uploading an existing file" on the repo page).

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Select branch: `main` (or `master`)
4. Folder: `/ (root)`
5. Click **Save**

Your app will be live at:
`https://YOUR-GITHUB-USERNAME.github.io/wolfmode/`

(Takes ~1 minute to go live after saving.)

---

## Install on Android

1. Open Chrome on your Android phone
2. Navigate to your GitHub Pages URL
3. Tap the **three-dot menu** (top right)
4. Tap **"Add to Home screen"**
5. Tap **"Add"**

WOLFMODE will appear on your home screen like a native app — full screen, no browser UI.

---

## Usage

- **Today** — tap tasks to check them off. Checked = done.
- **Tasks** — add, edit, or delete tasks. Set which days each one is active.
- **History** — tap any day to expand and review what you hit or missed.
- **Settings** — set your daily reset time. Tap "End of day review" to trigger the shame/praise screen.

---

## Data

Everything is stored locally in your browser's `localStorage`. No account, no cloud, no tracking.
