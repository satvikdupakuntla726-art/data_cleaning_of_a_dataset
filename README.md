📝 Overview

This repository contains my Data Cleaning Task, where I took a raw dataset and transformed it into a clean, structured, and analysis-ready format using Python (Pandas).
The purpose of this project is to demonstrate essential data-cleaning steps such as handling missing values, removing duplicates, fixing data types, and standardizing formats.

🔧 Steps I Performed
1️⃣ Identified Missing Values

Checked null values using .isnull().sum()

Filled missing text fields with "Unknown"

Filled missing numeric fields using the median

2️⃣ Removed Duplicate Records

Used .drop_duplicates() to remove all repeated rows

3️⃣ Standardized Text Columns

Converted text to lowercase

Trimmed unnecessary spaces

Cleaned inconsistent entries like country names (usa, united states, etc.)

4️⃣ Cleaned Date Formats

Converted date columns into a consistent format: dd-mm-yyyy

Handled incorrect/inconsistent date entries safely using errors='coerce'

5️⃣ Renamed Column Headers

Made all column names simple and uniform
Example:

Date Added  →  date_added  
Release Year → release_year

6️⃣ Corrected Data Types

Converted numeric-looking text columns to integers

Ensured date columns are in datetime format

Cleaned and standardized values wherever necessary

7️⃣ Exported the Final Cleaned Dataset

Saved the cleaned version as: cleaned_data.csv
