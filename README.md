# Water Potability Prediction

This project aims to predict water potability using machine learning models. The focus is on analyzing various water quality indicators to determine whether the water is safe (potable) or unsafe for human consumption.

## Project Overview
Water potability is a critical concern for public health. The dataset used in this project evaluates water quality based on several physical and chemical parameters. The goal is to develop predictive models that help city water authorities make informed decisions regarding water safety.

## Dataset
- **Key Variables**:
  - **pH**: Acidity or alkalinity level.
  - **Hardness**: Measure of mineral content.
  - **Solids**: Total dissolved solids.
  - **Chloramines**: Chloramines concentration.
  - **Sulfate**: Sulfate concentration.
  - **Conductivity**: Electrical conductivity.
  - **Organic_carbon**: Organic carbon content.
  - **Trihalomethanes**: Trihalomethanes concentration.
  - **Turbidity**: Water clarity level.
  - **Potability**: Target variable (1 = potable, 0 = non-potable).

## Key Steps
1. **Data Exploration**:
   - Understanding dataset structure and feature distributions.
2. **Preprocessing**:
   - Handling missing values and scaling features.
3. **Model Building**:
   - Logistic Regression, K-Nearest Neighbors (KNN), and Support Vector Classifier (SVC).
4. **Evaluation**:
   - Confusion Matrix, Precision, Recall, F1 Score, ROC Curve, and AUC.
5. **Optimization**:
   - Focusing on minimizing false positives to reduce health risks from unsafe water.

## False Positives and False Negatives
- **False Positives (FP)**: Predicting water as potable when it is unsafe, posing significant health risks.
- **False Negatives (FN)**: Predicting water as unsafe when it is potable, leading to resource wastage.

Given the severe implications of false positives, the models prioritize **high precision** for the potable class.

## Technologies Used
- **Programming**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Getting Started
1. Clone this repository.
2. Run the notebook `Water_Potability_ML_Project.ipynb`.
3. Follow the steps for data processing, model training, and evaluation.

## Results
The project highlights the trade-offs between precision and recall for different models, with a focus on ensuring public health safety by minimizing false positives.

