# Heart Attack Risk Prediction Model

This project implements a decision tree classifier to predict heart attack risk based on various health and lifestyle factors. The model is built using Python and scikit-learn, leveraging a dataset containing information about individuals' health metrics and their corresponding heart attack risk levels.

## Dataset

The dataset used in this project contains the following features:
- **Age**
- **Gender**
- **Smoking status**
- **Alcohol consumption**
- **Physical activity level**
- **BMI (Body Mass Index)**
- **Diabetes status**
- **Hypertension status**
- **Cholesterol level**
- **Resting blood pressure**
- **Heart rate**
- **Family history of heart disease**
- **Stress level**
- **Chest pain type**
- **Thalassemia**
- **Fasting blood sugar**
- **ECG results**
- **Exercise-induced angina**
- **Maximum heart rate achieved**

The target variable is **"Heart_Attack_Risk"** with three possible levels: **Low**, **Moderate**, and **High**.

## Model

The model uses a `DecisionTreeClassifier` from scikit-learn with the following parameters:

```python
DecisionTreeClassifier(random_state=123)
```

The `random_state` parameter is set to 123 to ensure reproducibility of results.

## Implementation

The implementation follows these steps:
1. **Import necessary libraries**: `pandas`, `scikit-learn`.
2. **Load the dataset**: Read the data from a CSV file.
3. **Preprocess the data**:
   - Handle categorical variables.
   - Split the dataset into features and target.
4. **Split the data**: Divide the dataset into training and testing sets.
5. **Create and train the model**: Use the decision tree classifier.
6. **Evaluate the model**:
   - Make predictions on the test set.
   - Assess performance using metrics such as accuracy, confusion matrix, and classification report.

## Usage

To use this model:
1. Ensure you have Python and the required libraries installed (`pandas`, `scikit-learn`, `matplotlib`).
2. Place your dataset file (`heart_attack_risk_dataset.csv`) in the appropriate directory.
3. Run the Jupyter notebook or Python script to execute the workflow and evaluate the model.

## Results

The model provides predictions for heart attack risk levels based on input features. It can be used for exploratory data analysis and to assist in identifying high-risk individuals.

