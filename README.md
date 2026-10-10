# 🏛️ AuraHomes | Ultra-Luxury Real Estate & 3D Architectural Twin

A cutting-edge, single-file luxury real estate web application built with **HTML5**, **Tailwind CSS**, and **Three.js**. AuraHomes delivers a high-end property discovery experience featuring interactive 3D digital twins, live solar shadow simulations, multi-currency conversion, and architectural floor plan inspections.

---

## ✨ Key Features

- **🎮 3D Architectural Villa Twin (Three.js):**
  - Interactive WebGL 3D architectural visualization with smooth orbit, pan, and zoom controls.
  - Procedural modern L-shaped villa architecture featuring natural timber cladding, charcoal steel louvers, and glass facades.
  - Multi-angle camera presets (`Hero Yard`, `Covered Patio`, `Upper Suite`, `Whole Estate`).
  - Dynamic atmospheric lighting presets (`Twilight Hour`, `Night Glow`, `Overcast`).

- **🌓 Before & After Renovation Comparison:**
  - Interactive split-screen drag slider comparing raw concrete construction against bespoke designer completions.

- **☀️ 24-Hour Solar Path & Shadow Simulator:**
  - Interactive timeline slider modeling real-time sun elevation, azimuth, and directional ground shadows.

- **💱 Unified Multi-Currency Engine:**
  - Live currency switcher supporting **USD ($)**, **EUR (€)**, **GBP (£)**, **AED (د.إ)**, and **BDT (৳)**.
  - Automatically updates property cards, details modals, and mortgage calculations simultaneously without page reloads.

- **📐 Dual-View Property Inspector Modal:**
  - **Gallery View:** High-resolution architectural photography with 3D virtual walkthrough launcher.
  - **CAD Floor Plan View:** Interactive level switcher with clickable room hotspot inspections and technical specs.

- **📊 Mortgage & Financing Calculator:**
  - Real-time loan modeling for valuation, down payment percentage, tenure, and interest rates.
  - Visual breakdown chart with amortized monthly installment estimates.

- **❤️ Persistent Private Vault (Wishlist):**
  - LocalStorage-backed slide-out drawer preserving saved properties across browser sessions with live counter badges.

- **📱 Fully Responsive Design:**
  - Fluid mobile navigation drawer, touch-optimized sliders, and warm alabaster & champagne aesthetic.

---

## 🛠️ Tech Stack

- **Frontend Core:** HTML5, Vanilla JavaScript (ES6+)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN)
- **3D Graphics:** [Three.js](https://threejs.org/) (r128) & OrbitControls
- **Icons:** [Font Awesome 6](https://fontawesome.com/)
- **Typography:** *Playfair Display* (Serif Headings) & *Plus Jakarta Sans* (Body)
- **Effects:** [Canvas Confetti](https://www.kirilv.com/canvas-confetti/)

---

## 🚀 Getting Started

No complex build steps or dependencies required. Everything runs directly in the browser!

### Option 1: Direct Browser Launch
Simply double-click the `index.html` file or right-click and choose **Open With > Google Chrome** (or your preferred browser).

### Option 2: Local HTTP Server (Recommended for WebGL)
Run a local Python server in the project directory:

```bash
# Python 3
python -m http.server 8080
