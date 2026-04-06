# Robust and Tuning-Free Time Series Decomposition via Implicit Neural Representations



## Supplementary figure

**Figure B.** Performance of INR-TSD on irregularly sampled real data. INR-TSD has been tested on the real-world dataset consisting of urine measurements collected from patients for the ICU mortality prediction task (https://physionet.org/content/challenge-2012/1.0.0/). This dataset is irregularly sampled and does not provide ground-truth trend or seasonality components. Applying INR-TSD yields a meaningful qualitative separation of trend and seasonal components

| <img src="https://anonymous.4open.science/r/INR_TSD-FC7B/figure/figure_B.png" width="800px"> |
| :----------------------------------------------------------: |
|                 (i) ours, pyBOAT, Rebust STL                 |
| <img src="https://anonymous.4open.science/r/INR_TSD-FC7B/figure/figure_B_2.png" width="800px"> |
|                    (ii) STL, MSTL, HP, CF                    |

|            |     Trend      |    Seasonal    |
| :--------: | :------------: | :------------: |
|            |  (MSE / MAE)   |  (MSE / MAE)   |
|    ours    |  3.46 / 1.47   |  15.36 / 2.84  |
|   PyBoat   |  5.66 / 1.97   |    N/A $^1$    |
| Robust STL | 203.25 / 11.07 | 197.68 / 11.33 |
|    MSTL    |  24.73 / 2.29  |  75.08 / 6.14  |
|    STL     |  7.52 / 1.78   |  63.92 / 5.82  |
| HP filter  |  8.46 / 1.66   |    N/A $^1$    |
| CF filter  |  5.92 / 1.94   |    N/A $^1$    |

$^1$ PyBOAT, HP, and CF filter do not provide an explicit seasonal decomposition; hence, the seasonal metrics are not applicable.
