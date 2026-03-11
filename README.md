<div align="center">

# 🧪 creative-lab

**Daily creative coding demos — canvas, WebGL, CSS, generative art.**

[![Live Gallery](https://img.shields.io/badge/🌐_gallery-cl.yuzhes.com-5865F2?style=for-the-badge)](https://cl.yuzhes.com)
[![GitHub stars](https://img.shields.io/github/stars/bkmashiro/creative-lab?style=for-the-badge&logo=github&color=FFD700)](https://github.com/bkmashiro/creative-lab)
[![MIT License](https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge)](LICENSE)

**English** | [中文](README.zh.md)

> One new demo every 2 days. Each is a single self-contained HTML file — no build step, no dependencies.

**[→ Open Gallery](https://cl.yuzhes.com)**

</div>

---

## 📦 Demos

| # | Name | Technique |
|:--|:-----|:----------|
| [001](demos/001-particles.html) | Particle Gravity Field | Canvas 2D, physics |
| [002](demos/002-fluid.html) | Fluid Particles | Canvas 2D, SPH-lite |
| [003](demos/003-raymarching.html) | SDF Raymarching | WebGL, GLSL |
| [004](demos/004-fractal.html) | Fractal Explorer | Canvas 2D, Mandelbrot/Julia |
| [005](demos/005-audio-visualizer.html) | Audio Visualizer | Web Audio API, FFT |
| [006](demos/006-voronoi.html) | Voronoi Diagram | Canvas 2D, Fortune's algorithm |
| [007](demos/007-noise-terrain.html) | Noise Terrain | Perlin noise, isometric |
| [008](demos/008-lsystem-tree.html) | L-System Tree | Canvas 2D, parametric branching |
| [009](demos/009-matrix-rain.html) | Matrix Rain | Canvas 2D, katakana/ASCII |
| [010](demos/010-physics-balls.html) | Physics Bouncing Balls | Canvas 2D, Verlet integration |
| [011](demos/011-card-flip-gallery.html) | CSS 3D Card Flip | CSS 3D transforms |
| [012](demos/012-generative-typography.html) | Generative Typography | Canvas 2D, text as particles |

*More coming every 2 days →*

---

## 📁 Format

Each demo is a **single `.html` file** with:
- Zero external dependencies
- Inline CSS + JavaScript
- Interactive controls where applicable
- A footer linking back to this repo

---

## 🤖 How it works

New demos are generated automatically every 2 days by a Claude AI agent.  
It picks the next item from a todo list, writes the code, and commits directly to this repo.  
The gallery updates automatically via CloudFlare Pages.

---

## 📄 License

MIT © [bkmashiro](https://github.com/bkmashiro)
