# Loan Data Analysis & Predictive Modeling

## Overview
This script performs exploratory data analysis (EDA) and predictive modeling on loan data from `LoanStats3a.csv`. The analysis covers various borrower characteristics such as interest rates, loan amounts, loan purposes, home ownership status, and geographical distribution. Additionally, a machine learning model is built to predict loan repayment success.

## Features & Functionalities
- **Data Loading & Cleaning**:
  - Loads the dataset while handling missing values and formatting inconsistencies.
- **Exploratory Data Analysis (EDA)**:
  - Interest rate distribution
  - Loan term lengths
  - Loan amount distribution
  - Borrower purposes for loans
  - Home ownership status of borrowers
  - Geographical distribution of borrowers
- **Feature Engineering**:
  - FICO score averaging
  - Debt-to-income ratio adjustments
  - Loan-to-income ratio
  - Interest rate to FICO ratio
  - Payment-to-income ratio
  - Utilization relative to total accounts
- **Predictive Modeling**:
  - Binary classification for loan repayment success (`Fully Paid` vs. others)
  - Data preprocessing using `StandardScaler`
  - Model training using `RandomForestClassifier` and `GradientBoostingClassifier`
  - Hyperparameter tuning with `GridSearchCV`
  - Model evaluation using accuracy, confusion matrix, and classification report

## Requirements
To run this script, install the necessary Python libraries:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Ensure `LoanStats3a.csv` is in the script's directory.
2. Run the script in a Python environment:
```sh
python loan_analysis.py
```
3. The script will output analysis results and visualizations.

## Output
- Statistical insights printed to the console.
- Data visualizations using `matplotlib` and `seaborn`.
- Model performance metrics including accuracy and confusion matrix.
- <img width="578" alt="image" src="https://github.com/user-attachments/assets/cda3b999-d304-4697-ace8-c7ba531fb914" />
- <img width="481" alt="image" src="https://github.com/user-attachments/assets/277ef6b3-b91a-4295-b504-bc2e23ebe12f" />
- <img width="579" alt="image" src="https://github.com/user-attachments/assets/6ff6bf36-dbab-4442-a261-3c86c75b8522" />
- <img width="496" alt="image" src="https://github.com/user-attachments/assets/e1c1ad6c-b10f-4e4f-8f7a-faa5652790fc" />
- <img width="584" alt="image" src="https://github.com/user-attachments/assets/2918bd29-f540-462e-92c2-f8838dd98285" />
- <img width="497" alt="image" src="https://github.com/user-attachments/assets/a9bdd675-c998-46b8-a41a-18092d9d3349" />
- <img width="449" alt="image" src="https://github.com/user-attachments/assets/1fd7d60e-0ac7-4491-b9f7-9ee06495f58b" />
- <img width="497" alt="image" src="https://github.com/user-attachments/assets/8aa09546-6df2-4b61-8a4e-593764ee1a8b" />
- <img width="496" alt="image" src="https://github.com/user-attachments/assets/0cbbeb27-d17e-466d-b16e-9270d2915d01" />
- <img width="497" alt="image" src="https://github.com/user-attachments/assets/1cfebd77-78fc-49be-a307-ff7c42b0a247" />
- <img width="496" alt="image" src="https://github.com/user-attachments/assets/2b67af46-d4de-4dbe-9a51-bfff65d19f4e" />
- <img width="497" alt="image" src="https://github.com/user-attachments/assets/ebf2d5af-b0ee-47a5-8890-c5e26ba0a4e4" />
- <img width="448" alt="image" src="https://github.com/user-attachments/assets/fb93051b-7818-4ade-9680-4eb96a6bcff1" />














## Notes
- Some categorical variables are one-hot encoded before model training.
- Additional feature engineering can enhance model accuracy.
- Data preprocessing is crucial to handle missing or inconsistent values effectively.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

