# Bank-Marketing-Classification

This classification project utilized several Machine Learning models to determine if a bank client has subscribed to a term deposit. The data used represents the results of a telemarketing campaign conducted by a Portuguese banking institiution. Each model was optimized and tuned to achieve the best possible scores.

## Dataset:

This project utilized the bank-additional-full.csv dataset retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/bank+marketing). This version closely resembles the data analyzed by [Moro et al., 2014] and contains 41188 samples and all 20 input features.

More information about each feature can be found in the bank-additional-names.txt file in the data folder.

## Models:

The Accuracy and ROC_AUC scores of each Machine Learning model used are presented below:

<table border = "1">
  <thead>
    <th colspan = "5">Final Classification Results</th>
  </thead>
  <tbody>
    <tr>
      <td><b>Model</b></td>
      <td colspan = "2"><b>Accuracy (%)</b></td>
      <td colspan = "2"><b>ROC_AUC (%)</b></td>
    </tr>
    <tr>
      <td><b></b></td>
      <td><b>CV</b></td>
      <td><b>Val.</b></td>
      <td><b>CV</b></td>
      <td><b>Val.</b></td>
    </tr> 
    <tr>
      <td><b>Logistic Regression (LR)</b></td>
      <td>90.945</td>
      <td>91.588</td>
      <td>93.110</td>
      <td>87.053</td>
    </tr>
    <tr>
      <td><b>Decision Tree (DT)</b></td>
      <td>91.392</td>
      <td>91.903</td>
      <td>93.575</td>
      <td>75.047</td>
    </tr>
    <tr>
      <td><b>Random Forest (RF)</b></td>
      <td>91.569</td>
      <td>91.879</td>
      <td>94.780</td>
      <td>72.988</td>
    </tr>
    <tr>
      <td><b>XGBoost (XGB)</b></td>
      <td>91.689</td>
      <td>92.243</td>
      <td>94.950</td>
      <td>76.251</td>
    </tr>
    <tr>
      <td><b>LightGBM (LGB)</b></td>
      <td>91.763</td>
      <td>92.143</td>
      <td>95.021</td>
      <td>77.243</td>
    </tr>
  </tbody>
</table>

## References:

- https://archive.ics.uci.edu/ml/datasets/bank+marketing
- [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014
