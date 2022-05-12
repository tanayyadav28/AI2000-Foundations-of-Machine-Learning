# Introduction

Here, the **sklearn** implementation of the Support Vector Classifier is used to draw conclusions from 2 datasets:
1. US Postal Zip Code Dataset
2. Gisette Dataset

# US Postal Zip Code Dataset

The softmargin SVM is applied on the handwritten digits. A **one-vs-one** classifier is trained for the digits **1** and **5**. Here observations were drawn on 
the Linear, Polynmomial and RBF kernels. For the Polynomial kernel different values of the degree were tried. All the kernels were tried with different gamma values.

# Gisette Dataset

The dataset is available at: https://archive.ics.uci.edu/ml/datasets/Gisette

The problem is to separate the highly confusible digits **4** and **9**. Here also the softmargin SVM is applied on the dataset. 6000 samples are used to train the 
Support Vector Classifier using the Linear, Polynomial and RBF kernels on different gamma values.

# Requirements

numpy == 1.19.2
sklearn == 0.23.2
pandas == 1.1.3
