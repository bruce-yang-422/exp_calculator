# 🎮 經驗值計算器

一個功能豐富的網頁應用程式，用於計算遊戲中每小時獲得的經驗值和金錢，並提供資料管理功能。

## 🚀 快速開始

### 線上使用
[![Deploy to GitHub Pages](https://github.com/bruce-yang-422/exp_calculator/workflows/Deploy%20to%20GitHub%20Pages/badge.svg)](https://bruce-yang-422.github.io/exp_calculator)

**立即體驗**：[https://bruce-yang-422.github.io/exp_calculator](https://bruce-yang-422.github.io/exp_calculator)

### 本地運行
```bash
# 克隆專案
git clone https://github.com/bruce-yang-422/exp_calculator.git
cd exp_calculator

# 啟動本地伺服器
python -m http.server 8000

# 在瀏覽器中訪問 http://localhost:8000
```

## ✨ 功能特色

### 📊 核心功能
- **經驗值計算**：根據總經驗值、遊戲時間計算每小時經驗值
- **金錢計算**：同時計算每小時獲得的金錢
- **時間輸入**：支援時、分、秒的詳細時間輸入
- **即時結果**：計算完成後立即顯示結果

### ⚡ 快捷功能
- **角色名稱快捷**：儲存常用角色名稱，快速選擇
- **掛網地點快捷**：儲存常用掛網地點，快速選擇
- **一鍵填入**：點擊快捷項目即可自動填入表單

### 📈 資料管理
- **計算歷史**：自動儲存最近50筆計算記錄
- **歷史檢視**：顯示最近15筆記錄的詳細資訊
- **記錄刪除**：可單獨刪除不需要的歷史記錄

### 📋 匯出匯入
- **Excel 匯出**：將計算記錄、快捷設定匯出為 Excel 檔案
- **Excel 匯入**：從 Excel 檔案匯入資料
- **資料備份**：支援完整的資料備份與還原

### 📱 分享功能
- **結果複製**：一鍵複製格式化的計算結果到剪貼簿
- **格式化輸出**：包含角色、地點、時間等完整資訊
- **跨平台分享**：支援各種通訊軟體分享

## 🚀 使用方法

### 基本計算
1. 輸入角色名稱（必填）
2. 輸入掛網地點（選填）
3. 輸入總經驗值
4. 輸入獲得金錢
5. 輸入遊戲時間（時、分、秒）
6. 點擊「計算每小時經驗值」按鈕

### 快捷設定
1. 在「角色名稱快捷」區域輸入角色名稱
2. 點擊「新增」按鈕儲存
3. 之後可直接點擊快捷項目快速填入

### 資料管理
- **匯出 Excel**：點擊「📤 匯出 Excel」按鈕下載資料
- **匯入 Excel**：點擊「📥 匯入 Excel」按鈕選擇檔案
- **清除資料**：點擊「🗑️ 清除資料」按鈕清空所有資料

### 主題切換
1. 點擊右上角的「主題」按鈕
2. 從下拉選單中選擇喜歡的主題：
   - **🌿 平靜簡約**：適合長時間使用和專業環境
   - **⚡ 活力明亮**：適合創意工作和激發靈感
   - **💼 專業時尚**：適合夜間使用和現代感需求
   - **🌟 霓虹活力**：適合遊戲環境和未來感展示
3. 主題會自動保存，下次訪問時自動應用

## 🛠️ 技術規格

### 前端技術
- **HTML5**：語義化標記
- **CSS3**：響應式設計、漸層背景、毛玻璃效果、CSS 變數系統
- **JavaScript (ES6+)**：現代 JavaScript 語法
- **SheetJS**：Excel 檔案處理庫
- **LocalStorage API**：本地資料儲存
- **CSS 變數系統**：完整的四主題色彩管理
- **動畫系統**：平滑的過渡效果和視覺回饋

### 瀏覽器支援
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### 資料儲存
- **LocalStorage**：本地瀏覽器儲存
- **JSON 格式**：結構化資料儲存
- **自動清理**：超過50筆記錄自動清理
- **主題偏好**：自動保存用戶選擇的主題
- **完整備份**：支援 Excel 格式的完整資料備份

## 📱 響應式設計

### 桌面版
- 雙欄式佈局
- 左側：計算表單和快捷設定
- 右側：計算結果和歷史記錄

### 行動版
- 單欄式佈局
- 垂直排列所有功能
- 觸控友善的按鈕設計

## 🎨 設計特色

### 🌈 四主題系統
- **🌿 平靜簡約**：基於色彩心理學的專業簡約風格，軟藍+米色調
- **⚡ 活力明亮**：充滿創意和積極能量的明亮風格，黃+綠+橙色調
- **💼 專業時尚**：現代專業的深色風格，藍紫+冷灰+青綠色調
- **🌟 霓虹活力**：未來感的科技風格，電藍+霓虹紫+亮綠色調
- **主題選擇器**：清單式主題切換，小巧精緻
- **高對比度設計**：所有主題都符合 WCAG 2.1 AA 無障礙標準（7:1+）

### 視覺設計
- **現代化 UI**：毛玻璃效果、漸層背景、CSS 變數系統
- **直觀操作**：清晰的視覺層次和操作流程
- **智能色彩**：每個主題都有專屬的色彩心理學設計
- **完整適配**：所有組件都完全適配四主題系統

### 使用者體驗
- **即時回饋**：按鈕懸停效果、成功訊息
- **流暢動畫**：平滑的過渡效果（0.3s）
- **錯誤處理**：友善的錯誤提示
- **主題記憶**：自動保存用戶主題偏好
- **完整覆蓋**：瀏覽器視窗背景也跟隨主題變化

## 🎯 主題特色

### 🌿 平靜簡約 (Calm Minimal)
- **主色調**：軟藍 `#AEC6CF` + 米色 `#EAE3D2`
- **背景**：純白 `#FFFFFF` + 淺灰 `#F5F5F5`
- **適用場景**：專業工作、長時間使用、需要專注的環境

### ⚡ 活力明亮 (Energetic Bright)
- **主色調**：黃色 `#FFD54F` + 綠色 `#81C784` + 橙色 `#FFB74D`
- **背景**：純白 `#FFFFFF` + 淺黃 `#FFF8E1`
- **適用場景**：創意工作、激發靈感、活潑的環境

### 💼 專業時尚 (Sleek Professional)
- **主色調**：藍紫 `#5C6BC0` + 冷灰 `#90A4AE` + 青綠 `#26A69A`
- **背景**：純黑 `#000000` + 深灰 `#121212`
- **適用場景**：專業環境、夜間使用、現代感需求

### 🌟 霓虹活力 (Vibrant Neon)
- **主色調**：電藍 `#00BFFF` + 霓虹紫 `#9C27B0` + 亮綠 `#00E676`
- **背景**：深黑 `#0D0D0D` + 深灰 `#1A1A1A`
- **適用場景**：遊戲環境、創意展示、未來感需求

## 📁 檔案結構

```
exp_calculator/
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions 部署配置
├── index.html              # 主應用程式檔案
├── package.json            # 專案配置和元數據
├── CNAME                   # 自定義域名配置（可選）
├── favicon.ico             # 網站圖標
├── .gitignore              # Git 忽略文件配置
└── README.md              # 專案說明文件
```

### 檔案說明
- **index.html**：單頁應用程式，包含所有 HTML、CSS 和 JavaScript
- **package.json**：專案元數據，用於 GitHub Pages 識別
- **deploy.yml**：GitHub Actions 自動部署配置
- **CNAME**：自定義域名配置文件（可選）
- **favicon.ico**：網站圖標文件

## 🔧 安裝與執行

### 本地執行
1. 下載專案檔案
2. 使用瀏覽器開啟 `index.html`
3. 開始使用！

### Python 本地伺服器（推薦）
```bash
# 在專案目錄中執行
python -m http.server 8000
# 然後在瀏覽器中訪問 http://localhost:8000
```

### GitHub Pages 部署

#### 方法一：自動部署（推薦）
1. **Fork 此專案**到您的 GitHub 帳戶
2. **啟用 GitHub Pages**：
   - 進入專案 Settings
   - 滾動到 "Pages" 部分
   - Source 選擇 "GitHub Actions"
3. **推送代碼**：
   ```bash
   git clone https://github.com/bruce-yang-422/exp_calculator.git
   cd exp_calculator
   # 修改 package.json 中的 repository 和 homepage URL
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```
4. **自動部署**：GitHub Actions 會自動部署到 `https://bruce-yang-422.github.io/exp_calculator`

#### 方法二：手動部署
1. **啟用 GitHub Pages**：
   - 進入專案 Settings
   - 滾動到 "Pages" 部分
   - Source 選擇 "Deploy from a branch"
   - Branch 選擇 "main"
2. **訪問網站**：`https://bruce-yang-422.github.io/exp_calculator`

#### 自定義域名（可選）
1. 在專案根目錄創建 `CNAME` 文件
2. 在文件中輸入您的域名（例如：`your-domain.com`）
3. 在域名服務商處設置 CNAME 記錄指向 `bruce-yang-422.github.io`

### 其他平台部署
- **Netlify**：直接拖拽專案資料夾到 Netlify
- **Vercel**：連接 GitHub 倉庫自動部署
- **任何靜態網頁伺服器**：上傳所有檔案即可

## 📊 資料格式

### Excel 匯出格式
- **計算記錄工作表**：包含所有計算歷史
- **角色快捷工作表**：儲存的角色名稱
- **掛網地點快捷工作表**：儲存的掛網地點

### LocalStorage 結構
```javascript
{
  "calculationHistory": [...],      // 計算記錄陣列
  "characterShortcuts": [...],     // 角色快捷陣列
  "locationShortcuts": [...]       // 地點快捷陣列
}
```

## 🚨 注意事項

### 資料安全
- 所有資料儲存在瀏覽器本地
- 清除瀏覽器資料會導致資料遺失
- 建議定期匯出 Excel 備份

### 瀏覽器相容性
- 需要支援 ES6+ 的現代瀏覽器
- 需要支援 LocalStorage 功能
- 需要支援 File API（匯入功能）

## 🤝 貢獻

歡迎提交 Issue 和 Pull Request 來改善這個專案！

### 開發建議
- 保持程式碼簡潔易讀
- 遵循現有的命名慣例
- 測試新功能在不同瀏覽器的相容性

## 📄 授權

此專案採用 MIT 授權條款。

## 📞 聯絡資訊

如有任何問題或建議，歡迎透過 GitHub Issues 聯絡。

---

**享受計算經驗值的樂趣！** 🎮✨
