<div align="center">
  <h1>YouTube 沉浸式播放器</h1>

  <p><strong><a href="README.md">English</a></strong> · <strong><a href="README.zh-CN.md">简体中文</a></strong> · <strong><a href="README.zh-TW.md">繁體中文</a></strong> · <strong><a href="README.ja.md">日本語</a></strong></p>

  <em>一个可配置的 Chrome 扩展，减少 YouTube 界面干扰，帮你专注观看内容。</em>
</div>

## 安装

[![从 Chrome 应用商店安装](https://developer.chrome.com/static/docs/webstore/branding/image/206x58-chrome-web-bcb82d15b2486.png)](https://chromewebstore.google.com/detail/youtube-immersive/hngegjpdebhohjehhcbkpoaeehbijjbj)

点击**添加至 Chrome**，然后刷新已打开的 YouTube 标签页。如果已经在用 YouTube Immersive 用户脚本，请停用该脚本，以免重复运行。

## 如果无法从 Chrome 应用商店安装

已安装 [Tampermonkey](https://www.tampermonkey.net/) 的用户可[直接安装用户脚本](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)，并在 Tampermonkey 中确认。

<details>
<summary>查看各浏览器的 Tampermonkey 设置步骤</summary>

### A) Chromium 内核浏览器

（Chrome / Edge / Brave / Opera / Vivaldi）

> 请先安装 **[Tampermonkey](https://www.tampermonkey.net/)**。  
> 一般可通过 **[Chrome 应用商店的 Tampermonkey](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)** 获取。

1. **打开扩展程序页面**  
   - 右上角 **更多（三点） → 扩展程序 → 管理扩展程序**。
2. **找到 Tampermonkey → 详情（Details）**  
   - Chrome 用户可直接访问：**[chrome://extensions/?id=dhdgffkkebhmkfjojejmpbldmpobfkfo](chrome://extensions/?id=dhdgffkkebhmkfjojejmpbldmpobfkfo)**  
   > 如果在 GitHub 上点击内部链接无效，请**复制并粘贴到地址栏**。
3. **开启 “Developer Mode”**（通常位于扩展页右上角）。
4. **允许在所有站点运行用户脚本**（Tampermonkey 的详情页）：  
   - **Site access** → **On all sites**  
   - *(可选)* 如需在隐身窗口使用，请开启 **Allow in Incognito**
5. **[打开此链接安装脚本](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** 并在 Tampermonkey 中确认。

<br><br>

### B) 🦊 Firefox

> 请先安装 **[Tampermonkey](https://www.tampermonkey.net/)**。  
> 可从 **[Firefox 附加组件商店的 Tampermonkey](https://addons.mozilla.org/firefox/addon/tampermonkey/)** 获取。

1. 打开 **附加组件管理器** → **扩展**：**[about:addons](about:addons)** → **Tampermonkey** → **权限（Permissions）**  
   - 确保其可**访问所有网站的数据**（默认）  
   - *(可选)* 如需在隐私窗口使用，开启 **Run in Private Windows**
2. **[打开此链接安装脚本](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** 并在 Tampermonkey 中确认。

<br><br>

### C)  macOS / iOS 的 Safari

> 请先安装 **[Tampermonkey](https://www.tampermonkey.net/)**（或其他用户脚本管理器）。  
> 可从 **[App Store 的 Tampermonkey](https://apps.apple.com/us/app/tampermonkey/id6738342400)** 获取。

1. **macOS Safari：** Safari → **设置** → **扩展** → 启用 **Tampermonkey**  
   - 点击 Tampermonkey → **编辑网站** → 允许 **所有网站**（或添加 **[YouTube](https://www.youtube.com/)**）  
   - *(可选)* 如需在私密浏览中使用，请开启相应权限  
2. **iOS/iPadOS Safari：** 系统 **设置** → **Safari** → **扩展** → 启用 **Tampermonkey** 并允许网站访问  
3. **[打开此链接安装脚本](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** 并在 Tampermonkey 中确认。

</details>

<div align="center">
  <img src="./example.png"
       alt="YouTube Immersive Player – 示例"
       width="800"
       style="max-width:100%; height:auto;">
</div>

## 功能

- 主视频**居中**，并带有淡入效果
- 避免布局抖动与视觉杂乱
- 在**右侧抽屉**隐藏推荐视频
- **按 V** 切换右侧抽屉
- **鼠标中键点击视频**可切换抽屉
- 可在扩展弹窗里自定义快捷键和播放器选项

> 安装后，**[打开任意 YouTube 视频](https://www.youtube.com/watch?v=az0J8O8wRU8)** 并按 **V**。<br>
> 在默认观看页面，你也可以**鼠标中键点击视频**来切换抽屉。<br>
> 除了 <mark>竖屏布局</mark> 外都应能正常工作。

## 隐私

Chrome 扩展在 YouTube 页面上本地运行，设置保存在你的设备上。详情见[隐私政策](PRIVACY.md)。

## 设置

点击 Chrome 工具栏中的 YouTube Immersive 图标，可修改快捷键与播放器选项。用户脚本的选项位于脚本的配置区。

## 兼容性

- 商店版适用于**桌面版 Chrome**。用户脚本需要兼容的脚本管理器。
- 用户脚本已在 Chrome 测试，也可在其他现代浏览器尝试使用。
- 仅适用于横向布局
- 竖屏布局**不在脚本适配范围**  
- 全屏下的“上滑”是 **YouTube 原生行为**（非脚本功能）

## 链接

- 项目主页：**[GitHub 仓库](https://github.com/aste2d/youtube-immersive)**
- 作者：**[aste](https://github.com/aste2d)**  
- **[YouTube](https://www.youtube.com/)**  
- **[Tampermonkey](https://www.tampermonkey.net/)**

<br>

## 许可证

YouTube Immersive Player

Copyright © 2025 aste2d

This project is licensed under the Apache License, Version 2.0.

See the LICENSE file for details.

喜欢这个项目？欢迎[请我喝杯咖啡](https://afdian.com/a/aste2d/plan)，支持后续维护。
