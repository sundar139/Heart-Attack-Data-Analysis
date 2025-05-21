# Heart Attack Data Analysis

## Summary
In this project, we analyzed a medical dataset obtained from kaggle to build a predictive model for heart attack detection. The dataset included vital signs and biochemical markers such as Age, Gender, Heart Rate, Systolic blood pressure, Diastolic blood pressure, Blood Sugar, Troponin, Ck-MB readings. We conducted thorough exploratory data analysis using visualizations, correlation matrices, and statistical testing to identify significant features. A new feature, Pulse Pressure, was engineered to enhance predictive insight.

We trained a Random Forest Classifier and conducted feature importance analysis. From correlation analysis, statistical testing, and model-based feature importance, we identified Age, Troponin, Ck-MB, and possibly Gender as the most critical predictors of heart attacks. These findings align with medical domain knowledge and reinforce the reliability of our approach in identifying high-risk patients.

## Dataset Overview

The dataset consists of 9 attributes across medical and demographic features of patients and a binary outcome column indicating heart attack presence ('Result'):

* **Age**
* **Gender** (0 = Female, 1 = Male)
* **Heart Rate**
* **Systolic Blood Pressure**
* **Diastolic Blood Pressure**
* **Blood Sugar** (1 if >120, else 0)
* **Ck-MB** (cardiac enzyme)
* **Troponin** (protein biomarker for heart injury)
* **Result** (Negative = No heart attack, Positive = Heart attack)

Additionally, a new feature **Pulse Pressure** (Systolic - Diastolic) was derived to capture vascular stiffness and cardiovascular risk.
