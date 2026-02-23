Data Cleaning Log — Healthcare Operations Analytics

Project Objective:
Prepare a healthcare admissions dataset for analytical modeling and dashboard development supporting hospital operations insights.

Dataset Source:
Synthetic Healthcare Dataset (Kaggle)

Location:
data/raw/healthcare_dataset.csv

Initial Data Assessment:
The dataset contains simulated hospital admission records including:
-Patient demographics
-Admission and discharge dates
-Medical conditions
-Hospitals and providers
-Billing information
-Insurance providers
-Initial observations identified potential data preparation needs before analysis.

Planned Cleaning Steps
1. Remove Personally Identifiable Information (PII)
   Action: Remove patient name column.

Reason:
   Simulate healthcare privacy compliance practices and ensure analytics dataset focuses on operational insights.

2. Data Type Standardization
   Convert columns to appropriate data types:

Column	Target Type
Age -	Whole Number
Billing Amount -	Decimal
Admission Date - 	Date
Discharge Date - 	Date

3. Derived Metrics Creation
Length of Stay (LOS)
Calculate number of days between admission and discharge.

Purpose:
Operational efficiency analysis
Capacity monitoring
Admission Month: Extract month from admission date for trend analysis.

4. Text Standardization
Standardize categorical fields:

Hospital
Medical Condition
Insurance Provider 
Format: Proper case capitalization.

5. Duplicate Removal
Remove duplicate records to ensure accurate aggregations.
Expected Output
Clean dataset exported to:

data/processed/healthcare_cleaned.csv

Tools Used
Power BI (Power Query)
Data transformation best practices

Status

✅ Cleaning in progress
Dataset validated
Ready for modeling
