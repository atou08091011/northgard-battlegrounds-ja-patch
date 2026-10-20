# Northgard Battlegrounds デモ版日本語化パッチ

### 北境战场 Demo 日语补丁 · Japanese Language Patch

---

## 日本語

この度はダウンロードいただき、ありがとうございます！

『Northgard Battlegrounds Demo』に日本語を追加するパッチです。インストーラーを実行するだけで、ゲーム内のテキストを日本語で表示できます。

### 機能

- 日本語テキスト約 1,150 件をゲームに書き込み（メニュー・チュートリアル・カードやスキルの説明など）
- 日本語の字形（ひらがな・カタカナ・漢字）をゲームのフォント図集に焼き込み、文字化け（四角い枠）を防止
- インストール後、ゲームの言語が自動で「日本語」に切り替わり、起動直後から日本語で遊べます
- 簡体中文・English など他の言語はそのまま残ります（ゲーム内 Options › Language でいつでも切替可能）
- 「アンインストール」で、元の状態に完全復元できます

### 使い方

1. インストーラーを実行します（ゲームフォルダは自動検出されます）
2. 「インストール」ボタンをクリック
3. ゲームを起動すると、最初から日本語で表示されます

> **所要時間について（重要）**
> インストールには **約 4〜6 分** かかります。これは不具合ではなく、**フォントのベイク処理**に時間がかかるためです。
> ゲーム付属の中国語フォントには日本語の仮名・漢字が含まれていないため、パッチ側で字形ごとに SDF（距離場付きビットマップ）を生成し、
> ゲームのフォントアトラスに書き戻しています。数百個の字形レンダリングと 100MB 超のリソースファイルの書き戻しが発生するため、
> どうしても数分かかります。進捗バーが 10% を超えたあたりがベイク工程です。**そのままお待ちください（中断しないでください）。**

### ゲームがアップデートされた場合

ゲームが更新されると、以前のインストール時に作られたバックアップは古いバージョンのものになります。
その状態で「アンインストール」を押すと、古いファイルが書き戻され、ゲーム内の言語一覧が消えることがあります。

本インストーラーはこれを自動で検出します。古いバックアップは `～.stale_日時` に退避され、
**復元は行われません**（ゲームはそのまま日本語で遊べる状態が維持されます）。

完全に公式の状態に戻したい場合は、Steam で
**ゲームを右クリック → プロパティ → インストール済みファイル → ゲームファイルの整合性を確認**
を実行してください。その後、もう一度インストーラーで「インストール」すれば問題ありません。

### 翻訳について

翻訳に至らない点がございましたら、Steam のレビュー・コメントよりお知らせください。頂いたご意見は順次反映して更新してまいります。

それでは、良いゲームを！

---

## 简体中文

感谢大家的下载！

本补丁为《Northgard Battlegrounds Demo》添加日语支持，运行安装器即可在游戏内使用日语。

### 功能

- 写入日文文本约 1,150 条（菜单、教程、卡牌与技能说明等）
- 日语字形（假名 / 汉字）全部烘焙进游戏字体图集，杜绝方框乱码
- 安装完成后自动切换游戏语言为「日本語」，进游戏直接就是日语
- 不影响简体中文 / English 等其他语言，游戏内 Options › Language 随时可切回
- 支持一键卸载，自动从备份完整还原

### 使用方法

1. 运行安装器（游戏目录自动检测，也可手动浏览）
2. 点击「安装」
3. 启动游戏，直接就是日语

> **关于安装耗时（请先看一眼）**
> 安装大约需要 **4〜6 分钟**，这是正常的，不是卡死——时间基本都花在**字体烘焙**上。
> 游戏自带的中文字体里没有日文假名和日文汉字，补丁必须逐个字形渲染成 SDF（带距离场的位图），
> 再写回游戏的字体图集；要处理数百个字形、并回写上百 MB 的资源文件，所以需要几分钟。
> 进度条走到 10% 之后就是烘焙阶段，**请耐心等待，中途不要关闭或中断**。

### 游戏更新之后

游戏更新后，之前安装时留下的备份就属于旧版本了。此时若点「卸载还原」，旧文件被写回，
游戏内的语言列表可能会整个消失。

安装器会自动检测这种情况：旧的备份会被归档成 `～.stale_时间戳`，并且**不执行还原**
（游戏会保持可正常游玩的状态，不会损坏）。

若想彻底恢复到官方原版，请在 Steam 里
**右键游戏 → 属性 → 已安装文件 → 验证游戏文件完整性**，
之后重新运行安装器安装一次即可。

### 翻译反馈

若有翻译不到位的地方，欢迎在 Steam 评论下留言给我，我会更新修正。

祝大家游戏愉快！

---

## English

Thanks for downloading!

This patch adds Japanese language support to *Northgard Battlegrounds Demo*. Just run the installer and play in Japanese.

### Features

- Writes ~1,150 Japanese text entries into the game (menus, tutorials, card & skill descriptions, etc.)
- Bakes all Japanese glyphs (kana & kanji) into the game's font atlas — no more tofu boxes
- Automatically switches the game language to Japanese — the game starts in Japanese
- Other languages (Simplified Chinese, English, …) are untouched; switch anytime via Options › Language
- One-click uninstall with full restore from backup

### How to use

1. Run the installer (the game folder is auto-detected, or browse manually)
2. Click "Install"
3. Launch the game — it's in Japanese from the start

> **About the install time (please read)**
> Installation takes about **4-6 minutes**. This is not a hang — nearly all of it is **glyph baking**.
> The game's built-in Chinese font contains no Japanese kana or kanji, so the patch renders every needed
> glyph into an SDF (signed distance field) bitmap and writes it back into the game's font atlas.
> That means hundreds of glyphs plus a 100+ MB resource rewrite, which simply takes a few minutes.
> Once the progress bar passes 10%, it is baking — **please wait and do not interrupt it.**

### After a game update

Once the game updates, the backups left behind by an earlier install belong to an older version.
Clicking "Uninstall" in that state would write those old files back, and the in-game language
list can disappear entirely.

The installer detects this automatically: stale backups are archived as `~.stale_<timestamp>`
and **nothing is restored** (the game stays playable and undamaged).

To get back to a clean official install, use Steam:
**Right-click the game → Properties → Installed Files → Verify integrity of game files**,
then simply run this installer again.

### Translation feedback

If anything reads awkwardly in Japanese, please leave a comment on the Steam page — I'll keep updating and improving it.

Enjoy the game!

---

## 版权与许可证 / Copyright and License

本补丁内嵌一份 **Noto Sans SC** 字体的子集化版本（用于向游戏字体图集注入日文假名与汉字字形）。
该字体遵循 **SIL Open Font License 1.1**，版权声明为
`Copyright 2014-2021 Adobe (http://www.adobe.com/), with Reserved Font Name 'Source'`。
完整许可证与版权声明见同目录的 **`LICENSE_NotoSansSC.txt`**。

This patch embeds a subset of the **Noto Sans SC** font (used to bake Japanese
kana and kanji glyphs into the game's font atlas). It is licensed under the
**SIL Open Font License 1.1**, `Copyright 2014-2021 Adobe
(http://www.adobe.com/), with Reserved Font Name 'Source'`. The full license
and copyright notice are provided in **`LICENSE_NotoSansSC.txt`** in the same folder.
