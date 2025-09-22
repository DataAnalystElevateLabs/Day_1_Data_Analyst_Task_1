# Day_1_Data_Analyst_Task_1
First Task of Data Analyst Internship @ Elevate Labs

problem statement/Guidelines:
 1.Identify and handle missing values using .isnull() in Python or filters in Excel.
 
 2.Remove duplicate rows using .drop_duplicates() or Excel’s “Remove Duplicates”.
 
 3.Standardize text values like gender, country names, etc.
 
 4.Convert date formats to a consistent type (e.g., dd-mm-yyyy).
 
 5.Rename column headers to be clean and uniform (e.g., lowercase, no spaces).
 
 6.Check and fix data types (e.g., age should be int, date as datetime)

Steps followed in Excel:
1.Imported raw dataset Raw_Sales_Data from Kaggle CSV into Excel for cleaning.

2.Checked for nulls and blanks using Filter and COUNTBLANK() to identify missing data.

3.Changed data types for all columns to ensure correct type (number, text, date).

4.Standardized column names: capitalized first letters and applied highlighting for clarity.

5.Formatted Sales_Date using a helper column.

6.Used TEXT() to convert date format from mm/dd/yyyy → dd/mm/yyyy.

7.Copied helper column → Paste Special → Values to replace original dates.

8.Deleted the old Sales_Date and helper column to remove unnecessary references.

9.Deleted redundant column Sales_Rep_by_Region to remove unnecessary data.

10.Rounded numerical columns to two decimal places for consistency.

11.Standardized categorical values using UNIQUE() to check and clean each column.

12.Converted Discount column from decimal to percentage for easier understanding.

13.Got the cleaned Data Set.


Steps followed for the task in Python:

1.Imported necessary libraries: pandas and numpy.

2.Loaded the dataset into Google Colaboratory using pd.read_csv().

3.Explored the dataset structure using .info(), .columns, and .shape().

4.Identified missing values with .isnull().sum() and duplicate rows with .duplicated().sum().

5.Checked categorical columns for consistency using .unique().

6.Dropped the redundant column Region_and_Sales_Rep using .drop(columns=[column_name], axis=1, inplace=True).

7.Verified data types using .dtypes.

8.Converted Sales_Date from object to datetime type and reformatted from 'YYYY/mm/dd' to 'dd/mm/yyyy' using .astype() and .dt.strftime().

9.Set product_id as the DataFrame index using .set_index('product_id', inplace=True).

10.Resulted in a clean, standardized, and analysis-ready dataset.

