# Probability of Default (PD) Model  
## Credit Risk Modeling & Default Prediction  

![Status](https://img.shields.io/badge/Project-Completed-success)
![Model](https://img.shields.io/badge/Model-Logistic%20Regression-blue)
![Domain](https://img.shields.io/badge/Domain-Credit%20Risk-purple)
![Framework](https://img.shields.io/badge/Framework-IFRS9-green)

---

## Executive Summary  

This project develops a **Probability of Default (PD) model** to estimate the likelihood that a borrower will default on a loan.  

The model leverages **statistical and machine learning techniques** to support:

- Credit risk assessment  
- Risk-based pricing  
- Portfolio monitoring  
- Regulatory compliance (IFRS 9 / Basel frameworks)  

---

## Problem Statement  

Financial institutions face significant challenges in accurately assessing borrower risk.  

Poor credit risk assessment can lead to:
- Increased default rates  
- Revenue losses  
- Poor portfolio quality  

This project aims to build a **robust PD model** that predicts borrower default probability and identifies key risk drivers.

---

## Dataset Description  

The dataset contains borrower-level financial and behavioral information:

### Key Features:
- Demographics (Age, Employment Status)  
- Financial metrics (Income, Loan Amount)  
- Credit history (Previous defaults, repayment patterns)  
- Loan characteristics  

### Target Variable:
- `Default`  
  - 1 → Default  
  - 0 → No Default  

---

## Methodology  

### 1. Data Preprocessing  

- Handling missing values  
- Encoding categorical variables  
- Feature scaling  
- Outlier detection and treatment  

---

### 2. Exploratory Data Analysis (EDA)  

- Distribution of default vs non-default  
- Correlation analysis  
- Feature relationships with default risk  

---

### 3. Model Development  

The primary model used is:

### Logistic Regression  

\[
PD = \frac{1}{1 + e^{-(\beta_0 + \beta_1 X_1 + \cdots + \beta_n X_n)}}
\]

Where:
- \(PD\) = Probability of Default  
- \(X_i\) = Input features  
- \(\beta_i\) = Model coefficients  

---

### 4. Model Evaluation  

The model is evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

---

### 5. Model Validation  

- Train/Test split  
- Cross-validation  
- Stability checks  

---

## Results & Key Insights  

### Key Drivers of Default:

- High loan-to-income ratio  
- Poor credit history  
- Low income stability  

---

### Model Performance:

- Strong ROC-AUC score  
- Balanced precision-recall tradeoff  
- Good classification performance  

---

##  Risk Interpretation  

- Higher PD → Higher risk borrower  
- Lower PD → Lower risk borrower  

### Applications:
- Loan approval decisions  
- Credit scoring  
- Risk-based pricing  

---

## Business Impact  

This model enables:

- Improved credit decision-making  
- Reduction in default losses  
- Enhanced portfolio quality  
- Better regulatory compliance (IFRS 9, Basel II/III)  

---

## IFRS 9 Alignment  

This PD model is a core component of **Expected Credit Loss (ECL)**:

\[
ECL = PD \times LGD \times EAD
\]

Where:
- PD → Probability of Default  
- LGD → Loss Given Default  
- EAD → Exposure at Default  

---

## Tools & Technologies  

- Python (Pandas, NumPy, Scikit-learn)  
- Data Visualization (Matplotlib, Seaborn)  
- Jupyter Notebook  

---

## 📁 Project Structure  
