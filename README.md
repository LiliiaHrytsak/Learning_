# Learning_
Practicing classic machine learning models.

Repository contains a set of my mini-projects in which I practiced my skills in applying different types of classical machine learning.

### **EDA_Vizualization**
The Exploratory Data Analysis of the House Prices dataset was carried out. I used data from [Kaggle competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) or file train.csv which is in this directory. Different visualization methods (numpy.triu, seaborn.heatmap, seaborn.pairplot) were used to study the correlation between the features. Hypotheses about differences in terms of features were formulated. The analysis of the missing values in the dataset  was carried out (missingno.matrix, missingno.bar, missingno.heatmap).

### **k-Mean_Clasterisation** 
The user segmentation based on their recency and frequency and on their costs was carried out. I used the dataset from the following source:https://archive.ics.uci.edu/ml/datasets/online+retail or file Online Retail.csv which is in this directory. The Recency-Frequency-Monetary analysis for further segmentation was conducted. A log transformation was performed on the variables to reduce the skewness of each variable. The Winsorizing technique was used to clean the tails in the data. The optimal number of clusters was found using the Elbow Method. For k = 3,4,5 segmentation of customers was carried out using TSNE dimensionality reduction and visual representation of segmentation. In addition, for such k  the Snake plots were drawn.

### **Linear_Regression_&_Polynomial_Regression**
Work with the data set on the level of happiness in countries for 2019. Data were taken from the  Kaggle [competition](https://www.kaggle.com/unsdsn/world-happiness?select=2019.csv) or file 2019.csv which is in this directory. The problem of univariate linear regression using the gradient descent method was solved. MinMaxScaler was used for feature scaling. Also,  sklearn.linear_model was used to build univariate and multivariate linear regression. A polynomial regression model (PolynomialFeatures was used in the learning process) with degree 2 was trained on the same data. Mean square errors were measured and analyzed for all obtained models.

### **Logistic_Regression_&_Decision_Tree**
Work with the following dataset: https://archive.ics.uci.edu/ml/datasets/car+evaluation or 
file car+evaluation.csv which is in this directory. The goal is to predict the car class according to its characteristics. The class can be unacceptable, acceptable, good, or very good.OrdinalEncoder from sklearn.preprocessing was used to encode test and training samples. The logistic regression model was trained on the data using LogisticRegression from sklearn.linear_model. Also, I built two different decision tree models for the same data. The first model with the specified hyperparameter max_depth = 4, and  the other - with selected optimal hyperparameters (used a GridSearchCV for it). Classification_report and confusion matrix was used to analyze metrics for all obtained models.

### **Validate_Hyperparameters_&_Decision_Tree**
It's the biggest mini-project of all those and includes all skills I used in previous mini-projects.  I used data from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) or file heart_disease.csv which is in this directory. The goal was to predict possible heart disease. Deep exploratory analysis, which includes the analysis of missing values (analysis of outliers (using the Interquartile Range Rule and boxplots) and searching for a correlation between features, was carried out. The searching optimal hyperparameters were conducted for the Decision Tree model. A comparison between chosen metrics of the default decision tree model and the improved decision model was carried out. Also, Precision-Recall Curve and ROC Curve were drawn. 
