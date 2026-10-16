# 🌸 GalFlow v1.12 — 视觉小说剧本与无限画布流程图整理工具

**Visual Novel Script Studio & Infinite Canvas Flowchart Organizer | 視覺小說劇本與無限畫布流程圖整理工具 | ビジュアルノベル・シナリオ＆無限キャンバスフローチャート整理ツール**

> **版本 / Version**：`v1.12`  
> **Language / 言語**：简体中文 ｜ 繁體中文 ｜ English ｜ 日本語

![image-20261014165509268](https://github.com/YZ2020CHINA/GalFlow/raw/main/image-20261014165509268.png)

## 👨‍💻 开发者与相关链接 / Developer & Links / 開発者リンク

**Author / 开发者**: Azhou (`YZ2020CHINA`) — 独立游戏开发者，Ai爱好者，使用Ai开发有用的小工具。

- **Online GalFlow / 在线体验**: https://yz2020china.github.io/GalFlow/
- **GitHub Repository / 项目地址**: https://github.com/YZ2020CHINA/GalFlow
- **GitHub Profile / 个人主页**: https://github.com/YZ2020CHINA
- **X (Twitter)**: https://x.com/johnvauk
- **Steam Store**: https://store.steampowered.com/app/4915190/_/
- **YouTube**: http://www.youtube.com/@ams-studio
- **Bilibili**: https://space.bilibili.com/404919238?spm_id_from=333.1007.0.0

# 简体中文说明 (Simplified Chinese)

**GalFlow v1.12** 是一款零依赖、单文件的视觉小说（Galgame）剧本工坊：集无限画布分支流程图、Typora 风格所见即所得 Markdown 剧本编辑、8 色自由缩放画布便签、自定义路线管理、24 色卡与路线标签联动、全资源按类型分文件夹 ZIP 打包、**三套整体主题（经典 / 液态玻璃 / 女神异闻录 P5R）× 日夜双模式**及简/繁/英/日四语切换于一体。

## 🚀 在线体验与使用

- **在线访问**：https://yz2020china.github.io/GalFlow/
- **本地使用**：下载本仓库的 `index.html`，在任意电脑、平板或手机浏览器中双击即可直接离线运行。

## 🔥 v1.12 版本全新特性

- **三套整体主题 × 日夜双模式切换**：
  - **🃏 女神异闻录 P5R 主题 (Persona 5 Royal)**：采用高对比红黑金视觉（印象空间夜间模式 / 秀尽涩谷日间模式），章节卡片、大纲项、分组框、战斗指令式分支选项条与怪盗「预告信」便签均采用**大胆非对称斜切漫画多边形剪裁设计**，连线端口化身为 45° 菱形星芒。
  - **🫧 液态玻璃主题 (Apple Liquid Glass)**：采用多层高折射毛玻璃材质，卡片重叠时呈现真实的光学模糊折射与高光反射、物理 3D 玻璃厚度切面与主题色焦散光影，所有彩色按钮、路线标签与色块均呈现**彩色半透明橡皮糖（Gummy Candy）立体质感**。
  - **🎨 经典主题 (Classic)**：沉稳清爽的标准专业工作台配色。
  - 每套主题均支持 **☀️ 日间模式 (Day)** 与 **🌙 夜间模式 (Night)** 一键切换。
- **24 色卡自由拾色与路线方框颜色联动**：
  - 编辑章节时可在「卡片主题色」下拉面板中直接选用 24 种预设色卡、调用自由拾色器或输入十六进制 HEX 色值。
  - 画布卡片左上角与左侧章节大纲目录中的「路线分类」方框颜色会**自动同步为该卡片的主题色**。
- **自定义路线管理与左侧大纲导航栏同步**：
  - 路线类型除内置「大纲、人物设定、序章、共通线、关键分支、个人线、结局」7 大分类外，支持在下拉菜单内直接**新增、重命名 (✎)、删除 (✕) 自定义路线**。
  - 新增的自定义路线会自动同步显示在左侧章节大纲导航栏「结局」标签右侧，支持一键筛选对应路线的章节。
- **画布 8 色自由缩放便签 (Sticky Notes)**：
  - 顶部工具栏「清除」按钮右侧内置「便签」创建器，支持 **8 种配色**（柠檬黄、樱花粉、晴空蓝、薄荷绿、蜜桃橙、薰衣草紫、冰川青、暖岩灰）与 **4 档预设尺寸 / 自定义宽高 (px)**，画布上支持自由拖拽移动、内联换色与右下角无级拉动缩放。
- **专注简约模式 (快捷键 `F`)**：
  - 点击画布左下角专注按钮或按键盘 `F` 键，可一键隐藏顶部工具栏、左侧大纲导航栏与右下角小地图，仅保留纯净背景与剧情卡片（按 `F` 或 `Esc` 退出）。

## ✨ 核心功能亮点



**无限画布分支流程图**：

- 支持自由拖拽平移、滚轮/双指捏合无级缩放、小地图全景导航与一键「自动整理布局」。
- 支持拖拽端口建立章节推进与多分支选择连线，支持 `Shift + 拖拽` 框选多个章节创建可视化「分组框」。



**Typora 风格 Markdown 剧本文档视图（支持所见即所得编辑）**：

- 点击顶部工具栏「文档视图」图标即可切换为左大纲/文件树（带实时关键词搜索）、右正文的沉浸式文档模式。
- 支持在文档视图中**直接点击修改**剧本总标题、章节标题、场景地点、出场人物、配乐 BGM、剧情梗概、台词正文与分支选项，所有修改实时双向同步至画布流程图。
- 底部状态栏提供 `</>` Markdown 源码视图切换与实时总词数统计。



**一键全资源分类打包（ZIP Bundle）**：

- 将工程源文件（`.galflow.json`，含节点、分组、便签与自定义路线）、汇总与单章 Markdown 剧本（`.md`）、大纲设定集（`.txt`）、所有章节 CG 与预览插画（`.png` / `.jpg` / `.svg`）、配乐清单（`.csv` / `.json`）、节点与分支数据表（`.csv`）、**可独立运行的 GalFlow v1.12 软件本体（`.html`）** 以及 **v1.12 双格式使用说明（`.md` + `.txt`）** 自动按文件类型归类到不同子文件夹并打包为 `.zip`，且文件夹与文件命名自动跟随当前界面语言。

**多步历史撤销与重做**：

- 内置 50 步历史栈（`Ctrl + Z` 还原 / `Ctrl + Y` 重做），全面覆盖卡片、便签、连线、分组、自定义路线与文档编辑。



**三套整体主题 × 日夜双模式与四语界面**：

- 支持「🎨 经典主题」「🫧 液态玻璃主题」「🃏 女神异闻录 P5R 主题」及「☀️ 日间 / 🌙 夜间」自由切换，内置**简体中文、繁體中文、English、日本語**完整本地化。

## 📦 打包（ZIP）目录结构 (v1.12)

```text
项目名称_打包工程.zip
└── 项目名称_打包工程/
    ├── 01_工程文件/               （存放 .galflow.json 完整工程源文件，含卡片、分组、便签与自定义路线）
    ├── 02_剧本文档/               （存放完整剧本文档 .md、大纲设定汇总 .txt 及「章节单篇」独立剧本）
    ├── 03_插画与预览图/            （自动提取所有章节的 CG 插画与预览图，按 .png / .jpg / .svg 存放）
    ├── 04_音频与配乐/              （生成 BGM 配乐使用清单 .csv、配乐索引 .json 及音频归档说明）
    ├── 05_分支与节点数据/          （生成章节节点总表 .csv 与分支跳转表 .csv）
    ├── GalFlow_剧本工坊.html       （自带完整 GalFlow v1.12 软件程序，双击即可在任意电脑直接运行）
    ├── GalFlow_使用说明.md         （v1.12 完整软件功能指南与快捷键说明 Markdown 文档）
    └── GalFlow_使用说明.txt        （v1.12 纯文本格式使用说明，方便直接用记事本查阅）
```

# 繁體中文說明 (Traditional Chinese)

**GalFlow v1.12** 是一款零依賴、單檔案的視覺小說（Galgame）劇本工坊：集無限畫布分支流程圖、Typora 風格所見即所得 Markdown 劇本編輯、8 色自由縮放畫布便籤、自訂路線管理、24 色卡與路線標籤連動、全資源按類型分資料夾 ZIP 打包、**三套整體主題（經典 / 液態玻璃 / 女神異聞錄 P5R）× 日夜雙模式**及簡/繁/英/日四語切換於一體。

## 🚀 線上體驗與使用

- **線上造訪**：https://yz2020china.github.io/GalFlow/
- **本地使用**：下載本倉庫的 `index.html`，在任意電腦、平板或手機瀏覽器中雙擊即可直接離線執行。

## 🔥 v1.12 版本全新特性

- **三套整體主題 × 日夜雙模式切換**：
  - **🃏 女神異聞錄 P5R 主題 (Persona 5 Royal)**：採用高對比紅黑金視覺（印象空間夜間模式 / 秀盡澀谷日間模式），章節卡片、大綱項、分組框、戰鬥指令式分支選項條與怪盜「預告信」便籤均採用**大膽非對稱斜切漫畫多邊形剪裁設計**，連線端口化身為 45° 菱形星芒。
  - **🫧 液態玻璃主題 (Apple Liquid Glass)**：採用多層高折射毛玻璃材質，卡片重疊時呈現真實的光學模糊折射與高光反射、物理 3D 玻璃厚度切面與主題色焦散光影，所有彩色按鈕、路線標籤與色塊均呈現**彩色半透明橡皮糖（Gummy Candy）立體質感**。
  - **🎨 經典主題 (Classic)**：沉穩清爽的標準專業工作台配色。
  - 每套主題均支援 **☀️ 日間模式 (Day)** 與 **🌙 夜間模式 (Night)** 一鍵切換。
- **24 色卡自由拾色與路線方框顏色連動**：
  - 編輯章節時可在「卡片主題色」下拉面板中直接選用 24 種預設色卡、呼叫自由拾色器或輸入十六進位 HEX 色值。
  - 畫布卡片左上角與左側章節大綱目錄中的「路線分類」方框顏色會**自動同步為該卡片的主題色**。
- **自訂路線管理與左側大綱導航欄同步**：
  - 路線類型除內建「大綱、人物設定、序章、共通線、關鍵分支、個人線、結局」7 大分類外，支援在下拉選單內直接**新增、重新命名 (✎)、刪除 (✕) 自訂路線**。
  - 新增的自訂路線會自動同步顯示在左側章節大綱導航欄「結局」標籤右側，支援一鍵篩選對應路線的章節。
- **畫布 8 色自由縮放便籤 (Sticky Notes)**：
  - 頂部工具列「清除」按鈕右側內建「便籤」建立器，支援 **8 種配色**與 **4 檔預設尺寸 / 自訂寬高 (px)**，畫布上支援自由拖曳移動、內聯換色與右下角無級拉動縮放。
- **專注簡約模式 (快捷鍵 `F`)**：
  - 點擊畫布左下角專注按鈕或按鍵盤 `F` 鍵，可一鍵隱藏頂部工具列、左側大綱導航欄與右下角小地圖，僅保留純淨背景與劇情卡片（按 `F` 或 `Esc` 退出）。

## ✨ 核心功能亮點



**無限畫布分支流程圖**：

- 支援自由拖曳平移、滾輪/雙指捏合無級縮放、全景小地圖導航與一鍵「自動整理佈局」。
- 支援拖曳端口建立章節推進與多分支選擇連線，支援 `Shift + 拖曳` 框選多個章節建立視覺化「分組框」。



**Typora 風格 Markdown 劇本文檔視圖（支援所見即所得編輯）**：

- 點擊頂部工具列「文檔視圖」圖示即可切換為左大綱/檔案樹（附即時關鍵字搜尋）、右正文的沉浸式文檔模式。
- 支援在文檔視圖中**直接點擊修改**劇本總標題、章節標題、場景地點、出場人物、配樂 BGM、劇情梗概、台詞正文與分支選項，所有修改即時雙向同步至畫布流程圖。
- 底部狀態列提供 `</>` Markdown 原始碼視圖切換與即時總字詞數統計。



**一鍵全資源分類打包（ZIP Bundle）**：

- 將專案原始檔（`.galflow.json`，含節點、分組、便籤與自訂路線）、彙總與單章 Markdown 劇本（`.md`）、大綱設定集（`.txt`）、所有章節 CG 與預覽插畫（`.png` / `.jpg` / `.svg`）、配樂清單（`.csv` / `.json`）、節點與分支資料表（`.csv`）、**可獨立執行的 GalFlow v1.12 軟體本體（`.html`）** 以及 **v1.12 雙格式使用說明（`.md` + `.txt`）** 自動按檔案類型歸類至不同子資料夾並打包為 `.zip`，且資料夾與檔案命名自動跟隨目前介面語言。

**多步歷史還原與重做**：

- 內建 50 步歷史堆疊（`Ctrl + Z` 還原 / `Ctrl + Y` 重做），全面涵蓋卡片、便籤、連線、分組、自訂路線與文檔編輯。



**三套整體主題 × 日夜雙模式與四語介面**：

- 支援「🎨 經典主題」「🫧 液態玻璃主題」「🃏 女神異聞錄 P5R 主題」及「☀️ 日間 / 🌙 夜間」一鍵切換，內建**簡體中文、繁體中文、English、日本語**完整本地化。

## 📦 打包（ZIP）目錄結構 (v1.12)

```text
專案名稱_打包專案.zip
└── 專案名稱_打包專案/
    ├── 01_專案檔案/               （存放 .galflow.json 完整專案原始檔，含卡片、分組、便籤與自訂路線）
    ├── 02_劇本文檔/               （存放完整劇本文檔 .md、大綱設定彙總 .txt 及「章節單篇」獨立劇本）
    ├── 03_插畫與預覽圖/            （自動提取所有章節的 CG 插畫與預覽圖，按 .png / .jpg / .svg 存放）
    ├── 04_音訊與配樂/              （產生 BGM 配樂使用清單 .csv、配樂索引 .json 及音訊歸檔說明）
    ├── 05_分支與節點資料/          （產生章節節點總表 .csv 與分支跳轉表 .csv）
    ├── GalFlow_劇本工坊.html       （隨附完整 GalFlow v1.12 軟體檔案，雙擊即可直接執行）
    ├── GalFlow_使用說明.md         （v1.12 完整軟體功能指南與快捷鍵說明 Markdown 文檔）
    └── GalFlow_使用說明.txt        （v1.12 純文字格式使用說明，方便直接用記事本查閱）
```

# English Overview

**GalFlow v1.12** is a zero-dependency, single-file Visual Novel (Galgame) Script Studio combining an infinite canvas branching flowchart, Typora-style WYSIWYG Markdown script editor, 8-color resizable sticky notes, custom route manager, 24-color palette with route badge sync, categorized ZIP project bundler, **3 overall UI themes (Classic / Apple Liquid Glass / Persona 5 Royal) × Day/Night modes**, and 4-language UI (`zh-CN` / `zh-TW` / `EN` / `JA`).

## 🚀 Online Demo & Local Usage

- **Online Access**: https://yz2020china.github.io/GalFlow/
- **Local Usage**: Download `index.html` from this repository and double-click to run it directly in any desktop, tablet, or mobile browser offline.

## 🔥 What's New in v1.12

- **3 Overall Themes × Day/Night Mode**:
  - **🃏 Persona 5 The Royal (P5R) Theme**: High-contrast Phantom Crimson, Jet Black, and Royal Gold palette (Metaverse Night & Shibuya Daylight modes) with **bold asymmetric polygon cut-out cards**, skewed comic headers, battle-command branch strips, Calling Card sticky notes, and 45° diamond star connection ports.
  - **🫧 Apple Liquid Glass Theme**: Multi-layered refractive frosted glass with optical refraction/reflection when cards overlap, physical 3D glass slab thickness, and **translucent gummy candy (彩色半透明橡皮糖)** buttons, badges, and swatches.
  - **🎨 Classic Theme**: Clean, balanced professional studio palette.
  - Every theme supports instant switching between **☀️ Day Mode (Light)** and **🌙 Night Mode (Dark)**.
- **24-Color Palette & Route Badge Color Sync**:
  - Pick from 24 curated color swatches, a native color picker, or custom HEX input inside the Card Theme Color dropdown.
  - Route badges on both canvas chapter cards and the left outline sidebar automatically synchronize with each card's theme color.
- **Custom Route In-Menu Manager & Sidebar Filter Sync**:
  - Alongside the 7 built-in route types (*Outline, Character Setting, Prologue, Common Route, Key Branch, Character Route, Ending*), you can **add, rename (✎), and delete (✕) custom routes** directly inside the Route Type dropdown menu.
  - Custom routes automatically appear to the right of *Ending* in the left sidebar filter tabs for one-click filtering.
- **8-Color Resizable Canvas Sticky Notes**:
  - Create sticky notes from the top toolbar with **8 color themes** and **4 size presets or custom W×H (px)**; freely drag, recolor, and resize them on the canvas.
- **Focus Minimalist Mode (Shortcut: `F`)**:
  - Click the bottom-left focus button or press `F` to hide all toolbars, sidebars, and the minimap, leaving only your chapter cards and canvas background (`F` or `Esc` to exit).

## ✨ Core Features



**Infinite Canvas Branching Flowchart**:

- Smooth canvas panning, mouse-wheel / two-finger pinch zooming, panoramic minimap navigation, and one-click **Auto Layout**.
- Drag output ports to connect story progressions and multi-choice branches; hold `Shift + Drag` to box-select multiple chapter cards into visual **Group Boxes**.



**Typora-Style Markdown Document View (Live WYSIWYG Editing)**:

- Switch between the infinite flowchart canvas and a two-column **Outline / File Tree (with live search) + Document Reader/Editor** with one click.
- Click any project title, chapter heading, location, character list, BGM track, plot summary, script dialogue, or branch choice directly in the document to edit in-place with instant two-way synchronization back to the flowchart canvas.
- Includes a bottom status bar with `</>` Raw Markdown Source Mode and live word/character counter.



**Categorized One-Click ZIP Project Bundler**:

- Packages all project files into a single root directory sorted into 5 categorized subfolders by file type (`01_Project_Files/`, `02_Script_Documents/`, `03_Illustrations_and_Previews/`, `04_Audio_and_BGM/`, `05_Branch_and_Node_Data/`), complete with a **standalone runnable copy of GalFlow v1.12 (`GalFlow_Script_Studio.html`)** and **v1.12 Usage Guides (`.md` + `.txt`)**. All folder and file names automatically match your active UI language.

**Multi-Step Undo & Redo**:

- 50-step history stack (`Ctrl + Z` / `Ctrl + Y`) across node edits, sticky notes, movements, connections, groups, layouts, and inline document edits.



**3 Themes × Day/Night Modes & 4 Languages**:

- Instant toggle among **Classic**, **Liquid Glass**, and **Persona 5 Royal (P5R)** themes in **Day** or **Night** mode, with full localization in **Simplified Chinese, Traditional Chinese, English, and Japanese**.

## 📦 Categorized ZIP Package Structure (v1.12)

```text
Project_Package.zip
└── Project_Package/
    ├── 01_Project_Files/              (Full .galflow.json project source file incl. stickies & custom routes)
    ├── 02_Script_Documents/           (Full_Script.md, Outline_and_Settings.txt & Chapters/ individual .md files)
    ├── 03_Illustrations_and_Previews/ (Extracted chapter CGs & preview illustrations as .png / .jpg / .svg)
    ├── 04_Audio_and_BGM/              (BGM_Usage_Manifest.csv, BGM_Index.json & Audio_Folder_Guide.txt)
    ├── 05_Branch_and_Node_Data/       (Chapters_Metadata.csv and Branch_Choices.csv tables)
    ├── GalFlow_Script_Studio.html     (Standalone GalFlow v1.12 software application file)
    ├── GalFlow_Usage_Guide.md         (Complete v1.12 Usage Guide & Shortcuts in Markdown format)
    └── GalFlow_Usage_Guide.txt        (Complete v1.12 Usage Guide & Shortcuts in plain text format)
```

# 日本語ガイド (Japanese)

**GalFlow v1.12** は、依存関係ゼロの単一ファイル型ビジュアルノベル（Galgame）シナリオ工房です。無限キャンバス分岐フローチャート、Typora風のリアルタイム編集対応Markdownビュー、8色サイズ可変付箋、カスタムルート管理、24色パレット＆ルート枠連動、ファイル種類別ZIPパッケージ出力、**3大全体テーマ（クラシック / 液体ガラス / ペルソナ5 ザ・ロイヤル P5R）× 昼夜モード**、4言語（簡体/繁体/英語/日本語）切替を搭載しています。

## 🚀 オンライン体験＆ローカル利用

- **オンラインアクセス**：https://yz2020china.github.io/GalFlow/
- **ローカル利用**：本リポジトリの `index.html` をダウンロードし、任意のPC・タブレット・スマートフォンのブラウザでダブルクリックするだけで直接起動できます。

## 🔥 v1.12 の新機能ハイライト

- **3大全体テーマ × 昼夜モード切替**：
  - **🃏 ペルソナ5 ザ・ロイヤル (P5R) テーマ**：高コントラストな赤・黒・ロイヤルゴールド配色（メメントス夜間モード／渋谷デイライト昼間モード）。チャプターカード、目次、グループ枠、コマンド式選択肢バー、怪盗団「予告状」風の付箋に**大胆な非対称コミック多角形カット**を採用し、接続ポートを45°回転ダイヤ星型に刷新。
  - **🫧 液体ガラス (Apple Liquid Glass) テーマ**：カードが重なった際の光学屈折・反射、3Dガラス厚エッジ、および**半透明グミキャンディ（彩色半透明橡皮糖）質感**のカラフルなボタン＆バッジを搭載。
  - **🎨 クラシックテーマ (Classic)**：落ち着いた標準スタジオ配色。
  - すべてのテーマで **☀️ ライトモード (Day)** と **🌙 ダークモード (Night)** の切替に対応。
- **24色パレット＆ルート枠カラー自動連動**：
  - チャプター編集時に24色パレット、自由カラーピッカー、HEXコード入力でカードテーマ色を設定でき、カード左上および左目次のルート枠カラーが自動連動します。
- **カスタムルート管理＆左目次フィルタタブ連動**：
  - 標準の7ルート種別（アウトライン、キャラ設定、プロローグ、共通ルート、重要分岐、個別ルート、エンディング）に加え、ドロップダウンメニュー内で**カスタムルートの追加・名前変更(✎)・削除(✕)**が可能。追加したカスタムルートは左目次の「エンディング」右側に自動で並び、ワンクリックで絞り込みできます。
- **8色・自由リサイズ対応キャンバス付箋 (Sticky Notes)**：
  - 上部ツールバー「クリア」ボタンの隣に「付箋」ツールを搭載。8色カラーと4種類のプリセット／カスタム幅×高さ(px)に対応し、キャンバス上で自由移動・色変更・サイズ変更が可能です。
- **集中シンプルモード (ショートカット：`F`)**：
  - 左下の集中ボタンまたは `F` キーで上部ツールバー、左サイドバー、ミニマップを一括非表示にし、カードと背景のみに集中できます（`F` または `Esc` で解除）。

## ✨ 主な機能



**無限キャンバス・分岐フローチャート**：

- 自由なドラッグ移動、ホイール／ピンチ操作による無段階ズーム、全体ミニマップナビゲーション、ワンクリック「自動整列」を搭載。
- ポートをドラッグして物語の進行や選択肢分岐を直感的に接続でき、`Shift + ドラッグ` で複数カードを範囲選択して「グループ枠」を作成可能。



**Typora風 Markdown シナリオ文書ビュー（直接編集対応）**：

- 上部ツールバーから、左サイドバー（検索バー付きアウトライン／ファイル一覧）＋右シナリオ本文の2ペイン文書モードへワンクリックで切替可能。
- 文書内の作品タイトル、章タイトル、場所、登場人物、BGM、あらすじ、セリフ本文、選択肢をクリックして**その場で直接編集**でき、変更内容は即座にフローチャート側へ双方向同期されます。
- 下部ステータスバーに `</>` Markdown ソースコードモード切替とリアルタイム文字数カウントを搭載。



**ファイル種類別自動パッケージ出力（ZIP Bundle）**：

- プロジェクト本体（`.galflow.json`、付箋・カスタムルート含む）、全体・章別シナリオ（`.md`）、アウトライン設定一覧（`.txt`）、各章のCG・プレビュー画像（`.png` / `.jpg` / `.svg`）、BGM一覧（`.csv` / `.json`）、ノード・分岐データ表（`.csv`）、**単体で起動可能な GalFlow v1.12 本体（`.html`）**、および **v1.12 使い方ガイド（`.md` + `.txt`）** を種類別サブフォルダに自動分類して `.zip` 出力します。

**マルチステップ「元に戻す / やり直し」**：

- 最大50ステップの履歴管理（`Ctrl + Z` / `Ctrl + Y`）に対応。



**3大テーマ × 昼夜モード切替＆4言語フル対応**：

- 「クラシック」「液体ガラス」「ペルソナ5 ザ・ロイヤル (P5R)」の3テーマと昼夜モード切替、および**簡体字中国語・繁体字中国語・英語・日本語**の4言語UIに完全対応。

## 📦 パッケージ（ZIP）フォルダ構造 (v1.12)

```text
作品名_パッケージ.zip
└── 作品名_パッケージ/
    ├── 01_プロジェクトファイル/     （.galflow.json プロジェクト本体ファイル・付箋＆カスタムルート含む）
    ├── 02_シナリオ文書/             （全体シナリオ文書 .md、設定一覧 .txt、「チャプター別」個別 .md）
    ├── 03_イラストとプレビュー画像/ （各章のCG・プレビュー画像を .png / .jpg / .svg で自動抽出）
    ├── 04_オーディオとBGM/          （BGM使用一覧表 .csv、BGMインデックス .json、格納ガイド）
    ├── 05_分岐とノードデータ/       （チャプターノード一覧 .csv と選択肢分岐一覧 .csv）
    ├── GalFlow_シナリオ工房.html    （GalFlow v1.12 ソフトウェア本体、ダブルクリックで即起動可能）
    ├── GalFlow_使い方ガイド.md      （v1.12 機能一覧・ショートカットキー解説 Markdown 文書）
    └── GalFlow_使い方ガイド.txt     （v1.12 テキスト形式の使い方ガイド）
```
