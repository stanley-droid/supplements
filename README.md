# 保健品服用紀錄

一個以手機介面為主的保健品服用紀錄網頁應用程式，無需安裝，直接在瀏覽器中使用。

## 功能

- **新增服用紀錄** — 快速記錄每日服用的保健品與劑量
- **保健品資料庫** — 瀏覽與搜尋常見保健品，依品牌或分類篩選
- **品牌搜尋** — 依品牌名稱查詢旗下產品
- **條碼掃描** — 掃描保健品包裝上的營養成份條碼自動填入資訊
- **手動輸入** — 手動輸入保健品名稱、劑量與服用時間
- **日期切換** — 瀏覽不同日期的服用紀錄

## 使用方式

直接用瀏覽器開啟 `index.html`，或部署至任何靜態網站服務（GitHub Pages、Netlify 等）。

## 技術

- 純 HTML / CSS / JavaScript，無框架依賴
- 手機優先設計（390×844 模擬 iPhone 尺寸）
- 使用 [Noto Sans TC](https://fonts.google.com/noto/specimen/Noto+Sans+TC) 字型
- 使用 [Remix Icon](https://remixicon.com/) 圖示庫

## 檔案結構

```
supplements/
├── index.html            # 入口，自動跳轉至主頁面
└── supplement-record.html  # 主應用程式
```
