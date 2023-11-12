# Credit-card-default-predictions


# 📖PROBLEM STATEMENT
The primary goal of this project is to forecast customer default cases in Taiwan. In terms of risk management, the predictive accuracy of the estimated probability of default is deemed more valuable than a binary classification outcome (creditable or not credible clients). The K-S chart will be employed to assess which customers are likely to default on their credit card payments.
# 📖ALGORITHMS USED:
### I. Logistic regressions 
### II. Decision Tree
### III. Random forests 
### IV. XGB Boost
### V. K-Neatest Neighbor 


# 📖Solution Strategy
My approach to address this challenge involved the following steps:

Step 01: Data Description - Utilizing statistical metrics to identify data distributions.

Step 02: Feature Engineering - Creating new attributes based on the original variables to provide a more comprehensive description of the modeled phenomenon.

Step 03: Exploratory Data Analysis - Investigating the data to uncover insights and gain a better understanding of how variables impact model learning.

Step 04: Feature Selection - Choosing the most significant attributes to train the model effectively.

Step 05: Machine Learning Modeling - Training the machine learning model.

Step 06: Hyperparameter Fine-Tuning - Selecting optimal values for each model parameter identified in the previous step.

Step 07: Converting Model Performance to Business Values - Translating the machine learning model's performance into meaningful business outcomes.

Step 08: Deploying the Model to Production - Releasing the model in a cloud environment to enable other individuals or services to leverage the results for improving business decisions.


# 📖CONCLUSION
In this task, our objective was to classify and predict whether a credit card customer is at risk of falling behind on payments. This is a critical concern for credit card companies as it enables them to identify high-risk borrowers and take necessary precautions to mitigate potential losses.

Within the dataset, approximately 22% are defaulters, and 78% are non-defaulters. Men exhibit a slightly higher frequency of default compared to women. Default rates are higher among both younger and older customers. The rate of defaults correlates with increased credit usage. The likelihood of default rises with the number of late payments, and those who haven't made any prior payments have a higher default rate.

To address any data imbalances, Synthetic Minority Over-sampling Technique (SMOTE) was employed during data preparation. In forecasting customer default, the XGBoost model outperformed others, achieving the highest accuracy (0.95), recall (0.84), F1 score (0.82), and area under the curve (AUC) (0.81).

A feature significance analysis using SHAP values identified PAY_1, Marriage, Education, and other factors as crucial for predicting customer default.

# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.

# 📜 Credits
 Kajal Wasnik| Data Scientist | Machine Learning Engineer | Data Science enthusiast

Special thanks to AlmaBetter

