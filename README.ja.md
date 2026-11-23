<div align="center">
  <h1>YouTube Immersive Player</h1>

  <p><strong><a href="README.md">English</a></strong> · <strong><a href="README.zh-CN.md">简体中文</a></strong> · <strong><a href="README.zh-TW.md">繁體中文</a></strong> · <strong><a href="README.ja.md">日本語</a></strong></p>

  <p><strong><a href="https://chromewebstore.google.com/detail/youtube-immersive/hngegjpdebhohjehhcbkpoaeehbijjbj">Chrome ウェブストアからインストール</a></strong></p>

  <img src="./example.png"
       alt="YouTube Immersive Player – デモ"
       width="800"
       style="max-width:100%; height:auto;">
  <br>
  <em>YouTube の画面をすっきりさせ、動画に集中しやすくする Chrome 拡張機能です。</em>
</div>

<br><br>

### 特長

- メイン動画を**中央配置**、フェードイン表示  
- レイアウトのガタつきや視覚的ノイズを抑制  
- **右側ドロワー**におすすめ動画を隠す  
- **V キー**で右ドロワーを切り替え  
- 動画を**中クリック**してドロワーを切り替え  
- 拡張機能のポップアップでショートカットやプレーヤーの動作を設定

### プライバシー

Chrome 拡張機能は YouTube 上でローカルに動作し、設定を端末に保存します。詳しくは[プライバシーポリシー](PRIVACY.md)をご覧ください。

## インストール

[Chrome ウェブストアのページ](https://chromewebstore.google.com/detail/youtube-immersive/hngegjpdebhohjehhcbkpoaeehbijjbj)を開き、**Chrome に追加**を選びます。インストール後、すでに開いている YouTube のタブを再読み込みしてください。YouTube Immersive のユーザースクリプトをお使いの場合は、二重に動作しないよう、そのスクリプトを無効にしてください。

> インストール後、**[任意の YouTube 動画ページ](https://www.youtube.com/watch?v=az0J8O8wRU8)** を開き、**V** を押してください。  
> 既定の視聴ページでは、動画を**中クリック**してドロワーを切り替えることもできます。  
> <mark>縦長レイアウト</mark> を除き、基本的に動作します。

### ユーザースクリプトを使う場合

[Tampermonkey](https://www.tampermonkey.net/) をお使いの方は、[ユーザースクリプトを直接インストール](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)し、Tampermonkey で確認してください。Tampermonkey の設定が必要な場合は、下記のお使いのブラウザの手順をご覧ください。

#### A) Chromium ベースのブラウザ

（Chrome / Edge / Brave / Opera / Vivaldi）

> まず **[Tampermonkey](https://www.tampermonkey.net/)** をインストールしてください。  
> 一般的には **[Chrome Web Store の Tampermonkey](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)** から入手できます。

1. **拡張機能ページを開く**  
   - 右上の **その他（三点） → 拡張機能 → 拡張機能を管理**。
2. **Tampermonkey → 詳細（Details）を開く**  
   - Chrome ユーザーは次のリンクを直接開けます：**[chrome://extensions/?id=dhdgffkkebhmkfjojejmpbldmpobfkfo](chrome://extensions/?id=dhdgffkkebhmkfjojejmpbldmpobfkfo)**  
   > GitHub から内部リンクが開かない場合は、**アドレスバーにコピー＆ペースト**してください。
3. **“Developer Mode” をオン**（拡張機能ページ右上あたり）
4. **すべてのサイトでユーザースクリプトを許可**（Tampermonkey の詳細ページ）：  
   - **Site access** → **On all sites**  
   - *(任意)* **Allow in Incognito** を有効化するとシークレットウィンドウでも動作
5. **[このリンクからスクリプトをインストール](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** し、Tampermonkey で確認します。

<br><br>

#### B) 🦊 Firefox

> まず **[Tampermonkey](https://www.tampermonkey.net/)** をインストールしてください。  
> **[Firefox アドオンの Tampermonkey](https://addons.mozilla.org/firefox/addon/tampermonkey/)** から入手できます。

1. **アドオンマネージャー** → **拡張機能**：**[about:addons](about:addons)** → **Tampermonkey** → **Permissions**  
   - **すべての Web サイトのデータにアクセス**できることを確認（既定）  
   - *(任意)* **Run in Private Windows** を有効化するとプライベートウィンドウでも動作
2. **[このリンクからスクリプトをインストール](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** し、Tampermonkey で確認します。

<br><br>

#### C)  macOS / iOS の Safari

> まず **[Tampermonkey](https://www.tampermonkey.net/)**（または他のユーザースクリプトマネージャ）をインストールしてください。  
> **[App Store の Tampermonkey](https://apps.apple.com/us/app/tampermonkey/id6738342400)** から入手できます。

1. **macOS Safari：** Safari → **設定** → **機能拡張** → **Tampermonkey** を有効化  
   - Tampermonkey → **Web サイトを編集（Edit Websites）** → **すべての Web サイト**を許可（あるいは **[YouTube](https://www.youtube.com/)** を追加）  
   - *(任意)* **プライベートブラウズ**での許可を有効化  
2. **iOS/iPadOS Safari：** 設定アプリ → **Safari** → **機能拡張** → **Tampermonkey** を有効化し、Web サイトアクセスを許可  
3. **[このリンクからスクリプトをインストール](https://raw.githubusercontent.com/aste2d/youtube-immersive/main/youtube-immersive-player.user.js)** し、Tampermonkey で確認します。

<br><br><br>

---

<br>

### 設定

Chrome のツールバーにある YouTube Immersive のアイコンをクリックすると、ショートカットやプレーヤーの動作を変更できます。ユーザースクリプトの設定はスクリプト内の設定欄にあります。

### 互換性

- ストア版は**パソコン版 Chrome**向けです。ユーザースクリプトには対応するスクリプトマネージャーが必要です。
- ユーザースクリプトは Chrome で動作を確認しています。他のモダンブラウザでも使用できる場合があります。
- **横向きのみ動作**  
- 縦長レイアウトは**対象外**  
- 全画面での「上方向スワイプ」は **YouTube のネイティブ機能**（本スクリプトの動作ではありません）

### リンク

- プロジェクト：**[GitHub Repository](https://github.com/aste2d/youtube-immersive)**
- 作者：**[aste](https://github.com/aste2d)**  
- **[YouTube](https://www.youtube.com/)**  
- **[Tampermonkey](https://www.tampermonkey.net/)**

<br>

## ライセンス

YouTube Immersive Player 

Copyright © 2025 aste2d

This project is licensed under the Apache License, Version 2.0. 

See the LICENSE file for details. 

このプロジェクトを気に入っていただけたら、[コーヒーを一杯おごって](https://afdian.com/a/aste2d/plan)開発を応援していただけるとうれしいです。
