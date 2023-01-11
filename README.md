# Bank-Marketing-Classification

This classification project utilized several Machine Learning models to determine if a bank client has subscribed to a term deposit. The data used represents the results of a telemarketing campaign conducted by a Portuguese banking institiution. Each model was optimized and tuned to achieve the best possible scores.

## Dataset:

This project utilized the bank-additional-full.csv dataset retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/bank+marketing). This version closely resembles the data analyzed by [Moro et al., 2014] and contains 41,188 samples and all 20 input features.

More information about each feature can be found in the bank-additional-names.txt file in the data folder.

## Models:

The following Machine Learning models were implemented in this project:

- Logistic Regresion (LR)
  - This is a baseline model simple to implement.
- Decision Tree (DT)
  - Tree-based model for more complex decision-making tasks.
- LightGBM (LGB)
  - Gradient boosting model; an alternative to the ubiquitous XGBoost model.

## References:

- Jason Brownlee, How to Calculate Feature Importance With Python, Machine Learning Mastery, Available from https://machinelearningmastery.com/calculate-feature-importance-with-python/, accessed May 29th, 2021.
- https://archive.ics.uci.edu/ml/datasets/bank+marketing
- [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014
