# Loan Approval Prediction System 🏦

An end-to-end machine learning project designed to automate the loan eligibility process based on customer details. This system leverages **Logistic Regression** to predict whether a loan application will be approved or rejected with high accuracy.

## 📌 Project Overview

Manual loan processing is time-consuming and prone to human error. This project provides a data-driven solution to streamline the credit risk assessment process. By analyzing historical data, the model identifies patterns and factors that contribute to successful loan approvals.

## 🚀 Key Features

- **Automated Preprocessing**: Handles missing values, outliers, and categorical encoding.
- **Exploratory Data Analysis (EDA)**: Insightful visualizations and statistical summaries.
- **Logistic Regression Model**: A robust classification model providing clear decision boundaries.
- **Performance Evaluation**: Comprehensive metrics including Accuracy, Precision, Recall, and Confusion Matrix.

## 📊 Dataset Description

The dataset consists of various applicant attributes:

| Feature | Description |
| :--- | :--- |
| `Loan_ID` | Unique identifier for each application |
| `Gender` | Male/Female |
| `Married` | Applicant's marital status |
| `Dependents` | Number of family members dependent on the applicant |
| `Education` | Graduate/Under-Graduate |
| `Self_Employed` | Employment status |
| `ApplicantIncome` | Total monthly income of the applicant |
| `CoapplicantIncome`| Income of the co-applicant |
| `LoanAmount` | The requested loan amount |
| `Loan_Amount_Term` | Duration of the loan (in months/days) |
| `Credit_History` | 1.0 (Good) or 0.0 (Poor) |
| `Property_Area` | Urban, Semi-Urban, or Rural |
| **`Loan_Status`** | **Target variable (Y/N)** |

## 🛠️ Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Hasaan901/loan-approval-prediction-system.git
   cd loan-approval-prediction-system
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks**:
   Open Jupyter Notebook or Lab and execute:
   - `01_Event_Data_Exploration.ipynb`: Understanding the dataset and initial insights.
   - `02_Loan_Approval_Prediction.ipynb`: Model training and evaluation.

## 📈 Model Performance

The Logistic Regression model achieves an accuracy of approximately **86%**, demonstrating strong predictive power for binary classification in financial datasets.

## 🔮 Future Enhancements

- [ ] Implementation of Random Forest and XGBoost for performance comparison.
- [ ] Development of a Flask/Streamlit web dashboard for real-time predictions.
- [ ] Integration with advanced feature engineering techniques.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

*Created by [Hasaan Ahmad](https://github.com/Hasaan901)*
