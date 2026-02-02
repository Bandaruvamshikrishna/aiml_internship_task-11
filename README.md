# 🩺 Breast Cancer Classification using Support Vector Machine (SVM)

## 📌 Task Overview
This project is part of **Task 11 – AI & ML Internship**, which focuses on **kernel-based classification** using **Support Vector Machines (SVM)**.  
The objective is to classify breast cancer tumors as **benign or malignant** using the Breast Cancer dataset.

---

## 📊 Dataset
- **Dataset Used:** Sklearn Breast Cancer Dataset  
- **Source:** `sklearn.datasets.load_breast_cancer()`  
- The dataset contains features computed from digitized images of fine needle aspirate (FNA) of breast masses.

---

## 🛠 Tools & Libraries
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## 🧩 Features & Target
- **Features:** 30 numerical features such as mean radius, texture, perimeter, smoothness, etc.
- **Target Variable:**
  - `0` → Malignant
  - `1` → Benign

---

## ⚙️ Workflow
1. Loaded the Breast Cancer dataset using `load_breast_cancer()`
2. Inspected feature shape and class distribution
3. Applied **StandardScaler** to normalize feature values
4. Split data into training and testing sets (stratified)
5. Trained a baseline **Linear SVM**
6. Trained **RBF Kernel SVM** and compared performance
7. Used **GridSearchCV** to tune hyperparameters (`C`, `gamma`)
8. Evaluated the best model using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
9. Plotted **ROC Curve** and calculated **AUC score**
10. Saved the tuned model pipeline for reuse

---

## 📈 Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- AUC Score

---

## 📊 Visualizations
- **ROC Curve with AUC Score**

These visualizations help evaluate model performance beyond accuracy.

---

## 💾 Saved Model
- The trained and tuned SVM model (including scaler) is saved as:
