# Introduction
This is the repository for percentile predictors for fetal pulmonary artery doppler parameters, **fetoPAD**

Each percentile prediction is made based on input gestation age (GA), fetal heart rate (FHR), and the measurement for the parameter of interest.

Warning will be raised if the input values are too low or too high (beyond the 2 SD range) of observations in our database.

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
## [Recommended] On Google Colab
1. Go to [Google Colab](https://colab.research.google.com/)
2. Click on **File** -> **Open notebook** or pressing **Ctrl + O**
3. Click on **GitHub** tab and search for **https://github.com/cmb-chula/fetoPAD**
4. The main file **predict_percentiles.ipynb.ipynb** should appear as below

![Colab's Github search screen](https://github.com/cmb-chula/fetoPAD/blob/main/images/colab_github_screen.png)

5. Click to open the file and follow the instructions

![Main notebook screen](https://github.com/cmb-chula/fetoPAD/blob/main/images/main_notebook_screen.png)

## [For Advanced Users] On Local Machine
1. Install Python
2. Install the following Python package
  * pandas == 1.5.2
  * numpy == 1.23.5
  * scikit-learn == 1.2.0
  * jupyter == 1.0.0
