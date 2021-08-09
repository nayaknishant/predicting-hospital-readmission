# Predicting hospital readmission for patients with diabetes

This repo uses data from the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008). The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. The data is prepared to analyze factors related to readmission as well as other outcomes pertaining to patients with diabetes. Each patient instance includes over 50 features representing patient and hospital outcomes and there are over 100,000 patient instances in the dataset.

The objective of this project is to develop a model that will predict whether or not a patient will be readmitted within 30 days. The report is divided into six sections:
- Data exploration
- Feature extraction
- Creating Training / Validation / Test Data
- Model Selection
- Test Evaluation
- Conclusion

The best model, the SGD Logistic Regression classifer, has a 67% prediction accuracy on held-out test data and an AUC score of 0.66.
