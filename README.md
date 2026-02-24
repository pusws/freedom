# Freedom: The Manifesto

This is an interactive conceptual web project that combines deep interactive narrative with advanced WebGL 3D rendering technology. It's not just a webpage, but a metaphorical digital art piece exploring censorship, privacy, and free will in the information age.

## 🌟 Core Concepts & Metaphors

This project abandons the particle effects commonly used in traditional websites for showing off technical skills, instead using physical metaphors to convey profound ideas:

### Redaction Effect

The manifesto text on the webpage adopts the typical classified archive style. Key terms (such as "Will", "Panopticon") are initially hidden under dark gray blocks. As users read (scroll down) or actively click, these "information blackouts" will dissipate one by one, revealing red text representing truth. This symbolizes the process of breaking information blockades and obtaining the truth.

### Shattering the Blockade

The 3D scene on the right side of the webpage is the soul of the entire project.

- **The Blockade**: A closed sphere composed of 1,200 hard, pitch-black cubes, metaphor for ubiquitous algorithmic censorship, data monopolies, and information cocoons. It is oppressive, cold, and even experiences digital glitch twitches.

- **The Spark of Will**: Trapped inside the blockade is an energy core radiating geek-blue glow and pulsating like a heart with blood-red grids, symbolizing uncompromising free will.

- **The Breakthrough**: This is the climax of the entire work. As users read deeper into the manifesto (scrolling down), the inner energy core's glow becomes increasingly intense. Finally, the massive black blockade can no longer suppress this force—1,200 cubes will be instantly blasted away, wildly rotating, and dissipating in the light of truth.

- **The Liberated Data**: After the cage shatters, 2,000 blue data particles burst out like a starburst, spiraling upward through the void, metaphor for data liberation and sovereignty reconstruction.

### The Geometric Spark

Abandoning concrete icons, the project uses pure geometric lines (circles, dashed lines, intersecting lines, polygons) to construct an SVG badge at the page header with a faint breathing halo, conveying a solemn sense of ritual and sci-fi religiousness.

## 🛠️ Tech Stack

This project uses a single-file structure, ready to use out of the box, with no build step dependencies,极致轻量:

- **HTML5**: Semantic structure, carrying document content.

- **Tailwind CSS (CDN)**: Used for building极致 responsive typography, dark mode UI, and CSS animations for text fade-in/out. Specially configured with exclusive theme colors (such as blood, geekblue, void).

- **Vanilla JavaScript**: Native JS handles all interaction logic, including scroll detection, parallax calculation, DOM element state switching (redaction effect), and complex mathematical interpolation algorithms.

- **Three.js (r128)**: Core 3D rendering engine.
  - Uses InstancedMesh for efficient rendering of 1,200 cubes (significantly improves performance).
  - Combines Fibonacci sphere algorithm for uniform initial sphere distribution.
  - Uses MeshPhysicalMaterial to simulate realistic metallic texture and reflections.
  - Utilizes extensive trigonometric functions and physical motion formulas to calculate cube explosion trajectories, rotation, and particle spiral ascent.

## 🚀 Getting Started

Since this project has no complex backend or build tools, running it is very simple:

1. **Clone or Download**: Download the project code to your local machine.

2. **Run**:
   - Simplest method: Double-click to open the `index.html` file in any modern browser (Chrome, Firefox, Safari, Edge).

   - Recommended method: For the best experience (to avoid some browsers' local file cross-origin restrictions affecting Three.js textures, although this project currently doesn't use external textures, it's a good habit), it is recommended to run with a local server. For example:
     - If Python 3 is installed: Run `python -m http.server 8000` in the project directory, then visit `http://localhost:8000` in your browser.
     - If using VS Code: Install and click the "Live Server" plugin.

## 💡 How to Interact

- **Reading & Scrolling**: The core experience of the webpage is driven by your scrolling behavior. Slowly scroll down the page and read the "Digital Independence Manifesto" on the left. You will observe the right-side 3D blockade's state undergoing an epic dissolution as your reading progress advances.

- **Active Decryption**: You can also actively click on those blackened blocks in the text on the left to force-decipher hidden words.

- **Parallax Observation**: Gently move your mouse to observe the subtle parallax effect of the 3D scene, enhancing immersion.

## 🤝 Contributions & Inspiration

This project aims to serve as an artistic concept and technical demonstration. Developers interested in digital art, graphics, or digital rights are welcome to replicate, modify, and share.

> "Freedom is not a default state; it is a protocol that must be executed."

---

# 数字独立宣言

这是一个结合了深度交互叙事与高级 WebGL 3D 渲染技术的交互式概念网页项目。它不仅仅是一个网页，更是一篇具有隐喻意义的数字艺术作品，旨在探讨信息时代下的审查、隐私与自由意志。

## 核心理念与隐喻

本项目抛弃了传统网页中为了炫技而堆砌的粒子特效，转而采用物理隐喻来传达深刻的思想：

### 信息遮蔽与解密

网页中的宣言文本采用了典型的机密档案样式。关键的词汇（如"意志"、"全景监狱"）最初被隐藏在深灰色的色块下。随着用户的阅读（向下滚动）或主动点击，这些"信息黑幕"会逐个消散，露出代表真理的红色文字。这象征着打破信息封锁，获取真相的过程。

### 数字封锁线的瓦解

网页右侧的 3D 场景是整个项目的灵魂。

- **封锁牢笼 (The Blockade)**: 由 1200 个坚硬、漆黑的方块构成的闭合球体，隐喻着无处不在的算法审查、数据垄断与信息茧房。它压抑、冰冷，甚至会产生数字故障 (Glitch) 的抽搐。

- **意志之核 (The Spark of Will)**: 被封锁线囚禁在内部的，是一个散发着极客蓝光芒、并如心脏般搏动着鲜血红网格的能量核心，象征着永不妥协的自由意志。

- **觉醒与突破 (The Breakthrough)**: 这是整个作品的高潮。随着用户阅读宣言的深入（向下滚动），内部的能量核心光芒会越来越盛。最终，庞大的黑色封锁线再也无法压制这股力量，1200 个方块会被瞬间炸飞、狂乱旋转，并在真理之光中消散。

- **自由数据流 (The Liberated Data)**: 牢笼破碎后，2000 个蓝色的数据粒子如同星暴般涌出，在虚空中螺旋上升，隐喻着数据的解放与主权的重构。

### 极简真理之眼

放弃了具象的图标，使用纯粹的几何线条（圆、虚线、相交线、多边形）在页首构建了一个带有微弱呼吸光晕的 SVG 徽章，传达出肃穆的仪式感与科幻宗教感。

## 技术栈

该项目采用单文件结构，即开即用，无任何构建步骤依赖，极致轻量：

- **HTML5**: 语义化结构，承载文档内容。

- **Tailwind CSS (CDN)**: 用于快速构建极致的响应式排版、深色模式 UI、以及文本淡入淡出的 CSS 动画。特别配置了专属的主题颜色（如 blood、geekblue、void）。

- **Vanilla JavaScript**: 原生 JS 处理所有交互逻辑，包括滚动侦测、视差计算、DOM 元素的状态切换（解密特效）以及复杂的数学插值算法。

- **Three.js (r128)**: 核心 3D 渲染引擎。
  - 使用 InstancedMesh 高效渲染 1200 个方块（极大提升性能）。
  - 结合斐波那契球面算法 (Fibonacci sphere) 均匀分布初始球体。
  - 运用物理材质 (MeshPhysicalMaterial) 模拟真实的金属质感与反光。
  - 利用大量三角函数和物理运动公式计算方块的爆炸轨迹、旋转以及粒子的螺旋上升。

## 快速启动

由于本项目没有复杂的后端或构建工具，运行它非常简单：

1. **克隆或下载**: 将本项目代码下载到本地。

2. **运行**:
   - 最简单的方法: 直接在任何现代浏览器（Chrome, Firefox, Safari、Edge）中双击打开 `index.html` 文件。

   - 推荐方法: 为了获得最佳体验（避免某些浏览器的本地文件跨域限制影响 Three.js 纹理，虽然本项目目前未用外部纹理，但这是好习惯），建议使用本地服务器运行。例如：
     - 如果安装了 Python 3: 在项目目录下运行 `python -m http.server 8000`，然后在浏览器访问 `http://localhost:8000`。
     - 如果使用 VS Code: 安装并点击 "Live Server" 插件。

## 交互说明

- **阅读与滚动**: 网页的核心体验由您的滚动行为驱动。慢慢向下滚动页面，阅读左侧的《数字独立宣言》。您会观察到右侧 3D 封锁线的状态随着您的阅读进度发生史诗般的瓦解。

- **主动解密**: 您也可以主动点击左侧文中那些被涂黑的方块，强制解密隐藏的词汇。

- **视差观察**: 轻轻移动鼠标，可以观察到 3D 场景微妙的视差效果，增强沉浸感。

## 贡献与启发

本项目旨在作为一个艺术概念和技术演示。欢迎任何对数字艺术、图形学或数字权利感兴趣的开发者复刻、修改和分享。

> "自由不是默认状态，它是一种必须被执行的协议。"
