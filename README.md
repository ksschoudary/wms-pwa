# WMS India — Warehouse Management System PWA

A mobile-first Progressive Web App for tracking warehouses across India.

## Features
- 🗺 **India Map** — Live warehouse pins on an accurate India map
- ⚠️ **Issues Tracker** — Log, assign and resolve warehouse issues
- 🏪 **Masters** — Full warehouse configuration (agreements, charges, area)
- ₹ **Monthly Spend** — Track all warehouse costs with trend charts
- 📋 **Agreements** — Monitor expiry, lock-in periods and rentals
- ⬇️ **CSV Export** — Export all data to CSV files

## Deploy to GitHub Pages

### Automatic (GitHub Actions)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **GitHub Actions**
4. Push a commit to `main` — the workflow auto-deploys

### Manual
1. Go to **Settings → Pages**
2. Under **Source**, select **Deploy from a branch**
3. Select `main` branch, `/ (root)` folder
4. Click **Save** — your app will be live at `https://yourusername.github.io/your-repo-name/`

## Files
| File | Purpose |
|------|---------|
| `index.html` | Main PWA application (single file, all-in-one) |
| `manifest.json` | PWA manifest for "Add to Home Screen" |
| `.github/workflows/deploy.yml` | GitHub Actions auto-deploy workflow |

## Install as App (PWA)
- **Android**: Open in Chrome → tap ⋮ menu → "Add to Home screen"
- **iOS**: Open in Safari → tap Share → "Add to Home Screen"
- **Desktop**: Click install icon in browser address bar
