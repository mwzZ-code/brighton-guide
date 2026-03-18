# 🌊 Brighton Guide: Eat · Drink · Play
## 布莱顿吃喝玩乐全攻略 — 高交互式旅游导览网页

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CS+AI Project](https://img.shields.io/badge/Focus-CS%20%2B%20AI-blueviolet)](https://github.com/)

An elegant, interactive single-page application (SPA) designed for exploring the vibrant coastal city of Brighton. Built with a focus on modern UI/UX and seamless GIS integration.
一个优雅、高交互的单页 Web 应用，专为探索充满活力的海滨城市布莱顿设计。开发重点在于现代 UI/UX 体验与地理信息系统（GIS）的无缝集成。

---

## ✨ Features | 项目特性

### 🎨 Visual Experience | 视觉体验
* **Aurora & Particles**: Immersive background with CSS radial gradients and `tsParticles` engine.
    * **极光与粒子**：结合 CSS 径向渐变与 `tsParticles` 引擎打造的沉浸式动态背景。
* **Adaptive Theme**: One-click toggle between Dark and Light modes with persistent `localStorage`.
    * **自适应主题**：支持深色/浅色模式一键切换，并利用 `localStorage` 持久化存储用户偏好。
* **Interactive Cursor**: Custom "Mouse Light" effect that follows the cursor for enhanced depth.
    * **交互式光标**：跟随鼠标的自定义“光感”特效，增强页面空间感。

### 🗺️ Smart Navigation | 智能导航
* **GIS Integration**: High-performance interactive maps powered by **Leaflet.js**.
    * **地图集成**：基于 **Leaflet.js** 的高性能交互式地图。
* **Bi-directional Linkage**: Click a sidebar item to auto-pan and zoom to the map marker.
    * **双向联动**：点击侧边栏地点，地图自动平移缩放至对应标记并弹出气泡。
* **Real-time Search**: Instant card filtering and map location indexing.
    * **实时搜索**：支持卡片即时筛选与地图地点的关键词索引。

---

## 🛠️ Tech Stack | 技术栈

| Category | Technology |
| :--- | :--- |
| **Core** | HTML5, CSS3 (Grid/Flexbox), JavaScript (ES6+) |
| **Maps** | [Leaflet.js](https://leafletjs.com/) & OpenStreetMap |
| **Animations** | [AOS.js](https://michalsnik.github.io/aos/) (Scroll), [tsParticles](https://particles.js.org/) (Background) |
| **SEO** | Open Graph Protocol, JSON-LD Structured Data |

---

## 🚀 Quick Start | 快速开始

1.  **Clone the Repo | 克隆项目**
    ```bash
    git clone [https://github.com/your-username/brighton-guide.git](https://github.com/your-username/brighton-guide.git)
    ```
2.  **Configuration | 配置**
    Search for `yourdomain.example` in `index.html` and replace it with your actual deployment URL.
    在 `index.html` 中搜索 `yourdomain.example` 并替换为您真实的部署域名。
3.  **Run | 运行**
    Simply open `index.html` in your browser. For development, **VS Code Live Server** is recommended.
    直接在浏览器打开 `index.html` 即可。推荐使用 **VS Code Live Server** 插件进行预览。

---

## 📌 Roadmap | 开发路线图

- [ ] **Weather Integration**: Display real-time Brighton temperature using OpenWeatherMap API.
    - **天气集成**：对接 API 实时显示布莱顿海滨气温。
- [ ] **AI Recommendation**: Deploy a lightweight LLM agent to suggest personalized itineraries.
    - **AI 智能推荐**：利用大模型根据用户口味生成个性化行程。
- [ ] **i18n**: Fully automated English/Chinese content switching.
    - **国际化**：全站内容中英文全自动切换。

---

## 📜 License | 许可

This project is licensed under the **MIT License**.
本项目采用 **MIT 许可证**。

---

**Developer Note**: As a student in **CS+AI**, I built this project to showcase how modern front-end technologies can transform static travel information into an engaging digital experience.
**开发者寄语**：作为一名 **CS+AI** 专业学生，我开发此项目是为了展示如何利用现代前端技术将静态旅游信息转化为极具吸引力的数字交互体验。
