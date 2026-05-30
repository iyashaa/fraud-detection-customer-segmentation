# Fraud Detection Customer Segmentation using Clustering

## Overview

This project applies unsupervised machine learning techniques to analyze financial transaction data and identify hidden patterns through clustering. The main objective of this project is to group data points with similar characteristics, which can later be used to support fraud risk analysis and customer behavior understanding.

## Dataset

The dataset used in this project was obtained from Google Drive.

Dataset link: [Google Drive Dataset Link]('https://docs.google.com/spreadsheets/d/e/2PACX-1vTbg5WVW6W3c8SPNUGc3A3AL-AG32TPEQGpdzARfNICMsLFI0LQj0jporhsLCeVhkN5AoRsTkn08AYl/pub?output=csv')

## Objectives

* Perform data cleaning and preprocessing.
* Explore the dataset using Exploratory Data Analysis (EDA).
* Apply clustering algorithms to group similar data points.
* Evaluate the clustering results using appropriate evaluation metrics.
* Interpret each cluster based on its characteristics.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Methodology

The workflow of this project includes several main steps. First, the dataset is loaded and cleaned to ensure that the data is ready for analysis. After that, Exploratory Data Analysis is performed to understand the distribution, patterns, and relationships between features.

Next, feature preprocessing is applied, including handling missing values, encoding categorical features if needed, and scaling numerical features. Then, a clustering algorithm is implemented to group the data into several clusters. The clustering results are evaluated and analyzed to understand the characteristics of each group.

## Result

The clustering model successfully grouped the dataset into several clusters based on similar transaction patterns and feature characteristics. These clusters can be used as a foundation for further analysis, especially in understanding potential fraud behavior and preparing labels for classification modeling.

## Conclusion

This project demonstrates how clustering can be used to discover hidden patterns in financial transaction data. The results of this clustering process can be useful for fraud risk analysis and can also be extended into a supervised learning task for classification.
