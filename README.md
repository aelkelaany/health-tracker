# صحتي+ — My Health Tracker PWA

## Setup on GitHub Pages (Free)

1. Go to **github.com** → New Repository → name it `sihati-plus`
2. Set it to **Public** → Create
3. Click **"uploading an existing file"** → upload ALL these files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
4. Commit changes
5. Go to **Settings → Pages** → select `main` branch → Save
6. Wait 1-2 minutes, your app: `https://YOUR_USERNAME.github.io/sihati-plus/`

## Install on Phone

**Android (Chrome):** Open the URL → you'll see "Install" banner → tap it.  
Or: Menu (⋮) → "Install app" or "Add to Home Screen"

**iPhone (Safari):** Open URL → Share button (⬆️) → "Add to Home Screen"

## Import Meal Plan

1. Upload your Dr. Nutrition .docx to Claude
2. Claude gives you a `.json` file
3. In the app: tap **+ أسبوع جديد** → select the JSON → Create

## Files
- `index.html` — Complete app
- `manifest.json` — PWA config
- `sw.js` — Offline support
- `icon-192.png` / `icon-512.png` — App icons
- `perfect-diet-week1.json` — Your first meal plan (import this!)
