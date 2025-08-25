# Podcast 首圖裁切器（1:1｜≥1400×1400）

一個用於 **Podcast 封面裁切與輸出** 的純前端工具。固定 **1:1** 比例，支援輸出 **至少 1400×1400**（也可到 3000×3000），整個流程皆在瀏覽器本機完成，不上傳圖片。

👉 線上 Demo（GitHub Pages）請見本 repo 的 Pages 設定完成後的網址。https://lulumi7788.github.io/podcast-cover-cropper/

## 功能
- 拖拉/選擇圖片，固定 1:1 裁切
- 伸縮、移動、旋轉、重置
- 指定輸出邊長（預設 1400，最小 1400）
- 輸出 PNG / JPEG / WEBP（可調整品質）
- 即時預覽、下載成品、嘗試複製到剪貼簿
- 完全在瀏覽器端運行（隱私友善）

## 使用
1. 開啟 `index.html`，或部署到 GitHub Pages 後直接使用。
2. 拖放或選擇圖片 → 調整裁切 → 右側設定尺寸/格式/品質 → 下載。

## 開發
- 純前端、單檔 `index.html`，以 CDN 引入 [Cropper.js](https://github.com/fengyuanchen/cropperjs)
- 無打包流程與依賴，直接開檔可用

## 授權
MIT License © 2025
