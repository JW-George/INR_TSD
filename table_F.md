# Robust and Tuning-Free Time Series Decomposition via Implicit Neural Representations



## Supplementary table

**Table F.** Comparison of the computational cost–accuracy trade-off on the synthetic datasets used in the original manuscript. To analyze this trade-off, we vary the number of nodes in the trend and seasonality networks, resulting in different model configurations whose memory costs are measured accordingly. The memory cost is reported as the relative increase (%) with respect to the smallest configuration (baseline). Performance is evaluated in terms of MSE and MAE (± standard deviation), where lower values indicate better accuracy. The best results are highlighted in bold.

|               |                  |             Trend             |          Seasonality          | Memory cost |
| :-----------: | :--------------: | :---------------------------: | :---------------------------: | :---------: |
| # Trend Nodes | # Seasonal Nodes |    (MSE ± Std / MAE ± Std)    |    (MSE ± Std / MAE ± Std)    |   (bytes)   |
|      20       |        20        |  0.06 ± 0.04 /  0.15 ± 0.08   |   0.08 ± 0.05 / 0.17 ± 0.08   | (baseline)  |
|               |        40        |  0.06 ± 0.04 /  0.15 ± 0.08   |   0.07 ± 0.05 / 0.16 ± 0.08   | $+48.36\%$  |
|               |        60        |  0.06 ± 0.04 /  0.15 ± 0.08   |   0.07 ± 0.05 / 0.16 ± 0.08   | $+97.54\%$  |
|      40       |        20        | **0.05 ± 0.04 / 0.13 ± 0.06** |   0.06 ± 0.05 / 0.15 ± 0.06   | $+48.36\%$  |
|               |        40        | **0.05 ± 0.04 / 0.13 ± 0.06** | **0.05 ± 0.04 / 0.14 ± 0.06** | $+96.72\%$  |
|               |        60        | **0.05 ± 0.04 / 0.13 ± 0.06** | **0.05 ± 0.04 / 0.14 ± 0.06** | $+145.90\%$ |
|      60       |        20        | **0.05 ± 0.05 / 0.13 ± 0.07** |   0.06 ± 0.05 / 0.15 ± 0.06   | $+97.54\%$  |
|               |        40        | **0.05 ± 0.05 / 0.13 ± 0.07** | **0.05 ± 0.05 / 0.15 ± 0.07** | $+145.90\%$ |
|               |        60        | **0.05 ± 0.05 / 0.13 ± 0.07** | **0.05 ± 0.05 / 0.15 ± 0.07** | $+195.08\%$ |
