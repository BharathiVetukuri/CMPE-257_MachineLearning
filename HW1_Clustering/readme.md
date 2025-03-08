# 📊 Fitbit Activity Clustering: K-Means & Additional Method

## 📌 Project Overview
This project applies **K-Means and an additional clustering method** to analyze **Fitbit activity data**. The goal is to discover **user behavior patterns** and provide insights for **personalized activity recommendations**.

## 📂 Artifacts

**Colab Link:** https://colab.research.google.com/drive/1c10XF50GQ63hj2hDO9AfOa1Hg7BDmfsd?usp=sharing 

**Write Up Link:** https://drive.google.com/file/d/1t_iGsUUDvAq0_-uF1p2HCFjI0n8GBwjR/view?usp=drive_link 

**Google Drive Link:** https://drive.google.com/drive/folders/1-pQuDngrw8GofkAKQESyRMA1hPNB4RTF 

## 📂 Dataset
- **Source:** [Fitbit Fitness Tracker Dataset](https://www.kaggle.com/datasets/arashnic/fitbit)
- **File Used:** `dailyActivity_merged.csv`
- **Features:**
  - `TotalSteps`, `TotalDistance`, `VeryActiveMinutes`, `Calories`
  - **Target:** Unsupervised clustering (no predefined labels)

## 🔬 Methodology
1️⃣ **Data Preprocessing**  
   - Converted `ActivityDate` to datetime  
   - Handled missing values & scaled features  
2️⃣ **Clustering Methods Applied**  
   - **K-Means Clustering** (with Elbow Method)  
   - **DBSCAN** (to detect varying density clusters)  
3️⃣ **Visualization & Evaluation**  
   - Cluster separation plots  
   - Feature distributions across clusters  

## 📊 Key Findings
- Users grouped into **low, medium, and high activity levels**.
- **DBSCAN** identified outliers better than K-Means.
- **Potential Applications:**
  - **Personalized activity recommendations**
  - **Optimized fitness schedules**
