# LUVS ESTATES — Architectural Walkthrough & Flagship Showcase

A luxury real estate web experience featuring a 240-frame high-DPI canvas scroll-driven architectural walkthrough of **Villa Serena** (Beverly Crest, $48,500,000), paired with interactive 3D spatial elevations, twilight residence portfolios, and private concierge viewings.

---

## ✨ Features

- **240-Frame Canvas Scroll Engine:** Hardware-accelerated 60/120 FPS canvas frame interpolation with `object-fit: cover` scaling.
- **Dynamic Brand Header:** Displays the signature "LUVS ESTATES" badge with golden typography and disappears smoothly when 30% scrolled.
- **Storytelling Narrative Overlays:** 4 glassmorphic story acts synchronised to the villa flythrough.
- **Curated Global Portfolio:** Showcases luxury residences across Monte Carlo (Monaco), Torno (Lake Como), and Palm Jumeirah (Dubai).
- **Interactive 3D Elevation Breakdown:** Multi-level telemetry explorer with 8K LiDAR metrics, ceiling heights, and travertine specifications.
- **Interactive 3D Virtual Tour Modal:** Multi-camera orbit with live azimuth & elevation readouts.
- **Private Advisory Concierge:** Client inquiry form for confidential dossiers and private showings.

---

## 🚀 Quick Start (Local)

### Option 1: Any static server
```bash
npx serve .
```
Or with Python:
```bash
python -m http.server 8080
```
Then open [http://localhost:8080](http://localhost:8080) in your browser.

---

## 🌐 Deploy to Vercel or Netlify

This project is 100% static and pre-configured for instant zero-config deployment.

### Deploy to Vercel:
1. Push your repository to GitHub.
2. Go to [Vercel Dashboard](https://vercel.com/new).
3. Import the `luvs-estates` repository.
4. Leave all settings default (Framework preset: `Other`, Root Directory: `./`).
5. Click **Deploy**.

*`vercel.json` is already included with optimized immutable caching headers for all 240 image frames.*

### Deploy to Netlify:
1. Push your repository to GitHub.
2. Go to [Netlify Dashboard](https://app.netlify.com/start).
3. Select GitHub and pick `luvs-estates`.
4. Publish directory: `.` (leave Build command blank).
5. Click **Deploy site**.

*`netlify.toml` is already included with security headers and caching configuration.*

---

## 📁 Repository Structure

```
├── frames/                 # 240 high-resolution architectural animation frames
│   ├── ezgif-frame-001.jpg
│   └── ...
├── Cinematic Twilight Luxury Villa.png  # Hero 3D virtual tour asset
├── index.html              # Main application & interactive engine
├── netlify.toml            # Netlify deployment & caching configuration
├── vercel.json             # Vercel deployment & caching configuration
├── package.json            # Project metadata & runner script
├── .gitignore              # Ignores local server binaries and OS metadata
└── README.md               # Project documentation
```

---

## 🏛️ License

MIT © [Luv's Estates](https://github.com/dakshita344-luv/luvs-estates)
