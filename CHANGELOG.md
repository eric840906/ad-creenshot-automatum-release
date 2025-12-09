# Changelog

All notable changes to AD Screenshot Automatum will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [v2.2.0] - 2025-12-09

### Changes since v2.1.0

#### Commits


**✨ Features:**
- feat(US3): 新增視覺化回饋與錯誤處理強化 (4bee234)
- feat: 新增視覺化廣告位置注入按鈕圖示 (e7c170f)
- feat: 「注入這裡」按鈕改為僅顯示圖示 (6032b8f)
- feat: 「注入這裡」按鈕改為僅顯示圖示 (adbebf3)
- feat: 新增視覺化廣告位置選擇功能 (User Story 1 - MVP) (9f5f725)

**🐞 Bug Fixes:**
- fix: 修正視覺化廣告放置的 CSS 選擇器生成與替換邏輯 (aaab43e)

**⚡ Improvements:**
- refactor: mobile-inread 與 DV360 改為手動注入模式 (9619fa4)
- improve user experience (bc4dc34)

**📝 Other Changes:**
- v2.2.0 (648289c)
- docs: 更新 CLAUDE.md 新增視覺化廣告位置選擇功能說明 (3ba345d)
- docs: 新增視覺化廣告位置選擇功能規格文件 (252b8f9)


## [v2.1.0] - 2025-12-04

### Changes since v2.0.0

#### Commits


**✨ Features:**
- feat(US3): 確保舊配置相容性，忽略已棄用欄位執行 (097d387)
- feat(US2): 從配置表單移除已棄用欄位 (9aa4435)
- feat(US1): 移除無頭模式UI，強制所有測試在可見除錯模式運行 (dfdbd8b)

**🐞 Bug Fixes:**
- 🐞 fix: issue that filter cleans selected items (c2f50e2)

**📝 Other Changes:**
- v2.1.0 (ca58f20)
- docs: 新增功能規格文件與版本更新 (98dd326)
- v2.0.1 (2789b26)


## [v2.0.0] - 2025-12-01

### Changes since v1.8.0

#### Commits


**✨ Features:**
- remove next config features (df9120e)
- feat: 新增 PNG 圖示與 CSS 樣式至截圖按鈕 (Screenshot Button Icon & Styling) (b609ee5)
- feat: Add CSS styling for PNG icon in screenshot button (d19c381)
- feat: 整合偵錯控制到自動化工作流程 (9893675)
- feat: 完成按鈕注入和事件監聽的完整整合 (370f5f2)
- feat: 實作手動截圖擷取核心功能 (T010-T025) (e1c3136)
- feat: 實作非干擾性按鈕放置邏輯 (T043-T057) (8cf333e)
- feat: 新增偵錯控制管理器基礎骨架 (T006-T009) (b9c5aa0)

**🐞 Bug Fixes:**
- fix: Fix debug controls hiding and Safari toolbar overlay composition (3d8a6c7)
- 🐞 fix: crash when closing browser (c8371b7)
- fix: Pass configIndex and configTotal in sequential and parallel config execution (33a0800)

**📝 Other Changes:**
- v2.0.0 (19730b6)
- add icon (f3501e5)
- inject camera button earlier (ba27729)
- implement instance cleaning (1e76a1c)
- migrate base64 (fe5dd9f)
- done planning (24f8ba3)


## [v1.8.0] - 2025-11-14

### Changes since v1.7.1

#### Commits


**✨ Features:**
- ✨feature: inline editing implementation (b5019ec)

**📝 Other Changes:**
- v1.8.0 (de9cc69)


## [v1.7.1] - 2025-11-14

### Changes since v1.6.1

#### Commits


**✨ Features:**
- ✨feature: native save as feature (b793993)
- feat: add campaign tab filtering to results page (baacc3f)
- feat: add campaign tabs UI for config organization (668a2fc)
- feat: add campaign management backend API (8473253)
- docs: add campaign tabs feature specification and tests (b10fbf1)

**🐞 Bug Fixes:**
- 🐞 fix: 1. fix undefined toast. 2.add config name validation to prevent duplicate name (28d159d)

**📝 Other Changes:**
- v1.7.1 (acbcad8)
- v1.7.0 (028d141)
- organize ui codes (a266492)


## [v1.6.1] - 2025-11-06

### Changes since v1.6.0

#### Commits


**🐞 Bug Fixes:**
- 🐞 fix: config 敘述修正 (5582e1a)

**📝 Other Changes:**
- v1.6.1 (acfe304)


## [v1.6.0] - 2025-11-06

### Changes since v1.5.0

#### Commits


**✨ Features:**
- feat: 為 DV360 模式新增橫幅隱藏支援 (8f10d88)
- feat: 將橫幅關閉機制從點擊改為 CSS 隱藏 (06756b7)

**📝 Other Changes:**
- v1.6.0 (173a7e9)
- docs: 新增橫幅 CSS 隱藏功能的規格文件 (eda80b5)
- docs: 更新橫幅隱藏配置文件 (ee02790)


## [v1.5.0] - 2025-10-31

### Changes since v1.4.2

#### Commits


**✨ Features:**
- ✨feature: update config list (5b8033e)
- ✨feature: 新增 android 相關 icon (a078ac6)
- feat: 新增 Android Chrome 框架支援 (部分完成) (8b97733)

**🐞 Bug Fixes:**
- fix: 修正 Chrome 框架組合的兩個關鍵問題 (d5b6ad0)
- fix: 新增 frame_type 欄位至 Joi 驗證架構 (b4e0728)

**⚡ Improvements:**
- ✨feature: update config list (5b8033e)

**📝 Other Changes:**
- v1.5.0 (9036c97)
- 修改介面說明 (dba9399)
- remove oudated workflow (9025202)


## [v1.4.2] - 2025-10-29

### Changes since v1.4.1

#### Commits


**🐞 Bug Fixes:**
- fix workflow (49c7798)

**📝 Other Changes:**
- v1.4.2 (ccca29d)


## [v1.4.0] - 2025-10-27

### Changes since v1.3.1

#### Commits


**✨ Features:**
- feat: 實作 Safari 底部工具列合成邏輯 (f1279db)
- feat: 新增 Safari 底部工具列模板基礎結構 (e2de092)

**📝 Other Changes:**
- docs: 加入 Safari 底部工具列功能規格文件 (21570a3)
- docs: 更新專案文件與版本至 v1.4.0 (eaf1dae)


## [v1.3.1] - 2025-10-23

### Changes since v1.3.0

#### Commits


**✨ Features:**
- ✨增加設備尺寸調整功能 (d1d38d8)
- ✨refactor plans

**📝 Other Changes:**
- 1.3.1 (730875c)
- 📝文件：完成應用層 JSDoc 註解（T087） (3d2cfdc)
- 📝文件：完成領域層 JSDoc 註解（T086） (09ebf21)
- 📚文件：完成開發者文件（T083-T085） (08cb678)
- 🏗️重構：完成清潔架構遷移與單元測試實作（Phase 1-3, 5-7） (5d37e56)


## [v1.3.0] - 2025-10-21

### Changes since v1.2.9

#### Commits


**✨ Features:**
- ✨feature: implement public release (cd71e13)

**📝 Other Changes:**
- v1.3.0 (3159728)

