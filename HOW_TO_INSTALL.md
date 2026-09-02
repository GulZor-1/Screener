# Indian Equity Screener — Install as Android App

## What's in this folder
```
index.html       ← the full screener app
manifest.json    ← makes it installable as an app
sw.js            ← service worker (offline support)
icons/           ← app icons (home screen + splash)
  icon-192.png
  icon-512.png
```

---

## Step 1 — Host it free on GitHub Pages (5 min)

1. Go to **github.com** → Sign in (or create a free account)
2. Click **New repository** → name it `screener` → set to **Public** → click **Create**
3. Click **uploading an existing file**
4. Drag and drop **all 4 files + the icons folder** into the upload area
5. Click **Commit changes**
6. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
7. Click **Save**
8. After ~1 min your app is live at:
   `https://YOUR-USERNAME.github.io/screener/`

---

## Step 2 — Install as app on Android (30 seconds)

1. Open **Chrome** on your Android phone
2. Go to `https://YOUR-USERNAME.github.io/screener/`
3. Tap the **three-dot menu** (⋮) in the top right
4. Tap **"Add to Home screen"**
5. Tap **"Add"**

✅ Done! The screener now appears on your home screen like a real app —
full screen, no browser bar, with its own icon.

---

## Alternative: Netlify (even easier, drag & drop)

1. Go to **netlify.com** → Sign up free
2. Drag your entire `screener-pwa` folder onto the Netlify dashboard
3. It deploys instantly — you get a URL like `https://random-name.netlify.app`
4. Follow Step 2 above to install on Android

---

## Features in the app
- 4 screens: Analyse / Results / History / Settings
- 6 frameworks: Buffett · Lynch · Graham · Greenblatt · Piotroski · Avishek
- Preset screens: All / Compounder / Quality value / Deep value / Turnaround
- 3 analysis depths: Quick / Deep dive / Compare two stocks
- Live data via web search (Screener.in + Tickertape)
- Last 20 analyses saved locally on your device
- Works offline (UI loads without internet; analysis needs connection)
- Installable on Android and iOS

---

**Not investment advice. For educational use only.**
