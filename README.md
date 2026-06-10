# 🔍 Roblox Demonology Interactive Cheat Sheet

An interactive, responsive single-page web utility application engineered to filter down ghost types inside the popular **Roblox horror experience: Demonology**. Heavily inspired by modern interactive Phasmophobia companion apps.

---

## 🛠️ Key Features

* **3-State Interactive Evidence Toggles:** Click any evidence modifier button to cycle cleanly through its states:
  * **Neutral (Grey):** Evidence parameter unknown.
  * **Included (Green):** Confirmed evidence found at the investigation site.
  * **Excluded (Red):** Evidence definitively ruled out.
* **⚡ Smart Impossible Combination Rule-Out:** The layout dynamically calculates potential outcomes in real-time. If choosing an unselected piece of evidence becomes mathematically impossible based on your current filters, the button will **automatically darken, cross out, and lock (disable clicking)** to prevent dead-end combinations.
* **🏆 Confirmed Entity Isolation:** When exactly 3 pieces of evidence are selected and only 1 matching entity remains, the application automatically applies a golden **"IDENTIFIED"** badge highlight and snaps the card directly to the absolute top of the board.
* **📌 Live Sorting Options:** Includes a toggle feature (**enabled by default**) that keeps all currently possible ghosts clustered at the top of your screen, while filtered out ghosts smoothly sink to the bottom. Turn it off to maintain strict alphabetical sorting.
* **Responsive Layout Structure:** Adapts flawlessly to secondary monitors, overlay browser displays, mobile setups, and tablets.

---

## 📊 Covered In-Game Evidence

This utility maps the exact collection of evidence parameters native to Demonology:
1. **EMF Level 5** (EMF Reader final target indicator spike)
2. **Handprints** (UV Blacklight structural interaction checks)
3. **Spirit Box** (Dark room radio response capture triggers)
4. **Ghost Orb** (Video monitor or head-mounted optics camera sweep)
5. **Freezing Temps** (Sub-zero context breaths or thermometer logs)
6. **Ghost Writing** (Entity interactions inside the Spirit Book log)
7. **Laser Projector** (Visible movement captures across target light grids)
8. **Wither** (Environmental decaying cues, specifically wilting flower assets)

---

## 📋 Ghost Registry Matrix Included

The data array currently supports fast cross-filtering matching configurations for the full directory:
* *Aswang, Banshee, Demon, Dullahan, Dybbuk, Entity, Ghoul, Keres, Leviathan, Nightmare, Oni, Phantom, Revenant, Shadow, Siren, Skinwalker, Specter, Spirit, The Wisp, Umbra, Vex, Wendigo, and Wraith.*

---

## 🤖 AI-Generated Project Details

This entire project—including the core web application logic (`index.html`), responsive CSS UI frameworks, advanced sorting matrices, and this accompanying documentation—was **generated completely by Artificial Intelligence (Gemini)**.

### Architectural Highlights:
* **Zero Dependencies:** The implementation relies exclusively on clean, raw, semantic HTML5, localized CSS3 variables, and vanilla JavaScript. No external libraries, node packages, or trackers are used.
* **Deterministic Logic:** The sorting and impossibility engines execute instantly on client-side triggers via lightweight computational loops, ensuring structural consistency with zero interface lag.
* **Optimized for In-Game Use:** Designed specifically for seamless integration as a second-monitor browser overlay, balancing low-contrast dark themes to preserve your night vision during gaming sessions.
