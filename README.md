# Hierarchical-Clustering
implementation Hierarchical Clustering

# Steps 

## 1. <a name="1">Read the dataset</a> (<a href="#0">Go to top</a>)
First dowmload the data set from this link https://www.kaggle.com/fernandol/countries-of-the-world
then import it in python.

## 2. <a name="2">Data investigation</a>
(<a href="#0">Go to top</a>)

in this part you need to check the data quality and assess any issues in the data as:
- null values in each column 
- each column has the proper data type
- outliers
- duplicate rows
- distribution for each column (skewness)
<br>

## 3. <a name="3">Data preprocessing</a>
(<a href="#0">Go to top</a>)
### Define below all the issues that you had found in the previous part


## 4. <a name="4">Features transformation</a>
(<a href="#0">Go to top</a>)

*What is the feature scaling technique that would use and why?* <br>
*return to this section again and try another technique and see how that will impact your result*<br>
for more details on different methods for scaling check these links
- https://scikit-learn.org/stable/modules/preprocessing.html#preprocessing
- https://scikit-learn.org/stable/modules/classes.html#module-sklearn.preprocessing
- https://www.analyticsvidhya.com/blog/2020/07/types-of-feature-transformation-and-scaling/

## 5. <a name="5">Training and hyperparamter tuning</a>
(<a href="#0">Go to top</a>)

Before we start the training process we need to specify 3 paramters:<br>
1- Linkage criteria : The linkage criterion determines the distance between two clusters
    - Complete-Linkage Clustering
    - Single-Linkage Clustering
    - Average-Linkage Clustering
    - Centroid Linkage Clustering
2- Distance function:
    - Euclidean Distance 
    - Manhattan Distance 
    - Mahalanobis distance 
3- Number of clusters
