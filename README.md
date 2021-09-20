# Module 14 Trading Algorithm

## Overview of the Analysis

Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.

-------

### Prediction Result

* **Baseline Performance**
Using short (4) and long (100) window SMA with the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data

![markdown_image](https://github.com/JuneB2021/-Module-14-Challenge/blob/main/Plot/Baseline%20Performance.png)

* **Baseline Performance: Decreasing Training window**
Prediction improved by decreasing training window to 2 opposed to increasing training window to 4

![markdown_image](https://github.com/JuneB2021/-Module-14-Challenge/blob/main/Plot/Baseline%20Performance_adjusted_training2Months.png)

* **Baseline Performance: Decreasing SMA short window**
Prediction improved by decreasing short window to 3 opposed to decreasing long window to 50

![markdown_image](https://github.com/JuneB2021/-Module-14-Challenge/blob/main/Plot/Baseline%20Performance_adjusted_window3.png)

* **Baseline Performance: Decreasing SMA short window and Training window**
Prediction optimized by adjusting both SMA (Short window = 3) and Training window (=2)

![markdown_image](https://github.com/JuneB2021/-Module-14-Challenge/blob/main/Plot/Baseline%Performance_adjusted_both.png)

* **Random Forrest Classifier**
Prediction improvment over baseline (SVC classifier model) with same parameter

![markdown_image](https://github.com/JuneB2021/-Module-14-Challenge/blob/main/Plot/Baseline%20Performance_rf.png)

-------

## Summary

**Random Forrest Classifier** model overall is outperform **SVC Classifier** model when applying the same parameters
