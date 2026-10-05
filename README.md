# ACA Learning Model Website

ACA 教學方法論單頁網站專案。

## 專案結構

```text
aca-learning-model-website/
├─ index.html
├─ README.md
└─ assets/
   ├─ css/
   │  └─ style.css
   ├─ js/
   │  └─ main.js
   └─ images/
      ├─ hero-illustration.webp
      ├─ aca-journey.webp
      ├─ aca-cover.webp
      ├─ logo-aca.svg
      ├─ favicon.svg
      ├─ icon-alignment.svg
      ├─ icon-challenge.svg
      └─ icon-action.svg
```

## 本機預覽

最簡單的方式是直接開啟 `index.html`。

若瀏覽器對本機資源有限制，可在專案目錄執行：

```bash
python -m http.server 8000
```

再開啟：

```text
http://localhost:8000
```

## 部署

這是一個純靜態網站，可以直接放到：

- GitHub Pages
- Azure Static Web Apps
- Azure Storage Static Website
- Cloudflare Pages
- Netlify / Vercel
- 任何可提供 HTML/CSS/JS 的 Web Server

## 設計方向

首頁維持原始 ACA 視覺：白底、台北城市與成熟成人學習者插畫、A/C/A 三色系與清楚的三階段流程。
後半段則延伸為完整的方法論網站內容，包含：

- 為什麼需要 ACA
- Alignment / Challenge / Action 詳解
- ACA 與傳統 Follow-along Lab 的差異
- ACA 循環
- 真實課程應用範例
- 適用對象
- 學習成果
- 方法論宣言
- FAQ

## 修改重點

主要文字都在 `index.html`。
視覺樣式在 `assets/css/style.css`。
互動（手機選單、滾動動畫、導覽高亮、回到頂端）在 `assets/js/main.js`。
