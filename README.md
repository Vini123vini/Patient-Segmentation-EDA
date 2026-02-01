# Patient Segmentation EDA

## Overview
This project performs **Exploratory Data Analysis (EDA)** on a patient dataset to uncover insights for healthcare analytics.

## Dataset
Columns include:
- PatientID, Age, Gender, State, City, Height_cm, Weight_kg, BMI, Insurance_Type, Primary_Condition, Num_Chronic_Conditions, Annual_Visits, Avg_Billing_Amount, Last_Visit_Date, Days_Since_Last_Visit, Preventive_Care_Flag

## Steps Performed
1. Data Loading and Cleaning
2. Missing Value Handling
3. Basic Statistics and Data Understanding
4. Visualizations:
   - Age Distribution (Histogram)
   - Gender Distribution (Countplot)
   - Insurance Type Distribution (Countplot)
   - BMI vs Billing Scatter Plot
   - Chronic Conditions vs Annual Visits (Bar Plot)
   - Correlation Heatmap
5. Insights Extraction

## Key Insights
- Majority of patients are between 30–55 years old.
- Gender distribution is relatively balanced.
- Private insurance dominates among patients.
- Patients with higher BMI tend to have higher billing amounts.
- Chronic conditions drive higher annual visits.
- Preventive care usage is low, indicating opportunity for improvement.

## Tools & Libraries
- Python, Pandas, NumPy, Matplotlib, Seaborn
