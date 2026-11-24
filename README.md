# Stock-Check-SM

Storeroom stock app for **Yonny 鱼你 AEON Seri Manjung (SM)** — Dynanex Sdn Bhd.

**App link:** https://dynanex11-hub.github.io/Stock-Check-SM/

Staff use it on their phones (QR code on the storeroom door) to record:
- 📦 Take out to kitchen (tap items, or paste a written list)
- 📥 Add into store / receive deliveries (with DO photo)
- 🗑️ Write-off
- 🔢 Stocktake

Languages: English · 中文 · မြန်မာ

## How it works
- This repo only hosts the phone page (`index.html`).
- All data is saved in the company Google Sheet (Apps Script, dynanex11@gmail.com). No stock data is stored here.

## Updating
- **Page (what staff see):** upload the new `index.html` → Commit. Live in 1–2 minutes.
- **Back-end logic:** update in Google Apps Script → Deploy → Manage deployments → Edit → New version (keeps the same link).
- Do **not** rename this repo or the account — the link and the printed QR code would stop working.
