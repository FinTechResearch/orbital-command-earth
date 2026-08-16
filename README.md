# ORBITAL COMMAND // EARTH

A single-file, interactive **3D Earth globe** built with Three.js — no build tools, no frameworks, no API keys. Just open `earth-globe.html` in a browser and you have a mission-control dashboard for planet Earth.

![Tech](https://img.shields.io/badge/three.js-r164-00e5ff) ![License](https://img.shields.io/badge/license-MIT-00e5ff)

## 🚀 Features

| Category | What you get |
| --- | --- |
| **Rendering** | Realistic day/night shader with a true sun terminator, city lights on the dark side, fresnel atmosphere glow, neon lat/long grid, animated polar aurora, 2,600-star backdrop |
| **Live ISS** | Real-time International Space Station position, computed orbit path, ground-track trail, and camera follow mode |
| **Flight arcs** | Animated neon great-circle routes between 16 major cities with travelling head dots |
| **Explorer** | Search 70+ cities and fly to them, click anywhere to drop a coordinate beacon |
| **Weather** | Live surface temperature overlay colored by heat (Open-Meteo, free, no key) |
| **Game** | "Orbital Quiz" — find the city on the globe before the timer runs out, with streaks, scores and confetti |
| **HUD** | Cyberpunk control panel, UTC clock, hover telemetry readout, layer toggles |

## 🎮 Controls

- **Drag** — rotate the camera
- **Scroll** — zoom
- **Click the globe** — tag coordinates (or answer the quiz)
- **Search box** — fly to any city in the database
- **Panel toggles** — grid / arcs / beacons / clouds / aurora / weather / ISS / auto-rotate

## ▶️ Run it

```bash
# nothing to install — just open the file
open earth-globe.html
```

Requires an internet connection (Three.js CDN, globe textures, and the live APIs). Works in any modern browser.

## 🛰️ Data sources

- **ISS position** — [wheretheiss.at](https://wheretheiss.at) (free, no key)
- **Weather** — [Open-Meteo](https://open-meteo.com) (free, no key)
- **Textures** — [three-globe](https://github.com/vasturiano/three-globe) example assets via jsDelivr CDN
- **Three.js** — r164 ES modules via importmap

## 📁 Project layout

```
earth-globe.html   ← the entire project, one file
```

## ⚠️ Disclaimer

The "aurora" is a stylized fake, the globe spins faster than reality, and the quiz judge is merciless. Proceed knowing the orbit knows all.

## 📄 License

MIT
