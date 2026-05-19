# Credit Loan Default Risk Prediction Demo

This repository contains a demo notebook for a credit loan default risk prediction project. The notebook explores borrower, receipt, and repayment data to build and evaluate a machine learning model for loan risk assessment.

## Project Contents

- `Credit Loan Defalt Risk Prediction Model 孟子钧 (2).ipynb` - main analysis and modeling notebook
- `借贷人风险评估模型方案--孟子钧.docx` - project proposal/report document

Raw CSV files are intentionally excluded from GitHub via `.gitignore` because they contain borrower-level fields. Keep them locally when running the notebook:

- `receipt_table.csv`
- `receipt_test.csv`
- `user.csv`
- `user_test.csv`
- `return_table.csv`
- `return_test.csv`

## Demo Goal

The project demonstrates an end-to-end credit risk workflow:

1. Load borrower and transaction data.
2. Explore feature distributions and repayment behavior.
3. Prepare features for modeling.
4. Train and evaluate a default risk prediction model.
5. Summarize model insights for credit decision support.

## How to Use

Open the notebook in Jupyter:

```bash
jupyter notebook "Credit Loan Defalt Risk Prediction Model 孟子钧 (2).ipynb"
```

The notebook expects the local CSV files to be in the same folder. They are not included in this public demo repository.
