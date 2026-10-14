# 🌸 GalFlow v1.0 — 视觉小说剧本与无限画布流程图整理工具

**Visual Novel Script Studio & Infinite Canvas Flowchart Organizer | 視覺小說劇本與無限畫布流程圖整理工具 | ビジュアルノベル・シナリオ＆無限キャンバスフローチャート整理ツール**

> **版本 / Version**：`v1.0`  
> Language / 言語**：**简体中文｜ 繁體中文｜ English｜ 日本語

---

![image-20261014165509268](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014165509268.png)

##  开发者与相关链接 / Developer & Links / 開発者リンク

**Author / 开发者**: Azhou (`YZ2020CHINA`) — 独立游戏开发者，Ai爱好者，使用Ai开发有用的小工具。

- **Online GalFlow / 在线体验**: https://yz2020china.github.io/GalFlow/

- **X (Twitter)**: https://x.com/johnvauk
- **Steam Store**: https://store.steampowered.com/app/4915190/_/
- **YouTube**: http://www.youtube.com/@ams-studio
- **Bilibili**: https://space.bilibili.com/404919238?spm

---



# 简体中文说明 (Simplified Chinese)



**GalFlow v1.0** 是一款零依赖、单文件的视觉小说（Galgame）剧本工坊：集无限画布分支流程图、Typora 风格所见即所得 Markdown 剧本编辑、全资源按类型分文件夹 ZIP 打包、日夜双主题及简/繁/英/日四语切换于一体。

## 🚀 在线体验与使用

- **在线访问**：https://yz2020china.github.io/GalFlow/
- **本地使用**：下载本仓库的 `index.html`，在任意电脑、平板或手机浏览器中双击即可直接运行。

## ✨ v1.0 核心功能亮点



![image-20261014165836799](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014165836799.png)

**无限画布分支流程图**：

- 支持自由拖拽平移、滚轮/双指无级缩放、全屏小地图全景导航与一键「自动整理布局」。

- 支持拖拽圆点建立章节推进与多分支选择连线，支持 `Shift + 拖拽` 框选多个章节创建可视化「分组框」。

  

![image-20261014170037780](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170037780.png)

**Typora 风格 Markdown 剧本文档视图（支持所见即所得编辑）**：

- 点击顶部工具栏「文档视图」图标即可切换为左大纲/文件树（带实时关键词搜索）、右正文的沉浸式文档模式。
- 支持在文档视图中**直接点击修改**剧本总标题、章节标题、场景地点、出场人物、配乐 BGM、剧情梗概、台词正文与分支选项，所有修改实时双向同步至画布流程图。
- 底部状态栏提供 `</>` Markdown 源码视图切换与实时总词数统计。



![image-20261014170136324](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170136324.png)

**一键全资源分类打包（ZIP Bundle）**：

- 将工程源文件（`.galflow.json`）、汇总与单章 Markdown 剧本（`.md`）、大纲设定集（`.txt`）、所有章节 CG 与预览插画（`.png` / `.jpg` / `.svg`）、配乐清单（`.csv` / `.json`）、节点与分支数据表（`.csv`）、**可独立运行的 GalFlow 软件本体（`.html`）** 以及 **双格式使用说明（`.md` + `.txt`）** 自动按文件类型归类到不同子文件夹并打包为 `.zip`，且文件夹与文件命名自动跟随当前界面语言。



**多步历史撤销与重做**：

- 内置 50 步历史栈（`Ctrl + Z` 还原 / `Ctrl + Y` 重做），全面覆盖卡片增删、移动、连线、分组与文档编辑。



![image-20261014170521411](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170521411.png)

**日夜双主题与四语界面**：

- 支持「暖白日间」与「夜间暗色」一键切换，内置**简体中文、繁體中文、English、日本語**完整本地化。

## 📦 打包（ZIP）目录结构

```text
项目名称_打包工程.zip
└── 项目名称_打包工程/
    ├── 01_工程文件/               （.galflow.json 完整工程源文件，可随时重新打开编辑）
    ├── 02_剧本文档/               （完整剧本文档 .md、大纲设定汇总 .txt 及「章节单篇」独立剧本）
    ├── 03_插画与预览图/            （自动提取所有章节的 CG 插画与预览图，按 .png / .jpg / .svg 存放）
    ├── 04_音频与配乐/              （生成 BGM 配乐使用清单 .csv、配乐索引 .json 及音频归档说明）
    ├── 05_分支与节点数据/          （生成章节节点总表 .csv 与分支跳转表 .csv）
    ├── GalFlow_剧本工坊.html       （自带完整 GalFlow 软件程序，双击即可在任意电脑直接运行）
    ├── GalFlow_使用说明.md         （软件功能指南与快捷键说明 Markdown 文档）
    └── GalFlow_使用说明.txt        （纯文本格式使用说明，方便直接用记事本查阅）
```

---



# 繁體中文說明 (Traditional Chinese)



**GalFlow v1.0** 是一款零依賴、單檔案的視覺小說（Galgame）劇本工坊：集無限畫布分支流程圖、Typora 風格所見即所得 Markdown 劇本編輯、全資源按類型分資料夾 ZIP 打包、日夜雙主題及簡/繁/英/日四語切換於一體。

## 🚀 線上體驗與使用

- **線上造訪**：https://yz2020china.github.io/GalFlow/
- **本地使用**：下載本倉庫的 `index.html`，在任意電腦、平板或手機瀏覽器中雙擊即可直接執行。

## ✨ v1.0 核心功能亮點



![image-20261014165836799](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014165836799.png)

**無限畫布分支流程圖**：

- 支援自由拖曳平移、滾輪/雙指無級縮放、全景小地圖導航與一鍵「自動整理佈局」。
- 支援拖曳圓點建立章節推進與多分支選擇連線，支援 `Shift + 拖曳` 框選多個章節建立視覺化「分組框」。



![image-20261014170037780](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170037780.png)

**Typora 風格 Markdown 劇本文檔視圖（支援所見即所得編輯）**：

- 點擊頂部工具列「文檔視圖」圖示即可切換為左大綱/檔案樹（附即時關鍵字搜尋）、右正文的沉浸式文檔模式。
- 支援在文檔視圖中**直接點擊修改**劇本總標題、章節標題、場景地點、出場人物、配樂 BGM、劇情梗概、台詞正文與分支選項，所有修改即時雙向同步至畫布流程圖。
- 底部狀態列提供 `</>` Markdown 原始碼視圖切換與即時總字詞數統計。



![image-20261014170136324](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170136324.png)

**一鍵全資源分類打包（ZIP Bundle）**：

- 將專案原始檔（`.galflow.json`）、彙總與單章 Markdown 劇本（`.md`）、大綱設定集（`.txt`）、所有章節 CG 與預覽插畫（`.png` / `.jpg` / `.svg`）、配樂清單（`.csv` / `.json`）、節點與分支資料表（`.csv`）、**可獨立執行的 GalFlow 軟體本體（`.html`）** 以及 **雙格式使用說明（`.md` + `.txt`）** 自動按檔案類型歸類至不同子資料夾並打包為 `.zip`，且資料夾與檔案命名自動跟隨目前介面語言。



**多步歷史還原與重做**：

- 內建 50 步歷史堆疊（`Ctrl + Z` 還原 / `Ctrl + Y` 重做），全面涵蓋卡片增刪、移動、連線、分組與文檔編輯。



![image-20261014170521411](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170521411.png)

**日夜雙主題與四語介面**：

- 支援「暖白日間」與「夜間暗色」一鍵切換，內建**簡體中文、繁體中文、English、日本語**完整本地化。

## 📦 打包（ZIP）目錄結構

```text
專案名稱_打包專案.zip
└── 專案名稱_打包專案/
    ├── 01_專案檔案/               （.galflow.json 完整專案原始檔，可隨時重新開啟編輯）
    ├── 02_劇本文檔/               （完整劇本文檔 .md、大綱設定彙總 .txt 及「章節單篇」獨立劇本）
    ├── 03_插畫與預覽圖/            （自動提取所有章節的 CG 插畫與預覽圖，按 .png / .jpg / .svg 存放）
    ├── 04_音訊與配樂/              （產生 BGM 配樂使用清單 .csv、配樂索引 .json 及音訊歸檔說明）
    ├── 05_分支與節點資料/          （產生章節節點總表 .csv 與分支跳轉表 .csv）
    ├── GalFlow_劇本工坊.html       （隨附完整 GalFlow 軟體檔案，雙擊即可直接執行）
    ├── GalFlow_使用說明.md         （軟體功能指南與快捷鍵說明 Markdown 文檔）
    └── GalFlow_使用說明.txt        （純文字格式使用說明，方便直接用記事本查閱）
```

---



# English Overview



**GalFlow v1.0** is a zero-dependency, single-file Visual Novel (Galgame) Script Studio combining an infinite canvas branching flowchart, Typora-style WYSIWYG Markdown script editor, categorized ZIP project bundler, Day/Night themes, and 4-language UI (`zh-CN` / `zh-TW` / `EN` / `JA`).

## 🚀 Online Demo & Local Usage

- **Online Access**: https://yz2020china.github.io/GalFlow/
- **Local Usage**: Download `index.html` from this repository and double-click to run it directly in any desktop, tablet, or mobile browser offline.

## ✨ v1.0 Key Features



![image-20261014165836799](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014165836799.png)

**Infinite Canvas Branching Flowchart**:

- Smooth canvas panning, mouse-wheel / pinch zooming, panoramic minimap navigation, and one-click **Auto Layout**.
- Drag output ports to connect story progressions and multi-choice branches; hold `Shift + Drag` to box-select multiple chapter cards into visual **Group Boxes**.



![image-20261014170037780](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170037780.png)

**Typora-Style Markdown Document View (Live WYSIWYG Editing)**:

- Switch between the infinite flowchart canvas and a two-column **Outline / File Tree (with live search) + Document Reader/Editor** with one click.
- Click any project title, chapter heading, location, character list, BGM track, plot summary, script dialogue, or branch choice directly in the document to edit in-place with instant two-way synchronization back to the flowchart canvas.
- Includes a bottom status bar with `</>` Raw Markdown Source Mode and live word/character counter.



![image-20261014170136324](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170136324.png)

**Categorized One-Click ZIP Project Bundler**:

- Packages all project files into a single root directory sorted into 5 categorized subfolders by file type (`01_Project_Files/`, `02_Script_Documents/`, `03_Illustrations_and_Previews/`, `04_Audio_and_BGM/`, `05_Branch_and_Node_Data/`), complete with a **standalone runnable copy of GalFlow (`GalFlow_Script_Studio.html`)** and **Usage Guides (`.md` + `.txt`)**. All folder and file names automatically match your active UI language.



**Multi-Step Undo & Redo**:

- 50-step history stack (`Ctrl + Z` / `Ctrl + Y`) across node edits, movements, connections, groups, layouts, and inline document edits.



![image-20261014170521411](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170521411.png)

**Day / Night Themes & 4 Languages**:

- Instant toggle between **Warm Light** and **Night Dark** themes, with full localization in **Simplified Chinese, Traditional Chinese, English, and Japanese**.

## 📦 Categorized ZIP Package Structure

```text
Project_Package.zip
└── Project_Package/
    ├── 01_Project_Files/              (Full .galflow.json project source file)
    ├── 02_Script_Documents/           (Full_Script.md, Outline_and_Settings.txt & Chapters/ individual .md files)
    ├── 03_Illustrations_and_Previews/ (Extracted chapter CGs & preview illustrations as .png / .jpg / .svg)
    ├── 04_Audio_and_BGM/              (BGM_Usage_Manifest.csv, BGM_Index.json & Audio_Folder_Guide.txt)
    ├── 05_Branch_and_Node_Data/       (Chapters_Metadata.csv and Branch_Choices.csv tables)
    ├── GalFlow_Script_Studio.html     (Standalone GalFlow software application file)
    ├── GalFlow_Usage_Guide.md         (Complete Usage Guide & Shortcuts in Markdown format)
    └── GalFlow_Usage_Guide.txt        (Complete Usage Guide & Shortcuts in plain text format)
```

---



# 日本語ガイド (Japanese)



**GalFlow v1.0** は、依存関係ゼロの単一ファイル型ビジュアルノベル（Galgame）シナリオ工房です。無限キャンバス分岐フローチャート、Typora風のリアルタイム編集対応Markdownビュー、ファイル種類別ZIPパッケージ出力、昼夜テーマ、4言語（簡体/繁体/英語/日本語）切替を搭載しています。

## 🚀 オンライン体験＆ローカル利用

- **オンラインアクセス**：https://yz2020china.github.io/GalFlow/
- **ローカル利用**：本リポジトリの `index.html` をダウンロードし、任意のPC・タブレット・スマートフォンのブラウザでダブルクリックするだけで直接起動できます。

## ✨ v1.0 主な機能



![image-20261014165836799](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014165836799.png)

**無限キャンバス・分岐フローチャート**：

- 自由なドラッグ移動、ホイール／ピンチ操作による無段階ズーム、全体ミニマップナビゲーション、ワンクリック「自動整列」を搭載。
- ドットをドラッグして物語の進行や選択肢分岐を直感的に接続でき、`Shift + ドラッグ` で複数カードを範囲選択して「グループ枠」を作成可能。



![image-20261014170037780](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170037780.png)

**Typora風 Markdown シナリオ文書ビュー（直接編集対応）**：

- 上部ツールバーから、左サイドバー（検索バー付きアウトライン／ファイル一覧）＋右シナリオ本文の2ペイン文書モードへワンクリックで切替可能。
- 文書内の作品タイトル、章タイトル、場所、登場人物、BGM、あらすじ、セリフ本文、選択肢をクリックして**その場で直接編集**でき、変更内容は即座にフローチャート側へ双方向同期されます。
- 下部ステータスバーに `</>` Markdown ソースコードモード切替とリアルタイム文字数カウントを搭載。



![image-20261014170136324](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170136324.png)

**ファイル種類別自動パッケージ出力（ZIP Bundle）**：

- プロジェクト本体（`.galflow.json`）、全体・章別シナリオ（`.md`）、アウトライン設定一覧（`.txt`）、各章のCG・プレビュー画像（`.png` / `.jpg` / `.svg`）、BGM一覧（`.csv` / `.json`）、ノード・分岐データ表（`.csv`）、**単体で起動可能な GalFlow 本体（`.html`）**、および**使い方ガイド（`.md` + `.txt`）**を種類別サブフォルダに自動分類して `.zip` 出力します。フォルダ名・ファイル名は選択中の表示言語に自動で合わせられます。



**マルチステップ「元に戻す / やり直し」**：

- 最大50ステップの履歴管理（`Ctrl + Z` / `Ctrl + Y`）に対応。



![image-20261014170521411](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014170521411.png)

**昼夜テーマ切替＆4言語フル対応**：

- ウォームライト／ナイトダークのテーマ切替、および**簡体字中国語・繁体字中国語・英語・日本語**の4言語UIに完全対応。

## 📦 パッケージ（ZIP）フォルダ構造

```text
作品名_パッケージ.zip
└── 作品名_パッケージ/
    ├── 01_プロジェクトファイル/     （.galflow.json プロジェクト本体ファイル）
    ├── 02_シナリオ文書/             （全体シナリオ文書 .md、設定一覧 .txt、「チャプター別」個別 .md）
    ├── 03_イラストとプレビュー画像/ （各章のCG・プレビュー画像を .png / .jpg / .svg で自動抽出）
    ├── 04_オーディオとBGM/          （BGM使用一覧表 .csv、BGMインデックス .json、格納ガイド）
    ├── 05_分岐とノードデータ/       （チャプターノード一覧 .csv と選択肢分岐一覧 .csv）
    ├── GalFlow_シナリオ工房.html    （GalFlow ソフトウェア本体、ダブルクリックで即起動可能）
    ├── GalFlow_使い方ガイド.md      （機能一覧・ショートカットキー解説 Markdown 文書）
    └── GalFlow_使い方ガイド.txt     （テキスト形式の使い方ガイド）
```

---

