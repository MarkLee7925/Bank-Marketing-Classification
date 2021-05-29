# Bank-Marketing-Classification

This classification project utilized several Machine Learning models to determine if a bank client has subscribed to a term deposit. The data used represents the results of a telemarketing campaign by a Portuguese banking institiution. Each model was optimized to achieve the best possible accuracy score.

## Dataset:

This project utilized the bank-additional-full.csv dataset retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/bank+marketing). This version closely resembles the data analyzed by [Moro et al., 2014] and contains 41188 samples and all 20 input features. This is located in the data folder.

More information about each feature can be found in the bank-additional-names.txt file in the data folder.

## Models:

The following Machine Learning models were implemented in this project:

- Logistic Regression (LR)
- Decision Tree Classification (DT)

## Results

The Accuracy and ROC_AUC scores of each model is presented below:

- Logistic Regression - Accuracy = 90.945%, ROC_AUC = 93.110%
- Decision Tree Classification - Accuracy = 91.392%, ROC_AUC = 93.575%

<table border = "1">
  <thead>
    <th colspan = "3">Grid Search Results</th>
  </thead>
  <tbody>
    <tr>
      <td><b></b></td>
      <td><b>Accuracy</b></td>
      <td><b>ROC_AUC</b></td>
    </tr>
    <tr>
      <td><b>Best Score</b></td>
      <td>91.569%</td>
      <td>%</td>
    </tr>
    <tr>
      <td colspan="3"><b>Best Parameters:</b></td>
    </tr>
    <tr>
      <td><b>criterion</b></td>
      <td>'gini'</td>
      <td>'entropy'</td>
    </tr>
    <tr>
      <td><b>max_depth</b></td>
      <td>60</td>
      <td>13</td>
    </tr>
    <tr>
      <td><b>max_samples</b></td>
      <td>0.8</td>
      <td></td>
    </tr>
    <tr>
      <td><b>min_samples_leaf</b></td>
      <td>6</td>
      <td></td>
    </tr>
    <tr>
      <td><b>min_samples_split</b></td>
      <td>9</td>
      <td></td>
    </tr>
    <tr>
      <td><b>n_estimators</b></td>
      <td>270</td>
      <td>149</td>
    </tr>
    <tr>
      <td><b>random_state</b></td>
      <td>2</td>
      <td></td>
    </tr>
  </tbody>
</table>

## Reference(s):

- https://archive.ics.uci.edu/ml/datasets/bank+marketing
- [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014
