# Loan-Data-Preprocessing

Description: Preprocessed and transformed a loan application dataset to prepare it for machine learning modeling, focusing on data cleaning, encoding, and outlier handling.

Loaded and explored raw data to identify missing values, duplicates, and irrelevant features.

Removed unique identifiers (Loan_ID) and addressed outliers in CoapplicantIncome for improved data quality.

Imputed missing values using mode and median strategies to ensure data completeness.

Applied Label Encoding to categorical columns such as Gender, Married, Education, Self_Employed, and Loan_Status.

Implemented One-Hot Encoding for multi-category fields like Dependents and Property_Area.

Generated a clean, machine learning–ready dataset (Encoded_loan_data.csv) for model training and further analysis.

Tech Stack: Python, pandas, scikit-learn (LabelEncoder)
