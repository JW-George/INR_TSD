# Robust and Tuning-Free Time Series Decomposition via Implicit Neural Representations

---

## Supplementary table

**Table B.** Ablation (작성중)

ablation 실험 결과 on synthetic datasets used in the original manuscript. decoupled learning strategy와 Joint learning strategy를 적용

Comparison of seasonality decomposition performance on 100 SCN datasets. The robustness of seasonality estimation under three downsampling strategies (irregular, sparse, missing) is evaluated using MAE metrics. INR-TSD demonstrates overall superior seasonality decomposition performance. We will further strengthen this comparison by incorporating a wider range of methodologies and evaluation metrics.

|                         |                          |      Joint strategy       |                            |      Decoupled strategy       |                               |
| :---------------------: | :----------------------: | :-----------------------: | :------------------------: | :---------------------------: | :---------------------------: |
|                         |                          |           Trend           |           Season           |             Trend             |            Season             |
| N. of Trend layer nodes | N. of Season layer nodes |  (MSE ± Std / MAE ± Std)  |  (MSE ± Std / MAE ± Std)   |    (MSE ± Std / MAE ± Std)    |    (MSE ± Std / MAE ± Std)    |
|           20            |            20            | 0.10 ± 0.08 / 0.18 ± 0.09 | 16.11 ± 8.82 / 3.77 ± 1.15 |  0.06 ± 0.04 /  0.15 ± 0.08   |   0.08 ± 0.05 / 0.17 ± 0.08   |
|                         |            40            | 0.09 ± 0.06 / 0.17 ± 0.07 | 16.11 ± 8.82 / 3.77 ± 1.16 |  0.06 ± 0.04 /  0.15 ± 0.08   |   0.07 ± 0.05 / 0.16 ± 0.08   |
|                         |            60            | 0.09 ± 0.06 / 0.19 ± 0.09 | 16.10 ± 8.82 / 3.77 ± 1.16 |  0.06 ± 0.04 /  0.15 ± 0.08   |   0.07 ± 0.05 / 0.16 ± 0.08   |
|           40            |            20            | 0.13 ± 0.08 / 0.22 ± 0.06 | 16.10 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.04 / 0.13 ± 0.06** |   0.06 ± 0.05 / 0.15 ± 0.06   |
|                         |            40            | 0.12 ± 0.08 / 0.20 ± 0.08 | 16.10 ± 8.81 / 3.77 ± 1.16 | **0.05 ± 0.04 / 0.13 ± 0.06** | **0.05 ± 0.04 / 0.14 ± 0.06** |
|                         |            60            | 0.13 ± 0.08 / 0.22 ± 0.08 | 16.10 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.04 / 0.13 ± 0.06** | **0.05 ± 0.04 / 0.14 ± 0.06** |
|           60            |            20            | 0.16 ± 0.09 / 0.24 ± 0.09 | 16.10 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.05 / 0.13 ± 0.07** |   0.06 ± 0.05 / 0.15 ± 0.06   |
|                         |            40            | 0.12 ± 0.08 / 0.21 ± 0.07 | 16.10 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.05 / 0.13 ± 0.07** | **0.05 ± 0.05 / 0.15 ± 0.07** |
|                         |            60            | 0.12 ± 0.07 / 0.23 ± 0.10 | 16.09 ± 8.82 / 3.77 ± 1.16 | **0.05 ± 0.05 / 0.13 ± 0.07** | **0.05 ± 0.05 / 0.15 ± 0.07** |
