# Lab-8
# K-Nearest Neighbors (KNN) Machine Learning Task

## Overview

This project demonstrates the use of the K-Nearest Neighbors (KNN) algorithm to perform binary classification. The dataset was preprocessed through feature scaling to ensure fair distance calculations, followed by splitting the data into training and testing subsets.

## Workflow

The following steps were carried out during the implementation:

1. Imported and inspected the dataset.
2. Applied feature scaling using StandardScaler.
3. Divided the dataset into training and testing portions.
4. Built a KNN classifier with varying values of K.
5. Evaluated model performance for each K value.
6. Visualized error rates to identify the optimal K.
7. Selected the most suitable K based on performance.
8. Trained the final model using the chosen K.
9. Assessed the model using confusion matrix and classification metrics.

## Optimal K Selection

After analyzing the error rates across multiple values, the most effective K was determined to be:

**K = 30**

## Performance Summary

The final trained model achieved an approximate accuracy of:

**0.82 (82%)**

## Project Files

* `KNN_Model.ipynb`
* `dataset.csv`
* `README.md`
