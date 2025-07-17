# diabetes-anomaly-detection-shap
Unsupervised anomaly detection of diabetes cases using autoencoders and SHAP for explainable AI.
Diabetes Anomaly Detection using Autoencoder and SHAP

This project implements an unsupervised machine learning approach to detect anomalies in a diabetes dataset using autoencoders and explains model outputs using SHAP (SHapley Additive exPlanations). 
The goal is to identify potential diabetic cases based on patterns and feature influence.

Project Overview include:
Type: Unsupervised Learning
Model: Autoencoder
Explainer: SHAP (for feature importance)
Dataset: Public diabetes dataset (custom-prepared)
Accuracy: 90.92%
Key Insight: Smoking status was identified as a strong predictor of diabetes risk.


Tools & Technologies include:
Python
NumPy, Pandas
Scikit-learn
TensorFlow / Keras
Matplotlib, Seaborn
SHAP


Key Steps include:
1. Data Preprocessing
  Cleaned missing and inconsistent entries
  Normalized input features
  Split into training and test sets

2.  Model Architecture
  Built an autoencoder to reconstruct non-diabetic patterns
  Calculated reconstruction error to classify anomalies

3.  Evaluation
  Achieved 90.92% accuracy
  Identified most influential features with SHAP

4.  Visualization
  Used SHAP plots to explain which features influenced anomaly predictions

Results
The model effectively flagged anomalous data points likely to represent diabetic cases.
SHAP analysis revealed that smoking status, BMI, and glucose level were among the most influential features.

✅ What I Learned
Applied unsupervised learning in a real-world health scenario
Used SHAP for transparent, explainable AI
Improved confidence in Python model building, tuning, and visualization






