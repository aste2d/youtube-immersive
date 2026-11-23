<div align="center">
  <h1>YouTube Immersive</h1>

  <p><strong><a href="README.md">English</a></strong> · <strong><a href="README.zh-CN.md">简体中文</a></strong> · <strong><a href="README.zh-TW.md">繁體中文</a></strong> · <strong><a href="README.ja.md">日本語</a></strong></p>

  <em>A configurable Chrome extension that reduces YouTube’s UI clutter and helps you focus on the content.</em>
</div>

## Install

[![Install from the Chrome Web Store](https://developer.chrome.com/static/docs/webstore/branding/image/206x58-chrome-web-bcb82d15b2486.png)](https://chromewebstore.google.com/detail/youtube-immersive/hngegjpdebhohjehhcbkpoaeehbijjbj)

Select **Add to Chrome**, then refresh any open YouTube tabs. If you already use the YouTube Immersive userscript, disable that script to avoid running both copies.

## If you can't install from the Chrome Web Store

[Tampermonkey](https://www.tampermonkey.net/) users can [install the userscript directly](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js) and confirm in Tampermonkey.

<details>
<summary>Tampermonkey setup by browser</summary>

### A) Chromium-based browsers

(Chrome / Edge / Brave / Opera / Vivaldi)

> Make sure **[Tampermonkey](https://www.tampermonkey.net/)** is installed first.  
> You’ll likely get it from **[Tampermonkey – Chrome Web Store](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)**

1. **Open your extensions page**  
   - At the top right, select **More (three dots) → Extensions → Manage extensions**.

2. **Find Tampermonkey → Details**  
   - Chrome users may use this direct link: **[chrome://extensions/?id=dhdgffkkebhmkfjojejmpbldmpobfkfo](chrome://extensions/?id=dhdgffkkebhmkfjojejmpbldmpobfkfo)**  
   > If internal links don’t open from GitHub, **copy and paste into the address bar**.

3. **Turn on “Developer Mode”** (usually top-right of the extensions page).

4. **Allow running userscripts on all sites** (in Tampermonkey’s **Details** page):  
   - **Site access** → **On all sites**  
   - *(Optional)* **Allow in Incognito** if you want it in private windows

5. **[Open this link to install the userscript](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** and confirm in Tampermonkey.

<br><br>

### B) 🦊 Firefox

> Make sure **[Tampermonkey](https://www.tampermonkey.net/)** is installed first.  
> You’ll likely get it from **[Tampermonkey – Get this Extension for Firefox](https://addons.mozilla.org/firefox/addon/tampermonkey/)**

1. Open **Add-ons Manager** → **Extensions**: **[about:addons](about:addons)** → **Tampermonkey** → **Permissions**  
   - Ensure it can **access data for all websites** (default)  
   - *(Optional)* **Run in Private Windows** if desired

2. **[Open this link to install the userscript](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** and confirm in Tampermonkey.

<br><br>

### C)  macOS / iOS Safari

> Make sure **[Tampermonkey](https://www.tampermonkey.net/)** (or another userscript manager) is installed **first**.  
> You’ll likely get it from **[Tampermonkey on the App Store](https://apps.apple.com/us/app/tampermonkey/id6738342400)**

1. **macOS Safari:** Safari → **Settings** → **Extensions** → Enable **Tampermonkey**  
   - Click Tampermonkey → **Edit Websites** → Allow on **All Websites** (or add **[YouTube](https://www.youtube.com/)**)  
   - *(Optional)* Allow in Private Browsing if you need it  
2. **iOS/iPadOS Safari:** Settings app → **Safari** → **Extensions** → Enable **Tampermonkey** and allow Website Access  
3. **[Open this link to install the userscript](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** and confirm in Tampermonkey.

</details>

<div align="center">
  <img src="./example.png"
       alt="YouTube Immersive Player – demo"
       width="800"
       style="max-width:100%; height:auto;">
</div>

## Features

- Remove a bunch of visual clutter
- **press R** | put shorts in the actual Player
- **press P** | Easy PiP
- **press V** | toggle the right feed
- **middle-click** the video to toggle the feed
- Customize shortcuts and playback options from the extension popup

> After installation, **[go to a YouTube video](https://www.youtube.com/watch?v=az0J8O8wRU8)** and press **V**.<br>
> On the default watch page, you can also **middle-click** the video to toggle the drawer.<br>
> It should work <mark>**except**</mark> in portrait layouts.

## Privacy

The Chrome extension runs locally on YouTube and keeps your settings on your device. See the [privacy policy](PRIVACY.md) for details.

## Configuration

Click the YouTube Immersive icon in Chrome’s toolbar to change shortcuts and player options. Userscript settings are in the script’s configuration section.

## Compatibility

- **Desktop Chrome** for the store extension. The userscript requires a compatible userscript manager.
- The userscript has been tested on Chrome and may also work in other modern browsers.
- Works only in landscape layout
- Portrait layouts are intentionally out of scope  
- Fullscreen “swipe up” is a **YouTube-native** behavior (not part of the script)

## Links

- Project home: **[GitHub Repository](https://github.com/aste2d/youtube-immersive)**
- Author: **[aste](https://github.com/aste2d)**  
- **[YouTube](https://www.youtube.com/)**  
- **[Tampermonkey](https://www.tampermonkey.net/)**

<br>

## License

YouTube Immersive Player

Copyright © 2025 aste2d

This project is licensed under the Apache License, Version 2.0.

See the LICENSE file for details.

Enjoy this project? [Buy me a coffee](https://afdian.com/a/aste2d/plan) to support its maintenance.
