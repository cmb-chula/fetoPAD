# Introduction
This is the repository for percentile predictors for fetal pulmonary artery doppler parameters, **fetoPAD**

Each percentile prediction is made based on input gestation age (GA), fetal heart rate (FHR), and the measurement for the parameter of interest.

Currently supported parameters:
1. AT
2. AT/ET
3. EDV
4. ET***
5. MtrPI**
6. PDV
7. PEDRF
8. PEDRF/PSV
9. PI**
10. PSV***
11. SNV
12. SNV/PSV
13. TSN
14. TSN/AT**
15. TSN/ET

***ET and PSV require both GA and FHR as inputs

**MtrPI, PI, and TSN/AT do not change over time and are modeled using normal distributions

The manuscript describing the data and model is being prepared. Please check back later for more details of this work.

# Usage guide (no coding required!)
1. Click [here](https://colab.research.google.com/github/cmb-chula/fetoPAD/blob/main/predict_percentiles.ipynb) to open the main script in Google Colaboratory
2. Hit the play button to the left to run each block of the script

![Main Script on Google Colab](https://github.com/cmb-chula/fetoPAD/blob/main/images/main_notebook_screen.png)

3. The user interface will then show up at the bottom

![UI Page](https://github.com/cmb-chula/fetoPAD/blob/main/images/colab_ui_screen_witherr.png)

## Warning will be raised if the input values are too low or too high (beyond the 2 SD range) of observations in our database.
