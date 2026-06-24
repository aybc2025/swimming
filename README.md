# 🏊 Swimming Progress Tracker PWA

A Progressive Web App that tracks swimming Level 1 skill progress between March and June 2026.

## Features

- 📊 Side-by-side comparison: March vs June 2026
- ⭐ Highlights newly mastered skills
- 📖 Expandable descriptions for every skill
- 🔄 Filter tabs: All / Ready / In Progress
- 📱 Installable as a home screen app
- 📶 Works fully offline
- 🔔 Auto-update banner when new version is deployed

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **GitHub Actions**
4. The workflow in `.github/workflows/deploy.yml` will deploy automatically on every push to `main`

## File Structure

```
swimming-pwa/
├── index.html          # Main app (all-in-one)
├── manifest.json       # PWA manifest
├── sw.js               # Service worker (offline + auto-update)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── .github/
    └── workflows/
        └── deploy.yml
```
