# Freedom: Free Speech Declaration

[中文](#freedom-言论自由宣言)

A refactored interactive manifesto webpage about free speech rights, platform transparency, and public knowledge sovereignty.
The project blends long-form narrative, bilingual switching, and real-time WebGL visuals into one immersive reading experience.

## Highlights

- **Bilingual live switch (EN / 中文):** One-click language toggle updates all narrative sections, metrics, and UI labels.
- **Progress-driven storytelling:** Scroll activates section reveals, progress indicator, and staged visual transitions.
- **Redaction-to-reveal interaction:** Key terms start as masked fragments and become visible through click and viewport-triggered decoding.
- **Refactored visual language:** Dark glass panels, protocol cards, geometric sigil, and layered gradients for a consistent “digital manifesto” tone.

## 3D Scene (Three.js)

The background scene is synchronized with reading progress:

- **Blockade shell:** `1600` instanced cubes distributed with a Fibonacci-sphere pattern.
- **Will core:** Emissive icosahedron + wireframe torus knot + 3 orbital rings.
- **Break phase:** Scroll progress drives shell expansion, rotation, and shrink-to-collapse behavior.
- **Data sparks:** `2800` additive particles emerge after threshold progress and form upward swirling motion.
- **Parallax control:** Mouse movement subtly offsets group rotation for depth.

## Tech Stack

No build step required (single-file app):

- **HTML5** structure and semantic content
- **Tailwind CSS (CDN)** for utility styling and responsive layout
- **Vanilla JavaScript** for i18n state, scroll logic, reveal behavior, and animation control
- **Three.js r128** for GPU rendering (`InstancedMesh`, custom particle updates, physically styled materials)

## Quick Start

1. Clone this repository.
2. Run either method below:

- **Direct open:** open `index.html` in a modern browser.
- **Local server (recommended):**
  - `python -m http.server 8000`
  - visit `http://localhost:8000`

## Interaction Guide

- **Scroll:** drives reading progress, content reveal, and 3D phase changes.
- **Click masked terms:** reveal redacted keywords.
- **Move mouse:** observe subtle 3D parallax.
- **Switch language:** use the top-right `EN / 中文` toggle.

## Project Structure

- `index.html` — UI, styles, i18n content, interactions, and Three.js scene logic
- `README.md` — project overview and usage
- `LICENSE` — MIT license text

## License

MIT

---

# Freedom: 言论自由宣言

一个重构后的交互式宣言网页项目，聚焦言论自由权利、平台透明度与公共知识主权。
项目将长文叙事、双语切换与 WebGL 实时视觉融合为一体化阅读体验。

## 亮点

- **双语即时切换（EN / 中文）：** 右上角一键切换，整页文案与界面标签同步更新。
- **滚动驱动叙事：** 随阅读进度触发内容显现、进度条变化与视觉阶段演进。
- **遮蔽词解密交互：** 关键词默认遮蔽，可点击解密，也会在视口触发下逐步显现。
- **重构后的视觉体系：** 深色玻璃面板、协议卡片、几何徽记与分层渐变统一整体风格。

## 3D 场景（Three.js）

背景 3D 场景与阅读进度实时联动：

- **封锁外壳：** `1600` 个实例化立方体，使用斐波那契球面分布。
- **意志核心：** 发光二十面体 + 线框环结 + 3 层轨道环。
- **突破阶段：** 滚动进度驱动外壳扩散、旋转与塌缩。
- **数据火花：** `2800` 个加色粒子在阈值后喷发并形成上升旋流。
- **视差控制：** 鼠标移动微调整体旋转，增强空间层次。

## 技术栈

无需构建流程（单文件应用）：

- **HTML5**：页面结构与语义内容
- **Tailwind CSS（CDN）**：实用类样式与响应式布局
- **Vanilla JavaScript**：i18n 状态、滚动逻辑、解密交互与动画控制
- **Three.js r128**：GPU 渲染（`InstancedMesh`、粒子更新、材质效果）

## 快速开始

1. 克隆仓库。
2. 任选以下方式运行：

- **直接打开：** 在现代浏览器中打开 `index.html`。
- **推荐本地服务：**
  - `python -m http.server 8000`
  - 访问 `http://localhost:8000`

## 交互说明

- **滚动：** 推进叙事、触发内容显现与 3D 阶段变化。
- **点击遮蔽词：** 解密关键词。
- **移动鼠标：** 观察细微 3D 视差。
- **语言切换：** 使用右上角 `EN / 中文` 按钮。

## 项目结构

- `index.html`：界面、样式、双语文案、交互逻辑与 Three.js 场景
- `README.md`：项目说明与使用指南
- `LICENSE`：MIT 许可证

## 许可证

MIT
