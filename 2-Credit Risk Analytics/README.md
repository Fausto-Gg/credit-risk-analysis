Credit Risk Analysis & Modeling

---Project Overview:

This project analyzes credit risk data to understand customer profiles and build predictive models to estimate the probability of loan default.
The goal is to combine exploratory data analysis, feature engineering, and machine learning models into a clear, reproducible workflow suitable for real-world business scenarios.


---Objectives:

-Perform exploratory data analysis (EDA) to identify patterns and risk factors

-Engineer relevant features for modeling

-Train and evaluate multiple classification models

-Compare model performance using standard classification metrics


---Project Structure:

credit-risk-project/
│
├── data/
│   └── credit_risk_dataset.csv
│
├── notebooks/
│   ├── 01_Eda.ipynb
│   ├── 02_Feature_Engineering.ipynb
│   └── 03_Modeling.ipynb
│
├── README.md
└── requirements.txt


---Dataset:

Synthetic dataset simulating real credit risk data with features such as:

Age

Income

Credit score

Loan amount and term

Interest rate

Employment status

Previous default history

Target variable:

default → whether the client defaulted on the loan


---Notebook Breakdown


--- 1-Exploratory Data Analysis (EDA):

-Data inspection and cleaning

-Distribution analysis

-Relationship between features and default risk

-Visual insights using matplotlib and seaborn


--- 2-Feature Engineering:

-Encoding categorical variables

-Feature selection

-Train-test split

-Data preparation for modeling


--- 3-Modeling:

-Logistic Regression

-Random Forest

-Gradient Boosting

-Model evaluation using:

-Accuracy

-Precision

-Recall

-F1-score

-ROC Curve

-Confusion Matrix

-Final model comparison


---Results:

Gradient Boosting achieved the best overall performance, balancing recall and precision, making it the most suitable model for credit risk prediction in this project.


---Tools & Technologies:

-Python

-Pandas, NumPy

-Matplotlib, Seaborn

-Scikit-learn

-Jupyter Notebook


---Future Improvements:

-Hyperparameter tuning

-Cross-validation

-Cost-sensitive learning

-Feature importance analysis

-Deployment as a simple API or dashboard