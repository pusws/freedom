# Freedom: The Manifesto

[中文](#数字独立宣言)

An interactive conceptual web project that combines narrative interaction with WebGL 3D visuals.
It is both a webpage and a metaphorical digital artwork about censorship, privacy, and free will in the information age.

## 🌟 Core Concepts

### 1) Redaction & Decryption

The manifesto text uses a “classified archive” style.
Important words (e.g. “Will”, “Panopticon”) are hidden under dark blocks at first, then gradually revealed while reading (scrolling) or clicking.
This symbolizes breaking information blockades to recover truth.

### 2) Shattering the Blockade

The 3D scene on the right is the project’s centerpiece:

- **The Blockade**: A closed sphere made of 1,200 black cubes, representing algorithmic censorship, platform monopoly, and information cocoons.
- **The Spark of Will**: A glowing core trapped inside, symbolizing uncompromising free will.
- **The Breakthrough**: As reading progresses, the core intensifies until the outer cubes are blasted apart.
- **Liberated Data**: After collapse, blue particles burst out and spiral upward, symbolizing data liberation and sovereignty.

### 3) Geometric Badge

Instead of concrete icons, the header uses pure geometric SVG elements (circles, dashed lines, intersections, polygons) with subtle breathing glow for a solemn, sci‑fi ritual tone.

## 🛠️ Tech Stack

Single-file architecture, no build step required:

- **HTML5**: Semantic structure and content.
- **Tailwind CSS (CDN)**: Typography, dark UI, and animation.
- **Vanilla JavaScript**: Scroll interaction, decryption state updates, parallax, interpolation.
- **Three.js (r128)**:
  - `InstancedMesh` for efficient rendering of 1,200 cubes.
  - Fibonacci sphere distribution for initial placement.
  - `MeshPhysicalMaterial` for metallic feel.
  - Physics-inspired trajectories and particle spiral motion.

## 🚀 Quick Start

1. Clone or download this repository.
2. Run in one of the following ways:

- **Direct open**: Double-click `index.html` in a modern browser.
- **Recommended (local server)**:
  - Python 3: `python -m http.server 8000`
  - Visit: `http://localhost:8000`
  - Or use VS Code Live Server.

## 💡 Interaction Guide

- **Read + Scroll**: Drives the narrative and 3D state transition.
- **Click to Decrypt**: Click masked words to reveal hidden terms.
- **Move Mouse**: Observe subtle 3D parallax.

## 📁 Project Structure

- `index.html`: All layout, styles, interaction logic, and 3D rendering.
- `README.md`: Project introduction and usage.
- `LICENSE`: License file.

## 🤝 Contribution

This project is intended as both an art concept and a technical demo.
Feel free to fork, remix, and share.

> “Freedom is not a default state; it is a protocol that must be executed.”

---

# 数字独立宣言

一个结合交互叙事与 WebGL 3D 渲染的概念网页项目。
它不仅是网页，也是一件关于审查、隐私与自由意志的数字隐喻作品。

## 🌟 核心理念

### 1）信息遮蔽与解密

宣言文本采用“机密档案”风格。
关键词（如“意志”“全景监狱”）初始被深色块遮蔽；随着滚动阅读或点击，会逐步显现。
这象征着打破信息封锁、获取真相的过程。

### 2）数字封锁线的瓦解

右侧 3D 场景是项目核心：

- **封锁牢笼**：由 1200 个黑色方块组成的闭合球体，隐喻算法审查、平台垄断与信息茧房。
- **意志之核**：被困于内部的发光核心，象征不妥协的自由意志。
- **觉醒突破**：随着阅读推进，核心能量增强，最终冲破封锁并击碎方块。
- **自由数据流**：牢笼崩解后，蓝色粒子喷涌上升，隐喻数据解放与主权重构。

### 3）几何徽章

页首放弃具象图标，改用纯几何 SVG（圆、虚线、相交线、多边形）与微弱呼吸光效，营造庄严、科幻的仪式感。

## 🛠️ 技术栈

单文件结构，即开即用，无需构建流程：

- **HTML5**：语义化结构与文档内容。
- **Tailwind CSS（CDN）**：排版、深色 UI、动画效果。
- **Vanilla JavaScript**：滚动交互、解密状态切换、视差与插值计算。
- **Three.js（r128）**：
  - 使用 `InstancedMesh` 高效渲染 1200 个方块。
  - 使用斐波那契球面算法进行均匀分布。
  - 使用 `MeshPhysicalMaterial` 模拟金属质感。
  - 基于物理直觉计算爆炸轨迹与粒子螺旋上升。

## 🚀 快速开始

1. 克隆或下载仓库。
2. 任选以下方式运行：

- **直接打开**：在现代浏览器中双击 `index.html`。
- **推荐（本地服务）**：
  - Python 3：`python -m http.server 8000`
  - 访问：`http://localhost:8000`
  - 或使用 VS Code Live Server 插件。

## 💡 交互说明

- **阅读 + 滚动**：驱动叙事推进与 3D 状态变化。
- **点击解密**：点击遮蔽词条，主动揭示关键词。
- **鼠标移动**：观察细微 3D 视差，增强沉浸感。

## 📁 项目结构

- `index.html`：页面结构、样式、交互逻辑与 3D 渲染。
- `README.md`：项目说明与使用指南。
- `LICENSE`：许可证文件。

## 🤝 贡献

本项目同时是艺术表达与技术演示，欢迎复刻、改造与分享。

> “自由不是默认状态，它是一种必须被执行的协议。”
