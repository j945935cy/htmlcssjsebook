# Vibe Coding 入門：HTML / CSS / JavaScript 網頁書

一本專為完全初學者設計的網頁開發教材，特別針對「使用 AI（Vibe Coding）」學習程式設計的入門者。

## 專案介紹

本教材包含 8 個章節，帶你從零認識 HTML、CSS、JavaScript，並學會如何用 AI 工具加速學習。學完後，你將能夠建立一個完整的個人介紹頁面並部署到 GitHub Pages。

### 章節內容

| 章節 | 標題 | 主題 |
|------|------|------|
| 第 1 章 | 什麼是 Vibe Coding？ | 入門概念、AI 工具介紹 |
| 第 2 章 | 為什麼要學 HTML/CSS/JS | 三種技術的分工與角色 |
| 第 3 章 | 第一個網頁 Hello World | HTML 文件骨架、VS Code 設定 |
| 第 4 章 | HTML 基本結構 | 常用標籤：標題、段落、連結、圖片、清單 |
| 第 5 章 | CSS 基本排版 | 選擇器、Box Model、Flexbox、RWD |
| 第 6 章 | JavaScript 基本互動 | 變數、函式、DOM 操作、事件監聽 |
| 第 7 章 | 用 AI 改網頁的方法 | 提問技巧、解 Bug 策略、開發者工具 |
| 第 8 章 | 小專案：個人介紹頁 | 整合實作 + 部署到 GitHub Pages |

## 技術說明

本專案僅使用：
- **HTML**：頁面結構
- **CSS**：樣式與響應式設計（RWD）
- **JavaScript（原生）**：互動功能

**不使用任何框架或建置工具**，所有頁面可直接用瀏覽器開啟，完全相容 GitHub Pages。

## 專案結構

```
/
├── index.html          ← 首頁
├── README.md           ← 本說明文件
├── assets/
│   ├── css/
│   │   └── style.css   ← 全站共用樣式
│   ├── js/
│   │   └── main.js     ← 共用 JavaScript（sidebar、進度條等）
│   └── img/            ← 圖片資源
└── chapters/
    ├── chapter1.html   ← 什麼是 Vibe Coding？
    ├── chapter2.html   ← 為什麼要學 HTML/CSS/JS
    ├── chapter3.html   ← 第一個網頁 Hello World
    ├── chapter4.html   ← HTML 基本結構
    ├── chapter5.html   ← CSS 基本排版
    ├── chapter6.html   ← JavaScript 基本互動
    ├── chapter7.html   ← 用 AI 改網頁的方法
    └── chapter8.html   ← 小專案：個人介紹頁
```

## 如何本地開啟

1. 下載或 clone 本專案：
   ```bash
   git clone https://github.com/你的帳號/htmlcssjsebook.git
   ```

2. 進入專案資料夾，雙擊 `index.html` 即可在瀏覽器開啟。

   或在 VS Code 中安裝 **Live Server** 插件，右鍵 `index.html` 選「Open with Live Server」。

> 本專案不需要 Node.js 或任何伺服器環境。

## 如何部署到 GitHub Pages

### 步驟一：建立 GitHub Repository

1. 登入 [GitHub](https://github.com)
2. 點右上角 **+** → **New repository**
3. 取名（例如：`htmlcssjsebook`），選 **Public**
4. 點 **Create repository**

### 步驟二：上傳檔案

**方法 A：透過網頁介面上傳**
1. 在 repository 頁面點 **Add file** → **Upload files**
2. 把所有檔案（含資料夾結構）拖曳上去
3. 點 **Commit changes**

**方法 B：使用 Git 命令列**
```bash
cd 你的專案資料夾
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/你的帳號/htmlcssjsebook.git
git push -u origin main
```

### 步驟三：啟用 GitHub Pages

1. 進入 repository 的 **Settings**
2. 左側選單找到 **Pages**
3. Source 選 **Deploy from a branch**
4. Branch 選 **main**，資料夾選 **/ (root)**
5. 按 **Save**

等待約 1~2 分鐘後，你的網站將部署在：
```
https://你的帳號.github.io/htmlcssjsebook/
```

## 授權

本教材採用 [MIT License](https://opensource.org/licenses/MIT)，歡迎自由使用與分享。
