# businessRelations

> **Automated business-entity correlation analysis** extracted from financial news documents.
> Each session folder contains heatmaps, correlation tables, and a detailed README.
> Formula: `Correlation(A,B) = (positive − negative co-occurrences) / total co-occurrences` → result in **[−1, +1]**

---

## Sessions Index

| Session | Date | Docs | Entities | Pairs | Folder |
|---------|------|------|----------|-------|--------|
| **T1 + T2** | 2026-10-21 | 8 | 35 | 153 | [2026-10-21\_07-00-48](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-21_07-00-48) |
| **Oct 22** | 2026-10-22 | 4 | 20 | 16 | [2026-10-22\_07-00-48](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-22_07-00-48) |
| **Oct 23 WSJ** | 2026-10-23 | 1 | 12 | 8 | [2026-10-23\_09-55-26](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-23_09-55-26) |

---

## Session 1 — 2026-10-21 (T1 + T2 · 8 documents · 35 entities · 153 pairs)

**Folder:** [`2026-10-21_07-00-48`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-21_07-00-48)

### Files

| File | Description | Size |
|------|-------------|------|
| [`README.md`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-21_07-00-48/README.md) | Full session report — clusters, top pairs, stock map | 9.6 KB |
| [`heatmap_full.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-21_07-00-48/heatmap_full.png) | 35×35 full entity correlation matrix | 114 KB |
| [`heatmap_clusters.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-21_07-00-48/heatmap_clusters.png) | Inter-cluster correlation overview (7 clusters) | 60 KB |
| [`heatmap_stocks.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-21_07-00-48/heatmap_stocks.png) | Stock-level heatmap (publicly traded tickers) | 92 KB |
| [`heatmap_stocks_lollipop.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-21_07-00-48/heatmap_stocks_lollipop.png) | Pairwise ranking lollipop — all non-zero stock pairs | 111 KB |
| **Session 11** | 2026-10-24 | 4 | 16 | 13 | [2026-10-24_11-40-49](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-24_11-40-49) |

### Cluster Summary

| Cluster | Key Entities | Internal Signal |
|---------|-------------|-----------------|
| Musk Ecosystem | Musk, SpaceX, Tesla, Starlink, Meta | +0.75 to +0.95 |
| Geopolitical | Trump, Putin, Xi, Zuckerberg, Ukraine, Zelensky | Mixed |
| Defense | GE Aero., Northrop, RTX, 3M, Boeing, GM | Perfect **+1.00** |
| Media & M&A | Ellison, W.Bros, Oracle, Paramount, D.Ellison | Perfect **+1.00** |
| AI | Anthropic, CoreWeave, DeepMind, Alphabet | Mostly positive |
| Housing | HomeDepot, Lennar, Housing index | **−0.65 to −0.70** |
| Markets | Nasdaq, NYSE | Strongest rivalry **−1.00** |

### Preview

![Full heatmap Oct 21](https://raw.githubusercontent.com/abdelhaknezzariiphone-hue/businessRelations/main/2026-10-21_07-00-48/heatmap_full.png)

---

## Session 2 — 2026-10-22 (4 documents · 20 entities · 16 pairs)

**Folder:** [`2026-10-22_07-00-48`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-22_07-00-48)

### Files

| File | Description | Size |
|------|-------------|------|
| [`README.md`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-22_07-00-48/README.md) | Full session report — tables, findings, stock map | 5.0 KB |
| [`heatmap_full.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-22_07-00-48/heatmap_full.png) | 20×20 full entity correlation matrix | 110 KB |
| [`heatmap_stocks.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-22_07-00-48/heatmap_stocks.png) | Stock-level heatmap (13 traded tickers) | 104 KB |
| [`heatmap_stocks_lollipop.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-22_07-00-48/heatmap_stocks_lollipop.png) | Pairwise lollipop ranking — 9 non-zero stock pairs | 74 KB |
| [`table_all_pairs.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-22_07-00-48/table_all_pairs.png) | All 16 pairs correlation table (pos/neg/total/corr) | 118 KB |
| [`table_stocks.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-22_07-00-48/table_stocks.png) | 9 traded stock pairs styled table | 85 KB |

### Correlation Table (all 16 pairs)

| Entity A | Entity B | Type | Pos | Neg | Total | Corr |
|----------|----------|------|:---:|:---:|:-----:|-----:|
| Tesla | SpaceX | M&A / Collaboration | 7 | 3 | 10 | **+0.40** |
| SMCI | Dell | AI Infra Co-movement | 2 | 0 | 2 | **+1.00** |
| SMCI | HPE | AI Infra Co-movement | 2 | 0 | 2 | **+1.00** |
| Akzo Nobel | Axalta | M&A | 2 | 0 | 2 | **+1.00** |
| Hudbay | Mitsubishi | M&A / JV | 2 | 0 | 2 | **+1.00** |
| Anthropic | Nasdaq | Strategic Partnership | 3 | 0 | 3 | **+1.00** |
| Barclays | Tesla | Financial Analysis | 2 | 0 | 2 | **+1.00** |
| Dell | HPE | AI Infra Co-movement | 1 | 0 | 1 | **+1.00** |
| Barclays | SpaceX | Financial Analysis | 1 | 0 | 1 | **+1.00** |
| GE Vernova | Vistra | Energy Co-movement | 1 | 0 | 1 | **+1.00** |
| CoreWeave | SpaceX | Tech Co-movement | 1 | 0 | 1 | **+1.00** |
| Am. Airlines | Southwest | Airline Sector Peers | 1 | 0 | 1 | **+1.00** |
| Anthropic | SpaceX | IPO Benchmark | 1 | 0 | 1 | **+1.00** |
| SpaceX | AT&T | Competition | 0 | 2 | 2 | **−1.00** |
| NYSE | Nasdaq | Exchange Rivalry | 0 | 3 | 3 | **−1.00** |
| Tesla | Berkshire | Investor Rotation | 0 | 1 | 1 | **−1.00** |

### Preview

![Full heatmap Oct 22](https://raw.githubusercontent.com/abdelhaknezzariiphone-hue/businessRelations/main/2026-10-22_07-00-48/heatmap_full.png)

![All pairs table Oct 22](https://raw.githubusercontent.com/abdelhaknezzariiphone-hue/businessRelations/main/2026-10-22_07-00-48/table_all_pairs.png)

---

## Methodology

```
Correlation(A, B) = (positive_cooccurrences - negative_cooccurrences) / total_cooccurrences
```

For any entity pair A–B, every sentence in the source documents where both appear is classified:
- **Positive**: merger, partnership, collaboration, shared benefit, co-movement, analyst support
- **Negative**: competition, legal dispute, opposing interests, inverse investor flow

The formula normalises the net sentiment to **[−1, +1]**:
- **+1.00** = purely collaborative / aligned
- **0.00** = balanced or no clear direction
- **−1.00** = purely adversarial / inverse

---

## Repository Structure

```
businessRelations/
  README.md                          <- this file (index)
  2026-10-21_07-00-48/
    README.md                        <- session report
    heatmap_full.png                 <- 35x35 entity matrix
    heatmap_clusters.png             <- 7-cluster overview
    heatmap_stocks.png               <- traded tickers heatmap
    heatmap_stocks_lollipop.png      <- pairwise lollipop
  2026-10-22_07-00-48/
    README.md                        <- session report
    heatmap_full.png                 <- 20x20 entity matrix
    heatmap_stocks.png               <- traded tickers heatmap
    heatmap_stocks_lollipop.png      <- pairwise lollipop
    table_all_pairs.png              <- all 16 pairs table
    table_stocks.png                 <- 9 stock pairs table
  2026-10-23_09-55-26/
    README.md                        <- session report
    heatmap_full.png                 <- 12x12 entity matrix
    heatmap_stocks.png               <- traded tickers heatmap
    heatmap_stocks_lollipop.png      <- pairwise lollipop
    table_all_pairs.png              <- all 8 pairs table
    table_stocks.png                 <- 7 stock pairs table
```

---

*Maintained by Joule · auto-generated from financial news documents*

---

## Session 3 — 2026-10-23 (1 document · 12 entities · 8 pairs)

**Folder:** [`2026-10-23_09-55-26`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-23_09-55-26)

### Files

| File | Description | Size |
|------|-------------|------|
| [`README.md`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-23_09-55-26/README.md) | Full session report — tables, findings, stock map | 3.6 KB |
| [`heatmap_full.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-23_09-55-26/heatmap_full.png) | 12×12 full entity correlation matrix | 83 KB |
| [`heatmap_stocks.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-23_09-55-26/heatmap_stocks.png) | Stock-level heatmap (10 traded tickers) | 91 KB |
| [`heatmap_stocks_lollipop.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-23_09-55-26/heatmap_stocks_lollipop.png) | Pairwise ranking lollipop — 7 stock pairs | 57 KB |
| [`table_all_pairs.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-23_09-55-26/table_all_pairs.png) | All 8 pairs correlation table | 68 KB |
| [`table_stocks.png`](https://github.com/abdelhaknezzariiphone-hue/businessRelations/blob/main/2026-10-23_09-55-26/table_stocks.png) | 7 traded stock pairs styled table | 68 KB |

### Correlation Table (all 8 pairs)

| Entity A | Entity B | Type | Pos | Neg | Total | Corr |
|----------|----------|------|:---:|:---:|:-----:|-----:|
| Meta | Alphabet | AI Infra Co-movement | 0 | 2 | 2 | **−1.00** |
| Meta | Tesla | Sector Peers | 0 | 1 | 1 | **−1.00** |
| Meta | Amazon | AI Infra Co-movement | 0 | 1 | 1 | **−1.00** |
| Alphabet | Amazon | AI Infra Co-movement | 0 | 1 | 1 | **−1.00** |
| OpenAI | Hugging Face | AI Security | 0 | 1 | 1 | **−1.00** |
| Apollo | State Street | Strategic Partnership | 1 | 0 | 1 | **+1.00** |
| U.S. Steel | Nippon Steel | M&A / Ownership | 1 | 0 | 1 | **+1.00** |
| Union Pacific | Norfolk Southern | Sector Peers | 1 | 0 | 1 | **+1.00** |

### Preview

![Full heatmap Oct 23](https://raw.githubusercontent.com/abdelhaknezzariiphone-hue/businessRelations/main/2026-10-23_09-55-26/heatmap_full.png)

![All pairs table Oct 23](https://raw.githubusercontent.com/abdelhaknezzariiphone-hue/businessRelations/main/2026-10-23_09-55-26/table_all_pairs.png)

---

## Session 11

**Folder:** [2026-10-24_11-40-49](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-24_11-40-49)

### Files

| File | Description | Size |
|---|---|---|
| [README.md](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-24_11-40-49/README.md) | Session report | 3.9 KB |
| [heatmap_full.png](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-24_11-40-49/heatmap_full.png) | Full 16×16 entity correlation matrix | 99 KB |
| [heatmap_stocks.png](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-24_11-40-49/heatmap_stocks.png) | Traded stocks heatmap | 94 KB |
| [heatmap_stocks_lollipop.png](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-24_11-40-49/heatmap_stocks_lollipop.png) | Pairwise ranking lollipop | 61 KB |
| [table_all_pairs.png](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-24_11-40-49/table_all_pairs.png) | All 13 pairs styled table | 104 KB |
| [table_stocks.png](https://github.com/abdelhaknezzariiphone-hue/businessRelations/tree/main/2026-10-24_11-40-49/table_stocks.png) | 7 traded pairs styled table | 71 KB |

### Correlation Table (all 13 pairs)

| Entity A | Entity B | Type | Pos | Neg | Total | Corr |
|---|---|---|---|---|---|---|
| Meta | Procter & Gamble | Investor Rotation | 0 | 1 | 1 | **-1.00** |
| SpaceX | AT&T | Direct Competition | 0 | 1 | 1 | **-1.00** |
| SpaceX | Verizon | Direct Competition | 0 | 1 | 1 | **-1.00** |
| Anthropic | SpaceX | IPO Benchmark | 1 | 0 | 1 | **+1.00** |
| Apple | Nvidia | Market Cap Benchmark | 1 | 0 | 1 | **+1.00** |
| Check Point | Palo Alto Networks | Sector Peers | 1 | 0 | 1 | **+1.00** |
| Harvard | SpaceX | Financial Backing | 1 | 0 | 1 | **+1.00** |
| OpenAI | Robinhood | Strategic Investment | 1 | 0 | 1 | **+1.00** |
| OpenAI | SpaceX | Co-Investment Portfolio | 1 | 0 | 1 | **+1.00** |
| SpaceX | Robinhood | Strategic Investment | 1 | 0 | 1 | **+1.00** |
| SpaceX | Tesla | M&A Speculation | 1 | 0 | 1 | **+1.00** |
| Stanford | SpaceX | Financial Backing | 1 | 0 | 1 | **+1.00** |
| UNC | SpaceX | Financial Backing | 1 | 0 | 1 | **+1.00** |

### Preview

![Full Heatmap](https://raw.githubusercontent.com/abdelhaknezzariiphone-hue/businessRelations/main/2026-10-24_11-40-49/heatmap_full.png)

![All Pairs Table](https://raw.githubusercontent.com/abdelhaknezzariiphone-hue/businessRelations/main/2026-10-24_11-40-49/table_all_pairs.png)