# Warehouse Terminators — Synthwave Website

Liquidation sales site with neon CN Tower backdrop, inventory grid, auctions, and contact info.

## Local Dev
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Deploy on GitHub Pages (automatic)
1. Create a new repo, push this folder to **main**.
2. GitHub → Settings → Pages → Source: **GitHub Actions**.
3. The included workflow `.github/workflows/deploy.yml` builds with Vite and deploys to Pages.

> Vite is configured with `base: './'` so it works under project subpaths.

## Edit contact & links
- Phone: `+1 437 333 3316`
- Address: `126A Oakdale Rd, North York, ON M3N 1V9`
- Hours: `Mon–Sat 12–7 PM`
- Facebook / Kijiji: in `src/App.jsx` Contact section

## Assets
Logo/hero artwork in `src/assets/`:
- `photo_2025-09-21_18-28-32.jpg` (primary)
- `photo_2025-09-21_18-28-33.jpg` (fallback)
