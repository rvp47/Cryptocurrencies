# Cryptocurrencies

![image](https://user-images.githubusercontent.com/90656004/153921477-07ef6e6e-f9d9-480a-9944-e87bac03440e.png)

## Overview of Analysis

The purpose of this analysis is to evaluate what cryptocurriencies are on the trading market and how they could be grouped to create a classification for a new cryptocurrency investment portfolio. The dataset was processed to fit the machine learning models using the Principal Component Analysis algorithm and grouped using a clustering algorithm (K-mean algorithm). Visualizations that represent the portfolio options have been provided. 

- Preprocessing the Data for PCA
- Reducing Data Dimensions Using PCA
- Clustering Cryptocurrencies Using K-means
- Visualizing Cryptocurrencies Results

## Visualizations

Using the K-means algorithm, this elbow curve was created to predict the K clusters for the cryptocurrencies' data.
![Elbow_Curve](https://user-images.githubusercontent.com/90656004/153777463-27d69b73-bc52-46bd-a549-b4a8059b5c7d.PNG)

A 3D scatter plot was created using Plotly Express to visualize the distinct groups that correspond to the three principle components from the Principle Component Analysis algorithm.
![3D_Scatter](https://user-images.githubusercontent.com/90656004/153777464-0e6d1380-a77d-497e-9c9f-7be4855cb561.PNG)

This table displays the currently tradable cryptocurrencies.
![hvplot_table](https://user-images.githubusercontent.com/90656004/153777466-167fd1ec-a79d-42d1-8bc3-6a45c9b36a18.PNG)

The scatter plot below was created using hvplot and MinMaxScaler for scaling the data. It shows the CoinName and Algorithm of each data point.
![hvplot_scatter](https://user-images.githubusercontent.com/90656004/153777468-b8ee579a-d89c-472e-85d6-2dc791f6240c.PNG)
