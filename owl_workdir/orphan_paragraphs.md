# 孤兒段落偵測報告

**檔案：** `output/IVL-balloon-complications-review.html`
**日期：** 2026-04-07
**偵測 Agent：** 📎 孤兒段落 Agent (Opus 4.6)

---

## 掃描範圍

- 掃描 `<main class="main-content">` 內所有 `<p>` 段落（共約 40 段）
- 排除項目：表頭/表註 (`<tfoot>`, `<caption>`)、圖說 (`<figcaption>`)、Protocol Box 內操作步驟 (`class="protocol-box"`)、IFU Alert Box (`class="ifu-alert"`)、Warning Box (`class="warning-box"`)、Take-Home Box (`class="takeaway-box"`)、Clinical Pearl (`class="clinical-pearl"`)、排除說明 (`class="exclusion-note"`)

---

## 結果摘要

| 分級 | 數量 |
|------|------|
| 高度可疑 (MUST) | 0 |
| 中度可疑 (SHOULD) | 0 |
| 低度 / 不需引用 | 2 |
| **總計孤兒段落** | **0 (需處理)** |

---

## 詳細分析

### 不需引用的孤兒段落（已排除）

#### 1. Section 2 開頭 — 表格引言（Line 538-543）

```
IVL balloon-related complications 的發生率在不同研究設計間呈現明顯差異。
表 1 彙整了目前主要臨床試驗與真實世界 registries 報告的 complications 數據。
值得注意的是，各研究在併發症定義、報告方式及收案族群方面存在顯著差異，
直接比較時需謹慎解讀。
```

**判定：不需引用**
**理由：** 此為章節介紹語句（section introduction），功能為引導讀者進入下方表格。內容為一般性方法學提醒（各研究定義不同、需謹慎比較），不含任何具體數字、發生率或試驗結果。引用已在緊接的表格與後續段落中完整呈現。

---

#### 2. Section 6.4 開頭 — 表格引言（Line 1153-1156）

```
不同世代的 IVL catheter 在脈衝限制與 re-insertion 規則上有重要差異，
直接影響 balloon complication 的處置決策：
```

**判定：不需引用**
**理由：** 此為引導讀者進入下方 C2/C2+/C2 Aero 規格比較表的過渡語句。不含具體數字，僅為定性概述。相關引用 [20][21] 已在表格 `<tfoot>` 中標註。

---

### 段落末尾無引用但段落整體有引用的句子（已排除）

以下為段落最後一句為總結性 inference 而未單獨掛引用的情況，但整個 `<p>` 段落已有充分引用，不列為孤兒：

| 位置 | 末句內容摘要 | 段落引用 | 判定 |
|------|-------------|----------|------|
| Sec 3.2 (Line 749-756) | 「換言之，多數 balloon rupture 為良性事件...不伴隨臨床後果。」 | [7][8] | OK — 為前文 [8] 數據的直接推論 |
| Sec 4 Calcium (Line 884) | 「此結果表明 IVL 在 concentric calcium 中是最安全的 calcium modification 選項...」 | [17] x5 | OK — 為同段 [17] 數據的作者結論 |
| Sec 5 Pulse (Line 913) | 「因此，維持低壓充氣（4 atm 或更低）...是保護 balloon 完整性的關鍵操作原則。」 | [19] x2 | OK — 為同段 [19] 建議的總結 |
| Sec 7.2 ROLLER (Line 1408-1418) | 「總體而言，在相似的 efficacy 下，IVL 的嚴重程序併發症率最低。」 | [13] x多 | OK — 為同段 RCT 數據的直接結論 |
| Sec 6 SCAI Pearl (Line 1146-1148) | 「此共識與 IFU 的...建議完全一致，並從臨床經驗角度強化了...的論點。」 | [22] | OK — Clinical Pearl 內的綜合摘要，[22] 已在段落中標註 |

---

## 結論

本 HTML Review 的引用覆蓋率**極佳**。全文 40 段正文段落中：

- **0 段**含有需要引用但缺乏引用的具體聲明（高度可疑 = 0，中度可疑 = 0）
- **2 段**為表格引言的過渡語句，不含需引用的實質聲明
- 所有含具體數字（百分比、OR、CI、P 值）的段落均有完整引用
- 所有試驗結果、機轉描述、比較性聲明均有引用支持
- Protocol Box、Warning Box、IFU Alert、Take-Home Messages 等特殊區塊均已正確標註來源 [21][22]

**無需修補。**
