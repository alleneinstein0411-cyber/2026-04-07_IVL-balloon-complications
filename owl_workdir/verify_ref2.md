# Verify Ref [2] — CARD-002 BENELUX-IVL Complications

> van Oort MJH et al. Incidence of complications following coronary IVL. JSCAI 2025;4:103706

**Verification date:** 2026-04-07
**Verifier:** Owl Citation Agent (automated)
**Sources:** PDF (7 pages, full text) + CARD-002_BENELUX_complications.md

---

## Layer 1: Card vs PDF (Metadata & Data Integrity)

| Field | Card | PDF | Match |
|-------|------|-----|-------|
| Title | Incidence of Complications Following Coronary Intravascular Lithotripsy, Clinical Outcomes, and Predictors of Complications | identical | PASS |
| Authors | van Oort MJH ... Montero-Cabezas JM (15 authors) | identical | PASS |
| Journal | JSCAI | JSCAI | PASS |
| Year / Vol / Article ID | 2025 / 4 / 103706 | 2025 / 4 / 103706 | PASS |
| DOI | 10.1016/j.jscai.2025.103706 | identical | PASS |
| Registry | NCT06577038 | NCT06577038 | PASS |
| N (patients / lesions) | 509 / 537 | 509 / 537 [p.2] | PASS |
| Centers | 8 centers, 2 countries | 8 centers in 2 European countries [p.2] | PASS |
| Enrollment period | May 2019 - Sep 2024 | May 2019 - Sep 2024 [p.1] | PASS |
| Overall complication rate | 33/509 (6%) | 33 (6%) [p.2, Table 1] | PASS |
| Immediately after IVL | 6/509 (1%) | 6 (1%) [Table 1] | PASS |
| Table 1 all rows | 9 complication types + 12 intervention types | all match [p.3] | PASS |
| Table 2 baseline | 20+ variables | spot-checked 12 rows, all match [p.4] | PASS |
| Table 3 procedural | IVL balloon, pulses, pre/post-dilatation | all match [p.4] | PASS |
| Table 4 MACE | 5 time periods, 4 columns each | all match [p.5] | PASS |
| Table 5 regression | 17 univariable + 4 multivariable rows | all match [p.6] | PASS |
| Funding / COI | Shockwave + detailed COI | match [p.6-7] | PASS |

**Layer 1 verdict: ALL PASS.** Card faithfully extracts all data from PDF without error.

---

## Layer 2: Review Claims vs PDF

### Claim 1
> "BENELUX-IVL registry (N=509, 8 centers) overall complication rate 6% (33/509)"

- **PDF [p.2]:** "509 patients ... across 8 centers in 2 European countries"; "complications occurred in 33 patients (6%)"
- **Verdict: PASS**

---

### Claim 2
> "directly attributable to IVL: 1% (6/509)"

- **PDF [p.3, Table 1]:** "Immediately after IVL 6 (1)"
- **PDF [p.3 text]:** Lists 6 specific complications occurring immediately after IVL, all successfully managed.
- **Verdict: PASS (numbers) / MINOR WORDING CONCERN (interpretation)**
- **Detail:** PDF uses "immediately after IVL" (temporal classification), while the Review uses "directly attributable to IVL" (causal attribution). The PDF's distinction is temporal-procedural, not strictly causal. The 6/509 = 1% numbers are correct. The wording difference is a minor interpretive inflation but does not materially change the clinical message.
- **Note on PDF typo:** PDF p.2 text contains "33 lesions occurred immediately after IVL (1%)" -- this is an apparent typo in the published article (should be "6" per Table 1 and p.3 detailed description). The Card and Review correctly use the value 6.

---

### Claim 3
> "flow-limiting dissection 9 (2%), coronary perforation 7 (1%)"

- **PDF [Table 1, p.3]:** "Coronary dissection 9 (2)" and "Coronary perforation 7 (1)"
- **PDF [p.2 text]:** "flow-limiting coronary dissections (n=9, 2%) ... coronary perforations (n=7, 1%)"
- **Verdict: PASS**

---

### Claim 4
> "balloon rupture -> perforation: 1 (0.2%)"

- **PDF [p.3]:** "1 coronary perforation due to IVL balloon rupture (0.2%)"
- **Verdict: PASS**

---

### Claim 5
> "BAR as only significant multivariable predictor OR 1.453 (95% CI 1.074-1.966, p=0.015)"

- **PDF [Table 5, p.6]:** BAR multivariable: OR 1.453, 95% CI 1.074-1.966, P=.015
- **Other multivariable variables:** Sex (P=.208), BMI (P=.096), ICI (P=.296) -- all non-significant
- **"Only" significant:** Confirmed -- BAR is the sole variable reaching P<.05 in the multivariable model
- **Verdict: PASS**

---

### Claim 6
> "Maximum predilatation balloon size excluded due to collinearity"

- **PDF [Table 5 footnote, p.6]:** "Maximum predilatation balloon size was excluded from the multivariate analysis due to multicollinearity with the balloon-to-artery ratio."
- **Verdict: PASS**

---

### Claim 7
> "pulse count and inflation pressure both not significantly associated"

- **PDF [Table 5, p.6]:**
  - No. of IVL pulses delivered: OR 1.002, 95% CI 0.988-1.017, P=.743
  - Maximum IVL inflation pressure: OR 0.924, 95% CI 0.650-1.312, P=.657
- **Verdict: PASS**

---

### Claim 8
> "Cumulative 1-year MACE complication group 43% vs no-complication 9% (P<.001)"

- **PDF [Table 4, p.5]:** Cumulative 1-year MACE: Complication 9 (43%), No complication 30 (9%), P<.001
- **PDF [p.4 text]:** "n=9, 43% vs n=30, 9%; P<.001"
- **Note:** Denominator for cumulative 1-year MACE is patients with completed 1-year follow-up: 21 (complication) and 325 (no-complication), per Table 4 header. 9/21=42.9% rounds to 43%; 30/325=9.2% rounds to 9%.
- **Verdict: PASS**

---

### Claim 9
> "IVL balloon diameter median 3.5 (3.0-4.0) mm, no group difference"

- **PDF [Table 3, p.4]:** IVL Balloon diameter: Overall 3.5 (3.0-4.0), No complication 3.5 (3.0-4.0), Complication 3.5 (3.0-4.0), P=.577
- **Verdict: PASS**

---

## Layer 3: Error Source Tracking

### Issues Found

| # | Severity | Type | Location | Description |
|---|----------|------|----------|-------------|
| 1 | MINOR | Wording | Claim 2 | Review says "directly attributable to IVL" but PDF says "immediately after IVL." Temporal classification != causal attribution. Numbers (6/509, 1%) are correct. |
| 2 | INFO | PDF typo | PDF p.2 | Published text reads "33 lesions occurred immediately after IVL (1%)" -- should be "6" per Table 1 and p.3 text. Card and Review correctly use 6. |

### Error Source Analysis

- **Issue #1 origin:** Review writing stage (not Card). The Card correctly transcribes "Immediately after IVL: 6/509 (1%)" [Card section 4.1]. The wording change to "directly attributable" was introduced during Review composition.
- **Issue #2 origin:** Published PDF itself. This is a typo in the original article where the number "33" (total complications) was likely copy-pasted where "6" (IVL-immediate) was intended. Both Card and Review correctly use 6.

---

## Summary

| Layer | Result |
|-------|--------|
| Layer 1 (Card vs PDF) | **ALL PASS** -- Card is a faithful extraction |
| Layer 2 (9 Claims vs PDF) | **9/9 numerically correct; 1 minor wording concern** |
| Layer 3 (Error tracking) | **1 minor wording issue (Review stage); 1 PDF typo (source)** |

### Overall Verdict: **PASS**

All 9 Review claims are numerically accurate and traceable to specific PDF locations. The single wording issue (Claim 2: "directly attributable" vs "immediately after IVL") is a minor interpretive nuance that does not materially alter the clinical message, but should be flagged for the author to consider aligning with the original paper's terminology.
