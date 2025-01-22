# SCT_DS_03

Task-03

Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

<img width="718" alt="image" src="https://github.com/user-attachments/assets/00e09b0d-96d6-48a2-9b22-cbb3c47c5363" />

# Project Title-Customer Purchase Prediction Using Decision Tree Classifier

# Project Introduction-
The ability to predict customer purchase behavior is a critical aspect of business success, enabling organizations to tailor marketing strategies, optimize resources, and enhance customer experiences. This project aims to build a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The dataset used for this project is the Bank Marketing dataset, sourced from the UCI Machine Learning Repository. It includes diverse features such as age, job type, marital status, education level, and past interactions, providing a comprehensive view of customer profiles.

# Project Summary-
This project involves analyzing customer data, identifying patterns, and applying machine learning techniques to build a predictive model. The dataset is preprocessed to handle missing values, remove outliers, and encode categorical variables. Exploratory data analysis is conducted to understand feature distributions and correlations. Using a Decision Tree Classifier, the model predicts whether a customer will purchase a product or service. The model's performance is evaluated using accuracy scores, confusion matrices, and visualization of decision-making processes. The project also explores hyperparameter tuning to optimize the model's performance.

# Business Objective-

The primary objective is to assist businesses in:

Predicting customer purchases based on their demographic and behavioral data.
Enhancing marketing efficiency by identifying high-potential customers for targeted campaigns.
Optimizing resources by focusing on customers most likely to convert, reducing marketing costs.
Improving customer experience by personalizing offers and services based on predictive insights.

# Step-by-Step Implementation
1. Exploratory Data Analysis (EDA) Performed basic dataset exploration using df.info(), df.describe(), and df.shape(). Checked for missing values and duplicates, and ensured data quality. Visualized data distributions: Histograms for numerical data. Count plots for categorical data using Seaborn.

2. Outlier Detection and Removal Used box plots to identify outliers in numerical columns. Calculated quartiles (Q1, Q3) and removed data outside acceptable bounds using the IQR method.

3. Feature Correlation Analysis Created a heatmap to visualize correlations between numerical features. Dropped highly correlated features to avoid multicollinearity.

4. Data Preprocessing Encoded categorical variables using LabelEncoder. Split the dataset into training and testing sets using train_test_split.

5. Model Building Trained a Decision Tree Classifier with parameters like criterion='gini', max_depth=5, and min_samples_split=10. Evaluated the model using accuracy, confusion matrix, and classification report.

6. Hyperparameter Tuning Optimized the model with criterion='entropy' and adjusted max_depth and min_samples_split to improve accuracy.

7. Model Visualization Visualized the decision tree structure using plot_tree, highlighting feature importance and decision-making paths.

# Conclusion-

The Decision Tree Classifier successfully predicts customer purchase behavior with a significant accuracy rate. The model provides interpretable insights into key factors influencing customer decisions, such as contact duration, marital status, and education level. Businesses can leverage these insights to develop focused marketing strategies and improve decision-making processes. The project highlights the power of machine learning in deriving actionable insights from data and emphasizes the importance of continuous evaluation and tuning for optimal performance.
