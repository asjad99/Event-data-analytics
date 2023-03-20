
Background:
Anomalies are often divided into point and pattern anomalies. Point anomalies are single instances of something abnormal, while 
pattern anomalies represent clusters of data that are abnormal.
Pattern anomalies are more difficult to detect because we must first be able to define a normal pattern, and then we 
could need more data to be able to classify that this pattern is anomalous compared to historical activity.

Point anomalies:

Given a sequence of real values, i.e., x = x1, x2, ..., xn, the task of time-series anomaly detection is to produce an output
sequence, y = y1,y2, ...,yn, where yi ∈ {0, 1} denotes whether xi is an anomaly point.

PATTERN ANOMALIES

Our aim here is to detect a continuous set of data points that are collectively anomalous even though the individual points 
may or may not be point anomalies. When we are looking for pattern anomalies 
the underlying assumption is that the raw data must show a pattern.

#### Libraries:

- TODS: TODS is a full-stack automated machine learning system for outlier detection on multivariate time-series data.
- skyline: Skyline is a near real time anomaly detection system.
- banpei: Banpei is a Python package of the anomaly detection.
- telemanom: A framework for using LSTMs to detect anomalies in multivariate time series data.
- DeepADoTS: A benchmarking pipeline for anomaly detection on time series data for multiple state-of-the-art deep learning methods.
- NAB: The Numenta Anomaly Benchmark: NAB is a novel benchmark for evaluating algorithms for anomaly detection in streaming, real-time applications.
- CueObserve: Anomaly detection on SQL data warehouses and databases.
- Chaos Genius: ML powered analytics engine for outlier/anomaly detection and root cause analysis.

#### Benchmarking:

Revisiting Time Series Outlier Detection: Definitions and Benchmarks
https://openreview.net/pdf?id=r8IvOsnHchr

#### Papers:

- Outlier detection for temporal data: A survey
- Detecting spacecraft anomalies using lstms and nonparametric dynamic thresholding
- Time-Series Anomaly Detection Service at Microsoft
- Revisiting Time Series Outlier Detection: Definitions and Benchmarks
- Graph-Augmented Normalizing Flows for Anomaly Detection of Multiple Time Series

Possible Approach:

1. Use TODS library and pycaret
2. use deep learning:
