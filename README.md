# Loan Customer Prediction

The company aims to automate the loan qualification process in real time based on the information provided by customers when completing an online loan application form. The objective is to develop a machine learning model that can accurately predict loan approval, thereby accelerating the decision-making process and determining whether an applicant qualifies for a loan.

## Overviews

This notebook presents a comprehensive workflow for analyzing and modeling a loan prediction dataset. The process includes the following key steps:

### Data Loading and Exploration

The dataset is loaded, and an initial exploratory data analysis (EDA) is performed to understand its structure, data types, and the presence of missing values.

### Data Cleaning and Preprocessing

Missing values are handled, categorical variables are encoded using label encoding, unnecessary columns are removed, duplicate records are checked, and descriptive statistics are generated.

### Exploratory Data Analysis (EDA)

Visualizations such as box plots, count plots, scatter plots, and heatmaps are used to examine the distribution of features and identify relationships between variables.

### Feature Engineering

Categorical variables are transformed into numerical representations to prepare the dataset for machine learning models.

### Model Training and Evaluation (Classification)

Several classification algorithms are trained to predict loan approval status, including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), XGBoost, CatBoost, and AdaBoost. Model performance is evaluated using accuracy, precision, recall, and F1-score.

### Model Comparison

The performance of each classification model is compared using F1-scores on both the training and test datasets, with the results visualized using bar charts.

### Best Model Selection

The CatBoost Classifier is identified as the best-performing model for loan approval prediction based on the evaluation metrics.

### Regression Modeling

The notebook also predicts loan amounts using XGBoost Regressor. Hyperparameter tuning is performed using GridSearchCV, and model performance is evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and the coefficient of determination (R²).

### Prediction and Submission

The predicted loan amounts are compared with the actual values, visualized, and prepared for submission as a CSV file.

