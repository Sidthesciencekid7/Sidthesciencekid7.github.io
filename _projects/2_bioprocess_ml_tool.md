---
layout: page
title: Bioprocess ML Tool
description: Streamlit app that analyzes time-series bioprocess runs and calculates titer and yield
importance: 2
category: work
---

A Streamlit app for analyzing bioprocess runs (CHO, microbial, fermentation, or any time-series bioprocess data). Upload a dataset and it calculates titer and yield, trains models, and produces a report.

**Features**

- Two models, Random Forest and XGBoost, with cross-validated metrics.
- SHAP explanations showing each feature's impact on the prediction, beyond simple importance scores.
- Process flags with adjustable thresholds for ammonia, glucose, viable cell density, lactate-to-glucose ratio and spikes.
- Correlation heatmap to spot redundant or co-varying features, and multi-run overlay plots to compare batches.
- PDF and Excel reports with timestamped file names.
- Works with any CSV or Excel file with numeric columns; it detects the target, time and group columns automatically, and reads the CDPpy Excel format directly.

**Stack:** Python, Streamlit, scikit-learn, XGBoost, SHAP.

[Source code on GitHub](https://github.com/Sidthesciencekid7/bioprocess-ml-tool)
