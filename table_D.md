# Robust and Tuning-Free Time Series Decomposition via Implicit Neural Representations

---

## Supplementary table

**Table D.** Impact of $\omega_0$ on decomposition performance. The impact SIREN’s $\omega_0$ is investigated by evaluating the performance of INR-TSD under different weight initialization intervals $[0, \omega_0]$. The results of this ablation study show that our default setting outperforms configurations where $\omega_0$ deviates from 1. This indicates that our normalization scheme effectively constrains the frequency values within the range $[0, 1]$.

|  $\omega_0$   |        0.5        |      1 (Default)      |         2         |         4         |        10         |        20         |        30         |
| :-----------: | :---------------: | :-------------------: | :---------------: | :---------------: | :---------------: | :---------------: | :---------------: |
| MAE $\pm$ STD | 0.246 $\pm$ 0.387 | **0.131 $\pm$ 0.051** | 0.139 $\pm$ 0.055 | 0.143 $\pm$ 0.035 | 0.140 $\pm$ 0.042 | 0.334 $\pm$ 0.244 | 0.366 $\pm$ 0.230 |
