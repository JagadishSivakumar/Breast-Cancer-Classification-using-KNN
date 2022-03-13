# Breast-Cancer-Classification-using-KNN
**Wisconsin Breast Cancer Classification using CNN**

### 1.1 About the Dataset
Wisconsin Breast Cancer dataset from the UCI Machine Learning Repository is a classification dataset containing records of breast cancer measurements.

The dataset contains `two classes, benign and malignant`

| Characteristics | Attributes | No. of Instances | No. of Attributes |
| --- | --- | --- | --- |
| Multivariate | Real | 569 | 32 |

### 1.2 K-Nearest Neighbours Algorithm What is K-NN?  
K-Nearest Neighbor (K-NN) is a classic example of a supervised machine learning algorithm for regression and classification tasks. 

K-NN uses the provided data and classifies new data points based on the similarity measures (such as EUCIidean or Manhattan distance) between the new data point and the data points in the training set.  

Unlike the traditional supervised learning approach KNN is unique with the two properties: `Lazy Learning and Non-parametric method`

  **a. Lazy Learning**  
  K-NN is a lazy learning algorithm because it doesn't learn the discriminative function from the supplied training data. Instead, it memorizes the training data and then uses it to predict the output. The generalization of the training data is delayed until a query is made.  

  **b. Non-parametric Method**
  The model parameters actually grow with the training set. We will need to keep all the training data for prediction later. This is unlike a parametric classifier(such as decision trees, linear, logistic regression) where, after finding the optimal parameters, we can use it for prediction.  
  
### Working and Predictions by K-NN  

K-NN works by finding the distance between a query and all the training data points and votes for the most frequent label. 

The distance is calculated using the similarity measures (such as EUCIidean or Manhattan distance), classifies new data points based on similarity. 

**Types of problem KNN is used?**

- K-NN can be used to solve classification and regression problems 
- Used for non-linear data (non-linear relation between dependent and independent variables) 
- Quick ad-hoc analysis on data, simple tunable parameter 
- Outlier detection on large datasets


View on Kaggle - [Wisconsin Breast Cancer Classification using KNN](https://www.kaggle.com/jagadish13/wisconsin-breast-cancer-classification-using-knn) 
