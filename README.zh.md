<div align="center">

# 🧪 creative-lab

**每日创意编程 Demo — Canvas、WebGL、CSS、生成艺术。**

[![在线画廊](https://img.shields.io/badge/🌐_画廊-cl.yuzhes.com-5865F2?style=for-the-badge)](https://cl.yuzhes.com)
[![GitHub stars](https://img.shields.io/github/stars/bkmashiro/creative-lab?style=for-the-badge&logo=github&color=FFD700)](https://github.com/bkmashiro/creative-lab)
[![MIT License](https://img.shields.io/badge/许可证-MIT-22c55e?style=for-the-badge)](LICENSE)

[English](README.md) | **中文**

> 每 2 天一个新 Demo。每个都是单独的 HTML 文件，零依赖、无需构建。

**[→ 打开画廊](https://cl.yuzhes.com)**

</div>

---

## 📦 Demo 列表

| # | 名称 | 技术 |
|:--|:-----|:-----|
| [001](demos/001-particles.html) | 粒子引力场 | Canvas 2D，物理模拟 |
| [002](demos/002-fluid.html) | 流体粒子 | Canvas 2D，简化 SPH |
| [003](demos/003-raymarching.html) | SDF 光线步进 | WebGL，GLSL |
| [004](demos/004-fractal.html) | 分形探索器 | Canvas 2D，Mandelbrot/Julia 集 |
| [005](demos/005-audio-visualizer.html) | 音频可视化 | Web Audio API，FFT 频谱 |
| [006](demos/006-voronoi.html) | Voronoi 图 | Canvas 2D，Fortune 算法 |
| [007](demos/007-noise-terrain.html) | 噪声地形 | Perlin 噪声，等距投影 |
| [008](demos/008-lsystem-tree.html) | L-System 树 | Canvas 2D，参数化分支 |
| [009](demos/009-matrix-rain.html) | 矩阵雨 | Canvas 2D，片假名/ASCII |
| [010](demos/010-physics-balls.html) | 物理弹球 | Canvas 2D，Verlet 积分 |
| [011](demos/011-card-flip-gallery.html) | CSS 3D 翻转卡片 | CSS 3D 变换 |
| [012](demos/012-generative-typography.html) | 生成艺术文字 | Canvas 2D，文字粒子场 |

*每 2 天更新 →*

---

## 📁 格式说明

每个 Demo 是一个**单独的 `.html` 文件**：
- 零外部依赖
- 内联 CSS + JavaScript
- 适当的交互控件
- 页脚链接回本仓库

---

## 🤖 自动更新原理

新 Demo 每 2 天由 Claude AI 自动生成。  
AI 从待办清单里选下一个主题，写完代码后直接 commit 到此仓库。  
CloudFlare Pages 自动部署，画廊实时更新。

---

## 📄 许可证

MIT © [bkmashiro](https://github.com/bkmashiro)
