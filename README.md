# Data-Science-Internship-Tasks

This repository contains the five data science projects covering exploratory data analysis (EDA), regression, and classification.
## 📊 Project Summary Table

| Task | Project Title | Model / Approach | Key Result / Accuracy |
| :--- | :--- | :--- | :--- |
| **Task 1** | Iris Dataset Exploration | EDA & Visualization (Seaborn) | Identified Petals as key features |
| **Task 2** | Credit Risk Prediction | Logistic Regression | **79% Accuracy** |
| **Task 3** | Customer Churn Prediction | Random Forest Classifier | **86% Accuracy** |
| **Task 4** | Insurance Claim Amount | Linear Regression | Identified Smoking as primary cost driver |
| **Task 5** | Personal Loan Acceptance | Random Forest / Classification | Optimized via `pdays` and macro factors |

## Task 1: Iris Dataset Analysis
* **Objective:** Explore and visualize how flower measurements (sepals/petals) vary across species.
* **Approach:** Used Seaborn for visualization and Pandas for data manipulation.
* **Insights:** Petal length and width are the most powerful features for distinguishing species. "Setosa" is completely isolated from others based on these measurements.

## Task 2: Credit Risk Prediction
* **Objective:** Predict if a loan applicant is likely to default based on customer details.
* **Approach:** Cleaned missing values using median/mode and applied Logistic Regression.
* **Insights:** The model achieved ~79% accuracy but struggles with "False Positives" (approving bad loans), which is costly for banks.

## Task 3: Customer Churn Prediction
* **Objective:** Build a model to predict which bank customers are likely to leave.
* **Approach:** Used a Random Forest model with feature scaling.
* **Insights:** Age is the strongest indicator of churn (~24%), with older and German customers showing higher exit rates.

## Task 4: Insurance Claim Amounts
* **Objective:** Estimate medical insurance charges based on personal data like age, BMI, and smoking habits.
* **Approach:** Applied Linear Regression to find the "settings" for each patient dial.
* **Insights:** Smoking is the primary driver of cost. The combination of high BMI and smoking creates the highest medical charges.

## Task 5: Personal Loan Acceptance
* **Objective:** Predict which customers will accept a term deposit offer to increase campaign efficiency.
* **Approach:** Used classification models, specifically dropping "call duration" to avoid data leakage.
* **Insights:** Macroeconomic factors (consumer confidence) and the number of days since last contact (`pdays`) heavily influence model performance.
