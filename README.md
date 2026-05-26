# 🇰🇪 seeNairobi — Mobile Tour Guide Platform

seeNairobi is a lightweight, mobile-first web application engineered to operate as an on-demand virtual tour guide right from a smartphone browser. The application provides an unfiltered, raw immersion into the rich culture, historic landmarks, and vibrant street life of Nairobi. 

It features built-in mapping integrations (`coolMap.html`) and custom stylesheet presentation architectures to ensure tourists and locals alike can navigate the city with ease.

---

## 🚀 Key Features

* **🗺️ Interactive City Mapping (`coolMap.html`):** A custom map interface curated to spotlight specific cultural landmarks, historical markets, matatu stages, and scenic routes across Nairobi.
* **📱 Mobile-First Responsive UI (`TOOR.css`):** Fluid styling layouts explicitly designed for low-latency, single-handed operation on mobile screens while exploring on foot.
* **🎒 Raw Cultural Immersion (`TOOR.html`):** Narrative-driven guides, local tips, and point-of-interest catalogs mapping out authentic Nairobi food, music, and community hubs.
* **⚡ Ultra-Lightweight & Dependency-Free:** Built using pure, vanilla web technologies to guarantee high performance and instant loading speeds over cellular mobile networks.

---

## 🛠️ Built With

* **HTML5 (52.3%):** Structures the page architectures, interactive map hooks, and content layouts (`TOOR.html`, `coolMap.html`).
* **CSS3 (47.7%):** Handles the fluid grids, responsive queries, and customized typography schemas tailored for smartphone browsers (`TOOR.css`).

---

## 📂 Codebase Directory Layout

```text
├── src/
│   ├── TOOR.css        # Mobile utility styles, layout layouts, and animation overrides
│   ├── TOOR.html       # Main content shell detailing local tour paths and locations
│   └── coolMap.html    # Dedicated view mapping point-of-interest coordinates
```

---

## 💻 Step-by-Step Local Deployment Procedure

Because this application relies entirely on native browser rendering engines, it requires zero package installations, node runtimes, or compilation steps to run locally.

### 1. Clone the Repository
Execute the command below inside your terminal window to download the project source files:
```bash
git clone https://github.com
cd seeNairobi
```

### 2. Launching the App
You can choose either of these straightforward methods to run the platform locally:

* **Method A (Direct File Exec):** Navigate into the `src/` directory using your system file manager and double-click `TOOR.html` to instantly spin it up in your default web browser.
* **Method B (VS Code Live Server):** Open the project folder in VS Code, right-click `src/TOOR.html`, and select **"Open with Live Server"** to view it on a local port (e.g., `http://127.0.0`).

*Tip: For the best visual representation, toggle your desktop browser's Developer Tools (`F12`) into **Mobile Device Emulation** mode.*
