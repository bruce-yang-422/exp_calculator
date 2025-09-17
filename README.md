# 🎮 經驗值計算器

一個功能豐富的網頁應用程式，採用 LOGO 同色系設計，用於計算遊戲中每小時獲得的經驗值和金錢，並提供完整的資料管理功能。採用輕量化設計，無動畫效果，固定背景，提供流暢的使用體驗。

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
- **統一管理**：所有資料管理功能集中在右欄，操作更便捷

### 📋 匯出匯入
- **Excel 匯出**：將計算記錄、快捷設定匯出為 Excel 檔案
- **Excel 匯入**：從 Excel 檔案匯入資料
- **資料備份**：支援完整的資料備份與還原
- **簡化操作**：移除測試功能，專注核心匯出匯入功能

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

### 視覺設計
- **LOGO 同色系**：採用電藍、青綠、霓虹紫、亮粉紅的同色系設計
- **輕量化設計**：無動畫效果，固定背景，流暢體驗
- **高對比度**：符合 WCAG AA 標準的文字對比度
- **毛玻璃效果**：現代化的視覺效果與柔和發光邊框
- **響應式布局**：上方跨欄 + 下方兩欄的清晰結構
- **固定背景**：technology_background.jpg 提供科技感視覺紋理

## 🛠️ 技術規格

### 前端技術
- **HTML5**：語義化標記，單頁應用程式架構
- **CSS3**：響應式設計、LOGO 同色系、毛玻璃效果、CSS Grid 布局
- **JavaScript (ES6+)**：現代 JavaScript 語法，完整的資料管理功能
- **SheetJS**：Excel 檔案處理庫，支援匯出匯入功能
- **LocalStorage API**：本地資料儲存，自動備份機制
- **CSS 變數系統**：統一的 LOGO 同色系色彩管理
- **輕量化設計**：無動畫效果，固定背景，優化性能

### 瀏覽器支援
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### 資料儲存
- **LocalStorage**：本地瀏覽器儲存
- **JSON 格式**：結構化資料儲存
- **自動清理**：超過50筆記錄自動清理
- **完整備份**：支援 Excel 格式的完整資料備份
- **資料安全**：所有資料本地儲存，保護隱私

## 📱 響應式設計

### 桌面版 (≥ 900px)
- **上方跨欄**：LOGO + 網站名稱置中顯示
- **下方兩欄**：CSS Grid 布局，96% 寬度，最大 864px
  - **左欄**：計算表單 → 計算結果 → 快捷設定
  - **右欄**：歷史記錄 → 資料管理（匯出、匯入、清除）
- **統一管理**：所有資料管理功能集中在右欄

### 行動版 (≤ 900px)
- **單欄直排**：頂部 hero → 左欄內容 → 右欄內容
- **垂直排列**：所有功能垂直堆疊
- **觸控友善**：按鈕改為直向排列，避免擁擠

## 🎨 設計特色

### 🌈 LOGO 同色系設計 (Logo Consistent Colors)
- **主色系**：電藍 (#00CFFF) → 青綠 (#00FFBF) → 深電藍 (#0099CC)
- **次色系**：霓虹紫 (#9C27FF) → 亮粉紅 (#FF3ACD) → 深霓虹紫 (#7B1FA2)
- **強調色系**：青綠 (#00FFBF) → 電藍 (#00CFFF) → 深青綠 (#00E676)
- **功能色彩**：亮粉紅 (#FF3ACD) 錯誤、深粉紅 (#E91E63) 警告
- **高對比度設計**：符合 WCAG 2.1 AA 無障礙標準（4.5:1+）

### 視覺設計
- **現代化 UI**：毛玻璃效果、LOGO 同色系漸層、柔和發光邊框
- **直觀操作**：清晰的視覺層次和操作流程
- **智能色彩**：電藍→青綠→霓虹紫的漸變延伸，避免突兀對比
- **完整適配**：所有組件都遵循 LOGO 同色系設計
- **輕量化體驗**：無動畫效果，固定背景，流暢操作

### 使用者體驗
- **即時回饋**：柔和的按鈕懸停效果、成功訊息
- **輕量化設計**：無動畫效果，固定背景，流暢體驗
- **錯誤處理**：友善的錯誤提示
- **響應式設計**：完美適配各種螢幕尺寸
- **固定背景**：technology_background.jpg 抽象科技背景，不隨頁面滾動

## 🎯 色彩系統

### 🌈 LOGO 同色系
- **電藍主色**：`#00CFFF` - 主要按鈕、邊框、標題
- **青綠延伸**：`#00FFBF` - 主色變體、hover 效果
- **霓虹紫次色**：`#9C27FF` - 次要按鈕、歷史記錄邊框
- **亮粉紅延伸**：`#FF3ACD` - 次色變體、漸層效果
- **青綠強調**：`#00FFBF` - 計算結果、成功狀態
- **電藍延伸**：`#00CFFF` - 強調色變體、hover 效果

### 🎨 功能色彩
- **錯誤提示**：亮粉紅 `#FF3ACD` - 友善的錯誤提示
- **警告提示**：深粉紅 `#E91E63` - 溫和的警告訊息
- **文字顏色**：純白 `#FFFFFF` - 高對比度主文字
- **次要文字**：藍灰 `#A0AEC0` - 和諧的次文字
- **背景色系**：深藍黑 `#0D0D0D` + 深紫藍 `#1A0033` - 避免突兀對比

## 📁 檔案結構

```
exp_calculator/
├── .github/
│   └── workflows/
│       └── deploy.yml              # GitHub Actions 部署配置
├── index.html                      # 主應用程式檔案
├── exp_calculator_logo.png         # 網站 LOGO
├── technology_background.jpg       # 抽象科技背景圖
├── package.json                    # 專案配置和元數據
├── CNAME                           # 自定義域名配置（可選）
├── favicon.ico                     # 網站圖標
├── .gitignore                      # Git 忽略文件配置
└── README.md                      # 專案說明文件
```

### 檔案說明
- **index.html**：單頁應用程式，包含所有 HTML、CSS 和 JavaScript
- **exp_calculator_logo.png**：網站 LOGO，用於頂部 hero 區域
- **technology_background.jpg**：抽象科技背景圖，提供視覺紋理
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
- 遵循現有的相似色配色法
- 確保新功能符合 WCAG AA 對比度標準
- 測試新功能在不同瀏覽器的相容性
- 維持響應式設計的一致性

## 📄 授權

此專案採用 MIT 授權條款。

## 📞 聯絡資訊

如有任何問題或建議，歡迎透過 GitHub Issues 聯絡。

---

**享受計算經驗值的樂趣！** 🎮✨

---

## 🆕 最新更新

### v3.0 - LOGO 同色系輕量化重設計
- **全新視覺設計**：採用 LOGO 同色系，電藍→青綠→霓虹紫→亮粉紅的漸變延伸
- **輕量化設計**：無動畫效果，固定背景，流暢體驗
- **響應式布局**：上方跨欄 + 下方兩欄的清晰結構，96% 寬度
- **高對比度**：符合 WCAG AA 標準的文字對比度
- **固定背景**：technology_background.jpg 提供科技感視覺紋理，不隨頁面滾動
- **統一管理**：所有資料管理功能集中在右欄，操作更便捷
- **柔和效果**：降低 hover 亮度，提供舒適的視覺體驗
- **統一色彩**：所有元素遵循 LOGO 同色系設計，視覺和諧統一
