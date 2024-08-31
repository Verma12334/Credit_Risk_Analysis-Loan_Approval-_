# Project Title: Credit Risk Analysis & Loan Approval Prediction


# Introduction:

Developed a Customer Loan Approval Prediction system utilizing advanced machine learning techniques to accurately assess the probability of loan repayment and evaluate customer credit risk. This system aids financial institutions in making informed lending decisions, thereby minimizing default rates and optimizing loan portfolio performance.


# Description:

The project began with a dataset that lacked sufficient columns necessary for effective model training. To address this, the Loan Status target column was dropped, and KMeans Clustering was applied to the remaining independent variables to create 10 distinct clusters. These clusters were interpreted such that higher cluster values indicated a higher probability of loan repayment and lower credit risk, while lower cluster values suggested the opposite. The cluster values were then mapped to estimated probabilities and integrated back into the original dataset as a new feature, a key aspect of feature construction.

Subsequent steps involved comprehensive data preprocessing and feature engineering, complemented by Exploratory Data Analysis (EDA) using various visualization techniques such as count plots, pie charts, scatter plots, distribution plots, heatmaps, cluster maps, and box plots for outlier detection. To address the issue of class imbalance in the dataset, SMOTE (Synthetic Minority Over-sampling Technique) was employed for oversampling.

### Multiple machine learning models, including Decision Tree, Random Forest, and Logistic Regression, were trained on the processed data. The models were evaluated based on their accuracy and F1 scores, achieving impressive results with an accuracy of 93% and an F1 score of 92%.


# Objectives:

### Enhance Predictive Accuracy:
Develop a robust model to accurately predict loan approval and assess credit risk.

### Optimize Decision-Making:
Provide financial institutions with reliable insights to inform lending decisions and reduce default rates.

### Handle Data Challenges: 
Address issues related to insufficient data columns and class imbalance to ensure model reliability and performance.


# Bullet Points:

### 1. Project Overview:
Developed a Customer Loan Approval Prediction system leveraging machine learning algorithms to assess loan repayment probabilities and evaluate credit risk, facilitating informed decision-making for financial institutions.


### 2. Implementation & Tools:
Executed feature construction using KMeans Clustering to create 10 credit risk-based clusters, conducted comprehensive data preprocessing and Exploratory Data Analysis (EDA) with visualization tools (count plots, scatter plots, heatmaps, etc.), applied SMOTE for handling class imbalance, and trained multiple models including Decision Tree, Random Forest, and Logistic Regression.


# Achievements:
Achieved a 93% accuracy and a 92% F1 score in predicting loan approvals and credit risk, demonstrating high model performance and reliability in real-world applications.


# Key Technologies & Tools Used:

**Programming Language:** Python

**Development Environment:** Jupyter Notebook, Google Colab (for running the code and experiments)

***Libraries & Frameworks:**  Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn

**Techniques:**  KMeans Clustering, SMOTE, Feature Engineering, Data Preprocessing, Exploratory Data Analysis (EDA)

**Machine Learning Models:** Decision Tree, Random Forest, Logistic Regression


# Acknowledgements:
We would like to thank the developers of the open-source libraries and frameworks used in this project. Their contributions to the data science and machine learning community made it possible for us to complete this project successfully.

**This project provides a comprehensive solution for financial institutions to assess credit risk and approve loans more accurately, leading to better decision-making and reduced financial risks.**