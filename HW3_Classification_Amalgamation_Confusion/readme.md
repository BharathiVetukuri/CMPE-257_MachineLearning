# HW Week 3 & Reading 4: Classification, Amalgamation , Confusion

### Assignment:

1.Find dataset 2 and 3, amalgamate them ; run classification (each team member try to pick a different classification)
show how performance is enhanced with each amalgamation
you can use [extra: either a regression or] a classification

Run a Muller loop on your data set 1, ds1+ds2, ds1+ds2+ds3 , i.e., your incrementally amalgamated datasets for classification
plot the results in a table

2.Pls update your project writeup as a new section or add a doc that explains this homework.

### Solution:

**Colab Link**: https://colab.research.google.com/drive/1izdFjWZG4qF1y91-30VcVFWA4FOe4K_5?usp=sharing 

**Project WriteUp**: https://docs.google.com/document/d/1_f5Rx0_Bq1Om7wGcp2bVJfWOf3kmxWhl4LG_uvrdcso/edit?tab=t.0 

**Google Drive Link**: https://drive.google.com/drive/folders/1rV2kb16ewh_uNR_wgewvsUsA3EZ-I6Bn 

## Datasets
We will use three datasets:
* Dataset 1 (ds1): Daily activity tracking data (steps, distances, active minutes)
* Dataset 2 (ds2): Sleep monitoring data
* Dataset 3 (ds3): Heart rate monitoring data
Each dataset contains valuable insights that, when combined, can enhance the accuracy of our personalized activity recommendations.

## Methodology
* **Step 1:** Load and Preprocess Data
Load the three datasets from CSV files.
Handle missing values using imputation techniques.
Normalize/scale numerical features to ensure consistent model input.
Merge datasets incrementally to analyze classification performance at each stage.

* **Step 2:** Classification Models
Each team member will implement and evaluate a different classification model:
Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)

* **Step 3:** Model Training and Evaluation
Perform a train-test split.
Train classification models on:
Dataset 1 only (ds1)
Dataset 1 + Dataset 2 (ds1 + ds2)
Dataset 1 + Dataset 2 + Dataset 3 (ds1 + ds2 + ds3)
Evaluate model performance using:
Accuracy Score
Precision, Recall, and F1 Score
Confusion Matrix Analysis

* **Step 4:** Running a Muller Loop
A Muller Loop is used to measure incremental performance improvements by adding datasets sequentially:
Run classification on Dataset 1 (ds1)
Run classification on Dataset 1 + Dataset 2 (ds1 + ds2)
Run classification on Dataset 1 + Dataset 2 + Dataset 3 (ds1 + ds2 + ds3)
Compare results across these iterations.

* **Step 5**: Results Analysis
Visualize results in tables and plots to demonstrate the impact of dataset amalgamation.
Discuss insights on how dataset integration influences classification accuracy and model robustness.
Assess the best-performing classification model based on key performance indicators (KPIs).

## Expected Outcomes
A structured approach to integrating multiple datasets.
Insights into the effectiveness of different classification models.
Evidence of performance improvements via dataset amalgamation.
Well-documented results supporting personalized activity recommendations.

