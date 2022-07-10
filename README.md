# Benchmarking person re-identification datasets and approaches for practical real-world implementations
Here we are going to publish complete results for our paper.
## Complete results for cross-dataset experiments
This section presents all the results from our cross-dataset Re-ID experiments. Four standard Re-ID approaches are trained on three different standard Re-ID datasets, and evaluated on a different dataset. The complete results from these experiments are reported in Table~\ref{tab:cross_full_res}, Table~\ref{tab:cross_full_res_pair} and Table~\ref{tab:cross_scal_full_res} .

| Train       | TEST        | Approach | Rank-1 | Rank-5 | Rank-10 | mAP  | mINP |
|-------------|-------------|----------|--------|--------|---------|------|------|
| CUHK03      | Market-1501 | AGW      | 0.54   | 0.67   | 0.73    | 0.29 | 0.05 |
|             |             | MGN      | 0.66   | 0.81   | 0.86    | 0.39 | 0.08 |
|             |             | SBS      | 0.60   | 0.75   | 0.80    | 0.34 | 0.07 |
|             |             | BoT      | 0.46   | 0.61   | 0.66    | 0.22 | 0.03 |
|             | DukeMTMC    | AGW      | 0.29   | 0.44   | 0.50    | 0.17 | 0.02 |
|             |             | MGN      | 0.50   | 0.65   | 0.70    | 0.31 | 0.04 |
|             |             | SBS      | 0.39   | 0.54   | 0.60    | 0.21 | 0.02 |
|             |             | BoT      | 0.19   | 0.30   | 0.36    | 0.10 | 0.01 |
|             | PRID        | AGW      | 0.07   | 0.14   | 0.18    | 0.11 | 0.11 |
|             |             | MGN      | 0.21   | 0.31   | 0.35    | 0.26 | 0.26 |
|             |             | SBS      | 0.14   | 0.25   | 0.29    | 0.20 | 0.20 |
|             |             | BoT      | 0.06   | 0.10   | 0.13    | 0.09 | 0.09 |
| DukeMTMC    | Market-1501 | AGW      | 0.53   | 0.68   | 0.75    | 0.26 | 0.03 |
|             |             | MGN      | 0.67   | 0.82   | 0.87    | 0.37 | 0.06 |
|             |             | SBS      | 0.61   | 0.77   | 0.82    | 0.31 | 0.03 |
|             |             | BoT      | 0.49   | 0.65   | 0.71    | 0.22 | 0.02 |
|             | CUHK03      | AGW      | 0.06   | 0.13   | 0.18    | 0.06 | 0.03 |
|             |             | MGN      | 0.14   | 0.26   | 0.34    | 0.14 | 0.07 |
|             |             | SBS      | 0.13   | 0.27   | 0.35    | 0.13 | 0.06 |
|             |             | BoT      | 0.05   | 0.10   | 0.15    | 0.05 | 0.03 |
|             | PRID        | AGW      | 0.08   | 0.15   | 0.20    | 0.12 | 0.12 |
|             |             | MGN      | 0.23   | 0.36   | 0.42    | 0.30 | 0.30 |
|             |             | SBS      | 0.12   | 0.22   | 0.26    | 0.17 | 0.17 |
|             |             | BoT      | 0.03   | 0.11   | 0.16    | 0.07 | 0.07 |
| Market-1501 | DukeMTMC    | AGW      | 0.37   | 0.52   | 0.58    | 0.22 | 0.03 |
|             |             | MGN      | 0.58   | 0.73   | 0.77    | 0.39 | 0.06 |
|             |             | SBS      | 0.54   | 0.68   | 0.74    | 0.34 | 0.05 |
|             |             | BoT      | 0.28   | 0.43   | 0.49    | 0.15 | 0.02 |
|             | CUHK03      | AGW      | 0.08   | 0.15   | 0.21    | 0.08 | 0.04 |
|             |             | MGN      | 0.22   | 0.38   | 0.47    | 0.22 | 0.13 |
|             |             | SBS      | 0.19   | 0.31   | 0.40    | 0.18 | 0.11 |
|             |             | BoT      | 0.04   | 0.11   | 0.15    | 0.04 | 0.02 |
|             | PRID        | AGW      | 0.14   | 0.22   | 0.26    | 0.19 | 0.19 |
|             |             | MGN      | 0.22   | 0.35   | 0.40    | 0.28 | 0.28 |
|             |             | SBS      | 0.15   | 0.24   | 0.30    | 0.20 | 0.20 |
|             |             | BoT      | 0.08   | 0.18   | 0.23    | 0.13 | 0.13 |

