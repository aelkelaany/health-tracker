# صحتي+ — My Health Tracker PWA

## Setup on GitHub Pages (Free Hosting)

1. Go to **github.com** → New Repository → name it `sihati-plus`
2. Set it to **Public** → Create
3. Click "uploading an existing file" → upload these files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.svg`
   - `icon-512.svg`
4. Commit changes
5. Go to **Settings → Pages** → select `main` branch → Save
6. Your app URL: `https://YOUR_USERNAME.github.io/sihati-plus/`

## Install on Phone

**Android**: Open URL in Chrome → tap "Install" banner or Menu (⋮) → "Add to Home Screen"

**iPhone**: Open URL in Safari → Share button (⬆️) → "Add to Home Screen"

## How to Import a Meal Plan

1. Upload your Dr. Nutrition .docx to Claude
2. Claude converts it to a `.json` file
3. In the app: tap **استيراد** (Import) → select the JSON file
4. Your week's meals appear with checkboxes ready!

## Files

- `index.html` — Complete app (single file)
- `manifest.json` — PWA metadata
- `sw.js` — Service worker for offline support
- `icon-192.svg` / `icon-512.svg` — App icons
- `perfect-diet-week1.json` — Your first week's meal plan (import this!)

## Backup

Always tap **Settings → Backup** after logging data to save a JSON backup.
