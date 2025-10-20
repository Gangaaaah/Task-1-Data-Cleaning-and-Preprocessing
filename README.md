# Medical Appointment Dataset Cleaning

## Project Overview
This project focuses on cleaning the **"Medical Appointment No Shows"** dataset using **Excel Power Query**. The dataset includes patient appointment information such as age, gender, scheduled date, appointment date, and whether the patient attended the appointment. The goal was to prepare the dataset for accurate analysis by addressing inconsistencies, formatting issues, and standardizing values.

## Data Cleaning Steps

### 1. Loaded Dataset
Imported the dataset into Excel Power Query for processing.

### 2. Promoted Headers
Converted the first row of data into column headers for clarity.

### 3. Handled Blanks and Errors
Checked for missing values or errors and confirmed that none were present.

### 4. Removed Duplicates
Verified and removed duplicate rows to ensure data uniqueness (none found).

### 5. Trimmed Text Fields
Cleaned leading and trailing spaces from text columns to maintain consistency.

### 6. Converted Data Types
Standardized date columns to proper date/time types and other columns to their respective data types.

### 7. Renamed Columns
Updated column headers to lowercase with underscores for uniformity.

### 8. Standardized Text Values
Replaced abbreviations in the gender column (`M` and `F`) with **"male"** and **"female"** for consistency.

### 9. Saved Cleaned Dataset
Renamed the query to `Medical_Appointments_Cleaned` and saved the cleaned version for analysis.

## Outcome
The dataset is now **clean, consistent, and ready for analysis**, enabling accurate insights and reporting on medical appointment attendance.

