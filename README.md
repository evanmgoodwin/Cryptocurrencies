# Cryptocurrencies

## Summary Analysis

For this challenge, we were tasked with performing unsupervised machine learning on a cryptocurrency dataset. The first step was to load and preprocess the data using Pandas. After the data was processed, properly encoded and scaled, we performed PCA (Principal Component Analysis) to reduce the number of features to three. We plotted an elbow curve to determine the ideal number of K clusters to use. After deciding on five, we ran a K-Means algorithm using five clusters and the three PCA features to determine which class each cryptocurrency belonged to. We then combined the original features with the PCA and class designations into a new dataframe.

For the final part of the analysis, we created three visualizations. The first, a 3D scatter plot showing the three PCA features, color-coded by class. The second, an hvplot table showing all the current tradable cryptocurrencies. The last visualization was a 2D scatter plot comparing the total coins mined values against the total coin supply values.
