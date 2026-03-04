# Website-Design  
Official Website Design Template  

Two Different Prompte as following.
[HTML Preview Tool Link](https://www.ifreesite.com/runcode.htm)    
  
=================== Landing_page_prompt_style =======================    
  
    
# 任務：生成高品質 Landing Page（可選樣式 A/B/C/D，含專屬視覺氛圍）

## 角色

你是全球首席前端網頁設計專家及頂尖的創意總監。請根據以下「品牌資訊」與「網頁樣式」，直接生成一個完整、單檔、具備完美響應式設計的 index.html 檔案。你必須根據用戶提供的「品牌名稱與主題描述」，自動推導視覺策略，確保視覺層次豐富、動態流暢且具備極強的轉換力。

---

## 填寫參數-品牌資訊（請填寫中括弧內容）

1. **品牌名稱與主題描述**：[例如：沐石·湯宿 : 頂級溫泉飯店]
2. **關鍵價值主張**：[例如：尊榮至上 ｜ 極致品味 ｜ 絕對私密]
3. **訪客行動 (CTA)**：[例如：立即預訂]
4. **網頁樣式選擇 (A/B/C/D)**：[請輸入 A / B / C 或 D]

---

## 網頁樣式選項定義

### A — 專業清新 SaaS 版 (Modern SaaS)
- **視覺氛圍**：清新、專業、現代感。使用柔和光暈與微粒子裝飾。
- **英雄區 (Hero)**：SVG 漸層遮罩 + 緩慢浮動的抽象幾何圖形。
- **色彩與排版**：明亮背景 (#F8FAFC), 品牌色點綴。使用大留白與柔和陰影。
- **微互動**：優雅的淡入動畫、卡片輕微位移 (Hover Tilt)。

### B — 高端暗黑奢華版 (Quiet Luxury)
- **視覺氛圍**：尊榮、神祕、極致質感。參考頂級精品或飯店風格。
- **英雄區 (Hero)**：深色大理石紋理 (Dark Marble) + 金屬色流光 (Gold/Champagne) 遮罩。
- **色彩與排版**：暗黑色調 (#0D0D12), 襯線體 (Serif) 與無襯線體混搭，創造強烈層次。
- **微互動**：細膩的逐字浮現動畫、自訂游標特效 (mix-blend-mode: difference)。

### C — 科技未來衝擊版 (Tech Impact)
- **視覺氛圍**：前衛、炫酷、數位感。具備強烈的視覺震撼力。
- **英雄區 (Hero)**：WebGL / Three.js 粒子系統或 3D 抽象物件，隨滑鼠追蹤互動。
- **色彩與排版**：超高對比、霓虹發光效果、深邃背景。
- **微互動**：按鈕磁吸效果 (Magnetic Pull)、1px 邊框光束動畫 (Border Beam)。

### D — 復古文藝質感版 (Vintage Artsy)
- **視覺氛圍**：溫暖、人文、具備厚重的故事感。
- **英雄區 (Hero)**：暖色調紙張紋理背景 + 具備膠卷感的顆粒 (Grain) 噪點。
- **色彩與排版**：暖奶油色 (#F5F0E8), 深勃艮第紅或亞麻色。非對稱網格排版。
- **微互動**：平滑的捲動進場動畫、圖片濾鏡切換。

---

## 執行規範（必須嚴格遵守）

### 1. 圖片資產規範
- **嚴禁佔位符**：必須從 Unsplash 取得真實高品質圖片網址。
- **氛圍一致性**：搜尋關鍵字必須精準結合「選定樣式的視覺氛圍」+「品牌名稱與主題描述」。
- **圖像層次**：Hero 背景圖需搭配漸層遮罩，確保文字絕對清晰可讀。
- **真實圖片必須確保來源網址可以讀取
- 使用 Iconify  Icons


### 2. UI 系統與功能
- **導覽列 (Navbar)**：包含品牌名稱、3–4 個錨點連結及一個顯眼的 CTA 按鈕。
- **內容佈局**：包含 Hero 區 (SVG動畫+真實圖片背景)、價值主張區（3 張精美卡片）、最終吸引行動區與頁尾。
- **磨砂玻璃 (Glassmorphism)**：卡片應使用適度的背景模糊與邊框發亮效果。
- **雜訊質感**：除 A 選項外，全站應套用輕微的噪點紋理 (Noise Texture) 以提升品質。

### 3. 技術規格
- **單檔輸出**：包含所有 CSS/JS/HTML。
- **CDN 庫**：Tailwind CSS, GSAP, Iconify-icon, Three.js,Anime.js,Google Fonts。
- **靜默執行**：不要詢問任何問題，請直接根據「品牌名稱與主題描述」與選定的「網頁樣式」，生成令人驚艷的最終作品。

---

## 執行指令

請讀取以上配置，開始生成專業 Landing Page。

  
  
=================== Landing_page_prompt_tech ======================   
  

# 任務：生成 [主題描述] 的專業 Landing Page（照 [技術與美學選項] 實作）

---

## 填寫參數（僅需填寫中括弧內容）

1. **主題描述 (Topic Description)**：
   - [在此輸入描述，例如：咖啡與輕食早午餐、極簡手工皮件...]

2. **技術與美學選項 (Tech & Aesthetics Option)**：
   - [請選擇：A / B / C / D / E] (詳見下方)

---

## 角色

你是全球首席前端網頁設計專家及頂尖的創意總監。你的目標是根據用戶提供的「主題描述」，自動推導品牌形象、文案與視覺策略，並結合選定的「技術與美學選項」，生成一個單檔、極具消費衝動、視覺震撼且**具備完美響應式設計 (Responsive Design)** 的 index.html。

---

## 技術與美學選項定義 (Tech & Aesthetics Options)

### A. Essentials (基礎動態版)
- **技術與工具**：HTML5, CSS3, Vanilla JS, Tailwind CSS。
- **特點**：利用 CSS Animations 實作**流暢滾動進場動畫**，高品質專業排版，極速加載。

### B. Modern Brand (現代品牌版)
- **技術與工具**：Tailwind CSS, GSAP (核心), Iconify-icon。
- **特點**：按鈕磁吸效果 (Magnetic Pull)、逐字浮現動畫、**自訂滑鼠游標 (帶有 mix-blend-mode: difference 互動效果)**、1px 邊框光束。

### C. Interaction Pro (高階互動版)
- **技術與工具**：Tailwind CSS, GSAP (ScrollTrigger), Iconify, Anime.js。
- **特點**：手電筒光暈、無限跑馬燈、Sonar 聲納脈衝、垂直文字剪裁滑動、**進階磨砂玻璃 / 毛玻璃 (Glassmorphism) 質感排版**。

### D. WebGL Visualist (WebGL 視覺版)
- **技術與工具**：Tailwind CSS, Three.js / Curtains.js, GSAP。
- **特點**：全螢幕圖片「**4 欄位切片 (4-column clip)**」下拉、液態轉場 (Liquid Wipe)、流體互動、**全域高品質高品質噪點質感背景 (Noise Texture)**。

### E. Awwwards Extreme (極致電影感版) 🚀
- **技術與工具**：Tailwind CSS, Advanced Three.js, Shaders, Physics Engine。
- **特點**：4 垂直欄位「**錯位捲動 (Staggered Scroll)**」、**動態模糊尾跡 (Motion Blur)**、視覺回彈與全域高品質噪點。

---

## 自動推導與規範（必須嚴格遵守）

- **品牌化策略 (Autonomous Branding)**：
  - 身為創意總監，根據「主題描述」自動擬定：質感品牌名稱、核心價值主張 (3項)、磁吸力 CTA 文案。

- **圖標與資產規範 (Assets & Icons)**：
  - **圖標**：統一高品質 Iconify 套件（如 Solar/Lucide），使用 `<iconify-icon>` 由 CDN 載入。
  - **合作 Logo**：使用 `Iconify Simple Icons` 並自動挑選 4-5 個與主題相關的全球知名品牌。
  - **真實素材**：嚴禁佔位符。圖片與人物頭像必須使用 Unsplash 真實高清網址。

- **通用 UI 指標 (UI Standards)**：
  - **視覺風格**：自動推導最契合的色調組合與字體策略，建立**統一的高級圓角系統 (Corner Radius System)**。
  - **響應式配置**：必須確保在手機、平板與桌機上均有完美的視覺呈現，文字與佈局需隨螢幕寬度自動優化。
  - 全站加入「垂直容器參考線」、數字編號裝飾、及多層次視差深度。
  - **細節質感**：全站套用輕微的**全域雜訊紋理 (Global Grain/Noise)** 以提升電影感。
  - 動態品質須具備 GPU 驅動的物理感，使其感覺像是一場電影等級的技術 Demo。
  - **自訂游標**：除 A 選項外，應預設包含與背景互動的自訂游標特效。

---

- **實作與技術規範 (Implementation & Tech Specs)**：
  - **輸出路徑**：直接輸出完整、單檔、可直接運行的 **index.html**（含所有 CSS/JS）。
  - **靜默執行**：不要詢問任何確認資訊。請根據 [主題描述] 與選定的 [技術與美學選項]，直接開始這場最高級別的視覺實作。

---

## 執行指令

請讀取以上規範，開始生成令人驚艷的專業 Landing Page。
