# Loan-Amount-Prediction-using-Machine-Learning
A simple machine learning project that predicts the loan amount based on applicant details such as income, loan term, and credit history. The project uses Python, pandas, and scikit-learn to preprocess data, train a Linear Regression model, evaluate its performance, and save it for reuse.

## Dataset

The dataset contains information on loan applicants, including:

- Applicant's income and co-applicant income
- Loan amount and loan term
- Credit history
- Property area
- Education, gender, marital status, and employment status

The dataset is typically sourced from a CSV file (`train.csv` or `loan_data.csv`) and contains both numerical and categorical features.

## Methodology

1. **Data Cleaning & Preprocessing**  
   Handling missing values, encoding categorical variables, and scaling features where necessary.

2. **Exploratory Data Analysis (EDA)**  
   Visualizing distributions, relationships, and correlations between features and the loan amount.

3. **Feature Engineering**  
   Creating new features or transforming existing ones to improve model performance.

4. **Model Building**  
   Training regression models like Linear Regression, Random Forest Regressor, and XGBoost to predict loan amounts.

5. **Model Evaluation**  
   Evaluating models using metrics such as RMSE (Root Mean Squared Error) and R² (Coefficient of Determination).

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/BhavinAghera/Loan-Amount-Prediction.git
   cd Loan-Amount-Prediction
