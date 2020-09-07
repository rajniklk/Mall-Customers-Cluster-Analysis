# Mall Customers Cluster Analysis

## Problem Statement
 
This data set is created only for the learning purpose of the customer segmentation concepts , also known as market basket analysis . I will demonstrate this by using unsupervised ML technique (KMeans Clustering Algorithm) in the simplest form.You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score. Problem Statement You own the mall and want to understand the customers like who can be easily converge Target Customers so that the sense can be given to marketing team and plan the strategy accordingly.

## Code and Resources Used

* Python Version: 3.7
* Packages: pandas, numpy, sklearn, matplotlib, Natural Language Toolkit, Regular expression

## Attributes

* CustomerId
* Gender
* Age
* Annual Income
* Spending Score (1-100)

## Data Handling

* Importing the libraries
* Data Preprocessing
* Using the elbow method to find the optimal number of clusters
* Training the K-Means model on the dataset
* Visualising the clusters

# Conclusions

* Now we have 4 different clusters grouped by Age and Spending Score.

* The analysis shows there is low score concentration in male gender (between 0 and 25 score points). In female gender, we have high concentration in ranges between 75 and 100 compared to male gender. In general, women have higher Spending Score than men.

* In other hand, the Annual Income distribution shows that in general, men have higher annual income than women. These two analysi together could give good insights for mall administrators.

* Senior Spending Scores concentrates in low and medium values; In high score valuation, adults have the highest levels; In gender comparison, young and senior women have higher Spending Score values than young and senior men.


