# Assembly Check Report — IVL Balloon Complications Review

**檢查日期：** 2026-04-07
**檢查檔案：** `output/IVL-balloon-complications-review.html`
**卡片目錄：** `cards/` (19 張 CARD-001 ~ CARD-019)
**已知有效參考文獻：** [1]–[22]（22 條）
**CARD-ID → ref 對照：** CARD-001→[1], CARD-002→[2], ..., CARD-019→[19], WEB-001→[20], WEB-002→[21], SCAI→[22]

---

## A. 編號完整性

| 檢查項 | 結果 |
|--------|------|
| `<ol>` 內 `<li>` 數量 | **22** |
| 編號範圍 | [1]–[22]，連續無跳號 |
| 重複編號 | 無 |
| 結論 | **PASS** |

---

## B. Metadata 一致性（HTML ref list vs 卡片 frontmatter）

逐條比對 title / first author / journal / year / DOI：

| Ref # | CARD-ID | First Author | Year | DOI Match | Title Match | Journal Match | 備註 |
|-------|---------|-------------|------|-----------|-------------|---------------|------|
| [1] | CARD-001 | Kereiakes DJ | 2021 | MATCH | MATCH | MATCH | — |
| [2] | CARD-002 | van Oort MJH | 2025 | MATCH | MATCH | MATCH | — |
| [3] | CARD-003 | van Oort MJH | 2025 | MATCH | MATCH | MATCH | — |
| [4] | CARD-004 | Chugh Y | 2021 | MATCH | MATCH | MATCH | — |
| [5] | CARD-005 | Mastrangelo A | 2022 | MATCH | MATCH | MATCH | HTML 用 "Front Cardiovasc Med"；卡片用 "Frontiers in Cardiovascular Medicine"（同義縮寫） |
| [6] | CARD-006 | Kereiakes DJ | 2021 | MATCH | MATCH | MATCH | — |
| [7] | CARD-007 | Honton B | 2022 | MATCH | MATCH | MATCH | — |
| [8] | CARD-008 | Lee TJ | 2021 | MATCH | MATCH | MATCH | — |
| [9] | CARD-009 | Nakata M | 2026 | MATCH | MATCH | MATCH | — |
| [10] | CARD-010 | Ali ZA | 2023 | MATCH | MATCH | MATCH | — |
| [11] | CARD-011 | Phagu AAS | 2025 | MATCH | MATCH | MATCH | — |
| [12] | CARD-012 | Nakamura M | 2025 | MATCH | MATCH | MATCH | — |
| [13] | CARD-013 | Jurado-Roman A | 2025 | MATCH | MATCH | MATCH | — |
| [14] | CARD-014 | Moghadam AS | 2025 | MATCH | MATCH | MATCH | — |
| [15] | CARD-015 | Cubero-Gallego H | 2022 | MATCH | MATCH | MATCH | — |
| [16] | CARD-016 | Kereiakes DJ | 2022 | MATCH | MATCH | MATCH | — |
| [17] | CARD-017 | Sekimoto T | 2025 | MATCH | MATCH | MATCH | — |
| [18] | CARD-018 | Ali ZA | 2024 | MATCH | MATCH | MATCH | — |
| [19] | CARD-019 | Choudhury A | 2025 | MATCH | MATCH | MATCH | — |
| [20] | WEB-001 | — (Shockwave Medical ISI) | 2026 | N/A (網頁) | N/A | N/A | 無卡片；為廠商 ISI 網頁 |
| [21] | WEB-002 | — (Shockwave Medical IFU) | 2023 | N/A (文件) | N/A | N/A | 無卡片；為廠商 IFU 文件 |
| [22] | SCAI | Riley RF | 2024 | MATCH (10.1016/j.jscai.2023.101259) | MATCH | MATCH | 無獨立卡片；為 SCAI consensus |

**結論：PASS — 所有 19 張卡片的 metadata 與 HTML ref list 完全一致。[20][21][22] 為非卡片來源（廠商文件/共識），DOI 及作者資訊正確。**

---

## C. 孤兒檢查（Orphan Analysis）

### C-1. 正文引用頻次

| Ref # | 正文出現次數 | 是否為孤兒 |
|-------|-------------|-----------|
| [1] | 4 | No |
| [2] | 9 | No |
| [3] | 4 | No |
| [4] | 3 | No |
| [5] | 5 | No |
| [6] | 14 | No |
| [7] | 23 | No |
| [8] | 14 | No |
| [9] | 15 | No |
| [10] | 5 | No |
| [11] | 8 | No |
| [12] | 7 | No |
| [13] | 14 | No |
| [14] | 13 | No |
| [15] | 2 | No |
| [16] | 3 | No |
| [17] | 14 | No |
| [18] | 4 | No |
| [19] | 27 | No |
| [20] | 1 | No |
| [21] | 13 | No |
| [22] | 3 | No |

### C-2. 列表有但正文未引用的
**無** — 所有 22 條參考文獻均在正文中被引用至少 1 次。

### C-3. 正文引用但列表缺少的
**無** — 正文引用最大值為 [22]，ref list 恰好 22 條。無 [23] 或更大的數字出現在正文中。

**結論：PASS — 無孤兒文獻，無缺漏文獻。**

---

## D. 重複文獻檢查

逐條以 DOI 排重：

| DOI | 出現次數 | 對應 Ref # |
|-----|---------|-----------|
| 10.1016/j.jcin.2021.04.015 | 1 | [1] |
| 10.1016/j.jscai.2025.103706 | 1 | [2] |
| 10.1136/heartjnl-2024-324703 | 1 | [3] |
| 10.25270/jic/21.00034 | 1 | [4] |
| 10.3389/fcvm.2022.829117 | 1 | [5] |
| 10.1016/j.jcin.2021.03.036 | 1 | [6] |
| 10.15420/icr.2021.14 | 1 | [7] |
| 10.1093/ehjcr/ytab432 | 1 | [8] |
| 10.1016/j.jaccas.2026.107494 | 1 | [9] |
| 10.1161/CIRCINTERVENTIONS.123.012898 | 1 | [10] |
| 10.1002/ccd.31637 | 1 | [11] |
| 10.1007/s12928-025-01130-9 | 1 | [12] |
| 10.1016/j.jcin.2024.11.012 | 1 | [13] |
| 10.1002/ccd.31664 | 1 | [14] |
| 10.25270/jic/22.00058 | 1 | [15] |
| 10.1016/j.jscai.2021.100001 | 1 | [16] |
| 10.1016/j.jcin.2025.06.035 | 1 | [17] |
| 10.4244/EIJ-D-24-00282 | 1 | [18] |
| 10.15420/icr.2025.09 | 1 | [19] |
| N/A (ISI 網頁) | 1 | [20] |
| N/A (IFU 文件) | 1 | [21] |
| 10.1016/j.jscai.2023.101259 | 1 | [22] |

**特別注意：** [2] 和 [3] 來自同一 BENELUX-IVL Registry，但為不同子分析、不同期刊、不同 DOI，不屬於重複。

**結論：PASS — 22 條參考文獻全部唯一，無重複。**

---

## E. 排除說明誤包問題（[23][24]）

| 檢查項 | 結果 |
|--------|------|
| HTML 中是否有 [23] 或 [24] 出現 | **無** |
| 排除說明的 HTML 結構 | `<div class="exclusion-note">` 內用 `<ul><li>` 呈現，**獨立於** ref list 的 `<ol>` |
| ref list `<ol>` 的 `<li>` 數量 | 精確 22 條 |
| 結論 | **PASS — 排除說明未被誤包在 ref list 的 `<ol>` 中** |

原先預期的「[23][24] 誤包在 ref list」瑕疵**不存在於目前版本**。排除說明以獨立 `<div class="exclusion-note">` + `<ul>` 呈現，結構正確。

---

## F. 其他發現

### F-1. Header 計數不一致
- Header banner 顯示 **"21 References"**（line 430）
- 實際 ref list 有 **22 條**
- **ISSUE：Header 應修正為 "22 References"**

### F-2. 引用頻次極端值
- [19] (Choudhury, Calcium Challenge tips) 被引用 27 次，為全文最高頻引用
- [20] (Shockwave ISI 網頁) 僅被引用 1 次

上述為觀察記錄，不影響組裝完整性判定。

---

## 總結

| 檢查項 | 結果 | 說明 |
|--------|------|------|
| A. 編號完整性 | **PASS** | [1]–[22] 連續、無跳號、無重複 |
| B. Metadata 一致性 | **PASS** | 所有 19 張卡片 + 3 條非卡片來源完全一致 |
| C. 孤兒檢查 | **PASS** | 無孤兒、無缺漏 |
| D. 重複文獻 | **PASS** | 22 條全部唯一 |
| E. 排除說明誤包 | **PASS** | 瑕疵不存在；結構正確 |
| F-1. Header 計數 | **ISSUE** | "21 References" 應修正為 "22 References" |

**整體判定：組裝完整性合格，僅 header 計數需修正。**
