# 操作日誌

> 格式：`## [YYYY-MM-DD] 操作類型 | 標題`
> 最新記錄在最上方。

---

## [2026-11-21] ingest | World Archery 競技項目頁面
- 來源：https://www.worldarchery.sport/sport/disciplines
- 新增頁面：1 頁
  - `wiki/competitions/競技項目總覽.md`
- 更新頁面：2 頁
  - `wiki/overview.md`（新增八種競技項目總表、連結至競技項目總覽）
  - `wiki/index.md`（頁面數 9→10、素材數 5→6、新增條目）
- 關鍵發現：
  - WA 官方承認 **8 種**競技項目（過去 wiki 只提到 4 種）：定靶、室內、野外、殘障、3D、飛行、滑雪、越野
  - 定靶射箭歷史：最早有記錄的比賽為 **1583 年**英國芬斯伯里公園
  - 世界錦標賽（World Archery Championships）首屆 **1931 年**，每兩年一屆
  - 室內世界錦標賽已於 2018 年停辦，改為 **Indoor Archery World Series** 大眾賽事
  - 野外射箭距離 5–60m，分「已標記」與「未標記」距離兩種形式

---

## [2026-11-21] init | 建立 AGENTS.md，修正 index.md
- 新增檔案：`AGENTS.md`（AI Agent 操作手冊，共 11 節）
  - 專案背景與目標
  - 目錄結構定義（equipment vs styles 分工釐清）
  - 核心規則（7 條）
  - Ingest / Query / Lint 三大工作流程（含 Antigravity 工具對應）
  - 頁面格式規範與各類型 Section 建議
  - index.md / log.md 維護規範
  - 分類系統說明表
  - 射箭術語中英對照表（31 條）
- 更新頁面：`wiki/index.md`
  - 修正頁面總數（7 → 9）
  - 各分類改用表格格式，新增「最後更新」欄位

---

## [2026-11-13] ingest | World Archery 官方器材頁面（5 篇）
- 來源：
  1. https://www.worldarchery.sport/sport/equipment（器材總覽）
  2. https://www.worldarchery.sport/sport/equipment/recurve（反曲弓）
  3. https://www.worldarchery.sport/sport/equipment/compound（複合弓）
  4. https://www.worldarchery.sport/sport/equipment/barebow（裸弓）
  5. https://www.worldarchery.sport/sport/disciplines/para-archery（殘障射箭）
- 新增頁面：6 頁
  - `wiki/equipment/弓具/器材總覽.md`
  - `wiki/equipment/弓具/反曲弓.md`
  - `wiki/equipment/弓具/複合弓.md`
  - `wiki/equipment/弓具/裸弓.md`
  - `wiki/competitions/殘障射箭.md`
  - `wiki/concepts/射手悖論.md`
- 更新頁面：1 頁（`wiki/index.md`）
- 關鍵發現：
  - 三大弓種規格數據已完整收錄（磅數、箭速、材質、競賽資格）
  - 裸弓弦行（String Walking）技術為獨特的本能瞄準核心，值得後續深入
  - 殘障射箭分級系統完整（PI1/PI2/W1/VI1/VI2），視覺障礙組尚未納入帕運
  - 射手悖論與脊值關係已建立獨立概念頁

---

## [2026-11-13] init | 知識庫初始化
- 建立目錄結構（raw/, wiki/ 及各子目錄）
- 建立 AGENTS.md — AI Agent 操作規範
- 建立 wiki/index.md — 總索引初稿
- 建立 wiki/log.md — 本操作日誌
- 建立 wiki/overview.md — 知識庫全景概述初稿
- 新增頁面：1 頁（overview.md）
- 下一步：開始 ingest 第一份射箭素材
