# Census Income Prediction

## 📌 Overview

This project predicts whether an individual's annual income is **greater than $50K or less than or equal to $50K** based on demographic and employment-related features.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## 📊 Dataset

The dataset contains demographic and employment-related information such as:

- Age
- Workclass
- Education
- Marital Status
- Occupation
- Relationship
- Race
- Gender
- Capital Gain
- Capital Loss
- Hours per Week
- Native Country

### Target Variable

The target variable represents whether an individual's income is:

- `<=50K`
- `>50K`

## 🔄 Project Workflow

1. Load the dataset
2. Understand the data
3. Handle missing values
4. Perform exploratory data analysis
5. Encode categorical features
6. Perform feature preprocessing
7. Split data into training and testing sets
8. Train machine learning models
9. Evaluate model performance
10. Compare model results
11. Predict income class for new data

## 🤖 Machine Learning

The project uses classification algorithms to predict income levels.

Model performance is evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 📁 Project Structure

```text
Census-Income-Prediction/
│
├── Census_Income_Prediction.ipynb
├── requirements.txt
└── README.md
