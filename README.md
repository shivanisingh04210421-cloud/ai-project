# Loan Approval Prediction Using Machine Learning

## Project overview
This AIA project predicts whether a loan application is approved (`Y`) or rejected (`N`) using applicant information.

- **Problem type:** Supervised machine learning – binary classification
- **Dataset:** Public Loan Prediction dataset, commonly distributed with 614 records and 13 columns
- **Target:** `Loan_Status`
- **Algorithms compared:** Logistic Regression, Decision Tree, Random Forest
- **Environment:** Google Colab / Python

## Dataset
Download the CSV dataset from this public raw CSV link:

https://raw.githubusercontent.com/SANKETKISHU/Loan_Approval_Prediction/main/Training%20Dataset.csv

Save it in this project folder as `loan_approval_dataset.csv` (or upload it directly when the notebook asks you to choose a file).

**Dataset note:** This standard dataset has 614 application records, not 1,000+. Do not artificially duplicate or generate rows to claim a larger real dataset. If your teacher requires 1,000+ genuine records, choose a different Kaggle dataset and verify its size and license.

## How to run in Google Colab
1. Open https://colab.research.google.com/
2. Upload `Loan_Approval_Prediction.ipynb`.
3. Run cells from top to bottom.
4. When the upload dialog appears, select `loan_approval_dataset.csv`.
5. At the end, download the trained `loan_approval_model.pkl` if required.

## Project workflow
1. Dataset loading and inspection (`head`, `info`, `describe`, missing values)
2. Duplicate removal and data cleaning
3. Exploratory analysis and numerical correlation heatmap
4. Train/test split (80% / 20%, stratified)
5. Missing-value imputation, scaling and one-hot encoding in a pipeline
6. Training and comparison of three classification algorithms
7. Evaluation using accuracy, precision, recall, F1-score, classification report and confusion matrix
8. Saving the selected complete pipeline

## Files
- `Loan_Approval_Prediction.ipynb` – complete Colab notebook with explanations
- `requirements.txt` – Python libraries
- `loan_approval_dataset.csv` – add the downloaded dataset before submitting to GitHub

## Important
This is an academic demonstration, not a real bank underwriting system. Model predictions should not be used to approve or reject real loan applications. Check the dataset source and license terms before redistribution.
