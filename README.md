# Histopathologic Cancer Detection

Data available from Kaggle at https://www.kaggle.com/c/histopathologic-cancer-detection/data

Objective: Predict a positive label indicating that the center 32x32px region of a patch image contains at least one pixel of tumor tissue. Tumor tissue in the outer region of the patch does not influence the label (this outer region is provided to enable fully-convolutional models that do not use zero-padding, to ensure consistent behavior when applied to a whole-slide image).

