# Renewable Energy Generation Prediction

## Repository Link

https://github.com/voss-jessica1-rgb/Renewable-Energie.git

## Description

[We want to accurately predict daily solar photovoltaic (PV) power generation on privately owned solar plants using weather (forecast) data.]

### Task Type

[Regression]

### Results Summary

#### Best Model Performance
- **Best Model:** [Simple Neural Network (baseline model)"]
- **Evaluation Metric:** [Accuracy calculating the MAE in percent.]
- **Final Performance:** [Best score achieved: 91% accuracy]

#### Model Comparison
- **Alternative Model:** [Long-short term memory (LSTM) model performance for comparison]
- **LSTM Performance:** [85-88% accuracy"]

#### Key Insights
- **Most Important Features:** [Sunlight duration and average temperature]
- **Model Strengths:** [The baseline model exhibits a linear prediction to actual value relation. Performing reasonably well across the whole generation spectrum.]
- **Model Limitations:** [For the LSTM model we did not have enough training data. More data would probably increase the accuracy of the that model.]
- **Business Impact:** [Practical implications of the model performance: The better the perdiction, the better one could adjust energy usage to it. Use case: Which day of the coming week, should I charge the electric car?]

## Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**
2. **[Dataset Characteristics](1_DatasetCharacteristics/exploratory_data_analysis_updated.ipynb)**
3. **[Baseline Model (Dobersdorf)](2_BaselineModel/baseline_model_final_Dobersdorf.ipynb)**
   **[Baseline Model (Elmshorn)](2_BaselineModel/baseline_model_final_Elmshorn.ipynb)**
4. **[Model Definition and Evaluation(Dobersdorf)](3_Model/model_definition_evaluation_Dobersdorf_final.ipynb)**
   **[Model Definition and Evaluation(Elmshorn)](3_Model/model_definition_evaluation_Elmshorn_final.ipynb)**
6. **[Presentation](4_Presentation/README.md)**

## Cover Image

![Project Cover Image](CoverImage/Cover_Image.jpeg)
