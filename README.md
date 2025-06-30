
# 📊 Loan Default Prediction System

## 📌 Project Goal
This project aims to build a machine learning model that can predict whether a loan applicant will default or repay a loan based on historical data. The objective is to assist financial institutions in automating and improving their loan decision process.

## 📂 Files Included
- `Loan_Default_Prediction_System.ipynb`: The main Jupyter Notebook containing all preprocessing, EDA, model training, evaluation, and ROC curve comparison.
- `loan_data.csv`: The dataset used for training and testing the ML models.
- `Loan_Default_Prediction_Summary.pdf`: A one-page summary of the project goal, chosen model, final accuracy, and key insights.
- `Loan_Default_Prediction_System.html`: Exported version of the notebook (viewable in browsers).

## 🛠 Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📈 Models Tested
- Logistic Regression
- Decision Tree
- Random Forest

## ✅ Best Performing Model
**Random Forest Classifier** was selected as the best model based on its high F1-score and ROC AUC.

## 📊 EDA Insights
- Applicants with good credit history (1.0) had much higher chances of approval.
- Applicant income and loan amount were skewed.
- Urban property area and education level influenced approval rates.
- No major multicollinearity was observed in the heatmap.

## 📄 How to Run
1. Clone the repository or download the files.
2. Make sure `loan_data.csv` is in the same directory as the notebook.
3. Run the notebook in Jupyter Lab or Jupyter Notebook.


