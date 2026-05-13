# **Loan Approval Prediction using Machine Learning**

1. **Project Overview**

 This project focuses on predicting loan approval using machine learning and statistical analysis. It goes beyond basic ML by incorporating probability, hypothesis testing, and deep exploratory data analysis to understand real-world banking behavior.

4. **Dataset**
 - 614 loan applications
 - Features include income, credit history, loan amount, education, property area, etc.
 - Target: Loan_Status (Approved / Rejected)
   
 ✔ **Advanced Statistical Analysis Performed**

 -  Chi-Square Test (Credit History vs Loan Approval)
 -  Skewness Analysis (Income & Loan Amount distribution)
 -  Crosstab Analysis (categorical relationships)
 -  GroupBy Statistical Analysis (Income vs Education vs Loan Status)
 -  Outlier detection using boxplots
 -  Correlation analysis of numerical variables

✔ **Key Statistical Findings**

 - Credit History is highly significant for loan approval (p-value ≈ 3e-40)
 - Applicant Income is highly right-skewed (6.53)
 - Loan Amount is also skewed (2.74)
 - Higher income groups generally receive higher loan amounts
 - Strong relationship between income and loan amount (moderate correlation)

3. **Workflow**
   
✔ **Data Preprocessing**
 - Missing value handling
 - Outlier treatment
 - Feature cleaning
   
✔ **Exploratory Data Analysis**
 - Income distribution analysis
 - Loan amount distribution
 - Boxplots & skewness analysis
 - Categorical relationship analysis
   
✔ **Feature Engineering**
 - Label Encoding
 - One-Hot Encoding
 - Feature scaling using StandardScaler
   
✔ **Handling Imbalance**
 - SMOTE applied to balance dataset
   
✔ **Model Building**
 - Logistic Regression
 - K-Nearest Neighbors (KNN)
   
✔ **Model Evaluation**
 - Accuracy Score
 - Confusion Matrix
 - Classification Report
   
4. **Model Performance**
   Model	Accuracy
 - Logistic Regression	76%
 - KNN	64%

✔ **Logistic Regression performed better overall**

5. **Key Insights**
 - Credit History is the strongest predictor of loan approval
 - Applicant income shows high variability and outliers
 - Education affects income levels significantly
 - Loan approval depends heavily on financial history

6. **Tools & Technologies**

 - Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy, SMOTE

7. **Conclusion**

**This project demonstrates how combining statistical analysis + machine learning leads to better understanding of real-world financial decision-making systems. The insights derived can help banks improve loan approval strategies and reduce risk.**
