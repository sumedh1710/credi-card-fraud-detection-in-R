# credi-card-fraud-detection-in-R

Credit Card Fraud Detection
This project aims to detect fraudulent credit card transactions using various machine learning models. The dataset used for this analysis is highly imbalanced, with a majority of transactions being genuine and a small minority being fraudulent. The project involves data loading and preprocessing, exploratory data analysis, data preparation, and building predictive models. The performance of the models is evaluated and compared to determine the most effective model for fraud detection.

Table of Contents
Data Loading and Pre-processing
Exploratory Data Analysis
Distribution of Class
Analysis of Transaction Amount
Analysis of Time
Data Preparation
Predictive Model Analysis
Logistic Regression Model
Decision Tree Model
K-Nearest Neighbors Model
Comparison of Models and Evaluation
Conclusion
Data Loading and Pre-processing
The dataset is loaded and pre-processed to remove any missing values and prepare it for analysis. Libraries such as ranger, caret, data.table, readr, class, dplyr, tidyr, and pROC are used for various tasks throughout the project.

Exploratory Data Analysis
Distribution of Class
The distribution of genuine and fraudulent transactions is highly imbalanced. This section includes a visualization of the class distribution.

Analysis of Transaction Amount
The distribution of transaction amounts is analyzed, revealing that most transactions involve smaller amounts. Fraudulent transactions exhibit two peaks, indicating distinct behaviors compared to genuine transactions.

Analysis of Time
The transaction times are analyzed, showing patterns that may reflect busier periods during the day or week. Fraudulent transactions do not follow these patterns as clearly as genuine transactions.

Data Preparation
The data is normalized and split into training and test sets. Due to the class imbalance, resampling is performed to balance the classes and avoid overfitting.

Predictive Model Analysis
Logistic Regression Model
A logistic regression model is fitted to the balanced training set. The model's performance is evaluated using metrics such as the confusion matrix, accuracy, and AUC (Area Under the Curve).

Decision Tree Model
A decision tree model is fitted, and its performance is evaluated similarly to the logistic regression model.

K-Nearest Neighbors Model
A KNN model is fitted and evaluated. The model's performance is assessed using ROC curves, accuracy, and AUC.

Comparison of Models and Evaluation
The ROC curves and AUC values for all three models are compared to determine the most effective model. Additionally, a bar plot is created to visualize the accuracy of each model.

Conclusion
The analysis shows that the KNN model performed the best with an accuracy of 99.96%. Logistic Regression followed closely with an accuracy of 97.49%, and the Decision Tree model had the lowest performance with an accuracy of 97.23%.
