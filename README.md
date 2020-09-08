# Mall Customers Cluster Analysis

## Problem Statement
 
* Malls or shopping complexes are often indulged in the race to increase their customers and hence making huge profits. To achieve this task machine learning is being applied by many stores already.
* It is amazing to realize the fact that how machine learning can aid in such ambitions. The shopping complexes make use of their customers’ data and develop ML models to target the right ones. This not only increases sales but also makes the complexes efficient.
## Code and Resources Used

* Python Version: 3.7
* Packages: pandas, numpy, sklearn, matplotlib, Natural Language Toolkit, Regular expression

## Attributes

1. CustomerID: It is the unique ID given to a customer
2. Gender: Gender of the customer
3. Age: The age of the customer
4. Annual Income: It is the annual income of the customer
5. Spending Score: It is the score(out of 100) given to a customer by the mall authorities, based on the money spent and the behavior of the customer.

## Data Handling

* Importing the libraries
* Data Preprocessing
* Using the elbow method to find the optimal number of clusters
* Training the K-Means model on the dataset
* Visualising the clusters

## Visualization

![download](https://user-images.githubusercontent.com/35190179/92410882-42068000-f163-11ea-9ed1-1c7c938fcd21.png)

## Conclusions

* Now we have 4 different clusters grouped by Age and Spending Score.
* The analysis shows there is low score concentration in male gender (between 0 and 25 score points). In female gender, we have high concentration in ranges between 75 and 100 compared to male gender. In general, women have higher Spending Score than men.
* In other hand, the Annual Income distribution shows that in general, men have higher annual income than women. These two analysi together could give good insights for mall administrators.
* Senior Spending Scores concentrates in low and medium values; In high score valuation, adults have the highest levels; In gender comparison, young and senior women have higher Spending Score values than young and senior men.


