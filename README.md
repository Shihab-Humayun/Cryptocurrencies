# Cryptocurrencies

## Summary
In this project, I preprocessed the dataset in order to perform Principal Component Analysis. I have also applied the Principal Component Analysis (PCA) algorithm to reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame. Using my knowledge of the K-means algorithm, I created an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created. Then, I ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data. Using  knowledge of creating scatter plots with Plotly Express and hvplot, I visualized the distinct groups that correspond to the three principal components created. I created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

## Results Displayed Through Images
### Preprocessed Data
![image](https://user-images.githubusercontent.com/49353083/122832852-fbc97a00-d2b9-11eb-8f33-eb5625f62ff8.png)

### Elbow Curve Used To Find Best Value For k
![image](https://user-images.githubusercontent.com/49353083/122832921-17348500-d2ba-11eb-863c-ef51add895dc.png)

### DataFrame With Predicted Clusters And Cryptocurrencies Features
![image](https://user-images.githubusercontent.com/49353083/122833022-41864280-d2ba-11eb-972b-8e86956acc0d.png)

### 3D Scatter Plot with PCA Data And Clusters
![image](https://user-images.githubusercontent.com/49353083/122833087-5b278a00-d2ba-11eb-9368-4e051615bb6a.png)

### 2D Scatter Plot Using TotalCoinsMined And TotalCoinSupply
![image](https://user-images.githubusercontent.com/49353083/122833164-7d210c80-d2ba-11eb-85e1-eb954c7963c2.png)
