# Vibe Shop

> **Sales & management software for small shops — light, smooth, free, no strings attached.**

📥 **Download**: <https://github.com/learningmapn/free-apps/tree/main/downloads/vibe-shop>

<div align="center">

[![Tiếng Việt](https://img.shields.io/badge/🇻🇳_Tiếng_Việt-9e9e9e?style=for-the-badge)](README.md)
[![English](https://img.shields.io/badge/🇬🇧_English-012169?style=for-the-badge)](README.en.md)

</div>

---

## 📸 Screenshots

| | |
|:---:|:---:|
| ![Dashboard](screenshots/01-dashboard.webp) | ![POS](screenshots/02-pos.webp) |
| **Dashboard** — Revenue overview | **POS** — Point of sale |
| ![KDS](screenshots/03-kds.webp) | ![Products](screenshots/04-products.webp) |
| **KDS** — Kitchen/Bar Kanban | **Products** — Menu management |
| ![Inventory](screenshots/05-inventory.webp) | ![Orders](screenshots/06-orders.webp) |
| **Inventory** — Recipe-based deduct | **Orders** — History & details |
| ![Customers](screenshots/07-customers.webp) | ![Reports](screenshots/08-reports.webp) |
| **Customers** — Gold/Silver/Bronze loyalty | **Reports** — 30-day revenue |
| ![Simulator](screenshots/09-simulator.webp) | ![Tycoon](screenshots/10-tycoon.webp) |
| **Simulator** — 30-day what-if | **Tycoon** — Manage your shop as a game |
| ![Settings](screenshots/11-settings.webp) | ![Onboarding](screenshots/12-onboarding.webp) |
| **Settings** — 14 toggleable features | **Onboarding** — 3-step setup |
| ![Customer QR](screenshots/13-customer-qr-mobile.webp) | |
| **Customer QR** — Self-order on phone | |

---

## 💡 The Story Behind

Every small shop in Vietnam — from the corner café to the alley grocery — needs something quite simple: a tool to sell, manage stock, track regulars, print receipts, and know whether today made or lost money. That's it.

But finding software for this isn't simple:

- "Free" software usually caps at 100 orders/month and pushes you to upgrade.
- Paid software runs 200–800K VND ($8–32) a month — enough for several bowls of pho a day.
- "Cloud" software depends on the internet — lose your connection, lose your sales.
- "Full-featured" software weighs 200MB and lags on older machines.
- Learning takes a week, and onboarding a new employee is painful.

**Vibe Shop was built to be different.**

A lightweight package — just **4.2 MB** total — that runs smoothly even on a 5-year-old machine. Your data lives **on your own machine**, no internet required, no dependence on anyone's server. Open it and start using it. No accounts, no subscription, no "7-day free trial".

Free. Forever.

---

## 🎯 What Vibe Shop Does

### 🛒 Point of Sale (POS)
Sell in seconds: search items, pick size + toppings (for F&B), apply vouchers, print k80 receipts, accept Cash / QR / Card. Fast barcode/SKU scanning, ⌘K command palette to find anything.

### 📱 Self-ordering via Table QR
Customers scan a QR with their phone → mobile-first menu opens → pick items → submit. Orders flow straight to the KDS marked **🔔 QR**. No separate customer app, no signup — the link is part of the app you already installed.

### 👨‍🍳 Kitchen/Bar Display (KDS) Kanban
Orders from POS and QR land in 3 columns: **Pending → In Progress → Ready**. Amber alert when an order exceeds 10 minutes, red after 20. No more paper tickets or shouting.

### 📦 Smart Inventory
Recipe-based: declare "1 cup of milk coffee = 15g coffee + 50ml milk + 1 spoon sugar" — every sale auto-deducts ingredients. Low-stock alerts, full transaction history (in/out/sale/adjust).

### 👥 Customers & Loyalty
Gold / Silver / Bronze tiers based on total spend. Detailed profiles, order history, last visit. Auto Happy Hour 2–4 PM and perks for regulars.

### 🍱 Multi-industry
4 ready presets for **Café · Restaurant · Fashion · Grocery**. 14 features that can be toggled independently (POS, KDS, QR, Tables, Variants, Combo, Voucher, Loyalty…). 3-step setup in 2 minutes.

### 📊 Real-data Reporting
30-day revenue, top products, payment-method breakdown, clean charts, CSV export (opens in Excel).

### 💰 Shift Management
Open a shift with starting cash → sell all day → close shift, count actual cash, system compares vs. expected → shows variance. Simple yet effective for shrinkage prevention.

### 💾 Backup & Restore
One-click export of all data to a JSON file. Move to a new machine → import → reload → everything is back. No more "machine died, all gone" nightmares.

---

## 🎮 Two Unique Features (Not in Any Other App)

### 🧪 Simulation Mode — "Test Before You Decide"

Wondering things like:
- *"What happens to profit if I raise prices 10%?"*
- *"Is adding more tables worth it?"*
- *"Will hiring one more barista pay off?"*
- *"District 1 rent is 4× District 7 — does the extra foot traffic justify it?"*

Run a 30-day simulation using Poisson + M/M/c queue + reputation mean-reversion + 5-tier location modeling — get an answer immediately with detailed P&L, hourly utilization, and lost revenue from long queues. **No need to test in real life to know the outcome.**

### 🎯 Tycoon Mode — "Manage Your Shop Like a Game"

A 2D cartoon shop floor: customers walk in, queue up, order, sit, leave — all real-time with 3 customer archetypes (passerby / regular / WFC) each behaving differently. You control: hire/fire baristas, add/remove tables, change prices, change layout, run marketing — and watch the impact on revenue and reputation instantly.

Speed 0.25× → 240×, one simulated day in 3.5 real seconds. Entertaining, and a real lesson in balancing cost and operations.

> *This is a serious mathematical model (Poisson process, compound distributions, AR(1) weather, customer heterogeneity) — not a toy. Same engine as Simulation Mode, just with a more intuitive UI.*

---

## 📥 Download & Install

### 👉 Download on GitHub

**<https://github.com/learningmapn/free-apps/tree/main/downloads/vibe-shop>**

| OS | File | How to install |
|---|---|---|
| 🍎 **macOS** Apple Silicon (M1/M2/M3) | `Vibe-Shop-1.2.0-aarch64.dmg` (~4.2 MB) | Double-click DMG → drag into Applications |
| 🍎 **macOS** Intel | (Coming via GitHub Actions) | Same as above |
| 🪟 **Windows 10/11** x64 | (Coming via GitHub Actions) | Install WebView2 Runtime → run `.msi` |
| 🐧 **Linux** | (Coming via GitHub Actions) | `.AppImage` runs directly |

> **First open on macOS**: Gatekeeper will block because the app isn't signed with an Apple Developer ID (it's not malware — signing just costs $99/year, which is steep for a free app). Go to **System Settings → Privacy & Security** → click **Open Anyway**. After that it opens normally.

> **First open on Windows**: SmartScreen will warn. Click **More info** → **Run anyway**.

### Minimum Requirements
- macOS 12+ / Windows 10+ / Ubuntu 20+
- 4 GB RAM, 50 MB disk
- WebView2 (Win 10) or WebKit (Linux) — Win 11 and macOS already include it

---

## 🚀 Get Started in 60 Seconds

1. **Open the app for the first time** → 3-step onboarding:
   - Enter shop name (changeable later)
   - Pick industry: Café / Restaurant / Fashion / Grocery
   - Toggle on the features you need
2. **Go to Dashboard** — see today's revenue overview
3. **Click "New Order"** → POS opens → pick items → check out
4. **Done.** Your first order is in 🎉

Then at your own pace:
- **Products** → add/edit items via emoji + color-picker UI
- **Inventory** → declare ingredients + recipes
- **Settings** → enable QR ordering, print QR for 12 tables, back up to JSON

---

## 👥 Who Vibe Shop Is For

✅ **Café / bubble-tea / juice owners** — full POS + KDS + topping/size customizer
✅ **Small restaurant / eatery owners** — table layout, QR menu, recipe deduct
✅ **Fashion / accessory shops** — variants (size/color) + barcode/SKU
✅ **Grocery stores** — quick scan, no complex combos required
✅ **Aspiring shop owners** — use Simulation Mode to check profitability before opening
✅ **Business / economics students** — Tycoon Mode teaches queueing and fixed/variable cost via gameplay

❌ **Chains with 10+ branches** — Vibe Shop is currently local-first, no cross-shop sync (planned for v2.x)
❌ **Need third-party ERP/POS integration** — Vibe Shop is standalone, no API yet
❌ **Businesses with complex tax-reporting needs** — basic reports are enough for small shops; not a replacement for accounting software

---

## 🔧 Why Choose Vibe Shop

| | Vibe Shop | Traditional cloud software |
|---|---|---|
| **Price** | Free forever | 200–800K VND/month |
| **Internet** | Not required | Required |
| **Speed** | Opens in < 1 second | 3–10 seconds to load |
| **Size** | 4 MB | 50–300 MB |
| **Data ownership** | Yours, on your device | Someone else's server |
| **Updates** | Download when you want | Auto-update, sometimes loses features |
| **Training** | 5-minute onboarding | Staff needs 1–2 days |
| **Business simulator** | ✅ Yes | ❌ No |

---

## 🛣️ In Development

### Coming soon (v1.3)
- Auto Loyalty tier discount
- Report date-range picker
- Manual customer add/edit UI
- Excel bulk import/export

### Future (v2.x)
- Real SQLite (currently localStorage)
- Multi-device sync over LAN
- Multi-account / staff permissions
- Reservation system (table booking)
- USB thermal printer driver (k58/k80)

---

## 💬 FAQ

**Q: Is it really free forever?**
A: Yes. Open-source code, no ads, no fees. The developer built it to help small shops.

**Q: Where is data stored? Is it safe?**
A: In `~/Library/Application Support/com.vibeshop.app/` (Mac) or `%APPDATA%\com.vibeshop.app\` (Windows). Nothing is sent anywhere. **Please back up regularly** via the Backup button in Settings.

**Q: What if I lose my machine?**
A: With a JSON backup → install on a new machine → import → fully restored. Without a backup → everything is lost (same as any local software).

**Q: Is there a mobile app?**
A: Currently desktop only. Customers can order via QR on their phones. A mobile owner app is on the roadmap.

**Q: Does it support thermal printers?**
A: Currently it prints via the OS default browser print (CSS @media print is already k80-ready). Native USB drivers are coming in v2.x.

**Q: I'm not techy — can I still use it?**
A: Yes. 3-step onboarding, UI with familiar Vietnamese flavor (colors, emojis, friendly wording). If you get stuck, [`INSTALL.md`](INSTALL.md) covers every common issue in detail.

**Q: Can I request features?**
A: Open an issue on GitHub. The repo is fully open-source — coders can submit pull requests, and non-coders can suggest features.

---

## 📜 License

Source code: open-source (exact license TBD — likely MIT/Apache).
Pre-built binaries: free for personal & commercial use, no warranty.

---

## 🌟 Support Us

Support us and learn more at: **<https://learningmap.net>**

---

## 🙏 Thank You

Thanks for considering Vibe Shop for your shop. Hopefully this app saves you time, lowers the daily stress of running a store, and gives you a few extra moments to enjoy a coffee in your own café.

**Wishing you good business and many happy customers 🎉**

---

📥 **Download once more**: <https://github.com/learningmapn/free-apps/tree/main/downloads/vibe-shop>
