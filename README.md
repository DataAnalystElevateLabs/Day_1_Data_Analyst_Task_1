# Day_1_Data_Analyst_Task_1
First Task of Data Analyst Internship @ Elevate Labs

problem statement/Guidelines:
 Identify and handle missing values using .isnull() in Python or filters in Excel.
 Remove duplicate rows using .drop_duplicates() or Excel’s “Remove Duplicates”.
 Standardize text values like gender, country names, etc.
 Convert date formats to a consistent type (e.g., dd-mm-yyyy).
 Rename column headers to be clean and uniform (e.g., lowercase, no spaces).
 Check and fix data types (e.g., age should be int, date as datetime)

Steps followed in Excel:
1.Imported raw dataset Raw_Sales_Data from Kaggle CSV into Excel for cleaning.

2.Checked for nulls and blanks using Filter and COUNTBLANK() to identify missing data.

3.Changed data types for all columns to ensure correct type (number, text, date).

4.Standardized column names: capitalized first letters and applied highlighting for clarity.

5.Formatted Sales_Date using a helper column:

6.Used TEXT() to convert date format from mm/dd/yyyy → dd/mm/yyyy.

7.Copied helper column → Paste Special → Values to replace original dates.

8.Deleted the old Sales_Date and helper column to remove unnecessary references.

9.Deleted redundant column Sales_Rep_by_Region to remove unnecessary data.

10.Rounded numerical columns to two decimal places for consistency.

Standardized categorical values using UNIQUE() to check and clean each column.

Converted Discount column from decimal to percentage for easier understanding.
