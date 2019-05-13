# Melanoma-detection
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)

## What it does
Classify a skin lesion into malignant or benign.

## Introduction
Melanoma cancer is a type of skin cancer which is not very common but can be fatal, if not detected in early stages. 
From all skin cancers, melanoma represents just 1% of cases, but 75% of deaths. However, early detection of Melanoma 
cancer is very critical, as the estimated 5-year survival rate for melanoma drops from over 99% if detected in its 
earliest stages to about 14% if detected in its latest stages. In this project we tried to build a classifier which, given a skin lesion image, could classify whether it is malignant or benign.

## Dataset
We used the dataset provided by the ISIC — International Skin Imaging Collaboration. To download the dataset
```
  1. Upload the .pkl dependencies to your Google drive.
  2. Open the downloadDataset.ipynb in Google Colab.
  3. Mount your drive.
  4. Run the cells.
```
Since the dataset is huge, it will take some time to download even using Colab's GPU, so be patient.

## Approach
Trained the dataset using Inception-V3 model then applied trasfer learning on it.

### To run
```
usingInception.ipynb
```

