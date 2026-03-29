# 🌸 小資東京迪士尼富士山7日遊 行程手冊 PWA

## 部署到 GitHub Pages

1. 建立一個新的 GitHub Repository（例如：`japan-trip-2025`）
2. 將以下檔案全部上傳：
   ```
   index.html
   manifest.json
   sw.js
   icons/
     icon-180.png
     icon-512.png
     icon-192.png
   ```
3. 進入 Repository Settings → Pages → Source 選 `main` branch → Save
4. 網址將會是：`https://你的帳號.github.io/japan-trip-2025/`

## 手機加入主畫面（iOS）

1. 用 Safari 開啟網址
2. 點擊下方分享按鈕 📤
3. 選「加入主畫面」
4. 即可離線使用！

## 功能
- ✅ 6個分頁：首頁、行程（7天切換）、交通、餐食、住宿、提醒
- ✅ Apple PWA 完整標籤（standalone模式）
- ✅ Service Worker 離線快取
- ✅ Safe Area / Notch 支援
- ✅ iOS 安裝引導
