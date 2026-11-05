# 國家漫畫博物館影展專題網站 (National Taiwan Museum of Comics Exhibition)

本專案為國家漫畫博物館影展專題的響應式網頁（RWD）示範，採用語意化 HTML5 與獨立切分的 CSS 檔案架構，完整支援 SEO 設定、CSS Grid 排版與行動裝置閱讀體驗。

## 📁 專案目錄結構

```text
├── index.html                  # 主頁面 (SEO Meta / Header / Grid Main / Sidebar / Pagination)
├── pages/                      # 分頁目錄
│   ├── history.html            # 歷史與場域
│   └── exhibitions.html        # 展覽與影展
├── css/                        # 樣式檔案匣
│   ├── base.css                # 全域基礎變數與重設
│   ├── layout.css              # 排版、網格系統與主要架構
│   └── components.css          # 卡片、按鈕、RWD與分頁元件
└── images/                     # 圖片檔案匣
    ├── hero.jpg
    ├── zone-a.jpg
    └── zone-b.jpg