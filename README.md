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

# Usage guide (No coding required!)
## [Recommended] On Google Colab
1. Go to [Google Colab](https://colab.research.google.com/)
2. Click on **GitHub** tab and search for **https://github.com/cmb-chula/fetal-pulm-artery-doppler-percentile**
    * This screen can also be launched by selecting **File** -> **Open notebook** or pressing **Ctrl + O**
3. The main file **predict_fetal_artery_doppler_percentiles.ipynb** should appear as below
    * We have provided two user interface options: one with *sliders* and one with *text boxes*

![Colab's Github search screen](https://github.com/cmb-chula/fetal-pulm-artery-doppler-percentile/blob/main/images/colab_github_screen.png)

4. Click to open the file and follow the instructions as shown below

![Main notebook screen](https://github.com/cmb-chula/fetal-pulm-artery-doppler-percentile/blob/main/images/main_notebook_screen.png)

## [For Advanced Users] On Local Machine
1. Install Python
2. Install the following Python package
  * pandas == 1.5.2 (latest version should be ok)
  * numpy == 1.23.5 (latest version should be ok)
  * scikit-learn == 1.2.0
  * jupyter == 1.0.0 (ipywidgets should come with jupyter)
3. The notebook .ipynb files provided can be run as is
