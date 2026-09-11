# Data Cleaning – Crime Incidents Dataset

## Project Overview

This project focuses on cleaning and preprocessing a messy crime incidents dataset using Python and Pandas.

The dataset contained duplicate records, missing values, inconsistent categorical values, invalid numerical values, inconsistent date/time formats, and improperly formatted phone numbers.

The goal was to transform the raw dataset into a cleaner and more reliable dataset suitable for further analysis.

## Dataset

**Dataset:** Messy Crime Dataset for Data Cleaning Practice

**Source:** Kaggle – Messy Crime Dataset for Data Cleaning Practice

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Data Cleaning Steps

The following cleaning operations were performed:

1. Loaded and inspected the dataset.
2. Identified missing values and duplicate records.
3. Removed 200 duplicate rows.
4. Standardized text values and removed unnecessary spaces.
5. Standardized inconsistent crime type names.
6. Corrected inconsistent case status values.
7. Standardized resolution categories.
8. Converted severity values and abbreviations into consistent categories.
9. Standardized the `reported_online` column into Yes/No values.
10. Converted `incident_datetime` into the correct datetime format.
11. Identified and corrected invalid suspect and victim ages.
12. Identified and corrected invalid latitude values.
13. Corrected negative arrest counts.
14. Standardized weapon categories.
15. Cleaned victim phone numbers and retained valid 10-digit numbers.
16. Performed final validation checks.
17. Exported the cleaned dataset as a CSV file.

## Final Dataset

- **Rows:** 5,050
- **Columns:** 33
- **Duplicate rows:** 0

## Output

The project produces a cleaned dataset:

`cleaned_crime_incidents.csv`

## Conclusion

The crime incidents dataset was successfully cleaned and standardized.

Duplicate records were removed, inconsistent values were corrected, invalid numerical values were handled, date/time information was converted to the appropriate format, and phone numbers were standardized.

Missing values were retained where the original information was unavailable rather than introducing fabricated data.

The final dataset is more consistent and reliable and can be used for further data analysis and visualization.

## Internship

This project was completed as part of the **Oasis Infobyte Data Analytics Internship – Level 1**.

**Task:** Cleaning Data
