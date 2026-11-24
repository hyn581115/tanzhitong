# 攤智通｜AI 攤商行銷助手（Hugo 專案）

## 本機預覽
1. 安裝 Hugo（建議使用目前的 Extended 版本）。
2. 在此專案資料夾開啟終端機。
3. 執行 `hugo server`
4. 瀏覽器開啟 http://localhost:1313/

## 建置正式網站
執行 `hugo`，產出的靜態網站會放在 `public/`。

## 部署前請修改
- `hugo.toml` 的 `baseURL`
- `layouts/index.html` 內 canonical、Open Graph 與 Twitter 圖片網址中的 `https://YOUR-SITE-URL/`
- 部署到 Netlify 時，可直接將專案連接 Git 儲存庫，Build command 設為 `hugo`，Publish directory 設為 `public`。

## 專案結構
- `hugo.toml`：網站基本設定、繁體中文與 SEO 基礎設定
- `layouts/index.html`：首頁與攤智通互動展示介面
- `static/images/logo.png`：品牌 Logo
- `static/images/og-image.png`：社群分享圖
- `static/favicon.svg`：網站圖示
- `static/robots.txt`：搜尋引擎爬蟲規則
- `content/`：保留作為未來內容擴充位置（目前不啟用部落格）

## 功能狀態提醒
目前文案、海報企劃、社群貼文、短影音腳本及行銷顧問功能，仍是原型內的前端範例模板，不是真正連線的 AI 服務；攤位資料也尚未寫入雲端資料庫。
