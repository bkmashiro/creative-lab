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
| [013](demos/013-game-of-life.html) | Game of Life | Canvas 2D, cellular automata |
| [014](demos/014-maze-generator.html) | Maze Generator | Canvas 2D, recursive backtracking |
| [015](demos/015-water-ripple.html) | Water Ripple | Canvas 2D, wave simulation |
| [016](demos/016-star-field.html) | Star Field | Canvas 2D, parallax depth |
| [017](demos/017-neural-network.html) | Neural Network | Canvas 2D, activation visualizer |
| [018](demos/018-cloth-simulation.html) | Cloth Simulation | Canvas 2D, Verlet constraints |
| [019](demos/019-svg-clock.html) | Artistic SVG Clock | SVG, generative modes |
| [020](demos/020-smoke-simulation.html) | Smoke Simulation | Canvas 2D, advection diffusion |
| [021](demos/021-fourier-epicycles.html) | Fourier Epicycles | Canvas 2D, DFT reconstruction |
| [022](demos/022-reaction-diffusion.html) | Reaction Diffusion | Canvas 2D, Gray-Scott model |
| [023](demos/023-boids-flocking.html) | Boids Flocking | Canvas 2D, emergent behavior |
| [024](demos/024-lorenz-attractor.html) | Lorenz Attractor | Canvas 2D, 3D chaos projection |
| [025](demos/025-spring-network.html) | Spring Network | Canvas 2D, elastic mesh |
| [026](demos/026-brownian-motion.html) | Brownian Motion | Canvas 2D, random walk heat map |
| [027](demos/027-bezier-curve-editor.html) | Bezier Curve Editor | Canvas 2D, de Casteljau |
| [028](demos/028-sand-simulation.html) | Sand Simulation | Canvas 2D, falling sand |
| [029](demos/029-metaballs.html) | Metaballs | WebGL, implicit surfaces |
| [030](demos/030-fireworks.html) | Fireworks | Canvas 2D, particle physics |
| [031](demos/031-lightning.html) | Lightning Generator | Canvas 2D, recursive branching, glow |
| [032](demos/032-kaleidoscope.html) | Kaleidoscope | Canvas 2D, radial symmetry, webcam |
| [033](demos/033-pendulum-wave.html) | Pendulum Wave | Canvas 2D, phase synchronization |
| [034](demos/034-double-pendulum.html) | Double Pendulum | Canvas 2D, RK4 chaos, trail rendering |
| [035](demos/035-wave-interference.html) | Wave Interference | Canvas 2D, superposition, double-slit |
| [036](demos/036-plasma-effect.html) | Plasma Effect | WebGL, GLSL, demoscene, color cycling |
| [037](demos/037-galaxy-spiral.html) | Galaxy Spiral | Canvas 2D, logarithmic spiral, rotation curves |

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
