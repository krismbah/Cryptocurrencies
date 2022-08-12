# Cryptocurrencies

## Overview

The purpose of this analysis is to put all these skills to use by creating an analysis for your clients who are preparing to get into the cryptocurrency market. In order to create a report that includes which cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment, the following tasks are to be completed: 

1. Preprocessing the Data for PCA.
2. Reducing Data Dimensions Using PCA.
3. Clustering Cryptocurrencies Using K-means.
4. Visualizing Cryptocurrencies Results.

## Results


***Deliverable 1: Preprocessing the Data for PCA***
Using knowledge of Pandas, preprocess the dataset in order to perform PCA in Deliverable 2:

Figure 1:

![Image1](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D1.png)


Figure 1.1:

![Image1.1](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D1.1.png)


Figure 1.2:

![Image1.2](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D1.2.png)


Figure 1.3:

![Image1.3](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D1.3.png)



***Deliverable 2: Reducing Data Dimensions Using PCA***
Using knowledge of how to apply the Principal Component Analysis (PCA) algorithm, reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame:

Figure 2:

![Image2](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D2.png)



***Deliverable 3: Clustering Cryptocurrencies Using K-means***
Using knowledge of the K-means algorithm, create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data:

Figure 3:

![Image3](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D3.png)


Figure 3.1:

![Image3.1](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D3.1.png)


Figure 3.2:

![Image3.2](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D3.2.png)




***Deliverable 4: Visualizing Cryptocurrencies Results***
Using knowledge of creating scatter plots with Plotly Express and hvplot, visualize the distinct groups that correspond to the three principal components  created in Deliverable 2, then create a table with all the currently tradable cryptocurrencies using the hvplot.table() function

Figure 4:

![Image4](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D4.jpg)


Figure 4.1:

![Image4.1](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D4.1.jpg)


Figure 4.2:

![Image4.2](https://raw.githubusercontent.com/krismbah/Cryptocurrencies/main/D4.2.jpg)

