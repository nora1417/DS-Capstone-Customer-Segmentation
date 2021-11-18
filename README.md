# DS-Capstone-Customer-Segmentation

Customer segmentation is a method of dividing customers into groups or clusters on the basis of common characteristics.  

It is important for businesses to understand their target audience.

In this project I am going to Segment customers based on their buying behavior on the market, using the K-Means algorithm in Python.


Data Set Information:

This is a transnational data set which contains all the transactions occurring in a year for a UK-based and registered non-store online retail.
Many customers of the company are wholesalers.
Dataset shape: 541909, 8
Source: Data World website https://data.world/iabhishek/customersegmentation/workspace/file?filename=customer_segmentation.csv

The two main steps of the project: 

A. Making clusters of products.

 Extracting useful information from the Description variable, using the content of this variable in order to group the products into different categories.

B. RFM segmentation. 

Creating columns to make RFM table such as Recency, Frequency, and Monetary column. 

By looking for certain metrics as when the customer buy the product for last time, how frequent the customer buy the product, and how much the customer pays for the product.

Conclusion:
cluster 0: is frequent and spend more also they buy the product recently.
cluster 1: is less frequent and less to spend, but they buy the product recently.
cluster 2 : is less frequent and less to spend, and they buy the product at old time.





1. Scikit-learn documentation [https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
2. **[Jason Brownlee](https://machinelearningmastery.com/author/jasonb/) ,**April 6, 2020[https://machinelearningmastery.com/clustering-algorithms-with-python/](https://machinelearningmastery.com/clustering-algorithms-with-python/)
3. Scikit-learn documentation [https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html](https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html)
4.  RFM Segmentation. [https://www.optimove.com/resources/learning-center/rfm-segmentation](https://www.optimove.com/resources/learning-center/rfm-segmentation)
5. Clustering: K-Means**.** [https://www.codecademy.com/learn/machine-learning/modules/dspath-clustering/cheatsheet](https://www.codecademy.com/learn/machine-learning/modules/dspath-clustering/cheatsheet)
6. Silhouette Coefficient ****[https://towardsdatascience.com/silhouette-coefficient-validating-clustering-techniques-e976bb81d10c](https://towardsdatascience.com/silhouette-coefficient-validating-clustering-techniques-e976bb81d10c)
7. Scikit-learn documentation [https://scikit-learn.org/stable/modules/clustering.html#k-means](https://scikit-learn.org/stable/modules/clustering.html#k-means)
