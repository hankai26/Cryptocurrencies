# Cryptocurrencies

## Overview
This analysis is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped, and to create a classification system for the new cryptocurrencies investment. The data without known output is processed to fit the unsupervised machine learning models. A clustering algorithm is applied to group the cryptocurrencies. Finally, the data and findings are visualized for public.

## Results
This study consists of four technical analysis deliverables as followings.

- Deliverable 1: Preprocessing the Data for PCA using Pandas

- Deliverable 2: Reducing Data Dimensions Using PCA
The Principal Component Analysis (PCA) algorithm is applied to reduce the dimensions of the DataFrame and place these dimensions in a new DataFrame.

- Deliverable 3: Clustering Cryptocurrencies Using K-means
Using the K-means algorithm, we create an elbow curve using hvPlot to find the best value for K from the developed DataFrame. We then run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

- Deliverable 4: Visualizing Cryptocurrencies Results
By creating scatter plots with Plotly Express and hvplot, we conduct data visualization on the distinct groups that correspond to the principal components. A table is prepared with all the currently tradable cryptocurrencies using the hvplot.table() function.




