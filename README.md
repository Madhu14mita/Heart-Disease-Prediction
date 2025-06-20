# 🫀 Heart Disease Prediction using Machine Learning

This repository demonstrates a hands-on application of machine learning techniques to predict the likelihood of heart disease based on clinical and demographic data. It includes end-to-end exploratory analysis, model training, and prediction interfaces using real-world data.

## 📁 Project Structure

- **`heart-disease.csv`** – Dataset containing patient medical records  
- **`end_to_end_pro.ipynb`** – End-to-end ML pipeline exploring and comparing:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest  
  Despite hyperparameter tuning, achieved less than 90% accuracy
- **`heart_disease.ipynb`** – Focused Logistic Regression model with:
  - User input system for live prediction
  - Evaluation on test and training sets

### ✅ Model Performance
| Model                | Train Accuracy | Test Accuracy |
|---------------------|----------------|----------------|
| Logistic Regression | 84.43%         | 84.61%         |
| KNN / Random Forest | ~84–89%        | ~84–88%        |

> While none of the models crossed the 90% mark, the system demonstrates strong foundational performance suitable for educational and early diagnostic use.

## 🔍 Features Used
- Age, Sex, Chest Pain Type
- Resting Blood Pressure, Cholesterol
- Fasting Blood Sugar, ECG Results
- Max Heart Rate, Exercise-Induced Angina
- ST Depression, Slope of ST Segment
- Number of Major Vessels, Thalassemia

## 💡 Highlights
- End-to-end comparison of classification models
- Clean user interface for testing predictions via form input
- Insightful model evaluation and error analysis
