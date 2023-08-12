# Logistic-Regression
Logistic regression is one of the most popular machine learning algorithms, which comes under the supervised learning technique. 

It is used for predicting the categorical dependent variable using a given set of independent variables. 

Logistic regression predicts the output of a categorical dependent variable. Therefore the outcome must be a categorical or discrete value. 
It can be either Yes or No, 0 or 1, true or False, etc., but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.


## Implementation
- Importing the required libraries and reading the data file
- Performing EDA (Exploratory Data Analysis) on the data
- Performing Visualisations on the data
- Encoding of Categorical Variables
- Building Logistic Regression model on the dataset
- Prediction of the dependent variable using the independent variables
- Testing Accuracy of the model
  - Confusion Matrix
  - ROC Curve
- Identification of the insignificant variables
- Identifying the best threshold to increase the accuracy of the model


## Packages Used
- pandas
- numpy
- seaborn
- matplotlib.pyplot
- from sklearn.linear_model import LogisticRegression
- from sklearn import metrics
- from sklearn.metrics import classification_report
- from sklearn.metrics import roc_auc_score
- from sklearn.metrics import roc_curve
