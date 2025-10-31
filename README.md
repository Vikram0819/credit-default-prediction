# credit-default-prediction

Predicting credit card default risk using XGBoost and SHAP

# Credit Default Prediction using XGBoost and SHAP



This project applies machine learning to predict whether a customer will default on their credit card payment. It uses the XGBoost algorithm for classification and SHAP for model interpretability.



\## 📊 Dataset



\- \*\*Source\*\*: `Credit Card Default.csv`

\- \*\*Records\*\*: ~30,000 customer profiles

\- \*\*Features\*\*: Demographics, payment history, bill amounts, and previous payments

\- \*\*Target\*\*: Binary label — `1` for default, `0` for non-default



\## 🔍 Workflow Summary



1\. \*\*Data Preprocessing\*\*

&nbsp;  - Missing value handling

&nbsp;  - Categorical encoding

&nbsp;  - Feature scaling



2\. \*\*Exploratory Data Analysis (EDA)\*\*

&nbsp;  - Distribution plots

&nbsp;  - Correlation heatmaps

&nbsp;  - Class imbalance check



3\. \*\*Modeling\*\*

&nbsp;  - XGBoost classifier

&nbsp;  - Hyperparameter tuning

&nbsp;  - Evaluation metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC



4\. \*\*Interpretability\*\*

&nbsp;  - SHAP values to explain feature impact

&nbsp;  - Visualizations for global and local interpretability



\## 🛠 Tools \& Libraries



\- Python 3.13

\- Pandas, NumPy

\- Matplotlib, Seaborn

\- Scikit-learn

\- XGBoost

\- SHAP

\- Jupyter Notebook



\## 🚀 Getting Started



1\. Clone the repository:

&nbsp;  ```bash

&nbsp;  git clone https://github.com/Vikram0819/credit-default-prediction.git

&nbsp;  cd credit-default-prediction



