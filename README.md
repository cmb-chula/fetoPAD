# Introduction
Percentile predictor for fetal doppler parameters, with gestation age (GA) and fetal heart rate (FHR) as inputs

Currently supported parameters:
1. AT
2. AT/ET
3. EDV
4. ET***
5. PDV
6. PEDRF
7. PEDRF/PSV
8. PSV***
9. SNV
10. SNV/PSV
11. TSN
12 TSN/ET

***ET and PSN require both GA and FHR as inputs

The manuscript describing the data and model is being prepared. Please check back later for more details of this work.

# Usage guide
## [Recommended for non-programmer] On Google Colab
1. Open *predict_fetal_doppler_percentiles.ipynb* on Google Colab
2. Follow the instruction in the notebook

## [For programmer] On Local Machine
1. Install Python
2. Install the following Python package
  * pandas == 1.5.2 (latest version should be ok)
  * numpy == 1.23.5 (latest version should be ok)
  * scikit-learn == 1.2.0
  * jupyter == 1.0.0 (ipywidgets should come with jupyter)
