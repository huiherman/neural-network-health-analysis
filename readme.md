# Neural Network Analysis on Health Dataset

## 📌 Brief Description
This project explores predictive modeling using neural networks applied to an obfuscated health dataset. The goal is to compare different neural network configurations with decision trees to identify the most accurate model for health status prediction.

## 🎯 Objective
To evaluate and compare the performance of multiple neural network models—one with default settings, one using z-score standardization with missing inputs included, and one with increased hidden layers—and determine the best performing model in terms of accuracy and variable importance.

## 📁 Project Structure
- **/data/**: Contains the Heart dataset from previous assignments.
- **/models/**: Neural network and decision tree pipelines in SAS Model Studio.
- **/outputs/**: Accuracy, misclassification rate, and variable importance reports.
- **/docs/**: Assignment answers and visual insights from SAS.

## 📊 Key Results
- **Most Accurate Model**: Neural Network with z-score standardization and missing inputs.
- **Champion Accuracy**: 0.6737
- **Top Variables**: Systolic, Diastolic, Blood Pressure Status, Cholesterol, Weight, Sex, Smoking, Height.
- **Misclassification Rate (Base Model)**: 0.3188

## 📚 Learning Outcomes
- Understood how to apply neural networks using SAS Model Studio.
- Learned how data preprocessing (z-score, missing inputs) affects model performance.
- Compared multiple models to select the most accurate one using accuracy and misclassification metrics.
- Interpreted model insights to identify key health variables influencing predictions.

## 🧠 Skills Applied
Neural network modeling, decision tree comparison, SAS Model Studio, data preprocessing with z-score standardization, misclassification analysis, and variable importance evaluation.
