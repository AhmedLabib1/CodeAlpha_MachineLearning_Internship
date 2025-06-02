# Credit Scoring Model – CodeAlpha Internship

## Project Objective
Predict an individual's creditworthiness using past financial and demographic data.  
This task is part of the CodeAlpha Machine Learning Internship (June 2025 – Sept 2025).

---

## Dataset Features

| Feature Name           | Description                              |
|------------------------|------------------------------------------|
| age                    | Age of the individual                    |
| annual_income          | Annual income                            |
| home_ownership         | Home ownership status                    |
| employment_length      | Employment duration (years)              |
| loan_purpose           | Purpose of the loan                      |
| grade                  | Credit grade assigned                    |
| loan_amount            | Loan amount requested                    |
| interest_rate          | Interest rate of the loan                |
| loan_to_income_ratio   | Loan amount as % of income               |
| default (Target)       | Whether loan was defaulted (1) or not (0)|
| has_prior_default      | Prior default status (Y/N)               |
| credit_history_length  | Length of credit history (years)         |

---

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Project Steps

1. **Load Data**: Import credit risk dataset and perform EDA.  
2. **Preprocess**: Handle missing values, encode categorical features, remove duplicates.  
3. **Scale Features**: Log-transform skewed data, apply StandardScaler.  
4. **Split Data**: Train-test split with stratified sampling.  
5. **Train Models**: Fit Logistic Regression, Decision Tree, Random Forest with GridSearchCV.  
6. **Evaluate**: Measure accuracy, precision, recall, F1, ROC-AUC; plot ROC curves, confusion matrices.  
7. **Save Model**: Pickle Random Forest model.

---

## Results

- **Best Model**: Random Forest Classifier  
- **AUC Score**: 0.9308
- **Conclusion**: Random Forest performed best with high recall and balanced accuracy.

---

## Project Structure

- **Dataset/**  
  - `credit_risk_dataset.csv`: Raw dataset for credit scoring.
  
- **images/**  
  - `Decision_Tree_confusion_matrix.png`: Confusion matrix for Decision Tree.  
  - `Decision_Tree_roc_curve.png`: ROC curve for Decision Tree.  
  - `Logistic_Regression_confusion_matrix.png`: Confusion matrix for Logistic Regression.  
  - `Logistic_Regression_roc_curve.png`: ROC curve for Logistic Regression.  
  - `Random_Forest_confusion_matrix.png`: Confusion matrix for Random Forest.  
  - `Random_Forest_roc_curve.png`: ROC curve for Random Forest.

- **models/**  
  - `encoders.pkl`: Saved encoders for preprocessing.  
  - `random_forest_model.pkl`: Saved Random Forest model.

- `credit_model.ipynb`: Main Jupyter notebook with the project code.  
- `credit_scoring_data_profile.html`: EDA profiling report.  
- `README.md`: Project documentation.  
- `requirements.txt`: Dependencies list.  
- `.gitignore`: Git ignore file.

---

## Project Demo

🔗 [LinkedIn Post with Demo Video](#)  
🔗 [GitHub Repository](#) https://github.com/AhmedLabib1/CodeAlpha_MachineLearning_Internship

---

## Internship

This project was developed as part of the **Machine Learning Internship at CodeAlpha**, from June to September 2025.