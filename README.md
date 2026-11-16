# 🏝️ Liam's 浮空小島 | Liam's Floating Island

**一個基於 Three.js 與 GSAP 打造的 3D 互動式個人主頁與作品集網站。**  
**An interactive 3D personal homepage and portfolio built with Three.js and GSAP.**

🌐 **線上預覽 / Live Demo:** [liamworld.pages.dev](https://www.google.com/search?q=https://liamworld.pages.dev)

## 📖 項目簡介 | Overview

**中文**  
「Liam's 浮空小島」是我 Vibe Coding 與 AI 3D 生成工具從 0 到 1 打造的個人數字空間。網站跳脫傳統平面簡歷排版，將個人履歷、近期 Vibe Coding 實驗作品、過往數據與學術項目，以及我的英國短毛藍貓「芝麻（Sesame）」融入一座可 360° 自由旋轉、縮放與探索的 3D 浮空島嶼中。

**English**  
**Liam's Floating Island** is an interactive 3D personal space built from scratch using [Three.js](https://threejs.org/) and AI 3D generation tools. Moving beyond traditional flat layouts, it brings together my professional resume, recent Vibe Coding experiments, data science projects, and my British Shorthair blue cat "Sesame" onto a floating island that visitors can freely rotate, zoom, and explore.

## ✨ 核心特色 | Key Features

- **3D 沉浸式導覽 (Interactive 3D Island):** 基於 [Three.js](https://threejs.org/) 載入 Draco 壓縮的 `.glb` 模型，具備小島呼吸懸浮動態、瀑布水流 UV 貼圖動畫，以及手繪程式化生成的粉格紋毛絨地墊與立體貓糧碗細節。
- **絲滑鏡頭運鏡 (Smooth Camera Transitions):** 結合 [GSAP](https://greensock.com/gsap/) 與 `OrbitControls`，點擊懸浮地標（Pin Labels）或底部膠囊導航欄即可自動推鏡聚焦至對應場景並展開詳情卡片。
- **即點即看中英雙語 (Instant Bilingual Switch):** 內建基於 `TreeWalker` 與 `MutationObserver` 的零延遲繁中 / 英文切換機制，自動記憶語言偏好。
- **跨裝置自適應排版 (Responsive Design):** 針對桌面端與手機端分別優化初始視角距離與雙排膠囊導航欄，確保觸控與滑鼠操作皆流暢自然。

## 🗺️ 島嶼導覽地標 | Island Spots

| 地標編號 | 島嶼場景 (Spot) | 內容簡介 (Description) |
| :--- | :--- | :--- |
| **00** | **全島全景 / Overview** | 重置鏡頭視角，俯瞰整座浮空小島與動態光影 |
| **01** | **樹屋 · 關於我 / Treehouse · About Me** | 個人履歷、現職經驗、教育背景、核心技能與 PDF 簡歷下載 |
| **02** | **瀑布 · 知識庫 / Waterfall · Knowledge** | 近期 Vibe Coding 實驗作品（[智能行情儀表盤](https://www.google.com/search?q=https://liamdashboard.pages.dev/)、[芝麻 3D 互動世界](https://www.google.com/search?q=https://sesameworld.pages.dev/)、[TextCrypt 本地加解密工具](https://www.google.com/search?q=https://textcrypt.pages.dev/)、[個人主頁](https://www.google.com/search?q=https://liamworld.pages.dev)） |
| **03** | **後山 · 項目展 / Hillside · Projects** | 過往作品與論文（[S&P 500 Market Heatmap](https://liamleelym.github.io/tableau-heatmap/)、[MDPI 區塊鏈金融應用論文](https://www.mdpi.com/2813-5288/2/3/14)、[Python 情感分析](https://www.google.com/search?q=https://liamleelym.github.io/Sentiment-Emotion-Analysis-in-Python/)、[SQL 資料庫設計](https://www.google.com/search?q=https://liamleelym.github.io/SQL-Project/)） |
| **04** | **島主芝麻 / Sesame · Contact** | 點擊或聚焦於藍貓「芝麻」3D 模型，查看聯絡方式與社群連結 |

## 🛠️ 技術棧 | Tech Stack

- **3D 渲染引擎 (3D Rendering):** [Three.js](https://threejs.org/) (`v0.160.0` — `WebGLRenderer`, `OrbitControls`, `GLTFLoader`, `DRACOLoader`, `Raycaster`)
- **動畫控制 (Animation):** [GSAP](https://greensock.com/gsap/) (`v3.12.5`)
- **前端架構 (Front-End):** 原生 HTML5、CSS3（Glassmorphism 毛玻璃視覺與 RWD 媒體查詢）、Vanilla JavaScript (ES Modules)，免打包工具即可直接部署
- **託管部署 (Deployment):** [Cloudflare Pages](https://pages.cloudflare.com/) / [GitHub Pages](https://pages.github.com/)

## 📂 目錄結構 | Project Structure

```text
├── index.html      # 主頁面（包含 UI 樣式、Three.js 3D 場景邏輯與中英雙語字典）
├── island.glb      # 浮空小島 3D 模型資源（支援 Draco 壓縮與水流動態貼圖）
├── blue cat.glb    # 島主「芝麻」英國短毛藍貓 3D 模型
├── resume.pdf      # 個人完整 PDF 履歷文件
└── README.md       # 項目說明文件
```


## 📬 聯絡方式 | Contact

- **Email:** liamleeym@outlook.com
- **LinkedIn:** [Liam Lee](https://linkedin.com/in/liam-lee-1463bb30a)
