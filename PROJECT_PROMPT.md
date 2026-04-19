PROJECT_PROMPT.md
專案名稱

Vibe Coding 入門：HTML / CSS / JavaScript 網頁書

專案目標

建立一個可直接部署在 GitHub Pages 的靜態網站，內容為一本提供初學者學習 HTML、CSS、JavaScript 的網頁教材，特別針對「使用 AI（Vibe Coding）」學習程式設計的入門者。

技術限制（務必遵守）
僅使用：
HTML
CSS
JavaScript（原生）
禁止使用：
React / Vue / Angular
Node.js
任何前端框架或建置工具（如 Vite、Webpack）
所有頁面必須可：
直接用瀏覽器開啟
相容 GitHub Pages
專案結構（必須建立）
/ (root)
├─ index.html
├─ README.md
├─ assets/
│  ├─ css/
│  │  └─ style.css
│  ├─ js/
│  │  └─ main.js
│  └─ img/
├─ chapters/
│  ├─ chapter1.html
│  ├─ chapter2.html
│  ├─ chapter3.html
│  ├─ chapter4.html
│  ├─ chapter5.html
│  ├─ chapter6.html
│  ├─ chapter7.html
│  └─ chapter8.html
網站設計需求
整體風格
清爽、專業、教學導向
類似：
GitBook / Docusaurus / 線上教材
避免：
過度商業化
過多動畫
版面配置
桌機版
左側：章節導覽（sidebar）
右側：內容區
手機版
sidebar 可收合（漢堡選單）
UI 元素（必備）
首頁 Hero 區塊
章節卡片列表
上一章 / 下一章按鈕
程式碼區塊（深色背景）
響應式設計（RWD）
首頁（index.html）內容

需包含：

標題（本書名稱）
副標題（學習定位）
適合對象（初學者 / Vibe Coding）
學習路線說明
章節列表（卡片形式）
開始閱讀按鈕
章節規劃（8 章）
什麼是 Vibe Coding
為什麼要學 HTML / CSS / JS
第一個網頁（Hello World）
HTML 基本結構
CSS 基本排版
JavaScript 基本互動
用 AI 改網頁的方法
小專案：個人介紹頁
每章內容格式（統一）

每一章必須包含：

1. 本章重點
條列式整理
2. 教學說明
白話解釋
適合初學者
3. 範例程式碼
使用 <pre><code> 顯示
可直接複製
4. 常見錯誤
初學者容易犯的錯誤
5. 小練習
1～3 題簡單練習
JavaScript 功能（main.js）

需實作：

sidebar 開關（手機版）
程式碼區塊簡單高亮（可用 CSS）
章節導航（上一章 / 下一章）
CSS 設計（style.css）

需包含：

基本排版（閱讀友善）
程式碼區塊樣式（深色）
按鈕樣式
卡片設計
響應式設計（RWD）
README.md 內容

需包含：

專案介紹
技術說明
如何本地開啟
如何部署 GitHub Pages：

步驟：

push 到 GitHub
Settings → Pages
選 branch 或 /docs
開發策略（重要）

請分三階段完成：

第一階段
建立完整專案結構
完成：
index.html
chapter1
chapter2
第二階段
完成 chapter3～chapter5
優化 UI
第三階段
完成 chapter6～chapter8
完整導覽功能
輸出要求（非常重要）
請一次輸出：
所有檔案內容
每個檔案需標示：
檔名
完整內容
不要省略
不要只給片段
語言要求
繁體中文
台灣用語
教學語氣清楚
額外要求
避免過長說明
重視可讀性
初學者看得懂優先
最終目標

產出一個：

可直接放上 GitHub
可啟用 GitHub Pages
可當教材使用的網站