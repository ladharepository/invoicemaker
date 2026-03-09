# JKM Invoice Maker

Mobile-first invoice generator for **Jugal Kishore Maheshwari**, Badabazar, Jaleswar.

## 🚀 Deploy to GitHub Pages

1. Upload all files to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your app will be live at: `https://yourusername.github.io/your-repo-name/invoice-generator.html`

## 📱 Install as App (after deploying)

**Android (Chrome):**
- Open the URL in Chrome
- Tap the **"Install"** banner that appears, or
- Tap menu (⋮) → "Add to Home Screen"

**iOS (Safari):**
- Open the URL in Safari
- Tap the **Share** button (box with arrow)
- Tap **"Add to Home Screen"**

## 📁 Files

| File | Purpose |
|---|---|
| `invoice-generator.html` | Main app |
| `manifest.json` | PWA metadata (name, icon, display) |
| `sw.js` | Service worker (offline support) |
| `icon-192.svg` | App icon (small) |
| `icon-512.svg` | App icon (large) |

## ✨ Features

- Create, save, edit, delete invoices
- Invoice history with search
- Read-only view per invoice
- Payment tracking (Amount Paid / Amount Due)
- Export PDF / Print
- Send Invoice Summary via WhatsApp
- Export all data to JSON backup
- Import JSON backup
- Works offline after first load
- Installable as home screen app
