# 🍷 Red Wine Quality Prediction

## 📌 Overview
The goal of this project is to **predict the quality of red wine** based on its **physicochemical properties**.  
Using **Machine Learning** techniques, we train models to classify wine quality on a scale (typically 0–10) using data provided in the **Wine Quality Dataset**.

---

## 📊 Dataset Details
- **Source:** UCI Machine Learning Repository / Kaggle (Wine Quality Dataset)  
- **Size:** ~1,600 samples (red wine)  
- **Features:**  
  - `fixed acidity`  
  - `volatile acidity`  
  - `citric acid`  
  - `residual sugar`  
  - `chlorides`  
  - `free sulfur dioxide`  
  - `total sulfur dioxide`  
  - `density`  
  - `pH`  
  - `sulphates`  
  - `alcohol`  
  - `quality` (target variable, ordinal scale 0–10)

---

## 🔄 Workflow

### 🧹 Data Preprocessing
- Checked for **missing values**  
- Data **cleaning & normalization**  
- Exploratory Data Analysis (**EDA**) with histograms, pairplots, and correlations  

### ✨ Feature Engineering
- Correlation heatmaps to identify important features  
- Standardization/Scaling of numerical features  

### 🤖 Model Training
Implemented and compared multiple ML models:
- **Logistic Regression**  
- **Decision Tree Classifier**  
- **Random Forest Classifier**  
- **Support Vector Classifier (SVC)**  
- **K-Nearest Neighbors (KNN)**  

### 📈 Evaluation
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-Score  

---

## 🚀 Quick Start

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Run the notebook
```bash
jupyter notebook red-wine-prediction.ipynb
```

---

## 🏆 Results
- Best accuracy achieved: **93%**  
- **Random Forest Classifier** gave the most robust results  
- Feature importance analysis showed **alcohol**, **volatile acidity**, and **sulphates** as key predictors  

---

## 🔮 Future Plans
- Hyperparameter tuning for even better performance  
- Experiment with advanced models (**XGBoost, LightGBM**)  
- Deploy as a simple **Flask/Django web app** for interactive wine quality prediction  

---

## 👨‍💻 Author
Created by an **AI/ML & MLOps enthusiast**, currently a **final-year student in India**, preparing for higher education exams and developing practical ML projects.  

---

## 📜 License
Open for **educational and research purposes**.  
Recommended: [MIT License](https://opensource.org/licenses/MIT)  

---
