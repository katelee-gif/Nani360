# Nani 學習 360

一個互動式的學習管理系統，專為教師和學生設計。

## ✨ 功能特色

- 📚 **知識點列表**：瀏覽和管理各章節的知識點，支援手風琴式展開/收合
- 📝 **派發測驗**：選擇學生並快速派發測驗任務
- 📊 **學生分析報表**：查看學生的學習數據和各科報表
- 🎨 **現代化 UI**：美觀且易於使用的響應式介面設計

## 🛠️ 技術架構

- HTML5 語義化標籤
- CSS3 (Flexbox 佈局、自定義動畫)
- Vanilla JavaScript (無框架依賴)
- SVG 可縮放向量圖示

## 🚀 快速開始

1. 開啟 `index.html` 即可開始使用
2. 系統會自動導向知識點列表頁面

## 📁 頁面結構

```
index.html (首頁 - 自動跳轉)
    ↓
knowledge-list.html (知識點列表)
    ├── 派發測驗彈窗
    ↓
success.html (派發成功)
    ↓
student-report.html (學生分析報表)
```

## 📄 主要檔案

- `knowledge-list.html` / `knowledge-list.css` - 知識點列表頁面
- `success.html` / `success.css` - 派發成功頁面
- `student-report.html` / `student-report.css` - 學生分析報表頁面
- `image/` - 圖示和圖片資源

## 🌐 部署

本專案可以直接部署到 GitHub Pages 或任何靜態網站託管服務。

### GitHub Pages 部署
1. 推送專案到 GitHub
2. 在倉庫設置中啟用 GitHub Pages
3. 選擇 main 分支作為來源
4. 網站將在 `https://[username].github.io/[repo-name]/` 上線

## 📝 License

© 2025 Nani 學習 360. All rights reserved.
