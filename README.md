# 🔍 Roblox Demonology Interactive Cheat Sheet

An interactive, responsive single-page web utility application engineered to filter down ghost types inside the popular **Roblox horror experience: Demonology**. Heavily inspired by modern interactive companion tools, built directly on precise game-wiki definitions.

---

## 🛠️ Key Features

* **3-State Interactive Evidence Toggles:** Click any evidence modifier button to cycle cleanly through its states:
  * **Neutral (Grey):** Evidence parameter unknown.
  * **Included (Green):** Confirmed evidence found at the investigation site.
  * **Excluded (Red):** Evidence definitively ruled out.
* **🚫 Direct Entity Exclusion:** Click the **"✕"** icon button located on any ghost card to immediately rule out that specific entity manually. This drops the card to the absolute bottom of the container layout and applies a heavy dimming mask, completely isolated from global evidence filters.
* **⚡ Smart Impossible Combination Rule-Out:** The layout dynamically calculates potential outcomes in real-time. If choosing an unselected piece of evidence becomes mathematically impossible based on your current filters, the button will **automatically darken, cross out, and lock (disable clicking)** to prevent dead-end combinations.
* **🐺 Skinwalker Ghost Orb Architecture:** Built with integrated handling for the Skinwalker's unique hidden mechanic. Since the Skinwalker fundamentally fakes the **Ghost Orb** signature in-game, the tracking matrix treats the Ghost Orb as an essential fourth valid parameter constraint for it.
* **⚙️ Comprehensive Settings Dashboard:** Clicking the gear icon button exposes an elegant contextual configuration layout containing:
  * **Float Valid Ghosts to Top:** Clear toggle option that controls whether viable target choices immediately snap to upper layout zones.
  * **Display Mode Filtering Profiles:** Toggle between **Full Details**, **Compact View (No Descriptions)**, or **Essential View (Names Only)** on the fly.
  * **Fixed Column Grids:** Manually lock the main card layout structure to explicit limits from 1 up to 5 columns wide (Defaults cleanly to **2 Columns** layout profile).
  * **2-Column Clues Layout Checkbox:** Re-orient evidence button components from a strict single vertical list into an optimized grid system mapped across 2 compact columns via a simple tick-box trigger.
  * **Shorter Clue Nomenclature Toggle:** Instantly shrinks UI evidence text strings into fast-read tactical jargon (e.g., *EMF Level 5 → EMF, Laser Projector → DOTS, Handprints → UV*).
* **👁️ Concealed Header Visibility Trigger:** A tiny, translucent macro switch (`👁️`) is nested in the absolute top-right viewport corner. Click it to collapse or expand the main introduction layout smoothly, clearing up screen real estate instantly.
* **✨ Animation Pipeline:** Native, GPU-accelerated CSS ease transitions track state alterations across the application, delivering buttery-smooth motion during card dimming, list rearranging, and menu sliding phases.

---

## 📊 Covered In-Game Evidence Nomenclature

| Raw Parameter | Short Jargon Profile |
| :--- | :--- |
| **EMF Level 5** | EMF |
| **Handprints** | UV |
| **Spirit Box** | Spirit |
| **Ghost Orb** | Orbs |
| **Freezing Temps** | Temps |
| **Ghost Writing** | Writing |
| **Laser Projector** | **DOTS** |
| **Wither** | Wither |

---

## 📋 Ghost Registry Matrix Included

The data array supports exact wiki-verified combinations for the full roster:
* *Aswang, Banshee, Demon, Dullahan, Dybbuk, Entity, Ghoul, Keres, Leviathan, Nightmare, Oni, Phantom, Revenant, Shadow, Siren, Skinwalker, Specter, Spirit, The Wisp, Umbra, Vex, Wendigo, and Wraith.*

---

## 🤖 AI-Generated Project Details

This entire project—including the core web application logic (`index.html`), responsive CSS UI frameworks, advanced sorting matrices, and this accompanying documentation—was **generated completely by Artificial Intelligence (Gemini)**.

### Architectural Highlights:
* **Zero Dependencies:** The implementation relies exclusively on clean, raw, semantic HTML5, localized CSS3 variables, and vanilla JavaScript. No external libraries, node packages, or trackers are used.
* **Deterministic Logic:** The sorting and impossibility engines execute instantly on client-side triggers via lightweight computational loops, ensuring structural consistency with zero interface lag.
* **Optimized for In-Game Use:** Designed specifically for seamless integration as a second-monitor browser overlay, balancing low-contrast dark themes to preserve your night vision during gaming sessions.
