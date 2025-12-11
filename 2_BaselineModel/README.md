# Baseline Model

**[Notebook](baseline_model.ipynb)**

## Baseline Model Results

### Model Selection
- **Baseline Model Type:** linear regression 
- **Rationale:** We tried a linear regression model and a random forest model because both seemed suitable for our task (predicting the production with 1-2 parameters) In the end we decided on the linear regression model, because it seemed to work best.

### Model Performance
- **Evaluation Metric:** MSE
- **Performance Score:** For Dobersdorf, we have a MSE of 0.0125, for Elmshorn its 0.0179 
- **Cross-Validation Score:** [Mean and standard deviation of CV scores, e.g., 0.82 ± 0.03]

### Evaluation Methodology
- **Data Split:** Train:80%, Test:20%
- **Evaluation Metrics:** [List all metrics used and justify why they are appropriate for this problem]

### Metric Practical Relevance
[Explain the practical relevance and business impact of each chosen evaluation metric. How do these metrics translate to real-world performance and decision-making? What do the metric values mean in the context of your specific problem domain?]

## Next Steps
This baseline model serves as a reference point for evaluating more sophisticated models in the [Model Definition and Evaluation](../3_Model/README.md) phase.
