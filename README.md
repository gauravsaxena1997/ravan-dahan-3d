# Dussehra Ravan Dahan 3D

An authentic, interactive 3D Vedic archery and Ravan Dahan celebration game built with Three.js, WebGL, and HTML5.

Experience the victory of light over darkness. Draw Lord Rama's celestial Kodanda bow, aim the fiery Agneyastra arrow, and hit the ten-headed Dashanan effigy to ignite the festival celebration.

---

## Live Demo

Play directly in your browser without any installation:
- **Live Game**: [https://creative-ui-two.vercel.app/dussehra-ravan-dahan.html](https://creative-ui-two.vercel.app/dussehra-ravan-dahan.html)

---

## Features

- **Authentic 10-Headed Dashanan**: Faithful 3D anatomical design featuring the 1 central king head flanked by 9 royal heads, traditional golden mukuts (crowns), royal tilaks, defined mustache patterns, and ceremonial gold ornaments.
- **Interactive Kodanda Bow**: Positioned realistically at the bottom center. Click and drag or touch and drag backward to draw the bowstring, tension the arrow, and release to shoot.
- **Realistic Arrow Physics**: Parabolic flight trajectory with orientation matching velocity vector and sound effects on release.
- **Embedded Arrows & Volumetric Fire**: Arrows physically embed upon impact. Each successful hit ignites and amplifies multi-layered volumetric fire and rising ember particles.
- **Cinematic Celebration Takeover**: Upon completing 3 hits, the 3D scene smoothly fades into a high-definition festive celebration video featuring dynamic fireworks and high-contrast 3D typography with a "Start Again" replay option.
- **Fully Mobile Responsive**: Designed from the ground up for both desktop mouse controls and mobile touch gestures with portrait and landscape support.
- **Zero Heavy Dependencies**: Completely standalone client-side application. Can be run locally by simply opening `index.html` or deployed to any static host.

---

## Controls

### Desktop
- **Aim**: Move mouse horizontally across the screen to rotate and aim the bow.
- **Draw**: Click and hold the left mouse button, then pull down/backward to charge tension.
- **Release**: Release the mouse button to loose the fiery Agneyastra arrow.

### Mobile & Touch
- **Aim & Draw**: Touch anywhere on screen, drag down to aim and tension the bowstring.
- **Release**: Lift your finger to fire.

---

## Quick Start (Run Locally)

Because the project is completely self-contained, no build steps are required.

### Option 1: Open Directly
Double-click `index.html` in your file explorer to open it directly in Google Chrome, Safari, or Microsoft Edge.

### Option 2: Using npx serve
```bash
npx serve -l 3000 .
```
Then visit `http://localhost:3000` in your browser.

### Option 3: Using Python
```bash
# Python 3
python3 -m http.server 3000
```
Then visit `http://localhost:3000` in your browser.

---

## Project Structure

```text
ravan-dahan-3d/
├── index.html                      # Complete game application (3D scene, UI, particle engines)
├── three.min.js                    # Three.js (r128) library
├── ravana-dahan-celebration.mp4    # HD festival celebration video
├── package.json                    # Optional convenience scripts
├── .gitignore                      # Git ignore rules
└── README.md                       # Project documentation
```

---

## Tech Stack

- **Three.js (r128)**: 3D scene graphing, custom geometry assembly, procedural textures, and camera projection.
- **WebGL**: Hardware-accelerated rendering and depth buffering.
- **HTML5 Canvas & Video**: Native particle canvas and responsive background video streaming.
- **Tailwind CSS**: Utility-first styling for HUD, crosshairs, and celebration overlays.
- **Web Audio API**: Synthesized bow twangs, whooshes, flame crackles, and impact acoustics.

---

## License

MIT License. Open source and free to use for celebratory and educational purposes.
