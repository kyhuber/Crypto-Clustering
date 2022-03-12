# Crypto_Clustering

This app analyzes cryptocurrency market data and performs statistical analysis to . The data is first collected from csv files and prepared. Next, the app normalizes the data for comparison across cryptocurrencies. As part of this analysis, the app creates plots to visualize the data.

The app uses KMeans modeling to create elbow curves, measure intertia, and identify the best value for k. Next, separate elbow curves are created with Primary Component Analysis. The analysis shows that the best value for k is the same in both plots.

The Crypto Clustering app creates value for the user by automating the analysis of how to cluster the market data. The app creates a framework that can be used to analyze any asset class across any time period for which there is data.

---

## Technologies

The Crypto Clustering App is written in Python 3.10.1 using Jupyter Lab. It is compatible with Mac and PC OS. It uses the Pandas libraries to collect, prepare, and analyze the data. Data visualization plots are rendered using Matplotlib. Scikit Learn provides the machine learning modules.

---

## Installation Guide

This app can be run in Gitbash or Terminal. The app and supporting files are located in this Github repository:
https://github.com/kyhuber/Crypto_Clustering
---

## Usage

To use the Crypto Clustering app, the user must upload CSV files with market data to the Resource folder. The app will then automatically do the analysis, plot the charts, and calculate the metrics.

---

## Contributors

The Crypto Clustering app was written by Kyle Huber in March 2022.

---

# Crypto_Clustering
