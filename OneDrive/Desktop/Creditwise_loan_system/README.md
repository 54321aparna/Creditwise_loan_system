# CreditWise Loan Approval System (Machine Learning)

## Project Overview

**CreditWise Loan Approval System** is a Machine Learning–powered solution designed for a mid-sized Indian financial institution (**SecureTrust Bank**) that offers personal and home loans across **urban and rural regions of India**.
Traditionally, the bank relied on a **manual loan verification process**, where loan officers evaluated applications using income proofs, employment details, credit history, and supporting documents. This approach was **time-consuming, biased, and inconsistent**, resulting in poor decision quality.
This project replaces manual screening with an **intelligent, data-driven loan approval system** that predicts whether a loan should be **Approved or Rejected** before final human verification.


##  Problem Statement

Every day, hundreds of customers apply for loans at SecureTrust Bank. Due to manual evaluation:

###  Key Challenges

1. **Good customers sometimes get rejected** → Loss of business and customer trust
2. **High-risk customers sometimes get approved** → Financial losses and increased NPAs

### Objective

To build an **AI-powered Loan Approval System** using **supervised Machine Learning** that:

* Automatically analyzes applicant details
* Learns hidden patterns from historical loan data
* Provides **fast, accurate, and unbiased loan approval predictions**
* Assists loan officers in decision-making

##  Machine Learning Approach

* **Learning Type:** Supervised Learning (Binary Classification)
* **Target Variable:** `Loan_Approved`

  * `1` → Approved
  * `0` → Rejected

### Algorithms Used

* Logistic Regression
* Random Forest Classifier
* Decision Tree Classifier
* Support Vector Machine (SVM)

### Model Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix


## Dataset Description

Each row in the dataset represents **one loan applicant** with personal, financial, and credit-related attributes.

### Applicant Information
| Column             | Description                             |
| ------------------ | --------------------------------------- |
| Applicant_ID       | Unique applicant identifier             |
| Applicant_Income   | Monthly income of applicant             |
| Coapplicant_Income | Monthly income of co-applicant          |
| Employment_Status  | Salaried / Self-Employed / Business     |
| Age                | Applicant age                           |
| Marital_Status     | Married / Single                        |
| Dependents         | Number of dependents                    |
| Education_Level    | Graduate / Postgraduate / Undergraduate |
| Gender             | Male / Female                           |
| Employer_Category  | Govt / Private / Self                   |

###  Financial & Credit Details

| Column           | Description             |
| ---------------- | ----------------------- |
| Credit_Score     | Credit bureau score     |
| Existing_Loans   | Number of running loans |
| DTI_Ratio        | Debt-to-Income ratio    |
| Savings          | Savings account balance |
| Collateral_Value | Value of collateral     |

### 🏦 Loan Details

| Column        | Description                                  |
| ------------- | -------------------------------------------- |
| Loan_Amount   | Loan amount requested                        |
| Loan_Term     | Loan duration (months)                       |
| Loan_Purpose  | Home / Education / Personal / Business       |
| Property_Area | Urban / Semi-Urban / Rural                   |
| Loan_Approved | Target variable (1 = Approved, 0 = Rejected) |

##  Data Preprocessing & Feature Engineering

* Handling missing values
* Encoding categorical variables
* Feature scaling using **StandardScaler**
* Outlier detection and treatment
* Class imbalance handling (if required)



## Key Outcomes & Insights

* Achieved **high prediction accuracy** for loan approval decisions
* Reduced **manual verification time** significantly
* Minimized approval bias through data-driven decisions
* Identified key factors influencing loan approval:

  * Credit score
  * DTI ratio
  * Income stability
  * Existing loans

## Tech Stack

* **Programming Language:** Python
* **Libraries:**
  * NumPy
  * Pandas
  * Scikit-learn
  * Matplotlib
  * Seaborn
* **Tools:**
  * Jupyter Notebook
  * Git & GitHub

**Dataset is intentionally excluded to maintain data privacy and follow best practices.
If you find this project useful, feel free to ⭐ star the repository!
