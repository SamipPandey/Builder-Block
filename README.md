# 🤖 JARVIS Build

A browser-based 3D voxel builder with a **liquid glass UI**, inspired by Iron Man's JARVIS interface.  
Built with **Three.js**, featuring dark/light mode, voice commands, hand gesture controls, and pre-built blueprints.

![JARVIS Build Preview](https://img.shields.io/badge/status-live-brightgreen) ![HTML](https://img.shields.io/badge/built%20with-HTML%2FJS-orange)

---

## ✨ Features

- 🧊 **3D Voxel Builder** — Place, rotate, and erase blocks in a 3D environment using Three.js
- 💎 **Liquid Glass UI** — iOS 26-inspired glassmorphism design with light & dark modes
- 🎙️ **Voice Commands** — Say *"build ironman suit"*, *"build castle"*, *"dark mode"* etc.
- 🤚 **Hand Gesture Controls** — Uses your webcam to detect pinch, fist, peace, and open-palm gestures
- 🏗️ **Blueprints** — Instantly build: Iron Man Suit, Rocket, House, Tower, Car, Castle, Plane, Pyramid
- 🎨 **Full Customization** — Choose block colors, shapes (cube, sphere, cylinder, pyramid, spike, slab), and materials (solid, glass, metal, glow)
- ↩️ **Undo / Clear** — Full undo history and one-click scene reset
- 🌙 **Dark / Light Mode** — Animated wallpaper background with scanline HUD in dark mode

---

## 🚀 Getting Started

No installation or build step required. It's a single HTML file.

## 🎮 Controls

| Action | How |
|---|---|
| **Place block** | Left click on grid |
| **Erase block** | Right click on block |
| **Orbit camera** | Click + drag |
| **Zoom** | Scroll wheel |
| **Voice build** | Click 🎙️ mic button, speak a blueprint name |
| **Hand gestures** | Enable camera → use pinch/fist/peace/open hand |
| **Toggle dark mode** | Click 🌙 / ☀️ button |

### 🎙️ Voice Commands
> *"build ironman suit"* · *"build rocket"* · *"build castle"* · *"build house"*  
> *"build tower"* · *"build car"* · *"build plane"* · *"build pyramid"*  
> *"clear"* · *"undo"* · *"dark mode"* · *"light mode"*

---

## 🛠️ Tech Stack

- **Three.js** — 3D rendering
- **MediaPipe Hands** — Hand gesture detection via webcam
- **Web Speech API** — Voice recognition (Chrome recommended)
- **Vanilla HTML / CSS / JS** — Zero dependencies, zero build tools

---

## 📂 Project Structure
```
jarvis-build/
├── index.html    # Everything — UI, styles, and logic in one file
└── README.md     # You're reading it
```

---

## 🌐 Browser Support

| Browser | Support |
|---|---|
| Chrome / Edge | ✅ Full (voice + gestures) |
| Firefox | ✅ Partial (no voice) |
| Safari | ⚠️ Limited (no MediaPipe) |

> Voice commands require microphone permission.  
> Hand gestures require camera permission.

---

## 📄 License

MIT — free to use, fork, and build upon.
