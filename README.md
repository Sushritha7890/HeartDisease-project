# HEART DISEASE PREDICTION USING MACHINE LEARNING

## Project Overview

This project predicts the presence of heart disease using Machine Learning classification algorithms. The dataset is preprocessed to improve data quality by removing duplicate records, handling invalid values, encoding categorical features, and scaling numerical features before training the models.

The project compares the performance of three classification algorithms:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

---

## Dataset

The project uses the **Heart Disease Dataset**, which contains patient medical information such as:

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG (restecg)
* Maximum Heart Rate (thalach)
* Exercise-Induced Angina (exang)
* ST Depression (oldpeak)
* Slope
* Number of Major Vessels (ca)
* Thalassemia (thal)
* Target (Heart Disease)

---

## Data Preprocessing

The following preprocessing steps were performed before model training:

* Removed duplicate records using `drop_duplicates()`
* Replaced invalid values (`chol = 0` and `trestbps = 0`) with `NaN`
* Imputed missing values using the median
* Applied One-Hot Encoding to categorical features:

  * cp
  * thal
  * slope
  * restecg
* Standardized numerical features using `StandardScaler`
* Split the dataset into training and testing sets

---

## Machine Learning Models

The following classification algorithms were implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree 
Each model was evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report
* F1 Score

---

## Model Comparison

| Algorithm           | Accuracy                  | F1 Score                  |
| ------------------- | ------------------------- | ------------------------- |
| Logistic Regression | 85%                       | 0.86                      |
| K-Nearest Neighbors | 82%                       | 0.83                      |
| Decision Tree       | 74%                       | 0.76 |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## Project Structure

```
Heart-Disease-Prediction/
│
├── heart.csv
├── heart_cleaned.csv
├── Heart_Disease_Prediction.ipynb
├── README.md
└── requirements.txt
```




## 📈 Results

After preprocessing the dataset and training the models, the algorithms are compared using Accuracy and F1 Score to determine the best-performing classifier for heart disease prediction.


