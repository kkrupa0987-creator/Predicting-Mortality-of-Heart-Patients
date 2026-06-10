# Heart Patient Mortality Prediction
A Machine Learning project that predicts the mortality risk of heart failure patients using clinical health records. The goal is to identify patterns in patient data and build predictive models that can assist in early risk assessment and healthcare decision-making.

# Project Overview
Heart disease and heart failure are among the leading causes of death worldwide. Early identification of high-risk patients can help healthcare professionals provide timely treatment and improve patient outcomes.

In this project, clinical data from heart failure patients is analyzed to understand the factors associated with mortality. The dataset undergoes preprocessing, exploratory data analysis, feature scaling, and model training. Multiple machine learning approaches are then used to predict whether a patient is likely to experience a death event.

# Dataset Features
Age
Anaemia
Diabetes
High Blood Pressure
Ejection Fraction
Platelets
Serum Creatinine
Serum Sodium
Smoking Status
Follow-up Time

## Project Workflow
1. **Data Exploration** – Understanding the dataset and its features.
2. **EDA & Visualization** – Analyzing patterns using statistical methods and visualizations.
3. **Data Preprocessing** – Feature selection, scaling, and train-test splitting.
4. **Model Development** – Training SVM and ANN models.
5. **Model Evaluation** – Measuring performance using classification metrics.
6. **Result Analysis** – Comparing outcomes and interpreting model predictions.

# Models Used
## Support Vector Machine (SVM)
A supervised machine learning algorithm used for classification tasks. SVM attempts to find the optimal boundary that separates patients based on mortality risk.

## Artificial Neural Network (ANN)
A deep learning model built using TensorFlow/Keras. The neural network learns complex relationships within patient health data and predicts mortality outcomes.

# Libraries and Tools
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, TensorFlow, Keras

# Evaluation Metrics
Accuracy Score, Precision, Recall, F1 Score, Classification Report, Confusion Matrix

# Future Scope
- Optimize models through hyperparameter tuning.
- Compare performance with additional machine learning algorithms.
- Deploy the model as a web application.
- Use larger datasets to improve prediction accuracy.
