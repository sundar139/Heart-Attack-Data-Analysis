# 🫀 Heart Attack Prediction and Data Analysis

## Introduction

This project explores a heart attack dataset collected from **Zheen Hospital in Erbil, Iraq**, spanning from January 2019 to May 2019. The primary goal is to analyze and visualize various clinical and demographic factors associated with heart attacks and build a predictive model with high accuracy. The dataset contains 9 features, including biomarkers such as **Troponin** and **CK-MB**, vital signs like **heart rate and blood pressure**, and demographic attributes such as **age and gender**.

Understanding the relationship between these features and heart attack risk can help medical professionals and data scientists make better-informed decisions and potentially support early diagnosis.

## Objectives

- **Explore** the dataset using **exploratory data analysis (EDA)** to uncover trends, correlations, and outliers.
- **Engineer** relevant features for improving model performance.
- **Visualize** the impact of various medical attributes on heart attack occurrence.
- **Predict** heart attack outcomes using machine learning models.
- **Evaluate** the performance of the models and derive clinical insights.

## Insights Sought

During this analysis, we aim to answer key questions such as:

- Which features are most strongly correlated with heart attack occurrence?
- Are there significant differences in heart attack incidence by **gender** or **age**?
- How do **Troponin** and **CK-MB** levels influence the prediction of heart attacks?
- Can we build a reliable model to **predict heart attack risk** with high accuracy?

## Methods & Visualization

1. **Data Cleaning and Preprocessing**

   - Handled categorical variables (e.g., gender and output normalization).
   - Created binary features like `high_glucose` (blood sugar > 120).

2. **Exploratory Data Analysis (EDA)**

   - Plotted histograms, correlation heatmaps, and boxplots to explore distributions and relationships.
   - Assessed outliers in vital signs and biomarker levels.

3. **Feature Engineering**

   - Created meaningful representations of features.
   - Normalized and scaled features where necessary.

4. **Modeling**

   - Applied classification algorithms including Logistic Regression, Decision Trees, and ensemble models.
   - Achieved up to **99% prediction accuracy** in the final model.

## Findings

- **Troponin** and **CK-MB** were among the most predictive features for heart attack classification.
- **Age** showed a positive correlation with heart attack risk, especially in older male patients.
- A notable disparity was observed between male and female patients in terms of outcome prevalence.
- **Blood sugar** alone was not a strong predictor, but when combined with other variables, it enhanced model performance.
- The predictive model successfully classified heart attack cases with **high precision and recall**, demonstrating its clinical applicability.

## Conclusion

This analysis provides a comprehensive view of the clinical indicators related to heart attacks. Through effective data visualization and machine learning, the project demonstrates that **data-driven healthcare insights** can significantly support diagnostic processes. With a **99% accurate prediction model**, this study highlights the potential of using even relatively small datasets for impactful medical decision support.

The outcomes of this project suggest that biomarkers like **Troponin** and **CK-MB**, when analyzed alongside vital signs and demographic data, can be powerful tools for **early detection** and **intervention planning** in cardiovascular care.

## Dataset Description

The dataset has 9 column:

- Age: The patient's age
- Gender: Biological sex of the patient (The male is set to 1 and the female to 0)
- Heart Rate: The number of heartbeats per minute
- Systolic Blood Pressure: The pressure in arteries when the heart contracts
- Diastolic Blood Pressure: The pressure in arteries between heartbeats
- Blood Sugar: The patient's blood glucose level
- Ck-mb: A cardiac enzyme released during heart muscle damage
- Troponin:A highly specific protein biomarker for heart muscle injury
- Result: The outcome label indicating whether or not the patient experienced a heart attack

## Dataset Reference

Rashid, Tarik A.; Hassan, Bryar (2022), “Heart Attack Dataset”, Mendeley Data, V1, doi: [10.17632/wmhctcrt5v.1](https://doi.org/10.17632/wmhctcrt5v.1)
