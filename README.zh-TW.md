<div align="center">
  <h1>YouTube 沉浸式播放器</h1>

  <p><strong><a href="README.md">English</a></strong> · <strong><a href="README.zh-CN.md">简体中文</a></strong> · <strong><a href="README.zh-TW.md">繁體中文</a></strong> · <strong><a href="README.ja.md">日本語</a></strong></p>

  <em>可自訂的 Chrome 擴充功能，減少 YouTube 介面干擾，讓你專注觀看內容。</em>
</div>

## 安裝

[![從 Chrome 線上應用程式商店安裝](https://developer.chrome.com/static/docs/webstore/branding/image/206x58-chrome-web-bcb82d15b2486.png)](https://chromewebstore.google.com/detail/youtube-immersive/hngegjpdebhohjehhcbkpoaeehbijjbj)

按一下**加到 Chrome**，再重新整理已開啟的 YouTube 分頁。如果已在使用 YouTube Immersive 使用者腳本，請停用該腳本，以免重複執行。

## 如果無法從 Chrome 線上應用程式商店安裝

已安裝 [Tampermonkey](https://www.tampermonkey.net/) 的使用者可[直接安裝使用者腳本](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)，並在 Tampermonkey 中確認。

<details>
<summary>查看各瀏覽器的 Tampermonkey 設定步驟</summary>

### A) Chromium 系列瀏覽器

（Chrome / Edge / Brave / Opera / Vivaldi）

> 請先安裝 **[Tampermonkey](https://www.tampermonkey.net/)**。  
> 通常可透過 **[Chrome 線上應用程式商店的 Tampermonkey](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)** 取得。

1. **開啟擴充功能頁面**  
   - 右上角 **更多（三點） → 擴充功能 → 管理擴充功能**。
2. **找到 Tampermonkey → 詳細資料（Details）**  
   - Chrome 使用者可直接造訪：**[chrome://extensions/?id=dhdgffkkebhmkfjojejmpbldmpobfkfo](chrome://extensions/?id=dhdgffkkebhmkfjojejmpbldmpobfkfo)**  
   > 若在 GitHub 點內部連結無效，請**複製並貼上到位址列**。
3. **開啟 “Developer Mode”**（通常在擴充頁右上角）。
4. **允許在所有網站執行使用者腳本**（Tampermonkey 詳細資料頁）：  
   - **Site access** → **On all sites**  
   - *(可選)* 如需在無痕視窗使用，請開啟 **Allow in Incognito**
5. **[開啟此連結安裝腳本](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** 並在 Tampermonkey 中確認。

<br><br>

### B) 🦊 Firefox

> 請先安裝 **[Tampermonkey](https://www.tampermonkey.net/)**。  
> 可從 **[Firefox 附加元件商店的 Tampermonkey](https://addons.mozilla.org/firefox/addon/tampermonkey/)** 取得。

1. 開啟 **附加元件管理器** → **擴充套件**：**[about:addons](about:addons)** → **Tampermonkey** → **權限（Permissions）**  
   - 確認其可**存取所有網站的資料**（預設）  
   - *(可選)* 需要在私密視窗使用時，開啟 **Run in Private Windows**
2. **[開啟此連結安裝腳本](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** 並在 Tampermonkey 中確認。

<br><br>

### C)  macOS / iOS 的 Safari

> 請先安裝 **[Tampermonkey](https://www.tampermonkey.net/)**（或其他使用者腳本管理器）。  
> 可從 **[App Store 的 Tampermonkey](https://apps.apple.com/us/app/tampermonkey/id6738342400)** 取得。

1. **macOS Safari：** Safari → **設定** → **擴充功能** → 啟用 **Tampermonkey**  
   - 點擊 Tampermonkey → **編輯網站** → 允許 **所有網站**（或加入 **[YouTube](https://www.youtube.com/)**）  
   - *(可選)* 需要在私密瀏覽使用時，開啟相應權限  
2. **iOS/iPadOS Safari：** 設定 app → **Safari** → **擴充功能** → 啟用 **Tampermonkey** 並允許網站存取  
3. **[開啟此連結安裝腳本](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** 並在 Tampermonkey 中確認。

</details>

<div align="center">
  <img src="./example.png"
       alt="YouTube Immersive Player – 範例"
       width="800"
       style="max-width:100%; height:auto;">
</div>

## 功能

- 主影片**置中**，並有淡入效果
- 避免版面抖動與視覺雜訊
- 在**右側抽屜**隱藏推薦影片
- **按下 V** 切換右側抽屜
- **滑鼠中鍵點擊影片**可切換抽屜
- 可在擴充功能的彈出視窗中自訂快速鍵和播放器選項

> 安裝後，**[前往任一 YouTube 影片](https://www.youtube.com/watch?v=az0J8O8wRU8)** 並按 **V**。<br>
> 在預設觀看頁，你也可以**中鍵點擊影片**來切換抽屜。<br>
> 除了 <mark>直向版面</mark> 外皆可正常運作。

## 隱私

Chrome 擴充功能在 YouTube 頁面上於本機執行，設定保存在你的裝置上。詳見[隱私權政策](PRIVACY.md)。

## 設定

按一下 Chrome 工具列中的 YouTube Immersive 圖示，即可變更快速鍵和播放器選項。使用者腳本的設定在腳本的設定區段。

## 相容性

- 商店版適用於**電腦版 Chrome**。使用者腳本需要相容的腳本管理器。
- 使用者腳本已在 Chrome 測試，也可在其他現代瀏覽器嘗試使用。
- **僅支援橫向**  
- 直向版面**不在腳本支援範圍**  
- 全螢幕的「上滑」是 **YouTube 原生行為**（非腳本功能）

## 連結

- 專案首頁：**[GitHub Repository](https://github.com/aste2d/youtube-immersive)**
- 作者：**[aste](https://github.com/aste2d)**  
- **[YouTube](https://www.youtube.com/)**  
- **[Tampermonkey](https://www.tampermonkey.net/)**

<br>

## 授權

YouTube Immersive Player

Copyright © 2025 aste2d

This project is licensed under the Apache License, Version 2.0.

See the LICENSE file for details.

喜歡這個專案？歡迎[請我喝杯咖啡](https://afdian.com/a/aste2d/plan)，支持後續維護。
