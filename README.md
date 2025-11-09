# 🎮 Steam PowerPlus
**A modular enhancement suite for the Steam Store**  
*Developed by ACE Productions*  

---

## 🚀 Overview
**Steam PowerPlus** is a comprehensive Tampermonkey userscript designed to modernize, declutter, and enhance the user experience on [store.steampowered.com](https://store.steampowered.com/).  

The Steam Store is full of useful features, but its interface can often be cluttered, repetitive, or inefficient for power-users. Steam PowerPlus addresses these issues by providing a suite of tools that improve usability, display real-time information, normalize media, and allow full visual customization — all from a lightweight, modular script that integrates seamlessly into your browser.

With Steam PowerPlus, you gain:  

- Cleaner browsing with unnecessary clutter hidden.  
- Real-time wishlist monitoring and discount notifications.  
- Instant access to gameplay videos and developer information.  
- Theme customization for a more visually comfortable interface.  
- Enhanced control over trailers, reviews, and store elements.  

This userscript is designed to be compatible with major browsers (Chrome, Edge, Firefox, and Safari via Tampermonkey) and works dynamically with Steam’s partial-page navigation system.

---

## ✨ Features

Steam PowerPlus is modular, meaning each feature can be enabled or disabled independently through the integrated **PowerPlus Control Panel**. Key features include:

1. **🧹 Curator CleanView**  
   Automatically collapses curator recommendations, “Recommended By” sections, and other repetitive UI elements, creating a streamlined browsing experience.

2. **🔊 Trailer Volume Normalizer**  
   All Steam trailers are automatically muted or normalized to a consistent volume level, preventing sudden loud audio or uneven playback experiences.

3. **🧭 Smart Wishlist Sidebar**  
   Injects a sidebar into the Steam Store displaying your wishlist games along with current discounts and sale prices, allowing you to track deals in real-time without leaving the page.

4. **🎨 Capsule Customizer**  
   Enables visual filters for game capsules such as brightness, contrast, hue-shifts, and grayscale. Supports custom capsule art overrides (SteamGridDB integration planned).

5. **🧩 Developer Breakdown Overlay**  
   Provides quick access to developer and publisher information, including other recent releases, average review scores, and meta-data from SteamDB.

6. **🎥 YouTube Gameplay Button**  
   Adds a one-click button next to game trailers that searches YouTube for high-quality gameplay footage (e.g., “4K, no commentary”), giving instant previews of gameplay before purchasing.

7. **👥 Friends’ Review Highlighter**  
   Highlights reviews authored by your Steam friends and prioritizes them in the review list, so you can quickly gauge trusted opinions.

8. **💲 Historical Pricing Tooltip**  
   Adds a tooltip to all game prices showing historical lowest prices from SteamDB over the past 12 months, helping you make smarter purchasing decisions.

9. **🚫 Free-to-Play / Monetization Filter**  
   Automatically hides games tagged as Free-to-Play or heavily monetized, such as gacha or microtransaction-heavy titles, giving you a cleaner and more curated experience.

10. **🌈 Theme Engine**  
    Provides multiple color themes, including OLED Black, Pastel, Retro CRT, and customizable user-defined themes. All theme preferences persist between sessions.

---

## 📥 Installation Instructions

Follow these steps to install Steam PowerPlus on your browser:

### 🪄 Step 1 — Download
Download the latest **`steampowerplus.zip`** from the **[Releases](../../releases)** section of this GitHub repository.

### 🧩 Step 2 — Install Tampermonkey
Install **[Tampermonkey](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)** on your browser. Tampermonkey is available for Chrome, Edge, Firefox, and Safari.

### ⚙️ Step 3 — Enable Developer Mode
1. Open `chrome://extensions/` in your browser.  
2. Toggle **Developer Mode** in the top-right corner.

### 🌐 Step 4 — Import Steam PowerPlus
1. Go to [store.steampowered.com](https://store.steampowered.com/).  
2. Click the **🧩 puzzle piece** icon in the Chrome toolbar to access extensions.  
3. Open **Tampermonkey → Dashboard → Utilities**.  
4. Under **“Import from file”**, click **Choose file** and select `steampowerplus.zip`.  
5. When prompted with *Steam PowerPlus — Store Enhancement Suite*, click **Import**.  

✅ Steam PowerPlus is now active. The **PowerPlus Control Panel** will appear in the Steam Store UI for feature toggling.

---

## 🐞 Bug Reporting
If you encounter any bugs, unexpected behavior, or compatibility issues:  
📧 Contact: **ok.hey.services@gmail.com**  

Please include the browser version, OS, and a description of the issue.

---

## 💻 Roadmap

Future features and improvements planned for Steam PowerPlus:

- **🎭 SteamGridDB Integration:** Automatic syncing of custom capsule artwork.  
- **🌍 Regional Price Comparison:** Display prices across multiple regions for better deals.  
- **💰 Bundle & Coupon Detection:** Automatically notify of relevant bundles or store coupons.  
- **🎨 Custom CSS Editor:** Allow users to fully customize Steam’s appearance with advanced styling options.  
- **🖥️ Standalone App Development:** PC & Mac applications planned for deeper system integration.  

---

## ⚙️ Architecture

Steam PowerPlus is built using a modular system with independent feature modules.  

- **Modular Loader:** Each feature runs as its own module for easy management and toggleability.  
- **Dynamic Updates:** Uses `MutationObserver` to monitor page changes and keep modules active on dynamic AJAX page loads.  
- **Persistent Settings:** Stores user preferences and themes using Tampermonkey’s `GM_getValue` and `GM_setValue` APIs.  
- **Lightweight & Fast:** Minimal DOM manipulation ensures the script does not affect Steam performance or page load times.

---

## 🤝 Credits
- **Concept & Development:** Colm  
- **Maintained by:** ACE Productions (*Advanced Computing for Entertainment*)  

Follow ACE Productions on [X](https://x.com/AdvComEnt) for updates, news, and projects.

---

## 📜 License
**Creative Commons Zero v1.0 Universal (CC0 1.0)**  
This work is dedicated to the public domain. You can copy, modify, distribute, and perform the work, even for commercial purposes, without asking permission.  

No attribution required, though crediting **ACE Productions** is appreciated when sharing or redistributing.
