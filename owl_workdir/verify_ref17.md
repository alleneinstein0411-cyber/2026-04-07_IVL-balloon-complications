# Ref [17] 驗證報告 — Sekimoto T et al. JACC Cardiovasc Interv 2025;18(17):2093-2104

**驗證日期**: 2026-04-07
**驗證員**: 卡片 Agent (CARD-017)
**PDF 來源**: CARD-017_comparison_of_vascular_injury_from_intravascular_lithotripsy.pdf (12 pages)
**Card 來源**: CARD-017_Sekimoto_vascular_injury.md

---

## Layer 1: 書目資料驗證

| 項目 | Review 引用 | PDF 原文 | 判定 |
|------|-----------|---------|------|
| 作者 | Sekimoto T et al. | Teruo Sekimoto, MD 等 13 位作者 | PASS |
| 期刊 | JACC Cardiovasc Interv | JACC: CARDIOVASCULAR INTERVENTIONS | PASS |
| 年份 | 2025 | 2025 | PASS |
| 卷/期/頁 | 18(17):2093-2104 | VOL. 18, NO. 17, 2025:2093-2104 | PASS |

---

## Layer 2: 數據逐項驗證

### Claim 1: 「6 具屍體心臟、17 calcified lesions、40 tissue sections」

- **PDF p.4**: "6 cadaveric hearts were included in this study" / "10 coronary arteries with 17 lesions were treated" / "A total of 40 tissue sections were prepared for analysis"
- **Card**: Section 1 表格一致記錄
- **判定**: ✅ PASS

---

### Claim 2: 「Calcium fracture by micro-CT+histology: IVL 80% vs CB 66.7% vs UHB 33.3% (P=0.350)」

- **PDF p.5**: "Fractures, as confirmed by the gold standard micro-CT, were observed in 4 of 5 lesions (80%) with IVL, 4 of 6 lesions (66.7%) with the CB, and 2 of 6 lesions (33.3%) with the UHB (P 0.350)"
- **PDF p.1 Abstract**: "Fractures confirmed by micro-CT and histology were observed in 80% of IVL-treated lesions, 66.7% treated with the CB, and 33.3% treated with the UHB (P 0.350)"
- **Card Section 5a**: 表格數據一致
- **判定**: ✅ PASS

---

### Claim 3: 「Medial injury: IVL 20% vs CB 83.3% vs UHB 100% (P=0.012)」

- **PDF p.5**: "Medial injury detected on histologic sections was found in 1 of 5 lesions (20.0%) with IVL, 5 of 6 lesions (83.3%) with the CB, and in all lesions with the UHB, with significantly fewer injuries observed in the IVL group (P 0.012)"
- **PDF p.1 Abstract**: "Medial injury occurred significantly less frequently with IVL (20.0%) compared with the CB (83.3%) and the UHB (100%) (P 0.012)"
- **Card Section 5b**: 表格數據一致
- **判定**: ✅ PASS

---

### Claim 4: 「IVL vs UHB: P=0.015」

- **PDF p.5**: "In post hoc analysis, a significant difference was observed between IVL and UHB (P 0.015)"
- **Card Section 5b Post hoc**: IVL vs UHB: P = 0.015
- **判定**: ✅ PASS
- **附註**: 此 P=0.015 是 lesion-level medial injury 的 post hoc comparison。注意在 section-level ≥180° 分析中也有一個 P=0.015，但那是 fracture rate 的 IVL vs CB 比較（見 Claim 6 附註）。Review 應明確標示此為 medial injury by lesion 的 post hoc。

---

### Claim 5: 「≥180° arc sections: IVL 100% fracture with 0% medial injury」

- **PDF p.7**: "In cross sections with an arc of ≥180° (n 16), IVL consistently produced fractures without any medial injury"
- **PDF p.1 Abstract**: "In histologic sections with a calcium arc of ≥180°, IVL induced fractures in 100% of sections, all without medial injury"
- **Central Illustration (p.6)**: IVL n=5, 100% fracture without medial injury, 0% fracture with medial injury, 0% nonfracture
- **Card Section 7b**: IVL 100% (5/5) fracture WITHOUT medial injury
- **判定**: ✅ PASS

---

### Claim 6: 「CB 16.7% fracture without injury, UHB 20% (P=0.007)」

- **Central Illustration (p.6)**: ≥180° subgroup — CB: 16.7% fracture without medial injury; UHB: 20.0% fracture without medial injury
- **PDF p.7**: Overall P = 0.007 for ≥180° section comparison
- **Card Section 7b**: CB 16.7% (1/6), UHB 20.0% (1/5), P = 0.007
- **判定**: ✅ PASS
- **附註**: P=0.007 是 ≥180° subgroup 中三組「fracture without medial injury」比率的 overall comparison（不是 CB vs UHB 的 pairwise P 值）。Review 的表述方式可能讓讀者誤以為 P=0.007 是 CB vs UHB 的直接比較；實際上 CB vs UHB 的 pairwise P = 0.221。建議 Review 改寫為明確標示 "overall P=0.007" 以避免歧義。

---

### Claim 7: 「Fracture depth: IVL 659 μm vs CB 377 μm vs UHB 708 μm (P=0.149)」

- **PDF p.7 (Figure 2 legend)**: "The depth of fracture was 659 μm (Q1-Q3: 461-797 μm) for IVL, 377 μm (Q1-Q3: 327-526 μm) for the CB, and 708 μm (Q1-Q3: 340-1,011 μm) for the UHB, with no significant difference among the 3 groups (P 0.149)"
- **Card Section 6**: 表格數據完全一致
- **判定**: ✅ PASS

---

### Claim 8: 「UHB fracture only in larger calcium arcs (P=0.003)」

- **PDF p.5**: "for UHB, sections with fractures (n 5) had a significantly larger arc of calcium compared with those without fractures (n 8) (288° [Q1-Q3: 227°-342°] vs 131° [Q1-Q3: 81°-144°]; P 0.003)"
- **Card Section 7a**: UHB fracture sections 288° vs non-fracture 131°, P = 0.003
- **判定**: ✅ PASS

---

### Claim 9: 「IVL = acoustic waves (no fulcrum), CB/UHB = fulcrum effect → injures media」

- **PDF p.9**: "IVL's mechanism—delivering controlled acoustic pressure waves to create precise fractures within calcified plaques at low atmospheric pressures—allows targeted plaque modification, with minimal impact on the surrounding vessel layers"
- **PDF p.10**: "contrary to IVL and CBs, which are dependent on a 'fulcrum effect,' meaning that they rely on a point or edge against which pressure is applied to create a fracture. Although this fulcrum effect may indeed facilitate fracture when embedded into calcium, it may also lead to injury to soft tissue such as the vascular media"
- **Card Section 8**: 詳細記錄機轉差異
- **判定**: ⚠️ MINOR INACCURACY
- **問題**: Review 聲明「IVL = acoustic waves (no fulcrum), CB/UHB = fulcrum effect」，但 PDF p.10 原文實際寫的是 "contrary to IVL **and CBs**, which are dependent on a 'fulcrum effect'"。仔細看上下文，原文的意思是 UHB 的 pressure-based mechanism "contrary to IVL and CBs, which are dependent on a 'fulcrum effect'"——即 **IVL 和 CB 都被歸為有 fulcrum effect**，而 UHB 是純壓力機制。但這段文字的語法確實有歧義。再看 Card Section 8 的整理：IVL 的機轉是 "Acoustic pressure waves at low atmospheric pressure"，CB 是 "Blade-based fulcrum effect"，UHB 是 "Pure high mechanical pressure"。綜合上下文，原文的邏輯是：(a) IVL = acoustic waves，(b) CB = blade fulcrum，(c) UHB = pure pressure → 依賴大 arc。Review 將 CB 和 UHB 都歸為 fulcrum effect 的說法需要更精確：CB 有 blade fulcrum，UHB 的 fracture mechanism 是 circumferential pressure（非 fulcrum），兩者都可能傷害 media 但機轉不同。

---

### Claim 10: 「IVL 治療壓力 4 atm vs CB 18 atm vs UHB 34 atm」

- **PDF p.2 (p.4 of text)**: IVL "delivering 120 pulses (equivalent to 12 treatments) at 4 atm of pressure"
- **PDF p.4**: CB "with an average inflation pressure of 18 atm" / UHB "with an average inflation pressure of 34 atm"
- **Card Section 2**: IVL 4 atm, CB Avg 18 atm, UHB Avg 34 atm
- **判定**: ✅ PASS
- **附註**: CB 的 18 atm 和 UHB 的 34 atm 是 "average" inflation pressure（遵照 COPS 和 ISAR-CALC trial protocol），非固定值。IVL 的 4 atm 是 manufacturer's instructions 的固定值。Review 應標註 CB/UHB 為平均值。

---

## Layer 3: 總結

### 統計摘要

| 層級 | 項目數 | PASS | MINOR | FAIL |
|------|--------|------|-------|------|
| Layer 1 (書目) | 4 | 4 | 0 | 0 |
| Layer 2 (數據) | 10 | 9 | 1 | 0 |
| **合計** | **14** | **13** | **1** | **0** |

### 需修正項目

1. **Claim 9 (MINOR)**: 機轉描述需精確化。PDF 原文中 CB 的機轉是 blade-based fulcrum effect，UHB 的機轉是 pure high mechanical pressure（非 fulcrum）。Review 將 CB 和 UHB 合稱 "fulcrum effect → injures media" 過度簡化，應分別描述：CB = blade fulcrum → media injury；UHB = high pressure → media injury（尤其在大 arc 時才有效 fracture）。

### 建議改善（非錯誤）

1. **Claim 4**: P=0.015 出現在兩個不同的比較中（lesion-level medial injury IVL vs UHB, 以及 ≥180° section fracture rate IVL vs CB）。Review 引用時應明確標示比較的層級和指標。
2. **Claim 6**: P=0.007 是 ≥180° subgroup 的 overall 三組比較，不是 CB vs UHB 的 pairwise P 值。建議加上 "overall" 修飾。
3. **Claim 10**: CB 18 atm 和 UHB 34 atm 為平均值（avg），非固定壓力，可標註。

### 整體判定

**PASS with minor revision** — 所有核心數據（百分比、P 值、樣本量）均與 PDF 原文完全吻合。唯一 minor issue 是機轉描述的過度簡化（Claim 9），以及幾個 P 值 context 的歧義風險（建議改善而非必須修正）。
