# 📊 Data Distribution & Model Performance

## 📌 Project Overview
This project explores how **modifying data distributions** affects the performance of machine learning models. Using **upsampling & downsampling**, we dynamically alter the distribution of a key feature and observe its impact on model metrics like **F1-score and confusion matrix**. The project includes an **interactive dashboard** that allows real-time experimentation with data distributions.

## 🚀 Key Features
✅ **Modify data distribution** dynamically using a slider  
✅ **Train & evaluate models** (Random Forest, XGBoost, SVM, MLP)  
✅ **Interactive confusion matrix** updates based on data changes  
✅ **Live comparison of F1-score** for different distributions  
✅ **Dashboard built using Holoviz Panel & HoloViews**  

---
## 📊 Dataset Used
- **Source:** Fitbit Activity Data (`dailyActivity_merged.csv`)
- **Features:**
  - `TotalSteps`: Total steps taken
  - `VeryActiveMinutes`: Minutes spent in intense physical activity
  - `Calories`: Calories burned (converted to classification target)
  - `ActivityDate`: Timestamp (converted to DateTime)

---

## 🔬 Data Preprocessing
1️⃣ **Converted `ActivityDate` to DateTime**  
2️⃣ **Created `TargetClass` using Calories (Low, Medium, High)**  
3️⃣ **Feature Selection:** Identified `VeryActiveMinutes` as an important feature  
4️⃣ **Implemented data modification techniques** (upsampling/downsampling)  

---

## 🤖 Models Implemented
✅ **Random Forest (RF)**  
✅ **XGBoost (XGB)**  
✅ **Support Vector Machine (SVM)**  
✅ **Multi-Layer Perceptron (MLP)**  

Each model is evaluated **before and after modifying data distribution** using the **Muller Loop approach**.

---

## 📊 Performance Metrics
- **F1-score** (Goodness of model predictions)
- **Confusion Matrix** (Visual misclassification analysis)
- **Specificity vs Sensitivity** (Impact of class imbalance)

---

## 🎛️ Interactive Dashboard Features
⚡ **Modify feature distribution dynamically**  
📈 **Retrain models instantly**  
🎯 **Live confusion matrix updates**  
📊 **Compare model performance interactively**  

<img width="456" alt="image" src="https://github.com/user-attachments/assets/bc4c8c2a-d983-4eb9-9743-b53f5012bbc4" />

---
## 📌 Key Learnings & Insights
* Upsampling improved MLP performance significantly, making it more effective for imbalanced datasets.
* XGBoost struggled with modified distributions, proving it is sensitive to data shifts.
* Random Forest remained stable across different distributions, demonstrating robustness.
* SVM performed better with downsampled data, as it benefits from a more balanced dataset.
