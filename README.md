# 🎨 Icon 產生器（AI）

輸入描述、選擇風格，由 AI 生成 SVG 圖示，並轉成 App 常用的 PNG 尺寸。

**線上使用**：https://kftseng2oo1.github.io/icon-ai/

## 主要功能
- 文字描述或從選項挑選主題，可多選風格
- AI 直接產生 SVG（約 10–20 秒），失敗可重試
- 下載 SVG、PNG 192、PNG 512

## 技術與依賴
- 單檔 HTML PWA（`index.html` 內含全部 HTML/CSS/JS），`manifest.json` + `sw.js` 提供安裝到主畫面與離線快取。
- AI 經 `arcar.kftseng2oo1.workers.dev` 代理
- Canvas 把 SVG 轉成 PNG

## 相關 repo
- [icon](https://github.com/kftseng2oo1/icon)：幾何形狀圖示產生器（不需 AI）
