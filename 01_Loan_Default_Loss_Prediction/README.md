# Loan Default Loss Prediction

This project builds a two-stage predictive modeling workflow for credit risk. The first stage estimates whether a loan will produce any loss, and the second stage estimates the loss amount for defaulting loans.

## What This Project Contains

- `Loan_Default_Loss_Prediction.Rmd`: R Markdown workflow covering data preparation, feature encoding, imputation, scaling, model training, validation, and prediction generation.
- `Loan_Default_Loss_Prediction.html`: Rendered analysis output for review.
- `Loan_Default_Loss_Prediction_Report.pdf`: Final written report.
- `Loan_Default_Loss_Prediction_Presentation.pptx`: Final presentation deck.
- `Loan_Default_Loss_Prediction_Submission.csv`: Prediction output generated from the modeling workflow.

## Methods Used

- Binary default classification
- Loss severity regression
- Train-validation splitting
- Missing-value imputation
- Feature scaling and encoding
- Model comparison using validation metrics

## Reproducibility Note

The raw training and testing files are not included in this repository. To rerun the notebook, place `train_v3.csv` and `test__no_lossv3.csv` in a local `data/` folder inside this project directory.
