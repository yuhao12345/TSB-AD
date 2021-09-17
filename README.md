# TSB-AUD: An End-to-End Anomaly Detection Benchmark Suite for Univariate Time-Series Data

TSB-UAD is a new end-to-end benchmark suite to ease the
evaluation of time-series anomaly detection methods. Overall, TSBUAD
contains 12686 time series with labeled anomalies spanning
different domains with high variability of anomaly types, ratios,
and sizes. Specifically, TSB-UAD includes 10 previously proposed
datasets containing 900 time series from real-world data science applications.
Motivated by flaws in datasets and evaluation strategies,
we study anomaly types and data transformations to contribute
two auxiliary datasets. Specifically, we generate 958 time series
using a principled methodology for transforming 126 time-series
classification datasets into time series with labeled anomalies. In
addition, we present a set of data transformations with which we
introduce new anomalies in the public datasets, resulting in 10828
time series with varying difficulty for anomaly detection.


## Installation

This package works with Python 3.8 and pip 21. You need to have the following packages installed on the system.

```
pip install -r requirements.txt
```

Clone the repository

```
git clone https://github.com/yuhao12345/TSB-AD.git
```

Install locally

```
cd TSB-AD-main
pip install .
```

## Examples
test_anomaly_detectors.ipynb, test_artificialConstruction.ipynb, and test_transformer.ipynb summarize the main contributions of this project.

## Benchmark 
In ./data contains four folders: 

1. benchmark/ contains ten public datasets
<img width="500" src="./docs/display_data.png"/>
3. UCR2018-NEW/ contains 128 subfolders 
4. artificial/ contains the data that are constructed based on UCR2018-NEW
5. synthetic/ contains the data that are synthesized by local and global tranformations

