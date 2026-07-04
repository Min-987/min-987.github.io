# 🌌 Min-987 個人官方網站 & 作品集 (Personal Portfolio)

Welcome! 這是我個人網站的官方代碼倉庫，採用現代前端架構建造，整合了我的個人作品展示、產品介紹頁、以及多功能 Web 工具。

👉 **正式網址**：[https://min-987.github.io/](https://min-987.github.io/)

---

## 🚀 專案技術棧 (Tech Stack)

- **核心框架**：[Astro v6](https://astro.build/) (超輕量靜態網站建置器)
- **視覺風格**：自訂 Vanilla CSS (實作玻璃擬態 Glassmorphism、極光光暈、Apple 風格懸浮膠囊導航列)
- **表單整合**：HubSpot API 聯絡表單 (整合訪客 IP 追蹤防護與防阻擋降級機制)
- **部署方式**：GitHub Pages 靜態託管 & GitHub Actions 自動化 CI/CD

---

## 📂 主要作品與子路由 (Projects & Routes)

本專案採用 Astro 檔案路由系統，所有功能子頁面均託管於 `src/pages/` 中：

### 1. 📱 [ExpiryRP — 物品期限管理 App](https://min-987.github.io/expiryrp/)
一個支援 iOS/Android，具備「到期提醒、家庭群組實時同步、條碼掃描、智慧分析圖表」的個人與家庭必備物品過期管理 App。
- **路徑**：`/expiryrp`
- **相關頁面**：
  - [技術支援 (Support)](https://min-987.github.io/expiryrp/support/)：解答使用問題與提供反饋渠道。
  - [隱私政策 (Privacy)](https://min-987.github.io/expiryrp/privacy/)：包含 Firebase Crashlytics 揭露與 GDPR/CCPA 合規聲明。
  - [服務條款 (Terms/EULA)](https://min-987.github.io/expiryrp/terms/)：完整中英日三語對齊的付費訂閱與免責協議。

### 2. ⏳ [Liquid Focus — 液態番茄鐘](https://min-987.github.io/liquid-focus/)
具備動態液體流動與氣泡點擊音效的沉浸式番茄工作鐘（Pomodoro）。
- **說明**：為提升開發維護效率，本專案已拆分至獨立倉庫 [liquid-focus](https://github.com/Min-987/liquid-focus)，但透過 GitHub Pages 路由配置，仍完美掛載於 `/liquid-focus` 子路徑下運作。

### 3. 🖼️ [PSD to PNG — 瀏覽器 PSD 轉檔工具](https://min-987.github.io/psd-to-png/)
100% 於瀏覽器本地端進行解析與轉檔的工具，不需上傳任何敏感圖檔至伺服器，安全且高效率。
- **路徑**：`/psd-to-png`

### 4. 📬 [Join — 聯絡與合作](https://min-987.github.io/join/)
整合 HubSpot 後台的快速聯絡表單，可提供客製化的商務合作或回饋回報。
- **路徑**：`/join`

---

## 🛠️ 開發與建置指南 (Development & Build)

本專案所有指令均在根目錄下執行：

| 指令 | 作用 |
| :--- | :--- |
| `npm install` | 安裝依賴套件 |
| `npm run dev` | 啟動本地開發伺服器（預設為 `localhost:4321`） |
| `npm run build` | 編譯靜態 HTML 至 `./dist/` 資料夾 |
| `npm run preview` | 在本地預覽打包後的網站效果 |

### ⚙️ CI/CD 自動部署
每當您將變更 Push 至 `main` 分支後，GitHub Actions 工作流會自動執行以下流程：
1. 下載依賴並編譯專案
2. 將打包好的 `dist/` 靜態檔案部署至主域名 `https://min-987.github.io/`

---

## 👤 聯絡開發者
如有任何合作或技術諮詢，請透過主頁的聯絡表單或官方電郵與我聯絡。
