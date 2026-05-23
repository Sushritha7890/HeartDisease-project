# Heart Disease Prediction using Machine Learning

This project predicts heart disease using multiple Machine Learning algorithms and compares their performance using Accuracy and F1-Score.

The project is implemented using Python and Scikit-learn.

---

#  Project Objective

The objective of this project is to:

- Analyze heart disease data
- Preprocess and clean the dataset
- Train multiple machine learning models
- Compare model performance
- Identify the best-performing algorithm

---

#  Dataset

Dataset used:
"heart.csv"

Technologies Used
Python
Pandas
NumPy
Scikit-learn

# The following algorithms were implemented:


Logistic Regression	Linear classification model
K-Nearest Neighbors (KNN)	Neighbor-based classification
Decision Tree	Tree-based classification


Models are evaluated using:

Accuracy Score
F1 Score
Confusion Matrix
Classification Report

# Project Workflow:
1. Import Libraries

Required Python libraries are imported.

2. Load Dataset

Dataset is loaded using Pandas.

df = pd.read_csv("heart.csv")

3. Data Preprocessing
Handle missing values
Clean dataset
Feature scaling using StandardScaler

5. Train-Test Split

Dataset is divided into:

Training data
Testing data

5. Train Models

Three ML algorithms are trained:

Logistic Regression
KNN
Decision Tree

6. Evaluate Models

Accuracy and F1-score are calculated for each model.

7. Compare Results

A comparison table is generated to identify the best algorithm.


Model Comparison Results
Algorithm         	Accuracy	F1 Score
Logistic Regression 	80%	      0.81
KNN	                  83%	      0.84
Decision Tree	        99%     	0.99

# Observation Report

Observations After Model Comparison
•	Logistic Regression provided good baseline performance with stable predictions.
•	KNN improved the prediction accuracy compared to Logistic Regression by analyzing nearest neighboring data points.
•	Decision Tree achieved the highest accuracy and F1-score among all models.
•	Decision Tree handled the dataset effectively and captured complex patterns in the data.


Best Performing Model
Model          	Accuracy	F1 Score
Decision Tree	   99%       	0.99
✅ Conclusion

The project successfully demonstrates the application of Machine Learning techniques for heart disease prediction.

Among all models:

Decision Tree performed best
Achieved:
99% Accuracy
0.99 F1 Score

# The project highlights:

•Data preprocessing
•Feature scaling
•Model training
•Model evaluation
•Performance comparison
