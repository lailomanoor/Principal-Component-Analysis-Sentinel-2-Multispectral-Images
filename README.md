# PCA (Principal Component Analysis) Project

## Overview

This project demonstrates the application of Principal Component Analysis (PCA) on a dataset to reduce its dimensionality and visualize the results. PCA is a statistical technique that transforms the data into a set of orthogonal components that capture the maximum variance. This project involves analyzing and visualizing spectral image data.

## Steps and Tasks

### 1. Import Libraries and Load Dataset

The necessary libraries for handling data manipulation, visualization, and PCA computation are imported. The dataset, which is a 3D array representing stacked spectral image bands, is loaded.

### 2. Data Visualization

The individual bands of the stacked image and a grayscale image created by averaging all bands are displayed using subplots.

### 3. Reshape and Standardize Data

The 3D array of the stacked image is reshaped into a 2D array and standardized to ensure similar scales for all variables (bands).

### 4. Calculate Covariance Matrix

The covariance matrix of the standardized data is computed.

### 5. Eigenvalues and Eigenvectors

Eigenvalues and eigenvectors of the covariance matrix are calculated and sorted in descending order.

### 6. Dimensionality Reduction

The number of principal components (k) is selected by analyzing the mean squared error for different values of k. The data is then reduced to the top k principal components.

### 7. Reconstruct Data and Visualization

The reduced data is reconstructed back to the original spectral space and visualized as a grayscale image. The error for each data point before and after applying PCA is calculated and visualized using a histogram.
