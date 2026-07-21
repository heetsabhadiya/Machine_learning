# Heart Disease Classification 🫀

This repository contains a Machine Learning project that predicts the presence of heart disease in patients based on various clinical parameters.

---

## 📌 Project Overview

The objective of this project is to build a binary classification model that predicts whether a patient has heart disease (`1`) or not (`0`). Multiple classification algorithms were trained, tuned, and evaluated on clinical patient data.

### Key Results
* **Best Model:** Logistic Regression
* **Accuracy:** **88.52%** on test data (Cross-Validated Average: **84.80%**)
* **Recall:** **92.73%** *(High sensitivity to detect positive heart disease cases)*
* **F1-Score:** **87.05%**

---

## 📊 Dataset Information

The dataset consists of 303 patient records with 13 features:

| Feature | Description |
| :--- | :--- |
| `age` | Age in years |
| `sex` | Gender (1 = male, 0 = female) |
| `cp` | Chest pain type (0-3) |
| `trestbps` | Resting blood pressure (in mm Hg) |
| `chol` | Serum cholestoral in mg/dl |
| `fbs` | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| `restecg` | Resting electrocardiographic results (0-2) |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise induced angina (1 = yes, 0 = no) |
| `oldpeak` | ST depression induced by exercise relative to rest |
| `slope` | Slope of the peak exercise ST segment |
| `ca` | Number of major vessels (0-3) colored by flourosopy |
| `thal` | Thalassemia (1 = normal, 2 = fixed defect, 3 = reversable defect) |
| **`target`** | **0 = No Heart Disease, 1 = Heart Disease** |

---

## 🛠️ Models Trained & Evaluated

The following models were compared during experiments:
1. **Logistic Regression** *(Best performing model)*
2. **Random Forest Classifier**
3. **K-Nearest Neighbors (KNN)**
4. **Support Vector Machine (SVM)**

Hyperparameters were tuned using `RandomizedSearchCV` and `GridSearchCV`.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/hetsabhadiya/Machine_learning.git](https://github.com/hetsabhadiya/Machine_learning.git)
cd Machine_learning