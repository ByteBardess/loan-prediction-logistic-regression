# loan-prediction-logistic-regression
📊 Logistic Regression Model for Loan Approval Prediction  
🏦 Explore this machine learning project to predict whether customers will subscribe to a bank's term deposit based on 
various demographic and banking-related features. 
📈 Analyze the code, 📊 dissect the dataset, and 🧐 evaluate model performance.

**Project Title:** Predicting Loan Approval Using Logistic Regression

**Project Description:
**In this project, I used logistic regression to predict whether customers would take a loan or not based on a dataset from a banking institution. The objective was to develop a model that could assist in identifying potential loan takers, helping the bank optimize its marketing efforts.

**Data Description:
**The dataset consists of 21 columns and 41,196 rows, with a mix of numeric and categorical features. Here's a brief overview of the dataset columns:

age: Age of the customer (numeric).
job: Type of job (categorical).
marital: Marital status (categorical).
education: Education level (categorical).
default: Whether the customer has credit in default (binary: 'yes', 'no').
housing: Whether the customer has a housing loan (binary: 'yes', 'no').
loan: Whether the customer has a personal loan (binary: 'yes', 'no').
contact: Type of communication used to contact the customer (categorical).
month: Last contact month of the year (categorical).
day_of_week: Last contact day of the week (categorical).
duration: Duration of the last contact in seconds (numeric).
campaign: Number of contacts performed during this campaign (numeric).
pdays: Number of days since the customer was last contacted (numeric).
previous: Number of contacts performed before this campaign (numeric).
poutcome: Outcome of the previous marketing campaign (categorical).
emp.var.rate: Employment variation rate (numeric).
cons.price.idx: Consumer price index (numeric).
cons.conf.idx: Consumer confidence index (numeric).
euribor3m: Euribor 3-month rate (numeric).
nr.employed: Number of employees (numeric).
y: Whether the customer subscribed to a term deposit (binary: 'yes', 'no').

**Methodology:
**

  **Data Preprocessing:** Handled missing values and encoded categorical variables.
  **Feature Engineering:** Selected relevant features and transformed data as needed.
  **Logistic Regression Model:** Built a logistic regression model to predict loan subscription.
  **Model Evaluation:** Assessed the model's performance using metrics like accuracy, precision, recall, and ROC AUC.
 
**Results:
**
The logistic regression model achieved an accuracy of [accuracy_score].
Precision: **92.8%**
Recall: **99.4%**
ROC AUC: **0.86**

**Visualizations:
**


![image](https://github.com/cipherchawla/loan-prediction-logistic-regression/assets/146151444/fae1c00a-afc4-44de-9f68-15625c84b15a)

ROC AUC curve

![image](https://github.com/cipherchawla/loan-prediction-logistic-regression/assets/146151444/0ef8b311-1070-45fd-b174-2e99ce807e8c)

The confusion matrix 

![image](https://github.com/cipherchawla/loan-prediction-logistic-regression/assets/146151444/a8b6bd24-bc5a-499a-ade5-1cf13cdc7ba3)

Histogram for predicted possibilities 

**Code:**
https://gist.github.com/cipherchawla/f354e70ac45439ab848e734930c781ff 

**Challenges and Learnings:**

  One challenge I faced was handling missing data and deciding on the best strategy for imputation.
  I learned the importance of feature selection and engineering in improving model performance.
  Understanding the business context and interpreting model results were key to making actionable recommendations.
**Conclusion:**
    This project demonstrates the application of logistic regression in predicting loan subscriptions for a banking institution. The model's insights can help the bank target potential loan takers more effectively, thereby optimizing marketing resources. Future work could involve exploring other machine learning algorithms or fine-tuning the logistic regression model for even better performance.
