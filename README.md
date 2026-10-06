# ⏱ DayTrack — Daily Activity Tracker

> Personal activity tracker for **Oct 7 – Nov 8, 2026** · Built as a PWA (Progressive Web App)

🌐 **Live:** [https://YOUR-USERNAME.github.io/daytrack](https://YOUR-USERNAME.github.io/daytrack)

---

## ✨ Features

- **📝 Log** — Tap to log any 30-min slot (6 AM – 10 PM), auto-detects current slot
- **📅 Timeline** — Day-by-day color-coded view of all 32 slots
- **📈 Analytics** — Donut chart, daily bar chart, 33-day trends, activity heatmap
- **🔄 Sync** — JSON export/import for phone ↔ laptop sync
- **📊 Excel export** — Color-coded `.xlsx` with 3 sheets
- **🔔 Reminders** — 30-min browser notifications
- **📵 Offline** — Works without internet after first load (Service Worker)
- **📲 Installable** — Add to Home Screen on Android/iOS

## 🗂 Category System

| Category | Sub-Activities |
|----------|---------------|
| 🌅 Morning Routine | Freshen-Up · Getting Ready · Breakfast |
| 🚌 Commute | Travel · Waiting for Transport |
| 💼 Work | Project · Meeting · Planning · Email/Admin |
| 📚 Learning | Self-Study · Lecture · Online Course · Research |
| 📖 Reading | Book · News · Articles |
| 🎨 Hobby | Yarn · Crafts · Other Hobby |
| 🏋️ Fitness | Gym · Walk/Run · Yoga · Sports |
| 📺 Entertainment | TV/Streaming · YouTube · Social Media · Music |
| ☕ Break/Other | Rest · Nap · Miscellaneous · Household |

## 🚀 Deployment (GitHub Pages)

1. Push this repo to GitHub
2. Go to **Settings → Pages → Source: Deploy from branch → main → / (root)**
3. Your site is live at `https://USERNAME.github.io/REPO-NAME`

## 🔄 Cross-Device Sync

Data is stored in `localStorage` on each device. To sync:
1. **Sync tab → Download JSON** on device A
2. Share file via WhatsApp/Email
3. **Sync tab → Import Data** on device B

## 📦 Tech Stack

- Vanilla HTML/CSS/JS (zero build step)
- [Chart.js](https://chartjs.org) — charts
- [SheetJS](https://sheetjs.com) — Excel export
- Service Worker — offline support
- localStorage — data persistence

---

*Built with ❤️ · Tracking period: Oct 7 → Nov 8, 2026*
