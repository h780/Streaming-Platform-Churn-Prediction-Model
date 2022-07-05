# Streaming-Platform-Churn-Prediction-Model
Churn Prediction Model for streaming platform using Decision Trees and Ensemble Technique

Business Objective: A Decision Tree is a Supervised learning technique that can be used for both classification and regression problems, but mostly it is preferred for solving Classification problems. It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules, and each leaf node represents the outcome. It is a graphical representation of all possible solutions to a problem/decision based on given conditions. It is called a decision tree because similar to a tree, it starts with the root node, which expands on further branches and constructs a tree-like structure. A decision tree asks a question and based on the answer (Yes/No), it further splits the tree into subtrees.

Customers that have decided to quit their engagement with their current company are known as churned customers. I decided to work with a churn dataset for this case study.

XYZ is a service provider that offers a one-year subscription plan for their product to customers. The corporation is curious as to whether or not customers would renew their subscriptions for the next year.

Data Description: This data provides information about a video streaming service company, where they want to predict if the customer will churn or not. The CSV consists of around 2000 rows and 16 columns.

Tech Stack: Language - Python Libraries - numpy, pandas, matplotlib, seaborn, sklearn, pickle, imblearn, statsmodel

Approach:

1. Importing the required libraries and reading the dataset.
2. Inspecting and cleaning up the data
3. Performing data encoding on categorical variables
4. Exploratory Data Analysis (EDA) <br />
   -> Data Visualization <br />
5. Feature Engineering <br />
   -> Dropping of unwanted columns <br />
6. Logistic Regression Model Building <br />
   -> Using the statsmodel library <br />
7. Logistic Regression Model Building <br /> 
   -> Performing train test split <br />
   -> Logistic Regression Model <br />
8. Logistic Regression Model Validation (predictions) <br />
   -> Accuracy score <br />
   -> Confusion matrix <br />
   -> ROC and AUC <br />
   -> Recall score <br />
   -> Precision score <br />
   -> F1-score <br />
9. Handling the unbalanced data <br />
   -> With balanced weights <br />
   -> Random weights <br />
   -> Adjusting imbalanced data <br />
   -> Using SMOTE <br />
10. Feature Selection <br />
   -> Barrier threshold selection <br />
   -> RFE method <br />
11. Saving the Logistic Regression model in the form of a pickle file <br />
12. Decision Tree Model Building <br /> 
   -> Performing train test split <br />
   -> Executing Decision Tree Model <br />
13. Decision Tree Model Evaluation <br />
14. Decision Tree Visualization <br />
15. Decision Tree Feature Selection (not successful yet) <br />
16. Random Forest Model <br />
17. Adaptive Boosting <br />
18. Gradient Boosting <br />
19. LIME Implementation <br />
