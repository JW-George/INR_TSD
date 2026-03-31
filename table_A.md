# Robust and Tuning-Free Time Series Decomposition via Implicit Neural Representations



## Supplementary table

**Table A.** Comparison of seasonality decomposition performance on 100 SCN datasets. The robustness of seasonality estimation under three downsampling strategies (irregular, sparse, missing) is evaluated using MAE metrics. INR-TSD demonstrates overall superior seasonality decomposition performance. We will further strengthen this comparison by incorporating a wider range of methodologies and evaluation metrics.

|                |       Irregular       |        Sparse         |        Missing        |
| :------------: | :-------------------: | :-------------------: | :-------------------: |
|                |      (MAE ± Std)      |      (MAE ± Std)      |      (MAE ± Std)      |
|     (ours)     | **1.69e-3 ± 7.07e-4** | **1.54e-3 ± 6.28e-4** | **1.64e-3 ± 7.29e-4** |
|      STL       |   3.53e-3 ± 1.04e-3   |   4.40e-3 ± 1.34e-3   |   2.95e-3 ± 9.25e-4   |
|      RSTL      |   3.48e-3 ± 1.17e-3   |   3.22e-3 ± 1.08e-3   |   3.19e-3 ± 1.12e-3   |
|      MSTL      |   3.52e-3 ± 1.11e-3   |   4.22e-3 ± 1.30e-3   |   1.50e-3 ± 5.04e-4   |
| Moving Average |   4.24e-3 ± 1.40e-3   |   4.51e-3 ± 1.46e-3   |   4.43e-3 ± 1.45e-3   |

