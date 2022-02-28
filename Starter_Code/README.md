# The enclosed notebook utilizes machine learning concepts to cluster cryptocurrencies by their performance in different time periods. The provided CSV data is first clustered using K Means and then optimized to three features using Principal Components Analysis (PCA).
--

## Technologies

This challenge uses machine learning concepts like K Means and PCA to model the behavior of a list of cryptocurrencies and seven corresponding performance attributes.

--

## Installation Guide

New libraries learned in this module and required to run this notebook are from sklearn: cluster import KMeans, decomposition import PCA, and preprocessing import StandardScaler.

--

## Usage

First the dataframe is scaled. Best value for k is determined using an elbow graph. Then the elbow data is utilized to cluster performance using KMeans. The scaled dataframe is then clustered using PCA method. The two methods (or number of features) are compared at the end.

The best value for k in both methods is four.

The end result is that using fewer features with the PCA method yields very similar results as the KMeans (non PCA) method.


The two set of graphs below pertain to the last section and summarize most of the work done:
![Scatter Plots: Non-PCA and PCA](Images/elbows.PNG)

![Scatter Plots: Non-PCA and PCA](Images/scatter.PNG)


--

## Contributors
Angela Richter is the sole contributor to all files in this repository.

--

## Licenses

This notebook and related items in this repository is intended for learning purposes only.