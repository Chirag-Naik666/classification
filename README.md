# classification
Telco Customer Churn Prediction.

### About the project-
   In this project I am using various classification algorithms to predict the customer churn using the features in the dataset.

### Python Packages used- Pandas,Numpy,Scipy,scikit-learn,Seaborn and matplotlib.

### About the data set :-
   Each row represents a customer, each column contains customer’s attributes described on the column Metadata.
The data set includes information about:
Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents

### Acknowledgements-
Downloaded the Dataset from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)

### This project involves-
1) **Exploratory data analysis-**
   Dropping unnecessary features, treating the null values and outliers if any. Univariate and Bivariate analysis using KDE plot, boxplots and also Barplot of the independendent features with the target variable.

2) **Feature transformation-**
   Scaling the numeric value and "get_dummies" on the categorical variables

3) **Building Various Classification models-**
   Various algorithms like Naive Bayes, SVM, Linear Discriminant Analysis also boosting algorithms like Adaboost and XG boost are used.

4) **Selection of the Best Model-**
   ALL the models are compared on their precision and recall on both training and testing dataset. the best one is chosen after proper evaluation.
   
### Conclusion- 
Linear Discriminant Analysis algorithm is used for the prediction.

![Confusion Matrix](https://github.com/Chirag-Naik666/classification/blob/main/confusion_matrix.JPG)
