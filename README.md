# Histopathologic Cancer Detection

Author: Alessio Tamburro

Date: 04/28/2021

Status: Need to explore/research stain normalization in pathology images. I expect this to improve significantly the CNN modeling approach. Also, I trained on my own laptop. I need to use more CPUs to experiment better.

The data (and idea) for this project is available from Kaggle at https://www.kaggle.com/c/histopathologic-cancer-detection/data

Objective:
Predict a positive label indicating that the center 32x32px region of a patch image contains at least one pixel of tumor tissue. Tumor tissue in the outer region of the patch does not influence the label (this outer region is provided to enable fully-convolutional models that do not use zero-padding, to ensure consistent behavior when applied to a whole-slide image).

This project is organized as follows (jupyter notebook): 
1. Explore XGBoost modeling approach (0.88 on leaderboard)
2. Explore CNN based modeling approach using fine tuning of open-sourced model (0.73 on leaderboard).

data: https://www.kaggle.com/c/histopathologic-cancer-detection/data (the notebook explains how to retrieve the data from Kaggle)

The notebook explaining the approach is available in this repo. If the notebook does not load, you can copy its linnk
https://github.com/alessiot/Histopathologic-Cancer-Detection/blob/main/Histopathologic%20Cancer%20Detection.ipynb and paste it at https://nbviewer.jupyter.org/ or just use this link https://nbviewer.jupyter.org/github/alessiot/Histopathologic-Cancer-Detection/blob/main/Histopathologic%20Cancer%20Detection.ipynb. However, this display will not show the entire output.

