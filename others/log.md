# 手沖咖啡風味科學 LLM Wiki — 異動紀錄 (Log)

---

## [2026-11-12] init | 建立知識庫架構與 AGENTS.md 運作規範
- 確立目標優先序：3 (教材簡報產出) > 1 (實戰診斷) > 2 (理論編譯)。
- 確立內容比例規範：70% 實踐風味應用 + 30% 科學原理解析。
- 採用 Obsidian `[[Page-Name]]` 雙向連結格式。
- 建立 `raw/`、`wiki/`（7大功能分類目錄）與 `AGENTS.md`。

---

## [2026-11-12] ingest | 手沖咖啡風味科學核心基礎：五大核心主題文獻
- **原始來源**：`raw/01-hand-drip-coffee-flavor-science-foundations.md`
- **生成來源摘要**：`wiki/sources/01-hand-drip-coffee-flavor-science-foundations.md`
- **橫向分發建立知識頁面**：
  - `wiki/processing-and-roast/processing-methods.md`（水洗、日曬、蜜處理）
  - `wiki/processing-and-roast/roast-levels.md`（淺、中、深焙的梅納與焦糖化反應）
  - `wiki/chemistry/golden-cup-and-extraction-kinetics.md`（金杯準則、TDS、EY% 與溶解時間動力學）
  - `wiki/variables/four-brew-variables.md`（水溫、研磨度、粉水比、時間擾動）
  - `wiki/equipment/dripper-comparison-guide.md`（V60、蛋糕濾杯、梯形與 Switch）
  - `wiki/troubleshooting/flavor-diagnosis-matrix.md`（風味診斷速查表與通道效應排除）
  - `wiki/curriculum/course-overview-and-slide-blueprint.md`（五大模組 20 張投影片簡報藍圖）
- **同步全庫目錄**：更新 `wiki/index.md`。


---

## [2026-11-12] ingest | 8 篇台灣專業手沖與烘焙專欄文獻攝入
- **原始來源**：`raw/02-web-sources-compilation.md`（收錄 Cafe Green、硬性格、盧貝斯、Matrix、Fuki、JC咖啡、Femobook）
- **生成來源摘要**：`wiki/sources/02-web-sources-compilation.md`
- **橫向分發 (Fan-out) 與擴充**：
  - 更新 `wiki/processing-and-roast/processing-methods.md`：新增印尼濕刨法（Giling Basah）、現代厭氧發酵（Anaerobic）、二氧化碳浸漬（Carbonic Maceration）與熱休克（Thermal Shock）機制。
  - 更新 `wiki/processing-and-roast/roast-levels.md`：補強烘焙四大階段（脫水期、梅納/焦糖化期、一爆、風味發展期 DTR%），以及與萃取器具（手沖、虹吸、義式）的深度適配。
  - 更新 `wiki/equipment/dripper-comparison-guide.md`：新增 Brewista 魔方可變流速濾杯；深度解析濾杯材質熱力學（樹脂不吸熱保溫 vs 陶瓷高吸熱 vs 金屬導熱散熱）；增補三大過濾介質（濾紙、法蘭絨濾布、金屬網）對油脂與 Body 的感官影響。
  - 更新 `wiki/variables/four-brew-variables.md`：納入 2 分 30 秒新手黃金實操 SOP（1:15、89°C、30秒悶蒸）、解密悶蒸排氣動力學，以及智慧流速秤（g/s）概念。
  - 更新 `wiki/curriculum/course-overview-and-slide-blueprint.md`：將新觀點（濕刨法、厭氧、烘焙四階段、材質熱力學、悶蒸科學）全面整合進 20 張投影片簡報藍圖。
- **同步全庫目錄**：更新 `wiki/index.md`。


---

## [2026-11-12] presentation | 生成 16 頁手沖風味科學互動式 HTML 投影片
- **輸出檔案**：`presentation.html`
- **設計風格**：深焙精品咖啡美學（Dark Roast Amber & Cream）、大卡片版面、低文字密度、重點標記膠囊（酸/甜/醇厚標籤）。
- **包含內容**：
  1. 封面與章節全景地圖
  2. 處理法（三大經典 + 濕刨/厭氧/熱休克）
  3. 烘焙四階段（脫水、梅納、一爆、DTR）與器具適配
  4. 金杯準則（TDS 1.15-1.45% / EY 18-22%）與動力學時間賽跑
  5. 通道效應微觀水力學與預防
  6. 四大變因儀表盤、悶蒸 30 秒排氣科學、2 分 30 秒黃金 SOP
  7. 濾杯流速（V60 vs Wave vs Switch）、材質熱力學冷知識、三大過濾介質
  8. 舌頭感測器風味診斷決策樹、結語與 Q&A
- **技術功能**：鍵盤快捷鍵（方向鍵/空白鍵翻頁、F 全螢幕、O 章節全覽）、觸控滑動、進度條與響應式卡片。


---

## [2026-11-12] style | 投影片 HTML 主題視覺切換為明亮暖白風格
- **更新檔案**：`presentation.html`
- **修改重點**：
  - 背景全面由深黑/深棕改為日系/北歐精品咖啡館明亮基調（暖麻白 `#FBF9F5`）。
  - 卡片改為純白 `#FFFFFF`，搭配溫潤柔和的咖啡暖調陰影（`rgba(74, 46, 27, 0.06)`）。
  - 文字改為濃縮深棕 `#22150E` 與可可灰褐 `#3D2D24`，大幅提升閱讀對比度與清爽質感。
  - 封底照片加上高透明度暖白遮罩，兼顧照片美感與內文可讀性。


---

## [2026-11-12] audit & lint | 全庫與簡報深度文獻對齊與科學修正
- **數據衝突修正**：
  - 金杯濃度 TDS 嚴格對齊來源 4（Matrix）與來源 5（Fuki）之 SCA 標準 **1.15% ~ 1.35%**（修正原本標記為 1.45% 的偏差）。
  - 烘焙階段溫度嚴格對齊來源 3（盧貝斯 Rubasse）：脫水至 150°C、梅納 150～200°C、一爆開始 200°C（淺焙 210°C、中焙 218～220°C、深焙 228～230°C 下豆）。
- **名詞與科學概念修正**：
  - 日曬處理法修正：移除「熱裂解」誤用，正名為「微生物發酵轉化」。
  - 物質溶出順序修正：咖啡因對熱水極易溶，移至「前段 (0~45s)」；烘焙褐變物質正名為「類黑素（Melanoidins）」，而非皮膚黑色素。
  - 研磨名詞修正：統一為「二號砂糖」（非二號白砂糖）。
  - 手沖四大變因對齊：對齊來源 6（JC 咖啡）之「水溫、磨粉粗細、萃取時間、烘焙程度」，並以 1:15 為基礎粉水比框架。
  - 濾杯流速定調：統一定調「錐形單大孔流速快、考驗控水；平底多孔搭配波浪濾紙流速均勻穩定、容錯率高」。
- **簡報 HTML 獨立性重大升級 (Zero Broken Images)**：
  - 全面將本地 `picture/` 依賴改為**純 CSS 幾何漸層背景與內嵌向量 SVG 圖示**。
  - 確保單一 `.html` 檔案任意移動、離線開啟或繳交作業，**100% 絕不破圖**。


---

## [2026-11-12] fix | 修正 Slide 10 四大要素排版跑版問題
- **問題診斷**：原 4 欄並列（`grid-4`）在常規螢幕寬度下卡片寬度過窄，導致中文詞語（如「研磨越細」、「二號砂糖」）被非自然強制折行中斷，欄位文字錯位。
- **修正處方**：
  1. 將 Slide 10 改為寬敞平衡的 **2x2 矩陣佈局（`grid-2`）**，卡片可用寬度增加一倍以上。
  2. 導入結構化標籤組件 `.bullet-tag` 與 `.bullet-tag-gold`，固定不折行（`white-space: nowrap`），並移除生硬冒號，使版面整齊劃一、呼吸感充足。


---

## [2026-11-12] fix | 徹底消除 .bullet-list 的 CSS Flex 匿名子項分欄跑版
- **問題根因**：原 `.bullet-list li` 宣告了 `display: flex; gap: 8px;`，在 CSS 標準中，Flex 容器內部所有的子節點（包含 `<b>` 標籤與前後的文字、冒號、逗號等匿名文字節點）皆會被瀏覽器強制轉化為獨立的 Flex Item，並套用 8px 間隙。這導致只要句子中出現 `<b>`，整句話就被切成多個橫向窄欄，字詞被壓縮直排、冒號前產生怪異空格。
- **修正處方**：
  - 將 `.bullet-list li` 徹底改為標準的 `display: block; position: relative; padding-left: 1.25rem;`。
  - 項目符號 `✦` 改為 `position: absolute; left: 0; top: 0;` 定位。
  - 所有內聯標籤 `<b>` 與普通文字恢復原生 Inline 排版，文字換行與標點符號 100% 自然流暢，徹底解決 Slide 8、Slide 10、Slide 3、4、12、13 的橫向擠壓斷行與冒號間隙問題。
