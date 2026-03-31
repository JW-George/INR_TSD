# Robust and Tuning-Free Time Series Decomposition via Implicit Neural Representations

---

## Supplementary table

**Table B.** Ablation results on synthetic datasets used in the original manuscript. We compare the performance of decoupled and joint learning strategies by varying the number of trend and seasonal layer nodes to analyze the sensitivity of the proposed architecture. Lower MSE and MAE indicate better performance. The best results are highlighted in bold.

|               |                  |           Joint           |                            |           Decoupled           |                               |
| :-----------: | :--------------: | :-----------------------: | :------------------------: | :---------------------------: | :---------------------------: |
|               |                  |           Trend           |        Seasonality         |             Trend             |          Seasonality          |
| # Trend Nodes | # Seasonal Nodes |  (MSE ± Std / MAE ± Std)  |  (MSE ± Std / MAE ± Std)   |    (MSE ± Std / MAE ± Std)    |    (MSE ± Std / MAE ± Std)    |
|      20       |        20        | 0.10 ± 0.08 / 0.18 ± 0.09 | 16.11 ± 8.82 / 3.77 ± 1.15 |  0.06 ± 0.04 /  0.15 ± 0.08   |   0.08 ± 0.05 / 0.17 ± 0.08   |
|               |        40        | 0.09 ± 0.06 / 0.17 ± 0.07 | 16.11 ± 8.82 / 3.77 ± 1.16 |  0.06 ± 0.04 /  0.15 ± 0.08   |   0.07 ± 0.05 / 0.16 ± 0.08   |
|               |        60        | 0.09 ± 0.06 / 0.19 ± 0.09 | 16.10 ± 8.82 / 3.77 ± 1.16 |  0.06 ± 0.04 /  0.15 ± 0.08   |   0.07 ± 0.05 / 0.16 ± 0.08   |
|      40       |        20        | 0.13 ± 0.08 / 0.22 ± 0.06 | 16.10 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.04 / 0.13 ± 0.06** |   0.06 ± 0.05 / 0.15 ± 0.06   |
|               |        40        | 0.12 ± 0.08 / 0.20 ± 0.08 | 16.10 ± 8.81 / 3.77 ± 1.16 | **0.05 ± 0.04 / 0.13 ± 0.06** | **0.05 ± 0.04 / 0.14 ± 0.06** |
|               |        60        | 0.13 ± 0.08 / 0.22 ± 0.08 | 16.10 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.04 / 0.13 ± 0.06** | **0.05 ± 0.04 / 0.14 ± 0.06** |
|      60       |        20        | 0.16 ± 0.09 / 0.24 ± 0.09 | 16.10 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.05 / 0.13 ± 0.07** |   0.06 ± 0.05 / 0.15 ± 0.06   |
|               |        40        | 0.12 ± 0.08 / 0.21 ± 0.07 | 16.10 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.05 / 0.13 ± 0.07** | **0.05 ± 0.05 / 0.15 ± 0.07** |
|               |        60        | 0.12 ± 0.07 / 0.23 ± 0.10 | 16.09 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.05 / 0.13 ± 0.07** | **0.05 ± 0.05 / 0.15 ± 0.07** |
