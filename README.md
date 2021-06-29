# Project-customer-segmentation
### Clustering Project

<img src="https://github.com/jatin090/Project-customer-segmentation/blob/main/clusters.gif" width="70%"/>

The aim was to analyzing the content of an E-commerce database that lists purchases made by  ∼ 4000 customers over a period of one year (from 2010/12/01 to 2011/12/09). Based on this analysis, I developed a model that allows to anticipate the purchases that will be made by a new customer, during the following year and this, from its first purchase.

  
Exploring the content of variables |
------------:|
Countries |
Customers and products |
Cancelling orders |
Insight on product categories |
<B>Product description |
Defining product categories |
Data encoding |
Clusters of products |
Characterizing the content of clusters |
<B>Formating data |
Grouping products |
Time spliting of the dataset |
Grouping orders |
Creating customer categories |
Data enconding |
Creating categories |
<B>Classifying customers |
Confusion matrix |
k-Nearest Neighbors |
Decision Tree |
Random Forest |
<B>Conclusion |
  
  

### After exploring, I have cleaned the dataset and chose only a few features which was important in order to carry out the training 

There were 8 features in total, from which I have combined a few and made only 3 features.

From those three, I first plotted the cluster with random value 4, but later on we checked it with 2 different techniques

I have used the Elbow method for having the range of cluster numbers -  we had range [3,8]

I checked this range, by the help of Silhoutte Score, the number 3 was giving the highest score in the given data, so I have chosen k = 3

At the end I have plotted the cluster visualization with 3 different clusters
