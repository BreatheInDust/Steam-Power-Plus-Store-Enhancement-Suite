# 🎮 Steam PowerPlus
**A modular enhancement suite for the Steam Store.**  
*Built by ACE Productions*

---

## 🚀 Overview
**Steam PowerPlus** is a Tampermonkey userscript that modernizes and declutters [store.steampowered.com](https://store.steampowered.com/).  
It’s built for gamers, designers, and power users who want a cleaner, faster, and more intelligent Steam browsing experience.

Every feature is modular, toggleable, and lightweight — designed to improve Steam’s functionality without compromising its design.

---

## ✨ Features
- 🧹 **Curator CleanView** – Hides curator and “Recommended By” clutter.  
- 🔊 **Trailer Volume Normalizer** – Auto-mutes and levels all trailers.  
- 🧭 **Smart Wishlist Sidebar** – Displays live discounts from your wishlist.  
- 🎨 **Capsule Customizer** – Apply filters or swap capsule art (SteamGridDB-ready).  
- 🧩 **Developer Breakdown Overlay** – Shows developer history, stats, and ratings.  
- 🎥 **YouTube Gameplay Button** – Instantly open gameplay footage for any title.  
- 👥 **Friends’ Review Highlighter** – Highlights reviews from your Steam friends.  
- 💲 **Historical Pricing Tooltip** – Shows price history via SteamDB integration.  
- 🚫 **F2P Filter** – Hides Free-to-Play or microtransaction-heavy titles.  
- 🌈 **Theme Engine** – OLED, Pastel, Retro CRT, and custom themes with persistent settings.

---

## ⚙️ Installation
1. Install **[Tampermonkey](https://tampermonkey.net/)** for your browser.  
2. Click **“Create a new script”**.  
3. Paste in the contents of `steam-powerplus.user.js`.  
4. Save and reload the Steam Store.  
5. Use the ⚙️ **PowerPlus Control Panel** to toggle features in real time.

---

## 🧠 Architecture
Steam PowerPlus uses a modular structure with individual feature modules loaded through a lightweight manager.  
`MutationObserver` keeps features live even during Steam’s dynamic AJAX navigation.  
Settings and theme preferences are stored via Tampermonkey’s `GM_getValue` / `GM_setValue` APIs.

---

## 🛠️ Roadmap
- 🎭 SteamGridDB integration for capsule art  
- 🌍 Regional price comparison support  
- 💰 Bundle and coupon auto-detection  
- 🎨 Custom CSS theme editor  

---

## 🤝 Credits
Created by **Colm** at **ACE Productions**  
A project by *Advanced Computing for Entertainment*  

Follow ACE Productions on [X](https://x.com/AdvComEnt)

---

## 📜 License
MIT License — free to modify, fork, and enhance.  
Please credit ACE Productions when redistributing.

---
