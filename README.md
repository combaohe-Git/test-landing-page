# test-landing-page# Test-landing-page

這是一個專為社群導流設計的輕量級落地頁（Landing Page），旨在透過精美的 Open Graph 卡片預覽，提高從抖音、LINE 或其他社群平台跳轉至個人聯絡方式（微信/LINE）的點擊率。

## 功能特色
- **社群預覽優化**：透過正確的 Open Graph 標籤，讓網址在聊天軟體中自動顯示頭像與自訂標題。
- **一鍵導流**：整合「複製 ID」功能與「二維碼展示」，降低用戶添加好友的門檻。
- **輕量且快速**：純 HTML/CSS/JS 實作，部署於 Vercel，加載速度極快。

## 專案結構
- `index.html`: 核心頁面代碼，包含跳轉邏輯與社群元標籤。
- `avatar.jpg`: 你的個人頭像（用於顯示在社群預覽卡片上）。
- `qrcode.jpg`: 你的二維碼圖片。

## 使用說明
1. 修改 `index.html` 中的微信/LINE ID。
2. 替換根目錄下的 `avatar.jpg` 與 `qrcode.jpg` 為你的真實圖片。
3. 推送 (Commit) 更新至 GitHub，Vercel 將自動觸發重新部署。

## 部署環境
- 代管平台：Vercel
- 框架：原生 HTML5 / JavaScript
