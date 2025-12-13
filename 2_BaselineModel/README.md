# Baseline Model

**[Notebook](baseline_model.ipynb)**

## Baseline Model Results

### Model Selection
- **Baseline Model Type:** linear regression 
- **Rationale:** We tried a linear regression model and a random forest model because both seemed suitable for our task (predicting the production with 1-2 parameters) In the end we decided on the linear regression model, because it seemed to work best.

### Model Performance
- **Evaluation Metric:** MSE
- **Performance Score:** For Dobersdorf, we have a MSE of 0.0125, for Elmshorn its 0.0179 
- **Cross-Validation Score:** for DObersdorf: 0.0377 +- 0.00143
For Elmshorn: 0.00698 +- 0.00068

### Evaluation Methodology
- **Data Split:** Train:80%, Test:20%
- **Evaluation Metrics:** Since we don't have any anomalies in our dataset, we decided to use mean squared error for our linear regression task, since it is the most commonly used and serves it's perpose.

### Metric Practical Relevance
MSE is practically relevant because it penalizes large errors strongly, aligns with common training losses, has strong mathematical and statistical properties, reflects risk-averse error costs and enables consistent and efficient model evaluation. MSE is computationally efficient and analytically manageable, especially in large-scale or production systems. The smaller the MSE, the better, but possible overfitting must be ruled out.

## Next Steps
This baseline model serves as a reference point for evaluating more sophisticated models in the [Model Definition and Evaluation](../3_Model/README.md) phase.
