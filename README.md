# Titanic-Survival-Pipeline
End-to-end ML Pipeline for Titanic Survival Prediction with 81.56% Accuracy.
###  Project Overview
This project predicts the survival of passengers on the Titanic using Machine Learning. It demonstrates a professional workflow using **Scikit-Learn Pipelines** for automated data processing and model training.

###  Performance
- **Model:** Random Forest Classifier 
- **Accuracy:** 81.56% 
- **Key Technique:** Hyperparameter Tuning (`max_depth=5`) and Feature Encoding.

###  Technical Workflow
1. **Numerical Pipeline:** Handles missing values (Median Imputation) and scales data (StandardScaler).
2. **Categorical Pipeline:** Converts gender and class into numbers using **One-Hot Encoding**.
3. **ColumnTransformer:** Maps specific logic to specific columns efficiently. 
4. **Final Pipeline:** Combines preprocessing and the model into a single, automated object.

###  How to Run
- Open the `.ipynb` file in Google Colab or Jupyter Notebook.
- Run all cells to see the pipeline in action!
