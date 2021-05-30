# Bank-Marketing-Classification

This classification project utilized several Machine Learning models to determine if a bank client has subscribed to a term deposit. The data used represents the results of a telemarketing campaign by a Portuguese banking institiution. Each model was optimized to achieve the best possible accuracy score.

## Dataset:

This project utilized the bank-additional-full.csv dataset retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/bank+marketing). This version closely resembles the data analyzed by [Moro et al., 2014] and contains 41188 samples and all 20 input features.

More information about each feature can be found in the bank-additional-names.txt file in the data folder.

## Models:

The Accuracy and ROC_AUC scores of each Machine Learning model used is presented below:

<table border = "1">
  <thead>
    <th colspan = "3">Classification Scores Per Model</th>
  </thead>
  <tbody>
    <tr>
      <td><b>Model</b></td>
      <td><b>Accuracy (%)</b></td>
      <td><b>ROC_AUC (%)</b></td>
    </tr>
    <tr>
      <td><b>Decision Tree (DT)</b></td>
      <td>91.392</td>
      <td>93.575</td>
    </tr>
    <tr>
      <td><b>LightGBM (LGB)</b></td>
      <td>91.763</td>
      <td>95.021</td>
    </tr>
    <tr>
      <td><b>Logistic Regression (LR)</b></td>
      <td>90.945</td>
      <td>93.110</td>
    </tr>
    <tr>
      <td><b>Random Forest (RF)</b></td>
      <td>91.569</td>
      <td>94.780</td>
    </tr>
  </tbody>
</table>

## References:

- https://archive.ics.uci.edu/ml/datasets/bank+marketing
- [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014
